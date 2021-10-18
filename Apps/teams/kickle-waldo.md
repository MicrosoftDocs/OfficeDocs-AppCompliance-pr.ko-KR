---
title: Kickle의 Waldo에 대한 응용 프로그램 정보
ms.author: elmalova
author: elenamalova
ms.date: 08/26/2021
ms.topic: article
ms.service: attestation
certification_type: attested
description: Waldo에 사용할 수 있는 모든 보안 및 규정 준수 정보, 데이터 처리 정책, CSA STAR 레지스트리의 Microsoft Cloud App Security 앱 카탈로그 정보 및 보안/규정 준수 정보
zone_pivot_groups: app-info-data-identity
ms.openlocfilehash: 88766f29eb80c8d9378fc117b42e688db3dff755
ms.sourcegitcommit: 983ed1755036e92d99745770f82f33417b21efec
ms.translationtype: MT
ms.contentlocale: ko-KR
ms.lasthandoff: 10/18/2021
ms.locfileid: "60434587"
---
# <a name="waldo"></a>Waldo

<p></p>
<img alt="Publisher Attestation: The information on this page is based on a self-assessment report provided by the app developer on the security, compliance, and data handling practices followed by this app. Microsoft makes no guarantees regarding the accuracy of the information." src="../media/attested.png" width="650" />
<p>개발자가 마지막으로 업데이트한 날짜: 2021년 6월 30일</p>

* <a href="https://teams.microsoft.com/l/app/1d041f16-ab49-4627-bfda-6b60ad2cab6a" target="_blank">저장소의 Teams 보기</a>
* <a href="https://appsource.microsoft.com/product/office/WA200003139" target="_blank">AppSource의 보기</a>

::: zone pivot="general"

### <a name="general-information"></a>일반 정보

Microsoft에 대해 Kickle에서 제공하는 정보:

| **정보** | **응답** |
|:----------------|:-------------|
| 앱 이름 | Waldo |
| ID | WA200003139 |
| Office 365 클라이언트 지원 | Microsoft Teams |
| 파트너 회사 이름 | Kickle |
| 파트너 웹 사이트의 URL | [https://hellowaldo.app](https://hellowaldo.app) |
| 응용 프로그램 Teams 페이지의 URL입니다. | [https://hellowaldo.app/takeatour/](https://hellowaldo.app/takeatour/) |
| 개인 정보 취급 방침의 URL | [https://hellowaldo.app/privacy-policy/](https://hellowaldo.app/privacy-policy/) |
| 사용 약관 URL | [https://hellowaldo.app/terms-and-conditions](https://hellowaldo.app/terms-and-conditions) |

 [!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="data"

### <a name="how-the-app-handles-data"></a>앱이 데이터를 처리하는 방법

이 정보는 이 앱이 조직 데이터를 수집 및 저장하는 방법 및 앱이 수집하는 데이터를 통해 조직이 하게 될 컨트롤에 대해 Kickle에서 제공했습니다.

#### <a name="data-access-using-microsoft-graph"></a>Microsoft 365를 사용한 데이터 Graph

이 앱에 [Graph Microsoft 사용자 권한을](https://docs.microsoft.com/graph/permissions-reference) 나열합니다.

>| **사용 권한**  | **사용 권한 유형(위임/ 응용 프로그램)** | **데이터가 수집하나요? 수집의 사당성** | **데이터가 저장되어 있나요? 저장 사정이 있나요?** | **Azure AD 앱 ID** |
>|:----------------|:------------------------------------------------|:--------------------------------------------------------|:--------------------------------------------------|:--------------------|
>| Chat.ReadBasic | 위임 | 채팅 기록에 따라 Waldo는 동료를 식별합니다. 이 목록은 이후에 달력 보기의 상태를 표시하는 데 사용됩니다. | Waldo에는 각 동료의 사용자 ID가 저장됩니다. 이러한 ID는 함께 작업하는 데 사용되는 동료 목록을 표시하는 데 사용됩니다. | [c71a6f53-cf0c-426d-a826-cedae8b073f7](https://docs.microsoft.com/microsoft-365-app-certification/azure/c71a6f53-cf0c-426d-a826-cedae8b073f7) |
>| User.Read | 위임 | 이 사용 권한은 Microsoft 365의 구성 요소 사용자가 Graph Toolkit | 해당 없음 | [c71a6f53-cf0c-426d-a826-cedae8b073f7](https://docs.microsoft.com/microsoft-365-app-certification/azure/c71a6f53-cf0c-426d-a826-cedae8b073f7) |
>| User.ReadBasic.All | 위임 | 이 사용 권한은 Microsoft 365의 구성 요소 사용자가 Graph Toolkit | 해당 없음 | [c71a6f53-cf0c-426d-a826-cedae8b073f7](https://docs.microsoft.com/microsoft-365-app-certification/azure/c71a6f53-cf0c-426d-a826-cedae8b073f7) |
>| offline_access | 위임 | 앱에서 사용자를 대신하여 백그라운드 작업을 수행하는 데 사용됩니다(인증 토큰 갱신). | 해당 없음 | [c71a6f53-cf0c-426d-a826-cedae8b073f7](https://docs.microsoft.com/microsoft-365-app-certification/azure/c71a6f53-cf0c-426d-a826-cedae8b073f7) |
>| openid | 위임 | 인증에 필요 | 해당 없음 | [c71a6f53-cf0c-426d-a826-cedae8b073f7](https://docs.microsoft.com/microsoft-365-app-certification/azure/c71a6f53-cf0c-426d-a826-cedae8b073f7) |


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

>조직은 에서 Waldo 관리자, 관리 연락처 및 기술 담당자를 볼 수 https://app.hellowaldo.app/admin-orga-contacts 있습니다.  조직은 에 문의하여 hello@kickle.com 개인 식별 정보를 제거할 수 있습니다. 이 경우 제공할 수 있는 서비스가 제한될 수 있습니다.

#### <a name="human-review-of-organizational-information"></a>조직 정보의 인적 검토

사람이 이 앱에서 수집하거나 저장하는 OII(조직 식별 정보) 데이터를 검토하거나 분석하는 데 관여하나요?

>아니요

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end


::: zone pivot="identity"

### <a name="identity-information"></a>ID 정보

이 정보는 앱이 인증, 권한 부여, 응용 프로그램 등록 모범 사례 및 기타 ID 조건을 처리하는 방법에 대해 Kickle에서 제공했습니다.

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
| 앱의 경우 어떻게 사용하지 않도록 해야 하나요? | - 와일드카드 리디렉션 URIS,<br/>- OAuth2 암시적 Flow SPA에 필요하지 않은 경우<br/>- 리소스 소유자 암호 자격 증명(ROPC) 흐름 |
| 앱에서 웹 API를 노출하나요? | 예 |
| 사용 권한 모델에서 클라이언트 앱이 적절한 동의를 받은 경우 통화 성공만 허용하나요? | 예 |
| 앱에서 미리 보기 API를 사용하나요? | 아니요 |
| 앱에서 사용되지 않는 API를 사용하나요? | 아니요 |

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end
