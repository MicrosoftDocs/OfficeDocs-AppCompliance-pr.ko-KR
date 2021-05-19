---
title: 비누 상자에 의해 비누 상자에 대한 응용 프로그램 정보
ms.author: elmalova
author: elenamalova
ms.date: 12/16/2019
ms.topic: article
ms.service: attestation
certification_type: attested
description: Soapbox에 대한 사용 가능한 모든 보안 및 규정 준수 정보 정보, 데이터 처리 정책, Microsoft Cloud App Security 앱 카탈로그 정보 및 CSA STAR 레지스트리의 보안/규정 준수 정보.
zone_pivot_groups: app-info-data-mcas
ms.openlocfilehash: 6e2b43df38aac6307c36c4a2cc8d00fe1c3fb629
ms.sourcegitcommit: a44420a99a1a3a9d0e49f4be66f266e2d4ca7bbb
ms.translationtype: MT
ms.contentlocale: ko-KR
ms.lasthandoff: 05/19/2021
ms.locfileid: "52552779"
---
# <a name="soapbox"></a>Soapbox

<p></p>
<img alt="Publisher Attestation: The information on this page is based on a self-assessment report provided by the app developer on the security, compliance, and data handling practices followed by this app. Microsoft makes no guarantees regarding the accuracy of the information." src="../media/attested.png" width="650" />
<p>최종 업데이트: 2019년 12월 16일</p>

* <a href="https://teams.microsoft.com/l/app/b49e7913-3b3f-4125-adde-2b698fc12c8b" target="_blank">Teams 스토어에서 보기</a>
* <a href="https://appsource.microsoft.com/product/office/WA104381501" target="_blank">앱소스에서 보기</a>

::: zone pivot="general"

### <a name="general-information"></a>일반 정보

비누 박스에서 마이크로 소프트에 제공 된 정보 :

