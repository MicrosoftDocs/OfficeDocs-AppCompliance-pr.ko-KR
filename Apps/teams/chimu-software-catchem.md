---
title: Chimu Software의 CatchEm에 대한 응용 프로그램 정보
ms.author: elmalova
author: elenamalova
ms.date: 03/27/2021
ms.topic: article
ms.service: attestation
certification_type: attested
description: CatchEm, 데이터 처리 정책, CSA STAR 레지스트리의 Microsoft Cloud App Security 앱 카탈로그 정보 및 보안/규정 준수 정보에 사용할 수 있는 모든 보안 및 규정 준수 정보
zone_pivot_groups: app-info-data-mcas-identity
ms.openlocfilehash: bdac27ddbc3148644562af20f8f6d415a56903d9
ms.sourcegitcommit: a613e40971c8b48fa2b7a35039b4331a8116763b
ms.translationtype: MT
ms.contentlocale: ko-KR
ms.lasthandoff: 07/22/2021
ms.locfileid: "53522031"
---
# <a name="catchem"></a>CatchEm

<p></p>
<img alt="Publisher Attestation: The information on this page is based on a self-assessment report provided by the app developer on the security, compliance, and data handling practices followed by this app. Microsoft makes no guarantees regarding the accuracy of the information." src="../media/attested.png" width="650" />
<p>개발자가 마지막으로 업데이트한 날짜: 2021년 3월 27일</p>

* <a href="https://teams.microsoft.com/l/app/fc686a41-3bd0-45b3-a56d-f278888fd694" target="_blank">저장소의 Teams 보기</a>
* <a href="https://appsource.microsoft.com/product/office/WA200002639" target="_blank">AppSource의 보기</a>

::: zone pivot="general"

### <a name="general-information"></a>일반 정보

Chimu Software에서 Microsoft에 제공하는 정보:

| **정보** | **응답** |
|:----------------|:-------------|
| 앱 이름 | CatchEm |
| ID | WA200002639 |
| Office 365 클라이언트 지원 | Microsoft Teams |
| 파트너 회사 이름 | Chimu Software |
| 파트너 웹 사이트의 URL | [https://chimusoftware.com](https://chimusoftware.com) |
| 응용 프로그램 Teams 페이지의 URL입니다. | [https://catchem.apps.chimusoftware.com/help](https://catchem.apps.chimusoftware.com/help) |
| 개인 정보 취급 방침의 URL | [https://www.chimusoftware.com/apps/catchem/privacy.html](https://www.chimusoftware.com/apps/catchem/privacy.html) |
| 사용 약관 URL | [https://www.chimusoftware.com/apps/catchem/termsofuse.html](https://www.chimusoftware.com/apps/catchem/termsofuse.html) |

 [!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="data"

### <a name="how-the-app-handles-data"></a>앱이 데이터를 처리하는 방법

이 정보는 Chimu Software에서 이 앱이 조직 데이터를 수집하고 저장하는 방법 및 앱이 수집하는 데이터를 통해 조직에서 제공하는 컨트롤에 대해 제공됩니다.

#### <a name="data-access-using-microsoft-graph"></a>Microsoft 365를 사용한 데이터 Graph

이 앱에 [Graph Microsoft 사용자 권한을](https://docs.microsoft.com/graph/permissions-reference) 나열합니다.

>| **사용 권한**  | **사용 권한 유형(위임/ 응용 프로그램)** | **데이터가 수집하나요? 수집의 사당성** | **데이터가 저장되어 있나요? 저장 사정이 있나요?** | **Azure AD 앱 ID** |
>|:----------------|:------------------------------------------------|:--------------------------------------------------------|:--------------------------------------------------|:--------------------|
>| Chat.ReadBasic | 위임 | 이 사용 권한은 응용 프로그램 사용자의 연락처를 확인하는 데 필요합니다. AadObjectId: 사용자를 고유하게 식별합니다. TenantId: 연락처가 사용자 내부인지 또는 외부 연락처인지를 판단합니다. DisplayName, GivenName, Surname: 응용 프로그램 사용자에 대한 연락처를 식별합니다. Email, UserPrincipalName: 이름이 같은 연락처를 구분하고 클릭하여 채팅 &quot; 기능을 &quot; 허용하는 데 도움이 됩니다. 최신 채팅 ID: &quot; 클릭하여 채팅 기능을 사용하도록 &quot; 설정하려면 | 이 사용 권한은 응용 프로그램 사용자의 연락처를 확인하는 데 필요합니다. AadObjectId: 사용자를 고유하게 식별합니다. TenantId: 연락처가 사용자 내부인지 또는 외부 연락처인지를 판단합니다. DisplayName, GivenName, Surname: 응용 프로그램 사용자에 대한 연락처를 식별합니다. Email, UserPrincipalName: 이름이 같은 연락처를 구분하고 클릭하여 채팅 &quot; 기능을 &quot; 허용하는 데 도움이 됩니다. 최신 채팅 ID: &quot; 클릭하여 채팅 기능을 사용하도록 &quot; 설정하려면 | [fc686a41-3bd0-45b3-a56d-f278888fd694](https://docs.microsoft.com/microsoft-365-app-certification/azure/fc686a41-3bd0-45b3-a56d-f278888fd694) |
>| People.Read | 위임 | 외부 연락처에 대한 데이터의 정확도를 향상시킵니다. DisplayName: 응용 프로그램 사용자에 대한 연락처를 식별합니다. | 외부 연락처에 대한 데이터의 정확도를 향상시킵니다. DisplayName: 응용 프로그램 사용자에 대한 연락처를 식별합니다. | [fc686a41-3bd0-45b3-a56d-f278888fd694](https://docs.microsoft.com/microsoft-365-app-certification/azure/fc686a41-3bd0-45b3-a56d-f278888fd694) |
>| Presence.Read.All | 위임 | 연락처 현재 현재 상태 | 해당 없음 | [fc686a41-3bd0-45b3-a56d-f278888fd694](https://docs.microsoft.com/microsoft-365-app-certification/azure/fc686a41-3bd0-45b3-a56d-f278888fd694) |
>| TeamsActivity.Send | 둘 다 | 연락처 현재 상태가 변경된 경우 사용자에게 알림을 보내기 위해 | 해당 없음 | [fc686a41-3bd0-45b3-a56d-f278888fd694](https://docs.microsoft.com/microsoft-365-app-certification/azure/fc686a41-3bd0-45b3-a56d-f278888fd694) |
>| TeamsAppInstallation.ReadWriteSelfForUser | 위임 | 응용 프로그램에 대해 자동 업데이트를 사용하도록 설정하려면 | 해당 없음 | [fc686a41-3bd0-45b3-a56d-f278888fd694](https://docs.microsoft.com/microsoft-365-app-certification/azure/fc686a41-3bd0-45b3-a56d-f278888fd694) |
>| User.Read | 위임 | AadObjectId: 사용자를 고유하게 식별합니다. TenantId: 연락처가 사용자 내부인지 또는 외부 연락처인지를 판단합니다. DisplayName, GivenName, Surname: 응용 프로그램 사용자에 대한 연락처를 식별합니다. 전자 메일, IM 주소, UserPrincipalName: 이름이 같은 연락처를 구분하고 클릭하여 채팅 기능을 &quot; &quot; 허용하는 데 도움이 됩니다. CompanyName, Country: Analytics. AccountEnabled, DeletedDateTime: 비활성화된 사용자에 대한 사용자 데이터 자동 삭제 | AadObjectId: 사용자를 고유하게 식별합니다. TenantId: 연락처가 사용자 내부인지 또는 외부 연락처인지를 판단합니다. DisplayName, GivenName, Surname: 응용 프로그램 사용자에 대한 연락처를 식별합니다. 전자 메일, IM 주소, UserPrincipalName: 이름이 같은 연락처를 구분하고 클릭하여 채팅 기능을 &quot; &quot; 허용하는 데 도움이 됩니다. CompanyName, Country: Analytics. AccountEnabled, DeletedDateTime: 비활성화된 사용자에 대한 사용자 데이터 자동 삭제 | [fc686a41-3bd0-45b3-a56d-f278888fd694](https://docs.microsoft.com/microsoft-365-app-certification/azure/fc686a41-3bd0-45b3-a56d-f278888fd694) |
>| User.ReadBasic.All | 위임 | 내부 연락처의 데이터 정확도를 향상시킵니다. AadObjectId: 사용자를 고유하게 식별합니다. TenantId: 연락처가 사용자 내부인지 또는 외부 연락처인지를 판단합니다. DisplayName, GivenName, Surname: 응용 프로그램 사용자에 대한 연락처를 식별합니다. Email, UserPrincipalName: 이름이 같은 연락처를 구분하고 클릭하여 채팅 &quot; 기능을 &quot; 허용하는 데 도움이 됩니다. | 내부 연락처의 데이터 정확도를 향상시킵니다. AadObjectId: 사용자를 고유하게 식별합니다. TenantId: 연락처가 사용자 내부인지 또는 외부 연락처인지를 판단합니다. DisplayName, GivenName, Surname: 응용 프로그램 사용자에 대한 연락처를 식별합니다. Email, UserPrincipalName: 이름이 같은 연락처를 구분하고 클릭하여 채팅 &quot; 기능을 &quot; 허용하는 데 도움이 됩니다. | [fc686a41-3bd0-45b3-a56d-f278888fd694](https://docs.microsoft.com/microsoft-365-app-certification/azure/fc686a41-3bd0-45b3-a56d-f278888fd694) |
>| offline_access | 위임 | Graph 보안 토큰을 사용하여 사용자가 응용 프로그램을 적극적으로 사용하지 않을 때 응용 프로그램에서 연락처 현재 상태 변경 내용을 알리고 연락처 목록을 업데이트할 수 있도록 허용 | Graph 토큰 | [fc686a41-3bd0-45b3-a56d-f278888fd694](https://docs.microsoft.com/microsoft-365-app-certification/azure/fc686a41-3bd0-45b3-a56d-f278888fd694) |


#### <a name="non-microsoft-services-used"></a>비영구 Microsoft 서비스

앱이 Microsoft가 아닌 서비스로 조직 데이터를 전송하거나 공유하는 경우 앱에서 사용하는 비 Microsoft 서비스, 전송되는 데이터를 나열하고 앱이 이 정보를 전송해야 하는 이유에 대한 사유를 포함합니다.

>비영구 Microsoft 서비스 사용되지 않습니다.

#### <a name="data-access-via-bots"></a>봇을 통한 데이터 액세스

이 앱에 봇 또는 메시징 확장이 포함되어 있는 경우 팀 구성원의 명단(이름, 성, 표시 이름, 전자 메일 주소)이나 팀 구성원이 추가된 채팅의 최종 사용자 식별 정보(EUII)에 액세스할 수 있습니다. 이 앱이 이 기능을 사용하나요?

>| **EUII 액세스의 사유는 무엇입니까?**  | **EUII가 데이터베이스에 저장되어 있나요?** | **EUII 저장의 사유는 무엇입니까?** |
>|:---------------------------------------|:-----------------------------------|:------------------------------------|
>| 메시지 기능의 태그는 연락처의 표시 이름을 사용하여 응용 프로그램 사용자에게 &quot; &quot; 표시해야 합니다. | 연락처의 표시 이름 | 연락처의 이름을 응용 프로그램 사용자에게 다시 제공 |


#### <a name="telemetry-data"></a>원격 분석 데이터

이 응용 프로그램의 원격 분석 또는 로그에 OII(조직 식별 정보) 또는 EUII(최종 사용자 식별 정보)가 나타나나요? 그렇다면 저장되는 데이터와 보존 및 제거 정책에 대해 설명하세요.

>응용 프로그램 원격 분석 또는 로그에 OII 또는 EUII가 나타나지 않습니다.

#### <a name="organizational-controls-for-data-stored-by-partner"></a>파트너가 저장한 데이터에 대한 조직 제어

조직의 관리자가 파트너 시스템에서 정보를 제어하는 방법에 대해 설명하는 방법 삭제, 보존, 감사, 보관, 최종 사용자 정책 등

>해당 없음

#### <a name="human-review-of-organizational-information"></a>조직 정보의 인적 검토

사람이 이 앱에서 수집하거나 저장하는 OII(조직 식별 정보) 데이터를 검토하거나 분석하는 데 관여하나요?

>예

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="mcas"

Microsoft Cloud App Security [카탈로그의](https://www.microsoft.com/enterprise-mobility-security/cloud-app-security) 정보가 아래에 표시됩니다.

<iframe height='1020' title='Microsoft Cloud App Security 정보' src='https://appmcasinfoprod.azurewebsites.net/#/dashboard/36911' frameborder='no' style='width: 100%;'></iframe>

<a href="https://appmcasinfoprod.azurewebsites.net/#/dashboard/36911" target="_blank">새 탭에서 보기</a>

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="identity"

### <a name="identity-information"></a>ID 정보

이 정보는 Chimu Software에서 이 앱이 인증, 권한 부여, 응용 프로그램 등록 모범 사례 및 기타 ID 조건을 처리하는 방법에 대해 제공했습니다.

| **정보** | **응답** |
|:----------------|:-------------|
| Microsoft Identify Platform(Azure AD)과 통합하나요?  | 예 |
| 통합 검사 목록에 설명된 적용 가능한 모든 모범 사례를 Microsoft ID 플랫폼 준수하나요?  | 예 |
| 앱에서 인증에 MSAL(Microsoft 인증 라이브러리)을 사용하나요? | 예 |
| 앱에서 조건부 액세스 정책을 지원하나요? | 아니요 |
| 앱에서 시나리오에 대한 최소 권한 권한을 요청하나요? | 예 |
| 앱의 정적으로 등록된 사용 권한은 앱이 동적으로 그리고 증분적으로 요청하는 권한을 정확하게 반영하나요? | 아니요 |
| 앱에서 다중 테넌시를 지원하나요? | 예 |
| 앱에 기밀 클라이언트가 있나요? | 예 |
| 앱에 등록된 리디렉션 URI(통합 리소스 식별자)를 모두 소유하고 있나요? | 예 |
| 앱에서 웹 API를 노출하나요? | 예 |
| 사용 권한 모델에서 클라이언트 앱이 적절한 동의를 받은 경우 통화 성공만 허용하나요? | 예 |
| 앱에서 미리 보기 API를 사용하나요? | 예 |
| 앱에서 사용되지 않는 API를 사용하나요? | 아니요 |

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end
