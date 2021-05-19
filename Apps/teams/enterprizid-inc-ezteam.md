---
title: 엔터프리지드 주식회사에 의한 ezTeam신청 정보
ms.author: elmalova
author: elenamalova
ms.date: 02/24/2021
ms.topic: article
ms.service: attestation
certification_type: attested
description: EZTeam에 대한 사용 가능한 모든 보안 및 규정 준수 정보 정보, 데이터 처리 정책, Microsoft Cloud App Security 앱 카탈로그 정보 및 CSA STAR 레지스트리의 보안/규정 준수 정보.
zone_pivot_groups: app-info-data-mcas-identity
ms.openlocfilehash: da54d5a540fd43c2bdc25a6f4e31ba88520ecbc3
ms.sourcegitcommit: a44420a99a1a3a9d0e49f4be66f266e2d4ca7bbb
ms.translationtype: MT
ms.contentlocale: ko-KR
ms.lasthandoff: 05/19/2021
ms.locfileid: "52553179"
---
# <a name="ezteam"></a>ezTeam

<p></p>
<img alt="Publisher Attestation: The information on this page is based on a self-assessment report provided by the app developer on the security, compliance, and data handling practices followed by this app. Microsoft makes no guarantees regarding the accuracy of the information." src="../media/attested.png" width="650" />
<p>최종 업데이트: 2021년 2월 24일</p>

* <a href="https://teams.microsoft.com/l/app/b02f0b53-d3b7-4d53-85a9-f820f5ab33c7" target="_blank">Teams 스토어에서 보기</a>
* <a href="https://appsource.microsoft.com/product/office/WA200002546" target="_blank">앱소스에서 보기</a>

::: zone pivot="general"

### <a name="general-information"></a>일반 정보

엔터프리지드에서 마이크로소프트에 제공한 정보:

| **정보** | **응답** |
|:----------------|:-------------|
| 앱 이름 | ezTeam |
| ID | WA200002546 |
| 지원되는 Office 365 클라이언트 | Microsoft Teams |
| 파트너 회사 이름 | EnterprizID Inc |
| 파트너 웹사이트의 URL | [https://enterprizid.com](https://enterprizid.com) |
| Teams 응용 프로그램 정보 페이지의 URL | [https://enterprizid.com/discover/](https://enterprizid.com/discover/) |
| 개인정보 처리방침의 URL | [https://enterprizid.com/privacy-policy/](https://enterprizid.com/privacy-policy/) |
| 이용 약관의 URL | [https://enterprizid.com/terms-of-use/](https://enterprizid.com/terms-of-use/) |

 [!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="data"

### <a name="how-the-app-handles-data"></a>앱이 데이터를 처리하는 방법

이 정보는 EnterprizID Inc에서 이 앱이 조직 데이터를 수집하고 저장하는 방법과 앱이 수집하는 데이터에 대한 조직이 가질 수 있는 제어에 대해 제공했습니다.

#### <a name="data-access-using-microsoft-graph"></a>Microsoft Graph 을 사용하여 데이터 액세스

이 [앱에서 필요한 Microsoft Graph 권한을 나열합니다.](https://docs.microsoft.com/graph/permissions-reference)

>| **사용 권한**  | **권한 유형(위임/응용 프로그램)** | **데이터가 수집되고 있습니까? 그것을 수집하기위한 정당화?** | **데이터가 저장되어 있습니까? 그것을 저장하는 정당화?** | **Azure AD 앱 ID** |
>|:----------------|:--------------------|:---------------------------------------------------|:--------------------------|:--------------------------|
>| 앱카탈로그.읽기.모든 것 | 위임 | Teams 사용할 수 있는 앱 목록이므로 Teams 요청 만들기 프로세스에 표시할 수 있습니다. | 해당 없음 | 2b1fb18f-54e4-4b08-9ef2-5610d0fffa8b |
>| 응용 프로그램.읽기.모든 | 위임 | 앱에서 로그인한 사용자를 대신하여 응용 프로그램 및 서비스 주체를 읽을 수 있습니다. | 해당 없음 | 2b1fb18f-54e4-4b08-9ef2-5610d0fffa8b |
>| Directory.AccessAsUser.All | 위임 | 앱이 로그인한 사용자와 디렉터리에서 정보에 동일한 액세스 권한을 가질 수 있습니다. | 해당 없음 | 2b1fb18f-54e4-4b08-9ef2-5610d0fffa8b |
>| Directory.Read.All | 위임 | 앱이 사용자, 그룹 및 앱과 같은 조직의 디렉터리에서 데이터를 읽을 수 있습니다. | Teams 소유권 및 회원 정보  | 2b1fb18f-54e4-4b08-9ef2-5610d0fffa8b |
>| Directory.Read.All | 신청 | 앱이 로그인한 사용자 없이 사용자, 그룹 및 앱과 같은 조직의 디렉터리에서 데이터를 읽을 수 있습니다. | 해당 없음 | 2b1fb18f-54e4-4b08-9ef2-5610d0fffa8b |
>| Directory.ReadWrite.All | 위임 | 앱이 사용자 및 그룹과 같은 조직의 디렉토리에서 데이터를 읽고 쓸 수 있도록 허용합니다. | 해당 없음 | 2b1fb18f-54e4-4b08-9ef2-5610d0fffa8b |
>| Directory.ReadWrite.All | 신청 | 앱이 로그인한 사용자 없이 사용자 및 그룹과 같은 조직의 디렉토리에서 데이터를 읽고 쓸 수 있습니다. 사용자 또는 그룹 삭제를 허용하지 않습니다. | 해당 없음 | 2b1fb18f-54e4-4b08-9ef2-5610d0fffa8b |
>| Files.Read.All | 신청 | 앱이 로그인한 사용자 없이 모든 사이트 컬렉션의 모든 파일을 읽을 수 있습니다. | GB의 최종 사용자 거버넌스에 따른 데이터 양 | 2b1fb18f-54e4-4b08-9ef2-5610d0fffa8b |
>| 그룹.만들기 | 신청 | 앱이 로그인한 사용자 없이 그룹을 만들 수 있습니다. | 새 그룹 속성 세부 정보입니다. | 2b1fb18f-54e4-4b08-9ef2-5610d0fffa8b |
>| Group.Read.All | 위임 | 앱이 그룹을 나열하고 로그인한 사용자를 대신하여 해당 속성 및 모든 그룹 멤버 자격을 읽을 수 있습니다. 내 Teams 결정하는 데 사용  | 해당 없음 | 2b1fb18f-54e4-4b08-9ef2-5610d0fffa8b |
>| Group.Read.All | 신청 | 앱이 그룹 속성 및 멤버십을 읽고 로그인한 사용자 없이 모든 그룹의 캘린더 및 대화를 읽을 수 있습니다. | 해당 없음 | 2b1fb18f-54e4-4b08-9ef2-5610d0fffa8b |
>| Group.ReadWrite.All | 위임 | 앱이 그룹을 만들고 로그인한 사용자를 대신하여 모든 그룹 속성 및 멤버십을 읽을 수 있습니다.  | 해당 없음 | 2b1fb18f-54e4-4b08-9ef2-5610d0fffa8b |
>| Group.ReadWrite.All | 신청 | 앱이 그룹을 만들고, 모든 그룹 속성 및 멤버십을 읽고, 그룹 속성 및 멤버십을 업데이트하고, 그룹을 삭제할 수 있습니다. 또한 응용 프로그램은 읽고 그룹 달력과 대화를 작성 할 수 있습니다.  | 팀의 마지막 활동. | 2b1fb18f-54e4-4b08-9ef2-5610d0fffa8b |
>| 그룹 멤버.읽기.모든 | 신청 | 앱이 로그인한 사용자 없이 모든 그룹에 대한 멤버십 및 기본 그룹 속성을 읽을 수 있습니다. | 해당 없음 | 2b1fb18f-54e4-4b08-9ef2-5610d0fffa8b |
>| 그룹 멤버.읽기 쓰기.모든 | 신청 | 앱이 그룹을 나열하고 기본 속성을 읽고 이 앱이 로그인 한 사용자없이 액세스 할 수있는 그룹의 구성원 을 읽고 업데이트 할 수 있습니다. | 해당 없음 | 2b1fb18f-54e4-4b08-9ef2-5610d0fffa8b |
>| 사람들.읽기.모든 것 | 신청 | 앱이 로그인한 사용자 없이 사용자의 점수가 있는 관련 사용자 목록을 읽을 수 있습니다. | 해당 없음 | 2b1fb18f-54e4-4b08-9ef2-5610d0fffa8b |
>| 보고서.읽기.모든 것 | 위임 | 앱에서 로그인한 사용자를 대신하여 모든 서비스 사용 보고서를 읽을 수 있습니다. | 해당 없음 | 2b1fb18f-54e4-4b08-9ef2-5610d0fffa8b |
>| 보고서.읽기.모든 것 | 신청 | 앱에서 로그인한 사용자 없이 모든 서비스 사용 보고서를 읽을 수 있습니다. | 그룹당 마지막 사용자 활동 | 2b1fb18f-54e4-4b08-9ef2-5610d0fffa8b |
>| Sites.ReadWrite.All | 신청 | 앱이 로그인한 사용자 없이 모든 사이트 컬렉션에서 문서 및 목록을 만들고 읽고 업데이트하고 삭제할 수 있습니다. | 각 사용자에 대한 크기별 상위 10개 사이트 | 2b1fb18f-54e4-4b08-9ef2-5610d0fffa8b |
>| User.Read | 위임 | 사용자가 앱에 로그인할 수 있으며 앱에서 로그인한 사용자의 프로필을 읽을 수 있습니다. | 해당 없음 | 2b1fb18f-54e4-4b08-9ef2-5610d0fffa8b |
>| User.Read.All | 신청 | 앱이 사용자 로그인 없이 사용자 프로필을 읽을 수 있습니다. | 해당 없음 | 2b1fb18f-54e4-4b08-9ef2-5610d0fffa8b |
>| offline_access | 위임 | 사용자가 현재 앱을 사용하지 않는 경우에도 앱에서 액세스 권한을 부여한 데이터를 보고 업데이트할 수 있습니다.  | 봇 알림 | 2b1fb18f-54e4-4b08-9ef2-5610d0fffa8b |
>| 오픈 ID | 위임 | 사용자가 직장 이나 학교 계정으로 앱에 로그인할 수 있으며 앱에서 기본 사용자 프로필 정보를 볼 수 있습니다. | 해당 없음 | 2b1fb18f-54e4-4b08-9ef2-5610d0fffa8b |
>| 윤곽 | 위임 | 앱이 사용자의 기본 프로필(이름, 사진, 사용자 이름)을 볼 수 있도록 허용합니다. | 해당 없음 | 2b1fb18f-54e4-4b08-9ef2-5610d0fffa8b |


#### <a name="non-microsoft-services-used"></a>사용되지 Microsoft 서비스

앱이 Microsoft 가 아닌 서비스와 조직 데이터를 전송하거나 공유하는 경우 앱에서 사용하는 비Microsoft 서비스, 전송되는 데이터를 나열하고 앱이 이 정보를 전송해야 하는 이유에 대한 명분을 포함합니다.

>비Microsoft 서비스 사용되지 않습니다.

#### <a name="data-access-via-bots"></a>봇을 통한 데이터 액세스

이 앱에 봇 또는 메시징 확장 프로그램이 포함된 경우 최종 사용자 식별 정보(EUII): 팀의 모든 팀 구성원의 명단(이름, 성, 표시 이름, 이메일 주소)에 액세스하거나 추가된 채팅을 할 수 있습니다. 이 응용 프로그램은이 기능을 사용합니까?

>| **EUII에 액세스할 수 있는 정당성?**  | **EUII는 데이터베이스에 저장되어 있습니까?** | **EUII를 저장하는 정당화?** |
>|:--------------------------------|:---------------------|:--------------------------|
>| 환영 메시지, 승인 및 증명 프로세스 알림 | ID의 표시 이름을 저장합니다.  | 우리의 도구는 최종 사용자가 다른 서비스 항목에 대한 요청을 만들 수 있도록하고 우리는 요청자의 표시 이름을 저장합니다. 요청은 승인 워크플로를 따르며 요청 세부 정보에 표시하려면 승인자 표시 이름이 필요합니다. 또한 팀 인증 프로세스의 구성원에는 구성원의 표시 이름이 나열됩니다. |


#### <a name="telemetry-data"></a>원격 분석 데이터

조직 식별 정보(OII) 또는 최종 사용자 식별 정보(EUII)가 이 응용 프로그램의 원격 분석 또는 로그에 표시됩니까? 그렇다면 저장되는 데이터와 보존 및 제거 정책은 무엇입니까?

>EndUser 및 조직 전체 이름입니다. 보존 및 제거 정책은 귀하의 개인 데이터 보존 섹션에서 찾을 수 https://enterprizid.com/privacy-policy &quot; &quot; 있습니다.

#### <a name="organizational-controls-for-data-stored-by-partner"></a>파트너가 저장한 데이터에 대한 조직 제어

조직의 관리자가 파트너 시스템에서 자신의 정보를 제어하는 방법을 설명해 보세요. 예를 들어 삭제, 보존, 감사, 보관, 최종 사용자 정책 등

>Azure 내에서 PMA(권한 있는 액세스 관리)를 활성화했으며, 2FA를 사용하여 보안을 강화하는 리소스에 연결할 권한이 있는 ID를 사용했습니다. Azure를 클라우드 파트너 공급자로 사용하고 Azure의 개인 정보 보호 및 사용 약관이 적용됩니다.

#### <a name="human-review-of-organizational-information"></a>조직 정보의 인간 검토

이 앱에서 수집하거나 저장되는 조직 식별 정보(OII) 데이터를 검토하거나 분석하는 데 관여하는 사람이 있습니까?

>예

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="mcas"

[Microsoft Cloud App Security](https://www.microsoft.com/enterprise-mobility-security/cloud-app-security) 카탈로그의 정보는 아래에 나타납니다.

<iframe height='1020' title='Microsoft Cloud App Security 정보' src='https://appmcasinfoprod.azurewebsites.net/#/dashboard/36552' frameborder='no' style='width: 100%;'></iframe>

<a href="https://appmcasinfoprod.azurewebsites.net/#/dashboard/36552" target="_blank">새 탭에서 보기</a>

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="identity"

### <a name="identity-information"></a>신원 정보

이 정보는 EnterprizID Inc에서 이 앱이 인증, 승인, 응용 프로그램 등록 모범 사례 및 기타 ID 기준을 처리하는 방법에 대해 제공했습니다.

| **정보** | **응답** |
|:----------------|:-------------|
| Microsoft 식별 플랫폼(Azure AD)과 통합합니까?  | 예 |
| Microsoft ID 플랫폼 통합 검사 목록에 설명된 모든 적용 가능한 모범 사례를 검토하고 준수했습니까?  | 예 |
| 앱에서 인증에 MSAL(Microsoft 인증 라이브러리)을 사용합니까? | 아니요 |
| 앱이 조건부 액세스 정책을 지원합니까? | 아니요 |
| 앱에서 시나리오에 대한 최소 권한 권한을 요청합니까? | 예 |
| 앱의 정적 등록 권한은 앱이 동적으로 점진적으로 요청하는 권한을 정확하게 반영합니까? | 예 |
| 앱이 다중 테넌션을 지원합니까? | 예 |
| 앱에 기밀 클라이언트가 있습니까? | 아니요 |
| 앱에 등록된 URI(리디렉션 통합 리소스 식별자)를 모두 소유하고 있습니까? | 예 |
| 앱의 경우 무엇을 사용하지 않으려습니까? | - 와일드카드 리디렉션 URI,<br/>- OAuth2 암시적 Flow, SPA에 필요한 경우가 아니면<br/>- 리소스 소유자 암호 자격 증명(ROPC) 흐름 |
| 앱에서 웹 API가 노출됩니까? | 예 |
| 권한 모델은 클라이언트 앱이 적절한 동의를 받는 경우에만 호출을 성공시킬 수 있습니까? | 예 |
| 앱에서 미리 보기 API를 사용합니까? | 예 |
| 앱에서 비하 API를 사용합니까? | 아니요 |

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end
