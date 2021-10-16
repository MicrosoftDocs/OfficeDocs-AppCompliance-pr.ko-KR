---
title: 임시로 작업 시간 인텔리전스에 대한 응용 프로그램 정보
ms.author: elmalova
author: elenamalova
ms.date: 09/24/2021
ms.topic: article
ms.service: attestation
certification_type: attested
description: CSA STAR 레지스트리의 Workbench 인텔리전스, 데이터 처리 정책, Microsoft Cloud App Security 앱 카탈로그 정보 및 보안/규정 준수 정보에 대해 사용 가능한 모든 보안 및 규정 준수 정보입니다.
zone_pivot_groups: app-info-data-identity
ms.openlocfilehash: 7adf907a083a4fcf5c7c57fe0cf048ba771d0d6e
ms.sourcegitcommit: 9dab9c9dacb9c6daaa6b0041ccc8a49bafdad331
ms.translationtype: MT
ms.contentlocale: ko-KR
ms.lasthandoff: 10/16/2021
ms.locfileid: "60414434"
---
# <a name="workbench-intelligence"></a>Workbench Intelligence

<p></p>
<img alt="Publisher Attestation: The information on this page is based on a self-assessment report provided by the app developer on the security, compliance, and data handling practices followed by this app. Microsoft makes no guarantees regarding the accuracy of the information." src="../media/attested.png" width="650" />
<p>개발자가 마지막으로 업데이트한 날짜: 2021년 9월 22일</p>

* <a href="https://teams.microsoft.com/l/app/d5630318-189a-4912-abae-99b1f8f82cce" target="_blank">저장소의 Teams 보기</a>
* <a href="https://appsource.microsoft.com/product/office/WA200002705" target="_blank">AppSource의 보기</a>

::: zone pivot="general"

### <a name="general-information"></a>일반 정보

Temporall에서 Microsoft에 제공하는 정보:

| **정보** | **응답** |
|:----------------|:-------------|
| 앱 이름 | Workbench Intelligence |
| ID | WA200002705 |
| Office 365 클라이언트 지원 | Microsoft Teams |
| 파트너 회사 이름 | Temporall |
| 파트너 웹 사이트의 URL | [https://www.temporall.com](https://www.temporall.com) |
| 응용 프로그램 Teams 페이지의 URL입니다. | [https://www.temporall.com/teams_intelligence/](https://www.temporall.com/teams_intelligence/) |
| 개인 정보 취급 방침의 URL | [https://temporall.com/privacy-policy/](https://temporall.com/privacy-policy/) |
| 사용 약관 URL | [https://www.temporall.com/eula](https://www.temporall.com/eula) |

 [!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="data"

### <a name="how-the-app-handles-data"></a>앱이 데이터를 처리하는 방법

이 정보는 Temporall에서 이 앱이 조직 데이터를 수집하고 저장하는 방법 및 앱이 수집하는 데이터를 통해 조직에서 사용할 컨트롤에 대해 제공됩니다.

#### <a name="data-access-using-microsoft-graph"></a>Microsoft 365를 사용한 데이터 Graph

이 앱에 [Graph Microsoft 사용자 권한을](https://docs.microsoft.com/graph/permissions-reference) 나열합니다.

>| **사용 권한**  | **사용 권한 유형(위임/ 응용 프로그램)** | **데이터가 수집하나요? 수집의 사당성** | **데이터가 저장되어 있나요? 저장 사정이 있나요?** | **Azure AD 앱 ID** |
>|:----------------|:------------------------------------------------|:--------------------------------------------------------|:--------------------------------------------------|:--------------------|
>| AppCatalog.Read.All | 위임 | 알려진 외부 ID에 대한 로컬 앱 ID를 얻을 수 있게 설치된 팀 앱 목록을 얻습니다. | 로컬 앱 ID입니다. 다른 테넌트에 설치할 때 앱을 식별할 수 있는 데 필요합니다. | [d5630318-189a-4912-abae-99b1f8f82cce](https://docs.microsoft.com/microsoft-365-app-certification/azure/d5630318-189a-4912-abae-99b1f8f82cce) |
>| Channel.ReadBasic.All | application | 채널 ID &amp; 이름입니다. 사명: 채널에 참가/나가서 메시지 활동을 동기화하도록 허용합니다.  | 채널을 통해 반환되는 원시 데이터 개체입니다. 사유: Temporall Workbench를 사용하면 채널에 따라 데이터를 필터링하고 분류할 수 있습니다. 이 원시 데이터는 원본 개체에 대한 참조를 들이기 위해 저장됩니다. | [d5630318-189a-4912-abae-99b1f8f82cce](https://docs.microsoft.com/microsoft-365-app-certification/azure/d5630318-189a-4912-abae-99b1f8f82cce) |
>| ChannelMessage.Read.All | application | 보낸 사람 대상과 함께 메시지 &amp; 활동 &amp; 유형입니다. /teams/${teamId}/channels/${channelId}/messages /teams/${teamId}/channels/${channelId}/messages/${messageId}. 정당성: 메시지 활동에 대한 메트릭 보고서를 &amp; 계산할 수 있습니다. 이는 사용자 팀 간의 활동 다이어그램을 그릴 수 있도록 관리 네트워크 분석 모듈의 &amp; 핵심입니다. | 반환된 원시 메시지 개체와 함께 이러한 메트릭을 저장하는 새 메시지/답장/반응/ 언급의 &amp; 양을 검색합니다. 데이터는 핵심 기능의 일부로 형성되는 데 필요합니다. 메시지 데이터에 대한 분석을 실행하려면 최적의 성능을 위해 데이터베이스에 저장해야 합니다. 따라서 동일한 데이터에 대한 후속 호출도 줄일 수 있습니다. | [d5630318-189a-4912-abae-99b1f8f82cce](https://docs.microsoft.com/microsoft-365-app-certification/azure/d5630318-189a-4912-abae-99b1f8f82cce) |
>| Directory.Read.All | application | ClientId, 사용자 목록, 조직 및 하위 채널 목록 사유: Temporall Workbench에 동기화 사용자를 읽는 &amp; 데 필요 | 사용자 이름, 전자 메일, 아이콘, 대화 참조. Justification:&#160;Temporall Workbench를 사용하면 채널에 따라 데이터를 필터링하고 분류할 수 있습니다. 설치 후 팀에 다시 연결하기 위해 조직 데이터가 저장됩니다. | [d5630318-189a-4912-abae-99b1f8f82cce](https://docs.microsoft.com/microsoft-365-app-certification/azure/d5630318-189a-4912-abae-99b1f8f82cce) |
>| Group.ReadWrite.All | application | 그룹 ID &amp; 이름입니다. 사당성: 각 그룹/채널에 앱을 설치하려면 | 참조할 원시 데이터 개체와 함께 그룹 ID &amp; 이름입니다. 사유: Temporall Workbench를 사용하면 그룹/팀에 따라 데이터를 필터링하고 분류할 수 있습니다. 이 원시 데이터는 원본 개체에 대한 참조를 들이기 위해 저장됩니다. | [d5630318-189a-4912-abae-99b1f8f82cce](https://docs.microsoft.com/microsoft-365-app-certification/azure/d5630318-189a-4912-abae-99b1f8f82cce) |
>| TeamMember.Read.All | application | 팀의 사용자 구성원 자격입니다. 사유: Temporall Workbench와 Teams 모든 사용자 동기화 허용 | 전자 메일 주소, 이름 및 성 사유: 전자 메일로 사용자 동기화를 허용하기 위해 Temporall Workbench의 사용자와 팀의 사용자 일치를 허용합니다. | [d5630318-189a-4912-abae-99b1f8f82cce](https://docs.microsoft.com/microsoft-365-app-certification/azure/d5630318-189a-4912-abae-99b1f8f82cce) |
>| TeamsAppInstallation.ReadWriteForTeam.All | application | 팀에 대해 설치된 앱 목록을 읽습니다. 사유: 앱이 이미 설치되어 있는 경우 그래프 api를 통해 메시지 활동을 얻을 수 있도록 앱을 설치합니다. | 해당 없음 | [d5630318-189a-4912-abae-99b1f8f82cce](https://docs.microsoft.com/microsoft-365-app-certification/azure/d5630318-189a-4912-abae-99b1f8f82cce) |
>| TeamsAppInstallation.ReadWriteForUser.All | application | 설치된 앱 목록을 읽습니다. 앱이 이미 설치되어 있는 경우 설문지에서 사용자 참여를 유도하도록 앱을 설치하는지 확인합니다. | 해당 없음 | [d5630318-189a-4912-abae-99b1f8f82cce](https://docs.microsoft.com/microsoft-365-app-certification/azure/d5630318-189a-4912-abae-99b1f8f82cce) |
>| User.Read | 위임 | 기본 사용자 &amp; 회사 정보입니다. 사유: 사용자별로 메시지 활동을 분류하는 데 사용되어 봇이 사전 메시징에 참여할 수 있습니다. | 사용자 이름, 전자 메일, 아이콘, 대화 참조. 사유: 봇에서 관련 정보를 사용하여 사용자에게 메시지를 사전적으로 보낼 수 있도록 허용합니다. 데이터 표시를 위해 사용자 그룹화 | [d5630318-189a-4912-abae-99b1f8f82cce](https://docs.microsoft.com/microsoft-365-app-certification/azure/d5630318-189a-4912-abae-99b1f8f82cce) |


#### <a name="non-microsoft-services-used"></a>비영구 Microsoft 서비스

앱이 Microsoft가 아닌 서비스로 조직 데이터를 전송하거나 공유하는 경우 앱에서 사용하는 비 Microsoft 서비스, 전송되는 데이터를 나열하고 앱이 이 정보를 전송해야 하는 이유에 대한 사유를 포함합니다.

>| **모든 비 Microsoft 서비스 OII가 다음으로 전송됩니다.** |  **전송되는 OII는 무엇입니까?** | **OII 전송의 사당성** |
>|:-----------------------------------------------------|:------------------------------|:----------------------------------------|
>| Google Cloud | LDAP 정보 | 플랫폼은 Google 클라우드 플랫폼에 있습니다. |

#### <a name="data-access-via-bots"></a>봇을 통한 데이터 액세스

이 앱에 봇 또는 메시징 확장이 포함되어 있는 경우 팀 구성원의 명단(이름, 성, 표시 이름, 전자 메일 주소)이나 팀 구성원이 추가된 채팅의 최종 사용자 식별 정보(EUII)에 액세스할 수 있습니다. 이 앱이 이 기능을 사용하나요?

>EUII에 액세스하지 않습니다.


#### <a name="telemetry-data"></a>원격 분석 데이터

이 응용 프로그램의 원격 분석 또는 로그에 OII(조직 식별 정보) 또는 EUII(최종 사용자 식별 정보)가 나타나나요? 그렇다면 저장되는 데이터와 보존 및 제거 정책에 대해 설명하세요.

>응용 프로그램 원격 분석 또는 로그에 OII 또는 EUII가 나타나지 않습니다.

#### <a name="organizational-controls-for-data-stored-by-partner"></a>파트너가 저장한 데이터에 대한 조직 제어

조직의 관리자가 파트너 시스템에서 정보를 제어하는 방법에 대해 설명하는 방법 삭제, 보존, 감사, 보관, 최종 사용자 정책 등

>https://temporall.com/privacy-policy/

#### <a name="human-review-of-organizational-information"></a>조직 정보의 인적 검토

사람이 이 앱에서 수집하거나 저장하는 OII(조직 식별 정보) 데이터를 검토하거나 분석하는 데 관여하나요?

>예

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end


::: zone pivot="identity"

### <a name="identity-information"></a>ID 정보

이 정보는 Temporall에서 이 앱이 인증, 권한 부여, 응용 프로그램 등록 모범 사례 및 기타 ID 조건을 처리하는 방법에 대해 제공했습니다.

| **정보** | **응답** |
|:----------------|:-------------|
| Microsoft Identify Platform(Azure AD)과 통합하나요?  | 예 |
| 통합 검사 목록에 설명된 적용 가능한 모든 모범 사례를 Microsoft ID 플랫폼 준수하나요?  | 예 |
| 앱에서 인증에 MSAL(Microsoft 인증 라이브러리)을 사용하나요? | 예 |
| 앱에서 조건부 액세스 정책을 지원하나요? | 아니요 |
| 앱에서 시나리오에 대한 최소 권한 권한을 요청하나요? | 예 |
| 앱의 정적으로 등록된 사용 권한은 앱이 동적으로 그리고 증분적으로 요청하는 권한을 정확하게 반영하나요? | 예 |
| 앱에서 다중 테넌시를 지원하나요? | 예 |
| 앱에 기밀 클라이언트가 있나요? | 예 |
| 앱에 등록된 리디렉션 URI(통합 리소스 식별자)를 모두 소유하고 있나요? | 예 |
| 앱의 경우 어떻게 사용하지 않도록 해야 하나요? | - 와일드카드 리디렉션 URIS,<br/>- OAuth2 암시적 Flow SPA에 필요하지 않은 경우<br/>- 리소스 소유자 암호 자격 증명(ROPC) 흐름 |
| 앱에서 웹 API를 노출하나요? | 아니요 |
| 앱에서 미리 보기 API를 사용하나요? | 예 |
| 앱에서 사용되지 않는 API를 사용하나요? | 아니요 |

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

