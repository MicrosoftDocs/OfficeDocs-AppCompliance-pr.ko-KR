---
title: SaaS 앱용 사용자 가이드
author: LGerrard
ms.author: legerrar
description: 앱 준수 Microsoft 365 SaaS용 ISV 사용자 가이드
keywords: 앱 준수 Microsoft 365 SaaS용 ISV 사용자 가이드
ms.topic: conceptual
ms.service: attestation
ms.openlocfilehash: b3b8c37a1babf2f941f5764fddd30523319d9a34
ms.sourcegitcommit: f6f3551bf1c00013efb6313ca3dc280de697137d
ms.translationtype: MT
ms.contentlocale: ko-KR
ms.lasthandoff: 06/29/2021
ms.locfileid: "53202779"
---
# <a name="partners-user-guide-for-microsoft-365-app-compliance-program---saas"></a><span data-ttu-id="a5fc9-104">앱 준수 프로그램에 대한 파트너의 Microsoft 365 가이드 - SaaS</span><span class="sxs-lookup"><span data-stu-id="a5fc9-104">Partner's User Guide for Microsoft 365 App Compliance Program - SaaS</span></span>

|<span data-ttu-id="a5fc9-105">작업 단계</span><span class="sxs-lookup"><span data-stu-id="a5fc9-105">Phase</span></span>|<span data-ttu-id="a5fc9-106">제목</span><span class="sxs-lookup"><span data-stu-id="a5fc9-106">Title</span></span>|
|---|---|
|<span data-ttu-id="a5fc9-107">1단계</span><span class="sxs-lookup"><span data-stu-id="a5fc9-107">Phase 1</span></span>| <span data-ttu-id="a5fc9-108">게시자 증명</span><span class="sxs-lookup"><span data-stu-id="a5fc9-108">Publisher Attestation</span></span>|
|<span data-ttu-id="a5fc9-109">2단계</span><span class="sxs-lookup"><span data-stu-id="a5fc9-109">Phase 2</span></span>| <span data-ttu-id="a5fc9-110">Microsoft 365 인증</span><span class="sxs-lookup"><span data-stu-id="a5fc9-110">Microsoft 365 Certification</span></span>|

## <a name="1-overview"></a><span data-ttu-id="a5fc9-111">1. 개요</span><span class="sxs-lookup"><span data-stu-id="a5fc9-111">1. Overview</span></span> 

<span data-ttu-id="a5fc9-112">이 문서는 파트너 센터 포털을 통해 SaaS 앱에 대한 Publisher 증명 및 인증을 획득하기 위한 Microsoft 365 앱 준수 프로그램에 등록된 파트너를 위한 단계별 사용자 가이드 역할을 합니다.</span><span class="sxs-lookup"><span data-stu-id="a5fc9-112">This document acts as a step-by-step user guide for our partners, enrolled for Microsoft 365 App Compliance program aiming to undergo Publisher Attestation and Certification for their SaaS apps, though the Partner Center portal.</span></span>

