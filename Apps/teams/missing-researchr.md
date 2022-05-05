---
title: KBE&#26666;&#24335;&#20250;&#31038; 의해 researcHR에 대한 애플리케이션 정보
ms.author: elmalova
author: elenamalova
manager: tonybal
ms.date: 08/05/2021
ms.topic: article
ms.service: attestation
certification_type: attested
description: researcHR, 해당 데이터 처리 정책, Microsoft Cloud App Security 앱 카탈로그 정보 및 CSA STAR 레지스트리의 보안/규정 준수 정보에 사용할 수 있는 모든 보안 및 규정 준수 정보입니다.
zone_pivot_groups: app-info-data-mcas-identity
ms.openlocfilehash: 66460d332f54b1868fbcd2895b6de088bb362d97
ms.sourcegitcommit: 7a7de9f48f6cf5b6acd435412477b6a59127f19a
ms.translationtype: MT
ms.contentlocale: ko-KR
ms.lasthandoff: 05/05/2022
ms.locfileid: "65229012"
---
# <a name="researchr"></a>researcHR

<p></p>
<img alt="Publisher Attestation: The information on this page is based on a self-assessment report provided by the app developer on the security, compliance, and data handling practices followed by this app. Microsoft makes no guarantees regarding the accuracy of the information." src="../media/attested.png" width="650" />
<p>개발자가 마지막으로 업데이트한 날짜: 2021년 8월 5일</p>

* <a href="https://teams.microsoft.com/l/app/13a58c36-8f58-46e7-90dd-16084830876c" target="_blank">Teams 스토어에서 보기</a>
* <a href="https://appsource.microsoft.com/product/office/WA200002557" target="_blank">AppSource에서 보기</a>

::: zone pivot="general"

### <a name="general-information"></a>일반 정보

KBE에서 Microsoft에&#26666;&#24335;&#20250;&#31038; 제공하는 정보:

