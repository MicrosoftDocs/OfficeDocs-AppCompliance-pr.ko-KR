---
title: 마이스터랩스 GmbH의 마인드마이스터 신청 정보
ms.author: elmalova
author: elenamalova
ms.date: 12/16/2019
ms.topic: article
ms.service: attestation
certification_type: attested
description: MindMeister의 모든 사용 가능한 보안 및 규정 준수 정보 정보, 데이터 처리 정책, Microsoft Cloud App Security 앱 카탈로그 정보 및 CSA STAR 레지스트리의 보안/규정 준수 정보.
zone_pivot_groups: app-info-data-mcas
ms.openlocfilehash: a37e6c35b7a557ee146ad91e65d8f453dd94377e
ms.sourcegitcommit: a44420a99a1a3a9d0e49f4be66f266e2d4ca7bbb
ms.translationtype: MT
ms.contentlocale: ko-KR
ms.lasthandoff: 05/19/2021
ms.locfileid: "52551919"
---
# <a name="mindmeister"></a>MindMeister

<p></p>
<img alt="Publisher Attestation: The information on this page is based on a self-assessment report provided by the app developer on the security, compliance, and data handling practices followed by this app. Microsoft makes no guarantees regarding the accuracy of the information." src="../media/attested.png" width="650" />
<p>최종 업데이트: 2019년 12월 16일</p>

* <a href="https://teams.microsoft.com/l/app/b66766e5-61ce-4001-b2e6-6817710d6d02" target="_blank">Teams 스토어에서 보기</a>
* <a href="https://appsource.microsoft.com/product/office/WA104381116" target="_blank">앱소스에서 보기</a>

::: zone pivot="general"

### <a name="general-information"></a>일반 정보

마이크로 소프트에 마이스터 랩스 GmbH에서 제공하는 정보 :

| **정보** | **응답** |
|:----------------|:-------------|
| 앱 이름 | MindMeister |
| ID | WA104381116 |
| 지원되는 Office 365 클라이언트 | Microsoft Teams |
| 파트너 회사 이름 | MeisterLabs GmbH |
| 파트너 웹사이트의 URL | [https://www.mindmeister.com](https://www.mindmeister.com) |
| Teams 응용 프로그램 정보 페이지의 URL | [https://support.mindmeister.com/](https://support.mindmeister.com/) |
| 개인정보 처리방침의 URL | [https://www.mindmeister.com/privacy](https://www.mindmeister.com/privacy) |
| 이용 약관의 URL | [https://www.mindmeister.com/legal](https://www.mindmeister.com/legal) |

 [!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="data"

### <a name="how-the-app-handles-data"></a>앱이 데이터를 처리하는 방법

이 정보는 이 앱이 조직 데이터를 수집하고 저장하는 방법과 앱이 수집하는 데이터에 대한 조직에 대한 제어에 대해 MeisterLabs GmbH에서 제공되었습니다.

#### <a name="data-access-using-microsoft-graph"></a>Microsoft Graph 을 사용하여 데이터 액세스

이 [앱에서 필요한 Microsoft Graph 권한을 나열합니다.](https://docs.microsoft.com/graph/permissions-reference)

>| **사용 권한**  | **권한 유형(위임/응용 프로그램)** | **데이터가 수집되고 있습니까? 그것을 수집하기위한 정당화?** | **데이터가 저장되어 있습니까? 그것을 저장하는 정당화?** | **Azure AD 앱 ID** |
>|:----------------|:--------------------|:---------------------------------------------------|:--------------------------|:--------------------------|
>| User.Read | 위임 | AAD ID, 테넌트 ID, 이메일, 디스플레이이름 - 당사의 응용 프로그램 내의 각 사용자를 식별할 수 있고 MindMeister 특정 데이터를 Microsoft 사용자와 연결할 수 있습니다(예: 어떤 맵이 어떤 사용자가 속한지). | 사용자가 로그인할 수 있도록 하고 앱이 UPN에 액세스할 수 있도록 하여 자동 로그인을 사용할 수 있습니다. | d312ff80-0c2b-42ad-887b-c6392bcf6353 |


#### <a name="non-microsoft-services-used"></a>사용되지 Microsoft 서비스

앱이 Microsoft 가 아닌 서비스와 조직 데이터를 전송하거나 공유하는 경우 앱에서 사용하는 비Microsoft 서비스, 전송되는 데이터를 나열하고 앱이 이 정보를 전송해야 하는 이유에 대한 명분을 포함합니다.

>비Microsoft 서비스 사용되지 않습니다.

#### <a name="data-access-via-bots"></a>봇을 통한 데이터 액세스

이 앱에 봇 또는 메시징 확장 프로그램이 포함된 경우 최종 사용자 식별 정보(EUII): 팀의 모든 팀 구성원의 명단(이름, 성, 표시 이름, 이메일 주소)에 액세스하거나 추가된 채팅을 할 수 있습니다. 이 응용 프로그램은이 기능을 사용합니까?

>| **EUII에 액세스할 수 있는 정당성?**  | **EUII는 데이터베이스에 저장되어 있습니까?** | **EUII를 저장하는 정당화?** |
>|:--------------------------------|:---------------------|:--------------------------|
>| 이미 MindMeister에 링크가 있는 Teams 사용자를 식별하고 봇이 설치되었다는 사실을 알려줍니다. | 팀 명단의 데이터는 저장하지 않습니다. |  |


#### <a name="telemetry-data"></a>원격 분석 데이터

조직 식별 정보(OII) 또는 최종 사용자 식별 정보(EUII)가 이 응용 프로그램의 원격 분석 또는 로그에 표시됩니까? 그렇다면 저장되는 데이터와 보존 및 제거 정책은 무엇입니까?

>경우에 따라 사용자 ID가 포함되지만 로그는 7일 후에 삭제되는 사용자 HTTP 요청을 기록합니다.

#### <a name="organizational-controls-for-data-stored-by-partner"></a>파트너가 저장한 데이터에 대한 조직 제어

조직의 관리자가 파트너 시스템에서 자신의 정보를 제어하는 방법을 설명해 보세요. 예를 들어 삭제, 보존, 감사, 보관, 최종 사용자 정책 등

>데이터는 독일의 보안 서버에 저장됩니다. 이 데이터에 대한 액세스는 2FA가 적용된 액세스 권한이 있는 소수의 조직 관리자로 제한됩니다.

#### <a name="human-review-of-organizational-information"></a>조직 정보의 인간 검토

이 앱에서 수집하거나 저장되는 조직 식별 정보(OII) 데이터를 검토하거나 분석하는 데 관여하는 사람이 있습니까?

>아니요

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="mcas"

[Microsoft Cloud App Security](https://www.microsoft.com/enterprise-mobility-security/cloud-app-security) 카탈로그의 정보는 아래에 나타납니다.

<iframe height='1020' title='Microsoft Cloud App Security 정보' src='https://appmcasinfoprod.azurewebsites.net/#/dashboard/20874' frameborder='no' style='width: 100%;'></iframe>

<a href="https://appmcasinfoprod.azurewebsites.net/#/dashboard/20874" target="_blank">새 탭에서 보기</a>

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

