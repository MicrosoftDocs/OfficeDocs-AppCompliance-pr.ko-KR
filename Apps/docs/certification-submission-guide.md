---
ms.author: oromalle
title: Microsoft 365 인증 제출 가이드
author: orionomalley
description: Microsoft 365 인증 제출 가이드 세분화 보기
keywords: 앱 인증 팀 Microsoft 365 준수 m365
ms.topic: conceptual
ms.service: attestation
ms.openlocfilehash: dd3a61b6b9768c278cd7d48dd88847ea9ee56421
ms.sourcegitcommit: 78dbace87a9b5027ea5aa23a6be9b8c613bd06ce
ms.translationtype: MT
ms.contentlocale: ko-KR
ms.lasthandoff: 07/07/2021
ms.locfileid: "53315128"
---
# <a name="microsoft-365-certification-submission-guide"></a><span data-ttu-id="7840e-104">Microsoft 365 인증 제출 가이드</span><span class="sxs-lookup"><span data-stu-id="7840e-104">Microsoft 365 Certification Submission Guide</span></span>

<span data-ttu-id="7840e-105">**이 문서에서는:**</span><span class="sxs-lookup"><span data-stu-id="7840e-105">**In this article:**</span></span>
- [<span data-ttu-id="7840e-106">소개</span><span class="sxs-lookup"><span data-stu-id="7840e-106">Introduction</span></span>](#introduction)
- [<span data-ttu-id="7840e-107">필수 구성 요소</span><span class="sxs-lookup"><span data-stu-id="7840e-107">Prerequisites</span></span>](#prerequisites) 
- [<span data-ttu-id="7840e-108">Microsoft 365 인증 사양 업데이트</span><span class="sxs-lookup"><span data-stu-id="7840e-108">Microsoft 365 Certification Specification Updates</span></span>](#microsoft-365-certification-specification-updates)
- [<span data-ttu-id="7840e-109">인증 범위</span><span class="sxs-lookup"><span data-stu-id="7840e-109">Certification Scope</span></span>](#certification-scope)
- [<span data-ttu-id="7840e-110">인증 프로세스</span><span class="sxs-lookup"><span data-stu-id="7840e-110">Certification Process</span></span>](#certification-process)
- [<span data-ttu-id="7840e-111">초기 문서 제출</span><span class="sxs-lookup"><span data-stu-id="7840e-111">Initial Document submission</span></span>](#initial-document-submission) 
- [<span data-ttu-id="7840e-112">증거 수집 및 평가 활동</span><span class="sxs-lookup"><span data-stu-id="7840e-112">Evidence Collection and Assessment Activities</span></span>](#evidence-collection-and-assessment-activities)
- [<span data-ttu-id="7840e-113">인증 기준</span><span class="sxs-lookup"><span data-stu-id="7840e-113">Certification Criteria</span></span>](#app-certification-criteria)
- [<span data-ttu-id="7840e-114">Application Security</span><span class="sxs-lookup"><span data-stu-id="7840e-114">Application Security</span></span>](#application-security)
- [<span data-ttu-id="7840e-115">운영 보안</span><span class="sxs-lookup"><span data-stu-id="7840e-115">Operational Security</span></span>](#operational-security) 
- [<span data-ttu-id="7840e-116">데이터 처리 보안 및 개인 정보</span><span class="sxs-lookup"><span data-stu-id="7840e-116">Data Handling Security and Privacy</span></span>](#data-handling-security-and-privacy)
- [<span data-ttu-id="7840e-117">선택적 외부 준수 프레임워크 검토</span><span class="sxs-lookup"><span data-stu-id="7840e-117">Optional External Compliance Frameworks Review</span></span>](#optional-external-compliance-frameworks-review)
- [<span data-ttu-id="7840e-118">부록 A</span><span class="sxs-lookup"><span data-stu-id="7840e-118">Appendix A</span></span>](#appendix-a)
- [<span data-ttu-id="7840e-119">부록 B</span><span class="sxs-lookup"><span data-stu-id="7840e-119">Appendix B</span></span>](#appendix-b) 
- [<span data-ttu-id="7840e-120">부록 C</span><span class="sxs-lookup"><span data-stu-id="7840e-120">Appendix C</span></span>](#appendix-c) 
- [<span data-ttu-id="7840e-121">부록 D</span><span class="sxs-lookup"><span data-stu-id="7840e-121">Appendix D</span></span>](#appendix-d) 
- [<span data-ttu-id="7840e-122">부록 E</span><span class="sxs-lookup"><span data-stu-id="7840e-122">Appendix E</span></span>](#appendix-e) 
- [<span data-ttu-id="7840e-123">부록 F</span><span class="sxs-lookup"><span data-stu-id="7840e-123">Appendix F</span></span>](#appendix-f) 
- [<span data-ttu-id="7840e-124">부록 G </span><span class="sxs-lookup"><span data-stu-id="7840e-124">Appendix G </span></span>](#appendix-g)
- [<span data-ttu-id="7840e-125">자세한 정보</span><span class="sxs-lookup"><span data-stu-id="7840e-125">Learn more</span></span>](#learn-more) 
- [<span data-ttu-id="7840e-126">용어</span><span class="sxs-lookup"><span data-stu-id="7840e-126">Glossary</span></span>](#glossary) 


## <a name="introduction"></a><span data-ttu-id="7840e-127">소개</span><span class="sxs-lookup"><span data-stu-id="7840e-127">Introduction</span></span>

<span data-ttu-id="7840e-128">Microsoft 365 앱 준수 프로그램의 일부인 Microsoft 365 인증은 타사 개발자 앱/추가 기능을 Microsoft 365 플랫폼에 통합할 때 데이터 및 개인 정보 보호가 적절하게 보호되는 보증과 확신을 기업 조직에 제공합니다.</span><span class="sxs-lookup"><span data-stu-id="7840e-128">Part of the Microsoft 365 App Compliance program, the Microsoft 365 Certification offers assurance and confidence to enterprise organizations that data and privacy are adequately secured and protected when integrating third-party developer apps/add-ins into the Microsoft 365 platform.</span></span> <span data-ttu-id="7840e-129">유효성 검사를 통과하는 응용 프로그램 및  추가 기능을 Microsoft 365 에코시스템 전체에서 Microsoft 365 지정됩니다.</span><span class="sxs-lookup"><span data-stu-id="7840e-129">Applications and add-ins that pass validation will be designated **Microsoft 365 Certified** throughout the Microsoft 365 ecosystem.</span></span> 

<span data-ttu-id="7840e-130">Microsoft 365 인증 프로그램에 참여하면 귀하는 이러한 추가 약관에 동의하고 Microsoft Corporation과의 Microsoft 365 인증 프로그램에 참여하는 데 적용되는 모든 관련 설명서("Microsoft", "microsoft", "당사" 또는 "당사")를 준수합니다.</span><span class="sxs-lookup"><span data-stu-id="7840e-130">By participating in the Microsoft 365 Certification  program, you are agreeing to these supplemental terms and to comply with any accompanying documentation that applies to your participation in the Microsoft 365 Certification program with Microsoft Corporation ("Microsoft", "we", "us",  or "our").</span></span> <span data-ttu-id="7840e-131">귀하는 귀하는 해당되는 경우, Microsoft 365 회사 및/또는 기타 엔터티를 대신하여 이러한 Microsoft 365 인증 보조 약관에 동의할 권한이 있는 것으로 표현하고 저희에게 경고합니다.</span><span class="sxs-lookup"><span data-stu-id="7840e-131">You represent and warrant to us that you have the authority to accept these Microsoft 365 Certification supplemental terms on behalf of yourself, a company, and/or other entity, as applicable.</span></span> <span data-ttu-id="7840e-132">당사는 이러한 추가 약관을 변경, 수정 또는 종료할 수 있습니다.</span><span class="sxs-lookup"><span data-stu-id="7840e-132">We may change, amend or terminate these supplemental terms at any time.</span></span> <span data-ttu-id="7840e-133">변경 또는 수정 후 Microsoft 365 인증 프로그램에 계속 참여하면 새로운 추가 약관에 동의하는 것입니다.</span><span class="sxs-lookup"><span data-stu-id="7840e-133">Your continued participation in the Microsoft 365 Certification program after any change or amendment means you agree to the new supplemental terms.</span></span> <span data-ttu-id="7840e-134">새 추가 약관에 동의하지 않는 경우 또는 이러한 추가 약관을 종료하는 경우 Microsoft 365 프로그램 참여를 중지해야 합니다.</span><span class="sxs-lookup"><span data-stu-id="7840e-134">If you do not agree to the new supplemental terms or if we terminate these supplemental terms, you must stop participating in the Microsoft 365 Certification program.</span></span>

<span data-ttu-id="7840e-135">이 문서는 ISV(Independent Software Vendor)에서 Microsoft 365 인증 프로세스, 프로세스 시작을 위한 선행 요구 사항 및 ISV에 있어야 하는 특정 보안 제어에 대한 세부 정보를 제공하기 위한 것입니다.</span><span class="sxs-lookup"><span data-stu-id="7840e-135">This document is aimed at ISVs (Independent Software Vendors) to provide information on the Microsoft 365 Certification process, prerequisites to starting the process and details of specific security controls that ISVs must have in place.</span></span>  <span data-ttu-id="7840e-136">앱 준수 Microsoft 365 대한 일반 정보는 앱 준수 Microsoft 365 페이지에서 찾을 수 [있습니다.](https://docs.microsoft.com/microsoft-365-app-certification/overview)</span><span class="sxs-lookup"><span data-stu-id="7840e-136">General information of the Microsoft 365 App Compliance program can be found under the Microsoft 365 App Compliance program [page](https://docs.microsoft.com/microsoft-365-app-certification/overview).</span></span> 

> [!IMPORTANT]
> <span data-ttu-id="7840e-137">현재는 Microsoft 365 인증이 모든 기관에 적용될 수 있습니다.</span><span class="sxs-lookup"><span data-stu-id="7840e-137">Currently, Microsoft 365 Certification is applicable to all:</span></span>
>* <span data-ttu-id="7840e-138">Microsoft Teams 응용 프로그램(Tabs, Bots 등)입니다.</span><span class="sxs-lookup"><span data-stu-id="7840e-138">Microsoft Teams applications (Tabs, Bots, etc.) .</span></span>
>* <span data-ttu-id="7840e-139">Sharepoint 앱/추가 기능</span><span class="sxs-lookup"><span data-stu-id="7840e-139">Sharepoint Apps/Add-ins</span></span>
>* <span data-ttu-id="7840e-140">Office 추가 기능(Word, Excel, PowerPoint, Outlook, Project, OneNote)</span><span class="sxs-lookup"><span data-stu-id="7840e-140">Office Add-ins (Word, Excel, PowerPoint, Outlook, Project, OneNote)</span></span>
>* <span data-ttu-id="7840e-141">WebApps</span><span class="sxs-lookup"><span data-stu-id="7840e-141">WebApps</span></span>

## <a name="prerequisites"></a><span data-ttu-id="7840e-142">필수 구성 요소</span><span class="sxs-lookup"><span data-stu-id="7840e-142">Prerequisites</span></span>

### <a name="publisher-attestation"></a><span data-ttu-id="7840e-143">게시자 증명</span><span class="sxs-lookup"><span data-stu-id="7840e-143">Publisher Attestation</span></span>

<span data-ttu-id="7840e-144">인증 Microsoft 365 자격 증명을 Publisher 완료해야 합니다.</span><span class="sxs-lookup"><span data-stu-id="7840e-144">Before being awarded the Microsoft 365 Certification process you must have completed Publisher Attestation.</span></span> <span data-ttu-id="7840e-145">그러나 Microsoft 365 증명을 완료하기 전에 Publisher 수 있습니다.</span><span class="sxs-lookup"><span data-stu-id="7840e-145">However, you may start the Microsoft 365 Certification process prior to completing Publisher Attestation.</span></span>  

### <a name="read-the-microsoft-365-certification-specification"></a><span data-ttu-id="7840e-146">인증 Microsoft 365 읽기</span><span class="sxs-lookup"><span data-stu-id="7840e-146">Read the Microsoft 365 Certification Specification</span></span>

<span data-ttu-id="7840e-147">모든 ISV(독립 소프트웨어 공급업체)는 이 Microsoft 365 인증 사양을 모두 읽어 범위 내 환경 및 앱/추가 기능을 통해 적용 가능한 모든 컨트롤이 충족되도록 하는 것이 좋습니다.</span><span class="sxs-lookup"><span data-stu-id="7840e-147">Microsoft recommends all ISVs (Independent Software Vendor) to read this Microsoft 365 Certification Specification in its entirety to ensure all applicable controls are being met by the in-scope environment and the app/add-in.</span></span> <span data-ttu-id="7840e-148">이렇게 하면 원활한 평가 프로세스를 보장하는 데 도움이 됩니다.</span><span class="sxs-lookup"><span data-stu-id="7840e-148">This will help ensure a smooth assessment process.</span></span>

## <a name="microsoft-365-certification-specification-updates"></a><span data-ttu-id="7840e-149">Microsoft 365 인증 사양 업데이트</span><span class="sxs-lookup"><span data-stu-id="7840e-149">Microsoft 365 Certification Specification Updates</span></span> 

<span data-ttu-id="7840e-150">Microsoft 365 인증 사양에 대한 업데이트는 약 6~12개월마다 예상됩니다.</span><span class="sxs-lookup"><span data-stu-id="7840e-150">Updates to the Microsoft 365 Certification specification are anticipated approximately every six to twelve months.</span></span> <span data-ttu-id="7840e-151">이러한 업데이트는 새로운 대상 보안 도메인 및/또는 보안 제어를 도입할 수 있습니다.</span><span class="sxs-lookup"><span data-stu-id="7840e-151">These updates might introduce new target security domains and / or security controls.</span></span> <span data-ttu-id="7840e-152">업데이트는 개발자 피드백, 위협 환경 변경을 기반으로 하여 프로그램의 보안 기준이 완성될 때 증가합니다.</span><span class="sxs-lookup"><span data-stu-id="7840e-152">Updates will be based on developer feedback, changes to the threat landscape, and to increase the security baseline of the program as it matures.</span></span> 

<span data-ttu-id="7840e-153">이미 Microsoft 365 인증 평가를 시작한 ISV는 평가가 시작될 때 유효한 Microsoft 365 인증 사양 버전으로 평가를 계속할 수 있습니다.</span><span class="sxs-lookup"><span data-stu-id="7840e-153">ISVs that have already started the Microsoft 365 Certification assessment can continue the assessment with the version of the Microsoft 365 Certification Specification that was valid when the assessment was started.</span></span> <span data-ttu-id="7840e-154">연간 재인증을 비롯한 모든 새 제출은 게시된 버전에 대해 평가해야 합니다.</span><span class="sxs-lookup"><span data-stu-id="7840e-154">All new submissions, including annual recertification, will be required to be assessed against the version published.</span></span>

> [!NOTE]
> <span data-ttu-id="7840e-155">인증을 획득하기 위해 이 Microsoft 365 내의 모든 컨트롤을 준수할 필요는 없습니다.</span><span class="sxs-lookup"><span data-stu-id="7840e-155">You are not required to comply with all the controls within this Microsoft 365 Certification Specification to be awarded a certification.</span></span> <span data-ttu-id="7840e-156">그러나 이 인증 사양에서 설명하는 각 보안 도메인에 대해 전달 임계값(공개되지 않을)Microsoft 365 있습니다.</span><span class="sxs-lookup"><span data-stu-id="7840e-156">However, passing thresholds (which will not be disclosed) are in place for each of the security domains discussed within this Microsoft 365 Certification Specification.</span></span> <span data-ttu-id="7840e-157">일부 컨트롤은 **'하드** 실패'로 분류됩니다. 즉, 이러한 보안 컨트롤이 부족하면 평가에 실패하게 됩니다.</span><span class="sxs-lookup"><span data-stu-id="7840e-157">Some controls will be classed as a ‘**Hard Fail**’ which means the lack of these security controls will result in a failed assessment.</span></span> 

## <a name="certification-scope"></a><span data-ttu-id="7840e-158">인증 범위</span><span class="sxs-lookup"><span data-stu-id="7840e-158">Certification Scope</span></span>

<span data-ttu-id="7840e-159">범위 **내** 환경은 앱/추가 기능 코드 배달을 지원하고 앱/추가 기능과 통신할 수 있는 모든 백end 시스템을 지원하는 환경입니다.</span><span class="sxs-lookup"><span data-stu-id="7840e-159">The **in-scope environment** is the environment that supports delivery of the app/add-in code and supports any backend systems that the app/add-in may be communicating with.</span></span> <span data-ttu-id="7840e-160">적절한 세분화가 이행되고 연결된 환경이 범위 내 환경의 보안에 영향을 줄 수 없는 경우를 위해 추가 연결된 환경도 범위에 포함됩니다.</span><span class="sxs-lookup"><span data-stu-id="7840e-160">Any additional connected-to environments will also be included in scope unless adequate segmentation is in place AND the connected-to environments cannot impact the security of the in-scope environment.</span></span> <span data-ttu-id="7840e-161">또한 기본 환경에 모든 일이 발생하면 서비스를 이행하는 데 이러한 환경이 필요하기 때문에 재해 복구 환경도 평가 범위 내에 포함해야 합니다.</span><span class="sxs-lookup"><span data-stu-id="7840e-161">Any disaster recovery environments will also need to be included within the scope of the assessment as these environments would be required to fulfil the service should anything happen to the primary environment.</span></span>  <span data-ttu-id="7840e-162">범위 내 **시스템 구성 요소 용어는** 범위 내 환경에서 사용되는 모든 장치 및   시스템을 참조합니다. </span><span class="sxs-lookup"><span data-stu-id="7840e-162">The term  **in-scope system components** reference **ALL** devices and systems that are used within the in-scope environment.</span></span> <span data-ttu-id="7840e-163">범위 내 구성 요소에는 다음이 포함됩니다.</span><span class="sxs-lookup"><span data-stu-id="7840e-163">In-scope components include, but are not limited to:</span></span>
* <span data-ttu-id="7840e-164">웹 응용 프로그램.</span><span class="sxs-lookup"><span data-stu-id="7840e-164">The web application(s).</span></span>
* <span data-ttu-id="7840e-165">서버.</span><span class="sxs-lookup"><span data-stu-id="7840e-165">Servers.</span></span>
* <span data-ttu-id="7840e-166">방화벽(또는 그에 상응하는 방화벽)</span><span class="sxs-lookup"><span data-stu-id="7840e-166">Firewalls (or equivalent).</span></span>
* <span data-ttu-id="7840e-167">스위치.</span><span class="sxs-lookup"><span data-stu-id="7840e-167">Switches.</span></span>
* <span data-ttu-id="7840e-168">부하를 균형 조정합니다.</span><span class="sxs-lookup"><span data-stu-id="7840e-168">Load balancers.</span></span>
* <span data-ttu-id="7840e-169">가상 인프라.</span><span class="sxs-lookup"><span data-stu-id="7840e-169">Virtual infrastructure.</span></span>
* <span data-ttu-id="7840e-170">클라우드 공급자 웹 관리 포털</span><span class="sxs-lookup"><span data-stu-id="7840e-170">Cloud provider web management portals</span></span> 

> [!IMPORTANT]
> <span data-ttu-id="7840e-171">범위 내 환경에는 DMZ가 있어야 합니다. 앱/추가 기능의 지원 환경은 내부 비즈니스 시스템 및 회사 환경에서 분할해야 따라서 평가 작업의 범위를 범위 내 시스템으로만 제한할 수 있습니다.</span><span class="sxs-lookup"><span data-stu-id="7840e-171">The in-scope environment, must have a DMZ and the supporting environment of the app/add-in must be segmented from the internal business systems and corporate environments thus limiting the scope of the assessment activities to the in-scope systems only.</span></span> <span data-ttu-id="7840e-172">인증 분석가가 평가하는 동안 분할 기술의 유효성을 검사하고 사용 중의 모든 분할 기술의 유효성을 검사하기 위한 테스트를 포함해야 하는 침투 테스트 보고서를 검토합니다.</span><span class="sxs-lookup"><span data-stu-id="7840e-172">Certification analysts will validate segmentation techniques during the assessment along with reviewing penetration testing reports which should have included testing to validate the effectiveness of any segmentation techniques in use.</span></span>

### <a name="infrastructure-as-a-service-iaas-platform-as-a-service-paas-and-software-as-a-service-saas"></a><span data-ttu-id="7840e-173">IaaS(Infrastructure as a Service), PaaS(Platform as a Service) 및 SaaS(Software as a Service)</span><span class="sxs-lookup"><span data-stu-id="7840e-173">Infrastructure as a Service (IaaS), Platform as a Service (PaaS) and Software as a Service (SaaS)</span></span> 
<span data-ttu-id="7840e-174">IaaS 및/또는 PaaS가 검토에 따라 응용 프로그램 또는 추가 기능 코드 배달의 인프라를 지원하는 데 사용되는 경우 클라우드 플랫폼 공급자는 인증 프로세스 전체에서 평가되는 일부 보안 컨트롤을 담당합니다.</span><span class="sxs-lookup"><span data-stu-id="7840e-174">Where IaaS and/or PaaS is used to support the infrastructure of the application or add-in code delivery under review, the Cloud platform provider will be responsible for some of the security controls assessed throughout the certification process.</span></span> <span data-ttu-id="7840e-175">따라서 [PCI DSS](bookmark://pci-dss)   준수 증명(AOC), ISO27001 또는 [SOC 2](bookmark://soc-2)유형 II 보고서와 같은 외부 규정 준수 보고서를 통해 클라우드 플랫폼 공급자가 보안 모범 사례에 대한 독립적인 외부 확인을 통해 인증 분석가를 제공해야   합니다.</span><span class="sxs-lookup"><span data-stu-id="7840e-175">Therefore, certification analysts will need to be provided with independent external verification of security best practices by the Cloud platform provider through external compliance reports such as [PCI DSS](bookmark://pci-dss) Attestation of Compliance (AOC), ISO27001 or [SOC 2](bookmark://soc-2) Type II reports.</span></span> 

<span data-ttu-id="7840e-176">부록 F는 다음 배포 유형 및 앱/추가 기능에서 M365 데이터를 유출하는지 여부에 따라 적용 가능한 보안 컨트롤에 대한 세부 정보를 제공합니다.</span><span class="sxs-lookup"><span data-stu-id="7840e-176">Appendix F provides details of what security controls will likely be applicable based on the following deployment types and based upon whether the app/add-in exfiltrates M365 data or not:</span></span> 
* <span data-ttu-id="7840e-177">ISV Hosted</span><span class="sxs-lookup"><span data-stu-id="7840e-177">ISV Hosted</span></span> 
* <span data-ttu-id="7840e-178">IaaS 호스트</span><span class="sxs-lookup"><span data-stu-id="7840e-178">IaaS Hosted</span></span> 
* <span data-ttu-id="7840e-179">PaaS/Serverless Hosted</span><span class="sxs-lookup"><span data-stu-id="7840e-179">PaaS/Serverless Hosted</span></span> 
* <span data-ttu-id="7840e-180">하이브리드 호스트</span><span class="sxs-lookup"><span data-stu-id="7840e-180">Hybrid Hosted</span></span> 
* <span data-ttu-id="7840e-181">공유 호스트</span><span class="sxs-lookup"><span data-stu-id="7840e-181">Shared Hosted</span></span> 

<span data-ttu-id="7840e-182">IaaS 또는 PaaS가 배포되는 경우 이러한 배포 유형 내에서 호스팅되는 환경의 증거를 제공해야 합니다.</span><span class="sxs-lookup"><span data-stu-id="7840e-182">Where IaaS or PaaS is deployed, you will need to provide evidence of the environment being hosted within these deployment types.</span></span>

### <a name="sampling"></a><span data-ttu-id="7840e-183">샘플링</span><span class="sxs-lookup"><span data-stu-id="7840e-183">Sampling</span></span>

<span data-ttu-id="7840e-184">인증 평가 지원에 대한 증거 요청은 다양한 운영 체제, 장치의 기본 기능 및 다양한 장치 유형을 고려하여 범위 내 시스템 구성 요소의 샘플을 기반으로 해야 합니다.</span><span class="sxs-lookup"><span data-stu-id="7840e-184">Requests for evidence in support of the certification assessment should be based on a sample of the in-scope system components in consideration of different operating systems, primary function of the device, and different device types.</span></span> <span data-ttu-id="7840e-185">인증 프로세스가 시작될 때 적합한 샘플이 선택됩니다.</span><span class="sxs-lookup"><span data-stu-id="7840e-185">A suitable sample will be selected at the start of the certification process.</span></span> <span data-ttu-id="7840e-186">다음 표는 샘플 크기가 어떻게 될 수 있는가에 대한 지침으로 사용해야 합니다.</span><span class="sxs-lookup"><span data-stu-id="7840e-186">The following table should be used as a guide on what the sample size may be:</span></span>

|<span data-ttu-id="7840e-187">인구 크기</span><span class="sxs-lookup"><span data-stu-id="7840e-187">Population Size</span></span>              | <span data-ttu-id="7840e-188">샘플</span><span class="sxs-lookup"><span data-stu-id="7840e-188">Sample</span></span>                  |
|---------------------------- |-------------------------|
|<span data-ttu-id="7840e-189"><5</span><span class="sxs-lookup"><span data-stu-id="7840e-189"><5</span></span>|<span data-ttu-id="7840e-190">1 </span><span class="sxs-lookup"><span data-stu-id="7840e-190">1</span></span>|
|<span data-ttu-id="7840e-191">>5 & <10</span><span class="sxs-lookup"><span data-stu-id="7840e-191">>5 & <10</span></span>|<span data-ttu-id="7840e-192">2 </span><span class="sxs-lookup"><span data-stu-id="7840e-192">2</span></span>|
|<span data-ttu-id="7840e-193">>9 & <25</span><span class="sxs-lookup"><span data-stu-id="7840e-193">>9 & <25</span></span>|<span data-ttu-id="7840e-194">3 </span><span class="sxs-lookup"><span data-stu-id="7840e-194">3</span></span>|
|<span data-ttu-id="7840e-195">>24</span><span class="sxs-lookup"><span data-stu-id="7840e-195">>24</span></span>|<span data-ttu-id="7840e-196">4 </span><span class="sxs-lookup"><span data-stu-id="7840e-196">4</span></span>|

> [!NOTE]
><span data-ttu-id="7840e-197">초기 샘플에 포함된 장치 간에 불일치가 식별되면 평가 중에 샘플 크기가 증가할 수 있습니다.</span><span class="sxs-lookup"><span data-stu-id="7840e-197">If discrepancies are identified between devices included within the initial sample, the sample size may be increased during the assessment.</span></span> 

## <a name="certification-process"></a><span data-ttu-id="7840e-198">인증 프로세스</span><span class="sxs-lookup"><span data-stu-id="7840e-198">Certification Process</span></span>

<span data-ttu-id="7840e-199">인증 프로세스를 시작하기 전에 인증서 증명을 성공적으로 Publisher 합니다.</span><span class="sxs-lookup"><span data-stu-id="7840e-199">Before starting the certification process, you will need to have successfully scompleted your Publisher Attestation.</span></span> <span data-ttu-id="7840e-200">증명 응답은 인증 Microsoft 365 지원에 사용되어 다음과 같이 진행됩니다.</span><span class="sxs-lookup"><span data-stu-id="7840e-200">Your attestation responses will be used in support of the Microsoft 365 Certification process and proceeds as follows:</span></span>

## <a name="certification-process"></a><span data-ttu-id="7840e-201">인증 프로세스</span><span class="sxs-lookup"><span data-stu-id="7840e-201">Certification Process</span></span>

<span data-ttu-id="7840e-202">인증 프로세스를 시작하기 전에 인증 증명을 Publisher 합니다.</span><span class="sxs-lookup"><span data-stu-id="7840e-202">Before you begin your certification process you will need to have completed the Publisher Attestation.</span></span> <span data-ttu-id="7840e-203">게시자 증명이 승인되면 Microsoft 365 인증에 참여할 수 있는 소개 전자 메일을 받게 됩니다.</span><span class="sxs-lookup"><span data-stu-id="7840e-203">Once your publisher attestation has been approved, you will receive an introductory email inviting you to join Microsoft 365 Certification.</span></span>

### <a name="preparation"></a><span data-ttu-id="7840e-204">준비</span><span class="sxs-lookup"><span data-stu-id="7840e-204">Preparation</span></span>
1. <span data-ttu-id="7840e-205">파트너 센터로 이동하여 완료된 Publisher [문서를 검토합니다.]( https://docs.microsoft.com/microsoft-365-app-certification/docs/attestation)</span><span class="sxs-lookup"><span data-stu-id="7840e-205">Navigate to partner center and review your completed [Publisher Attestation]( https://docs.microsoft.com/microsoft-365-app-certification/docs/attestation) documentation.</span></span> <span data-ttu-id="7840e-206">필요한 경우 응답을 편집하고 업데이트할 수 있습니다. 그러나 이 경우 승인을 위해 의거 문서를 다시 제출해야 합니다.</span><span class="sxs-lookup"><span data-stu-id="7840e-206">If necessary, you can edit and update your responses; however, if you do so, you will need to resubmit your attestation documentation for approval.</span></span> <span data-ttu-id="7840e-207">제출이 3개월보다 오래된 경우 검토 및 유효성 검사를 위해 Publisher 제출해야 합니다.</span><span class="sxs-lookup"><span data-stu-id="7840e-207">If your submission is older than three months, we will require that you resubmit Publisher Attestation for review and validation.</span></span> 
1. <span data-ttu-id="7840e-208">인증 제출 Microsoft 365 [신중하게](https://docs.microsoft.com/microsoft-365-app-certification/docs/certification-submission-guide) 읽어 요구되는 내용을 이해하세요.</span><span class="sxs-lookup"><span data-stu-id="7840e-208">Carefully read through the [Microsoft 365 Certification Submission Guide](https://docs.microsoft.com/microsoft-365-app-certification/docs/certification-submission-guide) to understand what will be required of you.</span></span> <span data-ttu-id="7840e-209">인증 제출 가이드의 인증 []( https://docs.microsoft.com/microsoft-365-app-certification/docs/certification-submission-guide#app-certification-criteria) 제출 가이드에 지정된 제어 Microsoft 365 수 있도록 합니다.</span><span class="sxs-lookup"><span data-stu-id="7840e-209">Ensure that you will be able to fulfill the [control requirements]( https://docs.microsoft.com/microsoft-365-app-certification/docs/certification-submission-guide#app-certification-criteria) specified in the Microsoft 365 Certification Submission Guide.</span></span>
1. <span data-ttu-id="7840e-210">파트너 센터 내에서 "인증 시작"을 클릭합니다.</span><span class="sxs-lookup"><span data-stu-id="7840e-210">Within partner center click “Start Certification”.</span></span> <span data-ttu-id="7840e-211">그러면 초기 문서 제출 포털로 이동됩니다.</span><span class="sxs-lookup"><span data-stu-id="7840e-211">This will bring you to your initial document submission portal.</span></span> <span data-ttu-id="7840e-212">초기 문서 [제출을 제출합니다.](https://docs.microsoft.com/microsoft-365-app-certification/docs/certification-submission-guide#initial-document-submission)</span><span class="sxs-lookup"><span data-stu-id="7840e-212">Submit your [Initial Document Submission](https://docs.microsoft.com/microsoft-365-app-certification/docs/certification-submission-guide#initial-document-submission).</span></span> <span data-ttu-id="7840e-213">이렇게 하면 앱이 설계 및 고객 데이터를 처리하는 방식에 따라 평가 범위 내 범위를 결정하는 데 도움이 됩니다.</span><span class="sxs-lookup"><span data-stu-id="7840e-213">This will help us determine what is in-scope for your assessment based on how your app is architected and handles customer data.</span></span> <span data-ttu-id="7840e-214">제출이 수락된 경우 이 페이지를 자주 확인하십시오.</span><span class="sxs-lookup"><span data-stu-id="7840e-214">Check this page frequently to see if your submission has been accepted.</span></span>

>[!NOTE]
><span data-ttu-id="7840e-215">모든 Office 앱에 대해 Office [앱 사용자 가이드를 참조할 수 있습니다.](https://docs.microsoft.com/microsoft-365-app-certification/docs/userguide)</span><span class="sxs-lookup"><span data-stu-id="7840e-215">For all office apps you can reference our [Office Apps User Guide](https://docs.microsoft.com/microsoft-365-app-certification/docs/userguide).</span></span> <span data-ttu-id="7840e-216">모든 WebApps에 대해 [SaaS](https://docs.microsoft.com/en-us/microsoft-365-app-certification/docs/saasuserguide)앱 사용자 가이드를 참조할 수 있습니다.</span><span class="sxs-lookup"><span data-stu-id="7840e-216">For all WebApps you can reference our [SaaS App User Guide](https://docs.microsoft.com/en-us/microsoft-365-app-certification/docs/saasuserguide).</span></span>

### <a name="assessment"></a><span data-ttu-id="7840e-217">평가</span><span class="sxs-lookup"><span data-stu-id="7840e-217">Assessment</span></span>
1. <span data-ttu-id="7840e-218">초기 문서 제출이 수락되면 앱에 필요한 보안 컨트롤 집합이 포털에 자동으로 표시됩니다.</span><span class="sxs-lookup"><span data-stu-id="7840e-218">Once your initial document submission has been accepted the set of security controls required for your app will be automatically displayed in the portal.</span></span> <span data-ttu-id="7840e-219">그런 다음 컨트롤이 준비 중이라 증명하는 각 컨트롤에 대한 증거를 제출해야 합니다.</span><span class="sxs-lookup"><span data-stu-id="7840e-219">You will then be required to submit evidence for each control demonstrating that the control is in place.</span></span> <span data-ttu-id="7840e-220">모든 증거를 제출할 **수 있는 60일이** 주어졌다는 사실에 유의합니다.</span><span class="sxs-lookup"><span data-stu-id="7840e-220">Keep in mind you will be given **60 days** to submit all evidence.</span></span> <span data-ttu-id="7840e-221">분석가가 증거를 검토하고 제어를 승인하거나 새 증거 또는 추가 증거를 요청합니다.</span><span class="sxs-lookup"><span data-stu-id="7840e-221">An analyst will review your evidence and either approve the control or request new or additional evidence.</span></span> <span data-ttu-id="7840e-222">이 페이지를 자주 확인하여 증거가 수락된지 확인하십시오.</span><span class="sxs-lookup"><span data-stu-id="7840e-222">Check this page frequently to see if your evidence has been accepted.</span></span>
### <a name="certification"></a><span data-ttu-id="7840e-223">인증</span><span class="sxs-lookup"><span data-stu-id="7840e-223">Certification</span></span>
1. <span data-ttu-id="7840e-224">분석가가 제출의 유효성을 검사한 후 인증 결정에 대한 알림을 하게 됩니다.</span><span class="sxs-lookup"><span data-stu-id="7840e-224">Once your submission has been validated by an analyst you will be notified of your certification decision.</span></span> <span data-ttu-id="7840e-225">인증을 받은 앱은 **AppSource** 및 **Microsoft 문서** 페이지 내에서 응용 프로그램에 대한 배지를 받게 됩니다.</span><span class="sxs-lookup"><span data-stu-id="7840e-225">Apps awarded a certification will receive a badge on their application within **AppSource**, and **Microsoft docs** pages.</span></span> <span data-ttu-id="7840e-226">여기에서 인증의 전체 이점에 대해 읽을 수 [있습니다.](https://docs.microsoft.com/microsoft-365-app-certification/docs/enterprise-app-certification-guide#program-benefits)</span><span class="sxs-lookup"><span data-stu-id="7840e-226">You can read about the full benefits of certification [here](https://docs.microsoft.com/microsoft-365-app-certification/docs/enterprise-app-certification-guide#program-benefits).</span></span>

## <a name="review-and-re-certification"></a><span data-ttu-id="7840e-227">검토 및 다시 인증</span><span class="sxs-lookup"><span data-stu-id="7840e-227">Review and Re-certification</span></span>
<span data-ttu-id="7840e-228">응용 프로그램에서 중요한 변경을 [](https://docs.microsoft.com/microsoft-365-app-certification/docs/certification-submission-guide#significant-changes) 진행하는 경우, 알림이 필요합니다.</span><span class="sxs-lookup"><span data-stu-id="7840e-228">In the event that your application undergoes [Significant changes](https://docs.microsoft.com/microsoft-365-app-certification/docs/certification-submission-guide#significant-changes) at any point you will be required to notify us.</span></span>

<span data-ttu-id="7840e-229">또한 매년 재인증을 거치야 합니다.</span><span class="sxs-lookup"><span data-stu-id="7840e-229">You will also be required to go through recertification on an annual basis.</span></span> <span data-ttu-id="7840e-230">이렇게 하면 현재 환경에 대해 범위 내 컨트롤을 다시 확인해야 합니다.</span><span class="sxs-lookup"><span data-stu-id="7840e-230">This will require the revalidation of the in-scope controls against your current environment.</span></span> <span data-ttu-id="7840e-231">이 프로세스는 인증이 만료되기 최대 90일 전에 시작할 수 있습니다.</span><span class="sxs-lookup"><span data-stu-id="7840e-231">This process can begin up to 90 days before the expiration of your certification.</span></span> <span data-ttu-id="7840e-232">기존 인증은 재인증 기간 동안 만료되지 않습니다.</span><span class="sxs-lookup"><span data-stu-id="7840e-232">Your existing certification will not expire during the re-certification period.</span></span> <span data-ttu-id="7840e-233">모든 프로그램에서 다시 인증은 Microsoft 365 1주년 후에 만료됩니다.</span><span class="sxs-lookup"><span data-stu-id="7840e-233">Re-certification across all programs expires on the one-year anniversary of your Microsoft 365 Certification.</span></span>

<span data-ttu-id="7840e-234">만료 날짜 전에 인증이 갱신되지 않은 경우 앱 인증 상태가 해지됩니다.</span><span class="sxs-lookup"><span data-stu-id="7840e-234">If your certification is not renewed before the expiration date, your apps certification status will be revoked.</span></span> <span data-ttu-id="7840e-235">모든 배지, 아이콘 및 관련 인증 브랜드가 앱에서 제거되고 인증된 앱으로 앱을 Microsoft 365 금지됩니다.</span><span class="sxs-lookup"><span data-stu-id="7840e-235">All badging, icons, and associated certification branding will be removed from your app, and you will be prohibited from advertising your app as Microsoft 365 Certified.</span></span>


> [!IMPORTANT]
> <span data-ttu-id="7840e-236">**제출 시간 프레임:** 제출 상태를 자주 확인하고 제시간 내에 의견 및 추가 증거 요청에 응답할 수 있는 경우 평균적으로 평가 프로세스는 30일이 걸릴 것으로 예상됩니다.</span><span class="sxs-lookup"><span data-stu-id="7840e-236">**Submission time frame:** It is anticipated that on average the assessment process should take 30 days, provided you are able to check your submission status frequently and respond to comments and supplemental evidence requests within a timely manner.</span></span> <span data-ttu-id="7840e-237">인증 프로세스를 시작하면 평가를 완료할 수 있는 최대 60일이 허용됩니다.</span><span class="sxs-lookup"><span data-stu-id="7840e-237">Upon starting the certification process, a maximum of 60 days is permitted to complete the assessment.</span></span> <span data-ttu-id="7840e-238">60일 기간 내에 모든 제출이 완료되지 않은 경우 제출에 오류가 발생하고 프로세스가 다시 시작되어야 합니다.</span><span class="sxs-lookup"><span data-stu-id="7840e-238">If all submissions have not been completed within the 60-day time-period, the submission will be issued a failure and the process must start again.</span></span> <span data-ttu-id="7840e-239">이러한 결과는 공개되지 않습니다.</span><span class="sxs-lookup"><span data-stu-id="7840e-239">These results will not be made public.</span></span>


## <a name="initial-document-submission"></a><span data-ttu-id="7840e-240">초기 문서 제출</span><span class="sxs-lookup"><span data-stu-id="7840e-240">Initial Document Submission</span></span>

<span data-ttu-id="7840e-241">초기 문서 제출은 인증 분석가가 범위를 지정하고 평가 범위에 포함되는 대상을 결정하는 데 도움이 됩니다.</span><span class="sxs-lookup"><span data-stu-id="7840e-241">The initial document submission will help certification analysts perform scoping and determine what will be in scope for your assessment.</span></span> <span data-ttu-id="7840e-242">그 이후에는 평가를 수행하기 위해 사용되는 지원 설명서 및 증거를 제출해야 합니다.</span><span class="sxs-lookup"><span data-stu-id="7840e-242">After which you will be required to submit supporting documentation and evidence used to carry out the assessment.</span></span> <span data-ttu-id="7840e-243">초기 제출에는 아래에 지정된 정보가 포함되어야 합니다.</span><span class="sxs-lookup"><span data-stu-id="7840e-243">Your initial submission must include the information specified below:</span></span>

| <span data-ttu-id="7840e-244">**설명서 &nbsp; 개요**</span><span class="sxs-lookup"><span data-stu-id="7840e-244">**Documentation&nbsp;Overview**</span></span>     |   <span data-ttu-id="7840e-245">**설명서 세부 정보**</span><span class="sxs-lookup"><span data-stu-id="7840e-245">**Documentation Details**</span></span>  |
| -------------------------| -----------------------------|
|<span data-ttu-id="7840e-246">**앱/추가 기능 설명**</span><span class="sxs-lookup"><span data-stu-id="7840e-246">**App/Add-in Description**</span></span> | <span data-ttu-id="7840e-247">앱/추가 기능의 목적 및 기능에 대한 설명입니다.</span><span class="sxs-lookup"><span data-stu-id="7840e-247">A description of the app/add-in’s purpose and functionality.</span></span> <span data-ttu-id="7840e-248">이를 통해 인증 분석가가 앱/추가 기능의 작동 방식과 용도를 잘 이해해야 합니다.</span><span class="sxs-lookup"><span data-stu-id="7840e-248">This should provide the certification analyst with a good understanding of how the app/add-in functions and what it is intended use is</span></span>
|<span data-ttu-id="7840e-249">**침투 테스트 보고서**</span><span class="sxs-lookup"><span data-stu-id="7840e-249">**Penetration Testing Report**</span></span> |<span data-ttu-id="7840e-250">지난 12개월 내에 완료된 침투 테스트 보고서입니다.</span><span class="sxs-lookup"><span data-stu-id="7840e-250">A penetration testing report completed within the last 12 months.</span></span> <span data-ttu-id="7840e-251">이 보고서에는 앱/추가 기능의 작동을 지원하는 추가 환경과 함께 앱/추가 배포를 지원하는 환경이 포함되어야 합니다.</span><span class="sxs-lookup"><span data-stu-id="7840e-251">This report must include the environment that supports the deployment of the app/add along with any additional environment that supports the operation of the app/add-in.</span></span> <span data-ttu-id="7840e-252">**참고:** 연간 침투 테스트를 수행하지 않는 경우 인증 프로세스를 통해 수행하게 할 수 있습니다.</span><span class="sxs-lookup"><span data-stu-id="7840e-252">**Note:** if you do not do annual penetration testing, you can elect to have them done through the certification process.</span></span>|
|<span data-ttu-id="7840e-253">**아키텍처 다이어그램**</span><span class="sxs-lookup"><span data-stu-id="7840e-253">**Architecture diagrams**</span></span>|<span data-ttu-id="7840e-254">앱/추가 기능의 지원 인프라에 대한 개략적인 개요를 나타내는 논리 아키텍처 다이어그램입니다.</span><span class="sxs-lookup"><span data-stu-id="7840e-254">A logical architecture diagram representing a high-level overview of your app's / add-in’s supporting infrastructure.</span></span> <span data-ttu-id="7840e-255">여기에는 모든 호스팅 **환경과** 앱/추가 기능을 지원하는 지원 인프라가 포함되어야 합니다.</span><span class="sxs-lookup"><span data-stu-id="7840e-255">This must include **all** hosting environments and supporting infrastructure supporting the app/add-in.</span></span> <span data-ttu-id="7840e-256">이 다이어그램은 인증 분석가가 범위 내의 시스템을 이해하고 샘플링을 결정하는 데 도움이 될 수 있도록 환경 내의 모든 지원 시스템 구성 요소를 표시해야 합니다.</span><span class="sxs-lookup"><span data-stu-id="7840e-256">This diagram MUST depict all the different supporting system components within the environment to help certification analysts understand systems in scope and help to determine sampling.</span></span> <span data-ttu-id="7840e-257">또한 사용되는 호스팅 환경 유형을 표시하십시오. ISV Hosted, IaaS, PaaS 또는 Hybrid.</span><span class="sxs-lookup"><span data-stu-id="7840e-257">Please also indicate what hosting environment type is used; ISV Hosted, IaaS, PaaS, or Hybrid.</span></span> <span data-ttu-id="7840e-258">**참고:** SaaS가 사용되는 경우 환경 내에서 지원 서비스를 제공하는 데 사용되는 다양한 SaaS 서비스를 표시하십시오.</span><span class="sxs-lookup"><span data-stu-id="7840e-258">**Note:** Where SaaS is used, please indicate the various SaaS services that are used to provide the supporting services within the environment.</span></span>|
|<span data-ttu-id="7840e-259">**공용 공간**</span><span class="sxs-lookup"><span data-stu-id="7840e-259">**Public Footprint**</span></span> | <span data-ttu-id="7840e-260">지원 **인프라에서** 사용하는 모든 공용 IP 주소 및 URL에 대한 세부 정보</span><span class="sxs-lookup"><span data-stu-id="7840e-260">Detailing **all** public IP Addresses and URLs used by the supporting infrastructure.</span></span> <span data-ttu-id="7840e-261">사용 범위를 분할하기 위해 적절한 분할을 구현하지 않는 한 환경에 할당된 라우팅 가능한 전체 IP 범위를 포함해야 합니다(적절한 분할 증거가 필요).</span><span class="sxs-lookup"><span data-stu-id="7840e-261">This must include the full routable IP range allocated to the environment unless adequate segmentation has been implemented to split the range in use (adequate evidence of segmentation will be required)</span></span>|
|<span data-ttu-id="7840e-262">**데이터 흐름 다이어그램**</span><span class="sxs-lookup"><span data-stu-id="7840e-262">**Data flow diagrams**</span></span> |<span data-ttu-id="7840e-263">Flow 설명하는 다이어그램을 참조합니다.</span><span class="sxs-lookup"><span data-stu-id="7840e-263">Flow diagrams detailing the following:</span></span>
||<span data-ttu-id="7840e-264">&#x2713; /추가 [기능(EUII](#euii) 및 [OII](#oii) 포함)과 M365 데이터 흐름을 제공합니다.</span><span class="sxs-lookup"><span data-stu-id="7840e-264">&#x2713; M365 Data flows to and from the App / Add-in (including [EUII](#euii) and [OII](#oii) ).</span></span>|
||<span data-ttu-id="7840e-265">&#x2713; 인프라 내에서 M365 데이터 흐름을 구성합니다(해당되는 경우).</span><span class="sxs-lookup"><span data-stu-id="7840e-265">&#x2713; M365 Data flows within the supporting infrastructure(where applicable)</span></span>|
||<span data-ttu-id="7840e-266">&#x2713; 데이터가 저장되는 위치 및 데이터, 외부 타사에 데이터가 전달되는 방법(타사에 대한 세부 정보 포함) 및 개방형/공용 네트워크 및 미사용 데이터를 통해 전송되는 동안 데이터가 보호되는 방법을 강조하는 다이어그램입니다.</span><span class="sxs-lookup"><span data-stu-id="7840e-266">&#x2713; Diagrams highlighting where and what data is stored, how data is passed to external third parties(including details of what third parties) , and how data is protected in transit over open/public networks and at rest.</span></span>|
|<span data-ttu-id="7840e-267">**API 끝점 세부 정보**</span><span class="sxs-lookup"><span data-stu-id="7840e-267">**API Endpoint Details**</span></span>| <span data-ttu-id="7840e-268">앱에서 사용하는 모든 API 끝점의 전체 목록입니다.</span><span class="sxs-lookup"><span data-stu-id="7840e-268">A complete listing of all API Endpoints used by your app.</span></span> <span data-ttu-id="7840e-269">환경 범위를 이해하기 위해 환경 내의 API 끝점 위치를 제공합니다.</span><span class="sxs-lookup"><span data-stu-id="7840e-269">To help understand the environment scope, provide API endpoint locations within your environment.</span></span>                                
|<span data-ttu-id="7840e-270">**Microsoft API 사용 권한**</span><span class="sxs-lookup"><span data-stu-id="7840e-270">**Microsoft API Permissions**</span></span>| <span data-ttu-id="7840e-271">앱/추가  기능이 작동하기 위해 요청되는 사용 권한과 함께 사용되는 모든 Microsoft API와 요청된 사용 권한에 대한 사의를 설명하는 설명서를 제공합니다.</span><span class="sxs-lookup"><span data-stu-id="7840e-271">Provide documentation detailing **ALL** the Microsoft APIs that are used along with what permissions are being requested for the app/add-in to function along with a justification for the requested permissions</span></span>|
|<span data-ttu-id="7840e-272">**데이터 저장소 유형**</span><span class="sxs-lookup"><span data-stu-id="7840e-272">**Data storage types**</span></span> |<span data-ttu-id="7840e-273">설명하는 문서 저장 및 처리:</span><span class="sxs-lookup"><span data-stu-id="7840e-273">Data storage and handling documents describing:</span></span>|
||<span data-ttu-id="7840e-274">&#x2713; M365 데이터 EUII 및 [OII가](#euii) 수신 및 저장되는 범위 [](#oii)</span><span class="sxs-lookup"><span data-stu-id="7840e-274">&#x2713; To what extent is your customers M365 Data [EUII](#euii) and [OII](#oii) is being received and stored</span></span>|
||<span data-ttu-id="7840e-275">&#x2713; 보존 기간입니다.</span><span class="sxs-lookup"><span data-stu-id="7840e-275">&#x2713; The data retention period.</span></span>|
||<span data-ttu-id="7840e-276">&#x2713; M365 데이터가 캡처되는 이유입니다.</span><span class="sxs-lookup"><span data-stu-id="7840e-276">&#x2713; Why the customer M365 Data is being captured.</span></span>|
||<span data-ttu-id="7840e-277">&#x2713; M365 데이터가 저장되는 위치입니다(위에서 제공한 데이터 흐름 다이어그램에 포함해야 합니다).</span><span class="sxs-lookup"><span data-stu-id="7840e-277">&#x2713; Where customer M365 Data is stored (should be included within data flow diagrams supplied above).</span></span>|
|<span data-ttu-id="7840e-278">**준수 확인**</span><span class="sxs-lookup"><span data-stu-id="7840e-278">**Compliance confirmation**</span></span>|<span data-ttu-id="7840e-279">Publisher 제출 내에 포함되거나 인증 컨트롤을 검토할 때 고려할 외부 보안 프레임워크에 대한 Microsoft 365 지원</span><span class="sxs-lookup"><span data-stu-id="7840e-279">Supporting documentation for external security frameworks included within the Publisher Attestation submission or to be considered when reviewing Microsoft 365 Certification controls.</span></span> <span data-ttu-id="7840e-280">현재 다음 세 가지가 지원됩니다.</span><span class="sxs-lookup"><span data-stu-id="7840e-280">Currently, the following three are supported:</span></span>|
||<span data-ttu-id="7840e-281">&#x2713;(AOC)의 [PCI DSS](#pci-dss) Attestation of Compliance(AOC)</span><span class="sxs-lookup"><span data-stu-id="7840e-281">&#x2713; [PCI DSS](#pci-dss) Attestation of Compliance (AOC).</span></span>|
||<span data-ttu-id="7840e-282">&#x2713; [SOC 2](#soc-2) 유형 I/유형 II 보고서입니다.</span><span class="sxs-lookup"><span data-stu-id="7840e-282">&#x2713; [SOC 2](#soc-2) Type I/Type II reports.</span></span>|
||<span data-ttu-id="7840e-283">&#x2713; [](#isms)  /  [ISMS IEC](#iec) - 1S0/IEC 27001 SoA(적용성 정책) 및 인증.</span><span class="sxs-lookup"><span data-stu-id="7840e-283">&#x2713; [ISMS](#isms) / [IEC](#iec) - 1S0/IEC 27001 Statement of Applicability (SoA) and Certification.</span></span>|
|<span data-ttu-id="7840e-284">**웹 종속성**</span><span class="sxs-lookup"><span data-stu-id="7840e-284">**Web Dependencies**</span></span>|<span data-ttu-id="7840e-285">현재 실행 중인 버전에서 앱/추가 기능에서 사용하는 모든 종속성 목록을 표시하는 설명서입니다.</span><span class="sxs-lookup"><span data-stu-id="7840e-285">Documentation listing all dependencies used by the app / add-in with the current running versions.</span></span>|
|<span data-ttu-id="7840e-286">**소프트웨어 인벤토리**</span><span class="sxs-lookup"><span data-stu-id="7840e-286">**Software Inventory**</span></span>|<span data-ttu-id="7840e-287">범위 내 환경에서 사용되는 모든 소프트웨어와 버전이 포함된 최신 소프트웨어 인벤토리입니다.</span><span class="sxs-lookup"><span data-stu-id="7840e-287">An up-to-date software inventory which includes all software used within the in-scope environment along with the versions.</span></span>|
|<span data-ttu-id="7840e-288">**하드웨어 인벤토리**</span><span class="sxs-lookup"><span data-stu-id="7840e-288">**Hardware Inventory**</span></span>| <span data-ttu-id="7840e-289">지원 인프라에서 사용하는 최신 하드웨어 인벤토리입니다.</span><span class="sxs-lookup"><span data-stu-id="7840e-289">An up-to-date hardware inventory used by the supporting infrastructure.</span></span> <span data-ttu-id="7840e-290">평가 단계를 수행할 때 샘플링에 도움이 됩니다.</span><span class="sxs-lookup"><span data-stu-id="7840e-290">This will be used to help with sampling when performing the assessment phase.</span></span> <span data-ttu-id="7840e-291">환경에 PaaS가 포함되어 있는 경우 소비된 서비스에 대한 세부 정보를 제공합니다.</span><span class="sxs-lookup"><span data-stu-id="7840e-291">If your environment includes PaaS provide details of services consumed.</span></span>|

## <a name="evidence-collection-and-assessment-activities"></a><span data-ttu-id="7840e-292">증거 수집 및 평가 활동</span><span class="sxs-lookup"><span data-stu-id="7840e-292">Evidence Collection and Assessment Activities</span></span>

<span data-ttu-id="7840e-293">인증 분석가가 정의된 샘플 집합 내의 모든 시스템 구성 요소에 대한 증거를 검토해야 합니다.</span><span class="sxs-lookup"><span data-stu-id="7840e-293">Certification analysts will need to review evidence across all system components within the defined sample set.</span></span> <span data-ttu-id="7840e-294">평가 프로세스를 지원하는 데 필요한 증거 유형은 다음과 같습니다.</span><span class="sxs-lookup"><span data-stu-id="7840e-294">The types of evidence required to support the assessment process include any or all the following:</span></span>

<span data-ttu-id="7840e-295">**Evidence 컬렉션**</span><span class="sxs-lookup"><span data-stu-id="7840e-295">**Evidence Collection**</span></span>

* <span data-ttu-id="7840e-296">위의 초기 설명서 제출 [섹션에서](#initial-document-submission) 강조 표시된 초기 설명서</span><span class="sxs-lookup"><span data-stu-id="7840e-296">Initial documentation, highlighted within the [Initial Documentation Submission](#initial-document-submission) section above</span></span> 
* <span data-ttu-id="7840e-297">정책 문서</span><span class="sxs-lookup"><span data-stu-id="7840e-297">Policy documents</span></span> 
* <span data-ttu-id="7840e-298">문서 처리</span><span class="sxs-lookup"><span data-stu-id="7840e-298">Process documents</span></span> 
* <span data-ttu-id="7840e-299">시스템 구성 설정</span><span class="sxs-lookup"><span data-stu-id="7840e-299">System configuration settings</span></span> 
* <span data-ttu-id="7840e-300">티켓 변경</span><span class="sxs-lookup"><span data-stu-id="7840e-300">Change tickets</span></span> 
* <span data-ttu-id="7840e-301">컨트롤 레코드 변경</span><span class="sxs-lookup"><span data-stu-id="7840e-301">Change control records</span></span> 
* <span data-ttu-id="7840e-302">시스템 보고서</span><span class="sxs-lookup"><span data-stu-id="7840e-302">System reports</span></span>

<span data-ttu-id="7840e-303">다양한 방법을 사용하여 평가 프로세스를 완료하는 데 필요한 증거를 수집합니다.</span><span class="sxs-lookup"><span data-stu-id="7840e-303">Various methods will be used to collect the evidence necessary to complete the assessment process.</span></span>  <span data-ttu-id="7840e-304">이 증거 컬렉션은 다음 형식일 수 있습니다.</span><span class="sxs-lookup"><span data-stu-id="7840e-304">This evidence collection may be in the form of:</span></span> 
* <span data-ttu-id="7840e-305">문서</span><span class="sxs-lookup"><span data-stu-id="7840e-305">Documents</span></span> 
* <span data-ttu-id="7840e-306">스크린샷</span><span class="sxs-lookup"><span data-stu-id="7840e-306">Screenshots</span></span> 
* <span data-ttu-id="7840e-307">인터뷰</span><span class="sxs-lookup"><span data-stu-id="7840e-307">Interviews</span></span> 
* <span data-ttu-id="7840e-308">화면 공유</span><span class="sxs-lookup"><span data-stu-id="7840e-308">Screensharing</span></span> 

<span data-ttu-id="7840e-309">사용되는 증거 수집 기술은 평가 프로세스 중에 결정됩니다.</span><span class="sxs-lookup"><span data-stu-id="7840e-309">The evidence collection techniques used will be determined during the assessment process.</span></span> 

<span data-ttu-id="7840e-310">**평가 활동**</span><span class="sxs-lookup"><span data-stu-id="7840e-310">**Assessment Activities**</span></span>

<span data-ttu-id="7840e-311">인증 분석가가 제공하는 증거를 검토하여 이 인증 사양 내에서 컨트롤을 적절하게 충족하는지 Microsoft 365 합니다.</span><span class="sxs-lookup"><span data-stu-id="7840e-311">Certification analysts will review evidence you provide to determine if you have adequately met controls within this Microsoft 365 Certification Specification.</span></span> 

<span data-ttu-id="7840e-312">가능한 경우 및 평가를 완료하는 데 필요한 시간을 줄이기 위해 초기 [](#initial-document-submission)설명서 제출에 자세히 설명된 설명서의 전체 또는 전체를 미리   제공해야 합니다.</span><span class="sxs-lookup"><span data-stu-id="7840e-312">Where possible and to reduce the amount of time required to complete the assessment, any or all of the documentation detailed in the [Initial Documentation Submission](#initial-document-submission) should be provided in advance.</span></span>

<span data-ttu-id="7840e-313">인증 분석가는 먼저 초기 설명서 제출에서 제공된 증거와 Publisher 증명 정보를 검토하여 적절한 문의 줄, 샘플링 크기 및 위에 자세히 설명된 대로 추가 증거를 얻을 필요성을 식별합니다.</span><span class="sxs-lookup"><span data-stu-id="7840e-313">Certification analysts will first review the evidence provided from the initial documentation submission and the Publisher Attestation information to identify appropriate lines of inquiry, sampling size, and the need for further evidence to be obtained as detailed above.</span></span>  <span data-ttu-id="7840e-314">인증 분석가는 수집된 모든 정보를 분석하여 이 인증 사양 내에서 제어를 충족하는 방법 및 Microsoft 365 결론을 내릴 것입니다.</span><span class="sxs-lookup"><span data-stu-id="7840e-314">Certification analysts will analyze all information gathered to draw conclusions as to how and if you are meeting the controls within this Microsoft 365 Certification Specification.</span></span> 

## <a name="app-certification-criteria"></a><span data-ttu-id="7840e-315">앱 인증 기준</span><span class="sxs-lookup"><span data-stu-id="7840e-315">App Certification Criteria</span></span>

<span data-ttu-id="7840e-316">앱, 지원 인프라 및 지원 설명서는 다음 보안 도메인에서 평가됩니다.</span><span class="sxs-lookup"><span data-stu-id="7840e-316">Your app, supporting infrastructure, and supporting documentation will be assessed across the following security domains:</span></span>

1. [<span data-ttu-id="7840e-317">**Application Security**</span><span class="sxs-lookup"><span data-stu-id="7840e-317">**Application Security**</span></span>](#application-security)
1. [<span data-ttu-id="7840e-318">**운영 보안/보안 배포**</span><span class="sxs-lookup"><span data-stu-id="7840e-318">**Operational Security / Secure Deployment**</span></span>](#operational-security)
1. [<span data-ttu-id="7840e-319">**데이터 처리 보안 및 개인 정보**</span><span class="sxs-lookup"><span data-stu-id="7840e-319">**Data Handling Security and Privacy**</span></span>](#data-handling-security-and-privacy)

<span data-ttu-id="7840e-320">이러한 각 보안 도메인에는 평가 프로세스의 일부로 평가될 하나 이상의 특정 요구 사항을 포함하는 특정 키 컨트롤이 포함되어 있습니다.</span><span class="sxs-lookup"><span data-stu-id="7840e-320">Each of these security domains includes specific key controls encompassing one or more specific requirements that will be evaluated as part of the assessment process.</span></span> <span data-ttu-id="7840e-321">모든 크기의 Microsoft 365 인증을 포함하도록 각 보안 도메인은 점수 지정 시스템을 사용하여 각 도메인의 전체 점수를 평가합니다.</span><span class="sxs-lookup"><span data-stu-id="7840e-321">To ensure that Microsoft 365 Certification is inclusive to developers of all sizes, each of the security domains is assessed using a scoring system to determine an overall score from each of the domains.</span></span> <span data-ttu-id="7840e-322">각 인증 Microsoft 365 컨트롤에 대한 점수는 1(낮음)과 3(높음) 사이에서 할당됩니다. 이 컨트롤이 충족되지 않을 경우의 인식된 위험에 따라 1(낮음)과 3(높음) 사이의 점수가 할당됩니다.</span><span class="sxs-lookup"><span data-stu-id="7840e-322">Scores for each of the Microsoft 365 Certification controls are allocated between 1 (low) and 3 (high) based upon the perceived risk of that control not being met.</span></span> <span data-ttu-id="7840e-323">각 보안 도메인에는 통과로 표시될 최소 백분율 표시가 있습니다.</span><span class="sxs-lookup"><span data-stu-id="7840e-323">Each of the security domains will have a minimum percentage mark to be deemed a pass.</span></span> <span data-ttu-id="7840e-324">이 사양의 특정 요소에는 몇 가지 자동 실패 조건이 포함됩니다.</span><span class="sxs-lookup"><span data-stu-id="7840e-324">Certain elements of this specification include some automatic fail criteria:</span></span>

- <span data-ttu-id="7840e-325">API 권한은 PoLP(최소 권한) 원칙을 따라야 합니다.</span><span class="sxs-lookup"><span data-stu-id="7840e-325">API permissions not following the principle of least privilege (PoLP).</span></span>  
- <span data-ttu-id="7840e-326">필요한 경우 침투 테스트 보고서가 없습니다.</span><span class="sxs-lookup"><span data-stu-id="7840e-326">No penetration testing report when it is required.</span></span>
- <span data-ttu-id="7840e-327">맬웨어 방지 방어 없음</span><span class="sxs-lookup"><span data-stu-id="7840e-327">No anti-malware defenses</span></span>
- <span data-ttu-id="7840e-328">관리 액세스를 보호하는 데 다단계 인증이 사용되지 않습니다.</span><span class="sxs-lookup"><span data-stu-id="7840e-328">Multi-Factor authentication not being used to protect administrative access.</span></span>  
- <span data-ttu-id="7840e-329">패치 프로세스가 없습니다.</span><span class="sxs-lookup"><span data-stu-id="7840e-329">No patching processes.</span></span>  
- <span data-ttu-id="7840e-330">적절한 [GDPR 개인 정보](#gdpr) 취급 방침이 없음</span><span class="sxs-lookup"><span data-stu-id="7840e-330">No suitable [GDPR](#gdpr) privacy notice.</span></span>  

## <a name="application-security"></a><span data-ttu-id="7840e-331">Application Security</span><span class="sxs-lookup"><span data-stu-id="7840e-331">Application Security</span></span>

<span data-ttu-id="7840e-332">응용 프로그램 보안 도메인은 다음 세 가지 영역에 초점을 맞추고 있습니다.</span><span class="sxs-lookup"><span data-stu-id="7840e-332">The application security domain focuses upon the following three areas:</span></span> 
* <span data-ttu-id="7840e-333">GraphAPI 사용 권한 유효성 검사</span><span class="sxs-lookup"><span data-stu-id="7840e-333">GraphAPI Permission Validation</span></span> 
* <span data-ttu-id="7840e-334">외부 연결 검사</span><span class="sxs-lookup"><span data-stu-id="7840e-334">External Connectivity Checks</span></span>
* <span data-ttu-id="7840e-335">응용 프로그램 보안 테스트</span><span class="sxs-lookup"><span data-stu-id="7840e-335">Application Security Testing</span></span> 

### <a name="graphapi-permission-validation"></a><span data-ttu-id="7840e-336">GraphAPI 사용 권한 유효성 검사</span><span class="sxs-lookup"><span data-stu-id="7840e-336">GraphAPI Permission Validation</span></span>

<span data-ttu-id="7840e-337">GraphAPI 권한 유효성 검사는 앱/추가 기능에서 과도하게 허용되는 권한을 요청하지 않는지 검사하기 위해 수행됩니다.</span><span class="sxs-lookup"><span data-stu-id="7840e-337">GraphAPI permission validation is carried out to validate the app/add-in does not request overly permissive permissions.</span></span> <span data-ttu-id="7840e-338">요청된 사용 권한을 수동으로 확인하여 수행됩니다.</span><span class="sxs-lookup"><span data-stu-id="7840e-338">This is carried out by manually checking what permissions are requested.</span></span> <span data-ttu-id="7840e-339">인증 분석가가 Publisher 증명 제출에 대해 이러한 검사를 교차 참조하고 요청되는 액세스 수준을 평가하여 '최소 권한' 관행이 충족되도록 합니다.</span><span class="sxs-lookup"><span data-stu-id="7840e-339">Certification analysts will cross reference these checks against the Publisher Attestation submission and evaluate the level of access being requested to ensure ‘least privilege’ practices are being met.</span></span> <span data-ttu-id="7840e-340">인증 분석가가 이러한 '최소 권한' 관행이 충족되지 않는 것으로 생각되는 경우 인증 분석가는 요청되는 사용 권한에 대한 비즈니스 사당성의 유효성을 검사하기 위해 공개적인 논의를 합니다.</span><span class="sxs-lookup"><span data-stu-id="7840e-340">Where certification analysts believe these ‘least privilege’ practices are not being met, certification analysts will have an open discussion with you to validate the business justification for the permissions being requested.</span></span> <span data-ttu-id="7840e-341">이 검토 중에 발견된 Publisher 제출에 대한 불일치도 피드백을 얻게 되어 Publisher 업데이트할 수 있습니다.</span><span class="sxs-lookup"><span data-stu-id="7840e-341">Any discrepancies against your Publisher Attestation submission found during this review will also get feedback so your Publisher Attestation can be updated.</span></span> 

### <a name="external-connectivity-checks"></a><span data-ttu-id="7840e-342">외부 연결 검사</span><span class="sxs-lookup"><span data-stu-id="7840e-342">External Connectivity Checks</span></span>

<span data-ttu-id="7840e-343">평가의 일부로 분석가가 M365 외부의 연결을 식별하기 위해 응용 프로그램 기능을 쉽게 확인할 수 있습니다.</span><span class="sxs-lookup"><span data-stu-id="7840e-343">As part of the assessment, an Analyst will perform a light walk through of the applications functionality to identify connections outside of M365.</span></span>  <span data-ttu-id="7840e-344">Microsoft로 식별되지 않는 연결 또는 서비스에 대한 직접 연결은 플래그가 지정되고 평가 중에 논의됩니다.</span><span class="sxs-lookup"><span data-stu-id="7840e-344">Any connections which are not identified as being Microsoft or direct connections to your service will be flagged and discussed during the assessment.</span></span>

### <a name="application-security-testing"></a><span data-ttu-id="7840e-345">응용 프로그램 보안 테스트</span><span class="sxs-lookup"><span data-stu-id="7840e-345">Application Security Testing</span></span>

<span data-ttu-id="7840e-346">앱/추가 기능 및 지원 환경과 관련된 위험을 적절하게 검토하는 것은 앱/추가 기능의 보안에 대한 보증을 고객에게 제공하는 데 필수적입니다.</span><span class="sxs-lookup"><span data-stu-id="7840e-346">An adequate review of the risks associated with your app/add-in and supporting environment is essential in providing customers with assurance in the security of the app/add-in.</span></span> <span data-ttu-id="7840e-347">응용 프로그램이 Microsoft에서 게시하지 않은 서비스에 대한 연결이 있는 경우 침투 테스트 형태의 응용 프로그램 보안 테스트를 수행해야 합니다.</span><span class="sxs-lookup"><span data-stu-id="7840e-347">Application security testing in the form of penetration testing MUST be carried out if your application has any connectivity to any service not published by Microsoft.</span></span> <span data-ttu-id="7840e-348">앱이 Microsoft가 아닌 다른 서비스 또는 백end에 연결하지 않고 독립 실행형으로 작동하는 경우 침투 테스트가 필요하지 않습니다.</span><span class="sxs-lookup"><span data-stu-id="7840e-348">If your app operates standalone without connectivity to any non-Microsoft service or backend, then penetration testing is not required.</span></span>


<span data-ttu-id="7840e-349">**침투 테스트 범위**</span><span class="sxs-lookup"><span data-stu-id="7840e-349">**Penetration Testing Scope**</span></span>

<span data-ttu-id="7840e-350">침투 테스트 작업에는 앱/추가 기능의 작동을 지원하는 추가 환경(예: 앱/추가 기능 코드가 매니페스트 파일 내의 리소스가 될 호스트되는 위치)을 지원하는 환경과 앱/추가 기능의 작동을 지원하는 추가 환경(예: 앱/추가 기능에서 앱 외부의 다른 웹 응용 프로그램과 Microsoft 365)을 지원하는 환경이 포함되어야 합니다. </span><span class="sxs-lookup"><span data-stu-id="7840e-350">Penetration testing activities **MUST** include the environment that supports the deployment of the app/add-in (for example; where the app/add-in code is hosted which will typically be the resource within the manifest file) along with any additional environment that supports the operation of the app/add-in (for example; if the app/add-in talks to other web applications outside of Microsoft 365).</span></span>  <span data-ttu-id="7840e-351">범위를 정의할 때 범위 내 환경의 보안에 영향을 줄 수 있는 "연결된" 시스템 또는 환경이 모든 침투 테스트 활동 내에 포함되도록 주의해야 합니다.</span><span class="sxs-lookup"><span data-stu-id="7840e-351">When defining the scope, care needs to be taken to ensure that any “connected-to” systems or environments that can impact upon the security of the in-scope environment is also included within ALL penetration testing activities.</span></span> 

<span data-ttu-id="7840e-352">범위 내 환경을 다른 환경과 구분하는 기술을 사용하는 경우 침투 테스트 활동은 해당 분할 기술의 효율성을 검증해야 합니다.</span><span class="sxs-lookup"><span data-stu-id="7840e-352">Where techniques are used to segment the in-scope environments from other environments, penetration testing activities MUST validate the effectiveness of said segmentation techniques.</span></span> <span data-ttu-id="7840e-353">이 내용은 침투 테스트 보고서 내에서 자세히 설명해야 합니다.</span><span class="sxs-lookup"><span data-stu-id="7840e-353">This must be detailed within the penetration testing report.</span></span> 

<span data-ttu-id="7840e-354">침투 테스트 보고서를 검토하여 아래 컨트롤에 설명된 다음과 같은 \*\*\*\* 자동 오류 기준을 충족하는 취약성은 없는지 검토합니다.</span><span class="sxs-lookup"><span data-stu-id="7840e-354">Penetration testing reports will be reviewed to ensure there are no vulnerabilities that meet the following **automatic failure criteria** outlined in the controls below.</span></span>
 
<span data-ttu-id="7840e-355">**침투 테스트 요구 사항**</span><span class="sxs-lookup"><span data-stu-id="7840e-355">**Penetration testing Requirements**</span></span>

||<span data-ttu-id="7840e-356">**침투 테스트 컨트롤**</span><span class="sxs-lookup"><span data-stu-id="7840e-356">**Penetration Test Controls**</span></span>|
| -------------------------|-----------------------------|
|<span data-ttu-id="7840e-357">**일반 조건**</span><span class="sxs-lookup"><span data-stu-id="7840e-357">**General Criteria**</span></span>| <span data-ttu-id="7840e-358">**컨트롤**</span><span class="sxs-lookup"><span data-stu-id="7840e-358">**Controls**</span></span>|
|| <span data-ttu-id="7840e-359">응용 프로그램 및 인프라  침투 테스트는 매년(12개월마다) 수행되어야 합니다.</span><span class="sxs-lookup"><span data-stu-id="7840e-359">Application and infrastructure penetration testing **MUST** take place annually (every 12 months) and conducted by a reputable independent company.</span></span> |
|| <span data-ttu-id="7840e-360">식별된 중요 및 고위험 취약성의 수정은 침투 테스트가 마무리된 후 한 달 이내에 또는 문서화된 패치 프로세스에 따라 더 빨리 완료해야 합니다.  </span><span class="sxs-lookup"><span data-stu-id="7840e-360">Remediation of identified critical and high-risk vulnerabilities **MUST** be completed within one month of the conclusion of the penetration testing, or sooner depending on the documented patching process. </span></span>|
|| <span data-ttu-id="7840e-361">전체 외부 공간(IP 주소, URL, API 끝점 등) 침투 테스트 범위 내에 포함되어야 하며 침투 테스트 보고서 내에 문서화해야 합니다.</span><span class="sxs-lookup"><span data-stu-id="7840e-361">The full external footprint (IP Addresses, URLs, API Endpoints, etc.) MUST be included within the scope of penetration testing and must be documented within the penetration testing report.</span></span> |
|| <span data-ttu-id="7840e-362">웹 응용 프로그램 침투 테스트에는 모든 취약성 클래스가 포함되어야 합니다. 예를 들어 가장 최근의 OWASP 상위 10 또는 SANS 상위 25개 CWE입니다.</span><span class="sxs-lookup"><span data-stu-id="7840e-362">Web application penetration testing MUST include all vulnerability classes; for example, the most current OWASP Top 10 or SANS Top 25 CWE.</span></span> |
|| <span data-ttu-id="7840e-363">침투 테스트 회사에서 식별된 취약점을 다시 테스트할 필요는 없습니다. 재구성 및 자체 검토로 충분하기는 하지만 평가 중에 충분한 수정을 입증할 수 있는 충분한 증거를 제공해야 합니다. </span><span class="sxs-lookup"><span data-stu-id="7840e-363">Retesting of identified vulnerabilities by the penetration testing company is not required — remediation and self-review is sufficient however, adequate evidence to demonstrate sufficient remediation **MUST** be provided during the assessment.</span></span>|
|<span data-ttu-id="7840e-364">**자동 오류 기준:**</span><span class="sxs-lookup"><span data-stu-id="7840e-364">**Automatic Failure Criteria:**</span></span>|<span data-ttu-id="7840e-365">**컨트롤**</span><span class="sxs-lookup"><span data-stu-id="7840e-365">**Controls**</span></span>|
|| <span data-ttu-id="7840e-366">지원되지 않는 운영 체제가 있습니다.</span><span class="sxs-lookup"><span data-stu-id="7840e-366">Presence of an unsupported operating system.</span></span> |
|| <span data-ttu-id="7840e-367">기본 계정, 열기 가능 또는 추측 가능한 관리 계정이 있습니다.</span><span class="sxs-lookup"><span data-stu-id="7840e-367">Presence of default, enumerable, or guessable administrative accounts.</span></span>|
|| <span data-ttu-id="7840e-368">삽입 위험 SQL 존재합니다.</span><span class="sxs-lookup"><span data-stu-id="7840e-368">Presence of SQL injection risks.</span></span>|
|| <span data-ttu-id="7840e-369">교차 사이트 스크립팅이 있습니다.</span><span class="sxs-lookup"><span data-stu-id="7840e-369">Presence of cross-site scripting.</span></span>|
|| <span data-ttu-id="7840e-370">디렉터리 트래버스(파일 경로) 취약성의 존재</span><span class="sxs-lookup"><span data-stu-id="7840e-370">Presence of directory traversal (file path) vulnerabilities.</span></span>|
|| <span data-ttu-id="7840e-371">HTTP 취약성(예: 헤더 응답 분할, 요청 밀기 및 디스ync 공격)이 있습니다.</span><span class="sxs-lookup"><span data-stu-id="7840e-371">Presence of HTTP vulnerabilities, e.g., Header response splitting, Request smuggling, and Desync attacks.</span></span>|
|| <span data-ttu-id="7840e-372">소스 코드 [공개(LFI 포함)가 있습니다.](#lfi)</span><span class="sxs-lookup"><span data-stu-id="7840e-372">Presence of source code disclosure (including [LFI](#lfi)).</span></span>|
|| <span data-ttu-id="7840e-373">CVSS 패치 관리 지침에 정의된 임의 또는 최고 점수입니다.</span><span class="sxs-lookup"><span data-stu-id="7840e-373">Any critical or high score as defined by the CVSS patch management guidelines.</span></span>|
|| <span data-ttu-id="7840e-374">많은 양의 EUII 또는 OUI를 손상하기 위해 쉽게 악용될 수 있는 중요한 기술 취약성.</span><span class="sxs-lookup"><span data-stu-id="7840e-374">Any significant technical vulnerability which can be readily exploited to compromise a large amount of EUII or OUI.</span></span>|






> [!IMPORTANT]
><span data-ttu-id="7840e-375">보고서는 응용 프로그램 보안 테스트 사양 섹션에 자세히 설명된 모든 내용을 보여줄 수 있어야 합니다.</span><span class="sxs-lookup"><span data-stu-id="7840e-375">Reports must be able to provide enough assurance that everything detailed within the Application Security Test Specification section can be demonstrated.</span></span>


<span data-ttu-id="7840e-376">**침투 테스트 요구 사항 및 비용**</span><span class="sxs-lookup"><span data-stu-id="7840e-376">**Penetration Testing Requirements and Cost**</span></span>

<span data-ttu-id="7840e-377">현재 침투 테스트에 참여하지 않는 ISV의 경우 침투 테스트는 Microsoft 365 인증에 포함됩니다.</span><span class="sxs-lookup"><span data-stu-id="7840e-377">For ISVs that currently do not engage in penetration testing, penetration testing is included under the Microsoft 365 Certification.</span></span> <span data-ttu-id="7840e-378">Microsoft는 최대 12일의 수동 테스트에 대한 침투 테스트 비용을 준비하고 지원할 것입니다.</span><span class="sxs-lookup"><span data-stu-id="7840e-378">Microsoft will arrange and cover the cost of a penetration test for up to 12 days of manual testing.</span></span> <span data-ttu-id="7840e-379">침투 테스트 비용은 환경을 테스트하는 데 필요한 일 수를 기준으로 계산됩니다.</span><span class="sxs-lookup"><span data-stu-id="7840e-379">Penetration tests costs are calculated based on the number of days required to test the environment.</span></span> <span data-ttu-id="7840e-380">테스트가 12일을 초과하는 비용은 ISV의 책임입니다.</span><span class="sxs-lookup"><span data-stu-id="7840e-380">Any expenses exceeding 12 days of testing will be the responsibility of the ISV.</span></span> <span data-ttu-id="7840e-381">또한 ISV는 인증을 획득하기 전에 침투 테스트에서 식별된 취약점이 수정되었다는 것을 증명하지만, 클린 보고서를 만들 필요가 없다고 증명할 책임이 있습니다.</span><span class="sxs-lookup"><span data-stu-id="7840e-381">The ISV will also be responsible for demonstrating that vulnerabilities identified in the penetration test have been remediated prior to a certification being awarded, but do not need to produce a clean report.</span></span>

<span data-ttu-id="7840e-382">침투 테스트가 정렬된 후 ISV는 다음과 같이 예약 및 취소와 관련된 요금을 담당합니다.</span><span class="sxs-lookup"><span data-stu-id="7840e-382">Once a penetration test is arranged, the ISV is responsible for fees associated with rescheduling and cancellations as follows:</span></span>

| <span data-ttu-id="7840e-383">**요금 시간제 재조정**</span><span class="sxs-lookup"><span data-stu-id="7840e-383">**Rescheduling Fee Timescale**</span></span> | <span data-ttu-id="7840e-384">**비례 지급 가능**</span><span class="sxs-lookup"><span data-stu-id="7840e-384">**Proportion Payable**</span></span> |
|------------------|------------------------|
| <span data-ttu-id="7840e-385">예약된 시작 날짜 30일 전에 다시 예약 요청이 수신된 경우</span><span class="sxs-lookup"><span data-stu-id="7840e-385">Re-schedule request received more than 30 days prior to scheduled start date.</span></span> | <span data-ttu-id="7840e-386">0% 지급 가능</span><span class="sxs-lookup"><span data-stu-id="7840e-386">0% Payable</span></span> |
| <span data-ttu-id="7840e-387">다시 예약 요청은 예약된 시작 날짜 8~30일 전에 수신했습니다.</span><span class="sxs-lookup"><span data-stu-id="7840e-387">Re-schedule request received 8 to 30 days prior to scheduled start date.</span></span> | <span data-ttu-id="7840e-388">25% 지급 가능</span><span class="sxs-lookup"><span data-stu-id="7840e-388">25% Payable</span></span> |
| <span data-ttu-id="7840e-389">회사 재예약 날짜가 있는 예약된 시작 날짜로부터 2~7일 이내에 수신된 요청을 다시 예약합니다.</span><span class="sxs-lookup"><span data-stu-id="7840e-389">Re-schedule request received within 2 to 7 days prior to scheduled start date with a firm re-booking date.</span></span>| <span data-ttu-id="7840e-390">50% 지급 가능</span><span class="sxs-lookup"><span data-stu-id="7840e-390">50% Payable</span></span> |
| <span data-ttu-id="7840e-391">다시 예약 요청은 시작 날짜 2일 전에 수신됩니다.</span><span class="sxs-lookup"><span data-stu-id="7840e-391">Re-schedule request received less than 2 days before the start date.</span></span> | <span data-ttu-id="7840e-392">100% 지급 가능</span><span class="sxs-lookup"><span data-stu-id="7840e-392">100% Payable</span></span> |

| <span data-ttu-id="7840e-393">**취소 요금 시간 기준**</span><span class="sxs-lookup"><span data-stu-id="7840e-393">**Cancellation Fee Timescale**</span></span> | <span data-ttu-id="7840e-394">**비례 지급 가능**</span><span class="sxs-lookup"><span data-stu-id="7840e-394">**Proportion Payable**</span></span> |
|------------------|------------------------|
| <span data-ttu-id="7840e-395">취소 요청이 예정된 시작 날짜보다 30일 전에 수신했습니다.</span><span class="sxs-lookup"><span data-stu-id="7840e-395">Cancellation request received more than 30 days prior to scheduled start date.</span></span> | <span data-ttu-id="7840e-396">25% 지급 가능</span><span class="sxs-lookup"><span data-stu-id="7840e-396">25% Payable</span></span> |
| <span data-ttu-id="7840e-397">취소 요청은 예약된 시작 날짜 8~30일 전에 수신했습니다.</span><span class="sxs-lookup"><span data-stu-id="7840e-397">Cancellation request received 8 to 30 days days prior to scheduled start date.</span></span> | <span data-ttu-id="7840e-398">50% 지급 가능</span><span class="sxs-lookup"><span data-stu-id="7840e-398">50% Payable</span></span> |
| <span data-ttu-id="7840e-399">예약된 시작 날짜로부터 7일 이내에 수신된 취소 요청입니다.</span><span class="sxs-lookup"><span data-stu-id="7840e-399">Cancellation request received within 7 days prior to scheduled start date.</span></span> | <span data-ttu-id="7840e-400">90% 지급 가능</span><span class="sxs-lookup"><span data-stu-id="7840e-400">90% Payable</span></span> |

## <a name="operational-security"></a><span data-ttu-id="7840e-401">운영 보안</span><span class="sxs-lookup"><span data-stu-id="7840e-401">Operational Security</span></span>

<span data-ttu-id="7840e-402">이 도메인은 앱의 지원 인프라 및 배포 프로세스와 보안 모범 사례의 일치를 측정합니다.</span><span class="sxs-lookup"><span data-stu-id="7840e-402">This domain measures the alignment of your app's supporting infrastructure and deployment processes with security best practices.</span></span>

### <a name="controls"></a><span data-ttu-id="7840e-403">컨트롤</span><span class="sxs-lookup"><span data-stu-id="7840e-403">Controls</span></span>

|<span data-ttu-id="7840e-404">**컨트롤 패밀리**</span><span class="sxs-lookup"><span data-stu-id="7840e-404">**Control Family**</span></span>| <span data-ttu-id="7840e-405">**컨트롤**</span><span class="sxs-lookup"><span data-stu-id="7840e-405">**Controls**</span></span>|
| ------------------------|------------------------------ |
| <span data-ttu-id="7840e-406">**맬웨어 보호**</span><span class="sxs-lookup"><span data-stu-id="7840e-406">**Malware Protection**</span></span>|<span data-ttu-id="7840e-407">바이러스 백신 사례 및 절차를 관리 하는 정책 설명서를 제공합니다.</span><span class="sxs-lookup"><span data-stu-id="7840e-407">Provide policy documentation that governs anti-virus practices and procedures.</span></span>|
||<span data-ttu-id="7840e-408">샘플링된 모든 시스템 구성 요소에서 바이러스 백신 소프트웨어가 실행되고 있는 악의적인 증거를 제공합니다.</span><span class="sxs-lookup"><span data-stu-id="7840e-408">Provide demonstratable evidence that anti-virus software is running across all sampled system components.</span></span>|
||<span data-ttu-id="7840e-409">바이러스 백신 서명이 모든 환경 전체에서 최신(1일 이내)에 걸쳐 최신임에 대한 악의적인 증거를 제공합니다.</span><span class="sxs-lookup"><span data-stu-id="7840e-409">Provide demonstratable evidence that anti-virus signatures are up-to-date across all environments (within 1 day).</span></span>|
||<span data-ttu-id="7840e-410">샘플링된 모든 시스템 구성 요소에서 액세스 검사 또는 주기적 스캔을 수행하도록 바이러스 백신이 구성되어 있는 악의적인 증거를 제공합니다.</span><span class="sxs-lookup"><span data-stu-id="7840e-410">Provide demonstratable evidence that anti-virus is configured  to perform on-access scanning or periodic scan across all sampled system components.</span></span> <span data-ttu-id="7840e-411">참고: 액세스 시 검색을 사용하도록 설정하지 않은 경우 최소 일일 검사 및 경고를 사용하도록 설정해야 합니다.</span><span class="sxs-lookup"><span data-stu-id="7840e-411">Note: If on-access scanning is not enabled, then a minimum of daily scanning and alerting MUST be enabled.</span></span>|
||<span data-ttu-id="7840e-412">바이러스 백신이 샘플링된 모든 시스템 구성 요소에서 자동으로 맬웨어를 차단하거나, 맬웨어를 차단하고, 경고를 차단하고 경고하도록 구성되어 있는 악의적인 증거를 제공합니다.</span><span class="sxs-lookup"><span data-stu-id="7840e-412">Provide demonstratable evidence that anti-virus is configured to automatically block malware or quarantine and alert across all sampled system components.</span></span>|
|<span data-ttu-id="7840e-413">**응용 프로그램 컨트롤:** 기존의 맬웨어 방지가 사용되지 않는 경우만 필요합니다.</span><span class="sxs-lookup"><span data-stu-id="7840e-413">**Application Controls**: ONLY required if traditional anti-malware is not used</span></span>|<span data-ttu-id="7840e-414">배포하기 전에 응용 프로그램이 승인된 악의적인 증거를 제공합니다.</span><span class="sxs-lookup"><span data-stu-id="7840e-414">Provide demonstratable evidence that applications are approved prior to being deployed.</span></span>|
||<span data-ttu-id="7840e-415">비즈니스 근거가 있는 승인된 응용 프로그램의 전체 목록이 존재하고 유지 관리되는 악의적인 증거를 제공합니다.</span><span class="sxs-lookup"><span data-stu-id="7840e-415">Provide demonstratable evidence that a complete list of approved applications with business justification exists and is maintained.</span></span>|
||<span data-ttu-id="7840e-416">응용 프로그램 제어 소프트웨어가 특정 응용 프로그램 제어 메커니즘을 충족하도록 구성되어 있는지 자세히 설명하는 지원 설명서를 제공합니다.</span><span class="sxs-lookup"><span data-stu-id="7840e-416">Provide supporting documentation detailing that application control software is configured to meet specific application control mechanisms.</span></span> <span data-ttu-id="7840e-417">(예: 허용된 목록: sample1, sample3, 코드 서명)</span><span class="sxs-lookup"><span data-stu-id="7840e-417">(Example:  Allowed listing: sample1, sample3, code signing)</span></span>|
||<span data-ttu-id="7840e-418">응용 프로그램 제어가 모든 샘플링된 시스템 구성 요소에서 문서화한 것으로 구성되는 악의적인 증거를 제공합니다.</span><span class="sxs-lookup"><span data-stu-id="7840e-418">Provide demonstratable evidence that application control is configured as documented from all sampled system components.</span></span>|
|<span data-ttu-id="7840e-419">**패치 관리 - 위험 순위**</span><span class="sxs-lookup"><span data-stu-id="7840e-419">**Patch Management - Risk Ranking**</span></span>| <span data-ttu-id="7840e-420">새 보안 취약성을 식별하고 위험 점수를 할당하는 방법을 관리하는 정책 설명서를 제공합니다.</span><span class="sxs-lookup"><span data-stu-id="7840e-420">Supply policy documentation that governs how new security vulnerabilities are identified and assigned a risk score.</span></span>|
||<span data-ttu-id="7840e-421">새로운 보안 취약점이 식별되는 방식에 대한 증거를 제공합니다.</span><span class="sxs-lookup"><span data-stu-id="7840e-421">Provide evidence of how new security vulnerabilities are identified.</span></span>|
||<span data-ttu-id="7840e-422">모든 취약점이 식별되면 위험 순위가 할당되었다는 증거를 제공합니다.</span><span class="sxs-lookup"><span data-stu-id="7840e-422">Provide evidence demonstrating that all vulnerabilities are assigned a risk ranking once identified.</span></span>|
|<span data-ttu-id="7840e-423">**Patch Managmeent - 패치**</span><span class="sxs-lookup"><span data-stu-id="7840e-423">**Patch Managmeent - Patching**</span></span>|<span data-ttu-id="7840e-424">위험, 높음 및 중간 위험 취약성에 적합한 최소 패치 기간을 포함하는 범위 내 시스템 구성 요소의 패치에 대한 정책 설명서를 제공합니다. 지원되지 않는 운영 체제 및 소프트웨어의 해제</span><span class="sxs-lookup"><span data-stu-id="7840e-424">Provide policy documentation for patching of in-scope system components that includes suitable minimal patching timeframe for critical, high, and medium risk vulnerabilities; and decommissioning of any unsupported operating systems and software.</span></span>|
||<span data-ttu-id="7840e-425">샘플링된 모든 시스템 구성 요소가 패치되고 있는 악의적인 증거를 제공합니다.</span><span class="sxs-lookup"><span data-stu-id="7840e-425">Provide demonstratable evidence that all sampled system components are being patched.</span></span>|
||<span data-ttu-id="7840e-426">지원되지 않는 운영 체제 및 소프트웨어 구성 요소가 환경 내에서 사용되지 않는 악의적인 증거를 제공합니다.</span><span class="sxs-lookup"><span data-stu-id="7840e-426">Provide demonstratable evidence that any unsupported operating systems and software components aren't used within the environment.</span></span>|
|<span data-ttu-id="7840e-427">**취약성 검색**</span><span class="sxs-lookup"><span data-stu-id="7840e-427">**Vulnerability scanning**</span></span>|<span data-ttu-id="7840e-428">분기별 인프라 및 웹 응용 프로그램 취약성 검사 보고서를 제공합니다.</span><span class="sxs-lookup"><span data-stu-id="7840e-428">Provide the quarterly infrastructure and web application vulnerability scanning reports.</span></span> <span data-ttu-id="7840e-429">전체 공용 공간(IP 주소 및 URL) 및 내부 IP 범위에 대해 검색을 수행해야 합니다.</span><span class="sxs-lookup"><span data-stu-id="7840e-429">Scanning needs to be carried out against the entire public footprint (IP addresses and URLs) and internal IP ranges.</span></span>|
||<span data-ttu-id="7840e-430">취약점 검사 중에 식별된 취약점의 수정이 문서 패치 기간에 따라 패치되는 악의적인 증거를 제공합니다.</span><span class="sxs-lookup"><span data-stu-id="7840e-430">Provide demonstratable evidence that remediation of vulnerabilities identified during vulnerability scanning are patched in line with your documented patching timeframe.</span></span>|
|<span data-ttu-id="7840e-431">**방화벽**</span><span class="sxs-lookup"><span data-stu-id="7840e-431">**Firewalls**</span></span>|<span data-ttu-id="7840e-432">방화벽 관리 사례 및 절차를 관리하는 정책 설명서를 제공합니다.</span><span class="sxs-lookup"><span data-stu-id="7840e-432">Provide policy documentation that governs firewall management practices and procedures.</span></span>|
||<span data-ttu-id="7840e-433">프로덕션 환경에 설치하기 전에 기본 관리 자격 증명이 변경된 데모 증거를 제공합니다.</span><span class="sxs-lookup"><span data-stu-id="7840e-433">Provide demonstrable evidence that any default administrative credentials are changed prior to installation into production environments.</span></span>|
||<span data-ttu-id="7840e-434">경계 네트워크(DMZ, 비무장 영역 및 차단된 서브넷) 및 내부 트러스트된 네트워크 사이에 방화벽이 설치되는 데모 증거를 제공합니다.</span><span class="sxs-lookup"><span data-stu-id="7840e-434">Provide demonstrable evidence that firewalls are installed on the boundary of the in-scope environment, and installed between the perimeter network (also known as DMZ, demilitarized zone, and screened subnet) and internal trusted networks.</span></span>|
||<span data-ttu-id="7840e-435">모든 공용 액세스가 DMZ(비무장 영역)에서 종료된다고 입증할 수 있는 증거를 제공합니다.</span><span class="sxs-lookup"><span data-stu-id="7840e-435">Provide demonstrable evidence that all public access terminates in the demilitarized zone (DMZ).</span></span>|
||<span data-ttu-id="7840e-436">방화벽을 통해 허용되는 모든 트래픽이 승인 프로세스를 통과하는 데 입증할 수 있는 증거를 제공합니다.</span><span class="sxs-lookup"><span data-stu-id="7840e-436">Provide demonstrable evidence that all traffic permitted through the firewall goes through an approval process.</span></span>|
||<span data-ttu-id="7840e-437">방화벽 규칙 기준이 명시적으로 정의되지 않은 트래픽을 삭제하도록 구성되어 있는지 입증할 수 있는 증거를 제공합니다.</span><span class="sxs-lookup"><span data-stu-id="7840e-437">Provide demonstrable evidence that the firewall rule base is configured to drop traffic not explicitly defined.</span></span>|
||<span data-ttu-id="7840e-438">방화벽이 콘솔이 아닌 모든 관리 인터페이스에서 강력한 암호화만 지원하고 있는 입증 가능한 증거를 제공합니다.</span><span class="sxs-lookup"><span data-stu-id="7840e-438">Provide demonstrable evidence that the firewall supports only strong cryptography on all non-console administrative interfaces.</span></span>|
||<span data-ttu-id="7840e-439">최소 6개월마다 방화벽 규칙 검토를 수행하고 있는 악의적인 증거를 제공합니다.</span><span class="sxs-lookup"><span data-stu-id="7840e-439">Provide demonstratable evidence that you are performing firewall rule reviews at least every 6 months.</span></span>|
|<span data-ttu-id="7840e-440">**WAF(웹** 응용 프로그램 방화벽) (OPTIONAL) : 다음 컨트롤을 충족하면 추가 크레딧이 지급됩니다.</span><span class="sxs-lookup"><span data-stu-id="7840e-440">**Web Application Firewall (WAF) (OPTIONAL)**: Additional credit will be rewarded for satisfying the following controls.</span></span>|<span data-ttu-id="7840e-441">WAF(웹 응용 프로그램 방화벽)가 악의적인 트래픽을 적극적으로 모니터링, 경고 및 차단하도록 구성되어 있는 악의적인 증거를 제공합니다.</span><span class="sxs-lookup"><span data-stu-id="7840e-441">Provide demonstratable evidence that the Web Application Firewall (WAF) is configured to actively monitor, alert, and block malicious traffic.</span></span>|
||<span data-ttu-id="7840e-442">WAF가 SSL 오프로드를 지원하고 있는 데모 증거를 제공합니다.</span><span class="sxs-lookup"><span data-stu-id="7840e-442">Provide demonstrable evidence that the WAF supports SSL offloading.</span></span>|
||<span data-ttu-id="7840e-443">OWASP 핵심 규칙 집합(3.0 또는 3.1)에 따라 WAF가 일부 또는 모든 취약성으로부터 보호하고 있는 악의적인 증거를 제공합니다.</span><span class="sxs-lookup"><span data-stu-id="7840e-443">Provide demonstratable evidence that the WAF is protects against some, or all of the following classes of vulnerabilities as per the OWASP Core Rule Set (3.0 or 3.1)</span></span> |
|<span data-ttu-id="7840e-444">**변경 컨트롤**</span><span class="sxs-lookup"><span data-stu-id="7840e-444">**Change Control**</span></span>|<span data-ttu-id="7840e-445">변경 제어 프로세스를 제어하는 정책 설명서를 제공합니다.</span><span class="sxs-lookup"><span data-stu-id="7840e-445">Provide policy documentation that governs change control processes.</span></span>|
||<span data-ttu-id="7840e-446">개발 및 테스트 환경이 프로덕션 환경에서 업무를 분리할 수 있는 악의적인 증거를 제공합니다.</span><span class="sxs-lookup"><span data-stu-id="7840e-446">Provide demonstratable evidence that development and test environments enforce separation of duties from the production environment.</span></span>|
||<span data-ttu-id="7840e-447">개발 또는 테스트 환경에서 중요한 프로덕션 데이터가 사용되지 않는 악의적인 증거를 제공합니다.</span><span class="sxs-lookup"><span data-stu-id="7840e-447">Provide demonstratable evidence that sensitive production data is not used within the development or test environments.</span></span>|
||<span data-ttu-id="7840e-448">문서화한 변경 요청에 변경의 영향, 백아웃 절차의 세부 정보 및 수행될 테스트가 포함되어 있는 악의적인 증거를 제공합니다.</span><span class="sxs-lookup"><span data-stu-id="7840e-448">Provide demonstratable evidence that documented change requests contain impact of the change, details of back-out procedures and of testing to be carried out.</span></span>|
||<span data-ttu-id="7840e-449">권한 부여 및 서명 프로세스를 통해 요청을 변경하는 악의적인 증거를 제공합니다.</span><span class="sxs-lookup"><span data-stu-id="7840e-449">Provide demonstratable evidence that change requests undergo an authorization and signoff process.</span></span>|
|<span data-ttu-id="7840e-450">**보안 소프트웨어 개발/배포**</span><span class="sxs-lookup"><span data-stu-id="7840e-450">**Secure Software Development/Deployment**</span></span>| <span data-ttu-id="7840e-451">OWASP 상위 10 또는 SANS 상위 25개 CWE와 같은 일반적인 취약성 클래스에 대한 보안 코딩 모범 사례 지침을 포함하여 보안 소프트웨어 개발 및 배포를 지원하는 정책 및 절차를 제공합니다.</span><span class="sxs-lookup"><span data-stu-id="7840e-451">Provide policies and procedures that support secure software development and deployment, including secure coding best practice guidance against common vulnerability classes such as, OWASP Top 10 or SANS Top 25 CWE.</span></span>|
|| <span data-ttu-id="7840e-452">두 번째 검토자가 코드 변경에 대한 검토 및 권한 부여 프로세스를 진행하는 악의적인 증거를 제공합니다.</span><span class="sxs-lookup"><span data-stu-id="7840e-452">Provide demonstratable evidence that code changes undergo a review and authorization process by a second reviewer.</span></span>|
|| <span data-ttu-id="7840e-453">개발자가 매년 보안 소프트웨어 개발 교육을 실시하고 있는 악의적인 증거를 제공합니다.</span><span class="sxs-lookup"><span data-stu-id="7840e-453">Provide demonstratable evidence that developers undergo secure software development training annually.</span></span>|
|| <span data-ttu-id="7840e-454">MFA(다단계 인증)를 사용하여 코드 리포지토리가 보호된다고 강증할 수 있는 증거를 제공합니다.</span><span class="sxs-lookup"><span data-stu-id="7840e-454">Provide demonstratable evidence that code repositories are secured with multi-factor authentication (MFA).</span></span>|
|| <span data-ttu-id="7840e-455">코드 리포지토리를 보호하기 위해 액세스 제어가 구현되어 있는 악의적인 증거를 제공합니다.</span><span class="sxs-lookup"><span data-stu-id="7840e-455">Provide demonstratable evidence that access controls are in place to secure code repositories.</span></span>
|<span data-ttu-id="7840e-456">**계정 관리**</span><span class="sxs-lookup"><span data-stu-id="7840e-456">**Account Management**</span></span>| <span data-ttu-id="7840e-457">계정 관리 사례 및 절차를 관리하는 정책 설명서를 제공합니다.</span><span class="sxs-lookup"><span data-stu-id="7840e-457">Provide policy documentation that governs account management practices and procedures.</span></span>
||<span data-ttu-id="7840e-458">샘플링된 시스템 구성 요소 전체에서 기본 자격 증명이 비활성화, 제거 또는 변경되었다는 악의적인 증거를 제공합니다.</span><span class="sxs-lookup"><span data-stu-id="7840e-458">Provide demonstratable evidence that default credentials are either disabled, removed, or changed across the sampled system components.</span></span>|
||<span data-ttu-id="7840e-459">계정 생성, 수정 및 삭제가 확립된 승인 프로세스를 통과하는 악의적인 증거를 제공합니다.</span><span class="sxs-lookup"><span data-stu-id="7840e-459">Provide demonstratable evidence that account creation, modification and deletion goes through an established approval process.</span></span>|
||<span data-ttu-id="7840e-460">프로세스가 3개월 내에 사용되지 않는 계정을 사용하지 않도록 설정하거나 삭제하기 위해 진행 중임에 대한 악의적인 증거를 제공합니다.</span><span class="sxs-lookup"><span data-stu-id="7840e-460">Provide demonstratable evidence that a process is in place to either disable or delete accounts not used within 3 months.</span></span>|
||<span data-ttu-id="7840e-461">강력한 암호 정책 또는 사용자 자격 증명을 보호하기 위한 기타 적절한 완화가 적용되어 있는 악의적인 증거를 제공합니다.</span><span class="sxs-lookup"><span data-stu-id="7840e-461">Provide demonstratable evidence that a strong password policy or other suitable mitigations to protect user credentials are in place.</span></span>  <span data-ttu-id="7840e-462">최소 지침으로 사용해야 합니다. 최소 암호 길이 8자, 10회 이상 시도한 계정 잠금 임계값, 최소 5개 암호의 암호 기록, 강력한 암호 사용 적용</span><span class="sxs-lookup"><span data-stu-id="7840e-462">The following should be used as a minimum guideline: minimum password length of 8 character, account lockout threshold of no more than 10 attempts, password history of a minimum of 5 passwords, enforcement of the use of strong password</span></span>|
|<span data-ttu-id="7840e-463">**침입 감지 및 방지(선택 사항):** 다음 컨트롤을 충족하면 추가 크레딧이 지급됩니다.</span><span class="sxs-lookup"><span data-stu-id="7840e-463">**Intrusion Detection and Prevention (OPTIONAL):** Additional credit will be rewarded for satisfying the following controls</span></span>|<span data-ttu-id="7840e-464">IDPS(침입 감지 및 방지 시스템)가 범위 내 환경의 경계에 배포되는 악의적인 증거를 제공합니다.</span><span class="sxs-lookup"><span data-stu-id="7840e-464">Provide demonstratable evidence that Intrusion Detection and Prevention Systems (IDPS) is deployed at the perimeter of the in-scope environments.</span></span>|
||<span data-ttu-id="7840e-465">IDPS 서명이 최신(24시간 내에) 유지된다고 강증할 수 있는 증거를 제공합니다.</span><span class="sxs-lookup"><span data-stu-id="7840e-465">Provide demonstratable evidence that IDPS signatures are kept current (within 24 hours).</span></span>|
||<span data-ttu-id="7840e-466">들어오는 모든 웹 트래픽에 대한 TLS 검사를 지원하도록 IDPS가 구성된다고 강등할 수 있는 증거를 제공합니다.</span><span class="sxs-lookup"><span data-stu-id="7840e-466">Provide demonstratable evidence that IDPS is configured to support TLS inspection of all incoming web traffic.</span></span>|
||<span data-ttu-id="7840e-467">모든 인바운드 트래픽 흐름을 모니터링하도록 IDPS가 구성되는 악의적인 증거를 제공합니다.</span><span class="sxs-lookup"><span data-stu-id="7840e-467">Provide demonstratable evidence that IDPS is configured to monitor all inbound traffic flows.</span></span>|
||<span data-ttu-id="7840e-468">모든 아웃바운드 트래픽 흐름을 모니터링하도록 IDPS가 구성되는 강등할 수 있는 증거를 제공합니다.</span><span class="sxs-lookup"><span data-stu-id="7840e-468">Provide demonstratable evidence that IDPS is configured to monitor all outbound traffic flows.</span></span>|
|<span data-ttu-id="7840e-469">**보안 이벤트 로깅**</span><span class="sxs-lookup"><span data-stu-id="7840e-469">**Security Event Logging**</span></span> |<span data-ttu-id="7840e-470">보안 이벤트 로깅을 관리하는 모범 사례 및 절차에 대한 정책 설명서를 제공합니다.</span><span class="sxs-lookup"><span data-stu-id="7840e-470">Provide policy documentation for best practices and procedures that governs security event logging.</span></span>|
|| <span data-ttu-id="7840e-471">시스템 구성 요소 및 응용 프로그램에 대한 사용자 액세스, 권한이 높은 사용자가 수행한 모든 작업, 잘못된 논리적 액세스 시도 권한 있는 계정 만들기 또는 수정, 이벤트 로그 변조, 보안 도구 사용 안 하도록 설정(예: 맬웨어 방지 또는 이벤트 로깅)을 기록하기 위해 샘플링된 모든 시스템 구성 요소에 대해 보안 이벤트 로깅이 설정되어 있는 악의적인 증거를 제공합니다. , 맬웨어 방지 로깅(예: 업데이트, 맬웨어 검색 및 검사 실패),IDPS 및 WAF 이벤트(구성된 경우)</span><span class="sxs-lookup"><span data-stu-id="7840e-471">Provide demonstratable evidence that shows security event logging is set up across all sampled system components to log the following events: User access to system components and the application, All actions taken by a high-privileged user, Invalid logical access attempts Privileged account creation or modification, Event log tampering, Disabling of security tools (such as antimalware or event logging), Antimalware logging (such as updates, malware detection, and scan failures).,IDPS and WAF events, if configured</span></span>|
||<span data-ttu-id="7840e-472">기록된 보안 이벤트에 영향을 받는 시스템을 식별하는 레이블, 사용자, 이벤트 유형, 날짜 및 시간, 성공 또는 실패 표시기, 레이블과 같은 최소 정보가 포함되어 있는 강등할 수 있는 증거를 제공합니다.</span><span class="sxs-lookup"><span data-stu-id="7840e-472">Provide demonstratable evidence that logged security events contain the following minimum information: User, Type of event, Date and time, Success or failure indicators, Label that identifies the affected system</span></span>|
||<span data-ttu-id="7840e-473">샘플링된 모든 시스템 구성 요소가 동일한 기본 서버와 보조 서버로 시간 동기화되는 강등할 수 있는 증거를 제공합니다.</span><span class="sxs-lookup"><span data-stu-id="7840e-473">Provide demonstratable evidence that all sampled system components are time-synchronized to the same primary and secondary servers.</span></span>|
||<span data-ttu-id="7840e-474">보안 이벤트 로그가 경계 네트워크 내에 없는 중앙 로깅 솔루션으로 전송되는 공용 연결 시스템이 사용 중일 때 강하는 증거를 제공합니다.</span><span class="sxs-lookup"><span data-stu-id="7840e-474">Provide demonstratable evidence when public facing systems are in use that security event logs are being sent to a centralized logging solution not within the perimeter network.</span></span>|
||<span data-ttu-id="7840e-475">중앙 로깅 솔루션이 로깅 데이터를 무단으로 변조하는 것을 방지하는 데 사용할 수 있는 증거를 제공합니다.</span><span class="sxs-lookup"><span data-stu-id="7840e-475">Provide demonstrable evidence to show that the centralized logging solution is protected against unauthorized tampering of logging data.</span></span>|
||<span data-ttu-id="7840e-476">최소 30일의 보안 이벤트 로깅 데이터를 즉시 사용할 수 있는 데모 증거를 제공하고 90일 동안의 보안 이벤트 로그를 보존합니다.</span><span class="sxs-lookup"><span data-stu-id="7840e-476">Provide demonstrable evidence that a minimum of 30 days of security event logging data is immediately available, with 90 days of security event logs being retained.</span></span>|
|<span data-ttu-id="7840e-477">**검토(로그 데이터)**</span><span class="sxs-lookup"><span data-stu-id="7840e-477">**Reviewing (Log Data)**</span></span> |<span data-ttu-id="7840e-478">로그 검토 사례 및 절차를 관리하는 정책 설명서를 제공합니다.</span><span class="sxs-lookup"><span data-stu-id="7840e-478">Provide policy documentation that governs log review practices and procedures.</span></span>|
||<span data-ttu-id="7840e-479">잠재적인 보안 이벤트를 식별하기 위해 수동 또는 자동화된 도구로 로그를 매일 검토하는 데 사용할 수 있는 증거를 제공합니다.</span><span class="sxs-lookup"><span data-stu-id="7840e-479">Provide demonstrable evidence that logs are reviewed on a daily basis by a human or automated tooling to identify potential security events.</span></span>|
||<span data-ttu-id="7840e-480">잠재적인 보안 이벤트 및 이의를 조사하고 수정하는 데 입증할 수 있는 증거를 제공합니다.</span><span class="sxs-lookup"><span data-stu-id="7840e-480">Provide demonstrable evidence that potential security events and anomalies are investigated and remediated.</span></span>|
|<span data-ttu-id="7840e-481">**경고**</span><span class="sxs-lookup"><span data-stu-id="7840e-481">**Alerting**</span></span> | <span data-ttu-id="7840e-482">보안 이벤트 경고 사례 및 절차를 관리하는 정책 설명서를 제공합니다.</span><span class="sxs-lookup"><span data-stu-id="7840e-482">Provide policy documentation that governs security event alerting practices and procedures.</span></span>|
|| <span data-ttu-id="7840e-483">권한 있는 계정 생성 또는 수정, 바이러스 또는 맬웨어 이벤트, 이벤트 로그 변조, IDPS 또는 WAF 이벤트와 같은 유형의 보안 이벤트에 대해 즉시 경고가 트리거되는 데모 증거를 제공합니다.</span><span class="sxs-lookup"><span data-stu-id="7840e-483">Provide demonstrable evidence that alerts are triggered for immediate triage for the following types of security events: Privileged account creation or modifications, Virus or malware events, Event log tampering, IDPS or WAF events</span></span>
|<span data-ttu-id="7840e-484">**리스크 관리**</span><span class="sxs-lookup"><span data-stu-id="7840e-484">**Risk management**</span></span>|<span data-ttu-id="7840e-485">공식적인 정보 보안 위험 관리 프로세스가 설정되었다는 악의적인 증거를 제공합니다.</span><span class="sxs-lookup"><span data-stu-id="7840e-485">Provide demonstratable evidence that a formal information security risk management process is established.</span></span>|
||<span data-ttu-id="7840e-486">최소한 매년 공식적인 위험 평가가 수행된다고 입증할 수 있는 증거를 제공합니다.</span><span class="sxs-lookup"><span data-stu-id="7840e-486">Provide demonstrable evidence that a formal risk assessment occurs annually, at a minimum.</span></span>|
||<span data-ttu-id="7840e-487">정보 보안 위험 평가에 위협, 취약성 또는 동등한 증거가 포함되어 있는 데모 증거를 제공합니다.</span><span class="sxs-lookup"><span data-stu-id="7840e-487">Provide demonstrable evidence that the information security risk assessment includes threats, vulnerabilities, or the equivalent.</span></span>|
||<span data-ttu-id="7840e-488">정보 보안 위험 평가에 영향, 가능성 위험 행렬 또는 그에 해당하는 증거를 제공합니다.</span><span class="sxs-lookup"><span data-stu-id="7840e-488">Provide demonstrable evidence that the information security  risk assessment includes impact, likelihood risk matrix, or the equivalent.</span></span>|
||<span data-ttu-id="7840e-489">정보 보안 위험 평가에 위험 등록 및 처리 계획이 포함되어 있는 데모 증거를 제공합니다.</span><span class="sxs-lookup"><span data-stu-id="7840e-489">Provide demonstrable evidence that the information security risk assessment includes a risk register and treatment plan.</span></span>|
|<span data-ttu-id="7840e-490">**사고 대응**</span><span class="sxs-lookup"><span data-stu-id="7840e-490">**Incident response**</span></span>|<span data-ttu-id="7840e-491">IRP(보안 인시던트 대응 계획)를 제공합니다.</span><span class="sxs-lookup"><span data-stu-id="7840e-491">Provide the security incident response plan (IRP).</span></span>|
||<span data-ttu-id="7840e-492">보안 IRP에 결제 브랜드 및 인수자, 규제 기관, 감독 기관, 디렉터 및 고객과 같은 주요 이해 관계자에게 시기 적절한 알림을 제공하기 위한 문서화된 통신 프로세스가 포함되어 있습니다.</span><span class="sxs-lookup"><span data-stu-id="7840e-492">Provide demonstrable evidence that the security IRP includes a documented communication process to ensure timely notification to key stakeholders, such as payment brands and acquirers, regulatory bodies, supervisory authorities, directors, and customers.</span></span>|
||<span data-ttu-id="7840e-493">인시던트 대응 팀의 모든 구성원이 연례 교육 또는 표 상위 연습을 완료했다는 데 입증할 수 있는 증거를 제공하세요.</span><span class="sxs-lookup"><span data-stu-id="7840e-493">Provide demonstrable evidence that all member of the incident response team have completed annual training or a table top exercise.</span></span>|
||<span data-ttu-id="7840e-494">학습된 교훈 또는 조직 변경 내용에 따라 업데이트된 보안 IRP를 표시하는 데 사용할 수 있는 증거를 제공합니다.</span><span class="sxs-lookup"><span data-stu-id="7840e-494">Provide demonstrable evidence to show the security IRP is updated based on lessons learned or organizational changes.</span></span>|

## <a name="data-handling-security-and-privacy"></a><span data-ttu-id="7840e-495">데이터 처리 보안 및 개인 정보</span><span class="sxs-lookup"><span data-stu-id="7840e-495">Data Handling Security and Privacy</span></span>

<span data-ttu-id="7840e-496">응용 프로그램 사용자, 중간 서비스 및 ISV 시스템 간에 전송되는 데이터는 최소 TLS v1.1을 지원하는 TLS 연결을 통해 암호화로 보호해야 합니다. *부록* [**A를 참조하세요.**](#appendix-a)</span><span class="sxs-lookup"><span data-stu-id="7840e-496">Data in transit between the application user, intermediary services, and ISV’s systems will be required to be protected by encryption through a TLS connection supporting a minimum of TLS v1.1.*See* [**Appendix A**](#appendix-a).</span></span>

<span data-ttu-id="7840e-497">응용 프로그램에서 M365 데이터를 검색하고 저장하는 경우 부록 B에 정의된 사양을 따르는 데이터 저장소 암호화 체계를 [**구현하는 데 필요합니다.**](#appendix-a)</span><span class="sxs-lookup"><span data-stu-id="7840e-497">Where your application retrieves and stores M365 data you will be required to implement a data storage encryption scheme that follows the specification as defined in [**Appendix B**](#appendix-a).</span></span>

### <a name="controls"></a><span data-ttu-id="7840e-498">컨트롤</span><span class="sxs-lookup"><span data-stu-id="7840e-498">Controls</span></span>

|<span data-ttu-id="7840e-499">**컨트롤 패밀리**</span><span class="sxs-lookup"><span data-stu-id="7840e-499">**Control Family**</span></span>| <span data-ttu-id="7840e-500">**컨트롤**</span><span class="sxs-lookup"><span data-stu-id="7840e-500">**Controls**</span></span> |
| -----------------------|-------------------------------- |
|<span data-ttu-id="7840e-501">**전송 중 데이터**</span><span class="sxs-lookup"><span data-stu-id="7840e-501">**Data in Transit**</span></span>| <span data-ttu-id="7840e-502">TLS 구성이 TLS 프로필 구성 요구 사항 내에서 암호화 요구 사항을 충족하거나 초과하는 악의적인 [증거를 제공합니다.](https://docs.microsoft.com/microsoft-365-app-certification/docs/certification-submission-guide#appendix-a)</span><span class="sxs-lookup"><span data-stu-id="7840e-502">Provide demonstratable evidence that TLS configuration meets or exceeds the encryption requirements within the [TLS profile configuration requirements](https://docs.microsoft.com/microsoft-365-app-certification/docs/certification-submission-guide#appendix-a)</span></span>|
||<span data-ttu-id="7840e-503">웹 요청을 처리하는 모든 공용 서비스에서 TLS 압축을 사용하지 않도록 설정했다는 악의적인 증거를 제공합니다.</span><span class="sxs-lookup"><span data-stu-id="7840e-503">Provide demonstratable evidence that TLS compression is disabled across all public-facing services that handle web requests.</span></span>|
||<span data-ttu-id="7840e-504">TLS HTTP 엄격한 전송 보안이 사용하도록 설정되고 모든 사이트 전체에서 >= 15552000으로 구성되고 강해진 증거를 제공합니다.</span><span class="sxs-lookup"><span data-stu-id="7840e-504">Provide demonstratable evidence that TLS HTTP strict transport security is enabled and configured to >= 15552000 across all sites.</span></span>|
|<span data-ttu-id="7840e-505">**미사시 데이터**</span><span class="sxs-lookup"><span data-stu-id="7840e-505">**Data at Rest**</span></span>| <span data-ttu-id="7840e-506">AES, 128비트 및 256비트의 암호화 키 크기와 같은 암호화 알고리즘을 사용하여 미사용 데이터가 암호화 프로필 요구 사항에 따라 인라인으로 암호화되고 있는 악의적인 증거를 제공합니다.</span><span class="sxs-lookup"><span data-stu-id="7840e-506">Provide demonstratable evidence that data at rest is encrypted inline with the encryption profile requirements, using encryption algorithms such as AES, Blowfish, TDES and encryption key sizes of 128-bit, and 256-bit.</span></span>|
||<span data-ttu-id="7840e-507">해시 기능 또는 메시지 인증(HMAC-SHA1)은 암호화 프로필 요구 사항을 사용하여 미사용 데이터를 보호하는 데만 사용되는 악의적인 증거를 제공합니다.</span><span class="sxs-lookup"><span data-stu-id="7840e-507">Provide demonstratable evidence that hash function or message authentication (HMAC-SHA1) is only used to protect data at rest inline with encryption profile requirements.</span></span>|
||<span data-ttu-id="7840e-508">저장 위치 및 데이터를 보호하는 데 사용되는 암호화를 포함하여 저장된 모든 데이터를 표시하는 인벤토리를 제공합니다.</span><span class="sxs-lookup"><span data-stu-id="7840e-508">Provide an inventory showing all stored data, including storage location and encryption used to protect the data.</span></span>|
|<span data-ttu-id="7840e-509">**데이터 보존 및 삭제**</span><span class="sxs-lookup"><span data-stu-id="7840e-509">**Data Retention and Disposal**</span></span>|<span data-ttu-id="7840e-510">승인 및 문서화된 데이터 보존 기간이 공식적으로 설정되었다는 악의적인 증거를 제공합니다.</span><span class="sxs-lookup"><span data-stu-id="7840e-510">Provide demonstratable evidence that an approved and documented data retention period is formally established.</span></span>|
||<span data-ttu-id="7840e-511">보존된 데이터가 정의된 보존 기간과 일치하는 악의적인 증거를 제공합니다.</span><span class="sxs-lookup"><span data-stu-id="7840e-511">Provide demonstratable evidence that retained data matches defined retention period.</span></span>|
||<span data-ttu-id="7840e-512">보존 기간이 지난 후 데이터를 안전하게 삭제하기 위해 프로세스가 설정되어 있는 악의적인 증거를 제공합니다.</span><span class="sxs-lookup"><span data-stu-id="7840e-512">Provide demonstratable evidence that processes are in place to securely delete data after its retention period.</span></span>|
|<span data-ttu-id="7840e-513">**데이터 액세스 관리**</span><span class="sxs-lookup"><span data-stu-id="7840e-513">**Data Access Management**</span></span>|<span data-ttu-id="7840e-514">업무 정당성 등 데이터 또는 암호화 키에 액세스할 수 있는 모든 개인 목록을 제공합니다.</span><span class="sxs-lookup"><span data-stu-id="7840e-514">Provide a list of all individuals with access to data or encryption keys, including the business justification.</span></span>|
||<span data-ttu-id="7840e-515">데이터 또는 암호화 키에 대한 액세스 권한이 있는 샘플링된 개인이 공식적으로 승인되어 업무 기능에 필요한 권한을 자세히 설명하는 악의적인 증거를 제공합니다.</span><span class="sxs-lookup"><span data-stu-id="7840e-515">Provide demonstratable evidence that the sampled individuals who have access to data or encryption keys were formally approved, detailing privileges required for their job function.</span></span>|
||<span data-ttu-id="7840e-516">데이터 또는 암호화 키에 대한 액세스 권한이 있는 샘플링된 개인에게 승인에 포함된 권한만 갖는 악의적인 증거를 제공합니다.</span><span class="sxs-lookup"><span data-stu-id="7840e-516">Provide demonstratable evidence that the sampled individuals who have access to data or encryption keys only have the privileges included in the approval.</span></span>|
||<span data-ttu-id="7840e-517">고객 데이터가 공유되는 모든 타사 목록을 제공합니다.</span><span class="sxs-lookup"><span data-stu-id="7840e-517">Provide a list of all third-parties that customer data is shared with.</span></span>|
||<span data-ttu-id="7840e-518">고객 데이터를 사용하는 모든 타사가 공유 계약을 체결했다는 악의적인 증거를 제공합니다.</span><span class="sxs-lookup"><span data-stu-id="7840e-518">Provide demonstratable evidence that all third-parties consuming customer data have sharing agreements in place.</span></span>|
|<span data-ttu-id="7840e-519">**GDPR(해당되는** 경우)</span><span class="sxs-lookup"><span data-stu-id="7840e-519">**GDPR** (If Applicable)</span></span>| <span data-ttu-id="7840e-520">문서화된 SAR(주체 액세스 요청) 프로세스를 제공하고 데이터 주체가 SARS를 발생시 이를 입증하는 증거를 제공합니다.</span><span class="sxs-lookup"><span data-stu-id="7840e-520">Provide a documented subject access request (SAR) process and provide evidence demonstrating that data subjects are able to raise SARs.</span></span>|
||<span data-ttu-id="7840e-521">SAR에 응답할 때 데이터 주체 데이터의 모든 위치를 식별할 수 있는 악의적인 증거를 제공합니다.</span><span class="sxs-lookup"><span data-stu-id="7840e-521">Provide demonstratable evidence that you are able to identify all locations of data subjects' data when responding to a SAR.</span></span>|
||<span data-ttu-id="7840e-522">회사 세부 정보(이름, 주소 등)를 포함해야 하는 개인 정보 취급 방침을 유지 관리합니다.</span><span class="sxs-lookup"><span data-stu-id="7840e-522">You maintain a privacy notice which should contain the companies details (Name, Address, etc..).</span></span>|
||<span data-ttu-id="7840e-523">처리되는 개인 데이터의 유형을 설명해야 하는 개인 정보 취급 방침을 유지 관리합니다.</span><span class="sxs-lookup"><span data-stu-id="7840e-523">You maintain a privacy notice which should explain the types of personal data being processed.</span></span>|
||<span data-ttu-id="7840e-524">개인 데이터 처리의 법률성을 설명해야 하는 개인 정보 취급 방침을 유지 관리합니다.</span><span class="sxs-lookup"><span data-stu-id="7840e-524">You maintain a privacy notice which should explain the lawfulness of processing personal data</span></span>|
||<span data-ttu-id="7840e-525">데이터 주체의 권리: 정보주체의 정보 제공 권한, 데이터 주체의 액세스 권한, 삭제권, 처리 제한권, 데이터 이식성, 이의 제기권, 프로파일링을 비롯한 자동화된 의사 결정과 관련한 권리에 대해 자세히 설명하는 개인 정보 취급 방침을 유지 관리합니다.</span><span class="sxs-lookup"><span data-stu-id="7840e-525">You maintain a privacy notice which explains in details the data subject's rights: Right to be informed, Right of access by the data subject, Right to erasure, Right to restriction of processing, Right to data portability, Right to object, Rights in relation to automated decision-making, including profiling.</span></span>|
|| <span data-ttu-id="7840e-526">개인 데이터가 보관되는 기간을 설명해야 하는 개인 정보 취급 방침을 유지 관리합니다.</span><span class="sxs-lookup"><span data-stu-id="7840e-526">You maintain a privacy notice which should explain how long personal data will be kept for.</span></span>|

## <a name="optional-external-compliance-frameworks-review"></a><span data-ttu-id="7840e-527">선택적 외부 준수 프레임워크 검토</span><span class="sxs-lookup"><span data-stu-id="7840e-527">Optional External Compliance Frameworks Review</span></span>

<span data-ttu-id="7840e-528">필수는 아니며, 현재 ISO 27001, PCI DSS 또는 SOC2를 준수하는 경우 이러한 인증을 사용하여 일부 Microsoft 365 인증 컨트롤을 충족할 수 있습니다.</span><span class="sxs-lookup"><span data-stu-id="7840e-528">Although it is not required, if you are currently in compliance with ISO 27001, PCI DSS, or SOC2, you can elect to use these certifications to satisfy some of the Microsoft 365 Certification controls.</span></span> <span data-ttu-id="7840e-529">인증 분석가가 기존 외부 보안 프레임워크를 인증 사양에 Microsoft 365 시도합니다.</span><span class="sxs-lookup"><span data-stu-id="7840e-529">Certification analysts will try to align existing external security frameworks to the Microsoft 365 Certification specification.</span></span> <span data-ttu-id="7840e-530">그러나 지원 문서가 외부 보안 프레임워크 감사/평가의 일부로 Microsoft 365 인증 컨트롤이 평가된다는 보장을 제공할 수 없는 경우 해당 컨트롤이 적용되고 있는 추가 증거를 제공해야 합니다.</span><span class="sxs-lookup"><span data-stu-id="7840e-530">However, if supporting documentation is unable to provide assurance that Microsoft 365 Certification controls were assessed as part of the external security frameworks audit/assessment you will need to provide additional evidence of the said controls being in place.</span></span>

<span data-ttu-id="7840e-531">설명서는 Microsoft 365 인증에 대한 범위 내 환경이 이러한 외부 보안 프레임워크의 범위 내에 포함되어 있는 것을 적절하게 증명해야 합니다.</span><span class="sxs-lookup"><span data-stu-id="7840e-531">Documentation must adequately demonstrate that the in-scope environment for the Microsoft 365 Certification was included within the scope of these external security frameworks.</span></span> <span data-ttu-id="7840e-532">이러한 보안 프레임워크의 유효성 검사는 외부 타사에서 수행한 유효한 인증의 증거를 수락하여 이행됩니다.</span><span class="sxs-lookup"><span data-stu-id="7840e-532">Validation of these security frameworks will be fulfilled by accepting evidence of valid certifications conducted by reputable external third-party companies.</span></span> <span data-ttu-id="7840e-533">이러한 명명된 회사는 관련 규정 준수 프로그램에 대한 국제 인증 기관의 구성원이 되어야 합니다.</span><span class="sxs-lookup"><span data-stu-id="7840e-533">These reputable companies must be members of international accreditation bodies for relevant compliance programs.</span></span> <span data-ttu-id="7840e-534">PCI DSS에 대한 ISO 27001 및 QSA(적격 보안 평가자)에 대한 ISO 인증 및 적합성 표준을 참조합니다.</span><span class="sxs-lookup"><span data-stu-id="7840e-534">See ISO Certification and Conformity Standards for ISO 27001 and Qualified Security Assessors (QSA) for PCI DSS.</span></span>

<span data-ttu-id="7840e-535">다음 표에서는 이 유효성 검사 프로세스의 일부로 인증 분석가가 요구하는 외부 프레임워크 및 설명서를 강조합니다.</span><span class="sxs-lookup"><span data-stu-id="7840e-535">The following table highlights the external frameworks and documentation required by certification analysts as part of this validation process:</span></span>

| <span data-ttu-id="7840e-536">**Standard**</span><span class="sxs-lookup"><span data-stu-id="7840e-536">**Standard**</span></span> | <span data-ttu-id="7840e-537">**요구 사항**</span><span class="sxs-lookup"><span data-stu-id="7840e-537">**Requirements**</span></span> |
| ----- | ----- |
| <span data-ttu-id="7840e-538">**[ISO 27001](#iso-27001)**</span><span class="sxs-lookup"><span data-stu-id="7840e-538">**[ISO 27001](#iso-27001)**</span></span> | <span data-ttu-id="7840e-539">공개적인 SOA(적용성 명세서) 버전과 발급된 ISO 27001 인증서 복사본이 필요합니다. </span><span class="sxs-lookup"><span data-stu-id="7840e-539">A public facing version of the **Statement of Applicability** (SOA) and a copy of the ISO 27001 certificate issued will be required.</span></span>  <span data-ttu-id="7840e-540">SOA는 114개 정보 보안 컨트롤 각각에 대한 위치를 요약하여 ISO 27001 인증서에 자세히 설명되지 않은 컨트롤을 제외하는지 식별하는 데 사용됩니다.</span><span class="sxs-lookup"><span data-stu-id="7840e-540">The SOA summarizes your position on each of the 114 information security controls and  will be used to identify if any exclusion of controls that are not satisfactorily detailed in the ISO 27001 certificate.</span></span> <span data-ttu-id="7840e-541">SOA의 공용 버전을 검토하여 이를 확인할 수 없는 경우, ISO 27001을 사용하여 일부 인증 사양 컨트롤의 유효성을 검사하는 경우 분석가가 전체 SOA에 액세스해야 할 Microsoft 365 있습니다.</span><span class="sxs-lookup"><span data-stu-id="7840e-541">If this can't be determined by reviewing the public facing version of the SOA, the analyst might need access to the full SOA if ISO 27001 will be used to validate some of the Microsoft 365 Certification Specification controls.</span></span>  <span data-ttu-id="7840e-542">분석가는 ISO 27001 평가 활동의 범위 유효성을 검사하는 것 외에도 위에서 설명한 대로 감사 회사의 유효성을 확인할 수 있습니다.</span><span class="sxs-lookup"><span data-stu-id="7840e-542">In addition to validating the scope of the ISO 27001 assessment activities, the analysts will also confirm the validity of the audit company as described above.</span></span>|
|<span data-ttu-id="7840e-543">**[PCI DSS](#pci-dss)**</span><span class="sxs-lookup"><span data-stu-id="7840e-543">**[PCI DSS](#pci-dss)**</span></span>| <span data-ttu-id="7840e-544">범위 내 응용 프로그램 및 시스템 구성 요소를 명확하게 식별하는 유효한 AOC(수준 **1** 준수) 문서가 제공되어야 합니다.</span><span class="sxs-lookup"><span data-stu-id="7840e-544">A valid **Level 1 Attestation of Compliance** (AOC) document must be provided clearly identifying the in-scope application and system components.</span></span>  <span data-ttu-id="7840e-545">자체 평가 **AOC는 모임 보안** 모범 사례의 증거로 받아들여지지 않습니다.</span><span class="sxs-lookup"><span data-stu-id="7840e-545">A self-assessment AOC **will not** be accepted as evidence of meeting security best practices.</span></span> <span data-ttu-id="7840e-546">AOC는 PCI DSS 평가의 일부로 평가되고 Microsoft 365 인증 사양 컨트롤을 확인하는 데 사용됩니다.</span><span class="sxs-lookup"><span data-stu-id="7840e-546">The AOC will be used to determine which of the Microsoft 365 Certification Specification controls have been evaluated and confirmed as part of the PCI DSS assessment.</span></span>|
|<span data-ttu-id="7840e-547">**[SOC 2](#soc-2)**</span><span class="sxs-lookup"><span data-stu-id="7840e-547">**[SOC 2](#soc-2)**</span></span>|<span data-ttu-id="7840e-548">**SOC 2(유형 I** 또는 II 유형) 보고서는 이 Microsoft 365 인증 사양 내의 평가 컨트롤에 대한 적합성의 증거로 사용하려면 현재(지난 15개월 내에 발행하고 지난 27개월 내에 시작된 선언된 기간)되어야 합니다.</span><span class="sxs-lookup"><span data-stu-id="7840e-548">The **SOC 2 (Type I or Type II)** report must be current (issued within the last 15 months and the declared time period started within the last 27 months) to be used as evidence of conformity with any of the assessment controls within this Microsoft 365 Certification Specification.</span></span>|

<span data-ttu-id="7840e-549">외부 보안 프레임워크가 Publisher 증명 내에 포함된 경우 인증 분석가가 Microsoft 365 인증 평가의 일부로 해당 보안 준수 프레임워크의 유효성을 검사해야 합니다.</span><span class="sxs-lookup"><span data-stu-id="7840e-549">If external security frameworks have been included within the Publisher Attestation, certification analysts will need to check the validity of those security compliance frameworks as part of the Microsoft 365 Certification assessment.</span></span>

|<span data-ttu-id="7840e-550">**프레임워크**</span><span class="sxs-lookup"><span data-stu-id="7840e-550">**Framework**</span></span> | <span data-ttu-id="7840e-551">**추가 고려 사항**</span><span class="sxs-lookup"><span data-stu-id="7840e-551">**Additional considerations**</span></span> |
|-------------- | --------------------|
|<span data-ttu-id="7840e-552">ISO 27001</span><span class="sxs-lookup"><span data-stu-id="7840e-552">ISO 27001</span></span>| <span data-ttu-id="7840e-553">[**부록 C:**](#appendix-c)Evidence Collection – ISO 27001의 델타</span><span class="sxs-lookup"><span data-stu-id="7840e-553">[**Appendix C**](#appendix-c): Evidence Collection – Deltas for ISO 27001.</span></span>|
|<span data-ttu-id="7840e-554">PCI DSS</span><span class="sxs-lookup"><span data-stu-id="7840e-554">PCI DSS</span></span> | <span data-ttu-id="7840e-555">[**부록 D:**](#appendix-d)증거 컬렉션 - PCI DSS용 델타.</span><span class="sxs-lookup"><span data-stu-id="7840e-555">[**Appendix D**](#appendix-d): Evidence Collection – Deltas for PCI DSS.</span></span>|
|<span data-ttu-id="7840e-556">SOC 2</span><span class="sxs-lookup"><span data-stu-id="7840e-556">SOC 2</span></span>| <span data-ttu-id="7840e-557">[**부록 E**](#appendix-e): 증거 컬렉션 - SOC 2의 델타</span><span class="sxs-lookup"><span data-stu-id="7840e-557">[**Appendix E**](#appendix-e): Evidence Collection – Deltas for SOC 2.</span></span>|

> [!NOTE]
> <span data-ttu-id="7840e-558">위에서 언급한 외부 보안 표준/프레임워크는 일부 Microsoft 365 인증 컨트롤을 충족하기 위한 증거로 제출될 수 있습니다. Microsoft 365 인증을 통과해도 해당 표준/프레임워크에 대한 감사를 통과하는 것은 의미가 없습니다.</span><span class="sxs-lookup"><span data-stu-id="7840e-558">Although the above-mentioned external security standards/frameworks can be submitted as evidence to meet some of the Microsoft 365 Certification controls, passing the Microsoft 365 Certification doesn't mean that you will successfully pass an audit against those standards/frameworks.</span></span> <span data-ttu-id="7840e-559">Microsoft 365 인증 사양은 Microsoft가 보안 자세를 참조하여 보증 수준을 얻을 수 있도록 하는 보안 표준/프레임워크의 작은 하위 집합에 불과합니다.</span><span class="sxs-lookup"><span data-stu-id="7840e-559">The Microsoft 365 Certification Specification is only a small subset of those security standards/frameworks that allows Microsoft to gain a level of assurance in reference to your security posture.</span></span>


### <a name="requirements-to-use-external-compliance-frameworks"></a><span data-ttu-id="7840e-560">외부 준수 프레임워크를 사용하기 위한 요구 사항</span><span class="sxs-lookup"><span data-stu-id="7840e-560">Requirements to use external compliance frameworks</span></span>

<span data-ttu-id="7840e-561">&#x2713; 앱/추가 기능 지원 환경  및 모든 지원  비즈니스 프로세스는 지원되는 외부 보안 준수 프레임워크의 범위 내에 포함되어야 합니다. 제공된 설명서에 명확하게 표시되어야 합니다.</span><span class="sxs-lookup"><span data-stu-id="7840e-561">&#x2713; The App/Add-in supporting environment **AND** any supporting business processes **MUST** be included within the scope of any supported external security compliance frameworks and must be clearly indicated in supplied documentation.</span></span>

<span data-ttu-id="7840e-562">&#x2713; 지원되는 외부 보안 준수  프레임워크는 현재(예: 지난 12개월 이내 또는 재평가가 현재 수행되고 증거를 제공될 수 있는 경우 15개월 이내)에 있어야 합니다.</span><span class="sxs-lookup"><span data-stu-id="7840e-562">&#x2713; Supported external security compliance frameworks **MUST** be current, i.e. within the past 12 months (or within 15months if the re-assessment is currently being carried out and evidence can be provided).</span></span>

<span data-ttu-id="7840e-563">&#x2713; 지원되는 외부 보안 준수  프레임워크는 독립적인 공인 회사에서 수행되어야 합니다.</span><span class="sxs-lookup"><span data-stu-id="7840e-563">&#x2713; Supported external security compliance frameworks **MUST** be carried out by an independent accredited company.</span></span>

## <a name="appendix-a"></a><span data-ttu-id="7840e-564">부록 A</span><span class="sxs-lookup"><span data-stu-id="7840e-564">Appendix A</span></span>

### <a name="tls-profile-configuration-requirements"></a><span data-ttu-id="7840e-565">TLS 프로필 구성 요구 사항</span><span class="sxs-lookup"><span data-stu-id="7840e-565">TLS Profile configuration requirements</span></span>

<span data-ttu-id="7840e-566">가상 네트워크, 클라우드 서비스 또는 데이터 센터 내에서 모든 네트워크 트래픽은 최소 TLS v1.1(TLS v1.2+권장) 또는 기타 적용 가능한 프로토콜로 보호해야 합니다.</span><span class="sxs-lookup"><span data-stu-id="7840e-566">All network traffic, whether within a virtual network, cloud service, or a data center, must be protected with a minimum of TLS v1.1 (TLS v1.2+ is recommended) or other applicable protocol.</span></span> <span data-ttu-id="7840e-567">이 요구 사항은 예외입니다.</span><span class="sxs-lookup"><span data-stu-id="7840e-567">Exceptions to this requirement are:</span></span>

* <span data-ttu-id="7840e-568">**HTTP-HTTPS 리디렉션**.</span><span class="sxs-lookup"><span data-stu-id="7840e-568">**HTTP-to-HTTPS redirect**.</span></span> <span data-ttu-id="7840e-569">앱은 HTTP를 통해 응답하여 클라이언트를 HTTPS로 리디렉션할 수 있지만 응답에 중요한 데이터(쿠키, 헤더, 콘텐츠)가 포함되어 있지는 않습니다.</span><span class="sxs-lookup"><span data-stu-id="7840e-569">Your app can respond over HTTP to redirect clients to HTTPS, but the response must not contain any sensitive data (cookies, headers, content).</span></span> <span data-ttu-id="7840e-570">HTTPS로 리디렉션하고 상태 프로브에 응답하는 것 외의 다른 HTTP 응답은 허용되지 않습니다.</span><span class="sxs-lookup"><span data-stu-id="7840e-570">No other HTTP responses other than redirects to HTTPS and responding to health probes are allowed.</span></span> <span data-ttu-id="7840e-571">아래를 참조하세요.</span><span class="sxs-lookup"><span data-stu-id="7840e-571">See below.</span></span>
* <span data-ttu-id="7840e-572">**상태 프로브.**</span><span class="sxs-lookup"><span data-stu-id="7840e-572">**Health probes**.</span></span> <span data-ttu-id="7840e-573">앱은 검사자에서 **HTTPS** 상태 프로브가 지원되지 않는 경우 HTTP를 통해 상태 프로브에 응답할 수 있습니다.</span><span class="sxs-lookup"><span data-stu-id="7840e-573">Your app can respond to health probes over HTTP **only if** HTTPS health probes are not supported by the checking party.</span></span>
* <span data-ttu-id="7840e-574">**인증서 액세스**.</span><span class="sxs-lookup"><span data-stu-id="7840e-574">**Certificate access**.</span></span> <span data-ttu-id="7840e-575">HTTP를 통해 인증서 유효성 검사 및 해지 확인을 위해 CRL, OCSP 및 AIA 끝점에 액세스할 수 있습니다.</span><span class="sxs-lookup"><span data-stu-id="7840e-575">Access to CRL, OCSP, and AIA endpoints for the purposes of certificate validation and revocation checking is allowed over HTTP.</span></span>
* <span data-ttu-id="7840e-576">**로컬 통신**.</span><span class="sxs-lookup"><span data-stu-id="7840e-576">**Local communications**.</span></span> <span data-ttu-id="7840e-577">앱은 운영 체제를 떠나지 않는 통신에 HTTP(또는 보호되지 않는 기타 프로토콜)를 사용할 수 있습니다.</span><span class="sxs-lookup"><span data-stu-id="7840e-577">Your app can use HTTP (or other non-protected protocols) for communications that do not leave the operating system, e.</span></span> <span data-ttu-id="7840e-578">g.</span><span class="sxs-lookup"><span data-stu-id="7840e-578">g.</span></span> <span data-ttu-id="7840e-579">localhost에 노출된 웹 서버 끝점에 연결합니다.</span><span class="sxs-lookup"><span data-stu-id="7840e-579">connecting to a web server endpoint exposed on localhost.</span></span>

<span data-ttu-id="7840e-580">TLS **압축을 사용하지** 않도록 설정해야 합니다.</span><span class="sxs-lookup"><span data-stu-id="7840e-580">TLS Compression **MUST** be disabled.</span></span>

## <a name="appendix-b"></a><span data-ttu-id="7840e-581">부록 B</span><span class="sxs-lookup"><span data-stu-id="7840e-581">Appendix B</span></span>

### <a name="encryption-profile-configuration-requirements"></a><span data-ttu-id="7840e-582">암호화 프로필 구성 요구 사항</span><span class="sxs-lookup"><span data-stu-id="7840e-582">Encryption Profile Configuration Requirements</span></span>

<span data-ttu-id="7840e-583">다음과 같이 암호화 기본 및 매개 변수만 허용됩니다.</span><span class="sxs-lookup"><span data-stu-id="7840e-583">Only cryptographic primitives and parameters are permitted as follows:</span></span>

### <a name="symmetric-cryptography"></a><span data-ttu-id="7840e-584">대칭형 암호화</span><span class="sxs-lookup"><span data-stu-id="7840e-584">Symmetric cryptography</span></span>

<span data-ttu-id="7840e-585">**Encryption**</span><span class="sxs-lookup"><span data-stu-id="7840e-585">**Encryption**</span></span>

<span data-ttu-id="7840e-586">&emsp;&#x2713; AES, BitLocker, 피싱 또는 TDES만 허용됩니다.</span><span class="sxs-lookup"><span data-stu-id="7840e-586">&emsp;&#x2713; Only AES, BitLocker, Blowfish or TDES are allowed.</span></span> <span data-ttu-id="7840e-587">지원되는 키 길이는 >=128(128, 192 및 256비트)으로 허용됩니다(256비트 키 권장).</span><span class="sxs-lookup"><span data-stu-id="7840e-587">Any of the supported key lengths >=128 are allowed (128, 192, and 256 bits) and may be used (256-bit keys are recommended).</span></span>

<span data-ttu-id="7840e-588">&emsp;&#x2713; CBC 모드만 허용됩니다.</span><span class="sxs-lookup"><span data-stu-id="7840e-588">&emsp;&#x2713; Only CBC mode is allowed.</span></span> <span data-ttu-id="7840e-589">모든 암호화 작업은 임의로 생성된 새로운 IV(초기화 벡터)를 사용해야 합니다.</span><span class="sxs-lookup"><span data-stu-id="7840e-589">Every encryption operation must use a fresh, randomly generated initialization vector (IV).</span></span>

<span data-ttu-id="7840e-590">&emsp;&#x2713; RC4와 같은 스트림 암호의 사용은 **허용되지** 않습니다.</span><span class="sxs-lookup"><span data-stu-id="7840e-590">&emsp;&#x2713; Use of stream ciphers, such as RC4, **IS NOT** allowed.</span></span>

<span data-ttu-id="7840e-591">**해시 함수**</span><span class="sxs-lookup"><span data-stu-id="7840e-591">**Hash functions**</span></span>

<span data-ttu-id="7840e-592">&emsp;&#x2713; 모든 새 코드는 SHA-256, SHA-384 또는 SHA-512(총칭 SHA-2)를 사용해야 합니다.</span><span class="sxs-lookup"><span data-stu-id="7840e-592">&emsp;&#x2713; All new code must use SHA-256, SHA-384, or SHA-512 (collectively referred to as SHA-2).</span></span> <span data-ttu-id="7840e-593">출력이 128비트 미만으로 줄어들 수 있습니다.</span><span class="sxs-lookup"><span data-stu-id="7840e-593">Output may be truncated to no less than 128 bits</span></span>

<span data-ttu-id="7840e-594">&emsp;&#x2713; 이유로만 SHA-1을 사용할 수 있습니다.</span><span class="sxs-lookup"><span data-stu-id="7840e-594">&emsp;&#x2713; SHA-1 may only be used for compatibility reasons.</span></span>

<span data-ttu-id="7840e-595">&emsp;&#x2713; 암호화되지 않은 응용 프로그램에도 MD5, MD4, MD2 및 기타 해시 함수를 사용할 수 없습니다.</span><span class="sxs-lookup"><span data-stu-id="7840e-595">&emsp;&#x2713; Use of MD5, MD4, MD2 and other hash functions IS NOT allowed, even for non-cryptographic applications.</span></span>

<span data-ttu-id="7840e-596">**메시지 인증**</span><span class="sxs-lookup"><span data-stu-id="7840e-596">**Message authentication**</span></span>

<span data-ttu-id="7840e-597">&emsp;&#x2713; 모든 새 코드는 승인된 해시 함수 중 하나와 함께 HMAC를 사용해야 합니다.</span><span class="sxs-lookup"><span data-stu-id="7840e-597">&emsp;&#x2713; All new code MUST use HMAC with one of the approved hash functions.</span></span> <span data-ttu-id="7840e-598">HMAC의 출력은 128비트 미만으로 줄어들 수 있습니다.</span><span class="sxs-lookup"><span data-stu-id="7840e-598">Output of HMAC may be truncated to no less than 128 bits.</span></span>

<span data-ttu-id="7840e-599">&emsp;&#x2713; HMAC-SHA1은 호환성을 위해만 사용할 수 있습니다.</span><span class="sxs-lookup"><span data-stu-id="7840e-599">&emsp;&#x2713; HMAC-SHA1 may only be used for compatibility reasons.</span></span>

<span data-ttu-id="7840e-600">&emsp;&#x2713; HMAC 키는 128비트 이상 있어야 합니다.</span><span class="sxs-lookup"><span data-stu-id="7840e-600">&emsp;&#x2713; HMAC key MUST be at least 128 bits.</span></span> <span data-ttu-id="7840e-601">256비트 키를 사용하는 것이 좋습니다.</span><span class="sxs-lookup"><span data-stu-id="7840e-601">256-bit keys are recommended.</span></span>

### <a name="asymmetric-algorithms"></a><span data-ttu-id="7840e-602">비대칭 알고리즘</span><span class="sxs-lookup"><span data-stu-id="7840e-602">Asymmetric algorithms</span></span>

<span data-ttu-id="7840e-603">**Encryption**</span><span class="sxs-lookup"><span data-stu-id="7840e-603">**Encryption**</span></span>

<span data-ttu-id="7840e-604">&emsp;&#x2713; RSA를 사용할 수 있습니다.</span><span class="sxs-lookup"><span data-stu-id="7840e-604">&emsp;&#x2713; RSA is allowed.</span></span> <span data-ttu-id="7840e-605">**키는** 2048비트 이상이면 OAEP 패딩을 사용해야 합니다.</span><span class="sxs-lookup"><span data-stu-id="7840e-605">Key **MUST** be at least 2048 bits and OAEP padding must be used.</span></span> <span data-ttu-id="7840e-606">PKCS 패딩은 호환성을 위해만 허용됩니다.</span><span class="sxs-lookup"><span data-stu-id="7840e-606">Use of PKCS padding only allowed for compatibility reasons.</span></span>

<span data-ttu-id="7840e-607">**서명**</span><span class="sxs-lookup"><span data-stu-id="7840e-607">**Signatures**</span></span>

<span data-ttu-id="7840e-608">&emsp;&#x2713; RSA를 사용할 수 있습니다.</span><span class="sxs-lookup"><span data-stu-id="7840e-608">&emsp;&#x2713; RSA is allowed.</span></span> <span data-ttu-id="7840e-609">**키는** 2048비트 이상 및 PSS 패딩을 사용해야 합니다.</span><span class="sxs-lookup"><span data-stu-id="7840e-609">Key **MUST** be at least 2048 bits and PSS padding must be used.</span></span> <span data-ttu-id="7840e-610">PKCS 패딩은 호환성을 위해만 허용됩니다.</span><span class="sxs-lookup"><span data-stu-id="7840e-610">Use of PKCS padding only allowed for compatibility reasons.</span></span>

<span data-ttu-id="7840e-611">&emsp;&#x2713;ECDSA를 사용할 수 있습니다.</span><span class="sxs-lookup"><span data-stu-id="7840e-611">&emsp;&#x2713;ECDSA is allowed.</span></span> <span data-ttu-id="7840e-612">**키는** 256비트 이상 있어야 합니다.</span><span class="sxs-lookup"><span data-stu-id="7840e-612">Key **MUST** be at least 256 bits.</span></span> <span data-ttu-id="7840e-613">NIST P-256, P-384 또는 P-521 곡선을 사용해야 합니다.</span><span class="sxs-lookup"><span data-stu-id="7840e-613">NIST P-256, P-384 or P-521 curve must be used.</span></span>

<span data-ttu-id="7840e-614">**키 Exchange**</span><span class="sxs-lookup"><span data-stu-id="7840e-614">**Key Exchange**</span></span>

<span data-ttu-id="7840e-615">&emsp;&#x2713; ECDH를 사용할 수 있습니다.</span><span class="sxs-lookup"><span data-stu-id="7840e-615">&emsp;&#x2713; ECDH is allowed.</span></span> <span data-ttu-id="7840e-616">**키는** 256비트 이상 있어야 합니다.</span><span class="sxs-lookup"><span data-stu-id="7840e-616">Key **MUST** be at least 256 bits.</span></span> <span data-ttu-id="7840e-617">NIST P-256, P-384 또는 P-521 곡선을 사용해야 합니다.</span><span class="sxs-lookup"><span data-stu-id="7840e-617">NIST P-256, P-384 or P-521 curve must be used.</span></span>

<span data-ttu-id="7840e-618">&emsp;&#x2713; ECDH를 사용할 수 있습니다.</span><span class="sxs-lookup"><span data-stu-id="7840e-618">&emsp;&#x2713; ECDH is allowed.</span></span> <span data-ttu-id="7840e-619">**키는** 256비트 이상 있어야 합니다.</span><span class="sxs-lookup"><span data-stu-id="7840e-619">Key **MUST** be at least 256 bits.</span></span> <span data-ttu-id="7840e-620">NIST P-256, P-384 또는 P-521 곡선을 사용해야 합니다.</span><span class="sxs-lookup"><span data-stu-id="7840e-620">NIST P-256, P-384 or P-521 curve must be used.</span></span>

## <a name="appendix-c"></a><span data-ttu-id="7840e-621">부록 C</span><span class="sxs-lookup"><span data-stu-id="7840e-621">Appendix C</span></span>

### <a name="evidence-collection--delta-for-iso-27001"></a><span data-ttu-id="7840e-622">Evidence 컬렉션 - ISO 27001 델타</span><span class="sxs-lookup"><span data-stu-id="7840e-622">Evidence Collection – Delta for ISO 27001</span></span>

<span data-ttu-id="7840e-623">ISO27001 규정 준수를 이미 획득한 경우 적어도 ISO 27001에서 다루지 않는 델타의 (간격)는 최소한 이 Microsoft 365 인증의 일부로 검토해야 합니다.</span><span class="sxs-lookup"><span data-stu-id="7840e-623">Where you have already attained ISO27001 compliance, the following delta’s (gaps) not wholly covered by ISO 27001 will, at a minimum, need to be reviewed as part of this Microsoft 365 Certification.</span></span>

> [!NOTE]
> <span data-ttu-id="7840e-624">Microsoft 365 인증 평가의 일부로 인증 분석가가 매핑된 ISO 27001 컨트롤이 ISO 27001 평가의 일부로 포함되지 않은지 여부를 결정하고 추가 보증을 제공하기 위해 포함된 것으로 확인된 샘플 컨트롤도 결정할 수 있습니다.</span><span class="sxs-lookup"><span data-stu-id="7840e-624">As part of your Microsoft 365 Certification assessment, the certification analyst will determine if any of the mapped ISO 27001 controls were not included as part of the ISO 27001 assessment and may also decide to sample controls that were found to be included to provide further assurance.</span></span> <span data-ttu-id="7840e-625">ISO 27001에서 누락된 모든 요구 사항은 인증 평가 Microsoft 365 포함되어야 합니다.</span><span class="sxs-lookup"><span data-stu-id="7840e-625">Any requirements missing from the ISO 27001 will need to be included within your Microsoft 365 Certification assessment activities.</span></span>

<span data-ttu-id="7840e-626">**맬웨어 보호 - 바이러스 백신**</span><span class="sxs-lookup"><span data-stu-id="7840e-626">**Malware Protection – Anti Virus**</span></span>

<span data-ttu-id="7840e-627">응용 프로그램 제어를 사용하여 맬웨어 보호가 적용 중이고 ISO 27001 내에서 맬웨어 보호가 것으로 조사된 경우 추가 조사가 필요하지 않습니다.</span><span class="sxs-lookup"><span data-stu-id="7840e-627">If malware protection is in place using application control and is attested to within ISO 27001 Report no further investigation is necessary.</span></span> <span data-ttu-id="7840e-628">응용 프로그램 제어가 없는 경우 인증 분석가가 환경 내에서 맬웨어가 발견되지 않도록 응용 프로그램 제어 메커니즘의 증거를 식별하고 평가해야 합니다.</span><span class="sxs-lookup"><span data-stu-id="7840e-628">If no application control is in place, certification analysts will need to identify and assess evidence of application control mechanisms to prevent detonation of malware within the environment.</span></span> <span data-ttu-id="7840e-629">이렇게 하면 다음이 필요할 수 있습니다.</span><span class="sxs-lookup"><span data-stu-id="7840e-629">This will require you to:</span></span>

* <span data-ttu-id="7840e-630">샘플링된 모든 시스템 구성 요소에서 바이러스 백신 소프트웨어가 실행되고 있는 것을 보여줄 수 있습니다.</span><span class="sxs-lookup"><span data-stu-id="7840e-630">Demonstrate that anti-virus software is running across all sampled system components.</span></span>

* <span data-ttu-id="7840e-631">바이러스 백신이 맬웨어를 자동으로 차단하거나, 경고를 차단하거나, 경고를 & 샘플링된 모든 시스템 구성 요소에 걸쳐 구성되어 있는지 보여 주도록 합니다.</span><span class="sxs-lookup"><span data-stu-id="7840e-631">Demonstrate that anti-virus is configured across all sampled system components to either automatically block malware, to quarantine & alert or to alert.</span></span>

* <span data-ttu-id="7840e-632">바이러스 백신 **소프트웨어는** 모든 활동을 기록하도록 구성해야 합니다.</span><span class="sxs-lookup"><span data-stu-id="7840e-632">Anti-virus software **MUST** be configured to log all activities.</span></span>

<span data-ttu-id="7840e-633">**패치 관리 - 패치**</span><span class="sxs-lookup"><span data-stu-id="7840e-633">**Patch Management – Patching**</span></span>

<span data-ttu-id="7840e-634">ISO 27001 감사에서는 이 범주를 구체적으로 평가하지 않는 경우 다음을 요구합니다.</span><span class="sxs-lookup"><span data-stu-id="7840e-634">As ISO 27001 audits do not specifically assess this category, this will require you to:</span></span>

* <span data-ttu-id="7840e-635">공급업체에서 더 이상 지원하지 않는  소프트웨어 구성 요소 및 운영 체제는 환경 내에서 사용되지 말아야 합니다.</span><span class="sxs-lookup"><span data-stu-id="7840e-635">Software components and operating systems no longer supported by the vendor **MUST** not be used within the environment.</span></span> <span data-ttu-id="7840e-636">지원 정책이 있어야 지원되지 않는 소프트웨어 구성 요소/운영 체제가 환경에서 제거되고 소프트웨어 구성 요소가 수명 종료될 때를 식별하는 프로세스가 있어야 합니다.</span><span class="sxs-lookup"><span data-stu-id="7840e-636">Supporting policies MUST be in place to ensure unsupported software components / operating systems will be removed from the environment and a process to identify when software components go end-of-life must be in place</span></span>

<span data-ttu-id="7840e-637">**취약점 검사**</span><span class="sxs-lookup"><span data-stu-id="7840e-637">**Vulnerability Scanning**</span></span>  

<span data-ttu-id="7840e-638">ISO 27001 감사에서는 이 범주를 구체적으로 평가하지 않는 경우 다음을 요구합니다.</span><span class="sxs-lookup"><span data-stu-id="7840e-638">As ISO 27001 audits do not specifically assess this category, this will require you to:</span></span>

* <span data-ttu-id="7840e-639">분기별 내부 및 외부 취약점 검사가 수행됩니다.</span><span class="sxs-lookup"><span data-stu-id="7840e-639">Demonstrate that quarterly internal and external vulnerability scanning is conducted.</span></span>

* <span data-ttu-id="7840e-640">다음과 같이 위험 순위에 따라 사양에 따라 취약점 수정을 위한 지원 설명서가 준비되어 있는지 확인</span><span class="sxs-lookup"><span data-stu-id="7840e-640">Confirm supporting documentation is in place for vulnerability remediation based on risk ranking and in line with the specification as follows:</span></span>
 
 <span data-ttu-id="7840e-641">&#x2713; 내부 검사에 대한 위험 순위와 함께 위험 및 높은 위험 문제를 모두 수정합니다.</span><span class="sxs-lookup"><span data-stu-id="7840e-641">&#x2713; Fix all Critical and Highs risk issues in-line with the risk ranking for Internal scanning.</span></span>
 
 <span data-ttu-id="7840e-642">&#x2713; 위험, 높은 위험 및 중간 위험 문제를 외부 검사에 대한 위험 순위와 함께 수정합니다.</span><span class="sxs-lookup"><span data-stu-id="7840e-642">&#x2713; Fix all Critical, Highs and Medium risk issues in-line with the risk ranking for external scanning.</span></span>
 
 <span data-ttu-id="7840e-643">&#x2713; 문서화한 취약점 수정 정책에 따라 수정이 수행되는 것을 보여 줄 수 있습니다.</span><span class="sxs-lookup"><span data-stu-id="7840e-643">&#x2713; Demonstrate that remediation is conducted in-line with the documented vulnerability remediation policy.</span></span>

<span data-ttu-id="7840e-644">**방화벽 - 방화벽(또는 동등한 기술)**</span><span class="sxs-lookup"><span data-stu-id="7840e-644">**Firewall – Firewalls (or equivalent technologies)**</span></span>

<span data-ttu-id="7840e-645">ISO 27001 감사에서는 이 범주를 구체적으로 평가하지 않는 경우 다음을 요구합니다.</span><span class="sxs-lookup"><span data-stu-id="7840e-645">As ISO 27001 audits do not specifically assess this category, this will require you to:</span></span>

* <span data-ttu-id="7840e-646">방화벽이 범위 내 환경의 경계에 설치되어 있는 것을 보여 줍니다.</span><span class="sxs-lookup"><span data-stu-id="7840e-646">Demonstrate that firewalls are installed on the boundary of the in-scope environment.</span></span>

* <span data-ttu-id="7840e-647">방화벽이 DMZ와 신뢰할 수 있는 네트워크 사이에 설치되어 있는 것을 보여 주시습니다.</span><span class="sxs-lookup"><span data-stu-id="7840e-647">Demonstrate that firewalls are installed between the DMZ and trusted networks.</span></span>

*   <span data-ttu-id="7840e-648">모든 공용 액세스가 DMZ에서 종료됩니다.</span><span class="sxs-lookup"><span data-stu-id="7840e-648">Demonstrate that all public access terminates in the DMZ.</span></span>

*   <span data-ttu-id="7840e-649">기본 관리 자격 증명이 라이브 환경에 설치하기 전에 변경된 경우를 보여 줍니다.</span><span class="sxs-lookup"><span data-stu-id="7840e-649">Demonstrate that default administrative credentials are changed prior to installation into the live environment.</span></span>

*   <span data-ttu-id="7840e-650">방화벽을 통해 허용된 모든 트래픽이 인증 프로세스를 통과하여 비즈니스 사당성에 따라 모든 트래픽에 대한 설명서를 작성하는 것을 입증합니다.</span><span class="sxs-lookup"><span data-stu-id="7840e-650">Demonstrate that all permitted traffic through the firewall(s) goes through an authorization process which results in the documentation of all traffic with a business justification.</span></span>

*   <span data-ttu-id="7840e-651">모든 방화벽이 명시적으로 정의되지 않은 트래픽을 떨어뜨리도록 구성되어 있는지를 보여줄 수 있습니다.</span><span class="sxs-lookup"><span data-stu-id="7840e-651">Demonstrate that all firewalls are configured to drop traffic not explicitly defined.</span></span>

*   <span data-ttu-id="7840e-652">방화벽이 콘솔이 아닌 모든 관리 인터페이스에서 강력한 암호화만 지원하고 있습니다.</span><span class="sxs-lookup"><span data-stu-id="7840e-652">Demonstrate that firewalls support only strong cryptography on all non-console administrative interfaces.</span></span>

*   <span data-ttu-id="7840e-653">인터넷에 노출되는 방화벽의 콘솔이 아닌 관리 인터페이스가 MFA를 지원하는지 보여줄 수 있습니다.</span><span class="sxs-lookup"><span data-stu-id="7840e-653">Demonstrate that firewall's non-console administrative interfaces exposed to the Internet support MFA.</span></span>

*   <span data-ttu-id="7840e-654">방화벽 규칙 검토가 적어도 6개월마다 수행됩니다.</span><span class="sxs-lookup"><span data-stu-id="7840e-654">Demonstrate that firewall rule reviews are conducted at least every 6 months</span></span>

<span data-ttu-id="7840e-655">**방화벽 - WAF(웹 응용 프로그램 방화벽)**</span><span class="sxs-lookup"><span data-stu-id="7840e-655">**Firewall – Web Application Firewalls (WAF)**</span></span>  

<span data-ttu-id="7840e-656">WAF가 배포되어 응용 프로그램이 노출될 수 있는 다양한 웹 응용 프로그램 위협 및 취약성으로부터 보호할 수 있는 추가 크레딧이 제공됩니다.</span><span class="sxs-lookup"><span data-stu-id="7840e-656">Additional credit will be provided if a WAF is deployed to help protect against the myriad of web application threats and vulnerabilities that the application can be exposed to.</span></span> <span data-ttu-id="7840e-657">WAF 또는 유사 WAF가 있는 경우 다음을 요구합니다.</span><span class="sxs-lookup"><span data-stu-id="7840e-657">When a WAF or similar is present, this will require you to:</span></span>

* <span data-ttu-id="7840e-658">WAF가 경고를 통해 활성 방어 모드 또는 더 많은 모니터링으로 구성되어 있는지를 보여줄 수 있습니다.</span><span class="sxs-lookup"><span data-stu-id="7840e-658">Demonstrate the WAF is configured in active defense mode or monitoring more with alerting.</span></span>

* <span data-ttu-id="7840e-659">WAF가 SSL 오프로드를 지원하도록 구성되어 있는지 보여줄 수 있습니다.</span><span class="sxs-lookup"><span data-stu-id="7840e-659">Demonstrate the WAF is configured to support SSL Offloading.</span></span>

* <span data-ttu-id="7840e-660">다음과 같은 대부분의 공격 유형으로부터 보호하기 위해 OWASP 핵심 규칙 집합(3.0 또는 3.1)에 따라 구성됩니다.</span><span class="sxs-lookup"><span data-stu-id="7840e-660">Is configured as per the OWASP Core Rule Set (3.0 or 3.1) to protect against most of the following attack types:</span></span>

<span data-ttu-id="7840e-661">&#x2713; 및 인코딩 문제를 해결합니다.</span><span class="sxs-lookup"><span data-stu-id="7840e-661">&#x2713; Protocol and encoding issues.</span></span>

<span data-ttu-id="7840e-662">&#x2713;, 요청 밀기 및 응답 분할을 요청합니다.</span><span class="sxs-lookup"><span data-stu-id="7840e-662">&#x2713; Header injection, request smuggling, and response splitting.</span></span>

<span data-ttu-id="7840e-663">&#x2713; 경로 트래버스 공격을 공격합니다.</span><span class="sxs-lookup"><span data-stu-id="7840e-663">&#x2713; File and path traversal attacks.</span></span>

<span data-ttu-id="7840e-664">&#x2713; RFI(원격 파일 포함) 공격을 제어합니다.</span><span class="sxs-lookup"><span data-stu-id="7840e-664">&#x2713; Remote file inclusion (RFI) attacks.</span></span>

<span data-ttu-id="7840e-665">&#x2713; 코드 실행 공격을 중지합니다.</span><span class="sxs-lookup"><span data-stu-id="7840e-665">&#x2713; Remote code execution attacks.</span></span>

<span data-ttu-id="7840e-666">&#x2713; PHP 주입 공격이 있습니다.</span><span class="sxs-lookup"><span data-stu-id="7840e-666">&#x2713; PHP-injection attacks.</span></span>

<span data-ttu-id="7840e-667">&#x2713; 스크립팅 공격을 수정합니다.</span><span class="sxs-lookup"><span data-stu-id="7840e-667">&#x2713; Cross-site scripting attacks.</span></span>

<span data-ttu-id="7840e-668">&#x2713; SQL 주입 공격.</span><span class="sxs-lookup"><span data-stu-id="7840e-668">&#x2713; SQL-injection attacks.</span></span>

<span data-ttu-id="7840e-669">&#x2713; 세션 수정 공격을 해결합니다.</span><span class="sxs-lookup"><span data-stu-id="7840e-669">&#x2713; Session-fixation attacks.</span></span>

<span data-ttu-id="7840e-670">**변경 컨트롤**</span><span class="sxs-lookup"><span data-stu-id="7840e-670">**Change Control**</span></span>

<span data-ttu-id="7840e-671">ISO 27001 감사는 변경 요청 프로세스의 일부 요소를 구체적으로 평가하지 않는 경우 다음을 요구합니다.</span><span class="sxs-lookup"><span data-stu-id="7840e-671">As ISO 27001 audits do not specifically assess some elements of Change Request processes, this will require you to:</span></span>

* <span data-ttu-id="7840e-672">변경 요청에 대한 자세한 내용은 다음과 같습니다.</span><span class="sxs-lookup"><span data-stu-id="7840e-672">Demonstrate that change requests have the following details:</span></span>

<span data-ttu-id="7840e-673">&#x2713; 영향</span><span class="sxs-lookup"><span data-stu-id="7840e-673">&#x2713; Documented impact.</span></span>

<span data-ttu-id="7840e-674">&#x2713; 테스트할 기능의 세부 정보입니다.</span><span class="sxs-lookup"><span data-stu-id="7840e-674">&#x2713; Details of what functionality testing is to be conducted.</span></span>

<span data-ttu-id="7840e-675">&#x2713; 절차에 대한 세부 정보입니다.</span><span class="sxs-lookup"><span data-stu-id="7840e-675">&#x2713; Details of any back-out procedures.</span></span>

* <span data-ttu-id="7840e-676">기능 테스트는 변경이 완료된 후에 수행됩니다.</span><span class="sxs-lookup"><span data-stu-id="7840e-676">Demonstrate that functionality testing is conducted after changes are completed.</span></span>

* <span data-ttu-id="7840e-677">기능 테스트가 수행된 후 변경 요청이 서명된 경우를 보여 집니다.</span><span class="sxs-lookup"><span data-stu-id="7840e-677">Demonstrate that change requests are signed off after functionality testing is conducted.</span></span>

<span data-ttu-id="7840e-678">**계정 관리**</span><span class="sxs-lookup"><span data-stu-id="7840e-678">**Account Management**</span></span>

<span data-ttu-id="7840e-679">ISO 27001 감사는 계정 관리 프로세스의 일부 요소를 구체적으로 평가하지 않는 경우 다음을 요구합니다.</span><span class="sxs-lookup"><span data-stu-id="7840e-679">As ISO 27001 audits do not specifically assess some elements of account management processes, this will require you to:</span></span>

*   <span data-ttu-id="7840e-680">재생 공격을 &#x2713;(예: MFA, Kerberos)를 구현하는 방법을 보여줄 수 있습니다.</span><span class="sxs-lookup"><span data-stu-id="7840e-680">Demonstrate how &#x2713;s are implemented to mitigate replay attacks (e.g. MFA, Kerberos).</span></span>
*   <span data-ttu-id="7840e-681">3개월 동안 사용되지 않은 계정을 사용하지 않도록 설정하거나 삭제하는 방법을 보여줄 수 있습니다.</span><span class="sxs-lookup"><span data-stu-id="7840e-681">Demonstrate how accounts that have not been used in 3 months are either disabled or deleted.</span></span>
*   <span data-ttu-id="7840e-682">&#x2713; 또는 기타 적절한 완화는 사용자 자격 증명을 보호하도록 구성해야 합니다.</span><span class="sxs-lookup"><span data-stu-id="7840e-682">&#x2713;  or other suitable mitigations must be configured to protect user credentials.</span></span> <span data-ttu-id="7840e-683">다음과 같은 최소 암호 정책을 지침으로 사용해야 합니다.</span><span class="sxs-lookup"><span data-stu-id="7840e-683">The following minimum password policy should be used as a guideline:</span></span>

<span data-ttu-id="7840e-684">&#x2713; 최소 암호 길이는 8자입니다.</span><span class="sxs-lookup"><span data-stu-id="7840e-684">&#x2713; Minimum password length of 8 characters.</span></span>

<span data-ttu-id="7840e-685">&#x2713; 계정 잠금 임계값은 10회를 넘지 않습니다.</span><span class="sxs-lookup"><span data-stu-id="7840e-685">&#x2713; Account lockout threshold of no more than 10 attempts.</span></span>
 
<span data-ttu-id="7840e-686">&#x2713; 암호의 최소 5개 암호 기록입니다.</span><span class="sxs-lookup"><span data-stu-id="7840e-686">&#x2713; Password history of a minimum of five passwords.</span></span>
 
<span data-ttu-id="7840e-687">&#x2713; 강력한 암호의 사용을 적용합니다.</span><span class="sxs-lookup"><span data-stu-id="7840e-687">&#x2713; Enforcement of the use of strong passwords.</span></span>
 
*   <span data-ttu-id="7840e-688">모든 원격 액세스 솔루션에 대해 MFA가 구성되어 있는지 보여 주십시오.</span><span class="sxs-lookup"><span data-stu-id="7840e-688">Demonstrate that MFA is configured for all remote access solutions.</span></span>

*   <span data-ttu-id="7840e-689">모든 원격 액세스 솔루션에 강력한 암호화가 구성되어 있는지 보여 주십시오.</span><span class="sxs-lookup"><span data-stu-id="7840e-689">Demonstrate that strong encryption is configured on all remote access solutions.</span></span>

*   <span data-ttu-id="7840e-690">공용 DNS 관리가 범위 내 환경 외부에 있는 경우 DNS를 수정할 수 있는 모든 사용자 계정은 MFA를 사용하도록 구성해야 합니다.</span><span class="sxs-lookup"><span data-stu-id="7840e-690">Where the management of Public DNS is outside of the in-scope environment, all user accounts able to make DNS modifications MUST be configured to use MFA.</span></span>

<span data-ttu-id="7840e-691">**침입 감지 및 방지(OPTIONAL)**</span><span class="sxs-lookup"><span data-stu-id="7840e-691">**Intrusion Detection and Prevention (OPTIONAL)**</span></span>

<span data-ttu-id="7840e-692">ISO 27001 감사에서는 IDPS(침입 감지 및 방지 서비스) 프로세스의 일부 요소를 구체적으로 평가하지 않는 경우 다음을 요구합니다.</span><span class="sxs-lookup"><span data-stu-id="7840e-692">As ISO 27001 audits do not specifically assess some elements of Intrusion Detection and Prevention Services (IDPS) processes, this will require you to:</span></span>

*   <span data-ttu-id="7840e-693">**IDPS는** 지원 환경의 경계에 배포해야 합니다.</span><span class="sxs-lookup"><span data-stu-id="7840e-693">IDPS **SHOULD** be deployed at the perimeter of the supporting environment.</span></span>

*   <span data-ttu-id="7840e-694">IDPS **서명은** 지난 날 내에 최신으로 유지해야 합니다.</span><span class="sxs-lookup"><span data-stu-id="7840e-694">IDPS signatures **SHOULD** be kept current, within the past day.</span></span>

*   <span data-ttu-id="7840e-695">TLS  검사를 위해 IDPS를 구성해야 합니다.</span><span class="sxs-lookup"><span data-stu-id="7840e-695">IDPS **SHOULD** be configured for TLS inspection.</span></span>

*   <span data-ttu-id="7840e-696">모든 **인바운드** 및 아웃바운드 트래픽에 대해 IDPS를 구성해야 합니다.</span><span class="sxs-lookup"><span data-stu-id="7840e-696">IDPS **SHOULD** be configured for ALL inbound and outbound traffic.</span></span>

*   <span data-ttu-id="7840e-697">경고를  위해 IDPS를 구성해야 합니다.</span><span class="sxs-lookup"><span data-stu-id="7840e-697">IDPS **SHOULD** be configured for alerting.</span></span>

<span data-ttu-id="7840e-698">**이벤트 로깅**</span><span class="sxs-lookup"><span data-stu-id="7840e-698">**Event Logging**</span></span>

<span data-ttu-id="7840e-699">ISO 27001 감사는 보안 이벤트 로깅 프로세스의 일부 요소를 구체적으로 평가하지 않는 경우 다음을 요구합니다.</span><span class="sxs-lookup"><span data-stu-id="7840e-699">As ISO 27001 audits do not specifically assess some elements of security event logging processes, this will require you to:</span></span>

* <span data-ttu-id="7840e-700">공용 시스템이 DMZ 내에 없는 중앙 로깅 솔루션에 로깅하는지 보여 주십시오.</span><span class="sxs-lookup"><span data-stu-id="7840e-700">Demonstrate that public facing systems are logging to a centralized logging solution which isn't within the DMZ.</span></span>

* <span data-ttu-id="7840e-701">최소 30일 동안의 로깅 데이터를 즉시 사용할 수 있는 방법을 보여 주며 90일이 보존됩니다.</span><span class="sxs-lookup"><span data-stu-id="7840e-701">Demonstrate how a minimum of 30 days’ worth of logging data is immediately available, with 90 days being retained.</span></span>

<span data-ttu-id="7840e-702">**검토(로깅 데이터)**</span><span class="sxs-lookup"><span data-stu-id="7840e-702">**Reviewing (Logging Data)**</span></span>

<span data-ttu-id="7840e-703">ISO 27001 감사는 이 범주의 일부 요소를 구체적으로 평가하지 않는 경우 다음을 요구합니다.</span><span class="sxs-lookup"><span data-stu-id="7840e-703">As ISO 27001 audits do not specifically assess some elements of this category, this will require you to:</span></span>

*   <span data-ttu-id="7840e-704">일별 로그 검토가 수행되는 방식과 예외 및 예외가 어떻게 처리되는지 보여줄 수 있습니다.</span><span class="sxs-lookup"><span data-stu-id="7840e-704">Demonstrate how daily log reviews are conducted and how exceptions and anomalies are identified showing how these are handled.</span></span>

<span data-ttu-id="7840e-705">**경고**</span><span class="sxs-lookup"><span data-stu-id="7840e-705">**Alerting**</span></span>

<span data-ttu-id="7840e-706">ISO 27001 감사는 이 범주의 일부 요소를 구체적으로 평가하지 않는 경우 다음을 요구합니다.</span><span class="sxs-lookup"><span data-stu-id="7840e-706">As ISO 27001 audits do not specifically assess some elements of this category, this will require you to:</span></span>

* <span data-ttu-id="7840e-707">즉각적인 경시를 위해 경고를 트리거하도록 보안 이벤트가 구성된 방법을 보여줄 수 있습니다.</span><span class="sxs-lookup"><span data-stu-id="7840e-707">Demonstrate how security events are configured to trigger alerts for immediate triage.</span></span>

* <span data-ttu-id="7840e-708">직원이 보안 경고에 응답하기 위해 24/7을 사용할 수 있는 방법을 보여줄 수 있습니다.</span><span class="sxs-lookup"><span data-stu-id="7840e-708">Demonstrate how staff are available 24/7 to respond to security alerts.</span></span>

<span data-ttu-id="7840e-709">**위험 관리**</span><span class="sxs-lookup"><span data-stu-id="7840e-709">**Risk Management**</span></span>

<span data-ttu-id="7840e-710">ISO 27001 감사는 위험 평가 프로세스의 일부 요소를 구체적으로 평가하지 않는 경우 다음을 요구합니다.</span><span class="sxs-lookup"><span data-stu-id="7840e-710">As ISO 27001 audits do not specifically assess some elements of risk assessment processes, this will require you to:</span></span>

* <span data-ttu-id="7840e-711">공식적인 위험 관리 프로세스가 설정되었다는 설명</span><span class="sxs-lookup"><span data-stu-id="7840e-711">Demonstrate that a formal risk management process is established.</span></span>

<span data-ttu-id="7840e-712">**인시던트 대응**</span><span class="sxs-lookup"><span data-stu-id="7840e-712">**Incident Response**</span></span>

<span data-ttu-id="7840e-713">ISO 27001 감사는 인시던트 대응 정책 및 프로세스의 일부 요소를 구체적으로 평가하지 않는 경우 다음을 요구합니다.</span><span class="sxs-lookup"><span data-stu-id="7840e-713">As ISO 27001 audits do not specifically assess some elements of incident response policies and processes, this will require you to:</span></span>

*   <span data-ttu-id="7840e-714">인시던트 대응 계획/절차에 다음이 포함됩니다.</span><span class="sxs-lookup"><span data-stu-id="7840e-714">Demonstrate that the incident response plan/procedure includes:</span></span>

<span data-ttu-id="7840e-715">&#x2713; 위협 모델에 대한 특정 응답 절차입니다.</span><span class="sxs-lookup"><span data-stu-id="7840e-715">&#x2713; Specific response procedures for expected threat models.</span></span>

<span data-ttu-id="7840e-716">&#x2713;(식별, 보호, 감지, 대응, 복구)에 맞춰진 인시던트 처리 기능을 제공합니다.</span><span class="sxs-lookup"><span data-stu-id="7840e-716">&#x2713; Incident handling capabilities aligning to NIST Cybersecurity Framework (Identify, Protect, Detect, Respond, Recover).</span></span>
 
<span data-ttu-id="7840e-717">&#x2713; 범위 내 시스템을 다루는 IRP입니다.</span><span class="sxs-lookup"><span data-stu-id="7840e-717">&#x2713; The IRP covers the in-scope systems.</span></span>
 
<span data-ttu-id="7840e-718">&#x2713; 대응 팀을 위한 연례 교육을 실시합니다.</span><span class="sxs-lookup"><span data-stu-id="7840e-718">&#x2713; Annual training for the incident response team.</span></span>

## <a name="appendix-d"></a><span data-ttu-id="7840e-719">부록 D</span><span class="sxs-lookup"><span data-stu-id="7840e-719">Appendix D</span></span>

### <a name="evidence-collection--deltas-for-pci-dss"></a><span data-ttu-id="7840e-720">증거 컬렉션 - PCI DSS용 델타</span><span class="sxs-lookup"><span data-stu-id="7840e-720">Evidence Collection – Deltas for PCI DSS</span></span>

<span data-ttu-id="7840e-721">PCI DSS 규정 준수를 이미 획득한 경우 PCI DSS에서 다루지 않는 다음 델타의 (간격)는 최소한 이 Microsoft 365 인증의 일부로 검토해야 합니다.</span><span class="sxs-lookup"><span data-stu-id="7840e-721">Where you have already attained PCI DSS compliance, the following delta’s (gaps) not wholly covered by PCI DSS will, at a minimum, need to be reviewed as part of this Microsoft 365 Certification.</span></span>

> [!NOTE]
> <span data-ttu-id="7840e-722">Microsoft 365 인증 평가의 일부로 인증 분석가가 매핑된 PCI DSS 컨트롤이 PCI DSS 평가의 일부로 포함되지 않은지 여부를 결정하고 추가 보증을 제공하기 위해 포함된 것으로 확인된 샘플 컨트롤도 결정할 수 있습니다.</span><span class="sxs-lookup"><span data-stu-id="7840e-722">As part of the Microsoft 365 Certification assessment, the certification analyst will determine if any of the mapped PCI DSS controls were not included as part of the PCI DSS assessment and may also decide to sample controls that were found to be included to provide further assurance.</span></span> <span data-ttu-id="7840e-723">PCI DSS에서 누락된 모든 요구 사항은 인증 평가 Microsoft 365 포함되어야 합니다.</span><span class="sxs-lookup"><span data-stu-id="7840e-723">Any requirements missing from the PCI DSS will need to be included into the Microsoft 365 Certification assessment activities.</span></span>

<span data-ttu-id="7840e-724">**맬웨어 보호 - 응용 프로그램 제어**</span><span class="sxs-lookup"><span data-stu-id="7840e-724">**Malware Protection - Application Control**</span></span>

<span data-ttu-id="7840e-725">바이러스 백신을 사용하여 맬웨어 보호가 진행 중이고 PCI DSS 보고서 내에서 맬웨어가 것으로 조사된 경우 추가 조사가 필요하지 않습니다.</span><span class="sxs-lookup"><span data-stu-id="7840e-725">If malware protection is in place through use of anti-virus and is attested to within PCI DSS Report no further investigation is necessary.</span></span> <span data-ttu-id="7840e-726">바이러스 백신이 없는 경우 인증 분석가가 환경 내에서 맬웨어가 발견되지 않도록 응용 프로그램 제어 메커니즘의 증거를 식별하고 평가해야 합니다.</span><span class="sxs-lookup"><span data-stu-id="7840e-726">If no anti-virus is in place, certification analysts will need to identify and assess evidence of application control mechanisms to prevent detonation of malware within the environment.</span></span> <span data-ttu-id="7840e-727">이렇게 하면 다음이 필요할 수 있습니다.</span><span class="sxs-lookup"><span data-stu-id="7840e-727">This will require you to:</span></span> 

*   <span data-ttu-id="7840e-728">응용 프로그램 승인이 수행된 방법을 보여 주며 이 작업을 완료하는지 확인할 수 있습니다.</span><span class="sxs-lookup"><span data-stu-id="7840e-728">Demonstrate how the application approval is conducted and confirm that this is completed.</span></span>

*   <span data-ttu-id="7840e-729">비즈니스 사정이 있는 승인된 응용 프로그램의 전체 목록이 존재할 수 있습니다.</span><span class="sxs-lookup"><span data-stu-id="7840e-729">Demonstrate that a complete list of approved applications with business justification exists.</span></span>

*   <span data-ttu-id="7840e-730">특정 응용 프로그램 제어 메커니즘(예: 화이트리스트, 코드 서명 등)을 충족하도록 응용 프로그램 제어 소프트웨어를 구성하는 방법을 자세히 설명하는 지원 설명서를 제공하거나 설명하는 문서가 제공됩니다.</span><span class="sxs-lookup"><span data-stu-id="7840e-730">Provide or demonstrate supporting documentation is in place detailing how application control software is configured to meet specific application control mechanisms (i.e. whitelisting, code signing, etc.).</span></span>

*   <span data-ttu-id="7840e-731">모든 샘플링된 시스템 구성 요소에서 응용 프로그램 제어가 문서화된 것으로 구성되어 있는지 보여 주도록 합니다.</span><span class="sxs-lookup"><span data-stu-id="7840e-731">Demonstrate that across all sampled system components, application control is configured as documented.</span></span>

<span data-ttu-id="7840e-732">**패치 관리 - 위험 순위**</span><span class="sxs-lookup"><span data-stu-id="7840e-732">**Patch Management – Risk Ranking**</span></span>

<span data-ttu-id="7840e-733">PCI DSS 감사는 이 범주를 구체적으로 평가하지 않는 경우 다음을 요구합니다.</span><span class="sxs-lookup"><span data-stu-id="7840e-733">As PCI DSS audits do not specifically assess this category, this will require you to:</span></span>

* <span data-ttu-id="7840e-734">취약성의 위험 순위가 수행된 방법을 보여줄 수 있습니다.</span><span class="sxs-lookup"><span data-stu-id="7840e-734">Demonstrate how risk ranking of vulnerabilities is conducted.</span></span>

<span data-ttu-id="7840e-735">**취약점 검사**</span><span class="sxs-lookup"><span data-stu-id="7840e-735">**Vulnerability Scanning**</span></span>

<span data-ttu-id="7840e-736">PCI DSS 감사는 이 범주를 구체적으로 평가하지 않는 경우 다음을 요구합니다.</span><span class="sxs-lookup"><span data-stu-id="7840e-736">As PCI DSS audits do not specifically assess this category, this will require you to:</span></span>

* <span data-ttu-id="7840e-737">문서화한 취약점 수정 정책에 따라 수정이 수행됩니다.</span><span class="sxs-lookup"><span data-stu-id="7840e-737">Demonstrate that remediation is conducted in-line with the documented vulnerability remediation policy.</span></span>

<span data-ttu-id="7840e-738">**방화벽 - 방화벽(또는 동등한 기술)**</span><span class="sxs-lookup"><span data-stu-id="7840e-738">**Firewall – Firewalls (or equivalent technologies)**</span></span>

<span data-ttu-id="7840e-739">PCI DSS 감사는 이 범주를 구체적으로 평가하지 않는 경우 다음을 요구합니다.</span><span class="sxs-lookup"><span data-stu-id="7840e-739">As PCI DSS audits do not specifically assess this category, this will require you to:</span></span>

* <span data-ttu-id="7840e-740">방화벽이 콘솔이 아닌 모든 관리 인터페이스에서 강력한 암호화만 지원하고 있습니다.</span><span class="sxs-lookup"><span data-stu-id="7840e-740">Demonstrate that firewalls support only strong cryptography on all non-console administrative interfaces.</span></span>

* <span data-ttu-id="7840e-741">인터넷에 노출되는 방화벽의 콘솔이 아닌 관리 인터페이스가 MFA를 지원하는지 보여줄 수 있습니다.</span><span class="sxs-lookup"><span data-stu-id="7840e-741">Demonstrate that firewall's non-console administrative interfaces exposed to the Internet support MFA.</span></span>

<span data-ttu-id="7840e-742">응용 프로그램이 노출될 수 있는 다양한 웹 응용 프로그램 위협 및 취약성으로부터 보호하기 위해 WAF(웹 응용 프로그램 방화벽)를 배포한 경우 추가 크레딧이 제공됩니다.</span><span class="sxs-lookup"><span data-stu-id="7840e-742">Additional credit will be provided if a Web Application Firewall (WAF) s deployed to help protect against the myriad of web application threats and vulnerabilities that the application can be exposed to.</span></span> <span data-ttu-id="7840e-743">WAF 또는 유사 WAF가 있는 경우 다음을 요구합니다.</span><span class="sxs-lookup"><span data-stu-id="7840e-743">When a WAF or similar is present, this will require you to:</span></span>

* <span data-ttu-id="7840e-744">WAF가 경고를 통해 활성 방어 모드 또는 더 많은 모니터링으로 구성되어 있는지를 보여줄 수 있습니다.</span><span class="sxs-lookup"><span data-stu-id="7840e-744">Demonstrate the WAF is configured in active defense mode or monitoring more with alerting.</span></span>

* <span data-ttu-id="7840e-745">WAF가 SSL 오프로드를 지원하도록 구성되어 있는지 보여 집니다.</span><span class="sxs-lookup"><span data-stu-id="7840e-745">Demonstrate the WAF is configured to support SSL offloading.</span></span>

* <span data-ttu-id="7840e-746">다음과 같은 대부분의 공격 유형으로부터 보호하기 위해 OWASP 핵심 규칙 집합(3.0 또는 3.1)에 따라 구성됩니다.</span><span class="sxs-lookup"><span data-stu-id="7840e-746">Is configured as per the OWASP Core Rule Set (3.0 or 3.1) to protect against most of the following attack types:</span></span>

<span data-ttu-id="7840e-747">&#x2713; 및 인코딩 문제를 해결합니다.</span><span class="sxs-lookup"><span data-stu-id="7840e-747">&#x2713; Protocol and encoding issues.</span></span>

<span data-ttu-id="7840e-748">&#x2713;, 요청 밀기 및 응답 분할을 요청합니다.</span><span class="sxs-lookup"><span data-stu-id="7840e-748">&#x2713; Header injection, request smuggling, and response splitting.</span></span>

<span data-ttu-id="7840e-749">&#x2713; 경로 트래버스 공격을 공격합니다.</span><span class="sxs-lookup"><span data-stu-id="7840e-749">&#x2713; File and path traversal attacks.</span></span>

<span data-ttu-id="7840e-750">&#x2713; RFI(원격 파일 포함) 공격을 제어합니다.</span><span class="sxs-lookup"><span data-stu-id="7840e-750">&#x2713; Remote file inclusion (RFI) attacks.</span></span>

<span data-ttu-id="7840e-751">&#x2713; 코드 실행 공격을 중지합니다.</span><span class="sxs-lookup"><span data-stu-id="7840e-751">&#x2713; Remote code execution attacks.</span></span>

<span data-ttu-id="7840e-752">&#x2713; PHP 주입 공격이 있습니다.</span><span class="sxs-lookup"><span data-stu-id="7840e-752">&#x2713; PHP-injection attacks.</span></span>

<span data-ttu-id="7840e-753">&#x2713; 스크립팅 공격을 수정합니다.</span><span class="sxs-lookup"><span data-stu-id="7840e-753">&#x2713; Cross-site scripting attacks.</span></span>

<span data-ttu-id="7840e-754">&#x2713; SQL 주입 공격.</span><span class="sxs-lookup"><span data-stu-id="7840e-754">&#x2713; SQL-injection attacks.</span></span>

<span data-ttu-id="7840e-755">&#x2713; 세션 수정 공격을 해결합니다.</span><span class="sxs-lookup"><span data-stu-id="7840e-755">&#x2713; Session-fixation attacks.</span></span>

<span data-ttu-id="7840e-756">**변경 컨트롤**</span><span class="sxs-lookup"><span data-stu-id="7840e-756">**Change Control**</span></span>

<span data-ttu-id="7840e-757">PCI DSS 감사는 변경 요청 프로세스의 일부 요소를 구체적으로 평가하지 않는 경우 다음을 요구합니다.</span><span class="sxs-lookup"><span data-stu-id="7840e-757">As PCI DSS audits do not specifically assess some elements of Change Request processes, this will require you to:</span></span>

* <span data-ttu-id="7840e-758">프로덕션 환경에서 변경 요청이 발생하기 전에 발생되는 것을 보여 주십시오.</span><span class="sxs-lookup"><span data-stu-id="7840e-758">Demonstrate that change requests are raised before being made in production environments.</span></span>

* <span data-ttu-id="7840e-759">프로덕션으로 이전하기 전에 변경 내용이 권한이 부여된 것을 보여줄 수 있습니다.</span><span class="sxs-lookup"><span data-stu-id="7840e-759">Demonstrate that changes are authorized before going into production.</span></span>

* <span data-ttu-id="7840e-760">기능 테스트는 변경이 완료된 후에 수행됩니다.</span><span class="sxs-lookup"><span data-stu-id="7840e-760">Demonstrate that functionality testing is conducted after changes are completed.</span></span>

* <span data-ttu-id="7840e-761">기능 테스트가 수행된 후 변경 요청이 서명된 경우를 보여 집니다.</span><span class="sxs-lookup"><span data-stu-id="7840e-761">Demonstrate that change requests are signed off after functionality testing is conducted.</span></span>

<span data-ttu-id="7840e-762">**보안 소프트웨어 개발/배포**</span><span class="sxs-lookup"><span data-stu-id="7840e-762">**Secure Software Development/Deployment**</span></span>

<span data-ttu-id="7840e-763">PCI DSS 감사는 보안 소프트웨어 개발 및 배포 프로세스의 일부 요소에 특별히 액세스하지 않습니다. 이렇게 하면 다음이 요구될 수 있습니다.</span><span class="sxs-lookup"><span data-stu-id="7840e-763">As PCI DSS audits do not specifically access some elements of secure software development and deployment processes; this will require to you:</span></span>

* <span data-ttu-id="7840e-764">코드 리포지토리는 MFA로 보호해야 합니다.</span><span class="sxs-lookup"><span data-stu-id="7840e-764">Code repositories MUST be secured by MFA.</span></span>

*   <span data-ttu-id="7840e-765">악성 코드 수정으로부터 코드 리포지토리를 보호하려면 적절한 액세스 제어가 있어야 합니다.</span><span class="sxs-lookup"><span data-stu-id="7840e-765">Adequate access controls MUST be in place to protect code repositories against malicious code modifications.</span></span>

<span data-ttu-id="7840e-766">**계정 관리**</span><span class="sxs-lookup"><span data-stu-id="7840e-766">**Account Management**</span></span>

<span data-ttu-id="7840e-767">PCI DSS 감사는 계정 관리 프로세스의 일부 요소를 구체적으로 평가하지 않는 경우 다음을 요구합니다.</span><span class="sxs-lookup"><span data-stu-id="7840e-767">As PCI DSS audits do not specifically assess some elements of account management processes, this will require you to:</span></span>

* <span data-ttu-id="7840e-768">재생 공격(예: MFA, Kerberos)을 완화하기 위해 인증 메커니즘을 구현하는 방법을 보여줄 수 있습니다.</span><span class="sxs-lookup"><span data-stu-id="7840e-768">Demonstrate how the authorization mechanisms are implemented to mitigate replay attacks (e.g. MFA, Kerberos).</span></span>

* <span data-ttu-id="7840e-769">강력한 암호 정책 또는 기타 적절한 완화는 사용자 자격 증명을 보호하도록 구성해야 합니다.</span><span class="sxs-lookup"><span data-stu-id="7840e-769">Strong password policies or other suitable mitigations must be configured to protect user credentials.</span></span> <span data-ttu-id="7840e-770">다음과 같은 최소 암호 정책을 지침으로 사용해야 합니다.</span><span class="sxs-lookup"><span data-stu-id="7840e-770">The following minimum password policy should be used as a guideline:</span></span> 

<span data-ttu-id="7840e-771">&#x2713; 최소 암호 길이는 8자입니다.</span><span class="sxs-lookup"><span data-stu-id="7840e-771">&#x2713; Minimum password length of 8 characters.</span></span>

<span data-ttu-id="7840e-772">&#x2713; 계정 잠금 임계값은 10회를 넘지 않습니다.</span><span class="sxs-lookup"><span data-stu-id="7840e-772">&#x2713; Account lockout threshold of no more than 10 attempts.</span></span>

<span data-ttu-id="7840e-773">&#x2713; 암호의 최소 5개 암호 기록입니다.</span><span class="sxs-lookup"><span data-stu-id="7840e-773">&#x2713; Password history of a minimum of five passwords.</span></span>

<span data-ttu-id="7840e-774">&#x2713; 강력한 암호의 사용을 적용합니다.</span><span class="sxs-lookup"><span data-stu-id="7840e-774">&#x2713; Enforcement of the use of strong passwords.</span></span>

* <span data-ttu-id="7840e-775">모든 원격 액세스 솔루션에 강력한 암호화가 구성되어 있는지 보여 주십시오.</span><span class="sxs-lookup"><span data-stu-id="7840e-775">Demonstrate that strong encryption is configured on all remote access solutions.</span></span>

* <span data-ttu-id="7840e-776">공용 DNS 관리가 범위 내 환경 외부에 있는 경우 DNS를 수정할 수 있는 모든 사용자 계정은 MFA를 사용하도록 구성해야 합니다.</span><span class="sxs-lookup"><span data-stu-id="7840e-776">Where the management of Public DNS is outside of the in-scope environment, all user accounts able to make DNS modifications MUST be configured to use MFA.</span></span>

<span data-ttu-id="7840e-777">**침입 감지 및 방지(OPTIONAL)**</span><span class="sxs-lookup"><span data-stu-id="7840e-777">**Intrusion Detection and Prevention (OPTIONAL)**</span></span>

<span data-ttu-id="7840e-778">PCI DSS 감사는 IDPS(침입 감지 및 방지 서비스) 프로세스의 일부 요소를 구체적으로 평가하지 않는 경우 다음을 요구합니다.</span><span class="sxs-lookup"><span data-stu-id="7840e-778">As PCI DSS audits do not specifically assess some elements of Intrusion Detection and Prevention Services (IDPS) processes, this will require you to:</span></span>

* <span data-ttu-id="7840e-779">TLS 검사를 위해 IDPS를 구성해야 합니다.</span><span class="sxs-lookup"><span data-stu-id="7840e-779">IDPS SHOULD be configured for TLS inspection.</span></span>

*   <span data-ttu-id="7840e-780">모든 인바운드 및 아웃바운드 트래픽에 대해 IDPS를 구성해야 합니다.</span><span class="sxs-lookup"><span data-stu-id="7840e-780">IDPS SHOULD be configured for ALL inbound and outbound traffic.</span></span>

<span data-ttu-id="7840e-781">**위험 관리**</span><span class="sxs-lookup"><span data-stu-id="7840e-781">**Risk Management**</span></span>

<span data-ttu-id="7840e-782">PCI DSS 감사는 위험 평가 프로세스의 일부 요소를 구체적으로 평가하지 않는 경우 다음을 요구합니다.</span><span class="sxs-lookup"><span data-stu-id="7840e-782">As PCI DSS audits do not specifically assess some elements of risk assessment processes, this will require you to:</span></span>

* <span data-ttu-id="7840e-783">위험 평가에 영향 및 가능성 분석이 포함됩니다.</span><span class="sxs-lookup"><span data-stu-id="7840e-783">Demonstrate the risk assessment includes impact and likelihood matrices.</span></span>

<span data-ttu-id="7840e-784">**인시던트 대응**</span><span class="sxs-lookup"><span data-stu-id="7840e-784">**Incident Response**</span></span>

<span data-ttu-id="7840e-785">PCI DSS 감사는 인시던트 대응 정책 및 프로세스의 일부 요소를 특별히 평가하지 않는 경우 개발자가 다음을 요구합니다.</span><span class="sxs-lookup"><span data-stu-id="7840e-785">As PCI DSS audits don't specifically assess some elements of incident response policies and processes, this will require the developer to:</span></span>

* <span data-ttu-id="7840e-786">인시던트 처리 기능이 NIST 사이버 보안 프레임워크(식별, 보호, 감지, 대응, 복구)에 맞춰진 것을 보여줄 수 있습니다.</span><span class="sxs-lookup"><span data-stu-id="7840e-786">Demonstrate Incident handling capabilities align to NIST Cybersecurity Framework (Identify, Protect, Detect, Respond, Recover).</span></span>

## <a name="appendix-e"></a><span data-ttu-id="7840e-787">부록 E</span><span class="sxs-lookup"><span data-stu-id="7840e-787">Appendix E</span></span>

### <a name="evidence-collection---deltas-for-soc-2"></a><span data-ttu-id="7840e-788">증거 수집 - SOC 2의 델타</span><span class="sxs-lookup"><span data-stu-id="7840e-788">Evidence Collection - Deltas for SOC 2</span></span>

<span data-ttu-id="7840e-789">이미 SOC 2 규정 준수를 획득한 경우 이 Microsoft 365 인증의 일부로 SOC 2에서 다루지 않는 다음 델타의 (간격)를 검토해야 합니다.</span><span class="sxs-lookup"><span data-stu-id="7840e-789">Where you have already attained SOC 2 compliance, the following delta’s (gaps) not wholly covered by SOC 2 will need to be reviewed as part of this Microsoft 365 Certification.</span></span>

> [!NOTE]
> <span data-ttu-id="7840e-790">Microsoft 365 인증 평가의 일부로 인증 분석가가 매핑된 SOC 2 컨트롤이 SOC 2 평가의 일부로 포함되지 않은지 여부를 결정하고 추가 보증을 제공하기 위해 포함된 것으로 확인된 샘플 컨트롤도 결정할 수 있습니다.</span><span class="sxs-lookup"><span data-stu-id="7840e-790">As part of the Microsoft 365 Certification assessment, the certification analyst will determine if any of the mapped SOC 2 controls were not included as part of your SOC 2 assessment and may also decide to sample controls that were found to be included to provide further assurance.</span></span> <span data-ttu-id="7840e-791">SOC 2 평가에서 누락된 요구 사항은 인증 평가 Microsoft 365 포함되어야 합니다.</span><span class="sxs-lookup"><span data-stu-id="7840e-791">Any requirements missing from your SOC 2 assessment will need to be included as part of the Microsoft 365 Certification assessment activities.</span></span>

<span data-ttu-id="7840e-792">**맬웨어 보호 - 응용 프로그램 제어**</span><span class="sxs-lookup"><span data-stu-id="7840e-792">**Malware Protection - Application Control**</span></span>

<span data-ttu-id="7840e-793">바이러스 백신을 사용하여 맬웨어 보호가 설정 중이고 SOC 2 보고서 내에 확인된 경우 추가 조사가 필요하지 않습니다.</span><span class="sxs-lookup"><span data-stu-id="7840e-793">If malware protection is in place through use of anti-virus and is attested to within your SOC 2 report no further investigation is necessary.</span></span> <span data-ttu-id="7840e-794">바이러스 백신이 없는 경우 인증 분석가가 환경 내에서 맬웨어가 발견되지 않도록 응용 프로그램 제어 메커니즘의 증거를 식별하고 평가해야 합니다.</span><span class="sxs-lookup"><span data-stu-id="7840e-794">If no anti-virus is in place, certification analysts will need to identify and assess evidence of application control mechanisms to prevent detonation of malware within the environment.</span></span> <span data-ttu-id="7840e-795">이렇게 하면 다음이 필요할 수 있습니다.</span><span class="sxs-lookup"><span data-stu-id="7840e-795">This will require you to:</span></span>

* <span data-ttu-id="7840e-796">특정 응용 프로그램 제어 메커니즘(예: 화이트리스트, 코드 서명 등)을 충족하도록 응용 프로그램 제어 소프트웨어를 구성하는 방법을 자세히 설명하는 지원 설명서를 제공하거나 설명하는 문서가 제공됩니다.</span><span class="sxs-lookup"><span data-stu-id="7840e-796">Provide or demonstrate supporting documentation is in place detailing how application control software is configured to meet specific application control mechanisms (i.e. whitelisting, code signing, etc.).</span></span>

* <span data-ttu-id="7840e-797">응용 프로그램 승인이 수행된 방법을 보여 주며 이 작업을 완료하는지 확인할 수 있습니다.</span><span class="sxs-lookup"><span data-stu-id="7840e-797">Demonstrate how the application approval is conducted and confirm that this is completed.</span></span>

*   <span data-ttu-id="7840e-798">비즈니스 사정이 있는 승인된 응용 프로그램의 전체 목록이 존재할 수 있습니다.</span><span class="sxs-lookup"><span data-stu-id="7840e-798">Demonstrate that a complete list of approved applications with business justification exists.</span></span>

*   <span data-ttu-id="7840e-799">모든 샘플링된 시스템 구성 요소에서 응용 프로그램 제어가 문서화된 것으로 구성되어 있는지 보여 주도록 합니다.</span><span class="sxs-lookup"><span data-stu-id="7840e-799">Demonstrate that across all sampled system components, application control is configured as documented.</span></span>

<span data-ttu-id="7840e-800">**패치 관리 - 패치**</span><span class="sxs-lookup"><span data-stu-id="7840e-800">**Patch Management – Patching**</span></span>

<span data-ttu-id="7840e-801">SOC 2 감사는 이 범주를 구체적으로 평가하지 않는 경우 다음을 요구합니다.</span><span class="sxs-lookup"><span data-stu-id="7840e-801">As SOC 2 audits do not specifically assess this category, this will require you to:</span></span>

*   <span data-ttu-id="7840e-802">낮음, 중간, 높음 또는 중요 문제는 일반 패치 작업 창 내에서 패치해야 합니다.</span><span class="sxs-lookup"><span data-stu-id="7840e-802">Any Low, Medium, High, or Critical issue must be patched within normal patching activity windows.</span></span>

*   <span data-ttu-id="7840e-803">공급업체에서 더 이상 지원하지 않는 소프트웨어 구성 요소 및 운영 체제는 환경 내에서 사용되지 말아야 합니다.</span><span class="sxs-lookup"><span data-stu-id="7840e-803">Software components and operating systems no longer supported by the vendor MUST not be used within the environment.</span></span> <span data-ttu-id="7840e-804">지원 정책이 있어야 지원되지 않는 소프트웨어 구성 요소/운영 체제가 환경에서 제거되고 소프트웨어 구성 요소가 수명 종료될 때를 식별하는 프로세스가 필요합니다.</span><span class="sxs-lookup"><span data-stu-id="7840e-804">Supporting policies MUST be in place to ensure unsupported software components / operating systems will be removed from the environment and a process to identify when software components go end-of-life must be in place.</span></span>

<span data-ttu-id="7840e-805">**방화벽 - 방화벽**</span><span class="sxs-lookup"><span data-stu-id="7840e-805">**Firewall – Firewalls**</span></span>

<span data-ttu-id="7840e-806">SOC 2 감사는 방화벽 액세스 제어 목록에 대한 변경 제어를 구체적으로 평가하지 않는 경우 다음을 요구합니다.</span><span class="sxs-lookup"><span data-stu-id="7840e-806">As SOC 2 audits do not specifically assess change controls to firewall access control lists, this will require you to:</span></span>

* <span data-ttu-id="7840e-807">방화벽을 통해 허용된 모든 트래픽이 인증 프로세스를 통과하여 비즈니스 사당성에 따라 모든 트래픽에 대한 설명서를 작성하는 것을 입증합니다.</span><span class="sxs-lookup"><span data-stu-id="7840e-807">Demonstrate that all permitted traffic through the firewall(s) goes through an authorization process which results in the documentation of all traffic with a business justification.</span></span>

* <span data-ttu-id="7840e-808">방화벽 규칙 검토는 최소 6개월마다 수행됩니다.</span><span class="sxs-lookup"><span data-stu-id="7840e-808">Demonstrate that firewall rule reviews are conducted at least every six months.</span></span>

<span data-ttu-id="7840e-809">응용 프로그램이 노출될 수 있는 다양한 웹 응용 프로그램 위협 및 취약성으로부터 보호하기 위해 WAF(웹 응용 프로그램 방화벽) 또는 이와 유사한 웹 응용 프로그램 방화벽이 배포된 경우 추가 크레딧이 제공됩니다.</span><span class="sxs-lookup"><span data-stu-id="7840e-809">Additional credit will be provided if a Web Application Firewall (WAF) or similar is deployed to help protect against the myriad of web application threats and vulnerabilities that the application can be exposed to.</span></span> <span data-ttu-id="7840e-810">WAF 또는 유사 WAF가 있는 경우 다음을 요구합니다.</span><span class="sxs-lookup"><span data-stu-id="7840e-810">When a WAF or similar is present, this will require you to:</span></span>

* <span data-ttu-id="7840e-811">WAF가 경고를 통해 활성 방어 모드 또는 더 많은 모니터링으로 구성되어 있는지를 보여줄 수 있습니다.</span><span class="sxs-lookup"><span data-stu-id="7840e-811">Demonstrate the WAF is configured in active defense mode or monitoring more with alerting.</span></span>

* <span data-ttu-id="7840e-812">WAF가 SSL 오프로드를 지원하도록 구성되어 있는지 보여 집니다.</span><span class="sxs-lookup"><span data-stu-id="7840e-812">Demonstrate the WAF is configured to support SSL offloading.</span></span>

* <span data-ttu-id="7840e-813">다음과 같은 대부분의 공격 유형으로부터 보호하기 위해 OWASP 핵심 규칙 집합((3.0 또는 3.1)에 따라 구성됩니다.</span><span class="sxs-lookup"><span data-stu-id="7840e-813">Is configured as per the OWASP Core Rule Set ((3.0 or 3.1) to protect against the majority of the following attack types:</span></span>

<span data-ttu-id="7840e-814">&emsp;&#x2713; 및 인코딩 문제를 해결합니다.</span><span class="sxs-lookup"><span data-stu-id="7840e-814">&emsp;&#x2713; Protocol and encoding issues.</span></span>

<span data-ttu-id="7840e-815">&emsp;&#x2713;, 요청 밀기 및 응답 분할을 요청합니다.</span><span class="sxs-lookup"><span data-stu-id="7840e-815">&emsp;&#x2713; Header injection, request smuggling, and response splitting.</span></span>

<span data-ttu-id="7840e-816">&emsp;&#x2713; 경로 트래버스 공격을 공격합니다.</span><span class="sxs-lookup"><span data-stu-id="7840e-816">&emsp;&#x2713; File and path traversal attacks.</span></span>

<span data-ttu-id="7840e-817">&emsp;&#x2713; RFI(원격 파일 포함) 공격이 있습니다.</span><span class="sxs-lookup"><span data-stu-id="7840e-817">&emsp;&#x2713; Remote file inclusion (RFI) attacks.</span></span>

<span data-ttu-id="7840e-818">&emsp;&#x2713; 코드 실행 공격을 중지합니다.</span><span class="sxs-lookup"><span data-stu-id="7840e-818">&emsp;&#x2713; Remote code execution attacks.</span></span>

<span data-ttu-id="7840e-819">&emsp;&#x2713; PHP 주입 공격이 있습니다.</span><span class="sxs-lookup"><span data-stu-id="7840e-819">&emsp;&#x2713; PHP-injection attacks.</span></span>

<span data-ttu-id="7840e-820">&emsp;&#x2713; 스크립팅 공격을 수정합니다.</span><span class="sxs-lookup"><span data-stu-id="7840e-820">&emsp;&#x2713; Cross-site scripting attacks.</span></span>

<span data-ttu-id="7840e-821">&emsp;&#x2713; SQL 주입 공격.</span><span class="sxs-lookup"><span data-stu-id="7840e-821">&emsp;&#x2713; SQL-injection attacks.</span></span>

<span data-ttu-id="7840e-822">&emsp;&#x2713; 수정 공격을 해결합니다.</span><span class="sxs-lookup"><span data-stu-id="7840e-822">&emsp;&#x2713; Session-fixation attacks.</span></span>

<span data-ttu-id="7840e-823">**변경 컨트롤**</span><span class="sxs-lookup"><span data-stu-id="7840e-823">**Change Control**</span></span>

<span data-ttu-id="7840e-824">SOC 2 감사는 변경 요청 프로세스의 일부 요소를 구체적으로 평가하지 않는 경우 개발자가 다음을 요구합니다.</span><span class="sxs-lookup"><span data-stu-id="7840e-824">As SOC 2 audits don't specifically assess some elements of Change Request processes, this will require the developer to:</span></span>

* <span data-ttu-id="7840e-825">개발/테스트 환경이 프로덕션 환경과 분리되어 업무 분리를 이행하는 방법을 보여 줍니다.</span><span class="sxs-lookup"><span data-stu-id="7840e-825">Demonstrate how development / test environments are separate from the production environment enforcing separation of duties.</span></span>

* <span data-ttu-id="7840e-826">개발/테스트 환경에서 라이브 데이터가 어떻게 사용되지 않는지 보여줄 수 있습니다.</span><span class="sxs-lookup"><span data-stu-id="7840e-826">Demonstrate how live data isn't used within the development / test environments.</span></span>

* <span data-ttu-id="7840e-827">기능 테스트는 변경이 완료된 후에 수행됩니다.</span><span class="sxs-lookup"><span data-stu-id="7840e-827">Demonstrate that functionality testing is conducted after changes are completed.</span></span>

* <span data-ttu-id="7840e-828">기능 테스트가 수행된 후 변경 요청이 서명된 경우를 보여 집니다.</span><span class="sxs-lookup"><span data-stu-id="7840e-828">Demonstrate that change requests are signed off after functionality testing is conducted.</span></span>

<span data-ttu-id="7840e-829">**보안 소프트웨어 개발/배포**</span><span class="sxs-lookup"><span data-stu-id="7840e-829">**Secure Software Development/Deployment**</span></span>

<span data-ttu-id="7840e-830">SOC 2 감사는 보안 소프트웨어 개발 및 배포 프로세스의 일부 요소에 특별히 액세스하지 않습니다. 이렇게 하면 다음이 요구될 수 있습니다.</span><span class="sxs-lookup"><span data-stu-id="7840e-830">As SOC 2 audits do not specifically access some elements of secure software development and deployment processes; this will require to you:</span></span>

*   <span data-ttu-id="7840e-831">전체 소프트웨어 개발 수명 주기를 다루는 설정 및 문서화된 소프트웨어 개발 프로세스가 있어야 합니다.</span><span class="sxs-lookup"><span data-stu-id="7840e-831">You MUST have an established and documented software development process covering the entire software-development lifecycle.</span></span>

*   <span data-ttu-id="7840e-832">개발자는 적어도 매년 보안 소프트웨어 코딩 교육을 실시해야 합니다.</span><span class="sxs-lookup"><span data-stu-id="7840e-832">Developers MUST undergo secure software coding training at least annually.</span></span>

*   <span data-ttu-id="7840e-833">코드 리포지토리는 MFA로 보호해야 합니다.</span><span class="sxs-lookup"><span data-stu-id="7840e-833">Code repositories MUST be secured by MFA.</span></span>

*   <span data-ttu-id="7840e-834">악성 코드 수정으로부터 코드 리포지토리를 보호하려면 적절한 액세스 제어가 있어야 합니다.</span><span class="sxs-lookup"><span data-stu-id="7840e-834">Adequate access controls MUST be in place to protect code repositories against malicious code modifications.</span></span>

<span data-ttu-id="7840e-835">**계정 관리**</span><span class="sxs-lookup"><span data-stu-id="7840e-835">**Account Management**</span></span>

<span data-ttu-id="7840e-836">SOC2 감사는 계정 관리 프로세스의 일부 요소를 구체적으로 평가하지 않는 경우 다음을 요구합니다.</span><span class="sxs-lookup"><span data-stu-id="7840e-836">As SOC2 audits do not specifically assess some elements of account management processes, this will require you to:</span></span>

*   <span data-ttu-id="7840e-837">재생 공격(예: MFA, Kerberos)을 완화하기 위해 인증 메커니즘을 구현하는 방법을 보여줄 수 있습니다.</span><span class="sxs-lookup"><span data-stu-id="7840e-837">Demonstrate how the authorization mechanisms are implemented to mitigate replay attacks (e.g. MFA, Kerberos).</span></span>

*   <span data-ttu-id="7840e-838">3개월 동안 사용되지 않은 계정을 사용하지 않도록 설정하거나 삭제하는 방법을 보여줄 수 있습니다.</span><span class="sxs-lookup"><span data-stu-id="7840e-838">Demonstrate how accounts that have not been used in 3 months are either disabled or deleted.</span></span>

*   <span data-ttu-id="7840e-839">강력한 암호 정책 또는 기타 적절한 완화는 사용자 자격 증명을 보호하도록 구성해야 합니다.</span><span class="sxs-lookup"><span data-stu-id="7840e-839">Strong password policies or other suitable mitigations must be configured to protect user credentials.</span></span> <span data-ttu-id="7840e-840">다음과 같은 최소 암호 정책을 지침으로 사용해야 합니다.</span><span class="sxs-lookup"><span data-stu-id="7840e-840">The following minimum password policy should be used as a guideline:</span></span>

<span data-ttu-id="7840e-841">&emsp;&#x2713; 최소 암호 길이는 8자입니다.</span><span class="sxs-lookup"><span data-stu-id="7840e-841">&emsp;&#x2713; Minimum password length of 8 characters.</span></span>

<span data-ttu-id="7840e-842">&emsp;&#x2713; 계정 잠금 임계값은 10회를 넘지 않습니다.</span><span class="sxs-lookup"><span data-stu-id="7840e-842">&emsp;&#x2713; Account lockout threshold of no more than 10 attempts.</span></span>

<span data-ttu-id="7840e-843">&emsp;&#x2713; 최소 5개 암호의 암호 기록입니다.</span><span class="sxs-lookup"><span data-stu-id="7840e-843">&emsp;&#x2713; Password history of a minimum of 5 passwords.</span></span>

<span data-ttu-id="7840e-844">&emsp;&#x2713; 강력한 암호 사용 적용</span><span class="sxs-lookup"><span data-stu-id="7840e-844">&emsp;&#x2713; Enforcement of the use of strong passwords</span></span>

*   <span data-ttu-id="7840e-845">고유한 사용자 계정이 모든 사용자에게 발급된 경우를 보여 줄 수 있습니다.</span><span class="sxs-lookup"><span data-stu-id="7840e-845">Demonstrate that unique user accounts are issued to all users.</span></span>

*   <span data-ttu-id="7840e-846">공용 DNS 관리가 범위 내 환경 외부에 있는 경우 DNS를 수정할 수 있는 모든 사용자 계정은 MFA를 사용하도록 구성해야 합니다.</span><span class="sxs-lookup"><span data-stu-id="7840e-846">Where the management of Public DNS is outside of the in-scope environment, all user accounts able to make DNS modifications MUST be configured to use MFA.</span></span>

<span data-ttu-id="7840e-847">**침입 감지 및 방지(OPTIONAL)**</span><span class="sxs-lookup"><span data-stu-id="7840e-847">**Intrusion Detection and Prevention (OPTIONAL).**</span></span>

<span data-ttu-id="7840e-848">SOC 2 감사는 IDPS(침입 감지 및 방지 서비스) 프로세스의 일부 요소를 구체적으로 평가하지 않는 경우 다음을 요구합니다.</span><span class="sxs-lookup"><span data-stu-id="7840e-848">As SOC 2 audits do not specifically assess some elements of Intrusion Detection and Prevention Services (IDPS) processes, this will require you to:</span></span>

*   <span data-ttu-id="7840e-849">IDPS 서명은 지난 날 내에 최신으로 유지해야 합니다.</span><span class="sxs-lookup"><span data-stu-id="7840e-849">IDPS signatures SHOULD be kept current, within the past day</span></span>

*   <span data-ttu-id="7840e-850">TLS 검사를 위해 IDPS를 구성해야 합니다.</span><span class="sxs-lookup"><span data-stu-id="7840e-850">IDPS SHOULD be configured for TLS inspection</span></span>

*   <span data-ttu-id="7840e-851">모든 인바운드 및 아웃바운드 트래픽에 대해 IDPS를 구성해야 합니다.</span><span class="sxs-lookup"><span data-stu-id="7840e-851">IDPS SHOULD be configured for ALL inbound and outbound traffic</span></span>

<span data-ttu-id="7840e-852">**이벤트 로깅**</span><span class="sxs-lookup"><span data-stu-id="7840e-852">**Event Logging**</span></span>

<span data-ttu-id="7840e-853">SOC 2 감사는 보안 이벤트 로깅 프로세스의 일부 요소를 구체적으로 평가하지 않는 경우 다음을 요구합니다.</span><span class="sxs-lookup"><span data-stu-id="7840e-853">As SOC 2 audits do not specifically assess some elements of security event logging processes, this will require you to:</span></span>

* <span data-ttu-id="7840e-854">샘플 집합 내의 모든 시스템 구성 요소에서 다음 이벤트를 기록하도록 다음 시스템을 구성하는 방법을 보여줄 수 있습니다.</span><span class="sxs-lookup"><span data-stu-id="7840e-854">Demonstrate how, on all system components within the sample set the following system are configured to log the following events</span></span>

<span data-ttu-id="7840e-855">&emsp;&#x2713; 구성 요소 및 응용 프로그램에 대한 사용자 액세스입니다.</span><span class="sxs-lookup"><span data-stu-id="7840e-855">&emsp;&#x2713; User access to system components and the application(s).</span></span>

<span data-ttu-id="7840e-856">&emsp;&#x2713; 권한이 높은 사용자가 수행한 모든 작업입니다.</span><span class="sxs-lookup"><span data-stu-id="7840e-856">&emsp;&#x2713; All actions taken by a high privileged user.</span></span>

<span data-ttu-id="7840e-857">&emsp;&#x2713; 액세스 시도가 잘못되었습니다.</span><span class="sxs-lookup"><span data-stu-id="7840e-857">&emsp;&#x2713; Invalid logical access attempts.</span></span>

<span data-ttu-id="7840e-858">기록된 이벤트에 포함된지 보여 주며, 최소한 다음 정보가 있습니다.</span><span class="sxs-lookup"><span data-stu-id="7840e-858">Demonstrate that logged events contain; at a minimum, the following information:</span></span>

<span data-ttu-id="7840e-859">&emsp;&#x2713; 사용자.</span><span class="sxs-lookup"><span data-stu-id="7840e-859">&emsp;&#x2713; User.</span></span>

<span data-ttu-id="7840e-860">&emsp;&#x2713; 유형입니다.</span><span class="sxs-lookup"><span data-stu-id="7840e-860">&emsp;&#x2713; Type of Event.</span></span>

<span data-ttu-id="7840e-861">&emsp;&#x2713; 날짜 및 시간입니다.</span><span class="sxs-lookup"><span data-stu-id="7840e-861">&emsp;&#x2713; Date and Time.</span></span>

<span data-ttu-id="7840e-862">&emsp;&#x2713;/실패 표시기입니다.</span><span class="sxs-lookup"><span data-stu-id="7840e-862">&emsp;&#x2713; Success/Failure indicator.</span></span>

<span data-ttu-id="7840e-863">&emsp;&#x2713; 레이블을 사용하여 영향을 받는 시스템을 식별합니다.</span><span class="sxs-lookup"><span data-stu-id="7840e-863">&emsp;&#x2713; Label to identify the affected system.</span></span>

*   <span data-ttu-id="7840e-864">샘플 집합 내의 모든 시스템 구성 요소는 시간 동기화를 활용하도록 구성되어 있으며 기본/보조 시간 서버와 동일하다는 설명입니다.</span><span class="sxs-lookup"><span data-stu-id="7840e-864">Demonstrate that all system components within the sample set are configured to utilize time-synchronization and that these are the same as the primary/secondary time servers.</span></span>

* <span data-ttu-id="7840e-865">공용 시스템이 DMZ 내에 없는 중앙 로깅 솔루션에 로깅하는지 보여 주십시오.</span><span class="sxs-lookup"><span data-stu-id="7840e-865">Demonstrate that public facing systems are logging to a centralized logging solution which isn't within the DMZ.</span></span>

*   <span data-ttu-id="7840e-866">공용 시스템이 DMZ 내에 없는 중앙 로깅 솔루션에 로깅하는지 보여 주십시오.</span><span class="sxs-lookup"><span data-stu-id="7840e-866">Demonstrate that public facing systems are logging to a centralized logging solution which isn't within the DMZ.</span></span>

* <span data-ttu-id="7840e-867">중앙 로깅 솔루션이 로깅 데이터를 무단으로 변조하지 못하게 보호하는 방법을 보여줄 수 있습니다.</span><span class="sxs-lookup"><span data-stu-id="7840e-867">Demonstrate how the centralized logging solution is protected from unauthorized tampering of logging data.</span></span>

* <span data-ttu-id="7840e-868">최소 30일 이상의 로깅 데이터를 즉시 사용할 수 있는 방법(90일 이상 보존)을 보여줄 수 있습니다.</span><span class="sxs-lookup"><span data-stu-id="7840e-868">Demonstrate how a minimum of 30 days’ worth of logging data is immediately available, with 90 days’ or more being retained.</span></span>

<span data-ttu-id="7840e-869">**위험 관리**</span><span class="sxs-lookup"><span data-stu-id="7840e-869">**Risk Management**</span></span>

<span data-ttu-id="7840e-870">SOC2 감사는 위험 평가 프로세스의 일부 요소를 구체적으로 평가하지 않는 경우 다음을 요구합니다.</span><span class="sxs-lookup"><span data-stu-id="7840e-870">As SOC2 audits do not specifically assess some elements of risk assessment processes, this will require you to:</span></span>

* <span data-ttu-id="7840e-871">공식적인 위험 평가가 적어도 매년 수행됩니다.</span><span class="sxs-lookup"><span data-stu-id="7840e-871">Demonstrate that a formal risk assessment is conducted at least annually.</span></span>

<span data-ttu-id="7840e-872">*인시던트 대응.*</span><span class="sxs-lookup"><span data-stu-id="7840e-872">*Incident Response.*</span></span>

<span data-ttu-id="7840e-873">SOC2 감사는 인시던트 대응 정책 및 프로세스의 일부 요소를 구체적으로 평가하지 않는 경우 다음을 요구합니다.</span><span class="sxs-lookup"><span data-stu-id="7840e-873">As SOC2 audits do not specifically assess some elements of incident response policies and processes, this will require you to:</span></span>

* <span data-ttu-id="7840e-874">인시던트 대응 계획/절차에 다음이 포함됩니다.</span><span class="sxs-lookup"><span data-stu-id="7840e-874">Demonstrate that the incident response plan/procedure includes:</span></span>

<span data-ttu-id="7840e-875">&emsp;&#x2713; 위협 모델에 대한 특정 응답 절차입니다.</span><span class="sxs-lookup"><span data-stu-id="7840e-875">&emsp;&#x2713; Specific response procedures for expected threat models.</span></span>

<span data-ttu-id="7840e-876">&emsp;&#x2713; 주요 이해 관계자(결제 브랜드/인수자, 규제 기관, 감독 기관, 이사, 고객 등)의 시기 적절한 알림을 보장하기 위한 문서화된 통신 프로세스입니다.</span><span class="sxs-lookup"><span data-stu-id="7840e-876">&emsp;&#x2713; Documented communications process to ensure timely notification of key stakeholders (payment brands/acquirers, regulatory bodies, supervisory authorities, directors, customers, etc.</span></span>

## <a name="appendix-f"></a><span data-ttu-id="7840e-877">부록 F</span><span class="sxs-lookup"><span data-stu-id="7840e-877">Appendix F</span></span>

### <a name="hosting-deployment-types"></a><span data-ttu-id="7840e-878">호스팅 배포 유형</span><span class="sxs-lookup"><span data-stu-id="7840e-878">Hosting Deployment Types</span></span>

<span data-ttu-id="7840e-879">Microsoft는 응용 프로그램을 배포하고 다른 호스팅 환경 내에 앱/추가 기능 코드를 저장합니다.</span><span class="sxs-lookup"><span data-stu-id="7840e-879">Microsoft acknowledges you will deploy applications and store app/add-in code within different hosting environments.</span></span> <span data-ttu-id="7840e-880">Microsoft 365 인증 내의 일부 보안 제어에 대한 전반적인 책임은 사용 되는 호스팅 환경에 따라 달라 집니다.</span><span class="sxs-lookup"><span data-stu-id="7840e-880">The overall responsibilities of some of the security controls within the Microsoft 365 Certification will depend on the hosting environment being used.</span></span> <span data-ttu-id="7840e-881">부록 F는 일반적인 배포 유형을 검토하여 평가 프로세스의 일부로 평가되는 보안 컨트롤에 매핑합니다.</span><span class="sxs-lookup"><span data-stu-id="7840e-881">Appendix F looks at common deployment types and maps these against the security controls that are evaluated as part of the assessment process.</span></span> <span data-ttu-id="7840e-882">다음과 같은 호스팅 배포 유형이 확인되었습니다.</span><span class="sxs-lookup"><span data-stu-id="7840e-882">The following hosting deployment types have been identified:</span></span>

|<span data-ttu-id="7840e-883">호스팅 유형</span><span class="sxs-lookup"><span data-stu-id="7840e-883">Hosting Types</span></span>  |<span data-ttu-id="7840e-884">설명</span><span class="sxs-lookup"><span data-stu-id="7840e-884">Description</span></span>  |
|-----|------|
|<span data-ttu-id="7840e-885">**ISV Hosted**</span><span class="sxs-lookup"><span data-stu-id="7840e-885">**ISV Hosted**</span></span>|<span data-ttu-id="7840e-886">ISV 호스팅 형식은 앱/추가 기능 환경을 지원하는 데 사용되는 인프라를 담당하는 위치로 정의할 수 있습니다.</span><span class="sxs-lookup"><span data-stu-id="7840e-886">ISV hosted types can be defined as where you are responsible for the infrastructure used to support the app/add-in environment.</span></span> <span data-ttu-id="7840e-887">이 위치는 공동 위치 서비스가 있는 자체 데이터 센터 또는 타사 데이터 센터 내에 물리적으로 위치할 수 있습니다.</span><span class="sxs-lookup"><span data-stu-id="7840e-887">This can be physically located within your own data centers or third-party data centers with a co-location service.</span></span> <span data-ttu-id="7840e-888">궁극적으로 지원 인프라 및 운영 환경에 대한 모든 소유권과 관리 제어권이 있습니다.</span><span class="sxs-lookup"><span data-stu-id="7840e-888">Ultimately, you have full ownership and administrative control over the supporting infrastructure and operating environment.</span></span>|
|<span data-ttu-id="7840e-889">**IaaS(Infrastructure as a Service)** (https://azure.microsoft.com/en-gb/overview/what-is-iaas/)</span><span class="sxs-lookup"><span data-stu-id="7840e-889">**Infrastructure as a Service (IaaS)** (https://azure.microsoft.com/en-gb/overview/what-is-iaas/)</span></span>|<span data-ttu-id="7840e-890">인프라 as a Service는 클라우드 서비스 공급자(CSP)가 실제 지원 인프라를 대신하여 관리 및 유지 관리하는 경우 제공되는 서비스입니다.</span><span class="sxs-lookup"><span data-stu-id="7840e-890">Infrastructure as a Service is a service that is provided whereby the physical supporting infrastructure is managed and maintained on their behalf by the cloud service provider (CSP).</span></span> <span data-ttu-id="7840e-891">일반적으로 네트워킹, 저장소, 실제 서버 및 가상화 인프라는 모두 CSP의 책임입니다.</span><span class="sxs-lookup"><span data-stu-id="7840e-891">Typically, networking, storage, physical servers, and the virtualization infrastructure is all the responsibility of the CSP.</span></span> <span data-ttu-id="7840e-892">운영 체제, 미들웨어, 런타임, 데이터 및 응용 프로그램은 사용자 책임입니다.</span><span class="sxs-lookup"><span data-stu-id="7840e-892">The Operating System, Middleware, Runtime, Data and Applications are the responsibilities of you.</span></span> <span data-ttu-id="7840e-893">방화벽 기능은 타사에서 관리 및 유지 관리하기도 하지만 방화벽 규칙 기반의 유지 관리는 일반적으로 소비자의 책임입니다.</span><span class="sxs-lookup"><span data-stu-id="7840e-893">Firewalling capabilities would also be managed and maintained by the third-party, however maintenance of the firewall rule base would usually be still the consumers responsibility.</span></span>|
|<span data-ttu-id="7840e-894">**PaaS(Platform as a Service/Serverless)** (https://azure.microsoft.com/en-gb/overview/what-is-paas/)</span><span class="sxs-lookup"><span data-stu-id="7840e-894">**Platform as a Service/Serverless (PaaS)** (https://azure.microsoft.com/en-gb/overview/what-is-paas/)</span></span>| <span data-ttu-id="7840e-895">Platform as a Service를 사용하면 사용할 수 있는 서비스를 제공하는 관리되는 플랫폼으로 프로비전됩니다.</span><span class="sxs-lookup"><span data-stu-id="7840e-895">With Platform as a Service, you are provisioned with a managed platform presenting a service that can be consumed.</span></span> <span data-ttu-id="7840e-896">운영 체제와 지원 인프라가 CSP에서 관리되는 sysadmin 기능을 수행할 필요는 없습니다.</span><span class="sxs-lookup"><span data-stu-id="7840e-896">You do not need to perform sysadmin functions as the operating system and supporting infrastructure is managed by the CSP.</span></span> <span data-ttu-id="7840e-897">이 작업은 일반적으로 조직에서 웹 서비스를 제공하는 것을 염려하지 않고 대신 웹 응용 프로그램 소스 코드를 만들고 클라우드 관리 웹 서비스에 웹 응용 프로그램을 게시하는 데 집중할 수 있는 경우 사용됩니다.</span><span class="sxs-lookup"><span data-stu-id="7840e-897">This would typically be used when organizations do not want to be concerned with presenting a web service and instead can concentrate on creating the web application source code and publishing the web application on the cloud managed web services.</span></span>  <span data-ttu-id="7840e-898">또 다른 예로는 데이터베이스에 대한 연결이 제공된 데이터베이스 서비스이지만, 지원 인프라 및 데이터베이스 응용 프로그램은 소비자로부터 추상화됩니다.</span><span class="sxs-lookup"><span data-stu-id="7840e-898">Another example may be a database service where connectivity is given to a database, however the supporting infrastructure and database application is abstracted from the consumer.</span></span>   <span data-ttu-id="7840e-899">**참고: Serverless 및 PaaS는 유사하기 때문에 Microsoft 365 인증 호스팅 배포 유형의 Serverless 및 PasS는 동일한 것으로 확인됩니다.**</span><span class="sxs-lookup"><span data-stu-id="7840e-899">**Note: Serverless and PaaS are similar so for the purpose of the Microsoft 365 Certification Hosting Deployment Type's Serverless and PasS are deemed the same**</span></span>|
|<span data-ttu-id="7840e-900">**하이브리드 호스트**</span><span class="sxs-lookup"><span data-stu-id="7840e-900">**Hybrid Hosted**</span></span>|<span data-ttu-id="7840e-901">하이브리드 호스팅 형식을 사용하면 여러 호스팅 형식을 사용하여 지원 환경의 다양한 부분을 지원할 수 있습니다.</span><span class="sxs-lookup"><span data-stu-id="7840e-901">With the hybrid hosted type, you may utilize multiple hosted types to support various parts of the supporting environment.</span></span> <span data-ttu-id="7840e-902">이는 여러 M365 스택에서 앱/추가 기능을 사용하는 경우에 더 많이 있을 수 있습니다.</span><span class="sxs-lookup"><span data-stu-id="7840e-902">This may be more the case where apps/add-ins are utilized across multiple M365 stacks.</span></span> <span data-ttu-id="7840e-903">Microsoft 365 인증은 여러 M365 서비스에서 앱/추가 기능을 개발하는 위치를 지원하기는 하지만, 해당하는 각 "호스트된 형식 매핑"에 따라 전체(앱/추가 기능) 지원 환경에 대한 평가를 평가해야 합니다.</span><span class="sxs-lookup"><span data-stu-id="7840e-903">Although the Microsoft 365 Certification will support where apps/add-ons across multiple M365 services are developed, an assessment of the entire (across app/add-ins) supporting environment would need to be assessed in line with each of the applicable "Hosted Type Mappings".</span></span> <span data-ttu-id="7840e-904">경우에 따라 단일 추가 기능에서 서로 다른 호스팅된 형식을 사용할 수 있습니다. 이 경우 조건의 적용 가능성은 다양한 호스트 형식에서 "호스트된 형식 매핑" 기준을 따라야 합니다.</span><span class="sxs-lookup"><span data-stu-id="7840e-904">Occasionally, you may utilize different hosted types for a single add-in, where this is being carried out, applicability of criteria will need to still follow the "Hosted Type Mappings" criteria across the various hosted types.</span></span>|
|<span data-ttu-id="7840e-905">**공유 호스팅**</span><span class="sxs-lookup"><span data-stu-id="7840e-905">**Shared Hosting**</span></span>|<span data-ttu-id="7840e-906">공유 호스팅은 여러 개별 소비자가 공유하는 플랫폼 내에서 환경을 호스팅하는 위치입니다.</span><span class="sxs-lookup"><span data-stu-id="7840e-906">Shared hosting is where you are hosting the environment within a platform that shared by multiple individual consumers.</span></span> <span data-ttu-id="7840e-907">Microsoft 365 클라우드 채택으로 인해 공유 호스팅이 일반적이지 않습니다.</span><span class="sxs-lookup"><span data-stu-id="7840e-907">The Microsoft 365 Certification Specification was not written to account for this due to the adoption of cloud, shared hosting is not common.</span></span> <span data-ttu-id="7840e-908">이 사용이 필요하다고 생각되는 경우 Microsoft에 문의하여 이 유형의 호스팅 유형에 따라 추가 위험을 고려하기 위해 추가 요구 사항을 만들어야 합니다.</span><span class="sxs-lookup"><span data-stu-id="7840e-908">If you believe this is being used please contact Microsoft as additional requirements will need to be created to account for the additional risks under this type of hosting type.</span></span>|


## <a name="appendix-g"></a><span data-ttu-id="7840e-909">부록 G</span><span class="sxs-lookup"><span data-stu-id="7840e-909">Appendix G</span></span>

### <a name="microsoft-365-certification-process-workflow"></a><span data-ttu-id="7840e-910">Microsoft 365 인증 프로세스 워크플로</span><span class="sxs-lookup"><span data-stu-id="7840e-910">Microsoft 365 Certification Process Workflow</span></span>

![워크플로](ProcessFlow.jpg)

## <a name="learn-more"></a><span data-ttu-id="7840e-912">자세한 정보</span><span class="sxs-lookup"><span data-stu-id="7840e-912">Learn more</span></span>

[<span data-ttu-id="7840e-913">Microsoft 365 앱 준수 프로그램 개요</span><span class="sxs-lookup"><span data-stu-id="7840e-913">Microsoft 365 App Compliance Program Overview</span></span>](~/overview.md)  
[<span data-ttu-id="7840e-914">앱 Microsoft 365 는 Publisher 무엇입니까?</span><span class="sxs-lookup"><span data-stu-id="7840e-914">What is Microsoft 365 App Publisher Attestation?</span></span>](~/docs/attestation.md)  
[<span data-ttu-id="7840e-915">인증이란 Microsoft 365 무엇입니까?</span><span class="sxs-lookup"><span data-stu-id="7840e-915">What is Microsoft 365 Certification?</span></span>](~/docs/enterprise-app-certification-guide.md)

## <a name="glossary"></a><span data-ttu-id="7840e-916">용어집</span><span class="sxs-lookup"><span data-stu-id="7840e-916">Glossary</span></span>

### <a name="aia"></a><span data-ttu-id="7840e-917">AIA</span><span class="sxs-lookup"><span data-stu-id="7840e-917">AIA</span></span>

<span data-ttu-id="7840e-918">\*기관 정보 액세스는 발급 인증 기관의 인증서를 찾는 데 사용되는 서비스 위치 설명자입니다.</span><span class="sxs-lookup"><span data-stu-id="7840e-918">\*Authority Information Access is a service location descriptor used to find the certificate of the issuing certificate authority.</span></span>

### <a name="crl"></a><span data-ttu-id="7840e-919">CRL</span><span class="sxs-lookup"><span data-stu-id="7840e-919">CRL</span></span>

<span data-ttu-id="7840e-920">\*인증서 해지 목록은 SSL(Secure Sockets Layer) 끝점을 통해 원격 호스트에서 받은 인증서가 유효하고 신뢰할 수 있는지 확인할 수 있는 수단을 제공합니다.</span><span class="sxs-lookup"><span data-stu-id="7840e-920">\*Certificate Revocation List provide a means for a Secure Sockets Layer (SSL) endpoint to verify that a certificate received from a remote host is valid and trustworthy.</span></span>

### <a name="cvss-score"></a><span data-ttu-id="7840e-921">CVSS 점수</span><span class="sxs-lookup"><span data-stu-id="7840e-921">CVSS score</span></span>

<span data-ttu-id="7840e-922">\*공통 취약성 점수 체계는 취약점을 측정하고 심각도에 따라 숫자 점수를 계산하는 게시된 표준입니다.</span><span class="sxs-lookup"><span data-stu-id="7840e-922">\*Common Vulnerability Scoring System is a published standard that measures vulnerability and calculates a numerical score based on its severity.</span></span>

### <a name="cvss-patch-management-guidelines"></a><span data-ttu-id="7840e-923">CVSS 패치 관리 지침</span><span class="sxs-lookup"><span data-stu-id="7840e-923">CVSS patch management guidelines</span></span>

* <span data-ttu-id="7840e-924">Critical(9.0 - 10.0)</span><span class="sxs-lookup"><span data-stu-id="7840e-924">Critical (9.0 - 10.0)</span></span>
* <span data-ttu-id="7840e-925">높음(7.0 - 8.9)</span><span class="sxs-lookup"><span data-stu-id="7840e-925">High (7.0 - 8.9)</span></span>
* <span data-ttu-id="7840e-926">보통(4.0 - 6.9)</span><span class="sxs-lookup"><span data-stu-id="7840e-926">Medium (4.0 - 6.9)</span></span>
* <span data-ttu-id="7840e-927">낮음(0.0 - 3.9)</span><span class="sxs-lookup"><span data-stu-id="7840e-927">Low (0.0 - 3.9)</span></span>

### <a name="dmz"></a><span data-ttu-id="7840e-928">DMZ</span><span class="sxs-lookup"><span data-stu-id="7840e-928">DMZ</span></span>

<span data-ttu-id="7840e-929">\*비미리타입 영역은 호스트의 내부 개인 네트워크를 분리하고 격리하면서 외부 또는 비소유 네트워크와 직접 상호 작용하는 물리적 또는 논리적 중간 네트워크입니다.</span><span class="sxs-lookup"><span data-stu-id="7840e-929">\*Demilitarized zone is a physical or logical intermediate network that interacts directly external or non-propriety networks while keeping the host's internal, private network separate and isolated.</span></span>

### <a name="euii"></a><span data-ttu-id="7840e-930">EUII</span><span class="sxs-lookup"><span data-stu-id="7840e-930">EUII</span></span>

<span data-ttu-id="7840e-931">*최종 사용자 식별 가능 정보.*</span><span class="sxs-lookup"><span data-stu-id="7840e-931">*End-user identifiable information*.</span></span>

### <a name="gdpr"></a><span data-ttu-id="7840e-932">GDPR</span><span class="sxs-lookup"><span data-stu-id="7840e-932">GDPR</span></span>

<span data-ttu-id="7840e-933">\*일반 데이터 보호 규정은 응용 프로그램 사이트가 있는 위치와 관계없이 모든 EU 시민 데이터에 대한 유럽 연합(EU) 개인 정보 보호 및 데이터 보호 규정입니다.</span><span class="sxs-lookup"><span data-stu-id="7840e-933">\*General Data Protection Regulation is a European Union (EU) privacy and data protection regulation for all EU citizens’ data regardless of where your application site is located.</span></span>

### <a name="hsts"></a><span data-ttu-id="7840e-934">HSTS</span><span class="sxs-lookup"><span data-stu-id="7840e-934">HSTS</span></span>

<span data-ttu-id="7840e-935">\*HTTP Strict Transport Security는 HTTPS를 통해 콘텐츠에만 액세스하는 웹 브라우저에 지시하는 HTTP 응답 헤더를 사용합니다.</span><span class="sxs-lookup"><span data-stu-id="7840e-935">\*HTTP Strict Transport Security utilizes a HTTP response header instructing the web browser to only access content over HTTPS.</span></span>  <span data-ttu-id="7840e-936">이는 다운그레이드 공격 및 쿠키 하이재킹으로부터 보호하기 위해 고안된 것입니다.</span><span class="sxs-lookup"><span data-stu-id="7840e-936">This is designed to protect against downgrade attacks and cookie hijacking.</span></span>

### <a name="iec"></a><span data-ttu-id="7840e-937">IEC</span><span class="sxs-lookup"><span data-stu-id="7840e-937">IEC</span></span>

<span data-ttu-id="7840e-938">\*International Electrotechnical Commission.</span><span class="sxs-lookup"><span data-stu-id="7840e-938">\*International Electrotechnical Commission.</span></span>

### <a name="isms"></a><span data-ttu-id="7840e-939">ISMS</span><span class="sxs-lookup"><span data-stu-id="7840e-939">ISMS</span></span>

<span data-ttu-id="7840e-940">\*정보 보안 관리 시스템.</span><span class="sxs-lookup"><span data-stu-id="7840e-940">\*Information Security Management System.</span></span>

### <a name="isv"></a><span data-ttu-id="7840e-941">ISV</span><span class="sxs-lookup"><span data-stu-id="7840e-941">ISV</span></span>

<span data-ttu-id="7840e-942">독립 보안 공급업체는 타사 소프트웨어 및 하드웨어 플랫폼에서 실행되는 소프트웨어를 개발, 출시 및 판매하는 개인 및 조직입니다.</span><span class="sxs-lookup"><span data-stu-id="7840e-942">Independent Security Vendors are individuals and organizations who develop, market and sell software that runs on third-party software and hardware platforms.</span></span>

### <a name="iso-27001"></a><span data-ttu-id="7840e-943">ISO 27001</span><span class="sxs-lookup"><span data-stu-id="7840e-943">ISO 27001</span></span>

<span data-ttu-id="7840e-944">조직 위험 관리 정책 및 절차 프로세스의 모든 기술 제어를 위한 정보 보안 관리 시스템 사양 프레임워크입니다.</span><span class="sxs-lookup"><span data-stu-id="7840e-944">An information security management system specification framework for all technical controls in an organizations risk management policies and procedures processes.</span></span>

### <a name="lfi"></a><span data-ttu-id="7840e-945">LFI</span><span class="sxs-lookup"><span data-stu-id="7840e-945">LFI</span></span>

<span data-ttu-id="7840e-946">*로컬 파일 포함을* 사용하면 공격자가 웹 브라우저를 통해 서버에 파일을 포함할 수 있습니다.</span><span class="sxs-lookup"><span data-stu-id="7840e-946">*Local File Inclusion* allows an attacker to include files on a server through the web browser.</span></span>

### <a name="nist"></a><span data-ttu-id="7840e-947">NIST</span><span class="sxs-lookup"><span data-stu-id="7840e-947">NIST</span></span>

<span data-ttu-id="7840e-948">미국 상무부의 비규격 기관인 NIST(National *Institute of Standards)는* 미국 내 개인 부문 조직이 사이버 공격을 방지, 탐지 및 대응하는 능력을 평가하고 승인할 수 있는 지침을 제공합니다.</span><span class="sxs-lookup"><span data-stu-id="7840e-948">The *National Institute of Standards* (NIST), a non-regulatory agency of the U.S. Department of Commerce  provides guidance for private sector organizations in the US to assess and approve their ability to prevent, detect, and respond to cyber attacks.</span></span>

### <a name="non-significant-changes"></a><span data-ttu-id="7840e-949">중요하지 않은 변경 내용</span><span class="sxs-lookup"><span data-stu-id="7840e-949">Non-Significant changes</span></span>

* <span data-ttu-id="7840e-950">경미한 버그 수정.</span><span class="sxs-lookup"><span data-stu-id="7840e-950">Minor Bug fixes.</span></span>
* <span data-ttu-id="7840e-951">성능이 사소하게 향상됩니다.</span><span class="sxs-lookup"><span data-stu-id="7840e-951">Minor performance improvements.</span></span>
* <span data-ttu-id="7840e-952">운영 체제/라이브러리/클라이언트 및 서버 응용 프로그램 패치.</span><span class="sxs-lookup"><span data-stu-id="7840e-952">Operating systems/libraries/client and server application patches.</span></span>

### <a name="ocsp"></a><span data-ttu-id="7840e-953">OCSP</span><span class="sxs-lookup"><span data-stu-id="7840e-953">OCSP</span></span>

<span data-ttu-id="7840e-954">*온라인 인증서 상태 프로토콜은* X.509 디지털 인증서의 해지 상태를 검사하는 데 사용됩니다.</span><span class="sxs-lookup"><span data-stu-id="7840e-954">*Online Certificate Status Protocol* is used to check the revocation status of X.509 digital certificates.</span></span>

### <a name="oii"></a><span data-ttu-id="7840e-955">OII</span><span class="sxs-lookup"><span data-stu-id="7840e-955">OII</span></span>

<span data-ttu-id="7840e-956">*조직 식별이 가능한 정보입니다.*</span><span class="sxs-lookup"><span data-stu-id="7840e-956">*Organizational identifiable information*.</span></span>

### <a name="owasp"></a><span data-ttu-id="7840e-957">OWASP</span><span class="sxs-lookup"><span data-stu-id="7840e-957">OWASP</span></span>

<span data-ttu-id="7840e-958">*웹 응용 프로그램 보안 Project.*</span><span class="sxs-lookup"><span data-stu-id="7840e-958">*Open Web Application Security Project*.</span></span>

### <a name="pci-dss"></a><span data-ttu-id="7840e-959">PCI DSS</span><span class="sxs-lookup"><span data-stu-id="7840e-959">PCI DSS</span></span>

<span data-ttu-id="7840e-960">*Payment Card Industry Data Security Standard*- 전 세계 카드주 데이터의 안전에 대한 표준을 유지하는 조직입니다.</span><span class="sxs-lookup"><span data-stu-id="7840e-960">*Payment Card Industry Data Security Standard*, an organization that maintains standards for the safety of cardholder data worldwide.</span></span>

### <a name="pen-testing"></a><span data-ttu-id="7840e-961">펜 테스트</span><span class="sxs-lookup"><span data-stu-id="7840e-961">Pen testing</span></span>

<span data-ttu-id="7840e-962">*침투 테스트는* 악의적인 공격을 시뮬레이션하여 공격자가 악용할 수 있는 보안 취약성을 찾아 웹앱을 테스트하는 방법입니다.</span><span class="sxs-lookup"><span data-stu-id="7840e-962">*Penetration testing* is a method of testing a web app by simulating malicious attacks to find security vulnerabilities that an attacker could exploit.</span></span>

### <a name="saml"></a><span data-ttu-id="7840e-963">SAML</span><span class="sxs-lookup"><span data-stu-id="7840e-963">SAML</span></span>

<span data-ttu-id="7840e-964">*Security Assertion Markup Language는* 사용자, ID 공급자 및 서비스 공급자 간의 인증 및 권한 부여 데이터를 변경하기 위한 개방형 표준입니다.</span><span class="sxs-lookup"><span data-stu-id="7840e-964">*Security Assertion Markup Language* is s an open standard for exchanging authentication and authorization data between the user, the identity provider and the service provider.</span></span>

### <a name="sensitive-data"></a><span data-ttu-id="7840e-965">중요한 데이터</span><span class="sxs-lookup"><span data-stu-id="7840e-965">Sensitive Data</span></span>

* <span data-ttu-id="7840e-966">액세스 제어 데이터.</span><span class="sxs-lookup"><span data-stu-id="7840e-966">Access control data.</span></span>
* <span data-ttu-id="7840e-967">고객 콘텐츠.</span><span class="sxs-lookup"><span data-stu-id="7840e-967">Customer content.</span></span>
* <span data-ttu-id="7840e-968">최종 사용자 ID 정보입니다.</span><span class="sxs-lookup"><span data-stu-id="7840e-968">End-user identity information.</span></span>
* <span data-ttu-id="7840e-969">지원 데이터.</span><span class="sxs-lookup"><span data-stu-id="7840e-969">Support data.</span></span>
* <span data-ttu-id="7840e-970">공용 개인 데이터.</span><span class="sxs-lookup"><span data-stu-id="7840e-970">Public personal data.</span></span>
* <span data-ttu-id="7840e-971">최종 사용자 가명 정보.</span><span class="sxs-lookup"><span data-stu-id="7840e-971">End-user pseudonymous information.</span></span>

### <a name="significant-changes"></a><span data-ttu-id="7840e-972">중요한 변경 사항</span><span class="sxs-lookup"><span data-stu-id="7840e-972">Significant changes</span></span>

* <span data-ttu-id="7840e-973">호스팅 환경의 위치입니다.</span><span class="sxs-lookup"><span data-stu-id="7840e-973">Relocation of the hosting environment.</span></span>
* <span data-ttu-id="7840e-974">지원 인프라로의 주요 업그레이드 예를 들어 새 방화벽 구현, 전면 서비스에 대한 주요 업그레이드 등</span><span class="sxs-lookup"><span data-stu-id="7840e-974">Major upgrades to the supporting infrastructure; for example, implementation of a new firewall, major upgrades to front facing services, etc.</span></span>
* <span data-ttu-id="7840e-975">앱에 기능 및 /또는 확장 추가.</span><span class="sxs-lookup"><span data-stu-id="7840e-975">Addition of capabilities and /or extensions to your app.</span></span>
* <span data-ttu-id="7840e-976">추가 중요한 데이터를 캡처하는 앱 업데이트입니다.</span><span class="sxs-lookup"><span data-stu-id="7840e-976">Updates to your app that capture additional sensitive Data.</span></span>
* <span data-ttu-id="7840e-977">앱의 데이터 흐름 또는 권한 부여 모델 변경</span><span class="sxs-lookup"><span data-stu-id="7840e-977">Changes to your app's data flows or authorization models</span></span>
* <span data-ttu-id="7840e-978">API 끝점 또는 API 끝점 함수 추가.</span><span class="sxs-lookup"><span data-stu-id="7840e-978">Addition of API endpoints or API endpoint functions.</span></span>

### <a name="soc-2"></a><span data-ttu-id="7840e-979">SOC 2</span><span class="sxs-lookup"><span data-stu-id="7840e-979">SOC 2</span></span>

<span data-ttu-id="7840e-980">*서비스 조직 제어 2*: 서비스 공급자가 조직의 클라이언트에 대한 데이터 및 개인 정보를 안전하게 관리하도록 보장하기 위해 5개의 보안 서비스 원칙으로 구성된 기술 감사 절차입니다.</span><span class="sxs-lookup"><span data-stu-id="7840e-980">*Service Organization Control 2*, a technical auditing procedure comprised of five Trust Service Principles to ensure that service providers securely manage the data and privacy for an organization's clients.</span></span>

### <a name="ssl"></a><span data-ttu-id="7840e-981">SSL</span><span class="sxs-lookup"><span data-stu-id="7840e-981">SSL</span></span>

<span data-ttu-id="7840e-982">*Secure Sockets Layer*.</span><span class="sxs-lookup"><span data-stu-id="7840e-982">*Secure Sockets Layer*.</span></span>

### <a name="tls"></a><span data-ttu-id="7840e-983">TLS</span><span class="sxs-lookup"><span data-stu-id="7840e-983">TLS</span></span>

<span data-ttu-id="7840e-984">*전송 계층 보안*.</span><span class="sxs-lookup"><span data-stu-id="7840e-984">*Transport Layer Security*.</span></span>
