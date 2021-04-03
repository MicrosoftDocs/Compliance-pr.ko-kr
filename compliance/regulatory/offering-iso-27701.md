---
title: ISO/IEC 27701 개인 정보 관리 시스템(PIMS)
description: 글로벌 데이터 처리 공급 체인 내의 컨트롤러 및 프로세서 간의 개인 정보 보호 책임 및 규정 준수를 지원하기 위한 ISO/IEC 27701 표준입니다.
keywords: Microsoft 365, 규정 준수, 제안
localization_priority: Priority
ms.prod: microsoft-365-enterprise
ms.topic: article
f1.keywords:
- NOCSH
ms.author: robmazz
author: robmazz
manager: laurawi
audience: itpro
ms.collection:
- M365-security-compliance
- MS-Compliance
hideEdit: true
titleSuffix: Microsoft Compliance
ms.openlocfilehash: 45cfa42a82e6fc4d7c1e9c26e59a23a944c4fd9c
ms.sourcegitcommit: 024137a15ab23d26cac5ec14c36f3577fd8a0cc4
ms.translationtype: HT
ms.contentlocale: ko-KR
ms.lasthandoff: 04/01/2021
ms.locfileid: "51496640"
---
# <a name="isoiec-27701-privacy-information-management-system-pims"></a>ISO/IEC 27701 PIMS(개인 정보 관리 시스템)

## <a name="privacy-information-management-system-pims-overview"></a>개인 정보 관리 시스템(PIMS) 개요

유럽 연합의 GDPR(일반 데이터 보호 규정)은 전 세계적으로 개인 정보 보호 규정 및 규정 준수의 새로운 시대를 열었습니다. GDPR 후 다양하게 모델링된 더 많은 개인 정보 규정이 여러 관할권(시장/산업 또는 물리적 위치)에서 제정되었습니다. 따라서 조직은 늘어나는 개인 정보 규정 항목들에 대한 준수를 보장하는 정책과 절차를 구현해야 합니다. 또한 우리는 데이터 수집 및 처리가 현저하게 늘어나는 신속한 디지털 변화의 한 가운데에 몰려 있습니다. 데이터 볼륨의 동시 증가율과 해당 데이터와 관련된 규정 요구 사항에 따라 모든 유형의 조직의 규정 준수 문제가 더욱 복잡 해지고 있습니다.

