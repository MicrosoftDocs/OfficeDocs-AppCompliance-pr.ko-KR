---
title: Microsoft 365 앱 규정 준수 프로그램
author: LGerrard
ms.author: Legerrar
description: 프로그램 소개 및 개요
keywords: microsoft 365 m365 앱 게시자 증명 인증
ms.topic: overview
ms.service: attestation
localization_priority: Priority
ms.openlocfilehash: c644414281f46696ff49f3b9eb1341f02e96f0ba
ms.sourcegitcommit: 78dbace87a9b5027ea5aa23a6be9b8c613bd06ce
ms.translationtype: HT
ms.contentlocale: ko-KR
ms.lasthandoff: 07/07/2021
ms.locfileid: "53315118"
---
# <a name="microsoft-365-app-compliance-program"></a><span data-ttu-id="e10ea-104">Microsoft 365 앱 규정 준수 프로그램</span><span class="sxs-lookup"><span data-stu-id="e10ea-104">Microsoft 365 App Compliance Program</span></span>

<span data-ttu-id="e10ea-105">Microsoft 365 앱 규정 준수 프로그램은 앱 보안 및 규정 준수에 대한 3계층 접근 방식입니다.</span><span class="sxs-lookup"><span data-stu-id="e10ea-105">The Microsoft 365 App Compliance Program, is a three tier approach to app security and compliance.</span></span> <span data-ttu-id="e10ea-106">각 계층은 다음을 기반으로 합니다. 사용자에게 Microsoft 365 에코시스템에서 앱을 사용하는 동안 필요한 신뢰도를 주는 계층화된 프로그램을 제공합니다.</span><span class="sxs-lookup"><span data-stu-id="e10ea-106">Each tier builds upon the next – offering a layered program to give users the confidence they need while using apps in the Microsoft 365 ecosystem.</span></span> <span data-ttu-id="e10ea-107">현재 프로그램의 모든 계층은 자율적으로 처리되며 개발자의 재량에 따라 완료됩니다.</span><span class="sxs-lookup"><span data-stu-id="e10ea-107">Currently all tiers in the program are voluntary and are completed at the app developers discretion.</span></span> 

<span data-ttu-id="e10ea-108">Microsoft의 임무: Microsoft 고객은 조직을 운영하는 데 사용되는 응용 프로그램을 완전히 신뢰합니다.</span><span class="sxs-lookup"><span data-stu-id="e10ea-108">Our mission statement: Microsoft customers have complete trust in the applications that run their organizations.</span></span>

  ![앱 규정 준수에 대한 3계층 접근 방식](media/Microsoft-App-Compliance-Overview.png) 

## <a name="publisher-verification"></a><span data-ttu-id="e10ea-110">게시자 확인</span><span class="sxs-lookup"><span data-stu-id="e10ea-110">Publisher Verification</span></span>

