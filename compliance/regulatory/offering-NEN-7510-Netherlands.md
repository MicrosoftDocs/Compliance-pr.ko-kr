---
title: NEN 7510
description: 네덜란드의 조직은 NEN 7510 표준에 따라 환자 건강 데이터에 대한 통제력을 입증해야 합니다.
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
ms.openlocfilehash: 79dc7fc209b85048189016a9bed8f5ca45b99bdb
ms.sourcegitcommit: 9b0c8852e73e2be54a0f9c6570da67f4964f616c
ms.translationtype: HT
ms.contentlocale: ko-KR
ms.lasthandoff: 07/12/2021
ms.locfileid: "53384458"
---
# <a name="nen-7510"></a><span data-ttu-id="370c3-104">NEN 7510</span><span class="sxs-lookup"><span data-stu-id="370c3-104">NEN 7510</span></span>

## <a name="nen-7510-overview"></a><span data-ttu-id="370c3-105">NEN 7510 개요</span><span class="sxs-lookup"><span data-stu-id="370c3-105">NEN 7510 overview</span></span>

<span data-ttu-id="370c3-106">환자 건강 정보를 처리하는 네덜란드의 조직은 NEN 7510 표준에 명시된 요구 사항과 일치하는 데이터 및 조직에 대한 통제력을 입증해야 합니다.</span><span class="sxs-lookup"><span data-stu-id="370c3-106">Organizations in the Netherlands that process patient health information must demonstrate control over that data and their organization consistent with the requirements set out in the NEN 7510 standard.</span></span> <span data-ttu-id="370c3-107">Microsoft 자체는 NEN 7510의 적용을 받지 않지만 의료 부문의 클라우드 고객은 Microsoft 클라우드에 구축된 솔루션과 관련하여 NEN 7510을 준수하도록 해야 합니다.</span><span class="sxs-lookup"><span data-stu-id="370c3-107">Microsoft is not itself subject to NEN 7510, but its cloud customers in the healthcare sector need to establish that they comply with NEN 7510 regarding solutions built on the Microsoft Cloud.</span></span> <span data-ttu-id="370c3-108">Microsoft 클라우드 서비스는 다양한 정기 인증 및 감사를 거치며 일부는 NEN 7510에 지정된 요구 사항과 밀접하게 관련된 요소를 포함합니다.</span><span class="sxs-lookup"><span data-stu-id="370c3-108">Microsoft cloud services undergo various periodic certifications and audits, some of which include elements closely related to requirements specified in NEN 7510.</span></span>

## <a name="microsoft-and-nen-75102011"></a><span data-ttu-id="370c3-109">Microsoft와 NEN 7510:2011</span><span class="sxs-lookup"><span data-stu-id="370c3-109">Microsoft and NEN 7510:2011</span></span>

