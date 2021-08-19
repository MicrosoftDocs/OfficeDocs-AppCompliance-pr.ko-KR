---
title: 의사 결정에 대한 응용 프로그램 정보
ms.author: elmalova
author: elenamalova
ms.date: 06/02/2021
ms.topic: article
ms.service: attestation
certification_type: attested
description: CSA STAR 레지스트리의 의사 결정, 데이터 처리 정책, Microsoft Cloud App Security 앱 카탈로그 정보 및 보안/규정 준수 정보에 사용할 수 있는 모든 보안 및 규정 준수 정보
zone_pivot_groups: app-info-data-identity
ms.openlocfilehash: 19a710fc8edbcb5243b81755ce3d61e8bcaa5b25
ms.sourcegitcommit: 3660f89e183c638979a31c295ac059daa6c387dd
ms.translationtype: MT
ms.contentlocale: ko-KR
ms.lasthandoff: 08/18/2021
ms.locfileid: "58391901"
---
# <a name="decisions"></a>결정

<p></p>
<img alt="Publisher Attestation: The information on this page is based on a self-assessment report provided by the app developer on the security, compliance, and data handling practices followed by this app. Microsoft makes no guarantees regarding the accuracy of the information." src="../media/attested.png" width="650" />
<p>개발자가 마지막으로 업데이트한 날짜: 2021년 6월 2일</p>

* <a href="https://teams.microsoft.com/l/app/d3d1be68-066c-4967-a74b-9edcf902dcfb" target="_blank">저장소의 Teams 보기</a>
* <a href="https://appsource.microsoft.com/product/office/WA104381880" target="_blank">AppSource의 보기</a>

::: zone pivot="general"

### <a name="general-information"></a>일반 정보

Microsoft에 대한 의사 결정에서 제공하는 정보:

| **정보** | **응답** |
|:----------------|:-------------|
| 앱 이름 | 결정 |
| ID | WA104381880 |
| Office 365 클라이언트 지원 | Microsoft Teams |
| 파트너 회사 이름 | 결정 |
| 파트너 웹 사이트의 URL | [https://www.meetingdecisions.com](https://www.meetingdecisions.com) |
| 응용 프로그램 Teams 페이지의 URL입니다. | [https://www.meetingdecisions.com](https://www.meetingdecisions.com) |
| 개인 정보 취급 방침의 URL | [https://www.meetingdecisions.com/privacy](https://www.meetingdecisions.com/privacy) |
| 사용 약관 URL | [https://www.meetingdecisions.com/terms-of-service](https://www.meetingdecisions.com/terms-of-service) |

 [!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="data"

### <a name="how-the-app-handles-data"></a>앱이 데이터를 처리하는 방법

이 정보는 이 앱이 조직 데이터를 수집 및 저장하는 방법 및 앱이 수집하는 데이터를 통해 조직이 제어할 수 있는 결정에 의해 제공됩니다.

#### <a name="data-access-using-microsoft-graph"></a>Microsoft 365를 사용한 데이터 Graph

이 앱에 [Graph Microsoft 사용자 권한을](https://docs.microsoft.com/graph/permissions-reference) 나열합니다.

>| **사용 권한**  | **사용 권한 유형(위임/ 응용 프로그램)** | **데이터가 수집하나요? 수집의 사당성** | **데이터가 저장되어 있나요? 저장 사정이 있나요?** | **Azure AD 앱 ID** |
>|:----------------|:------------------------------------------------|:--------------------------------------------------------|:--------------------------------------------------|:--------------------|
>| Calendars.ReadWrite | 위임 | 사용자가 일정을&#8217;정보를 읽어 모임 목록 및 검색과 같은 기능을 사용하도록 설정하는 데 사용됩니다. 또한 사용자가 의사 결정에서 항목을 삭제할 때 일정에서 특정 모임을 삭제할 수 있는 옵션을 제공합니다. | 고객 데이터는 고객&#8217;Office 365 고객 디바이스에서만 처리됩니다. Decisions 데이터베이스는 실제 데이터가 아니라 테넌트에 있는 Office 365 개체에 대한 참조만 유지 관리합니다. 자세한 내용은 https://www.meetingdecisions.com/security-and-privacy 을 참조합니다. | [1064f7e4-a9e2-467d-8d42-f45cc59f145d](https://docs.microsoft.com/microsoft-365-app-certification/azure/1064f7e4-a9e2-467d-8d42-f45cc59f145d) |
>| Chat.ReadWrite | 위임 | 투표 결정을 전송하고 개별 어젠더 항목에 대한 발표자 목록을 모임 채팅에 직접 Microsoft Teams 사용됩니다. | 고객 데이터는 고객&#8217;Office 365 고객 디바이스에서만 처리됩니다. Decisions 데이터베이스는 실제 데이터가 아니라 테넌트에 있는 Office 365 개체에 대한 참조만 유지 관리합니다. 자세한 내용은 https://www.meetingdecisions.com/security-and-privacy 을 참조합니다. | [1064f7e4-a9e2-467d-8d42-f45cc59f145d](https://docs.microsoft.com/microsoft-365-app-certification/azure/1064f7e4-a9e2-467d-8d42-f45cc59f145d) |
>| Directory.Read.All | 위임 | 테넌트 이름 및 확인된 도메인과 Office 365 테넌트에 대한 기본 정보를 수집하는 데 사용됩니다. 또한 그룹 구성원 자격을 확인하는 데도 필요합니다. | 고객 데이터는 고객&#8217;Office 365 고객 디바이스에서만 처리됩니다. Decisions 데이터베이스는 실제 데이터가 아니라 테넌트에 있는 Office 365 개체에 대한 참조만 유지 관리합니다. 자세한 내용은 https://www.meetingdecisions.com/security-and-privacy 을 참조합니다. | [1064f7e4-a9e2-467d-8d42-f45cc59f145d](https://docs.microsoft.com/microsoft-365-app-certification/azure/1064f7e4-a9e2-467d-8d42-f45cc59f145d) |
>| Files.Read.All | 위임 | 이러한 파일을 PDF 모임 책에 병합하기 위해 사용자와 공유되는 파일을 읽는 데 사용됩니다. | 고객 데이터는 고객&#8217;Office 365 고객 디바이스에서만 처리됩니다. Decisions 데이터베이스는 실제 데이터가 아니라 테넌트에 있는 Office 365 개체에 대한 참조만 유지 관리합니다. 자세한 내용은 https://www.meetingdecisions.com/security-and-privacy 을 참조합니다. | [1064f7e4-a9e2-467d-8d42-f45cc59f145d](https://docs.microsoft.com/microsoft-365-app-certification/azure/1064f7e4-a9e2-467d-8d42-f45cc59f145d) |
>| Files.ReadWrite.All | 위임 | 개인 파일 주석에 대한 지원을 사용자에게 제공하는 데 사용됩니다. 주석이 있는 파일은 SSS의 사용자&#8217;개인 비즈니스용 OneDrive. | 고객 데이터는 고객&#8217;Office 365 고객 디바이스에서만 처리됩니다. Decisions 데이터베이스는 실제 데이터가 아니라 테넌트에 있는 Office 365 개체에 대한 참조만 유지 관리합니다. 자세한 내용은 https://www.meetingdecisions.com/security-and-privacy 을 참조합니다. | [1064f7e4-a9e2-467d-8d42-f45cc59f145d](https://docs.microsoft.com/microsoft-365-app-certification/azure/1064f7e4-a9e2-467d-8d42-f45cc59f145d) |
>| Group.ReadWrite.All | 위임 | 모임 의제, 관련 파일 및 그룹 대화를 Office 365 그룹&#8217;SharePoint 폴더 구조를 만드는 데 사용됩니다.   참고: 의사 결정 사용자는 조직의 모든 테넌트에서 아직 액세스할 수 없는 리소스(예: 그룹)에 액세스할 Office 365 없습니다. | 고객 데이터는 고객&#8217;Office 365 고객 디바이스에서만 처리됩니다. Decisions 데이터베이스는 실제 데이터가 아니라 테넌트에 있는 Office 365 개체에 대한 참조만 유지 관리합니다. 자세한 내용은 https://www.meetingdecisions.com/security-and-privacy 을 참조합니다. | [1064f7e4-a9e2-467d-8d42-f45cc59f145d](https://docs.microsoft.com/microsoft-365-app-certification/azure/1064f7e4-a9e2-467d-8d42-f45cc59f145d) |
>| Mail.Send | 위임 | 의사 결정 사용자가 모임 참가자에게 어젠더 업데이트 및 공동 작성자의 모임 링크와 같은 알림을 보낼 수 있도록 하는 데 사용됩니다. 전자 메일은 모임 참가자 또는 모임 소유자가 선택한 메일로 이동됩니다. 전송된 모든 알림 및 전자 메일은 의사 결정 사용자가 적극적으로 수행됩니다.  참고: 이렇게 해서 사용자에게 결정을 통해 받은 편지함 액세스 권한을 부여하지는 않습니다. | 고객 데이터는 고객&#8217;Office 365 고객 디바이스에서만 처리됩니다. Decisions 데이터베이스는 실제 데이터가 아니라 테넌트에 있는 Office 365 개체에 대한 참조만 유지 관리합니다. 자세한 내용은 https://www.meetingdecisions.com/security-and-privacy 을 참조합니다. | [1064f7e4-a9e2-467d-8d42-f45cc59f145d](https://docs.microsoft.com/microsoft-365-app-certification/azure/1064f7e4-a9e2-467d-8d42-f45cc59f145d) |
>| MailboxSettings.Read | 위임 | 언어 기본 설정에&#8217;식별하는 데 사용됩니다. | 고객 데이터는 고객&#8217;Office 365 고객 디바이스에서만 처리됩니다. Decisions 데이터베이스는 실제 데이터가 아니라 테넌트에 있는 Office 365 개체에 대한 참조만 유지 관리합니다. 자세한 내용은 https://www.meetingdecisions.com/security-and-privacy 을 참조합니다. | [1064f7e4-a9e2-467d-8d42-f45cc59f145d](https://docs.microsoft.com/microsoft-365-app-certification/azure/1064f7e4-a9e2-467d-8d42-f45cc59f145d) |
>| Notes.ReadWrite | 위임 | 메모를 작성하고 설명 및 질문을 준비하기 위해 모임에 대한 개인 전자 필기장을 설정하는 데 사용됩니다. 또한 그룹에서 공유 전자 필기장에 그룹 모임 시간(OneNote)을 저장할 수 OneNote. | 고객 데이터는 고객&#8217;Office 365 고객 디바이스에서만 처리됩니다. Decisions 데이터베이스는 실제 데이터가 아니라 테넌트에 있는 Office 365 개체에 대한 참조만 유지 관리합니다. 자세한 내용은 https://www.meetingdecisions.com/security-and-privacy 을 참조합니다. | [1064f7e4-a9e2-467d-8d42-f45cc59f145d](https://docs.microsoft.com/microsoft-365-app-certification/azure/1064f7e4-a9e2-467d-8d42-f45cc59f145d) |
>| Sites.ReadWrite.All | 위임 | 모임 정보를 위해 비공개 채널에서 폴더 구조를 만드는 데 사용할 수 있습니다. | 고객 데이터는 고객&#8217;Office 365 고객 디바이스에서만 처리됩니다. Decisions 데이터베이스는 실제 데이터가 아니라 테넌트에 있는 Office 365 개체에 대한 참조만 유지 관리합니다. 자세한 내용은 https://www.meetingdecisions.com/security-and-privacy 을 참조합니다. | [1064f7e4-a9e2-467d-8d42-f45cc59f145d](https://docs.microsoft.com/microsoft-365-app-certification/azure/1064f7e4-a9e2-467d-8d42-f45cc59f145d) |
>| Tasks.ReadWrite | 위임 | 작업 및 결정을 Microsoft Planner와 동기화하는 데 사용됩니다. 또한 사용자가 작업 및 결정을 내보낼 수 Excel. | 고객 데이터는 고객&#8217;Office 365 고객 디바이스에서만 처리됩니다. Decisions 데이터베이스는 실제 데이터가 아니라 테넌트에 있는 Office 365 개체에 대한 참조만 유지 관리합니다. 자세한 내용은 https://www.meetingdecisions.com/security-and-privacy 을 참조합니다. | [1064f7e4-a9e2-467d-8d42-f45cc59f145d](https://docs.microsoft.com/microsoft-365-app-certification/azure/1064f7e4-a9e2-467d-8d42-f45cc59f145d) |
>| TeamsAppInstallation.ReadWriteForUser | 위임 | 채팅에서 의사 결정 앱을 프로그래밍식으로 설치하는 데 필요합니다. 이는 모임 환경의 결정 탭을 추가하기 전에 필요합니다. | 고객 데이터는 고객&#8217;Office 365 고객 디바이스에서만 처리됩니다. Decisions 데이터베이스는 실제 데이터가 아니라 테넌트에 있는 Office 365 개체에 대한 참조만 유지 관리합니다. 자세한 내용은 https://www.meetingdecisions.com/security-and-privacy 을 참조합니다. | [1064f7e4-a9e2-467d-8d42-f45cc59f145d](https://docs.microsoft.com/microsoft-365-app-certification/azure/1064f7e4-a9e2-467d-8d42-f45cc59f145d) |
>| TeamsAppInstallation.ReadWriteForUser.All | 위임 | 채팅에서 의사 결정 앱을 프로그래밍식으로 설치하는 데 필요합니다. 이는 모임 환경의 결정 탭을 추가하기 전에 필요합니다. | 고객 데이터는 고객&#8217;Office 365 고객 디바이스에서만 처리됩니다. Decisions 데이터베이스는 실제 데이터가 아니라 테넌트에 있는 Office 365 개체에 대한 참조만 유지 관리합니다. 자세한 내용은 https://www.meetingdecisions.com/security-and-privacy 을 참조합니다. | [1064f7e4-a9e2-467d-8d42-f45cc59f145d](https://docs.microsoft.com/microsoft-365-app-certification/azure/1064f7e4-a9e2-467d-8d42-f45cc59f145d) |
>| TeamsTab.Create | 위임 | 모임 내/채널 탭을 추가해야 Teams. | 고객 데이터는 고객&#8217;Office 365 고객 디바이스에서만 처리됩니다. Decisions 데이터베이스는 실제 데이터가 아니라 테넌트에 있는 Office 365 개체에 대한 참조만 유지 관리합니다. 자세한 내용은 https://www.meetingdecisions.com/security-and-privacy 을 참조합니다. | [1064f7e4-a9e2-467d-8d42-f45cc59f145d](https://docs.microsoft.com/microsoft-365-app-certification/azure/1064f7e4-a9e2-467d-8d42-f45cc59f145d) |
>| TeamsTab.Read.All | 위임 | 탭이 설치되어 있지 않은지 확인하려면 필요합니다. | 고객 데이터는 고객&#8217;Office 365 고객 디바이스에서만 처리됩니다. Decisions 데이터베이스는 실제 데이터가 아니라 테넌트에 있는 Office 365 개체에 대한 참조만 유지 관리합니다. 자세한 내용은 https://www.meetingdecisions.com/security-and-privacy 을 참조합니다. | [1064f7e4-a9e2-467d-8d42-f45cc59f145d](https://docs.microsoft.com/microsoft-365-app-certification/azure/1064f7e4-a9e2-467d-8d42-f45cc59f145d) |
>| User.ReadBasic.All | 위임 | 그룹 구성원 및 외부 참가자의 이름과 성, 사진 및 전자 메일 주소를 표시하는 데 사용됩니다. | 고객 데이터는 고객&#8217;Office 365 고객 디바이스에서만 처리됩니다. Decisions 데이터베이스는 실제 데이터가 아니라 테넌트에 있는 Office 365 개체에 대한 참조만 유지 관리합니다. 자세한 내용은 https://www.meetingdecisions.com/security-and-privacy 을 참조합니다. | [1064f7e4-a9e2-467d-8d42-f45cc59f145d](https://docs.microsoft.com/microsoft-365-app-certification/azure/1064f7e4-a9e2-467d-8d42-f45cc59f145d) |
>| 프로필 | 위임 | 로그인하는 데 사용됩니다. | 고객 데이터는 고객&#8217;Office 365 고객 디바이스에서만 처리됩니다. Decisions 데이터베이스는 실제 데이터가 아니라 테넌트에 있는 Office 365 개체에 대한 참조만 유지 관리합니다. 자세한 내용은 https://www.meetingdecisions.com/security-and-privacy 을 참조합니다. | [1064f7e4-a9e2-467d-8d42-f45cc59f145d](https://docs.microsoft.com/microsoft-365-app-certification/azure/1064f7e4-a9e2-467d-8d42-f45cc59f145d) |


#### <a name="non-microsoft-services-used"></a>비영구 Microsoft 서비스

앱이 Microsoft가 아닌 서비스로 조직 데이터를 전송하거나 공유하는 경우 앱에서 사용하는 비 Microsoft 서비스, 전송되는 데이터를 나열하고 앱이 이 정보를 전송해야 하는 이유에 대한 사유를 포함합니다.

>비영구 Microsoft 서비스 사용되지 않습니다.

#### <a name="data-access-via-bots"></a>봇을 통한 데이터 액세스

이 앱에 봇 또는 메시징 확장이 포함되어 있는 경우 팀 구성원의 명단(이름, 성, 표시 이름, 전자 메일 주소)이나 팀 구성원이 추가된 채팅의 최종 사용자 식별 정보(EUII)에 액세스할 수 있습니다. 이 앱이 이 기능을 사용하나요?

>EUII에 액세스하지 않습니다.


#### <a name="telemetry-data"></a>원격 분석 데이터

이 응용 프로그램의 원격 분석 또는 로그에 OII(조직 식별 정보) 또는 EUII(최종 사용자 식별 정보)가 나타나나요? 그렇다면 저장되는 데이터와 보존 및 제거 정책에 대해 설명하세요.

>응용 프로그램 원격 분석 또는 로그에 OII 또는 EUII가 나타나지 않습니다.

#### <a name="organizational-controls-for-data-stored-by-partner"></a>파트너가 저장한 데이터에 대한 조직 제어

조직의 관리자가 파트너 시스템에서 정보를 제어하는 방법에 대해 설명하는 방법 삭제, 보존, 감사, 보관, 최종 사용자 정책 등

>소프트웨어를 사용하는 동안 고객이 제공한 데이터는 고객에게만 제공됩니다.  서비스는 클라우드 서비스 및 Microsoft Office 365 서비스에서 Microsoft Azure. 모든 고객 데이터는 테넌트의 고객 Microsoft Office 365 저장됩니다. 서비스에 저장되거나 처리되는 모든 데이터는 익명이며 개별 사용자가 추적할 수 없습니다. 따라서 의사 결정은 고객을 대신하여 개인 데이터를 저장, 수집 또는 처리하지 않습니다.

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

이 정보는 이 앱이 인증, 권한 부여, 응용 프로그램 등록 모범 사례 및 기타 ID 조건을 처리하는 방법에 대한 의사 결정에 의해 제공됩니다.

| **정보** | **응답** |
|:----------------|:-------------|
| Microsoft Identify Platform(Azure AD)과 통합하나요?  | 예 |
| 통합 검사 목록에 설명된 적용 가능한 모든 모범 사례를 Microsoft ID 플랫폼 준수하나요?  | 예 |
| 앱에서 인증에 MSAL(Microsoft 인증 라이브러리)을 사용하나요? | 예 |
| 앱에서 조건부 액세스 정책을 지원하나요? | 예 |
| 지원되는 정책 유형 나열 | 모두 |
| 앱에서 시나리오에 대한 최소 권한 권한을 요청하나요? | 예 |
| 앱의 정적으로 등록된 사용 권한은 앱이 동적으로 그리고 증분적으로 요청하는 권한을 정확하게 반영하나요? | 예 |
| 앱에서 다중 테넌시를 지원하나요? | 예 |
| 앱에 기밀 클라이언트가 있나요? | 예 |
| 앱에 등록된 리디렉션 URI(통합 리소스 식별자)를 모두 소유하고 있나요? | 예 |
| 앱의 경우 어떻게 사용하지 않도록 해야 하나요? | - 와일드카드 리디렉션 URIS,<br/>- OAuth2 암시적 Flow SPA에 필요하지 않은 경우<br/>- 리소스 소유자 암호 자격 증명(ROPC) 흐름 |
| 앱에서 웹 API를 노출하나요? | 예 |
| 사용 권한 모델에서 클라이언트 앱이 적절한 동의를 받은 경우 통화 성공만 허용하나요? | 예 |
| 앱에서 미리 보기 API를 사용하나요? | 아니요 |
| 앱에서 사용되지 않는 API를 사용하나요? | 아니요 |

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end
