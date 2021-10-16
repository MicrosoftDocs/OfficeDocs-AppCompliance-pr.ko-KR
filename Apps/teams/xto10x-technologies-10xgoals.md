---
title: xto10x 기술의 10xGoals에 대한 응용 프로그램 정보
ms.author: elmalova
author: elenamalova
ms.date: 08/19/2021
ms.topic: article
ms.service: attestation
certification_type: attested
description: CSA STAR 레지스트리의 10xGoals, 데이터 처리 정책, Microsoft Cloud App Security 앱 카탈로그 정보 및 보안/규정 준수 정보에 대해 사용 가능한 모든 보안 및 규정 준수 정보
zone_pivot_groups: app-info-data-identity
ms.openlocfilehash: 82730906a833ef43df8a3eafaee1111cf6889472
ms.sourcegitcommit: 9dab9c9dacb9c6daaa6b0041ccc8a49bafdad331
ms.translationtype: MT
ms.contentlocale: ko-KR
ms.lasthandoff: 10/16/2021
ms.locfileid: "60411363"
---
# <a name="10xgoals"></a>10xGoals

<p></p>
<img alt="Publisher Attestation: The information on this page is based on a self-assessment report provided by the app developer on the security, compliance, and data handling practices followed by this app. Microsoft makes no guarantees regarding the accuracy of the information." src="../media/attested.png" width="650" />
<p>개발자가 마지막으로 업데이트한 날짜: 2021년 7월 8일</p>

* <a href="https://teams.microsoft.com/l/app/950aa4fb-0583-4b13-9b5f-bbc92b9cc376" target="_blank">저장소의 Teams 보기</a>
* <a href="https://appsource.microsoft.com/product/office/WA200003122" target="_blank">AppSource의 보기</a>

::: zone pivot="general"

### <a name="general-information"></a>일반 정보

xto10x 기술에서 Microsoft에 제공하는 정보:

| **정보** | **응답** |
|:----------------|:-------------|
| 앱 이름 | 10xGoals |
| ID | WA200003122 |
| Office 365 클라이언트 지원 | Microsoft Teams |
| 파트너 회사 이름 | xto10x Technologies |
| 파트너 웹 사이트의 URL | [https://www.xto10x.com/10xgoals/](https://www.xto10x.com/10xgoals/) |
| 응용 프로그램 Teams 페이지의 URL입니다. | [https://www.xto10x.com/10xgoals/](https://www.xto10x.com/10xgoals/) |
| 개인 정보 취급 방침의 URL | [https://www.xto10x.com/security/privacy-policy/](https://www.xto10x.com/security/privacy-policy/) |
| 사용 약관 URL | [https://www.xto10x.com/security/terms-of-use/](https://www.xto10x.com/security/terms-of-use/) |

 [!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="data"

### <a name="how-the-app-handles-data"></a>앱이 데이터를 처리하는 방법

이 정보는 xto10x 기술에서 이 앱이 조직 데이터를 수집하고 저장하는 방법 및 앱이 수집하는 데이터에 대해 조직이 제어할 수 있는 컨트롤에 의해 제공됩니다.

#### <a name="data-access-using-microsoft-graph"></a>Microsoft 365를 사용한 데이터 Graph

이 앱에 [Graph Microsoft 사용자 권한을](https://docs.microsoft.com/graph/permissions-reference) 나열합니다.

>| **사용 권한**  | **사용 권한 유형(위임/ 응용 프로그램)** | **데이터가 수집하나요? 수집의 사당성** | **데이터가 저장되어 있나요? 저장 사정이 있나요?** | **Azure AD 앱 ID** |
>|:----------------|:------------------------------------------------|:--------------------------------------------------------|:--------------------------------------------------|:--------------------|
>| Directory.Read.All | application | 사용자가 전자 메일 및 Azure ID를 반치하여 앱이 모든 사용자에 대해 사전적으로 앱을 설치할 수 있도록 합니다.  | 이 앱을 사용하려면 먼저 10xGoals 서비스 구독이 필요하기 때문에 사용자 전자 메일 및 사용자의 Azure ID가 10xGoals 서비스로 전송될 수 있으므로 해당 사용자와 관련된 일부 활동이 발생할 때 사용자의 팀 앱에 사전 알림을 보낼 수 있습니다. | [950aa4fb-0583-4b13-9b5f-bbc92b9cc376](https://docs.microsoft.com/microsoft-365-app-certification/azure/950aa4fb-0583-4b13-9b5f-bbc92b9cc376) |
>| TeamsAppInstallation.ReadWriteSelfForUser.All | application | 앱이 관리자를 위해 설치된 teamsAppDefinition을 반출한 다음 모든 사용자에 대해 사전적으로 자체적으로 설치할 수 있도록 하는 것이 필요합니다.  | 이 api에서 페치되는 데이터베이스에는 아무 것도 저장되지 않습니다. | [950aa4fb-0583-4b13-9b5f-bbc92b9cc376](https://docs.microsoft.com/microsoft-365-app-certification/azure/950aa4fb-0583-4b13-9b5f-bbc92b9cc376) |


#### <a name="non-microsoft-services-used"></a>비영구 Microsoft 서비스

앱이 Microsoft가 아닌 서비스로 조직 데이터를 전송하거나 공유하는 경우 앱에서 사용하는 비 Microsoft 서비스, 전송되는 데이터를 나열하고 앱이 이 정보를 전송해야 하는 이유에 대한 사유를 포함합니다.

>| **모든 비 Microsoft 서비스 OII가 다음으로 전송됩니다.** |  **전송되는 OII는 무엇입니까?** | **OII 전송의 사당성** |
>|:-----------------------------------------------------|:------------------------------|:----------------------------------------|
>| 10xGoals, AWS | 사용자 전자 메일 및 사용자의 AzureId.  | 이 앱을 사용하려면 먼저 10xGoals 서비스 구독이 필요하기 때문에 사용자 전자 메일과 사용자의 Azure ID가 10xGoals 서비스로 전송됩니다. 그러면 해당 사용자와 관련된 일부 활동이 발생할 때 시스템에서 사용자에게 사전 알림을 보낼 수 있습니다. |

#### <a name="data-access-via-bots"></a>봇을 통한 데이터 액세스

이 앱에 봇 또는 메시징 확장이 포함되어 있는 경우 팀 구성원의 명단(이름, 성, 표시 이름, 전자 메일 주소)이나 팀 구성원이 추가된 채팅의 최종 사용자 식별 정보(EUII)에 액세스할 수 있습니다. 이 앱이 이 기능을 사용하나요?

>| **EUII 액세스의 사유는 무엇입니까?**  | **EUII가 데이터베이스에 저장되어 있나요?** | **EUII 저장의 사유는 무엇입니까?** |
>|:---------------------------------------|:-----------------------------------|:------------------------------------|
>| 이 앱을 사용하려면 먼저 10xGoals 서비스 구독이 필요하기 때문에 사용자 전자 메일 및 사용자의 Azure ID가 10xGoals 서비스로 전송될 수 있으므로 해당 사용자와 관련된 일부 활동이 발생할 때 사용자의 팀 앱에 사전 알림을 보낼 수 있습니다. | 아니요 |  |


#### <a name="telemetry-data"></a>원격 분석 데이터

이 응용 프로그램의 원격 분석 또는 로그에 OII(조직 식별 정보) 또는 EUII(최종 사용자 식별 정보)가 나타나나요? 그렇다면 저장되는 데이터와 보존 및 제거 정책에 대해 설명하세요.

>tenantId 테넌트에 필요한 사용 권한을 부여한지 여부에 따라 환영 메시지가 달라지기 위해 저장됩니다. 테넌트가 이미 권한을 부여한 경우 해당 해당 사용자의 다른 사용자는 사용 권한을 부여하는 흐름을 다시 살펴 볼 필요가 없습니다.

#### <a name="organizational-controls-for-data-stored-by-partner"></a>파트너가 저장한 데이터에 대한 조직 제어

조직의 관리자가 파트너 시스템에서 정보를 제어하는 방법에 대해 설명하는 방법 삭제, 보존, 감사, 보관, 최종 사용자 정책 등

>해당 없음

#### <a name="human-review-of-organizational-information"></a>조직 정보의 인적 검토

사람이 이 앱에서 수집하거나 저장하는 OII(조직 식별 정보) 데이터를 검토하거나 분석하는 데 관여하나요?

>아니요

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end


::: zone pivot="identity"

### <a name="identity-information"></a>ID 정보

이 정보는 xto10x 기술에서 이 앱이 인증, 권한 부여, 응용 프로그램 등록 모범 사례 및 기타 ID 조건을 처리하는 방법에 대해 제공되었습니다.

| **정보** | **응답** |
|:----------------|:-------------|
| Microsoft Identify Platform(Azure AD)과 통합하나요?  | 예 |
| 통합 검사 목록에 설명된 적용 가능한 모든 모범 사례를 Microsoft ID 플랫폼 준수하나요?  | 예 |
| 앱에서 인증에 MSAL(Microsoft 인증 라이브러리)을 사용하나요? | 예 |
| 앱에서 조건부 액세스 정책을 지원하나요? | 아니요 |
| 앱에서 시나리오에 대한 최소 권한 권한을 요청하나요? | 예 |
| 앱의 정적으로 등록된 사용 권한은 앱이 동적으로 그리고 증분적으로 요청하는 권한을 정확하게 반영하나요? | 예 |
| 앱에서 다중 테넌시를 지원하나요? | 아니요 |
| 앱에 기밀 클라이언트가 있나요? | 아니요 |
| 앱에 등록된 리디렉션 URI(통합 리소스 식별자)를 모두 소유하고 있나요? | 예 |
| 앱에서 웹 API를 노출하나요? | 예 |
| 사용 권한 모델에서 클라이언트 앱이 적절한 동의를 받은 경우 통화 성공만 허용하나요? | 예 |
| 앱에서 미리 보기 API를 사용하나요? | 아니요 |
| 앱에서 사용되지 않는 API를 사용하나요? | 아니요 |

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

