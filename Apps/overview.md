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
ms.sourcegitcommit: d85595f6518d8d05f0aee75380f51659908b6bcb
ms.translationtype: HT
ms.contentlocale: ko-KR
ms.lasthandoff: 09/12/2021
ms.locfileid: "59288274"
---
# <a name="microsoft-365-app-compliance-program"></a>Microsoft 365 앱 규정 준수 프로그램

Microsoft 365 앱 규정 준수 프로그램은 앱 보안 및 규정 준수에 대한 3계층 접근 방식입니다. 각 계층은 다음을 기반으로 합니다. 사용자에게 Microsoft 365 에코시스템에서 앱을 사용하는 동안 필요한 신뢰도를 주는 계층화된 프로그램을 제공합니다. 현재 프로그램의 모든 계층은 자율적으로 처리되며 개발자의 재량에 따라 완료됩니다. 

Microsoft의 임무: Microsoft 고객은 조직을 운영하는 데 사용되는 응용 프로그램을 완전히 신뢰합니다.

  ![앱 규정 준수에 대한 3계층 접근 방식](media/Microsoft-App-Compliance-Overview.png) 

## <a name="publisher-verification"></a>게시자 확인

[게시자 확인](https://docs.microsoft.com/azure/active-directory/develop/publisher-verification-overview)은 관리자 및 사용자가 Microsoft ID 플랫폼과 통합하는 앱 개발자의 신뢰성을 파악하는 데 도움이 됩니다. 앱이 게시자 확인됨으로 표시되는 경우 게시자가 확인 프로세스가 완료된 Microsoft 파트너 네트워크 계정을 사용하여 해당 ID를 확인했고 응용 프로그램 등록을 통해 이 MPN 계정과 연결되었음을 의미합니다.
게시자 확인은 다음 조건을 충족하는 앱에 적용됩니다.  
- OAuth 2.0 및 OpenID Connect를 사용하여 사용자가 로그인하도록 하고 Microsoft Graph 등의 서비스 측면 API를 사용하여 데이터에 대한 액세스를 요청합니다. 
- Azure AD에 다중 테넌트로 등록되었습니다.  

> [!IMPORTANT]
> 게시자 확인은 앱 개발자가 게시자 증명 또는 Microsoft 365 인증을 시작하거나 완료하지 못하게 방해하지 않습니다. 앱에 적용되지 않는 경우에는 확인을 건너뛰고 증명을 시작할 수 있습니다.

## <a name="publisher-attestation"></a>게시자 증명

[게시자 증명](https://docs.microsoft.com/microsoft-365-app-certification/docs/enterprise-app-attestation-guide)에서는 개발자가 앱 서비스애 대한 일반, 데이터 처리, 보안 및 규정 준수 정보를 공유합니다. 이는 IT 관리자가 앱 게시자와 직접 작업할 필요성을 줄여 줍니다. 합리적 결정을 하는 데 필요한 모든 정보는 게시자 증명을 완료한 모든 앱에 대해 한 곳에서 일관된 형식으로 확인할 수 있습니다. 게시자 증명의 목표는 고객이 테넌트에서 사용하는 앱이 조직 표준을 충족하도록 보장하면서 앱 채택 프로세스를 보다 쉽고 빠르게 처리하는 것입니다.

게시자 증명은 WebApps 및 다음 Microsoft 제품과 통합되는 모든 앱에 적용됩니다.
-   Teams
-   Word
-   Excel
-   PowerPoint 
-   Outlook
- SharePoint
- Project
- OneNote

> [!IMPORTANT]
> Microsoft는 제공된 정보를 확인하지 않습니다. 개발자가 단독으로 증명 문서 및 해당 앱 성능 데이터의 진위 여부와 정확도, 무결성을 확인합니다. 

## <a name="microsoft-365-certification"></a>Microsoft 365 인증
[Microsoft 365 인증](https://docs.microsoft.com/microsoft-365-app-certification/docs/enterprise-app-certification-guide)은 Microsoft Teams 앱을 사용할 때 데이터 및 개인 정보가 충분히 안전하며 보호됨을 조직에 보증하고 이에 대한 신뢰를 줍니다. 인증은 앱 솔루션이 Microsoft 기술과 호환되고 Cloud App Security 모범 사례를 준수하며, Microsoft에서 지원됨을 확인합니다.이 프로세스 동안 앱 개발자는 타사 평가자와 협업하여 조직 보안 및 규정 준수 표준을 확인합니다. Microsoft 365 인증은 Publisher 증명을 받을 수 있는 동일한 앱에 적용됩니다. 


