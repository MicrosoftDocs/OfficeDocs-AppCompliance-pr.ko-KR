---
ms.author: oromalle
title: Microsoft 365 인증 제출 가이드
author: orionomalley
description: Microsoft 365 인증 제출 가이드 세분화 보기
keywords: 앱 인증 팀 Microsoft 365 보안 준수 m365
ms.topic: conceptual
ms.service: attestation
ms.openlocfilehash: 4d0f09b3a1dd6bde7022e93d08a491e2855d90a7
ms.sourcegitcommit: e97156a6eaf1d5ec5c26fd14add210a92bacd944
ms.translationtype: MT
ms.contentlocale: ko-KR
ms.lasthandoff: 04/28/2021
ms.locfileid: "52071367"
---
# <a name="microsoft-365-certification-submission-guide"></a><span data-ttu-id="e3a11-104">Microsoft 365 인증 제출 가이드</span><span class="sxs-lookup"><span data-stu-id="e3a11-104">Microsoft 365 Certification Submission Guide</span></span>

<span data-ttu-id="e3a11-105">**이 문서의 내용**</span><span class="sxs-lookup"><span data-stu-id="e3a11-105">**In this article:**</span></span>
- [<span data-ttu-id="e3a11-106">소개</span><span class="sxs-lookup"><span data-stu-id="e3a11-106">Introduction</span></span>](#introduction)
- [<span data-ttu-id="e3a11-107">필수 구성 요소</span><span class="sxs-lookup"><span data-stu-id="e3a11-107">Prerequisites</span></span>](#prerequisites) 
- [<span data-ttu-id="e3a11-108">Microsoft 365 인증 사양 업데이트</span><span class="sxs-lookup"><span data-stu-id="e3a11-108">Microsoft 365 Certification Specification Updates</span></span>](#microsoft-365-certification-specification-updates)
- [<span data-ttu-id="e3a11-109">인증 범위</span><span class="sxs-lookup"><span data-stu-id="e3a11-109">Certification Scope</span></span>](#certification-scope)
- [<span data-ttu-id="e3a11-110">인증 프로세스</span><span class="sxs-lookup"><span data-stu-id="e3a11-110">Certification Process</span></span>](#certification-process)
- [<span data-ttu-id="e3a11-111">준수 증거</span><span class="sxs-lookup"><span data-stu-id="e3a11-111">Compliance Evidence</span></span>](#compliance-evidence) 
- [<span data-ttu-id="e3a11-112">초기 문서 제출</span><span class="sxs-lookup"><span data-stu-id="e3a11-112">Initial Document submission</span></span>](#initial-document-submission) 
- [<span data-ttu-id="e3a11-113">증거 수집 및 평가 활동</span><span class="sxs-lookup"><span data-stu-id="e3a11-113">Evidence Collection and Assessment Activities</span></span>](#evidence-collection-and-assessment-activities)
- [<span data-ttu-id="e3a11-114">인증 기준</span><span class="sxs-lookup"><span data-stu-id="e3a11-114">Certification Criteria</span></span>](#app-certification-criteria)
- [<span data-ttu-id="e3a11-115">Application Security</span><span class="sxs-lookup"><span data-stu-id="e3a11-115">Application Security</span></span>](#application-security)
- [<span data-ttu-id="e3a11-116">운영 보안</span><span class="sxs-lookup"><span data-stu-id="e3a11-116">Operational Security</span></span>](#operational-security) 
- [<span data-ttu-id="e3a11-117">데이터 처리 보안 및 개인 정보</span><span class="sxs-lookup"><span data-stu-id="e3a11-117">Data Handling Security and Privacy</span></span>](#data-handling-security-and-privacy)
- [<span data-ttu-id="e3a11-118">선택적 외부 준수 프레임워크 검토</span><span class="sxs-lookup"><span data-stu-id="e3a11-118">Optional External Compliance Frameworks Review</span></span>](#optional-external-compliance-frameworks-review)
- [<span data-ttu-id="e3a11-119">부록 A</span><span class="sxs-lookup"><span data-stu-id="e3a11-119">Appendix A</span></span>](#appendix-a)
- [<span data-ttu-id="e3a11-120">부록 B</span><span class="sxs-lookup"><span data-stu-id="e3a11-120">Appendix B</span></span>](#appendix-b) 
- [<span data-ttu-id="e3a11-121">부록 C</span><span class="sxs-lookup"><span data-stu-id="e3a11-121">Appendix C</span></span>](#appendix-c) 
- [<span data-ttu-id="e3a11-122">부록 D</span><span class="sxs-lookup"><span data-stu-id="e3a11-122">Appendix D</span></span>](#appendix-d) 
- [<span data-ttu-id="e3a11-123">부록 E</span><span class="sxs-lookup"><span data-stu-id="e3a11-123">Appendix E</span></span>](#appendix-e) 
- [<span data-ttu-id="e3a11-124">부록 F</span><span class="sxs-lookup"><span data-stu-id="e3a11-124">Appendix F</span></span>](#appendix-f) 
- [<span data-ttu-id="e3a11-125">부록 G </span><span class="sxs-lookup"><span data-stu-id="e3a11-125">Appendix G </span></span>](#appendix-g)
- [<span data-ttu-id="e3a11-126">자세한 정보</span><span class="sxs-lookup"><span data-stu-id="e3a11-126">Learn more</span></span>](#learn-more) 
- [<span data-ttu-id="e3a11-127">용어</span><span class="sxs-lookup"><span data-stu-id="e3a11-127">Glossary</span></span>](#glossary) 


## <a name="introduction"></a><span data-ttu-id="e3a11-128">소개</span><span class="sxs-lookup"><span data-stu-id="e3a11-128">Introduction</span></span>

<span data-ttu-id="e3a11-129">Microsoft 365 앱 준수 프로그램의 일부인 Microsoft 365 인증은 타사 개발자 앱/추가 기능을 Microsoft 365 플랫폼에 통합할 때 데이터 및 개인 정보 보호가 적절하게 보호되는 보증과 확신을 기업 조직에 제공합니다.</span><span class="sxs-lookup"><span data-stu-id="e3a11-129">Part of the Microsoft 365 App Compliance program, the Microsoft 365 Certification offers assurance and confidence to enterprise organizations that data and privacy are adequately secured and protected when integrating third-party developer apps/add-ins into the Microsoft 365 platform.</span></span> <span data-ttu-id="e3a11-130">유효성 검사를 통과하는 응용 프로그램 및 추가 기능은 Microsoft 365 에코시스템 전체에서 **Microsoft 365 인증으로** 지정됩니다.</span><span class="sxs-lookup"><span data-stu-id="e3a11-130">Applications and add-ins that pass validation will be designated **Microsoft 365 Certified** throughout the Microsoft 365 ecosystem.</span></span> 

<span data-ttu-id="e3a11-131">Microsoft 365 인증 프로그램에 참여하면 귀하는 이러한 추가 약관에 동의하고 Microsoft Corporation과의 Microsoft 365 인증 프로그램에 참여하는 데 적용되는 모든 관련 설명서("Microsoft", "Microsoft", "당사", "당사" 또는 "당사")를 준수하는 데 동의합니다.</span><span class="sxs-lookup"><span data-stu-id="e3a11-131">By participating in the Microsoft 365 Certification  program, you are agreeing to these supplemental terms and to comply with any accompanying documentation that applies to your participation in the Microsoft 365 Certification program with Microsoft Corporation ("Microsoft", "we", "us",  or "our").</span></span> <span data-ttu-id="e3a11-132">귀하는 적용 가능한 경우 사용자, 회사 및/또는 기타 엔터티를 대신하여 이러한 Microsoft 365 인증 보조 약관에 동의할 권한이 있는 것으로 표현하고 Microsoft에 이를 요구합니다.</span><span class="sxs-lookup"><span data-stu-id="e3a11-132">You represent and warrant to us that you have the authority to accept these Microsoft 365 Certification supplemental terms on behalf of yourself, a company, and/or other entity, as applicable.</span></span> <span data-ttu-id="e3a11-133">당사는 이러한 추가 약관을 변경, 수정 또는 종료할 수 있습니다.</span><span class="sxs-lookup"><span data-stu-id="e3a11-133">We may change, amend or terminate these supplemental terms at any time.</span></span> <span data-ttu-id="e3a11-134">변경 또는 수정 후 Microsoft 365 인증 프로그램에 계속 참여하면 새로운 추가 약관에 동의하는 것입니다.</span><span class="sxs-lookup"><span data-stu-id="e3a11-134">Your continued participation in the Microsoft 365 Certification program after any change or amendment means you agree to the new supplemental terms.</span></span> <span data-ttu-id="e3a11-135">새 추가 약관에 동의하지 않는 경우 또는 이러한 추가 약관을 종료하는 경우 Microsoft 365 인증 프로그램에 참여하지 말아야 합니다.</span><span class="sxs-lookup"><span data-stu-id="e3a11-135">If you do not agree to the new supplemental terms or if we terminate these supplemental terms, you must stop participating in the Microsoft 365 Certification program.</span></span>

<span data-ttu-id="e3a11-136">이 문서는 ISV(Independent Software Vendor)가 Microsoft 365 인증 프로세스에 대한 정보, 프로세스 시작을 위한 선행 요구 사항 및 ISV에 있어야 하는 특정 보안 제어에 대한 세부 정보를 제공하기 위한 것입니다.</span><span class="sxs-lookup"><span data-stu-id="e3a11-136">This document is aimed at ISVs (Independent Software Vendors) to provide information on the Microsoft 365 Certification process, prerequisites to starting the process and details of specific security controls that ISVs must have in place.</span></span>  <span data-ttu-id="e3a11-137">Microsoft 365 앱 준수 프로그램의 일반 정보는 Microsoft 365 앱 준수 프로그램 페이지에서 찾을 수 [있습니다.](https://docs.microsoft.com/microsoft-365-app-certification/overview)</span><span class="sxs-lookup"><span data-stu-id="e3a11-137">General information of the Microsoft 365 App Compliance program can be found under the Microsoft 365 App Compliance program [page](https://docs.microsoft.com/microsoft-365-app-certification/overview).</span></span> 

> [!IMPORTANT]
> <span data-ttu-id="e3a11-138">현재 Microsoft 365 인증은 제한됩니다.</span><span class="sxs-lookup"><span data-stu-id="e3a11-138">Currently, Microsoft 365 Certification is limited:</span></span>
>* <span data-ttu-id="e3a11-139">Microsoft Teams 응용 프로그램(탭, 봇 등)입니다.</span><span class="sxs-lookup"><span data-stu-id="e3a11-139">Microsoft Teams applications (Tabs, Bots, etc.) .</span></span>
>* <span data-ttu-id="e3a11-140">Sharepoint 앱/추가 기능</span><span class="sxs-lookup"><span data-stu-id="e3a11-140">Sharepoint Apps/Add-ins</span></span>
>* <span data-ttu-id="e3a11-141">Office 추가 기능(Word, Excel, PowerPoint, Outlook, Project, OneNote)</span><span class="sxs-lookup"><span data-stu-id="e3a11-141">Office Add-ins (Word, Excel, PowerPoint, Outlook, Project, OneNote)</span></span>

## <a name="prerequisites"></a><span data-ttu-id="e3a11-142">필수 구성 요소</span><span class="sxs-lookup"><span data-stu-id="e3a11-142">Prerequisites</span></span>

### <a name="publisher-attestation"></a><span data-ttu-id="e3a11-143">게시자 Attestation</span><span class="sxs-lookup"><span data-stu-id="e3a11-143">Publisher Attestation</span></span>

<span data-ttu-id="e3a11-144">Microsoft 365 인증 프로세스를 수여하기 전에 게시자 증명을 완료해야 합니다.</span><span class="sxs-lookup"><span data-stu-id="e3a11-144">Before being awarded the Microsoft 365 Certification process you must have completed Publisher Attestation.</span></span> <span data-ttu-id="e3a11-145">그러나 게시자 증명을 완료하기 전에 Microsoft 365 인증 프로세스를 시작할 수 있습니다.</span><span class="sxs-lookup"><span data-stu-id="e3a11-145">However, you may start the Microsoft 365 Certification process prior to completing Publisher Attestation.</span></span>  

### <a name="read-the-microsoft-365-certification-specification"></a><span data-ttu-id="e3a11-146">Microsoft 365 인증 사양 읽기</span><span class="sxs-lookup"><span data-stu-id="e3a11-146">Read the Microsoft 365 Certification Specification</span></span>

<span data-ttu-id="e3a11-147">Microsoft는 모든 ISV(Independent Software Vendor)가 이 Microsoft 365 인증 사양을 전체적으로 읽어 범위 내 환경 및 앱/추가 기능을 통해 적용 가능한 모든 컨트롤이 충족되도록 하는 것이 좋습니다.</span><span class="sxs-lookup"><span data-stu-id="e3a11-147">Microsoft recommends all ISVs (Independent Software Vendor) to read this Microsoft 365 Certification Specification in its entirety to ensure all applicable controls are being met by the in-scope environment and the app/add-in.</span></span> <span data-ttu-id="e3a11-148">이렇게 하면 원활한 평가 프로세스를 보장하는 데 도움이 됩니다.</span><span class="sxs-lookup"><span data-stu-id="e3a11-148">This will help ensure a smooth assessment process.</span></span>

## <a name="microsoft-365-certification-specification-updates"></a><span data-ttu-id="e3a11-149">Microsoft 365 인증 사양 업데이트</span><span class="sxs-lookup"><span data-stu-id="e3a11-149">Microsoft 365 Certification Specification Updates</span></span> 

<span data-ttu-id="e3a11-150">Microsoft 365 인증 사양의 업데이트는 약 6~12개월마다 예상됩니다.</span><span class="sxs-lookup"><span data-stu-id="e3a11-150">Updates to the Microsoft 365 Certification specification are anticipated approximately every six to twelve months.</span></span> <span data-ttu-id="e3a11-151">이러한 업데이트는 새로운 대상 보안 도메인 및/또는 보안 제어를 도입할 수 있습니다.</span><span class="sxs-lookup"><span data-stu-id="e3a11-151">These updates might introduce new target security domains and / or security controls.</span></span> <span data-ttu-id="e3a11-152">업데이트는 개발자 피드백, 위협 환경 변경을 기반으로 하여 프로그램의 보안 기준이 완성될 때 증가합니다.</span><span class="sxs-lookup"><span data-stu-id="e3a11-152">Updates will be based on developer feedback, changes to the threat landscape, and to increase the security baseline of the program as it matures.</span></span> 

<span data-ttu-id="e3a11-153">이미 Microsoft 365 인증 평가를 시작한 ISV는 평가가 시작될 때 유효한 Microsoft 365 인증 사양 버전으로 평가를 계속할 수 있습니다.</span><span class="sxs-lookup"><span data-stu-id="e3a11-153">ISVs that have already started the Microsoft 365 Certification assessment can continue the assessment with the version of the Microsoft 365 Certification Specification that was valid when the assessment was started.</span></span> <span data-ttu-id="e3a11-154">연간 재인증을 비롯한 모든 새 제출은 게시된 버전에 대해 평가해야 합니다.</span><span class="sxs-lookup"><span data-stu-id="e3a11-154">All new submissions, including annual recertification, will be required to be assessed against the version published.</span></span>

> [!NOTE]
> <span data-ttu-id="e3a11-155">인증을 획득하기 위해 이 Microsoft 365 인증 사양 내의 모든 컨트롤을 준수할 필요는 없습니다.</span><span class="sxs-lookup"><span data-stu-id="e3a11-155">You are not required to comply with all the controls within this Microsoft 365 Certification Specification to be awarded a certification.</span></span> <span data-ttu-id="e3a11-156">그러나 이 Microsoft 365 인증 사양에 설명된 각 보안 도메인에 대해 전달 임계값(공개되지 않을)이 설정되어 있습니다.</span><span class="sxs-lookup"><span data-stu-id="e3a11-156">However, passing thresholds (which will not be disclosed) are in place for each of the security domains discussed within this Microsoft 365 Certification Specification.</span></span> <span data-ttu-id="e3a11-157">일부 컨트롤은 **'하드** 실패'로 분류됩니다. 즉, 이러한 보안 컨트롤이 부족하면 평가에 실패하게 됩니다.</span><span class="sxs-lookup"><span data-stu-id="e3a11-157">Some controls will be classed as a ‘**Hard Fail**’ which means the lack of these security controls will result in a failed assessment.</span></span> 

## <a name="certification-scope"></a><span data-ttu-id="e3a11-158">인증 범위</span><span class="sxs-lookup"><span data-stu-id="e3a11-158">Certification Scope</span></span>

<span data-ttu-id="e3a11-159">범위 **내** 환경은 앱/추가 기능 코드 배달을 지원하고 앱/추가 기능과 통신할 수 있는 모든 백end 시스템을 지원하는 환경입니다.</span><span class="sxs-lookup"><span data-stu-id="e3a11-159">The **in-scope environment** is the environment that supports delivery of the app/add-in code and supports any backend systems that the app/add-in may be communicating with.</span></span> <span data-ttu-id="e3a11-160">적절한 세분화가 이행되고 연결된 환경이 범위 내 환경의 보안에 영향을 줄 수 없는 경우를 위해 추가 연결된 환경도 범위에 포함됩니다.</span><span class="sxs-lookup"><span data-stu-id="e3a11-160">Any additional connected-to environments will also be included in scope unless adequate segmentation is in place AND the connected-to environments cannot impact the security of the in-scope environment.</span></span> <span data-ttu-id="e3a11-161">또한 기본 환경에 모든 일이 발생하면 서비스를 이행하는 데 이러한 환경이 필요하기 때문에 재해 복구 환경도 평가 범위 내에 포함해야 합니다.</span><span class="sxs-lookup"><span data-stu-id="e3a11-161">Any disaster recovery environments will also need to be included within the scope of the assessment as these environments would be required to fulfil the service should anything happen to the primary environment.</span></span>  <span data-ttu-id="e3a11-162">범위 내 **시스템 구성 요소 용어는** 범위 내 환경에서 사용되는 모든 장치 및   시스템을 참조합니다. </span><span class="sxs-lookup"><span data-stu-id="e3a11-162">The term  **in-scope system components** reference **ALL** devices and systems that are used within the in-scope environment.</span></span> <span data-ttu-id="e3a11-163">범위 내 구성 요소에는 다음이 포함됩니다.</span><span class="sxs-lookup"><span data-stu-id="e3a11-163">In-scope components include, but are not limited to:</span></span>
* <span data-ttu-id="e3a11-164">웹 응용 프로그램.</span><span class="sxs-lookup"><span data-stu-id="e3a11-164">The web application(s).</span></span>
* <span data-ttu-id="e3a11-165">서버.</span><span class="sxs-lookup"><span data-stu-id="e3a11-165">Servers.</span></span>
* <span data-ttu-id="e3a11-166">방화벽(또는 그에 상응하는 방화벽)</span><span class="sxs-lookup"><span data-stu-id="e3a11-166">Firewalls (or equivalent).</span></span>
* <span data-ttu-id="e3a11-167">스위치.</span><span class="sxs-lookup"><span data-stu-id="e3a11-167">Switches.</span></span>
* <span data-ttu-id="e3a11-168">부하를 균형 조정합니다.</span><span class="sxs-lookup"><span data-stu-id="e3a11-168">Load balancers.</span></span>
* <span data-ttu-id="e3a11-169">가상 인프라.</span><span class="sxs-lookup"><span data-stu-id="e3a11-169">Virtual infrastructure.</span></span>
* <span data-ttu-id="e3a11-170">클라우드 공급자 웹 관리 포털</span><span class="sxs-lookup"><span data-stu-id="e3a11-170">Cloud provider web management portals</span></span> 

> [!IMPORTANT]
> <span data-ttu-id="e3a11-171">범위 내 환경에는 DMZ가 있어야 합니다. 앱/추가 기능의 지원 환경은 내부 비즈니스 시스템 및 회사 환경에서 분할해야 따라서 평가 작업의 범위를 범위 내 시스템으로만 제한할 수 있습니다.</span><span class="sxs-lookup"><span data-stu-id="e3a11-171">The in-scope environment, must have a DMZ and the supporting environment of the app/add-in must be segmented from the internal business systems and corporate environments thus limiting the scope of the assessment activities to the in-scope systems only.</span></span> <span data-ttu-id="e3a11-172">인증 분석가가 평가하는 동안 분할 기술의 유효성을 검사하고 사용 중의 모든 분할 기술의 유효성을 검사하기 위한 테스트를 포함해야 하는 침투 테스트 보고서를 검토합니다.</span><span class="sxs-lookup"><span data-stu-id="e3a11-172">Certification analysts will validate segmentation techniques during the assessment along with reviewing penetration testing reports which should have included testing to validate the effectiveness of any segmentation techniques in use.</span></span>

### <a name="infrastructure-as-a-service-iaas-platform-as-a-service-paas-and-software-as-a-service-saas"></a><span data-ttu-id="e3a11-173">IaaS(Infrastructure as a Service), PaaS(Platform as a Service) 및 SaaS(Software as a Service)</span><span class="sxs-lookup"><span data-stu-id="e3a11-173">Infrastructure as a Service (IaaS), Platform as a Service (PaaS) and Software as a Service (SaaS)</span></span> 
<span data-ttu-id="e3a11-174">IaaS 및/또는 PaaS가 검토에 따라 응용 프로그램 또는 추가 기능 코드 배달의 인프라를 지원하는 데 사용되는 경우 클라우드 플랫폼 공급자는 인증 프로세스 전체에서 평가되는 일부 보안 컨트롤을 담당합니다.</span><span class="sxs-lookup"><span data-stu-id="e3a11-174">Where IaaS and/or PaaS is used to support the infrastructure of the application or add-in code delivery under review, the Cloud platform provider will be responsible for some of the security controls assessed throughout the certification process.</span></span> <span data-ttu-id="e3a11-175">따라서 [PCI DSS](bookmark://pci-dss)   준수 증명(AOC), ISO27001 또는 [SOC 2](bookmark://soc-2)유형 II 보고서와 같은 외부 규정 준수 보고서를 통해 클라우드 플랫폼 공급자가 보안 모범 사례에 대한 독립적인 외부 확인을 통해 인증 분석가를 제공해야   합니다.</span><span class="sxs-lookup"><span data-stu-id="e3a11-175">Therefore, certification analysts will need to be provided with independent external verification of security best practices by the Cloud platform provider through external compliance reports such as [PCI DSS](bookmark://pci-dss) Attestation of Compliance (AOC), ISO27001 or [SOC 2](bookmark://soc-2) Type II reports.</span></span> 

<span data-ttu-id="e3a11-176">부록 F는 다음 배포 유형 및 앱/추가 기능에서 M365 데이터를 유출하는지 여부에 따라 적용 가능한 보안 컨트롤에 대한 세부 정보를 제공합니다.</span><span class="sxs-lookup"><span data-stu-id="e3a11-176">Appendix F provides details of what security controls will likely be applicable based on the following deployment types and based upon whether the app/add-in exfiltrates M365 data or not:</span></span> 
* <span data-ttu-id="e3a11-177">ISV Hosted</span><span class="sxs-lookup"><span data-stu-id="e3a11-177">ISV Hosted</span></span> 
* <span data-ttu-id="e3a11-178">IaaS 호스트</span><span class="sxs-lookup"><span data-stu-id="e3a11-178">IaaS Hosted</span></span> 
* <span data-ttu-id="e3a11-179">PaaS/Serverless Hosted</span><span class="sxs-lookup"><span data-stu-id="e3a11-179">PaaS/Serverless Hosted</span></span> 
* <span data-ttu-id="e3a11-180">하이브리드 호스트</span><span class="sxs-lookup"><span data-stu-id="e3a11-180">Hybrid Hosted</span></span> 
* <span data-ttu-id="e3a11-181">공유 호스트</span><span class="sxs-lookup"><span data-stu-id="e3a11-181">Shared Hosted</span></span> 

<span data-ttu-id="e3a11-182">IaaS 또는 PaaS가 배포되는 경우 이러한 배포 유형 내에서 호스팅되는 환경의 증거를 제공해야 합니다.</span><span class="sxs-lookup"><span data-stu-id="e3a11-182">Where IaaS or PaaS is deployed, you will need to provide evidence of the environment being hosted within these deployment types.</span></span>

### <a name="sampling"></a><span data-ttu-id="e3a11-183">샘플링</span><span class="sxs-lookup"><span data-stu-id="e3a11-183">Sampling</span></span>

<span data-ttu-id="e3a11-184">인증 평가 지원에 대한 증거 요청은 다양한 운영 체제, 장치의 기본 기능 및 다양한 장치 유형을 고려하여 범위 내 시스템 구성 요소의 샘플을 기반으로 해야 합니다.</span><span class="sxs-lookup"><span data-stu-id="e3a11-184">Requests for evidence in support of the certification assessment should be based on a sample of the in-scope system components in consideration of different operating systems, primary function of the device, and different device types.</span></span> <span data-ttu-id="e3a11-185">인증 프로세스가 시작될 때 적합한 샘플이 선택됩니다.</span><span class="sxs-lookup"><span data-stu-id="e3a11-185">A suitable sample will be selected at the start of the certification process.</span></span> <span data-ttu-id="e3a11-186">다음 표는 샘플 크기가 어떻게 될 수 있는가에 대한 지침으로 사용해야 합니다.</span><span class="sxs-lookup"><span data-stu-id="e3a11-186">The following table should be used as a guide on what the sample size may be:</span></span>

|<span data-ttu-id="e3a11-187">인구 크기</span><span class="sxs-lookup"><span data-stu-id="e3a11-187">Population Size</span></span>              | <span data-ttu-id="e3a11-188">샘플</span><span class="sxs-lookup"><span data-stu-id="e3a11-188">Sample</span></span>                  |
|---------------------------- |-------------------------|
|<span data-ttu-id="e3a11-189"><5</span><span class="sxs-lookup"><span data-stu-id="e3a11-189"><5</span></span>|<span data-ttu-id="e3a11-190">1</span><span class="sxs-lookup"><span data-stu-id="e3a11-190">1</span></span>|
|<span data-ttu-id="e3a11-191">>5 & <10</span><span class="sxs-lookup"><span data-stu-id="e3a11-191">>5 & <10</span></span>|<span data-ttu-id="e3a11-192">2</span><span class="sxs-lookup"><span data-stu-id="e3a11-192">2</span></span>|
|<span data-ttu-id="e3a11-193">>9 & <25</span><span class="sxs-lookup"><span data-stu-id="e3a11-193">>9 & <25</span></span>|<span data-ttu-id="e3a11-194">3</span><span class="sxs-lookup"><span data-stu-id="e3a11-194">3</span></span>|
|<span data-ttu-id="e3a11-195">>24</span><span class="sxs-lookup"><span data-stu-id="e3a11-195">>24</span></span>|<span data-ttu-id="e3a11-196">4 </span><span class="sxs-lookup"><span data-stu-id="e3a11-196">4</span></span>|

> [!NOTE]
><span data-ttu-id="e3a11-197">초기 샘플에 포함된 장치 간에 불일치가 식별되면 평가 중에 샘플 크기가 증가할 수 있습니다.</span><span class="sxs-lookup"><span data-stu-id="e3a11-197">If discrepancies are identified between devices included within the initial sample, the sample size may be increased during the assessment.</span></span> 

## <a name="certification-process"></a><span data-ttu-id="e3a11-198">인증 프로세스</span><span class="sxs-lookup"><span data-stu-id="e3a11-198">Certification Process</span></span>

<span data-ttu-id="e3a11-199">인증 프로세스를 시작하기 전에 Publisher 증명을 성공적으로 시작하거나 완료해야 합니다.</span><span class="sxs-lookup"><span data-stu-id="e3a11-199">Before starting the certification process, you would need to have successfully started or completed your Publisher Attestation.</span></span> <span data-ttu-id="e3a11-200">증명 응답은 Microsoft 365 인증 프로세스를 지원하는 데 사용하며 다음과 같이 진행됩니다.</span><span class="sxs-lookup"><span data-stu-id="e3a11-200">Your attestation responses will be used in support of the Microsoft 365 Certification process and proceeds as follows:</span></span> 

1. <span data-ttu-id="e3a11-201">현재 환경과 일치하도록 게시자 설명 설명서를 검토합니다.</span><span class="sxs-lookup"><span data-stu-id="e3a11-201">Review your Publisher Attestation documentation to ensure alignment with your current environment</span></span> 
2. <span data-ttu-id="e3a11-202">전자 메일을 통해 Microsoft 365 인증 진행 요청 <AppCert@microsoft.com></span><span class="sxs-lookup"><span data-stu-id="e3a11-202">Request to progress to the Microsoft 365 Certification by emailing <AppCert@microsoft.com></span></span> 
3. <span data-ttu-id="e3a11-203">인증 분석가가 Microsoft 365 인증 프로세스를 시작하기 전에 대화 상자를 열게 됩니다.</span><span class="sxs-lookup"><span data-stu-id="e3a11-203">Certification analysts will open a dialogue before starting the Microsoft 365 Certification process</span></span>   
4. <span data-ttu-id="e3a11-204">초기 문서 [제출 제출](#initial-document-submission)</span><span class="sxs-lookup"><span data-stu-id="e3a11-204">Submit your [Initial Document Submission](#initial-document-submission)</span></span>
5. <span data-ttu-id="e3a11-205">인증 분석가가 Microsoft 365 인증 프로세스를 공식적으로 시작하는 증거가 필요한 컨트롤 목록을 제공합니다.</span><span class="sxs-lookup"><span data-stu-id="e3a11-205">Certification analyst will provide a listing of controls for which evidence is required, which formally starts the Microsoft 365 Certification process</span></span>
6. <span data-ttu-id="e3a11-206">Microsoft 365 인증을 완료하기 위해 60일 이내에 모든 범위 내 Microsoft 365 인증 컨트롤이 충족된 것 입증하는 증거 제출</span><span class="sxs-lookup"><span data-stu-id="e3a11-206">Submit evidence that demonstrates that all in-scope Microsoft 365 Certification controls have been met within a 60-day window to complete Microsoft 365 Certification</span></span> 

> [!IMPORTANT]
> <span data-ttu-id="e3a11-207">**제출 시간 프레임:** 제시간에 증거 요청에 응답할 수 있는 경우 평균적으로 평가 프로세스는 15일이 걸릴 것으로 예상됩니다.</span><span class="sxs-lookup"><span data-stu-id="e3a11-207">**Submission time frame:** It is anticipated that on average the assessment process should take 15 days, provided you are able to respond to evidence requests within a timely manner.</span></span> <span data-ttu-id="e3a11-208">이 인증 제출 가이드를 읽고 해당 가이드 내에서 설정된 컨트롤을 충족할 수 있으며 인증 프로세스를 시작하기 전에 충분한 증거를 제공할 수 있도록 하는 것이 좋습니다.</span><span class="sxs-lookup"><span data-stu-id="e3a11-208">Microsoft recommends that you ensure this certification submission guide has been read and be confident that you can meet the controls set out within it, and you can provide enough evidence before starting the certification process.</span></span> <span data-ttu-id="e3a11-209">인증 프로세스를 시작하면 평가를 최대 60일까지 완료할 수 있습니다. 그렇지 않으면 이미 수집된 증거가 부실해집니다.</span><span class="sxs-lookup"><span data-stu-id="e3a11-209">Upon starting the certification process, a maximum of 60 days is permitted to complete the assessment, otherwise evidence already collected becomes stale.</span></span> <span data-ttu-id="e3a11-210">60일 기간이 지난 후 성공적인 평가에 도달하지 못하면 제출에 실패가 발생하고 프로세스가 다시 시작되어야 합니다.</span><span class="sxs-lookup"><span data-stu-id="e3a11-210">If, after the 60-day time-period, a successful assessment is not reached, the submission will be issued a fail and the process must start again.</span></span> <span data-ttu-id="e3a11-211">Microsoft 365 인증 사양을 충족하지 못하거나 60일의 기간에 도달하고 충분한 증거가 제공되지 않은 경우 실패 결과가 Microsoft에서 공개되지 않습니다.</span><span class="sxs-lookup"><span data-stu-id="e3a11-211">If a fail is issued due to failing to meet the Microsoft 365 Certification Specification or because the 60-day time-period is reached and enough evidence is not provided, failing results will not be made public by Microsoft.</span></span> 

## <a name="compliance-evidence"></a><span data-ttu-id="e3a11-212">준수 증거</span><span class="sxs-lookup"><span data-stu-id="e3a11-212">Compliance Evidence</span></span>

<span data-ttu-id="e3a11-213">필수는 아니며, 현재 다른 외부 보안 프레임워크를 준수하는 경우 이러한 인증을 사용하여 Microsoft 365 인증 컨트롤 중 일부를 충족할 수 있습니다.</span><span class="sxs-lookup"><span data-stu-id="e3a11-213">Although it is not required, if you are currently in compliance with other external security frameworks, you can elect to use these certifications to satisfy some of the Microsoft 365 Certification controls.</span></span> <span data-ttu-id="e3a11-214">인증 분석가는 지원되는 모든 외부 보안 프레임워크의 범위 및 보안 제어 범위를 검토하여 Microsoft 365 인증 평가에서 제외할 수 있는 컨트롤을 결정하며, Microsoft 365 인증 평가를 위한 범위 내 환경이 외부 보안 프레임워크의 범위를 제공합니다.</span><span class="sxs-lookup"><span data-stu-id="e3a11-214">Certification analysts will review the scope and security control coverage of any supported external security frameworks to determine which controls can be excluded from the Microsoft 365 Certification assessment, providing the scope of the external security frameworks include the in-scope environments for the Microsoft 365 Certification assessment.</span></span> 

<span data-ttu-id="e3a11-215">인증 분석가가 기존 외부 보안 프레임워크를 Microsoft 365 인증 사양에 맞추려고 합니다.</span><span class="sxs-lookup"><span data-stu-id="e3a11-215">Certification analysts will try to align existing external security frameworks to the Microsoft 365 Certification specification.</span></span> <span data-ttu-id="e3a11-216">그러나 지원 문서가 외부 보안 프레임워크 감사/평가의 일부로 Microsoft 365 인증 컨트롤이 평가된다는 보장을 제공할 수 없는 경우 해당 컨트롤이 적용되고 있는 추가 증거를 제공해야 합니다.</span><span class="sxs-lookup"><span data-stu-id="e3a11-216">However, if supporting documentation is unable to provide assurance that Microsoft 365 Certification controls were assessed as part of the external security frameworks audit/assessment you will need to provide additional evidence of the said controls being in place.</span></span> 

<span data-ttu-id="e3a11-217">현재 Microsoft 365 인증 평가를 지원하는 데 사용할 수 있는 외부 보안 프레임워크는 다음과 같습니다.</span><span class="sxs-lookup"><span data-stu-id="e3a11-217">Currently, the external security frameworks that can be used in support of the Microsoft 365 Certification assessment include:</span></span>

*  <span data-ttu-id="e3a11-218">[ISMS](#isms) / [IEC](#iec) - IS0/IEC 27001 사양</span><span class="sxs-lookup"><span data-stu-id="e3a11-218">[ISMS](#isms)/[IEC](#iec) - IS0/IEC 27001 specification</span></span> 
*  [<span data-ttu-id="e3a11-219">PCI DSS</span><span class="sxs-lookup"><span data-stu-id="e3a11-219">PCI DSS</span></span>](#pci-dss)
*  [<span data-ttu-id="e3a11-220">SOC 2</span><span class="sxs-lookup"><span data-stu-id="e3a11-220">SOC 2</span></span>](#soc-2)

<span data-ttu-id="e3a11-221">설명서는 Microsoft 365 인증의 범위 내 환경이 이러한 외부 보안 프레임워크의 범위 내에 포함되어 있는 것을 적절하게 증명해야 합니다.</span><span class="sxs-lookup"><span data-stu-id="e3a11-221">Documentation must adequately demonstrate that the in-scope environment for the Microsoft 365 Certification was included within the scope of these external security frameworks.</span></span> <span data-ttu-id="e3a11-222">이러한 보안 프레임워크의 유효성 검사는 외부 타사에서 수행한 유효한 인증의 증거를 수락하여 이행됩니다.</span><span class="sxs-lookup"><span data-stu-id="e3a11-222">Validation of these security frameworks will be fulfilled by accepting evidence of valid certifications conducted by reputable external third-party companies.</span></span> <span data-ttu-id="e3a11-223">이러한 명명된 회사는 관련 규정 준수 프로그램에 대한 국제 인증 기관의 구성원이 되어야 합니다.</span><span class="sxs-lookup"><span data-stu-id="e3a11-223">These reputable companies must be members of international accreditation bodies for relevant compliance programs.</span></span><span data-ttu-id="e3a11-224">PCI DSS에 대한 [ISO](https://www.iso.org/certification.html) 27001 및 QSA(적격 보안 평가자)에 대한 ISO 인증 및 적합성 표준을 참조합니다. [](https://www.pcisecuritystandards.org/assessors_and_solutions/qualified_security_assessors)</span><span class="sxs-lookup"><span data-stu-id="e3a11-224"> See [ISO Certification and Conformity Standards](https://www.iso.org/certification.html) for ISO 27001 and [Qualified Security Assessors](https://www.pcisecuritystandards.org/assessors_and_solutions/qualified_security_assessors) (QSA) for PCI DSS.</span></span> 

<span data-ttu-id="e3a11-225">다음 표에서는 이 유효성 검사 프로세스의 일부로 인증 분석가가 요구하는 설명서를 강조합니다.</span><span class="sxs-lookup"><span data-stu-id="e3a11-225">The following table highlights documentation required by certification analysts as part of this validation process:</span></span>

| <span data-ttu-id="e3a11-226">**Standard**</span><span class="sxs-lookup"><span data-stu-id="e3a11-226">**Standard**</span></span> | <span data-ttu-id="e3a11-227">**요구 사항**</span><span class="sxs-lookup"><span data-stu-id="e3a11-227">**Requirements**</span></span> |
| ----- | ----- |
| <span data-ttu-id="e3a11-228">**[ISO 27001](#iso-27001)**</span><span class="sxs-lookup"><span data-stu-id="e3a11-228">**[ISO 27001](#iso-27001)**</span></span> | <span data-ttu-id="e3a11-229">공개적인 SOA(적용성 명세서) 버전과 발급된 ISO 27001 인증서 복사본이 필요합니다. </span><span class="sxs-lookup"><span data-stu-id="e3a11-229">A public facing version of the **Statement of Applicability** (SOA) and a copy of the ISO 27001 certificate issued will be required.</span></span>  <span data-ttu-id="e3a11-230">SOA는 114개 정보 보안 컨트롤 각각에 대한 위치를 요약하여 ISO 27001 인증서에 자세히 설명되지 않은 컨트롤을 제외하는지 식별하는 데 사용됩니다.</span><span class="sxs-lookup"><span data-stu-id="e3a11-230">The SOA summarizes your position on each of the 114 information security controls and  will be used to identify if any exclusion of controls that are not satisfactorily detailed in the ISO 27001 certificate.</span></span> <span data-ttu-id="e3a11-231">SOA의 공개 버전을 검토하여 이를 확인할 수 없는 경우, ISO 27001을 사용하여 일부 Microsoft 365 인증 사양 컨트롤의 유효성을 검사하는 경우 분석가가 전체 SOA에 액세스해야 할 수 있습니다.</span><span class="sxs-lookup"><span data-stu-id="e3a11-231">If this can't be determined by reviewing the public facing version of the SOA, the analyst might need access to the full SOA if ISO 27001 will be used to validate some of the Microsoft 365 Certification Specification controls.</span></span>  <span data-ttu-id="e3a11-232">분석가는 ISO 27001 평가 활동의 범위 유효성을 검사하는 것 외에도 위에서 설명한 대로 감사 회사의 유효성을 확인할 수 있습니다.</span><span class="sxs-lookup"><span data-stu-id="e3a11-232">In addition to validating the scope of the ISO 27001 assessment activities, the analysts will also confirm the validity of the audit company as described above.</span></span>|
|<span data-ttu-id="e3a11-233">**[PCI DSS](#pci-dss)**</span><span class="sxs-lookup"><span data-stu-id="e3a11-233">**[PCI DSS](#pci-dss)**</span></span>| <span data-ttu-id="e3a11-234">범위 내 응용 프로그램 및 시스템 구성 요소를 명확하게 식별하는 유효한 AOC(수준 **1** 준수) 문서가 제공되어야 합니다.</span><span class="sxs-lookup"><span data-stu-id="e3a11-234">A valid **Level 1 Attestation of Compliance** (AOC) document must be provided clearly identifying the in-scope application and system components.</span></span>  <span data-ttu-id="e3a11-235">자체 평가 **AOC는 모임 보안** 모범 사례의 증거로 받아들여지지 않습니다.</span><span class="sxs-lookup"><span data-stu-id="e3a11-235">A self-assessment AOC **will not** be accepted as evidence of meeting security best practices.</span></span> <span data-ttu-id="e3a11-236">AOC는 PCI DSS 평가의 일부로 평가되고 확인된 Microsoft 365 인증 사양 컨트롤을 확인하는 데 사용됩니다.</span><span class="sxs-lookup"><span data-stu-id="e3a11-236">The AOC will be used to determine which of the Microsoft 365 Certification Specification controls have been evaluated and confirmed as part of the PCI DSS assessment.</span></span>|
|<span data-ttu-id="e3a11-237">**[SOC 2](#soc-2)**</span><span class="sxs-lookup"><span data-stu-id="e3a11-237">**[SOC 2](#soc-2)**</span></span>|<span data-ttu-id="e3a11-238">**SOC 2(유형 I** 또는 II 유형) 보고서는 이 Microsoft 365 인증 사양 내의 평가 컨트롤을 준수하는 증거로 사용하려면 현재(지난 15개월 이내에 발급하고 지난 27개월 내에 시작된 선언된 기간)되어야 합니다.</span><span class="sxs-lookup"><span data-stu-id="e3a11-238">The **SOC 2 (Type I or Type II)** report must be current (issued within the last 15 months and the declared time period started within the last 27 months) to be used as evidence of conformity with any of the assessment controls within this Microsoft 365 Certification Specification.</span></span>|


## <a name="microsoft-365-certification"></a><span data-ttu-id="e3a11-239">Microsoft 365 인증</span><span class="sxs-lookup"><span data-stu-id="e3a11-239">Microsoft 365 Certification</span></span>

<span data-ttu-id="e3a11-240">지원되는 외부 보안 프레임워크는 Microsoft 365 인증 컨트롤 중 일부를 모임의 증거로 사용할 수 있습니다.</span><span class="sxs-lookup"><span data-stu-id="e3a11-240">Supported external security frameworks can be used as evidence of meeting some of the Microsoft 365 Certification controls.</span></span> <span data-ttu-id="e3a11-241">외부 보안 프레임워크를 고려하기 전에 인증 분석가가 위에 제출된 설명서를 사용하여 외부 보안 프레임워크의 범위 및 보안 제어 범위를 검토합니다.</span><span class="sxs-lookup"><span data-stu-id="e3a11-241">Before external security frameworks can be considered, certification analysts will review the scope and security control coverage of the external security framework using the documentation submitted above.</span></span> 

<span data-ttu-id="e3a11-242">다음 부록을 사용하여 외부 보안 프레임워크와 Microsoft 365 인증 사양 간의 잠재적인 간격이 존재하는 위치를 식별할 수 있습니다.</span><span class="sxs-lookup"><span data-stu-id="e3a11-242">The following appendixes can be used to identify where potential gaps between the external security framework and the Microsoft 365 Certification specification exist as follows:</span></span> 

|<span data-ttu-id="e3a11-243">**프레임워크**</span><span class="sxs-lookup"><span data-stu-id="e3a11-243">**Framework**</span></span> | <span data-ttu-id="e3a11-244">**추가 고려 사항**</span><span class="sxs-lookup"><span data-stu-id="e3a11-244">**Additional considerations**</span></span> |
|-------------- | --------------------|
|<span data-ttu-id="e3a11-245">ISO 27001</span><span class="sxs-lookup"><span data-stu-id="e3a11-245">ISO 27001</span></span>| <span data-ttu-id="e3a11-246">[**부록 C:**](#appendix-c)Evidence Collection – ISO 27001의 델타</span><span class="sxs-lookup"><span data-stu-id="e3a11-246">[**Appendix C**](#appendix-c): Evidence Collection – Deltas for ISO 27001.</span></span>|
|<span data-ttu-id="e3a11-247">PCI DSS</span><span class="sxs-lookup"><span data-stu-id="e3a11-247">PCI DSS</span></span> | <span data-ttu-id="e3a11-248">[**부록 D:**](#appendix-d)증거 컬렉션 - PCI DSS용 델타.</span><span class="sxs-lookup"><span data-stu-id="e3a11-248">[**Appendix D**](#appendix-d): Evidence Collection – Deltas for PCI DSS.</span></span>|
|<span data-ttu-id="e3a11-249">SOC 2</span><span class="sxs-lookup"><span data-stu-id="e3a11-249">SOC 2</span></span>| <span data-ttu-id="e3a11-250">[**부록 E**](#appendix-e): 증거 컬렉션 - SOC 2의 델타</span><span class="sxs-lookup"><span data-stu-id="e3a11-250">[**Appendix E**](#appendix-e): Evidence Collection – Deltas for SOC 2.</span></span>|

> [!NOTE]
> <span data-ttu-id="e3a11-251">위에서 언급한 외부 보안 표준/프레임워크는 일부 Microsoft 365 인증 컨트롤을 충족하기 위한 증거로 제출할 수 있습니다. 그러나 Microsoft 365 인증을 통과하는 것은 해당 표준/프레임워크에 대한 감사를 성공적으로 통과하는 것은 아니며,</span><span class="sxs-lookup"><span data-stu-id="e3a11-251">Although the above-mentioned external security standards/frameworks can be submitted as evidence to meet some of the Microsoft 365 Certification controls, passing the Microsoft 365 Certification doesn't mean that you will successfully pass an audit against those standards/frameworks.</span></span> <span data-ttu-id="e3a11-252">Microsoft 365 인증 사양은 해당 보안 표준/프레임워크 중 일부에 불과하기만 하여 Microsoft가 보안국을 참조하여 보증 수준을 얻을 수 있도록 합니다.</span><span class="sxs-lookup"><span data-stu-id="e3a11-252">The Microsoft 365 Certification Specification is only a small subset of those security standards/frameworks that allows Microsoft to gain a level of assurance in reference to your security posture.</span></span>

## <a name="initial-document-submission"></a><span data-ttu-id="e3a11-253">초기 문서 제출</span><span class="sxs-lookup"><span data-stu-id="e3a11-253">Initial document submission</span></span>

<span data-ttu-id="e3a11-254">초기 문서 제출은 인증 분석가가 범위를 지정하고 평가 범위에 포함되는 대상을 결정하는 데 도움이 됩니다.</span><span class="sxs-lookup"><span data-stu-id="e3a11-254">The initial document submission will help certification analysts perform scoping and determine what will be in scope for your assessment.</span></span> <span data-ttu-id="e3a11-255">그 이후에는 평가를 수행하기 위해 사용되는 지원 설명서 및 증거를 제출해야 합니다.</span><span class="sxs-lookup"><span data-stu-id="e3a11-255">After which you will be required to submit supporting documentation and evidence used to carry out the assessment.</span></span> <span data-ttu-id="e3a11-256">초기 제출에는 아래에 지정된 정보가 포함되어야 합니다.</span><span class="sxs-lookup"><span data-stu-id="e3a11-256">Your initial submission must include the information specified below:</span></span>

| <span data-ttu-id="e3a11-257">**설명서 &nbsp; 개요**</span><span class="sxs-lookup"><span data-stu-id="e3a11-257">**Documentation&nbsp;Overview**</span></span>     |   <span data-ttu-id="e3a11-258">**설명서 세부 정보**</span><span class="sxs-lookup"><span data-stu-id="e3a11-258">**Documentation Details**</span></span>  |
| -------------------------| -----------------------------|
|<span data-ttu-id="e3a11-259">**앱/추가 기능 설명**</span><span class="sxs-lookup"><span data-stu-id="e3a11-259">**App/Add-in Description**</span></span> | <span data-ttu-id="e3a11-260">앱/추가 기능의 목적 및 기능에 대한 설명입니다.</span><span class="sxs-lookup"><span data-stu-id="e3a11-260">A description of the app/add-in’s purpose and functionality.</span></span> <span data-ttu-id="e3a11-261">이를 통해 인증 분석가가 앱/추가 기능의 작동 방식과 용도를 잘 이해해야 합니다.</span><span class="sxs-lookup"><span data-stu-id="e3a11-261">This should provide the certification analyst with a good understanding of how the app/add-in functions and what it is intended use is</span></span>
|<span data-ttu-id="e3a11-262">**침투 테스트 보고서**</span><span class="sxs-lookup"><span data-stu-id="e3a11-262">**Penetration Testing Report**</span></span> |<span data-ttu-id="e3a11-263">지난 12개월 내에 완료된 침투 테스트 보고서입니다.</span><span class="sxs-lookup"><span data-stu-id="e3a11-263">A penetration testing report completed within the last 12 months.</span></span> <span data-ttu-id="e3a11-264">이 보고서에는 앱/추가 기능의 작동을 지원하는 추가 환경과 함께 앱/추가 배포를 지원하는 환경이 포함되어야 합니다.</span><span class="sxs-lookup"><span data-stu-id="e3a11-264">This report must include the environment that supports the deployment of the app/add along with any additional environment that supports the operation of the app/add-in.</span></span> <span data-ttu-id="e3a11-265">**참고:** 연간 침투 테스트를 수행하지 않는 경우 인증 프로세스를 통해 수행하게 할 수 있습니다.</span><span class="sxs-lookup"><span data-stu-id="e3a11-265">**Note:** if you do not do annual penetration testing, you can elect to have them done through the certification process.</span></span>|
|<span data-ttu-id="e3a11-266">**아키텍처 다이어그램**</span><span class="sxs-lookup"><span data-stu-id="e3a11-266">**Architecture diagrams**</span></span>|<span data-ttu-id="e3a11-267">앱/추가 기능의 지원 인프라에 대한 개략적인 개요를 나타내는 논리 아키텍처 다이어그램입니다.</span><span class="sxs-lookup"><span data-stu-id="e3a11-267">A logical architecture diagram representing a high-level overview of your app's / add-in’s supporting infrastructure.</span></span> <span data-ttu-id="e3a11-268">여기에는 모든 호스팅 **환경과** 앱/추가 기능을 지원하는 지원 인프라가 포함되어야 합니다.</span><span class="sxs-lookup"><span data-stu-id="e3a11-268">This must include **all** hosting environments and supporting infrastructure supporting the app/add-in.</span></span> <span data-ttu-id="e3a11-269">이 다이어그램은 인증 분석가가 범위 내의 시스템을 이해하고 샘플링을 결정하는 데 도움이 될 수 있도록 환경 내의 모든 지원 시스템 구성 요소를 표시해야 합니다.</span><span class="sxs-lookup"><span data-stu-id="e3a11-269">This diagram MUST depict all the different supporting system components within the environment to help certification analysts understand systems in scope and help to determine sampling.</span></span> <span data-ttu-id="e3a11-270">또한 사용되는 호스팅 환경 유형을 표시하십시오. ISV Hosted, IaaS, PaaS 또는 Hybrid.</span><span class="sxs-lookup"><span data-stu-id="e3a11-270">Please also indicate what hosting environment type is used; ISV Hosted, IaaS, PaaS, or Hybrid.</span></span> <span data-ttu-id="e3a11-271">**참고:** SaaS가 사용되는 경우 환경 내에서 지원 서비스를 제공하는 데 사용되는 다양한 SaaS 서비스를 표시하십시오.</span><span class="sxs-lookup"><span data-stu-id="e3a11-271">**Note:** Where SaaS is used, please indicate the various SaaS services that are used to provide the supporting services within the environment.</span></span>|
|<span data-ttu-id="e3a11-272">**공용 공간**</span><span class="sxs-lookup"><span data-stu-id="e3a11-272">**Public Footprint**</span></span> | <span data-ttu-id="e3a11-273">지원 **인프라에서** 사용하는 모든 공용 IP 주소 및 URL에 대한 세부 정보</span><span class="sxs-lookup"><span data-stu-id="e3a11-273">Detailing **all** public IP Addresses and URLs used by the supporting infrastructure.</span></span> <span data-ttu-id="e3a11-274">사용 범위를 분할하기 위해 적절한 분할을 구현하지 않는 한 환경에 할당된 라우팅 가능한 전체 IP 범위를 포함해야 합니다(적절한 분할 증거가 필요).</span><span class="sxs-lookup"><span data-stu-id="e3a11-274">This must include the full routable IP range allocated to the environment unless adequate segmentation has been implemented to split the range in use (adequate evidence of segmentation will be required)</span></span>|
|<span data-ttu-id="e3a11-275">**데이터 흐름 다이어그램**</span><span class="sxs-lookup"><span data-stu-id="e3a11-275">**Data flow diagrams**</span></span> |<span data-ttu-id="e3a11-276">다음을 자세히 설명하는 흐름 다이어그램</span><span class="sxs-lookup"><span data-stu-id="e3a11-276">Flow diagrams detailing the following:</span></span>
||<span data-ttu-id="e3a11-277">&#x2713; /추가 [기능(EUII](#euii) 및 [OII](#oii) 포함)과 M365 데이터 흐름을 제공합니다.</span><span class="sxs-lookup"><span data-stu-id="e3a11-277">&#x2713; M365 Data flows to and from the App / Add-in (including [EUII](#euii) and [OII](#oii) ).</span></span>|
||<span data-ttu-id="e3a11-278">&#x2713; 인프라 내에서 M365 데이터 흐름을 구성합니다(해당되는 경우).</span><span class="sxs-lookup"><span data-stu-id="e3a11-278">&#x2713; M365 Data flows within the supporting infrastructure(where applicable)</span></span>|
||<span data-ttu-id="e3a11-279">&#x2713; 데이터가 저장되는 위치 및 데이터, 외부 타사에 데이터가 전달되는 방법(타사에 대한 세부 정보 포함) 및 개방형/공용 네트워크 및 미사용 데이터를 통해 전송되는 동안 데이터가 보호되는 방법을 강조하는 다이어그램입니다.</span><span class="sxs-lookup"><span data-stu-id="e3a11-279">&#x2713; Diagrams highlighting where and what data is stored, how data is passed to external third parties(including details of what third parties) , and how data is protected in transit over open/public networks and at rest.</span></span>|
|<span data-ttu-id="e3a11-280">**API 끝점 세부 정보**</span><span class="sxs-lookup"><span data-stu-id="e3a11-280">**API Endpoint Details**</span></span>| <span data-ttu-id="e3a11-281">앱에서 사용하는 모든 API 끝점의 전체 목록입니다.</span><span class="sxs-lookup"><span data-stu-id="e3a11-281">A complete listing of all API Endpoints used by your app.</span></span> <span data-ttu-id="e3a11-282">환경 범위를 이해하기 위해 환경 내의 API 끝점 위치를 제공합니다.</span><span class="sxs-lookup"><span data-stu-id="e3a11-282">To help understand the environment scope, provide API endpoint locations within your environment.</span></span>                                
|<span data-ttu-id="e3a11-283">**Microsoft API 사용 권한**</span><span class="sxs-lookup"><span data-stu-id="e3a11-283">**Microsoft API Permissions**</span></span>| <span data-ttu-id="e3a11-284">앱/추가  기능이 작동하기 위해 요청되는 사용 권한과 함께 사용되는 모든 Microsoft API와 요청된 사용 권한에 대한 사의를 설명하는 설명서를 제공합니다.</span><span class="sxs-lookup"><span data-stu-id="e3a11-284">Provide documentation detailing **ALL** the Microsoft APIs that are used along with what permissions are being requested for the app/add-in to function along with a justification for the requested permissions</span></span>|
|<span data-ttu-id="e3a11-285">**데이터 저장소 유형**</span><span class="sxs-lookup"><span data-stu-id="e3a11-285">**Data storage types**</span></span> |<span data-ttu-id="e3a11-286">설명하는 문서 저장 및 처리:</span><span class="sxs-lookup"><span data-stu-id="e3a11-286">Data storage and handling documents describing:</span></span>|
||<span data-ttu-id="e3a11-287">&#x2713; M365 데이터 EUII 및 [OII가](#euii) 수신 및 저장되는 범위 [](#oii)</span><span class="sxs-lookup"><span data-stu-id="e3a11-287">&#x2713; To what extent is your customers M365 Data [EUII](#euii) and [OII](#oii) is being received and stored</span></span>|
||<span data-ttu-id="e3a11-288">&#x2713; 보존 기간입니다.</span><span class="sxs-lookup"><span data-stu-id="e3a11-288">&#x2713; The data retention period.</span></span>|
||<span data-ttu-id="e3a11-289">&#x2713; M365 데이터가 캡처되는 이유입니다.</span><span class="sxs-lookup"><span data-stu-id="e3a11-289">&#x2713; Why the customer M365 Data is being captured.</span></span>|
||<span data-ttu-id="e3a11-290">&#x2713; M365 데이터가 저장되는 위치입니다(위에서 제공한 데이터 흐름 다이어그램에 포함해야 합니다).</span><span class="sxs-lookup"><span data-stu-id="e3a11-290">&#x2713; Where customer M365 Data is stored (should be included within data flow diagrams supplied above).</span></span>|
|<span data-ttu-id="e3a11-291">**준수 확인**</span><span class="sxs-lookup"><span data-stu-id="e3a11-291">**Compliance confirmation**</span></span>|<span data-ttu-id="e3a11-292">게시자 증명 제출에 포함되거나 Microsoft 365 인증 컨트롤을 검토할 때 고려할 외부 보안 프레임워크에 대한 설명서 지원</span><span class="sxs-lookup"><span data-stu-id="e3a11-292">Supporting documentation for external security frameworks included within the Publisher Attestation submission or to be considered when reviewing Microsoft 365 Certification controls.</span></span> <span data-ttu-id="e3a11-293">현재 다음 세 가지가 지원됩니다.</span><span class="sxs-lookup"><span data-stu-id="e3a11-293">Currently, the following three are supported:</span></span>|
||<span data-ttu-id="e3a11-294">&#x2713;(AOC)의 [PCI DSS](#pci-dss) Attestation of Compliance(AOC)</span><span class="sxs-lookup"><span data-stu-id="e3a11-294">&#x2713; [PCI DSS](#pci-dss) Attestation of Compliance (AOC).</span></span>|
||<span data-ttu-id="e3a11-295">&#x2713; [SOC 2](#soc-2) 유형 I/유형 II 보고서입니다.</span><span class="sxs-lookup"><span data-stu-id="e3a11-295">&#x2713; [SOC 2](#soc-2) Type I/Type II reports.</span></span>|
||<span data-ttu-id="e3a11-296">&#x2713; [](#isms)  /  [ISMS IEC](#iec) - 1S0/IEC 27001 SoA(적용성 정책) 및 인증.</span><span class="sxs-lookup"><span data-stu-id="e3a11-296">&#x2713; [ISMS](#isms) / [IEC](#iec) - 1S0/IEC 27001 Statement of Applicability (SoA) and Certification.</span></span>|
|<span data-ttu-id="e3a11-297">**웹 종속성**</span><span class="sxs-lookup"><span data-stu-id="e3a11-297">**Web Dependencies**</span></span>|<span data-ttu-id="e3a11-298">현재 실행 중인 버전에서 앱/추가 기능에서 사용하는 모든 종속성 목록을 표시하는 설명서입니다.</span><span class="sxs-lookup"><span data-stu-id="e3a11-298">Documentation listing all dependencies used by the app / add-in with the current running versions.</span></span>|
|<span data-ttu-id="e3a11-299">**소프트웨어 인벤토리**</span><span class="sxs-lookup"><span data-stu-id="e3a11-299">**Software Inventory**</span></span>|<span data-ttu-id="e3a11-300">범위 내 환경에서 사용되는 모든 소프트웨어와 버전이 포함된 최신 소프트웨어 인벤토리입니다.</span><span class="sxs-lookup"><span data-stu-id="e3a11-300">An up-to-date software inventory which includes all software used within the in-scope environment along with the versions.</span></span>|
|<span data-ttu-id="e3a11-301">**하드웨어 인벤토리**</span><span class="sxs-lookup"><span data-stu-id="e3a11-301">**Hardware Inventory**</span></span>| <span data-ttu-id="e3a11-302">지원 인프라에서 사용하는 최신 하드웨어 인벤토리입니다.</span><span class="sxs-lookup"><span data-stu-id="e3a11-302">An up-to-date hardware inventory used by the supporting infrastructure.</span></span> <span data-ttu-id="e3a11-303">평가 단계를 수행할 때 샘플링에 도움이 됩니다.</span><span class="sxs-lookup"><span data-stu-id="e3a11-303">This will be used to help with sampling when performing the assessment phase.</span></span> <span data-ttu-id="e3a11-304">환경에 PaaS가 포함되어 있는 경우 소비된 서비스에 대한 세부 정보를 제공합니다.</span><span class="sxs-lookup"><span data-stu-id="e3a11-304">If your environment includes PaaS provide details of services consumed.</span></span>|

## <a name="evidence-collection-and-assessment-activities"></a><span data-ttu-id="e3a11-305">증거 수집 및 평가 활동</span><span class="sxs-lookup"><span data-stu-id="e3a11-305">Evidence Collection and Assessment Activities</span></span>

<span data-ttu-id="e3a11-306">강력한 증거 수집 및 평가 활동을 통해 인증 분석가가 보안 상태를 평가하여 적절한 수준의 데이터 보안 보증을 획득하고 Microsoft 365 인증 사양 컨트롤을 준수할 수 있습니다.</span><span class="sxs-lookup"><span data-stu-id="e3a11-306">Through robust evidence collection and assessment activities, certification analysts will be able to assess your security posture to obtain an adequate level of data security assurance and adherence to the Microsoft 365 Certification Specification controls.</span></span> <span data-ttu-id="e3a11-307">인증 분석가는 다음과 같이 이를 달성합니다.</span><span class="sxs-lookup"><span data-stu-id="e3a11-307">Certification analysts will achieve this as follows:</span></span> 

<span data-ttu-id="e3a11-308">**Evidence 컬렉션**</span><span class="sxs-lookup"><span data-stu-id="e3a11-308">**Evidence Collection**</span></span>

* <span data-ttu-id="e3a11-309">위의 초기 설명서 제출 [섹션에서](#initial-document-submission) 강조 표시된 초기 설명서</span><span class="sxs-lookup"><span data-stu-id="e3a11-309">Initial documentation, highlighted within the [Initial Documentation Submission](#initial-document-submission) section above</span></span> 
* <span data-ttu-id="e3a11-310">정책 문서</span><span class="sxs-lookup"><span data-stu-id="e3a11-310">Policy documents</span></span> 
* <span data-ttu-id="e3a11-311">문서 처리</span><span class="sxs-lookup"><span data-stu-id="e3a11-311">Process documents</span></span> 
* <span data-ttu-id="e3a11-312">시스템 구성 설정</span><span class="sxs-lookup"><span data-stu-id="e3a11-312">System configuration settings</span></span> 
* <span data-ttu-id="e3a11-313">티켓 변경</span><span class="sxs-lookup"><span data-stu-id="e3a11-313">Change tickets</span></span> 
* <span data-ttu-id="e3a11-314">컨트롤 레코드 변경</span><span class="sxs-lookup"><span data-stu-id="e3a11-314">Change control records</span></span> 
* <span data-ttu-id="e3a11-315">시스템 보고서</span><span class="sxs-lookup"><span data-stu-id="e3a11-315">System reports</span></span>

<span data-ttu-id="e3a11-316">다양한 방법을 사용하여 평가 프로세스를 완료하는 데 필요한 증거를 수집합니다.</span><span class="sxs-lookup"><span data-stu-id="e3a11-316">Various methods will be used to collect the evidence necessary to complete the assessment process.</span></span>  <span data-ttu-id="e3a11-317">이 증거 컬렉션은 다음 형식일 수 있습니다.</span><span class="sxs-lookup"><span data-stu-id="e3a11-317">This evidence collection may be in the form of:</span></span> 
* <span data-ttu-id="e3a11-318">문서</span><span class="sxs-lookup"><span data-stu-id="e3a11-318">Documents</span></span> 
* <span data-ttu-id="e3a11-319">스크린샷</span><span class="sxs-lookup"><span data-stu-id="e3a11-319">Screenshots</span></span> 
* <span data-ttu-id="e3a11-320">인터뷰</span><span class="sxs-lookup"><span data-stu-id="e3a11-320">Interviews</span></span> 
* <span data-ttu-id="e3a11-321">화면 공유</span><span class="sxs-lookup"><span data-stu-id="e3a11-321">Screensharing</span></span> 

<span data-ttu-id="e3a11-322">사용되는 증거 수집 기술은 평가 프로세스 중에 결정됩니다.</span><span class="sxs-lookup"><span data-stu-id="e3a11-322">The evidence collection techniques used will be determined during the assessment process.</span></span> 

<span data-ttu-id="e3a11-323">**평가 활동**</span><span class="sxs-lookup"><span data-stu-id="e3a11-323">**Assessment Activities**</span></span>

<span data-ttu-id="e3a11-324">인증 분석가가 제공하는 증거를 검토하여 이 Microsoft 365 인증 사양 내에서 컨트롤을 적절하게 충족하는지 여부를 확인할 수 있습니다.</span><span class="sxs-lookup"><span data-stu-id="e3a11-324">Certification analysts will review evidence you provide to determine if you have adequately met controls within this Microsoft 365 Certification Specification.</span></span> 

<span data-ttu-id="e3a11-325">가능한 경우 및 평가를 완료하는 데 필요한 시간을 줄이기 위해 초기 [](#initial-document-submission)설명서 제출에 자세히 설명된 설명서의 전체 또는 전체를 미리   제공해야 합니다.</span><span class="sxs-lookup"><span data-stu-id="e3a11-325">Where possible and to reduce the amount of time required to complete the assessment, any or all of the documentation detailed in the [Initial Documentation Submission](#initial-document-submission) should be provided in advance.</span></span>

<span data-ttu-id="e3a11-326">인증 분석가는 먼저 초기 문서 제출에서 제공된 증거와 게시자 증명 정보를 검토하여 적절한 문의 라인, 샘플링 크기 및 위에 자세히 설명된 대로 추가 증거를 얻을 필요성을 식별합니다.</span><span class="sxs-lookup"><span data-stu-id="e3a11-326">Certification analysts will first review the evidence provided from the initial documentation submission and the Publisher Attestation information to identify appropriate lines of inquiry, sampling size, and the need for further evidence to be obtained as detailed above.</span></span>  <span data-ttu-id="e3a11-327">인증 분석가는 수집된 모든 정보를 분석하여 이 Microsoft 365 인증 사양 내에서 제어를 충족하는 방법과 경우와 그에 대한 결론을 내릴 것입니다.</span><span class="sxs-lookup"><span data-stu-id="e3a11-327">Certification analysts will analyze all information gathered to draw conclusions as to how and if you are meeting the controls within this Microsoft 365 Certification Specification.</span></span> 

## <a name="app-certification-criteria"></a><span data-ttu-id="e3a11-328">앱 인증 기준</span><span class="sxs-lookup"><span data-stu-id="e3a11-328">App Certification Criteria</span></span>

<span data-ttu-id="e3a11-329">앱, 지원 인프라 및 지원 설명서는 다음 보안 도메인에서 평가됩니다.</span><span class="sxs-lookup"><span data-stu-id="e3a11-329">Your app, supporting infrastructure, and supporting documentation will be assessed across the following security domains:</span></span>

1. [<span data-ttu-id="e3a11-330">**Application Security**</span><span class="sxs-lookup"><span data-stu-id="e3a11-330">**Application Security**</span></span>](#application-security)
1. [<span data-ttu-id="e3a11-331">**운영 보안/보안 배포**</span><span class="sxs-lookup"><span data-stu-id="e3a11-331">**Operational Security / Secure Deployment**</span></span>](#operational-security)
1. [<span data-ttu-id="e3a11-332">**데이터 처리 보안 및 개인 정보**</span><span class="sxs-lookup"><span data-stu-id="e3a11-332">**Data Handling Security and Privacy**</span></span>](#data-handling-security-and-privacy)
1. [<span data-ttu-id="e3a11-333">**선택적 외부 준수 프레임워크 검토**</span><span class="sxs-lookup"><span data-stu-id="e3a11-333">**Optional External Compliance Framework Review**</span></span>](#optional-external-compliance-frameworks-review)

<span data-ttu-id="e3a11-334">이러한 각 보안 도메인에는 평가 프로세스의 일부로 평가될 하나 이상의 특정 요구 사항을 아우를 수 있는 특정 키 컨트롤이 포함되어 있습니다.</span><span class="sxs-lookup"><span data-stu-id="e3a11-334">Each of these security domains include specific key controls encompassing one or more specific requirements that will be evaluated as part of the assessment process.</span></span> <span data-ttu-id="e3a11-335">Microsoft 365 인증이 모든 크기의 개발자에게 포함되도록 보장하기 위해 네 가지 보안 도메인은 점수 지정 시스템을 사용하여 각 도메인의 전체 점수를 평가합니다.</span><span class="sxs-lookup"><span data-stu-id="e3a11-335">To ensure that Microsoft 365 Certification is inclusive to developers of all sizes, each of the four security domains is assessed using a scoring system to determine an overall score from each of the domains.</span></span> <span data-ttu-id="e3a11-336">각 Microsoft 365 인증 컨트롤에 대한 점수는 이 컨트롤이 충족되지 않을 경우의 인식된 위험에 따라 1(낮음)과 3(높음) 사이에 할당됩니다.</span><span class="sxs-lookup"><span data-stu-id="e3a11-336">Scores for each of the Microsoft 365 Certification controls are allocated between 1 (low) and 3 (high) based upon the perceived risk of that control not being met.</span></span> <span data-ttu-id="e3a11-337">4개의 각 보안 도메인에는 통과로 표시될 최소 백분율 표시가 있습니다.</span><span class="sxs-lookup"><span data-stu-id="e3a11-337">Each of the four security domains will have a minimum percentage mark to be deemed a pass.</span></span> <span data-ttu-id="e3a11-338">이 사양의 특정 요소에는 몇 가지 자동 실패 조건이 포함됩니다.</span><span class="sxs-lookup"><span data-stu-id="e3a11-338">Certain elements of this specification include some automatic fail criteria:</span></span>

- <span data-ttu-id="e3a11-339">API 권한은 PoLP(최소 권한) 원칙을 따라야 합니다.</span><span class="sxs-lookup"><span data-stu-id="e3a11-339">API permissions not following the principle of least privilege (PoLP).</span></span>  
- <span data-ttu-id="e3a11-340">필요한 경우 침투 테스트 보고서가 없습니다.</span><span class="sxs-lookup"><span data-stu-id="e3a11-340">No penetration testing report when it is required.</span></span>
- <span data-ttu-id="e3a11-341">맬웨어 방지 방어 없음</span><span class="sxs-lookup"><span data-stu-id="e3a11-341">No anti-malware defenses</span></span>
- <span data-ttu-id="e3a11-342">관리 액세스를 보호하는 데 다단계 인증이 사용되지 않습니다.</span><span class="sxs-lookup"><span data-stu-id="e3a11-342">Multi-Factor authentication not being used to protect administrative access.</span></span>  
- <span data-ttu-id="e3a11-343">패치 프로세스가 없습니다.</span><span class="sxs-lookup"><span data-stu-id="e3a11-343">No patching processes.</span></span>  
- <span data-ttu-id="e3a11-344">적절한 [GDPR 개인 정보](#gdpr) 취급 방침이 없음</span><span class="sxs-lookup"><span data-stu-id="e3a11-344">No suitable [GDPR](#gdpr) privacy notice.</span></span>  

## <a name="application-security"></a><span data-ttu-id="e3a11-345">Application Security</span><span class="sxs-lookup"><span data-stu-id="e3a11-345">Application Security</span></span>

<span data-ttu-id="e3a11-346">응용 프로그램 보안 도메인은 다음 세 가지 영역에 초점을 맞추고 있습니다.</span><span class="sxs-lookup"><span data-stu-id="e3a11-346">The application security domain focuses upon the follow three areas:</span></span> 
* <span data-ttu-id="e3a11-347">GraphAPI 사용 권한 유효성 검사</span><span class="sxs-lookup"><span data-stu-id="e3a11-347">GraphAPI Permission Validation</span></span> 
* <span data-ttu-id="e3a11-348">외부 연결 검사</span><span class="sxs-lookup"><span data-stu-id="e3a11-348">External Connectivity Checks</span></span>
* <span data-ttu-id="e3a11-349">응용 프로그램 보안 테스트</span><span class="sxs-lookup"><span data-stu-id="e3a11-349">Application Security Testing</span></span> 

<span data-ttu-id="e3a11-350">**GraphAPI 사용 권한 유효성 검사**</span><span class="sxs-lookup"><span data-stu-id="e3a11-350">**GraphAPI Permission Validation**</span></span>

<span data-ttu-id="e3a11-351">GraphAPI 권한 유효성 검사는 앱/추가 기능에서 과도하게 허용되는 권한을 요청하지 않는지 검사하기 위해 수행됩니다.</span><span class="sxs-lookup"><span data-stu-id="e3a11-351">GraphAPI permission validation is carried out to validate the app/add-in does not request overly permissive permissions.</span></span> <span data-ttu-id="e3a11-352">요청된 사용 권한을 수동으로 확인하여 수행됩니다.</span><span class="sxs-lookup"><span data-stu-id="e3a11-352">This is carried out by manually checking what permissions are requested.</span></span> <span data-ttu-id="e3a11-353">인증 분석가가 게시자 증명 제출에 대해 이러한 검사를 교차 참조하고 요청되는 액세스 수준을 평가하여 '최소 권한' 관행이 충족되도록 합니다.</span><span class="sxs-lookup"><span data-stu-id="e3a11-353">Certification analysts will cross reference these checks against the Publisher Attestation submission and evaluate the level of access being requested to ensure ‘least privilege’ practices are being met.</span></span> <span data-ttu-id="e3a11-354">인증 분석가가 이러한 '최소 권한' 관행이 충족되지 않는 것으로 생각되는 경우 인증 분석가는 요청되는 사용 권한에 대한 비즈니스 사당성의 유효성을 검사하기 위해 공개적인 논의를 합니다.</span><span class="sxs-lookup"><span data-stu-id="e3a11-354">Where certification analysts believe these ‘least privilege’ practices are not being met, certification analysts will have an open discussion with you to validate the business justification for the permissions being requested.</span></span> <span data-ttu-id="e3a11-355">이 검토 중에 발견된 게시자에 대한 모든 불일치가 피드백을 얻게 되어 게시자에 대한 의거가 업데이트될 수 있습니다.</span><span class="sxs-lookup"><span data-stu-id="e3a11-355">Any discrepancies against your Publisher Attestation submission found during this review will also get feedback so your Publisher Attestation can be updated.</span></span> 

<span data-ttu-id="e3a11-356">**외부 연결 검사**</span><span class="sxs-lookup"><span data-stu-id="e3a11-356">**External Connectivity Checks**</span></span>

<span data-ttu-id="e3a11-357">평가의 일부로 분석가가 M365 외부의 연결을 식별하기 위해 응용 프로그램 기능을 쉽게 확인할 수 있습니다.</span><span class="sxs-lookup"><span data-stu-id="e3a11-357">As part of the assessment, an Analyst will perform a light walk through of the applications functionality to identify connections outside of M365.</span></span>  <span data-ttu-id="e3a11-358">Microsoft로 식별되지 않는 연결 또는 서비스에 대한 직접 연결은 플래그가 지정되고 평가 중에 논의됩니다.</span><span class="sxs-lookup"><span data-stu-id="e3a11-358">Any connections which are not identified as being Microsoft or direct connections to your service will be flagged and discussed during the assessment.</span></span>

<span data-ttu-id="e3a11-359">**응용 프로그램 보안 테스트**</span><span class="sxs-lookup"><span data-stu-id="e3a11-359">**Application Security Testing**</span></span>

<span data-ttu-id="e3a11-360">앱/추가 기능 및 지원 환경과 관련된 위험을 적절하게 검토하는 것은 앱/추가 기능의 보안에 대한 보증을 고객에게 제공하는 데 필수적입니다.</span><span class="sxs-lookup"><span data-stu-id="e3a11-360">An adequate review of the risks associated with your app/add-in and supporting environment is essential in providing customers with assurance in the security of the app/add-in.</span></span> <span data-ttu-id="e3a11-361">응용 프로그램이 Microsoft에서 게시하지 않은 서비스에 대한 연결이 있는 경우 침투 테스트 형태의 응용 프로그램 보안 테스트를 수행해야 합니다.</span><span class="sxs-lookup"><span data-stu-id="e3a11-361">Application security testing in the form of penetration testing MUST be carried out if your application has any connectivity to any service not published by Microsoft.</span></span> <span data-ttu-id="e3a11-362">앱이 Microsoft가 아닌 다른 서비스 또는 백end에 연결하지 않고 독립 실행형으로 작동하는 경우 침투 테스트가 필요하지 않습니다.</span><span class="sxs-lookup"><span data-stu-id="e3a11-362">If your app operates standalone without connectivity to any non-Microsoft service or backend, then penetration testing is not required.</span></span>


### <a name="penetration-testing-scope"></a><span data-ttu-id="e3a11-363">침투 테스트 범위</span><span class="sxs-lookup"><span data-stu-id="e3a11-363">Penetration Testing Scope</span></span>

<span data-ttu-id="e3a11-364">침투 테스트 작업에는 앱/추가 기능의 배포를 지원하는 환경(예: 앱/추가 기능 코드가 호스트되는 위치)과 앱/추가 기능의 작동을 지원하는 추가 환경(예: 앱/추가 기능에서 Microsoft 365 외부의 다른 웹 응용 프로그램과 연결되는 경우)이 포함되어야 합니다. </span><span class="sxs-lookup"><span data-stu-id="e3a11-364">Penetration testing activities **MUST** include the environment that supports the deployment of the app/add-in (for example; where the app/add-in code is hosted which will typically be the resource within the manifest file) along with any additional environment that supports the operation of the app/add-in (for example; if the app/add-in talks to other web applications outside of Microsoft 365).</span></span>  <span data-ttu-id="e3a11-365">범위를 정의할 때 범위 내 환경의 보안에 영향을 줄 수 있는 "연결된" 시스템 또는 환경이 모든 침투 테스트 활동 내에 포함되도록 주의해야 합니다.</span><span class="sxs-lookup"><span data-stu-id="e3a11-365">When defining the scope, care needs to be taken to ensure that any “connected-to” systems or environments that can impact upon the security of the in-scope environment is also included within ALL penetration testing activities.</span></span> 

<span data-ttu-id="e3a11-366">범위 내 환경을 다른 환경과 구분하는 기술을 사용하는 경우 침투 테스트 활동은 해당 분할 기술의 효율성을 검증해야 합니다.</span><span class="sxs-lookup"><span data-stu-id="e3a11-366">Where techniques are used to segment the in-scope environments from other environments, penetration testing activities MUST validate the effectiveness of said segmentation techniques.</span></span> <span data-ttu-id="e3a11-367">이 내용은 침투 테스트 보고서 내에서 자세히 설명해야 합니다.</span><span class="sxs-lookup"><span data-stu-id="e3a11-367">This must be detailed within the penetration testing report.</span></span> 
 

### <a name="testspecification"></a><span data-ttu-id="e3a11-368">테스트 사양</span><span class="sxs-lookup"><span data-stu-id="e3a11-368">Test Specification</span></span> 

|<span data-ttu-id="e3a11-369">테스트</span><span class="sxs-lookup"><span data-stu-id="e3a11-369">Test</span></span> | <span data-ttu-id="e3a11-370">컨트롤</span><span class="sxs-lookup"><span data-stu-id="e3a11-370">Controls</span></span> |
|-------|-----------|
|<span data-ttu-id="e3a11-371">**침투 테스트**</span><span class="sxs-lookup"><span data-stu-id="e3a11-371">**Penetration testing**</span></span>| <span data-ttu-id="e3a11-372">응용 프로그램 및 인프라  침투 테스트는 매년(12개월마다) 수행되어야 합니다.</span><span class="sxs-lookup"><span data-stu-id="e3a11-372">Application and infrastructure penetration testing **MUST** take place annually (every 12 months) and conducted by a reputable independent company.</span></span> <span data-ttu-id="e3a11-373">식별된 중요 및 고위험 취약성의 수정은 침투 테스트가 마무리된 후 한 달 이내에 또는 문서화된 패치 프로세스에 따라 더 빨리 완료해야 합니다. </span><span class="sxs-lookup"><span data-stu-id="e3a11-373">Remediation of identified critical and high-risk vulnerabilities **MUST** be completed within one month of the conclusion of the penetration testing, or sooner depending on the documented patching process.</span></span><span data-ttu-id="e3a11-374">전체 외부 공간(IP 주소, URL, API 끝점 등) 침투 테스트 범위 내에 포함되어야 하며 침투 테스트 보고서 내에 문서화해야 합니다. 전체 외부 공간(IP 주소, URL, API 끝점 등) **침투** 테스트 범위 내에 포함되어야 하며 침투 테스트 보고서 내에 문서화해야 합니다.</span><span class="sxs-lookup"><span data-stu-id="e3a11-374"> The full external footprint (IP Addresses, URLs, API Endpoints, etc.) MUST be included within the scope of penetration testing and must be documented within the penetration testing report.The full external footprint (IP Addresses, URLs, API Endpoints, etc.) *\*MUST** be included within the scope of penetration testing and must be documented within the penetration testing report.</span></span>                                                                                                                                                                           <span data-ttu-id="e3a11-375">웹 응용 프로그램 침투 테스트에는 모든 취약성 클래스가 포함되어야 합니다. 예를 들어 가장 최근의 OWASP 상위 10 또는 SANS 상위 25개 CWE입니다.</span><span class="sxs-lookup"><span data-stu-id="e3a11-375">Web application penetration testing MUST include all vulnerability classes; for example, the most current OWASP Top 10 or SANS Top 25 CWE.</span></span>                                                                                                                                                                                <span data-ttu-id="e3a11-376">침투 테스트 회사에서 식별된 취약점을 다시 테스트할 필요는 없습니다. 재구성 및 자체 검토로 충분하기는 하지만 평가 중에 충분한 수정을 입증할 수 있는 충분한 증거를 제공해야 합니다. </span><span class="sxs-lookup"><span data-stu-id="e3a11-376">Retesting of identified vulnerabilities by the penetration testing company is not required — remediation and self-review is sufficient however, adequate evidence to demonstrate sufficient remediation **MUST** be provided during the assessment.</span></span>|

### <a name="application-security-testing-reportreview"></a><span data-ttu-id="e3a11-377">응용 프로그램 보안 테스트 보고서 검토</span><span class="sxs-lookup"><span data-stu-id="e3a11-377">Application Security Testing Report Review</span></span>

<span data-ttu-id="e3a11-378">침투 테스트 보고서를 검토하여 다음과 같은 자동 오류 기준을 충족하는 취약점이 **없는지 검토합니다.**</span><span class="sxs-lookup"><span data-stu-id="e3a11-378">Penetration testing reports will be reviewed to ensure there are no vulnerabilities that meet the following **automatic failure criteria:**</span></span>

* <span data-ttu-id="e3a11-379">지원되지 않는 운영 체제가 있습니다.</span><span class="sxs-lookup"><span data-stu-id="e3a11-379">Presence of an unsupported operating system.</span></span> 

* <span data-ttu-id="e3a11-380">기본 계정, 열기 가능 또는 추측 가능한 관리 계정이 있습니다.</span><span class="sxs-lookup"><span data-stu-id="e3a11-380">Presence of default, enumerable, or guessable administrative accounts.</span></span>

* <span data-ttu-id="e3a11-381">삽입 위험 SQL 존재합니다.\*</span><span class="sxs-lookup"><span data-stu-id="e3a11-381">Presence of SQL injection risks.\*</span></span>

* <span data-ttu-id="e3a11-382">교차 사이트 스크립팅이 있습니다.\*</span><span class="sxs-lookup"><span data-stu-id="e3a11-382">Presence of cross-site scripting.\*</span></span>

* <span data-ttu-id="e3a11-383">디렉터리 트래버스(파일 경로) 취약성의 존재.\*</span><span class="sxs-lookup"><span data-stu-id="e3a11-383">Presence of directory traversal (file path) vulnerabilities.\*</span></span>

* <span data-ttu-id="e3a11-384">HTTP 취약성(예: 헤더 응답 분할, 요청 밀기 및 Desync 공격)이 있습니다.\*</span><span class="sxs-lookup"><span data-stu-id="e3a11-384">Presence of HTTP vulnerabilities, e.g., Header response splitting, Request smuggling, and Desync attacks.\*</span></span>

* <span data-ttu-id="e3a11-385">소스 코드 공개 [유무(LFI 포함)\*](#lfi)</span><span class="sxs-lookup"><span data-stu-id="e3a11-385">Presence of source code disclosure (including [LFI](#lfi)).\*</span></span>

* <span data-ttu-id="e3a11-386">CVSS 패치 관리 지침에 정의된 임의 또는 최고 점수입니다.</span><span class="sxs-lookup"><span data-stu-id="e3a11-386">Any critical or high score as defined by the CVSS patch management guidelines.</span></span>

* <span data-ttu-id="e3a11-387">많은 양의 EUII 또는 OUI를 손상하기 위해 쉽게 악용될 수 있는 중요한 기술 취약성.</span><span class="sxs-lookup"><span data-stu-id="e3a11-387">Any significant technical vulnerability which can be readily exploited to compromise a large amount of EUII or OUI.</span></span>

<span data-ttu-id="e3a11-388">\*취약성 CVSS 점수에 관계없이</span><span class="sxs-lookup"><span data-stu-id="e3a11-388">\*Regardless of the vulnerabilities CVSS Score</span></span>

> [!IMPORTANT]
><span data-ttu-id="e3a11-389">보고서는 응용 프로그램 보안 테스트 사양 섹션에 자세히 설명된 모든 내용을 보여줄 수 있어야 합니다.</span><span class="sxs-lookup"><span data-stu-id="e3a11-389">Reports must be able to provide enough assurance that everything detailed within the Application Security Test Specification section can be demonstrated.</span></span>


### <a name="penetration-testing-requirements-and-cost"></a><span data-ttu-id="e3a11-390">침투 테스트 요구 사항 및 비용</span><span class="sxs-lookup"><span data-stu-id="e3a11-390">Penetration Testing Requirements and Cost</span></span>

<span data-ttu-id="e3a11-391">현재 침투 테스트에 참여하지 않는 ISV의 경우 침투 테스트가 Microsoft 365 인증에 포함됩니다.</span><span class="sxs-lookup"><span data-stu-id="e3a11-391">For ISVs that currently do not engage in penetration testing, penetration testing is included under the Microsoft 365 Certification.</span></span> <span data-ttu-id="e3a11-392">Microsoft는 최대 12일의 수동 테스트에 대한 침투 테스트 비용을 준비하고 지원할 것입니다.</span><span class="sxs-lookup"><span data-stu-id="e3a11-392">Microsoft will arrange and cover the cost of a penetration test for up to 12 days of manual testing.</span></span> <span data-ttu-id="e3a11-393">침투 테스트 비용은 환경을 테스트하는 데 필요한 일 수를 기준으로 계산됩니다.</span><span class="sxs-lookup"><span data-stu-id="e3a11-393">Penetration tests costs are calculated based on the number of days required to test the environment.</span></span> <span data-ttu-id="e3a11-394">테스트가 12일을 초과하는 비용은 ISV의 책임입니다.</span><span class="sxs-lookup"><span data-stu-id="e3a11-394">Any expenses exceeding 12 days of testing will be the responsibility of the ISV.</span></span> <span data-ttu-id="e3a11-395">또한 ISV는 인증을 획득하기 전에 침투 테스트에서 식별된 취약점이 수정되었다는 것을 증명하지만, 클린 보고서를 만들 필요가 없다고 증명할 책임이 있습니다.</span><span class="sxs-lookup"><span data-stu-id="e3a11-395">The ISV will also be responsible for demonstrating that vulnerabilities identified in the penetration test have been remediated prior to a certification being awarded, but do not need to produce a clean report.</span></span>

<span data-ttu-id="e3a11-396">침투 테스트가 정렬된 후 ISV는 다음과 같이 예약 및 취소와 관련된 요금을 담당합니다.</span><span class="sxs-lookup"><span data-stu-id="e3a11-396">Once a penetration test is arranged, the ISV is responsible for fees associated with rescheduling and cancellations as follows:</span></span>

| <span data-ttu-id="e3a11-397">**요금 시간제 재조정**</span><span class="sxs-lookup"><span data-stu-id="e3a11-397">**Rescheduling Fee Timescale**</span></span> | <span data-ttu-id="e3a11-398">**비례 지급 가능**</span><span class="sxs-lookup"><span data-stu-id="e3a11-398">**Proportion Payable**</span></span> |
|------------------|------------------------|
| <span data-ttu-id="e3a11-399">예약된 시작 날짜 30일 전에 다시 예약 요청이 수신된 경우</span><span class="sxs-lookup"><span data-stu-id="e3a11-399">Re-schedule request received more than 30 days prior to scheduled start date.</span></span> | <span data-ttu-id="e3a11-400">0% 지급 가능</span><span class="sxs-lookup"><span data-stu-id="e3a11-400">0% Payable</span></span> |
| <span data-ttu-id="e3a11-401">다시 예약 요청은 예약된 시작 날짜 8~30일 전에 수신했습니다.</span><span class="sxs-lookup"><span data-stu-id="e3a11-401">Re-schedule request received 8 to 30 days prior to scheduled start date.</span></span> | <span data-ttu-id="e3a11-402">25% 지급 가능</span><span class="sxs-lookup"><span data-stu-id="e3a11-402">25% Payable</span></span> |
| <span data-ttu-id="e3a11-403">회사 재예약 날짜가 있는 예약된 시작 날짜로부터 2~7일 이내에 수신된 요청을 다시 예약합니다.</span><span class="sxs-lookup"><span data-stu-id="e3a11-403">Re-schedule request received within 2 to 7 days prior to scheduled start date with a firm re-booking date.</span></span>| <span data-ttu-id="e3a11-404">50% 지급 가능</span><span class="sxs-lookup"><span data-stu-id="e3a11-404">50% Payable</span></span> |
| <span data-ttu-id="e3a11-405">다시 예약 요청은 시작 날짜 2일 전에 수신됩니다.</span><span class="sxs-lookup"><span data-stu-id="e3a11-405">Re-schedule request received less than 2 days before the start date.</span></span> | <span data-ttu-id="e3a11-406">100% 지급 가능</span><span class="sxs-lookup"><span data-stu-id="e3a11-406">100% Payable</span></span> |

| <span data-ttu-id="e3a11-407">**취소 요금 시간 기준**</span><span class="sxs-lookup"><span data-stu-id="e3a11-407">**Cancellation Fee Timescale**</span></span> | <span data-ttu-id="e3a11-408">**비례 지급 가능**</span><span class="sxs-lookup"><span data-stu-id="e3a11-408">**Proportion Payable**</span></span> |
|------------------|------------------------|
| <span data-ttu-id="e3a11-409">취소 요청이 예정된 시작 날짜보다 30일 전에 수신했습니다.</span><span class="sxs-lookup"><span data-stu-id="e3a11-409">Cancellation request received more than 30 days prior to scheduled start date.</span></span> | <span data-ttu-id="e3a11-410">25% 지급 가능</span><span class="sxs-lookup"><span data-stu-id="e3a11-410">25% Payable</span></span> |
| <span data-ttu-id="e3a11-411">취소 요청은 예약된 시작 날짜 8~30일 전에 수신했습니다.</span><span class="sxs-lookup"><span data-stu-id="e3a11-411">Cancellation request received 8 to 30 days days prior to scheduled start date.</span></span> | <span data-ttu-id="e3a11-412">50% 지급 가능</span><span class="sxs-lookup"><span data-stu-id="e3a11-412">50% Payable</span></span> |
| <span data-ttu-id="e3a11-413">예약된 시작 날짜로부터 7일 이내에 수신된 취소 요청입니다.</span><span class="sxs-lookup"><span data-stu-id="e3a11-413">Cancellation request received within 7 days prior to scheduled start date.</span></span> | <span data-ttu-id="e3a11-414">90% 지급 가능</span><span class="sxs-lookup"><span data-stu-id="e3a11-414">90% Payable</span></span> |

## <a name="operational-security"></a><span data-ttu-id="e3a11-415">운영 보안</span><span class="sxs-lookup"><span data-stu-id="e3a11-415">Operational Security</span></span>

<span data-ttu-id="e3a11-416">이 도메인은 앱의 지원 인프라 및 배포 프로세스와 보안 모범 사례의 일치를 측정합니다.</span><span class="sxs-lookup"><span data-stu-id="e3a11-416">This domain measures the alignment of your app's supporting infrastructure and deployment processes with security best practices.</span></span>

### <a name="test-specification"></a><span data-ttu-id="e3a11-417">테스트 사양</span><span class="sxs-lookup"><span data-stu-id="e3a11-417">Test Specification</span></span>

|<span data-ttu-id="e3a11-418">테스트</span><span class="sxs-lookup"><span data-stu-id="e3a11-418">Test</span></span> | <span data-ttu-id="e3a11-419">컨트롤</span><span class="sxs-lookup"><span data-stu-id="e3a11-419">Controls</span></span> |
| ------------------------|------------------------------ |
| <span data-ttu-id="e3a11-420">**맬웨어 보호**</span><span class="sxs-lookup"><span data-stu-id="e3a11-420">**Malware Protection**</span></span> | <span data-ttu-id="e3a11-421">일반적으로 맬웨어의 영향을 받는 모든 범위 내 시스템에 맬웨어 보호 메커니즘을 배포해야 합니다.</span><span class="sxs-lookup"><span data-stu-id="e3a11-421">You must deploy malware protection mechanisms on all in-scope systems that are commonly affected by malware.</span></span> <span data-ttu-id="e3a11-422">이러한 보호 메커니즘에는 맬웨어로부터 보호하는 바이러스 백신 소프트웨어 또는 응용 프로그램 제어 기술을 사용할 수 있습니다.</span><span class="sxs-lookup"><span data-stu-id="e3a11-422">These protection mechanisms can include the use of anti-virus software or application control techniques that protect against malware.</span></span> <span data-ttu-id="e3a11-423">바이러스 백신 소프트웨어 또는 응용 프로그램 제어가 사용되는 경우 다음 조건을 충족해야 합니다.</span><span class="sxs-lookup"><span data-stu-id="e3a11-423">Where anti-virus software or application control is used, it MUST meet the following criteria.</span></span>                                                                                            <span data-ttu-id="e3a11-424">바이러스 백신(맬웨어 방지 제품 포함)은 다음을 충족해야 합니다.</span><span class="sxs-lookup"><span data-stu-id="e3a11-424">Anti-virus (also including anti-malware products) MUST meet the following:</span></span> |
||<span data-ttu-id="e3a11-425">&#x2713; 내의 모든 시스템 구성 요소에서 바이러스 백신 소프트웨어가 실행되고 있습니다.</span><span class="sxs-lookup"><span data-stu-id="e3a11-425">&#x2713; Anti-virus software is running on all system components within scope.</span></span>|
||<span data-ttu-id="e3a11-426">&#x2713; 바이러스 백신 소프트웨어는 최신으로 유지됩니다(30일 이내).</span><span class="sxs-lookup"><span data-stu-id="e3a11-426">&#x2713; Anti-virus software is kept up to date (within 30 days).</span></span>|
||<span data-ttu-id="e3a11-427">&#x2713; 바이러스 백신 서명은 최신으로 유지됩니다(1일 이내).</span><span class="sxs-lookup"><span data-stu-id="e3a11-427">&#x2713; Anti-virus signatures are kept up to date (within 1 day).</span></span>|
||<span data-ttu-id="e3a11-428">&#x2713; 검사 및/또는 알림이 있는 주기적 검사 중 하나를 구성해야 합니다.</span><span class="sxs-lookup"><span data-stu-id="e3a11-428">&#x2713; Either on-access scanning and/or periodic scans with notifications must be configured.</span></span>  <span data-ttu-id="e3a11-429">액세스 시 검사가 사용되는 경우 주별  검사도 구성해야 하지만 액세스 시 검색이 구성되지 않은 경우 매일 검색을 구성해야 합니다.</span><span class="sxs-lookup"><span data-stu-id="e3a11-429">Where on-access scanning is used, weekly scans **MUST** also be configured, however if on-access scanning is not configured, daily scanning must be configured.</span></span>|
||<span data-ttu-id="e3a11-430">&#x2713; 바이러스 백신 **소프트웨어는** 다음과 같이 구성해야 합니다.</span><span class="sxs-lookup"><span data-stu-id="e3a11-430">&#x2713; Anti-virus software **MUST** be configured as follows.</span></span>|
||<span data-ttu-id="e3a11-431">&emsp;&#x25fc; 의심되는 맬웨어를 차단합니다.</span><span class="sxs-lookup"><span data-stu-id="e3a11-431">&emsp;&#x25fc; Block suspected malware.</span></span>|
||<span data-ttu-id="e3a11-432">&emsp;&#x25fc; 의심되는 맬웨어를 차단합니다.</span><span class="sxs-lookup"><span data-stu-id="e3a11-432">&emsp;&#x25fc; Quarantine suspected malware.</span></span>|
||<span data-ttu-id="e3a11-433">&emsp;&#x25fc; 의심되는 맬웨어에 대한 경고를 제공합니다.</span><span class="sxs-lookup"><span data-stu-id="e3a11-433">&emsp;&#x25fc; Provide an alert on suspected malware.</span></span>|
||<span data-ttu-id="e3a11-434">&#x2713; 모든 활동을 기록하도록  바이러스 백신 소프트웨어를 구성해야 합니다.</span><span class="sxs-lookup"><span data-stu-id="e3a11-434">&#x2713; Anti-virus software **MUST** be configured to log all activities.</span></span>
||<span data-ttu-id="e3a11-435">&#x2713; 맬웨어 방지  모범 사례를 홍보하기 위해 정책 및 절차를 적용해야 합니다.</span><span class="sxs-lookup"><span data-stu-id="e3a11-435">&#x2713; Policies and procedures **MUST** be in place to promote strong anti-malware practices.</span></span>|
||<span data-ttu-id="e3a11-436">또는</span><span class="sxs-lookup"><span data-stu-id="e3a11-436">or</span></span>|
||<span data-ttu-id="e3a11-437">다음을 충족하려면 모든 범위 내 시스템에서 응용 프로그램 컨트롤을 구성해야 합니다.</span><span class="sxs-lookup"><span data-stu-id="e3a11-437">Application controls MUST be configured on all in-scope system to meet the following:</span></span>|
||<span data-ttu-id="e3a11-438">&#x2713; 범위 내 시스템 구성 요소에서 실행하도록 허용된 모든 허용 응용 프로그램은 조직에서 공식적으로 승인해야 합니다.</span><span class="sxs-lookup"><span data-stu-id="e3a11-438">&#x2713; All allowed applications permitted to execute on in-scope system components MUST be formally approved by the organization..</span></span>|
||<span data-ttu-id="e3a11-439">&#x2713; 조직은 응용 프로그램에 대한 업무 정당성에 따라 승인된 응용 프로그램의 전체 목록을 유지 관리해야 합니다.</span><span class="sxs-lookup"><span data-stu-id="e3a11-439">&#x2713; The organization MUST maintain a complete list of approved applications with business justification for the application.</span></span>|
||<span data-ttu-id="e3a11-440">&#x2713; 특정 응용 프로그램 제어 메커니즘을 완전히 문서화해야 합니다. 예: 화이트리스트 위치 코드 서명 등</span><span class="sxs-lookup"><span data-stu-id="e3a11-440">&#x2713; Specific application control mechanisms MUST be fully documented: i.e. whitelisted locations; code signing, etc.</span></span>|
||<span data-ttu-id="e3a11-441">&#x2713; 응용 프로그램 컨트롤을 문서로 구성해야 합니다.</span><span class="sxs-lookup"><span data-stu-id="e3a11-441">&#x2713; Application control MUST be configured as document.</span></span>|
||<span data-ttu-id="e3a11-442">&#x2713; 문서화한 응용 프로그램 승인 프로세스가 준비되어 감사가 가능해야 합니다.</span><span class="sxs-lookup"><span data-stu-id="e3a11-442">&#x2713; Documented process for application approvals must be in place and auditable.</span></span>|
|<span data-ttu-id="e3a11-443">**패치 관리**</span><span class="sxs-lookup"><span data-stu-id="e3a11-443">**Patch Management**</span></span>|<span data-ttu-id="e3a11-444">**패치가** 시기 적절한 방식으로 수행되도록 하는 패치 정책 및 절차를 문서화해야 합니다.</span><span class="sxs-lookup"><span data-stu-id="e3a11-444">You **MUST** have documented patching policies and procedures in place that ensure patching is conducted in a timely manner.</span></span> <span data-ttu-id="e3a11-445">CVSS V3.1 권장 위험 순위 점수 또는 동등한 점수 지정법을 기반으로 새 보안 취약성을 식별, 순위 및 패치하는 강력한 프로세스가 있어야 합니다. </span><span class="sxs-lookup"><span data-stu-id="e3a11-445">A robust process **MUST** be in place that identifies, ranks, and patches new security vulnerabilities based on the CVSS V3.1 **Recommended Risk Ranking Scores**, or equivalent scoring taxonomy:</span></span> 
||<span data-ttu-id="e3a11-446">**권장 위험 순위** 점수(CVSS v3.1 기본 점수 범위)</span><span class="sxs-lookup"><span data-stu-id="e3a11-446">**Recommended Risk Ranking Scores** (CVSS v3.1 Base Score Range)</span></span>|
||<span data-ttu-id="e3a11-447">&emsp;**Critical**: 9.0 - 10.0.</span><span class="sxs-lookup"><span data-stu-id="e3a11-447">&emsp; **Critical**: 9.0 - 10.0.</span></span>|
||<span data-ttu-id="e3a11-448">&emsp;**높음**: 7.0 - 8.9.</span><span class="sxs-lookup"><span data-stu-id="e3a11-448">&emsp; **High**: 7.0 - 8.9.</span></span>|
||<span data-ttu-id="e3a11-449">&emsp;**보통**: 4.0 - 6.9.</span><span class="sxs-lookup"><span data-stu-id="e3a11-449">&emsp; **Medium**: 4.0 - 6.9.</span></span>|
||<span data-ttu-id="e3a11-450">&emsp;**낮음**: 0.1 - 3.9.</span><span class="sxs-lookup"><span data-stu-id="e3a11-450">&emsp; **Low**: 0.1 - 3.9.</span></span>|
||<span data-ttu-id="e3a11-451">&emsp;**없음:** 0.0</span><span class="sxs-lookup"><span data-stu-id="e3a11-451">&emsp; **None**: 0.0</span></span> |
|| <span data-ttu-id="e3a11-452">**중요:** 새로운 취약점을 식별하는 프로세스는 정의한 문서화한 패치 창에 따라 취약점을 식별하고 패치할 수 있을 만큼 강력해야 합니다.</span><span class="sxs-lookup"><span data-stu-id="e3a11-452">**IMPORTANT**: The process to identify new vulnerabilities must be robust enough to allow for the identification and patching of vulnerabilities in line with the documented patching window you have defined.</span></span> |
|<span data-ttu-id="e3a11-453">**Patching**</span><span class="sxs-lookup"><span data-stu-id="e3a11-453">**Patching**</span></span>|<span data-ttu-id="e3a11-454">&#x2713; 위험, 높음 또는 중간  위험 문제는 ISV에서 결정한 미리 결정된 기간 내에 패치해야 합니다. 이 기간은 문제를 해결해야 합니다. </span><span class="sxs-lookup"><span data-stu-id="e3a11-454">&#x2713; Any Critical, High, or Medium risk issues **MUST** be patched within a pre-determined and documented period decided by the ISV which represents the minimal window of time before the issue **must be** resolved.</span></span>  <span data-ttu-id="e3a11-455">패치 창이 ISV에 의해 정의되어 있는 경우 창은 적절한 기간 내에야 합니다.</span><span class="sxs-lookup"><span data-stu-id="e3a11-455">Although the patching window is defined by the ISV, the window needs to be within a reasonable timeframe.</span></span> <span data-ttu-id="e3a11-456">예를 들어 중요 취약점을 패치하는 데 3개월이면 합리적이지 못하므로 Microsoft 365 인증 평가 내에서 거부됩니다.</span><span class="sxs-lookup"><span data-stu-id="e3a11-456">For example, three months to patch a Critical vulnerability would not be reasonable and therefore rejected within your Microsoft 365 Certification assessment.</span></span>|
||<span data-ttu-id="e3a11-457">&#x2713; 패치 수행 방법을 자세히 설명하는 정책  및 절차는 적용되어야 **합니다.** 또한 해당 환경 내에서 사용되는 모든 운영 체제, 응용 프로그램 및 소프트웨어 구성 요소를 포함해야 합니다.</span><span class="sxs-lookup"><span data-stu-id="e3a11-457">&#x2713; Policies and procedures detailing how patching is conducted **MUST** be in place and **MUST** include all applicable operating systems, applications and software components used within the environment.</span></span> <span data-ttu-id="e3a11-458">여기에는 앱/추가 기능 내에서 사용되는 모든 웹 종속성도 포함됩니다.</span><span class="sxs-lookup"><span data-stu-id="e3a11-458">This includes any web dependencies used within the app/add-in.</span></span>|
||<span data-ttu-id="e3a11-459">&#x2713; 소프트웨어 구성 요소 및 운영 체제가 공급업체에서 더 이상 지원되지 않는 경우 해당 환경에서는 사용되지 않습니다. </span><span class="sxs-lookup"><span data-stu-id="e3a11-459">&#x2713; Software components and operating systems no longer supported by the vendor **MUST** not be used within the environment.</span></span> <span data-ttu-id="e3a11-460">지원 **정책이** 있어야 지원되지 않는 소프트웨어 구성 요소/운영 체제가 환경에서 제거되고 소프트웨어 구성 요소가 수명 종료될 때를 식별하는 프로세스가 필요합니다.</span><span class="sxs-lookup"><span data-stu-id="e3a11-460">Supporting policies **MUST** be in place to ensure unsupported software components / operating systems will be removed from the environment and a process to identify when software components go end-of-life must be in place.</span></span>|
|<span data-ttu-id="e3a11-461">**취약성 검색**</span><span class="sxs-lookup"><span data-stu-id="e3a11-461">**Vulnerability scanning**</span></span>|<span data-ttu-id="e3a11-462">취약점 검사에는 다음이 포함되어야 합니다.</span><span class="sxs-lookup"><span data-stu-id="e3a11-462">Vulnerability scanning must include:</span></span>|
||<span data-ttu-id="e3a11-463">&#x2713; 환경의 전체 공용 공간(인프라 및 웹  응용 프로그램 검색용 URL 및 IP 주소)에 대해 분기별 외부 취약점 검사가 수행됩니다.</span><span class="sxs-lookup"><span data-stu-id="e3a11-463">&#x2713; Quarterly external vulnerability scanning carried out against the **FULL** public footprint of the in-scope environment (URLs AND IP Addresses for Infrastructure and Web Application scanning).</span></span>|
||<span data-ttu-id="e3a11-464">&#x2713; 내부 취약점 검사는 PaaS가 아닌 범위 내 시스템 구성 요소에 대해 수행됩니다.</span><span class="sxs-lookup"><span data-stu-id="e3a11-464">&#x2713; Quarterly authenticated internal vulnerability scanning carried out against in-scope system components (not for PaaS).</span></span>|
||<span data-ttu-id="e3a11-465">&#x2713; 정의된 CVSS 권장 위험  순위 점수에 따라 취약점을 해결하기 위한 타임라인을 자세히 설명하여 시스템 구성 요소가 알려진 \*\*\*\* 취약성으로부터 자유로이 사용되도록 문서화된 취약점 수정 정책을 설정해야 합니다(위 참조).</span><span class="sxs-lookup"><span data-stu-id="e3a11-465">&#x2713; A documented vulnerability remediation policy **MUST** be in place to ensure system components are free from known vulnerabilities by detailing the timeline to fix vulnerabilities based upon your defined CVSS **Recommended Risk Ranking Scores**(see above).</span></span>|
||<span data-ttu-id="e3a11-466">&#x2713; ISV의 수정 정책에  정의된 위험 순위 취약점이 필요한 시간 내에 수정될 때까지 지속적인 재조사가 수행되어야 합니다.</span><span class="sxs-lookup"><span data-stu-id="e3a11-466">&#x2713; Ongoing re-scans **MUST** be carried out until identified risk ranked vulnerabilities are remediated within the required timeline, as defined by the ISV’s remediation policy.</span></span> <span data-ttu-id="e3a11-467">재구성 타임라인은 ISV에 의해 정의되어 있기는 하지만 창은 적절한 기간 내에야 합니다.</span><span class="sxs-lookup"><span data-stu-id="e3a11-467">Although the remediation timeline is defined by the ISV, the window needs to be within a reasonable timeframe.</span></span> <span data-ttu-id="e3a11-468">예를 들어 중요한 취약성을 수정하는 데 3개월이면 합리적이지 못하므로 Microsoft 365 인증 평가 내에서 거부됩니다.</span><span class="sxs-lookup"><span data-stu-id="e3a11-468">For example, three months to remediate a Critical vulnerability would not be reasonable and therefore rejected within your Microsoft 365 Certification assessment.</span></span>|
|<span data-ttu-id="e3a11-469">**방화벽**</span><span class="sxs-lookup"><span data-stu-id="e3a11-469">**Firewalls**</span></span>|<span data-ttu-id="e3a11-470">지원 인프라에 다음과 같이 방화벽(또는 클라우드 서비스가 사용되고 있는 동등한 위치)이 구성되어 있을 것으로 예상됩니다.</span><span class="sxs-lookup"><span data-stu-id="e3a11-470">Your supporting infrastructure will be expected to have a firewall (or equivalent where Cloud services are being consumed) configured as follows:</span></span>|
||<span data-ttu-id="e3a11-471">&#x2713; 환경을  노출하는 모든 인터넷 연결에 설치해야 합니다.</span><span class="sxs-lookup"><span data-stu-id="e3a11-471">&#x2713; **MUST** be installed on all internet connections exposing the in-scope environments.</span></span>|
||<span data-ttu-id="e3a11-472">&#x2713; DMZ(Demilitarized Zones)와 신뢰할 수 있는 네트워크 사이에 설치해야 합니다. </span><span class="sxs-lookup"><span data-stu-id="e3a11-472">&#x2713; **MUST** be installed between all DMZs (Demilitarized Zones) and any trusted networks.</span></span>|
||<span data-ttu-id="e3a11-473">&#x2713; 모든 공용 **액세스는** DMZ(비무장 영역)에서 종료되어야 합니다.</span><span class="sxs-lookup"><span data-stu-id="e3a11-473">&#x2713; All public access **MUST** terminate in a DMZ (Demilitarized Zone).</span></span> |
||<span data-ttu-id="e3a11-474">&#x2713; 환경에 설치하기 전에  기본 관리 자격 증명을 변경해야 합니다.</span><span class="sxs-lookup"><span data-stu-id="e3a11-474">&#x2713; Default administrative credentials **MUST** be changed, prior to installation into production environments.</span></span>|
||<span data-ttu-id="e3a11-475">&#x2713; 범위 내 방화벽을 통해 허용되는 모든 트래픽(어느  방향이든)은 승인 프로세스를 거치고 모든 프로토콜, 서비스 및 포트는 업무 정당성에 따라 문서화되어야 합니다.</span><span class="sxs-lookup"><span data-stu-id="e3a11-475">&#x2713; ­All traffic permitted through in-scope firewalls (in either direction) **MUST** go through an approval process and all protocols, services and ports must be documented with business justifications.</span></span>|
||<span data-ttu-id="e3a11-476">&#x2713; 허용된 규칙을 사용하여 방화벽 규칙을 인라인으로 구성해야 합니다.</span><span class="sxs-lookup"><span data-stu-id="e3a11-476">&#x2713; Firewall rules must be configured in-line with the documented permitted rules.</span></span>|
||<span data-ttu-id="e3a11-477">&#x2713; 부록 **B와** 함께 강력한 암호화는 모든 방화벽  비 콘솔 관리 인터페이스에서 사용하도록 설정해야 합니다.</span><span class="sxs-lookup"><span data-stu-id="e3a11-477">&#x2713; ­Strong cryptography, in line with **Appendix B**, **MUST** be enabled on all firewall non-console administrative interfaces.</span></span>|
||<span data-ttu-id="e3a11-478">&#x2713; 액세스하려면 MFA(다단계 인증)를 사용하도록 설정해야 합니다. </span><span class="sxs-lookup"><span data-stu-id="e3a11-478">&#x2713; Multi-factor authentication (MFA) **MUST** be enabled for firewall administrative access..</span></span>|
||<span data-ttu-id="e3a11-479">&#x2713; 방화벽 **검토는 적어도** 6개월마다 실시해야 합니다.</span><span class="sxs-lookup"><span data-stu-id="e3a11-479">&#x2713;­ Firewall reviews **MUST** be conducted at least every six months.</span></span>|
||<span data-ttu-id="e3a11-480">인증 분석은 외부 타사 데이터 공유의 유효성을 검사하기 위해 잠재적 타사로의 유입 트래픽 흐름이 존재하기 위한 방화벽 규칙 기준을 검토합니다.</span><span class="sxs-lookup"><span data-stu-id="e3a11-480">Certification analysis will review the firewall rules base for the presence of egress traffic flows to potential third parties to validate external third-party data sharing.</span></span>  |
||<span data-ttu-id="e3a11-481">**WAF(웹 응용 프로그램 방화벽)**.</span><span class="sxs-lookup"><span data-stu-id="e3a11-481">**Web Application Firewall (WAF)**.</span></span> <span data-ttu-id="e3a11-482">웹 응용 프로그램 위협 및 취약성을 보호하기 위해 WAF 또는 동등한 조치가 배포된 경우 추가 크레딧이 부여됩니다.</span><span class="sxs-lookup"><span data-stu-id="e3a11-482">Additional credit will be given if a WAF or equivalent measure is deployed to help protect against web application threats and vulnerabilities.</span></span> <span data-ttu-id="e3a11-483">있는 경우 다음 WAF  구성과 함께 지원 정책 및 절차를 적용해야 합니다.</span><span class="sxs-lookup"><span data-stu-id="e3a11-483">If present, supporting policies and procedures **SHOULD** be in place along with the following WAF configurations:</span></span> |
||<span data-ttu-id="e3a11-484">&#x2713; WAF는 활성 방어 모드(식별된 공격을 자동으로 차단) 또는 모니터링 모드(경고를 적극적으로 모니터링/조사)에서 작동해야 합니다.</span><span class="sxs-lookup"><span data-stu-id="e3a11-484">&#x2713; WAF SHOULD operate in active defense mode (automatically blocking identified attacks) or in monitoring mode (actively monitoring/investigating alerts).</span></span>|
||<span data-ttu-id="e3a11-485">&#x2713; 오프로더링을 지원하도록 구성된 [WAF입니다.](#ssl)</span><span class="sxs-lookup"><span data-stu-id="e3a11-485">&#x2713; WAF configured to support [SSL](#ssl) offloading.</span></span>|
||<span data-ttu-id="e3a11-486">&#x2713; WAF는 다음의 대부분으로부터 보호하기 위해 [OWASP](#owasp) **핵심** 규칙   집합(3.0 또는 3.1)에 따라 구성해야 합니다.</span><span class="sxs-lookup"><span data-stu-id="e3a11-486">&#x2713; WAF SHOULD be configured as per the [OWASP](#owasp) **Core Rule Set** (3.0 or 3.1) to protect against the majority of the following:</span></span>|
||<span data-ttu-id="e3a11-487">&emsp;&#x25fc; 및 인코딩 문제를 해결합니다.</span><span class="sxs-lookup"><span data-stu-id="e3a11-487">&emsp;&#x25fc; Protocol and encoding issues.</span></span>|
||<span data-ttu-id="e3a11-488">&emsp;&#x25fc;, 요청 밀기 및 응답 분할을 요청합니다.</span><span class="sxs-lookup"><span data-stu-id="e3a11-488">&emsp;&#x25fc; Header injection, request smuggling, and response splitting.</span></span>|
||<span data-ttu-id="e3a11-489">&emsp;&#x25fc; 경로 트래버스 공격을 공격합니다.</span><span class="sxs-lookup"><span data-stu-id="e3a11-489">&emsp;&#x25fc; File and path traversal attacks.</span></span>|
||<span data-ttu-id="e3a11-490">&emsp;&#x25fc; RFI(원격 파일 포함) 공격이 있습니다.</span><span class="sxs-lookup"><span data-stu-id="e3a11-490">&emsp;&#x25fc; Remote file inclusion (RFI) attacks.</span></span>|
||<span data-ttu-id="e3a11-491">&emsp;&#x25fc; 코드 실행 공격을 중지합니다.</span><span class="sxs-lookup"><span data-stu-id="e3a11-491">&emsp;&#x25fc; Remote code execution attacks.</span></span>|
||<span data-ttu-id="e3a11-492">&emsp;&#x25fc; PHP 주입 공격이 있습니다.</span><span class="sxs-lookup"><span data-stu-id="e3a11-492">&emsp;&#x25fc; PHP-injection attacks.</span></span>|
||<span data-ttu-id="e3a11-493">&emsp;&#x25fc; 스크립팅 공격을 수정합니다.</span><span class="sxs-lookup"><span data-stu-id="e3a11-493">&emsp;&#x25fc; Cross-site scripting attacks.</span></span>|
||<span data-ttu-id="e3a11-494">&emsp;&#x25fc; SQL 주입 공격.</span><span class="sxs-lookup"><span data-stu-id="e3a11-494">&emsp;&#x25fc; SQL-injection attacks.</span></span>|
||<span data-ttu-id="e3a11-495">&emsp;&#x25fc; 수정 공격을 해결합니다.</span><span class="sxs-lookup"><span data-stu-id="e3a11-495">&emsp;&#x25fc; Session-fixation attacks.</span></span>|
|<span data-ttu-id="e3a11-496">**변경 컨트롤**</span><span class="sxs-lookup"><span data-stu-id="e3a11-496">**Change Control**</span></span>|<span data-ttu-id="e3a11-497">변경 제어 정책 및 **절차는** 환경의 보안, 안정성 및 무결성을 유지하기 위한 방식으로 변경 내용이 구현되도록 해야 합니다.</span><span class="sxs-lookup"><span data-stu-id="e3a11-497">Change control policies and procedures **MUST** be in place to ensure that changes are implemented in a manner aimed at maintaining the security, stability, and integrity of the environment.</span></span> <span data-ttu-id="e3a11-498">다음과 같은 변경 제어 **조건이** 필요합니다.</span><span class="sxs-lookup"><span data-stu-id="e3a11-498">The following change control criteria **ARE** required:</span></span>|
||<span data-ttu-id="e3a11-499">&#x2713; 업무 분리 - 개발 환경과  테스트 환경은 프로덕션 환경과 분리되어야 합니다.</span><span class="sxs-lookup"><span data-stu-id="e3a11-499">&#x2713; Separation of duties—development and test environments **MUST** be separate from the production environments.</span></span>|
||<span data-ttu-id="e3a11-500">&#x2713; 환경의 중요한 데이터는 **개발/테스트** 환경에서 사용되지 말아야 합니다.</span><span class="sxs-lookup"><span data-stu-id="e3a11-500">&#x2713; Sensitive data from production environments **MUST** not be used within development/test environments.</span></span>|
||<span data-ttu-id="e3a11-501">&#x2713; 프로덕션 환경에 도입하기 전에 테스트/개발 환경에서 모든 변경 내용을 테스트해야 합니다.</span><span class="sxs-lookup"><span data-stu-id="e3a11-501">&#x2713; All changes MUST be tested within a test/development environment prior to being introduced into the production environment.</span></span>|
||<span data-ttu-id="e3a11-502">&#x2713; 변경 **요청은** 프로덕션으로 들어오기  전에 발생하고 권한이 부여됩니다.</span><span class="sxs-lookup"><span data-stu-id="e3a11-502">&#x2713; Change requests **ARE** raised and authorized **PRIOR** to going into production.</span></span>|
||<span data-ttu-id="e3a11-503">&#x2713; 변경 요청에는 다음이 **포함되어야** 합니다.</span><span class="sxs-lookup"><span data-stu-id="e3a11-503">&#x2713; At a minimum, change requests **MUST** include:</span></span>|
||<span data-ttu-id="e3a11-504">&emsp;&#x25fc; 문서화합니다.</span><span class="sxs-lookup"><span data-stu-id="e3a11-504">&emsp;&#x25fc; Documentation of impact.</span></span>|
||<span data-ttu-id="e3a11-505">&emsp;&#x25fc; 문서화된 백아웃 프로시저입니다.</span><span class="sxs-lookup"><span data-stu-id="e3a11-505">&emsp;&#x25fc; Documented back-out procedures.</span></span>|
||<span data-ttu-id="e3a11-506">&#x2713; 변경 요청은  기능 테스트가 성공적으로  수행된 후에만 완료로 표시되어야 합니다.</span><span class="sxs-lookup"><span data-stu-id="e3a11-506">&#x2713; Change requests **MUST** be marked as complete, only **AFTER** successful functionality testing has been carried out.</span></span>|
|<span data-ttu-id="e3a11-507">**보안 소프트웨어 개발/배포**</span><span class="sxs-lookup"><span data-stu-id="e3a11-507">**Secure Software Development/Deployment**</span></span>|<span data-ttu-id="e3a11-508">앱/추가 기능으로 코딩 취약성을 도입하여 보안 환경을 유지 관리하고 데이터를 보호할 위험을 최소화하기 위해 소프트웨어 개발 관행의 최전방에 보안을 유지해야 합니다.</span><span class="sxs-lookup"><span data-stu-id="e3a11-508">Security needs to be at the forefront of software development practices to minimize the risk of introducing coding vulnerabilities into the app / add-in, thereby maintaining a secure environment, and securing data.</span></span> <span data-ttu-id="e3a11-509">다음과 같은 소프트웨어 개발  보안 사례가 있어야 합니다.</span><span class="sxs-lookup"><span data-stu-id="e3a11-509">The following software development secure practices **MUST** be in place:</span></span> |
||<span data-ttu-id="e3a11-510">&#x2713; 전체 소프트웨어 개발 수명 주기를 다루는 설정 및 문서화 소프트웨어 개발 프로세스가 있어야 합니다.</span><span class="sxs-lookup"><span data-stu-id="e3a11-510">&#x2713; You MUST have an established and documented software development process covering the entire software-development lifecycle.</span></span>|
||<span data-ttu-id="e3a11-511">&#x2713; 모든 코드 변경 내용은 원래 개발자가 아는 사람이 검토 및 권한 부여 프로세스를 거치야 합니다.</span><span class="sxs-lookup"><span data-stu-id="e3a11-511">&#x2713; All code changes MUST go through a review and authorization process by someone other than the original developer.</span></span>|
||<span data-ttu-id="e3a11-512">&#x2713; 코딩 방법 및 검토 기술은  [OWASP 상위 10](https://owasp.org/www-project-top-ten) 또는 SANS 상위 [25개 CWE](https://www.sans.org/top25-software-errors) 취약성 클래스를 해결해야 합니다.</span><span class="sxs-lookup"><span data-stu-id="e3a11-512">&#x2713; Secure coding practices and review techniques **MUST** address the [OWASP Top 10](https://owasp.org/www-project-top-ten) or [SANS Top 25 CWE](https://www.sans.org/top25-software-errors) Vulnerability Classes.</span></span>|
||<span data-ttu-id="e3a11-513">&#x2713; 개발자는 **적어도** 매년 보안 소프트웨어 코딩 교육을 실시해야 합니다.</span><span class="sxs-lookup"><span data-stu-id="e3a11-513">&#x2713; Developers **MUST** undergo secure software coding training at least annually.</span></span>|
||<span data-ttu-id="e3a11-514">&#x2713; 코드 리포지토리는 MFA로 보호해야 합니다. </span><span class="sxs-lookup"><span data-stu-id="e3a11-514">&#x2713; Code repositories **MUST** be secured by MFA.</span></span>|
||<span data-ttu-id="e3a11-515">&#x2713; 코드가 수정되지  않은 경우 코드 리포지토리를 보호하기 위해 적절한 액세스 제어가 있어야 합니다.</span><span class="sxs-lookup"><span data-stu-id="e3a11-515">&#x2713; Adequate access controls **MUST** be in place to protect code repositories against malicious code modifications.</span></span>|
||<span data-ttu-id="e3a11-516">**참고:** Microsoft는 제품 [](https://www.microsoft.com/en-us/securityengineering/sdl/) 내에서 보안 보장 및 규정 준수 요구 사항을 지원하기 위해 Microsoft가 따르는 SDL(보안 개발 수명 주기)을 게시했습니다.</span><span class="sxs-lookup"><span data-stu-id="e3a11-516">**Note**: Microsoft has published the [Security Development Lifecycle](https://www.microsoft.com/en-us/securityengineering/sdl/) (SDL) that Microsoft follows to support security assurance and compliance requirements within its products.</span></span> <span data-ttu-id="e3a11-517">SDL을 사용하면 개발자가 소프트웨어의 취약성 수와 심각도는 줄이면서 개발 비용을 절감하여 보다 안전한 소프트웨어를 빌드할 수 있습니다.</span><span class="sxs-lookup"><span data-stu-id="e3a11-517">The SDL helps developers build more secure software by reducing the number and severity of vulnerabilities in software, while reducing development cost.</span></span>|
|<span data-ttu-id="e3a11-518">**계정 관리**</span><span class="sxs-lookup"><span data-stu-id="e3a11-518">**Account Management**</span></span>| <span data-ttu-id="e3a11-519">범위 내 시스템 구성 요소 계정 관리 및 지원 정책 및 절차는 **다음을** 충족해야 합니다.</span><span class="sxs-lookup"><span data-stu-id="e3a11-519">In-scope system component account management as well as supporting policies and procedures **MUST** meet the following:</span></span> |
||<span data-ttu-id="e3a11-520">&#x2713;(공급업체 또는 ISV)는 모든  범위 내 시스템 구성 요소에서 사용하지 않도록 설정되거나 제거됩니다.</span><span class="sxs-lookup"><span data-stu-id="e3a11-520">&#x2713; Default credentials (Vendor or ISV) **ARE** either disabled or removed across all in-scope system components.</span></span>|
||<span data-ttu-id="e3a11-521">&#x2713; 계정 만들기, 수정 및 삭제는 **정해진** 승인 프로세스를 거치야 합니다.</span><span class="sxs-lookup"><span data-stu-id="e3a11-521">&#x2713; Account creation, modification and deletion **MUST** go through an established approval process.</span></span>|
||<span data-ttu-id="e3a11-522">&#x2713; 3개월 이상 사용되지 않은 계정은  사용하지 않도록 설정하거나 삭제해야 하므로 ISV에서 이를 달성하는 메커니즘이 있어야 합니다.</span><span class="sxs-lookup"><span data-stu-id="e3a11-522">&#x2713; Accounts that have not been used for over 3 months **MUST** be disabled or deleted, therefore, ISV needs to have a mechanism of achieving this.</span></span>|
||<span data-ttu-id="e3a11-523">&#x2713;강력한 암호 정책 또는 기타 적절한  완화는 사용자 자격 증명을 보호하도록 구성해야 합니다.</span><span class="sxs-lookup"><span data-stu-id="e3a11-523">&#x2713;Strong password policies or other suitable mitigation **MUST** be configured to protect user credentials.</span></span> <span data-ttu-id="e3a11-524">다음 암호 정책을 지침으로 사용해야 합니다.</span><span class="sxs-lookup"><span data-stu-id="e3a11-524">The following password policy should be used as a guideline:</span></span>|
||<span data-ttu-id="e3a11-525">&emsp;&#x25fc; 8자 최소 암호 길이</span><span class="sxs-lookup"><span data-stu-id="e3a11-525">&emsp;&#x25fc; Minimum password length of eight characters</span></span>|
||<span data-ttu-id="e3a11-526">&emsp;&#x25fc; 계정 잠금 임계값은 10회를 초과하지 않습니다.</span><span class="sxs-lookup"><span data-stu-id="e3a11-526">&emsp;&#x25fc; Account lockout threshold of no more than 10 attempts</span></span>|
||<span data-ttu-id="e3a11-527">&emsp;&#x25fc; 암호의 최소 5개 암호 기록</span><span class="sxs-lookup"><span data-stu-id="e3a11-527">&emsp;&#x25fc; Password history of a minimum of five passwords</span></span>|
||<span data-ttu-id="e3a11-528">&emsp;&#x25fc; 강력한 암호 사용 적용</span><span class="sxs-lookup"><span data-stu-id="e3a11-528">&emsp;&#x25fc; Enforcement of the use of strong passwords</span></span>|
||<span data-ttu-id="e3a11-529">&#x2713; 고유한 사용자 계정을 각 사용자에게 발급해야 합니다. 공유 계정은 사용할 수 없습니다.</span><span class="sxs-lookup"><span data-stu-id="e3a11-529">&#x2713; Unique user accounts MUST be issued to each user; no shared accounts are to be used.</span></span>|
||<span data-ttu-id="e3a11-530">&#x2713; 최소 권한 원칙은 모든 사용자에게 적용되어야 합니다. 이를 위해 사용하는 메커니즘을 문서화해야 합니다(예: 그룹 사용). </span><span class="sxs-lookup"><span data-stu-id="e3a11-530">&#x2713; Least privilege principles **MUST** apply to all users, the mechanism used to achieve this should be documented (i.e. the use of groups).</span></span> |
||<span data-ttu-id="e3a11-531">&#x2713; 적절한 서비스 계정의 **하드텐트는** 대화형 로그온 사용 안 하도록 설정, 특정 호스트로 제한되는 로그온 등의 문서화 및 수행되어야 합니다.</span><span class="sxs-lookup"><span data-stu-id="e3a11-531">&#x2713; Suitable service account hardening **MUST** be documented and carried out, for example, interactive logon disabled, logons limited to specific hosts, etc.</span></span> |
||<span data-ttu-id="e3a11-532">&#x2713; 원격 액세스 솔루션은 다음을 해야 **합니다.**</span><span class="sxs-lookup"><span data-stu-id="e3a11-532">&#x2713; Remote Access solutions **MUST**:</span></span> |
||<span data-ttu-id="e3a11-533">&emsp;&#x25fc; MFA(Multi Factor Authentication) 활용</span><span class="sxs-lookup"><span data-stu-id="e3a11-533">&emsp;&#x25fc; utilize MFA (Multi Factor Authentication)</span></span>|
||<span data-ttu-id="e3a11-534">&emsp;&#x25fc; A에 설명된 데이터 전송 구성 프로필을 충족하거나 초과하는 전송 보호 프로필의 데이터를 활용하는 방법</span><span class="sxs-lookup"><span data-stu-id="e3a11-534">&emsp;&#x25fc; utilize a data in transit protection profile that meets or exceeds the data-in-transit configuration profile as described in Appendix A</span></span>|
||<span data-ttu-id="e3a11-535">&#x2713; 공용 DNS 관리가 범위 내 환경 외부에 있는 경우 DNS를 수정할 수 있는 모든 사용자 계정이 MFA를 사용하도록 구성해야 합니다.</span><span class="sxs-lookup"><span data-stu-id="e3a11-535">&#x2713; Where the management of Public DNS is outside of the in-scope environment, all user accounts able to make DNS modifications MUST be configured to use MFA.</span></span>|
||<span data-ttu-id="e3a11-536">**참고:** 클라우드 관리 포털은 적용 가능한 계정 관리 요구 사항을 충족해야 합니다. 자세한 내용은 부록 F를 참조하세요.</span><span class="sxs-lookup"><span data-stu-id="e3a11-536">**Note** : Cloud Management Portals will also need to meet applicable account management requirements, see Appendix F for further details.</span></span>|
|<span data-ttu-id="e3a11-537">**침입 감지 및 방지(OPTIONAL)**</span><span class="sxs-lookup"><span data-stu-id="e3a11-537">**Intrusion Detection and Prevention (OPTIONAL)**</span></span>| <span data-ttu-id="e3a11-538">범위 내 지원 환경의 경계에서 IDPS(침입 감지 및 방지 시스템)가 사용되는 경우 추가 크레딧이 부여됩니다.</span><span class="sxs-lookup"><span data-stu-id="e3a11-538">Extra credit will be given where IDPS (Intrusion Detection and Prevention System) is used at the perimeter of the in-scope supporting environments.</span></span>  <span data-ttu-id="e3a11-539">다음과 같은 권장 컨트롤이 포함됩니다.</span><span class="sxs-lookup"><span data-stu-id="e3a11-539">The following recommended controls include:</span></span> |
||<span data-ttu-id="e3a11-540">&#x2713; IDPS는 지원 환경의 경계에 배포해야 합니다.</span><span class="sxs-lookup"><span data-stu-id="e3a11-540">&#x2713; IDPS SHOULD be deployed at the perimeter of the supporting environment</span></span> |
||<span data-ttu-id="e3a11-541">&#x2713; IDPS 서명을 최신으로 유지해야 합니다.</span><span class="sxs-lookup"><span data-stu-id="e3a11-541">&#x2713; IDPS signatures SHOULD be kept current, within the past day</span></span> |
||<span data-ttu-id="e3a11-542">&#x2713; TLS 검사를 위해 IDPS를 구성해야 합니다.</span><span class="sxs-lookup"><span data-stu-id="e3a11-542">&#x2713; IDPS SHOULD be configured for TLS inspection</span></span> |
||<span data-ttu-id="e3a11-543">&#x2713; 모든 인바운드 및 아웃바운드 트래픽에 대해 IDPS를 구성해야 합니다.</span><span class="sxs-lookup"><span data-stu-id="e3a11-543">&#x2713; IDPS SHOULD be configured for ALL inbound and outbound traffic</span></span> |
||<span data-ttu-id="e3a11-544">&#x2713; IDPS를 구성해야 합니다.</span><span class="sxs-lookup"><span data-stu-id="e3a11-544">&#x2713; IDPS SHOULD be configured for alerting</span></span> |
|<span data-ttu-id="e3a11-545">**이벤트 로깅**</span><span class="sxs-lookup"><span data-stu-id="e3a11-545">**Event Logging**</span></span> |<span data-ttu-id="e3a11-546">로깅 **범위에는** **맬웨어** 보호 메커니즘을 비롯한 모든 범위 내 시스템 구성 요소 및 응용 프로그램이 포함되어야 합니다.</span><span class="sxs-lookup"><span data-stu-id="e3a11-546">Logging coverage **MUST** include **ALL** in-scope system components and applications, including malware protection mechanisms.</span></span> <span data-ttu-id="e3a11-547">다음 이벤트를 **기록해야** 합니다.</span><span class="sxs-lookup"><span data-stu-id="e3a11-547">The following events **MUST** be logged:</span></span>|
||<span data-ttu-id="e3a11-548">&emsp;&#x25fc; 구성 요소 및 응용 프로그램에 대한 사용자 액세스</span><span class="sxs-lookup"><span data-stu-id="e3a11-548">&emsp;&#x25fc; Users access to system components and the application</span></span>|
||<span data-ttu-id="e3a11-549">&emsp;&#x25fc; 권한이 높은 사용자가 수행한 모든 작업</span><span class="sxs-lookup"><span data-stu-id="e3a11-549">&emsp;&#x25fc; All actions taken by a high-privileged user</span></span>|
||<span data-ttu-id="e3a11-550">&emsp;&#x25fc; 논리적 액세스 시도가 잘못되었습니다.</span><span class="sxs-lookup"><span data-stu-id="e3a11-550">&emsp;&#x25fc; Invalid logical access attempts</span></span>|
||<span data-ttu-id="e3a11-551">&emsp;&#x25fc; 계정 만들기/수정</span><span class="sxs-lookup"><span data-stu-id="e3a11-551">&emsp;&#x25fc; Privileged account creation / modification</span></span>|
||<span data-ttu-id="e3a11-552">&emsp;&#x25fc; 로그 변조</span><span class="sxs-lookup"><span data-stu-id="e3a11-552">&emsp;&#x25fc; Event log tampering</span></span>|
||<span data-ttu-id="e3a11-553">&emsp;&#x25fc; 도구를 사용할 수 없습니다. 예를 들어 맬웨어 방지 또는 이벤트 로깅</span><span class="sxs-lookup"><span data-stu-id="e3a11-553">&emsp;&#x25fc; Disabling of security tools; for example, Anti-Malware or event logging</span></span>|
||<span data-ttu-id="e3a11-554">&emsp;&#x25fc; 맬웨어 방지 로깅 예를 들어 업데이트, 맬웨어 검색, 검사 실패</span><span class="sxs-lookup"><span data-stu-id="e3a11-554">&emsp;&#x25fc; Anti-Malware logging; for example, updates, malware detection, scan failures</span></span>|
||<span data-ttu-id="e3a11-555">&emsp;&#x25fc; IDPS/WAF 이벤트(구성된 경우)</span><span class="sxs-lookup"><span data-stu-id="e3a11-555">&emsp;&#x25fc; IDPS/WAF events (if configured)</span></span>|
||<span data-ttu-id="e3a11-556">이벤트 **로그에는 다음** 정보가 포함되어야 합니다.</span><span class="sxs-lookup"><span data-stu-id="e3a11-556">­Event logs **MUST** include the following information:</span></span>|
||<span data-ttu-id="e3a11-557">&emsp;&#x25fc; 사용자 식별</span><span class="sxs-lookup"><span data-stu-id="e3a11-557">&emsp;&#x25fc; User Identification</span></span> |
||<span data-ttu-id="e3a11-558">&emsp;&#x25fc; 이벤트 유형입니다.</span><span class="sxs-lookup"><span data-stu-id="e3a11-558">&emsp;&#x25fc; Type of event</span></span> |
||<span data-ttu-id="e3a11-559">&emsp;&#x25fc; 날짜 및 시간</span><span class="sxs-lookup"><span data-stu-id="e3a11-559">&emsp;&#x25fc; Date and time</span></span> |
||<span data-ttu-id="e3a11-560">&emsp;&#x25fc;/실패 표시기</span><span class="sxs-lookup"><span data-stu-id="e3a11-560">&emsp;&#x25fc; Success/Failure indicator</span></span>|
||<span data-ttu-id="e3a11-561">&emsp;&#x25fc; 레이블을 사용하여 영향을 받는 시스템 식별</span><span class="sxs-lookup"><span data-stu-id="e3a11-561">&emsp;&#x25fc; Label to identify the affected system</span></span> |
||<span data-ttu-id="e3a11-562">포렌식  조사를 지원하려면 모든 범위 내 시스템 구성 요소에서 시간 동기화를 사용해야 합니다.</span><span class="sxs-lookup"><span data-stu-id="e3a11-562">­Time-synchronization **MUST** be used across all in-scope system components to aid in forensic investigations.</span></span>|
||<span data-ttu-id="e3a11-563">동일한 기본(필요한 경우 보조) 시간 원본을 활용하도록 시간 동기화를 구성해야 합니다. </span><span class="sxs-lookup"><span data-stu-id="e3a11-563">Time-synchronization **MUST** be configured to utilize the same primary (and secondary if required) time source</span></span>|
||<span data-ttu-id="e3a11-564">공용 시스템(DMZ 내의 **시스템)은** 내부 중앙 로깅 리포지토리에 로그를 작성해야 합니다.</span><span class="sxs-lookup"><span data-stu-id="e3a11-564">­Public facing systems (systems within the DMZ) **MUST** write logs to an internal centralized logging repository.</span></span> <span data-ttu-id="e3a11-565">중앙 로깅 리포지토리는 DMZ 내에 있지 않을 수 있습니다.</span><span class="sxs-lookup"><span data-stu-id="e3a11-565">The centralized logging repository must not be within the DMZ.</span></span>|
||<span data-ttu-id="e3a11-566">위협 **요소에** 의해 로그 데이터를 변경할 수 없는 경우 감사 내역을 보호해야 합니다.</span><span class="sxs-lookup"><span data-stu-id="e3a11-566">­ Audit trails **MUST** be secured to ensure log data cannot be altered by a threat actor.</span></span> <span data-ttu-id="e3a11-567">중앙 로깅 리포지토리에 대한 액세스는 권한이 부여된 직원으로만 제한되어야 합니다.</span><span class="sxs-lookup"><span data-stu-id="e3a11-567">Access to the centralized logging repository must be limited to authorized personnel only.</span></span>|
||<span data-ttu-id="e3a11-568">로그는  30일 동안 즉시 사용할 수 있어야 합니다.</span><span class="sxs-lookup"><span data-stu-id="e3a11-568">­ Logs **MUST** be immediately available for 30 days.</span></span> <span data-ttu-id="e3a11-569">로깅 데이터는 **최소** 90일 동안 보존해야 합니다.</span><span class="sxs-lookup"><span data-stu-id="e3a11-569">Logging data **MUST** be retained for a minimum of 90 days.</span></span>|
|<span data-ttu-id="e3a11-570">**검토**</span><span class="sxs-lookup"><span data-stu-id="e3a11-570">**Reviewing**</span></span> |<span data-ttu-id="e3a11-571">지원 정책 및 절차뿐만 아니라 프로세스를 검토하려면 **다음을** 충족해야 합니다.</span><span class="sxs-lookup"><span data-stu-id="e3a11-571">Review processes as well as supporting policies and procedures **MUST** meet the following:</span></span>|
||<span data-ttu-id="e3a11-572">&#x2713; 일별 로그 검토를 수행하거나 자동화된 로그 분석 및 경고 기술을 사용하여 모든 범위 내 시스템 구성 요소의 이벤트를 검토하여 잠재적인 보안 이벤트를 식별합니다.</span><span class="sxs-lookup"><span data-stu-id="e3a11-572">&#x2713; Perform daily log reviews or utilize automated log analysis and alerting technology to review events from all in-scope system components to identify any potential security events.</span></span>|
||<span data-ttu-id="e3a11-573">&#x2713; 보안 이벤트를  즉시 따라야 합니다.</span><span class="sxs-lookup"><span data-stu-id="e3a11-573">&#x2713; Potential security events **MUST** be immediately followed up.</span></span>|
|<span data-ttu-id="e3a11-574">**경고**</span><span class="sxs-lookup"><span data-stu-id="e3a11-574">**Alerting**</span></span> |<span data-ttu-id="e3a11-575">경고 프로세스 및 지원 정책 및 절차는 **다음을** 충족해야 합니다.</span><span class="sxs-lookup"><span data-stu-id="e3a11-575">Alerting processes as well as supporting policies and procedures **MUST** meet the following:</span></span> |
||<span data-ttu-id="e3a11-576">&#x2713;, 작업 또는 데이터의 보안에 위험을 유발하는 기록된 보안 이벤트는 전체 목록이 아닌 즉시 경고를 트리거해야 합니다.</span><span class="sxs-lookup"><span data-stu-id="e3a11-576">&#x2713; Logged security events that pose a risk to the security of your systems, operations or data MUST trigger an immediate alert, for example (not an exhaustive list):</span></span>|
||<span data-ttu-id="e3a11-577">&emsp;&#x25fc; 권한 계정 만들기/수정</span><span class="sxs-lookup"><span data-stu-id="e3a11-577">&emsp;&#x25fc; Privilege account creation / modifications</span></span>|
||<span data-ttu-id="e3a11-578">&emsp;&#x25fc; 맬웨어 이벤트 발생</span><span class="sxs-lookup"><span data-stu-id="e3a11-578">&emsp;&#x25fc; Malware events</span></span>|
||<span data-ttu-id="e3a11-579">&emsp;&#x25fc; 도구 사용 안 하게</span><span class="sxs-lookup"><span data-stu-id="e3a11-579">&emsp;&#x25fc; Disabling security tools</span></span>|
||<span data-ttu-id="e3a11-580">&emsp;&#x25fc; 로그 변조</span><span class="sxs-lookup"><span data-stu-id="e3a11-580">&emsp;&#x25fc; Event log tampering</span></span>|
||<span data-ttu-id="e3a11-581">&emsp;&#x25fc; IDPS/WAF 이벤트(구성된 경우)</span><span class="sxs-lookup"><span data-stu-id="e3a11-581">&emsp;&#x25fc; IDPS / WAF events (if configured)</span></span> |
||<span data-ttu-id="e3a11-582">&#x2713; 트리거된 경고에 대응하려면 항상 직원을 사용할 수 있어야 합니다(24/7).</span><span class="sxs-lookup"><span data-stu-id="e3a11-582">&#x2713; Staff MUST always be available (24/7) to react to triggered alerts.</span></span>|
|<span data-ttu-id="e3a11-583">**리스크 관리**</span><span class="sxs-lookup"><span data-stu-id="e3a11-583">**Risk management**</span></span>|<span data-ttu-id="e3a11-584">위험 평가 방법은 다음을 포함하는 개발 및 수행되어야 합니다.</span><span class="sxs-lookup"><span data-stu-id="e3a11-584">A risk-assessment methodology must be developed and conducted that includes the following:</span></span>|
||<span data-ttu-id="e3a11-585">&#x2713; 공식적으로 정의된 프로세스입니다.</span><span class="sxs-lookup"><span data-stu-id="e3a11-585">&#x2713; A formally defined process.</span></span>|
||<span data-ttu-id="e3a11-586">&#x2713; 적어도 매년 수행됩니다.</span><span class="sxs-lookup"><span data-stu-id="e3a11-586">&#x2713; Performed at least annually.</span></span>|
||<span data-ttu-id="e3a11-587">&#x2713; 범위 내 환경 내의 모든 자산을 포함합니다.</span><span class="sxs-lookup"><span data-stu-id="e3a11-587">&#x2713; Includes all assets within the in-scope environment.</span></span>|
||<span data-ttu-id="e3a11-588">&#x2713; 포함된 모든 자산에 대한 위협 및 취약성을 식별합니다.</span><span class="sxs-lookup"><span data-stu-id="e3a11-588">&#x2713; Identifies threats and vulnerabilities against all included assets.</span></span>|
||<span data-ttu-id="e3a11-589">&#x2713; 정의한 영향 및 가능성 열의 사용을 포함합니다.</span><span class="sxs-lookup"><span data-stu-id="e3a11-589">&#x2713; Includes the use of defined impact and likelihood matrices.</span></span>|
||<span data-ttu-id="e3a11-590">&#x2713; 결과로 위험 등록 및 해당 위험 처리 계획이 생성됩니다.</span><span class="sxs-lookup"><span data-stu-id="e3a11-590">&#x2713; Results in the creation of a risk register and corresponding risk treatment plan.</span></span>|
|<span data-ttu-id="e3a11-591">**사고 대응**</span><span class="sxs-lookup"><span data-stu-id="e3a11-591">**Incident response**</span></span>|<span data-ttu-id="e3a11-592">철저한 인시던트 대응 **계획이** **필요하며** 최소한 다음을 포함해야 합니다.</span><span class="sxs-lookup"><span data-stu-id="e3a11-592">A thorough incident response plan **IS** required and **MUST** include as a minimum:</span></span>|
||<span data-ttu-id="e3a11-593">&#x2713; 범위 내 시스템 구성 요소 및 응용 프로그램의 범위입니다.</span><span class="sxs-lookup"><span data-stu-id="e3a11-593">&#x2713; At a minimum, coverage of the in-scope systems components and applications.</span></span>|
||<span data-ttu-id="e3a11-594">&#x2713; 위협 모델에 대한 특정 인시던트 대응 절차를 제공합니다.</span><span class="sxs-lookup"><span data-stu-id="e3a11-594">&#x2713; Specific incident response procedures for expected threat models.</span></span>|
||<span data-ttu-id="e3a11-595">&#x2713; 문서화된 통신 프로세스를 통해 모든 주요 이해 관계자와 모든 관련 외부 기관에 시기적시에 알림을 하도록 합니다. 규정된 보고 요구 사항에 따라 결제 브랜드/인수자, 규제 기관 및[감독 기관(GDPR)입니다.](#gdpr)</span><span class="sxs-lookup"><span data-stu-id="e3a11-595">&#x2713; Documented communications process, ensuring the timely notification of all key stakeholders and any relevant external bodies such as; payment brands/acquirers, regulatory bodies and supervisory authorities ([GDPR](#gdpr)) in line with mandated reporting requirements.</span></span>|
||<span data-ttu-id="e3a11-596">&#x2713; 인시던트 대응은 학습된 교훈, 조직 변경 및 산업 개발 통합에 따라 업데이트됩니다.</span><span class="sxs-lookup"><span data-stu-id="e3a11-596">&#x2713; The incident response is updated based upon lessons learned, organizational changes and to incorporate industry developments.</span></span>|
||<span data-ttu-id="e3a11-597">&#x2713; 대응 팀 구성원을 위한 연간 교육입니다.</span><span class="sxs-lookup"><span data-stu-id="e3a11-597">&#x2713; Annual training for members of the incident response team.</span></span>|

## <a name="data-handling-security-and-privacy"></a><span data-ttu-id="e3a11-598">데이터 처리 보안 및 개인 정보</span><span class="sxs-lookup"><span data-stu-id="e3a11-598">Data Handling Security and Privacy</span></span>

<span data-ttu-id="e3a11-599">응용 프로그램 사용자, 중간 서비스 및 ISV 시스템 간에 전송되는 데이터는 최소 TLS v1.1을 지원하는 TLS 연결을 통해 암호화로 보호해야 합니다. *부록* [**A를 참조하세요.**](#appendix-a)</span><span class="sxs-lookup"><span data-stu-id="e3a11-599">Data in transit between the application user, intermediary services, and ISV’s systems will be required to be protected by encryption through a TLS connection supporting a minimum of TLS v1.1.*See* [**Appendix A**](#appendix-a).</span></span>

<span data-ttu-id="e3a11-600">응용 프로그램에서 M365 데이터를 검색하고 저장하는 경우 부록 B에 정의된 사양을 따르는 데이터 저장소 암호화 체계를 [**구현하는 데 필요합니다.**](#appendix-a)</span><span class="sxs-lookup"><span data-stu-id="e3a11-600">Where your application retrieves and stores M365 data you will be required to implement a data storage encryption scheme that follows the specification as defined in [**Appendix B**](#appendix-a).</span></span>

### <a name="test-specification"></a><span data-ttu-id="e3a11-601">테스트 사양</span><span class="sxs-lookup"><span data-stu-id="e3a11-601">Test Specification</span></span>

|<span data-ttu-id="e3a11-602">테스트</span><span class="sxs-lookup"><span data-stu-id="e3a11-602">Test</span></span> | <span data-ttu-id="e3a11-603">컨트롤</span><span class="sxs-lookup"><span data-stu-id="e3a11-603">Controls</span></span> |
| -----------------------|-------------------------------- |
|<span data-ttu-id="e3a11-604">**전송 중 데이터**</span><span class="sxs-lookup"><span data-stu-id="e3a11-604">**Data in Transit**</span></span>| <span data-ttu-id="e3a11-605">중요한 데이터의 전송은 부록 A에 설명된 몇 가지 예외를 제외하고 최소 TLS 1.1을 사용해야 합니다.</span><span class="sxs-lookup"><span data-stu-id="e3a11-605">Transmission of sensitive data MUST use a minimum of TLS 1.1 with a few exceptions described in Appendix A.</span></span>|
||<span data-ttu-id="e3a11-606">중요한 데이터의 **전송은** 부록 B에 설명된 암호화 프로필과 함께 적합하게 암호화되어야 합니다.</span><span class="sxs-lookup"><span data-stu-id="e3a11-606">Transmission of sensitive data **MUST** be suitably encrypted in line with encryption profiles described in Appendix B.</span></span>|
||<span data-ttu-id="e3a11-607">TLS 압축을 사용하지 않도록 설정해야 합니다.</span><span class="sxs-lookup"><span data-stu-id="e3a11-607">TLS compression must be disabled.</span></span>|
||<span data-ttu-id="e3a11-608">HSTS(HTTP Strict Transport  Security)는 15552000을 >구성해야 합니다.</span><span class="sxs-lookup"><span data-stu-id="e3a11-608">HSTS (HTTP Strict Transport Security) **MUST** be configured to >= 15552000</span></span>|
|<span data-ttu-id="e3a11-609">**미사시 데이터**</span><span class="sxs-lookup"><span data-stu-id="e3a11-609">**Data at Rest**</span></span>| <span data-ttu-id="e3a11-610">암호화,  알고리즘, 키 크기, 해시 및 메시지 인증의 최소 요구 사항을 다루는 부록 B에 설명된 암호화 프로필과 함께 중요한 데이터 저장소를 보호해야 합니다.</span><span class="sxs-lookup"><span data-stu-id="e3a11-610">Sensitive data storage **MUST** be protected in line with the encryption profiles described in Appendix B covering minimum requirements of encryption, algorithms, key sizes, hashing and message authentication.</span></span>|
||<span data-ttu-id="e3a11-611">저장된 모든 데이터 형식을 문서화해야 합니다.</span><span class="sxs-lookup"><span data-stu-id="e3a11-611">All stored data types MUST be documented.</span></span>|
|<span data-ttu-id="e3a11-612">**데이터 보존 및 삭제**</span><span class="sxs-lookup"><span data-stu-id="e3a11-612">**Data Retention and Disposal**</span></span>|<span data-ttu-id="e3a11-613">다음과 같은  데이터 보존 및 폐기 정책, 절차 및 프로세스를 구현하여 중요한 데이터 저장소를 최소한으로 유지해야 합니다.</span><span class="sxs-lookup"><span data-stu-id="e3a11-613">Sensitive data storage **MUST** be kept to a minimum by implementing data retention and disposal policies, procedures and processes that minimally include:</span></span>|
||<span data-ttu-id="e3a11-614">&#x2713;, 규정 및/또는 비즈니스 요구 사항에 필요한 데이터 저장소 양 및 보존 시간을 문서화하고 제한합니다.</span><span class="sxs-lookup"><span data-stu-id="e3a11-614">&#x2713; Document and limit data storage amount and retention time to that which is required for legal, regulatory, and/or business requirements.</span></span>|
||<span data-ttu-id="e3a11-615">&#x2713; 필요 없는 경우 문서화 정책을 사용하여 중요한 데이터를 안전하게 지우기 위한 프로세스를 문서화하고 배포할 수 있습니다.</span><span class="sxs-lookup"><span data-stu-id="e3a11-615">&#x2713; Document and deploy processes for secure deletion of sensitive data when no longer needed, in-line with documented policies.</span></span>|
||<span data-ttu-id="e3a11-616">&#x2713; 보존 기간을 초과하는 저장된 중요한 데이터를 식별하고 안전하게 삭제하기 위한 분기별 프로세스를 문서화하고 배포합니다.</span><span class="sxs-lookup"><span data-stu-id="e3a11-616">&#x2713; Document and deploy a quarterly process for identifying and securely deleting stored sensitive data that exceeds the defined retention period.</span></span>|
|<span data-ttu-id="e3a11-617">**데이터 액세스 관리**</span><span class="sxs-lookup"><span data-stu-id="e3a11-617">**Data Access Management**</span></span>|<span data-ttu-id="e3a11-618">합법적인 비즈니스 사유가 있는 사용자에 대한 데이터 액세스를 제한하면 조직에서 부적 절제 또는 유해를 통해 중요한 데이터를 잘못 처리하지 못하게 방지할 수 있습니다.</span><span class="sxs-lookup"><span data-stu-id="e3a11-618">Limiting data access to those with a legitimate business reason helps organizations prevent mishandling of sensitive data through inexperience or malice.</span></span> <span data-ttu-id="e3a11-619">앱/추가 기능에서 수신하고 암호화 키에 액세스하려면 액세스하기 위해 모든 액세스 수준에서 승인된 당사자에 대해 문서화된 승인(전자 또는 서면)이 필요하며, 정책을 설명하는 승인 및 확인된 권한 목록이 다음과 같이 지정된 요구 사항을 통합해야 합니다.</span><span class="sxs-lookup"><span data-stu-id="e3a11-619">Sensitive data, received by the app/add-in and access to encryption keys requires documented approval (electronic or in writing) for authorized parties at all access levels to access and must include a listing of approved and verified privileges demonstrating the policy incorporates the specified requirements as follows:</span></span> |
||<span data-ttu-id="e3a11-620">&#x2713; 권한 있는 액세스가 특별히 필요한 역할에만 액세스 요구 및 권한 할당 정의</span><span class="sxs-lookup"><span data-stu-id="e3a11-620">&#x2713; Defining access needs and privilege assignments only to roles that specifically require such privileged access.</span></span> |
||<span data-ttu-id="e3a11-621">&#x2713; 업무를 수행하는 데 필요한 최소 권한으로의 액세스를 제한합니다.</span><span class="sxs-lookup"><span data-stu-id="e3a11-621">&#x2713; Restricting access to the least privileges necessary to perform job responsibilities.</span></span>|
||<span data-ttu-id="e3a11-622">&#x2713; M365 데이터를 사용하는 모든 타사와 데이터 공유 계약이 설정되어 있도록 합니다.</span><span class="sxs-lookup"><span data-stu-id="e3a11-622">&#x2713; Ensure data sharing agreements are in place with all third-parties consuming M365 data.</span></span>|
|<span data-ttu-id="e3a11-623">**GDPR**</span><span class="sxs-lookup"><span data-stu-id="e3a11-623">**GDPR**</span></span>| <span data-ttu-id="e3a11-624">Microsoft 365 인증 프로세스의 일부로 다음을 통해 GDPR 준수를 입증해야 합니다.</span><span class="sxs-lookup"><span data-stu-id="e3a11-624">As part of the Microsoft 365 Certification process, you must demonstrate adherence to the GDPR, either by:</span></span>|
||<span data-ttu-id="e3a11-625">&#x2713; 숙련된 외부 감사 회사의 GDPR 적합성에 대한 독립적인 검토를 제공</span><span class="sxs-lookup"><span data-stu-id="e3a11-625">&#x2713; Providing an independent review of the GDPR conformance by an experienced external audit company.</span></span> <span data-ttu-id="e3a11-626">검토를 위해 보고서를 제출하거나 분석가가 보고서를 볼 수 있도록 허용해야 합니다.</span><span class="sxs-lookup"><span data-stu-id="e3a11-626">You will be required to submit the report for review or allow the analyst to view the report.</span></span> <span data-ttu-id="e3a11-627">보고서는 외부 감사자 평가의 유효성을 검사할 뿐만 아니라 외부 검토에서 GDPR의 준수를 확인한 충분한 신뢰도 제공해야 합니다.</span><span class="sxs-lookup"><span data-stu-id="e3a11-627">The report should provide enough details to not only validate the external auditor’s assessment but also provide enough confidence that the external review has confirmed conformance to the GDPR.</span></span>|
||<span data-ttu-id="e3a11-628">또는</span><span class="sxs-lookup"><span data-stu-id="e3a11-628">or</span></span>|
||<span data-ttu-id="e3a11-629">&#x2713; 다음과 같이 추가 증거를 제출하여 데이터 개인 정보 보호법에 대한 귀하의 약속을 추가로 보장합니다.</span><span class="sxs-lookup"><span data-stu-id="e3a11-629">&#x2713; Submitting further evidence to provide additional assurance of your commitment to data privacy laws, as follows:</span></span>|
||<span data-ttu-id="e3a11-630">&#x25fc; 고객의 요청을 충족하고 GDPR의 30일 요구 사항을 충족하도록 설계된 문서화된 SAR(주체 액세스 요청) 프로세스입니다.</span><span class="sxs-lookup"><span data-stu-id="e3a11-630">&#x25fc; A documented subject access request (SAR) process designed to meet the requests of customers and meet the thirty-day requirement of the GDPR.</span></span> <span data-ttu-id="e3a11-631">이러한 기간 내에 SAR이 수행되도록 적절한 데이터 검색 도구를 사용하는 것이 좋습니다.</span><span class="sxs-lookup"><span data-stu-id="e3a11-631">It is recommended that adequate data discovery tooling is in place to ensure a SAR is fulfilled within these time frames.</span></span> <span data-ttu-id="e3a11-632">**참고:** 이러한 도구가 사용되지 않는 경우 이러한 작동 방식에 대해 설명하고 프로세스가 모든 데이터 주체의 정보 검색을 보장하는 방법을 보여 주야 합니다.</span><span class="sxs-lookup"><span data-stu-id="e3a11-632">**Note** : Where these tools are not used, you will need to demonstrate how this works and demonstrate how the processes are able to guarantee discovery of all data subject’s information.</span></span>|
||<span data-ttu-id="e3a11-633">&#x25fc;개인 정보 취급 방침은 웹 사이트에 있어야 하며 다음 정보를 포함해야 합니다.</span><span class="sxs-lookup"><span data-stu-id="e3a11-633">&#x25fc;Privacy Notices must be present on the website and contain the following information:</span></span>
||
||<span data-ttu-id="e3a11-634">독립 GDPR 보고서를 사용할 수 없는 경우 M365 인증 평가의 일부로 다음을 검토해야 합니다.</span><span class="sxs-lookup"><span data-stu-id="e3a11-634">Where an independent GDPR report isn’t available, the following must be in place to be reviewed as part of the M365 Certification assessment:</span></span> |
||<span data-ttu-id="e3a11-635">&#x2713; 고객의 요청을 충족하고 GDPR의 30일 요구 사항을 충족하도록 설계된 문서화된 SAR(주체 액세스 요청) 프로세스입니다.</span><span class="sxs-lookup"><span data-stu-id="e3a11-635">&#x2713; A documented subject access request (SAR) process designed to meet the requests of customers and meet the thirty-day requirement of the GDPR.</span></span>  <span data-ttu-id="e3a11-636">이러한 도구가 사용되지 않는 이러한 기간 내에 SAR이 수행되도록 보장하기 위해 적절한 데이터 검색 도구를 사용하는 것이 좋습니다. 이러한 도구가 작동하는 방식과 프로세스가 모든 데이터 주체 정보의 검색을 보장하는 방법을 보여 주야 합니다.</span><span class="sxs-lookup"><span data-stu-id="e3a11-636">It is recommended that adequate data discovery tooling is in place to ensure a SAR is fulfilled within these time frames, where these tools aren't used, you will need to demonstrate how this works and demonstrate how the processes are able to guarantee discovery of all data subject’s information.</span></span>|
||<span data-ttu-id="e3a11-637">&#x2713; 개인 정보 취급 방침은 웹 사이트에 있어야 하며 다음 정보를 포함해야 합니다.</span><span class="sxs-lookup"><span data-stu-id="e3a11-637">&#x2713; Privacy Notices must be present on the website and contain the following information:</span></span>|
||<span data-ttu-id="e3a11-638">&emsp;&emsp;&#x25a1; 조직 연락처 세부 정보입니다.</span><span class="sxs-lookup"><span data-stu-id="e3a11-638">&emsp;&emsp;&#x25a1; Organizations contact details.</span></span>|
||<span data-ttu-id="e3a11-639">&emsp;&emsp;&#x25a1; 처리되는 개인 데이터의 유형입니다.</span><span class="sxs-lookup"><span data-stu-id="e3a11-639">&emsp;&emsp;&#x25a1; Type of personal data being processed.</span></span>|
||<span data-ttu-id="e3a11-640">&emsp;&emsp;&#x25a1; 개인 데이터 처리의 정당성(*제6조)입니다.*</span><span class="sxs-lookup"><span data-stu-id="e3a11-640">&emsp;&emsp;&#x25a1; Lawfulness of processing personal data (*Article 6*).</span></span>|
||<span data-ttu-id="e3a11-641">&emsp;&emsp;&#x25a1; 데이터 주체의 권리에 대한 세부 정보:</span><span class="sxs-lookup"><span data-stu-id="e3a11-641">&emsp;&emsp;&#x25a1; Details of data subject's rights:</span></span>|
||<span data-ttu-id="e3a11-642">&emsp;&emsp;&#x25a1; 알 수 있는 권리(*문서 13 및 14).*</span><span class="sxs-lookup"><span data-stu-id="e3a11-642">&emsp;&emsp;&#x25a1; Right to be informed (*Articles13 and 14*).</span></span>
||<span data-ttu-id="e3a11-643">&emsp;&emsp;&#x25a1; 주체의 *액세스권(제15조)입니다.*</span><span class="sxs-lookup"><span data-stu-id="e3a11-643">&emsp;&emsp;&#x25a1; Right of access by the data subject (*Article 15*).</span></span>|
||<span data-ttu-id="e3a11-644">&emsp;&emsp;&#x25a1; 정정권(*제16조)입니다.*</span><span class="sxs-lookup"><span data-stu-id="e3a11-644">&emsp;&emsp;&#x25a1; Right of rectification (*Article 16*).</span></span>|
||<span data-ttu-id="e3a11-645">&emsp;&emsp;&#x25a1;*삭제권(제17조)입니다.*</span><span class="sxs-lookup"><span data-stu-id="e3a11-645">&emsp;&emsp;&#x25a1; Right to erasure (*Article 17*).</span></span>|
||<span data-ttu-id="e3a11-646">&emsp;&emsp;&#x25a1; 처리 *제한권(제18조)입니다.*</span><span class="sxs-lookup"><span data-stu-id="e3a11-646">&emsp;&emsp;&#x25a1; Right to restriction of processing (*Article 18*).</span></span>|
||<span data-ttu-id="e3a11-647">&emsp;&emsp;&#x25a1; 이식성에 대한 권리(*제20조)*</span><span class="sxs-lookup"><span data-stu-id="e3a11-647">&emsp;&emsp;&#x25a1; Right to data portability (*Article 20*).</span></span>|
||<span data-ttu-id="e3a11-648">&emsp;&emsp;&#x25a1; 권리(*제21조)입니다.*</span><span class="sxs-lookup"><span data-stu-id="e3a11-648">&emsp;&emsp;&#x25a1; Right to object (*Article 21*).</span></span>|
||<span data-ttu-id="e3a11-649">&emsp;&emsp;&#x25a1; 프로파일링을 포함한 자동화된 의사 결정과 관련한 권리(*제22조)*</span><span class="sxs-lookup"><span data-stu-id="e3a11-649">&emsp;&emsp;&#x25a1; Rights in relation to automated decision-marking, including profiling (*Article 22*).</span></span>|
||<span data-ttu-id="e3a11-650">&#x2713; 정보 공유는 데이터 주체의 데이터 처리가 데이터 개인 정보 보호법을 준수하도록 보장하기 위한 계약이 있어야 합니다.</span><span class="sxs-lookup"><span data-stu-id="e3a11-650">&#x2713; Information sharing with third-parties must have agreements in place to ensure processing of data subject’s data are in line with data privacy laws.</span></span>|

## <a name="optional-external-compliance-frameworks-review"></a><span data-ttu-id="e3a11-651">선택적 외부 준수 프레임워크 검토</span><span class="sxs-lookup"><span data-stu-id="e3a11-651">Optional External Compliance Frameworks Review</span></span>

<span data-ttu-id="e3a11-652">외부 보안 프레임워크가 게시자 증명 내에 포함된 경우 인증 분석가가 Microsoft 365 인증 평가의 일부로 해당 보안 준수 프레임워크의 유효성을 검사해야 합니다.</span><span class="sxs-lookup"><span data-stu-id="e3a11-652">If external security frameworks have been included within the Publisher Attestation, certification analysts will need to check the validity of those security compliance frameworks as part of the Microsoft 365 Certification assessment.</span></span>
<span data-ttu-id="e3a11-653">지원되는 다음과 같은 외부 보안 준수 프레임워크에 대한 증거는 다음과 같습니다.</span><span class="sxs-lookup"><span data-stu-id="e3a11-653">Evidence for the following supported external security compliance frameworks include:</span></span>

* <span data-ttu-id="e3a11-654">[ISMS](#isms) /  [IEC](#iec) - IS0/IEC 27001 사양</span><span class="sxs-lookup"><span data-stu-id="e3a11-654">[ISMS](#isms)/ [IEC](#iec) - IS0/IEC 27001 specification</span></span></h5>
* [<span data-ttu-id="e3a11-655">PCI DSS</span><span class="sxs-lookup"><span data-stu-id="e3a11-655">PCI DSS</span></span>](#pci-dss)
* [<span data-ttu-id="e3a11-656">SOC 2</span><span class="sxs-lookup"><span data-stu-id="e3a11-656">SOC 2</span></span>](#soc-2)

<span data-ttu-id="e3a11-657">준수 증거 [섹션에서 식별된](#compliance-evidence) 설명서는 이 검토를 수행하는 데 사용됩니다.</span><span class="sxs-lookup"><span data-stu-id="e3a11-657">Documentation identified within the [Compliance Evidence](#compliance-evidence) section will be used to perform this review.</span></span>

### <a name="test-specifications"></a><span data-ttu-id="e3a11-658">테스트 사양</span><span class="sxs-lookup"><span data-stu-id="e3a11-658">Test Specifications</span></span>

<span data-ttu-id="e3a11-659">&#x2713; 앱/추가 기능 지원 환경  및 모든 지원  비즈니스 프로세스는 지원되는 외부 보안 준수 프레임워크의 범위 내에 포함되어야 합니다. 제공된 설명서에 명확하게 표시되어야 합니다.</span><span class="sxs-lookup"><span data-stu-id="e3a11-659">&#x2713; The App/Add-in supporting environment **AND** any supporting business processes **MUST** be included within the scope of any supported external security compliance frameworks and must be clearly indicated in supplied documentation.</span></span>

<span data-ttu-id="e3a11-660">&#x2713; 지원되는 외부 보안 준수  프레임워크는 현재(예: 지난 12개월 이내 또는 재평가가 현재 수행되고 증거를 제공될 수 있는 경우 15개월 이내)에 있어야 합니다.</span><span class="sxs-lookup"><span data-stu-id="e3a11-660">&#x2713; Supported external security compliance frameworks **MUST** be current, i.e. within the past 12 months (or within 15months if the re-assessment is currently being carried out and evidence can be provided).</span></span>

<span data-ttu-id="e3a11-661">&#x2713; 지원되는 외부 보안 준수  프레임워크는 독립적인 공인 회사에서 수행되어야 합니다.</span><span class="sxs-lookup"><span data-stu-id="e3a11-661">&#x2713; Supported external security compliance frameworks **MUST** be carried out by an independent accredited company.</span></span>

## <a name="appendix-a"></a><span data-ttu-id="e3a11-662">부록 A</span><span class="sxs-lookup"><span data-stu-id="e3a11-662">Appendix A</span></span>

### <a name="tls-profile-configuration-requirements"></a><span data-ttu-id="e3a11-663">TLS 프로필 구성 요구 사항</span><span class="sxs-lookup"><span data-stu-id="e3a11-663">TLS Profile configuration requirements</span></span>

<span data-ttu-id="e3a11-664">가상 네트워크, 클라우드 서비스 또는 데이터 센터 내에서 모든 네트워크 트래픽은 최소 TLS v1.1(TLS v1.2+권장) 또는 기타 적용 가능한 프로토콜로 보호해야 합니다.</span><span class="sxs-lookup"><span data-stu-id="e3a11-664">All network traffic, whether within a virtual network, cloud service, or a data center, must be protected with a minimum of TLS v1.1 (TLS v1.2+ is recommended) or other applicable protocol.</span></span> <span data-ttu-id="e3a11-665">이 요구 사항은 예외입니다.</span><span class="sxs-lookup"><span data-stu-id="e3a11-665">Exceptions to this requirement are:</span></span>

* <span data-ttu-id="e3a11-666">**HTTP-HTTPS 리디렉션**.</span><span class="sxs-lookup"><span data-stu-id="e3a11-666">**HTTP-to-HTTPS redirect**.</span></span> <span data-ttu-id="e3a11-667">앱은 HTTP를 통해 응답하여 클라이언트를 HTTPS로 리디렉션할 수 있지만 응답에 중요한 데이터(쿠키, 헤더, 콘텐츠)가 포함되어 있지는 않습니다.</span><span class="sxs-lookup"><span data-stu-id="e3a11-667">Your app can respond over HTTP to redirect clients to HTTPS, but the response must not contain any sensitive data (cookies, headers, content).</span></span> <span data-ttu-id="e3a11-668">HTTPS로 리디렉션하고 상태 프로브에 응답하는 것 외의 다른 HTTP 응답은 허용되지 않습니다.</span><span class="sxs-lookup"><span data-stu-id="e3a11-668">No other HTTP responses other than redirects to HTTPS and responding to health probes are allowed.</span></span> <span data-ttu-id="e3a11-669">아래를 참조하세요.</span><span class="sxs-lookup"><span data-stu-id="e3a11-669">See below.</span></span>
* <span data-ttu-id="e3a11-670">**상태 프로브.**</span><span class="sxs-lookup"><span data-stu-id="e3a11-670">**Health probes**.</span></span> <span data-ttu-id="e3a11-671">앱은 검사자에서 **HTTPS** 상태 프로브가 지원되지 않는 경우 HTTP를 통해 상태 프로브에 응답할 수 있습니다.</span><span class="sxs-lookup"><span data-stu-id="e3a11-671">Your app can respond to health probes over HTTP **only if** HTTPS health probes are not supported by the checking party.</span></span>
* <span data-ttu-id="e3a11-672">**인증서 액세스**.</span><span class="sxs-lookup"><span data-stu-id="e3a11-672">**Certificate access**.</span></span> <span data-ttu-id="e3a11-673">HTTP를 통해 인증서 유효성 검사 및 해지 확인을 위해 CRL, OCSP 및 AIA 끝점에 액세스할 수 있습니다.</span><span class="sxs-lookup"><span data-stu-id="e3a11-673">Access to CRL, OCSP, and AIA endpoints for the purposes of certificate validation and revocation checking is allowed over HTTP.</span></span>
* <span data-ttu-id="e3a11-674">**로컬 통신**.</span><span class="sxs-lookup"><span data-stu-id="e3a11-674">**Local communications**.</span></span> <span data-ttu-id="e3a11-675">앱은 운영 체제를 떠나지 않는 통신에 HTTP(또는 보호되지 않는 기타 프로토콜)를 사용할 수 있습니다.</span><span class="sxs-lookup"><span data-stu-id="e3a11-675">Your app can use HTTP (or other non-protected protocols) for communications that do not leave the operating system, e.</span></span> <span data-ttu-id="e3a11-676">g.</span><span class="sxs-lookup"><span data-stu-id="e3a11-676">g.</span></span> <span data-ttu-id="e3a11-677">localhost에 노출된 웹 서버 끝점에 연결합니다.</span><span class="sxs-lookup"><span data-stu-id="e3a11-677">connecting to a web server endpoint exposed on localhost.</span></span>

<span data-ttu-id="e3a11-678">TLS **압축을 사용하지** 않도록 설정해야 합니다.</span><span class="sxs-lookup"><span data-stu-id="e3a11-678">TLS Compression **MUST** be disabled.</span></span>

## <a name="appendix-b"></a><span data-ttu-id="e3a11-679">부록 B</span><span class="sxs-lookup"><span data-stu-id="e3a11-679">Appendix B</span></span>

### <a name="encryption-profile-configuration-requirements"></a><span data-ttu-id="e3a11-680">암호화 프로필 구성 요구 사항</span><span class="sxs-lookup"><span data-stu-id="e3a11-680">Encryption Profile Configuration Requirements</span></span>

<span data-ttu-id="e3a11-681">다음과 같이 암호화 기본 및 매개 변수만 허용됩니다.</span><span class="sxs-lookup"><span data-stu-id="e3a11-681">Only cryptographic primitives and parameters are permitted as follows:</span></span>

### <a name="symmetric-cryptography"></a><span data-ttu-id="e3a11-682">대칭형 암호화</span><span class="sxs-lookup"><span data-stu-id="e3a11-682">Symmetric cryptography</span></span>

<span data-ttu-id="e3a11-683">**Encryption**</span><span class="sxs-lookup"><span data-stu-id="e3a11-683">**Encryption**</span></span>

<span data-ttu-id="e3a11-684">&emsp;&#x2713; AES, BitLocker, 피싱 또는 TDES만 허용됩니다.</span><span class="sxs-lookup"><span data-stu-id="e3a11-684">&emsp;&#x2713; Only AES, BitLocker, Blowfish or TDES are allowed.</span></span> <span data-ttu-id="e3a11-685">지원되는 키 길이는 >=128(128, 192 및 256비트)으로 허용됩니다(256비트 키 권장).</span><span class="sxs-lookup"><span data-stu-id="e3a11-685">Any of the supported key lengths >=128 are allowed (128, 192, and 256 bits) and may be used (256-bit keys are recommended).</span></span>

<span data-ttu-id="e3a11-686">&emsp;&#x2713; CBC 모드만 허용됩니다.</span><span class="sxs-lookup"><span data-stu-id="e3a11-686">&emsp;&#x2713; Only CBC mode is allowed.</span></span> <span data-ttu-id="e3a11-687">모든 암호화 작업은 임의로 생성된 새로운 IV(초기화 벡터)를 사용해야 합니다.</span><span class="sxs-lookup"><span data-stu-id="e3a11-687">Every encryption operation must use a fresh, randomly generated initialization vector (IV).</span></span>

<span data-ttu-id="e3a11-688">&emsp;&#x2713; RC4와 같은 스트림 암호의 사용은 **허용되지** 않습니다.</span><span class="sxs-lookup"><span data-stu-id="e3a11-688">&emsp;&#x2713; Use of stream ciphers, such as RC4, **IS NOT** allowed.</span></span>

<span data-ttu-id="e3a11-689">**해시 함수**</span><span class="sxs-lookup"><span data-stu-id="e3a11-689">**Hash functions**</span></span>

<span data-ttu-id="e3a11-690">&emsp;&#x2713; 모든 새 코드는 SHA-256, SHA-384 또는 SHA-512(총칭 SHA-2)를 사용해야 합니다.</span><span class="sxs-lookup"><span data-stu-id="e3a11-690">&emsp;&#x2713; All new code must use SHA-256, SHA-384, or SHA-512 (collectively referred to as SHA-2).</span></span> <span data-ttu-id="e3a11-691">출력이 128비트 미만으로 줄어들 수 있습니다.</span><span class="sxs-lookup"><span data-stu-id="e3a11-691">Output may be truncated to no less than 128 bits</span></span>

<span data-ttu-id="e3a11-692">&emsp;&#x2713; 이유로만 SHA-1을 사용할 수 있습니다.</span><span class="sxs-lookup"><span data-stu-id="e3a11-692">&emsp;&#x2713; SHA-1 may only be used for compatibility reasons.</span></span>

<span data-ttu-id="e3a11-693">&emsp;&#x2713; 암호화되지 않은 응용 프로그램에도 MD5, MD4, MD2 및 기타 해시 함수를 사용할 수 없습니다.</span><span class="sxs-lookup"><span data-stu-id="e3a11-693">&emsp;&#x2713; Use of MD5, MD4, MD2 and other hash functions IS NOT allowed, even for non-cryptographic applications.</span></span>

<span data-ttu-id="e3a11-694">**메시지 인증**</span><span class="sxs-lookup"><span data-stu-id="e3a11-694">**Message authentication**</span></span>

<span data-ttu-id="e3a11-695">&emsp;&#x2713; 모든 새 코드는 승인된 해시 함수 중 하나와 함께 HMAC를 사용해야 합니다.</span><span class="sxs-lookup"><span data-stu-id="e3a11-695">&emsp;&#x2713; All new code MUST use HMAC with one of the approved hash functions.</span></span> <span data-ttu-id="e3a11-696">HMAC의 출력은 128비트 미만으로 줄어들 수 있습니다.</span><span class="sxs-lookup"><span data-stu-id="e3a11-696">Output of HMAC may be truncated to no less than 128 bits.</span></span>

<span data-ttu-id="e3a11-697">&emsp;&#x2713; HMAC-SHA1은 호환성을 위해만 사용할 수 있습니다.</span><span class="sxs-lookup"><span data-stu-id="e3a11-697">&emsp;&#x2713; HMAC-SHA1 may only be used for compatibility reasons.</span></span>

<span data-ttu-id="e3a11-698">&emsp;&#x2713; HMAC 키는 128비트 이상 있어야 합니다.</span><span class="sxs-lookup"><span data-stu-id="e3a11-698">&emsp;&#x2713; HMAC key MUST be at least 128 bits.</span></span> <span data-ttu-id="e3a11-699">256비트 키를 사용하는 것이 좋습니다.</span><span class="sxs-lookup"><span data-stu-id="e3a11-699">256-bit keys are recommended.</span></span>

### <a name="asymmetric-algorithms"></a><span data-ttu-id="e3a11-700">비대칭 알고리즘</span><span class="sxs-lookup"><span data-stu-id="e3a11-700">Asymmetric algorithms</span></span>

<span data-ttu-id="e3a11-701">**Encryption**</span><span class="sxs-lookup"><span data-stu-id="e3a11-701">**Encryption**</span></span>

<span data-ttu-id="e3a11-702">&emsp;&#x2713; RSA를 사용할 수 있습니다.</span><span class="sxs-lookup"><span data-stu-id="e3a11-702">&emsp;&#x2713; RSA is allowed.</span></span> <span data-ttu-id="e3a11-703">**키는** 2048비트 이상이면 OAEP 패딩을 사용해야 합니다.</span><span class="sxs-lookup"><span data-stu-id="e3a11-703">Key **MUST** be at least 2048 bits and OAEP padding must be used.</span></span> <span data-ttu-id="e3a11-704">PKCS 패딩은 호환성을 위해만 허용됩니다.</span><span class="sxs-lookup"><span data-stu-id="e3a11-704">Use of PKCS padding only allowed for compatibility reasons.</span></span>

<span data-ttu-id="e3a11-705">**서명**</span><span class="sxs-lookup"><span data-stu-id="e3a11-705">**Signatures**</span></span>

<span data-ttu-id="e3a11-706">&emsp;&#x2713; RSA를 사용할 수 있습니다.</span><span class="sxs-lookup"><span data-stu-id="e3a11-706">&emsp;&#x2713; RSA is allowed.</span></span> <span data-ttu-id="e3a11-707">**키는** 2048비트 이상 및 PSS 패딩을 사용해야 합니다.</span><span class="sxs-lookup"><span data-stu-id="e3a11-707">Key **MUST** be at least 2048 bits and PSS padding must be used.</span></span> <span data-ttu-id="e3a11-708">PKCS 패딩은 호환성을 위해만 허용됩니다.</span><span class="sxs-lookup"><span data-stu-id="e3a11-708">Use of PKCS padding only allowed for compatibility reasons.</span></span>

<span data-ttu-id="e3a11-709">&emsp;&#x2713;ECDSA를 사용할 수 있습니다.</span><span class="sxs-lookup"><span data-stu-id="e3a11-709">&emsp;&#x2713;ECDSA is allowed.</span></span> <span data-ttu-id="e3a11-710">**키는** 256비트 이상 있어야 합니다.</span><span class="sxs-lookup"><span data-stu-id="e3a11-710">Key **MUST** be at least 256 bits.</span></span> <span data-ttu-id="e3a11-711">NIST P-256, P-384 또는 P-521 곡선을 사용해야 합니다.</span><span class="sxs-lookup"><span data-stu-id="e3a11-711">NIST P-256, P-384 or P-521 curve must be used.</span></span>

<span data-ttu-id="e3a11-712">**키 Exchange**</span><span class="sxs-lookup"><span data-stu-id="e3a11-712">**Key Exchange**</span></span>

<span data-ttu-id="e3a11-713">&emsp;&#x2713; ECDH를 사용할 수 있습니다.</span><span class="sxs-lookup"><span data-stu-id="e3a11-713">&emsp;&#x2713; ECDH is allowed.</span></span> <span data-ttu-id="e3a11-714">**키는** 256비트 이상 있어야 합니다.</span><span class="sxs-lookup"><span data-stu-id="e3a11-714">Key **MUST** be at least 256 bits.</span></span> <span data-ttu-id="e3a11-715">NIST P-256, P-384 또는 P-521 곡선을 사용해야 합니다.</span><span class="sxs-lookup"><span data-stu-id="e3a11-715">NIST P-256, P-384 or P-521 curve must be used.</span></span>

<span data-ttu-id="e3a11-716">&emsp;&#x2713; ECDH를 사용할 수 있습니다.</span><span class="sxs-lookup"><span data-stu-id="e3a11-716">&emsp;&#x2713; ECDH is allowed.</span></span> <span data-ttu-id="e3a11-717">**키는** 256비트 이상 있어야 합니다.</span><span class="sxs-lookup"><span data-stu-id="e3a11-717">Key **MUST** be at least 256 bits.</span></span> <span data-ttu-id="e3a11-718">NIST P-256, P-384 또는 P-521 곡선을 사용해야 합니다.</span><span class="sxs-lookup"><span data-stu-id="e3a11-718">NIST P-256, P-384 or P-521 curve must be used.</span></span>

## <a name="appendix-c"></a><span data-ttu-id="e3a11-719">부록 C</span><span class="sxs-lookup"><span data-stu-id="e3a11-719">Appendix C</span></span>

### <a name="evidence-collection--delta-for-iso-27001"></a><span data-ttu-id="e3a11-720">Evidence 컬렉션 - ISO 27001 델타</span><span class="sxs-lookup"><span data-stu-id="e3a11-720">Evidence Collection – Delta for ISO 27001</span></span>

<span data-ttu-id="e3a11-721">이미 ISO27001 규정 준수를 획득한 경우 ISO 27001에서 다루지 않는 다음 델타의(간격)는 적어도 이 Microsoft 365 인증의 일부로 검토해야 합니다.</span><span class="sxs-lookup"><span data-stu-id="e3a11-721">Where you have already attained ISO27001 compliance, the following delta’s (gaps) not wholly covered by ISO 27001 will, at a minimum, need to be reviewed as part of this Microsoft 365 Certification.</span></span>

> [!NOTE]
> <span data-ttu-id="e3a11-722">Microsoft 365 인증 평가의 일부로 인증 분석가가 매핑된 ISO 27001 컨트롤이 ISO 27001 평가의 일부로 포함되지 않은지 여부를 결정하고 추가 보증을 제공하기 위해 포함된 것으로 확인된 샘플 컨트롤도 결정할 수 있습니다.</span><span class="sxs-lookup"><span data-stu-id="e3a11-722">As part of your Microsoft 365 Certification assessment, the certification analyst will determine if any of the mapped ISO 27001 controls were not included as part of the ISO 27001 assessment and may also decide to sample controls that were found to be included to provide further assurance.</span></span> <span data-ttu-id="e3a11-723">ISO 27001에서 누락된 요구 사항은 Microsoft 365 인증 평가 활동에 포함되어야 합니다.</span><span class="sxs-lookup"><span data-stu-id="e3a11-723">Any requirements missing from the ISO 27001 will need to be included within your Microsoft 365 Certification assessment activities.</span></span>

<span data-ttu-id="e3a11-724">**맬웨어 보호 - 바이러스 백신**</span><span class="sxs-lookup"><span data-stu-id="e3a11-724">**Malware Protection – Anti Virus**</span></span>

<span data-ttu-id="e3a11-725">응용 프로그램 제어를 사용하여 맬웨어 보호가 적용 중이고 ISO 27001 내에서 맬웨어 보호가 것으로 조사된 경우 추가 조사가 필요하지 않습니다.</span><span class="sxs-lookup"><span data-stu-id="e3a11-725">If malware protection is in place using application control and is attested to within ISO 27001 Report no further investigation is necessary.</span></span> <span data-ttu-id="e3a11-726">응용 프로그램 제어가 없는 경우 인증 분석가가 환경 내에서 맬웨어가 발견되지 않도록 응용 프로그램 제어 메커니즘의 증거를 식별하고 평가해야 합니다.</span><span class="sxs-lookup"><span data-stu-id="e3a11-726">If no application control is in place, certification analysts will need to identify and assess evidence of application control mechanisms to prevent detonation of malware within the environment.</span></span> <span data-ttu-id="e3a11-727">이렇게 하면 다음이 필요할 수 있습니다.</span><span class="sxs-lookup"><span data-stu-id="e3a11-727">This will require you to:</span></span>

* <span data-ttu-id="e3a11-728">샘플링된 모든 시스템 구성 요소에서 바이러스 백신 소프트웨어가 실행되고 있는 것을 보여줄 수 있습니다.</span><span class="sxs-lookup"><span data-stu-id="e3a11-728">Demonstrate that anti-virus software is running across all sampled system components.</span></span>

* <span data-ttu-id="e3a11-729">바이러스 백신이 맬웨어를 자동으로 차단하거나, 경고를 차단하거나, 경고를 & 샘플링된 모든 시스템 구성 요소에 걸쳐 구성되어 있는지 보여 주도록 합니다.</span><span class="sxs-lookup"><span data-stu-id="e3a11-729">Demonstrate that anti-virus is configured across all sampled system components to either automatically block malware, to quarantine & alert or to alert.</span></span>

* <span data-ttu-id="e3a11-730">바이러스 백신 **소프트웨어는** 모든 활동을 기록하도록 구성해야 합니다.</span><span class="sxs-lookup"><span data-stu-id="e3a11-730">Anti-virus software **MUST** be configured to log all activities.</span></span>

<span data-ttu-id="e3a11-731">**패치 관리 - 패치**</span><span class="sxs-lookup"><span data-stu-id="e3a11-731">**Patch Management – Patching**</span></span>

<span data-ttu-id="e3a11-732">ISO 27001 감사에서는 이 범주를 구체적으로 평가하지 않는 경우 다음을 요구합니다.</span><span class="sxs-lookup"><span data-stu-id="e3a11-732">As ISO 27001 audits do not specifically assess this category, this will require you to:</span></span>

* <span data-ttu-id="e3a11-733">공급업체에서 더 이상 지원하지 않는  소프트웨어 구성 요소 및 운영 체제는 환경 내에서 사용되지 말아야 합니다.</span><span class="sxs-lookup"><span data-stu-id="e3a11-733">Software components and operating systems no longer supported by the vendor **MUST** not be used within the environment.</span></span> <span data-ttu-id="e3a11-734">지원 정책이 있어야 지원되지 않는 소프트웨어 구성 요소/운영 체제가 환경에서 제거되고 소프트웨어 구성 요소가 수명 종료될 때를 식별하는 프로세스가 있어야 합니다.</span><span class="sxs-lookup"><span data-stu-id="e3a11-734">Supporting policies MUST be in place to ensure unsupported software components / operating systems will be removed from the environment and a process to identify when software components go end-of-life must be in place</span></span>

<span data-ttu-id="e3a11-735">**취약점 검사**</span><span class="sxs-lookup"><span data-stu-id="e3a11-735">**Vulnerability Scanning**</span></span>  

<span data-ttu-id="e3a11-736">ISO 27001 감사에서는 이 범주를 구체적으로 평가하지 않는 경우 다음을 요구합니다.</span><span class="sxs-lookup"><span data-stu-id="e3a11-736">As ISO 27001 audits do not specifically assess this category, this will require you to:</span></span>

* <span data-ttu-id="e3a11-737">분기별 내부 및 외부 취약점 검사가 수행됩니다.</span><span class="sxs-lookup"><span data-stu-id="e3a11-737">Demonstrate that quarterly internal and external vulnerability scanning is conducted.</span></span>

* <span data-ttu-id="e3a11-738">다음과 같이 위험 순위에 따라 사양에 따라 취약점 수정을 위한 지원 설명서가 준비되어 있는지 확인</span><span class="sxs-lookup"><span data-stu-id="e3a11-738">Confirm supporting documentation is in place for vulnerability remediation based on risk ranking and in line with the specification as follows:</span></span>
 
 <span data-ttu-id="e3a11-739">&#x2713; 내부 검사에 대한 위험 순위와 함께 위험 및 높은 위험 문제를 모두 수정합니다.</span><span class="sxs-lookup"><span data-stu-id="e3a11-739">&#x2713; Fix all Critical and Highs risk issues in-line with the risk ranking for Internal scanning.</span></span>
 
 <span data-ttu-id="e3a11-740">&#x2713; 위험, 높은 위험 및 중간 위험 문제를 외부 검사에 대한 위험 순위와 함께 수정합니다.</span><span class="sxs-lookup"><span data-stu-id="e3a11-740">&#x2713; Fix all Critical, Highs and Medium risk issues in-line with the risk ranking for external scanning.</span></span>
 
 <span data-ttu-id="e3a11-741">&#x2713; 문서화한 취약점 수정 정책에 따라 수정이 수행되는 것을 보여 줄 수 있습니다.</span><span class="sxs-lookup"><span data-stu-id="e3a11-741">&#x2713; Demonstrate that remediation is conducted in-line with the documented vulnerability remediation policy.</span></span>

<span data-ttu-id="e3a11-742">**방화벽 - 방화벽(또는 동등한 기술)**</span><span class="sxs-lookup"><span data-stu-id="e3a11-742">**Firewall – Firewalls (or equivalent technologies)**</span></span>

<span data-ttu-id="e3a11-743">ISO 27001 감사에서는 이 범주를 구체적으로 평가하지 않는 경우 다음을 요구합니다.</span><span class="sxs-lookup"><span data-stu-id="e3a11-743">As ISO 27001 audits do not specifically assess this category, this will require you to:</span></span>

* <span data-ttu-id="e3a11-744">방화벽이 범위 내 환경의 경계에 설치되어 있는 것을 보여 줍니다.</span><span class="sxs-lookup"><span data-stu-id="e3a11-744">Demonstrate that firewalls are installed on the boundary of the in-scope environment.</span></span>

* <span data-ttu-id="e3a11-745">방화벽이 DMZ와 신뢰할 수 있는 네트워크 사이에 설치되어 있는 것을 보여 주시습니다.</span><span class="sxs-lookup"><span data-stu-id="e3a11-745">Demonstrate that firewalls are installed between the DMZ and trusted networks.</span></span>

*   <span data-ttu-id="e3a11-746">모든 공용 액세스가 DMZ에서 종료됩니다.</span><span class="sxs-lookup"><span data-stu-id="e3a11-746">Demonstrate that all public access terminates in the DMZ.</span></span>

*   <span data-ttu-id="e3a11-747">기본 관리 자격 증명이 라이브 환경에 설치하기 전에 변경된 경우를 보여 줍니다.</span><span class="sxs-lookup"><span data-stu-id="e3a11-747">Demonstrate that default administrative credentials are changed prior to installation into the live environment.</span></span>

*   <span data-ttu-id="e3a11-748">방화벽을 통해 허용된 모든 트래픽이 인증 프로세스를 통과하여 비즈니스 사당성에 따라 모든 트래픽에 대한 설명서를 작성하는 것을 입증합니다.</span><span class="sxs-lookup"><span data-stu-id="e3a11-748">Demonstrate that all permitted traffic through the firewall(s) goes through an authorization process which results in the documentation of all traffic with a business justification.</span></span>

*   <span data-ttu-id="e3a11-749">모든 방화벽이 명시적으로 정의되지 않은 트래픽을 떨어뜨리도록 구성되어 있는지를 보여줄 수 있습니다.</span><span class="sxs-lookup"><span data-stu-id="e3a11-749">Demonstrate that all firewalls are configured to drop traffic not explicitly defined.</span></span>

*   <span data-ttu-id="e3a11-750">방화벽이 콘솔이 아닌 모든 관리 인터페이스에서 강력한 암호화만 지원하고 있습니다.</span><span class="sxs-lookup"><span data-stu-id="e3a11-750">Demonstrate that firewalls support only strong cryptography on all non-console administrative interfaces.</span></span>

*   <span data-ttu-id="e3a11-751">인터넷에 노출되는 방화벽의 콘솔이 아닌 관리 인터페이스가 MFA를 지원하는지 보여줄 수 있습니다.</span><span class="sxs-lookup"><span data-stu-id="e3a11-751">Demonstrate that firewall's non-console administrative interfaces exposed to the Internet support MFA.</span></span>

*   <span data-ttu-id="e3a11-752">방화벽 규칙 검토가 적어도 6개월마다 수행됩니다.</span><span class="sxs-lookup"><span data-stu-id="e3a11-752">Demonstrate that firewall rule reviews are conducted at least every 6 months</span></span>

<span data-ttu-id="e3a11-753">**방화벽 - WAF(웹 응용 프로그램 방화벽)**</span><span class="sxs-lookup"><span data-stu-id="e3a11-753">**Firewall – Web Application Firewalls (WAF)**</span></span>  

<span data-ttu-id="e3a11-754">WAF가 배포되어 응용 프로그램이 노출될 수 있는 다양한 웹 응용 프로그램 위협 및 취약성으로부터 보호할 수 있는 추가 크레딧이 제공됩니다.</span><span class="sxs-lookup"><span data-stu-id="e3a11-754">Additional credit will be provided if a WAF is deployed to help protect against the myriad of web application threats and vulnerabilities that the application can be exposed to.</span></span> <span data-ttu-id="e3a11-755">WAF 또는 유사 WAF가 있는 경우 다음을 요구합니다.</span><span class="sxs-lookup"><span data-stu-id="e3a11-755">When a WAF or similar is present, this will require you to:</span></span>

* <span data-ttu-id="e3a11-756">WAF가 경고를 통해 활성 방어 모드 또는 더 많은 모니터링으로 구성되어 있는지를 보여줄 수 있습니다.</span><span class="sxs-lookup"><span data-stu-id="e3a11-756">Demonstrate the WAF is configured in active defense mode or monitoring more with alerting.</span></span>

* <span data-ttu-id="e3a11-757">WAF가 SSL 오프로드를 지원하도록 구성되어 있는지 보여줄 수 있습니다.</span><span class="sxs-lookup"><span data-stu-id="e3a11-757">Demonstrate the WAF is configured to support SSL Offloading.</span></span>

* <span data-ttu-id="e3a11-758">다음과 같은 대부분의 공격 유형으로부터 보호하기 위해 OWASP 핵심 규칙 집합(3.0 또는 3.1)에 따라 구성됩니다.</span><span class="sxs-lookup"><span data-stu-id="e3a11-758">Is configured as per the OWASP Core Rule Set (3.0 or 3.1) to protect against most of the following attack types:</span></span>

<span data-ttu-id="e3a11-759">&#x2713; 및 인코딩 문제를 해결합니다.</span><span class="sxs-lookup"><span data-stu-id="e3a11-759">&#x2713; Protocol and encoding issues.</span></span>

<span data-ttu-id="e3a11-760">&#x2713;, 요청 밀기 및 응답 분할을 요청합니다.</span><span class="sxs-lookup"><span data-stu-id="e3a11-760">&#x2713; Header injection, request smuggling, and response splitting.</span></span>

<span data-ttu-id="e3a11-761">&#x2713; 경로 트래버스 공격을 공격합니다.</span><span class="sxs-lookup"><span data-stu-id="e3a11-761">&#x2713; File and path traversal attacks.</span></span>

<span data-ttu-id="e3a11-762">&#x2713; RFI(원격 파일 포함) 공격을 제어합니다.</span><span class="sxs-lookup"><span data-stu-id="e3a11-762">&#x2713; Remote file inclusion (RFI) attacks.</span></span>

<span data-ttu-id="e3a11-763">&#x2713; 코드 실행 공격을 중지합니다.</span><span class="sxs-lookup"><span data-stu-id="e3a11-763">&#x2713; Remote code execution attacks.</span></span>

<span data-ttu-id="e3a11-764">&#x2713; PHP 주입 공격이 있습니다.</span><span class="sxs-lookup"><span data-stu-id="e3a11-764">&#x2713; PHP-injection attacks.</span></span>

<span data-ttu-id="e3a11-765">&#x2713; 스크립팅 공격을 수정합니다.</span><span class="sxs-lookup"><span data-stu-id="e3a11-765">&#x2713; Cross-site scripting attacks.</span></span>

<span data-ttu-id="e3a11-766">&#x2713; SQL 주입 공격.</span><span class="sxs-lookup"><span data-stu-id="e3a11-766">&#x2713; SQL-injection attacks.</span></span>

<span data-ttu-id="e3a11-767">&#x2713; 세션 수정 공격을 해결합니다.</span><span class="sxs-lookup"><span data-stu-id="e3a11-767">&#x2713; Session-fixation attacks.</span></span>

<span data-ttu-id="e3a11-768">**변경 컨트롤**</span><span class="sxs-lookup"><span data-stu-id="e3a11-768">**Change Control**</span></span>

<span data-ttu-id="e3a11-769">ISO 27001 감사는 변경 요청 프로세스의 일부 요소를 구체적으로 평가하지 않는 경우 다음을 요구합니다.</span><span class="sxs-lookup"><span data-stu-id="e3a11-769">As ISO 27001 audits do not specifically assess some elements of Change Request processes, this will require you to:</span></span>

* <span data-ttu-id="e3a11-770">변경 요청에 대한 자세한 내용은 다음과 같습니다.</span><span class="sxs-lookup"><span data-stu-id="e3a11-770">Demonstrate that change requests have the following details:</span></span>

<span data-ttu-id="e3a11-771">&#x2713; 영향</span><span class="sxs-lookup"><span data-stu-id="e3a11-771">&#x2713; Documented impact.</span></span>

<span data-ttu-id="e3a11-772">&#x2713; 테스트할 기능의 세부 정보입니다.</span><span class="sxs-lookup"><span data-stu-id="e3a11-772">&#x2713; Details of what functionality testing is to be conducted.</span></span>

<span data-ttu-id="e3a11-773">&#x2713; 절차에 대한 세부 정보입니다.</span><span class="sxs-lookup"><span data-stu-id="e3a11-773">&#x2713; Details of any back-out procedures.</span></span>

* <span data-ttu-id="e3a11-774">기능 테스트는 변경이 완료된 후에 수행됩니다.</span><span class="sxs-lookup"><span data-stu-id="e3a11-774">Demonstrate that functionality testing is conducted after changes are completed.</span></span>

* <span data-ttu-id="e3a11-775">기능 테스트가 수행된 후 변경 요청이 서명된 경우를 보여 집니다.</span><span class="sxs-lookup"><span data-stu-id="e3a11-775">Demonstrate that change requests are signed off after functionality testing is conducted.</span></span>

<span data-ttu-id="e3a11-776">**계정 관리**</span><span class="sxs-lookup"><span data-stu-id="e3a11-776">**Account Management**</span></span>

<span data-ttu-id="e3a11-777">ISO 27001 감사는 계정 관리 프로세스의 일부 요소를 구체적으로 평가하지 않는 경우 다음을 요구합니다.</span><span class="sxs-lookup"><span data-stu-id="e3a11-777">As ISO 27001 audits do not specifically assess some elements of account management processes, this will require you to:</span></span>

*   <span data-ttu-id="e3a11-778">재생 공격을 &#x2713;(예: MFA, Kerberos)를 구현하는 방법을 보여줄 수 있습니다.</span><span class="sxs-lookup"><span data-stu-id="e3a11-778">Demonstrate how &#x2713;s are implemented to mitigate replay attacks (e.g. MFA, Kerberos).</span></span>
*   <span data-ttu-id="e3a11-779">3개월 동안 사용되지 않은 계정을 사용하지 않도록 설정하거나 삭제하는 방법을 보여줄 수 있습니다.</span><span class="sxs-lookup"><span data-stu-id="e3a11-779">Demonstrate how accounts that have not been used in 3 months are either disabled or deleted.</span></span>
*   <span data-ttu-id="e3a11-780">&#x2713; 또는 기타 적절한 완화는 사용자 자격 증명을 보호하도록 구성해야 합니다.</span><span class="sxs-lookup"><span data-stu-id="e3a11-780">&#x2713;  or other suitable mitigations must be configured to protect user credentials.</span></span> <span data-ttu-id="e3a11-781">다음과 같은 최소 암호 정책을 지침으로 사용해야 합니다.</span><span class="sxs-lookup"><span data-stu-id="e3a11-781">The following minimum password policy should be used as a guideline:</span></span>

<span data-ttu-id="e3a11-782">&#x2713; 최소 암호 길이는 8자입니다.</span><span class="sxs-lookup"><span data-stu-id="e3a11-782">&#x2713; Minimum password length of 8 characters.</span></span>

<span data-ttu-id="e3a11-783">&#x2713; 계정 잠금 임계값은 10회를 넘지 않습니다.</span><span class="sxs-lookup"><span data-stu-id="e3a11-783">&#x2713; Account lockout threshold of no more than 10 attempts.</span></span>
 
<span data-ttu-id="e3a11-784">&#x2713; 암호의 최소 5개 암호 기록입니다.</span><span class="sxs-lookup"><span data-stu-id="e3a11-784">&#x2713; Password history of a minimum of five passwords.</span></span>
 
<span data-ttu-id="e3a11-785">&#x2713; 강력한 암호의 사용을 적용합니다.</span><span class="sxs-lookup"><span data-stu-id="e3a11-785">&#x2713; Enforcement of the use of strong passwords.</span></span>
 
*   <span data-ttu-id="e3a11-786">모든 원격 액세스 솔루션에 대해 MFA가 구성되어 있는지 보여 주십시오.</span><span class="sxs-lookup"><span data-stu-id="e3a11-786">Demonstrate that MFA is configured for all remote access solutions.</span></span>

*   <span data-ttu-id="e3a11-787">모든 원격 액세스 솔루션에 강력한 암호화가 구성되어 있는지 보여 주십시오.</span><span class="sxs-lookup"><span data-stu-id="e3a11-787">Demonstrate that strong encryption is configured on all remote access solutions.</span></span>

*   <span data-ttu-id="e3a11-788">공용 DNS 관리가 범위 내 환경 외부에 있는 경우 DNS를 수정할 수 있는 모든 사용자 계정은 MFA를 사용하도록 구성해야 합니다.</span><span class="sxs-lookup"><span data-stu-id="e3a11-788">Where the management of Public DNS is outside of the in-scope environment, all user accounts able to make DNS modifications MUST be configured to use MFA.</span></span>

<span data-ttu-id="e3a11-789">**침입 감지 및 방지(OPTIONAL)**</span><span class="sxs-lookup"><span data-stu-id="e3a11-789">**Intrusion Detection and Prevention (OPTIONAL)**</span></span>

<span data-ttu-id="e3a11-790">ISO 27001 감사에서는 IDPS(침입 감지 및 방지 서비스) 프로세스의 일부 요소를 구체적으로 평가하지 않는 경우 다음을 요구합니다.</span><span class="sxs-lookup"><span data-stu-id="e3a11-790">As ISO 27001 audits do not specifically assess some elements of Intrusion Detection and Prevention Services (IDPS) processes, this will require you to:</span></span>

*   <span data-ttu-id="e3a11-791">**IDPS는** 지원 환경의 경계에 배포해야 합니다.</span><span class="sxs-lookup"><span data-stu-id="e3a11-791">IDPS **SHOULD** be deployed at the perimeter of the supporting environment.</span></span>

*   <span data-ttu-id="e3a11-792">IDPS **서명은** 지난 날 내에 최신으로 유지해야 합니다.</span><span class="sxs-lookup"><span data-stu-id="e3a11-792">IDPS signatures **SHOULD** be kept current, within the past day.</span></span>

*   <span data-ttu-id="e3a11-793">TLS  검사를 위해 IDPS를 구성해야 합니다.</span><span class="sxs-lookup"><span data-stu-id="e3a11-793">IDPS **SHOULD** be configured for TLS inspection.</span></span>

*   <span data-ttu-id="e3a11-794">모든 **인바운드** 및 아웃바운드 트래픽에 대해 IDPS를 구성해야 합니다.</span><span class="sxs-lookup"><span data-stu-id="e3a11-794">IDPS **SHOULD** be configured for ALL inbound and outbound traffic.</span></span>

*   <span data-ttu-id="e3a11-795">경고를  위해 IDPS를 구성해야 합니다.</span><span class="sxs-lookup"><span data-stu-id="e3a11-795">IDPS **SHOULD** be configured for alerting.</span></span>

<span data-ttu-id="e3a11-796">**이벤트 로깅**</span><span class="sxs-lookup"><span data-stu-id="e3a11-796">**Event Logging**</span></span>

<span data-ttu-id="e3a11-797">ISO 27001 감사는 보안 이벤트 로깅 프로세스의 일부 요소를 구체적으로 평가하지 않는 경우 다음을 요구합니다.</span><span class="sxs-lookup"><span data-stu-id="e3a11-797">As ISO 27001 audits do not specifically assess some elements of security event logging processes, this will require you to:</span></span>

* <span data-ttu-id="e3a11-798">공용 시스템이 DMZ 내에 없는 중앙 로깅 솔루션에 로깅하는지 보여 주십시오.</span><span class="sxs-lookup"><span data-stu-id="e3a11-798">Demonstrate that public facing systems are logging to a centralized logging solution which isn't within the DMZ.</span></span>

* <span data-ttu-id="e3a11-799">최소 30일 동안의 로깅 데이터를 즉시 사용할 수 있는 방법을 보여 주며 90일이 보존됩니다.</span><span class="sxs-lookup"><span data-stu-id="e3a11-799">Demonstrate how a minimum of 30 days’ worth of logging data is immediately available, with 90 days being retained.</span></span>

<span data-ttu-id="e3a11-800">**검토(로깅 데이터)**</span><span class="sxs-lookup"><span data-stu-id="e3a11-800">**Reviewing (Logging Data)**</span></span>

<span data-ttu-id="e3a11-801">ISO 27001 감사는 이 범주의 일부 요소를 구체적으로 평가하지 않는 경우 다음을 요구합니다.</span><span class="sxs-lookup"><span data-stu-id="e3a11-801">As ISO 27001 audits do not specifically assess some elements of this category, this will require you to:</span></span>

*   <span data-ttu-id="e3a11-802">일별 로그 검토가 수행되는 방식과 예외 및 예외가 어떻게 처리되는지 보여줄 수 있습니다.</span><span class="sxs-lookup"><span data-stu-id="e3a11-802">Demonstrate how daily log reviews are conducted and how exceptions and anomalies are identified showing how these are handled.</span></span>

<span data-ttu-id="e3a11-803">**경고**</span><span class="sxs-lookup"><span data-stu-id="e3a11-803">**Alerting**</span></span>

<span data-ttu-id="e3a11-804">ISO 27001 감사는 이 범주의 일부 요소를 구체적으로 평가하지 않는 경우 다음을 요구합니다.</span><span class="sxs-lookup"><span data-stu-id="e3a11-804">As ISO 27001 audits do not specifically assess some elements of this category, this will require you to:</span></span>

* <span data-ttu-id="e3a11-805">즉각적인 경시를 위해 경고를 트리거하도록 보안 이벤트가 구성된 방법을 보여줄 수 있습니다.</span><span class="sxs-lookup"><span data-stu-id="e3a11-805">Demonstrate how security events are configured to trigger alerts for immediate triage.</span></span>

* <span data-ttu-id="e3a11-806">직원이 보안 경고에 응답하기 위해 24/7을 사용할 수 있는 방법을 보여줄 수 있습니다.</span><span class="sxs-lookup"><span data-stu-id="e3a11-806">Demonstrate how staff are available 24/7 to respond to security alerts.</span></span>

<span data-ttu-id="e3a11-807">**위험 관리**</span><span class="sxs-lookup"><span data-stu-id="e3a11-807">**Risk Management**</span></span>

<span data-ttu-id="e3a11-808">ISO 27001 감사는 위험 평가 프로세스의 일부 요소를 구체적으로 평가하지 않는 경우 다음을 요구합니다.</span><span class="sxs-lookup"><span data-stu-id="e3a11-808">As ISO 27001 audits do not specifically assess some elements of risk assessment processes, this will require you to:</span></span>

* <span data-ttu-id="e3a11-809">공식적인 위험 관리 프로세스가 설정되었다는 설명</span><span class="sxs-lookup"><span data-stu-id="e3a11-809">Demonstrate that a formal risk management process is established.</span></span>

<span data-ttu-id="e3a11-810">**인시던트 대응**</span><span class="sxs-lookup"><span data-stu-id="e3a11-810">**Incident Response**</span></span>

<span data-ttu-id="e3a11-811">ISO 27001 감사는 인시던트 대응 정책 및 프로세스의 일부 요소를 구체적으로 평가하지 않는 경우 다음을 요구합니다.</span><span class="sxs-lookup"><span data-stu-id="e3a11-811">As ISO 27001 audits do not specifically assess some elements of incident response policies and processes, this will require you to:</span></span>

*   <span data-ttu-id="e3a11-812">인시던트 대응 계획/절차에 다음이 포함됩니다.</span><span class="sxs-lookup"><span data-stu-id="e3a11-812">Demonstrate that the incident response plan/procedure includes:</span></span>

<span data-ttu-id="e3a11-813">&#x2713; 위협 모델에 대한 특정 응답 절차입니다.</span><span class="sxs-lookup"><span data-stu-id="e3a11-813">&#x2713; Specific response procedures for expected threat models.</span></span>

<span data-ttu-id="e3a11-814">&#x2713;(식별, 보호, 감지, 대응, 복구)에 맞춰진 인시던트 처리 기능을 제공합니다.</span><span class="sxs-lookup"><span data-stu-id="e3a11-814">&#x2713; Incident handling capabilities aligning to NIST Cybersecurity Framework (Identify, Protect, Detect, Respond, Recover).</span></span>
 
<span data-ttu-id="e3a11-815">&#x2713; 범위 내 시스템을 다루는 IRP입니다.</span><span class="sxs-lookup"><span data-stu-id="e3a11-815">&#x2713; The IRP covers the in-scope systems.</span></span>
 
<span data-ttu-id="e3a11-816">&#x2713; 대응 팀을 위한 연례 교육을 실시합니다.</span><span class="sxs-lookup"><span data-stu-id="e3a11-816">&#x2713; Annual training for the incident response team.</span></span>

## <a name="appendix-d"></a><span data-ttu-id="e3a11-817">부록 D</span><span class="sxs-lookup"><span data-stu-id="e3a11-817">Appendix D</span></span>

### <a name="evidence-collection--deltas-for-pci-dss"></a><span data-ttu-id="e3a11-818">증거 컬렉션 - PCI DSS용 델타</span><span class="sxs-lookup"><span data-stu-id="e3a11-818">Evidence Collection – Deltas for PCI DSS</span></span>

<span data-ttu-id="e3a11-819">PCI DSS 규정 준수를 이미 획득한 경우 PCI DSS에서 다루지 않는 다음 델타의 (간격)는 최소한 이 Microsoft 365 인증의 일부로 검토해야 합니다.</span><span class="sxs-lookup"><span data-stu-id="e3a11-819">Where you have already attained PCI DSS compliance, the following delta’s (gaps) not wholly covered by PCI DSS will, at a minimum, need to be reviewed as part of this Microsoft 365 Certification.</span></span>

> [!NOTE]
> <span data-ttu-id="e3a11-820">Microsoft 365 인증 평가의 일부로 인증 분석가가 매핑된 PCI DSS 컨트롤이 PCI DSS 평가의 일부로 포함되지 않은지 여부를 결정하고 추가 보증을 제공하기 위해 포함된 것으로 확인된 샘플 컨트롤도 결정할 수 있습니다.</span><span class="sxs-lookup"><span data-stu-id="e3a11-820">As part of the Microsoft 365 Certification assessment, the certification analyst will determine if any of the mapped PCI DSS controls were not included as part of the PCI DSS assessment and may also decide to sample controls that were found to be included to provide further assurance.</span></span> <span data-ttu-id="e3a11-821">PCI DSS에서 누락된 요구 사항은 Microsoft 365 인증 평가 활동에 포함해야 합니다.</span><span class="sxs-lookup"><span data-stu-id="e3a11-821">Any requirements missing from the PCI DSS will need to be included into the Microsoft 365 Certification assessment activities.</span></span>

<span data-ttu-id="e3a11-822">**맬웨어 보호 - 응용 프로그램 제어**</span><span class="sxs-lookup"><span data-stu-id="e3a11-822">**Malware Protection - Application Control**</span></span>

<span data-ttu-id="e3a11-823">바이러스 백신을 사용하여 맬웨어 보호가 진행 중이고 PCI DSS 보고서 내에서 맬웨어가 것으로 조사된 경우 추가 조사가 필요하지 않습니다.</span><span class="sxs-lookup"><span data-stu-id="e3a11-823">If malware protection is in place through use of anti-virus and is attested to within PCI DSS Report no further investigation is necessary.</span></span> <span data-ttu-id="e3a11-824">바이러스 백신이 없는 경우 인증 분석가가 환경 내에서 맬웨어가 발견되지 않도록 응용 프로그램 제어 메커니즘의 증거를 식별하고 평가해야 합니다.</span><span class="sxs-lookup"><span data-stu-id="e3a11-824">If no anti-virus is in place, certification analysts will need to identify and assess evidence of application control mechanisms to prevent detonation of malware within the environment.</span></span> <span data-ttu-id="e3a11-825">이렇게 하면 다음이 필요할 수 있습니다.</span><span class="sxs-lookup"><span data-stu-id="e3a11-825">This will require you to:</span></span> 

*   <span data-ttu-id="e3a11-826">응용 프로그램 승인이 수행된 방법을 보여 주며 이 작업을 완료하는지 확인할 수 있습니다.</span><span class="sxs-lookup"><span data-stu-id="e3a11-826">Demonstrate how the application approval is conducted and confirm that this is completed.</span></span>

*   <span data-ttu-id="e3a11-827">비즈니스 사정이 있는 승인된 응용 프로그램의 전체 목록이 존재할 수 있습니다.</span><span class="sxs-lookup"><span data-stu-id="e3a11-827">Demonstrate that a complete list of approved applications with business justification exists.</span></span>

*   <span data-ttu-id="e3a11-828">특정 응용 프로그램 제어 메커니즘(예: 화이트리스트, 코드 서명 등)을 충족하도록 응용 프로그램 제어 소프트웨어를 구성하는 방법을 자세히 설명하는 지원 설명서를 제공하거나 설명하는 문서가 제공됩니다.</span><span class="sxs-lookup"><span data-stu-id="e3a11-828">Provide or demonstrate supporting documentation is in place detailing how application control software is configured to meet specific application control mechanisms (i.e. whitelisting, code signing, etc.).</span></span>

*   <span data-ttu-id="e3a11-829">모든 샘플링된 시스템 구성 요소에서 응용 프로그램 제어가 문서화된 것으로 구성되어 있는지 보여 주도록 합니다.</span><span class="sxs-lookup"><span data-stu-id="e3a11-829">Demonstrate that across all sampled system components, application control is configured as documented.</span></span>

<span data-ttu-id="e3a11-830">**패치 관리 - 위험 순위**</span><span class="sxs-lookup"><span data-stu-id="e3a11-830">**Patch Management – Risk Ranking**</span></span>

<span data-ttu-id="e3a11-831">PCI DSS 감사는 이 범주를 구체적으로 평가하지 않는 경우 다음을 요구합니다.</span><span class="sxs-lookup"><span data-stu-id="e3a11-831">As PCI DSS audits do not specifically assess this category, this will require you to:</span></span>

* <span data-ttu-id="e3a11-832">취약성의 위험 순위가 수행된 방법을 보여줄 수 있습니다.</span><span class="sxs-lookup"><span data-stu-id="e3a11-832">Demonstrate how risk ranking of vulnerabilities is conducted.</span></span>

<span data-ttu-id="e3a11-833">**취약점 검사**</span><span class="sxs-lookup"><span data-stu-id="e3a11-833">**Vulnerability Scanning**</span></span>

<span data-ttu-id="e3a11-834">PCI DSS 감사는 이 범주를 구체적으로 평가하지 않는 경우 다음을 요구합니다.</span><span class="sxs-lookup"><span data-stu-id="e3a11-834">As PCI DSS audits do not specifically assess this category, this will require you to:</span></span>

* <span data-ttu-id="e3a11-835">문서화한 취약점 수정 정책에 따라 수정이 수행됩니다.</span><span class="sxs-lookup"><span data-stu-id="e3a11-835">Demonstrate that remediation is conducted in-line with the documented vulnerability remediation policy.</span></span>

<span data-ttu-id="e3a11-836">**방화벽 - 방화벽(또는 동등한 기술)**</span><span class="sxs-lookup"><span data-stu-id="e3a11-836">**Firewall – Firewalls (or equivalent technologies)**</span></span>

<span data-ttu-id="e3a11-837">PCI DSS 감사는 이 범주를 구체적으로 평가하지 않는 경우 다음을 요구합니다.</span><span class="sxs-lookup"><span data-stu-id="e3a11-837">As PCI DSS audits do not specifically assess this category, this will require you to:</span></span>

* <span data-ttu-id="e3a11-838">방화벽이 콘솔이 아닌 모든 관리 인터페이스에서 강력한 암호화만 지원하고 있습니다.</span><span class="sxs-lookup"><span data-stu-id="e3a11-838">Demonstrate that firewalls support only strong cryptography on all non-console administrative interfaces.</span></span>

* <span data-ttu-id="e3a11-839">인터넷에 노출되는 방화벽의 콘솔이 아닌 관리 인터페이스가 MFA를 지원하는지 보여줄 수 있습니다.</span><span class="sxs-lookup"><span data-stu-id="e3a11-839">Demonstrate that firewall's non-console administrative interfaces exposed to the Internet support MFA.</span></span>

<span data-ttu-id="e3a11-840">응용 프로그램이 노출될 수 있는 다양한 웹 응용 프로그램 위협 및 취약성으로부터 보호하기 위해 WAF(웹 응용 프로그램 방화벽)를 배포한 경우 추가 크레딧이 제공됩니다.</span><span class="sxs-lookup"><span data-stu-id="e3a11-840">Additional credit will be provided if a Web Application Firewall (WAF) s deployed to help protect against the myriad of web application threats and vulnerabilities that the application can be exposed to.</span></span> <span data-ttu-id="e3a11-841">WAF 또는 유사 WAF가 있는 경우 다음을 요구합니다.</span><span class="sxs-lookup"><span data-stu-id="e3a11-841">When a WAF or similar is present, this will require you to:</span></span>

* <span data-ttu-id="e3a11-842">WAF가 경고를 통해 활성 방어 모드 또는 더 많은 모니터링으로 구성되어 있는지를 보여줄 수 있습니다.</span><span class="sxs-lookup"><span data-stu-id="e3a11-842">Demonstrate the WAF is configured in active defense mode or monitoring more with alerting.</span></span>

* <span data-ttu-id="e3a11-843">WAF가 SSL 오프로드를 지원하도록 구성되어 있는지 보여 집니다.</span><span class="sxs-lookup"><span data-stu-id="e3a11-843">Demonstrate the WAF is configured to support SSL offloading.</span></span>

* <span data-ttu-id="e3a11-844">다음과 같은 대부분의 공격 유형으로부터 보호하기 위해 OWASP 핵심 규칙 집합(3.0 또는 3.1)에 따라 구성됩니다.</span><span class="sxs-lookup"><span data-stu-id="e3a11-844">Is configured as per the OWASP Core Rule Set (3.0 or 3.1) to protect against most of the following attack types:</span></span>

<span data-ttu-id="e3a11-845">&#x2713; 및 인코딩 문제를 해결합니다.</span><span class="sxs-lookup"><span data-stu-id="e3a11-845">&#x2713; Protocol and encoding issues.</span></span>

<span data-ttu-id="e3a11-846">&#x2713;, 요청 밀기 및 응답 분할을 요청합니다.</span><span class="sxs-lookup"><span data-stu-id="e3a11-846">&#x2713; Header injection, request smuggling, and response splitting.</span></span>

<span data-ttu-id="e3a11-847">&#x2713; 경로 트래버스 공격을 공격합니다.</span><span class="sxs-lookup"><span data-stu-id="e3a11-847">&#x2713; File and path traversal attacks.</span></span>

<span data-ttu-id="e3a11-848">&#x2713; RFI(원격 파일 포함) 공격을 제어합니다.</span><span class="sxs-lookup"><span data-stu-id="e3a11-848">&#x2713; Remote file inclusion (RFI) attacks.</span></span>

<span data-ttu-id="e3a11-849">&#x2713; 코드 실행 공격을 중지합니다.</span><span class="sxs-lookup"><span data-stu-id="e3a11-849">&#x2713; Remote code execution attacks.</span></span>

<span data-ttu-id="e3a11-850">&#x2713; PHP 주입 공격이 있습니다.</span><span class="sxs-lookup"><span data-stu-id="e3a11-850">&#x2713; PHP-injection attacks.</span></span>

<span data-ttu-id="e3a11-851">&#x2713; 스크립팅 공격을 수정합니다.</span><span class="sxs-lookup"><span data-stu-id="e3a11-851">&#x2713; Cross-site scripting attacks.</span></span>

<span data-ttu-id="e3a11-852">&#x2713; SQL 주입 공격.</span><span class="sxs-lookup"><span data-stu-id="e3a11-852">&#x2713; SQL-injection attacks.</span></span>

<span data-ttu-id="e3a11-853">&#x2713; 세션 수정 공격을 해결합니다.</span><span class="sxs-lookup"><span data-stu-id="e3a11-853">&#x2713; Session-fixation attacks.</span></span>

<span data-ttu-id="e3a11-854">**변경 컨트롤**</span><span class="sxs-lookup"><span data-stu-id="e3a11-854">**Change Control**</span></span>

<span data-ttu-id="e3a11-855">PCI DSS 감사는 변경 요청 프로세스의 일부 요소를 구체적으로 평가하지 않는 경우 다음을 요구합니다.</span><span class="sxs-lookup"><span data-stu-id="e3a11-855">As PCI DSS audits do not specifically assess some elements of Change Request processes, this will require you to:</span></span>

* <span data-ttu-id="e3a11-856">프로덕션 환경에서 변경 요청이 발생하기 전에 발생되는 것을 보여 주십시오.</span><span class="sxs-lookup"><span data-stu-id="e3a11-856">Demonstrate that change requests are raised before being made in production environments.</span></span>

* <span data-ttu-id="e3a11-857">프로덕션으로 이전하기 전에 변경 내용이 권한이 부여된 것을 보여줄 수 있습니다.</span><span class="sxs-lookup"><span data-stu-id="e3a11-857">Demonstrate that changes are authorized before going into production.</span></span>

* <span data-ttu-id="e3a11-858">기능 테스트는 변경이 완료된 후에 수행됩니다.</span><span class="sxs-lookup"><span data-stu-id="e3a11-858">Demonstrate that functionality testing is conducted after changes are completed.</span></span>

* <span data-ttu-id="e3a11-859">기능 테스트가 수행된 후 변경 요청이 서명된 경우를 보여 집니다.</span><span class="sxs-lookup"><span data-stu-id="e3a11-859">Demonstrate that change requests are signed off after functionality testing is conducted.</span></span>

<span data-ttu-id="e3a11-860">**보안 소프트웨어 개발/배포**</span><span class="sxs-lookup"><span data-stu-id="e3a11-860">**Secure Software Development/Deployment**</span></span>

<span data-ttu-id="e3a11-861">PCI DSS 감사는 보안 소프트웨어 개발 및 배포 프로세스의 일부 요소에 특별히 액세스하지 않습니다. 이렇게 하면 다음이 요구될 수 있습니다.</span><span class="sxs-lookup"><span data-stu-id="e3a11-861">As PCI DSS audits do not specifically access some elements of secure software development and deployment processes; this will require to you:</span></span>

* <span data-ttu-id="e3a11-862">코드 리포지토리는 MFA로 보호해야 합니다.</span><span class="sxs-lookup"><span data-stu-id="e3a11-862">Code repositories MUST be secured by MFA.</span></span>

*   <span data-ttu-id="e3a11-863">악성 코드 수정으로부터 코드 리포지토리를 보호하려면 적절한 액세스 제어가 있어야 합니다.</span><span class="sxs-lookup"><span data-stu-id="e3a11-863">Adequate access controls MUST be in place to protect code repositories against malicious code modifications.</span></span>

<span data-ttu-id="e3a11-864">**계정 관리**</span><span class="sxs-lookup"><span data-stu-id="e3a11-864">**Account Management**</span></span>

<span data-ttu-id="e3a11-865">PCI DSS 감사는 계정 관리 프로세스의 일부 요소를 구체적으로 평가하지 않는 경우 다음을 요구합니다.</span><span class="sxs-lookup"><span data-stu-id="e3a11-865">As PCI DSS audits do not specifically assess some elements of account management processes, this will require you to:</span></span>

* <span data-ttu-id="e3a11-866">재생 공격(예: MFA, Kerberos)을 완화하기 위해 인증 메커니즘을 구현하는 방법을 보여줄 수 있습니다.</span><span class="sxs-lookup"><span data-stu-id="e3a11-866">Demonstrate how the authorization mechanisms are implemented to mitigate replay attacks (e.g. MFA, Kerberos).</span></span>

* <span data-ttu-id="e3a11-867">강력한 암호 정책 또는 기타 적절한 완화는 사용자 자격 증명을 보호하도록 구성해야 합니다.</span><span class="sxs-lookup"><span data-stu-id="e3a11-867">Strong password policies or other suitable mitigations must be configured to protect user credentials.</span></span> <span data-ttu-id="e3a11-868">다음과 같은 최소 암호 정책을 지침으로 사용해야 합니다.</span><span class="sxs-lookup"><span data-stu-id="e3a11-868">The following minimum password policy should be used as a guideline:</span></span> 

<span data-ttu-id="e3a11-869">&#x2713; 최소 암호 길이는 8자입니다.</span><span class="sxs-lookup"><span data-stu-id="e3a11-869">&#x2713; Minimum password length of 8 characters.</span></span>

<span data-ttu-id="e3a11-870">&#x2713; 계정 잠금 임계값은 10회를 넘지 않습니다.</span><span class="sxs-lookup"><span data-stu-id="e3a11-870">&#x2713; Account lockout threshold of no more than 10 attempts.</span></span>

<span data-ttu-id="e3a11-871">&#x2713; 암호의 최소 5개 암호 기록입니다.</span><span class="sxs-lookup"><span data-stu-id="e3a11-871">&#x2713; Password history of a minimum of five passwords.</span></span>

<span data-ttu-id="e3a11-872">&#x2713; 강력한 암호의 사용을 적용합니다.</span><span class="sxs-lookup"><span data-stu-id="e3a11-872">&#x2713; Enforcement of the use of strong passwords.</span></span>

* <span data-ttu-id="e3a11-873">모든 원격 액세스 솔루션에 강력한 암호화가 구성되어 있는지 보여 주십시오.</span><span class="sxs-lookup"><span data-stu-id="e3a11-873">Demonstrate that strong encryption is configured on all remote access solutions.</span></span>

* <span data-ttu-id="e3a11-874">공용 DNS 관리가 범위 내 환경 외부에 있는 경우 DNS를 수정할 수 있는 모든 사용자 계정은 MFA를 사용하도록 구성해야 합니다.</span><span class="sxs-lookup"><span data-stu-id="e3a11-874">Where the management of Public DNS is outside of the in-scope environment, all user accounts able to make DNS modifications MUST be configured to use MFA.</span></span>

<span data-ttu-id="e3a11-875">**침입 감지 및 방지(OPTIONAL)**</span><span class="sxs-lookup"><span data-stu-id="e3a11-875">**Intrusion Detection and Prevention (OPTIONAL)**</span></span>

<span data-ttu-id="e3a11-876">PCI DSS 감사는 IDPS(침입 감지 및 방지 서비스) 프로세스의 일부 요소를 구체적으로 평가하지 않는 경우 다음을 요구합니다.</span><span class="sxs-lookup"><span data-stu-id="e3a11-876">As PCI DSS audits do not specifically assess some elements of Intrusion Detection and Prevention Services (IDPS) processes, this will require you to:</span></span>

* <span data-ttu-id="e3a11-877">TLS 검사를 위해 IDPS를 구성해야 합니다.</span><span class="sxs-lookup"><span data-stu-id="e3a11-877">IDPS SHOULD be configured for TLS inspection.</span></span>

*   <span data-ttu-id="e3a11-878">모든 인바운드 및 아웃바운드 트래픽에 대해 IDPS를 구성해야 합니다.</span><span class="sxs-lookup"><span data-stu-id="e3a11-878">IDPS SHOULD be configured for ALL inbound and outbound traffic.</span></span>

<span data-ttu-id="e3a11-879">**위험 관리**</span><span class="sxs-lookup"><span data-stu-id="e3a11-879">**Risk Management**</span></span>

<span data-ttu-id="e3a11-880">PCI DSS 감사는 위험 평가 프로세스의 일부 요소를 구체적으로 평가하지 않는 경우 다음을 요구합니다.</span><span class="sxs-lookup"><span data-stu-id="e3a11-880">As PCI DSS audits do not specifically assess some elements of risk assessment processes, this will require you to:</span></span>

* <span data-ttu-id="e3a11-881">위험 평가에 영향 및 가능성 분석이 포함됩니다.</span><span class="sxs-lookup"><span data-stu-id="e3a11-881">Demonstrate the risk assessment includes impact and likelihood matrices.</span></span>

<span data-ttu-id="e3a11-882">**인시던트 대응**</span><span class="sxs-lookup"><span data-stu-id="e3a11-882">**Incident Response**</span></span>

<span data-ttu-id="e3a11-883">PCI DSS 감사는 인시던트 대응 정책 및 프로세스의 일부 요소를 특별히 평가하지 않는 경우 개발자가 다음을 요구합니다.</span><span class="sxs-lookup"><span data-stu-id="e3a11-883">As PCI DSS audits don't specifically assess some elements of incident response policies and processes, this will require the developer to:</span></span>

* <span data-ttu-id="e3a11-884">인시던트 처리 기능이 NIST 사이버 보안 프레임워크(식별, 보호, 감지, 대응, 복구)에 맞춰진 것을 보여줄 수 있습니다.</span><span class="sxs-lookup"><span data-stu-id="e3a11-884">Demonstrate Incident handling capabilities align to NIST Cybersecurity Framework (Identify, Protect, Detect, Respond, Recover).</span></span>

## <a name="appendix-e"></a><span data-ttu-id="e3a11-885">부록 E</span><span class="sxs-lookup"><span data-stu-id="e3a11-885">Appendix E</span></span>

### <a name="evidence-collection---deltas-for-soc-2"></a><span data-ttu-id="e3a11-886">증거 수집 - SOC 2의 델타</span><span class="sxs-lookup"><span data-stu-id="e3a11-886">Evidence Collection - Deltas for SOC 2</span></span>

<span data-ttu-id="e3a11-887">SOC 2 규정 준수를 이미 획득한 경우 이 Microsoft 365 인증의 일부로 SOC 2에서 다루지 않는 다음 델타의 (간격)를 검토해야 합니다.</span><span class="sxs-lookup"><span data-stu-id="e3a11-887">Where you have already attained SOC 2 compliance, the following delta’s (gaps) not wholly covered by SOC 2 will need to be reviewed as part of this Microsoft 365 Certification.</span></span>

> [!NOTE]
> <span data-ttu-id="e3a11-888">Microsoft 365 인증 평가의 일부로 인증 분석가가 매핑된 SOC 2 컨트롤이 SOC 2 평가의 일부로 포함되지 않은지 여부를 결정하고 추가 보증을 제공하기 위해 포함된 것으로 확인된 샘플 컨트롤도 결정할 수 있습니다.</span><span class="sxs-lookup"><span data-stu-id="e3a11-888">As part of the Microsoft 365 Certification assessment, the certification analyst will determine if any of the mapped SOC 2 controls were not included as part of your SOC 2 assessment and may also decide to sample controls that were found to be included to provide further assurance.</span></span> <span data-ttu-id="e3a11-889">SOC 2 평가에서 누락된 요구 사항은 Microsoft 365 인증 평가 활동의 일부로 포함해야 합니다.</span><span class="sxs-lookup"><span data-stu-id="e3a11-889">Any requirements missing from your SOC 2 assessment will need to be included as part of the Microsoft 365 Certification assessment activities.</span></span>

<span data-ttu-id="e3a11-890">**맬웨어 보호 - 응용 프로그램 제어**</span><span class="sxs-lookup"><span data-stu-id="e3a11-890">**Malware Protection - Application Control**</span></span>

<span data-ttu-id="e3a11-891">바이러스 백신을 사용하여 맬웨어 보호가 설정 중이고 SOC 2 보고서 내에 확인된 경우 추가 조사가 필요하지 않습니다.</span><span class="sxs-lookup"><span data-stu-id="e3a11-891">If malware protection is in place through use of anti-virus and is attested to within your SOC 2 report no further investigation is necessary.</span></span> <span data-ttu-id="e3a11-892">바이러스 백신이 없는 경우 인증 분석가가 환경 내에서 맬웨어가 발견되지 않도록 응용 프로그램 제어 메커니즘의 증거를 식별하고 평가해야 합니다.</span><span class="sxs-lookup"><span data-stu-id="e3a11-892">If no anti-virus is in place, certification analysts will need to identify and assess evidence of application control mechanisms to prevent detonation of malware within the environment.</span></span> <span data-ttu-id="e3a11-893">이렇게 하면 다음이 필요할 수 있습니다.</span><span class="sxs-lookup"><span data-stu-id="e3a11-893">This will require you to:</span></span>

* <span data-ttu-id="e3a11-894">특정 응용 프로그램 제어 메커니즘(예: 화이트리스트, 코드 서명 등)을 충족하도록 응용 프로그램 제어 소프트웨어를 구성하는 방법을 자세히 설명하는 지원 설명서를 제공하거나 설명하는 문서가 제공됩니다.</span><span class="sxs-lookup"><span data-stu-id="e3a11-894">Provide or demonstrate supporting documentation is in place detailing how application control software is configured to meet specific application control mechanisms (i.e. whitelisting, code signing, etc.).</span></span>

* <span data-ttu-id="e3a11-895">응용 프로그램 승인이 수행된 방법을 보여 주며 이 작업을 완료하는지 확인할 수 있습니다.</span><span class="sxs-lookup"><span data-stu-id="e3a11-895">Demonstrate how the application approval is conducted and confirm that this is completed.</span></span>

*   <span data-ttu-id="e3a11-896">비즈니스 사정이 있는 승인된 응용 프로그램의 전체 목록이 존재할 수 있습니다.</span><span class="sxs-lookup"><span data-stu-id="e3a11-896">Demonstrate that a complete list of approved applications with business justification exists.</span></span>

*   <span data-ttu-id="e3a11-897">모든 샘플링된 시스템 구성 요소에서 응용 프로그램 제어가 문서화된 것으로 구성되어 있는지 보여 주도록 합니다.</span><span class="sxs-lookup"><span data-stu-id="e3a11-897">Demonstrate that across all sampled system components, application control is configured as documented.</span></span>

<span data-ttu-id="e3a11-898">**패치 관리 - 패치**</span><span class="sxs-lookup"><span data-stu-id="e3a11-898">**Patch Management – Patching**</span></span>

<span data-ttu-id="e3a11-899">SOC 2 감사는 이 범주를 구체적으로 평가하지 않는 경우 다음을 요구합니다.</span><span class="sxs-lookup"><span data-stu-id="e3a11-899">As SOC 2 audits do not specifically assess this category, this will require you to:</span></span>

*   <span data-ttu-id="e3a11-900">낮음, 중간, 높음 또는 중요 문제는 일반 패치 작업 창 내에서 패치해야 합니다.</span><span class="sxs-lookup"><span data-stu-id="e3a11-900">Any Low, Medium, High, or Critical issue must be patched within normal patching activity windows.</span></span>

*   <span data-ttu-id="e3a11-901">공급업체에서 더 이상 지원하지 않는 소프트웨어 구성 요소 및 운영 체제는 환경 내에서 사용되지 말아야 합니다.</span><span class="sxs-lookup"><span data-stu-id="e3a11-901">Software components and operating systems no longer supported by the vendor MUST not be used within the environment.</span></span> <span data-ttu-id="e3a11-902">지원 정책이 있어야 지원되지 않는 소프트웨어 구성 요소/운영 체제가 환경에서 제거되고 소프트웨어 구성 요소가 수명 종료될 때를 식별하는 프로세스가 필요합니다.</span><span class="sxs-lookup"><span data-stu-id="e3a11-902">Supporting policies MUST be in place to ensure unsupported software components / operating systems will be removed from the environment and a process to identify when software components go end-of-life must be in place.</span></span>

<span data-ttu-id="e3a11-903">**방화벽 - 방화벽**</span><span class="sxs-lookup"><span data-stu-id="e3a11-903">**Firewall – Firewalls**</span></span>

<span data-ttu-id="e3a11-904">SOC 2 감사는 방화벽 액세스 제어 목록에 대한 변경 제어를 구체적으로 평가하지 않는 경우 다음을 요구합니다.</span><span class="sxs-lookup"><span data-stu-id="e3a11-904">As SOC 2 audits do not specifically assess change controls to firewall access control lists, this will require you to:</span></span>

* <span data-ttu-id="e3a11-905">방화벽을 통해 허용된 모든 트래픽이 인증 프로세스를 통과하여 비즈니스 사당성에 따라 모든 트래픽에 대한 설명서를 작성하는 것을 입증합니다.</span><span class="sxs-lookup"><span data-stu-id="e3a11-905">Demonstrate that all permitted traffic through the firewall(s) goes through an authorization process which results in the documentation of all traffic with a business justification.</span></span>

* <span data-ttu-id="e3a11-906">방화벽 규칙 검토는 최소 6개월마다 수행됩니다.</span><span class="sxs-lookup"><span data-stu-id="e3a11-906">Demonstrate that firewall rule reviews are conducted at least every six months.</span></span>

<span data-ttu-id="e3a11-907">응용 프로그램이 노출될 수 있는 다양한 웹 응용 프로그램 위협 및 취약성으로부터 보호하기 위해 WAF(웹 응용 프로그램 방화벽) 또는 이와 유사한 웹 응용 프로그램 방화벽이 배포된 경우 추가 크레딧이 제공됩니다.</span><span class="sxs-lookup"><span data-stu-id="e3a11-907">Additional credit will be provided if a Web Application Firewall (WAF) or similar is deployed to help protect against the myriad of web application threats and vulnerabilities that the application can be exposed to.</span></span> <span data-ttu-id="e3a11-908">WAF 또는 유사 WAF가 있는 경우 다음을 요구합니다.</span><span class="sxs-lookup"><span data-stu-id="e3a11-908">When a WAF or similar is present, this will require you to:</span></span>

* <span data-ttu-id="e3a11-909">WAF가 경고를 통해 활성 방어 모드 또는 더 많은 모니터링으로 구성되어 있는지를 보여줄 수 있습니다.</span><span class="sxs-lookup"><span data-stu-id="e3a11-909">Demonstrate the WAF is configured in active defense mode or monitoring more with alerting.</span></span>

* <span data-ttu-id="e3a11-910">WAF가 SSL 오프로드를 지원하도록 구성되어 있는지 보여 집니다.</span><span class="sxs-lookup"><span data-stu-id="e3a11-910">Demonstrate the WAF is configured to support SSL offloading.</span></span>

* <span data-ttu-id="e3a11-911">다음과 같은 대부분의 공격 유형으로부터 보호하기 위해 OWASP 핵심 규칙 집합((3.0 또는 3.1)에 따라 구성됩니다.</span><span class="sxs-lookup"><span data-stu-id="e3a11-911">Is configured as per the OWASP Core Rule Set ((3.0 or 3.1) to protect against the majority of the following attack types:</span></span>

<span data-ttu-id="e3a11-912">&emsp;&#x2713; 및 인코딩 문제를 해결합니다.</span><span class="sxs-lookup"><span data-stu-id="e3a11-912">&emsp;&#x2713; Protocol and encoding issues.</span></span>

<span data-ttu-id="e3a11-913">&emsp;&#x2713;, 요청 밀기 및 응답 분할을 요청합니다.</span><span class="sxs-lookup"><span data-stu-id="e3a11-913">&emsp;&#x2713; Header injection, request smuggling, and response splitting.</span></span>

<span data-ttu-id="e3a11-914">&emsp;&#x2713; 경로 트래버스 공격을 공격합니다.</span><span class="sxs-lookup"><span data-stu-id="e3a11-914">&emsp;&#x2713; File and path traversal attacks.</span></span>

<span data-ttu-id="e3a11-915">&emsp;&#x2713; RFI(원격 파일 포함) 공격이 있습니다.</span><span class="sxs-lookup"><span data-stu-id="e3a11-915">&emsp;&#x2713; Remote file inclusion (RFI) attacks.</span></span>

<span data-ttu-id="e3a11-916">&emsp;&#x2713; 코드 실행 공격을 중지합니다.</span><span class="sxs-lookup"><span data-stu-id="e3a11-916">&emsp;&#x2713; Remote code execution attacks.</span></span>

<span data-ttu-id="e3a11-917">&emsp;&#x2713; PHP 주입 공격이 있습니다.</span><span class="sxs-lookup"><span data-stu-id="e3a11-917">&emsp;&#x2713; PHP-injection attacks.</span></span>

<span data-ttu-id="e3a11-918">&emsp;&#x2713; 스크립팅 공격을 수정합니다.</span><span class="sxs-lookup"><span data-stu-id="e3a11-918">&emsp;&#x2713; Cross-site scripting attacks.</span></span>

<span data-ttu-id="e3a11-919">&emsp;&#x2713; SQL 주입 공격.</span><span class="sxs-lookup"><span data-stu-id="e3a11-919">&emsp;&#x2713; SQL-injection attacks.</span></span>

<span data-ttu-id="e3a11-920">&emsp;&#x2713; 수정 공격을 해결합니다.</span><span class="sxs-lookup"><span data-stu-id="e3a11-920">&emsp;&#x2713; Session-fixation attacks.</span></span>

<span data-ttu-id="e3a11-921">**변경 컨트롤**</span><span class="sxs-lookup"><span data-stu-id="e3a11-921">**Change Control**</span></span>

<span data-ttu-id="e3a11-922">SOC 2 감사는 변경 요청 프로세스의 일부 요소를 구체적으로 평가하지 않는 경우 개발자가 다음을 요구합니다.</span><span class="sxs-lookup"><span data-stu-id="e3a11-922">As SOC 2 audits don't specifically assess some elements of Change Request processes, this will require the developer to:</span></span>

* <span data-ttu-id="e3a11-923">개발/테스트 환경이 프로덕션 환경과 분리되어 업무 분리를 이행하는 방법을 보여 줍니다.</span><span class="sxs-lookup"><span data-stu-id="e3a11-923">Demonstrate how development / test environments are separate from the production environment enforcing separation of duties.</span></span>

* <span data-ttu-id="e3a11-924">개발/테스트 환경에서 라이브 데이터가 어떻게 사용되지 않는지 보여줄 수 있습니다.</span><span class="sxs-lookup"><span data-stu-id="e3a11-924">Demonstrate how live data isn't used within the development / test environments.</span></span>

* <span data-ttu-id="e3a11-925">기능 테스트는 변경이 완료된 후에 수행됩니다.</span><span class="sxs-lookup"><span data-stu-id="e3a11-925">Demonstrate that functionality testing is conducted after changes are completed.</span></span>

* <span data-ttu-id="e3a11-926">기능 테스트가 수행된 후 변경 요청이 서명된 경우를 보여 집니다.</span><span class="sxs-lookup"><span data-stu-id="e3a11-926">Demonstrate that change requests are signed off after functionality testing is conducted.</span></span>

<span data-ttu-id="e3a11-927">**보안 소프트웨어 개발/배포**</span><span class="sxs-lookup"><span data-stu-id="e3a11-927">**Secure Software Development/Deployment**</span></span>

<span data-ttu-id="e3a11-928">SOC 2 감사는 보안 소프트웨어 개발 및 배포 프로세스의 일부 요소에 특별히 액세스하지 않습니다. 이렇게 하면 다음이 요구될 수 있습니다.</span><span class="sxs-lookup"><span data-stu-id="e3a11-928">As SOC 2 audits do not specifically access some elements of secure software development and deployment processes; this will require to you:</span></span>

*   <span data-ttu-id="e3a11-929">전체 소프트웨어 개발 수명 주기를 다루는 설정 및 문서화된 소프트웨어 개발 프로세스가 있어야 합니다.</span><span class="sxs-lookup"><span data-stu-id="e3a11-929">You MUST have an established and documented software development process covering the entire software-development lifecycle.</span></span>

*   <span data-ttu-id="e3a11-930">개발자는 적어도 매년 보안 소프트웨어 코딩 교육을 실시해야 합니다.</span><span class="sxs-lookup"><span data-stu-id="e3a11-930">Developers MUST undergo secure software coding training at least annually.</span></span>

*   <span data-ttu-id="e3a11-931">코드 리포지토리는 MFA로 보호해야 합니다.</span><span class="sxs-lookup"><span data-stu-id="e3a11-931">Code repositories MUST be secured by MFA.</span></span>

*   <span data-ttu-id="e3a11-932">악성 코드 수정으로부터 코드 리포지토리를 보호하려면 적절한 액세스 제어가 있어야 합니다.</span><span class="sxs-lookup"><span data-stu-id="e3a11-932">Adequate access controls MUST be in place to protect code repositories against malicious code modifications.</span></span>

<span data-ttu-id="e3a11-933">**계정 관리**</span><span class="sxs-lookup"><span data-stu-id="e3a11-933">**Account Management**</span></span>

<span data-ttu-id="e3a11-934">SOC2 감사는 계정 관리 프로세스의 일부 요소를 구체적으로 평가하지 않는 경우 다음을 요구합니다.</span><span class="sxs-lookup"><span data-stu-id="e3a11-934">As SOC2 audits do not specifically assess some elements of account management processes, this will require you to:</span></span>

*   <span data-ttu-id="e3a11-935">재생 공격(예: MFA, Kerberos)을 완화하기 위해 인증 메커니즘을 구현하는 방법을 보여줄 수 있습니다.</span><span class="sxs-lookup"><span data-stu-id="e3a11-935">Demonstrate how the authorization mechanisms are implemented to mitigate replay attacks (e.g. MFA, Kerberos).</span></span>

*   <span data-ttu-id="e3a11-936">3개월 동안 사용되지 않은 계정을 사용하지 않도록 설정하거나 삭제하는 방법을 보여줄 수 있습니다.</span><span class="sxs-lookup"><span data-stu-id="e3a11-936">Demonstrate how accounts that have not been used in 3 months are either disabled or deleted.</span></span>

*   <span data-ttu-id="e3a11-937">강력한 암호 정책 또는 기타 적절한 완화는 사용자 자격 증명을 보호하도록 구성해야 합니다.</span><span class="sxs-lookup"><span data-stu-id="e3a11-937">Strong password policies or other suitable mitigations must be configured to protect user credentials.</span></span> <span data-ttu-id="e3a11-938">다음과 같은 최소 암호 정책을 지침으로 사용해야 합니다.</span><span class="sxs-lookup"><span data-stu-id="e3a11-938">The following minimum password policy should be used as a guideline:</span></span>

<span data-ttu-id="e3a11-939">&emsp;&#x2713; 최소 암호 길이는 8자입니다.</span><span class="sxs-lookup"><span data-stu-id="e3a11-939">&emsp;&#x2713; Minimum password length of 8 characters.</span></span>

<span data-ttu-id="e3a11-940">&emsp;&#x2713; 계정 잠금 임계값은 10회를 넘지 않습니다.</span><span class="sxs-lookup"><span data-stu-id="e3a11-940">&emsp;&#x2713; Account lockout threshold of no more than 10 attempts.</span></span>

<span data-ttu-id="e3a11-941">&emsp;&#x2713; 최소 5개 암호의 암호 기록입니다.</span><span class="sxs-lookup"><span data-stu-id="e3a11-941">&emsp;&#x2713; Password history of a minimum of 5 passwords.</span></span>

<span data-ttu-id="e3a11-942">&emsp;&#x2713; 강력한 암호 사용 적용</span><span class="sxs-lookup"><span data-stu-id="e3a11-942">&emsp;&#x2713; Enforcement of the use of strong passwords</span></span>

*   <span data-ttu-id="e3a11-943">고유한 사용자 계정이 모든 사용자에게 발급된 경우를 보여 줄 수 있습니다.</span><span class="sxs-lookup"><span data-stu-id="e3a11-943">Demonstrate that unique user accounts are issued to all users.</span></span>

*   <span data-ttu-id="e3a11-944">공용 DNS 관리가 범위 내 환경 외부에 있는 경우 DNS를 수정할 수 있는 모든 사용자 계정은 MFA를 사용하도록 구성해야 합니다.</span><span class="sxs-lookup"><span data-stu-id="e3a11-944">Where the management of Public DNS is outside of the in-scope environment, all user accounts able to make DNS modifications MUST be configured to use MFA.</span></span>

<span data-ttu-id="e3a11-945">**침입 감지 및 방지(OPTIONAL)**</span><span class="sxs-lookup"><span data-stu-id="e3a11-945">**Intrusion Detection and Prevention (OPTIONAL).**</span></span>

<span data-ttu-id="e3a11-946">SOC 2 감사는 IDPS(침입 감지 및 방지 서비스) 프로세스의 일부 요소를 구체적으로 평가하지 않는 경우 다음을 요구합니다.</span><span class="sxs-lookup"><span data-stu-id="e3a11-946">As SOC 2 audits do not specifically assess some elements of Intrusion Detection and Prevention Services (IDPS) processes, this will require you to:</span></span>

*   <span data-ttu-id="e3a11-947">IDPS 서명은 지난 날 내에 최신으로 유지해야 합니다.</span><span class="sxs-lookup"><span data-stu-id="e3a11-947">IDPS signatures SHOULD be kept current, within the past day</span></span>

*   <span data-ttu-id="e3a11-948">TLS 검사를 위해 IDPS를 구성해야 합니다.</span><span class="sxs-lookup"><span data-stu-id="e3a11-948">IDPS SHOULD be configured for TLS inspection</span></span>

*   <span data-ttu-id="e3a11-949">모든 인바운드 및 아웃바운드 트래픽에 대해 IDPS를 구성해야 합니다.</span><span class="sxs-lookup"><span data-stu-id="e3a11-949">IDPS SHOULD be configured for ALL inbound and outbound traffic</span></span>

<span data-ttu-id="e3a11-950">**이벤트 로깅**</span><span class="sxs-lookup"><span data-stu-id="e3a11-950">**Event Logging**</span></span>

<span data-ttu-id="e3a11-951">SOC 2 감사는 보안 이벤트 로깅 프로세스의 일부 요소를 구체적으로 평가하지 않는 경우 다음을 요구합니다.</span><span class="sxs-lookup"><span data-stu-id="e3a11-951">As SOC 2 audits do not specifically assess some elements of security event logging processes, this will require you to:</span></span>

* <span data-ttu-id="e3a11-952">샘플 집합 내의 모든 시스템 구성 요소에서 다음 이벤트를 기록하도록 다음 시스템을 구성하는 방법을 보여줄 수 있습니다.</span><span class="sxs-lookup"><span data-stu-id="e3a11-952">Demonstrate how, on all system components within the sample set the following system are configured to log the following events</span></span>

<span data-ttu-id="e3a11-953">&emsp;&#x2713; 구성 요소 및 응용 프로그램에 대한 사용자 액세스입니다.</span><span class="sxs-lookup"><span data-stu-id="e3a11-953">&emsp;&#x2713; User access to system components and the application(s).</span></span>

<span data-ttu-id="e3a11-954">&emsp;&#x2713; 권한이 높은 사용자가 수행한 모든 작업입니다.</span><span class="sxs-lookup"><span data-stu-id="e3a11-954">&emsp;&#x2713; All actions taken by a high privileged user.</span></span>

<span data-ttu-id="e3a11-955">&emsp;&#x2713; 액세스 시도가 잘못되었습니다.</span><span class="sxs-lookup"><span data-stu-id="e3a11-955">&emsp;&#x2713; Invalid logical access attempts.</span></span>

<span data-ttu-id="e3a11-956">기록된 이벤트에 포함된지 보여 주며, 최소한 다음 정보가 있습니다.</span><span class="sxs-lookup"><span data-stu-id="e3a11-956">Demonstrate that logged events contain; at a minimum, the following information:</span></span>

<span data-ttu-id="e3a11-957">&emsp;&#x2713; 사용자.</span><span class="sxs-lookup"><span data-stu-id="e3a11-957">&emsp;&#x2713; User.</span></span>

<span data-ttu-id="e3a11-958">&emsp;&#x2713; 유형입니다.</span><span class="sxs-lookup"><span data-stu-id="e3a11-958">&emsp;&#x2713; Type of Event.</span></span>

<span data-ttu-id="e3a11-959">&emsp;&#x2713; 날짜 및 시간입니다.</span><span class="sxs-lookup"><span data-stu-id="e3a11-959">&emsp;&#x2713; Date and Time.</span></span>

<span data-ttu-id="e3a11-960">&emsp;&#x2713;/실패 표시기입니다.</span><span class="sxs-lookup"><span data-stu-id="e3a11-960">&emsp;&#x2713; Success/Failure indicator.</span></span>

<span data-ttu-id="e3a11-961">&emsp;&#x2713; 레이블을 사용하여 영향을 받는 시스템을 식별합니다.</span><span class="sxs-lookup"><span data-stu-id="e3a11-961">&emsp;&#x2713; Label to identify the affected system.</span></span>

*   <span data-ttu-id="e3a11-962">샘플 집합 내의 모든 시스템 구성 요소는 시간 동기화를 활용하도록 구성되어 있으며 기본/보조 시간 서버와 동일하다는 설명입니다.</span><span class="sxs-lookup"><span data-stu-id="e3a11-962">Demonstrate that all system components within the sample set are configured to utilize time-synchronization and that these are the same as the primary/secondary time servers.</span></span>

* <span data-ttu-id="e3a11-963">공용 시스템이 DMZ 내에 없는 중앙 로깅 솔루션에 로깅하는지 보여 주십시오.</span><span class="sxs-lookup"><span data-stu-id="e3a11-963">Demonstrate that public facing systems are logging to a centralized logging solution which isn't within the DMZ.</span></span>

*   <span data-ttu-id="e3a11-964">공용 시스템이 DMZ 내에 없는 중앙 로깅 솔루션에 로깅하는지 보여 주십시오.</span><span class="sxs-lookup"><span data-stu-id="e3a11-964">Demonstrate that public facing systems are logging to a centralized logging solution which isn't within the DMZ.</span></span>

* <span data-ttu-id="e3a11-965">중앙 로깅 솔루션이 로깅 데이터를 무단으로 변조하지 못하게 보호하는 방법을 보여줄 수 있습니다.</span><span class="sxs-lookup"><span data-stu-id="e3a11-965">Demonstrate how the centralized logging solution is protected from unauthorized tampering of logging data.</span></span>

* <span data-ttu-id="e3a11-966">최소 30일 이상의 로깅 데이터를 즉시 사용할 수 있는 방법(90일 이상 보존)을 보여줄 수 있습니다.</span><span class="sxs-lookup"><span data-stu-id="e3a11-966">Demonstrate how a minimum of 30 days’ worth of logging data is immediately available, with 90 days’ or more being retained.</span></span>

<span data-ttu-id="e3a11-967">**위험 관리**</span><span class="sxs-lookup"><span data-stu-id="e3a11-967">**Risk Management**</span></span>

<span data-ttu-id="e3a11-968">SOC2 감사는 위험 평가 프로세스의 일부 요소를 구체적으로 평가하지 않는 경우 다음을 요구합니다.</span><span class="sxs-lookup"><span data-stu-id="e3a11-968">As SOC2 audits do not specifically assess some elements of risk assessment processes, this will require you to:</span></span>

* <span data-ttu-id="e3a11-969">공식적인 위험 평가가 적어도 매년 수행됩니다.</span><span class="sxs-lookup"><span data-stu-id="e3a11-969">Demonstrate that a formal risk assessment is conducted at least annually.</span></span>

<span data-ttu-id="e3a11-970">*인시던트 대응.*</span><span class="sxs-lookup"><span data-stu-id="e3a11-970">*Incident Response.*</span></span>

<span data-ttu-id="e3a11-971">SOC2 감사는 인시던트 대응 정책 및 프로세스의 일부 요소를 구체적으로 평가하지 않는 경우 다음을 요구합니다.</span><span class="sxs-lookup"><span data-stu-id="e3a11-971">As SOC2 audits do not specifically assess some elements of incident response policies and processes, this will require you to:</span></span>

* <span data-ttu-id="e3a11-972">인시던트 대응 계획/절차에 다음이 포함됩니다.</span><span class="sxs-lookup"><span data-stu-id="e3a11-972">Demonstrate that the incident response plan/procedure includes:</span></span>

<span data-ttu-id="e3a11-973">&emsp;&#x2713; 위협 모델에 대한 특정 응답 절차입니다.</span><span class="sxs-lookup"><span data-stu-id="e3a11-973">&emsp;&#x2713; Specific response procedures for expected threat models.</span></span>

<span data-ttu-id="e3a11-974">&emsp;&#x2713; 주요 이해 관계자(결제 브랜드/인수자, 규제 기관, 감독 기관, 이사, 고객 등)의 시기 적절한 알림을 보장하기 위한 문서화된 통신 프로세스입니다.</span><span class="sxs-lookup"><span data-stu-id="e3a11-974">&emsp;&#x2713; Documented communications process to ensure timely notification of key stakeholders (payment brands/acquirers, regulatory bodies, supervisory authorities, directors, customers, etc.</span></span>

## <a name="appendix-f"></a><span data-ttu-id="e3a11-975">부록 F</span><span class="sxs-lookup"><span data-stu-id="e3a11-975">Appendix F</span></span>

### <a name="hosting-deployment-types"></a><span data-ttu-id="e3a11-976">호스팅 배포 유형</span><span class="sxs-lookup"><span data-stu-id="e3a11-976">Hosting Deployment Types</span></span>

<span data-ttu-id="e3a11-977">Microsoft는 응용 프로그램을 배포하고 다른 호스팅 환경 내에 앱/추가 기능 코드를 저장합니다.</span><span class="sxs-lookup"><span data-stu-id="e3a11-977">Microsoft acknowledges you will deploy applications and store app/add-in code within different hosting environments.</span></span> <span data-ttu-id="e3a11-978">Microsoft 365 인증 내의 일부 보안 제어에 대한 전반적인 책임은 사용 되는 호스팅 환경에 따라 달라 집니다.</span><span class="sxs-lookup"><span data-stu-id="e3a11-978">The overall responsibilities of some of the security controls within the Microsoft 365 Certification will depend on the hosting environment being used.</span></span> <span data-ttu-id="e3a11-979">부록 F는 일반적인 배포 유형을 검토하여 평가 프로세스의 일부로 평가되는 보안 컨트롤에 매핑합니다.</span><span class="sxs-lookup"><span data-stu-id="e3a11-979">Appendix F looks at common deployment types and maps these against the security controls that are evaluated as part of the assessment process.</span></span> <span data-ttu-id="e3a11-980">다음과 같은 호스팅 배포 유형이 확인되었습니다.</span><span class="sxs-lookup"><span data-stu-id="e3a11-980">The following hosting deployment types have been identified:</span></span>

|  |  |
|-----|------|
|<span data-ttu-id="e3a11-981">**ISV Hosted**</span><span class="sxs-lookup"><span data-stu-id="e3a11-981">**ISV Hosted**</span></span>|<span data-ttu-id="e3a11-982">ISV 호스팅 형식은 앱/추가 기능 환경을 지원하는 데 사용되는 인프라를 담당하는 위치로 정의할 수 있습니다.</span><span class="sxs-lookup"><span data-stu-id="e3a11-982">ISV hosted types can be defined as where you are responsible for the infrastructure used to support the app/add-in environment.</span></span> <span data-ttu-id="e3a11-983">이 위치는 공동 위치 서비스가 있는 자체 데이터 센터 또는 타사 데이터 센터 내에 물리적으로 위치할 수 있습니다.</span><span class="sxs-lookup"><span data-stu-id="e3a11-983">This can be physically located within your own data centers or third-party data centers with a co-location service.</span></span> <span data-ttu-id="e3a11-984">궁극적으로 지원 인프라 및 운영 환경에 대한 모든 소유권과 관리 제어권이 있습니다.</span><span class="sxs-lookup"><span data-stu-id="e3a11-984">Ultimately, you have full ownership and administrative control over the supporting infrastructure and operating environment.</span></span>|
|<span data-ttu-id="e3a11-985">**IaaS(Infrastructure as a Service)** (https://azure.microsoft.com/en-gb/overview/what-is-iaas/)</span><span class="sxs-lookup"><span data-stu-id="e3a11-985">**Infrastructure as a Service (IaaS)** (https://azure.microsoft.com/en-gb/overview/what-is-iaas/)</span></span>|<span data-ttu-id="e3a11-986">인프라 as a Service는 클라우드 서비스 공급자(CSP)가 실제 지원 인프라를 대신하여 관리 및 유지 관리하는 경우 제공되는 서비스입니다.</span><span class="sxs-lookup"><span data-stu-id="e3a11-986">Infrastructure as a Service is a service that is provided whereby the physical supporting infrastructure is managed and maintained on their behalf by the cloud service provider (CSP).</span></span> <span data-ttu-id="e3a11-987">일반적으로 네트워킹, 저장소, 실제 서버 및 가상화 인프라는 모두 CSP의 책임입니다.</span><span class="sxs-lookup"><span data-stu-id="e3a11-987">Typically, networking, storage, physical servers, and the virtualization infrastructure is all the responsibility of the CSP.</span></span> <span data-ttu-id="e3a11-988">운영 체제, 미들웨어, 런타임, 데이터 및 응용 프로그램은 사용자 책임입니다.</span><span class="sxs-lookup"><span data-stu-id="e3a11-988">The Operating System, Middleware, Runtime, Data and Applications are the responsibilities of you.</span></span> <span data-ttu-id="e3a11-989">방화벽 기능은 타사에서 관리 및 유지 관리하기도 하지만 방화벽 규칙 기반의 유지 관리는 일반적으로 소비자의 책임입니다.</span><span class="sxs-lookup"><span data-stu-id="e3a11-989">Firewalling capabilities would also be managed and maintained by the third-party, however maintenance of the firewall rule base would usually be still the consumers responsibility.</span></span>|
|<span data-ttu-id="e3a11-990">**PaaS(Platform as a Service/Serverless)** (https://azure.microsoft.com/en-gb/overview/what-is-paas/)</span><span class="sxs-lookup"><span data-stu-id="e3a11-990">**Platform as a Service/Serverless (PaaS)** (https://azure.microsoft.com/en-gb/overview/what-is-paas/)</span></span>| <span data-ttu-id="e3a11-991">Platform as a Service를 사용하면 사용할 수 있는 서비스를 제공하는 관리되는 플랫폼으로 프로비전됩니다.</span><span class="sxs-lookup"><span data-stu-id="e3a11-991">With Platform as a Service, you are provisioned with a managed platform presenting a service that can be consumed.</span></span> <span data-ttu-id="e3a11-992">운영 체제와 지원 인프라가 CSP에서 관리되는 sysadmin 기능을 수행할 필요는 없습니다.</span><span class="sxs-lookup"><span data-stu-id="e3a11-992">You do not need to perform sysadmin functions as the operating system and supporting infrastructure is managed by the CSP.</span></span> <span data-ttu-id="e3a11-993">이 작업은 일반적으로 조직에서 웹 서비스를 제공하는 것을 염려하지 않고 대신 웹 응용 프로그램 소스 코드를 만들고 클라우드 관리 웹 서비스에 웹 응용 프로그램을 게시하는 데 집중할 수 있는 경우 사용됩니다.</span><span class="sxs-lookup"><span data-stu-id="e3a11-993">This would typically be used when organizations do not want to be concerned with presenting a web service and instead can concentrate on creating the web application source code and publishing the web application on the cloud managed web services.</span></span>  <span data-ttu-id="e3a11-994">또 다른 예로는 데이터베이스에 대한 연결이 제공된 데이터베이스 서비스이지만, 지원 인프라 및 데이터베이스 응용 프로그램은 소비자로부터 추상화됩니다.</span><span class="sxs-lookup"><span data-stu-id="e3a11-994">Another example may be a database service where connectivity is given to a database, however the supporting infrastructure and database application is abstracted from the consumer.</span></span>   <span data-ttu-id="e3a11-995">**참고: Serverless 및 PaaS는 Microsoft 365 인증 호스팅 배포 유형의 Serverless 및 PasS가 동일한 것으로 확인됩니다.**</span><span class="sxs-lookup"><span data-stu-id="e3a11-995">**Note: Serverless and PaaS are similar so for the purpose of the Microsoft 365 Certification Hosting Deployment Type's Serverless and PasS are deemed the same**</span></span>|
|<span data-ttu-id="e3a11-996">**하이브리드 호스트**</span><span class="sxs-lookup"><span data-stu-id="e3a11-996">**Hybrid Hosted**</span></span>|<span data-ttu-id="e3a11-997">하이브리드 호스팅 형식을 사용하면 여러 호스팅 형식을 사용하여 지원 환경의 다양한 부분을 지원할 수 있습니다.</span><span class="sxs-lookup"><span data-stu-id="e3a11-997">With the hybrid hosted type, you may utilize multiple hosted types to support various parts of the supporting environment.</span></span> <span data-ttu-id="e3a11-998">이는 여러 M365 스택에서 앱/추가 기능을 사용하는 경우에 더 많이 있을 수 있습니다.</span><span class="sxs-lookup"><span data-stu-id="e3a11-998">This may be more the case where apps/add-ins are utilized across multiple M365 stacks.</span></span> <span data-ttu-id="e3a11-999">Microsoft 365 인증은 여러 M365 서비스에서 앱/추가 기능을 개발하는 위치를 지원하기는 하지만, 해당하는 각 "호스트된 형식 매핑"에 따라 지원 환경 전체(앱/추가 기능 전체)에 대한 평가를 평가해야 합니다.</span><span class="sxs-lookup"><span data-stu-id="e3a11-999">Although the Microsoft 365 Certification will support where apps/add-ons across multiple M365 services are developed, an assessment of the entire (across app/add-ins) supporting environment would need to be assessed in line with each of the applicable "Hosted Type Mappings".</span></span> <span data-ttu-id="e3a11-1000">경우에 따라 단일 추가 기능에서 서로 다른 호스팅된 형식을 사용할 수 있습니다. 이 경우 조건의 적용 가능성은 다양한 호스트 형식에서 "호스트된 형식 매핑" 기준을 따라야 합니다.</span><span class="sxs-lookup"><span data-stu-id="e3a11-1000">Occasionally, you may utilize different hosted types for a single add-in, where this is being carried out, applicability of criteria will need to still follow the "Hosted Type Mappings" criteria across the various hosted types.</span></span>|
|<span data-ttu-id="e3a11-1001">**공유 호스팅**</span><span class="sxs-lookup"><span data-stu-id="e3a11-1001">**Shared Hosting**</span></span>|<span data-ttu-id="e3a11-1002">공유 호스팅은 여러 개별 소비자가 공유하는 플랫폼 내에서 환경을 호스팅하는 위치입니다.</span><span class="sxs-lookup"><span data-stu-id="e3a11-1002">Shared hosting is where you are hosting the environment within a platform that shared by multiple individual consumers.</span></span> <span data-ttu-id="e3a11-1003">클라우드 채택으로 인해 Microsoft 365 인증 사양이 작성되지 않은 경우 공유 호스팅이 일반적이지 않습니다.</span><span class="sxs-lookup"><span data-stu-id="e3a11-1003">The Microsoft 365 Certification Specification was not written to account for this due to the adoption of cloud, shared hosting is not common.</span></span> <span data-ttu-id="e3a11-1004">이 사용이 필요하다고 생각되는 경우 Microsoft에 문의하여 이 유형의 호스팅 유형에 따라 추가 위험을 고려하기 위해 추가 요구 사항을 만들어야 합니다.</span><span class="sxs-lookup"><span data-stu-id="e3a11-1004">If you believe this is being used please contact Microsoft as additional requirements will need to be created to account for the additional risks under this type of hosting type.</span></span>|


## <a name="appendix-g"></a><span data-ttu-id="e3a11-1005">부록 G</span><span class="sxs-lookup"><span data-stu-id="e3a11-1005">Appendix G</span></span>

### <a name="microsoft-365-certification-process-workflow"></a><span data-ttu-id="e3a11-1006">Microsoft 365 인증 프로세스 워크플로</span><span class="sxs-lookup"><span data-stu-id="e3a11-1006">Microsoft 365 Certification Process Workflow</span></span>

![워크플로](ProcessFlow.jpg)

## <a name="learn-more"></a><span data-ttu-id="e3a11-1008">자세한 정보</span><span class="sxs-lookup"><span data-stu-id="e3a11-1008">Learn more</span></span>

[<span data-ttu-id="e3a11-1009">Microsoft 365 앱 준수 프로그램 개요</span><span class="sxs-lookup"><span data-stu-id="e3a11-1009">Microsoft 365 App Compliance Program Overview</span></span>](~/overview.md)  
[<span data-ttu-id="e3a11-1010">Microsoft 365 앱 게시자 Attestation이란?</span><span class="sxs-lookup"><span data-stu-id="e3a11-1010">What is Microsoft 365 App Publisher Attestation?</span></span>](~/docs/attestation.md)  
[<span data-ttu-id="e3a11-1011">Microsoft 365 인증이란?</span><span class="sxs-lookup"><span data-stu-id="e3a11-1011">What is Microsoft 365 Certification?</span></span>](~/docs/enterprise-app-certification-guide.md)

## <a name="glossary"></a><span data-ttu-id="e3a11-1012">용어집</span><span class="sxs-lookup"><span data-stu-id="e3a11-1012">Glossary</span></span>

### <a name="aia"></a><span data-ttu-id="e3a11-1013">AIA</span><span class="sxs-lookup"><span data-stu-id="e3a11-1013">AIA</span></span>

<span data-ttu-id="e3a11-1014">\*기관 정보 액세스는 발급 인증 기관의 인증서를 찾는 데 사용되는 서비스 위치 설명자입니다.</span><span class="sxs-lookup"><span data-stu-id="e3a11-1014">\*Authority Information Access is a service location descriptor used to find the certificate of the issuing certificate authority.</span></span>

### <a name="crl"></a><span data-ttu-id="e3a11-1015">CRL</span><span class="sxs-lookup"><span data-stu-id="e3a11-1015">CRL</span></span>

<span data-ttu-id="e3a11-1016">\*인증서 해지 목록은 SSL(Secure Sockets Layer) 끝점을 통해 원격 호스트에서 받은 인증서가 유효하고 신뢰할 수 있는지 확인할 수 있는 수단을 제공합니다.</span><span class="sxs-lookup"><span data-stu-id="e3a11-1016">\*Certificate Revocation List provide a means for a Secure Sockets Layer (SSL) endpoint to verify that a certificate received from a remote host is valid and trustworthy.</span></span>

### <a name="cvss-score"></a><span data-ttu-id="e3a11-1017">CVSS 점수</span><span class="sxs-lookup"><span data-stu-id="e3a11-1017">CVSS score</span></span>

<span data-ttu-id="e3a11-1018">\*공통 취약성 점수 체계는 취약점을 측정하고 심각도에 따라 숫자 점수를 계산하는 게시된 표준입니다.</span><span class="sxs-lookup"><span data-stu-id="e3a11-1018">\*Common Vulnerability Scoring System is a published standard that measures vulnerability and calculates a numerical score based on its severity.</span></span>

### <a name="cvss-patch-management-guidelines"></a><span data-ttu-id="e3a11-1019">CVSS 패치 관리 지침</span><span class="sxs-lookup"><span data-stu-id="e3a11-1019">CVSS patch management guidelines</span></span>

* <span data-ttu-id="e3a11-1020">Critical(9.0 - 10.0)</span><span class="sxs-lookup"><span data-stu-id="e3a11-1020">Critical (9.0 - 10.0)</span></span>
* <span data-ttu-id="e3a11-1021">높음(7.0 - 8.9)</span><span class="sxs-lookup"><span data-stu-id="e3a11-1021">High (7.0 - 8.9)</span></span>
* <span data-ttu-id="e3a11-1022">보통(4.0 - 6.9)</span><span class="sxs-lookup"><span data-stu-id="e3a11-1022">Medium (4.0 - 6.9)</span></span>
* <span data-ttu-id="e3a11-1023">낮음(0.0 - 3.9)</span><span class="sxs-lookup"><span data-stu-id="e3a11-1023">Low (0.0 - 3.9)</span></span>

### <a name="dmz"></a><span data-ttu-id="e3a11-1024">DMZ</span><span class="sxs-lookup"><span data-stu-id="e3a11-1024">DMZ</span></span>

<span data-ttu-id="e3a11-1025">\*비미리타입 영역은 호스트의 내부 개인 네트워크를 분리하고 격리하면서 외부 또는 비소유 네트워크와 직접 상호 작용하는 물리적 또는 논리적 중간 네트워크입니다.</span><span class="sxs-lookup"><span data-stu-id="e3a11-1025">\*Demilitarized zone is a physical or logical intermediate network that interacts directly external or non-propriety networks while keeping the host's internal, private network separate and isolated.</span></span>

### <a name="euii"></a><span data-ttu-id="e3a11-1026">EUII</span><span class="sxs-lookup"><span data-stu-id="e3a11-1026">EUII</span></span>

<span data-ttu-id="e3a11-1027">*최종 사용자 식별 가능 정보.*</span><span class="sxs-lookup"><span data-stu-id="e3a11-1027">*End-user identifiable information*.</span></span>

### <a name="gdpr"></a><span data-ttu-id="e3a11-1028">GDPR</span><span class="sxs-lookup"><span data-stu-id="e3a11-1028">GDPR</span></span>

<span data-ttu-id="e3a11-1029">\*일반 데이터 보호 규정은 응용 프로그램 사이트가 있는 위치와 관계없이 모든 EU 시민 데이터에 대한 유럽 연합(EU) 개인 정보 보호 및 데이터 보호 규정입니다.</span><span class="sxs-lookup"><span data-stu-id="e3a11-1029">\*General Data Protection Regulation is a European Union (EU) privacy and data protection regulation for all EU citizens’ data regardless of where your application site is located.</span></span>

### <a name="hsts"></a><span data-ttu-id="e3a11-1030">HSTS</span><span class="sxs-lookup"><span data-stu-id="e3a11-1030">HSTS</span></span>

<span data-ttu-id="e3a11-1031">\*HTTP Strict Transport Security는 HTTPS를 통해 콘텐츠에만 액세스하는 웹 브라우저에 지시하는 HTTP 응답 헤더를 사용합니다.</span><span class="sxs-lookup"><span data-stu-id="e3a11-1031">\*HTTP Strict Transport Security utilizes a HTTP response header instructing the web browser to only access content over HTTPS.</span></span>  <span data-ttu-id="e3a11-1032">이는 다운그레이드 공격 및 쿠키 하이재킹으로부터 보호하기 위해 고안된 것입니다.</span><span class="sxs-lookup"><span data-stu-id="e3a11-1032">This is designed to protect against downgrade attacks and cookie hijacking.</span></span>

### <a name="iec"></a><span data-ttu-id="e3a11-1033">IEC</span><span class="sxs-lookup"><span data-stu-id="e3a11-1033">IEC</span></span>

<span data-ttu-id="e3a11-1034">\*International Electrotechnical Commission.</span><span class="sxs-lookup"><span data-stu-id="e3a11-1034">\*International Electrotechnical Commission.</span></span>

### <a name="isms"></a><span data-ttu-id="e3a11-1035">ISMS</span><span class="sxs-lookup"><span data-stu-id="e3a11-1035">ISMS</span></span>

<span data-ttu-id="e3a11-1036">\*정보 보안 관리 시스템.</span><span class="sxs-lookup"><span data-stu-id="e3a11-1036">\*Information Security Management System.</span></span>

### <a name="isv"></a><span data-ttu-id="e3a11-1037">ISV</span><span class="sxs-lookup"><span data-stu-id="e3a11-1037">ISV</span></span>

<span data-ttu-id="e3a11-1038">독립 보안 공급업체는 타사 소프트웨어 및 하드웨어 플랫폼에서 실행되는 소프트웨어를 개발, 출시 및 판매하는 개인 및 조직입니다.</span><span class="sxs-lookup"><span data-stu-id="e3a11-1038">Independent Security Vendors are individuals and organizations who develop, market and sell software that runs on third-party software and hardware platforms.</span></span>

### <a name="iso-27001"></a><span data-ttu-id="e3a11-1039">ISO 27001</span><span class="sxs-lookup"><span data-stu-id="e3a11-1039">ISO 27001</span></span>

<span data-ttu-id="e3a11-1040">조직 위험 관리 정책 및 절차 프로세스의 모든 기술 제어를 위한 정보 보안 관리 시스템 사양 프레임워크입니다.</span><span class="sxs-lookup"><span data-stu-id="e3a11-1040">An information security management system specification framework for all technical controls in an organizations risk management policies and procedures processes.</span></span>

### <a name="lfi"></a><span data-ttu-id="e3a11-1041">LFI</span><span class="sxs-lookup"><span data-stu-id="e3a11-1041">LFI</span></span>

<span data-ttu-id="e3a11-1042">*로컬 파일 포함을* 사용하면 공격자가 웹 브라우저를 통해 서버에 파일을 포함할 수 있습니다.</span><span class="sxs-lookup"><span data-stu-id="e3a11-1042">*Local File Inclusion* allows an attacker to include files on a server through the web browser.</span></span>

### <a name="nist"></a><span data-ttu-id="e3a11-1043">NIST</span><span class="sxs-lookup"><span data-stu-id="e3a11-1043">NIST</span></span>

<span data-ttu-id="e3a11-1044">미국 상무부의 비규격 기관인 NIST(National *Institute of Standards)는* 미국 내 개인 부문 조직이 사이버 공격을 방지, 탐지 및 대응하는 능력을 평가하고 승인할 수 있는 지침을 제공합니다.</span><span class="sxs-lookup"><span data-stu-id="e3a11-1044">The *National Institute of Standards* (NIST), a non-regulatory agency of the U.S. Department of Commerce  provides guidance for private sector organizations in the US to assess and approve their ability to prevent, detect, and respond to cyber attacks.</span></span>

### <a name="non-significant-changes"></a><span data-ttu-id="e3a11-1045">중요하지 않은 변경 내용</span><span class="sxs-lookup"><span data-stu-id="e3a11-1045">Non-Significant changes</span></span>

* <span data-ttu-id="e3a11-1046">경미한 버그 수정.</span><span class="sxs-lookup"><span data-stu-id="e3a11-1046">Minor Bug fixes.</span></span>
* <span data-ttu-id="e3a11-1047">성능이 사소하게 향상됩니다.</span><span class="sxs-lookup"><span data-stu-id="e3a11-1047">Minor performance improvements.</span></span>
* <span data-ttu-id="e3a11-1048">운영 체제/라이브러리/클라이언트 및 서버 응용 프로그램 패치.</span><span class="sxs-lookup"><span data-stu-id="e3a11-1048">Operating systems/libraries/client and server application patches.</span></span>

### <a name="ocsp"></a><span data-ttu-id="e3a11-1049">OCSP</span><span class="sxs-lookup"><span data-stu-id="e3a11-1049">OCSP</span></span>

<span data-ttu-id="e3a11-1050">*온라인 인증서 상태 프로토콜은* X.509 디지털 인증서의 해지 상태를 검사하는 데 사용됩니다.</span><span class="sxs-lookup"><span data-stu-id="e3a11-1050">*Online Certificate Status Protocol* is used to check the revocation status of X.509 digital certificates.</span></span>

### <a name="oii"></a><span data-ttu-id="e3a11-1051">OII</span><span class="sxs-lookup"><span data-stu-id="e3a11-1051">OII</span></span>

<span data-ttu-id="e3a11-1052">*조직 식별이 가능한 정보입니다.*</span><span class="sxs-lookup"><span data-stu-id="e3a11-1052">*Organizational identifiable information*.</span></span>

### <a name="owasp"></a><span data-ttu-id="e3a11-1053">OWASP</span><span class="sxs-lookup"><span data-stu-id="e3a11-1053">OWASP</span></span>

<span data-ttu-id="e3a11-1054">*웹 응용 프로그램 보안 프로젝트를 여는 경우.*</span><span class="sxs-lookup"><span data-stu-id="e3a11-1054">*Open Web Application Security Project*.</span></span>

### <a name="pci-dss"></a><span data-ttu-id="e3a11-1055">PCI DSS</span><span class="sxs-lookup"><span data-stu-id="e3a11-1055">PCI DSS</span></span>

<span data-ttu-id="e3a11-1056">*Payment Card Industry Data Security Standard*- 전 세계 카드주 데이터의 안전에 대한 표준을 유지하는 조직입니다.</span><span class="sxs-lookup"><span data-stu-id="e3a11-1056">*Payment Card Industry Data Security Standard*, an organization that maintains standards for the safety of cardholder data worldwide.</span></span>

### <a name="pen-testing"></a><span data-ttu-id="e3a11-1057">펜 테스트</span><span class="sxs-lookup"><span data-stu-id="e3a11-1057">Pen testing</span></span>

<span data-ttu-id="e3a11-1058">*침투 테스트는* 악의적인 공격을 시뮬레이션하여 공격자가 악용할 수 있는 보안 취약성을 찾아 웹앱을 테스트하는 방법입니다.</span><span class="sxs-lookup"><span data-stu-id="e3a11-1058">*Penetration testing* is a method of testing a web app by simulating malicious attacks to find security vulnerabilities that an attacker could exploit.</span></span>

### <a name="saml"></a><span data-ttu-id="e3a11-1059">SAML</span><span class="sxs-lookup"><span data-stu-id="e3a11-1059">SAML</span></span>

<span data-ttu-id="e3a11-1060">*Security Assertion Markup Language는* 사용자, ID 공급자 및 서비스 공급자 간의 인증 및 권한 부여 데이터를 변경하기 위한 개방형 표준입니다.</span><span class="sxs-lookup"><span data-stu-id="e3a11-1060">*Security Assertion Markup Language* is s an open standard for exchanging authentication and authorization data between the user, the identity provider and the service provider.</span></span>

### <a name="sensitive-data"></a><span data-ttu-id="e3a11-1061">중요한 데이터</span><span class="sxs-lookup"><span data-stu-id="e3a11-1061">Sensitive Data</span></span>

* <span data-ttu-id="e3a11-1062">액세스 제어 데이터.</span><span class="sxs-lookup"><span data-stu-id="e3a11-1062">Access control data.</span></span>
* <span data-ttu-id="e3a11-1063">고객 콘텐츠.</span><span class="sxs-lookup"><span data-stu-id="e3a11-1063">Customer content.</span></span>
* <span data-ttu-id="e3a11-1064">최종 사용자 ID 정보입니다.</span><span class="sxs-lookup"><span data-stu-id="e3a11-1064">End-user identity information.</span></span>
* <span data-ttu-id="e3a11-1065">지원 데이터.</span><span class="sxs-lookup"><span data-stu-id="e3a11-1065">Support data.</span></span>
* <span data-ttu-id="e3a11-1066">공용 개인 데이터.</span><span class="sxs-lookup"><span data-stu-id="e3a11-1066">Public personal data.</span></span>
* <span data-ttu-id="e3a11-1067">최종 사용자 가명 정보.</span><span class="sxs-lookup"><span data-stu-id="e3a11-1067">End-user pseudonymous information.</span></span>

### <a name="significant-changes"></a><span data-ttu-id="e3a11-1068">중요한 변경 사항</span><span class="sxs-lookup"><span data-stu-id="e3a11-1068">Significant changes</span></span>

* <span data-ttu-id="e3a11-1069">호스팅 환경의 위치입니다.</span><span class="sxs-lookup"><span data-stu-id="e3a11-1069">Relocation of the hosting environment.</span></span>
* <span data-ttu-id="e3a11-1070">지원 인프라로의 주요 업그레이드 예를 들어 새 방화벽 구현, 전면 서비스에 대한 주요 업그레이드 등</span><span class="sxs-lookup"><span data-stu-id="e3a11-1070">Major upgrades to the supporting infrastructure; for example, implementation of a new firewall, major upgrades to front facing services, etc.</span></span>
* <span data-ttu-id="e3a11-1071">앱에 기능 및 /또는 확장 추가.</span><span class="sxs-lookup"><span data-stu-id="e3a11-1071">Addition of capabilities and /or extensions to your app.</span></span>
* <span data-ttu-id="e3a11-1072">추가 중요한 데이터를 캡처하는 앱 업데이트입니다.</span><span class="sxs-lookup"><span data-stu-id="e3a11-1072">Updates to your app that capture additional sensitive Data.</span></span>
* <span data-ttu-id="e3a11-1073">앱의 데이터 흐름 또는 권한 부여 모델 변경</span><span class="sxs-lookup"><span data-stu-id="e3a11-1073">Changes to your app's data flows or authorization models</span></span>
* <span data-ttu-id="e3a11-1074">API 끝점 또는 API 끝점 함수 추가.</span><span class="sxs-lookup"><span data-stu-id="e3a11-1074">Addition of API endpoints or API endpoint functions.</span></span>

### <a name="soc-2"></a><span data-ttu-id="e3a11-1075">SOC 2</span><span class="sxs-lookup"><span data-stu-id="e3a11-1075">SOC 2</span></span>

<span data-ttu-id="e3a11-1076">*서비스 조직 제어 2*: 서비스 공급자가 조직의 클라이언트에 대한 데이터 및 개인 정보를 안전하게 관리하도록 보장하기 위해 5개의 보안 서비스 원칙으로 구성된 기술 감사 절차입니다.</span><span class="sxs-lookup"><span data-stu-id="e3a11-1076">*Service Organization Control 2*, a technical auditing procedure comprised of five Trust Service Principles to ensure that service providers securely manage the data and privacy for an organization's clients.</span></span>

### <a name="ssl"></a><span data-ttu-id="e3a11-1077">SSL</span><span class="sxs-lookup"><span data-stu-id="e3a11-1077">SSL</span></span>

<span data-ttu-id="e3a11-1078">*Secure Sockets Layer*.</span><span class="sxs-lookup"><span data-stu-id="e3a11-1078">*Secure Sockets Layer*.</span></span>

### <a name="tls"></a><span data-ttu-id="e3a11-1079">TLS</span><span class="sxs-lookup"><span data-stu-id="e3a11-1079">TLS</span></span>

<span data-ttu-id="e3a11-1080">*전송 계층 보안*.</span><span class="sxs-lookup"><span data-stu-id="e3a11-1080">*Transport Layer Security*.</span></span>
