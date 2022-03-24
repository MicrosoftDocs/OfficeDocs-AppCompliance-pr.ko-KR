---
title: LiveTiles로 도달에 대한 응용 프로그램 정보
ms.author: elmalova
author: elenamalova
manager: tonybal
ms.date: 04/19/2021
ms.topic: article
ms.service: attestation
certification_type: attested
description: Reach에 사용할 수 있는 모든 보안 및 규정 준수 정보, 데이터 처리 정책, CSA STAR 레지스트리의 Microsoft Cloud App Security 앱 카탈로그 정보 및 보안/규정 준수 정보
zone_pivot_groups: app-info-data-mcas-identity
ms.openlocfilehash: c58462500079df7f7b8b2736eec9289443df4a4c
ms.sourcegitcommit: 9199fd569c5e7c5dd338abd87428c94798a22352
ms.translationtype: MT
ms.contentlocale: ko-KR
ms.lasthandoff: 03/23/2022
ms.locfileid: "63753739"
---
# <a name="reach"></a>Reach

<p></p>
<img alt="Publisher Attestation: The information on this page is based on a self-assessment report provided by the app developer on the security, compliance, and data handling practices followed by this app. Microsoft makes no guarantees regarding the accuracy of the information." src="../media/attested.png" width="650" />
<p>개발자가 마지막으로 업데이트한 날짜: 2021년 3월 22일</p>

* <a href="https://teams.microsoft.com/l/app/5df8ebd2-bf7b-4fb5-bb35-0bfbf5d10a23" target="_blank">저장소의 Teams 보기</a>
* <a href="https://appsource.microsoft.com/product/office/WA200002045" target="_blank">AppSource의 보기</a>

::: zone pivot="general"

### <a name="general-information"></a>일반 정보

LiveTiles에서 Microsoft에 제공하는 정보:

| **정보** | **응답** |
|:----------------|:-------------|
| 앱 이름 | Reach |
| ID | WA200002045 |
| Office 365 클라이언트 지원 | Microsoft Teams |
| 파트너 회사 이름 | LiveTiles |
| 파트너 웹 사이트의 URL | [https://livetilesglobal.com](https://livetilesglobal.com) |
| 응용 Teams 정보 페이지의 URL입니다. | [https://livetilesglobal.com/products/livetiles-reach/](https://livetilesglobal.com/products/livetiles-reach/) |
| 개인 정보 취급 방침의 URL | [https://livetilesglobal.com/privacy-policy/](https://livetilesglobal.com/privacy-policy/) |
| 사용 약관 URL | [https://livetilesglobal.com/eula/](https://livetilesglobal.com/eula/) |

 [!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="data"

### <a name="how-the-app-handles-data"></a>앱이 데이터를 처리하는 방법

이 정보는 LiveTiles에서 이 앱이 조직 데이터를 수집하고 저장하는 방법 및 앱이 수집하는 데이터를 통해 조직에서 제공하는 컨트롤에 대해 제공됩니다.

#### <a name="data-access-using-microsoft-graph"></a>Microsoft 365를 사용하여 데이터 Graph

이 앱에 [Graph Microsoft 사용자 권한을](https://docs.microsoft.com/graph/permissions-reference) 나열합니다.

>| **사용 권한**  | **사용 권한 유형(위임/ 응용 프로그램)** | **데이터가 수집하나요? 수집의 사당성** | **데이터가 저장되어 있나요? 저장 사정이 있나요?** | **Azure AD 앱 ID** |
>|:----------------|:------------------------------------------------|:--------------------------------------------------------|:--------------------------------------------------|:--------------------|
>| TeamsActivity.Send | application | 없음 | 없음 | [a7c1920d-3ac0-42db-9757-078a2b321fd8 ](../azure/a7c1920d-3ac0-42db-9757-078a2b321fd8.md ) |
>| User.Read | 위임 | User DisplayName, User Email Address, UPN. 사용자가 앱에 로그인하고 로그인한 사용자의 기본 정보(예: 표시 이름)를 받을 수 있도록 허용하는 데 필요합니다. 전자 메일 주소는 전자 메일 알림을 보내는 데 사용됩니다.  | User DisplayName, User Email Address, UPN. 사용자가 앱에 로그인하고 로그인한 사용자의 기본 정보(예: 표시 이름)를 받을 수 있도록 허용하는 데 필요합니다. 전자 메일 주소는 전자 메일 알림을 보내는 데 사용됩니다.  | [d492530a-8cff-481c-90da-9c3c3f1be7da](../azure/d492530a-8cff-481c-90da-9c3c3f1be7da.md) |
>| User.ReadBasic.All | 위임 | User DisplayName, User Email Address, UPN, User Department, User Job Title, User Mobile 전화 Number, User Business 전화 Number, User Office Location. 사용자가 앱(Phonebook) 내에서 다른 사용자를 검색하고 다른 사용자의 기본 프로필 및 연락처 정보를 볼 수 있도록 하는 데 필요합니다.  | 없음 | [d492530a-8cff-481c-90da-9c3c3f1be7da](../azure/d492530a-8cff-481c-90da-9c3c3f1be7da.md) |
>| Directory.Read.All | application | 그룹 구성원 자격, 디렉터리의 AD 그룹. 사용자의 그룹 구성원 자격은 Microsoft 365 API에 대한 호출을 최소화하기 위해 Graph 저장됩니다. 사용자가 Active Directory 그룹을 검색할 수 있도록 하는 데 필요합니다. 또한 응용 프로그램에서 백end의 웹 작업에서 사용자의 AD 그룹 구성원 자격을 확인하려면 이 권한이 필요합니다. | 사용자의 그룹 구성원 자격입니다. 사용자의 그룹 구성원 자격은 Microsoft 365 API에 대한 호출을 최소화하기 위해 Graph 저장됩니다. 사용자가 Active Directory 그룹을 검색할 수 있도록 하는 데 필요합니다. 또한 응용 프로그램에서 백end의 웹 작업에서 사용자의 AD 그룹 구성원 자격을 확인하려면 이 권한이 필요합니다.  | [d492530a-8cff-481c-90da-9c3c3f1be7da ](../azure/d492530a-8cff-481c-90da-9c3c3f1be7da.md ) |
>| User.Read.All | application | 사용자 프로필에서 검색되는 데이터는 앱 내에 지정된 대상 지정 기능 구성에 따라 다릅니다. 앱에서 로그인한 사용자 없이 사용자 프로필을 읽을 수 있도록 허용하는 데 필요합니다. 특정 프로필 속성 값에 따라 정보를 특정 사용자에게 표시하려면 응용 프로그램 내의 정보 대상 지정 기능에 프로필 데이터를 읽어야 합니다.  | 없음 | [d492530a-8cff-481c-90da-9c3c3f1be7da ](../azure/d492530a-8cff-481c-90da-9c3c3f1be7da.md ) |


#### <a name="non-microsoft-services-used"></a>비영구 Microsoft 서비스

앱이 Microsoft가 아닌 서비스로 조직 데이터를 전송하거나 공유하는 경우 앱에서 사용하는 비 Microsoft 서비스, 전송되는 데이터를 나열하고 앱이 이 정보를 전송해야 하는 이유에 대한 사유를 포함합니다.

>| **모든 비 Microsoft 서비스 OII가 다음으로 전송됩니다.** |  **전송되는 OII는 무엇입니까?** | **OII 전송의 사당성** |
>|:-----------------------------------------------------|:------------------------------|:----------------------------------------|
>| SendGrid, OneSignal | 전자 메일 주소, 표시 이름 | 전자 메일 및 모바일 푸시 알림을 통해 사용자에게 알림 보내기 |

#### <a name="data-access-via-bots"></a>봇을 통한 데이터 액세스

이 앱에 봇 또는 메시징 확장이 포함되어 있는 경우 팀 구성원의 명단(이름, 성, 표시 이름, 전자 메일 주소)이나 팀 구성원이 추가된 채팅의 최종 사용자 식별 정보(EUII)에 액세스할 수 있습니다. 이 앱이 이 기능을 사용하나요?

>EUII에 액세스하지 않습니다.


#### <a name="telemetry-data"></a>원격 분석 데이터

이 응용 프로그램의 원격 분석 또는 로그에 OII(조직 식별 정보) 또는 EUII(최종 사용자 식별 정보)가 나타나나요? 그렇다면 저장되는 데이터와 보존 및 제거 정책에 대해 설명하세요.

>전자 메일 주소 UPN. 최대 60일 보존, 제거된 후

#### <a name="organizational-controls-for-data-stored-by-partner"></a>파트너가 저장한 데이터에 대한 조직 제어

조직의 관리자가 파트너 시스템에서 정보를 제어하는 방법에 대해 설명하는 방법 삭제, 보존, 감사, 보관, 최종 사용자 정책 등

>관리자는 문의에 대해 지원 팀에 문의할 수 있습니다.

#### <a name="human-review-of-organizational-information"></a>조직 정보의 인적 검토

사람이 이 앱에서 수집하거나 저장하는 OII(조직 식별 정보) 데이터를 검토하거나 분석하는 데 관여하나요?

>아니오

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="mcas"

Microsoft Cloud App Security [카탈로그의](https://www.microsoft.com/enterprise-mobility-security/cloud-app-security) 정보가 아래에 표시됩니다.

<iframe height='1020' title='Microsoft Cloud App Security 정보' src='https://appmcasinfoprod.azurewebsites.net/#/dashboard/36551' frameborder='no' style='width: 100%;'></iframe>

<a href="https://appmcasinfoprod.azurewebsites.net/#/dashboard/36551" target="_blank">새 탭에서 보기</a>

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="identity"

### <a name="identity-information"></a>ID 정보

이 정보는 LiveTiles에서 이 앱이 인증, 권한 부여, 응용 프로그램 등록 모범 사례 및 기타 ID 조건을 처리하는 방법에 대해 제공했습니다.

| **정보** | **응답** |
|:----------------|:-------------|
| Microsoft Identify Platform(Azure AD)과 통합하나요?  | 예 |
| 통합 검사 목록에 설명된 적용 가능한 모든 모범 사례를 Microsoft ID 플랫폼 준수하나요?  | 아니오 |
| 앱에서 인증에 MSAL(Microsoft 인증 라이브러리)을 사용하나요? | 예 |
| 앱에서 조건부 액세스 정책을 지원하나요? | 예 |
| 지원되는 정책 유형 나열 | 다단계 인증, 사용자 위치 및 IP 범위 제한 |
| 앱에서 시나리오에 대한 최소 권한 권한을 요청하나요? | 예 |
| 앱의 정적으로 등록된 사용 권한은 앱이 동적으로 그리고 증분적으로 요청하는 권한을 정확하게 반영하나요? | 예 |
| 앱에서 다중 테넌시를 지원하나요? | 예 |
| 앱에 기밀 클라이언트가 있나요? | 아니오 |
| 앱에 등록된 리디렉션 URI(통합 리소스 식별자)를 모두 소유하고 있나요? | 예 |
| 앱의 경우 어떻게 사용하지 않도록 해야 하나요? | - 와일드카드 리디렉션 URIS,<br/>- OAuth2 암시적 Flow SPA에 필요하지 않은 경우<br/>- 리소스 소유자 암호 자격 증명(ROPC) 흐름 |
| 앱에서 웹 API를 노출하나요? | 예 |
| 사용 권한 모델에서 클라이언트 앱이 적절한 동의를 받은 경우 통화 성공만 허용하나요? | 예 |
| 앱에서 미리 보기 API를 사용하나요? | 예 |
| 앱에서 사용되지 않는 API를 사용하나요? | 아니요 |

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end
