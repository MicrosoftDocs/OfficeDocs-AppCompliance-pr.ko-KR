---
title: LMS365에 대한 애플리케이션 정보
ms.author: elmalova
author: elenamalova
ms.date: 06/23/2021
ms.topic: article
ms.service: attestation
certification_type: certified
description: LMS365에 사용 가능한 모든 보안 및 규정 준수 정보, 데이터 처리 정책, Microsoft Cloud App Security 앱 카탈로그 정보 및 CSA STAR 레지스트리의 보안/규정 준수 정보입니다.
zone_pivot_groups: app-info-data-mcas-identity
ms.openlocfilehash: 7136a0f4a71f54772dc250433686996f2d236a19
ms.sourcegitcommit: 7a7de9f48f6cf5b6acd435412477b6a59127f19a
ms.translationtype: MT
ms.contentlocale: ko-KR
ms.lasthandoff: 05/05/2022
ms.locfileid: "65224992"
---
# <a name="application-information-for-lms365-by-elearningforce-international-aps"></a>ELEARNINGFORCE International Aps의 LMS365에 대한 애플리케이션 정보

<p></p><a href="https://aka.ms/appcertification" alt="This Microsoft 365 Certified app has been reviewed by Microsoft against industry standards and controls for security, compliance, and data handling practices. Where applicable, Microsoft has verified the developer's claims of compliance with reasonable and effective practices." target="_blank"><img alt="Click here for more information on the Microsoft Certified app program." src="../media/certified.png" width="650" /></a>
<p>개발자가 마지막으로 업데이트한 날짜: 2021년 6월 23일</p>

* <a href="https://appsource.microsoft.com/product/web-apps/elearningforce.lms365_spfx" target="_blank">AppSource에서 보기</a>

::: zone pivot="general"

### <a name="general-information"></a>일반 정보

ELEARNINGFORCE International Aps에서 Microsoft에 제공한 정보:

| **정보** | **응답** |
|:----------------|:-------------|
| 앱 이름 | LMS365 |
| ID | elearningforce.lms365_spfx |
| 파트너 회사 이름 | ELEARNINGFORCE International Aps |
| 파트너 웹 사이트의 URL | [https://www.elearningforce.com](https://www.elearningforce.com) |
| 개인 정보 취급 방침의 URL | [https://www.lms365.com/privacy](https://www.lms365.com/privacy) |
| 사용 약관 URL | [https://www.elearningforce.com/LMS365-SaaS-Terms](https://www.elearningforce.com/LMS365-SaaS-Terms) |

 [!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="data"

### <a name="how-the-app-handles-data"></a>앱에서 데이터를 처리하는 방법

이 정보는 ELEARNINGFORCE International Aps에서 이 앱이 조직 데이터를 수집하고 저장하는 방법과 앱이 수집하는 데이터에 대해 조직에서 제어하는 방법에 대해 제공되었습니다.

#### <a name="data-access-using-microsoft-graph"></a>Microsoft Graph 사용하여 데이터 액세스

이 앱[에 필요한 Microsoft Graph 권한을](/graph/permissions-reference) 나열합니다.

>| **사용 권한**  | **권한 유형(위임/애플리케이션)** | **데이터가 수집되었나요? 수집에 대한 정당성?** | **데이터가 저장되어 있나요? 저장에 대한 근거?** | **앱 ID Azure AD** |
>|:----------------|:--------------------|:---------------------------------------------------|:--------------------------|:--------------------------|
>| GroupMember.Read.All | 응용 프로그램 | 없음 | 앱에서 AD 그룹 구성원을 확장할 수 있습니다. 이 멤버는 사용자 그룹을 과정에 등록하는 데 필요합니다. | a1a0b277-0efb-4f00-9661-6d1a3df3cddc |
>| Mail.Send | 위임 | 없음 | 알림을 위해 전자 메일 계정을 구성하는 동안 사용 권한이 동적으로 요청됩니다. 앱에서 알림 전자 메일을 보낼 수 있도록 허용 | a1a0b277-0efb-4f00-9661-6d1a3df3cddc |
>| RoleManagement.Read.Directory | 응용 프로그램 | 없음 | 테넌트 프로비전 중에 앱이 SharePoint 도메인을 가져올 수 있습니다. 도메인은 URL 생성에 사용됩니다. | a1a0b277-0efb-4f00-9661-6d1a3df3cddc |
>| User.Invite.All | 위임 | 없음 | 앱이 현재 로그인한 사용자를 대신하여 외부 사용자를 초대할 수 있도록 허용 | a1a0b277-0efb-4f00-9661-6d1a3df3cddc |
>| User.Read | 위임 | 없음 | 로그인하고 사용자 프로필을 읽습니다. | a1a0b277-0efb-4f00-9661-6d1a3df3cddc |
>| User.Read.All | 위임 | 없음 | 앱에서 현재 로그인한 사용자의 전체 프로필을 읽을 수 있습니다. | a1a0b277-0efb-4f00-9661-6d1a3df3cddc |
>| User.Read.All | 응용 프로그램 | 앱에서 전체 사용자 프로필을 읽을 수 있습니다. 계층 보고서를 작성하기 위해 사용자&#8217; 관리자를 읽는 데 필요한&#8217;. | 다음 개인 데이터는 애플리케이션 내 Learner Management &amp; Manager 대시보드 기능에 사용되는 각 고객의 전용 데이터베이스에 저장됩니다. 계정 이름, 사용자 표시 이름, 전자 메일 주소, 부서, 직종, Office, 국가, 도시, 관리자 ID/전자 메일 | a1a0b277-0efb-4f00-9661-6d1a3df3cddc |
>| 프로필 | 위임 | 없음 | 사용자의 기본 프로필을 봅니다. | a1a0b277-0efb-4f00-9661-6d1a3df3cddc |

#### <a name="data-access-using-other-microsoft-apis"></a>다른 Microsoft API를 사용하여 데이터 액세스

Microsoft 365 기본 제공되는 앱 및 추가 기능은 Microsoft Graph 이외의 추가 Microsoft API를 사용하여 OII(조직 식별 정보)를 수집하거나 처리할 수 있습니다. 이 앱에서 사용하는 Microsoft Graph 이외의 Microsoft API를 나열합니다.

>| **API** |  **OII가 수집되었나요?** |  **수집되는 OII는 무엇인가요?** | **OII를 수집하기 위한 근거는 무엇인가요?** | **OII가 저장되어 있나요?** | **OII를 저장하기 위한 근거는 무엇인가요?** |
>|:-------------------|:-------------------|:--------------------------|:--------------------------|:---------------------------------------------------|:--------------------------|
>| SharePoint | 아니요 |  |  |  |  |

#### <a name="non-microsoft-services-used"></a>사용되지 않는 Microsoft 서비스

앱이 비 Microsoft 서비스와 조직 데이터를 전송하거나 공유하는 경우 앱에서 사용하는 비 Microsoft 서비스, 전송되는 데이터를 나열하고 앱이 이 정보를 전송해야 하는 이유에 대한 근거를 포함합니다.

>Microsoft 서비스 사용되지 않습니다.



#### <a name="telemetry-data"></a>원격 분석 데이터

이 애플리케이션의 원격 분석 또는 로그에 OII(조직 식별 정보) 또는 EUII(최종 사용자 식별 정보)가 표시됩니까? 그렇다면 저장되는 데이터와 보존 및 제거 정책이 무엇인지 설명합니다.

>예, 문제 해결에만 사용되는 Insights Log Analytics 원격 분석/로그를 사용하며 모든 데이터가 삭제된 후 90일 보존 정책이 있습니다.

#### <a name="organizational-controls-for-data-stored-by-partner"></a>파트너가 저장한 데이터에 대한 조직 제어

조직의 관리자가 파트너 시스템에서 정보를 제어하는 방법을 설명하시겠습니까? 예: 삭제, 보존, 감사, 보관, 최종 사용자 정책 등

>LMS365에는 클라이언트 LMS365 데이터베이스에서 개인 데이터를 제거하는 Purge 함수가 장착되어 있습니다.

#### <a name="human-review-of-organizational-information"></a>조직 정보에 대한 사용자 검토

인간은 이 앱에서 수집하거나 저장하는 조직 식별 정보(OII) 데이터를 검토하거나 분석하는 데 관여합니까?

>아니요

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="mcas"

[Microsoft Cloud App Security](https://www.microsoft.com/enterprise-mobility-security/cloud-app-security) 카탈로그의 정보는 다음과 같습니다.

<iframe height='1020' title='Microsoft Cloud App Security 정보' src='https://appmcasinfoprod.azurewebsites.net/#/dashboard/35695' frameborder='no'></iframe>

<a href="https://appmcasinfoprod.azurewebsites.net/#/dashboard/35695" target="_blank">새 탭에서 보기</a>

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="identity"

### <a name="identity-information"></a>ID 정보

이 정보는 ELEARNINGFORCE International Aps에서 이 앱이 인증, 권한 부여, 애플리케이션 등록 모범 사례 및 기타 ID 기준을 처리하는 방법에 대해 제공했습니다.

| **정보** | **응답** |
|:----------------|:-------------|
| Microsoft Identify Platform(Azure AD)과 통합하시겠습니까?  | 예 |
| Microsoft ID 플랫폼 통합 검사 목록에 설명된 모든 적용 가능한 모범 사례를 검토하고 준수했나요?  | 예 |
| 앱이 인증에 MSAL(Microsoft 인증 라이브러리)을 사용하나요? | 예 |
| 앱에서 조건부 액세스 정책을 지원하나요? | 예 |
| 지원되는 정책 유형 나열 | 디바이스 플랫폼, 디바이스 상태, 클라이언트 앱 |
| 앱이 시나리오에 대한 최소 권한 권한을 요청하나요? | 예 |
| 앱의 정적으로 등록된 권한은 앱이 동적으로 그리고 증분적으로 요청할 권한을 정확하게 반영하나요? | 예 |
| 앱이 다중 테넌시를 지원하나요? | 예 |
| 앱에 기밀 클라이언트가 있나요? | 아니요 |
| 앱에 등록된 리디렉션 URI(통합 리소스 식별자)를 모두 소유하고 있나요? | 예 |
| 앱이 웹 API를 노출하나요? | 예 |
| 권한 모델은 클라이언트 앱이 적절한 동의를 받는 경우에만 호출이 성공하도록 허용하나요? | 예 |
| 앱에서 미리 보기 API를 사용하나요? | 아니요 |
| 앱에서 사용되지 않는 API를 사용하나요? | 아니요 |

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end
