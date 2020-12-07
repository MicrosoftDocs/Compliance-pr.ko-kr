---
title: PCI(Payment Card Industry) DSS(Data Security Standard)
description: Azure, SharePoint Online 및 비즈니스용 OneDrive는 Payment Card Industry Data Security 표준 수준 1 버전 3.2를 준수합니다.
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
ms.openlocfilehash: 3121119635d6dad9567f4497ecdaeb1111aabb7a
ms.sourcegitcommit: 626b0076d133e588cd28598c149a7f272fc18bae
ms.translationtype: HT
ms.contentlocale: ko-KR
ms.lasthandoff: 11/30/2020
ms.locfileid: "49509393"
---
# <a name="payment-card-industry-pci-data-security-standard-dss"></a>PCI(Payment Card Industry) DSS(Data Security Standard)

## <a name="pci-dss-overview"></a>PCI DSS 개요

PCI(Payment Card Industry) DSS(Data Security Standard)는 신용 카드 데이터에 대한 통제를 강화하여 사기를 방지하도록 고안된 글로벌 정보 보안 표준입니다. 모든 규모의 조직은 Visa, MasterCard, American Express, Discover, JCB(Japan Credit Bureau) 등 5개 주요 신용 카드 브랜드의 결제 카드를 수락하는 경우 PCI DSS 표준을 따라야 합니다. 지불 및 카드 소유자 데이터를 저장, 처리 또는 전송하는 모든 조직은 PCI DSS를 준수해야 합니다.

## <a name="microsoft-and-pci-dss"></a>Microsoft와 PCI DSS

Microsoft는 승인된 QSA(Qualified Security Assessor)를 사용하여 연간 PCI DSS 평가를 완료했습니다. 감사자는 인프라, 개발, 운영, 관리, 지원 및 범위 내 서비스 검증을 포함하여 Microsoft Azure, 비즈니스용 Microsoft OneDrive 및 Microsoft SharePoint Online 환경을 검토했습니다. PCI DSS는 거래량을 기준으로 네 가지 규정 준수 수준을 지정합니다. Azure, 비즈니스용 OneDrive, SharePoint Online은 PCI DSS 버전 3.2의 서비스 공급자 수준 1(최고 거래량이 연간 6백만 건 이상)의 규정 준수 인증을 획득했습니다.

평가는 AoC(Attestation on Compliance)로 제공되며 이는 고객이 열람 가능하고 QSA에서 발행한 Report on Compliance (RoC)에서 볼 수 있습니다. 규정 준수에 대한 유효 기간은 감사를 통과하여 평가자로부터 AoC를 받은 시점부터 AoC에 서명한 날짜가 포함된 연도의 말일까지입니다. 

카드 데이터 전용 네트워크(CDE) 또는 카드 처리 서비스를 개발하려는 고객은 많은 기본적인 부분에서 이러한 검증을 사용할 수 있습니다. 이를 통해 자체적으로 PCI DSS 인증을 얻기 위한 관련된 작업과 비용을 줄일 수 있습니다.

Azure, 비즈니스용 OneDrive, SharePoint Online의 PCI DSS 규정 준수 상태가 고객이 이러한 플랫폼에서 빌드하거나 호스팅하는 서비스에 대한 PCI DSS 인증으로 자동으로 전환되는 것은 아닙니다. 고객은 일부 PCI DSS 요구 사항을 준수하는지 확인해야 할 책임이 있습니다.

## <a name="microsoft-in-scope-cloud-services"></a>Microsoft 범위 내 클라우드 서비스

