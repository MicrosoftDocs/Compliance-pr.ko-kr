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
ms.openlocfilehash: 9ae0ba0b3ad10e4b1f2d308090f05c698bce092f
ms.sourcegitcommit: fb379d1110a9a86c7f9bab8c484dc3f4b3dfd6f0
ms.translationtype: HT
ms.contentlocale: ko-KR
ms.lasthandoff: 06/23/2021
ms.locfileid: "53088487"
---
# <a name="nen-7510"></a><span data-ttu-id="39479-104">NEN 7510</span><span class="sxs-lookup"><span data-stu-id="39479-104">NEN 7510</span></span>

## <a name="nen-7510-overview"></a><span data-ttu-id="39479-105">NEN 7510 개요</span><span class="sxs-lookup"><span data-stu-id="39479-105">NEN 7510 overview</span></span>

<span data-ttu-id="39479-106">환자 건강 정보를 처리하는 네덜란드의 조직은 NEN 7510 표준에 명시된 요구 사항과 일치하는 데이터 및 조직에 대한 통제력을 입증해야 합니다.</span><span class="sxs-lookup"><span data-stu-id="39479-106">Organizations in the Netherlands that process patient health information must demonstrate control over that data and their organization consistent with the requirements set out in the NEN 7510 standard.</span></span> <span data-ttu-id="39479-107">Microsoft 자체는 NEN 7510의 적용을 받지 않지만 의료 부문의 클라우드 고객은 Microsoft 클라우드에 구축된 솔루션과 관련하여 NEN 7510을 준수하도록 해야 합니다.</span><span class="sxs-lookup"><span data-stu-id="39479-107">Microsoft is not itself subject to NEN 7510, but its cloud customers in the healthcare sector need to establish that they comply with NEN 7510 regarding solutions built on the Microsoft Cloud.</span></span> <span data-ttu-id="39479-108">Microsoft 클라우드 서비스는 다양한 정기 인증 및 감사를 거치며 일부는 NEN 7510에 지정된 요구 사항과 밀접하게 관련된 요소를 포함합니다.</span><span class="sxs-lookup"><span data-stu-id="39479-108">Microsoft cloud services undergo various periodic certifications and audits, some of which include elements closely related to requirements specified in NEN 7510.</span></span>

## <a name="microsoft-and-nen-75102011"></a><span data-ttu-id="39479-109">Microsoft와 NEN 7510:2011</span><span class="sxs-lookup"><span data-stu-id="39479-109">Microsoft and NEN 7510:2011</span></span>

