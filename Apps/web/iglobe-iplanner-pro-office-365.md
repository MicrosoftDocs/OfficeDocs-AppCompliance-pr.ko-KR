---
title: iPlanner Pro Office 365 대한 애플리케이션 정보
ms.author: elmalova
author: elenamalova
ms.date: 06/22/2021
ms.topic: article
ms.service: attestation
certification_type: attested
description: iPlanner Pro Office 365 사용 가능한 모든 보안 및 규정 준수 정보, 데이터 처리 정책, Microsoft Cloud App Security 앱 카탈로그 정보 및 CSA STAR 레지스트리의 보안/규정 준수 정보입니다.
zone_pivot_groups: app-info-data-mcas-identity
ms.openlocfilehash: c934c8d519163934f27b39a1f52f8c5b343cdb82
ms.sourcegitcommit: 7a7de9f48f6cf5b6acd435412477b6a59127f19a
ms.translationtype: MT
ms.contentlocale: ko-KR
ms.lasthandoff: 05/05/2022
ms.locfileid: "65228006"
---
# <a name="application-information-for-iplanner-pro-office-365"></a>iPlanner Pro Office 365 대한 애플리케이션 정보

<p></p>
<img alt="Publisher Attestation: The information on this page is based on a self-assessment report provided by the app developer on the security, compliance, and data handling practices followed by this app. Microsoft makes no guarantees regarding the accuracy of the information." src="../media/attested.png" width="650" />
<p>개발자가 마지막으로 업데이트한 날짜: 2021년 6월 22일</p>

* <a href="https://appsource.microsoft.com/product/web-apps/17859280.iplannerpro" target="_blank">AppSource에서 보기</a>

::: zone pivot="general"

### <a name="general-information"></a>일반 정보

iGlobe에서 Microsoft에 제공한 정보:

