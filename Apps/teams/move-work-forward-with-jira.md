---
title: Jira를 통해 작업 진행을 위한 응용 프로그램 정보
ms.author: elmalova
author: elenamalova
ms.date: 06/10/2021
ms.topic: article
ms.service: attestation
certification_type: attested
description: CSA STAR 레지스트리의 Jira로 이동, 데이터 처리 정책, Microsoft Cloud App Security 앱 카탈로그 정보 및 보안/규정 준수 정보에 사용할 수 있는 모든 보안 및 규정 준수 정보
zone_pivot_groups: app-info-data-mcas-identity
ms.openlocfilehash: 7120519c2ecb0643465760677b2bef895b1e2f4d
ms.sourcegitcommit: d85595f6518d8d05f0aee75380f51659908b6bcb
ms.translationtype: MT
ms.contentlocale: ko-KR
ms.lasthandoff: 09/12/2021
ms.locfileid: "59288429"
---
# <a name="move-work-forward-with-jira"></a>Jira를 사용하여 작업을 앞으로 이동

<p></p>
<img alt="Publisher Attestation: The information on this page is based on a self-assessment report provided by the app developer on the security, compliance, and data handling practices followed by this app. Microsoft makes no guarantees regarding the accuracy of the information." src="../media/attested.png" width="650" />
<p>개발자가 마지막으로 업데이트한 날짜: 2021년 6월 10일</p>

* <a href="https://teams.microsoft.com/l/app/79ca2e8f-dd2c-40d5-897e-1b22d41038fe" target="_blank">저장소의 Teams 보기</a>
* <a href="https://appsource.microsoft.com/product/office/WA200002855" target="_blank">AppSource의 보기</a>

::: zone pivot="general"

### <a name="general-information"></a>일반 정보

Microsoft로 작업 이동에서 제공하는 정보:

| **정보** | **응답** |
|:----------------|:-------------|
| 앱 이름 | Jira를 사용하여 작업을 앞으로 이동 |
| ID | WA200002855 |
| Office 365 클라이언트 지원 | Microsoft Teams |
| 파트너 회사 이름 | 작업을 앞으로 이동 |
| 파트너 웹 사이트의 URL | [https://www.moveworkforward.com](https://www.moveworkforward.com) |
| 응용 프로그램 Teams 페이지의 URL입니다. | [https://www.moveworkforward.com/product/microsoft-teams-jir...](https://www.moveworkforward.com/product/microsoft-teams-jira-connector) |
| 개인 정보 취급 방침의 URL | [https://www.moveworkforward.com/privacy-policy](https://www.moveworkforward.com/privacy-policy) |
| 사용 약관 URL | [https://www.moveworkforward.com/license-agreement/eula](https://www.moveworkforward.com/license-agreement/eula) |

 [!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="data"

### <a name="how-the-app-handles-data"></a>앱이 데이터를 처리하는 방법

이 정보는 이 앱이 조직 데이터를 수집하고 저장하는 방법 및 앱이 수집하는 데이터를 통해 조직에서 사용할 컨트롤에 대한 이동 작업 전달에서 제공됩니다.

#### <a name="data-access-using-microsoft-graph"></a>Microsoft 365를 사용한 데이터 Graph

이 앱에 [Graph Microsoft 사용자 권한을](https://docs.microsoft.com/graph/permissions-reference) 나열합니다.

>| **사용 권한**  | **사용 권한 유형(위임/ 응용 프로그램)** | **데이터가 수집하나요? 수집의 사당성** | **데이터가 저장되어 있나요? 저장 사정이 있나요?** | **Azure AD 앱 ID** |
>|:----------------|:------------------------------------------------|:--------------------------------------------------------|:--------------------------------------------------|:--------------------|
>| Channel.Create | 위임 | 문제 토론 채널을 만드는 데 사용됩니다. | 새로 만든 채널의 웹 URL은 Jira에 표시되어 공유 토론 채널에 Microsoft Teams 저장됩니다. | [39d845a0-3fa2-4fba-acc2-61afe40cfcea](https://docs.microsoft.com/microsoft-365-app-certification/azure/39d845a0-3fa2-4fba-acc2-61afe40cfcea) |
>| Channel.ReadBasic.All | 위임 | 채널 이름 및 ID는 Jira에서 채널로 알림을 보내는 Microsoft Teams. | 채널 ID 및 이름은 Jira에서 채널로의 알림을 구성하기 위해 Microsoft Teams. | [39d845a0-3fa2-4fba-acc2-61afe40cfcea](https://docs.microsoft.com/microsoft-365-app-certification/azure/39d845a0-3fa2-4fba-acc2-61afe40cfcea) |
>| Team.ReadBasic.All | 위임 | 사용 권한은 사용자가 Jira에서 이 참가 팀 중 하나를 선택할 수 있도록 하는 데 사용됩니다. | Jira의 구성 화면에 표시할 팀 ID 및 이름입니다. | [39d845a0-3fa2-4fba-acc2-61afe40cfcea](https://docs.microsoft.com/microsoft-365-app-certification/azure/39d845a0-3fa2-4fba-acc2-61afe40cfcea) |
>| TeamsAppInstallation.ReadForTeam | 위임 | 팀의 Teams 설치된 앱을 읽습니다. 봇에 배달을 설정할 Microsoft Teams 봇이 Teams 앱으로 보낼 수 있습니다. | Nothing | [39d845a0-3fa2-4fba-acc2-61afe40cfcea](https://docs.microsoft.com/microsoft-365-app-certification/azure/39d845a0-3fa2-4fba-acc2-61afe40cfcea) |
>| User.Read | 위임 | 사용자가 채널 메시지에서 @-mention을 사용하여 공동 작업자와 토론 채널을 만들 수 있습니다. | Nothing | [39d845a0-3fa2-4fba-acc2-61afe40cfcea](https://docs.microsoft.com/microsoft-365-app-certification/azure/39d845a0-3fa2-4fba-acc2-61afe40cfcea) |
>| 전자 메일 | 위임 | 전자 메일은 Atlassian 및 Microsoft Users 일치에 사용됩니다. | 전자 메일이 저장되지 않습니다. 일치하는 프로세스 중에만 사용됩니다. | [39d845a0-3fa2-4fba-acc2-61afe40cfcea](https://docs.microsoft.com/microsoft-365-app-certification/azure/39d845a0-3fa2-4fba-acc2-61afe40cfcea) |


#### <a name="non-microsoft-services-used"></a>비영구 Microsoft 서비스

앱이 Microsoft가 아닌 서비스로 조직 데이터를 전송하거나 공유하는 경우 앱에서 사용하는 비 Microsoft 서비스, 전송되는 데이터를 나열하고 앱이 이 정보를 전송해야 하는 이유에 대한 사유를 포함합니다.

>비영구 Microsoft 서비스 사용되지 않습니다.

#### <a name="data-access-via-bots"></a>봇을 통한 데이터 액세스

이 앱에 봇 또는 메시징 확장이 포함되어 있는 경우 팀 구성원의 명단(이름, 성, 표시 이름, 전자 메일 주소)이나 팀 구성원이 추가된 채팅의 최종 사용자 식별 정보(EUII)에 액세스할 수 있습니다. 이 앱이 이 기능을 사용하나요?

>| **EUII 액세스의 사유는 무엇입니까?**  | **EUII가 데이터베이스에 저장되어 있나요?** | **EUII 저장의 사유는 무엇입니까?** |
>|:---------------------------------------|:-----------------------------------|:------------------------------------|
>| 앱을 설치할 때 이름을 통해 사용자를 인사말합니다. 사용자 Microsoft Teams 및 Atlassian 사용자 일치 | 아니요 |  |


#### <a name="telemetry-data"></a>원격 분석 데이터

이 응용 프로그램의 원격 분석 또는 로그에 OII(조직 식별 정보) 또는 EUII(최종 사용자 식별 정보)가 나타나나요? 그렇다면 저장되는 데이터와 보존 및 제거 정책에 대해 설명하세요.

>최대 5일 동안 로그에 저장되는 테넌트 URL을 기록합니다.

#### <a name="organizational-controls-for-data-stored-by-partner"></a>파트너가 저장한 데이터에 대한 조직 제어

조직의 관리자가 파트너 시스템에서 정보를 제어하는 방법에 대해 설명하는 방법 삭제, 보존, 감사, 보관, 최종 사용자 정책 등

>당사는 엄격한 데이터 개인 정보 보호를 보장하는 서비스만 사용하게 됩니다.

#### <a name="human-review-of-organizational-information"></a>조직 정보의 인적 검토

사람이 이 앱에서 수집하거나 저장하는 OII(조직 식별 정보) 데이터를 검토하거나 분석하는 데 관여하나요?

>아니요

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="mcas"

Microsoft Cloud App Security [카탈로그의](https://www.microsoft.com/enterprise-mobility-security/cloud-app-security) 정보가 아래에 표시됩니다.

<iframe height='1020' title='Microsoft Cloud App Security 정보' src='https://appmcasinfoprod.azurewebsites.net/#/dashboard/39108' frameborder='no' style='width: 100%;'></iframe>

<a href="https://appmcasinfoprod.azurewebsites.net/#/dashboard/39108" target="_blank">새 탭에서 보기</a>

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="identity"

### <a name="identity-information"></a>ID 정보

이 정보는 Move Work Forward에서 이 앱이 인증, 권한 부여, 응용 프로그램 등록 모범 사례 및 기타 ID 조건을 처리하는 방법에 대해 제공했습니다.

| **정보** | **응답** |
|:----------------|:-------------|
| Microsoft Identify Platform(Azure AD)과 통합하나요?  | 예 |
| 통합 검사 목록에 설명된 적용 가능한 모든 모범 사례를 Microsoft ID 플랫폼 준수하나요?  | 예 |
| 앱에서 인증에 MSAL(Microsoft 인증 라이브러리)을 사용하나요? | 예 |
| 앱에서 조건부 액세스 정책을 지원하나요? | 아니요 |
| 앱에서 시나리오에 대한 최소 권한 권한을 요청하나요? | 예 |
| 앱의 정적으로 등록된 사용 권한은 앱이 동적으로 그리고 증분적으로 요청하는 권한을 정확하게 반영하나요? | 예 |
| 앱에서 다중 테넌시를 지원하나요? | 예 |
| 앱에 기밀 클라이언트가 있나요? | 아니요 |
| 앱에 등록된 리디렉션 URI(통합 리소스 식별자)를 모두 소유하고 있나요? | 예 |
| 앱의 경우 어떻게 사용하지 않도록 해야 하나요? | - 와일드카드 리디렉션 URIS,<br/><br/>- 리소스 소유자 암호 자격 증명(ROPC) 흐름 |
| 앱에서 웹 API를 노출하나요? | 아니요 |
| 앱에서 미리 보기 API를 사용하나요? | 아니요 |
| 앱에서 사용되지 않는 API를 사용하나요? | 아니요 |

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end
