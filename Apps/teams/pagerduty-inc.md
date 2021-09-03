---
title: PagerDuty, Inc.의 PagerDuty에 대한 응용 프로그램 정보
ms.author: elmalova
author: elenamalova
ms.date: 08/27/2021
ms.topic: article
ms.service: attestation
certification_type: attested
description: PagerDuty, 데이터 처리 정책, CSA STAR 레지스트리의 Microsoft Cloud App Security 앱 카탈로그 정보 및 보안/규정 준수 정보에 대해 사용할 수 있는 모든 보안 및 규정 준수 정보
zone_pivot_groups: app-info-data-identity
ms.openlocfilehash: 3729a9523ea4af31015f6e8111c6843e90d465f3
ms.sourcegitcommit: 23a1fdeaf3905ab5f7acfbb378c7c23aaedcdc29
ms.translationtype: MT
ms.contentlocale: ko-KR
ms.lasthandoff: 09/03/2021
ms.locfileid: "58873922"
---
# <a name="pagerduty"></a>PagerDuty

<p></p>
<img alt="Publisher Attestation: The information on this page is based on a self-assessment report provided by the app developer on the security, compliance, and data handling practices followed by this app. Microsoft makes no guarantees regarding the accuracy of the information." src="../media/attested.png" width="650" />
<p>개발자가 마지막으로 업데이트한 날짜: 2021년 8월 27일</p>

* <a href="https://teams.microsoft.com/l/app/c8c302dc-4e77-4536-890d-0c2bffbef9cc" target="_blank">저장소의 Teams 보기</a>
* <a href="https://appsource.microsoft.com/product/office/WA200001637" target="_blank">AppSource의 보기</a>

::: zone pivot="general"

### <a name="general-information"></a>일반 정보

PagerDuty, Inc.에서 Microsoft에 제공한 정보:

| **정보** | **응답** |
|:----------------|:-------------|
| 앱 이름 | PagerDuty |
| ID | WA200001637 |
| Office 365 클라이언트 지원 | Microsoft Teams |
| 파트너 회사 이름 | PagerDuty, Inc. |
| 파트너 웹 사이트의 URL | [https://www.pagerduty.com](https://www.pagerduty.com) |
| 응용 프로그램 Teams 페이지의 URL입니다. | [https://www.pagerduty.com/integrations/microsoft-teams](https://www.pagerduty.com/integrations/microsoft-teams) |
| 개인 정보 취급 방침의 URL | [https://www.pagerduty.com/privacy-policy/](https://www.pagerduty.com/privacy-policy/) |
| 사용 약관 URL | [https://www.pagerduty.com/service-terms-use/](https://www.pagerduty.com/service-terms-use/) |

 [!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="data"

### <a name="how-the-app-handles-data"></a>앱이 데이터를 처리하는 방법

이 정보는 PagerDuty, Inc.에서 이 앱이 조직 데이터를 수집하고 저장하는 방법 및 앱이 수집하는 데이터를 통해 조직이 하게 될 컨트롤에 대해 제공합니다.

#### <a name="data-access-using-microsoft-graph"></a>Microsoft 365를 사용한 데이터 Graph

이 앱에 [Graph Microsoft 사용자 권한을](https://docs.microsoft.com/graph/permissions-reference) 나열합니다.

>| **사용 권한**  | **사용 권한 유형(위임/ 응용 프로그램)** | **데이터가 수집하나요? 수집의 사당성** | **데이터가 저장되어 있나요? 저장 사정이 있나요?** | **Azure AD 앱 ID** |
>|:----------------|:------------------------------------------------|:--------------------------------------------------------|:--------------------------------------------------|:--------------------|
>| OnlineMeetings.ReadWrite | 위임 | 모임 만들기/응답에서 이러한 필드(예: join_web_url, audioConferencing)를 사용하고 있습니다. 이러한 필드는 모임 또는 모임에서 연결하는 다른 방법에 대한 링크를 사용자에게 표시하는 데 필요합니다. | 저장: join_web_url, audioConferencing. 이러한 필드는 모임 또는 모임에서 연결하는 다른 방법에 대한 링크를 사용자에게 표시하는 데 필요합니다. | [05ffe668-5b27-45ff-a64d-b2ed6c475d7a](https://docs.microsoft.com/microsoft-365-app-certification/azure/05ffe668-5b27-45ff-a64d-b2ed6c475d7a) |
>| TeamsAppInstallation.ReadForTeam | 위임 | 채팅에 pagerduty 앱을 추가하는 데 사용. | 채팅에 pagerduty 앱을 추가하는 데 사용. | [05ffe668-5b27-45ff-a64d-b2ed6c475d7a](https://docs.microsoft.com/microsoft-365-app-certification/azure/05ffe668-5b27-45ff-a64d-b2ed6c475d7a) |
>| TeamsAppInstallation.ReadWriteForTeam.All | 위임 | 채팅에 pagerduty 앱을 추가하는 데 사용. | 채팅에 pagerduty 앱을 추가하는 데 사용. | [05ffe668-5b27-45ff-a64d-b2ed6c475d7a](https://docs.microsoft.com/microsoft-365-app-certification/azure/05ffe668-5b27-45ff-a64d-b2ed6c475d7a) |
>| TeamsTab.ReadWrite.All | 위임 | 모임에서 pagerduty 앱을 탭으로 추가하는 데 사용 | 모임에서 pagerduty 앱을 탭으로 추가하는 데 사용 | [05ffe668-5b27-45ff-a64d-b2ed6c475d7a](https://docs.microsoft.com/microsoft-365-app-certification/azure/05ffe668-5b27-45ff-a64d-b2ed6c475d7a) |
>| User.Read | 위임 | 데이터가 사용됩니다. id, userPrincipalName . Microsoft Teams 사용자가 모임에 참가자로 추가하게 하는 데 사용됩니다. | 데이터가 사용됩니다. id, userPrincipalName . Microsoft Teams 사용자가 모임에 참가자로 추가하게 하는 데 사용됩니다. | [05ffe668-5b27-45ff-a64d-b2ed6c475d7a](https://docs.microsoft.com/microsoft-365-app-certification/azure/05ffe668-5b27-45ff-a64d-b2ed6c475d7a) |
>| User.ReadBasic.All | 위임 | 데이터가 사용됩니다. id, userPrincipalName . Microsoft Teams 사용자가 모임에 참가자로 추가하게 하는 데 사용됩니다. | 데이터가 사용됩니다. id, userPrincipalName . Microsoft Teams 사용자가 모임에 참가자로 추가하게 하는 데 사용됩니다. | [05ffe668-5b27-45ff-a64d-b2ed6c475d7a](https://docs.microsoft.com/microsoft-365-app-certification/azure/05ffe668-5b27-45ff-a64d-b2ed6c475d7a) |
>| 전자 메일 | 위임 | 권한 부여 및 토큰 요청에 사용 데이터 사용: access_token, refresh_token, expires_in, 범위 | access_token, refresh_token expires_in 범위입니다. 이 데이터는 사용자 및 온라인 모임에 대한 정보를 수집하는 데 필요합니다. | [05ffe668-5b27-45ff-a64d-b2ed6c475d7a](https://docs.microsoft.com/microsoft-365-app-certification/azure/05ffe668-5b27-45ff-a64d-b2ed6c475d7a) |
>| offline_access | 위임 | 권한 부여 및 토큰 요청에 사용 데이터 사용: access_token, refresh_token, expires_in, 범위 | access_token, refresh_token expires_in 범위입니다. 이 데이터는 사용자 및 온라인 모임에 대한 정보를 수집하기 위해 다시 제공됩니다. | [05ffe668-5b27-45ff-a64d-b2ed6c475d7a](https://docs.microsoft.com/microsoft-365-app-certification/azure/05ffe668-5b27-45ff-a64d-b2ed6c475d7a) |
>| openid | 위임 | 권한 부여 및 토큰 요청에 사용 데이터 사용: access_token, refresh_token, expires_in, 범위 | access_token, refresh_token expires_in 범위입니다. 이 데이터는 사용자에 대한 정보 및 온라인 모임 만들기/시작에 대한 정보가 다시 제공된 것입니다. | [05ffe668-5b27-45ff-a64d-b2ed6c475d7a](https://docs.microsoft.com/microsoft-365-app-certification/azure/05ffe668-5b27-45ff-a64d-b2ed6c475d7a) |
>| 프로필 | 위임 | 권한 부여 및 토큰 요청에 사용 데이터 사용: access_token, refresh_token, expires_in, 범위 | access_token, refresh_token expires_in 범위입니다. 이 데이터는 사용자에 대한 정보 및 온라인 모임 만들기/시작에 대한 정보가 다시 제공된 것입니다. | [05ffe668-5b27-45ff-a64d-b2ed6c475d7a](https://docs.microsoft.com/microsoft-365-app-certification/azure/05ffe668-5b27-45ff-a64d-b2ed6c475d7a) |
>| OnlineMeetings.ReadWrite | 위임 | 모임 만들기/응답에서 이러한 필드(예: join_web_url, audioConferencing)를 사용하고 있습니다. 이러한 필드는 모임 또는 모임에서 연결하는 다른 방법에 대한 링크를 사용자에게 표시하는 데 필요합니다. | 저장: join_web_url, audioConferencing. 이러한 필드는 모임 또는 모임에서 연결하는 다른 방법에 대한 링크를 사용자에게 표시하는 데 필요합니다. | [8f79a561-d2f1-4a1e-8092-c2039043a40e](https://docs.microsoft.com/microsoft-365-app-certification/azure/8f79a561-d2f1-4a1e-8092-c2039043a40e) |
>| TeamsAppInstallation.ReadForTeam | 위임 | 채팅에 pagerduty 앱을 추가하는 데 사용. | 채팅에 pagerduty 앱을 추가하는 데 사용. | [8f79a561-d2f1-4a1e-8092-c2039043a40e](https://docs.microsoft.com/microsoft-365-app-certification/azure/8f79a561-d2f1-4a1e-8092-c2039043a40e) |
>| TeamsAppInstallation.ReadForTeam.All | 위임 | 채팅에 pagerduty 앱을 추가하는 데 사용. | 채팅에 pagerduty 앱을 추가하는 데 사용. | [8f79a561-d2f1-4a1e-8092-c2039043a40e](https://docs.microsoft.com/microsoft-365-app-certification/azure/8f79a561-d2f1-4a1e-8092-c2039043a40e) |
>| TeamsTab.ReadWrite.All | 위임 | 모임에서 pagerduty 앱을 탭으로 추가하는 데 사용 | 모임에서 pagerduty 앱을 탭으로 추가하는 데 사용 | [8f79a561-d2f1-4a1e-8092-c2039043a40e](https://docs.microsoft.com/microsoft-365-app-certification/azure/8f79a561-d2f1-4a1e-8092-c2039043a40e) |
>| User.Read | 위임 | 데이터가 사용됩니다. id, userPrincipalName . Microsoft Teams 사용자가 모임에 참가자로 추가하게 하는 데 사용됩니다. | 데이터가 사용됩니다. id, userPrincipalName . Microsoft Teams 사용자가 모임에 참가자로 추가하게 하는 데 사용됩니다. | [8f79a561-d2f1-4a1e-8092-c2039043a40e](https://docs.microsoft.com/microsoft-365-app-certification/azure/8f79a561-d2f1-4a1e-8092-c2039043a40e) |
>| User.ReadBasic.All | 위임 | 데이터가 사용됩니다. id, userPrincipalName . Microsoft Teams 사용자가 모임에 참가자로 추가하게 하는 데 사용됩니다. | 데이터가 사용됩니다. id, userPrincipalName . Microsoft Teams 사용자가 모임에 참가자로 추가하게 하는 데 사용됩니다. | [8f79a561-d2f1-4a1e-8092-c2039043a40e](https://docs.microsoft.com/microsoft-365-app-certification/azure/8f79a561-d2f1-4a1e-8092-c2039043a40e) |
>| 전자 메일 | 위임 | 권한 부여 및 토큰 요청에 사용 데이터 사용: access_token, refresh_token, expires_in, 범위 | access_token, refresh_token expires_in 범위입니다. 이 데이터는 사용자 및 온라인 모임에 대한 정보를 수집하는 데 필요합니다. | [8f79a561-d2f1-4a1e-8092-c2039043a40e](https://docs.microsoft.com/microsoft-365-app-certification/azure/8f79a561-d2f1-4a1e-8092-c2039043a40e) |
>| offline_access | 위임 | 권한 부여 및 토큰 요청에 사용 데이터 사용: access_token, refresh_token, expires_in, 범위 | access_token, refresh_token expires_in 범위입니다. 이 데이터는 사용자 및 온라인 모임에 대한 정보를 수집하는 데 필요합니다. | [8f79a561-d2f1-4a1e-8092-c2039043a40e](https://docs.microsoft.com/microsoft-365-app-certification/azure/8f79a561-d2f1-4a1e-8092-c2039043a40e) |
>| openid | 위임 | 권한 부여 및 토큰 요청에 사용 데이터 사용: access_token, refresh_token, expires_in, 범위 | access_token, refresh_token expires_in 범위입니다. 이 데이터는 사용자에 대한 정보 및 온라인 모임 만들기/시작에 대한 정보가 다시 제공된 것입니다. | [8f79a561-d2f1-4a1e-8092-c2039043a40e](https://docs.microsoft.com/microsoft-365-app-certification/azure/8f79a561-d2f1-4a1e-8092-c2039043a40e) |
>| 프로필 | 위임 | 권한 부여 및 토큰 요청에 사용 데이터 사용: access_token, refresh_token, expires_in, 범위 | access_token, refresh_token expires_in 범위입니다. 이 데이터는 사용자에 대한 정보 및 온라인 모임 만들기/시작에 대한 정보가 다시 제공된 것입니다. | [8f79a561-d2f1-4a1e-8092-c2039043a40e](https://docs.microsoft.com/microsoft-365-app-certification/azure/8f79a561-d2f1-4a1e-8092-c2039043a40e) |


#### <a name="non-microsoft-services-used"></a>비영구 Microsoft 서비스

앱이 Microsoft가 아닌 서비스로 조직 데이터를 전송하거나 공유하는 경우 앱에서 사용하는 비 Microsoft 서비스, 전송되는 데이터를 나열하고 앱이 이 정보를 전송해야 하는 이유에 대한 사유를 포함합니다.

>| **모든 비 Microsoft 서비스 OII가 다음으로 전송됩니다.** |  **전송되는 OII는 무엇입니까?** | **OII 전송의 사당성** |
>|:-----------------------------------------------------|:------------------------------|:----------------------------------------|
>| PagerDuty에서 유지 관리하는 데이터는 모니터링 제품의 컴퓨터 데이터로 제한됩니다. PII 정보는 회사 전자 메일 주소, 이름, 성 및 전화 번호로 제한됩니다. 해당 데이터에 액세스할 수 있는 하위 프로세서 목록은 다음에서 찾을 수 있습니다. https://www.pagerduty.com/subprocessors/ | PagerDuty에서 유지 관리하는 데이터는 모니터링 제품의 컴퓨터 데이터로 제한됩니다. PII 정보는 회사 전자 메일 주소, 이름, 성 및 전화 번호로 제한됩니다. 해당 데이터에 액세스할 수 있는 하위 프로세서 목록은 다음에서 찾을 수 있습니다. https://www.pagerduty.com/subprocessors/ | PagerDuty에서 유지 관리하는 데이터는 모니터링 제품의 컴퓨터 데이터로 제한됩니다. PII 정보는 회사 전자 메일 주소, 이름, 성 및 전화 번호로 제한됩니다. 해당 데이터에 액세스할 수 있는 하위 프로세서 목록은 여기에서 찾을 수 있습니다. 데이터 개인 정보 보호에 대한 자세한 내용은 https://www.pagerduty.com/subprocessors/ 다음에서 찾을 수 있습니다. https://www.pagerduty.com/privacy-policy/ |

#### <a name="data-access-via-bots"></a>봇을 통한 데이터 액세스

이 앱에 봇 또는 메시징 확장이 포함되어 있는 경우 팀 구성원의 명단(이름, 성, 표시 이름, 전자 메일 주소)이나 팀 구성원이 추가된 채팅의 최종 사용자 식별 정보(EUII)에 액세스할 수 있습니다. 이 앱이 이 기능을 사용하나요?

>EUII에 액세스하지 않습니다.


#### <a name="telemetry-data"></a>원격 분석 데이터

이 응용 프로그램의 원격 분석 또는 로그에 OII(조직 식별 정보) 또는 EUII(최종 사용자 식별 정보)가 나타나나요? 그렇다면 저장되는 데이터와 보존 및 제거 정책에 대해 설명하세요.

>응용 프로그램 원격 분석 또는 로그에 OII 또는 EUII가 나타나지 않습니다.

#### <a name="organizational-controls-for-data-stored-by-partner"></a>파트너가 저장한 데이터에 대한 조직 제어

조직의 관리자가 파트너 시스템에서 정보를 제어하는 방법에 대해 설명하는 방법 삭제, 보존, 감사, 보관, 최종 사용자 정책 등

>PagerDuty를 사용하려면 PagerDuty에서 유지 관리하는 데이터 보안 표준을 서명된 DPA 형식의 계약 의무를 포함하여 데이터를 전송하는 모든 공급업체에서 유지 관리해야 합니다. 데이터 보안 표준에 대한 자세한 내용은 다음에서 찾을 수 있습니다. https://www.pagerduty.com/data-security-policy/

#### <a name="human-review-of-organizational-information"></a>조직 정보의 인적 검토

사람이 이 앱에서 수집하거나 저장하는 OII(조직 식별 정보) 데이터를 검토하거나 분석하는 데 관여하나요?

>아니요

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="mcas"

Microsoft Cloud App Security [카탈로그의](https://www.microsoft.com/enterprise-mobility-security/cloud-app-security) 정보가 아래에 표시됩니다.

<iframe height='1020' title='Microsoft Cloud App Security 정보' src='https://appmcasinfoprod.azurewebsites.net/#/dashboard/' frameborder='no' style='width: 100%;'></iframe>

<a href="https://appmcasinfoprod.azurewebsites.net/#/dashboard/" target="_blank">새 탭에서 보기</a>

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="identity"

### <a name="identity-information"></a>ID 정보

이 정보는 PagerDuty, Inc.에서 이 앱이 인증, 권한 부여, 응용 프로그램 등록 모범 사례 및 기타 ID 조건을 처리하는 방법에 대해 제공했습니다.

| **정보** | **응답** |
|:----------------|:-------------|
| Microsoft Identify Platform(Azure AD)과 통합하나요?  | 아니요 |

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end
