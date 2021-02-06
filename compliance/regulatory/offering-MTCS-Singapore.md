---
title: 싱가포르 MTCS(다단계 클라우드 보안) 표준
description: Microsoft는 싱가포르 다단계 클라우드 보안 표준에 대한 인증을 받았습니다.
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
ms.openlocfilehash: 07620a613cefd4ebac5acd0626ee855f8d077089
ms.sourcegitcommit: 21ed42335efd37774ff5d17d9586d5546147241a
ms.translationtype: HT
ms.contentlocale: ko-KR
ms.lasthandoff: 02/05/2021
ms.locfileid: "50120097"
---
# <a name="multi-tier-cloud-security-mtcs-standard-for-singapore"></a><span data-ttu-id="25b6d-104">싱가포르 MTCS(다단계 클라우드 보안) 표준</span><span class="sxs-lookup"><span data-stu-id="25b6d-104">Multi-Tier Cloud Security (MTCS) Standard for Singapore</span></span>

## <a name="mtcs-overview"></a><span data-ttu-id="25b6d-105">MTCS 개요</span><span class="sxs-lookup"><span data-stu-id="25b6d-105">MTCS overview</span></span>

<span data-ttu-id="25b6d-106">싱가포르의 MTCS(다단계 클라우드 보안) 표준은 싱가포르 IDA(정보 통신 개발국(Infocomm Development Authority)), ITSC(Information Technology Standards Committee: 정보 기술 표준 위원회)의 지휘 아래 작성되었습니다.</span><span class="sxs-lookup"><span data-stu-id="25b6d-106">The Multi-Tier Cloud Security (MTCS) Standard for Singapore was prepared under the direction of the Information Technology Standards Committee (ITSC) of the Infocomm Development Authority of Singapore (IDA).</span></span> <span data-ttu-id="25b6d-107">ITSC는 IT 및 통신을 표준화하기 위한 국내 프로그램과 싱가포르의 국제 표준화 활동 참여를 장려하고 지원합니다..</span><span class="sxs-lookup"><span data-stu-id="25b6d-107">The ITSC promotes and facilitates national programs to standardize IT and communications, and Singapore's participation in international standardization activities.</span></span>

<span data-ttu-id="25b6d-108">MTCS의 목적은 다음과 같습니다.</span><span class="sxs-lookup"><span data-stu-id="25b6d-108">The purpose of the MTCS is to provide:</span></span>

- <span data-ttu-id="25b6d-109">클라우드 데이터의 보안 및 기밀성에 대한 일반적인 고객 문제와 클라우드 서비스 사용이 비즈니스에 미치는 영향을 해결하기 위해 CSP(클라우드 서비스 공급자)에서 적용할 수 있는 공통 표준</span><span class="sxs-lookup"><span data-stu-id="25b6d-109">A common standard that cloud service providers (CSPs) can apply to address customer concerns about the security and confidentiality of data in the cloud, and the impact on businesses of using cloud services.</span></span>
- <span data-ttu-id="25b6d-110">고객이 클라우드 서비스 사용 시 접할 수 있는 위험에 대한 가시성과 확인 가능한 운영 투명성</span><span class="sxs-lookup"><span data-stu-id="25b6d-110">Verifiable operational transparency and visibility into risks to the customer when they use cloud services.</span></span>

<span data-ttu-id="25b6d-111">MTCS는 ISO/IEC 27001 같은 인정받는 국제 표준에 기초하며, 데이터 보존, 데이터 자주권, 데이터 이동성, 책임, 가용성, 비즈니스 연속성, 재해 복구 및 인시던트 관리 등 여러 부분을 포함합니다.</span><span class="sxs-lookup"><span data-stu-id="25b6d-111">The MTCS builds upon recognized international standards such as ISO/IEC 27001, and covers such areas as data retention, data sovereignty, data portability, liability, availability, business continuity, disaster recovery, and incident management.</span></span> <span data-ttu-id="25b6d-112">또한 고객이 최소한의 기본 보안 요구 사항에 따라 CSP의 역량을 벤치마킹하고 순위를 매길 수 있는 메커니즘도 포함되어 있습니다.</span><span class="sxs-lookup"><span data-stu-id="25b6d-112">It also includes a mechanism for customers to benchmark and rank the capabilities of CSPs against a set of minimum baseline security requirements.</span></span>