<span data-ttu-id="39479-110">Microsoft는 현재 인증 및 보장 진술문을 분석하고 [NEN 7510 커버리지 보고서](https://servicetrust.microsoft.com/ViewPage/TrustDocumentsV3?command=Download&downloadType=Document&downloadId=3285c45c-921c-49ad-b881-be43e0b70490&tab=7f51cb60-3d6c-11e9-b2af-7bb9f5d2d913&docTab=7f51cb60-3d6c-11e9-b2af-7bb9f5d2d913_Compliance_Guides) (Service Trust Platform에서 사용 가능)를 작성했습니다. 이 보고서는 해당 인증 및 보장 진술문을 클라우드 서비스 제공 업체로서 Microsoft가 담당하는 NEN 7510 컨트롤에 매핑합니다.</span><span class="sxs-lookup"><span data-stu-id="39479-110">Microsoft has analyzed our current certifications and assurance statements and created a [NEN 7510 coverage report](https://servicetrust.microsoft.com/ViewPage/TrustDocumentsV3?command=Download&downloadType=Document&downloadId=3285c45c-921c-49ad-b881-be43e0b70490&tab=7f51cb60-3d6c-11e9-b2af-7bb9f5d2d913&docTab=7f51cb60-3d6c-11e9-b2af-7bb9f5d2d913_Compliance_Guides) (available on the Service Trust Platform), which maps those certifications and assurance statements against the NEN 7510 controls for which Microsoft is responsible as a cloud service provider.</span></span> <span data-ttu-id="39479-111">이 문서는 고객이 환자 건강 정보의 저장 또는 처리를 위해 Microsoft 클라우드 서비스를 사용하여 NEN 7510을 준수하는지 확인하기 위해 구현해야 하는 다른 컨트롤을 결정하는 데 도움이 될 수 있습니다.</span><span class="sxs-lookup"><span data-stu-id="39479-111">This document can help customers determine which other controls they must implement to ensure that their use of Microsoft cloud services for the storage or processing of patient health information complies with NEN 7510.</span></span>

<span data-ttu-id="39479-112">Azure 보안 및 규정 준수 청사진을 사용하여 NEN 7510 배포를 가속화하는 방법에 대해 알아보세요. [Microsoft 클라우드 다운로드 — Azure 및 Office 365 NEN7510-2011 Standard Coverage 사용자 가이드](https://aka.ms/Azure-NEN7510-2011)</span><span class="sxs-lookup"><span data-stu-id="39479-112">Learn how to accelerate your NEN 7510 deployment with our Azure Security and Compliance Blueprints: [Download the Microsoft Cloud: Azure and Office 365 NEN7510-2011 Standard Coverage User Guide](https://aka.ms/Azure-NEN7510-2011)</span></span>

## <a name="microsoft-in-scope-cloud-services"></a><span data-ttu-id="39479-113">Microsoft 범위 내 클라우드 서비스</span><span class="sxs-lookup"><span data-stu-id="39479-113">Microsoft in-scope cloud services</span></span>

- [<span data-ttu-id="39479-114">Azure 및 Azure Government</span><span class="sxs-lookup"><span data-stu-id="39479-114">Azure and Azure Government</span></span>](https://aka.ms/AzureCompliance)
- <span data-ttu-id="39479-115">Intune</span><span class="sxs-lookup"><span data-stu-id="39479-115">Intune</span></span>
- [<span data-ttu-id="39479-116">Office 365</span><span class="sxs-lookup"><span data-stu-id="39479-116">Office 365</span></span>](https://go.microsoft.com/fwlink/p/?LinkID=2077751)

## <a name="audits-reports-and-certificates"></a><span data-ttu-id="39479-117">감사, 보고서 및 인증서</span><span class="sxs-lookup"><span data-stu-id="39479-117">Audits, reports, and certificates</span></span>

- [<span data-ttu-id="39479-118">Azure와 Office 365 NEN 7510:2011 Standard Coverage</span><span class="sxs-lookup"><span data-stu-id="39479-118">Azure and Office 365 NEN 7510:2011 Standard Coverage</span></span>](https://servicetrust.microsoft.com/ViewPage/MSComplianceGuideV3?command=Download&downloadType=Document&downloadId=15d5a5fa-fbb6-4ea6-8126-2a2c684ae789&tab=7027ead0-3d6b-11e9-b9e1-290b1eb4cdeb&docTab=7027ead0-3d6b-11e9-b9e1-290b1eb4cdeb_GRC_Assessment_Reports)

## <a name="frequently-asked-questions"></a><span data-ttu-id="39479-119">질문과 대답</span><span class="sxs-lookup"><span data-stu-id="39479-119">Frequently asked questions</span></span>

<span data-ttu-id="39479-120">**Microsoft 클라우드 서비스를 사용하는 고객이 NEN 7510을 준수하나요?**</span><span class="sxs-lookup"><span data-stu-id="39479-120">**Is a customer that uses Microsoft cloud services compliant with NEN 7510?**</span></span>

<span data-ttu-id="39479-121">NEN 규정 준수를 입증하는 것은 의료 기관(‘고객’)의 책임입니다.</span><span class="sxs-lookup"><span data-stu-id="39479-121">Demonstrating NEN compliance is the responsibility of the healthcare organization (the 'customer').</span></span> <span data-ttu-id="39479-122">클라우드 서비스 공급 업체를 사용할 때, 고객은 일반적으로 공급 업체의 보증을 요구하고 자체(기타) 기술과 조직의 결정, 선택 및 프로세스를 추가합니다.</span><span class="sxs-lookup"><span data-stu-id="39479-122">When using a cloud services vendor, customers typically demand assurances from the vendor, and add their own (other) technology and organizational decisions, choices, and processes.</span></span> <span data-ttu-id="39479-123">이러한 노력을 통해 NEN 7510 규정 준수에 대한 고객의 전반적인 평가가 이루어지며 검토 또는 인증을 위해 제 3의 감사관에게 제출할 수 있습니다.</span><span class="sxs-lookup"><span data-stu-id="39479-123">This effort results in an overall assessment by the customer on its NEN 7510 compliance, which can be submitted for review or certification to a third-party auditor.</span></span> <span data-ttu-id="39479-124">NEN 7510 적용 범위 보고서는 Microsoft 클라우드 서비스가 적용할 수있는 NEN 7510 컨트롤에 대한 통찰력을 제공하지만 종단간 규정 준수는 다루지 않습니다.</span><span class="sxs-lookup"><span data-stu-id="39479-124">The NEN 7510 coverage report provides insight into which NEN 7510 controls are covered by Microsoft cloud services, but, as such, does not cover end-to-end compliance.</span></span>

<span data-ttu-id="39479-125">**Microsoft는 NEN 7510을 준수하나요?**</span><span class="sxs-lookup"><span data-stu-id="39479-125">**Is Microsoft compliant with NEN 7510?**</span></span>

<span data-ttu-id="39479-126">NEN 7510 규정 준수에 대한 책임은 Dutch Healthcare 조직에 적용됩니다.</span><span class="sxs-lookup"><span data-stu-id="39479-126">The responsibility for NEN 7510 compliance is applicable to Dutch Healthcare organizations.</span></span> <span data-ttu-id="39479-127">조직은 정보보안 관리시스템을 구현하고 적절한 기술적 및 조직적 조치를 통해 위험을 해결해야 합니다.</span><span class="sxs-lookup"><span data-stu-id="39479-127">It requires the organization to implement an information security management system and to address risk with appropriate technical and organizational measures.</span></span> <span data-ttu-id="39479-128">클라우드 서비스 공급자 역할을 하는 Microsoft의 경우 NEN 7510 규정 준수는 목표가 아니며, 기술적으로도 가능하지 않습니다.</span><span class="sxs-lookup"><span data-stu-id="39479-128">For Microsoft in its role as cloud service provider, NEN 7510 compliance is not the objective, nor is it technically feasible.</span></span> <span data-ttu-id="39479-129">고객이 Microsoft 클라우드 서비스를 구현하거나 사용하는 경우 해당 서비스는 NEN 7510 평가 범위에 속할 수 있습니다.</span><span class="sxs-lookup"><span data-stu-id="39479-129">When a customer implements or uses Microsoft cloud services, those services may be in scope of a NEN 7510 evaluation.</span></span> <span data-ttu-id="39479-130">그러나 조직에서 전체 NEN 7510 평가의 일부로 자체(기타) 컨트롤, 선택 및 프로세스를 추가해야 합니다.</span><span class="sxs-lookup"><span data-stu-id="39479-130">However, the organization must add its own (other) controls, choices, and processes that are part of the overall NEN 7510 evaluation.</span></span> <span data-ttu-id="39479-131">이 보고서의 목적은 의료 기관이 NEN 7510을 준수하는 방식으로 Microsoft 클라우드 서비스를 채택할 수 있음을 보여주기 위한 것입니다.</span><span class="sxs-lookup"><span data-stu-id="39479-131">The objective of the report is to demonstrate that a Healthcare entity can adopt the Microsoft cloud services in a manner that is compliant with NEN 7510.</span></span>

<span data-ttu-id="39479-132">**보고서에 100% 적용범위가 표시되지 않습니다. NEN 7510 규정 준수가 적합하지 않나요?**</span><span class="sxs-lookup"><span data-stu-id="39479-132">**The report does not show 100% coverage. Is NEN 7510 compliance not feasible?**</span></span>

<span data-ttu-id="39479-133">Microsoft 클라우드 서비스는 Dutch Healthcare 내의 조직이 NEN 7510 규정 준수 요구를 충족할 수 있도록 많은 컨트롤을 제공합니다.</span><span class="sxs-lookup"><span data-stu-id="39479-133">Microsoft cloud services provide many controls that help organizations within Dutch Healthcare with their NEN 7510 compliance needs.</span></span> <span data-ttu-id="39479-134">그러나 조직에서는 자체 구현 선택, 기타 기술 컨트롤 및 관리 프로세스를 통해 이러한 공급 업체 보증을 보완해야 합니다.</span><span class="sxs-lookup"><span data-stu-id="39479-134">However, an organization needs to complement those vendor assurances with their own implementation choices, other technology controls, and administrative processes.</span></span> <span data-ttu-id="39479-135">이 보고서는 적용 가능한 전체 컨트롤 목록에 대해 이미 94%이상의 직접적인 적용 범위를 보여줍니다.</span><span class="sxs-lookup"><span data-stu-id="39479-135">The report shows already over 94% direct coverage of the full list of applicable controls.</span></span> <span data-ttu-id="39479-136">나머지 컨트롤의 경우, Microsoft는 해당 컨트롤의 준수 여부를 보여주는 방법에 대한 보고서의 지침을 제공합니다.</span><span class="sxs-lookup"><span data-stu-id="39479-136">For the remaining controls, Microsoft provides guidance in the report on how compliance with those controls can be demonstrated.</span></span>

> [!NOTE]
> <span data-ttu-id="39479-137">전체 컨트롤 목록을 구현하는 것이 NEN 7510의 주요 목적은 아닙니다 (Microsoft 온라인 서비스의 광범위한 적용 범위가 도움이 되더라도).</span><span class="sxs-lookup"><span data-stu-id="39479-137">Implementing the full list of controls is not the primary purpose of NEN 7510 (although the large coverage of Microsoft Online Services does help).</span></span> <span data-ttu-id="39479-138">NEN 7510은 조직이 어떤 통제가 적용 가능한지를 결정하기 위해 사용할 수 있는 리스크기반 정보보안 시스템의 구현을 의무화합니다.</span><span class="sxs-lookup"><span data-stu-id="39479-138">NEN 7510 mandates the implementation of a risk-based information security system that can be used by an organization to determine which controls are applicable to them.</span></span>

<span data-ttu-id="39479-139">**NEN 7510 커버리지 보고서는 법적 구속력이 있는 문서인가요?**</span><span class="sxs-lookup"><span data-stu-id="39479-139">**Is the NEN 7510 coverage report a legal binding document?**</span></span>

<span data-ttu-id="39479-140">아니요.</span><span class="sxs-lookup"><span data-stu-id="39479-140">No.</span></span> <span data-ttu-id="39479-141">고객의 내부 NEN 7510 보증 프로세스를 지원하는 도구이며 NEN 7510 준수가 실현 가능하다는 확신과 신뢰를 구축하는 데 도움이 됩니다.</span><span class="sxs-lookup"><span data-stu-id="39479-141">It is a supporting tool for the customer's internal NEN 7510 assurance process and helps to establish confidence and trust that NEN 7510 compliance is feasible.</span></span> <span data-ttu-id="39479-142">보고서 (독립 감사인, KPMG가 만든)는 설명적인 지위를 가지며 법적 면책 조항을 포함합니다.</span><span class="sxs-lookup"><span data-stu-id="39479-142">The report (created by independent auditor, KPMG) has a descriptive status and includes a legal disclaimer.</span></span>

<span data-ttu-id="39479-143">**Microsoft에서 보고서 비용을 지불했나요?**</span><span class="sxs-lookup"><span data-stu-id="39479-143">**Did Microsoft pay for the report?**</span></span>

<span data-ttu-id="39479-144">Microsoft는 NEN 7510 표준의 글로벌 보증과 컨트롤간의 매핑을 만들었습니다.</span><span class="sxs-lookup"><span data-stu-id="39479-144">Microsoft created a mapping between its global assurances to the controls in the NEN 7510 standard.</span></span> <span data-ttu-id="39479-145">그런 다음 Microsoft는 KPMG (독립 감사인)를 고용하여 NEN 7510에 대한 컨트롤 매핑에 대한 독립적인 검토를 수행하여 보고서를 작성했습니다.</span><span class="sxs-lookup"><span data-stu-id="39479-145">Microsoft then hired KPMG (an independent auditor) to perform an independent review on the control mapping to NEN 7510, which resulted in the report.</span></span>

<span data-ttu-id="39479-146">**이 보고서를 공유할 수 있나요?**</span><span class="sxs-lookup"><span data-stu-id="39479-146">**Can we share this report?**</span></span>

<span data-ttu-id="39479-147">이 보고서는 고객 정보 전용이며 Microsoft Service Trust Portal 이외의 다른 채널을 통해 복사 또는 공개되지 않을 것이라는 근거로 기밀 유지 계약 (NDA)에 따라 제공됩니다.</span><span class="sxs-lookup"><span data-stu-id="39479-147">The report is provided with you under a non-disclosure agreement (NDA), on the basis that it is for customer information only and that it will not be copied or disclosed via other channels than the Microsoft Service Trust Portal.</span></span>

<span data-ttu-id="39479-148">고객은 규정 준수 또는 보장 프로세스의 일부로 자체 내부 또는 외부 감사인을 사용하여 보고서를 공유할 수 있습니다.</span><span class="sxs-lookup"><span data-stu-id="39479-148">Customers can share the report with their own internal or external auditor as part of their compliance or assurance processes.</span></span>

## <a name="resources"></a><span data-ttu-id="39479-149">리소스</span><span class="sxs-lookup"><span data-stu-id="39479-149">Resources</span></span>

- [<span data-ttu-id="39479-150">NEN 정보</span><span class="sxs-lookup"><span data-stu-id="39479-150">About NEN</span></span>](https://www.nen.nl/About-NEN.htm)
- [<span data-ttu-id="39479-151">NEN 7510:2011 표준</span><span class="sxs-lookup"><span data-stu-id="39479-151">NEN 7510:2011 standard</span></span>](https://www.nen.nl/NEN-Shop-2/Standard/NEN-75102011-nl.htm)
- [<span data-ttu-id="39479-152">Microsoft 보안 센터에 대한 규정 준수</span><span class="sxs-lookup"><span data-stu-id="39479-152">Compliance on the Microsoft Trust Center</span></span>](https://www.microsoft.com/trust-center/compliance/compliance-overview)
