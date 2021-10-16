---
title: 파일럿 AS로 InCaseIT에 대한 응용 프로그램 정보
ms.author: elmalova
author: elenamalova
ms.date: 09/20/2021
ms.topic: article
ms.service: attestation
certification_type: attested
description: InCaseIT, 데이터 처리 정책, CSA STAR 레지스트리의 Microsoft Cloud App Security 앱 카탈로그 정보 및 보안/규정 준수 정보에 대해 사용 가능한 모든 보안 및 규정 준수 정보
zone_pivot_groups: app-info-data-identity
ms.openlocfilehash: 22e675ac91be216175d16271e1f0d2f7339fc36b
ms.sourcegitcommit: 9dab9c9dacb9c6daaa6b0041ccc8a49bafdad331
ms.translationtype: MT
ms.contentlocale: ko-KR
ms.lasthandoff: 10/16/2021
ms.locfileid: "60414985"
---
# <a name="incaseit"></a>InCaseIT

<p></p>
<img alt="Publisher Attestation: The information on this page is based on a self-assessment report provided by the app developer on the security, compliance, and data handling practices followed by this app. Microsoft makes no guarantees regarding the accuracy of the information." src="../media/attested.png" width="650" />
<p>개발자가 마지막으로 업데이트한 날짜: 2021년 8월 3일</p>

* <a href="https://teams.microsoft.com/l/app/4420b597-c1d5-4d40-ba81-2b2a78575c81" target="_blank">저장소의 Teams 보기</a>
* <a href="https://appsource.microsoft.com/product/office/WA200003265" target="_blank">AppSource의 보기</a>

::: zone pivot="general"

### <a name="general-information"></a>일반 정보

Pilotech AS에서 Microsoft에 제공한 정보:

| **정보** | **응답** |
|:----------------|:-------------|
| 앱 이름 | InCaseIT |
| ID | WA200003265 |
| Office 365 클라이언트 지원 | Microsoft Teams |
| 파트너 회사 이름 | Pilotech AS |
| 파트너 웹 사이트의 URL | [https://incaseit.com](https://incaseit.com) |
| 응용 프로그램 Teams 페이지의 URL입니다. | [https://www.manula.com/manuals/pilotech-as/incaseit2/1/en/t...](https://www.manula.com/manuals/pilotech-as/incaseit2/1/en/topic/introduction-to-incaseit-version-2-0) |
| 개인 정보 취급 방침의 URL | [https://www.incaseit.com/privacy-policy/](https://www.incaseit.com/privacy-policy/) |
| 사용 약관 URL | [https://www.manula.com/manuals/pilotech-as/incaseit2/1/en/t...](https://www.manula.com/manuals/pilotech-as/incaseit2/1/en/topic/1-4-terms-of-use) |

 [!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="data"

### <a name="how-the-app-handles-data"></a>앱이 데이터를 처리하는 방법

이 정보는 이 앱이 조직 데이터를 수집하고 저장하는 방법 및 앱이 수집하는 데이터를 통해 조직이 제어할 수 있는 제어에 대해 파일럿ch AS에서 제공했습니다.

#### <a name="data-access-using-microsoft-graph"></a>Microsoft 365를 사용한 데이터 Graph

이 앱에 [Graph Microsoft 사용자 권한을](https://docs.microsoft.com/graph/permissions-reference) 나열합니다.

>| **사용 권한**  | **사용 권한 유형(위임/ 응용 프로그램)** | **데이터가 수집하나요? 수집의 사당성** | **데이터가 저장되어 있나요? 저장 사정이 있나요?** | **Azure AD 앱 ID** |
>|:----------------|:------------------------------------------------|:--------------------------------------------------------|:--------------------------------------------------|:--------------------|
>| Calendars.ReadWrite | 위임 | 사용자가 액세스 토큰을 사용하여 응용 프로그램 API를 호출할 수 있도록 사용자가 명시적으로 Graph 데이터뿐입니다. | 이 응용 프로그램은 사용자가 쉽게 모임에 접근할 수 있도록 예약된 모임에 대한 링크만 저장합니다.  예제. 1. 예약된 모임 Teams 만들기 2. 데이터베이스 3에 모임 링크를 저장합니다. 모임에 쉽게 액세스할 수 있도록 응용 프로그램의 단추에 모임 링크를 사용하세요. | [9af6eceb-6a8b-4710-b51d-dde2ac01cc71](https://docs.microsoft.com/microsoft-365-app-certification/azure/9af6eceb-6a8b-4710-b51d-dde2ac01cc71) |
>| OnlineMeetings.ReadWrite | 위임 | 사용자가 액세스 토큰을 사용하여 응용 프로그램 API를 호출할 수 있도록 사용자가 명시적으로 Graph 데이터뿐입니다. | 응용 프로그램은 사용자가 쉽게 모임에 접근할 수 있도록 온라인 모임 링크만 저장합니다.  예제. 1. 온라인 Teams 만들기 2. 데이터베이스 3에 모임 링크를 저장합니다. 모임에 쉽게 액세스할 수 있도록 응용 프로그램의 단추에 모임 링크를 사용하세요. | [9af6eceb-6a8b-4710-b51d-dde2ac01cc71](https://docs.microsoft.com/microsoft-365-app-certification/azure/9af6eceb-6a8b-4710-b51d-dde2ac01cc71) |
>| User.Read | 위임 | 사용자가 액세스 토큰을 사용하여 응용 프로그램 API를 호출할 수 있도록 사용자가 명시적으로 Graph 데이터뿐입니다. | User.Read 권한이 있는 데이터는 저장되지 않습니다. | [9af6eceb-6a8b-4710-b51d-dde2ac01cc71](https://docs.microsoft.com/microsoft-365-app-certification/azure/9af6eceb-6a8b-4710-b51d-dde2ac01cc71) |


#### <a name="non-microsoft-services-used"></a>비영구 Microsoft 서비스

앱이 Microsoft가 아닌 서비스로 조직 데이터를 전송하거나 공유하는 경우 앱에서 사용하는 비 Microsoft 서비스, 전송되는 데이터를 나열하고 앱이 이 정보를 전송해야 하는 이유에 대한 사유를 포함합니다.

>비영구 Microsoft 서비스 사용되지 않습니다.

#### <a name="data-access-via-bots"></a>봇을 통한 데이터 액세스

이 앱에 봇 또는 메시징 확장이 포함되어 있는 경우 팀 구성원의 명단(이름, 성, 표시 이름, 전자 메일 주소)이나 팀 구성원이 추가된 채팅의 최종 사용자 식별 정보(EUII)에 액세스할 수 있습니다. 이 앱이 이 기능을 사용하나요?

>EUII에 액세스하지 않습니다.


#### <a name="telemetry-data"></a>원격 분석 데이터

이 응용 프로그램의 원격 분석 또는 로그에 OII(조직 식별 정보) 또는 EUII(최종 사용자 식별 정보)가 나타나나요? 그렇다면 저장되는 데이터와 보존 및 제거 정책에 대해 설명하세요.

>EUII는 위기 중에 내부 위기 관리 팀에 통신을 보낼 때 응용 프로그램 로그에 나타날 수 있습니다. 로그 제거 정책은 최대 3개월의 로그를 저장하는 것입니다. 필요한 경우 요청 시 이러한 파일을 삭제할 수 있습니다. 

#### <a name="organizational-controls-for-data-stored-by-partner"></a>파트너가 저장한 데이터에 대한 조직 제어

조직의 관리자가 파트너 시스템에서 정보를 제어하는 방법에 대해 설명하는 방법 삭제, 보존, 감사, 보관, 최종 사용자 정책 등

>데이터 프로세서 및 데이터 하위 프로세서의 위치를 규정하는 GDPR 규정을 준수하는 데 모든 파트너 및 하위 파트너와 데이터 보호 계약이 있습니다.

#### <a name="human-review-of-organizational-information"></a>조직 정보의 인적 검토

사람이 이 앱에서 수집하거나 저장하는 OII(조직 식별 정보) 데이터를 검토하거나 분석하는 데 관여하나요?

>아니요

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end


::: zone pivot="identity"

### <a name="identity-information"></a>ID 정보

이 정보는 이 앱이 인증, 권한 부여, 응용 프로그램 등록 모범 사례 및 기타 ID 조건을 처리하는 방법에 대해 파일럿ch AS에서 제공했습니다.

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
| 앱의 경우 어떻게 사용하지 않도록 해야 하나요? | - 와일드카드 리디렉션 URIS,<br/><br/> |
| 앱에서 웹 API를 노출하나요? | 예 |
| 사용 권한 모델에서 클라이언트 앱이 적절한 동의를 받은 경우 통화 성공만 허용하나요? | 예 |
| 앱에서 미리 보기 API를 사용하나요? | 아니요 |
| 앱에서 사용되지 않는 API를 사용하나요? | 아니요 |

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

