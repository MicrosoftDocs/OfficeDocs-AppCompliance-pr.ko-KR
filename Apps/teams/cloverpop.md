---
title: Cloverpop의 Cloverpop에 대한 응용 프로그램 정보
ms.author: elmalova
author: elenamalova
ms.date: 08/24/2020
ms.topic: article
ms.service: attestation
description: Cloverpop에 사용할 수 있는 모든 보안 및 규정 준수 정보, 데이터 처리 정책, CSA STAR 레지스트리의 Microsoft Cloud App Security 앱 카탈로그 정보 및 보안/규정 준수 정보
zone_pivot_groups: app-info-data-mcas
ms.openlocfilehash: 292334b46b1faf54938bb559d2d94c700d37faf3
ms.sourcegitcommit: e97156a6eaf1d5ec5c26fd14add210a92bacd944
ms.translationtype: MT
ms.contentlocale: ko-KR
ms.lasthandoff: 04/30/2021
ms.locfileid: "52095369"
---
# <a name="cloverpop"></a>Cloverpop

<p></p>
<img alt="Publisher Attestation: The information on this page is based on a self-assessment report provided by the app developer on the security, compliance, and data handling practices followed by this app. Microsoft makes no guarantees regarding the accuracy of the information." src="../media/attested.png" width="650" />
<p>개발자가 마지막으로 업데이트한 날짜: 2020년 8월 24일</p>

* <a href="https://teams.microsoft.com/l/app/3f8519a6-2428-4088-8d12-1b4fd234ff19" target="_blank">저장소의 Teams 보기</a>
* <a href="https://appsource.microsoft.com/product/office/WA200001803" target="_blank">AppSource의 보기</a>

::: zone pivot="general"

### <a name="general-information"></a>일반 정보

Cloverpop에서 Microsoft에 제공하는 정보:

| **정보** | **응답** |
|:----------------|:-------------|
| 앱 이름 | Cloverpop |
| ID | WA200001803 |
| 기능 | 봇, 탭, 메시징 익스텐션 |
| Office 365 클라이언트 지원 | Microsoft Teams |
| 파트너 회사 이름 | Cloverpop |
| 파트너 웹 사이트의 URL | [https://www.cloverpop.com](https://www.cloverpop.com) |
| 개인 정보 취급 방침의 URL | [https://www.cloverpop.com/privacy-policy/](https://www.cloverpop.com/privacy-policy/) |
| 사용 약관 URL | [https://www.cloverpop.com/terms-of-service](https://www.cloverpop.com/terms-of-service) |

 [!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="data"

### <a name="how-the-app-handles-data"></a>앱이 데이터를 처리하는 방법

이 정보는 Cloverpop에서 이 앱이 조직 데이터를 수집하고 저장하는 방법 및 앱이 수집하는 데이터를 통해 조직에서 사용할 컨트롤에 대해 제공됩니다.

#### <a name="data-access-using-microsoft-graph"></a>Microsoft 365를 사용한 데이터 Graph

이 앱에 [Graph Microsoft 사용자 권한을](https://docs.microsoft.com/graph/permissions-reference) 나열합니다.

>| **사용 권한**  | **사용 권한 유형(위임/응용 프로그램)** | **데이터가 수집하나요? 수집의 사당성** | **데이터가 저장되어 있나요? 저장 사정이 있나요?** | **Azure AD 앱 ID** |
>|:----------------|:--------------------|:---------------------------------------------------|:--------------------------|:--------------------------|
>| User.Read | 위임 | 사용자 데이터를 저장합니다. email, oid, givenName, familyName, user avatar, user object id. organization id(tenantId), organization display name, Also we store on our side teams/channels names, ids, teams members. 사용자가 결정을 만들고 상호 작용할 때 이 데이터를 만든 사용자, 팀 및 조직과 연결합니다. 또한 사람이 친숙한 UX에 이 소유권을 표시해야 하여 표시 정보(예: 사용자가 아바타로&#8217;저장합니다. | 사용자가 로그인할 수 있도록 허용하고 UPN에 대한 앱 액세스 권한을 부여하여 전자 메일, 이름&#8221; oid, tid, givenName, surname, familyName, user avatar(photo), organization displayName | 1040474b-572d-4575-a423-95dd262a8b8a |
>| openid | 위임 | 사용자 데이터를 저장합니다. email, oid, givenName, familyName, user avatar, user object id. organization id(tenantId), organization display name, Also we store on our side teams/channels names, ids, teams members. 사용자가 결정을 만들고 상호 작용할 때 이 데이터를 만든 사용자, 팀 및 조직과 연결합니다. 또한 사람이 친숙한 UX에 이 소유권을 표시해야 하여 표시 정보(예: 사용자가 아바타로&#8217;저장합니다. | 웹앱에서 &#8220;로그인을 Teams&#8221; 로그인합니다. | 1040474b-572d-4575-a423-95dd262a8b8a |
>| profile | 위임 | 사용자 데이터를 저장합니다. email, oid, givenName, familyName, user avatar, user object id. organization id(tenantId), organization display name, Also we store on our side teams/channels names, ids, teams members. 사용자가 결정을 만들고 상호 작용할 때 이 데이터를 만든 사용자, 팀 및 조직과 연결합니다. 또한 사람이 친숙한 UX에 이 소유권을 표시해야 하여 표시 정보(예: 사용자가 아바타로&#8217;저장합니다. | 웹앱에서 &#8220;로그인을 Teams&#8221; 로그인합니다. | 1040474b-572d-4575-a423-95dd262a8b8a |


#### <a name="non-microsoft-services-used"></a>비영구 Microsoft 서비스

앱이 Microsoft가 아닌 서비스로 조직 데이터를 전송하거나 공유하는 경우 앱에서 사용하는 비 Microsoft 서비스, 전송되는 데이터를 나열하고 앱이 이 정보를 전송해야 하는 이유에 대한 사유를 포함합니다.

>비영구 Microsoft 서비스 사용되지 않습니다.

#### <a name="data-access-via-bots"></a>봇을 통한 데이터 액세스

이 앱에 봇 또는 메시징 확장이 포함되어 있는 경우 팀 구성원의 명단(이름, 성, 표시 이름, 전자 메일 주소)이나 팀 구성원이 추가된 채팅의 최종 사용자 식별 정보(EUII)에 액세스할 수 있습니다. 이 앱이 이 기능을 사용하나요?

>| **EUII 액세스의 사유는 무엇입니까?**  | **EUII가 데이터베이스에 저장되어 있나요?** | **EUII 저장의 사유는 무엇입니까?** |
>|:--------------------------------|:---------------------|:--------------------------|
>| 결정과 관련된 특정 사용자가 수행한 작업을 정확하게 표시하기 위해 첫 번째/성/표시 이름 데이터에 액세스합니다. 각 사용자가 여러 조직에 속하도록 허용하기 위해 전자 메일 주소를 db의 각 사용자에 대한 고유 식별자로 사용하게 됩니다. 앱과 상호 작용하는 경우(예: 설문에 응답하는 경우) 이 데이터에만 액세스합니다. | 결정과 관련된 특정 사용자가 수행한 작업을 정확하게 표시하기 위해 첫 번째/성/표시 이름 데이터를 저장합니다.  전자 메일 주소는 각 사용자가 여러 조직에 속할 수 있도록 허용하기 때문에 db의 각 사용자에 대한 고유 식별자로 사용하기 때문에 저장됩니다. 이 데이터는 앱과 상호 작용할 때(예: 설문에 응답하는 경우) 저장합니다. 의사 결정 데이터는 결정에 대한 기록 시스템으로 설정됩니다. 따라서 각 사용자가 결정에 참여한 방법을 식별하기 위해 데이터를 저장하는 것이 중요합니다. |  |



#### <a name="telemetry-data"></a>원격 분석 데이터

이 응용 프로그램의 원격 분석 또는 로그에 OII(조직 식별 정보) 또는 EUII(최종 사용자 식별 정보)가 나타나나요? 그렇다면 저장되는 데이터와 보존 및 제거 정책에 대해 설명하세요.

>예.
팀에서 앱이 상호 작용할 때 팀 ID가 로그에 표시됩니다.
미국에 있는 세 개의 창업자에 대한 프로덕션 로그에 제한적으로 액세스할 수 있습니다.

#### <a name="organizational-controls-for-data-stored-by-partner"></a>파트너가 저장한 데이터에 대한 조직 제어

조직의 관리자가 파트너 시스템에서 정보를 제어하는 방법에 대해 설명하는 방법 삭제, 보존, 감사, 보관, 최종 사용자 정책 등

>Cloverpop 앱은 레일의 Ruby를 사용하여 구축된 후 클라우드 인프라에 AWS를 활용하는 Heroku PaaS(서비스로 플랫폼)에서 호스트됩니다. Heroku와 AWS에는 모두 액세스할 수 있는 SOC 보고서가 있습니다. 앱에서는 휴지 데이터 저장소에서 암호화된 PostgreSQL을 사용하며 다중 테넌트 환경입니다.
 
모든 코드에는 데이터 액세스 보안을 다루는 자동화된 테스트가 작성되었습니다. 각 빌드는 보안에 대한 엄격한 코드 검토 프로세스와 사용 가능한 사용자 작업을 통한 사용자 인증 및 데이터 액세스 검사도 포함하는 수동 QA 테스트 프로세스를 진행합니다. 프로덕션 환경과 개발 및 테스트와 같은 다른 모든 환경은 명확히 구분됩니다.
 
일부 직원만 프로덕션 환경 및 데이터베이스에 액세스할 수 있습니다. 회사 창립자 및 소수의 검사를 통해 배경 검사를 진행하고 수량화 요구 사항(예: 고객 지원)이 있는 직원입니다.

#### <a name="human-review-of-organizational-information"></a>조직 정보의 인적 검토

사람이 이 앱에서 수집하거나 저장하는 OII(조직 식별 정보) 데이터를 검토하거나 분석하는 데 관여하나요?

>예

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="mcas"

Microsoft Cloud App Security [카탈로그의](https://www.microsoft.com/enterprise-mobility-security/cloud-app-security) 정보가 아래에 표시됩니다.

<iframe height='1020' title='Microsoft Cloud App Security 정보' src='https://appmcasinfoprod.azurewebsites.net/#/dashboard/35992' frameborder='no' style='width: 100%;'></iframe>

<a href="https://appmcasinfoprod.azurewebsites.net/#/dashboard/35992" target="_blank">새 탭에서 보기</a>

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

