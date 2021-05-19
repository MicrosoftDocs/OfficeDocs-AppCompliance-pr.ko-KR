---
title: 재해기술 주사위 신청 정보
ms.author: elmalova
author: elenamalova
ms.date: 08/24/2020
ms.topic: article
ms.service: attestation
certification_type: attested
description: 재해 기술 DICE에 대한 사용 가능한 모든 보안 및 규정 준수 정보 정보, 데이터 처리 정책, Microsoft Cloud App Security 앱 카탈로그 정보 및 CSA STAR 레지스트리의 보안 /규정 준수 정보.
zone_pivot_groups: app-info-data-mcas
ms.openlocfilehash: 29d53402a9bbf635e83d6d262227a8363577e261
ms.sourcegitcommit: a44420a99a1a3a9d0e49f4be66f266e2d4ca7bbb
ms.translationtype: MT
ms.contentlocale: ko-KR
ms.lasthandoff: 05/19/2021
ms.locfileid: "52552239"
---
# <a name="disastertech-dice"></a>DisasterTech DICE

<p></p>
<img alt="Publisher Attestation: The information on this page is based on a self-assessment report provided by the app developer on the security, compliance, and data handling practices followed by this app. Microsoft makes no guarantees regarding the accuracy of the information." src="../media/attested.png" width="650" />
<p>최종 업데이트: 2020년 8월 24일</p>

* <a href="https://teams.microsoft.com/l/app/7df3e67b-ed62-48e9-a950-c95bd7ebce80" target="_blank">Teams 스토어에서 보기</a>
* <a href="https://appsource.microsoft.com/product/office/WA200001909" target="_blank">앱소스에서 보기</a>

::: zone pivot="general"

### <a name="general-information"></a>일반 정보

재해텍에서 Microsoft에 제공한 정보:

| **정보** | **응답** |
|:----------------|:-------------|
| 앱 이름 | DisasterTech DICE |
| ID | WA200001909 |
| 지원되는 Office 365 클라이언트 | Microsoft Teams |
| 파트너 회사 이름 | DisasterTech |
| 파트너 웹사이트의 URL | [https://dice.disastertech.com](https://dice.disastertech.com) |
| 개인정보 처리방침의 URL | [https://dice.disastertech.com/privacy.html](https://dice.disastertech.com/privacy.html) |
| 이용 약관의 URL | [https://dice.disastertech.com/tos.html](https://dice.disastertech.com/tos.html) |

 [!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="data"

### <a name="how-the-app-handles-data"></a>앱이 데이터를 처리하는 방법

이 정보는 이 앱이 조직 데이터를 수집하고 저장하는 방법과 앱이 수집하는 데이터에 대한 조직에 대한 제어에 대해 재해텍에서 제공되었습니다.

#### <a name="data-access-using-microsoft-graph"></a>Microsoft Graph 을 사용하여 데이터 액세스

이 [앱에서 필요한 Microsoft Graph 권한을 나열합니다.](https://docs.microsoft.com/graph/permissions-reference)

>| **사용 권한**  | **권한 유형(위임/응용 프로그램)** | **데이터가 수집되고 있습니까? 그것을 수집하기위한 정당화?** | **데이터가 저장되어 있습니까? 그것을 저장하는 정당화?** | **Azure AD 앱 ID** |
>|:----------------|:--------------------|:---------------------------------------------------|:--------------------------|:--------------------------|
>| User.Read | 위임 | 액세스 권한 설정을 위해 저장된 사용자 이메일 주소와 이름으로 사용자를 식별하는 사용자 이름 | 사용자가 로그인할 수 있도록 하고 APPN에 액세스할 수 있으므로 자동 로그인과 로그인 Teams 사용자 이름 및 이메일 주소를 설정할 수 있습니다. | 36d23b76-c58b-4a34-a60f-dceac6962bad |
>| 전자 메일 | 위임 | 없음 | Teams 단일 Sign-On | 36d23b76-c58b-4a34-a60f-dceac6962bad |
>| offline_access | 위임 | 없음 | Teams 단일 Sign-On | 36d23b76-c58b-4a34-a60f-dceac6962bad |
>| 오픈 ID | 위임 | 없음 | Teams 단일 Sign-On | 36d23b76-c58b-4a34-a60f-dceac6962bad |
>| 윤곽 | 위임 | 없음 | 단일 사인온을 Teams 데 필요합니다. | 36d23b76-c58b-4a34-a60f-dceac6962bad |


#### <a name="non-microsoft-services-used"></a>사용되지 Microsoft 서비스

앱이 Microsoft 가 아닌 서비스와 조직 데이터를 전송하거나 공유하는 경우 앱에서 사용하는 비Microsoft 서비스, 전송되는 데이터를 나열하고 앱이 이 정보를 전송해야 하는 이유에 대한 명분을 포함합니다.

>비Microsoft 서비스 사용되지 않습니다.

#### <a name="data-access-via-bots"></a>봇을 통한 데이터 액세스

이 앱에 봇 또는 메시징 확장 프로그램이 포함된 경우 최종 사용자 식별 정보(EUII): 팀의 모든 팀 구성원의 명단(이름, 성, 표시 이름, 이메일 주소)에 액세스하거나 추가된 채팅을 할 수 있습니다. 이 응용 프로그램은이 기능을 사용합니까?

>EUII에 액세스할 수 없습니다.


#### <a name="telemetry-data"></a>원격 분석 데이터

조직 식별 정보(OII) 또는 최종 사용자 식별 정보(EUII)가 이 응용 프로그램의 원격 분석 또는 로그에 표시됩니까? 그렇다면 저장되는 데이터와 보존 및 제거 정책은 무엇입니까?

>사용자가 응용 프로그램에서 함께 공동 작업할 수 있도록 Azure가 호스팅하는 PostgreSQL 데이터베이스에 사용자 이름, 이름 및 성을 저장합니다. 컨트롤은 재해 기술 직원만 데이터베이스에 직접 액세스할 수 있다는 것입니다. 사용자가 응용 프로그램에서 제거되면 정보를 보관합니다. 사용자는 언제든지 시스템에서 개인 데이터를 제거할 수 있는 권리를 유지합니다. 그러나 이러한 정보를 제거하면 응용 프로그램의 사용도 금지됩니다.

#### <a name="organizational-controls-for-data-stored-by-partner"></a>파트너가 저장한 데이터에 대한 조직 제어

조직의 관리자가 파트너 시스템에서 자신의 정보를 제어하는 방법을 설명해 보세요. 예를 들어 삭제, 보존, 감사, 보관, 최종 사용자 정책 등

>응용 프로그램 데이터는 Azure의 PostgreSQL 데이터베이스에 저장되며, 나머지는 암호화됩니다. 어떤 사용자도 데이터베이스 또는 백 엔드 API에 직접 액세스할 수 없습니다. 모든 API 호출은 Active Directory 액세스 토큰으로 보호됩니다.

#### <a name="human-review-of-organizational-information"></a>조직 정보의 인간 검토

이 앱에서 수집하거나 저장되는 조직 식별 정보(OII) 데이터를 검토하거나 분석하는 데 관여하는 사람이 있습니까?

>예

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="mcas"

[Microsoft Cloud App Security](https://www.microsoft.com/enterprise-mobility-security/cloud-app-security) 카탈로그의 정보는 아래에 나타납니다.

<iframe height='1020' title='Microsoft Cloud App Security 정보' src='https://appmcasinfoprod.azurewebsites.net/#/dashboard/35993' frameborder='no' style='width: 100%;'></iframe>

<a href="https://appmcasinfoprod.azurewebsites.net/#/dashboard/35993" target="_blank">새 탭에서 보기</a>

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

