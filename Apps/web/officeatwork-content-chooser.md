---
title: 콘텐츠 선택기용 애플리케이션 정보
ms.author: elmalova
author: elenamalova
ms.date: 06/23/2021
ms.topic: article
ms.service: attestation
certification_type: attested
description: 콘텐츠 선택기, 데이터 처리 정책, Microsoft Cloud App Security 앱 카탈로그 정보 및 CSA STAR 레지스트리의 보안/규정 준수 정보에 사용할 수 있는 모든 보안 및 규정 준수 정보입니다.
zone_pivot_groups: app-info-data-mcas-identity
ms.openlocfilehash: 3c477a04e970c4290ee3552b3d7730de24a52a96
ms.sourcegitcommit: 7a7de9f48f6cf5b6acd435412477b6a59127f19a
ms.translationtype: MT
ms.contentlocale: ko-KR
ms.lasthandoff: 05/05/2022
ms.locfileid: "65225021"
---
# <a name="application-information-for-content-chooser-by-officeatwork"></a>Officeatwork별 콘텐츠 선택기 애플리케이션 정보

<p></p>
<img alt="Publisher Attestation: The information on this page is based on a self-assessment report provided by the app developer on the security, compliance, and data handling practices followed by this app. Microsoft makes no guarantees regarding the accuracy of the information." src="../media/attested.png" width="650" />
<p>개발자가 마지막으로 업데이트한 날짜: 2021년 6월 23일</p>

* <a href="https://appsource.microsoft.com/product/web-apps/officeatwork-ag.content-chooser" target="_blank">AppSource에서 보기</a>

::: zone pivot="general"

### <a name="general-information"></a>일반 정보

Officeatwork에서 Microsoft에 제공하는 정보:

| **정보** | **응답** |
|:----------------|:-------------|
| 앱 이름 | 콘텐츠 선택기 |
| ID | officeatwork-ag.content-chooser |
| 파트너 회사 이름 | officeatwork |
| 파트너 웹 사이트의 URL | [https://www.officeatwork.com](https://www.officeatwork.com) |
| 개인 정보 취급 방침의 URL | [https://links.officeatwork.com/officeatwork-privacystatement](https://links.officeatwork.com/officeatwork-privacystatement) |
| 사용 약관 URL | [https://links.officeatwork.com/officeatwork-licenseterms](https://links.officeatwork.com/officeatwork-licenseterms) |

 [!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="data"

### <a name="how-the-app-handles-data"></a>앱에서 데이터를 처리하는 방법

이 정보는 이 앱이 조직 데이터를 수집하고 저장하는 방법과 앱이 수집하는 데이터에 대해 조직에서 제어하는 방법에 대한 officeatwork에서 제공되었습니다.

#### <a name="data-access-using-microsoft-graph"></a>Microsoft Graph 사용하여 데이터 액세스

이 앱[에 필요한 Microsoft Graph 권한을](/graph/permissions-reference) 나열합니다.

>| **사용 권한**  | **권한 유형(위임/애플리케이션)** | **데이터가 수집되었나요? 수집에 대한 정당성?** | **데이터가 저장되어 있나요? 저장에 대한 근거?** | **앱 ID Azure AD** |
>|:----------------|:--------------------|:---------------------------------------------------|:--------------------------|:--------------------------|
>| Files.ReadWrite.All | 위임 | 데이터가 저장되지 않습니다. | 즐겨찾기: OneDrive 사용자에게 데이터를 읽고 쓸 수 있습니다. | edb24f8f-38af-4b3e-9475-0da243678d5a |
>| Files.ReadWrite.All | 위임 | 데이터가 저장되지 않습니다. | OneDrive: OneDrive 사용자에게 데이터를 읽고 쓸 수 있습니다. | edb24f8f-38af-4b3e-9475-0da243678d5a |
>| Group.ReadWrite.All | 위임 | 데이터가 저장되지 않습니다. | Teams: 데이터를 읽고 그룹에 쓸 수 있습니다. | edb24f8f-38af-4b3e-9475-0da243678d5a |
>| GroupMember.Read.All | 위임 | 데이터가 저장되지 않습니다. | SharePoint Online - 보안 그룹 지원: 앱이 그룹을 나열하고, 기본 그룹 속성을 읽고, 로그인한 사용자가 액세스할 수 있는 모든 그룹의 멤버 자격을 읽을 수 있도록 허용 | edb24f8f-38af-4b3e-9475-0da243678d5a |
>| Sites.Read.All | 위임 | 데이터가 저장되지 않습니다. | SharePoint Online: SharePoint Online에서 데이터를 읽을 수 있도록 합니다. | edb24f8f-38af-4b3e-9475-0da243678d5a |
>| User.Read | 위임 | 데이터가 저장되지 않습니다. | Sing-In: officeatwork 앱이 사용자의 기본 속성을 읽을 수 있도록 합니다. | edb24f8f-38af-4b3e-9475-0da243678d5a |
>| User.Read.All | 위임 | 데이터가 저장되지 않습니다. | Teams: 사용자가 속한 그룹을 확인합니다. | edb24f8f-38af-4b3e-9475-0da243678d5a |
>| offline_access | 위임 | 데이터가 저장되지 않습니다. | Sing-In: 새로 고침 토큰을 통해 자동 로그인을 사용하도록 설정하려면 사용자가 officeatwork 앱을 시작할 때마다 수동으로 로그인해야 합니다. 이 범위는 SSO가 아닌 호스트 애플리케이션에만 필요합니다. | edb24f8f-38af-4b3e-9475-0da243678d5a |
>| openid | 위임 | 데이터가 저장되지 않습니다. | Sing-In: 사용자가 조직 및/또는 Microsoft 계정으로 officeatwork 앱에 로그인할 수 있도록 합니다. | edb24f8f-38af-4b3e-9475-0da243678d5a |
>| 프로필 | 위임 | 데이터가 저장되지 않습니다. | Sing-In: officeatwork 앱에서 로그인한 사용자를 표시합니다. 이렇게 하면 officeatwork 앱에 로그인하는 데 사용된 계정을 사용자에게 확인/확인하는 데 도움이 됩니다. | edb24f8f-38af-4b3e-9475-0da243678d5a |

#### <a name="data-access-using-other-microsoft-apis"></a>다른 Microsoft API를 사용하여 데이터 액세스

Microsoft 365 기본 제공되는 앱 및 추가 기능은 Microsoft Graph 이외의 추가 Microsoft API를 사용하여 OII(조직 식별 정보)를 수집하거나 처리할 수 있습니다. 이 앱에서 사용하는 Microsoft Graph 이외의 Microsoft API를 나열합니다.

>| **API** |  **OII가 수집되었나요?** |  **수집되는 OII는 무엇인가요?** | **OII를 수집하기 위한 근거는 무엇인가요?** | **OII가 저장되어 있나요?** | **OII를 저장하기 위한 근거는 무엇인가요?** |
>|:-------------------|:-------------------|:--------------------------|:--------------------------|:---------------------------------------------------|:--------------------------|
>| SharePoint REST API | 아니요 |  |  |  |  |

#### <a name="non-microsoft-services-used"></a>사용되지 않는 Microsoft 서비스

앱이 비 Microsoft 서비스와 조직 데이터를 전송하거나 공유하는 경우 앱에서 사용하는 비 Microsoft 서비스, 전송되는 데이터를 나열하고 앱이 이 정보를 전송해야 하는 이유에 대한 근거를 포함합니다.

>Microsoft 서비스 사용되지 않습니다.



#### <a name="telemetry-data"></a>원격 분석 데이터

이 애플리케이션의 원격 분석 또는 로그에 OII(조직 식별 정보) 또는 EUII(최종 사용자 식별 정보)가 표시됩니까? 그렇다면 저장되는 데이터와 보존 및 제거 정책이 무엇인지 설명합니다.

>예, 이벤트에는 oid 및 tenantId가 포함되며 Azure AppInsights로 전송됩니다. 이벤트는 90일 후에 자동으로 삭제됩니다. 고객이 이 데이터를 삭제하려는 경우 개인 정보 취급 방침에 제공된 링크를 사용하여 해당 데이터의 삭제를 시작할 수 있습니다.

#### <a name="organizational-controls-for-data-stored-by-partner"></a>파트너가 저장한 데이터에 대한 조직 제어

조직의 관리자가 파트너 시스템에서 정보를 제어하는 방법을 설명하시겠습니까? 예: 삭제, 보존, 감사, 보관, 최종 사용자 정책 등

>애플리케이션 설정 데이터(기능 플래그, 조직 표시 이름, tenantId, 관리자 oids 목록)는 Azure Cosmos DB 인스턴스(테넌트당 하나의 파일)에 저장됩니다. DB 파일은 암호화되며, 액세스는 선택한 Officeatwork 엔지니어 및 지원 직원으로 제한됩니다. 고객은 관리 센터 웹앱을 사용하여 officeatwork 앱 설정 데이터에 액세스하고 조작할 수 있습니다.

#### <a name="human-review-of-organizational-information"></a>조직 정보에 대한 사용자 검토

인간은 이 앱에서 수집하거나 저장하는 조직 식별 정보(OII) 데이터를 검토하거나 분석하는 데 관여합니까?

>아니요

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="mcas"

[Microsoft Cloud App Security](https://www.microsoft.com/enterprise-mobility-security/cloud-app-security) 카탈로그의 정보는 다음과 같습니다.

<iframe height='1020' title='Microsoft Cloud App Security 정보' src='https://appmcasinfoprod.azurewebsites.net/#/dashboard/35751' frameborder='no'></iframe>

<a href="https://appmcasinfoprod.azurewebsites.net/#/dashboard/35751" target="_blank">새 탭에서 보기</a>

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="identity"

### <a name="identity-information"></a>ID 정보

이 정보는 이 앱이 인증, 권한 부여, 애플리케이션 등록 모범 사례 및 기타 ID 조건을 처리하는 방법에 대한 Officeatwork에서 제공되었습니다.

| **정보** | **응답** |
|:----------------|:-------------|
| Microsoft Identify Platform(Azure AD)과 통합하시겠습니까?  | 예 |
| Microsoft ID 플랫폼 통합 검사 목록에 설명된 모든 적용 가능한 모범 사례를 검토하고 준수했나요?  | 예 |
| 앱이 인증에 MSAL(Microsoft 인증 라이브러리)을 사용하나요? | 아니요 |
| 앱에서 조건부 액세스 정책을 지원하나요? | 예 |
| 지원되는 정책 유형 나열 | 보안 기본값 |
| 앱이 시나리오에 대한 최소 권한 권한을 요청하나요? | 예 |
| 앱의 정적으로 등록된 권한은 앱이 동적으로 그리고 증분적으로 요청할 권한을 정확하게 반영하나요? | 아니요 |
| 앱이 다중 테넌시를 지원하나요? | 예 |
| 앱에 기밀 클라이언트가 있나요? | 예 |
| 앱에 등록된 리디렉션 URI(통합 리소스 식별자)를 모두 소유하고 있나요? | 예 |
| 앱의 경우 무엇을 사용하지 않도록 해야 할까요? | - 와일드카드 리디렉션 URI,<br/>- SPA에 필요한 경우가 아니면 OAuth2 암시적 Flow<br/>- ROPC(리소스 소유자 암호 자격 증명) 흐름 |
| 앱이 웹 API를 노출하나요? | 아니요 |
| 앱에서 미리 보기 API를 사용하나요? | 아니요 |
| 앱에서 사용되지 않는 API를 사용하나요? | 아니요 |

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end
