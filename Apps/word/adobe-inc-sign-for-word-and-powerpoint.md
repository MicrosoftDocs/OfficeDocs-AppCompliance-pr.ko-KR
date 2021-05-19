---
title: 어도비 사인용 어도비 사인용 어도비 링크 및 PowerPoint
ms.author: elmalova
author: elenamalova
ms.date: 02/12/2021
ms.topic: article
ms.service: attestation
certification_type: certified
description: Adobe Sign for Word 및 PowerPoint, 데이터 처리 정책, Microsoft Cloud App Security 앱 카탈로그 정보 및 CSA STAR 레지스트리의 보안/규정 준수 정보에 대한 사용 가능한 모든 보안 및 규정 준수 정보.
zone_pivot_groups: app-info-data-mcas-identity
ms.openlocfilehash: aa9b4a19f83574d7d9428bbf979ac7ee1375227c
ms.sourcegitcommit: a44420a99a1a3a9d0e49f4be66f266e2d4ca7bbb
ms.translationtype: MT
ms.contentlocale: ko-KR
ms.lasthandoff: 05/19/2021
ms.locfileid: "52552669"
---
# <a name="adobe-sign-for-word-and-powerpoint"></a>단어와 PowerPoint 어도비 기호

<p></p><a href="https://aka.ms/appcertification" alt="This Microsoft 365 Certified app has been reviewed by Microsoft against industry standards and controls for security, compliance, and data handling practices. Where applicable, Microsoft has verified the developer's claims of compliance with reasonable and effective practices." target="_blank"><img alt="Click here for more information on the Microsoft Certified app program." src="../media/certified.png" width="650" /></a>
<p>최종 업데이트: 2021년 2월 12일</p>

* <a href="https://appsource.microsoft.com/product/office/WA104381155" target="_blank">앱소스에서 보기</a>

::: zone pivot="general"

### <a name="general-information"></a>일반 정보

Adobe Inc.가 Microsoft에 제공한 정보:

| **정보** | **응답** |
|:----------------|:-------------|
| 앱 이름 | 단어와 PowerPoint 어도비 기호 |
| ID | WA104381155 |
| 지원되는 Office 365 클라이언트 | mac에서 Word 2016 또는 그 이후, PowerPoint 2013 서비스 팩 1 이상 Windows, Word 2013 서비스 팩 1 이상에서 Windows, 웹용 Word, 웹용 PowerPoint, PowerPoint 2016 또는 이후 Mac에서 |
| 파트너 회사 이름 | 어도비 주식회사 |
| 파트너 웹사이트의 URL | [https://www.adobe.com/](https://www.adobe.com/) |
| 개인정보 처리방침의 URL | [https://www.adobe.com/privacy/policies-business/esign.html](https://www.adobe.com/privacy/policies-business/esign.html) |
| 이용 약관의 URL | [https://support.office.com/client/61994a3b-2c87-41c4-a88d-a...](https://support.office.com/client/61994a3b-2c87-41c4-a88d-a6455efa362d?omkt=en) |

 [!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="data"

### <a name="how-the-app-handles-data"></a>앱이 데이터를 처리하는 방법

이 정보는 Adobe Inc.에서 이 앱이 조직 데이터를 수집하고 저장하는 방법과 앱이 수집하는 데이터에 대한 조직이 가질 수 있는 제어에 대해 제공했습니다.

#### <a name="data-access-using-microsoft-graph"></a>Microsoft Graph 을 사용하여 데이터 액세스

이 [앱에서 필요한 Microsoft Graph 권한을 나열합니다.](https://docs.microsoft.com/graph/permissions-reference)

>| **사용 권한**  | **권한 유형(위임/응용 프로그램)** | **데이터가 수집되고 있습니까? 그것을 수집하기위한 정당화?** | **데이터가 저장되어 있습니까? 그것을 저장하는 정당화?** | **Azure AD 앱 ID** |
>|:----------------|:--------------------|:---------------------------------------------------|:--------------------------|:--------------------------|
>| 메일.읽기 쓰기 | 위임 | 첨부된 문서, 보낸 자 및 수신자 이메일 및 전자 메일에서 Adobe 사인에 이르는 메시지 콘텐츠를 채우려면 서명을 보내십시오. 이는 Adobe Sign에서 해당 필드를 다시 입력하는 데 사용자 시간을 절약하기 위한 것입니다. 계약이 체결된 후 사용자가 수신자에게 트랜잭션이 완료됨을 알리는 이메일을 보낼 새 이메일을 자동으로 작성합니다. | Adobe Sign은 첨부 파일을 24시간 만료되는 임시 파일로 저장합니다. | 72d5ac5d-a427-408b-907d-72da3f3ddd1 |
>| 사람들.읽기 | 위임 | 서명 환경을 위해 보내기에서 전자 메일 주소를 자동 채우려면 &quot; &quot; 초기 문자를 입력하여 사용자가 전체 전자 메일을 입력할 필요가 없습니다. | Adobe Sign은 계약에 받는 사람 전자 메일 및 디스플레이 이름만 저장합니다. | 72d5ac5d-a427-408b-907d-72da3f3ddd1 |
>| User.Read | 위임 | 사용자의 프로필을 읽고 어도비 사인을 사용할 수 있도록 프로필(기본적으로 이메일 및 userId)을 데이터베이스에 일치시려면. | 사용자의 프로필을 읽고 어도비 사인을 사용할 수 있도록 프로필(기본적으로 이메일 및 userId)을 데이터베이스에 일치시려면. | 72d5ac5d-a427-408b-907d-72da3f3ddd1 |
>| offline_access | 위임 | 액세스 토큰을 새로 고치려면 현재 토큰이 만료된 경우 예를 들어 사용자가 서명 &quot; 창에 대한 보내기에 &quot; 있고 너무 오랫동안 비활성 상태로 두면 사용자가 활성 상태일 때 새 토큰을 새로 고쳐야 합니다. | 액세스 토큰을 새로 고치려면 현재 토큰이 만료된 경우 예를 들어 사용자가 서명 &quot; 창에 대한 보내기에 &quot; 있고 너무 오랫동안 비활성 상태로 두면 사용자가 활성 상태일 때 새 토큰을 새로 고쳐야 합니다. | 72d5ac5d-a427-408b-907d-72da3f3ddd1 |
>| 오픈 ID | 위임 | 이메일 및 UserId. Adobe Sign 앱 사용 허가에 대한 동의를 보장하기 위해 사용자에게 로그인합니다.  | 전자 메일은 Adobe Sign의 사용자를 위한 고유 식별자입니다. 우리는 이메일 ID를 저장하여 해당 사용자의 모든 활동을 Adobe Sign 레코드에 매핑할 수 있습니다.  | 72d5ac5d-a427-408b-907d-72da3f3ddd1 |


#### <a name="non-microsoft-services-used"></a>사용되지 Microsoft 서비스

앱이 Microsoft 가 아닌 서비스와 조직 데이터를 전송하거나 공유하는 경우 앱에서 사용하는 비Microsoft 서비스, 전송되는 데이터를 나열하고 앱이 이 정보를 전송해야 하는 이유에 대한 명분을 포함합니다.

>비Microsoft 서비스 사용되지 않습니다.



#### <a name="telemetry-data"></a>원격 분석 데이터

조직 식별 정보(OII) 또는 최종 사용자 식별 정보(EUII)가 이 응용 프로그램의 원격 분석 또는 로그에 표시됩니까? 그렇다면 저장되는 데이터와 보존 및 제거 정책은 무엇입니까?

>로그는 고객 문제를 식별하고 해결할 수 있는 충분한 정보가 포함되어 있습니다. 로그는 90일 동안 유지되며 액세스가 제한됩니다. 사용자가 오프라인 상태에서 인증을 위해 데이터베이스 저장소해시 식별 정보를 해시했습니다. 데이터베이스 보존 정책은 마지막으로 사용한 날로부터 30일 입니다.

#### <a name="organizational-controls-for-data-stored-by-partner"></a>파트너가 저장한 데이터에 대한 조직 제어

조직의 관리자가 파트너 시스템에서 자신의 정보를 제어하는 방법을 설명해 보세요. 예를 들어 삭제, 보존, 감사, 보관, 최종 사용자 정책 등

>우리는 응용 프로그램을 Microsoft Teams 위해 시스템에 고객 관리자 상호 작용이 없습니다.

#### <a name="human-review-of-organizational-information"></a>조직 정보의 인간 검토

이 앱에서 수집하거나 저장되는 조직 식별 정보(OII) 데이터를 검토하거나 분석하는 데 관여하는 사람이 있습니까?

>예

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="mcas"

[Microsoft Cloud App Security](https://www.microsoft.com/enterprise-mobility-security/cloud-app-security) 카탈로그의 정보는 아래에 나타납니다.

<iframe height='1020' title='Microsoft Cloud App Security 정보' src='https://appmcasinfoprod.azurewebsites.net/#/dashboard/11641' frameborder='no' style='width: 100%;'></iframe>

<a href="https://appmcasinfoprod.azurewebsites.net/#/dashboard/11641" target="_blank">새 탭에서 보기</a>

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="identity"

### <a name="identity-information"></a>신원 정보

이 정보는 Adobe Inc.에서 이 앱이 인증, 승인, 응용 프로그램 등록 모범 사례 및 기타 ID 기준을 처리하는 방법에 대해 제공했습니다.

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
| 앱에서 미리 보기 API를 사용합니까? | 아니요 |
| 앱에서 비하 API를 사용합니까? | 아니요 |

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end
