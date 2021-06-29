---
title: SaaS 앱용 사용자 가이드
author: LGerrard
ms.author: legerrar
description: 앱 준수 Microsoft 365 SaaS용 ISV 사용자 가이드
keywords: 앱 준수 Microsoft 365 SaaS용 ISV 사용자 가이드
ms.topic: conceptual
ms.service: attestation
ms.openlocfilehash: 64059ff6d38313765053ab0fe5d023fb606d4eda
ms.sourcegitcommit: bfabb191087786fae2b476e3f30861317886defa
ms.translationtype: MT
ms.contentlocale: ko-KR
ms.lasthandoff: 06/29/2021
ms.locfileid: "53178997"
---
# <a name="partners-user-guide-for-microsoft-365-app-compliance-program---saas"></a><span data-ttu-id="7ff43-104">앱 준수 프로그램에 대한 파트너의 Microsoft 365 가이드 - SaaS</span><span class="sxs-lookup"><span data-stu-id="7ff43-104">Partner's User Guide for Microsoft 365 App Compliance Program - SaaS</span></span>

|<span data-ttu-id="7ff43-105">작업 단계</span><span class="sxs-lookup"><span data-stu-id="7ff43-105">Phase</span></span>|<span data-ttu-id="7ff43-106">제목</span><span class="sxs-lookup"><span data-stu-id="7ff43-106">Title</span></span>|
|---|---|
|<span data-ttu-id="7ff43-107">1단계</span><span class="sxs-lookup"><span data-stu-id="7ff43-107">Phase 1</span></span>| <span data-ttu-id="7ff43-108">게시자 증명</span><span class="sxs-lookup"><span data-stu-id="7ff43-108">Publisher Attestation</span></span>|
|<span data-ttu-id="7ff43-109">2단계</span><span class="sxs-lookup"><span data-stu-id="7ff43-109">Phase 2</span></span>| <span data-ttu-id="7ff43-110">Microsoft 365 인증</span><span class="sxs-lookup"><span data-stu-id="7ff43-110">Microsoft 365 Certification</span></span>|

## <a name="1-overview"></a><span data-ttu-id="7ff43-111">1. 개요</span><span class="sxs-lookup"><span data-stu-id="7ff43-111">1. Overview</span></span> 

<span data-ttu-id="7ff43-112">이 문서는 파트너 센터 포털을 통해 SaaS 앱에 대한 Publisher 증명 및 인증을 획득하기 위한 Microsoft 365 앱 준수 프로그램에 등록된 파트너를 위한 단계별 사용자 가이드 역할을 합니다.</span><span class="sxs-lookup"><span data-stu-id="7ff43-112">This document acts as a step-by-step user guide for our Partners, enrolled for Microsoft 365 App Compliance Program aiming to undergo Publisher Attestation and Certification for their SaaS apps, though Partner Center portal.</span></span>

