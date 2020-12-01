---
title: GDPR 및 CCPA에 대한 Windows 엔터프라이즈 데이터 주체 요청용 데이터 프로세서 서비스
description: Microsoft 제품, 서비스 및 관리 도구를 사용하여 개인 데이터를 찾아서 작업을 하여 DSR에 응답하는 방법을 알아봅니다.
keywords: Microsoft 365, Microsoft 365 Education, Microsoft 365 설명서, GDPR
localization_priority: Priority
ROBOTS: NOINDEX, NOFOLLOW
ms.prod: microsoft-365-enterprise
ms.topic: article
f1.keywords:
- NOCSH
ms.author: daniha
author: DaniHalfin
manager: dansimp
audience: itpro
ms.collection:
- GDPR
- M365-security-compliance
- MS-Compliance
ms.openlocfilehash: 196796cbbfe7755f2639ed5acc163cce130d98d8
ms.sourcegitcommit: 626b0076d133e588cd28598c149a7f272fc18bae
ms.translationtype: HT
ms.contentlocale: ko-KR
ms.lasthandoff: 11/30/2020
ms.locfileid: "49508540"
---
# <a name="data-processor-service-for-windows-enterprise-data-subject-requests-for-the-gdpr-and-ccpa"></a>GDPR 및 CCPA에 대한 Windows 엔터프라이즈 데이터 주체 요청용 데이터 프로세서 서비스 

