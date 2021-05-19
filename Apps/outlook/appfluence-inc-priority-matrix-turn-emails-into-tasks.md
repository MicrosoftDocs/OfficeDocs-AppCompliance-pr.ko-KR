---
title: 우선 순위 매트릭스에 대한 응용 프로그램 정보 - Appfluence Inc.에 의해 작업으로 이메일을 켭니다
ms.author: elmalova
author: elenamalova
ms.date: 04/16/2021
ms.topic: article
ms.service: attestation
certification_type: certified
description: Priority Matrix에 대한 사용 가능한 모든 보안 및 규정 준수 정보 정보 - CSA STAR 레지스트리의 작업, 데이터 처리 정책, Microsoft Cloud App Security 앱 카탈로그 정보 및 보안/규정 준수 정보로 이메일을 변환합니다.
zone_pivot_groups: app-info-data-mcas-identity
ms.openlocfilehash: 9843ece5a330f4a8b8adb6f1388a4a26e12dbe21
ms.sourcegitcommit: a44420a99a1a3a9d0e49f4be66f266e2d4ca7bbb
ms.translationtype: MT
ms.contentlocale: ko-KR
ms.lasthandoff: 05/19/2021
ms.locfileid: "52553759"
---
# <a name="priority-matrix---turn-emails-into-tasks"></a>우선 순위 매트릭스 - 전자 메일을 작업으로 전환

<p></p><a href="https://aka.ms/appcertification" alt="This Microsoft 365 Certified app has been reviewed by Microsoft against industry standards and controls for security, compliance, and data handling practices. Where applicable, Microsoft has verified the developer's claims of compliance with reasonable and effective practices." target="_blank"><img alt="Click here for more information on the Microsoft Certified app program." src="../media/certified.png" width="650" /></a>
<p>최종 업데이트: 2021년 4월 16일</p>

* <a href="https://appsource.microsoft.com/product/office/WA104381735" target="_blank">앱소스에서 보기</a>

::: zone pivot="general"

### <a name="general-information"></a>일반 정보

마이크로소프트에 대한 Appfluence Inc.에서 제공하는 정보:

