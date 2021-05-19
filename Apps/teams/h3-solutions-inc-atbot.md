---
title: 주식회사 H3 솔루션에 의한 AtBot용 애플리케이션 정보
ms.author: elmalova
author: elenamalova
ms.date: 12/16/2019
ms.topic: article
ms.service: attestation
certification_type: attested
description: AtBot의 모든 사용 가능한 보안 및 규정 준수 정보 정보, 데이터 처리 정책, Microsoft Cloud App Security 앱 카탈로그 정보 및 CSA STAR 레지스트리의 보안/규정 준수 정보.
zone_pivot_groups: app-info-data-mcas
ms.openlocfilehash: 3f56d0b3eb19f5bed8f7092507c8605af936b911
ms.sourcegitcommit: a44420a99a1a3a9d0e49f4be66f266e2d4ca7bbb
ms.translationtype: MT
ms.contentlocale: ko-KR
ms.lasthandoff: 05/19/2021
ms.locfileid: "52552139"
---
# <a name="atbot"></a>AtBot

<p></p>
<img alt="Publisher Attestation: The information on this page is based on a self-assessment report provided by the app developer on the security, compliance, and data handling practices followed by this app. Microsoft makes no guarantees regarding the accuracy of the information." src="../media/attested.png" width="650" />
<p>최종 업데이트: 2019년 12월 16일</p>

* <a href="https://teams.microsoft.com/l/app/7c01af81-ae7d-416e-98a3-c139cae8cfb0" target="_blank">Teams 스토어에서 보기</a>
* <a href="https://appsource.microsoft.com/product/office/WA104381219" target="_blank">앱소스에서 보기</a>

::: zone pivot="general"

### <a name="general-information"></a>일반 정보

H3 솔루션, Inc.에서 마이크로소프트에 제공 하는 정보:

