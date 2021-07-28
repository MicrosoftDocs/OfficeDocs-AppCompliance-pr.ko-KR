---
title: StarLeaf의 StarLeaf에 대한 응용 프로그램 정보
ms.author: elmalova
author: elenamalova
ms.date: 08/24/2020
ms.topic: article
ms.service: attestation
certification_type: attested
description: StarLeaf에 사용할 수 있는 모든 보안 및 규정 준수 정보, 데이터 처리 정책, CSA STAR 레지스트리의 Microsoft Cloud App Security 앱 카탈로그 정보 및 보안/규정 준수 정보
zone_pivot_groups: app-info-data-mcas
ms.openlocfilehash: 8f9878d4de6e09c283c6d13ee7351de9fb5f0eb8
ms.sourcegitcommit: a613e40971c8b48fa2b7a35039b4331a8116763b
ms.translationtype: MT
ms.contentlocale: ko-KR
ms.lasthandoff: 07/22/2021
ms.locfileid: "53528234"
---
# <a name="starleaf"></a>StarLeaf

<p></p>
<img alt="Publisher Attestation: The information on this page is based on a self-assessment report provided by the app developer on the security, compliance, and data handling practices followed by this app. Microsoft makes no guarantees regarding the accuracy of the information." src="../media/attested.png" width="650" />
<p>개발자가 마지막으로 업데이트한 날짜: 2020년 8월 24일</p>

* <a href="https://teams.microsoft.com/l/app/220b3db0-e3be-40df-8148-f0e0c33a986a" target="_blank">저장소의 Teams 보기</a>
* <a href="https://appsource.microsoft.com/product/office/WA200000185" target="_blank">AppSource의 보기</a>

::: zone pivot="general"

### <a name="general-information"></a>일반 정보

StarLeaf에서 Microsoft에 제공한 정보:

