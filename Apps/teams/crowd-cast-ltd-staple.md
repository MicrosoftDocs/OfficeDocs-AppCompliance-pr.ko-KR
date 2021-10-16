---
title: 크라우드 캐스트(Ltd.)의 Staple에 대한 응용 프로그램 정보
ms.author: elmalova
author: elenamalova
ms.date: 09/27/2021
ms.topic: article
ms.service: attestation
certification_type: attested
description: Staple, 데이터 처리 정책, CSA STAR 레지스트리의 Microsoft Cloud App Security 앱 카탈로그 정보 및 보안/규정 준수 정보에 사용할 수 있는 모든 보안 및 규정 준수 정보
zone_pivot_groups: app-info-data-identity
ms.openlocfilehash: 9eb6274274c3970b20ebb53d03a163fa79e206df
ms.sourcegitcommit: 9dab9c9dacb9c6daaa6b0041ccc8a49bafdad331
ms.translationtype: MT
ms.contentlocale: ko-KR
ms.lasthandoff: 10/16/2021
ms.locfileid: "60410311"
---
# <a name="staple"></a>Staple

<p></p>
<img alt="Publisher Attestation: The information on this page is based on a self-assessment report provided by the app developer on the security, compliance, and data handling practices followed by this app. Microsoft makes no guarantees regarding the accuracy of the information." src="../media/attested.png" width="650" />
<p>개발자가 마지막으로 업데이트한 날짜: 2021년 9월 27일</p>

* <a href="https://teams.microsoft.com/l/app/ac9ca94a-e666-4f61-959a-12c063e13e69" target="_blank">저장소의 Teams 보기</a>
* <a href="https://appsource.microsoft.com/product/office/WA200003281" target="_blank">AppSource의 보기</a>

::: zone pivot="general"

### <a name="general-information"></a>일반 정보