| **정보** | **응답** |
|:----------------|:-------------|
| 앱 이름 | AtBot |
| ID | WA104381219 |
| 지원되는 Office 365 클라이언트 | Microsoft Teams |
| 파트너 회사 이름 | H3 Solutions, Inc. |
| 파트너 웹사이트의 URL | [https://atbot.io](https://atbot.io) |
| Teams 응용 프로그램 정보 페이지의 URL | [https://admin.atbot.io/Docs/GettingStarted](https://admin.atbot.io/Docs/GettingStarted) |
| 개인정보 처리방침의 URL | [https://admin.atbot.io/privacy](https://admin.atbot.io/privacy) |
| 이용 약관의 URL | [https://admin.atbot.io/terms](https://admin.atbot.io/terms) |

 [!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="data"

### <a name="how-the-app-handles-data"></a>앱이 데이터를 처리하는 방법

이 정보는 H3 Solutions, Inc.에서 이 앱이 조직 데이터를 수집하고 저장하는 방법과 앱이 수집하는 데이터에 대한 조직이 가질 수 있는 제어에 대해 제공했습니다.

#### <a name="data-access-using-microsoft-graph"></a>Microsoft Graph 을 사용하여 데이터 액세스

이 [앱에서 필요한 Microsoft Graph 권한을 나열합니다.](https://docs.microsoft.com/graph/permissions-reference)

>| **사용 권한**  | **권한 유형(위임/응용 프로그램)** | **데이터가 수집되고 있습니까? 그것을 수집하기위한 정당화?** | **데이터가 저장되어 있습니까? 그것을 저장하는 정당화?** | **Azure AD 앱 ID** |
>|:----------------|:--------------------|:---------------------------------------------------|:--------------------------|:--------------------------|
>| Directory.Read.All | 신청 | AAD 그룹 이름, AAD 그룹 GUID, UPN | AAD 그룹을 확대하여 봇 기술의 보안 트리밍을 허용합니다. 라이선스를 적용할 수 있도록 사용자를 확대합니다. 사용자를 관리자/기고자로 추가할 테고를 확대 | 066a6b3a-f7a0-450a-98c7-34db1da31594 |
>| Directory.Read.All | 위임 | AAD 그룹 이름, AAD 그룹 GUID, UPN | AAD 그룹을 확대하여 봇 기술의 보안 트리밍을 허용합니다. 라이선스를 적용할 수 있도록 사용자를 확대합니다. 사용자를 관리자/기고자로 추가할 테고를 확대 | 066a6b3a-f7a0-450a-98c7-34db1da31594 |
>| 사람들.읽기 | 위임 | 아니요 | Flow 사람 얻기 액션으로 사람들을 예층합니다.  봇이 Microsoft Graph /People 끝점에서 사람들을 검색할 수 있습니다. | 066a6b3a-f7a0-450a-98c7-34db1da31594 |
>| User.Read | 위임 | 테넌트 ID, UPN | 테넌트 ID와 UPN을&#8217;사용자에게 액세스 권한을 부여하여 사용자가 만든 사용자에게 만든 흐름/논리 앱을 연결할 수 있습니다. | 066a6b3a-f7a0-450a-98c7-34db1da31594 |
>| 전자 메일 | 위임 | 아니요 | 사용자의 이메일 주소에 대한 액세스를 제공합니다. | 066a6b3a-f7a0-450a-98c7-34db1da31594 |
>| offline_access | 위임 | 토큰에 액세스/새로 고침. | 새로 고침 토큰을 사용하여 사용자가 로그인할 수 있도록 할 수 있습니다. | 066a6b3a-f7a0-450a-98c7-34db1da31594 |
>| 오픈 ID | 위임 | 아니요 | 사용자가 로그인할 수 있습니다. | 066a6b3a-f7a0-450a-98c7-34db1da31594 |
>| 윤곽 | 위임 | UPN | 사용자의 UPN에 액세스합니다. | 066a6b3a-f7a0-450a-98c7-34db1da31594 |


#### <a name="non-microsoft-services-used"></a>사용되지 Microsoft 서비스

앱이 Microsoft 가 아닌 서비스와 조직 데이터를 전송하거나 공유하는 경우 앱에서 사용하는 비Microsoft 서비스, 전송되는 데이터를 나열하고 앱이 이 정보를 전송해야 하는 이유에 대한 명분을 포함합니다.

>비Microsoft 서비스 사용되지 않습니다.

#### <a name="data-access-via-bots"></a>봇을 통한 데이터 액세스

이 앱에 봇 또는 메시징 확장 프로그램이 포함된 경우 최종 사용자 식별 정보(EUII): 팀의 모든 팀 구성원의 명단(이름, 성, 표시 이름, 이메일 주소)에 액세스하거나 추가된 채팅을 할 수 있습니다. 이 응용 프로그램은이 기능을 사용합니까?

>| **EUII에 액세스할 수 있는 정당성?**  | **EUII는 데이터베이스에 저장되어 있습니까?** | **EUII를 저장하는 정당화?** |
>|:--------------------------------|:---------------------|:--------------------------|
>| 봇에서 생성된 채팅 메시지에 멘션 생성 | 아니요 |  |


#### <a name="telemetry-data"></a>원격 분석 데이터

조직 식별 정보(OII) 또는 최종 사용자 식별 정보(EUII)가 이 응용 프로그램의 원격 분석 또는 로그에 표시됩니까? 그렇다면 저장되는 데이터와 보존 및 제거 정책은 무엇입니까?

>테넌트 ID, UPN 우리는 응용 프로그램 통찰력을 사용하고 우리의 로그는 자동으로 보관되기 전에 90 일 동안 지속됩니다. (https://docs.microsoft.com/azure/azure-monitor/app/data-retention-privacy)

#### <a name="organizational-controls-for-data-stored-by-partner"></a>파트너가 저장한 데이터에 대한 조직 제어

조직의 관리자가 파트너 시스템에서 자신의 정보를 제어하는 방법을 설명해 보세요. 예를 들어 삭제, 보존, 감사, 보관, 최종 사용자 정책 등

>관리자는 AAD 그룹 이름/GUID를 포함할 수 있는 봇 구성을 삭제할 수 있습니다.
서비스가 취소되면 모든 UPN이 라이선싱 데이터베이스에서 제거됩니다.
Data Residency 'Azure 서비스'를 참조하십시오.  AtBot을 사용하여 생성된 고객 별 데이터의 대부분은 고객의 테넌트에 저장되므로 해당 테넌트의 관리자는 데이터를 완전히 제어할 수 있습니다.


[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="mcas"

[Microsoft Cloud App Security](https://www.microsoft.com/enterprise-mobility-security/cloud-app-security) 카탈로그의 정보는 아래에 나타납니다.

<iframe height='1020' title='Microsoft Cloud App Security 정보' src='https://appmcasinfoprod.azurewebsites.net/#/dashboard/35672' frameborder='no' style='width: 100%;'></iframe>

<a href="https://appmcasinfoprod.azurewebsites.net/#/dashboard/35672" target="_blank">새 탭에서 보기</a>

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

