---
title: SalesTim에 대한 애플리케이션 정보
ms.author: elmalova
author: elenamalova
ms.date: 06/24/2021
ms.topic: article
ms.service: attestation
certification_type: attested
description: SalesTim에 사용할 수 있는 모든 보안 및 규정 준수 정보, 데이터 처리 정책, Microsoft Cloud App Security 앱 카탈로그 정보 및 CSA STAR 레지스트리의 보안/규정 준수 정보입니다.
zone_pivot_groups: app-info-data-mcas-identity
ms.openlocfilehash: 9fce7871fc306b19170cddb2d1524ef7a82a01f4
ms.sourcegitcommit: 7a7de9f48f6cf5b6acd435412477b6a59127f19a
ms.translationtype: MT
ms.contentlocale: ko-KR
ms.lasthandoff: 05/05/2022
ms.locfileid: "65222439"
---
# <a name="application-information-for-salestim-by-salestim"></a>SalesTim by SalesTim에 대한 애플리케이션 정보

<p></p>
<img alt="Publisher Attestation: The information on this page is based on a self-assessment report provided by the app developer on the security, compliance, and data handling practices followed by this app. Microsoft makes no guarantees regarding the accuracy of the information." src="../media/attested.png" width="650" />
<p>개발자가 마지막으로 업데이트한 날짜: 2021년 6월 24일</p>

* <a href="https://appsource.microsoft.com/product/web-apps/salestim.salestim" target="_blank">AppSource에서 보기</a>

::: zone pivot="general"

### <a name="general-information"></a>일반 정보

SalesTim에서 Microsoft에 제공한 정보:

