---
title: Solutions2Share GmbH의 Teams 관리자에 대한 응용 프로그램 정보
ms.author: elmalova
author: elenamalova
ms.date: 12/16/2019
ms.topic: article
ms.service: attestation
certification_type: attested
description: Teams Manager, 데이터 처리 정책, CSA STAR 레지스트리의 Microsoft Cloud App Security 앱 카탈로그 정보 및 보안/규정 준수 정보에 대해 사용할 수 있는 모든 보안 및 규정 준수 정보
zone_pivot_groups: app-info-data-mcas
ms.openlocfilehash: fbca7409c87bed006a18b31d7de2fa43afd9b95f
ms.sourcegitcommit: 65d4afba6f46d45315b2a90d2b21ce1737707e7b
ms.translationtype: MT
ms.contentlocale: ko-KR
ms.lasthandoff: 07/02/2021
ms.locfileid: "53283192"
---
# <a name="teams-manager"></a>Teams Manager

<p></p>
<img alt="Publisher Attestation: The information on this page is based on a self-assessment report provided by the app developer on the security, compliance, and data handling practices followed by this app. Microsoft makes no guarantees regarding the accuracy of the information." src="../media/attested.png" width="650" />
<p>개발자가 마지막으로 업데이트한 날짜: 2019년 12월 16일</p>

* <a href="https://teams.microsoft.com/l/app/87000000-3db9-bb44-5015-0b4a327a6597" target="_blank">저장소의 Teams 보기</a>
* <a href="https://appsource.microsoft.com/product/office/WA200000764" target="_blank">AppSource의 보기</a>

::: zone pivot="general"

### <a name="general-information"></a>일반 정보

Solutions2Share GmbH에서 Microsoft로 제공되는 정보:

| **정보** | **응답** |
|:----------------|:-------------|
| 앱 이름 | Teams Manager |
| ID | WA200000764 |
| Office 365 클라이언트 지원 | Microsoft Teams |
| 파트너 회사 이름 | Solutions2Share GmbH |
| 파트너 웹 사이트의 URL | [https://teams-manager.com/](https://teams-manager.com/) |
| 개인 정보 취급 방침의 URL | [https://www.teams-manager.com/privacy](https://www.teams-manager.com/privacy) |
| 사용 약관 URL | [https://www.teams-manager.com/terms-of-use/](https://www.teams-manager.com/terms-of-use/) |

 [!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="data"

### <a name="how-the-app-handles-data"></a>앱이 데이터를 처리하는 방법

이 정보는 Solutions2Share GmbH에서 이 앱이 조직 데이터를 수집 및 저장하는 방법 및 앱이 수집하는 데이터를 통해 조직이 가지는 컨트롤에 대해 제공됩니다.

#### <a name="data-access-using-microsoft-graph"></a>Microsoft 365를 사용한 데이터 Graph

이 앱에 [Graph Microsoft 사용자 권한을](https://docs.microsoft.com/graph/permissions-reference) 나열합니다.

>| **사용 권한**  | **사용 권한 유형(위임/응용 프로그램)** | **데이터가 수집하나요? 수집의 사당성** | **데이터가 저장되어 있나요? 저장 사정이 있나요?** | **Azure AD 앱 ID** |
>|:----------------|:--------------------|:---------------------------------------------------|:--------------------------|:--------------------------|
>| Group.ReadWrite.All | 둘 다 | 템플릿을 매핑하기 위해 TenantID 및 TeamId를 저장합니다.  | 모든 웹 Teams 허용하고 Teams. | b9a1aaab-e8aa-4b92-b4ce-f13cae74caa7 |
>| Notes.ReadWrite.All | application | 없음 | 앱에서 승인된 팀에 전자 필기장을 추가할 수 있습니다. | b9a1aaab-e8aa-4b92-b4ce-f13cae74caa7 |
>| User.Read | 위임 | 없음 | 사용자가 로그인할 수 있도록 허용하고 자동 로그인을 사용하도록 설정하기 위해 앱에 UPN에 대한 액세스 권한을 부여합니다. | b9a1aaab-e8aa-4b92-b4ce-f13cae74caa7 |
>| User.Read.All | 둘 다 | 승인자/관리자 섹션에 입력한 사용자의 ID를 저장합니다. | 앱 내의 사용자 선택에 표시하기 위해 모든 사용자를 나열합니다. | b9a1aaab-e8aa-4b92-b4ce-f13cae74caa7 |
>| User.ReadBasic.All | 위임 | 없음 | 앱 내의 사용자 선택에 표시하기 위해 모든 사용자를 나열합니다. | b9a1aaab-e8aa-4b92-b4ce-f13cae74caa7 |


#### <a name="non-microsoft-services-used"></a>비영구 Microsoft 서비스

앱이 Microsoft가 아닌 서비스로 조직 데이터를 전송하거나 공유하는 경우 앱에서 사용하는 비 Microsoft 서비스, 전송되는 데이터를 나열하고 앱이 이 정보를 전송해야 하는 이유에 대한 사유를 포함합니다.

>비영구 Microsoft 서비스 사용되지 않습니다.

#### <a name="data-access-via-bots"></a>봇을 통한 데이터 액세스

이 앱에 봇 또는 메시징 확장이 포함되어 있는 경우 팀 구성원의 명단(이름, 성, 표시 이름, 전자 메일 주소)이나 팀 구성원이 추가된 채팅의 최종 사용자 식별 정보(EUII)에 액세스할 수 있습니다. 이 앱이 이 기능을 사용하나요?

>EUII에 액세스하지 않습니다.


#### <a name="telemetry-data"></a>원격 분석 데이터

이 응용 프로그램의 원격 분석 또는 로그에 OII(조직 식별 정보) 또는 EUII(최종 사용자 식별 정보)가 나타나나요? 그렇다면 저장되는 데이터와 보존 및 제거 정책에 대해 설명하세요.

>Azure Log Analytics에 로그인하고 있으며 보관/보존 정책을 사용하고 있습니다.
테넌트 ID 및 팀 ID를 기록하여 문제를 식별하고 고객이 문제를 해결할 수 있도록 지원하고 있습니다.

#### <a name="organizational-controls-for-data-stored-by-partner"></a>파트너가 저장한 데이터에 대한 조직 제어

조직의 관리자가 파트너 시스템에서 정보를 제어하는 방법에 대해 설명하는 방법 삭제, 보존, 감사, 보관, 최종 사용자 정책 등

>액세스 제어를 위한 규정 준수 및 운영 프로세스가 있습니다. 모든 사용자 관련 데이터 및 토큰이 암호화됩니다. 데이터는 데이터 원본에 Azure SQL Database. 방화벽을 사용하여 특정 IP(시스템 간의 보호된 IP 범위)에서만 연결을 허용합니다. Azure 내에서 PMA(Privileged Access Management)를 사용하도록 설정했습니다.

#### <a name="human-review-of-organizational-information"></a>조직 정보의 인적 검토

사람이 이 앱에서 수집하거나 저장하는 OII(조직 식별 정보) 데이터를 검토하거나 분석하는 데 관여하나요?

>아니요

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="mcas"

Microsoft Cloud App Security [카탈로그의](https://www.microsoft.com/enterprise-mobility-security/cloud-app-security) 정보가 아래에 표시됩니다.

<iframe height='1020' title='Microsoft Cloud App Security 정보' src='https://appmcasinfoprod.azurewebsites.net/#/dashboard/35836' frameborder='no' style='width: 100%;'></iframe>

<a href="https://appmcasinfoprod.azurewebsites.net/#/dashboard/35836" target="_blank">새 탭에서 보기</a>

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