>[!NOTE]
>This topic is intended for participants in the data processor service for Windows Enterprise preview program and requires acceptance of specific terms of use. To learn more about the program and agree to the terms of use, see [https://aka.ms/WindowsEnterprisePublicPreview](https://aka.ms/WindowsEnterprisePublicPreview).

## <a name="introduction-to-data-subject-requests-dsrs"></a>DSR(데이터 주체 요청) 소개 

EU GDPR(일반 데이터 보호 규정)은 사용자(규정에 _데이터 주체_ 로 알려짐)에게 고용주 또는 다른 유형의 대리점 및 조직(_데이터 컨트롤러_ 또는 단순히 _컨트롤러_ 로 지칭)이 수집한 개인 데이터를 관리할 수 있는 권한을 부여합니다. 개인 데이터는 GDPR에서는 보다 광범위하게 식별되었거나 식별 가능한 자연인과 관련된 모든 데이터로 정의됩니다. GDPR은 데이터 주체에게 개인 데이터에 대한 특정 권한을 부여합니다. 이러한 권한에는 개인 데이터 복사본 획득, 수정 요청, 처리 제한, 삭제 또는 다른 컨트롤러에게 이동될 수 있도록 전자 형식으로 수신하는 권한이 포함됩니다. 데이터 주체가 컨트롤러에게 개인 데이터에 대해 조치를 취할 것을 요구하는 공식적인 요청을 _데이터 주체 요청_ 또는 DSR이라고 합니다. 

마찬가지로, CCPA(캘리포니아 소비자 개인 정보 보호법, CCPA)는 개인 정보를 삭제, 액세스 및 수신(이동 가능)할 수 있는 권한과 같은 GDPR의 데이터 주체 권한과 유사한 권한을 포함하여 캘리포니아 소비자에게 개인 정보 보호 권한 및 의무를 제공합니다. 또한 CCPA는 특정 공개, 행사 권한 선택 시 차별에 대한 보호, "판매"로 분류된 특정 데이터 전송에 대한 "옵션/옵션" 요구사항을 제공합니다. 판매는 가치 있는 고려를 위해 데이터 공유를 포함하도록 광범위하게 정의됩니다. CCPA에 대한 자세한 내용은 [캘리포니아 소비자 개인 정보 보호법](https://docs.microsoft.com/microsoft-365/compliance/offering-ccpa) 및 [캘리포니아 소비자 개인 정보 보호법 FAQ](https://docs.microsoft.com/microsoft-365/compliance/ccpa-faq)를 참조하시기 바랍니다.

이 가이드에서는 Microsoft 제품, 서비스 및 관리 도구를 사용하여 컨트롤러 고객이 DSR에 응답하기 위해 개인 데이터를 찾고 조치를 취하는 데 도움을 주는 방식을 설명합니다. 특히, Microsoft 클라우드에 있는 개인 데이터를 찾고, 액세스하고, 조치를 취하는 방법도 포함되어 있습니다. 이 가이드에 설명된 프로세스에 대한 간략한 개요는 다음과 같습니다. 

1. **액세스**—Microsoft 클라우드에 있는 개인 데이터를 검색하고, 요청될 경우 데이터 주체가 사용할 수 있는 복사본을 만듭니다. 
2. **삭제** Microsoft 클라우드에 있는 개인 데이터를 영구적으로 제거합니다. 
3. **내보내기**—데이터 제목에 개인 데이터의 전자 사본(컴퓨터가 읽을 수 있는 형식)을 제공합니다. CCPA에 따른 개인정보는 신원 또는 신원확인과 관련된 모든 정보입니다.

CCPA에 따른 개인정보는 신원 또는 신원확인과 관련된 모든 정보입니다. 개인의 사적 역할, 공적 역할 또는 업무 역할의 구분이 없습니다. 정의된 용어 "개인 정보"의 의미는 GDPR의 "개인 데이터"와 대략 일치합니다. 그러나 CCPA에는 가족 및 가계 데이터도 포함됩니다. CCPA에 대한 자세한 내용은 [캘리포니아 소비자 개인 정보 보호법](https://docs.microsoft.com/microsoft-365/compliance/offering-ccpa) 및 [캘리포니아 소비자 개인 정보 보호법 FAQ](https://docs.microsoft.com/microsoft-365/compliance/ccpa-faq)를 참조하시기 바랍니다.

이 가이드의 각 섹션에서는 데이터 컨트롤러가 Microsoft 클라우드의 개인 데이터에 대한 DSR에 응답하기 위해 수행할 수 있는 기술적 절차를 간략하게 설명합니다. 

## <a name="terminology"></a>용어

다음 목록은 이 가이드와 관련된 용어의 정의를 제공합니다. 

* _통제자:_ 단독으로 또는 다른 대상과 함께 개인 데이터 처리의 목적 및 방법을 결정하는 자연인이나 법인, 공공 기관, 대리점 또는 기타 단체입니다. 이러한 처리의 목적 및 방법을 연합국 법률 또는 회원국 법률에 따라 결정하는 경우, 통제자 또는 구체적인 지명 기준을 연합국 법률 또는 회원국 법률에서 제공할 수 있습니다. 

* _개인 데이터 및 데이터 주체_ 식별되었거나 식별 가능한 자연인(‘데이터 주체’)과 관련된 모든 정보입니다. 식별 가능한 자연인은 직간접적으로, 특히 이름, 식별 번호, 위치 데이터, 온라인 식별자 또는 해당 자연인의 신체적, 생리적, 유전적, 정신적, 경제적, 문화적 또는 사회적 ID와 같은 식별자를 참조하여 식별될 수 있는 사람입니다. 

* _데이터 프로세서_ 데이터 컨트롤러를 대신하여 개인 정보를 처리하는 자연인 또는 법인, 공공 당국, 기관 또는 기타 주체입니다. 

* _고객 데이터_—모든 텍스트, 사운드, 비디오 또는 이미지 파일 및 소프트웨어를 포함한 모든 데이터와 엔터프라이즈 서비스를 사용하여 고객이 또는 대신하여 Microsoft에 제공합니다. 

* _Windows 진단 데이터_ - 장치와 Windows 및 관련 소프트웨어의 작동 방식에 대한 Windows 장치의 핵심적인 기술 데이터입니다. Windows를 최신 상태로 유지하고, 안전하고, 안정적이며, 성능을 향상시키는 데 사용되며, Windows사용의 집계 분석을 통해 Windows를 개선합니다. Windows 진단 데이터의 몇 가지 예로는 사용 중인 하드웨어 유형, 각각의 용도와 함께 설치된 응용 프로그램 및 장치 드라이버의 안정성 정보가 있습니다. 일부 Windows 구성 요소 및 앱은 Microsoft 서비스에 직접 연결되지만 교환하는 데이터는 Windows 진단 데이터가 아닙니다. 예를 들어 로컬 날씨 또는 뉴스를 위해 사용자 위치를 교환하는 것은 Windows 진단 데이터의 예가 아닙니다. 

## <a name="how-to-use-this-guide"></a>이 가이드를 사용하는 방법 

Windows 엔터프라이즈 등록 장치에 데이터 프로세서 서비스를 사용하면 Windows에서 서비스를 제공하기 위해 Windows 진단 데이터라고 하는 일부 정보를 생성합니다.

## <a name="windows-diagnostic-data"></a>Windows 진단 데이터 

Microsoft는 사용자의 Windows 엔터프라이즈용 데이터 프로세서 서비스 사용과 관련된 Windows 진단 데이터에 액세스, 삭제 및 내보낼 수 있는 기능을 제공합니다.

>[!IMPORTANT]
>Windows 진단 데이터를 수정하는 기능은 지원되지 않습니다. Windows 진단 데이터는 Windows 내에서 수행되는 사실상의 작업으로, 이러한 데이터를 수정하면 작업 기록의 기록이 손상되어 보안 위험이 증가하고 신뢰성이 저하됩니다. 이 문서에서 다루는 모든 데이터는 Windows 진단 데이터로 간주됩니다. 

## <a name="executing-dsrs-against-windows-diagnostic-data"></a>Windows 진단 데이터에 대해 DSR을 실행하고 있습니다. 

Microsoft는 Azure Portal을 통해 그리고 또한 기존 API(응용 프로그래밍 인터페이스)를 통해 직접 특정 Windows 진단 데이터에 액세스, 삭제 및 내보낼 수 있는 기능을 제공합니다.

### <a name="step-1-access"></a>1단계: 액세스 

테넌트 관리자는 조직 내에서 특정 사용자의 Windows Enterprise 등록 장치용 데이터 프로세서 서비스 사용과 관련된 Windows 진단 데이터에 액세스할 수 있는 유일한 사용자입니다. 액세스 요청에 대해 검색된 데이터는 내보내기를 통해 시스템에서 읽을 수 있는 형식으로 제공되며, 사용자가 데이터와 연결된 장치 및 서비스를 알 수 있는 파일로 제공됩니다. 앞에서 설명한 대로 검색된 데이터에는 Windows 장치의 보안이나 안정성을 해칠 수 있는 데이터가 포함되지 않습니다. 

Microsoft는 기업 고객의 테넌트 관리자에게 DSR 액세스 요청을 관리할 수 있는 기능을 제공하는 포털 환경을 제공합니다. [Azure DSR, Part 2, Step 3: Export](https://docs.microsoft.com/microsoft-365/compliance/gdpr-dsr-azure#step-3-export)에서는 내보내기를 통해 Azure 포털을 통해 DSR 액세스 요청을 실행하는 방법을 설명합니다.

### <a name="step-2-delete"></a>2단계: 삭제 

Microsoft는 특정 사용자의 Azure Active Directory 개체를 기반으로 사용자 기반 DSR 삭제 요청을 실행하는 방법을 제공합니다.

사용자 기반 삭제 요청의 경우 Microsoft는 기업 고객의 테넌트 관리자에게 DSR 삭제 요청을 관리할 수 있는 기능을 제공하는 포털 환경을 제공합니다. [Azure DSR, 제1부, 5단계: 삭제](https://docs.microsoft.com/microsoft-365/compliance/gdpr-dsr-azure#step-5-delete)는 Azure 포털을 통해 DSR 삭제 요청을 실행하는 방법을 설명합니다. 

Microsoft는 사용자를 삭제할 수 있는 기능을 제공하며, 이 기능을 사용하면 기존 API(응용 프로그램 프로그래밍 인터페이스)를 통해 고객 데이터를 직접 삭제할 수 있습니다. 자세한 내용은 [API 참조 설명서](https://docs.microsoft.com/graph/api/directory-deleteditems-delete)에 설명되어 있습니다. 

>[!IMPORTANT]  
>수집된 데이터를 삭제해도 추가 수집이 중지되지 않습니다. 데이터 수집을 해제하려면 [ 관련 서비스의 참조 문서](https://docs.microsoft.com/windows/privacy/configure-windows-diagnostic-data-in-your-organization#enterprise-management)에 설명된 절차를 따릅니다.
 
 또한 사용자 기반 삭제 요청의 경우 사용자 계정 자체를 삭제해야 합니다. 

### <a name="step-3-export"></a>3단계: 내보내기 

테넌트 관리자는 조직 내에서 특정 사용자의 Windows Enterprise 등록 장치용 데이터 프로세서 서비스 사용과 관련된 Windows 진단 데이터에 액세스할 수 있는 유일한 사용자입니다. 내보내기 요청에 대해 검색된 데이터는 시스템에서 읽을 수 있는 형식으로 제공되며 사용자가 해당 데이터와 연결된 장치 및 서비스를 알 수 있는 파일로 제공됩니다. 앞에서 설명한 대로 검색된 데이터에는 Windows 장치의 보안이나 안정성을 해칠 수 있는 데이터가 포함되지 않습니다. [Azure DSR, 제2부, 3단계: 내보내기](https://docs.microsoft.com/microsoft-365/compliance/gdpr-dsr-azure#step-3-export)에는 Azure 포털을 통해 DSR 내보내기 요청을 실행하는 방법이 설명되어 있습니다. 

Microsoft는 기존 API(응용 프로그램 프로그래밍 인터페이스)를 통해 고객 데이터를 직접 내보낼 수 있는 기능을 제공합니다. 자세한 내용은 [API 참조 설명서](https://docs.microsoft.com/graph/api/user-exportpersonaldata)에 설명되어 있습니다.

## <a name="notify-about-exporting-or-deleting-issues"></a>내보내기 또는 삭제 중 발생하는 문제에 대한 알림 

Azure Portal에서 데이터를 내보내거나 삭제하는 동안 문제가 발생하면 Azure Portal **도움말 + 지원** 블레이드로 이동하여 **등록 관리 > 기타 보안 및 준수 요청 > 개인 정보 보호 블레이드 및 GDPR 요청** 에서 새 티켓을 제출합니다. 
