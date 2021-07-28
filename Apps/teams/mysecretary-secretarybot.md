---
title: MySecretary의에 대한인계자용 응용 프로그램 정보
ms.author: elmalova
author: elenamalova
ms.date: 12/16/2019
ms.topic: article
ms.service: attestation
certification_type: attested
description: 에 대한 모든 보안 및 규정 준수 정보로, 이 정보의 데이터 처리 정책, CSA STAR 레지스트리의 Microsoft Cloud App Security 앱 카탈로그 정보 및 보안/규정 준수 정보를 확인할 수 있습니다.
zone_pivot_groups: app-info-data-mcas
ms.openlocfilehash: 8d7e2fce37cf43fe52cb050e85aa9e4fd5e00802
ms.sourcegitcommit: a613e40971c8b48fa2b7a35039b4331a8116763b
ms.translationtype: MT
ms.contentlocale: ko-KR
ms.lasthandoff: 07/22/2021
ms.locfileid: "53525452"
---
# <a name="secretarybot"></a>SecretaryBot

<p></p>
<img alt="Publisher Attestation: The information on this page is based on a self-assessment report provided by the app developer on the security, compliance, and data handling practices followed by this app. Microsoft makes no guarantees regarding the accuracy of the information." src="../media/attested.png" width="650" />
<p>개발자가 마지막으로 업데이트한 날짜: 2019년 12월 16일</p>

* <a href="https://teams.microsoft.com/l/app/256ff1bc-fd16-4f82-aeb3-8a6977ff2ec4" target="_blank">저장소의 Teams 보기</a>
* <a href="https://appsource.microsoft.com/product/office/WA104381085" target="_blank">AppSource의 보기</a>

::: zone pivot="general"

### <a name="general-information"></a>일반 정보

MySecretary에서 Microsoft에 제공하는 정보:

| **정보** | **응답** |
|:----------------|:-------------|
| 앱 이름 | SecretaryBot |
| ID | WA104381085 |
| Office 365 클라이언트 지원 | Microsoft Teams |
| 파트너 회사 이름 | MySecretary |
| 파트너 웹 사이트의 URL | [https://secretarybot.wordpress.com/](https://secretarybot.wordpress.com/) |
| 응용 프로그램 Teams 페이지의 URL입니다. | [https://secretarybot.wordpress.com/faq/](https://secretarybot.wordpress.com/faq/) |
| 개인 정보 취급 방침의 URL | [https://secretarybot.wordpress.com/privacy-policy/](https://secretarybot.wordpress.com/privacy-policy/) |
| 사용 약관 URL | [https://secretarybot.wordpress.com/terms-of-use/](https://secretarybot.wordpress.com/terms-of-use/) |

 [!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="data"

### <a name="how-the-app-handles-data"></a>앱이 데이터를 처리하는 방법

이 정보는 MySecretary에서 이 앱이 조직 데이터를 수집 및 저장하는 방법 및 앱이 수집하는 데이터를 통해 조직이 하게 될 컨트롤에 대해 제공됩니다.

#### <a name="data-access-using-microsoft-graph"></a>Microsoft 365를 사용한 데이터 Graph

이 앱에 [Graph Microsoft 사용자 권한을](https://docs.microsoft.com/graph/permissions-reference) 나열합니다.

>| **사용 권한**  | **사용 권한 유형(위임/ 응용 프로그램)** | **데이터가 수집하나요? 수집의 사당성** | **데이터가 저장되어 있나요? 저장 사정이 있나요?** | **Azure AD 앱 ID** |
>|:----------------|:------------------------------------------------|:--------------------------------------------------------|:--------------------------------------------------|:--------------------|
>| Calendars.Read.Shared | 위임 |  | 사용자 및 해당 동료의 무료 시간 정보를 페치합니다. | [](https://docs.microsoft.com/microsoft-365-app-certification/azure/) |
>| Calendars.ReadWrite | 위임 |  | 사용자 대신 모임 요청을 전송합니다. | [](https://docs.microsoft.com/microsoft-365-app-certification/azure/) |
>| MailboxSettings.Read | 위임 | 올바른 언어 표시를 위한 저장소 언어입니다. MS Graph API를 올바르게 호출하기 위해 타임존 저장 | 사용자의 언어 및 시간제어 설정을 페치합니다. | [](https://docs.microsoft.com/microsoft-365-app-certification/azure/) |
>| People.Read | 위임 |  | 사용자와 강력한 관계가 있는 동료를 찾아보아야 합니다. | [](https://docs.microsoft.com/microsoft-365-app-certification/azure/) |
>| User.Read | 위임 | 사용자 분석을 위한 사용자 이름, 도시, 국가 및 langauge를 저장합니다. 고객에게 연락하기 위한 전자 메일을 저장합니다. 전자 메일 주소를 사용한 적이 없지만 지원에 사용할 수 있습니다. | 사용자의 국가 및 기본 설정 언어를 찾으려고 합니다. MailboxSettings.Read에 대한 백업에 사용됩니다. | [](https://docs.microsoft.com/microsoft-365-app-certification/azure/) |
>| 전자 메일 | 위임 | 위 내용을 참조하세요. | 전자 메일을 저장합니다. | [](https://docs.microsoft.com/microsoft-365-app-certification/azure/) |
>| openid | 위임 |  | OpenID 인증의 경우 | [](https://docs.microsoft.com/microsoft-365-app-certification/azure/) |
>| profile | 위임 | MS ID 시스템에서 사용자의 고유 ID를 식별하기 위해 OID를 저장합니다. | 사용자 이름 및 OID를 들이기. OID를 사용하여 향후 추가 Outlook 연결해 보아야 합니다. | [](https://docs.microsoft.com/microsoft-365-app-certification/azure/) |


#### <a name="non-microsoft-services-used"></a>비영구 Microsoft 서비스

앱이 Microsoft가 아닌 서비스로 조직 데이터를 전송하거나 공유하는 경우 앱에서 사용하는 비 Microsoft 서비스, 전송되는 데이터를 나열하고 앱이 이 정보를 전송해야 하는 이유에 대한 사유를 포함합니다.

>비영구 Microsoft 서비스 사용되지 않습니다.

#### <a name="data-access-via-bots"></a>봇을 통한 데이터 액세스

이 앱에 봇 또는 메시징 확장이 포함되어 있는 경우 팀 구성원의 명단(이름, 성, 표시 이름, 전자 메일 주소)이나 팀 구성원이 추가된 채팅의 최종 사용자 식별 정보(EUII)에 액세스할 수 있습니다. 이 앱이 이 기능을 사용하나요?

>| **EUII 액세스의 사유는 무엇입니까?**  | **EUII가 데이터베이스에 저장되어 있나요?** | **EUII 저장의 사유는 무엇입니까?** |
>|:---------------------------------------|:-----------------------------------|:------------------------------------|
>| 이 정보를 사용하여 팀 모임 예약 | 아니요 |  |


#### <a name="telemetry-data"></a>원격 분석 데이터

이 응용 프로그램의 원격 분석 또는 로그에 OII(조직 식별 정보) 또는 EUII(최종 사용자 식별 정보)가 나타나나요? 그렇다면 저장되는 데이터와 보존 및 제거 정책에 대해 설명하세요.

>OII 또는 EUII 데이터는 원격 분석 또는 로그에 표시됩니다.

#### <a name="organizational-controls-for-data-stored-by-partner"></a>파트너가 저장한 데이터에 대한 조직 제어

조직의 관리자가 파트너 시스템에서 정보를 제어하는 방법에 대해 설명하는 방법 삭제, 보존, 감사, 보관, 최종 사용자 정책 등

>최종 사용자에게는 아직 관리 컨트롤을 제공하지 않지만 최종 사용자가 데이터 삭제를 요청하는 경우 해당 요청을 따를 수 있습니다.


[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="mcas"

Microsoft Cloud App Security [카탈로그의](https://www.microsoft.com/enterprise-mobility-security/cloud-app-security) 정보가 아래에 표시됩니다.

<iframe height='1020' title='Microsoft Cloud App Security 정보' src='https://appmcasinfoprod.azurewebsites.net/#/dashboard/35678' frameborder='no' style='width: 100%;'></iframe>

<a href="https://appmcasinfoprod.azurewebsites.net/#/dashboard/35678" target="_blank">새 탭에서 보기</a>

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

