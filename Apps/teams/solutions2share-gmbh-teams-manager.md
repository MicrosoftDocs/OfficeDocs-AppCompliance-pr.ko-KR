---
title: 솔루션2Share GmbH에 의해 Teams 관리자를위한 응용 프로그램 정보
ms.author: elmalova
author: elenamalova
ms.date: 12/16/2019
ms.topic: article
ms.service: attestation
certification_type: attested
description: Teams 관리자, 데이터 처리 정책, Microsoft Cloud App Security 앱 카탈로그 정보 및 CSA STAR 레지스트리의 보안/규정 준수 정보에 대한 사용 가능한 모든 보안 및 규정 준수 정보.
zone_pivot_groups: app-info-data-mcas
ms.openlocfilehash: f941df5497b74f3558a56c0407456b42f3b2095d
ms.sourcegitcommit: a44420a99a1a3a9d0e49f4be66f266e2d4ca7bbb
ms.translationtype: MT
ms.contentlocale: ko-KR
ms.lasthandoff: 05/19/2021
ms.locfileid: "52552769"
---
# <a name="teams-manager"></a>Teams Manager

<p></p>
<img alt="Publisher Attestation: The information on this page is based on a self-assessment report provided by the app developer on the security, compliance, and data handling practices followed by this app. Microsoft makes no guarantees regarding the accuracy of the information." src="../media/attested.png" width="650" />
<p>최종 업데이트: 2019년 12월 16일</p>

* <a href="https://teams.microsoft.com/l/app/87000000-3db9-bb44-5015-0b4a327a6597" target="_blank">Teams 스토어에서 보기</a>
* <a href="https://appsource.microsoft.com/product/office/WA200000764" target="_blank">앱소스에서 보기</a>

::: zone pivot="general"

### <a name="general-information"></a>일반 정보

Microsoft에 대한 Solutions2Share GmbH에서 제공하는 정보:

| **정보** | **응답** |
|:----------------|:-------------|
| 앱 이름 | Teams Manager |
| ID | WA20000764 |
| 지원되는 Office 365 클라이언트 | Microsoft Teams |
| 파트너 회사 이름 | Solutions2Share GmbH |
| 파트너 웹사이트의 URL | [https://www.teams-manager.com](https://www.teams-manager.com) |
| 개인정보 처리방침의 URL | [https://www.teams-manager.com/privacy](https://www.teams-manager.com/privacy) |
| 이용 약관의 URL | [https://www.teams-manager.com/terms-of-use/](https://www.teams-manager.com/terms-of-use/) |

 [!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="data"

### <a name="how-the-app-handles-data"></a>앱이 데이터를 처리하는 방법

이 정보는 Solutions2Share GmbH에서 이 앱이 조직 데이터를 수집하고 저장하는 방법과 앱이 수집하는 데이터에 대한 조직이 가질 수 있는 제어에 대해 제공했습니다.

#### <a name="data-access-using-microsoft-graph"></a>Microsoft Graph 을 사용하여 데이터 액세스

이 [앱에서 필요한 Microsoft Graph 권한을 나열합니다.](https://docs.microsoft.com/graph/permissions-reference)

>| **사용 권한**  | **권한 유형(위임/응용 프로그램)** | **데이터가 수집되고 있습니까? 그것을 수집하기위한 정당화?** | **데이터가 저장되어 있습니까? 그것을 저장하는 정당화?** | **Azure AD 앱 ID** |
>|:----------------|:--------------------|:---------------------------------------------------|:--------------------------|:--------------------------|
>| Group.ReadWrite.All | 둘다 | 템플릿을 매핑하기 위해 테넌트ID와 TeamId를 저장합니다.  | 모든 Teams 나열하고 Teams 만듭니다. | b9a1aaab-e8aaa-4b92-b4ce-f13cae74caa7 |
>| 참고. 읽기 쓰기.모든 | 신청 | 없음 | 앱이 승인된 팀에 노트북을 추가할 수 있습니다. | b9a1aaab-e8aaa-4b92-b4ce-f13cae74caa7 |
>| User.Read | 위임 | 없음 | 사용자가 로그인할 수 있도록 하고 앱이 UPN에 액세스할 수 있도록 하여 자동 로그인을 사용할 수 있습니다. | b9a1aaab-e8aaa-4b92-b4ce-f13cae74caa7 |
>| User.Read.All | 둘다 | 승인자/관리자 섹션에 입력된 사용자의 ID를 저장합니다. | 모든 사용자를 나열하여 앱 내의 사용자 선택기에 표시합니다. | b9a1aaab-e8aaa-4b92-b4ce-f13cae74caa7 |
>| User.ReadBasic.All | 위임 | 없음 | 모든 사용자를 나열하여 앱 내의 사용자 선택기에 표시합니다. | b9a1aaab-e8aaa-4b92-b4ce-f13cae74caa7 |


#### <a name="non-microsoft-services-used"></a>사용되지 Microsoft 서비스

앱이 Microsoft 가 아닌 서비스와 조직 데이터를 전송하거나 공유하는 경우 앱에서 사용하는 비Microsoft 서비스, 전송되는 데이터를 나열하고 앱이 이 정보를 전송해야 하는 이유에 대한 명분을 포함합니다.

>비Microsoft 서비스 사용되지 않습니다.

#### <a name="data-access-via-bots"></a>봇을 통한 데이터 액세스

이 앱에 봇 또는 메시징 확장 프로그램이 포함된 경우 최종 사용자 식별 정보(EUII): 팀의 모든 팀 구성원의 명단(이름, 성, 표시 이름, 이메일 주소)에 액세스하거나 추가된 채팅을 할 수 있습니다. 이 응용 프로그램은이 기능을 사용합니까?

>EUII에 액세스할 수 없습니다.


#### <a name="telemetry-data"></a>원격 분석 데이터

조직 식별 정보(OII) 또는 최종 사용자 식별 정보(EUII)가 이 응용 프로그램의 원격 분석 또는 로그에 표시됩니까? 그렇다면 저장되는 데이터와 보존 및 제거 정책은 무엇입니까?

>Azure Log Analytics에 로그인하고 있으며 아카이브/보존 정책을 사용하고 있습니다.
테넌트 ID와 팀 ID를 로깅하여 문제를 식별하고 고객이 문제를 해결할 수 있도록 돕고 있습니다.

#### <a name="organizational-controls-for-data-stored-by-partner"></a>파트너가 저장한 데이터에 대한 조직 제어

조직의 관리자가 파트너 시스템에서 자신의 정보를 제어하는 방법을 설명해 보세요. 예를 들어 삭제, 보존, 감사, 보관, 최종 사용자 정책 등

>우리는 액세스 제어를위한 규정 준수 및 운영 프로세스를 가지고 있습니다. 모든 사용자 관련 데이터와 토큰은 암호화됩니다. 데이터는 Azure SQL Database 저장됩니다. 방화벽을 사용하여 특정 IP(시스템 간 보호된 IP 범위)의 연결만 허용하고 있습니다. Azure 내에서 PMA(권한 있는 액세스 관리)를 사용하도록 설정했습니다.

#### <a name="human-review-of-organizational-information"></a>조직 정보의 인간 검토

이 앱에서 수집하거나 저장되는 조직 식별 정보(OII) 데이터를 검토하거나 분석하는 데 관여하는 사람이 있습니까?

>아니요

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="mcas"

[Microsoft Cloud App Security](https://www.microsoft.com/enterprise-mobility-security/cloud-app-security) 카탈로그의 정보는 아래에 나타납니다.

<iframe height='1020' title='Microsoft Cloud App Security 정보' src='https://appmcasinfoprod.azurewebsites.net/#/dashboard/35836' frameborder='no' style='width: 100%;'></iframe>

<a href="https://appmcasinfoprod.azurewebsites.net/#/dashboard/35836" target="_blank">새 탭에서 보기</a>

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