## <a name="2-acronyms--definitions"></a><span data-ttu-id="a5fc9-113">2. 약어 & 정의</span><span class="sxs-lookup"><span data-stu-id="a5fc9-113">2. Acronyms & Definitions</span></span>
|<span data-ttu-id="a5fc9-114">두문자어</span><span class="sxs-lookup"><span data-stu-id="a5fc9-114">Acronym</span></span> | <span data-ttu-id="a5fc9-115">정의</span><span class="sxs-lookup"><span data-stu-id="a5fc9-115">Definition</span></span> |
|----|----|
|[<span data-ttu-id="a5fc9-116">PC(파트너 센터)</span><span class="sxs-lookup"><span data-stu-id="a5fc9-116">PC (Partner Center)</span></span>](https://partner.microsoft.com/)|<span data-ttu-id="a5fc9-117">모든 Microsoft 파트너를 위한 포털입니다.</span><span class="sxs-lookup"><span data-stu-id="a5fc9-117">A portal for all Microsoft partners.</span></span> <span data-ttu-id="a5fc9-118">파트너는 파트너 센터에 로그인하고 자체 평가 설문서를 제출합니다.</span><span class="sxs-lookup"><span data-stu-id="a5fc9-118">A partner logs in to Partner Center and submits self-assessment questionnaire.</span></span> <span data-ttu-id="a5fc9-119">앱 준수를 [Microsoft 365 파트너 센터](https://partner.microsoft.com/dashboard/home)</span><span class="sxs-lookup"><span data-stu-id="a5fc9-119">Partner Center for [Microsoft 365 App Compliance](https://partner.microsoft.com/dashboard/home)</span></span>|
|<span data-ttu-id="a5fc9-120">ISV</span><span class="sxs-lookup"><span data-stu-id="a5fc9-120">ISV</span></span> | <span data-ttu-id="a5fc9-121">Independent Software Vendor a.k.a.</span><span class="sxs-lookup"><span data-stu-id="a5fc9-121">Independent Software Vendor a.k.a.</span></span> <span data-ttu-id="a5fc9-122">파트너 또는 개발자</span><span class="sxs-lookup"><span data-stu-id="a5fc9-122">Partner or Developer</span></span> |
|<span data-ttu-id="a5fc9-123">앱 원본</span><span class="sxs-lookup"><span data-stu-id="a5fc9-123">App Source</span></span> | <span data-ttu-id="a5fc9-124">앱 카탈로그</span><span class="sxs-lookup"><span data-stu-id="a5fc9-124">Catalog of apps</span></span> |
|<span data-ttu-id="a5fc9-125">예시</span><span class="sxs-lookup"><span data-stu-id="a5fc9-125">Example</span></span> |[<span data-ttu-id="a5fc9-126">이제 가상 에이전트</span><span class="sxs-lookup"><span data-stu-id="a5fc9-126">Now virtual agent</span></span>](https://appsource.microsoft.com/product/office/WA104381816)|

## <a name="3-publisher-attestation-workflow"></a><span data-ttu-id="a5fc9-127">3. Publisher 워크플로</span><span class="sxs-lookup"><span data-stu-id="a5fc9-127">3. Publisher Attestation Workflow</span></span>

<span data-ttu-id="a5fc9-128">**홈페이지:** 파트너가 파트너 센터에 로그인하면 방문 페이지입니다.</span><span class="sxs-lookup"><span data-stu-id="a5fc9-128">**Home Page**: This is the landing page once a partner logs in to Partner Center.</span></span>

![파트너 센터 홈 화면](../media/Saas1.PNG)
  
<span data-ttu-id="a5fc9-130">**1단계:** 페이지 왼쪽의 탐색 모음에서 다음을 진행합니다.</span><span class="sxs-lookup"><span data-stu-id="a5fc9-130">**Step 1** : On the left side of the page, on the navigation bar:</span></span>

- <span data-ttu-id="a5fc9-131">상업용 마켓플레이스 선택</span><span class="sxs-lookup"><span data-stu-id="a5fc9-131">Select Commercial Marketplace</span></span>
- <span data-ttu-id="a5fc9-132">개요 선택</span><span class="sxs-lookup"><span data-stu-id="a5fc9-132">Select Overview</span></span>

![파트너 센터의 상업용 마켓플레이스](../media/Saas2.PNG)
  
<span data-ttu-id="a5fc9-134">'개요'를 선택하면 파트너는 앱 준수 프로그램을 시작하는 데 사용할 수 있는 앱 Microsoft 365 있습니다.</span><span class="sxs-lookup"><span data-stu-id="a5fc9-134">Upon selecting ‘Overview’, partner can see list of apps available to start the Microsoft 365 Compliance program.</span></span>
  
<span data-ttu-id="a5fc9-135">**2단계:** 목록에서 앱을 선택하여 Publisher 프로세스를 시작할 수 있습니다.</span><span class="sxs-lookup"><span data-stu-id="a5fc9-135">**Step 2**: Select an app from the list to begin the Publisher Attestation process.</span></span>

![상업용 마켓플레이스에서 앱 선택](../media/Saas3.PNG)

<span data-ttu-id="a5fc9-137">앱을 선택하면 다른 탐색 모음에 '앱 준수' 옵션이 팝업됩니다.</span><span class="sxs-lookup"><span data-stu-id="a5fc9-137">On selecting an app, another navigation bar will pop up with option ‘App Compliance’.</span></span>
  
<span data-ttu-id="a5fc9-138">**3단계:**'앱 준수' 선택</span><span class="sxs-lookup"><span data-stu-id="a5fc9-138">**Step 3**: Select 'App Compliance’</span></span>
  
![상업용 마켓플레이스의 앱 준수](../media/Saas4.PNG)
  
<span data-ttu-id="a5fc9-140">**4단계:** 자가 평가 설문지에서 Publisher 작성합니다.</span><span class="sxs-lookup"><span data-stu-id="a5fc9-140">**Step 4**: Fill out the self-assessment questionnaire for Publisher Attestation.</span></span>

![전체 Publisher Attestation](../media/UserGuidePhotos/5.5.png)
  
<span data-ttu-id="a5fc9-142">**참고 응용 프로그램을 업데이트/다시 제출할 예정인 경우 '제품 선택'에 대한 드롭다운을 클릭하고 앱을 선택하고 '복제'를 클릭합니다.**</span><span class="sxs-lookup"><span data-stu-id="a5fc9-142">**NOTE If you are coming back to update/re-submit your application, click dropdown for ‘Choose the product’, select the app and click ‘Clone’.**</span></span>

![복제 기능](../media/UserGuidePhotos/05.png)

<span data-ttu-id="a5fc9-144">**양식의 전체 Import/Export 사용하여 양식을 오프라인으로 완성하고 완료되면 가져올 수 있습니다.**</span><span class="sxs-lookup"><span data-stu-id="a5fc9-144">**You can also leverage the Import/Export feature to complete the form offline and import it once completed.**</span></span>

![내보내기 기능 가져오기](../media/UserGuidePhotos/06.png)
 
<span data-ttu-id="a5fc9-146">**5단계:** 완료되면 '제출'을 클릭하면 평가가 '검토 중'이 됩니다.</span><span class="sxs-lookup"><span data-stu-id="a5fc9-146">**Step 5**: Once completed, click on ‘Submit’, the assessment will now be ‘Under Review’.</span></span>
 
 <span data-ttu-id="a5fc9-147">![제출 Publisher 제출 확인 ](../media/UserGuidePhotos/07.png) ![ 제출](../media/UserGuidePhotos/08.png)</span><span class="sxs-lookup"><span data-stu-id="a5fc9-147">![Submit Publisher Attesation](../media/UserGuidePhotos/07.png) ![Confirmation of submission](../media/UserGuidePhotos/08.png)</span></span>
  
<span data-ttu-id="a5fc9-148">**승인/거부 시나리오:**</span><span class="sxs-lookup"><span data-stu-id="a5fc9-148">**Approve/Reject Scenarios:**</span></span>
  
<span data-ttu-id="a5fc9-149">대답.</span><span class="sxs-lookup"><span data-stu-id="a5fc9-149">A.</span></span> <span data-ttu-id="a5fc9-150">Publisher 퇴장 거부</span><span class="sxs-lookup"><span data-stu-id="a5fc9-150">Publisher Attestation Rejection</span></span>
- <span data-ttu-id="a5fc9-151">거부의 경우 파트너는 다음을 할 수 있습니다.</span><span class="sxs-lookup"><span data-stu-id="a5fc9-151">In case of rejection, a partner can:</span></span>
     - <span data-ttu-id="a5fc9-152">실패 보고서 보기</span><span class="sxs-lookup"><span data-stu-id="a5fc9-152">View failure report</span></span>
          - <span data-ttu-id="a5fc9-153">파트너는 전자 메일을 통해 알림을 보내며 파트너 센터에서 오류 보고서를 볼 수 있습니다.</span><span class="sxs-lookup"><span data-stu-id="a5fc9-153">Partner will be notified via email, and they can view the failure report in Partner Center</span></span>
     - <span data-ttu-id="a5fc9-154">자체 평가 설문지 업데이트 및 다시 제출</span><span class="sxs-lookup"><span data-stu-id="a5fc9-154">Update and re-submit self-assessment questionnaire.</span></span>
        
![Publisher 거부된 Attestation](../media/UserGuidePhotos/09.png)

<span data-ttu-id="a5fc9-156">B.</span><span class="sxs-lookup"><span data-stu-id="a5fc9-156">B.</span></span>  <span data-ttu-id="a5fc9-157">Publisher 의거 승인</span><span class="sxs-lookup"><span data-stu-id="a5fc9-157">Publisher Attestation Approval</span></span>
- <span data-ttu-id="a5fc9-158">파트너는 승인 시 다음을 할 수 있습니다.</span><span class="sxs-lookup"><span data-stu-id="a5fc9-158">Upon approval, the partner can:</span></span>
     - <span data-ttu-id="a5fc9-159">업데이트 및 다시 제출 attestation</span><span class="sxs-lookup"><span data-stu-id="a5fc9-159">Update and resubmit attestation</span></span>
     - <span data-ttu-id="a5fc9-160">완료된 Publisher 보기</span><span class="sxs-lookup"><span data-stu-id="a5fc9-160">View completed Publisher Attestation</span></span>
     - <span data-ttu-id="a5fc9-161">인증 Microsoft 365 시작</span><span class="sxs-lookup"><span data-stu-id="a5fc9-161">Start the Microsoft 365 Certification process</span></span>
        
 ![Publisher Attestation Completed](../media/UserGuidePhotos/10.png)       
  
 ![Microsoft 365 인증 시작](../media/UserGuidePhotos/11.png)
  
<span data-ttu-id="a5fc9-164">**Post Publisher Attestation Approval: Example of link in AppSource for publisher attested apps.**</span><span class="sxs-lookup"><span data-stu-id="a5fc9-164">**Post Publisher Attestation Approval: Example of link in AppSource for publisher attested apps.**</span></span>
  
![승인된 연락처 예제](../media/UserGuidePhotos/12.png)
   
## <a name="4---microsoft-365-certification-workflow"></a><span data-ttu-id="a5fc9-166">4. Microsoft 365 워크플로</span><span class="sxs-lookup"><span data-stu-id="a5fc9-166">4.   Microsoft 365 Certification Workflow</span></span>
  
<span data-ttu-id="a5fc9-167">파트너는 확인란을 선택하고 '제출'을 클릭하여 인증 프로세스를 시작할 수 있습니다.</span><span class="sxs-lookup"><span data-stu-id="a5fc9-167">A partner can begin the Certification process by selecting the checkbox and clicking ‘Submit’</span></span>
  
![인증 Microsoft 365 시작](../media/UserGuidePhotos/13.png) 
  
<span data-ttu-id="a5fc9-169">**1단계:** 초기 문서 제출</span><span class="sxs-lookup"><span data-stu-id="a5fc9-169">**Step 1** : Initial Document Submission</span></span>

<span data-ttu-id="a5fc9-170">모든 세부 정보를 입력하고 관련 문서를 업로드하고 '제출'을 클릭합니다.</span><span class="sxs-lookup"><span data-stu-id="a5fc9-170">Fill out all the details, upload relevant documents and click ‘Submit’</span></span>
  
<span data-ttu-id="a5fc9-171">![초기 문서 제출 ](../media/UserGuidePhotos/14.png) 
 ![ 초기 문서 제출](../media/UserGuidePhotos/15.png)</span><span class="sxs-lookup"><span data-stu-id="a5fc9-171">![Initial Document Submission](../media/UserGuidePhotos/14.png) 
![Submit Initial Document Submission](../media/UserGuidePhotos/15.png)</span></span>
  
<span data-ttu-id="a5fc9-172">제출을 클릭하면 초기 문서 제출이 검토됩니다.</span><span class="sxs-lookup"><span data-stu-id="a5fc9-172">On clicking submit, the initial document submission will be under review.</span></span>

![검토 중 초기 문서 제출](../media/UserGuidePhotos/16.png)
  
<span data-ttu-id="a5fc9-174">초기 문서가 충분하지 않을 경우 분석가가 개정을 요청합니다.</span><span class="sxs-lookup"><span data-stu-id="a5fc9-174">An analyst requests a revision in case the initial documents are not sufficient or relevant.</span></span> <span data-ttu-id="a5fc9-175">분석가가 파트너와 협력하여 승인을 위해 올바른 문서를 얻습니다.</span><span class="sxs-lookup"><span data-stu-id="a5fc9-175">The analyst will work with the partner to help get the right documents for approval.</span></span>

![필요한 업데이트](../media/UserGuidePhotos/17.png)

<span data-ttu-id="a5fc9-177">분석가가 초기 문서 제출을 승인하면 파트너는 제어 요구 사항을 제출해야 합니다.</span><span class="sxs-lookup"><span data-stu-id="a5fc9-177">Once the analyst approves the initial document submission, the partner needs to submit the control requirements.</span></span>
  
<span data-ttu-id="a5fc9-178">**2단계:** 제어 요구 사항 제출</span><span class="sxs-lookup"><span data-stu-id="a5fc9-178">**Step 2**: Control Requirement Submission</span></span>
  
<span data-ttu-id="a5fc9-179">모든 세부 정보를 입력하고 관련 문서를 업로드하고 '제출'을 클릭합니다.</span><span class="sxs-lookup"><span data-stu-id="a5fc9-179">Fill out all the details, upload relevant documents and Click ‘Submit’</span></span>

![전체 제어 요구 사항](../media/UserGuidePhotos/18.png)
  
![업로드 제어 요구 사항](../media/UserGuidePhotos/19.png)

![제어 요구 사항 충족](../media/UserGuidePhotos/20.png)
 
<span data-ttu-id="a5fc9-183">제출을 클릭하면 초기 문서 제출이 검토됩니다.</span><span class="sxs-lookup"><span data-stu-id="a5fc9-183">On clicking Submit, the initial document submission will be under review.</span></span>

![검토 중 제출](../media/UserGuidePhotos/21.png)
  
<span data-ttu-id="a5fc9-185">분석가가 제어 요구 사항 문서가 충분하지 않은 경우 또는 관련성이 없는 경우 개정을 요청합니다.</span><span class="sxs-lookup"><span data-stu-id="a5fc9-185">An analyst requests a revision in case the control requirement documents are not sufficient or relevant.</span></span> <span data-ttu-id="a5fc9-186">분석가가 파트너와 협력하여 승인을 위해 올바른 문서를 얻습니다.</span><span class="sxs-lookup"><span data-stu-id="a5fc9-186">The analyst will work with the partner to help get the right documents for approval.</span></span>

![증거 요구 업데이트](../media/UserGuidePhotos/22.png)

![업데이트해야 하는 컨트롤](../media/UserGuidePhotos/23.png)
  
![검토 진행 중](../media/UserGuidePhotos/24.png) 
 
<span data-ttu-id="a5fc9-190">제출이 승인 표준을 충족하지 않는 경우 분석가가 제출을 거부합니다.</span><span class="sxs-lookup"><span data-stu-id="a5fc9-190">In case the submission does not satisfy the approval standards, the analyst will reject the submission.</span></span>
  
<span data-ttu-id="a5fc9-191">파트너는 분석가와 협력하여 관련 정보 및 문서를 제공할 수 있습니다.</span><span class="sxs-lookup"><span data-stu-id="a5fc9-191">The partner can work with the analyst to provide the relevant information and documents.</span></span>

![인증 거부](../media/UserGuidePhotos/25.png)
  
<span data-ttu-id="a5fc9-193">모든 보안 표준이 충족되고 나면 분석가가 제출을 승인하고 파트너가 인증을 Microsoft 365 합니다.</span><span class="sxs-lookup"><span data-stu-id="a5fc9-193">Once all the security standards have been met, the analyst will approve the submission and the partner will be Microsoft 365 Certified.</span></span>

![Microsoft 365 앱 인증 승인됨](../media/UserGuidePhotos/26.png)
  
<span data-ttu-id="a5fc9-195">**인증 후 승인: AppSource에서 Microsoft 365 인증 배지의 예입니다.**</span><span class="sxs-lookup"><span data-stu-id="a5fc9-195">**Post Certification Approval: Example of Microsoft 365 certification badge in AppSource.**</span></span> 

![인증 후 승인](../media/UserGuidePhotos/27.png)
 
## <a name="5---microsoft-365-renewal-workflow"></a><span data-ttu-id="a5fc9-197">5. Microsoft 365 갱신 워크플로:</span><span class="sxs-lookup"><span data-stu-id="a5fc9-197">5.   Microsoft 365 Renewal Workflow:</span></span>
  
<span data-ttu-id="a5fc9-198">**Microsoft 365Publisher 증명 및 인증 갱신 워크플로:**</span><span class="sxs-lookup"><span data-stu-id="a5fc9-198">**Microsoft 365 Publisher Attestation and Certification Renewal Workflow:**</span></span>  

<span data-ttu-id="a5fc9-199">Microsoft 365 이제 앱 준수 프로그램은 연간 갱신 프로세스를 제공합니다.</span><span class="sxs-lookup"><span data-stu-id="a5fc9-199">Microsoft 365 App Compliance program now offers an annual renewal process.</span></span> <span data-ttu-id="a5fc9-200">이 프로세스 동안 앱 개발자는 기존 Publisher 증명 설문지 및 인증에 필요한 문서를 Microsoft 365 있습니다.</span><span class="sxs-lookup"><span data-stu-id="a5fc9-200">During this process, app developers can update their existing Publisher Attestation questionnaire and documents required for Microsoft 365 Certification.</span></span> 
 
<span data-ttu-id="a5fc9-201">**이점:**</span><span class="sxs-lookup"><span data-stu-id="a5fc9-201">**Benefits:**</span></span> 

- <span data-ttu-id="a5fc9-202">AppSource, Office 스토어, Teams 스토어 및 다양한 관리 포털에서 인증 배지를 유지 관리하여 앱을 다른 사용자와 차별화합니다.</span><span class="sxs-lookup"><span data-stu-id="a5fc9-202">Maintain your certification badge in AppSource, the Office Store, the Teams Store and various admin portals to differentiate your app from others.</span></span> 
- <span data-ttu-id="a5fc9-203">인증된 앱을 사용할 때 고객의 신뢰를 높이기</span><span class="sxs-lookup"><span data-stu-id="a5fc9-203">Increase customer confidence in using your certified app.</span></span> 
- <span data-ttu-id="a5fc9-204">IT 관리자가 업데이트된 인증 정보를 통해 정보를 통해 의사 결정을 내리는 데 도움을 줄 수 있습니다.</span><span class="sxs-lookup"><span data-stu-id="a5fc9-204">Help IT admins make informed decisions with updated certification information.</span></span>

<span data-ttu-id="a5fc9-205">새로운 갱신 프로세스는 원활한 [환경을](https://partner.microsoft.com/dashboard/home) 제공하기 위해 파트너 센터에서 사용할 수 있습니다.</span><span class="sxs-lookup"><span data-stu-id="a5fc9-205">The new renewal process is available in [Partner Center](https://partner.microsoft.com/dashboard/home) to provide a seamless experience.</span></span> <span data-ttu-id="a5fc9-206">갱신 미리 알림은 만료 날짜 90일 전부터 파트너 센터에 표시됩니다.</span><span class="sxs-lookup"><span data-stu-id="a5fc9-206">A renewal reminder will be shown in Partner Center starting 90 days before the expiration date.</span></span> <span data-ttu-id="a5fc9-207">만료 90일, 60일 및 30일 전에 전자 메일을 통해 주기적인 미리 알림도 전송됩니다.</span><span class="sxs-lookup"><span data-stu-id="a5fc9-207">Periodic reminders will also be sent via email at 90, 60 and 30 days before expiration.</span></span> 
 
<span data-ttu-id="a5fc9-208">**1단계: Publisher 갱신:**</span><span class="sxs-lookup"><span data-stu-id="a5fc9-208">**Phase 1: Publisher Attestation Renewal:**</span></span>
  
<span data-ttu-id="a5fc9-209">앱의 Publisher 답변을 매년 다시 제출해야 합니다.</span><span class="sxs-lookup"><span data-stu-id="a5fc9-209">The app’s Publisher Attestation answers will need to be resubmitted on an annual basis.</span></span> <span data-ttu-id="a5fc9-210">1년 표시에 가까운 경우 스터스터를 다시 제출할 수 있는 전자 메일 미리 알림이 전송됩니다.</span><span class="sxs-lookup"><span data-stu-id="a5fc9-210">When the attestation nears the 1-year mark, an email reminder will be sent encouraging a resubmission of the attestation.</span></span> 
 
<span data-ttu-id="a5fc9-211">**1단계:** **갱신을** 선택하여 Publisher 갱신합니다.</span><span class="sxs-lookup"><span data-stu-id="a5fc9-211">**Step 1**: Select **Renew** to renew the Publisher Attestation.</span></span>
  
![갱신 승인됨](../media/UserGuidePhotos/31.png)
  
<span data-ttu-id="a5fc9-213">**2단계:** 이전 Publisher 정보를 검토하고 필요한 경우 최신 정보로 업데이트합니다.</span><span class="sxs-lookup"><span data-stu-id="a5fc9-213">**Step 2**: Review the previous Publisher Attestation answers and update with the latest information as needed.</span></span> 
  
<span data-ttu-id="a5fc9-214">준비가 Publisher 갱신에 대한 제출을 제출합니다.</span><span class="sxs-lookup"><span data-stu-id="a5fc9-214">Submit Publisher Attestation for renewal when ready.</span></span> <span data-ttu-id="a5fc9-215">M365 앱 준수 분석가가 검토합니다.</span><span class="sxs-lookup"><span data-stu-id="a5fc9-215">It will be reviewed by an M365 App Compliance analyst.</span></span>

![은(를) 으로 갱신](../media/UserGuidePhotos/29.png)
  
<span data-ttu-id="a5fc9-217">**Publisher 인증 갱신 승인됨:**</span><span class="sxs-lookup"><span data-stu-id="a5fc9-217">**Publisher Attestation Renewal Approved:**</span></span>
  
![갱신 제출](../media/UserGuidePhotos/30.png)
  
<span data-ttu-id="a5fc9-219">**Publisher 만료된 의거:**</span><span class="sxs-lookup"><span data-stu-id="a5fc9-219">**Publisher Attestation Expired:**</span></span>
  
<span data-ttu-id="a5fc9-220">Microsoft docs에서 앱의 Publisher 페이지를 유지 관리하기 위해 만료 날짜 전에 앱의 정보를 갱신해야 합니다. 또한 시기 적절한 갱신을 통해 다양한 스토어의 앱에 대한 계속해서 배지 및 아이콘을 사용할 수 있습니다.</span><span class="sxs-lookup"><span data-stu-id="a5fc9-220">The app’s information needs to be renewed before the expiration date to maintain the app’s Publisher Attestation page on the Microsoft docs. Timely renewal will also ensure continued badging and icons for the app in various storefronts.</span></span> 
 
![갱신 승인됨](../media/UserGuidePhotos/31.png)

<span data-ttu-id="a5fc9-222">**참고:** 만료되면 Publisher 갱신 프로세스를 언제든지 '갱신'을 클릭하여 시작할 수 있습니다.</span><span class="sxs-lookup"><span data-stu-id="a5fc9-222">**Note**: Once expired, Publisher Attestation renewal process can be started anytime by clicking ‘Renew’.</span></span>
 
<span data-ttu-id="a5fc9-223">**2단계: Microsoft 365 갱신**</span><span class="sxs-lookup"><span data-stu-id="a5fc9-223">**Phase 2: Microsoft 365 Certification Renewal**</span></span>
  
<span data-ttu-id="a5fc9-224">앱의 인증 정보는 매년 다시 제출해야 합니다.</span><span class="sxs-lookup"><span data-stu-id="a5fc9-224">The app’s certification information needs to be resubmitted on an annual basis.</span></span> <span data-ttu-id="a5fc9-225">이렇게 하면 현재 환경의 범위 내 컨트롤을 다시 확인해야 합니다.</span><span class="sxs-lookup"><span data-stu-id="a5fc9-225">This will require revalidation of the in-scope controls of your current environment.</span></span> <span data-ttu-id="a5fc9-226">인증이 1년이 다가오면 문서 및 증거를 다시 전송할 수 있는 전자 메일 알림이 전송됩니다.</span><span class="sxs-lookup"><span data-stu-id="a5fc9-226">When the Certification nears 1-year mark an email notification will be sent encouraging a resubmission of the documents and evidence.</span></span>
 
![Attestation Renewel](../media/UserGuidePhotos/32.png) 

<span data-ttu-id="a5fc9-228">**인증 갱신 승인/거부 시나리오:**</span><span class="sxs-lookup"><span data-stu-id="a5fc9-228">**Certification Renewal Approve/Reject Scenarios:**</span></span>

<span data-ttu-id="a5fc9-229">**시나리오 1:**</span><span class="sxs-lookup"><span data-stu-id="a5fc9-229">**Scenario 1:**</span></span> 

<span data-ttu-id="a5fc9-230">인증 갱신이 시작된 후 검토 중입니다.</span><span class="sxs-lookup"><span data-stu-id="a5fc9-230">Certification renewal has started and is under review.</span></span>
 
![인증 갱신](../media/UserGuidePhotos/33.png) 

<span data-ttu-id="a5fc9-232">시나리오 1A:</span><span class="sxs-lookup"><span data-stu-id="a5fc9-232">Scenario 1A:</span></span> 

<span data-ttu-id="a5fc9-233">인증 갱신 거부:</span><span class="sxs-lookup"><span data-stu-id="a5fc9-233">Certification renewal rejection:</span></span> 
- <span data-ttu-id="a5fc9-234">인증은 거부될 수 있습니다.</span><span class="sxs-lookup"><span data-stu-id="a5fc9-234">Certification may be rejected if:</span></span> 
     - <span data-ttu-id="a5fc9-235">앱에 필요한 도구, 프로세스 또는 구성이 없는 경우 인증 기간 내에 필요한 변경 내용을 구현할 수 없습니다.</span><span class="sxs-lookup"><span data-stu-id="a5fc9-235">The app does not have the required tooling, processes, or configurations in place and will not be able to implement required changes within the certification window.</span></span> 
     - <span data-ttu-id="a5fc9-236">앱에 미해결 취약점이 있으며 인증 기간 내에 수정될 수 없습니다.</span><span class="sxs-lookup"><span data-stu-id="a5fc9-236">The app has outstanding vulnerabilities in place and cannot be fixed within the certification window.</span></span> 
 
![인증 거부](../media/UserGuidePhotos/34.png)

<span data-ttu-id="a5fc9-238">시나리오 1B:</span><span class="sxs-lookup"><span data-stu-id="a5fc9-238">Scenario 1B:</span></span> 

<span data-ttu-id="a5fc9-239">인증 갱신 승인</span><span class="sxs-lookup"><span data-stu-id="a5fc9-239">Certification renewal is approved</span></span>

![인증 갱신 승인](../media/UserGuidePhotos/35.png)

<span data-ttu-id="a5fc9-241">**인증 만료:**</span><span class="sxs-lookup"><span data-stu-id="a5fc9-241">**Certification Expiration:**</span></span>

<span data-ttu-id="a5fc9-242">Microsoft docs에서 앱의 인증 페이지를 유지 관리하기 위해 만료 날짜 전에 앱의 정보를 갱신해야 합니다. 또한 시기 적절한 갱신을 통해 AppSource 및 팀 스토어에서 앱의 배지 및 아이콘을 계속 사용할 수 있습니다.</span><span class="sxs-lookup"><span data-stu-id="a5fc9-242">The app’s information needs to be renewed before the expiration date to maintain app’s Certification page on the Microsoft docs. Timely renewal will also ensure continued badging and icons for the app in AppSource and Team Store.</span></span>

![인증 갱신 승인](../media/UserGuidePhotos/36.png)
  
<span data-ttu-id="a5fc9-244">참고: 만료되면 Publisher '갱신'을 클릭하여 언제든지 증명 및 인증 프로세스를 시작할 수 있습니다.</span><span class="sxs-lookup"><span data-stu-id="a5fc9-244">Note: Once expired, Publisher Attestation and Certification process can be started anytime by clicking ‘Renew’.</span></span> 