| **정보** | **응답** |
|:----------------|:-------------|
| 앱 이름 | SalesTim |
| ID | salestim.salestim |
| 파트너 회사 이름 | SalesTim |
| 파트너 웹 사이트의 URL | [https://salestim.com](https://salestim.com) |
| 개인 정보 취급 방침의 URL | [https://www.salestim.com/legal/privacy/](https://www.salestim.com/legal/privacy/) |
| 사용 약관 URL | [https://www.salestim.com/legal/tos/](https://www.salestim.com/legal/tos/) |

 [!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="data"

### <a name="how-the-app-handles-data"></a>앱에서 데이터를 처리하는 방법

이 정보는 SalesTim에서 이 앱이 조직 데이터를 수집하고 저장하는 방법과 앱이 수집하는 데이터에 대해 조직에서 가질 컨트롤에 대해 제공되었습니다.

#### <a name="data-access-using-microsoft-graph"></a>Microsoft Graph 사용하여 데이터 액세스

이 앱[에 필요한 Microsoft Graph 권한을](/graph/permissions-reference) 나열합니다.

>| **사용 권한**  | **권한 유형(위임/애플리케이션)** | **데이터가 수집되었나요? 수집에 대한 정당성?** | **데이터가 저장되어 있나요? 저장에 대한 근거?** | **앱 ID Azure AD** |
>|:----------------|:--------------------|:---------------------------------------------------|:--------------------------|:--------------------------|
>| AppCatalog.ReadWrite.All | 위임 | 아니요 | 앱이 회사 앱 카탈로그에 자체 패키지를 설치하고 업데이트하도록 허용합니다. | 2a651f59-97ce-42bb-97d7-cf7a2af4b635 |
>| Directory.AccessAsUser.All | 위임 | 프로필 데이터가 아닌 일부 사용자 ID만 저장할&#8217;있습니다. | 사용자가 워크플로에서 승인자를 선택하는 등 애플리케이션의 다양한 위치에서 다른 사용자를 선택할 수 있습니다. | 2a651f59-97ce-42bb-97d7-cf7a2af4b635 |
>| Group.ReadWrite.All | 위임 | 그룹/팀 ID만 저장할&#8217;, 그룹/팀 콘텐츠를 저장하지&#8217;. | 앱에서 로그인한 사용자를 대신하여 그룹을 만들고 모든 그룹 속성 및 멤버 자격을 읽을 수 있습니다. 또한 그룹 소유자가 그룹을 관리하고 그룹 구성원이 그룹 콘텐츠를 업데이트할 수 있도록 허용합니다. | 2a651f59-97ce-42bb-97d7-cf7a2af4b635 |
>| Mail.Send | 위임 | 알림 날짜, 받는 사람(ID만 해당), 요청 ID와 같은 이 작업의 메타데이터를 다시 저장할&#8217;있습니다. | 승인 워크플로 중에 앱이 예를 들어 알림 이메일을 보낼 수 있도록 허용합니다. | 2a651f59-97ce-42bb-97d7-cf7a2af4b635 |
>| Sites.ReadWrite.All | 위임 | 일부 Azure 서비스를 사용하여 데이터, 특히 Azure 및 Cosmos DB의 Redis를 저장합니다. | 앱에서 팀 프로비저닝 프로세스 중에 팀과 연결된 드라이브(파일 및 폴더)를 관리할 수 있습니다. | 2a651f59-97ce-42bb-97d7-cf7a2af4b635 |
>| User.Read.All | 위임 | 프로필 데이터가 아닌 일부 사용자 ID만 저장할&#8217;있습니다. | 앱에서 모든 사용자의 프로필 속성, 보고서 및 관리자의 전체 집합을 읽을 수 있습니다. 특히 대상 그룹 대상 지정 프로세스 중에 현재 사용자 프로필을 기반으로 일부 콘텐츠를 필터링하는 데 사용됩니다. | 2a651f59-97ce-42bb-97d7-cf7a2af4b635 |
>| offline_access | 위임 | 아니요 | 앱에서 일부 백그라운드 작업 및 작업을 사용자로 수행할 수 있습니다. | 2a651f59-97ce-42bb-97d7-cf7a2af4b635 |


#### <a name="non-microsoft-services-used"></a>사용되지 않는 Microsoft 서비스

앱이 비 Microsoft 서비스와 조직 데이터를 전송하거나 공유하는 경우 앱에서 사용하는 비 Microsoft 서비스, 전송되는 데이터를 나열하고 앱이 이 정보를 전송해야 하는 이유에 대한 근거를 포함합니다.

>| **모든 비 Microsoft 서비스 OII가** |  **어떤 OII가 전송됩니까?** | **OII 전송에 대한 근거는 무엇인가요?** |
>|:-------------------|:--------------------------|:--------------------------|
>| Intercom을 주요 지원 애플리케이션으로 사용하고 있습니다. Intercom에는 다음과 같은 몇 가지 기본 사용자 프로필 정보가 포함될 수 있습니다. https://developers.salestim.com/platform/datamanagement.html#support-data | 회사명 | GitHub API를 사용하여 프로덕션 환경에서 자동으로 문제를 생성합니다. 또한 몇 가지 기술 로그를 GitHub 저장합니다(여기서 https://developers.salestim.com/platform/datamanagement.html#error-reporting-data)설명한 대로). 이러한 문제 및 로그에는 몇 가지 기본 사용자 프로필 정보가 포함될 수 있습니다. 이러한 문제 및 로그는 15일마다 자동으로 삭제됩니다. |



#### <a name="telemetry-data"></a>원격 분석 데이터

이 애플리케이션의 원격 분석 또는 로그에 OII(조직 식별 정보) 또는 EUII(최종 사용자 식별 정보)가 표시됩니까? 그렇다면 저장되는 데이터와 보존 및 제거 정책이 무엇인지 설명합니다.

>수집된 모든 데이터는 여기에 설명되어 있습니다 https://developers.salestim.com/platform/datamanagement.html#application-data . 설명된 대로 로그는 15일 동안 일시적으로 저장되고 자동으로 삭제됩니다.

#### <a name="organizational-controls-for-data-stored-by-partner"></a>파트너가 저장한 데이터에 대한 조직 제어

조직의 관리자가 파트너 시스템에서 정보를 제어하는 방법을 설명하시겠습니까? 예: 삭제, 보존, 감사, 보관, 최종 사용자 정책 등

>대부분의 데이터는 Azure Cosmos DB에 저장됩니다.
프로덕션 환경에 대한 액세스는 두 사람으로 제한되며 이러한 관리자 계정은 MFA가 적용됩니다.
이러한 계정은 전용이며 회사 계정과 다릅니다.
데이터는 사용 중인 모든 Azure 서비스에서 미사용 시 암호화됩니다.
프로덕션 환경에 대한 배포는 두 사람만 변경 내용을 승인할 수 있는 GitHub 환경의 전용 보호된 분기를 통해 자동화됩니다.

#### <a name="human-review-of-organizational-information"></a>조직 정보에 대한 사용자 검토

인간은 이 앱에서 수집하거나 저장하는 조직 식별 정보(OII) 데이터를 검토하거나 분석하는 데 관여합니까?

>예

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="mcas"

[Microsoft Cloud App Security](https://www.microsoft.com/enterprise-mobility-security/cloud-app-security) 카탈로그의 정보는 다음과 같습니다.

<iframe height='1020' title='Microsoft Cloud App Security 정보' src='https://appmcasinfoprod.azurewebsites.net/#/dashboard/35853' frameborder='no'></iframe>

<a href="https://appmcasinfoprod.azurewebsites.net/#/dashboard/35853" target="_blank">새 탭에서 보기</a>

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="identity"

### <a name="identity-information"></a>ID 정보

이 정보는 SalesTim에서 이 앱이 인증, 권한 부여, 애플리케이션 등록 모범 사례 및 기타 ID 조건을 처리하는 방법에 대해 제공했습니다.

| **정보** | **응답** |
|:----------------|:-------------|
| Microsoft Identify Platform(Azure AD)과 통합하시겠습니까?  | 예 |
| Microsoft ID 플랫폼 통합 검사 목록에 설명된 모든 적용 가능한 모범 사례를 검토하고 준수했나요?  | 예 |
| 앱이 인증에 MSAL(Microsoft 인증 라이브러리)을 사용하나요? | 예 |
| 앱에서 조건부 액세스 정책을 지원하나요? | 예 |
| 지원되는 정책 유형 나열 | MFA, 위치 조건 |
| 앱이 시나리오에 대한 최소 권한 권한을 요청하나요? | 예 |
| 앱의 정적으로 등록된 권한은 앱이 동적으로 그리고 증분적으로 요청할 권한을 정확하게 반영하나요? | 예 |
| 앱이 다중 테넌시를 지원하나요? | 예 |
| 앱에 기밀 클라이언트가 있나요? | 예 |
| 앱에 등록된 리디렉션 URI(통합 리소스 식별자)를 모두 소유하고 있나요? | 예 |
| 앱의 경우 무엇을 사용하지 않도록 해야 할까요? | ,<br/>- SPA에 필요한 경우가 아니면 OAuth2 암시적 Flow<br/> |
| 앱이 웹 API를 노출하나요? | 예 |
| 권한 모델은 클라이언트 앱이 적절한 동의를 받는 경우에만 호출이 성공하도록 허용하나요? | 예 |
| 앱에서 미리 보기 API를 사용하나요? | 아니요 |
| 앱에서 사용되지 않는 API를 사용하나요? | 아니요 |

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end