| **정보** | **응답** |
|:----------------|:-------------|
| 앱 이름 | StarLeaf |
| ID | WA200000185 |
| Office 365 클라이언트 지원 | Microsoft Teams |
| 파트너 회사 이름 | StarLeaf |
| 파트너 웹 사이트의 URL | [https://www.starleaf.com](https://www.starleaf.com) |
| 개인 정보 취급 방침의 URL | [https://support.starleaf.com/legal-information/starleaf-pri...](https://support.starleaf.com/legal-information/starleaf-privacy-notice/) |
| 사용 약관 URL | [https://support.starleaf.com/legal-information/starleaf-clo...](https://support.starleaf.com/legal-information/starleaf-cloud-services-customer-terms-of-use/) |

 [!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="data"

### <a name="how-the-app-handles-data"></a>앱이 데이터를 처리하는 방법

이 정보는 StarLeaf에서 이 앱이 조직 데이터를 수집하고 저장하는 방법 및 조직이 수집하는 데이터를 통해 조직이 제공하는 컨트롤에 대해 제공됩니다.

#### <a name="data-access-using-microsoft-graph"></a>Microsoft 365를 사용한 데이터 Graph

이 앱에 [Graph Microsoft 사용자 권한을](https://docs.microsoft.com/graph/permissions-reference) 나열합니다.

>| **사용 권한**  | **사용 권한 유형(위임/ 응용 프로그램)** | **데이터가 수집하나요? 수집의 사당성** | **데이터가 저장되어 있나요? 저장 사정이 있나요?** | **Azure AD 앱 ID** |
>|:----------------|:------------------------------------------------|:--------------------------------------------------------|:--------------------------------------------------|:--------------------|
>| Calendars.ReadWrite | application | 모임의 iCalUId, 모임 시간/날짜, 참석자 전자 메일 주소 및 모임에서 사용자 지정 속성 인터페이스를 사용하여 읽고 쓰는 Single-Value-Extended-Property를 Office.js 저장합니다. iCalUId는 사용자의 outlook 일정에 있는&#8217;서비스의 비디오 모임과 상관 관계가 있는 데 사용됩니다. 시간/날짜 및 참석자는 서비스의 올바른 사용자에게 올바른 시기에 비디오 모임을 제공하는 데 사용됩니다. SVEP는 O365 추가 기능과 함께 사용되어 사용자가 녹음/녹화와 같은 서비스에서 비디오 모임에 대한 세부 정보를 설정할 수 있는 인터페이스를 제공합니다. | webhook 알림을 구독하여 일정의 이벤트에 대한 사용자 변경 내용을 추적하고 일관되게 서비스를 업데이트하는 데 사용됩니다. 또한 사용자가 Teams 앱과 상호 작용하고 서비스에서 모임을 예약할 때 일정에 이벤트를 만드는 데도 사용됩니다. | [6e86b349-768f-4953-ac2e-fb03f92db4be](https://docs.microsoft.com/microsoft-365-app-certification/azure/6e86b349-768f-4953-ac2e-fb03f92db4be) |
>| User.Read | application | 로그인할 수 있게 oauth 새로 고침 토큰을 저장합니다. 사용자 프로필 ID를 저장하여 해당 사용자의 향후 OAuth 시도와 비교할 수 있도록&#8217;두 번 저장하지 않도록 합니다.  | 사용자가 앱에 로그인할 수 있도록 허용하고 앱에서 사용자의 전자&#8217;주소로 로그인을 서비스의 계정과 상관 관계화할 수 있도록 허용합니다.  | [6e86b349-768f-4953-ac2e-fb03f92db4be](https://docs.microsoft.com/microsoft-365-app-certification/azure/6e86b349-768f-4953-ac2e-fb03f92db4be) |


#### <a name="non-microsoft-services-used"></a>비영구 Microsoft 서비스

앱이 Microsoft가 아닌 서비스로 조직 데이터를 전송하거나 공유하는 경우 앱에서 사용하는 비 Microsoft 서비스, 전송되는 데이터를 나열하고 앱이 이 정보를 전송해야 하는 이유에 대한 사유를 포함합니다.

>| **모든 비 Microsoft 서비스 OII가 다음으로 전송됩니다.** |  **전송되는 OII는 무엇입니까?** | **OII 전송의 사당성** |
>|:-----------------------------------------------------|:------------------------------|:----------------------------------------|
>| 기술 지원 문제가 발생하는 경우 사례 관리를 위해 조직 데이터가 SalesForce로 전송될 수 있습니다. 사용자가 PSTN 전화 접속 기능을 사용하는 경우 통화가 Twilio, Plivo 또는 Voxbone을 통해 흐르게 됩니다. |  | 해당 없음 |

#### <a name="data-access-via-bots"></a>봇을 통한 데이터 액세스

이 앱에 봇 또는 메시징 확장이 포함되어 있는 경우 팀 구성원의 명단(이름, 성, 표시 이름, 전자 메일 주소)이나 팀 구성원이 추가된 채팅의 최종 사용자 식별 정보(EUII)에 액세스할 수 있습니다. 이 앱이 이 기능을 사용하나요?

>| **EUII 액세스의 사유는 무엇입니까?**  | **EUII가 데이터베이스에 저장되어 있나요?** | **EUII 저장의 사유는 무엇입니까?** |
>|:---------------------------------------|:-----------------------------------|:------------------------------------|
>| 봇은 봇을 통해 모임을 예약하는 사용자/호스트를 대신하여 모임을 예약하기 위해 팀의 로스터에 액세스합니다. 이를 통해 StarLeaf는 하나의 단추로 모임에 참가할 수 있는 원활한 참가 환경을 제공할 수 있습니다. | 이름, 성, 전자 메일 주소. 이렇게 하면 StarLeaf 봇이 봇과 상호 작용한 사용자/호스트를 대신하여 모임을 예약하고 팀의 다른 구성원을 모임에 초대할 수 있습니다. |  |


#### <a name="telemetry-data"></a>원격 분석 데이터

이 응용 프로그램의 원격 분석 또는 로그에 OII(조직 식별 정보) 또는 EUII(최종 사용자 식별 정보)가 나타나나요? 그렇다면 저장되는 데이터와 보존 및 제거 정책에 대해 설명하세요.

>예. 로그에는 사용자 이름, IP 주소, 통화 정보 기록, 연결 품질(패킷 손실, 비트 전송률), 장치 유형, 통화 진행률에 대한 정보가 포함됩니다. 이 정보는 기술 지원 팀 및 선임 개발자가 서비스 문제를 분석하는 데 사용할 수 있습니다. 데이터는 90일 후에 비동기화됩니다. 이 데이터를 보호하기 위한 컨트롤은 ISO/IEC 27001 인증에 따라 감사됩니다.

#### <a name="organizational-controls-for-data-stored-by-partner"></a>파트너가 저장한 데이터에 대한 조직 제어

조직의 관리자가 파트너 시스템에서 정보를 제어하는 방법에 대해 설명하는 방법 삭제, 보존, 감사, 보관, 최종 사용자 정책 등

>데이터는 사용자가 계정이&#8217;센터에 있는 데이터 센터의 StarLeaf&#8217;로그 서버에 저장되고 동일한 관할권 내의 하나 이상의 데이터 센터에 백업됩니다. 데이터에 대한 액세스는 강도를 검사하는 사용자별 암호를 사용하여 개별 사용자 계정으로 액세스할 수 있습니다. StarLeaf&#8217;서비스 사용자 계정이 HR 시스템 및 회사 Active Directory 그룹에 대해 자동으로 감사되어 보안 및 규정 준수 팀에 문제가 발견될 경우 경고합니다.

#### <a name="human-review-of-organizational-information"></a>조직 정보의 인적 검토

사람이 이 앱에서 수집하거나 저장하는 OII(조직 식별 정보) 데이터를 검토하거나 분석하는 데 관여하나요?

>예

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="mcas"

Microsoft Cloud App Security [카탈로그의](https://www.microsoft.com/enterprise-mobility-security/cloud-app-security) 정보가 아래에 표시됩니다.

<iframe height='1020' title='Microsoft Cloud App Security 정보' src='https://appmcasinfoprod.azurewebsites.net/#/dashboard/35997' frameborder='no' style='width: 100%;'></iframe>

<a href="https://appmcasinfoprod.azurewebsites.net/#/dashboard/35997" target="_blank">새 탭에서 보기</a>

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

