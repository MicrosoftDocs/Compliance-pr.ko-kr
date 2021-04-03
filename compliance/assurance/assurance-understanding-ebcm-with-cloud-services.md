---
title: 클라우드 서비스를 사용하여 엔터프라이즈 비즈니스 연속성 관리을 이해하기
description: 클라우드 서비스가 IT 제공의 일부일 때 비즈니스 연속성을 계획하고 구현하는 방법에 대해 알아보세요.
author: robmazz
ms.author: robmazz
manager: laurawi
ms.reviewer: sosstah
audience: ITPro
ms.topic: article
f1.keywords:
- NOCSH
ms.service: o365-solutions
localization_priority: Normal
ms.collection:
- M365-subscription-management
- Strat_O365_Enterprise
- remotework
titleSuffix: Microsoft Service Assurance
hideEdit: true
ms.openlocfilehash: d0d19941bb64462423b8488d38fb151eaa1faeb8
ms.sourcegitcommit: 024137a15ab23d26cac5ec14c36f3577fd8a0cc4
ms.translationtype: MT
ms.contentlocale: ko-KR
ms.lasthandoff: 04/01/2021
ms.locfileid: "51497363"
---
# <a name="enterprise-business-continuity-management-ebcm-with-cloud-services"></a><span data-ttu-id="4d369-103">클라우드 서비스를 사용한 엔터프라이즈 비즈니스 연속성 관리(EBCM)</span><span class="sxs-lookup"><span data-stu-id="4d369-103">Enterprise business continuity management (EBCM) with cloud services</span></span>

<span data-ttu-id="4d369-104">조직의 디지털 변환의 일환으로 재해 복구 및 비즈니스 연속성 계획을 재검토하고 업데이트하여 Microsoft 365 클라우드 서비스에 종속 되는 비즈니스 프로세스를 설명해야 합니다.</span><span class="sxs-lookup"><span data-stu-id="4d369-104">As part of your organizations digital transformation, you need to revisit and update your disaster recovery and business continuity plans to account for the business process that depend on Microsoft 365 Cloud services.</span></span> <span data-ttu-id="4d369-105">Exchange Online, SharePoint Online, 비즈니스용 OneDrive와 같은 Microsoft 365 클라우드 서비스가 더욱 탄력적으로 설계되고 운영됩니다.</span><span class="sxs-lookup"><span data-stu-id="4d369-105">Microsoft 365 Cloud services, like Exchange Online, SharePoint Online and OneDrive for Business are designed and operated to be highly resilient.</span></span>

> [!NOTE]
> <span data-ttu-id="4d369-106">[엔터프라이즈 비즈니스 연속성 관리 프로그램 백서](https://go.microsoft.com/fwlink/?linkid=2121521)에서 Microsoft의 자체 EBCM 플랜에 대한 자세한 내용을 확인할 수 있습니다.</span><span class="sxs-lookup"><span data-stu-id="4d369-106">You can learn more about Microsoft's own EBCM plan in the [Enterprise Business Continuity Management Program whitepaper](https://go.microsoft.com/fwlink/?linkid=2121521).</span></span> <span data-ttu-id="4d369-107">로그인해야 합니다.</span><span class="sxs-lookup"><span data-stu-id="4d369-107">Login is required.</span></span>

<span data-ttu-id="4d369-108">이 탄력성이 있더라도 서비스 사고가 발생합니다.</span><span class="sxs-lookup"><span data-stu-id="4d369-108">Even with this resilience, service incidents do occur.</span></span> <span data-ttu-id="4d369-109">그러한 경우에는 조직은 이에 준비를 하고 비즈니스 연속성 전략을 잘 정의해야 합니다.</span><span class="sxs-lookup"><span data-stu-id="4d369-109">When they do, your organization should be prepared and have a well-defined business continuity strategy.</span></span>

<span data-ttu-id="4d369-110">아직 계획을 업데이트 하지 않은 경우에는 이 주제 시리즈는 서비스가 알려진 상태로 장애를 발생시키도록 전략을 계획하는데 도움을 줍니다.</span><span class="sxs-lookup"><span data-stu-id="4d369-110">If you haven't updated your plans yet this series of topics helps you to plan your strategy so your services can fail to a known state.</span></span> <span data-ttu-id="4d369-111">이 주제는 연속성 준비를 개선하기 위한 주요 고려사항을 강조합니다.</span><span class="sxs-lookup"><span data-stu-id="4d369-111">These topics highlight key considerations for improving your continuity readiness.</span></span>

## <a name="list-of-topics-with-links"></a><span data-ttu-id="4d369-112">링크가 포함된 주제 목록</span><span class="sxs-lookup"><span data-stu-id="4d369-112">List of topics with links</span></span>

- [<span data-ttu-id="4d369-113">고객 및 클라우드 파트너의 책임</span><span class="sxs-lookup"><span data-stu-id="4d369-113">Customer and cloud partner responsibilities</span></span>](assurance-customer-and-cloud-partner-ebcm-responsibilities.md)
- [<span data-ttu-id="4d369-114">Microsoft 365 서비스 탄력성</span><span class="sxs-lookup"><span data-stu-id="4d369-114">Microsoft 365 service resiliency</span></span>](assurance-m365-service-resiliency.md)
- [<span data-ttu-id="4d369-115">연속성 계획 개발</span><span class="sxs-lookup"><span data-stu-id="4d369-115">Developing your continuity plan</span></span>](assurance-developing-your-ebcm-plan.md)
- [<span data-ttu-id="4d369-116">Microsoft 365 서비스 사고 완화 시나리오</span><span class="sxs-lookup"><span data-stu-id="4d369-116">Microsoft 365 service incident mitigation scenarios</span></span>](assurance-microsoft-365-mitigations.md)
- [<span data-ttu-id="4d369-117">비즈니스 연속성을 위한Microsoft 365 계획 교육 및 예행 연습</span><span class="sxs-lookup"><span data-stu-id="4d369-117">Microsoft 365 for business continuity plan training and rehearsal</span></span>](assurance-ebcm-plan-rehearsal-and-user-training.md)

## <a name="see-also"></a><span data-ttu-id="4d369-118">참고 항목</span><span class="sxs-lookup"><span data-stu-id="4d369-118">See also</span></span>

- [<span data-ttu-id="4d369-119">엔터프라이즈 비즈니스 연속성 법적 고지 사항</span><span class="sxs-lookup"><span data-stu-id="4d369-119">Enterprise business continuity legal disclaimer</span></span>](assurance-ebcm-legal-disclaimer.md)
