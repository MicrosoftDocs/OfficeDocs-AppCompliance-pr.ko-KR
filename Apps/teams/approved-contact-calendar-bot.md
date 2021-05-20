---
title: 승인된 연락처의 일정 BOT에 대한 응용 프로그램 정보
ms.author: elmalova
author: elenamalova
ms.date: 12/16/2019
ms.topic: article
ms.service: attestation
certification_type: attested
description: 일정 BOT에 사용할 수 있는 모든 보안 및 규정 준수 정보, 데이터 처리 정책, CSA STAR 레지스트리의 Microsoft Cloud App Security 앱 카탈로그 정보 및 보안/규정 준수 정보
zone_pivot_groups: app-info-data-mcas
ms.openlocfilehash: 7e34564a01f326390ce807373e33818bef877c3e
ms.sourcegitcommit: a44420a99a1a3a9d0e49f4be66f266e2d4ca7bbb
ms.translationtype: MT
ms.contentlocale: ko-KR
ms.lasthandoff: 05/19/2021
ms.locfileid: "52553419"
---
# <a name="calendar-bot"></a>Calendar BOT

<p></p>
<img alt="Publisher Attestation: The information on this page is based on a self-assessment report provided by the app developer on the security, compliance, and data handling practices followed by this app. Microsoft makes no guarantees regarding the accuracy of the information." src="../media/attested.png" width="650" />
<p>개발자가 마지막으로 업데이트한 날짜: 2019년 12월 16일</p>

* <a href="https://teams.microsoft.com/l/app/f02fddc9-159a-4d58-9800-d94c4f64bfe8" target="_blank">저장소의 Teams 보기</a>
* <a href="https://appsource.microsoft.com/product/office/WA104381271" target="_blank">AppSource의 보기</a>

::: zone pivot="general"

### <a name="general-information"></a>일반 정보

승인된 연락처가 Microsoft에 제공한 정보:

| **정보** | **응답** |
|:----------------|:-------------|
| 앱 이름 | Calendar BOT |
| ID | WA104381271 |
| Office 365 클라이언트 지원 | Microsoft Teams |
| 파트너 회사 이름 | Approved Contact |
| 파트너 웹 사이트의 URL | [https://approvedcontact.com](https://approvedcontact.com) |
| 개인 정보 취급 방침의 URL | [https://approvedcontact.com/Privacy%20Policy%20Bot.pdf](https://approvedcontact.com/Privacy%20Policy%20Bot.pdf) |
| 사용 약관 URL | [https://approvedcontact.com/Terms%20of%20use.pdf](https://approvedcontact.com/Terms%20of%20use.pdf) |

 [!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="data"

### <a name="how-the-app-handles-data"></a>앱이 데이터를 처리하는 방법

이 정보는 승인된 연락처에서 이 앱이 조직 데이터를 수집 및 저장하는 방법 및 앱이 수집하는 데이터를 통해 조직이 하게 될 컨트롤에 대해 제공됩니다.

#### <a name="data-access-using-microsoft-graph"></a>Microsoft 365를 사용한 데이터 Graph

이 앱에 [Graph Microsoft 사용자 권한을](https://docs.microsoft.com/graph/permissions-reference) 나열합니다.

>| **사용 권한**  | **사용 권한 유형(위임/응용 프로그램)** | **데이터가 수집하나요? 수집의 사당성** | **데이터가 저장되어 있나요? 저장 사정이 있나요?** | **Azure AD 앱 ID** |
>|:----------------|:--------------------|:---------------------------------------------------|:--------------------------|:--------------------------|
>| Calendars.ReadWrite | 위임 | 일정 BOT의 경우 여러 사용자가 약속 있는 시간을 찾을 수 있는 약속이 있는 시간/약속이 있는 시간을 저장합니다.  | 모임을 예약하고, 무료/사용 시간 및 일정을 읽고 비교합니다. | adef9811-448f-4dd5-88d9-68734050fe58 |
>| Contacts.Read | 위임 | 예, 연락처 정보를 저장합니다. | 연락처 가져오기 및 동기화 | adef9811-448f-4dd5-88d9-68734050fe58 |
>| User.Read | 위임 | 예 | 기본 프로필 정보입니다. | adef9811-448f-4dd5-88d9-68734050fe58 |
>| User.ReadBasic.All | 위임 | 아니요 | 직장의 프로필을 보고, 무료 시간을 비교하고, 회의실을 예약하는 데 사용됩니다. | adef9811-448f-4dd5-88d9-68734050fe58 |
>| offline_access | 위임 | 예, 오프라인 사용자의 경우 사용 가능합니다. | 사용자가 Graph 사용하지 않는 경우 전화를 걸 수 있습니다. | adef9811-448f-4dd5-88d9-68734050fe58 |
>| openid | 위임 | 아니요 | Office 365 SSO. | adef9811-448f-4dd5-88d9-68734050fe58 |


#### <a name="non-microsoft-services-used"></a>비영구 Microsoft 서비스

앱이 Microsoft가 아닌 서비스로 조직 데이터를 전송하거나 공유하는 경우 앱에서 사용하는 비 Microsoft 서비스, 전송되는 데이터를 나열하고 앱이 이 정보를 전송해야 하는 이유에 대한 사유를 포함합니다.

>비영구 Microsoft 서비스 사용되지 않습니다.

#### <a name="data-access-via-bots"></a>봇을 통한 데이터 액세스

이 앱에 봇 또는 메시징 확장이 포함되어 있는 경우 팀 구성원의 명단(이름, 성, 표시 이름, 전자 메일 주소)이나 팀 구성원이 추가된 채팅의 최종 사용자 식별 정보(EUII)에 액세스할 수 있습니다. 이 앱이 이 기능을 사용하나요?

>| **EUII 액세스의 사유는 무엇입니까?**  | **EUII가 데이터베이스에 저장되어 있나요?** | **EUII 저장의 사유는 무엇입니까?** |
>|:--------------------------------|:---------------------|:--------------------------|
>| 이 로스터를 사용하여 팀의 모든 사람이 열려 있는 시간의 모임을 예약하는 데 사용할 수 있는 무료/사용 시간을 비교합니다. | 전자 메일 주소를 저장하기만 하여 사용중인 시간/시간을 비교할 수 있습니다. |  |


#### <a name="telemetry-data"></a>원격 분석 데이터

이 응용 프로그램의 원격 분석 또는 로그에 OII(조직 식별 정보) 또는 EUII(최종 사용자 식별 정보)가 나타나나요? 그렇다면 저장되는 데이터와 보존 및 제거 정책에 대해 설명하세요.

>예, 라이선스 구매를 Commercial Appsource에 연결하기 위한 전자 메일 주소를 기록합니다. 로그에서 이 정보를 삭제할 수 있는 기능을 제공합니다.

#### <a name="organizational-controls-for-data-stored-by-partner"></a>파트너가 저장한 데이터에 대한 조직 제어

조직의 관리자가 파트너 시스템에서 정보를 제어하는 방법에 대해 설명하는 방법 삭제, 보존, 감사, 보관, 최종 사용자 정책 등

>개발자만 로그에 액세스할 수 있습니다. 모든 개발 플랫폼에 액세스하기 위해 2FA를 적용합니다.

#### <a name="human-review-of-organizational-information"></a>조직 정보의 인적 검토

사람이 이 앱에서 수집하거나 저장하는 OII(조직 식별 정보) 데이터를 검토하거나 분석하는 데 관여하나요?

>아니요

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="mcas"

Microsoft Cloud App Security [카탈로그의](https://www.microsoft.com/enterprise-mobility-security/cloud-app-security) 정보가 아래에 표시됩니다.

<iframe height='1020' title='Microsoft Cloud App Security 정보' src='https://appmcasinfoprod.azurewebsites.net/#/dashboard/20445' frameborder='no' style='width: 100%;'></iframe>

<a href="https://appmcasinfoprod.azurewebsites.net/#/dashboard/20445" target="_blank">새 탭에서 보기</a>

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

