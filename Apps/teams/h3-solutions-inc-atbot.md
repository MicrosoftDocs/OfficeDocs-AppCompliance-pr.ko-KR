---
title: Application Information for AtBot by H3 Solutions, Inc.
ms.author: elmalova
author: elenamalova
ms.date: 12/16/2019
ms.topic: article
ms.service: attestation
description: AtBot에 사용할 수 있는 모든 보안 및 규정 준수 정보, 데이터 처리 정책, CSA STAR 레지스트리의 Microsoft Cloud App Security 앱 카탈로그 정보 및 보안/규정 준수 정보
zone_pivot_groups: app-info-data-mcas
ms.openlocfilehash: 4280f34bdcd960664e77e95541d7ede3102608cf
ms.sourcegitcommit: e97156a6eaf1d5ec5c26fd14add210a92bacd944
ms.translationtype: MT
ms.contentlocale: ko-KR
ms.lasthandoff: 04/30/2021
ms.locfileid: "52095122"
---
# <a name="atbot"></a>AtBot

<p></p>
<img alt="Publisher Attestation: The information on this page is based on a self-assessment report provided by the app developer on the security, compliance, and data handling practices followed by this app. Microsoft makes no guarantees regarding the accuracy of the information." src="../media/attested.png" width="650" />
<p>개발자가 마지막으로 업데이트한 날짜: 2019년 12월 16일</p>

* <a href="https://teams.microsoft.com/l/app/7c01af81-ae7d-416e-98a3-c139cae8cfb0" target="_blank">저장소의 Teams 보기</a>
* <a href="https://appsource.microsoft.com/product/office/WA104381219" target="_blank">AppSource의 보기</a>

::: zone pivot="general"

### <a name="general-information"></a>일반 정보

H3 Solutions, Inc.에서 Microsoft에 제공하는 정보:

| **정보** | **응답** |
|:----------------|:-------------|
| 앱 이름 | AtBot |
| ID | WA104381219 |
| 기능 | 봇 |
| Office 365 클라이언트 지원 | Microsoft Teams |
| 파트너 회사 이름 | H3 Solutions, Inc. |
| 파트너 웹 사이트의 URL | [https://atbot.io](https://atbot.io) |
| 응용 프로그램 Teams 페이지의 URL입니다. | [https://admin.atbot.io/Docs/GettingStarted](https://admin.atbot.io/Docs/GettingStarted) |
| 개인 정보 취급 방침의 URL | [https://admin.atbot.io/privacy](https://admin.atbot.io/privacy) |
| 사용 약관 URL | [https://admin.atbot.io/terms](https://admin.atbot.io/terms) |

 [!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="data"

### <a name="how-the-app-handles-data"></a>앱이 데이터를 처리하는 방법

이 정보는 H3 Solutions, Inc.에서 이 앱이 조직 데이터를 수집하고 저장하는 방법 및 앱이 수집하는 데이터를 통해 조직이 가지는 컨트롤에 대해 제공됩니다.

#### <a name="data-access-using-microsoft-graph"></a>Microsoft 365를 사용한 데이터 Graph

이 앱에 [Graph Microsoft 사용자 권한을](https://docs.microsoft.com/graph/permissions-reference) 나열합니다.

>| **사용 권한**  | **사용 권한 유형(위임/응용 프로그램)** | **데이터가 수집하나요? 수집의 사당성** | **데이터가 저장되어 있나요? 저장 사정이 있나요?** | **Azure AD 앱 ID** |
>|:----------------|:--------------------|:---------------------------------------------------|:--------------------------|:--------------------------|
>| Directory.Read.All | application | AAD 그룹 이름, AAD 그룹 GUID, UPN | 봇 기술의 보안 트리밍을 허용하도록 AAD 그룹을 열00개합니다. 사용자가 라이선스를 적용할 수 있도록 열세합니다. 관리자/참가자로 추가할 사용자 열기 | 066a6b3a-f7a0-450a-98c7-34db1da31594 |
>| Directory.Read.All | 위임 | AAD 그룹 이름, AAD 그룹 GUID, UPN | 봇 기술의 보안 트리밍을 허용하도록 AAD 그룹을 열00개합니다. 사용자가 라이선스를 적용할 수 있도록 열세합니다. 관리자/참가자로 추가할 사용자 열기 | 066a6b3a-f7a0-450a-98c7-34db1da31594 |
>| People.Read | 위임 | 아니요 | Flow.  봇이 Microsoft 365의 /People 끝점에서 사용자 검색을 Graph. | 066a6b3a-f7a0-450a-98c7-34db1da31594 |
>| User.Read | 위임 | 테넌트 ID, UPN | 사용자가 테넌트 ID 및 UPN을&#8217;액세스 권한을 부여하여 만든 흐름/논리 앱을 해당 앱을 만든 사용자에게 에일 수 있도록 합니다. | 066a6b3a-f7a0-450a-98c7-34db1da31594 |
>| 전자 메일 | 위임 | 아니요 | 사용자의 전자 메일 주소에 대한 액세스 권한을 부여합니다. | 066a6b3a-f7a0-450a-98c7-34db1da31594 |
>| offline_access | 위임 | 토큰 액세스/새로 고침 | 사용자가 로그인된 유지를 위해 새로 고침 토큰을 사용할 수 있습니다. | 066a6b3a-f7a0-450a-98c7-34db1da31594 |
>| openid | 위임 | 아니요 | 사용자가 로그인할 수 있습니다. | 066a6b3a-f7a0-450a-98c7-34db1da31594 |
>| profile | 위임 | UPN | 사용자의 UPN에 액세스합니다. | 066a6b3a-f7a0-450a-98c7-34db1da31594 |


#### <a name="non-microsoft-services-used"></a>비영구 Microsoft 서비스

앱이 Microsoft가 아닌 서비스로 조직 데이터를 전송하거나 공유하는 경우 앱에서 사용하는 비 Microsoft 서비스, 전송되는 데이터를 나열하고 앱이 이 정보를 전송해야 하는 이유에 대한 사유를 포함합니다.

>비영구 Microsoft 서비스 사용되지 않습니다.

#### <a name="data-access-via-bots"></a>봇을 통한 데이터 액세스

이 앱에 봇 또는 메시징 확장이 포함되어 있는 경우 팀 구성원의 명단(이름, 성, 표시 이름, 전자 메일 주소)이나 팀 구성원이 추가된 채팅의 최종 사용자 식별 정보(EUII)에 액세스할 수 있습니다. 이 앱이 이 기능을 사용하나요?

>| **EUII 액세스의 사유는 무엇입니까?**  | **EUII가 데이터베이스에 저장되어 있나요?** | **EUII 저장의 사유는 무엇입니까?** |
>|:--------------------------------|:---------------------|:--------------------------|
>| 봇 생성 채팅 메시지에서 메시지 생성 | 아니요 |  |



#### <a name="telemetry-data"></a>원격 분석 데이터

이 응용 프로그램의 원격 분석 또는 로그에 OII(조직 식별 정보) 또는 EUII(최종 사용자 식별 정보)가 나타나나요? 그렇다면 저장되는 데이터와 보존 및 제거 정책에 대해 설명하세요.

>테넌트 ID, UPN Application Insights를 사용하며 로그는 자동으로 보관되기 전에 90일 동안 지속됩니다. (https://docs.microsoft.com/azure/azure-monitor/app/data-retention-privacy)

#### <a name="organizational-controls-for-data-stored-by-partner"></a>파트너가 저장한 데이터에 대한 조직 제어

조직의 관리자가 파트너 시스템에서 정보를 제어하는 방법에 대해 설명하는 방법 삭제, 보존, 감사, 보관, 최종 사용자 정책 등

>관리자는 AAD 그룹 이름/GUID를 포함할 수 있는 봇 구성을 삭제할 수 있습니다.
서비스를 취소하면 모든 UPNS가 라이선스 데이터베이스에서 제거됩니다.
자세한 내용은 아래에서 'Azure Services'를 Data Residency.  AtBot 사용을 통해 생성되는 고객별 데이터 중 다수는 고객의 테넌트에 저장되어 있으므로 해당 테넌트의 관리자는 해당 테넌트의 데이터에 대한 모든 권한을 하게 됩니다.


[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="mcas"

Microsoft Cloud App Security [카탈로그의](https://www.microsoft.com/enterprise-mobility-security/cloud-app-security) 정보가 아래에 표시됩니다.

<iframe height='1020' title='Microsoft Cloud App Security 정보' src='https://appmcasinfoprod.azurewebsites.net/#/dashboard/35672' frameborder='no' style='width: 100%;'></iframe>

<a href="https://appmcasinfoprod.azurewebsites.net/#/dashboard/35672" target="_blank">새 탭에서 보기</a>

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

