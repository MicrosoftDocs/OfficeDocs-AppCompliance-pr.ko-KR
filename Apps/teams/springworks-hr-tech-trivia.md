---
title: Springworks HR Tech의 Trivia에 대한 응용 프로그램 정보
ms.author: elmalova
author: elenamalova
ms.date: 01/13/2021
ms.topic: article
ms.service: attestation
certification_type: attested
description: CSA STAR 레지스트리의 Trivia, 데이터 처리 정책, Microsoft Cloud App Security 앱 카탈로그 정보 및 보안/규정 준수 정보에 대해 사용할 수 있는 모든 보안 및 규정 준수 정보
zone_pivot_groups: app-info-data-mcas-identity
ms.openlocfilehash: e22205d2584abd257a6fdff585f129fb915ff6b2
ms.sourcegitcommit: a613e40971c8b48fa2b7a35039b4331a8116763b
ms.translationtype: MT
ms.contentlocale: ko-KR
ms.lasthandoff: 07/22/2021
ms.locfileid: "53528364"
---
# <a name="trivia"></a>Trivia

<p></p>
<img alt="Publisher Attestation: The information on this page is based on a self-assessment report provided by the app developer on the security, compliance, and data handling practices followed by this app. Microsoft makes no guarantees regarding the accuracy of the information." src="../media/attested.png" width="650" />
<p>개발자가 마지막으로 업데이트한 날짜: 2021년 1월 13일</p>

* <a href="https://teams.microsoft.com/l/app/391082c3-968b-47b1-9c92-b5daf008000b" target="_blank">저장소의 Teams 보기</a>
* <a href="https://appsource.microsoft.com/product/office/WA200001956" target="_blank">AppSource의 보기</a>

::: zone pivot="general"

### <a name="general-information"></a>일반 정보

Springworks HR Tech에서 Microsoft에 제공하는 정보:

| **정보** | **응답** |
|:----------------|:-------------|
| 앱 이름 | Trivia |
| ID | WA200001956 |
| Office 365 클라이언트 지원 | Microsoft Teams |
| 파트너 회사 이름 | Springworks HR Tech |
| 파트너 웹 사이트의 URL | [https://www.springworks.in](https://www.springworks.in) |
| 응용 프로그램 Teams 페이지의 URL입니다. | [https://www.springworks.in/trivia](https://www.springworks.in/trivia) |
| 개인 정보 취급 방침의 URL | [https://trivia.springworks.in/policy](https://trivia.springworks.in/policy) |
| 사용 약관 URL | [https://trivia.springworks.in/tnc](https://trivia.springworks.in/tnc) |

 [!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="data"

### <a name="how-the-app-handles-data"></a>앱이 데이터를 처리하는 방법

이 정보는 Springworks HR Tech에서 이 앱이 조직 데이터를 수집하고 저장하는 방법 및 앱이 수집하는 데이터에 대해 조직이 제어할 수 있는 컨트롤에 대해 제공됩니다.

#### <a name="data-access-using-microsoft-graph"></a>Microsoft 365를 사용한 데이터 Graph

이 앱에 [Graph Microsoft 사용자 권한을](https://docs.microsoft.com/graph/permissions-reference) 나열합니다.

>| **사용 권한**  | **사용 권한 유형(위임/ 응용 프로그램)** | **데이터가 수집하나요? 수집의 사당성** | **데이터가 저장되어 있나요? 저장 사정이 있나요?** | **Azure AD 앱 ID** |
>|:----------------|:------------------------------------------------|:--------------------------------------------------------|:--------------------------------------------------|:--------------------|
>| Group.Read.All | 위임 | 아니요 | 사용자가 Teams 목록 | [43bc466a-7678-476f-b904-2d933c5bbfc3](https://docs.microsoft.com/microsoft-365-app-certification/azure/43bc466a-7678-476f-b904-2d933c5bbfc3) |
>| Team.ReadBasic.All | 위임 | 예, 봇이 추가된 팀 목록을 저장합니다. | 작업 영역의 모든 팀에 대한 기본 정보를 수집하기 위해 | [43bc466a-7678-476f-b904-2d933c5bbfc3](https://docs.microsoft.com/microsoft-365-app-certification/azure/43bc466a-7678-476f-b904-2d933c5bbfc3) |
>| User.Read.All | 위임 | 예. 사용자의 고유한 aadObjectId를 저장합니다. 사용자 이름, 전자 메일 등 사용자의 다양한 세부 정보도 표시하고 Trivia 대시보드에 표시합니다. | 작업 영역의 모든 사용자에 대한 세부 정보를 얻습니다. | [43bc466a-7678-476f-b904-2d933c5bbfc3](https://docs.microsoft.com/microsoft-365-app-certification/azure/43bc466a-7678-476f-b904-2d933c5bbfc3) |
>| openid | 위임 | 예. 앱에 로그인한 사용자를 저장합니다. |  사용자가 계정과 앱에서 모두 앱을 사용하여 사용자 데이터를 사용할 수 있도록 허용하려면 | [43bc466a-7678-476f-b904-2d933c5bbfc3](https://docs.microsoft.com/microsoft-365-app-certification/azure/43bc466a-7678-476f-b904-2d933c5bbfc3) |
>| profile | 위임 | 예. 퀴즈 호스트 및 기타 기능의 사용자 ID와 이름을 저장하고 고유하게 식별 | 사용자 이름, 전자 메일과 같은 사용자의 기본 프로필 정보를 읽으면 | [43bc466a-7678-476f-b904-2d933c5bbfc3](https://docs.microsoft.com/microsoft-365-app-certification/azure/43bc466a-7678-476f-b904-2d933c5bbfc3) |


#### <a name="non-microsoft-services-used"></a>비영구 Microsoft 서비스

앱이 Microsoft가 아닌 서비스로 조직 데이터를 전송하거나 공유하는 경우 앱에서 사용하는 비 Microsoft 서비스, 전송되는 데이터를 나열하고 앱이 이 정보를 전송해야 하는 이유에 대한 사유를 포함합니다.

>| **모든 비 Microsoft 서비스 OII가 다음으로 전송됩니다.** |  **전송되는 OII는 무엇입니까?** | **OII 전송의 사당성** |
>|:-----------------------------------------------------|:------------------------------|:----------------------------------------|
>| AWS, Mailchimp, Stripe.  | 고객 이름, 전자 메일, IP, 결제 정보 | 이러한 타사를 사용하여 고객에게 최상의 고객 환경을 제공합니다. |

#### <a name="data-access-via-bots"></a>봇을 통한 데이터 액세스

이 앱에 봇 또는 메시징 확장이 포함되어 있는 경우 팀 구성원의 명단(이름, 성, 표시 이름, 전자 메일 주소)이나 팀 구성원이 추가된 채팅의 최종 사용자 식별 정보(EUII)에 액세스할 수 있습니다. 이 앱이 이 기능을 사용하나요?

>| **EUII 액세스의 사유는 무엇입니까?**  | **EUII가 데이터베이스에 저장되어 있나요?** | **EUII 저장의 사유는 무엇입니까?** |
>|:---------------------------------------|:-----------------------------------|:------------------------------------|
>| 이 데이터는 퀴즈에 참석자 목록 및 기타 기능을 표시하고 저장하는 데 사용됩니다. | 이름, 전자 메일 | 예, 오류 발생 시 호스트와의 분석 및 통신을 위한 퀴즈 및 기타 기능 및 호스트의 데이터를 저장합니다. |


#### <a name="telemetry-data"></a>원격 분석 데이터

이 응용 프로그램의 원격 분석 또는 로그에 OII(조직 식별 정보) 또는 EUII(최종 사용자 식별 정보)가 나타나나요? 그렇다면 저장되는 데이터와 보존 및 제거 정책에 대해 설명하세요.

>OII: 조직 이름, 테넌트 ID가 로그에 표시됩니다. EUII: aad 개체 ID, 전체 이름, 전자 메일이 로그에 표시됩니다. 로그가 자동으로 삭제되는 30일 보존 기간 게시물이 있습니다. 


#### <a name="organizational-controls-for-data-stored-by-partner"></a>파트너가 저장한 데이터에 대한 조직 제어

조직의 관리자가 파트너 시스템에서 정보를 제어하는 방법에 대해 설명하는 방법 삭제, 보존, 감사, 보관, 최종 사용자 정책 등

>AWS, RDS에 저장된 데이터. 암호화됩니다. 액세스는 엔지니어, 엔지니어링 DevOps 창업자만 액세스할 수 있습니다.

#### <a name="human-review-of-organizational-information"></a>조직 정보의 인적 검토

사람이 이 앱에서 수집하거나 저장하는 OII(조직 식별 정보) 데이터를 검토하거나 분석하는 데 관여하나요?

>예

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="mcas"

Microsoft Cloud App Security [카탈로그의](https://www.microsoft.com/enterprise-mobility-security/cloud-app-security) 정보가 아래에 표시됩니다.

<iframe height='1020' title='Microsoft Cloud App Security 정보' src='https://appmcasinfoprod.azurewebsites.net/#/dashboard/36138' frameborder='no' style='width: 100%;'></iframe>

<a href="https://appmcasinfoprod.azurewebsites.net/#/dashboard/36138" target="_blank">새 탭에서 보기</a>

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="identity"

### <a name="identity-information"></a>ID 정보

이 정보는 Springworks HR Tech에서 이 앱이 인증, 권한 부여, 응용 프로그램 등록 모범 사례 및 기타 ID 조건을 처리하는 방법에 대해 제공했습니다.

| **정보** | **응답** |
|:----------------|:-------------|
| Microsoft Identify Platform(Azure AD)과 통합하나요?  | 아니요 |

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end
