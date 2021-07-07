---
title: iGlobe에서 Planner를 Office 365 iPlanner 보고 도구에 대한 응용 프로그램 정보
ms.author: elmalova
author: elenamalova
ms.date: 12/16/2019
ms.topic: article
ms.service: attestation
certification_type: certified
description: CSA STAR 레지스트리의 Office 365 Planner, 데이터 처리 정책, Microsoft Cloud App Security 앱 카탈로그 정보 및 보안/규정 준수 정보를 iPlanner 보고 도구에 사용할 수 있는 모든 보안 및 규정 준수 정보입니다.
zone_pivot_groups: app-info-data-mcas
ms.openlocfilehash: 2b9797eb2b4ec271804711473a77f26a9cce4e13
ms.sourcegitcommit: 65d4afba6f46d45315b2a90d2b21ce1737707e7b
ms.translationtype: MT
ms.contentlocale: ko-KR
ms.lasthandoff: 07/02/2021
ms.locfileid: "53281150"
---
# <a name="iplanner-reporting-tool-for-office-365-planner"></a>Planner용 iPlanner 보고 Office 365

<p></p><a href="https://aka.ms/appcertification" alt="This Microsoft 365 Certified app has been reviewed by Microsoft against industry standards and controls for security, compliance, and data handling practices. Where applicable, Microsoft has verified the developer's claims of compliance with reasonable and effective practices." target="_blank"><img alt="Click here for more information on the Microsoft Certified app program." src="../media/certified.png" width="650" /></a>
<p>개발자가 마지막으로 업데이트한 날짜: 2019년 12월 16일</p>

* <a href="https://appsource.microsoft.com/product/office/WA104380686" target="_blank">AppSource의 보기</a>

::: zone pivot="general"

### <a name="general-information"></a>일반 정보

iGlobe에서 Microsoft에 제공한 정보:

| **정보** | **응답** |
|:----------------|:-------------|
| 앱 이름 | Planner용 iPlanner 보고 Office 365 |
| ID | WA104380686 |
| Office 365 클라이언트 지원 | Excel 2016 Mac의 Windows, 웹용 Excel Excel 2016 이상에서 또는 그 이상을 사용할 수 있습니다. |
| 파트너 회사 이름 | iGlobe |
| 파트너 웹 사이트의 URL | [https://iglobecrm.com/](https://iglobecrm.com/) |
| 개인 정보 취급 방침의 URL | [https://instassl.iglobecrm.com/legal-information](https://instassl.iglobecrm.com/legal-information) |
| 사용 약관 URL | [https://mipa.iglobe.dk/EULA](https://mipa.iglobe.dk/EULA) |

 [!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="data"

### <a name="how-the-app-handles-data"></a>앱이 데이터를 처리하는 방법

이 정보는 iGlobe에서 이 앱이 조직 데이터를 수집 및 저장하는 방법 및 앱이 수집하는 데이터를 통해 조직에서 제공하는 컨트롤에 대해 제공됩니다.

#### <a name="data-access-using-microsoft-graph"></a>Microsoft 365를 사용한 데이터 Graph

이 앱에 [Graph Microsoft 사용자 권한을](https://docs.microsoft.com/graph/permissions-reference) 나열합니다.

>| **사용 권한**  | **사용 권한 유형(위임/응용 프로그램)** | **데이터가 수집하나요? 수집의 사당성** | **데이터가 저장되어 있나요? 저장 사정이 있나요?** | **Azure AD 앱 ID** |
>|:----------------|:--------------------|:---------------------------------------------------|:--------------------------|:--------------------------|
>| Calendars.ReadWrite | 위임 | 응용 프로그램 데이터베이스에 데이터가 저장되지 않습니다. | 작업 기한에 달력을&#8217;달력 항목을 만들 수 있습니다. |  |
>| Directory.AccessAsUser.All | 위임 | 응용 프로그램 데이터베이스에 데이터가 저장되지 않습니다. | 사용자의 동의를 확인하고 API를 사용할 수 있는 액세스 권한을 습니다. |  |
>| Directory.ReadWrite.All | 위임 | 응용 프로그램 데이터베이스에 데이터가 저장되지 않습니다. | 플래너 작업을 Outlook To Do 플래그가 지정되어 업데이트됩니다. 새 Planner 작업을 만들 수 있습니다. |  |
>| Files.ReadWrite.All | 위임 | 응용 프로그램 데이터베이스에 데이터가 저장되지 않습니다. | 첨부 파일로 파일에 액세스하고 작업에 파일을 업로드하려면 |  |
>| Group.Read.All | 위임 | 응용 프로그램 데이터베이스에 데이터가 저장되지 않습니다. | 계획 목록을 다운로드하고 작업을 업데이트합니다. |  |
>| Group.ReadWrite.All | 위임 | 응용 프로그램 데이터베이스에 데이터가 저장되지 않습니다. | 플래너 작업을 시작하고 새 작업을 추가하기 위해 버킷 및 스위빙 라인을 업데이트합니다. |  |
>| Mail.Read | 위임 | 응용 프로그램 데이터베이스에 데이터가 저장되지 않습니다. | User.Read- 플래너 작업을 Outlook To Do 플래그가 지정되어 있는 전자 메일을 업데이트합니다. 새 Planner 작업을 만들 수 있습니다. |  |
>| Mail.ReadWrite | 위임 | 응용 프로그램 데이터베이스에 데이터가 저장되지 않습니다. | 메일을 표시하고 메일을 보내기 위해 |  |
>| Mail.ReadWrite.All | 위임 | 응용 프로그램 데이터베이스에 데이터가 저장되지 않습니다. | 선택한 메일에서 메일 제목을 얻습니다. 앱이 선택한 전자 메일에서 정보를 얻을 수 있도록 허용하여 설명 필드를 작업 설명에 복사하고 메일이나 메일 자체의 첨부 파일을 작업에 저장할 수 있도록 허용합니다. 알림 보내기. |  |
>| Tasks.ReadWrite | 위임 | 응용 프로그램 데이터베이스에 데이터가 저장되지 않습니다. | 로그인한 사용자를 Outlook To Do.Read를 업데이트하고 플래너 작업을 다운로드하고 플래그가 Outlook To Do 전자 메일을 업데이트합니다. 새 Planner 작업을 만들 수 있습니다. |  |
>| User.Read | 위임 | 응용 프로그램 데이터베이스에 데이터가 저장되지 않습니다. | 로그인 및 사용자 프로필 읽기 |  |


#### <a name="non-microsoft-services-used"></a>비영구 Microsoft 서비스

앱이 Microsoft가 아닌 서비스로 조직 데이터를 전송하거나 공유하는 경우 앱에서 사용하는 비 Microsoft 서비스, 전송되는 데이터를 나열하고 앱이 이 정보를 전송해야 하는 이유에 대한 사유를 포함합니다.

>비영구 Microsoft 서비스 사용되지 않습니다.



#### <a name="telemetry-data"></a>원격 분석 데이터

이 응용 프로그램의 원격 분석 또는 로그에 OII(조직 식별 정보) 또는 EUII(최종 사용자 식별 정보)가 나타나나요? 그렇다면 저장되는 데이터와 보존 및 제거 정책에 대해 설명하세요.

>iGlobe는 효과적으로 작동하고 제품 및 서비스에 대한 최상의 환경을 제공하기 위해 데이터를 수집합니다. 라이선스의 경우: 무료 추가 기능을&#8217;평가판 구독을 만들거나 구독을 구매하는 경우와 같이 조직을 관리하기 위해 수집된 데이터와 라이선스 계정이 필요합니다. 다음 정보는 수집됩니다. 
- 재무 목적: 회사 이름 및 주소
- 구독된 사용자: 사용자 이름 및 전자 메일

#### <a name="organizational-controls-for-data-stored-by-partner"></a>파트너가 저장한 데이터에 대한 조직 제어

조직의 관리자가 파트너 시스템에서 정보를 제어하는 방법에 대해 설명하는 방법 삭제, 보존, 감사, 보관, 최종 사용자 정책 등

>모든 데이터는 고객의 자체 테넌트에 있습니다. 응용 프로그램 데이터가 저장되지 않습니다. 최신 추가 기능을 샌드박스 브라우저에서 실행하고 &#8220;실행되지&#8221;. 사용자 데이터를 사용하여 사용자 데이터와 상호 작용합니다Microsoft 서비스. 추가 기능에서 사용자가 작업하는 데이터에만 액세스할 수 있습니다.

#### <a name="human-review-of-organizational-information"></a>조직 정보의 인적 검토

사람이 이 앱에서 수집하거나 저장하는 OII(조직 식별 정보) 데이터를 검토하거나 분석하는 데 관여하나요?

>아니요

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="mcas"

Microsoft Cloud App Security [카탈로그의](https://www.microsoft.com/enterprise-mobility-security/cloud-app-security) 정보가 아래에 표시됩니다.

<iframe height='1020' title='Microsoft Cloud App Security 정보' src='https://appmcasinfoprod.azurewebsites.net/#/dashboard/35699' frameborder='no' style='width: 100%;'></iframe>

<a href="https://appmcasinfoprod.azurewebsites.net/#/dashboard/35699" target="_blank">새 탭에서 보기</a>

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