새로운 국제 표준 [ISO/IEC 27701 개인 정보 관리 시스템(PIMS)](https://www.iso.org/standard/71670.html)(초안 기간 동안의 이전 명칭: ISO/IEC 27552)은 조직이 개인 정보 규정 요구 사항을 조정하는 데 도움이 됩니다. 표준은 GDPR을 포함하여 다양한 규정에 매핑될 수 있는 포괄적인 운영 제어 집합을 간략하게 보여 줍니다. 매핑한 후 PIMS 운영 제어는 개인 정보 보호 전문가에 의해 구현되며 내부 또는 제3자 감사자를 통해 감사를 하여 인증 및 종합적 규정 준수 증명이 이루어집니다.

## <a name="compliance-challenges"></a>규정 준수 문제

공급 업체가 PIMS를 인증하려면 조직 규모와 상관없이 공급자와 파트너가 책임 개인 정보 보호 방침을 설정하는 것이 효율적입니다. ISO/IEC 27701는 다음 세 가지 주요 규정 준수 문제를 해결합니다.

- **조율할 규정 요구 사항이 너무 많음**: 법용 운영 제어 집합을 사용하여 여러 규제 요구 사항을 조정하는 것이 일관되고 효율적인 구현를 가능하게 합니다.
- **규정을 통해 규정을 감사하는 데 너무 많은 비용이 듦**: 감사자(내부 및 제3자)는 하나의 감사 주기 내에서 범용 운영 제어 집합을 사용하여 규제 준수를 평가할 수 있습니다.
- **증명을 사용하지 않는 규정 준수 약속은 잠재 위험 요소가 있음**: 개인 정보 이동을 포함한 상업적 계약이 규정 준수에 대한 인증을 보증할 수 있습니다.

## <a name="too-many-regulatory-requirements-to-juggle"></a>조율할 규정 요구 사항이 너무 많음

ISO/IEC 27701에는 컨트롤러 및 프로세서에 대한 GDPR의 관련 요구 사항에 대해 매핑된 표준의 운영 제어가 포함된 부록이 포함되어 있습니다. 이 매핑은 ISO 프레임워크를 사용하여 개인 정보 규정을 운용할 수 있게 하는 방법을 보여 주는 예제일 뿐입니다. 다른 규정을 사용하여 추가 매핑도 사용 가능하게 되고 검증되면 표준의 운영 제어를 규제 검토에서 구현으로 직접 이전할 수 있습니다. 이 범용 프레임워크를 사용하면 조직이 ‘사이클을 혁신’하지 않고 관련 규제 요구 사항을 안정적으로 운용할 수 있게 할 수 있습니다. 개인 정보 보호 커뮤니티에서 다른 규정을 매핑하고 기존 매핑의 유효성을 검사할 수 있도록 보류 중인 오픈 소스 프로젝트가 진행되고 있습니다. 공지 사항을 계속 확인하세요.

## <a name="too-costly-to-audit-regulation-by-regulation"></a>규정을 통해 규정을 감사하는 데 너무 많은 비용이 듦

현재 풍경에서 서론 문장으로 돌아가 보겠습니다. 더 많은 개인 정보 규정이 다양한 관할권에서 제정되면서 규정 준수에 대한 증거를 제공하라는 압박도 증가합니다. 모든 규정이 자체 고유의 감사를 요구할 경우에는 별도의 규정 인증 비용이 지나치게 커질 수 있습니다. PIMS는 범용 운영 제어 집합을 간략하게 설명하면서 여러 규정 요구 사항에 대해 감사하고 잠재적으로 인증하는 데 사용할 수 있는 범용 규정 준수 프레임워크를 간략하게 설명합니다.

공식 GDPR 인증에서 유럽 규제 기관의 승인 결정을 보류할 것을 요구함을 인식하는 것이 중요합니다. PIMS와 GDPR 사이의 정렬은 명확하게 나타나지만, PIMS 인증은 규정 결정이 완료될 때까지 공식 GDPR 인증이 아니라 GDPR 규정 준수의 증거로 사용되어야 합니다.

## <a name="promises-of-compliance-without-proof-is-potentially-risky"></a>증명을 사용하지 않는 규정 준수 약속은 잠재 위험 요소가 있음

최신 조직은 파트너 조직이나 공동 컨트롤러, 프로세서(예: 클라우드 공급자) 및 하위 프로세서(예: 그와 동일한 프로세서를 지원하는 공급업체)를 비롯한 비즈니스 파트너의 심도 있는 네트워크를 통한 복잡한 데이터 전송에 참여합니다. 이 네트워크에서 규정을 준수하지 않으면 공급 체인에서 연속적인 규정 준수 문제가 발생할 수 있습니다. 이는 이러한 조직 사이의 계약 약관이 제공하는 보장을 넘어 규정 준수 확인이 가치가 있는 위치입니다. 글로벌 경제성은 대부분의 조직들이 전 세계에 걸쳐 퍼져 있음을 의미하기 때문에 ISO에서 국제 표준을 사용하여 네트워크에서 규정 준수를 관리하는 것이 좋습니다.

규정 준수에 대한 이러한 의존도 때문에 표준에 대한 인증의 중요성이 높아집니다. 모든 회사와 조직에서 그러한 인증을 받아야 하는 것은 아니며, 특히 중요한 볼륨 또는 많은 볼륨의 데이터 처리가 관련된 경우에는 수행 파트너 및 공급업체로부터 대부분 이익을 얻게 됩니다.

## <a name="building-blocks-of-the-standard"></a>표준의 구성 요소

PIMS는 정보 보안 관리 [ISO/IEC 27001](offering-iso-27001.md)에 대해 가장 널리 채택되는 국제 표준 중 하나를 기반으로 구축되었습니다. 조직이 이미 ISO/IEC 27001에 익숙한 경우 PIMS의 새 개인 정보 제어를 통합하는 것이 논리적이고 더 효율적입니다. 즉, 이 둘에 대한 구현과 감사는 비용이 덜 들고 실현하기 더 쉽습니다.

ISO/IEC 27001 및 PIMS의 주요 사항:

- ISO/IEC 27001는 세계에서 가장 많이 사용되는 ISO 표준 중 하나로, 많은 회사가 이미 그에 대한 인증을 획득했습니다.
- PIMS에는 개인 정보 보호 및 보안 사이의 차이를 파악하는 데 도움이 되는 새로운 컨트롤러와 프로세서별 제어가 포함되어 있습니다. 이는 조직의 두 가지 별도의 기능일 수 있는 요소 간의 통합 지점을 제공합니다.
- 개인 정보는 보안에 따라 다릅니다. 마찬가지로 PIMS는 보안 관리에 대한 ISO/IEC 27001에 따라 다릅니다. PIMS에 대한 인증은 ISO/IEC 27001 인증의 확장으로서 획득해야 하며 독립적으로 받을 수 없습니다.

## <a name="what-should-your-organization-do-with-pims"></a>조직은 PIMS로 무엇을 해야 하나요?

조직의 규모 및 컨트롤러인지 프로세서인지에 상관없이 조직은 조직 자체를 위해 또는 비즈니스 요구 사항을 기반으로 공급업체 또는 공급자의 요청을 받아 인증을 진행하는 것을 고려해야 합니다. 이는 중요한 볼륨 또는 많은 볼륨의 개인 데이터를 처리하는 프로세서, 하위 프로세서 및 공동 컨트롤러에 특히 적용됩니다. 어떤 경우든 조직은 자신의 제품 및 서비스에 대한 인증이 적합한지 확인하기 위해 비즈니스 요구 사항을 평가해야 합니다.

## <a name="microsoft-in-scope-cloud-services"></a>Microsoft 범위 내 클라우드 서비스

- Azure, Azure Government, Azure Germany
- Azure DevOps Services
- Microsoft Cloud App Security
- Dynamics 365, Dynamics 365 Government, Dynamics 365 Germany
- Microsoft Graph
- Microsoft Healthcare Bot
- Intune
- [Microsoft Managed Desktop](/microsoft-365/managed-desktop/intro/compliance)
- Power Automate(과거 Microsoft Flow)
- PowerApps
- Power BI
- Power BI Embedded
- Power Virtual Agents
- Microsoft Stream
- Microsoft 위협 전문가
- 엔드포인트용 Microsoft Defender

## <a name="audits-reports-and-certificates"></a>감사, 보고서 및 인증서

- [Azure, Dynamics 365 및 온라인 서비스: ISO27701 인증](https://aka.ms/azureiso27701cert)
- [Azure, Dynamics 365 및 온라인 서비스: ISO27701 평가 보고서](https://aka.ms/azureiso27701report)

## <a name="use-microsoft-compliance-manager-to-assess-your-risk"></a>Microsoft 준수 관리자를 사용하여 위험 평가

[Microsoft 준수 관리자](/microsoft-365/compliance/compliance-manager)는 조직의 준수 입장을 이해하고 위험을 줄이기 위한 조치를 취하도록 돕는 [Microsoft 365 규정 준수 센터](/microsoft-365/compliance/microsoft-365-compliance-center)의 기능입니다. 준수 관리자는 이 규제에 대한 평가를 빌드하기 위한 프리미엄 서식 파일을 제공합니다. 준수 관리자의 **평가 서식 파일** 페이지에서 서식 파일을 찾습니다. [준수 관리자의 평가 빌드](/microsoft-365/compliance/compliance-manager-assessments) 방법에 대해 알아봅니다.

## <a name="resources"></a>리소스

- [구매에 대한 ISO/IEC 27701(PIMS)](https://www.iso.org/standard/71670.html)
- [PIMS에 대한 BSI 백서 및 콘텐츠](https://www.bsigroup.com/globalassets/localfiles/en-gb/data-protection/bsi_privacy_matters_white_paper-web.pdf)
- [PIMS 소개 비디오](https://www.microsoft.com/videoplayer/embed/RE3uaQJ)
- [Microsoft 보안 센터에 대한 규정 준수](https://www.microsoft.com/trust-center/compliance/compliance-overview)