## <a name="2-acronyms--definitions"></a><span data-ttu-id="7ff43-113">2. 약어 & 정의</span><span class="sxs-lookup"><span data-stu-id="7ff43-113">2. Acronyms & Definitions</span></span>
|<span data-ttu-id="7ff43-114">두문자어</span><span class="sxs-lookup"><span data-stu-id="7ff43-114">Acronym</span></span> | <span data-ttu-id="7ff43-115">정의</span><span class="sxs-lookup"><span data-stu-id="7ff43-115">Definition</span></span> |
|----|----|
|[<span data-ttu-id="7ff43-116">PC(파트너 센터)</span><span class="sxs-lookup"><span data-stu-id="7ff43-116">PC (Partner Center)</span></span>](https://partner.microsoft.com/)|<span data-ttu-id="7ff43-117">모든 Microsoft 파트너를 위한 포털입니다.</span><span class="sxs-lookup"><span data-stu-id="7ff43-117">A portal for all Microsoft Partners.</span></span> <span data-ttu-id="7ff43-118">파트너가 파트너 센터에 로그인하여 설문 Self-Assessment 제출합니다.</span><span class="sxs-lookup"><span data-stu-id="7ff43-118">A Partner logs in to Partner Center and submits Self-Assessment Questionnaire.</span></span> <span data-ttu-id="7ff43-119">앱 준수를 [Microsoft 365 파트너 센터](https://partner.microsoft.com/dashboard/home)</span><span class="sxs-lookup"><span data-stu-id="7ff43-119">Partner Center for [Microsoft 365 App Compliance](https://partner.microsoft.com/dashboard/home)</span></span>|
|<span data-ttu-id="7ff43-120">ISV</span><span class="sxs-lookup"><span data-stu-id="7ff43-120">ISV</span></span> | <span data-ttu-id="7ff43-121">Independent Software Vendor a.k.a.</span><span class="sxs-lookup"><span data-stu-id="7ff43-121">Independent Software Vendor a.k.a.</span></span> <span data-ttu-id="7ff43-122">파트너 또는 개발자</span><span class="sxs-lookup"><span data-stu-id="7ff43-122">Partner or Developer</span></span> |
|<span data-ttu-id="7ff43-123">앱 원본</span><span class="sxs-lookup"><span data-stu-id="7ff43-123">App Source</span></span> | <span data-ttu-id="7ff43-124">앱 카탈로그(AppSource) 예제: [이제 가상 에이전트](https://appsource.microsoft.com/product/office/WA104381816)</span><span class="sxs-lookup"><span data-stu-id="7ff43-124">Catalog of apps (AppSource) Example: [Now virtual agent](https://appsource.microsoft.com/product/office/WA104381816)</span></span> |

## <a name="3-publisher-attestation-workflow"></a><span data-ttu-id="7ff43-125">3. Publisher 워크플로</span><span class="sxs-lookup"><span data-stu-id="7ff43-125">3. Publisher Attestation Workflow</span></span>

<span data-ttu-id="7ff43-126">**홈페이지:** 파트너가 파트너 센터에 로그인하면 방문 페이지입니다.</span><span class="sxs-lookup"><span data-stu-id="7ff43-126">**Home Page**: This is the landing page once a partner logs in to Partner Center.</span></span>

![01](../media/UserGuidePhotos/01.png)
  
<span data-ttu-id="7ff43-128">**1단계:** 페이지 왼쪽의 탐색 모음에서 다음을 진행합니다.</span><span class="sxs-lookup"><span data-stu-id="7ff43-128">**Step 1** : On the left side of the page, on the navigation bar:</span></span>

      a.    Select Commercial Marketplace
      
      b.    Select Overview

![02](../Apps/media/UserGuidePhotos/02.png)
  
<span data-ttu-id="7ff43-130">'개요'를 선택하면 파트너는 앱 준수 프로그램을 시작하는 데 사용할 수 있는 앱 Microsoft 365 있습니다.</span><span class="sxs-lookup"><span data-stu-id="7ff43-130">Upon selecting ‘Overview’, partner can see list of apps available to start the Microsoft 365 Compliance program.</span></span>
  
<span data-ttu-id="7ff43-131">**2단계:** 목록에서 앱을 선택하여 Publisher 프로세스를 시작할 수 있습니다.</span><span class="sxs-lookup"><span data-stu-id="7ff43-131">**Step 2**: Select an app from the list to begin the Publisher Attestation process.</span></span>

 ![3 ](../Apps/media/UserGuidePhotos/03.png)

<span data-ttu-id="7ff43-133">앱을 선택하면 다른 탐색 모음에 '앱 준수' 옵션이 팝업됩니다.</span><span class="sxs-lookup"><span data-stu-id="7ff43-133">On selecting an app, another navigation bar will pop up with option ‘App Compliance’.</span></span>
  
<span data-ttu-id="7ff43-134">**3단계:**'앱 준수' 선택</span><span class="sxs-lookup"><span data-stu-id="7ff43-134">**Step 3**: Select 'App Compliance’</span></span>
  
![4 ](../Apps/media/UserGuidePhotos/04.png)
  
<span data-ttu-id="7ff43-136">**4단계:** Self-Assessment 설문지 작성을 Publisher 작성합니다.</span><span class="sxs-lookup"><span data-stu-id="7ff43-136">**Step 4**: Fill out the Self-Assessment Questionnaire for Publisher Attestation.</span></span>
 
![5 ](../Apps/media/UserGuidePhotos/05.png)
  
<span data-ttu-id="7ff43-138">**참고: 응용 프로그램을 업데이트/다시 제출할 예정인 경우 '제품 선택'에 대한 드롭다운을 클릭하고 앱을 선택하고 '복제'를 클릭합니다.**</span><span class="sxs-lookup"><span data-stu-id="7ff43-138">**Note: If you are coming back to update/re-submit your application, click dropdown for ‘Choose the product’, select the app and click ‘Clone’.**</span></span>
  
![6 ](../Apps/media/UserGuidePhotos/06.png)
  
<span data-ttu-id="7ff43-140">**양식의 전체 Import/Export 사용하여 양식을 오프라인으로 완성하고 완료되면 가져올 수 있습니다.**</span><span class="sxs-lookup"><span data-stu-id="7ff43-140">**You can also leverage the Import/Export feature to complete the form offline and import it once completed.**</span></span>
  
 ![7 ](../Apps/media/UserGuidePhotos/07.png)
  
 <span data-ttu-id="7ff43-142">**5단계:** 완료되면 '제출'을 클릭하면 평가가 '검토 중'이 됩니다.</span><span class="sxs-lookup"><span data-stu-id="7ff43-142">**Step 5**: Once completed, click on ‘Submit’, the assessment will now be ‘under review’.</span></span>
  
 ![8 ](../Apps/media/UserGuidePhotos/08.png)
  
 ![9 ](../Apps/media/UserGuidePhotos/09.png)
  
<span data-ttu-id="7ff43-145">**승인/거부 시나리오:**</span><span class="sxs-lookup"><span data-stu-id="7ff43-145">**Approve/Reject Scenarios:**</span></span>
  
<span data-ttu-id="7ff43-146">대답.</span><span class="sxs-lookup"><span data-stu-id="7ff43-146">A.</span></span>  <span data-ttu-id="7ff43-147">Publisher 퇴장 거부</span><span class="sxs-lookup"><span data-stu-id="7ff43-147">Publisher Attestation Rejection</span></span>

    a.  In case of rejection, a Partner can:
    
        •   View failure report
        
            o   Partner will be notified via email, and they can view the failure report in Partner Center
          
        •   Update and re-submit Self-Assessment Questionnaire.
  
 ![10 ](../Apps/media/UserGuidePhotos/10.png)
  
<span data-ttu-id="7ff43-149">B.</span><span class="sxs-lookup"><span data-stu-id="7ff43-149">B.</span></span>  <span data-ttu-id="7ff43-150">Publisher 의거 승인</span><span class="sxs-lookup"><span data-stu-id="7ff43-150">Publisher Attestation Approval</span></span>

    a.  Upon approval, the partner can:
    
        •   Update and resubmit attestation
        
        •   View completed Publisher Attestation
        
        •   Start M365 Certification Process
  
 ![11 ](../Apps/media/UserGuidePhotos/11.png)
  
 ![12 ](../Apps/media/UserGuidePhotos/12.png)
  
 <span data-ttu-id="7ff43-153">**Post Publisher Verification Approval: Example of link in AppSource for publisher attested apps.**</span><span class="sxs-lookup"><span data-stu-id="7ff43-153">**Post Publisher Verification Approval: Example of link in AppSource for publisher attested apps.**</span></span>
  
  ![13 ](../Apps/media/UserGuidePhotos/13.png)
  
 ## <a name="4--microsoft-365-certification-workflow"></a><span data-ttu-id="7ff43-155">4. Microsoft 365 워크플로</span><span class="sxs-lookup"><span data-stu-id="7ff43-155">4.  Microsoft 365 Certification Workflow</span></span>
  
 <span data-ttu-id="7ff43-156">파트너는 확인란을 선택하고 '제출'을 클릭하여 인증 프로세스를 시작할 수 있습니다.</span><span class="sxs-lookup"><span data-stu-id="7ff43-156">A partner can begin the Certification process by selecting the checkbox and clicking ‘Submit’</span></span>
  
 ![14 ](../Apps/media/UserGuidePhotos/14.png)
  
<span data-ttu-id="7ff43-158">**1단계:** 초기 문서 제출</span><span class="sxs-lookup"><span data-stu-id="7ff43-158">**Step 1** : Initial Document Submission</span></span>

 <span data-ttu-id="7ff43-159">모든 세부 정보를 입력하고 관련 문서를 업로드하고 '제출'을 클릭합니다.</span><span class="sxs-lookup"><span data-stu-id="7ff43-159">Fill out all the details, upload relevant documents and Click ‘Submit’</span></span>
  
 ![15](../Apps/media/UserGuidePhotos/15.png)
  
 ![16 ](../Apps/media/UserGuidePhotos/16.png)
 
<span data-ttu-id="7ff43-162">제출을 클릭하면 제출이 검토됩니다.</span><span class="sxs-lookup"><span data-stu-id="7ff43-162">On clicking Submit, the submission will be under review.</span></span>
 
![17 ](../Apps/media/UserGuidePhotos/17.png)
  
 <span data-ttu-id="7ff43-164">초기 문서가 충분하지 않을 경우 분석가가 개정을 요청합니다.</span><span class="sxs-lookup"><span data-stu-id="7ff43-164">An analyst requests a revision in case the initial documents are not sufficient or relevant.</span></span> <span data-ttu-id="7ff43-165">분석가가 파트너와 협력하여 승인을 위해 올바른 문서를 얻습니다.</span><span class="sxs-lookup"><span data-stu-id="7ff43-165">The analyst will work with the Partner to help get the right documents for approval.</span></span>
  
![18 ](https://github.com/MicrosoftDocs/OfficeDocs-AppCompliance-pr/blob/master/Apps/media/UserGuidePhotos/18.png)
  
<span data-ttu-id="7ff43-167">분석가가 초기 문서 제출을 승인하면 파트너는 제어 요구 사항을 제출해야 합니다.</span><span class="sxs-lookup"><span data-stu-id="7ff43-167">Once the analyst approves the initial document submission, the partner needs to submit the control requirements.</span></span>
  
<span data-ttu-id="7ff43-168">**2단계:** 제어 요구 사항 제출</span><span class="sxs-lookup"><span data-stu-id="7ff43-168">**Step 2**: Control Requirement Submission</span></span>
  
<span data-ttu-id="7ff43-169">모든 세부 정보를 입력하고 관련 문서를 업로드하고 '제출'을 클릭합니다.</span><span class="sxs-lookup"><span data-stu-id="7ff43-169">Fill out all the details, upload relevant documents and Click ‘Submit’</span></span>

![19](../Apps/media/UserGuidePhotos/19.png)

![20](../Apps/media/UserGuidePhotos/20.png)

![ 21](../Apps/media/UserGuidePhotos/21.png)
 
<span data-ttu-id="7ff43-173">제출을 클릭하면 제출이 검토됩니다.</span><span class="sxs-lookup"><span data-stu-id="7ff43-173">On clicking Submit, the submission will be under review.</span></span>
  
![22](../Apps/media/UserGuidePhotos/22.png)
  
<span data-ttu-id="7ff43-175">분석가가 제어 요구 사항 문서가 충분하지 않은 경우 또는 관련성이 없는 경우 개정을 요청합니다.</span><span class="sxs-lookup"><span data-stu-id="7ff43-175">An analyst requests a revision in case the control requirement documents are not sufficient or relevant.</span></span> <span data-ttu-id="7ff43-176">분석가가 파트너와 협력하여 승인을 위해 올바른 문서를 얻습니다.</span><span class="sxs-lookup"><span data-stu-id="7ff43-176">The analyst will work with the Partner to help get the right documents for approval.</span></span>
  
![23](../Apps/media/UserGuidePhotos/23.png)
  
![24](../Apps/media/UserGuidePhotos/24.png)
  
![25](../Apps/media/UserGuidePhotos/25.png)
  
<span data-ttu-id="7ff43-180">제출이 승인 표준을 충족하지 않는 경우 분석가가 제출을 거부합니다.</span><span class="sxs-lookup"><span data-stu-id="7ff43-180">In case the submission does not satisfy the approval standards, the analyst will reject the submission.</span></span>
  
<span data-ttu-id="7ff43-181">파트너는 분석가와 협력하여 관련 정보 및 문서를 제공할 수 있습니다.</span><span class="sxs-lookup"><span data-stu-id="7ff43-181">The partner can work with the analyst to provide the relevant information and documents.</span></span>
  
![26](../Apps/media/UserGuidePhotos/26.png)
  
<span data-ttu-id="7ff43-183">모든 보안 표준이 충족되고 나면 분석가가 제출을 승인하고 파트너가 인증을 Microsoft 365 합니다.</span><span class="sxs-lookup"><span data-stu-id="7ff43-183">Once all the security standards have been met, the analyst will approve the submission and the partner will be Microsoft 365 Certified.</span></span>
  
![27](../media/UserGuidePhotos/27.png)
  
<span data-ttu-id="7ff43-185">\*\*인증 후 승인: AppSource에서 Microsoft 365 인증 배지의 예입니다.</span><span class="sxs-lookup"><span data-stu-id="7ff43-185">\*\*Post Certification Approval: Example of Microsoft 365 certification badge in AppSource.</span></span> ** 
  
![28](../Apps/media/UserGuidePhotos/28.png)
  
## <a name="5---microsoft-365-renewal-workflow"></a><span data-ttu-id="7ff43-187">5. Microsoft 365 갱신 워크플로:</span><span class="sxs-lookup"><span data-stu-id="7ff43-187">5.   Microsoft 365 Renewal Workflow:</span></span>
  
<span data-ttu-id="7ff43-188">**Microsoft 365Publisher 증명 및 인증 갱신 워크플로:**</span><span class="sxs-lookup"><span data-stu-id="7ff43-188">**Microsoft 365 Publisher Attestation and Certification Renewal Workflow:**</span></span>  

<span data-ttu-id="7ff43-189">Microsoft 365 이제 앱 준수 프로그램은 연간 갱신 프로세스를 제공합니다.</span><span class="sxs-lookup"><span data-stu-id="7ff43-189">Microsoft 365 App Compliance Program now offers an annual renewal process.</span></span> <span data-ttu-id="7ff43-190">이 프로세스 동안 앱 개발자는 기존 Publisher 증명 설문지 및 인증에 필요한 문서를 Microsoft 365 있습니다.</span><span class="sxs-lookup"><span data-stu-id="7ff43-190">During this process, app developers can update their existing Publisher Attestation questionnaire and documents required for Microsoft 365 Certification.</span></span> 
 
<span data-ttu-id="7ff43-191">**이점:**</span><span class="sxs-lookup"><span data-stu-id="7ff43-191">**Benefits:**</span></span> 

  <span data-ttu-id="7ff43-192">• AppSource 및 팀 스토어에서 인증 배지를 유지 관리하여 앱을 다른 앱과 차별화합니다.</span><span class="sxs-lookup"><span data-stu-id="7ff43-192">• Maintain your certification badge in AppSource and Team Store to differentiate your app from others.</span></span> 
  
  <span data-ttu-id="7ff43-193">• 인증된 앱을 사용할 때 고객의 신뢰를 높이기</span><span class="sxs-lookup"><span data-stu-id="7ff43-193">• Increase customer confidence in using your certified app.</span></span> 
  
  <span data-ttu-id="7ff43-194">• IT 관리자가 업데이트된 인증 정보를 통해 정보를 통해 의사 결정을 내리는 데 도움을 줄 수 있습니다.</span><span class="sxs-lookup"><span data-stu-id="7ff43-194">• Help IT admins make informed decisions with updated certification information.</span></span>

<span data-ttu-id="7ff43-195">새로운 갱신 프로세스는 원활한 환경을 제공하기 위해 파트너 https://partner.microsoft.com/dashboard/home) 센터()에서 사용할 수 있습니다.</span><span class="sxs-lookup"><span data-stu-id="7ff43-195">The new renewal process is available in Partner Center(https://partner.microsoft.com/dashboard/home) to provide a seamless experience.</span></span> <span data-ttu-id="7ff43-196">갱신 미리 알림은 만료 날짜 90일 전부터 파트너 센터에 표시됩니다.</span><span class="sxs-lookup"><span data-stu-id="7ff43-196">A renewal reminder will be shown in Partner Center starting 90 days before the expiration date.</span></span> <span data-ttu-id="7ff43-197">만료 90일, 60일 및 30일 전에 전자 메일을 통해 주기적인 미리 알림도 전송됩니다.</span><span class="sxs-lookup"><span data-stu-id="7ff43-197">Periodic reminders will also be sent via email at 90, 60 and 30 days before expiration.</span></span> 
 
<span data-ttu-id="7ff43-198">**계층 1: Publisher 갱신:**</span><span class="sxs-lookup"><span data-stu-id="7ff43-198">**Tier 1: Publisher Attestation Renewal:**</span></span>
  
<span data-ttu-id="7ff43-199">앱의 Publisher 답변을 매년 다시 제출해야 합니다.</span><span class="sxs-lookup"><span data-stu-id="7ff43-199">The app’s Publisher Attestation answers will need to be resubmitted on an annual basis.</span></span> <span data-ttu-id="7ff43-200">1년이 다가오면 전자 메일 미리 알림이 전송되고 스터스터가 다시 전송됩니다.</span><span class="sxs-lookup"><span data-stu-id="7ff43-200">When the attestation nears 1-year mark, an email reminder will be sent encouraging a resubmission of the attestation.</span></span> 
 
<span data-ttu-id="7ff43-201">**1단계:** **갱신을** 선택하여 Publisher 갱신합니다.</span><span class="sxs-lookup"><span data-stu-id="7ff43-201">**Step 1**: Select **Renew** to renew the Publisher Attestation.</span></span>
  
![29](../Apps/media/UserGuidePhotos/29.png)
  
<span data-ttu-id="7ff43-203">**2단계:** 이전 Publisher 정보를 검토하고 필요한 경우 최신 정보로 업데이트합니다.</span><span class="sxs-lookup"><span data-stu-id="7ff43-203">**Step 2**: Review the previous Publisher Attestation answers and update with the latest information as needed.</span></span> 
  
<span data-ttu-id="7ff43-204">준비가 Publisher 갱신에 대한 제출을 제출합니다.</span><span class="sxs-lookup"><span data-stu-id="7ff43-204">Submit Publisher Attestation for renewal when ready.</span></span> <span data-ttu-id="7ff43-205">M365 앱 준수 분석가가 검토합니다.</span><span class="sxs-lookup"><span data-stu-id="7ff43-205">It will be reviewed by an M365 App Compliance Analyst.</span></span>
  
![30](../Apps/media/UserGuidePhotos/30.png)
  
<span data-ttu-id="7ff43-207">**Publisher 인증 갱신 승인됨:**</span><span class="sxs-lookup"><span data-stu-id="7ff43-207">**Publisher Attestation Renewal Approved:**</span></span>
  
![31](../Apps/media/UserGuidePhotos/31.png)
  
<span data-ttu-id="7ff43-209">**Publisher 만료된 의거:**</span><span class="sxs-lookup"><span data-stu-id="7ff43-209">**Publisher Attestation Expired:**</span></span>
  
<span data-ttu-id="7ff43-210">Microsoft docs에서 앱의 Publisher 페이지를 유지 관리하기 위해 만료 날짜 전에 앱의 정보를 갱신해야 합니다. 또한 시기 적절한 갱신을 통해 AppSource 및 팀 스토어에서 앱의 배지 및 아이콘을 계속 사용할 수 있습니다.</span><span class="sxs-lookup"><span data-stu-id="7ff43-210">The app’s information needs to be renewed before the expiration date to maintain the app’s Publisher Attestation page on the Microsoft docs. Timely renewal will also ensure continued badging and icons for the app in AppSource and Team Store.</span></span>
  
![32](../Apps/media/UserGuidePhotos/32.png)
  
<span data-ttu-id="7ff43-212">**참고:** 만료되면 Publisher 갱신 프로세스를 언제든지 '갱신'을 클릭하여 시작할 수 있습니다.</span><span class="sxs-lookup"><span data-stu-id="7ff43-212">**Note**: Once expired, Publisher Attestation renewal process can be started anytime by clicking ‘Renew’.</span></span>
 
<span data-ttu-id="7ff43-213">**계층 2: Microsoft 365 갱신**</span><span class="sxs-lookup"><span data-stu-id="7ff43-213">**Tier 2: Microsoft 365 Certification Renewal**</span></span>
  
<span data-ttu-id="7ff43-214">앱의 인증 정보는 매년 다시 제출해야 합니다.</span><span class="sxs-lookup"><span data-stu-id="7ff43-214">The app’s certification information needs to be resubmitted on an annual basis.</span></span> <span data-ttu-id="7ff43-215">이렇게 하면 현재 환경의 범위 내 컨트롤을 다시 확인해야 합니다.</span><span class="sxs-lookup"><span data-stu-id="7ff43-215">This will require revalidation of the in-scope controls of your current environment.</span></span> <span data-ttu-id="7ff43-216">인증이 1년이 다가오면 문서 및 증거를 다시 전송할 수 있는 전자 메일 알림이 전송됩니다.</span><span class="sxs-lookup"><span data-stu-id="7ff43-216">When the Certification nears 1-year mark an email notification will be sent encouraging a resubmission of the documents and evidence.</span></span>
  
![33](../Apps/media/UserGuidePhotos/33.png)
  
<span data-ttu-id="7ff43-218">**인증 갱신 승인/거부 시나리오:**</span><span class="sxs-lookup"><span data-stu-id="7ff43-218">**Certification Renewal Approve/Reject Scenarios:**</span></span>
 
<span data-ttu-id="7ff43-219">**시나리오 1:** 인증 갱신이 시작된 후 검토 중입니다.</span><span class="sxs-lookup"><span data-stu-id="7ff43-219">**Scenario 1:** Certification renewal has started and is under review.</span></span>
  
![34](../Apps/media/UserGuidePhotos/34.png)

<span data-ttu-id="7ff43-221">시나리오 1A: 인증 갱신 거부: 다음의 경우 인증이 거부될 수 있습니다. • 앱에 필요한 도구, 프로세스 또는 구성이 없는 경우 인증 기간 내에 필요한 변경 내용을 구현할 수 없습니다.</span><span class="sxs-lookup"><span data-stu-id="7ff43-221">Scenario 1A: Certification renewal rejection: Certification may be rejected if: •   The app does not have the required tooling, processes, or configurations in place and will not be able to implement required changes within the certification window.</span></span> <span data-ttu-id="7ff43-222">• 앱에 미해결 취약점이 있으며 인증 기간 내에 수정될 수 없습니다.</span><span class="sxs-lookup"><span data-stu-id="7ff43-222">•   The app has outstanding vulnerabilities in place and cannot be fixed within the certification window.</span></span> 
  
![35](../Apps/media/UserGuidePhotos/35.png)
  
<span data-ttu-id="7ff43-224">시나리오 1B: 인증 갱신 승인</span><span class="sxs-lookup"><span data-stu-id="7ff43-224">Scenario 1B: Certification renewal is approved</span></span>

![36](../Apps/media/UserGuidePhotos/36.png)

<span data-ttu-id="7ff43-226">**인증 만료:**</span><span class="sxs-lookup"><span data-stu-id="7ff43-226">**Certification Expiration:**</span></span>
 
<span data-ttu-id="7ff43-227">Microsoft docs에서 앱의 인증 페이지를 유지 관리하기 위해 만료 날짜 전에 앱의 정보를 갱신해야 합니다. 또한 시기 적절한 갱신을 통해 AppSource 및 팀 스토어에서 앱의 배지 및 아이콘을 계속 사용할 수 있습니다.</span><span class="sxs-lookup"><span data-stu-id="7ff43-227">The app’s information needs to be renewed before the expiration date to maintain app’s Certification page on the Microsoft docs. Timely renewal will also ensure continued badging and icons for the app in AppSource and Team Store.</span></span>

![5.5](../Apps/media/UserGuidePhotos/5.5.png)
  
<span data-ttu-id="7ff43-229">참고: 만료되면 Publisher '갱신'을 클릭하여 언제든지 증명 및 인증 프로세스를 시작할 수 있습니다.</span><span class="sxs-lookup"><span data-stu-id="7ff43-229">Note: Once expired, Publisher Attestation and Certification process can be started anytime by clicking ‘Renew’.</span></span> 




  

  
 

  

 
