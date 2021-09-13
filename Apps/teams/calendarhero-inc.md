---
title: CalendarHero Inc의 CalendarHero에 대한 응용 프로그램 정보
ms.author: elmalova
author: elenamalova
ms.date: 03/17/2020
ms.topic: article
ms.service: attestation
certification_type: attested
description: CalendarHero에 사용할 수 있는 모든 보안 및 규정 준수 정보, 데이터 처리 정책, CSA STAR 레지스트리의 Microsoft Cloud App Security 앱 카탈로그 정보 및 보안/규정 준수 정보
zone_pivot_groups: app-info-data-mcas
ms.openlocfilehash: 41a7dd8a2cb7d900ac26b228c4cc2522d76da59c
ms.sourcegitcommit: d85595f6518d8d05f0aee75380f51659908b6bcb
ms.translationtype: MT
ms.contentlocale: ko-KR
ms.lasthandoff: 09/12/2021
ms.locfileid: "59287082"
---
# <a name="calendarhero"></a>CalendarHero

<p></p>
<img alt="Publisher Attestation: The information on this page is based on a self-assessment report provided by the app developer on the security, compliance, and data handling practices followed by this app. Microsoft makes no guarantees regarding the accuracy of the information." src="../media/attested.png" width="650" />
<p>개발자가 마지막으로 업데이트한 날짜: 2020년 3월 17일</p>

* <a href="https://teams.microsoft.com/l/app/cac7469b-37cc-44f5-bf08-ff6654d35819" target="_blank">저장소의 Teams 보기</a>
* <a href="https://appsource.microsoft.com/product/office/WA200000150" target="_blank">AppSource의 보기</a>

::: zone pivot="general"

### <a name="general-information"></a>일반 정보

CalendarHero Inc에서 Microsoft에 제공한 정보:

| **정보** | **응답** |
|:----------------|:-------------|
| 앱 이름 | CalendarHero |
| ID | WA200000150 |
| Office 365 클라이언트 지원 | Microsoft Teams |
| 파트너 회사 이름 | CalendarHero Inc |
| 파트너 웹 사이트의 URL | [https://zoom.ai](https://zoom.ai) |
| 응용 프로그램 Teams 페이지의 URL입니다. | [https://faq.zoom.ai/](https://faq.zoom.ai/) |
| 개인 정보 취급 방침의 URL | [https://zoom.ai/privacy-policy](https://zoom.ai/privacy-policy) |
| 사용 약관 URL | [https://zoom.ai/terms-of-use](https://zoom.ai/terms-of-use) |

 [!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="data"

### <a name="how-the-app-handles-data"></a>앱이 데이터를 처리하는 방법

이 정보는 CalendarHero Inc에서 이 앱이 조직 데이터를 수집하고 저장하는 방법 및 앱이 수집하는 데이터를 통해 조직에서 제공하는 컨트롤에 대해 제공됩니다.

#### <a name="data-access-using-microsoft-graph"></a>Microsoft 365를 사용한 데이터 Graph

이 앱에 [Graph Microsoft 사용자 권한을](https://docs.microsoft.com/graph/permissions-reference) 나열합니다.

>| **사용 권한**  | **사용 권한 유형(위임/ 응용 프로그램)** | **데이터가 수집하나요? 수집의 사당성** | **데이터가 저장되어 있나요? 저장 사정이 있나요?** | **Azure AD 앱 ID** |
>|:----------------|:------------------------------------------------|:--------------------------------------------------------|:--------------------------------------------------|:--------------------|
>| Calendars.ReadWrite | 둘 다 | 모임은 Azure의 mongoDB에서 캐시되지만 설명은 암호화됩니다. | 사용자의 일정 이벤트에 액세스합니다. | [](https://docs.microsoft.com/microsoft-365-app-certification/azure/) |
>| Contacts.ReadWrite | 둘 다 | 연락처 이름 및 전자 메일 주소입니다. | 사용자의 연락처를 읽어 모임에 초대할 수 있습니다. | [](https://docs.microsoft.com/microsoft-365-app-certification/azure/) |
>| Group.Read.All | 둘 다 | 그룹 이름 및 구성원. | (선택 사항) 회사 사용자 그룹을 읽습니다(그룹과의 계획용). | [](https://docs.microsoft.com/microsoft-365-app-certification/azure/) |
>| Mail.Read | 둘 다 | 연락처 전자 메일/이름, 상호 작용의 빈도/재시도. | (선택 사항)는 사용자의 가장 중요한 연락처 아래에 전자 메일 메타 데이터를 읽는 데 사용됩니다(Machine Learning. | [](https://docs.microsoft.com/microsoft-365-app-certification/azure/) |
>| MailboxSettings.ReadWrite | 둘 다 | 사용자의 시간제어 | 사용자의 시간제어 | [](https://docs.microsoft.com/microsoft-365-app-certification/azure/) |
>| User.Read.All | 둘 다 | 사용자의 이름 전자 &amp; 메일(연락처로 저장) | (선택 사항) 회사 사용자 읽기(동료와의 계획) | [](https://docs.microsoft.com/microsoft-365-app-certification/azure/) |
>| offline_access | application | 아니요 | 사용자가 존재하지 않고 언제든지 백 엔드를 읽고 써야 합니다. | [](https://docs.microsoft.com/microsoft-365-app-certification/azure/) |


#### <a name="non-microsoft-services-used"></a>비영구 Microsoft 서비스

앱이 Microsoft가 아닌 서비스로 조직 데이터를 전송하거나 공유하는 경우 앱에서 사용하는 비 Microsoft 서비스, 전송되는 데이터를 나열하고 앱이 이 정보를 전송해야 하는 이유에 대한 사유를 포함합니다.

>비영구 Microsoft 서비스 사용되지 않습니다.

#### <a name="data-access-via-bots"></a>봇을 통한 데이터 액세스

이 앱에 봇 또는 메시징 확장이 포함되어 있는 경우 팀 구성원의 명단(이름, 성, 표시 이름, 전자 메일 주소)이나 팀 구성원이 추가된 채팅의 최종 사용자 식별 정보(EUII)에 액세스할 수 있습니다. 이 앱이 이 기능을 사용하나요?

>| **EUII 액세스의 사유는 무엇입니까?**  | **EUII가 데이터베이스에 저장되어 있나요?** | **EUII 저장의 사유는 무엇입니까?** |
>|:---------------------------------------|:-----------------------------------|:------------------------------------|
>| 모임 도우미 봇이 모임을 예약할 수 있도록 직장의 이름/전자 메일 가져오기 | 이름 &amp; 전자 메일. 두 가지 모두 빠른 검색 및 부분 이름 검색(예: )을 위해 데이터베이스에 저장됩니다. Joe P와의 만남) |  |


#### <a name="telemetry-data"></a>원격 분석 데이터

이 응용 프로그램의 원격 분석 또는 로그에 OII(조직 식별 정보) 또는 EUII(최종 사용자 식별 정보)가 나타나나요? 그렇다면 저장되는 데이터와 보존 및 제거 정책에 대해 설명하세요.

>사용자 및/또는 연락처의 전자 메일 주소는 로깅 공급자인 LogDNA에 이벤트를 기록하는 데 사용됩니다.

#### <a name="organizational-controls-for-data-stored-by-partner"></a>파트너가 저장한 데이터에 대한 조직 제어

조직의 관리자가 파트너 시스템에서 정보를 제어하는 방법에 대해 설명하는 방법 삭제, 보존, 감사, 보관, 최종 사용자 정책 등

>모든 데이터는 캐나다 Quebec 시에 있는 MS Azure 클라우드 데이터 센터에 저장됩니다. AES256으로 암호화된 필드도 여러 개 있습니다. 데이터베이스에 대한 액세스는 사용자/서비스 수준 자격 증명을 통해 엔지니어 및 백 엔드 서버에서만 사용할 수 있습니다.

#### <a name="human-review-of-organizational-information"></a>조직 정보의 인적 검토

사람이 이 앱에서 수집하거나 저장하는 OII(조직 식별 정보) 데이터를 검토하거나 분석하는 데 관여하나요?

>아니요

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="mcas"

Microsoft Cloud App Security [카탈로그의](https://www.microsoft.com/enterprise-mobility-security/cloud-app-security) 정보가 아래에 표시됩니다.

<iframe height='1020' title='Microsoft Cloud App Security 정보' src='https://appmcasinfoprod.azurewebsites.net/#/dashboard/35668' frameborder='no' style='width: 100%;'></iframe>

<a href="https://appmcasinfoprod.azurewebsites.net/#/dashboard/35668" target="_blank">새 탭에서 보기</a>

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