| **정보** | **응답** |
|:----------------|:-------------|
| 앱 이름 | Soapbox |
| ID | WA104381501 |
| 지원되는 Office 365 클라이언트 | Microsoft Teams |
| 파트너 회사 이름 | Soapbox |
| 파트너 웹사이트의 URL | [https://soapboxhq.com](https://soapboxhq.com) |
| Teams 응용 프로그램 정보 페이지의 URL | [https://msteams.services.soapboxhq.com/faqs](https://msteams.services.soapboxhq.com/faqs) |
| 개인정보 처리방침의 URL | [https://soapboxhq.com/privacy-policy/microsoft-teams](https://soapboxhq.com/privacy-policy/microsoft-teams) |
| 이용 약관의 URL | [https://soapboxhq.com/terms-of-service](https://soapboxhq.com/terms-of-service) |

 [!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="data"

### <a name="how-the-app-handles-data"></a>앱이 데이터를 처리하는 방법

이 정보는 이 앱이 조직 데이터를 수집하고 저장하는 방법과 조직에서 앱이 수집하는 데이터에 대한 제어에 대해 Soapbox에서 제공했습니다.

#### <a name="data-access-using-microsoft-graph"></a>Microsoft Graph 을 사용하여 데이터 액세스

이 [앱에서 필요한 Microsoft Graph 권한을 나열합니다.](https://docs.microsoft.com/graph/permissions-reference)

>| **사용 권한**  | **권한 유형(위임/응용 프로그램)** | **데이터가 수집되고 있습니까? 그것을 수집하기위한 정당화?** | **데이터가 저장되어 있습니까? 그것을 저장하는 정당화?** | **Azure AD 앱 ID** |
>|:----------------|:--------------------|:---------------------------------------------------|:--------------------------|:--------------------------|
>| 캘린더.읽기 쓰기 | 위임 | 동기화 토큰. | 캘린더 이벤트에 SoapBox 회의를 동기화하려면 캘린더 액세스가 필요합니다. |  |
>| User.Read | 위임 | 이름, 이메일, 마이크로 소프트 사용자 ID. | 이름과 이메일은 SoapBox 사용자를 만드는 데 사용됩니다. |  |
>| offline_access | 위임 |  | 동기화된 캘린더 이벤트와 관련있는 SoapBox 알림 시간을 만들기 위해 캘린더에 대한 오프라인 액세스가 필요합니다. |  |


#### <a name="non-microsoft-services-used"></a>사용되지 Microsoft 서비스

앱이 Microsoft 가 아닌 서비스와 조직 데이터를 전송하거나 공유하는 경우 앱에서 사용하는 비Microsoft 서비스, 전송되는 데이터를 나열하고 앱이 이 정보를 전송해야 하는 이유에 대한 명분을 포함합니다.

>비Microsoft 서비스 사용되지 않습니다.

#### <a name="data-access-via-bots"></a>봇을 통한 데이터 액세스

이 앱에 봇 또는 메시징 확장 프로그램이 포함된 경우 최종 사용자 식별 정보(EUII): 팀의 모든 팀 구성원의 명단(이름, 성, 표시 이름, 이메일 주소)에 액세스하거나 추가된 채팅을 할 수 있습니다. 이 응용 프로그램은이 기능을 사용합니까?

>| **EUII에 액세스할 수 있는 정당성?**  | **EUII는 데이터베이스에 저장되어 있습니까?** | **EUII를 저장하는 정당화?** |
>|:--------------------------------|:---------------------|:--------------------------|
>| 이 앱은 팀 명단 과 채팅 명단에 액세스하여 팀/채팅 팀과 함께 SoapBox에서 팀 채널을 만들 수 있습니다. | 이름, 이메일, 사용자의 Microsoft 사용자 ID는 Microsoft 팀 사용자에 대한 앱의 모양과 느낌을 개선하고 각 사용자가 회의 소프트웨어에 완전히 참여할 수 있도록 합니다. |  |


#### <a name="telemetry-data"></a>원격 분석 데이터

조직 식별 정보(OII) 또는 최종 사용자 식별 정보(EUII)가 이 응용 프로그램의 원격 분석 또는 로그에 표시됩니까? 그렇다면 저장되는 데이터와 보존 및 제거 정책은 무엇입니까?

>예. 이름, 이메일 및 Microsoft 사용자 ID는 최대 30일 동안 통합 로깅 플랫폼에 표시되어 문제를 식별하고 사용자가 플랫폼을 사용하도록 지원합니다. 30일 후에는 로깅 서버에서 데이터가 제거됩니다.

#### <a name="organizational-controls-for-data-stored-by-partner"></a>파트너가 저장한 데이터에 대한 조직 제어

조직의 관리자가 파트너 시스템에서 자신의 정보를 제어하는 방법을 설명해 보세요. 예를 들어 삭제, 보존, 감사, 보관, 최종 사용자 정책 등

>당사의 주요 인프라는 개인 네트워크의 AWS에 저장됩니다. 또한 Heroku 및 Azure에 구성된 봇도 있습니다. SSH 키 요구 사항으로 서버에 대한 액세스가 제한됩니다. 모든 요청은 SSL(TLS 1.3)을 통해입니다. 당사는 봇에서 플랫폼으로의 트래픽이 안전한지 확인하기 위해 서명된 요청을 사용합니다. 데이터는 현재 암호화됩니다. Dev ops 직원은 자신의 계정에 액세스하려면 2FA가 필요합니다.

#### <a name="human-review-of-organizational-information"></a>조직 정보의 인간 검토

이 앱에서 수집하거나 저장되는 조직 식별 정보(OII) 데이터를 검토하거나 분석하는 데 관여하는 사람이 있습니까?

>예

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="mcas"

[Microsoft Cloud App Security](https://www.microsoft.com/enterprise-mobility-security/cloud-app-security) 카탈로그의 정보는 아래에 나타납니다.

<iframe height='1020' title='Microsoft Cloud App Security 정보' src='https://appmcasinfoprod.azurewebsites.net/#/dashboard/35464' frameborder='no' style='width: 100%;'></iframe>

<a href="https://appmcasinfoprod.azurewebsites.net/#/dashboard/35464" target="_blank">새 탭에서 보기</a>

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

