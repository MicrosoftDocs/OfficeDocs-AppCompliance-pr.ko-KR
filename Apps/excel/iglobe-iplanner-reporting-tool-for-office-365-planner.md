---
title: iGlobe에 의해 Office 365 플래너에 대한 iPlanner 보고 도구에 대한 응용 프로그램 정보
ms.author: elmalova
author: elenamalova
ms.date: 12/16/2019
ms.topic: article
ms.service: attestation
certification_type: certified
description: Office 365 플래너를 위한 iPlanner 보고 도구, 데이터 처리 정책, Microsoft Cloud App Security 앱 카탈로그 정보 및 CSA STAR 레지스트리의 보안/규정 준수 정보에 대한 사용 가능한 모든 보안 및 규정 준수 정보.
zone_pivot_groups: app-info-data-mcas
ms.openlocfilehash: a577fcc75982703bfae0de740a7e69d9d13e509a
ms.sourcegitcommit: a44420a99a1a3a9d0e49f4be66f266e2d4ca7bbb
ms.translationtype: MT
ms.contentlocale: ko-KR
ms.lasthandoff: 05/19/2021
ms.locfileid: "52548768"
---
# <a name="iplanner-reporting-tool-for-office-365-planner"></a>Office 365 플래너를 위한 iPlanner 보고 도구

<p></p><a href="https://aka.ms/appcertification" alt="This Microsoft 365 Certified app has been reviewed by Microsoft against industry standards and controls for security, compliance, and data handling practices. Where applicable, Microsoft has verified the developer's claims of compliance with reasonable and effective practices." target="_blank"><img alt="Click here for more information on the Microsoft Certified app program." src="../media/certified.png" width="650" /></a>
<p>최종 업데이트: 2019년 12월 16일</p>

* <a href="https://appsource.microsoft.com/product/office/WA104380686" target="_blank">앱소스에서 보기</a>

::: zone pivot="general"

### <a name="general-information"></a>일반 정보

iGlobe에서 마이크로소프트에 제공 하는 정보:

| **정보** | **응답** |
|:----------------|:-------------|
| 앱 이름 | Office 365 플래너를 위한 iPlanner 보고 도구 |
| ID | WA104380686 |
| 지원되는 Office 365 클라이언트 | Excel 2016 또는 이후 Windows, 웹용 Excel, Excel 2016 또는 이후 Mac에서 |
| 파트너 회사 이름 | iGlobe |
| 파트너 웹사이트의 URL | [https://www.iglobecrm.com/](https://www.iglobecrm.com/) |
| 개인정보 처리방침의 URL | [https://iglobecrm.com/content/legal-information](https://iglobecrm.com/content/legal-information) |
| 이용 약관의 URL | [https://pinpointprod.blob.core.windows.net/marketing/Partne...](https://pinpointprod.blob.core.windows.net/marketing/Partner_21474836912/Product_42949680354/Asset_9d620695-979f-49e4-bc56-98259b0cdeb2/EULAPlanner.pdf) |

 [!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="data"

### <a name="how-the-app-handles-data"></a>앱이 데이터를 처리하는 방법

이 정보는 iGlobe에서 이 앱이 조직 데이터를 수집하고 저장하는 방법과 앱이 수집하는 데이터에 대한 조직이 가질 수 있는 제어에 대해 제공했습니다.

#### <a name="data-access-using-microsoft-graph"></a>Microsoft Graph 을 사용하여 데이터 액세스

이 [앱에서 필요한 Microsoft Graph 권한을 나열합니다.](https://docs.microsoft.com/graph/permissions-reference)

>| **사용 권한**  | **권한 유형(위임/응용 프로그램)** | **데이터가 수집되고 있습니까? 그것을 수집하기위한 정당화?** | **데이터가 저장되어 있습니까? 그것을 저장하는 정당화?** | **Azure AD 앱 ID** |
>|:----------------|:--------------------|:---------------------------------------------------|:--------------------------|:--------------------------|
>| 캘린더.읽기 쓰기 | 위임 | 응용 프로그램 데이터베이스에 데이터가 저장되지 않습니다. | 작업 기한에&#8217;사용자 캘린더 항목을 만들려면 |  |
>| Directory.AccessAsUser.All | 위임 | 응용 프로그램 데이터베이스에 데이터가 저장되지 않습니다. | 사용자가 동의를 가지고 있는지 확인하고 API를 사용할 수 있습니다. |  |
>| Directory.ReadWrite.All | 위임 | 응용 프로그램 데이터베이스에 데이터가 저장되지 않습니다. | 플래너 작업을 Outlook To Do 얻으려면 이메일에 신고하고 업데이트합니다. 새 플래너 작업을 만들수 있습니다. |  |
>| Files.ReadWrite.All | 위임 | 응용 프로그램 데이터베이스에 데이터가 저장되지 않습니다. | 파일에 첨부 파일로 액세스하고 작업에 파일을 업로드합니다. |  |
>| Group.Read.All | 위임 | 응용 프로그램 데이터베이스에 데이터가 저장되지 않습니다. | 계획 목록을 얻고 작업을 업데이트하려면. |  |
>| Group.ReadWrite.All | 위임 | 응용 프로그램 데이터베이스에 데이터가 저장되지 않습니다. | 플래너 작업을 얻고 새 작업을 추가하려면 버킷 및 수영 라인을 업데이트합니다. |  |
>| Mail.Read | 위임 | 응용 프로그램 데이터베이스에 데이터가 저장되지 않습니다. | 사용자.읽기, 플래너 작업 Outlook To Do 얻으려면, 플래그 이메일 및 업데이트. 새 플래너 작업을 만들려면 |  |
>| 메일.읽기 쓰기 | 위임 | 응용 프로그램 데이터베이스에 데이터가 저장되지 않습니다. | 메일을 표시하고 메일을 보내려면. |  |
>| 메일.읽기 쓰기.모든 | 위임 | 응용 프로그램 데이터베이스에 데이터가 저장되지 않습니다. | 선택한 메일에서 메일 제목을 가져옵니다. 앱이 선택한 이메일에서 정보를 얻을 수 있도록 설명 필드를 작업 설명에 복사하고 메일 또는 메일 자체에서 작업에 첨부 파일을 저장할 수 있습니다. 알림을 보냅니다. |  |
>| 작업.읽기 | 위임 | 응용 프로그램 데이터베이스에 데이터가 저장되지 않습니다. | 로그인한 사용자를 Outlook To Do 받고 User.Read를 업데이트하려면 플래너 작업을 Outlook To Do 플래그가 지정된 전자 메일을 업데이트합니다. 새 플래너 작업을 만들수 있습니다. |  |
>| User.Read | 위임 | 응용 프로그램 데이터베이스에 데이터가 저장되지 않습니다. | 로그인 및 사용자 프로필 읽기 |  |


#### <a name="non-microsoft-services-used"></a>사용되지 Microsoft 서비스

앱이 Microsoft 가 아닌 서비스와 조직 데이터를 전송하거나 공유하는 경우 앱에서 사용하는 비Microsoft 서비스, 전송되는 데이터를 나열하고 앱이 이 정보를 전송해야 하는 이유에 대한 명분을 포함합니다.

>비Microsoft 서비스 사용되지 않습니다.



#### <a name="telemetry-data"></a>원격 분석 데이터

조직 식별 정보(OII) 또는 최종 사용자 식별 정보(EUII)가 이 응용 프로그램의 원격 분석 또는 로그에 표시됩니까? 그렇다면 저장되는 데이터와 보존 및 제거 정책은 무엇입니까?

>iGlobe는 효과적으로 작동하고 제품 및 서비스에 대한 최상의 경험을 제공하기 위해 데이터를 수집합니다. 라이선스: 무료 추가 기능을 배포하거나, 평가판 구독을 만들거나, 구독을 구매할 때와 같이 조직에서 라이선스 계정을&#8217;관리하도록 수집된 데이터입니다. 다음 정보가 수집됩니다. 
- 재무목적: 회사 이름 및 주소
- 구독된 사용자: 사용자 이름 및 이메일

#### <a name="organizational-controls-for-data-stored-by-partner"></a>파트너가 저장한 데이터에 대한 조직 제어

조직의 관리자가 파트너 시스템에서 자신의 정보를 제어하는 방법을 설명해 보세요. 예를 들어 삭제, 보존, 감사, 보관, 최종 사용자 정책 등

>모든 데이터는 고객의 테넌트에 있습니다. 응용 프로그램 데이터가 저장되지 않습니다. 최신 추가 기능 샌드 박스 브라우저에서 실행, 프로세스&#8221; &#8220;. Microsoft 서비스 사용하여 사용자 데이터와 상호 작용합니다. 추가 기능만 사용자가 작업 중인 데이터에 액세스할 수 있습니다.

#### <a name="human-review-of-organizational-information"></a>조직 정보의 인간 검토

이 앱에서 수집하거나 저장되는 조직 식별 정보(OII) 데이터를 검토하거나 분석하는 데 관여하는 사람이 있습니까?

>아니요

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="mcas"

[Microsoft Cloud App Security](https://www.microsoft.com/enterprise-mobility-security/cloud-app-security) 카탈로그의 정보는 아래에 나타납니다.

<iframe height='1020' title='Microsoft Cloud App Security 정보' src='https://appmcasinfoprod.azurewebsites.net/#/dashboard/35699' frameborder='no' style='width: 100%;'></iframe>

<a href="https://appmcasinfoprod.azurewebsites.net/#/dashboard/35699" target="_blank">새 탭에서 보기</a>

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