<span data-ttu-id="e10ea-111">[게시자 확인](https://docs.microsoft.com/azure/active-directory/develop/publisher-verification-overview)은 관리자 및 사용자가 Microsoft ID 플랫폼과 통합하는 앱 개발자의 신뢰성을 파악하는 데 도움이 됩니다.</span><span class="sxs-lookup"><span data-stu-id="e10ea-111">[Publisher Verification](https://docs.microsoft.com/azure/active-directory/develop/publisher-verification-overview) helps admins and users understand the authenticity of app developers integrating with the Microsoft identity platform.</span></span> <span data-ttu-id="e10ea-112">앱이 게시자 확인됨으로 표시되는 경우 게시자가 확인 프로세스가 완료된 Microsoft 파트너 네트워크 계정을 사용하여 해당 ID를 확인했고 응용 프로그램 등록을 통해 이 MPN 계정과 연결되었음을 의미합니다.</span><span class="sxs-lookup"><span data-stu-id="e10ea-112">When an app is marked as publisher verified, it means that the publisher has verified their identity using a Microsoft Partner Network account that has completed the verification process and has associated this MPN account with their application registration.</span></span>
<span data-ttu-id="e10ea-113">게시자 확인은 다음 조건을 충족하는 앱에 적용됩니다.</span><span class="sxs-lookup"><span data-stu-id="e10ea-113">Publisher Verification applies to apps that meet the following conditions:</span></span>  
- <span data-ttu-id="e10ea-114">OAuth 2.0 및 OpenID Connect를 사용하여 사용자가 로그인하도록 하고 Microsoft Graph 등의 서비스 측면 API를 사용하여 데이터에 대한 액세스를 요청합니다.</span><span class="sxs-lookup"><span data-stu-id="e10ea-114">Using OAuth 2.0 and OpenID Connect to sign users in and request access to data using service-side APIs such as Microsoft Graph.</span></span> 
- <span data-ttu-id="e10ea-115">Azure AD에 다중 테넌트로 등록되었습니다.</span><span class="sxs-lookup"><span data-stu-id="e10ea-115">Registered in Azure AD as multi-tenant.</span></span>  

> [!IMPORTANT]
> <span data-ttu-id="e10ea-116">게시자 확인은 앱 개발자가 게시자 증명 또는 Microsoft 365 인증을 시작하거나 완료하지 못하게 방해하지 않습니다.</span><span class="sxs-lookup"><span data-stu-id="e10ea-116">Publisher Verification does not preclude an app developer from starting or completing Publisher Attestation or Microsoft 365 Certification.</span></span> <span data-ttu-id="e10ea-117">앱에 적용되지 않는 경우에는 확인을 건너뛰고 증명을 시작할 수 있습니다.</span><span class="sxs-lookup"><span data-stu-id="e10ea-117">If it does not apply to the app verification may be skipped and the attestation can be started.</span></span>

## <a name="publisher-attestation"></a><span data-ttu-id="e10ea-118">게시자 증명</span><span class="sxs-lookup"><span data-stu-id="e10ea-118">Publisher Attestation</span></span>

<span data-ttu-id="e10ea-119">[게시자 증명](https://docs.microsoft.com/microsoft-365-app-certification/docs/enterprise-app-attestation-guide)에서는 개발자가 앱 서비스애 대한 일반, 데이터 처리, 보안 및 규정 준수 정보를 공유합니다.</span><span class="sxs-lookup"><span data-stu-id="e10ea-119">[Publisher Attestation](https://docs.microsoft.com/microsoft-365-app-certification/docs/enterprise-app-attestation-guide) is where developers share general, data handling, and security and compliance information about their app service.</span></span> <span data-ttu-id="e10ea-120">이는 IT 관리자가 앱 게시자와 직접 작업할 필요성을 줄여 줍니다.</span><span class="sxs-lookup"><span data-stu-id="e10ea-120">This reduces the need for IT admins to work directly with app publishers.</span></span> <span data-ttu-id="e10ea-121">합리적 결정을 하는 데 필요한 모든 정보는 게시자 증명을 완료한 모든 앱에 대해 한 곳에서 일관된 형식으로 확인할 수 있습니다.</span><span class="sxs-lookup"><span data-stu-id="e10ea-121">All the information needed to make an informed decision can be found for all apps that have completed the publisher attestation in one place and in a consistent format.</span></span> <span data-ttu-id="e10ea-122">게시자 증명의 목표는 고객이 테넌트에서 사용하는 앱이 조직 표준을 충족하도록 보장하면서 앱 채택 프로세스를 보다 쉽고 빠르게 처리하는 것입니다.</span><span class="sxs-lookup"><span data-stu-id="e10ea-122">The goal is to make it easier and speed up the process of app adoption while assuring customers that the apps they use in their tenants meets their organizational standards.</span></span>

<span data-ttu-id="e10ea-123">게시자 증명은 WebApps 및 다음 Microsoft 제품과 통합되는 모든 앱에 적용됩니다.</span><span class="sxs-lookup"><span data-stu-id="e10ea-123">Publisher Attestation applies to WebApps, and all apps that integrate with the following Microsoft products:</span></span>
-   <span data-ttu-id="e10ea-124">Teams</span><span class="sxs-lookup"><span data-stu-id="e10ea-124">Teams</span></span>
-   <span data-ttu-id="e10ea-125">Word</span><span class="sxs-lookup"><span data-stu-id="e10ea-125">Word</span></span>
-   <span data-ttu-id="e10ea-126">Excel</span><span class="sxs-lookup"><span data-stu-id="e10ea-126">Excel</span></span>
-   <span data-ttu-id="e10ea-127">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="e10ea-127">PowerPoint</span></span> 
-   <span data-ttu-id="e10ea-128">Outlook</span><span class="sxs-lookup"><span data-stu-id="e10ea-128">Outlook</span></span>
- <span data-ttu-id="e10ea-129">SharePoint</span><span class="sxs-lookup"><span data-stu-id="e10ea-129">SharePoint</span></span>
- <span data-ttu-id="e10ea-130">Project</span><span class="sxs-lookup"><span data-stu-id="e10ea-130">Project</span></span>
- <span data-ttu-id="e10ea-131">OneNote</span><span class="sxs-lookup"><span data-stu-id="e10ea-131">OneNote</span></span>

> [!IMPORTANT]
> <span data-ttu-id="e10ea-p105">Microsoft는 제공된 정보를 확인하지 않습니다. 개발자가 단독으로 증명 문서 및 해당 앱 성능 데이터의 진위 여부와 정확도, 무결성을 확인합니다.</span><span class="sxs-lookup"><span data-stu-id="e10ea-p105">Microsoft does not validate the information provided. The developer, solely affirms the veracity, accuracy, and integrity of the attestation documentation and corresponding app performance data.</span></span> 

## <a name="microsoft-365-certification"></a><span data-ttu-id="e10ea-134">Microsoft 365 인증</span><span class="sxs-lookup"><span data-stu-id="e10ea-134">Microsoft 365 Certification</span></span>
<span data-ttu-id="e10ea-135">[Microsoft 365 인증](https://docs.microsoft.com/microsoft-365-app-certification/docs/enterprise-app-certification-guide)은 Microsoft Teams 앱을 사용할 때 데이터 및 개인 정보가 충분히 안전하며 보호됨을 조직에 보증하고 이에 대한 신뢰를 줍니다.</span><span class="sxs-lookup"><span data-stu-id="e10ea-135">The [Microsoft 365 Certification](https://docs.microsoft.com/microsoft-365-app-certification/docs/enterprise-app-certification-guide) offers assurance and confidence to organizations that data and privacy are adequately secured and protected when using Microsoft Teams apps.</span></span> <span data-ttu-id="e10ea-136">인증은 앱 솔루션이 Microsoft 기술과 호환되고 Cloud App Security 모범 사례를 준수하며, Microsoft에서 지원됨을 확인합니다.</span><span class="sxs-lookup"><span data-stu-id="e10ea-136">Certification confirms that an app solution is compatible with Microsoft technologies, compliant with cloud app security best practices, and supported by Microsoft.</span></span><span data-ttu-id="e10ea-137">이 프로세스 동안 앱 개발자는 타사 평가자와 협업하여 조직 보안 및 규정 준수 표준을 확인합니다.</span><span class="sxs-lookup"><span data-stu-id="e10ea-137"> During this process, app developers work with a third-party assessor to validate organizational security and compliance standards.</span></span> <span data-ttu-id="e10ea-138">Microsoft 365 인증은 Publisher 증명을 받을 수 있는 동일한 앱에 적용됩니다.</span><span class="sxs-lookup"><span data-stu-id="e10ea-138">Microsoft 365 Certification applies to the same apps that qualify for the Publisher Attestation.</span></span> 


