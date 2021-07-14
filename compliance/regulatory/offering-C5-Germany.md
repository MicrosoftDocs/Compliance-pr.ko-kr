---
title: 클라우드 컴퓨팅 규정 준수 컨트롤 카탈로그(C5)
description: Azure, Azure Government 및 Azure Germany가 C5(클라우드 컴퓨팅 규정 준수 컨트롤 카달로그)에 대한 규정 준수를 증명하는 방법을 알아보십시오.
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
ms.openlocfilehash: 7a530d78107af4f37607f90c6a93008ec695f765
ms.sourcegitcommit: 9b0c8852e73e2be54a0f9c6570da67f4964f616c
ms.translationtype: HT
ms.contentlocale: ko-KR
ms.lasthandoff: 07/12/2021
ms.locfileid: "53385468"
---
# <a name="cloud-computing-compliance-controls-catalog-c5"></a><span data-ttu-id="f5f48-104">클라우드 컴퓨팅 규정 준수 컨트롤 카탈로그(C5)</span><span class="sxs-lookup"><span data-stu-id="f5f48-104">Cloud Computing Compliance Controls Catalog (C5)</span></span>

## <a name="c5-overview"></a><span data-ttu-id="f5f48-105">C5 개요</span><span class="sxs-lookup"><span data-stu-id="f5f48-105">C5 overview</span></span>

<span data-ttu-id="f5f48-106">2016에서 정보 보안을 위한 독일어 (Bundesamt für Sicherheit, BSI)는 클라우드 컴퓨팅 준수 컨트롤 카탈로그 (C5)를 만들었습니다.</span><span class="sxs-lookup"><span data-stu-id="f5f48-106">In 2016, the German Federal Office for Information Security (Bundesamt für Sicherheit in der Informationstechnik, or BSI) created the Cloud Computing Compliance Controls Catalog (C5).</span></span> <span data-ttu-id="f5f48-107">C5는 감사 표준으로, 클라우드 보안을 위한 필수 최소 기준을 설정하고 독일 정부 기관 및 정부와 협력하는 조직의 퍼블릭 클라우드 솔루션 채택을 설정합니다.</span><span class="sxs-lookup"><span data-stu-id="f5f48-107">C5 is an audited standard that establishes a mandatory minimum baseline for cloud security and the adoption of public cloud solutions by German government agencies and organizations that work with government.</span></span> <span data-ttu-id="f5f48-108">또한 C5는 민간 부문에서도 도입 사례가 점차 늘고 있습니다.</span><span class="sxs-lookup"><span data-stu-id="f5f48-108">C5 is also being increasingly adopted by the private sector.</span></span>

<span data-ttu-id="f5f48-109">C5 요구 사항 카탈로그의 목적은 클라우드 서비스 공급자를 인증하기 위한 일관된 보안 프레임워크를 제공하고 고객에게 데이터가 안전하게 관리된다는 확신을 제공하는 것입니다.</span><span class="sxs-lookup"><span data-stu-id="f5f48-109">The purpose of the C5 catalog of requirements is to provide a consistent security framework for certifying cloud service providers and to give customers assurance that their data will be managed securely.</span></span>

<span data-ttu-id="f5f48-110">C5는 ISO/IEC 27001:2013, 클라우드 보안 제휴 클라우드 컨트롤 매트릭스 3.0.1 및 BSI의 IT-Grundschutz 카달로그와 같은 국제적으로 유명한 보안 표준을 바탕으로 합니다.</span><span class="sxs-lookup"><span data-stu-id="f5f48-110">C5 is based on internationally recognized IT security standards like ISO/IEC 27001:2013, the Cloud Security Alliance Cloud Controls Matrix 3.0.1, and BSI's own IT-Grundschutz Catalogues.</span></span> <span data-ttu-id="f5f48-111">이 카탈로그는 17개의 도메인(예: 정보 보안 및 물리적 보안 조직)에 대한 114개의 요구 사항으로 구성되어 있으며 모든 클라우드 서비스 제공자의 기본 보안 요구 사항과 기밀성이 높은 데이터 및 고가용성이 필요한 상황을 처리하기 위한 기타 요구 사항이 포함되어 있습니다.</span><span class="sxs-lookup"><span data-stu-id="f5f48-111">The catalog consists of 114 requirements across 17 domains, for example, the organization of information security and physical security, with security requirements basic to all cloud service providers, and other requirements for processing highly confidential data and situations requiring high availability.</span></span>

