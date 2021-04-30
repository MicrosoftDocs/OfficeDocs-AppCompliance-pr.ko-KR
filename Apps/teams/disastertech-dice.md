---
title: DisasterTech의 DisasterTech DICE에 대한 응용 프로그램 정보
ms.author: elmalova
author: elenamalova
ms.date: 08/24/2020
ms.topic: article
ms.service: attestation
description: DisasterTech DICE에 사용할 수 있는 모든 보안 및 규정 준수 정보, 데이터 처리 정책, CSA STAR 레지스트리의 Microsoft Cloud App Security 앱 카탈로그 정보 및 보안/규정 준수 정보
zone_pivot_groups: app-info-data-mcas
ms.openlocfilehash: 3ff4168c5490b235c97b24e77b279f407c7bea12
ms.sourcegitcommit: e97156a6eaf1d5ec5c26fd14add210a92bacd944
ms.translationtype: MT
ms.contentlocale: ko-KR
ms.lasthandoff: 04/30/2021
ms.locfileid: "52095309"
---
# <a name="disastertech-dice"></a>DisasterTech DICE

<p></p>
<img alt="Publisher Attestation: The information on this page is based on a self-assessment report provided by the app developer on the security, compliance, and data handling practices followed by this app. Microsoft makes no guarantees regarding the accuracy of the information." src="../media/attested.png" width="650" />
<p>개발자가 마지막으로 업데이트한 날짜: 2020년 8월 24일</p>

* <a href="https://teams.microsoft.com/l/app/7df3e67b-ed62-48e9-a950-c95bd7ebce80" target="_blank">저장소의 Teams 보기</a>
* <a href="https://appsource.microsoft.com/product/office/WA200001909" target="_blank">AppSource의 보기</a>

::: zone pivot="general"

### <a name="general-information"></a>일반 정보

DisasterTech에서 Microsoft에 제공한 정보:

| **정보** | **응답** |
|:----------------|:-------------|
| 앱 이름 | DisasterTech DICE |
| ID | WA200001909 |
| 기능 | 탭 |
| Office 365 클라이언트 지원 | Microsoft Teams |
| 파트너 회사 이름 | DisasterTech |
| 파트너 웹 사이트의 URL | [https://dice.disastertech.com](https://dice.disastertech.com) |
| 개인 정보 취급 방침의 URL | [https://dice.disastertech.com/privacy.html](https://dice.disastertech.com/privacy.html) |
| 사용 약관 URL | [https://dice.disastertech.com/tos.html](https://dice.disastertech.com/tos.html) |

 [!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="data"

### <a name="how-the-app-handles-data"></a>앱이 데이터를 처리하는 방법

이 정보는 DisasterTech에서 이 앱이 조직 데이터를 수집하고 저장하는 방법 및 앱이 수집하는 데이터를 통해 조직이 제공하는 컨트롤에 대해 제공됩니다.

#### <a name="data-access-using-microsoft-graph"></a>Microsoft 365를 사용한 데이터 Graph

이 앱에 [Graph Microsoft 사용자 권한을](https://docs.microsoft.com/graph/permissions-reference) 나열합니다.

>| **사용 권한**  | **사용 권한 유형(위임/응용 프로그램)** | **데이터가 수집하나요? 수집의 사당성** | **데이터가 저장되어 있나요? 저장 사정이 있나요?** | **Azure AD 앱 ID** |
>|:----------------|:--------------------|:---------------------------------------------------|:--------------------------|:--------------------------|
>| User.Read | 위임 | 사용자 이름으로 사용자를 식별하기 위해 액세스 권한 및 사용자 이름을 설정하기 위해 저장된 사용자 전자 메일 주소 | 사용자가 로그인할 수 있도록 허용하고 UPN에 대한 액세스 권한을 부여하여 사용자 이름 및 전자 메일 주소를 설정하기 위해 자동 로그인을 Teams 수 있습니다. | 36d23b76-c58b-4a34-a60f-dceac6962bad |
>| 전자 메일 | 위임 | 없음 | 단일 Teams 필수 Sign-On | 36d23b76-c58b-4a34-a60f-dceac6962bad |
>| offline_access | 위임 | 없음 | 단일 Teams 필수 Sign-On | 36d23b76-c58b-4a34-a60f-dceac6962bad |
>| openid | 위임 | 없음 | 단일 Teams 필수 Sign-On | 36d23b76-c58b-4a34-a60f-dceac6962bad |
>| profile | 위임 | 없음 | Single Teams 로그인에 필요합니다. | 36d23b76-c58b-4a34-a60f-dceac6962bad |


#### <a name="non-microsoft-services-used"></a>비영구 Microsoft 서비스

앱이 Microsoft가 아닌 서비스로 조직 데이터를 전송하거나 공유하는 경우 앱에서 사용하는 비 Microsoft 서비스, 전송되는 데이터를 나열하고 앱이 이 정보를 전송해야 하는 이유에 대한 사유를 포함합니다.

>비영구 Microsoft 서비스 사용되지 않습니다.

#### <a name="data-access-via-bots"></a>봇을 통한 데이터 액세스

이 앱에 봇 또는 메시징 확장이 포함되어 있는 경우 팀 구성원의 명단(이름, 성, 표시 이름, 전자 메일 주소)이나 팀 구성원이 추가된 채팅의 최종 사용자 식별 정보(EUII)에 액세스할 수 있습니다. 이 앱이 이 기능을 사용하나요?

>EUII에 액세스하지 않습니다.



#### <a name="telemetry-data"></a>원격 분석 데이터

이 응용 프로그램의 원격 분석 또는 로그에 OII(조직 식별 정보) 또는 EUII(최종 사용자 식별 정보)가 나타나나요? 그렇다면 저장되는 데이터와 보존 및 제거 정책에 대해 설명하세요.

>사용자가 응용 프로그램에서 공동 작업을 할 수 있도록 Azure에서 호스트하는 PostgreSQL 데이터베이스에 사용자 이름, 이름 및 성이 저장됩니다. 재해 기술 직원만 데이터베이스에 직접 액세스할 수 있습니다. 사용자가 응용 프로그램에서 제거되면 정보를 보관합니다. 사용자는 수시로 시스템에서 개인 데이터를 제거할 수 있는 권리가 유지 관리됩니다. 그러나 이러한 정보를 제거하면 응용 프로그램을 사용할 수 없습니다.

#### <a name="organizational-controls-for-data-stored-by-partner"></a>파트너가 저장한 데이터에 대한 조직 제어

조직의 관리자가 파트너 시스템에서 정보를 제어하는 방법에 대해 설명하는 방법 삭제, 보존, 감사, 보관, 최종 사용자 정책 등

>응용 프로그램 데이터는 미사용 암호화된 Azure의 PostgreSQL 데이터베이스에 저장됩니다. 사용자가 데이터베이스 또는 백 엔드 API에 직접 액세스할 수 없습니다. 모든 API 호출은 Active Directory 액세스 토큰으로 보호됩니다.

#### <a name="human-review-of-organizational-information"></a>조직 정보의 인적 검토

사람이 이 앱에서 수집하거나 저장하는 OII(조직 식별 정보) 데이터를 검토하거나 분석하는 데 관여하나요?

>예

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="mcas"

Microsoft Cloud App Security [카탈로그의](https://www.microsoft.com/enterprise-mobility-security/cloud-app-security) 정보가 아래에 표시됩니다.

<iframe height='1020' title='Microsoft Cloud App Security 정보' src='https://appmcasinfoprod.azurewebsites.net/#/dashboard/35993' frameborder='no' style='width: 100%;'></iframe>

<a href="https://appmcasinfoprod.azurewebsites.net/#/dashboard/35993" target="_blank">새 탭에서 보기</a>

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

