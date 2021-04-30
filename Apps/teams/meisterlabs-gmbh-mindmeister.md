---
title: MeisterLabs GmbH의 MindMeister에 대한 응용 프로그램 정보
ms.author: elmalova
author: elenamalova
ms.date: 12/16/2019
ms.topic: article
ms.service: attestation
description: MindMeister, 데이터 처리 정책, CSA STAR 레지스트리의 Microsoft Cloud App Security 앱 카탈로그 정보 및 보안/규정 준수 정보에 대해 사용할 수 있는 모든 보안 및 규정 준수 정보
zone_pivot_groups: app-info-data-mcas
ms.openlocfilehash: c1630248ebdb667baf6b386f03f777a8d7dd6c89
ms.sourcegitcommit: e97156a6eaf1d5ec5c26fd14add210a92bacd944
ms.translationtype: MT
ms.contentlocale: ko-KR
ms.lasthandoff: 04/30/2021
ms.locfileid: "52094489"
---
# <a name="mindmeister"></a>MindMeister

<p></p>
<img alt="Publisher Attestation: The information on this page is based on a self-assessment report provided by the app developer on the security, compliance, and data handling practices followed by this app. Microsoft makes no guarantees regarding the accuracy of the information." src="../media/attested.png" width="650" />
<p>개발자가 마지막으로 업데이트한 날짜: 2019년 12월 16일</p>

* <a href="https://teams.microsoft.com/l/app/b66766e5-61ce-4001-b2e6-6817710d6d02" target="_blank">저장소의 Teams 보기</a>
* <a href="https://appsource.microsoft.com/product/office/WA104381116" target="_blank">AppSource의 보기</a>

::: zone pivot="general"

### <a name="general-information"></a>일반 정보

MeisterLabs GmbH에서 Microsoft에 제공하는 정보:

| **정보** | **응답** |
|:----------------|:-------------|
| 앱 이름 | MindMeister |
| ID | WA104381116 |
| 기능 | 봇, 탭, 메시징 익스텐션, 커넥터 |
| Office 365 클라이언트 지원 | Microsoft Teams |
| 파트너 회사 이름 | MeisterLabs GmbH |
| 파트너 웹 사이트의 URL | [https://www.mindmeister.com](https://www.mindmeister.com) |
| 응용 프로그램 Teams 페이지의 URL입니다. | [https://support.mindmeister.com/](https://support.mindmeister.com/) |
| 개인 정보 취급 방침의 URL | [https://www.mindmeister.com/privacy](https://www.mindmeister.com/privacy) |
| 사용 약관 URL | [https://www.mindmeister.com/legal](https://www.mindmeister.com/legal) |

 [!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="data"

### <a name="how-the-app-handles-data"></a>앱이 데이터를 처리하는 방법

이 정보는 MeisterLabs GmbH에서 이 앱이 조직 데이터를 수집하고 저장하는 방법 및 앱이 수집하는 데이터에 대해 조직에서 사용할 컨트롤에 대해 제공됩니다.

#### <a name="data-access-using-microsoft-graph"></a>Microsoft 365를 사용한 데이터 Graph

이 앱에 [Graph Microsoft 사용자 권한을](https://docs.microsoft.com/graph/permissions-reference) 나열합니다.

>| **사용 권한**  | **사용 권한 유형(위임/응용 프로그램)** | **데이터가 수집하나요? 수집의 사당성** | **데이터가 저장되어 있나요? 저장 사정이 있나요?** | **Azure AD 앱 ID** |
>|:----------------|:--------------------|:---------------------------------------------------|:--------------------------|:--------------------------|
>| User.Read | 위임 | AAD ID, 테넌트 ID, 전자 메일, displayName - 응용 프로그램 내에서 각 사용자를 식별하고 MindMeister 특정 데이터를 Microsoft 사용자(예: 어느 사용자에게 속하는 지도)와 연결하는 데 사용할 수 있습니다. | 사용자가 로그인할 수 있도록 허용하고 자동 로그인을 사용하도록 설정하기 위해 앱에 UPN에 대한 액세스 권한을 부여합니다. | d312ff80-0c2b-42ad-887b-c6392bcf6353 |


#### <a name="non-microsoft-services-used"></a>비영구 Microsoft 서비스

앱이 Microsoft가 아닌 서비스로 조직 데이터를 전송하거나 공유하는 경우 앱에서 사용하는 비 Microsoft 서비스, 전송되는 데이터를 나열하고 앱이 이 정보를 전송해야 하는 이유에 대한 사유를 포함합니다.

>비영구 Microsoft 서비스 사용되지 않습니다.

#### <a name="data-access-via-bots"></a>봇을 통한 데이터 액세스

이 앱에 봇 또는 메시징 확장이 포함되어 있는 경우 팀 구성원의 명단(이름, 성, 표시 이름, 전자 메일 주소)이나 팀 구성원이 추가된 채팅의 최종 사용자 식별 정보(EUII)에 액세스할 수 있습니다. 이 앱이 이 기능을 사용하나요?

>| **EUII 액세스의 사유는 무엇입니까?**  | **EUII가 데이터베이스에 저장되어 있나요?** | **EUII 저장의 사유는 무엇입니까?** |
>|:--------------------------------|:---------------------|:--------------------------|
>| MindMeister에 Teams 이미 있는 사용자를 식별하고 봇이 설치되었습니다. | 팀명단의 데이터는 저장하지 않습니다. |  |



#### <a name="telemetry-data"></a>원격 분석 데이터

이 응용 프로그램의 원격 분석 또는 로그에 OII(조직 식별 정보) 또는 EUII(최종 사용자 식별 정보)가 나타나나요? 그렇다면 저장되는 데이터와 보존 및 제거 정책에 대해 설명하세요.

>경우에 따라 사용자 ID를 포함하지만 로그가 7일 후에 삭제되는 사용자 HTTP 요청을 기록합니다.

#### <a name="organizational-controls-for-data-stored-by-partner"></a>파트너가 저장한 데이터에 대한 조직 제어

조직의 관리자가 파트너 시스템에서 정보를 제어하는 방법에 대해 설명하는 방법 삭제, 보존, 감사, 보관, 최종 사용자 정책 등

>데이터는 독일의 보안 서버에 저장됩니다. 이 데이터에 대한 액세스는 2FA가 적용된 액세스 권한을 가진 일부 조직 관리자로 제한됩니다.

#### <a name="human-review-of-organizational-information"></a>조직 정보의 인적 검토

사람이 이 앱에서 수집하거나 저장하는 OII(조직 식별 정보) 데이터를 검토하거나 분석하는 데 관여하나요?

>아니요

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="mcas"

Microsoft Cloud App Security [카탈로그의](https://www.microsoft.com/enterprise-mobility-security/cloud-app-security) 정보가 아래에 표시됩니다.

<iframe height='1020' title='Microsoft Cloud App Security 정보' src='https://appmcasinfoprod.azurewebsites.net/#/dashboard/20874' frameborder='no' style='width: 100%;'></iframe>

<a href="https://appmcasinfoprod.azurewebsites.net/#/dashboard/20874" target="_blank">새 탭에서 보기</a>

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