<span data-ttu-id="f5f48-112">또한 BSI는 투명성에 중점을 둡니다.</span><span class="sxs-lookup"><span data-stu-id="f5f48-112">The BSI also puts emphasis on transparency.</span></span> <span data-ttu-id="f5f48-113">감사의 일환으로, 클라우드 제공자는 상세한 시스템 설명을 포함하고 관할권 및 데이터 처리 위치, 서비스 제공 및 클라우드 서비스에 발행된 기타 인증과 같은 환경 매개 변수와 클라우드 제공자의 공공기관에 대한 공개 의무에 대한 정보를 공개해야 합니다.</span><span class="sxs-lookup"><span data-stu-id="f5f48-113">As part of an audit, the cloud provider must include a detailed system description and disclose environmental parameters like jurisdiction and data processing location, provision of services, and other certifications issued to the cloud services, and information about the cloud provider's disclosure obligations to public authorities.</span></span> <span data-ttu-id="f5f48-114">이를 통해 잠재적인 클라우드 고객은 클라우드 서비스가 데이터 보호, 회사 정책 또는 산업 스파이의 위협을 해결하는 기능과 같은 법적 요구 사항 준수와 같은 필수 요구 사항을 충족하는지 여부를 결정할 수 있습니다.</span><span class="sxs-lookup"><span data-stu-id="f5f48-114">This helps potential cloud customers decide whether the cloud services meet their essential requirements such as compliance with legal requirements like data protection, company policies, or the ability to address the threat of industrial espionage.</span></span>

## <a name="microsoft-and-c5"></a><span data-ttu-id="f5f48-115">Microsoft와 C5</span><span class="sxs-lookup"><span data-stu-id="f5f48-115">Microsoft and C5</span></span>

<span data-ttu-id="f5f48-116">SOC 2(AT Section 101) 표준에 따라 Microsoft 클라우드 서비스를 적어도 매년 감사합니다.</span><span class="sxs-lookup"><span data-stu-id="f5f48-116">Microsoft cloud services are audited at least annually against SOC 2 (AT Section 101) standards.</span></span> <span data-ttu-id="f5f48-117">BSI에 따르면 C5 감사는 SOC 2 감사와 결합되어 시스템 설명의 일부 및 겹치는 컨트롤에 대한 감사 결과를 재사용할 수 있습니다.</span><span class="sxs-lookup"><span data-stu-id="f5f48-117">According to BSI, a C5 audit can be combined with a SOC 2 audit to reuse parts of the system description and audit results for overlapping controls.</span></span> <span data-ttu-id="f5f48-118">Microsoft Azure, Azure Government 및 Azure Germany는 독립 감사원이 수행한 감사 평가를 기반으로 C5 준수 여부를 증명하는 결합된 보고서(C5, SOC 2 유형 2, CSA STAR 증명)를 유지 관리합니다.</span><span class="sxs-lookup"><span data-stu-id="f5f48-118">Microsoft Azure, Azure Government, and Azure Germany maintain a combined report (C5, SOC 2 Type 2, CSA STAR Attestation) based on the audit assessment performed by an independent auditor, which demonstrates proof of compliance with C5.</span></span>

## <a name="microsoft-in-scope-cloud-platforms--services"></a><span data-ttu-id="f5f48-119">Microsoft 범위 내 클라우드 플랫폼 및 서비스</span><span class="sxs-lookup"><span data-stu-id="f5f48-119">Microsoft in-scope cloud platforms & services</span></span>

