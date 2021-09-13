---
title: Officeatwork의 업로더에 대한 응용 프로그램 정보
ms.author: elmalova
author: elenamalova
ms.date: 06/23/2021
ms.topic: article
ms.service: attestation
certification_type: attested
description: 업로더, 데이터 처리 정책, CSA STAR 레지스트리의 Microsoft Cloud App Security 앱 카탈로그 정보 및 보안/규정 준수 정보에 대해 사용할 수 있는 모든 보안 및 규정 준수 정보
zone_pivot_groups: app-info-data-mcas-identity
ms.openlocfilehash: c42d6784cea1a1ce867c2935b91f30fc3ac2a1f8
ms.sourcegitcommit: d85595f6518d8d05f0aee75380f51659908b6bcb
ms.translationtype: MT
ms.contentlocale: ko-KR
ms.lasthandoff: 09/12/2021
ms.locfileid: "59284893"
---
# <a name="uploader"></a>업로더

<p></p>
<img alt="Publisher Attestation: The information on this page is based on a self-assessment report provided by the app developer on the security, compliance, and data handling practices followed by this app. Microsoft makes no guarantees regarding the accuracy of the information." src="../media/attested.png" width="650" />
<p>개발자가 마지막으로 업데이트한 날짜: 2021년 6월 23일</p>

* <a href="https://appsource.microsoft.com/product/web-apps/officeatwork-ag.uploader" target="_blank">AppSource의 보기</a>

::: zone pivot="general"

### <a name="general-information"></a>일반 정보

Officeatwork에서 Microsoft에 제공하는 정보:

| **정보** | **응답** |
|:----------------|:-------------|
| 앱 이름 | 업로더 |
| ID | officeatwork-ag.uploader |
| 파트너 회사 이름 | officeatwork |
| 파트너 웹 사이트의 URL | [https://www.officeatwork.com](https://www.officeatwork.com) |
| 개인 정보 취급 방침의 URL | [https://links.officeatwork.com/officeatwork-privacystatement](https://links.officeatwork.com/officeatwork-privacystatement) |
| 사용 약관 URL | [https://links.officeatwork.com/officeatwork-licenseterms](https://links.officeatwork.com/officeatwork-licenseterms) |

 [!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="data"

### <a name="how-the-app-handles-data"></a>앱이 데이터를 처리하는 방법

이 정보는 이 앱이 조직 데이터를 수집 및 저장하는 방법 및 앱이 수집하는 데이터를 통해 조직이 제어할 수 있는 방법에 대한 정보를 Officeatwork에서 제공합니다.

#### <a name="data-access-using-microsoft-graph"></a>Microsoft 365를 사용한 데이터 Graph

이 앱에 [Graph Microsoft 사용자 권한을](https://docs.microsoft.com/graph/permissions-reference) 나열합니다.

>| **사용 권한**  | **사용 권한 유형(위임/응용 프로그램)** | **데이터가 수집하나요? 수집의 사당성** | **데이터가 저장되어 있나요? 저장 사정이 있나요?** | **Azure AD 앱 ID** |
>|:----------------|:--------------------|:---------------------------------------------------|:--------------------------|:--------------------------|
>| Files.ReadWrite.All | 위임 | 데이터가 저장되지 않습니다. | OneDrive: 사용자의 데이터 원본에 데이터를 읽고 쓸 수 OneDrive. | f5c9f179-b9a5-4364-8f99-18d203b902ad |
>| Group.ReadWrite.All | 위임 | 데이터가 저장되지 않습니다. | Teams: 그룹에 데이터를 읽고 쓰는 데 사용할 수 있습니다. | f5c9f179-b9a5-4364-8f99-18d203b902ad |
>| GroupMember.Read.All | 위임 | 데이터가 저장되지 않습니다. | SharePoint 온라인 - 보안 그룹 지원: 앱이 그룹을 나열하고, 기본 그룹 속성을 읽고, 로그인한 사용자가 액세스할 수 있는 모든 그룹의 구성원 자격을 읽을 수 있도록 허용합니다. | f5c9f179-b9a5-4364-8f99-18d203b902ad |
>| Sites.Read.All | 위임 | 데이터가 저장되지 않습니다. | SharePoint 온라인: SharePoint 온라인에서 데이터를 읽을 수 있도록 로그인한 사용자가 액세스할 수 있습니다. 온라인에서 데이터 업로드를 SharePoint | f5c9f179-b9a5-4364-8f99-18d203b902ad |
>| User.Read | 위임 | 데이터가 저장되지 않습니다. | Sing-In: officeatwork 앱에서 사용자의 기본 속성을 읽을 수 있도록 합니다. | f5c9f179-b9a5-4364-8f99-18d203b902ad |
>| User.Read.All | 위임 | 데이터가 저장되지 않습니다. | Teams: 사용자가 속한 그룹을 찾아야 합니다. | f5c9f179-b9a5-4364-8f99-18d203b902ad |
>| offline_access | 위임 | 데이터가 저장되지 않습니다. | Sing-In: 새로 고침 토큰을 통해 자동 로그인을 사용하도록 설정하려면 사용자가 officeatwork 앱을 실행하기 전마다 수동으로 로그인해야 합니다. 이 범위는 SSO를 사용할 수 없는 호스트 응용 프로그램에만 필요합니다. | f5c9f179-b9a5-4364-8f99-18d203b902ad |
>| openid | 위임 | 데이터가 저장되지 않습니다. | Sing-In: 사용자가 조직 및/또는 Microsoft 계정을 사용하여 officeatwork 앱에 로그인할 수 있도록 합니다. | f5c9f179-b9a5-4364-8f99-18d203b902ad |
>| 프로필 | 위임 | 데이터가 저장되지 않습니다. | Sing-In: officeatwork 앱에서 로그인한 사용자를 표시하기 위한 것입니다. 이렇게 하면 officeatwork 앱에 로그인하는 데 사용된 계정을 사용자에게 확인/확인하는 데 도움이 됩니다. | f5c9f179-b9a5-4364-8f99-18d203b902ad |

#### <a name="data-access-using-other-microsoft-apis"></a>다른 Microsoft API를 사용한 데이터 액세스

기본 제공 앱 및 추가 Microsoft 365 Microsoft Graph 기타 Microsoft API를 사용하여 OII(조직 식별 가능 정보)를 수집하거나 처리합니다. 이 앱에서 사용하는 Microsoft API를 Graph Microsoft API를 나열합니다.

>| **API** |  **OII가 수집하나요?** |  **수집되는 OII는 무엇입니까?** | **OII 수집의 사당성** | **OII가 저장되어 있나요?** | **OII 저장의 사당성** |
>|:-------------------|:-------------------|:--------------------------|:--------------------------|:---------------------------------------------------|:--------------------------|
>| SharePoint REST API | 아니요 |  |  |  |  |

#### <a name="non-microsoft-services-used"></a>비영구 Microsoft 서비스

앱이 Microsoft가 아닌 서비스로 조직 데이터를 전송하거나 공유하는 경우 앱에서 사용하는 비 Microsoft 서비스, 전송되는 데이터를 나열하고 앱이 이 정보를 전송해야 하는 이유에 대한 사유를 포함합니다.

>비영구 Microsoft 서비스 사용되지 않습니다.



#### <a name="telemetry-data"></a>원격 분석 데이터

이 응용 프로그램의 원격 분석 또는 로그에 OII(조직 식별 정보) 또는 EUII(최종 사용자 식별 정보)가 나타나나요? 그렇다면 저장되는 데이터와 보존 및 제거 정책에 대해 설명하세요.

>예, 이벤트는 oid 및 tenantId를 포함하며 Azure AppInsights로 전송됩니다. 이벤트는 90일 후에 자동으로 삭제됩니다. 고객이 이 데이터를 삭제하려면 개인 정보 취급 방침에 제공된 링크를 사용하여 해당 데이터 삭제를 시작할 수 있습니다.

#### <a name="organizational-controls-for-data-stored-by-partner"></a>파트너가 저장한 데이터에 대한 조직 제어

조직의 관리자가 파트너 시스템에서 정보를 제어하는 방법에 대해 설명하는 방법 삭제, 보존, 감사, 보관, 최종 사용자 정책 등

>응용 프로그램 설정 데이터(기능 플래그, 조직 표시 이름, 테넌트Id, 관리자 목록)는 Azure Cosmos DB 인스턴스(테넌트당 하나의 파일)에 저장됩니다. DB 파일은 암호화되며 선택한 사무실 작업 엔지니어 및 지원 직원으로만 액세스가 제한됩니다. 고객은 관리 센터 Web App을 사용하여 officeatwork 앱 설정 데이터에 액세스하고 데이터를 조작할 수 있습니다.

#### <a name="human-review-of-organizational-information"></a>조직 정보의 인적 검토

사람이 이 앱에서 수집하거나 저장하는 OII(조직 식별 정보) 데이터를 검토하거나 분석하는 데 관여하나요?

>아니요

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="mcas"

Microsoft Cloud App Security [카탈로그의](https://www.microsoft.com/enterprise-mobility-security/cloud-app-security) 정보가 아래에 표시됩니다.

<iframe height='1020' title='Microsoft Cloud App Security 정보' src='https://appmcasinfoprod.azurewebsites.net/#/dashboard/35750' frameborder='no' style='width: 100%;'></iframe>

<a href="https://appmcasinfoprod.azurewebsites.net/#/dashboard/35750" target="_blank">새 탭에서 보기</a>

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="identity"

### <a name="identity-information"></a>ID 정보

이 정보는 Officeatwork에서 이 앱이 인증, 권한 부여, 응용 프로그램 등록 모범 사례 및 기타 ID 조건을 처리하는 방법에 대해 제공했습니다.

| **정보** | **응답** |
|:----------------|:-------------|
| Microsoft Identify Platform(Azure AD)과 통합하나요?  | 예 |
| 통합 검사 목록에 설명된 적용 가능한 모든 모범 사례를 Microsoft ID 플랫폼 준수하나요?  | 예 |
| 앱에서 인증에 MSAL(Microsoft 인증 라이브러리)을 사용하나요? | 아니요 |
| 앱에서 조건부 액세스 정책을 지원하나요? | 예 |
| 지원되는 정책 유형 나열 | 보안 기본값 |
| 앱에서 시나리오에 대한 최소 권한 권한을 요청하나요? | 예 |
| 앱의 정적으로 등록된 사용 권한은 앱이 동적으로 그리고 증분적으로 요청하는 권한을 정확하게 반영하나요? | 아니요 |
| 앱에서 다중 테넌시를 지원하나요? | 예 |
| 앱에 기밀 클라이언트가 있나요? | 예 |
| 앱에 등록된 리디렉션 URI(통합 리소스 식별자)를 모두 소유하고 있나요? | 예 |
| 앱의 경우 어떻게 사용하지 않도록 해야 하나요? | - 와일드카드 리디렉션 URIS,<br/>- OAuth2 암시적 Flow SPA에 필요하지 않은 경우<br/>- 리소스 소유자 암호 자격 증명(ROPC) 흐름 |
| 앱에서 웹 API를 노출하나요? | 아니요 |
| 앱에서 미리 보기 API를 사용하나요? | 아니요 |
| 앱에서 사용되지 않는 API를 사용하나요? | 아니요 |

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end
