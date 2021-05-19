---
title: 휴가 추적기에 의해 휴가 추적기에 대한 응용 프로그램 정보
ms.author: elmalova
author: elenamalova
ms.date: 02/05/2021
ms.topic: article
ms.service: attestation
certification_type: attested
description: 휴가 추적기에 대한 사용 가능한 모든 보안 및 규정 준수 정보 정보, 데이터 처리 정책, Microsoft Cloud App Security 앱 카탈로그 정보 및 CSA STAR 레지스트리의 보안 /규정 준수 정보.
zone_pivot_groups: app-info-data-mcas-identity
ms.openlocfilehash: 89ed0cc27e26acdeae13cc787fc180cc9f93b8ae
ms.sourcegitcommit: a44420a99a1a3a9d0e49f4be66f266e2d4ca7bbb
ms.translationtype: MT
ms.contentlocale: ko-KR
ms.lasthandoff: 05/19/2021
ms.locfileid: "52550998"
---
# <a name="vacation-tracker"></a>Vacation Tracker

<p></p>
<img alt="Publisher Attestation: The information on this page is based on a self-assessment report provided by the app developer on the security, compliance, and data handling practices followed by this app. Microsoft makes no guarantees regarding the accuracy of the information." src="../media/attested.png" width="650" />
<p>최종 업데이트: 2021년 2월 5일</p>

* <a href="https://teams.microsoft.com/l/app/eab5463e-8168-40ee-887a-7ac78de1d266" target="_blank">Teams 스토어에서 보기</a>
* <a href="https://appsource.microsoft.com/product/office/WA200002167" target="_blank">앱소스에서 보기</a>

::: zone pivot="general"

### <a name="general-information"></a>일반 정보

Microsoft에 휴가 추적기에 의해 제공 된 정보 :