| **정보** | **응답** |
|:----------------|:-------------|
| 앱 이름 | iPlanner Pro Office 365 |
| ID | 17859280.iplannerpro |
| 파트너 회사 이름 | iGlobe |
| 파트너 웹 사이트의 URL | [https://www.iglobecrm.com](https://www.iglobecrm.com) |
| 개인 정보 취급 방침의 URL | [https://www.iglobecrm.com/content/legal-information](https://www.iglobecrm.com/content/legal-information) |
| 사용 약관 URL | [https://iglobecrm.com/content/end-user-license-agreement-ig...](https://iglobecrm.com/content/end-user-license-agreement-iglobe-iplanner-add-ins) |

 [!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="data"

### <a name="how-the-app-handles-data"></a>앱에서 데이터를 처리하는 방법

이 정보는 iGlobe에서 이 앱이 조직 데이터를 수집하고 저장하는 방법과 앱이 수집하는 데이터에 대해 조직에서 가질 컨트롤에 대해 제공되었습니다.

#### <a name="data-access-using-microsoft-graph"></a>Microsoft Graph 사용하여 데이터 액세스

이 앱[에 필요한 Microsoft Graph 권한을](/graph/permissions-reference) 나열합니다.

>| **사용 권한**  | **권한 유형(위임/애플리케이션)** | **데이터가 수집되었나요? 수집에 대한 정당성?** | **데이터가 저장되어 있나요? 저장에 대한 근거?** | **앱 ID Azure AD** |
>|:----------------|:--------------------|:---------------------------------------------------|:--------------------------|:--------------------------|
>| Calendars.ReadWrite | 위임 | 애플리케이션 데이터베이스에 데이터가 저장되지 않습니다. | Planner 작업을 얻고 새 작업을 추가하려면 특정 사용자에 대한 버킷 및 스윔 라인을 업데이트합니다. | a6f5c2f4-0bc2-48bf-8afe-6c93583a152b |
>| Contacts.ReadWrite | 위임 | 애플리케이션 데이터베이스에 데이터가 저장되지 않습니다. | 작업 기한에 대한 사용자 일정에 약속을 만들려면 | a6f5c2f4-0bc2-48bf-8afe-6c93583a152b |
>| Directory.AccessAsUser.All | 위임 | 애플리케이션 데이터베이스에 데이터가 저장되지 않습니다. | 앱에서 로그인한 사용자와 디렉터리의 정보에 동일한 액세스 권한을 가질 수 있습니다. | a6f5c2f4-0bc2-48bf-8afe-6c93583a152b |
>| Files.Read | 위임 | 애플리케이션 데이터베이스에 데이터가 저장되지 않습니다. | 파일을 첨부 파일로 액세스하고 작업에 파일을 업로드하려면 | a6f5c2f4-0bc2-48bf-8afe-6c93583a152b |
>| Files.ReadWrite.All | 위임 | 애플리케이션 데이터베이스에 데이터가 저장되지 않습니다. | 선택한 메일에서 메일 제목을 가져옵니다. 앱이 선택한 전자 메일에서 정보를 가져올 수 있도록 하여 설명 필드를 작업 설명에 복사하고 메일 또는 메일 자체의 첨부 파일을 작업에 저장할 수 있습니다. | a6f5c2f4-0bc2-48bf-8afe-6c93583a152b |
>| Group.Read.All | 위임 | 애플리케이션 데이터베이스에 데이터가 저장되지 않습니다. | Planner 작업을 가져와서 새 작업을 추가하면 특정 사용자에 대한 버킷 및 스윔 라인이 업데이트됩니다. | a6f5c2f4-0bc2-48bf-8afe-6c93583a152b |
>| User.Read | 위임 | 애플리케이션 데이터베이스에 데이터가 저장되지 않습니다. | Planner 작업을 얻고 새 작업을 추가하려면 특정 사용자에 대한 버킷 및 스윔 라인을 업데이트합니다. | a6f5c2f4-0bc2-48bf-8afe-6c93583a152b |
>| User.ReadBasic.All | 위임 | 애플리케이션 데이터베이스에 데이터가 저장되지 않습니다. | 사용 권한을 확인하고 Planner 작업을 가져와서 새 작업을 추가하면 특정 사용자에 대한 버킷 및 스윔 라인이 업데이트됩니다. | a6f5c2f4-0bc2-48bf-8afe-6c93583a152b |
>| 프로필 | 위임 | 애플리케이션 데이터베이스에 데이터가 저장되지 않습니다. | Planner 작업을 얻고 새 작업을 추가하려면 특정 사용자에 대한 버킷 및 스윔 라인을 업데이트합니다. | a6f5c2f4-0bc2-48bf-8afe-6c93583a152b |

#### <a name="data-access-using-other-microsoft-apis"></a>다른 Microsoft API를 사용하여 데이터 액세스

Microsoft 365 기본 제공되는 앱 및 추가 기능은 Microsoft Graph 이외의 추가 Microsoft API를 사용하여 OII(조직 식별 정보)를 수집하거나 처리할 수 있습니다. 이 앱에서 사용하는 Microsoft Graph 이외의 Microsoft API를 나열합니다.

>| **API** |  **OII가 수집되었나요?** |  **수집되는 OII는 무엇인가요?** | **OII를 수집하기 위한 근거는 무엇인가요?** | **OII가 저장되어 있나요?** | **OII를 저장하기 위한 근거는 무엇인가요?** |
>|:-------------------|:-------------------|:--------------------------|:--------------------------|:---------------------------------------------------|:--------------------------|
>| Exchange - EWS. AccessAsUser.All | 아니요 |  |  |  |  |
>| Exchange - Mail.Read.All | 아니요 |  |  |  |  |
>| SharePoint - AllSites.Manage | 아니요 |  |  |  |  |
>| SharePoint - AllSites.Read | 아니요 |  |  |  |  |
>| SharePoint - AllSites.Write | 아니요 |  |  |  |  |
>| SharePoint - MyFiles.Read | 아니요 |  |  |  |  |
>| SharePoint - MyFiles.Write | 아니요 |  |  |  |  |

#### <a name="non-microsoft-services-used"></a>사용되지 않는 Microsoft 서비스

앱이 비 Microsoft 서비스와 조직 데이터를 전송하거나 공유하는 경우 앱에서 사용하는 비 Microsoft 서비스, 전송되는 데이터를 나열하고 앱이 이 정보를 전송해야 하는 이유에 대한 근거를 포함합니다.

>Microsoft 서비스 사용되지 않습니다.



#### <a name="telemetry-data"></a>원격 분석 데이터

이 애플리케이션의 원격 분석 또는 로그에 OII(조직 식별 정보) 또는 EUII(최종 사용자 식별 정보)가 표시됩니까? 그렇다면 저장되는 데이터와 보존 및 제거 정책이 무엇인지 설명합니다.

>iGlobe는 데이터를 수집하여 효과적으로 작동하고 제품 및 서비스에 대한 최상의 환경을 제공합니다. 라이선스의 경우: 무료 추가 기능을 배포하거나 평가판 구독을 만들거나 구독을 구매하는 경우와 같이 조직&#8217;라이선스 계정을 관리하기 위해 수집된 데이터입니다. 다음 정보가 수집됩니다. 
- 재무 목적: 회사 이름 및 주소
- 구독한 사용자: 사용자 이름 및 전자 메일

#### <a name="organizational-controls-for-data-stored-by-partner"></a>파트너가 저장한 데이터에 대한 조직 제어

조직의 관리자가 파트너 시스템에서 정보를 제어하는 방법을 설명하시겠습니까? 예: 삭제, 보존, 감사, 보관, 최종 사용자 정책 등

>모든 데이터는 고객의 테넌트에 있습니다. 애플리케이션 데이터가 저장되지 않습니다. 최신 추가 기능은 샌드박스 브라우저에서 실행되며, 프로세스&#8221; &#8220;. Microsoft 서비스 사용하여 사용자 데이터와 상호 작용합니다. 추가 기능은 사용자가 작업 중인 데이터에만 액세스할 수 있습니다.

#### <a name="human-review-of-organizational-information"></a>조직 정보에 대한 사용자 검토

인간은 이 앱에서 수집하거나 저장하는 조직 식별 정보(OII) 데이터를 검토하거나 분석하는 데 관여합니까?

>아니요

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="mcas"

[Microsoft Cloud App Security](https://www.microsoft.com/enterprise-mobility-security/cloud-app-security) 카탈로그의 정보는 다음과 같습니다.

<iframe height='1020' title='Microsoft Cloud App Security 정보' src='https://appmcasinfoprod.azurewebsites.net/#/dashboard/36163' frameborder='no'></iframe>

<a href="https://appmcasinfoprod.azurewebsites.net/#/dashboard/36163" target="_blank">새 탭에서 보기</a>

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="identity"

### <a name="identity-information"></a>ID 정보

이 정보는 iGlobe에서 이 앱이 인증, 권한 부여, 애플리케이션 등록 모범 사례 및 기타 ID 조건을 처리하는 방법에 대해 제공했습니다.

| **정보** | **응답** |
|:----------------|:-------------|
| Microsoft Identify Platform(Azure AD)과 통합하시겠습니까?  | 예 |
| Microsoft ID 플랫폼 통합 검사 목록에 설명된 모든 적용 가능한 모범 사례를 검토하고 준수했나요?  | 예 |
| 앱이 인증에 MSAL(Microsoft 인증 라이브러리)을 사용하나요? | 아니요 |
| 앱에서 조건부 액세스 정책을 지원하나요? | 예 |
| 지원되는 정책 유형 나열 | 보안 기본값 및 기타 일반적인 정책(예: 레거시 인증 차단* 관리자용 MFA 필요* Azure 관리에 MFA 필요* 모든 사용자에 대해 MFA 필요* |
| 앱이 시나리오에 대한 최소 권한 권한을 요청하나요? | 예 |
| 앱의 정적으로 등록된 권한은 앱이 동적으로 그리고 증분적으로 요청할 권한을 정확하게 반영하나요? | 예 |
| 앱이 다중 테넌시를 지원하나요? | 예 |
| 앱에 기밀 클라이언트가 있나요? | 예 |
| 앱에 등록된 리디렉션 URI(통합 리소스 식별자)를 모두 소유하고 있나요? | 예 |
| 앱이 웹 API를 노출하나요? | 아니요 |
| 앱에서 미리 보기 API를 사용하나요? | 아니요 |
| 앱에서 사용되지 않는 API를 사용하나요? | 아니요 |

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end
