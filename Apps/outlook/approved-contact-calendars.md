---
title: 승인된 연락처에 의해 승인된 연락처 달력에 대한 응용 프로그램 정보
ms.author: elmalova
author: elenamalova
ms.date: 12/16/2019
ms.topic: article
ms.service: attestation
certification_type: attested
description: 승인된 연락처 캘린더에 대한 사용 가능한 모든 보안 및 규정 준수 정보 정보, 데이터 처리 정책, Microsoft Cloud App Security 앱 카탈로그 정보 및 CSA STAR 레지스트리의 보안/규정 준수 정보.
zone_pivot_groups: app-info-data-mcas
ms.openlocfilehash: 57dd499fe648ed9a9b481d4175056977a0d6fa61
ms.sourcegitcommit: a44420a99a1a3a9d0e49f4be66f266e2d4ca7bbb
ms.translationtype: MT
ms.contentlocale: ko-KR
ms.lasthandoff: 05/19/2021
ms.locfileid: "52552559"
---
# <a name="approved-contact-calendars"></a>승인된 연락처 캘린더

<p></p>
<img alt="Publisher Attestation: The information on this page is based on a self-assessment report provided by the app developer on the security, compliance, and data handling practices followed by this app. Microsoft makes no guarantees regarding the accuracy of the information." src="../media/attested.png" width="650" />
<p>최종 업데이트: 2019년 12월 16일</p>

* <a href="https://appsource.microsoft.com/product/office/WA104380294" target="_blank">앱소스에서 보기</a>

::: zone pivot="general"

### <a name="general-information"></a>일반 정보

Microsoft에 승인된 연락처에서 제공하는 정보:

| **정보** | **응답** |
|:----------------|:-------------|
| 앱 이름 | 승인된 연락처 캘린더 |
| ID | WA104380294 |
| 지원되는 Office 365 클라이언트 | Outlook 2013 년 이후 Windows, Outlook 2016 또는 이후 Mac에서 웹에서 Outlook |
| 파트너 회사 이름 | Approved Contact |
| 파트너 웹사이트의 URL | [https://approvedcontact.com/](https://approvedcontact.com/) |
| 개인정보 처리방침의 URL | [https://approvedcontact.com/Privacy%20Policy.pdf](https://approvedcontact.com/Privacy%20Policy.pdf) |
| 이용 약관의 URL | [https://go.microsoft.com/fwlink/?LinkID=521715&amp.omkt=en-US](https://go.microsoft.com/fwlink/?LinkID=521715&amp;omkt=en-US) |

 [!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="data"

### <a name="how-the-app-handles-data"></a>앱이 데이터를 처리하는 방법

이 정보는 이 앱이 조직 데이터를 수집하고 저장하는 방법과 앱이 수집하는 데이터에 대한 조직에서 가질 수 있는 제어에 대해 승인된 연락처에서 제공했습니다.

#### <a name="data-access-using-microsoft-graph"></a>Microsoft Graph 을 사용하여 데이터 액세스

이 [앱에서 필요한 Microsoft Graph 권한을 나열합니다.](https://docs.microsoft.com/graph/permissions-reference)

>| **사용 권한**  | **권한 유형(위임/응용 프로그램)** | **데이터가 수집되고 있습니까? 그것을 수집하기위한 정당화?** | **데이터가 저장되어 있습니까? 그것을 저장하는 정당화?** | **Azure AD 앱 ID** |
>|:----------------|:--------------------|:---------------------------------------------------|:--------------------------|:--------------------------|
>| 캘린더.읽기 쓰기 | 위임 | 캘린더 봇의 경우 여러 사용자가 무료 시간을 찾기 위해 무료/바쁜 시간을 사용자에게 저장합니다.  | 우리는 무료 / 바쁜 시간과 일정을 읽고 비교합니다. | adef9811-448f-4dd5-88d9-68734050fe58 |
>| 연락처.읽기 | 위임 | 예, 연락처 정보를 저장합니다. | 연락처 가져오기 및 동기화. | adef9811-448f-4dd5-88d9-68734050fe58 |
>| User.Read | 위임 | 예 | 기본 프로필 정보. | adef9811-448f-4dd5-88d9-68734050fe58 |
>| User.ReadBasic.All | 위임 | 아니요 | 동료의 프로필을 보고 자유 시간을 비교하고 회의실 을 예약하는 데 사용됩니다. | adef9811-448f-4dd5-88d9-68734050fe58 |
>| offline_access | 위임 | 예, 오프라인 사용자를위한 무료 / 바쁜 시간. | 사용자가 사이트를 적극적으로 사용하지 않을 때 Graph 전화하십시오. | adef9811-448f-4dd5-88d9-68734050fe58 |
>| 오픈 ID | 위임 | 아니요 | Office 365 SSO. | adef9811-448f-4dd5-88d9-68734050fe58 |


#### <a name="non-microsoft-services-used"></a>사용되지 Microsoft 서비스

앱이 Microsoft 가 아닌 서비스와 조직 데이터를 전송하거나 공유하는 경우 앱에서 사용하는 비Microsoft 서비스, 전송되는 데이터를 나열하고 앱이 이 정보를 전송해야 하는 이유에 대한 명분을 포함합니다.

>비Microsoft 서비스 사용되지 않습니다.



#### <a name="telemetry-data"></a>원격 분석 데이터

조직 식별 정보(OII) 또는 최종 사용자 식별 정보(EUII)가 이 응용 프로그램의 원격 분석 또는 로그에 표시됩니까? 그렇다면 저장되는 데이터와 보존 및 제거 정책은 무엇입니까?

>예, 우리는 상용 Appsource에 라이센스 구매를 연결하기위한 이메일 주소를 기록합니다. 로그에서 이 정보를 삭제할 수 있는 기능을 제공합니다.

#### <a name="organizational-controls-for-data-stored-by-partner"></a>파트너가 저장한 데이터에 대한 조직 제어

조직의 관리자가 파트너 시스템에서 자신의 정보를 제어하는 방법을 설명해 보세요. 예를 들어 삭제, 보존, 감사, 보관, 최종 사용자 정책 등

>개발자만 로그에 액세스할 수 있습니다. 우리는 모든 개발 플랫폼에 액세스 하기 위해 2FA를 적용 합니다.

#### <a name="human-review-of-organizational-information"></a>조직 정보의 인간 검토

이 앱에서 수집하거나 저장되는 조직 식별 정보(OII) 데이터를 검토하거나 분석하는 데 관여하는 사람이 있습니까?

>아니요

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="mcas"

[Microsoft Cloud App Security](https://www.microsoft.com/enterprise-mobility-security/cloud-app-security) 카탈로그의 정보는 아래에 나타납니다.

<iframe height='1020' title='Microsoft Cloud App Security 정보' src='https://appmcasinfoprod.azurewebsites.net/#/dashboard/20445' frameborder='no' style='width: 100%;'></iframe>

<a href="https://appmcasinfoprod.azurewebsites.net/#/dashboard/20445" target="_blank">새 탭에서 보기</a>

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