| **정보** | **응답** |
|:----------------|:-------------|
| 앱 이름 | Vacation Tracker |
| ID | WA200002167 |
| 지원되는 Office 365 클라이언트 | Microsoft Teams |
| 파트너 회사 이름 | Vacation Tracker |
| 파트너 웹사이트의 URL | [https://vacationtracker.io](https://vacationtracker.io) |
| Teams 응용 프로그램 정보 페이지의 URL | [https://vacationtracker.io/vacation-calendar-tracker-featur...](https://vacationtracker.io/vacation-calendar-tracker-features/) |
| 개인정보 처리방침의 URL | [https://vacationtracker.io/privacy-policy/](https://vacationtracker.io/privacy-policy/) |
| 이용 약관의 URL | [https://vacationtracker.io/terms-of-service/](https://vacationtracker.io/terms-of-service/) |

 [!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="data"

### <a name="how-the-app-handles-data"></a>앱이 데이터를 처리하는 방법

이 정보는 이 앱이 조직 데이터를 수집하고 저장하는 방법과 앱이 수집하는 데이터에 대한 조직에 대한 제어에 대해 Vacation Tracker에서 제공했습니다.

#### <a name="data-access-using-microsoft-graph"></a>Microsoft Graph 을 사용하여 데이터 액세스

이 [앱에서 필요한 Microsoft Graph 권한을 나열합니다.](https://docs.microsoft.com/graph/permissions-reference)

>| **사용 권한**  | **권한 유형(위임/응용 프로그램)** | **데이터가 수집되고 있습니까? 그것을 수집하기위한 정당화?** | **데이터가 저장되어 있습니까? 그것을 저장하는 정당화?** | **Azure AD 앱 ID** |
>|:----------------|:--------------------|:---------------------------------------------------|:--------------------------|:--------------------------|
>| Group.Read.All | 위임 | 사용자가 주간 또는 일일 알림을 설정할 때 공용 채널 ID와 이름을 읽습니다. | 사용자는 휴가 추적기에서 매일 또는 매주 알림을 수신하려는 채널을 선택할 수 있습니다. 사용자가 원하는 채널을 선택하면 채널 ID를 저장합니다. | eab5463e-8168-40ee-887a-7ac78de1d2666 |
>| 팀.읽기 기본.모든 | 위임 | 사용자가 휴가 추적기에 가입할 팀을 선택할 수 있도록 가입 기간 동안 가입한 Microsoft Teams 팀 사용자를 나열합니다. 그들은 또는 자신의 전체 조직에 가입 할 수 있습니다. | 사용자가 휴가 추적기에 단일 팀으로 가입하는 경우에만 선택한 팀에 Microsoft Teams 팀 ID를 저장합니다(전체 조직이 아님). 당사는 팀 아이디를 사용하여 로그인한 사용자를 Vacation Tracker의 기존 계정과 연결합니다. | eab5463e-8168-40ee-887a-7ac78de1d2666 |
>| User.Read | 위임 | 이름, ID 및 테넌트 ID를 포함한 기본 사용자의 정보를 수집합니다. 이 데이터를 사용하여 로그인한 사용자를 휴가 추적기의 조직에 연결합니다. | 사용자의 이름, ID 및 테넌트 ID를 저장합니다. 이 데이터를 사용하여 로그인한 사용자를 휴가 추적기의 조직에 연결합니다. | eab5463e-8168-40ee-887a-7ac78de1d2666 |
>| User.Read.All | 위임 | 당사 사용자는 Microsoft 365 조직 또는 Microsoft Teams 팀에서 모든 사용자를 가져올 수 있습니다. 이 권한을 사용하여 선택한 Microsoft Teams 팀 또는 조직에 대해 라이선스가 부여된 사용자만 가져옵니다. | 당사는 이름, 이메일 주소 및 사용자 ID를 포함하여 가져온 사용자에 대한 기본 정보를 저장합니다. | eab5463e-8168-40ee-887a-7ac78de1d2666 |
>| User.ReadBasic.All | 위임 | 사용자가 조직 또는 Microsoft Teams 팀에서 다른 사용자를 가져올 수 있도록 허용합니다. 이 권한을 사용하여 사용 가능한 사용자와 해당 이메일 주소를 가져오기 팝업에 나열합니다. | 사용자가 휴가 추적기로 가져올 동료를 선택하면 이름, 이메일 주소 및 사용자 ID를 포함하여 이러한 가져온 사용자에 대한 기본 정보를 저장합니다. | eab5463e-8168-40ee-887a-7ac78de1d2666 |
>| 전자 메일 | 위임 | 사용자가 Microsoft AAD를 사용하여 로그인할 때 전자 메일 주소를 고유 식별자로 저장합니다. | 우리는 사용자의 이메일을 고유 식별자로 저장합니다. 우리는 통신이 이메일을 사용하지 않습니다, 사용자는 우리가 가입 하는 동안 통신에 사용 하는 그들의 비즈니스 이메일 주소를 입력 합니다. | eab5463e-8168-40ee-887a-7ac78de1d2666 |
>| offline_access | 위임 | 당사는 이 허가를 받은 데이터를 수집하지 않습니다. 액세스 권한이 있는 데이터에 대한 액세스를 유지하는 데 사용됩니다. | 이 권한으로 는 어떠한 데이터도 저장하지 않습니다. | eab5463e-8168-40ee-887a-7ac78de1d2666 |
>| 오픈 ID | 위임 | 이 권한을 사용하여 휴가 추적기에 로그인하거나 사용자를 등록합니다. 당사는 이 권한으로 특정 데이터를 수집하지 않습니다. | 이 권한을 사용하여 휴가 추적기에 로그인하거나 사용자를 등록합니다. 이 권한으로 특정 데이터를 저장하지 않습니다. | eab5463e-8168-40ee-887a-7ac78de1d2666 |
>| 윤곽 | 위임 | 이름, ID 및 테넌트 ID를 포함한 기본 사용자의 정보를 수집합니다. 이 데이터를 사용하여 로그인한 사용자를 휴가 추적기의 조직에 연결합니다. | 사용자의 이름, ID 및 테넌트 ID를 저장합니다. 이 데이터를 사용하여 로그인한 사용자를 휴가 추적기의 조직에 연결합니다. | eab5463e-8168-40ee-887a-7ac78de1d2666 |


#### <a name="non-microsoft-services-used"></a>사용되지 Microsoft 서비스

앱이 Microsoft 가 아닌 서비스와 조직 데이터를 전송하거나 공유하는 경우 앱에서 사용하는 비Microsoft 서비스, 전송되는 데이터를 나열하고 앱이 이 정보를 전송해야 하는 이유에 대한 명분을 포함합니다.

>| **모든 Microsoft 서비스 OII가** |  **어떤 OII가 전송됩니까?** | **OII 전송에 대한 정당화?** |
>|:-------------------|:--------------------------|:--------------------------|
>| 스트라이프, AWS, 선명한, Customer.io, 세그먼트, 진폭, 구글 태그 매니저 | 회사 이름(사용자가 입력한 대로) | 사용자가 가입하면 회사 이름을 입력하고 제품 내에서 이 이름을 조직 이름으로 사용합니다. |

#### <a name="data-access-via-bots"></a>봇을 통한 데이터 액세스

이 앱에 봇 또는 메시징 확장 프로그램이 포함된 경우 최종 사용자 식별 정보(EUII): 팀의 모든 팀 구성원의 명단(이름, 성, 표시 이름, 이메일 주소)에 액세스하거나 추가된 채팅을 할 수 있습니다. 이 응용 프로그램은이 기능을 사용합니까?

>| **EUII에 액세스할 수 있는 정당성?**  | **EUII는 데이터베이스에 저장되어 있습니까?** | **EUII를 저장하는 정당화?** |
>|:--------------------------------|:---------------------|:--------------------------|
>| 봇은 봇과 통신하는 사용자에 대한 기본 정보를 볼 수 있습니다. 그러나 해당 정보를 저장하거나 사용하지 않습니다. 우리는 사용자의 ID, 대화 ID 및 봇에 보낸 메시지만 사용합니다. | 우리는 사용자의 이메일 주소, 사용자의 이름 (Microsoft AAD에 정의 된 대로) 및 사용자의 프로필 사진 (Microsoft AAD에서)을 저장합니다. | 당사는 이메일 주소를 사용자의 고유 식별자로 사용하고 사용자의 이름과 프로필 사진을 사용하여 동일한 회사의 관리자와 승인자가 대시보드에서 직원을 인식할 수 있도록 합니다.  |


#### <a name="telemetry-data"></a>원격 분석 데이터

조직 식별 정보(OII) 또는 최종 사용자 식별 정보(EUII)가 이 응용 프로그램의 원격 분석 또는 로그에 표시됩니까? 그렇다면 저장되는 데이터와 보존 및 제거 정책은 무엇입니까?

>회사 이름과 이러한 유형의 데이터에 대한 표준 1년 보존 정책에 따라 유지 및 제거됩니다.

#### <a name="organizational-controls-for-data-stored-by-partner"></a>파트너가 저장한 데이터에 대한 조직 제어

조직의 관리자가 파트너 시스템에서 자신의 정보를 제어하는 방법을 설명해 보세요. 예를 들어 삭제, 보존, 감사, 보관, 최종 사용자 정책 등

>우선, 당사는 사용자가 요구하는 최소한의 데이터를 수집합니다. 그런 다음 파트너와 가능한 최소 한도를 공유하고 마지막으로 데이터 보존 정책이 있어 해당되는 경우 모든 데이터가 1년 이내에 제거됩니다.

#### <a name="human-review-of-organizational-information"></a>조직 정보의 인간 검토

이 앱에서 수집하거나 저장되는 조직 식별 정보(OII) 데이터를 검토하거나 분석하는 데 관여하는 사람이 있습니까?

>예

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="mcas"

[Microsoft Cloud App Security](https://www.microsoft.com/enterprise-mobility-security/cloud-app-security) 카탈로그의 정보는 아래에 나타납니다.

<iframe height='1020' title='Microsoft Cloud App Security 정보' src='https://appmcasinfoprod.azurewebsites.net/#/dashboard/36417' frameborder='no' style='width: 100%;'></iframe>

<a href="https://appmcasinfoprod.azurewebsites.net/#/dashboard/36417" target="_blank">새 탭에서 보기</a>

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="identity"

### <a name="identity-information"></a>신원 정보

이 정보는 이 앱이 인증, 권한 부여, 응용 프로그램 등록 모범 사례 및 기타 ID 기준을 처리하는 방법에 대해 Vacation Tracker에서 제공했습니다.

| **정보** | **응답** |
|:----------------|:-------------|
| Microsoft 식별 플랫폼(Azure AD)과 통합합니까?  | 예 |
| Microsoft ID 플랫폼 통합 검사 목록에 설명된 모든 적용 가능한 모범 사례를 검토하고 준수했습니까?  | 예 |
| 앱에서 인증에 MSAL(Microsoft 인증 라이브러리)을 사용합니까? | 아니요 |
| 앱이 조건부 액세스 정책을 지원합니까? | 아니요 |
| 앱에서 시나리오에 대한 최소 권한 권한을 요청합니까? | 예 |
| 앱의 정적 등록 권한은 앱이 동적으로 점진적으로 요청하는 권한을 정확하게 반영합니까? | 예 |
| 앱이 다중 테넌션을 지원합니까? | 예 |
| 앱에 기밀 클라이언트가 있습니까? | 예 |
| 앱에 등록된 URI(리디렉션 통합 리소스 식별자)를 모두 소유하고 있습니까? | 예 |
| 앱의 경우 무엇을 사용하지 않으려습니까? | - 와일드카드 리디렉션 URI,<br/>- OAuth2 암시적 Flow, SPA에 필요한 경우가 아니면<br/>- 리소스 소유자 암호 자격 증명(ROPC) 흐름 |
| 앱에서 웹 API가 노출됩니까? | 예 |
| 권한 모델은 클라이언트 앱이 적절한 동의를 받는 경우에만 호출을 성공시킬 수 있습니까? | 예 |
| 앱에서 미리 보기 API를 사용합니까? | 아니요 |
| 앱에서 비하 API를 사용합니까? | 아니요 |

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end
