---
title: 스프링웍스 HR 테크의 퀴즈 신청 정보
ms.author: elmalova
author: elenamalova
ms.date: 01/13/2021
ms.topic: article
ms.service: attestation
certification_type: attested
description: 퀴즈에 대한 사용 가능한 모든 보안 및 규정 준수 정보 정보, 데이터 처리 정책, Microsoft Cloud App Security 앱 카탈로그 정보, CSA STAR 레지스트리의 보안/규정 준수 정보.
zone_pivot_groups: app-info-data-mcas-identity
ms.openlocfilehash: fbd1b9f5f308f3690a9d55a40993ba6122e8f81b
ms.sourcegitcommit: a44420a99a1a3a9d0e49f4be66f266e2d4ca7bbb
ms.translationtype: MT
ms.contentlocale: ko-KR
ms.lasthandoff: 05/19/2021
ms.locfileid: "52553849"
---
# <a name="trivia"></a>Trivia

<p></p>
<img alt="Publisher Attestation: The information on this page is based on a self-assessment report provided by the app developer on the security, compliance, and data handling practices followed by this app. Microsoft makes no guarantees regarding the accuracy of the information." src="../media/attested.png" width="650" />
<p>최종 업데이트: 2021년 1월 13일</p>

* <a href="https://teams.microsoft.com/l/app/391082c3-968b-47b1-9c92-b5daf008000b" target="_blank">Teams 스토어에서 보기</a>
* <a href="https://appsource.microsoft.com/product/office/WA200001956" target="_blank">앱소스에서 보기</a>

::: zone pivot="general"

### <a name="general-information"></a>일반 정보

스프링웍스 HR 테크에서 마이크로소프트에 제공한 정보:

| **정보** | **응답** |
|:----------------|:-------------|
| 앱 이름 | Trivia |
| ID | WA200001956 |
| 지원되는 Office 365 클라이언트 | Microsoft Teams |
| 파트너 회사 이름 | Springworks HR Tech |
| 파트너 웹사이트의 URL | [https://springworks.in/](https://springworks.in/) |
| Teams 응용 프로그램 정보 페이지의 URL | [https://www.springworks.in/trivia](https://www.springworks.in/trivia) |
| 개인정보 처리방침의 URL | [https://trivia.springworks.in/policy](https://trivia.springworks.in/policy) |
| 이용 약관의 URL | [https://trivia.springworks.in/tnc](https://trivia.springworks.in/tnc) |

 [!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="data"

### <a name="how-the-app-handles-data"></a>앱이 데이터를 처리하는 방법

이 정보는 Springworks HR Tech에서 이 앱이 조직 데이터를 수집하고 저장하는 방법과 앱이 수집하는 데이터에 대한 조직이 가질 수 있는 제어에 대해 제공했습니다.

#### <a name="data-access-using-microsoft-graph"></a>Microsoft Graph 을 사용하여 데이터 액세스

이 [앱에서 필요한 Microsoft Graph 권한을 나열합니다.](https://docs.microsoft.com/graph/permissions-reference)

>| **사용 권한**  | **권한 유형(위임/응용 프로그램)** | **데이터가 수집되고 있습니까? 그것을 수집하기위한 정당화?** | **데이터가 저장되어 있습니까? 그것을 저장하는 정당화?** | **Azure AD 앱 ID** |
>|:----------------|:--------------------|:---------------------------------------------------|:--------------------------|:--------------------------|
>| Group.Read.All | 위임 | 아니요 | 사용자가 속한 Teams 목록을 얻으려면 | 43bc466a-7678-476f-b904-2d933c5bbfc3 |
>| 팀.읽기 기본.모든 | 위임 | 예. 봇이 추가된 팀 목록 저장 | 작업 영역에 있는 모든 팀에 대한 기본 정보를 수집하려면 | 43bc466a-7678-476f-b904-2d933c5bbfc3 |
>| User.Read.All | 위임 | 예, 사용자의 고유 aadObjectId를 저장합니다. 또한 사용자 이름, 이메일 등과 같은 사용자의 다양한 세부 사항및 퀴즈 대시 보드에 표시 | 작업 영역에 있는 모든 사용자의 세부 정보를 얻으려면 | 43bc466a-7678-476f-b904-2d933c5bbfc3 |
>| 오픈 ID | 위임 | 예, 앱에 로그인하는 사용자를 저장합니다. |  사용자가 자신의 계정과 앱과 함께 앱을 사용하여 사용자의 데이터를 사용할 수 있도록 하려면 | 43bc466a-7678-476f-b904-2d933c5bbfc3 |
>| 윤곽 | 위임 | 예, 퀴즈 및 기타 기능호스트의 사용자 ID 및 이름을 저장하고 고유하게 식별하려면 | 사용자 이름과 같은 사용자의 기본 프로필 정보를 읽으려면 이메일 | 43bc466a-7678-476f-b904-2d933c5bbfc3 |


#### <a name="non-microsoft-services-used"></a>사용되지 Microsoft 서비스

앱이 Microsoft 가 아닌 서비스와 조직 데이터를 전송하거나 공유하는 경우 앱에서 사용하는 비Microsoft 서비스, 전송되는 데이터를 나열하고 앱이 이 정보를 전송해야 하는 이유에 대한 명분을 포함합니다.

>| **모든 Microsoft 서비스 OII가** |  **어떤 OII가 전송됩니까?** | **OII 전송에 대한 정당화?** |
>|:-------------------|:--------------------------|:--------------------------|
>| AWS, 메일침팬지, 스트라이프.  | 고객 이름, 이메일, IP, 결제 정보 | 당사는 이러한 제3자를 사용하여 고객에게 최상의 고객 경험을 제공합니다. |

#### <a name="data-access-via-bots"></a>봇을 통한 데이터 액세스

이 앱에 봇 또는 메시징 확장 프로그램이 포함된 경우 최종 사용자 식별 정보(EUII): 팀의 모든 팀 구성원의 명단(이름, 성, 표시 이름, 이메일 주소)에 액세스하거나 추가된 채팅을 할 수 있습니다. 이 응용 프로그램은이 기능을 사용합니까?

>| **EUII에 액세스할 수 있는 정당성?**  | **EUII는 데이터베이스에 저장되어 있습니까?** | **EUII를 저장하는 정당화?** |
>|:--------------------------------|:---------------------|:--------------------------|
>| 이 데이터는 퀴즈 및 기타 기능에 참가자 목록을 표시하고 저장하는 데 사용됩니다. | 이름, 이메일 | 예. 오류 발생 시 호스트와의 분석 및 통신을 위한 퀴즈 및 기타 기능의 호스트 및 참가자의 데이터 저장 |


#### <a name="telemetry-data"></a>원격 분석 데이터

조직 식별 정보(OII) 또는 최종 사용자 식별 정보(EUII)가 이 응용 프로그램의 원격 분석 또는 로그에 표시됩니까? 그렇다면 저장되는 데이터와 보존 및 제거 정책은 무엇입니까?

>OII: 조직 이름, 테넌트 ID가 로그에 나타납니다. EUII: aad 개체 ID, 전체 이름, 이메일이 로그에 나타납니다. 로그가 자동으로 삭제되는 30일 보존 기간 게시물이 있습니다. 


#### <a name="organizational-controls-for-data-stored-by-partner"></a>파트너가 저장한 데이터에 대한 조직 제어

조직의 관리자가 파트너 시스템에서 자신의 정보를 제어하는 방법을 설명해 보세요. 예를 들어 삭제, 보존, 감사, 보관, 최종 사용자 정책 등

>AWS의 RDS에 저장된 데이터입니다. 암호화됩니다. 액세스는 DevOps 엔지니어, 엔지니어링 리드 및 설립자에게만 가능합니다.

#### <a name="human-review-of-organizational-information"></a>조직 정보의 인간 검토

이 앱에서 수집하거나 저장되는 조직 식별 정보(OII) 데이터를 검토하거나 분석하는 데 관여하는 사람이 있습니까?

>예

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="mcas"

[Microsoft Cloud App Security](https://www.microsoft.com/enterprise-mobility-security/cloud-app-security) 카탈로그의 정보는 아래에 나타납니다.

<iframe height='1020' title='Microsoft Cloud App Security 정보' src='https://appmcasinfoprod.azurewebsites.net/#/dashboard/36138' frameborder='no' style='width: 100%;'></iframe>

<a href="https://appmcasinfoprod.azurewebsites.net/#/dashboard/36138" target="_blank">새 탭에서 보기</a>

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="identity"

### <a name="identity-information"></a>신원 정보

이 정보는 이 앱이 인증, 승인, 응용 프로그램 등록 모범 사례 및 기타 ID 기준을 처리하는 방법에 대해 Springworks HR Tech에서 제공했습니다.

| **정보** | **응답** |
|:----------------|:-------------|
| Microsoft 식별 플랫폼(Azure AD)과 통합합니까?  | 아니요 |

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end
