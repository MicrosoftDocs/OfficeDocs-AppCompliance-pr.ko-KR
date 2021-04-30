---
title: 개발자 Invillia의 InStation에 대한 응용 프로그램 정보
ms.author: elmalova
author: elenamalova
ms.date: 08/06/2020
ms.topic: article
ms.service: attestation
description: InStation, 데이터 처리 정책, CSA STAR 레지스트리의 Microsoft Cloud App Security 앱 카탈로그 정보 및 보안/규정 준수 정보에 대해 사용할 수 있는 모든 보안 및 규정 준수 정보
zone_pivot_groups: app-info-data-mcas
ms.openlocfilehash: 942790109cfa1493954f50be11e15ee36dbf2af2
ms.sourcegitcommit: e97156a6eaf1d5ec5c26fd14add210a92bacd944
ms.translationtype: MT
ms.contentlocale: ko-KR
ms.lasthandoff: 04/30/2021
ms.locfileid: "52095319"
---
# <a name="instation"></a>InStation

<p></p>
<img alt="Publisher Attestation: The information on this page is based on a self-assessment report provided by the app developer on the security, compliance, and data handling practices followed by this app. Microsoft makes no guarantees regarding the accuracy of the information." src="../media/attested.png" width="650" />
<p>개발자가 마지막으로 업데이트한 날짜: 2020년 8월 6일</p>

* <a href="https://teams.microsoft.com/l/app/0c841985-9919-4c0a-b87d-b06b301148b3" target="_blank">저장소의 Teams 보기</a>
* <a href="https://appsource.microsoft.com/product/office/WA200001701" target="_blank">AppSource의 보기</a>

::: zone pivot="general"

### <a name="general-information"></a>일반 정보

개발자 Invillia가 Microsoft에 제공하는 정보:

| **정보** | **응답** |
|:----------------|:-------------|
| 앱 이름 | InStation |
| ID | WA200001701 |
| 기능 | 탭 |
| Office 365 클라이언트 지원 | Microsoft Teams |
| 파트너 회사 이름 | Developers Invillia |
| 파트너 웹 사이트의 URL | [https://instation.invillia.com/](https://instation.invillia.com/) |
| 개인 정보 취급 방침의 URL | [https://instation.invillia.com/terms#privacy-policy](https://instation.invillia.com/terms#privacy-policy) |
| 사용 약관 URL | [https://instation.invillia.com/terms#terms-of-use](https://instation.invillia.com/terms#terms-of-use) |

 [!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="data"

### <a name="how-the-app-handles-data"></a>앱이 데이터를 처리하는 방법

이 정보는 개발자 Invillia에서 이 앱이 조직 데이터를 수집하고 저장하는 방법 및 앱이 수집하는 데이터를 통해 조직이 제어할 수 있는 컨트롤에 대해 제공했습니다.

#### <a name="data-access-using-microsoft-graph"></a>Microsoft 365를 사용한 데이터 Graph

이 앱에 [Graph Microsoft 사용자 권한을](https://docs.microsoft.com/graph/permissions-reference) 나열합니다.

>| **사용 권한**  | **사용 권한 유형(위임/응용 프로그램)** | **데이터가 수집하나요? 수집의 사당성** | **데이터가 저장되어 있나요? 저장 사정이 있나요?** | **Azure AD 앱 ID** |
>|:----------------|:--------------------|:---------------------------------------------------|:--------------------------|:--------------------------|
>| OnlineMeetings.Read.All | 위임 | stores: id, join_url, join_web_url chat_id. 앱에서 모임을 만들 수 있습니다. | stores: id, join_url, join_web_url chat_id. 앱에서 모임을 만들 수 있습니다. | 0c841985-9919-4c0a-b87d-b06b301148b3 |
>| OnlineMeetings.ReadWrite.All | 위임 | stores: id, join_url, join_web_url chat_id. 앱에서 모임을 만들 수 있습니다. | stores: id, join_url, join_web_url chat_id. 앱에서 모임을 만들 수 있습니다. | 0c841985-9919-4c0a-b87d-b06b301148b3 |
>| Presence.Read | 위임 | 앱이 첫 번째 단계에서 조직에 로그인할 수 있습니다. | 활동 및 사용 가능성. 앱에서 사용자 상태를 캡처할 수 있도록 허용합니다. | 0c841985-9919-4c0a-b87d-b06b301148b3 |
>| Presence.Read.All | 위임 | 앱이 첫 번째 단계에서 조직에 로그인할 수 있습니다. | 활동 및 사용 가능성. 앱에서 사용자 상태를 캡처할 수 있도록 허용합니다. | 0c841985-9919-4c0a-b87d-b06b301148b3 |
>| User.Read | 위임 | stores: id, mail, display name, surname and picture. 앱에서 사용자 데이터를 검색할 수 있도록 허용합니다. | stores: id, mail, display name, surname and picture. 앱에서 사용자 데이터를 검색할 수 있도록 허용합니다. | 0c841985-9919-4c0a-b87d-b06b301148b3 |
>| User.Read.All | 위임 | stores: id, mail, display name, surname and picture. 앱에서 사용자 데이터를 검색할 수 있도록 허용합니다. | stores: id, mail, display name, surname and picture. 앱에서 사용자 데이터를 검색할 수 있도록 허용합니다. | 0c841985-9919-4c0a-b87d-b06b301148b3 |
>| 전자 메일 | 위임 | 앱이 첫 번째 로그인에 대한 관리자&#180;정보를 캡처할 수 있습니다. | 앱이 첫 번째 로그인에 대한 관리자&#180;정보를 캡처할 수 있습니다. | 0c841985-9919-4c0a-b87d-b06b301148b3 |
>| offline_access | 위임 | stores: 토큰 및 새로 고침 토큰. 앱이 MS 토큰에 대한 새로 고침을 수행할 수 있습니다. | stores: 토큰 및 새로 고침 토큰. 앱이 MS 토큰에 대한 새로 고침을 수행할 수 있습니다. | 0c841985-9919-4c0a-b87d-b06b301148b3 |
>| openid | 위임 | 앱이 첫 번째 단계에서 조직에 로그인할 수 있습니다. | 앱이 첫 번째 단계에서 조직에 로그인할 수 있습니다. | 0c841985-9919-4c0a-b87d-b06b301148b3 |
>| profile | 위임 | 앱이 첫 번째 로그인에 대한 관리자&#180;정보를 캡처할 수 있습니다. | 앱이 첫 번째 로그인에 대한 관리자&#180;정보를 캡처할 수 있습니다. | 0c841985-9919-4c0a-b87d-b06b301148b3 |


#### <a name="non-microsoft-services-used"></a>비영구 Microsoft 서비스

앱이 Microsoft가 아닌 서비스로 조직 데이터를 전송하거나 공유하는 경우 앱에서 사용하는 비 Microsoft 서비스, 전송되는 데이터를 나열하고 앱이 이 정보를 전송해야 하는 이유에 대한 사유를 포함합니다.

>비영구 Microsoft 서비스 사용되지 않습니다.

#### <a name="data-access-via-bots"></a>봇을 통한 데이터 액세스

이 앱에 봇 또는 메시징 확장이 포함되어 있는 경우 팀 구성원의 명단(이름, 성, 표시 이름, 전자 메일 주소)이나 팀 구성원이 추가된 채팅의 최종 사용자 식별 정보(EUII)에 액세스할 수 있습니다. 이 앱이 이 기능을 사용하나요?

>EUII에 액세스하지 않습니다.



#### <a name="telemetry-data"></a>원격 분석 데이터

이 응용 프로그램의 원격 분석 또는 로그에 OII(조직 식별 정보) 또는 EUII(최종 사용자 식별 정보)가 나타나나요? 그렇다면 저장되는 데이터와 보존 및 제거 정책에 대해 설명하세요.

>응용 프로그램 내에서만 사용자 사용 현황 로그를 저장합니다.

#### <a name="organizational-controls-for-data-stored-by-partner"></a>파트너가 저장한 데이터에 대한 조직 제어

조직의 관리자가 파트너 시스템에서 정보를 제어하는 방법에 대해 설명하는 방법 삭제, 보존, 감사, 보관, 최종 사용자 정책 등

>응용 프로그램 내에서만 사용자 사용 현황 로그를 저장합니다. 기밀이 아니며, 암호화를 요구하지 않고 특정 관리자만 이 데이터에 액세스할 수 있습니다.

#### <a name="human-review-of-organizational-information"></a>조직 정보의 인적 검토

사람이 이 앱에서 수집하거나 저장하는 OII(조직 식별 정보) 데이터를 검토하거나 분석하는 데 관여하나요?

>아니요

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="mcas"

Microsoft Cloud App Security [카탈로그의](https://www.microsoft.com/enterprise-mobility-security/cloud-app-security) 정보가 아래에 표시됩니다.

<iframe height='1020' title='Microsoft Cloud App Security 정보' src='https://appmcasinfoprod.azurewebsites.net/#/dashboard/35954' frameborder='no' style='width: 100%;'></iframe>

<a href="https://appmcasinfoprod.azurewebsites.net/#/dashboard/35954" target="_blank">새 탭에서 보기</a>

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

