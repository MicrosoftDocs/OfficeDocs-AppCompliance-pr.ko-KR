---
title: 학교 날 헬싱키 Oy의 학교 날 웰링에 대한 응용 프로그램 정보
ms.author: elmalova
author: elenamalova
ms.date: 10/12/2021
ms.topic: article
ms.service: attestation
certification_type: attested
description: School Day Wellbeing, 데이터 처리 정책, CSA STAR 레지스트리의 Microsoft Cloud App Security 앱 카탈로그 정보 및 보안/규정 준수 정보에 사용할 수 있는 모든 보안 및 규정 준수 정보
zone_pivot_groups: app-info-data-identity
ms.openlocfilehash: babc51460ddb23fd19007f2ebfc8ebab00300a69
ms.sourcegitcommit: 9dab9c9dacb9c6daaa6b0041ccc8a49bafdad331
ms.translationtype: MT
ms.contentlocale: ko-KR
ms.lasthandoff: 10/16/2021
ms.locfileid: "60408427"
---
# <a name="school-day-wellbeing"></a>School Day Wellbeing

<p></p>
<img alt="Publisher Attestation: The information on this page is based on a self-assessment report provided by the app developer on the security, compliance, and data handling practices followed by this app. Microsoft makes no guarantees regarding the accuracy of the information." src="../media/attested.png" width="650" />
<p>개발자가 마지막으로 업데이트한 날짜: 2021년 10월 12일</p>

* <a href="https://teams.microsoft.com/l/app/7caaa66b-34b0-4c15-a65d-dba6edf0c8fd" target="_blank">저장소의 Teams 보기</a>
* <a href="https://appsource.microsoft.com/product/office/WA200001430" target="_blank">AppSource의 보기</a>

::: zone pivot="general"

### <a name="general-information"></a>일반 정보

학교 날 Helsinki Oy가 Microsoft에 제공한 정보:

| **정보** | **응답** |
|:----------------|:-------------|
| 앱 이름 | School Day Wellbeing |
| ID | WA200001430 |
| Office 365 클라이언트 지원 | Microsoft Teams |
| 파트너 회사 이름 | School Day Helsinki Oy |
| 파트너 웹 사이트의 URL | [https://www.schoolday.com](https://www.schoolday.com) |
| 응용 프로그램 Teams 페이지의 URL입니다. | [https://www.schoolday.com/en/resources/faq](https://www.schoolday.com/en/resources/faq) |
| 개인 정보 취급 방침의 URL | [https://www.schoolday.com/privacy](https://www.schoolday.com/privacy) |
| 사용 약관 URL | [https://www.schoolday.com/eula](https://www.schoolday.com/eula) |

 [!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="data"

### <a name="how-the-app-handles-data"></a>앱이 데이터를 처리하는 방법

이 정보는 학교 날 Helsinki Oy에서 이 앱이 조직 데이터를 수집하고 저장하는 방법 및 앱이 수집하는 데이터를 통해 조직이 하게 될 컨트롤에 대해 제공됩니다.

#### <a name="data-access-using-microsoft-graph"></a>Microsoft 365를 사용한 데이터 Graph

이 앱에 [Graph Microsoft 사용자 권한을](https://docs.microsoft.com/graph/permissions-reference) 나열합니다.

>| **사용 권한**  | **사용 권한 유형(위임/ 응용 프로그램)** | **데이터가 수집하나요? 수집의 사당성** | **데이터가 저장되어 있나요? 저장 사정이 있나요?** | **Azure AD 앱 ID** |
>|:----------------|:------------------------------------------------|:--------------------------------------------------------|:--------------------------------------------------|:--------------------|
>| GroupMember.Read.All | 위임 | 그룹 이름 및 그룹 구성원 자격 교사인 사용자는 그룹에서 학생을 학교 날에 추가할 수 있습니다. | 그룹 이름, 그룹 구성원. 학교 날의 그룹 이름은 O365 그룹을 기준으로 할 수 있습니다. 그룹 구성원이 학생으로 이 수업에 추가됩니다. | [61dc5e28-775a-4dd0-8990-aaabe3be9e2f](https://docs.microsoft.com/microsoft-365-app-certification/azure/61dc5e28-775a-4dd0-8990-aaabe3be9e2f) |
>| Team.ReadBasic.All | 위임 | 팀 이름은 교사 사용자가 팀과 그룹의 학생을 추가하려는 경우 사용됩니다. | 팀 이름은 학교 날에 저장되지 않습니다. | [61dc5e28-775a-4dd0-8990-aaabe3be9e2f](https://docs.microsoft.com/microsoft-365-app-certification/azure/61dc5e28-775a-4dd0-8990-aaabe3be9e2f) |
>| User.Read | 위임 | 사용자 전자 메일, 이름 및 ID 토큰은 사용자 관리 및 인증에 사용됩니다. | 사용자 전자 메일, 이름 및 토큰은 사용자 관리 및 인증을 위해 저장됩니다. | [61dc5e28-775a-4dd0-8990-aaabe3be9e2f](https://docs.microsoft.com/microsoft-365-app-certification/azure/61dc5e28-775a-4dd0-8990-aaabe3be9e2f) |
>| User.ReadBasic.All | 위임 | 사용자 아바타에 사용할 사용자 프로필 사진입니다. | 사용자 프로필 사진이 저장되지 않습니다. | [61dc5e28-775a-4dd0-8990-aaabe3be9e2f](https://docs.microsoft.com/microsoft-365-app-certification/azure/61dc5e28-775a-4dd0-8990-aaabe3be9e2f) |
>| 전자 메일 | 위임 | 사용자 전자 메일은 계정 인증을 위해 수집됩니다. | 사용자 전자 메일은 계정 만들기 및/또는 인증을 위해 저장됩니다. | [61dc5e28-775a-4dd0-8990-aaabe3be9e2f](https://docs.microsoft.com/microsoft-365-app-certification/azure/61dc5e28-775a-4dd0-8990-aaabe3be9e2f) |
>| offline_access | 위임 | 인증 - 액세스 토큰 새로 고침. 사용자 환경이 매끄럽게 진행됩니다. | 인증을 위한 액세스 토큰입니다. | [61dc5e28-775a-4dd0-8990-aaabe3be9e2f](https://docs.microsoft.com/microsoft-365-app-certification/azure/61dc5e28-775a-4dd0-8990-aaabe3be9e2f) |
>| openid | 위임 | OpenID 로그인에 대한 사용자의 고유 식별자입니다.  | 사용자의 고유 식별자는 인증을 위해 저장됩니다. | [61dc5e28-775a-4dd0-8990-aaabe3be9e2f](https://docs.microsoft.com/microsoft-365-app-certification/azure/61dc5e28-775a-4dd0-8990-aaabe3be9e2f) |
>| 프로필 | 위임 | 사용자 관리 및 인증을 위해 기본 설정 사용자 이름 및 개체 ID입니다. | 사용자 관리 및 인증을 위한 개체 ID입니다. | [61dc5e28-775a-4dd0-8990-aaabe3be9e2f](https://docs.microsoft.com/microsoft-365-app-certification/azure/61dc5e28-775a-4dd0-8990-aaabe3be9e2f) |

#### <a name="data-access-using-other-microsoft-apis"></a>다른 Microsoft API를 사용한 데이터 액세스

기본 제공 앱 및 추가 Microsoft 365 Microsoft Graph 기타 Microsoft API를 사용하여 OII(조직 식별 가능 정보)를 수집하거나 처리합니다. 이 앱에서 사용하는 Microsoft API를 Graph Microsoft API를 나열합니다.

>| **API** |  **OII가 수집하나요?** |  **수집되는 OII는 무엇입니까?** | **OII 수집의 사당성** | **OII가 저장되어 있나요?** | **OII 저장의 사당성** |
>|:--------|:-----------------------|:----------------------------|:--------------------------------------|:-------------------|:-----------------------------------|
>| 몰입형 리더 | 아니요 |  |  |  |  |

#### <a name="non-microsoft-services-used"></a>비영구 Microsoft 서비스

앱이 Microsoft가 아닌 서비스로 조직 데이터를 전송하거나 공유하는 경우 앱에서 사용하는 비 Microsoft 서비스, 전송되는 데이터를 나열하고 앱이 이 정보를 전송해야 하는 이유에 대한 사유를 포함합니다.

>비영구 Microsoft 서비스 사용되지 않습니다.

#### <a name="data-access-via-bots"></a>봇을 통한 데이터 액세스

이 앱에 봇 또는 메시징 확장이 포함되어 있는 경우 팀 구성원의 명단(이름, 성, 표시 이름, 전자 메일 주소)이나 팀 구성원이 추가된 채팅의 최종 사용자 식별 정보(EUII)에 액세스할 수 있습니다. 이 앱이 이 기능을 사용하나요?

>EUII에 액세스하지 않습니다.


#### <a name="telemetry-data"></a>원격 분석 데이터

이 응용 프로그램의 원격 분석 또는 로그에 OII(조직 식별 정보) 또는 EUII(최종 사용자 식별 정보)가 나타나나요? 그렇다면 저장되는 데이터와 보존 및 제거 정책에 대해 설명하세요.

>사용자 계정, 그룹 사용자가 속해 있는 그룹, 웰웰링 질문 응답 데이터. 계정이 삭제되면 90일 이내에 데이터가 제거됩니다.

#### <a name="organizational-controls-for-data-stored-by-partner"></a>파트너가 저장한 데이터에 대한 조직 제어

조직의 관리자가 파트너 시스템에서 정보를 제어하는 방법에 대해 설명하는 방법 삭제, 보존, 감사, 보관, 최종 사용자 정책 등

>조직 관리자는 학교 날 관리자 도구를 통해 CRUD(데이터)를 제어할 수 있습니다. 

#### <a name="human-review-of-organizational-information"></a>조직 정보의 인적 검토

사람이 이 앱에서 수집하거나 저장하는 OII(조직 식별 정보) 데이터를 검토하거나 분석하는 데 관여하나요?

>예

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end


::: zone pivot="identity"

### <a name="identity-information"></a>ID 정보

이 정보는 학교 날 Helsinki Oy에서 이 앱이 인증, 권한 부여, 응용 프로그램 등록 모범 사례 및 기타 ID 기준을 처리하는 방법에 대해 제공했습니다.

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
| 앱의 경우 어떻게 사용하지 않도록 해야 하나요? | - 와일드카드 리디렉션 URIS,<br/>- OAuth2 암시적 Flow SPA에 필요하지 않은 경우<br/>- 리소스 소유자 암호 자격 증명(ROPC) 흐름 |
| 앱에서 웹 API를 노출하나요? | 아니요 |
| 앱에서 미리 보기 API를 사용하나요? | 아니요 |
| 앱에서 사용되지 않는 API를 사용하나요? | 아니요 |

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