<span data-ttu-id="370c3-110">Microsoft는 현재 인증 및 보장 진술문을 분석하고 [NEN 7510 커버리지 보고서](https://servicetrust.microsoft.com/ViewPage/TrustDocumentsV3?command=Download&downloadType=Document&downloadId=3285c45c-921c-49ad-b881-be43e0b70490&tab=7f51cb60-3d6c-11e9-b2af-7bb9f5d2d913&docTab=7f51cb60-3d6c-11e9-b2af-7bb9f5d2d913_Compliance_Guides) (Service Trust Platform에서 사용 가능)를 작성했습니다. 이 보고서는 해당 인증 및 보장 진술문을 클라우드 서비스 제공 업체로서 Microsoft가 담당하는 NEN 7510 컨트롤에 매핑합니다.</span><span class="sxs-lookup"><span data-stu-id="370c3-110">Microsoft has analyzed our current certifications and assurance statements and created a [NEN 7510 coverage report](https://servicetrust.microsoft.com/ViewPage/TrustDocumentsV3?command=Download&downloadType=Document&downloadId=3285c45c-921c-49ad-b881-be43e0b70490&tab=7f51cb60-3d6c-11e9-b2af-7bb9f5d2d913&docTab=7f51cb60-3d6c-11e9-b2af-7bb9f5d2d913_Compliance_Guides) (available on the Service Trust Platform), which maps those certifications and assurance statements against the NEN 7510 controls for which Microsoft is responsible as a cloud service provider.</span></span> <span data-ttu-id="370c3-111">이 문서는 고객이 환자 건강 정보의 저장 또는 처리를 위해 Microsoft 클라우드 서비스를 사용하여 NEN 7510을 준수하는지 확인하기 위해 구현해야 하는 다른 컨트롤을 결정하는 데 도움이 될 수 있습니다.</span><span class="sxs-lookup"><span data-stu-id="370c3-111">This document can help customers determine which other controls they must implement to ensure that their use of Microsoft cloud services for the storage or processing of patient health information complies with NEN 7510.</span></span>

<span data-ttu-id="370c3-112">Azure 보안 및 규정 준수 청사진을 사용하여 NEN 7510 배포를 가속화하는 방법에 대해 알아보세요. [Microsoft 클라우드 다운로드 — Azure 및 Office 365 NEN7510-2011 Standard Coverage 사용자 가이드](https://aka.ms/Azure-NEN7510-2011)</span><span class="sxs-lookup"><span data-stu-id="370c3-112">Learn how to accelerate your NEN 7510 deployment with our Azure Security and Compliance Blueprints: [Download the Microsoft Cloud: Azure and Office 365 NEN7510-2011 Standard Coverage User Guide](https://aka.ms/Azure-NEN7510-2011)</span></span>

## <a name="microsoft-in-scope-cloud-platforms--services"></a><span data-ttu-id="370c3-113">Microsoft 범위 내 클라우드 플랫폼 및 서비스</span><span class="sxs-lookup"><span data-stu-id="370c3-113">Microsoft in-scope cloud platforms & services</span></span>

- <span data-ttu-id="370c3-114">Azure 및 Azure Government</span><span class="sxs-lookup"><span data-stu-id="370c3-114">Azure and Azure Government</span></span>
- <span data-ttu-id="370c3-115">Intune</span><span class="sxs-lookup"><span data-stu-id="370c3-115">Intune</span></span>
- <span data-ttu-id="370c3-116">Office 365</span><span class="sxs-lookup"><span data-stu-id="370c3-116">Office 365</span></span>

## <a name="office-365-and-iso-27001"></a><span data-ttu-id="370c3-117">Office 365 및 ISO 27001</span><span class="sxs-lookup"><span data-stu-id="370c3-117">Office 365 and ISO 27001</span></span>

### <a name="office-365-cloud-environments"></a><span data-ttu-id="370c3-118">Office 365 클라우드 환경</span><span class="sxs-lookup"><span data-stu-id="370c3-118">Office 365 cloud environments</span></span>

[!INCLUDE [Office 365 offering intro](../includes/o365-offering-introduction.md)]

### <a name="office-365-applicability-and-in-scope-services"></a><span data-ttu-id="370c3-119">Office 365 적용 가능성 및 범위 내 서비스</span><span class="sxs-lookup"><span data-stu-id="370c3-119">Office 365 applicability and in-scope services</span></span>

<span data-ttu-id="370c3-120">다음 표를 사용하여 Office 365 서비스 및 구독에 대한 적용 가능성을 확인합니다.</span><span class="sxs-lookup"><span data-stu-id="370c3-120">Use the following table to determine applicability for your Office 365 services and subscription:</span></span>

| <span data-ttu-id="370c3-121">**적용 가능성**</span><span class="sxs-lookup"><span data-stu-id="370c3-121">**Applicability**</span></span> | <span data-ttu-id="370c3-122">**범위 내 서비스**</span><span class="sxs-lookup"><span data-stu-id="370c3-122">**In-scope services**</span></span> |
|:------------------|:----------------------|
| <span data-ttu-id="370c3-123">**Office 365**</span><span class="sxs-lookup"><span data-stu-id="370c3-123">**Office 365**</span></span> | <span data-ttu-id="370c3-124">Azure Information Protection, Bookings, Delve, Exchange Online, Exchange Online, Kaizala, Microsoft Analytics, Microsoft Booking, Microsoft Graph, Microsoft Teams, 웹용 Microsoft To-Do, MyAnalytics, Office 365 Cloud App Security, Office 365 그룹, Office 365 Video, 비즈니스용 OneDrive, Planner, Power Apps, Power Automate, Office 365용 Power BI, PowerApps, SharePoint Online, 비즈니스용 Skype, StaffHub, Stream, Sway, Yammer Enterprise</span><span class="sxs-lookup"><span data-stu-id="370c3-124">Azure Information Protection, Bookings, Delve, Exchange Online, Exchange Online Protection, Kaizala, Microsoft Analytics, Microsoft Booking, Microsoft Graph, Microsoft Teams, Microsoft To- Do for Web, MyAnalytics, Office 365 Cloud App Security, Office 365 Groups, Office 365 Video, OneDrive for Business,Planner, Power Apps, Power Automate, Power BI for Office 365, PowerApps, SharePoint Online, Skype for Business, StaffHub, Stream, Sway, Yammer Enterprise</span></span> |

## <a name="audits-reports-and-certificates"></a><span data-ttu-id="370c3-125">감사, 보고서 및 인증서</span><span class="sxs-lookup"><span data-stu-id="370c3-125">Audits, reports, and certificates</span></span>

- [<span data-ttu-id="370c3-126">Azure와 Office 365 NEN 7510:2011 Standard Coverage</span><span class="sxs-lookup"><span data-stu-id="370c3-126">Azure and Office 365 NEN 7510:2011 Standard Coverage</span></span>](https://servicetrust.microsoft.com/ViewPage/MSComplianceGuideV3?command=Download&downloadType=Document&downloadId=15d5a5fa-fbb6-4ea6-8126-2a2c684ae789&tab=7027ead0-3d6b-11e9-b9e1-290b1eb4cdeb&docTab=7027ead0-3d6b-11e9-b9e1-290b1eb4cdeb_GRC_Assessment_Reports)

## <a name="frequently-asked-questions"></a><span data-ttu-id="370c3-127">질문과 대답</span><span class="sxs-lookup"><span data-stu-id="370c3-127">Frequently asked questions</span></span>

<span data-ttu-id="370c3-128">**Microsoft 클라우드 서비스를 사용하는 고객이 NEN 7510을 준수하나요?**</span><span class="sxs-lookup"><span data-stu-id="370c3-128">**Is a customer that uses Microsoft cloud services compliant with NEN 7510?**</span></span>

<span data-ttu-id="370c3-129">NEN 규정 준수를 입증하는 것은 의료 기관(‘고객’)의 책임입니다.</span><span class="sxs-lookup"><span data-stu-id="370c3-129">Demonstrating NEN compliance is the responsibility of the healthcare organization (the 'customer').</span></span> <span data-ttu-id="370c3-130">클라우드 서비스 공급 업체를 사용할 때, 고객은 일반적으로 공급 업체의 보증을 요구하고 자체(기타) 기술과 조직의 결정, 선택 및 프로세스를 추가합니다.</span><span class="sxs-lookup"><span data-stu-id="370c3-130">When using a cloud services vendor, customers typically demand assurances from the vendor, and add their own (other) technology and organizational decisions, choices, and processes.</span></span> <span data-ttu-id="370c3-131">이러한 노력을 통해 NEN 7510 규정 준수에 대한 고객의 전반적인 평가가 이루어지며 검토 또는 인증을 위해 제 3의 감사관에게 제출할 수 있습니다.</span><span class="sxs-lookup"><span data-stu-id="370c3-131">This effort results in an overall assessment by the customer on its NEN 7510 compliance, which can be submitted for review or certification to a third-party auditor.</span></span> <span data-ttu-id="370c3-132">NEN 7510 적용 범위 보고서는 Microsoft 클라우드 서비스가 적용할 수있는 NEN 7510 컨트롤에 대한 통찰력을 제공하지만 종단간 규정 준수는 다루지 않습니다.</span><span class="sxs-lookup"><span data-stu-id="370c3-132">The NEN 7510 coverage report provides insight into which NEN 7510 controls are covered by Microsoft cloud services, but, as such, does not cover end-to-end compliance.</span></span>

<span data-ttu-id="370c3-133">**Microsoft는 NEN 7510을 준수하나요?**</span><span class="sxs-lookup"><span data-stu-id="370c3-133">**Is Microsoft compliant with NEN 7510?**</span></span>

<span data-ttu-id="370c3-134">NEN 7510 규정 준수에 대한 책임은 Dutch Healthcare 조직에 적용됩니다.</span><span class="sxs-lookup"><span data-stu-id="370c3-134">The responsibility for NEN 7510 compliance is applicable to Dutch Healthcare organizations.</span></span> <span data-ttu-id="370c3-135">조직은 정보보안 관리시스템을 구현하고 적절한 기술적 및 조직적 조치를 통해 위험을 해결해야 합니다.</span><span class="sxs-lookup"><span data-stu-id="370c3-135">It requires the organization to implement an information security management system and to address risk with appropriate technical and organizational measures.</span></span> <span data-ttu-id="370c3-136">클라우드 서비스 공급자 역할을 하는 Microsoft의 경우 NEN 7510 규정 준수는 목표가 아니며, 기술적으로도 가능하지 않습니다.</span><span class="sxs-lookup"><span data-stu-id="370c3-136">For Microsoft in its role as cloud service provider, NEN 7510 compliance is not the objective, nor is it technically feasible.</span></span> <span data-ttu-id="370c3-137">고객이 Microsoft 클라우드 서비스를 구현하거나 사용하는 경우 해당 서비스는 NEN 7510 평가 범위에 속할 수 있습니다.</span><span class="sxs-lookup"><span data-stu-id="370c3-137">When a customer implements or uses Microsoft cloud services, those services may be in scope of a NEN 7510 evaluation.</span></span> <span data-ttu-id="370c3-138">그러나 조직에서 전체 NEN 7510 평가의 일부로 자체(기타) 컨트롤, 선택 및 프로세스를 추가해야 합니다.</span><span class="sxs-lookup"><span data-stu-id="370c3-138">However, the organization must add its own (other) controls, choices, and processes that are part of the overall NEN 7510 evaluation.</span></span> <span data-ttu-id="370c3-139">이 보고서의 목적은 의료 기관이 NEN 7510을 준수하는 방식으로 Microsoft 클라우드 서비스를 채택할 수 있음을 보여주기 위한 것입니다.</span><span class="sxs-lookup"><span data-stu-id="370c3-139">The objective of the report is to demonstrate that a Healthcare entity can adopt the Microsoft cloud services in a manner that is compliant with NEN 7510.</span></span>

<span data-ttu-id="370c3-140">**보고서에 100% 적용범위가 표시되지 않습니다. NEN 7510 규정 준수가 적합하지 않나요?**</span><span class="sxs-lookup"><span data-stu-id="370c3-140">**The report does not show 100% coverage. Is NEN 7510 compliance not feasible?**</span></span>

<span data-ttu-id="370c3-141">Microsoft 클라우드 서비스는 Dutch Healthcare 내의 조직이 NEN 7510 규정 준수 요구를 충족할 수 있도록 많은 컨트롤을 제공합니다.</span><span class="sxs-lookup"><span data-stu-id="370c3-141">Microsoft cloud services provide many controls that help organizations within Dutch Healthcare with their NEN 7510 compliance needs.</span></span> <span data-ttu-id="370c3-142">그러나 조직에서는 자체 구현 선택, 기타 기술 컨트롤 및 관리 프로세스를 통해 이러한 공급 업체 보증을 보완해야 합니다.</span><span class="sxs-lookup"><span data-stu-id="370c3-142">However, an organization needs to complement those vendor assurances with their own implementation choices, other technology controls, and administrative processes.</span></span> <span data-ttu-id="370c3-143">이 보고서는 적용 가능한 전체 컨트롤 목록에 대해 이미 94%이상의 직접적인 적용 범위를 보여줍니다.</span><span class="sxs-lookup"><span data-stu-id="370c3-143">The report shows already over 94% direct coverage of the full list of applicable controls.</span></span> <span data-ttu-id="370c3-144">나머지 컨트롤의 경우, Microsoft는 해당 컨트롤의 준수 여부를 보여주는 방법에 대한 보고서의 지침을 제공합니다.</span><span class="sxs-lookup"><span data-stu-id="370c3-144">For the remaining controls, Microsoft provides guidance in the report on how compliance with those controls can be demonstrated.</span></span>

> [!NOTE]
> <span data-ttu-id="370c3-145">전체 컨트롤 목록을 구현하는 것이 NEN 7510의 주요 목적은 아닙니다 (Microsoft 온라인 서비스의 광범위한 적용 범위가 도움이 되더라도).</span><span class="sxs-lookup"><span data-stu-id="370c3-145">Implementing the full list of controls is not the primary purpose of NEN 7510 (although the large coverage of Microsoft Online Services does help).</span></span> <span data-ttu-id="370c3-146">NEN 7510은 조직이 어떤 통제가 적용 가능한지를 결정하기 위해 사용할 수 있는 리스크기반 정보보안 시스템의 구현을 의무화합니다.</span><span class="sxs-lookup"><span data-stu-id="370c3-146">NEN 7510 mandates the implementation of a risk-based information security system that can be used by an organization to determine which controls are applicable to them.</span></span>

<span data-ttu-id="370c3-147">**NEN 7510 커버리지 보고서는 법적 구속력이 있는 문서인가요?**</span><span class="sxs-lookup"><span data-stu-id="370c3-147">**Is the NEN 7510 coverage report a legal binding document?**</span></span>

<span data-ttu-id="370c3-148">아니요.</span><span class="sxs-lookup"><span data-stu-id="370c3-148">No.</span></span> <span data-ttu-id="370c3-149">고객의 내부 NEN 7510 보증 프로세스를 지원하는 도구이며 NEN 7510 준수가 실현 가능하다는 확신과 신뢰를 구축하는 데 도움이 됩니다.</span><span class="sxs-lookup"><span data-stu-id="370c3-149">It is a supporting tool for the customer's internal NEN 7510 assurance process and helps to establish confidence and trust that NEN 7510 compliance is feasible.</span></span> <span data-ttu-id="370c3-150">보고서 (독립 감사인, KPMG가 만든)는 설명적인 지위를 가지며 법적 면책 조항을 포함합니다.</span><span class="sxs-lookup"><span data-stu-id="370c3-150">The report (created by independent auditor, KPMG) has a descriptive status and includes a legal disclaimer.</span></span>

<span data-ttu-id="370c3-151">**Microsoft에서 보고서 비용을 지불했나요?**</span><span class="sxs-lookup"><span data-stu-id="370c3-151">**Did Microsoft pay for the report?**</span></span>

<span data-ttu-id="370c3-152">Microsoft는 NEN 7510 표준의 글로벌 보증과 컨트롤간의 매핑을 만들었습니다.</span><span class="sxs-lookup"><span data-stu-id="370c3-152">Microsoft created a mapping between its global assurances to the controls in the NEN 7510 standard.</span></span> <span data-ttu-id="370c3-153">그런 다음 Microsoft는 KPMG (독립 감사인)를 고용하여 NEN 7510에 대한 컨트롤 매핑에 대한 독립적인 검토를 수행하여 보고서를 작성했습니다.</span><span class="sxs-lookup"><span data-stu-id="370c3-153">Microsoft then hired KPMG (an independent auditor) to perform an independent review on the control mapping to NEN 7510, which resulted in the report.</span></span>

<span data-ttu-id="370c3-154">**이 보고서를 공유할 수 있나요?**</span><span class="sxs-lookup"><span data-stu-id="370c3-154">**Can we share this report?**</span></span>

<span data-ttu-id="370c3-155">이 보고서는 고객 정보 전용이며 Microsoft Service Trust Portal 이외의 다른 채널을 통해 복사 또는 공개되지 않을 것이라는 근거로 기밀 유지 계약 (NDA)에 따라 제공됩니다.</span><span class="sxs-lookup"><span data-stu-id="370c3-155">The report is provided with you under a non-disclosure agreement (NDA), on the basis that it is for customer information only and that it will not be copied or disclosed via other channels than the Microsoft Service Trust Portal.</span></span>

<span data-ttu-id="370c3-156">고객은 규정 준수 또는 보장 프로세스의 일부로 자체 내부 또는 외부 감사인을 사용하여 보고서를 공유할 수 있습니다.</span><span class="sxs-lookup"><span data-stu-id="370c3-156">Customers can share the report with their own internal or external auditor as part of their compliance or assurance processes.</span></span>

## <a name="resources"></a><span data-ttu-id="370c3-157">리소스</span><span class="sxs-lookup"><span data-stu-id="370c3-157">Resources</span></span>

- [<span data-ttu-id="370c3-158">NEN 정보</span><span class="sxs-lookup"><span data-stu-id="370c3-158">About NEN</span></span>](https://www.nen.nl/About-NEN.htm)
- [<span data-ttu-id="370c3-159">NEN 7510:2011 표준</span><span class="sxs-lookup"><span data-stu-id="370c3-159">NEN 7510:2011 standard</span></span>](https://www.nen.nl/NEN-Shop-2/Standard/NEN-75102011-nl.htm)
- [<span data-ttu-id="370c3-160">Microsoft 보안 센터에 대한 규정 준수</span><span class="sxs-lookup"><span data-stu-id="370c3-160">Compliance on the Microsoft Trust Center</span></span>](https://www.microsoft.com/trust-center/compliance/compliance-overview)
