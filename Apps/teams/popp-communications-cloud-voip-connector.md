---
title: POPP 통신을 통해 POPP 클라우드 VoIP 커넥터에 대한 응용 프로그램 정보
ms.author: elmalova
author: elenamalova
ms.date: 10/01/2021
ms.topic: article
ms.service: attestation
certification_type: attested
description: POPP Cloud VoIP Connector, 데이터 처리 정책, CSA STAR 레지스트리의 Microsoft Cloud App Security 앱 카탈로그 정보 및 보안/규정 준수 정보에 대해 사용할 수 있는 모든 보안 및 규정 준수 정보
zone_pivot_groups: app-info-data-identity
ms.openlocfilehash: 42930c1020e86aeb6f55fb81929f30285e17dae3
ms.sourcegitcommit: 9dab9c9dacb9c6daaa6b0041ccc8a49bafdad331
ms.translationtype: MT
ms.contentlocale: ko-KR
ms.lasthandoff: 10/16/2021
ms.locfileid: "60414975"
---
# <a name="popp-cloud-voip-connector"></a>POPP 클라우드 VoIP 커넥터

<p></p>
<img alt="Publisher Attestation: The information on this page is based on a self-assessment report provided by the app developer on the security, compliance, and data handling practices followed by this app. Microsoft makes no guarantees regarding the accuracy of the information." src="../media/attested.png" width="650" />
<p>개발자가 마지막으로 업데이트한 날짜: 2021년 9월 20일</p>

* <a href="https://teams.microsoft.com/l/app/b8e57f6b-31cf-468e-9e99-81f0395cb1f9" target="_blank">저장소의 Teams 보기</a>
* <a href="https://appsource.microsoft.com/product/office/WA200003306" target="_blank">AppSource의 보기</a>

::: zone pivot="general"

### <a name="general-information"></a>일반 정보

POPP Communications에서 Microsoft에 제공하는 정보:

| **정보** | **응답** |
|:----------------|:-------------|
| 앱 이름 | POPP 클라우드 VoIP 커넥터 |
| ID | WA200003306 |
| Office 365 클라이언트 지원 | Microsoft Teams |
| 파트너 회사 이름 | POPP Communications |
| 파트너 웹 사이트의 URL | [https://popp.com](https://popp.com) |
| 개인 정보 취급 방침의 URL | [https://popp.com/terms/privacy-policy/](https://popp.com/terms/privacy-policy/) |
| 사용 약관 URL | [https://popp.com/pvnterms/](https://popp.com/pvnterms/) |

 [!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="data"

### <a name="how-the-app-handles-data"></a>앱이 데이터를 처리하는 방법

이 정보는 POPP Communications에서 이 앱이 조직 데이터를 수집 및 저장하는 방법 및 조직에서 수집하는 데이터를 통해 조직에서 제공하는 컨트롤에 대해 제공됩니다.

#### <a name="data-access-using-microsoft-graph"></a>Microsoft 365를 사용한 데이터 Graph

이 앱에 [Graph Microsoft 사용자 권한을](https://docs.microsoft.com/graph/permissions-reference) 나열합니다.

>| **사용 권한**  | **사용 권한 유형(위임/ 응용 프로그램)** | **데이터가 수집하나요? 수집의 사당성** | **데이터가 저장되어 있나요? 저장 사정이 있나요?** | **Azure AD 앱 ID** |
>|:----------------|:------------------------------------------------|:--------------------------------------------------------|:--------------------------------------------------|:--------------------|
>| ChannelMember.Read.All | 위임 | 사용자 ID 및 현재 채널의 구성원 이름을 표시합니다. 앱은 이를 사용하여 사용자에게 호출할 채널 구성원 목록을 제공합니다. | 메타스위치에서는 이 데이터를 저장하지 않습니다. | [b8e57f6b-31cf-468e-9e99-81f0395cb1f9](https://docs.microsoft.com/microsoft-365-app-certification/azure/b8e57f6b-31cf-468e-9e99-81f0395cb1f9) |
>| Chat.Read | 위임 |  어떤 데이터를 수집하거나 사용하나요? 데이터 수집 또는 사용에 대한 사정을 추가합니다. 사용자 ID 및 현재 채팅 구성원의 이름을 표시합니다. 앱은 이를 사용하여 사용자에게 통화할 채팅 구성원 목록을 제공합니다. | 메타스위치에서는 이 데이터를 저장하지 않습니다. | [b8e57f6b-31cf-468e-9e99-81f0395cb1f9](https://docs.microsoft.com/microsoft-365-app-certification/azure/b8e57f6b-31cf-468e-9e99-81f0395cb1f9) |
>| TeamMember.Read.All | 위임 | 사용자 ID 및 현재 팀 구성원의 이름을 표시합니다. 앱은 이를 사용하여 사용자에게 통화할 팀 구성원 목록을 제공합니다. | 메타스위치에서는 이 데이터를 저장하지 않습니다. | [b8e57f6b-31cf-468e-9e99-81f0395cb1f9](https://docs.microsoft.com/microsoft-365-app-certification/azure/b8e57f6b-31cf-468e-9e99-81f0395cb1f9) |
>| User.Read.All | 위임 |  어떤 데이터를 수집하거나 사용하나요? 데이터 수집 또는 사용에 대한 사정을 추가합니다. 사용자의 업무 및 휴대폰 번호입니다. 이러한 번호로의 전화 통화를 시작할 수 있도록 이 작업을 시작해야 합니다. |   메타스위치에서 이 데이터를 저장하지 않습니다. | [b8e57f6b-31cf-468e-9e99-81f0395cb1f9](https://docs.microsoft.com/microsoft-365-app-certification/azure/b8e57f6b-31cf-468e-9e99-81f0395cb1f9) |
>| openid | 위임 | 사용자를 대신하여 나열된 다른 Graph API 끝점에 액세스하도록 앱에 권한을 부여하는 사용자에 대한 권한 부여 토큰입니다. | 메타스위치에서는 이 데이터를 저장하지 않습니다. | [b8e57f6b-31cf-468e-9e99-81f0395cb1f9](https://docs.microsoft.com/microsoft-365-app-certification/azure/b8e57f6b-31cf-468e-9e99-81f0395cb1f9) |

#### <a name="data-access-using-other-microsoft-apis"></a>다른 Microsoft API를 사용한 데이터 액세스

기본 제공 앱 및 추가 Microsoft 365 Microsoft Graph 기타 Microsoft API를 사용하여 OII(조직 식별 가능 정보)를 수집하거나 처리합니다. 이 앱에서 사용하는 Microsoft API를 Graph Microsoft API를 나열합니다.

>| **API** |  **OII가 수집하나요?** |  **수집되는 OII는 무엇입니까?** | **OII 수집의 사당성** | **OII가 저장되어 있나요?** | **OII 저장의 사당성** |
>|:--------|:-----------------------|:----------------------------|:--------------------------------------|:-------------------|:-----------------------------------|
>| Microsoft Identity Platform | 아니요 |  |  |  |  |

#### <a name="non-microsoft-services-used"></a>비영구 Microsoft 서비스

앱이 Microsoft가 아닌 서비스로 조직 데이터를 전송하거나 공유하는 경우 앱에서 사용하는 비 Microsoft 서비스, 전송되는 데이터를 나열하고 앱이 이 정보를 전송해야 하는 이유에 대한 사유를 포함합니다.

>| **모든 비 Microsoft 서비스 OII가 다음으로 전송됩니다.** |  **전송되는 OII는 무엇입니까?** | **OII 전송의 사당성** |
>|:-----------------------------------------------------|:------------------------------|:----------------------------------------|
>| 메타스위치 네트워크 및 POPP 통신 | 다음 OII는 MCT 호스트된 봇 서버로 전송됩니다. Azure AD 테넌트 ID 팀 ID 채널/채팅 ID 메시지 콘텐츠도 전송됩니다. 이는 잠재적으로 OII를 포함할 수 있습니다. 다음 OII는 CommPortal JSON API로 전송될 수 있습니다. 전화 그룹의 사용자 수: 전자 메일 주소 사용자 IP 주소의 도메인 | OII를 전송해야 하는 이유에 대한 사당성 추가 앱&#8217;주요 목적은 전화 통화를 용이하게 하는 것입니다. 사용자가 전화 통화를 시도하는 경우 CommPortal 계정에 로그인하고 통화를 올바른 사용자에게 다시 연결하려면 이 정보를 제공해야 합니다.  MCT Hosted Bot Server로 전송되는 OII는 봇 프레임워크 API에 기본 제공되어 사용자와 통합되는 Teams 방지할 수 없습니다. |

#### <a name="data-access-via-bots"></a>봇을 통한 데이터 액세스

이 앱에 봇 또는 메시징 확장이 포함되어 있는 경우 팀 구성원의 명단(이름, 성, 표시 이름, 전자 메일 주소)이나 팀 구성원이 추가된 채팅의 최종 사용자 식별 정보(EUII)에 액세스할 수 있습니다. 이 앱이 이 기능을 사용하나요?

>| **EUII 액세스의 사유는 무엇입니까?**  | **EUII가 데이터베이스에 저장되어 있나요?** | **EUII 저장의 사유는 무엇입니까?** |
>|:---------------------------------------|:-----------------------------------|:------------------------------------|
>| 이&#8217;주요 목적은 전화 통화를 용이하게 하는 것입니다. 사용자가 전화 통화를 시도하는 경우 올바른 전화 통신 사용자 간에 통화를 설정하려면 통화의 모든 당사자에 대한 EUII를 제공해야 합니다. | 아니요 |  |


#### <a name="telemetry-data"></a>원격 분석 데이터

이 응용 프로그램의 원격 분석 또는 로그에 OII(조직 식별 정보) 또는 EUII(최종 사용자 식별 정보)가 나타나나요? 그렇다면 저장되는 데이터와 보존 및 제거 정책에 대해 설명하세요.

>응용 프로그램 원격 분석 또는 로그에 OII 또는 EUII가 나타나지 않습니다.

#### <a name="organizational-controls-for-data-stored-by-partner"></a>파트너가 저장한 데이터에 대한 조직 제어

조직의 관리자가 파트너 시스템에서 정보를 제어하는 방법에 대해 설명하는 방법 삭제, 보존, 감사, 보관, 최종 사용자 정책 등

>메타스위치 및 POPP는 CommPortal 웹에서 MCT 웹 페이지를 로드하는 즉시 필요한 시간보다 더 오래 데이터를 저장하지 않습니다. 데이터는 보존되지 않습니다. 즉시 제거됩니다.

#### <a name="human-review-of-organizational-information"></a>조직 정보의 인적 검토

사람이 이 앱에서 수집하거나 저장하는 OII(조직 식별 정보) 데이터를 검토하거나 분석하는 데 관여하나요?

>아니요

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end


::: zone pivot="identity"

### <a name="identity-information"></a>ID 정보

이 정보는 POPP Communications에서 이 앱이 인증, 권한 부여, 응용 프로그램 등록 모범 사례 및 기타 ID 조건을 처리하는 방법에 대해 제공했습니다.

| **정보** | **응답** |
|:----------------|:-------------|
| Microsoft Identify Platform(Azure AD)과 통합하나요?  | 예 |
| 통합 검사 목록에 설명된 적용 가능한 모든 모범 사례를 Microsoft ID 플랫폼 준수하나요?  | 아니요 |
| 앱에서 인증에 MSAL(Microsoft 인증 라이브러리)을 사용하나요? | 예 |
| 앱에서 조건부 액세스 정책을 지원하나요? | 예 |
| 지원되는 정책 유형 나열 | 인증에 사용되는 MSAL 라이브러리에서 이러한 지원이 자동으로 제공되는 범위까지의 조건부 액세스 정책  |
| 앱에서 시나리오에 대한 최소 권한 권한을 요청하나요? | 예 |
| 앱의 정적으로 등록된 사용 권한은 앱이 동적으로 그리고 증분적으로 요청하는 권한을 정확하게 반영하나요? | 예 |
| 앱에서 다중 테넌시를 지원하나요? | 아니요 |
| 앱에 기밀 클라이언트가 있나요? | 아니요 |
| 앱에 등록된 리디렉션 URI(통합 리소스 식별자)를 모두 소유하고 있나요? | 예 |
| 앱의 경우 어떻게 사용하지 않도록 해야 하나요? | - 와일드카드 리디렉션 URIS,<br/><br/> |
| 앱에서 웹 API를 노출하나요? | 아니요 |
| 앱에서 미리 보기 API를 사용하나요? | 아니요 |
| 앱에서 사용되지 않는 API를 사용하나요? | 아니요 |

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