<span data-ttu-id="25b6d-113">MTCS는 다양한 심각도 수준이 적용된 최초의 클라우드 보안 표준이므로 인증된 CSP는 제공되는 다양한 수준을 지정할 수 있습니다.</span><span class="sxs-lookup"><span data-stu-id="25b6d-113">MTCS is the first cloud security standard with different levels of security, so certified CSPs can specify which levels they offer.</span></span> <span data-ttu-id="25b6d-114">MTCS에는 기본 보안을 제공하는 수준 1, 보다 엄격한 관리 및 테넌트 제어를 제공하는 수준 2, 그리고 강력한 정보 시스템에 대해 안정성과 복원성을 제공하는 수준 3으로 나뉜 총 535개의 통제 사항이 포함되어 있습니다.</span><span class="sxs-lookup"><span data-stu-id="25b6d-114">MTCS includes a total of 535 controls, covering basic security in Level 1, more stringent governance and tenancy controls in Level 2, and reliability and resiliency for high-impact information systems in Level 3.</span></span>

## <a name="microsoft-and-mtcs"></a><span data-ttu-id="25b6d-115">Microsoft 및 MTCS</span><span class="sxs-lookup"><span data-stu-id="25b6d-115">Microsoft and MTCS</span></span>

<span data-ttu-id="25b6d-116">Microsoft 클라우드 서비스는 MTCS 인증 주체에 의해 엄격한 평가를 거친 후 IaaS(서비스형 인프라), PaaS(서비스형 플랫폼) 및 SaaS(서비스형 소프트웨어)라는 세 가지 서비스 범주에 대해 MTCS 584:2013 인증을 취득했습니다.</span><span class="sxs-lookup"><span data-stu-id="25b6d-116">After rigorous assessments conducted by the MTCS Certification Body, Microsoft cloud services received MTCS 584:2013 certification across all three service classifications — Infrastructure as a Service (IaaS), Platform as a Service (PaaS), and Software as a Service (SaaS).</span></span> <span data-ttu-id="25b6d-117">Microsoft는 세 가지 범주 모두에서 이 인증을 획득한 최초의 글로벌 CSP입니다.</span><span class="sxs-lookup"><span data-stu-id="25b6d-117">Microsoft was the first global CSP to receive this certification across all three classifications.</span></span>

<span data-ttu-id="25b6d-118">Microsoft Azure 서비스 (IaaS 및 PaaS), Microsoft Dynamics 365 서비스 (SaaS) 및 Microsoft Office 365 서비스 (SaaS)에 대해 수준 3의 인증을 받았습니다.</span><span class="sxs-lookup"><span data-stu-id="25b6d-118">Certifications were granted at Level 3 for Microsoft Azure services (IaaS and PaaS), Microsoft Dynamics 365 services (SaaS), and Microsoft Office 365 services (SaaS).</span></span> <span data-ttu-id="25b6d-119">수준 3 인증은 범위 내 Microsoft 클라우드 서비스가 가장 엄격한 보안 요구 사항을 준수해야 하는 규제 조직에 대해 영향도가 높은 데이터를 호스팅할 수 있음을 의미합니다.</span><span class="sxs-lookup"><span data-stu-id="25b6d-119">A Level 3 certification means that in-scope Microsoft cloud services can host high-impact data for regulated organizations with the strictest security requirements.</span></span> <span data-ttu-id="25b6d-120">싱가포르 정부는 특정 클라우드 솔루션의 구현에 이 수준을 요구하고 있습니다.</span><span class="sxs-lookup"><span data-stu-id="25b6d-120">It's required for certain cloud solution implementations by the Singapore government.</span></span>

## <a name="microsoft-in-scope-cloud-services"></a><span data-ttu-id="25b6d-121">Microsoft 범위 내 클라우드 서비스</span><span class="sxs-lookup"><span data-stu-id="25b6d-121">Microsoft in-scope cloud services</span></span>