| **정보** | **응답** |
|:----------------|:-------------|
| 앱 이름 | 우선 순위 매트릭스 - 전자 메일을 작업으로 전환 |
| ID | WA104381735 |
| 지원되는 Office 365 클라이언트 | Outlook 2016 또는 나중에 Windows, Outlook 2016 또는 나중에 맥에서, iOS에 Outlook, 안드로이드에 Outlook, 웹에서 Outlook |
| 파트너 회사 이름 | Appfluence Inc |
| 파트너 웹사이트의 URL | [https://appfluence.com/](https://appfluence.com/) |
| 개인정보 처리방침의 URL | [https://appfluence.com/privacy](https://appfluence.com/privacy) |
| 이용 약관의 URL | [https://appfluence.com/eula](https://appfluence.com/eula) |

 [!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="data"

### <a name="how-the-app-handles-data"></a>앱이 데이터를 처리하는 방법

이 정보는 Appfluence Inc에서 이 앱이 조직 데이터를 수집하고 저장하는 방법과 앱이 수집하는 데이터에 대한 조직이 가질 수 있는 제어에 대해 제공했습니다.

#### <a name="data-access-using-microsoft-graph"></a>Microsoft Graph 을 사용하여 데이터 액세스

이 [앱에서 필요한 Microsoft Graph 권한을 나열합니다.](https://docs.microsoft.com/graph/permissions-reference)

>| **사용 권한**  | **권한 유형(위임/응용 프로그램)** | **데이터가 수집되고 있습니까? 그것을 수집하기위한 정당화?** | **데이터가 저장되어 있습니까? 그것을 저장하는 정당화?** | **Azure AD 앱 ID** |
>|:----------------|:--------------------|:---------------------------------------------------|:--------------------------|:--------------------------|
>| Calendars.Read | 위임 | 새 사용자가 계정에 추가된 경우에만 이메일을 저장합니다. | 새 계정 생성시 다른 팀 구성원을 제안하기 위해 이 것을 사용합니다. | 5be2b320-a5b7-4221-893c-dee506e4e365 |
>| User.ReadBasic.All | 위임 | 새 사용자가 계정에 추가된 경우에만 이메일을 저장합니다. | 새 계정 생성시 다른 팀 구성원을 제안하기 위해 이 것을 사용합니다. | 5be2b320-a5b7-4221-893c-dee506e4e365 |
>| offline_access | 위임 | 사용자를 대신하여 요청을 수행하기 위해 로그인 토큰을 저장합니다. | 사용자를 귀찮게하지 않고 토큰을 새로 고칩니다. (Teams 우선 매트릭스) | 5be2b320-a5b7-4221-893c-dee506e4e365 |
>| Files.Read.All | 위임 | 사용자가 명시적으로 고의로 원래 파일에 연결되는 Priority Matrix 항목을 생성하지 않는 한 파일 정보를 저장하지 않습니다. | 일대일 기능(웹 앱및 Outlook/Teams 추가 기능을 통해 사용할 수 있음)에서 이 기능을 사용하여 회의 및 전반적인 협업을 용이하게 하기 위한 방법으로 시스템의 두 사용자 간에 공유되는 SharePoint/OneDrive 파일을 강조표시합니다. | affadfb6-f17b-428f-97f9-9aae3b6175bc |
>| User.Read | 위임 | 기본 사용자 프로필 정보(표시 이름, 이름, 성, 이메일, 아바타)는 당사에 저장됩니다. | 사용자의 이름, 이메일, 아바타를 사용하여 계정을 개인화하십시오. | affadfb6-f17b-428f-97f9-9aae3b6175bc |
>| 오픈 ID | 위임 | 우리는 사용자의 로그인 모드를 나타내기 위해 SSO 연결을 저장합니다. | 단일 사인온을 통해 사용자에게 로그인합니다. | affadfb6-f17b-428f-97f9-9aae3b6175bc |
>| Calendars.Read | 위임 | 소수의 캘린더 이벤트가 시스템에 저장된 작업으로 바뀌습니다. | 캘린더 이벤트를 읽고 1:1 뷰에 표시할 수 있습니다. 또한 새 계정을 초기화합니다.  | d76f016f-52c7-41b5-835b-900361d7040c |
>| Mail.Read | 위임 | 시스템에서 만든 작업을 원래 메시지에 대한 링크와 함께 저장합니다. | Outlook 추가 기능에서 사용하여 전자 메일을 작업으로 전환하고 공유 작업을 1:1 뷰로 표시합니다. | d76f016f-52c7-41b5-835b-900361d7040c |
>| 작업.읽기 | 위임 | 일부 Outlook/플래너 작업은 새로운 사용자를 돕기 위해 시스템에서 복제됩니다. | 우리는 그들의 Graph 작업으로 새로운 사용자 계정을 부트 스트랩. | d76f016f-52c7-41b5-835b-900361d7040c |


#### <a name="non-microsoft-services-used"></a>사용되지 Microsoft 서비스

앱이 Microsoft 가 아닌 서비스와 조직 데이터를 전송하거나 공유하는 경우 앱에서 사용하는 비Microsoft 서비스, 전송되는 데이터를 나열하고 앱이 이 정보를 전송해야 하는 이유에 대한 명분을 포함합니다.

>비Microsoft 서비스 사용되지 않습니다.



#### <a name="telemetry-data"></a>원격 분석 데이터

조직 식별 정보(OII) 또는 최종 사용자 식별 정보(EUII)가 이 응용 프로그램의 원격 분석 또는 로그에 표시됩니까? 그렇다면 저장되는 데이터와 보존 및 제거 정책은 무엇입니까?

>예. 당사는 사용자의 이메일을 시스템의 고유 ID로 사용하고 응용 프로그램 오류를 추적하고 시스템의 주요 이벤트(다운로드, 로그인, 응용 프로그램 버전 등)를 추적하여 고객 서비스 팀이 고객 쿼리에 대한 신속한 응답을 제공할 수 있도록 합니다. GDPR 규정 준수의 일환으로 삭제 요청 후 2주 이내에 모든 고객 데이터를 삭제하지만 실제로는 반자동 방식으로 이 작업을 수행할 내부 스크립트가 있으므로 실제로 는 같은 날에 이 작업을 수행합니다.

#### <a name="organizational-controls-for-data-stored-by-partner"></a>파트너가 저장한 데이터에 대한 조직 제어

조직의 관리자가 파트너 시스템에서 자신의 정보를 제어하는 방법을 설명해 보세요. 예를 들어 삭제, 보존, 감사, 보관, 최종 사용자 정책 등

>응용 프로그램 데이터는 소수의 관리자 그룹으로 제한된 암호화된 데이터베이스에 안전하게 저장됩니다. 액세스를 더욱 안전하게 하기 위해 2단계 인증을 적용하고, 제어된 IP 주소 집합에 대한 액세스를 제한하며, 개방형 인터넷에서 직접 액세스할 수 없는 자체 개인 서브넷에서 데이터베이스를 찾습니다.

#### <a name="human-review-of-organizational-information"></a>조직 정보의 인간 검토

이 앱에서 수집하거나 저장되는 조직 식별 정보(OII) 데이터를 검토하거나 분석하는 데 관여하는 사람이 있습니까?

>아니요

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="mcas"

[Microsoft Cloud App Security](https://www.microsoft.com/enterprise-mobility-security/cloud-app-security) 카탈로그의 정보는 아래에 나타납니다.

<iframe height='1020' title='Microsoft Cloud App Security 정보' src='https://appmcasinfoprod.azurewebsites.net/#/dashboard/35667' frameborder='no' style='width: 100%;'></iframe>

<a href="https://appmcasinfoprod.azurewebsites.net/#/dashboard/35667" target="_blank">새 탭에서 보기</a>

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="identity"

### <a name="identity-information"></a>신원 정보

이 정보는 Appfluence Inc에서 이 앱이 인증, 승인, 응용 프로그램 등록 모범 사례 및 기타 ID 기준을 처리하는 방법에 대해 제공했습니다.

| **정보** | **응답** |
|:----------------|:-------------|
| Microsoft 식별 플랫폼(Azure AD)과 통합합니까?  | 예 |
| Microsoft ID 플랫폼 통합 검사 목록에 설명된 모든 적용 가능한 모범 사례를 검토하고 준수했습니까?  | 예 |
| 앱에서 인증에 MSAL(Microsoft 인증 라이브러리)을 사용합니까? | 예 |
| 앱이 조건부 액세스 정책을 지원합니까? | 아니요 |
| 앱에서 시나리오에 대한 최소 권한 권한을 요청합니까? | 예 |
| 앱의 정적 등록 권한은 앱이 동적으로 점진적으로 요청하는 권한을 정확하게 반영합니까? | 예 |
| 앱이 다중 테넌션을 지원합니까? | 예 |
| 앱에 기밀 클라이언트가 있습니까? | 예 |
| 앱에 등록된 URI(리디렉션 통합 리소스 식별자)를 모두 소유하고 있습니까? | 예 |
| 앱의 경우 무엇을 사용하지 않으려습니까? | - 와일드카드 리디렉션 URI,<br/><br/>- 리소스 소유자 암호 자격 증명(ROPC) 흐름 |
| 앱에서 웹 API가 노출됩니까? | 예 |
| 권한 모델은 클라이언트 앱이 적절한 동의를 받는 경우에만 호출을 성공시킬 수 있습니까? | 예 |
| 앱에서 미리 보기 API를 사용합니까? | 아니요 |
| 앱에서 비하 API를 사용합니까? | 아니요 |

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end
