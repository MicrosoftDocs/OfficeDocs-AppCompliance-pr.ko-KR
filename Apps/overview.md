---
title: Microsoft 365 앱 규정 준수 프로그램
author: LGerrard
ms.author: Legerrar
description: 프로그램 소개 및 개요
keywords: microsoft 365 m365 앱 게시자 증명 인증
ms.topic: overview
ms.service: attestation
localization_priority: Priority
ms.openlocfilehash: e36bee4289de320d264a8a5e55c7bc20a4ea803b
ms.sourcegitcommit: cab3c02db1b748f3502714d89bd9b65408fd9f54
ms.translationtype: HT
ms.contentlocale: ko-KR
ms.lasthandoff: 10/22/2021
ms.locfileid: "60545770"
---
# <a name="microsoft-365-app-compliance-program"></a>Microsoft 365 앱 규정 준수 프로그램

Microsoft 365 앱 규정 준수 프로그램은 앱 보안 및 규정 준수를 위한 2단계 접근 방식이며 게시자 확인 및 Microsoft 365 인증을 포함합니다. 각 계층은 다음을 기반으로 합니다. 사용자에게 Microsoft 365 에코시스템에서 앱을 사용하는 동안 필요한 신뢰도를 주는 계층화된 프로그램을 제공합니다.  

Microsoft의 사명: Microsoft 고객이 조직을 실행하는 응용 프로그램을 완전히 신뢰할 수 있는 방법을 제공합니다.

![앱 규정 준수에 대한 2계층 접근 방식](media/Microsoft365AppComplianceBanner.png)

## <a name="publisher-verification"></a>게시자 확인

[게시자 확인](https://docs.microsoft.com/azure/active-directory/develop/publisher-verification-overview)은 관리자 및 사용자가 Microsoft ID 플랫폼과 통합하는 앱 개발자의 신뢰성을 파악하는 데 도움이 됩니다. 앱이 게시자 확인됨으로 표시되는 경우 게시자가 확인 프로세스가 완료된 Microsoft 파트너 네트워크 계정을 사용하여 해당 ID를 확인했고 응용 프로그램 등록을 통해 이 MPN 계정과 연결되었음을 의미합니다.
게시자 확인은 다음 조건을 충족하는 앱에 적용됩니다.  
- OAuth 2.0 및 OpenID Connect를 사용하여 사용자가 로그인하도록 하고 Microsoft Graph 등의 서비스 측면 API를 사용하여 데이터에 대한 액세스를 요청합니다. 
- Azure AD에 다중 테넌트로 등록되었습니다.  

> [!IMPORTANT]
> 게시자 확인은 앱 개발자가 게시자 증명 또는 Microsoft 365 인증을 시작하거나 완료하지 못하게 방해하지 않습니다. 앱에 적용되지 않는 경우에는 확인을 건너뛰고 증명을 시작할 수 있습니다.

## <a name="microsoft-365-certification"></a>Microsoft 365 인증
Microsoft 365 인증 프로세스에는 **증명** 및 **인증** 의 두 단계가 있습니다.
1.  **증명** 에는 고객에게 가장 중요한 앱의 보안, 데이터 처리 및 규정 준수 속성에 대한 설문지를 작성하는 작업이 포함됩니다. 모든 정보는 한 곳에서 일관되고 읽기 쉬운 형식으로 게시됩니다. 목표는 고객이 테넌트에서 사용하는 앱이 조직 표준을 충족하는지 확인하는 동시에 앱 채택 프로세스의 속도를 높이는 것입니다.
1.  **인증** 에는 주요 산업 표준 프레임워크에서 파생된 일련의 제어에 대한 앱의 철저한 감사가 포함됩니다. ISV는 인증을 받기 전에 각 제어를 충족한다는 증거를 제공해야 합니다. 목표는 Microsoft 365 인증을 받은 앱이 데이터 보안 및 개인 정보를 보호하기 위해 강력한 보안 및 규정 준수 관행을 갖추고 있다는 앱을 신뢰할 수 있다는 확신을 고객에게 제공하는 것입니다.


Microsoft 365 인증은 WebApp 및 다음 Microsoft 제품과 통합되는 모든 앱에 적용됩니다.
-   Teams
-   Word
-   Excel
-   PowerPoint 
-   Outlook
- SharePoint
- Project
- OneNote

### <a name="get-started"></a>시작하기
- [게시자 확인을 완료하는 방법](https://docs.microsoft.com/en-us/azure/active-directory/develop/mark-app-as-publisher-verified)
- [Microsoft 365 인증을 완료하는 방법](https://docs.microsoft.com/en-us/microsoft-365-app-certification/docs/certification)