크라우드 캐스트( Ltd.가 Microsoft에 제공한 정보:

| **정보** | **응답** |
|:----------------|:-------------|
| 앱 이름 | Staple |
| ID | WA200003281 |
| Office 365 클라이언트 지원 | Microsoft Teams |
| 파트너 회사 이름 | Crowd Cast, Ltd. |
| 파트너 웹 사이트의 URL | [https://crowdcast.jp/ja/](https://crowdcast.jp/ja/) |
| 응용 프로그램 Teams 페이지의 URL입니다. | [https://intercom.help/staple/ja](https://intercom.help/staple/ja) |
| 개인 정보 취급 방침의 URL | [https://crowdcast.jp/ja/privacy/](https://crowdcast.jp/ja/privacy/) |
| 사용 약관 URL | [https://go.microsoft.com](https://go.microsoft.com) |

 [!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="data"

### <a name="how-the-app-handles-data"></a>앱이 데이터를 처리하는 방법

이 정보는 크라우드 캐스트( Ltd.)에서 이 앱이 조직 데이터를 수집 및 저장하는 방법 및 앱이 수집하는 데이터를 통해 조직에서 제공하는 컨트롤에 대해 제공됩니다.

#### <a name="data-access-using-microsoft-graph"></a>Microsoft 365를 사용한 데이터 Graph

이 앱에 [Graph Microsoft 사용자 권한을](https://docs.microsoft.com/graph/permissions-reference) 나열합니다.

>| **사용 권한**  | **사용 권한 유형(위임/ 응용 프로그램)** | **데이터가 수집하나요? 수집의 사당성** | **데이터가 저장되어 있나요? 저장 사정이 있나요?** | **Azure AD 앱 ID** |
>|:----------------|:------------------------------------------------|:--------------------------------------------------------|:--------------------------------------------------|:--------------------|
>| Organization.Read.All | application | 테넌트 ID를 수집하는 데 사용됩니다. 플랫폼에서 인증하는 사용자가 특정 테넌트의 구성원이 되도록 하는 데 사용됩니다. | 테넌트 ID입니다. 플랫폼에서 인증하는 사용자가 특정 테넌트의 구성원이 되도록 하는 데 사용됩니다. | [ac9ca94a-e666-4f61-959a-12c063e13e69](https://docs.microsoft.com/microsoft-365-app-certification/azure/ac9ca94a-e666-4f61-959a-12c063e13e69) |
>| TeamsAppInstallation.ReadWriteSelfForUser.All | application | Teams 앱의 사용자 팀에 자체 설치 | 해당 없음 | [ac9ca94a-e666-4f61-959a-12c063e13e69](https://docs.microsoft.com/microsoft-365-app-certification/azure/ac9ca94a-e666-4f61-959a-12c063e13e69) |
>| AppCatalog.Read.All | 위임 | 사용자의 앱 카탈로그를 읽어 Teams 앱이 설치되어 있는지 확인합니다. | 해당 없음 | [bbdcd676-7448-453c-bec7-70e5384bc290](https://docs.microsoft.com/microsoft-365-app-certification/azure/bbdcd676-7448-453c-bec7-70e5384bc290) |
>| User.Read | 위임 | 올바른 사용자에게 메시지를 보내기 위해 사용자의 ID를 읽는 데 사용됩니다. | 사용자에게 사전 메시지를 보내기 위해 저장된 사용자 ID입니다. | [bbdcd676-7448-453c-bec7-70e5384bc290](https://docs.microsoft.com/microsoft-365-app-certification/azure/bbdcd676-7448-453c-bec7-70e5384bc290) |
>| openid | 위임 | 기본 프로필 정보를 읽기 위해 사용자 로그인 | 해당 없음 | [bbdcd676-7448-453c-bec7-70e5384bc290](https://docs.microsoft.com/microsoft-365-app-certification/azure/bbdcd676-7448-453c-bec7-70e5384bc290) |


#### <a name="non-microsoft-services-used"></a>비영구 Microsoft 서비스

앱이 Microsoft가 아닌 서비스로 조직 데이터를 전송하거나 공유하는 경우 앱에서 사용하는 비 Microsoft 서비스, 전송되는 데이터를 나열하고 앱이 이 정보를 전송해야 하는 이유에 대한 사유를 포함합니다.

>비영구 Microsoft 서비스 사용되지 않습니다.

#### <a name="data-access-via-bots"></a>봇을 통한 데이터 액세스

이 앱에 봇 또는 메시징 확장이 포함되어 있는 경우 팀 구성원의 명단(이름, 성, 표시 이름, 전자 메일 주소)이나 팀 구성원이 추가된 채팅의 최종 사용자 식별 정보(EUII)에 액세스할 수 있습니다. 이 앱이 이 기능을 사용하나요?

>EUII에 액세스하지 않습니다.


#### <a name="telemetry-data"></a>원격 분석 데이터

이 응용 프로그램의 원격 분석 또는 로그에 OII(조직 식별 정보) 또는 EUII(최종 사용자 식별 정보)가 나타나나요? 그렇다면 저장되는 데이터와 보존 및 제거 정책에 대해 설명하세요.

>응용 프로그램 원격 분석 또는 로그에 OII 또는 EUII가 나타나지 않습니다.

#### <a name="organizational-controls-for-data-stored-by-partner"></a>파트너가 저장한 데이터에 대한 조직 제어

조직의 관리자가 파트너 시스템에서 정보를 제어하는 방법에 대해 설명하는 방법 삭제, 보존, 감사, 보관, 최종 사용자 정책 등

>조직의 관리자가 파트너 시스템의 데이터를 제어합니다(AWS, Heroku).

#### <a name="human-review-of-organizational-information"></a>조직 정보의 인적 검토

사람이 이 앱에서 수집하거나 저장하는 OII(조직 식별 정보) 데이터를 검토하거나 분석하는 데 관여하나요?

>아니요

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end


::: zone pivot="identity"

### <a name="identity-information"></a>ID 정보

이 정보는 크라우드 캐스트, Ltd.에서 이 앱이 인증, 권한 부여, 응용 프로그램 등록 모범 사례 및 기타 ID 조건을 처리하는 방법에 대해 제공했습니다.

| **정보** | **응답** |
|:----------------|:-------------|
| Microsoft Identify Platform(Azure AD)과 통합하나요?  | 예 |
| 통합 검사 목록에 설명된 적용 가능한 모든 모범 사례를 Microsoft ID 플랫폼 준수하나요?  | 예 |
| 앱에서 인증에 MSAL(Microsoft 인증 라이브러리)을 사용하나요? | 아니요 |
| 앱에서 조건부 액세스 정책을 지원하나요? | 아니요 |
| 앱에서 시나리오에 대한 최소 권한 권한을 요청하나요? | 예 |
| 앱의 정적으로 등록된 사용 권한은 앱이 동적으로 그리고 증분적으로 요청하는 권한을 정확하게 반영하나요? | 예 |
| 앱에서 다중 테넌시를 지원하나요? | 예 |
| 앱에 기밀 클라이언트가 있나요? | 아니요 |
| 앱에 등록된 리디렉션 URI(통합 리소스 식별자)를 모두 소유하고 있나요? | 예 |
| 앱의 경우 어떻게 사용하지 않도록 해야 하나요? | - 와일드카드 리디렉션 URIS,<br/>- OAuth2 암시적 Flow SPA에 필요하지 않은 경우<br/>- 리소스 소유자 암호 자격 증명(ROPC) 흐름 |
| 앱에서 웹 API를 노출하나요? | 예 |
| 사용 권한 모델에서 클라이언트 앱이 적절한 동의를 받은 경우 통화 성공만 허용하나요? | 예 |
| 앱에서 미리 보기 API를 사용하나요? | 아니요 |
| 앱에서 사용되지 않는 API를 사용하나요? | 아니요 |

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

