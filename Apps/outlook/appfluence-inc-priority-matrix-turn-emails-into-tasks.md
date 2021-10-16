---
title: 우선 순위 매트릭스에 대한 응용 프로그램 정보 - Appfluence Inc를 통해 전자 메일을 작업으로 전환
ms.author: elmalova
author: elenamalova
ms.date: 06/23/2021
ms.topic: article
ms.service: attestation
certification_type: certified
description: 우선 순위 매트릭스에 사용할 수 있는 모든 보안 및 규정 준수 정보 - CSA STAR 레지스트리에서 전자 메일을 작업, 데이터 처리 정책, Microsoft Cloud App Security 앱 카탈로그 정보 및 보안/규정 준수 정보로 전환합니다.
zone_pivot_groups: app-info-data-mcas-identity
ms.openlocfilehash: b175c992f970dfa2477f549f88be6a4db905f217
ms.sourcegitcommit: 9dab9c9dacb9c6daaa6b0041ccc8a49bafdad331
ms.translationtype: MT
ms.contentlocale: ko-KR
ms.lasthandoff: 10/16/2021
ms.locfileid: "60414202"
---
# <a name="priority-matrix---turn-emails-into-tasks"></a>우선 순위 매트릭스 - 전자 메일을 작업으로 전환

<p></p><a href="https://aka.ms/appcertification" alt="This Microsoft 365 Certified app has been reviewed by Microsoft against industry standards and controls for security, compliance, and data handling practices. Where applicable, Microsoft has verified the developer's claims of compliance with reasonable and effective practices." target="_blank"><img alt="Click here for more information on the Microsoft Certified app program." src="../media/certified.png" width="650" /></a>
<p>개발자가 마지막으로 업데이트한 날짜: 2021년 6월 23일</p>

* <a href="https://appsource.microsoft.com/product/office/WA104381735" target="_blank">AppSource의 보기</a>

::: zone pivot="general"

### <a name="general-information"></a>일반 정보

Appfluence Inc에서 Microsoft에 제공한 정보:

| **정보** | **응답** |
|:----------------|:-------------|
| 앱 이름 | 우선 순위 매트릭스 - 전자 메일을 작업으로 전환 |
| ID | WA104381735 |
| Office 365 클라이언트 지원 | Outlook 2016 Windows, Outlook 2016 이상, iOS, Outlook android, Outlook 이상에서 웹용 Outlook |
| 파트너 회사 이름 | Appfluence Inc |
| 파트너 웹 사이트의 URL | [https://appfluence.com/office-365-project-management-integr...](https://appfluence.com/office-365-project-management-integration/) |
| 개인 정보 취급 방침의 URL | [https://appfluence.com/privacy/](https://appfluence.com/privacy/) |
| 사용 약관 URL | [https://appfluence.com/eula](https://appfluence.com/eula) |

 [!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="data"

### <a name="how-the-app-handles-data"></a>앱이 데이터를 처리하는 방법

이 정보는 Appfluence Inc에서 이 앱이 조직 데이터를 수집 및 저장하는 방법과 앱이 수집하는 데이터를 통해 조직이 하게 될 컨트롤에 대해 제공됩니다.

#### <a name="data-access-using-microsoft-graph"></a>Microsoft 365를 사용한 데이터 Graph

이 앱에 [Graph Microsoft 사용자 권한을](https://docs.microsoft.com/graph/permissions-reference) 나열합니다.

>| **사용 권한**  | **사용 권한 유형(위임/ 응용 프로그램)** | **데이터가 수집하나요? 수집의 사당성** | **데이터가 저장되어 있나요? 저장 사정이 있나요?** | **Azure AD 앱 ID** |
>|:----------------|:------------------------------------------------|:--------------------------------------------------------|:--------------------------------------------------|:--------------------|
>| Calendars.Read | 위임 | 새 사용자가 계정에 추가될 때만 전자 메일을 저장합니다. | 새 계정을 만들 때 이 계정을 사용하여 다른 팀 구성원을 제안합니다. | [5be2b320-a5b7-4221-893c-dee506e4e365](https://docs.microsoft.com/microsoft-365-app-certification/azure/5be2b320-a5b7-4221-893c-dee506e4e365) |
>| User.ReadBasic.All | 위임 | 새 사용자가 계정에 추가될 때만 전자 메일을 저장합니다. | 새 계정을 만들 때 이 계정을 사용하여 다른 팀 구성원을 제안합니다. | [5be2b320-a5b7-4221-893c-dee506e4e365](https://docs.microsoft.com/microsoft-365-app-certification/azure/5be2b320-a5b7-4221-893c-dee506e4e365) |
>| offline_access | 위임 | 사용자를 대신하여 요청을 수행하기 위해 로그인 토큰을 저장합니다. | 사용자를 유인하지 않고 토큰을 새로 고침합니다. (우선 순위 매트릭스(Teams) | [5be2b320-a5b7-4221-893c-dee506e4e365](https://docs.microsoft.com/microsoft-365-app-certification/azure/5be2b320-a5b7-4221-893c-dee506e4e365) |
>| Files.Read.All | 위임 | 사용자가 명시적으로 원래 파일에 연결되는 우선 순위 매트릭스 항목을 명시적으로 만들지 않는 한 어떤 파일 정보도 저장하지 않습니다. | 웹앱 및 Outlook/Teams 추가 기능을 통해 사용할 수 있는 일대일 기능에서는 이 기능을 사용하여 모임 및 전반적인 공동 작업을 용이하게 하기 위해 시스템에서 두 사용자 간에 공유되는 SharePoint/OneDrive 파일을 강조합니다. | [affadfb6-f17b-428f-97f9-9aae3b6175bc](https://docs.microsoft.com/microsoft-365-app-certification/azure/affadfb6-f17b-428f-97f9-9aae3b6175bc) |
>| User.Read | 위임 | 기본 사용자 프로필 정보(표시 이름, 이름, 성, 전자 메일, 아바타)는 저희가 저장합니다. | 사용자 이름, 전자 메일, 아바타를 사용하여 계정을 개인 설정하세요. | [affadfb6-f17b-428f-97f9-9aae3b6175bc](https://docs.microsoft.com/microsoft-365-app-certification/azure/affadfb6-f17b-428f-97f9-9aae3b6175bc) |
>| openid | 위임 | 사용자의 로그인 모드를 나타내기 위해 SSO 연결을 저장합니다. | Single Sign-On을 통해 사용자를 로그인하기 위해 | [affadfb6-f17b-428f-97f9-9aae3b6175bc](https://docs.microsoft.com/microsoft-365-app-certification/azure/affadfb6-f17b-428f-97f9-9aae3b6175bc) |
>| Calendars.Read | 위임 | 소수의 일정 이벤트가 시스템에 저장된 작업으로 설정됩니다. | 1:1 보기에 표시될 수 있도록 일정 이벤트를 읽습니다. 또한 새 계정을 초기화합니다.  | [d76f016f-52c7-41b5-835b-900361d7040c](https://docs.microsoft.com/microsoft-365-app-certification/azure/d76f016f-52c7-41b5-835b-900361d7040c) |
>| Mail.Read | 위임 | 시스템에서 만든 작업을 원본 메시지에 대한 링크와 함께 저장합니다. | 이 Outlook 추가 기능에서 전자 메일을 작업으로 전환하고 공유 작업을 1:1 보기로 표시하는 데 사용됩니다. | [d76f016f-52c7-41b5-835b-900361d7040c](https://docs.microsoft.com/microsoft-365-app-certification/azure/d76f016f-52c7-41b5-835b-900361d7040c) |
>| Tasks.Read | 위임 | 일부 Outlook/Planner 작업은 새 사용자를 지원하기 위해 시스템에 복제됩니다. | 새 사용자 계정을 해당 사용자 계정으로 부트스트스트 Graph 작업을 수행합니다. | [d76f016f-52c7-41b5-835b-900361d7040c](https://docs.microsoft.com/microsoft-365-app-certification/azure/d76f016f-52c7-41b5-835b-900361d7040c) |


#### <a name="non-microsoft-services-used"></a>비영구 Microsoft 서비스

앱이 Microsoft가 아닌 서비스로 조직 데이터를 전송하거나 공유하는 경우 앱에서 사용하는 비 Microsoft 서비스, 전송되는 데이터를 나열하고 앱이 이 정보를 전송해야 하는 이유에 대한 사유를 포함합니다.

>비영구 Microsoft 서비스 사용되지 않습니다.



#### <a name="telemetry-data"></a>원격 분석 데이터

이 응용 프로그램의 원격 분석 또는 로그에 OII(조직 식별 정보) 또는 EUII(최종 사용자 식별 정보)가 나타나나요? 그렇다면 저장되는 데이터와 보존 및 제거 정책에 대해 설명하세요.

>예, 사용자의 전자 메일을 시스템에서 고유 ID로 사용하며, 이 ID는 응용 프로그램 오류를 추적하고, 고객 서비스 팀이 고객 쿼리에 대한 신속한 응답을 제공할 수 있도록 시스템의 주요 이벤트(다운로드, 로그인, 응용 프로그램 버전 등)를 추적하는 데 사용됩니다. GDPR 규정 준수의 일부로, 삭제 요청 후 2주 이내에 모든 고객 데이터를 삭제합니다. 그러나 실제로는 동일한 날에 이 작업을 수행하기는 하지만 반기적으로 이 작업을 수행하기 위한 내부 스크립트가 있습니다.

#### <a name="organizational-controls-for-data-stored-by-partner"></a>파트너가 저장한 데이터에 대한 조직 제어

조직의 관리자가 파트너 시스템에서 정보를 제어하는 방법에 대해 설명하는 방법 삭제, 보존, 감사, 보관, 최종 사용자 정책 등

>응용 프로그램 데이터는 소규모 관리자 그룹으로 제한된 액세스 권한이 있는 암호화된 데이터베이스에 안전하게 저장됩니다. 액세스를 보다 안전하게 보호하기 위해 2단계 인증을 적용하고, 제어된 IP 주소 집합에 대한 액세스를 제한하고, 개방형 인터넷에서 직접 액세스할 수 없는 자체 개인 서브넷에서 데이터베이스를 찾습니다.

#### <a name="human-review-of-organizational-information"></a>조직 정보의 인적 검토

사람이 이 앱에서 수집하거나 저장하는 OII(조직 식별 정보) 데이터를 검토하거나 분석하는 데 관여하나요?

>아니요

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="mcas"

Microsoft Cloud App Security [카탈로그의](https://www.microsoft.com/enterprise-mobility-security/cloud-app-security) 정보가 아래에 표시됩니다.

<iframe height='1020' title='Microsoft Cloud App Security 정보' src='https://appmcasinfoprod.azurewebsites.net/#/dashboard/35667' frameborder='no' style='width: 100%;'></iframe>

<a href="https://appmcasinfoprod.azurewebsites.net/#/dashboard/35667" target="_blank">새 탭에서 보기</a>

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="identity"

### <a name="identity-information"></a>ID 정보

이 정보는 Appfluence Inc에서 이 앱이 인증, 권한 부여, 응용 프로그램 등록 모범 사례 및 기타 ID 조건을 처리하는 방법에 대해 제공했습니다.

| **정보** | **응답** |
|:----------------|:-------------|
| Microsoft Identify Platform(Azure AD)과 통합하나요?  | 예 |
| 통합 검사 목록에 설명된 적용 가능한 모든 모범 사례를 Microsoft ID 플랫폼 준수하나요?  | 예 |
| 앱에서 인증에 MSAL(Microsoft 인증 라이브러리)을 사용하나요? | 아니요 |
| 앱에서 조건부 액세스 정책을 지원하나요? | 아니요 |
| 앱에서 시나리오에 대한 최소 권한 권한을 요청하나요? | 예 |
| 앱의 정적으로 등록된 사용 권한은 앱이 동적으로 그리고 증분적으로 요청하는 권한을 정확하게 반영하나요? | 예 |
| 앱에서 다중 테넌시를 지원하나요? | 예 |
| 앱에 기밀 클라이언트가 있나요? | 예 |
| 앱에 등록된 리디렉션 URI(통합 리소스 식별자)를 모두 소유하고 있나요? | 예 |
| 앱의 경우 어떻게 사용하지 않도록 해야 하나요? | - 와일드카드 리디렉션 URIS,<br/><br/>- 리소스 소유자 암호 자격 증명(ROPC) 흐름 |
| 앱에서 웹 API를 노출하나요? | 예 |
| 사용 권한 모델에서 클라이언트 앱이 적절한 동의를 받은 경우 통화 성공만 허용하나요? | 예 |
| 앱에서 미리 보기 API를 사용하나요? | 아니요 |
| 앱에서 사용되지 않는 API를 사용하나요? | 아니요 |

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