- [Azure 및 Azure Government](https://aka.ms/AzureCompliance)
- Microsoft Cloud App Security
- 독립 실행형 서비스 혹은 Office 365 혹은 Dynamics 365에 브랜딩된 플랜 또는 제품군에 포함된 형태로서의 Flow 클라우드 서비스
- Microsoft Graph
- Intune
- [Microsoft Defender Advanced Threat Protection](https://docs.microsoft.com/windows/security/threat-protection/microsoft-defender-atp/microsoft-defender-advanced-threat-protection)
- 독립 실행형 서비스 혹은 Office 365 혹은 Dynamics 365에 브랜딩된 플랜 또는 제품군에 포함된 형태로서의 PowerApps 클라우드 서비스
- 독립 실행형 서비스 혹은 Office 365에 브랜딩된 플랜 또는 제품군에 포함된 형태로서의 Power BI 클라우드 서비스
- 비즈니스용 OneDrive 및 SharePoint Online(미국에만 해당)

## <a name="audit-reports-and-certificates"></a>감사, 보고서 및 인증서

- [Azure PCI DSS 준수 증명(AoC)](https://aka.ms/azure-pci)
- [비즈니스용 OneDrive 및 SharePoint Online PCI DSS 준수 증명(AoC)](https://aka.ms/spo-pci)

## <a name="get-your-pci-dss-solution-running-on-azure"></a>Azure에서 실행되는 PCI DSS 솔루션 받기

Azure 보안 및 준수 PCI DSS 청사진을 사용하여 클라우드에서 PCI DSS 솔루션을 더 빠르게 빌드하고 배포합니다. 참조 아키텍처, 배포 지침, 제어 구현 매핑, 자동화된 스크립트 등을 가져옵니다. [Azure PCI DSS 청사진 사용 시작하기](https://aka.ms/pciblueprint)

## <a name="frequently-asked-questions"></a>자주하는 질문

**AoC(Attestation on Compliance) 표지 페이지에 ‘2018년 6월’이 표시된 이유는 무엇인가요?**

표지 페이지의 날짜 2018년 6월은 AoC 서식 파일이 게시된 날짜입니다. 평가 날짜는 2조를 참조하세요.

**Azure 규정 준수 증명서가 여러 개인 이유는 무엇인가요?**

Azure AoC 패키지에는 Azure Public, Germany, 클라우드에 해당하는 Aoc가 있습니다. 고객은 고객의 Azure 환경에 해당하는 AoC를 사용해야 합니다.  

**PA DSS와 PCI DSS는 서로 어떤 관계인가요?**

PA DSS(Payment Application Data Security Standard)는 PCI DSS를 준수하고, Visa의 지불 응용 프로그램 모범 사례를 대체하고, 다른 주요 카드 발급자의 규정 준수(compliance) 요건을 통합하는 요건 모음입니다. 소프트웨어 공급업체에서는 PA DSS에 따라 카드 인증 또는 결제 프로세스의 일환으로 카드 소유자 지불 데이터를 저장, 처리 또는 전송하는 타사 응용 프로그램을 개발할 수 있습니다. 소매업체에서는 PCI DSS 규정을 효율적으로 준수하려면 PA DSS 인증 응용 프로그램을 사용해야 합니다. PA DSS는 Azure에 적용되지 않습니다.

**전표 매입업체란 무엇인가요? Azure는 매입업체를 이용하나요?**

전표 매입업체란 결제 카드 거래를 처리하는 은행 또는 기타 기관입니다. Azure는 카드 결제 처리 서비스를 제공하지 않으므로 전표 매입업체를 이용하지 않습니다.

**PCI DSS는 어떤 회사 및 판매자에게 적용되나요?**

거래의 규모나 수에 상관없이 카드 소유자 데이터를 수락, 전송 또는 저장하는 모든 회사에 적용됩니다. 즉, 고객이 신용 카드 또는 직불 카드를 사용하여 회사에 지불하는 경우 PCI DSS 요구 사항이 적용됩니다. 기업은 12개월 동안의 총 거래량을 기준으로 네 가지 수준 중 하나로 검증됩니다. 연간 처리하는 거래 건수가 600만 건 초과인 기업은 수준 1, 100만 ~ 600만 건인 기업은 수준 2, 2만 ~ 1백만 건인 기업은 수준 3, 2만 건 미만인 기업은 수준 4에 해당합니다.

**Azure에 배포된 솔루션에 대한 우리 회사의 PCI DSS 규정 준수 활동은 어느 것부터 시작해야 하나요?**

특정 규정 준수(compliance) 요건에 대한 자세한 내용은 PCI 보안 표준 심의회에서 제공하는 정보를 참조하십시오. 위원회는 결제 카드 처리에 포함되는 판매자 및 기타 당사자를 대상으로 하는 [PCI DSS 빠른 참조 설명서(영문)](https://www.pcisecuritystandards.org/documents/PCISSC%20QRG%20August%202014%20-print.pdf)를 발행합니다. 이 설명서는 PCI DSS를 통해 결제 카드 거래 환경을 보호하고 PCI DSS를 적용하는 방법을 설명합니다.

규정 준수는 Azure에서 호스팅되지 않는 시스템 및 프로세스 평가를 비롯한 많은 요소를 포함합니다. 개별 요구 사항은 사용되는 Azure 서비스와 Azure가 솔루션에서 사용되는 방법에 따라 다릅니다.

**비즈니스용 OneDrive 및 SharePoint Online가 미국 이외의 지역에서 PCI DSS를 준수할 계획이 있나요?**

현재 비즈니스용 OneDrive 및 SharePoint Online은 미국(US)에서만 PCI-DSS를 준수합니다. Microsoft는 미국 이외의 지역에 대한 요구 사항과 타임라인을 평가하고 다른 지역이 로드맵에 추가되면 업데이트를 제공할 것입니다.

**비즈니스용 OneDrive 및 SharePoint Online 범위 내에 어떤 것이 있나요?**

현재 비즈니스용 OneDrive 및 SharePoint Online에 업로드된 파일과 문서만 PCI DSS를 준수합니다.

## <a name="use-microsoft-compliance-manager-to-assess-your-risk"></a>Microsoft 준수 관리자를 사용하여 위험을 평가해 보세요.

[Microsoft 준수 관리자](https://docs.microsoft.com/microsoft-365/compliance/compliance-manager)는 조직의 준수 입장을 이해하고 위험을 줄이기 위한 조치를 취하도록 돕는 [Microsoft 365 규정 준수 센터](https://docs.microsoft.com/microsoft-365/compliance/microsoft-365-compliance-center)의 기능입니다. 준수 관리자는 이 규제에 대한 평가를 빌드하기 위한 프리미엄 서식 파일을 제공합니다. 준수 관리자의 **평가 서식 파일** 페이지에서 서식 파일을 찾습니다. [준수 관리자의 평가 빌드](https://docs.microsoft.com/microsoft-365/compliance/compliance-manager-assessments) 방법에 대해 알아봅니다.

## <a name="resources"></a>리소스

- [PCI 보안 표준 심의회(영문)](https://www.pcisecuritystandards.org/)
- [PCI 데이터 보안 표준(영문)](https://www.pcisecuritystandards.org/documents/PCI_DSS_v3-1.pdf)
- [Azure PCI DSS 3.2.1 청사진](https://docs.microsoft.com/azure/governance/blueprints/samples/pci-dss-3.2.1/)
- [PCI DSS 빠른 참조 설명서(영문)](https://www.pcisecuritystandards.org/documents/PCISSC%20QRG%20August%202014%20-print.pdf)
- [Microsoft 보안 센터에 대한 규정 준수](https://www.microsoft.com/trust-center/compliance/compliance-overview)
