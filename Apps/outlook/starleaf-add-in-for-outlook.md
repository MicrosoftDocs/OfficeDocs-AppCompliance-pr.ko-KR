---
title: 스타리프의 Outlook 위한 스타리프 추가 신청 정보
ms.author: elmalova
author: elenamalova
ms.date: 08/24/2020
ms.topic: article
ms.service: attestation
certification_type: attested
description: Outlook 위한 StarLeaf 추가 기능, 데이터 처리 정책, Microsoft Cloud App Security 앱 카탈로그 정보 및 CSA STAR 레지스트리의 보안/규정 준수 정보에 대한 사용 가능한 모든 보안 및 규정 준수 정보.
zone_pivot_groups: app-info-data-mcas
ms.openlocfilehash: f201131be32c743550a02a24e653f784a1d91817
ms.sourcegitcommit: a44420a99a1a3a9d0e49f4be66f266e2d4ca7bbb
ms.translationtype: MT
ms.contentlocale: ko-KR
ms.lasthandoff: 05/19/2021
ms.locfileid: "52552479"
---
# <a name="starleaf-add-in-for-outlook"></a>스타리프 Outlook 위한 추가 기능

<p></p>
<img alt="Publisher Attestation: The information on this page is based on a self-assessment report provided by the app developer on the security, compliance, and data handling practices followed by this app. Microsoft makes no guarantees regarding the accuracy of the information." src="../media/attested.png" width="650" />
<p>최종 업데이트: 2020년 8월 24일</p>

* <a href="https://appsource.microsoft.com/product/office/WA104381343" target="_blank">앱소스에서 보기</a>

::: zone pivot="general"

### <a name="general-information"></a>일반 정보

스타리프에서 마이크로소프트에 제공한 정보:

| **정보** | **응답** |
|:----------------|:-------------|
| 앱 이름 | 스타리프 Outlook 위한 추가 기능 |
| ID | WA104381343 |
| 지원되는 Office 365 클라이언트 | Outlook 2013 년 이후 Windows, Outlook 2016 또는 이후 Mac에서 웹에서 Outlook |
| 파트너 회사 이름 | StarLeaf |
| 파트너 웹사이트의 URL | [https://www.starleaf.com/](https://www.starleaf.com/) |
| 개인정보 처리방침의 URL | [https://www.starleaf.com/privacy-policy](https://www.starleaf.com/privacy-policy) |
| 이용 약관의 URL | [https://support.starleaf.com/legal-information/end-user-lic...](https://support.starleaf.com/legal-information/end-user-license-agreement-for-starleaf-applications) |

 [!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="data"

### <a name="how-the-app-handles-data"></a>앱이 데이터를 처리하는 방법

이 정보는 StarLeaf에서 이 앱이 조직 데이터를 수집하고 저장하는 방법과 앱이 수집하는 데이터에 대한 조직이 가질 수 있는 제어에 대해 제공했습니다.

#### <a name="data-access-using-microsoft-graph"></a>Microsoft Graph 을 사용하여 데이터 액세스

이 [앱에서 필요한 Microsoft Graph 권한을 나열합니다.](https://docs.microsoft.com/graph/permissions-reference)

>| **사용 권한**  | **권한 유형(위임/응용 프로그램)** | **데이터가 수집되고 있습니까? 그것을 수집하기위한 정당화?** | **데이터가 저장되어 있습니까? 그것을 저장하는 정당화?** | **Azure AD 앱 ID** |
>|:----------------|:--------------------|:---------------------------------------------------|:--------------------------|:--------------------------|
>| 캘린더.읽기 쓰기 | 신청 | 우리는 회의의 iCalUId, 회의의 시간 / 날짜, 참석자 이메일 주소 및 Office.js 사용자 지정 속성 인터페이스를 사용하여 모임에서 읽고 쓰는 단일 값 확장 속성을 저장합니다. iCalUId는 사용자의 outlook 캘린더에서 당사 서비스의 비디오 모임과&#8217;회의의 상관 관계를 상호 연관시키는 데 사용됩니다. 시간/날짜 및 참석자는 적절한 시기에 당사 서비스에 적합한 사람들에게 비디오 회의를 제공하는 데 사용됩니다. SVEP는 O365 애드인과 함께 사용자가 레코딩과 같은 서비스에서 화상 회의에 대한 세부 정보를 설정할 수 있는 인터페이스를 제공하는 데 사용됩니다. | 웹후크 알림을 구독하여 캘린더의 이벤트 변경 내용을 추적하고 서비스를 업데이트하여 일관되게 유지했습니다. 또한 사용자가 Teams 앱과 상호 작용하고 서비스에서 회의를 예약할 때 캘린더에서 이벤트를 만드는 데도 사용됩니다. | 6e86b349-768f-4953-ac2e-fb03f92db4be |
>| User.Read | 신청 | 로그인할 수 있도록 oauth 새로 고침 토큰을 저장합니다. 사용자 프로필 ID를 저장하여 해당 사용자의 향후 OAuth 시도와 비교할 수 있으며 세부 정보를 두 번 저장하지&#8217;않도록 합니다.  | 사용자가 앱에 로그인할 수 있도록 하고 앱에서 사용자가&#8217;이메일 주소를 얻을 수 있어 사용자의 로그인과 당사의 서비스의 계정과 상관 관계를 맺을 수 있습니다.  | 6e86b349-768f-4953-ac2e-fb03f92db4be |


#### <a name="non-microsoft-services-used"></a>사용되지 Microsoft 서비스

앱이 Microsoft 가 아닌 서비스와 조직 데이터를 전송하거나 공유하는 경우 앱에서 사용하는 비Microsoft 서비스, 전송되는 데이터를 나열하고 앱이 이 정보를 전송해야 하는 이유에 대한 명분을 포함합니다.

>| **모든 Microsoft 서비스 OII가** |  **어떤 OII가 전송됩니까?** | **OII 전송에 대한 정당화?** |
>|:-------------------|:--------------------------|:--------------------------|
>| 기술 지원 문제가 발생하면 조직 데이터를 서비스 케이스 관리를 위해 SalesForce로 전송될 수 있습니다. 사용자가 PSTN 전화 접속 기능을 사용하는 경우 통화가 Twilio, Plivo 또는 Voxbone을 통해 흐릅니다. |  | 해당 없음 |



#### <a name="telemetry-data"></a>원격 분석 데이터

조직 식별 정보(OII) 또는 최종 사용자 식별 정보(EUII)가 이 응용 프로그램의 원격 분석 또는 로그에 표시됩니까? 그렇다면 저장되는 데이터와 보존 및 제거 정책은 무엇입니까?

>예. 로그는 사용자 이름, IP 주소, 통화 세부 정보 기록, 연결 품질에 대한 정보 (패킷 손실, 비트 전송), 장치 유형, 통화 진행 상황을 포함한다. 이 정보는 서비스 문제를 진단하기 위해 기술 지원 팀과 수석 개발자가 사용할 수 있습니다. 데이터는 90일 후에 익명화됩니다. 이 데이터를 보호하기 위한 제어는 ISO/IEC 27001 인증에 따라 감사됩니다.

#### <a name="organizational-controls-for-data-stored-by-partner"></a>파트너가 저장한 데이터에 대한 조직 제어

조직의 관리자가 파트너 시스템에서 자신의 정보를 제어하는 방법을 설명해 보세요. 예를 들어 삭제, 보존, 감사, 보관, 최종 사용자 정책 등

>데이터는 사용자가 계정을&#8217;데이터 센터에 있는 StarLeaf&#8217;자체 로그 서버에 저장되며 동일한 관할권 내에 하나 이상의 데이터 센터로 백업됩니다. 데이터에 대한 액세스는 강도 확인된 사용자별 암호를 사용하는 개별 사용자 계정입니다. StarLeaf&#8217;서비스 사용자 계정은 HR 시스템과 회사 Active Directory 그룹에 대해 자동으로 감사되어 이상이 발견되면 보안 및 규정 준수 팀에 경고합니다.

#### <a name="human-review-of-organizational-information"></a>조직 정보의 인간 검토

이 앱에서 수집하거나 저장되는 조직 식별 정보(OII) 데이터를 검토하거나 분석하는 데 관여하는 사람이 있습니까?

>예

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="mcas"

[Microsoft Cloud App Security](https://www.microsoft.com/enterprise-mobility-security/cloud-app-security) 카탈로그의 정보는 아래에 나타납니다.

<iframe height='1020' title='Microsoft Cloud App Security 정보' src='https://appmcasinfoprod.azurewebsites.net/#/dashboard/35997' frameborder='no' style='width: 100%;'></iframe>

<a href="https://appmcasinfoprod.azurewebsites.net/#/dashboard/35997" target="_blank">새 탭에서 보기</a>

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