- [<span data-ttu-id="25b6d-122">Azure</span><span class="sxs-lookup"><span data-stu-id="25b6d-122">Azure</span></span>](https://go.microsoft.com/fwlink/p/?linkid=2092718)
- [<span data-ttu-id="25b6d-123">Dynamics 365</span><span class="sxs-lookup"><span data-stu-id="25b6d-123">Dynamics 365</span></span>](https://go.microsoft.com/fwlink/p/?linkid=2051700)
- <span data-ttu-id="25b6d-124">Microsoft Cloud App Security</span><span class="sxs-lookup"><span data-stu-id="25b6d-124">Microsoft Cloud App Security</span></span>
- <span data-ttu-id="25b6d-125">유전체학</span><span class="sxs-lookup"><span data-stu-id="25b6d-125">Genomics</span></span>
- <span data-ttu-id="25b6d-126">Microsoft Graph</span><span class="sxs-lookup"><span data-stu-id="25b6d-126">Microsoft Graph</span></span>
- <span data-ttu-id="25b6d-127">Microsoft Healthcare Bot</span><span class="sxs-lookup"><span data-stu-id="25b6d-127">Microsoft Healthcare Bot</span></span>
- <span data-ttu-id="25b6d-128">Intune</span><span class="sxs-lookup"><span data-stu-id="25b6d-128">Intune</span></span>
- <span data-ttu-id="25b6d-129">Flow</span><span class="sxs-lookup"><span data-stu-id="25b6d-129">Flow</span></span>
- <span data-ttu-id="25b6d-130">OMS 서비스 맵</span><span class="sxs-lookup"><span data-stu-id="25b6d-130">OMS Service Map</span></span>
- <span data-ttu-id="25b6d-131">PowerApps</span><span class="sxs-lookup"><span data-stu-id="25b6d-131">PowerApps</span></span>
- <span data-ttu-id="25b6d-132">Power BI</span><span class="sxs-lookup"><span data-stu-id="25b6d-132">Power BI</span></span>
- <span data-ttu-id="25b6d-133">Microsoft Stream</span><span class="sxs-lookup"><span data-stu-id="25b6d-133">Microsoft Stream</span></span>
- [<span data-ttu-id="25b6d-134">Office 365</span><span class="sxs-lookup"><span data-stu-id="25b6d-134">Office 365</span></span>](https://go.microsoft.com/fwlink/p/?LinkID=2077751)

## <a name="audits-reports-and-certificates"></a><span data-ttu-id="25b6d-135">감사, 보고서 및 인증서</span><span class="sxs-lookup"><span data-stu-id="25b6d-135">Audits, reports, and certificates</span></span>

<span data-ttu-id="25b6d-136">인증은 3년간 유효하며, 연례 사후 관리 감사를 실시해야 합니다.</span><span class="sxs-lookup"><span data-stu-id="25b6d-136">Certification is valid for three years, with a yearly surveillance audit to be conducted.</span></span>

### <a name="microsoft-mtcs-certification"></a><span data-ttu-id="25b6d-137">Microsoft MTCS 인증</span><span class="sxs-lookup"><span data-stu-id="25b6d-137">Microsoft MTCS certification</span></span>

- [<span data-ttu-id="25b6d-138">Microsoft Azure 및 기타 온라인 서비스</span><span class="sxs-lookup"><span data-stu-id="25b6d-138">Microsoft Azure and Other Online Services</span></span>](https://go.microsoft.com/fwlink/p/?linkid=2092614)
- [<span data-ttu-id="25b6d-139">Dynamics 365</span><span class="sxs-lookup"><span data-stu-id="25b6d-139">Dynamics 365</span></span>](https://go.microsoft.com/fwlink/p/?linkid=2092451)
- [<span data-ttu-id="25b6d-140">Office 365</span><span class="sxs-lookup"><span data-stu-id="25b6d-140">Office 365</span></span>](https://go.microsoft.com/fwlink/p/?linkid=2092719)

### <a name="microsoft-mtcs-cloud-service-provider-disclosure"></a><span data-ttu-id="25b6d-141">Microsoft MTCS 클라우드 서비스 공급자 공개</span><span class="sxs-lookup"><span data-stu-id="25b6d-141">Microsoft MTCS cloud service provider disclosure</span></span>

- [<span data-ttu-id="25b6d-142">Microsoft Azure 및 기타 온라인 서비스</span><span class="sxs-lookup"><span data-stu-id="25b6d-142">Microsoft Azure and Other Online Services</span></span>](https://go.microsoft.com/fwlink/p/?linkid=2092614)
- [<span data-ttu-id="25b6d-143">Dynamics 365</span><span class="sxs-lookup"><span data-stu-id="25b6d-143">Dynamics 365</span></span>](https://go.microsoft.com/fwlink/p/?linkid=2092720)
- [<span data-ttu-id="25b6d-144">Intune</span><span class="sxs-lookup"><span data-stu-id="25b6d-144">Intune</span></span>](https://go.microsoft.com/fwlink/p/?linkid=2099397)
- [<span data-ttu-id="25b6d-145">Office 365</span><span class="sxs-lookup"><span data-stu-id="25b6d-145">Office 365</span></span>](https://go.microsoft.com/fwlink/p/?linkid=2092550)

## <a name="frequently-asked-questions"></a><span data-ttu-id="25b6d-146">자주하는 질문</span><span class="sxs-lookup"><span data-stu-id="25b6d-146">Frequently asked questions</span></span>

<span data-ttu-id="25b6d-147">**이 표준은 누구에게 적용되나요?**</span><span class="sxs-lookup"><span data-stu-id="25b6d-147">**To whom does the standard apply?**</span></span>

<span data-ttu-id="25b6d-148">MTCS 표준을 준수해야 하는 클라우드 서비스를 구입한 싱가포르 기업에 적용됩니다.</span><span class="sxs-lookup"><span data-stu-id="25b6d-148">It applies to businesses in Singapore that purchase cloud services requiring compliance with the MTCS standard.</span></span>

<span data-ttu-id="25b6d-149">**MTCS 보안 수준 간에는 어떤 차이가 있나요?**</span><span class="sxs-lookup"><span data-stu-id="25b6d-149">**What are the differences between MTCS security levels?**</span></span>

<span data-ttu-id="25b6d-150">MTCS에는 세 가지 보안 수준에 적용되는 총 535개의 통제 사항이 있습니다.</span><span class="sxs-lookup"><span data-stu-id="25b6d-150">MTCS has a total of 535 controls that cover three levels of security:</span></span>

- <span data-ttu-id="25b6d-151">수준 1은 저렴한 비용으로 필요한 최소한의 기본 보안 통제 사항을 포함합니다.</span><span class="sxs-lookup"><span data-stu-id="25b6d-151">Level 1 is low cost, with a minimum number of required baseline security controls.</span></span> <span data-ttu-id="25b6d-152">수준 1은 웹 사이트 호스팅, 테스트 및 개발 작업, 시뮬레이션 및 중요하지 않은 비즈니스 응용 프로그램에 적합합니다.</span><span class="sxs-lookup"><span data-stu-id="25b6d-152">It is suitable for web site hosting, test and development work, simulation, and noncritical business applications.</span></span>
- <span data-ttu-id="25b6d-153">수준 2는 데이터에 대한 보안 위험과 위협을 대상으로 하는 보다 엄격한 통제 수단으로 구성되어, 데이터 보안을 우려하는 대다수 기업의 요구에 알맞습니다.</span><span class="sxs-lookup"><span data-stu-id="25b6d-153">Level 2 addresses the needs of most organizations that are concerned about data security, with a set of more stringent controls targeted at security risks and threats to data.</span></span> <span data-ttu-id="25b6d-154">수준 2는 중요 업무용 비즈니스 응용 프로그램 등 대부분의 클라우드 용도에 적용할 수 있습니다.</span><span class="sxs-lookup"><span data-stu-id="25b6d-154">Level 2 is applicable for most cloud usage, including mission-critical business applications.</span></span>
- <span data-ttu-id="25b6d-155">수준 3은 특정 요구 사항을 가지고 있으며 보다 엄격한 보안 요구 사항을 충족해야 하는 규제 조직을 위한 것입니다.</span><span class="sxs-lookup"><span data-stu-id="25b6d-155">Level 3 is designed for regulated organizations with specific requirements and those willing to pay for stricter security requirements.</span></span> <span data-ttu-id="25b6d-156">몇 가지 보안 통제 사항을 추가하여 수준 3은 수준 1 및 2의 통제를 보완합니다.</span><span class="sxs-lookup"><span data-stu-id="25b6d-156">Level 3 adds a set of security controls to supplement those in Levels 1 and 2.</span></span> <span data-ttu-id="25b6d-157">이는 규제 대상 시스템에서 중요한 정보를 취급하는 응용 프로그램을 호스팅하는 등 클라우드 서비스를 사용하는 강력한 정보 시스템에서 보안 위험 및 위협 문제를 해결해 줍니다.</span><span class="sxs-lookup"><span data-stu-id="25b6d-157">They address security risks and threats in high-impact information systems using cloud services, such as hosting applications with sensitive information and in regulated systems.</span></span>

<span data-ttu-id="25b6d-158">**우리 회사의 자체 규정 준수 활동은 어느 것부터 시작해야 하나요?**</span><span class="sxs-lookup"><span data-stu-id="25b6d-158">**Where do I start with my organization's own compliance effort?**</span></span>

<span data-ttu-id="25b6d-159">[MTCS 인증 체계](https://go.microsoft.com/fwlink/p/?linkid=2099490)는 감사 제어 및 보안 요구 사항에 대한 지침을 담고 있습니다.</span><span class="sxs-lookup"><span data-stu-id="25b6d-159">The [MTCS Certification Scheme](https://go.microsoft.com/fwlink/p/?linkid=2099490) provides guidance on audit controls and security requirements.</span></span>

<span data-ttu-id="25b6d-160">**우리 회사의 인증 프로세스에 Microsoft의 규정 준수를 사용할 수 있나요?**</span><span class="sxs-lookup"><span data-stu-id="25b6d-160">**Can I use Microsoft's compliance in my organization's certification process?**</span></span>

<span data-ttu-id="25b6d-161">예.</span><span class="sxs-lookup"><span data-stu-id="25b6d-161">Yes.</span></span> <span data-ttu-id="25b6d-162">이러한 Microsoft 클라우드 서비스에 기초하여 구축된 서비스를 인증해야 하는 경우 MTCS 인증을 사용하면 IT 인프라에 의존하는 경우 IT 인프라 감사의 영향을 줄일 수 있습니다.</span><span class="sxs-lookup"><span data-stu-id="25b6d-162">If you have a requirement to certify your services built on these Microsoft cloud services, you can use the MTCS certification to reduce the impact of auditing your IT infrastructure, if it relies on them.</span></span> <span data-ttu-id="25b6d-163">하지만 구현에 대한 규정 준수를 평가하기 위한 평가자와의 계약과 고유 조직 내 통제 수단 및 프로세스에 대해서는 파트너가 책임을 져야 합니다.</span><span class="sxs-lookup"><span data-stu-id="25b6d-163">However, you are responsible for engaging an assessor to evaluate your implementation for compliance, and for the controls and processes within your own organization.</span></span>

## <a name="use-microsoft-compliance-manager-to-assess-your-risk"></a><span data-ttu-id="25b6d-164">Microsoft 준수 관리자를 사용하여 위험 평가</span><span class="sxs-lookup"><span data-stu-id="25b6d-164">Use Microsoft Compliance Manager to assess your risk</span></span>

<span data-ttu-id="25b6d-165">[Microsoft 준수 관리자](/microsoft-365/compliance/compliance-manager)는 조직의 준수 입장을 이해하고 위험을 줄이기 위한 조치를 취하도록 돕는 [Microsoft 365 규정 준수 센터](/microsoft-365/compliance/microsoft-365-compliance-center)의 기능입니다.</span><span class="sxs-lookup"><span data-stu-id="25b6d-165">[Microsoft Compliance Manager](/microsoft-365/compliance/compliance-manager) is a feature in the [Microsoft 365 compliance center](/microsoft-365/compliance/microsoft-365-compliance-center) to help you understand your organization's compliance posture and take actions to help reduce risks.</span></span> <span data-ttu-id="25b6d-166">준수 관리자는 이 규제에 대한 평가를 빌드하기 위한 프리미엄 서식 파일을 제공합니다.</span><span class="sxs-lookup"><span data-stu-id="25b6d-166">Compliance Manager offers a premium template for building an assessment for this regulation.</span></span> <span data-ttu-id="25b6d-167">준수 관리자의 **평가 서식 파일** 페이지에서 서식 파일을 찾습니다.</span><span class="sxs-lookup"><span data-stu-id="25b6d-167">Find the template in the **assessment templates** page in Compliance Manager.</span></span> <span data-ttu-id="25b6d-168">[준수 관리자의 평가 빌드](/microsoft-365/compliance/compliance-manager-assessments) 방법에 대해 알아봅니다.</span><span class="sxs-lookup"><span data-stu-id="25b6d-168">Learn how to [build assessments in Compliance Manager](/microsoft-365/compliance/compliance-manager-assessments).</span></span>

## <a name="resources"></a><span data-ttu-id="25b6d-169">리소스</span><span class="sxs-lookup"><span data-stu-id="25b6d-169">Resources</span></span>

- [<span data-ttu-id="25b6d-170">MTCS 인증 체계</span><span class="sxs-lookup"><span data-stu-id="25b6d-170">MTCS Certification Scheme</span></span>](https://go.microsoft.com/fwlink/p/?linkid=2092918)
- [<span data-ttu-id="25b6d-171">싱가포르 보안 및 개인 정보 요구 사항 컨텍스트의 Azure 준수</span><span class="sxs-lookup"><span data-stu-id="25b6d-171">Azure compliance in the context of Singapore security and privacy requirements</span></span>](https://aka.ms/azurecompliancesingapore)
- [<span data-ttu-id="25b6d-172">Microsoft 온라인 서비스 사용 약관</span><span class="sxs-lookup"><span data-stu-id="25b6d-172">Microsoft Online Services Terms</span></span>](https://aka.ms/Online-Services-Terms)
- [<span data-ttu-id="25b6d-173">Microsoft 보안 센터에 대한 규정 준수</span><span class="sxs-lookup"><span data-stu-id="25b6d-173">Compliance on the Microsoft Trust Center</span></span>](https://www.microsoft.com/trust-center/compliance/compliance-overview)