| **정보** | **응답** |
|:----------------|:-------------|
| 앱 이름 | researcHR |
| ID | WA200002557 |
| 지원되는 Office 365 클라이언트 | Microsoft Teams |
| 파트너 회사 이름 | KBE&#26666;&#24335;&#20250;&#31038; |
| 파트너 웹 사이트의 URL | [https://app.researchr.work/corporate](https://app.researchr.work/corporate) |
| Teams 애플리케이션 정보 페이지의 URL | [https://app.researchr.work](https://app.researchr.work) |
| 개인 정보 취급 방침의 URL | [https://researchr.work/privacypolicy](https://researchr.work/privacypolicy) |
| 사용 약관 URL | [https://app.researchr.work/tos](https://app.researchr.work/tos) |

 [!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="data"

### <a name="how-the-app-handles-data"></a>앱에서 데이터를 처리하는 방법

이 정보는 KBE&#26666;&#24335;&#20250;&#31038; 이 앱이 조직 데이터를 수집하고 저장하는 방법과 앱이 수집하는 데이터에 대해 조직에서 가질 컨트롤에 대해 제공되었습니다.

#### <a name="data-access-using-microsoft-graph"></a>Microsoft Graph 사용하여 데이터 액세스

이 앱[에 필요한 Microsoft Graph 권한을](/graph/permissions-reference) 나열합니다.

>| **사용 권한**  | **권한 유형(위임됨/애플리케이션)** | **데이터가 수집되었나요? 수집에 대한 정당성?** | **데이터가 저장되어 있나요? 저장에 대한 근거?** | **앱 ID Azure AD** |
>|:----------------|:------------------------------------------------|:--------------------------------------------------------|:--------------------------------------------------|:--------------------|
>| Channel.Create | 응용 프로그램 | 이 범위를 사용하여 봇이 Teams 클라이언트에 새 채널을 만들 수 있습니다. 참조: /graph/api/channel-post | 이러한 데이터는 데이터베이스에 저장하지 않습니다. | [82df726e-0de2-46af-b4f1-0645fd95fc97](../azure/82df726e-0de2-46af-b4f1-0645fd95fc97.md) |
>| Directory.Read.All | 응용 프로그램 | 이 범위를 사용하여 웹 사이트에 이러한 데이터를 표시하는 채널 ID 및 이름을 가져옵니다. 참조: /graph/api/channel-list | 이러한 데이터는 데이터베이스에 저장하지 않습니다. | [82df726e-0de2-46af-b4f1-0645fd95fc97](../azure/82df726e-0de2-46af-b4f1-0645fd95fc97.md) |
>| Group.Read.All | 응용 프로그램 | 이 범위를 사용하여 웹 사이트에 이러한 데이터를 표시하는 채널 ID 및 이름을 가져옵니다. 참조: /graph/api/channel-list | 이러한 데이터는 데이터베이스에 저장하지 않습니다. | [82df726e-0de2-46af-b4f1-0645fd95fc97](../azure/82df726e-0de2-46af-b4f1-0645fd95fc97.md) |
>| Team.ReadBasic.All | 응용 프로그램 | 이 범위를 사용하여 사용자가 웹 사이트에서 팀 구성원을 볼 수 있도록 팀 구성원을 가져옵니다. 참조: /graph/api/group-list-members | 이러한 데이터는 외부 데이터베이스에 저장하지 않습니다. | [82df726e-0de2-46af-b4f1-0645fd95fc97](../azure/82df726e-0de2-46af-b4f1-0645fd95fc97.md) |
>| User.Read.All | 응용 프로그램 | 이 범위를 사용하여 사용자가 웹 사이트에서 참가한 팀을 볼 수 있도록 사용자의 가입 채널을 가져옵니다. 참조: /graph/api/user-list-joinedteams | 이러한 데이터는 데이터베이스에 저장하지 않습니다. | [82df726e-0de2-46af-b4f1-0645fd95fc97](../azure/82df726e-0de2-46af-b4f1-0645fd95fc97.md) |
>| User.ReadBasic.All | 위임 | 이 범위를 사용하여 OAuth 로그인을 사용하도록 설정하고 사용자의 AAD ID, 액세스 토큰 및 새로 고침 토큰을 수집합니다. 참조: /graph/auth-v2-user | 사용자가 OAuth를 사용하여 웹 사이트에 로그인할 수 있도록 사용자의 AAD ID, 액세스 토큰 및 새로 고침 토큰을 데이터베이스에 저장합니다. | [82df726e-0de2-46af-b4f1-0645fd95fc97].. /azure/82df726e-0de2-46af-b4f1-0645fd95fc97.md) |
>| offline_access | 위임 | 이 범위를 사용하여 사용자 상호 작용 없이 인증된 사용자의 액세스 토큰을 새로 고칠 수 있도록 새로 고침 토큰을 가져옵니다. 참조: /azure/active-directory/develop/v2-permissions-and-consent#offline_access | 사용자 상호 작용 없이 액세스 토큰을 새로 고칠 수 있도록 데이터베이스에 새로 고침 토큰을 저장합니다. | [82df726e-0de2-46af-b4f1-0645fd95fc97](../azure/82df726e-0de2-46af-b4f1-0645fd95fc97.md) |


#### <a name="non-microsoft-services-used"></a>사용되지 않는 Microsoft 서비스

앱이 비 Microsoft 서비스와 조직 데이터를 전송하거나 공유하는 경우 앱에서 사용하는 비 Microsoft 서비스, 전송되는 데이터를 나열하고 앱이 이 정보를 전송해야 하는 이유에 대한 근거를 포함합니다.

>Microsoft 서비스 사용되지 않습니다.

#### <a name="data-access-via-bots"></a>봇을 통한 데이터 액세스

이 앱에 봇 또는 메시징 확장이 포함된 경우 최종 사용자 식별 정보(EUII)에 액세스하여 팀 구성원의 명단(이름, 성, 표시 이름, 전자 메일 주소)에 액세스하거나 추가한 채팅을 할 수 있습니다. 이 앱이 이 기능을 사용하나요?

>EUII에 액세스하지 않습니다.


#### <a name="telemetry-data"></a>원격 분석 데이터

이 애플리케이션의 원격 분석 또는 로그에 OII(조직 식별 정보) 또는 EUII(최종 사용자 식별 정보)가 표시됩니까? 그렇다면 저장되는 데이터와 보존 및 제거 정책이 무엇인지 설명합니다.

>애플리케이션 원격 분석 또는 로그에 OII 또는 EUII가 표시되지 않습니다.

#### <a name="organizational-controls-for-data-stored-by-partner"></a>파트너가 저장한 데이터에 대한 조직 제어

조직의 관리자가 파트너 시스템에서 정보를 제어하는 방법을 설명하시겠습니까? 예: 삭제, 보존, 감사, 보관, 최종 사용자 정책 등

>데이터베이스의 모든 데이터가 암호화됩니다. 데이터베이스 데이터의 백업은 내부 운영 정책에 따라 일정 기간 동안 수행 및 저장됩니다. 사용자가 이 서비스를 취소하는 경우 법률에 규정된 스토리지 의무를 이행하는 데 필요한 범위를 제외하고 사용자의 사용자 정보를 지체 없이 삭제합니다. 자세한 내용은 다음과 같습니다. https://app.researchr.work/privacypolicy

#### <a name="human-review-of-organizational-information"></a>조직 정보에 대한 사용자 검토

인간은 이 앱에서 수집하거나 저장하는 조직 식별 정보(OII) 데이터를 검토하거나 분석하는 데 관여합니까?

>아니요

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="mcas"

[Microsoft Cloud App Security](https://www.microsoft.com/enterprise-mobility-security/cloud-app-security) 카탈로그의 정보는 다음과 같습니다.

<iframe height='1020' title='Microsoft Cloud App Security 정보' src='https://appmcasinfoprod.azurewebsites.net/#/dashboard/' frameborder='no'></iframe>

<a href="https://appmcasinfoprod.azurewebsites.net/#/dashboard/" target="_blank">새 탭에서 보기</a>

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="identity"

### <a name="identity-information"></a>ID 정보

이 정보는 이 앱이 인증, 권한 부여, 애플리케이션 등록 모범 사례 및 기타 ID 조건을 처리하는 방법에 대한 KBE&#26666;&#24335;&#20250;&#31038; 제공되었습니다.

| **정보** | **응답** |
|:----------------|:-------------|
| Microsoft Identify Platform(Azure AD)과 통합하시겠습니까?  | 아니요 |

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end