- [<span data-ttu-id="f5f48-120">Azure, Azure Government, Azure Germany</span><span class="sxs-lookup"><span data-stu-id="f5f48-120">Azure, Azure Government, and Azure Germany</span></span>](https://go.microsoft.com/fwlink/p/?linkid=2051569)
- <span data-ttu-id="f5f48-121">Office 365 Germany</span><span class="sxs-lookup"><span data-stu-id="f5f48-121">Office 365 Germany</span></span>

## <a name="audits-reports-and-certificates"></a><span data-ttu-id="f5f48-122">감사, 보고서 및 인증서</span><span class="sxs-lookup"><span data-stu-id="f5f48-122">Audits, reports, and certificates</span></span>

- [<span data-ttu-id="f5f48-123">Azure, Azure Government, 및 Azure Germany SOC 2 유형 II 보고서.pdf</span><span class="sxs-lookup"><span data-stu-id="f5f48-123">Azure, Azure Government, and Azure Germany SOC 2 Type II Report.pdf</span></span>](https://go.microsoft.com/fwlink/p/?linkid=2093520)

## <a name="frequently-asked-questions"></a><span data-ttu-id="f5f48-124">자주하는 질문</span><span class="sxs-lookup"><span data-stu-id="f5f48-124">Frequently asked questions</span></span>

<span data-ttu-id="f5f48-125">**사용자가 C5에 대한 Microsoft 규정 준수를 사용하여 조직에서 자신의 C5 증명을 받을 수 있나요?**</span><span class="sxs-lookup"><span data-stu-id="f5f48-125">**Can I use Microsoft compliance with C5 to help my organization get its own C5 attestation?**</span></span>

<span data-ttu-id="f5f48-126">예.</span><span class="sxs-lookup"><span data-stu-id="f5f48-126">Yes.</span></span> <span data-ttu-id="f5f48-127">C5가 요구되는 프로그램이나 이니셔티브에 대한 기초로서 Microsoft 클라우드 서비스의 증명을 활용할 수 있습니다.</span><span class="sxs-lookup"><span data-stu-id="f5f48-127">You may use the attestation of Microsoft cloud services as the foundation for any program or initiative that requires C5.</span></span> <span data-ttu-id="f5f48-128">그러나 이러한 서비스 외부에 있거나 이러한 서비스에 구축 된 구성 요소에 대해서 자체적인 C5 증명을 달성해야 합니다.</span><span class="sxs-lookup"><span data-stu-id="f5f48-128">However, you need to achieve your own C5 attestation for components outside or built on top of these services.</span></span>

<span data-ttu-id="f5f48-129">**C5와 IT-Grundschutz 카탈로그의 차이점은 무엇인가요?**</span><span class="sxs-lookup"><span data-stu-id="f5f48-129">**What's the difference between C5 and the IT-Grundschutz Catalogues?**</span></span>

<span data-ttu-id="f5f48-130">IT-Grundschutz는 조직이 IT 시스템에 대한 보안 조치를 식별하고 구현하는 데 도움이 되는 특정 방법론을 제공하며 C5 표준이 구축되는 요소 중 하나입니다.</span><span class="sxs-lookup"><span data-stu-id="f5f48-130">IT-Grundschutz supplies the specific methodology to help organizations identify and implement security measures for IT systems and is one of the elements upon which the C5 standards are built.</span></span> <span data-ttu-id="f5f48-131">C5는 클라우드 서비스 제공자를 위한 일련의 감사 표준을 제공하지만 구현 세부 사항은 클라우드 서비스 제공자에 맡깁니다.</span><span class="sxs-lookup"><span data-stu-id="f5f48-131">C5 provides a set of audit standards for cloud service providers but leaves the details of implementation up to the cloud service provider.</span></span>

<span data-ttu-id="f5f48-132">**Microsoft Cloud Germany 란 무엇인가요?**</span><span class="sxs-lookup"><span data-stu-id="f5f48-132">**What is Microsoft Cloud Germany?**</span></span>

<span data-ttu-id="f5f48-133">Microsoft Cloud Germany는 독일에 물리적으로 기반을 두고 있으며 독일 개인 정보 보호법의 요구 사항을 준수하며, 다른 국가로의 개인 데이터 전송을 제한하고, 국내 법률을 위반할 수 있는 다른 관할 구역으로부터 당국에 의한 액세스를 보호합니다.</span><span class="sxs-lookup"><span data-stu-id="f5f48-133">Microsoft Cloud Germany is physically based in Germany, adhering to the requirement of German privacy law, which limits the transfer of personal data to other countries and offers protection against access by authorities from other jurisdictions who could violate domestic laws.</span></span> <span data-ttu-id="f5f48-134">Azure Germany는 독일의 데이터 상주가 있는 독일 데이터 센터의 Azure 서비스를 제공하며 독일 법률에 따라 통제되는 고유한 데이터 피신탁 모델을 통해 제공되는 엄격한 데이터 액세스 및 제어 수단을 제공합니다.</span><span class="sxs-lookup"><span data-stu-id="f5f48-134">Azure Germany delivers Azure services from German datacenters with data residency in Germany, and it delivers strict data access and control measures provided through a unique data trustee model governed under German law.</span></span>

## <a name="use-microsoft-compliance-manager-to-assess-your-risk"></a><span data-ttu-id="f5f48-135">Microsoft 준수 관리자를 사용하여 위험 평가</span><span class="sxs-lookup"><span data-stu-id="f5f48-135">Use Microsoft Compliance Manager to assess your risk</span></span>

<span data-ttu-id="f5f48-136">[Microsoft 준수 관리자](/microsoft-365/compliance/compliance-manager)는 조직의 준수 입장을 이해하고 위험을 줄이기 위한 조치를 취하도록 돕는 [Microsoft 365 규정 준수 센터](/microsoft-365/compliance/microsoft-365-compliance-center)의 기능입니다.</span><span class="sxs-lookup"><span data-stu-id="f5f48-136">[Microsoft Compliance Manager](/microsoft-365/compliance/compliance-manager) is a feature in the [Microsoft 365 compliance center](/microsoft-365/compliance/microsoft-365-compliance-center) to help you understand your organization's compliance posture and take actions to help reduce risks.</span></span> <span data-ttu-id="f5f48-137">준수 관리자는 이 규제에 대한 평가를 빌드하기 위한 프리미엄 서식 파일을 제공합니다.</span><span class="sxs-lookup"><span data-stu-id="f5f48-137">Compliance Manager offers a premium template for building an assessment for this regulation.</span></span> <span data-ttu-id="f5f48-138">준수 관리자의 **평가 서식 파일** 페이지에서 서식 파일을 찾습니다.</span><span class="sxs-lookup"><span data-stu-id="f5f48-138">Find the template in the **assessment templates** page in Compliance Manager.</span></span> <span data-ttu-id="f5f48-139">[준수 관리자의 평가 빌드](/microsoft-365/compliance/compliance-manager-assessments) 방법에 대해 알아봅니다.</span><span class="sxs-lookup"><span data-stu-id="f5f48-139">Learn how to [build assessments in Compliance Manager](/microsoft-365/compliance/compliance-manager-assessments).</span></span>

## <a name="resources"></a><span data-ttu-id="f5f48-140">리소스</span><span class="sxs-lookup"><span data-stu-id="f5f48-140">Resources</span></span>

- <span data-ttu-id="f5f48-141">클라우드 컴퓨팅 규정 준수 컨트롤 카탈로그(C5) ([영어](https://www.bsi.bund.de/EN/Topics/CloudComputing/Compliance_Criteria_Catalogue/Compliance_Criteria_Catalogue_node.html)) ([독일어](https://www.bsi.bund.de/DE/Themen/DigitaleGesellschaft/CloudComputing/Kriterienkatalog/Kriterienkatalog_node.html))</span><span class="sxs-lookup"><span data-stu-id="f5f48-141">Cloud Computing Compliance Controls Catalogue (C5) ([English](https://www.bsi.bund.de/EN/Topics/CloudComputing/Compliance_Criteria_Catalogue/Compliance_Criteria_Catalogue_node.html)) ([German](https://www.bsi.bund.de/DE/Themen/DigitaleGesellschaft/CloudComputing/Kriterienkatalog/Kriterienkatalog_node.html))</span></span>
- <span data-ttu-id="f5f48-142">클라우드 컴퓨팅 공급자에 대한 보안 권장 사항([영어](https://www.bsi.bund.de/EN/Topics/CloudComputing/Secure_use_of_cloud_services/Secure_use_cloud_services_node.html)) ([독일어](https://www.bsi.bund.de/DE/Themen/DigitaleGesellschaft/CloudComputing/Sichere_Nutzung_Cloud/Sichere_Nutzung_Cloud_node.html))</span><span class="sxs-lookup"><span data-stu-id="f5f48-142">Security Recommendations for Cloud Computing Providers ([English](https://www.bsi.bund.de/EN/Topics/CloudComputing/Secure_use_of_cloud_services/Secure_use_cloud_services_node.html)) ([German](https://www.bsi.bund.de/DE/Themen/DigitaleGesellschaft/CloudComputing/Sichere_Nutzung_Cloud/Sichere_Nutzung_Cloud_node.html))</span></span>
- [<span data-ttu-id="f5f48-143">준수 보고서: C5-und SOC-Testate Azure 독일</span><span class="sxs-lookup"><span data-stu-id="f5f48-143">Compliance Reports: C5- und SOC-Testate Azure Deutschland</span></span>](https://servicetrust.microsoft.com/ViewPage/MSComplianceGuide?command=Download&downloadType=Document&downloadId=df100ae1-baf9-4785-8a6d-864c0bc5c308&docTab=4ce99610-c9c0-11e7-8c2c-f908a777fa4d_SOC%20%2F%20SSAE%2016%20Reports)
- <span data-ttu-id="f5f48-144">Microsoft Azure Germany용 [IT-Grundschutz 규정 준수 통합 문서](https://gallery.technet.microsoft.com/Azure-Germany-IT-fca4afd7)</span><span class="sxs-lookup"><span data-stu-id="f5f48-144">[IT-Grundschutz Compliance Workbook](https://gallery.technet.microsoft.com/Azure-Germany-IT-fca4afd7) for Microsoft Azure Germany</span></span>
- [<span data-ttu-id="f5f48-145">Microsoft 보안 센터에 대한 규정 준수</span><span class="sxs-lookup"><span data-stu-id="f5f48-145">Compliance on the Microsoft Trust Center</span></span>](https://www.microsoft.com/trust-center/compliance/compliance-overview)
