---
title: 휴가 추적기에서 휴가 추적에 대한 응용 프로그램 정보
ms.author: elmalova
author: elenamalova
ms.date: 09/15/2021
ms.topic: article
ms.service: attestation
certification_type: attested
description: 휴가 추적기, 데이터 처리 정책, CSA STAR 레지스트리의 Microsoft Cloud App Security 앱 카탈로그 정보 및 보안/규정 준수 정보에 사용할 수 있는 모든 보안 및 규정 준수 정보
zone_pivot_groups: app-info-data-identity
ms.openlocfilehash: 0bd430bb14f85f563d490148f00988fa7634176e
ms.sourcegitcommit: 3ac3366e04e24db2d12183ef212738d5b599f553
ms.translationtype: MT
ms.contentlocale: ko-KR
ms.lasthandoff: 09/28/2021
ms.locfileid: "59971700"
---
# <a name="vacation-tracker"></a>Vacation Tracker

<p></p>
<img alt="Publisher Attestation: The information on this page is based on a self-assessment report provided by the app developer on the security, compliance, and data handling practices followed by this app. Microsoft makes no guarantees regarding the accuracy of the information." src="../media/attested.png" width="650" />
<p>개발자가 마지막으로 업데이트한 날짜: 2021년 9월 15일</p>

* <a href="https://teams.microsoft.com/l/app/eab5463e-8168-40ee-887a-7ac78de1d266" target="_blank">저장소의 Teams 보기</a>
* <a href="https://appsource.microsoft.com/product/office/WA200002167" target="_blank">AppSource의 보기</a>

::: zone pivot="general"

### <a name="general-information"></a>일반 정보

휴가 추적기에서 Microsoft에 제공한 정보:

| **정보** | **응답** |
|:----------------|:-------------|
| 앱 이름 | Vacation Tracker |
| ID | WA200002167 |
| Office 365 클라이언트 지원 | Microsoft Teams |
| 파트너 회사 이름 | Vacation Tracker |
| 파트너 웹 사이트의 URL | [https://vacationtracker.io](https://vacationtracker.io) |
| 응용 프로그램 Teams 페이지의 URL입니다. | [https://vacationtracker.io/vacation-calendar-tracker-featur...](https://vacationtracker.io/vacation-calendar-tracker-features/) |
| 개인 정보 취급 방침의 URL | [https://vacationtracker.io/privacy-policy/](https://vacationtracker.io/privacy-policy/) |
| 사용 약관 URL | [https://vacationtracker.io/terms-of-service/](https://vacationtracker.io/terms-of-service/) |

 [!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="data"

### <a name="how-the-app-handles-data"></a>앱이 데이터를 처리하는 방법

이 정보는 휴가 추적기에서 이 앱이 조직 데이터를 수집하고 저장하는 방법 및 앱이 수집하는 데이터를 통해 조직이 하게 될 컨트롤에 대해 제공됩니다.

#### <a name="data-access-using-microsoft-graph"></a>Microsoft 365를 사용한 데이터 Graph

이 앱에 [Graph Microsoft 사용자 권한을](https://docs.microsoft.com/graph/permissions-reference) 나열합니다.

>| **사용 권한**  | **사용 권한 유형(위임/ 응용 프로그램)** | **데이터가 수집하나요? 수집의 사당성** | **데이터가 저장되어 있나요? 저장 사정이 있나요?** | **Azure AD 앱 ID** |
>|:----------------|:------------------------------------------------|:--------------------------------------------------------|:--------------------------------------------------|:--------------------|
>| Group.Read.All | 위임 | 사용자가 매주 또는 일별 알림을 설정할 때 공개 채널 ID 및 이름을 읽습니다. | 사용자는 휴가 추적기에서 매일 또는 매주 알림을 받을 채널을 선택할 수 있습니다. 사용자가 원하는 채널을 선택하면 채널 ID가 저장됩니다. | [eab5463e-8168-40ee-887a-7ac78de1d266](https://docs.microsoft.com/microsoft-365-app-certification/azure/eab5463e-8168-40ee-887a-7ac78de1d266) |
>| Team.ReadBasic.All | 위임 | 사용자가 휴가 Microsoft Teams 등록할 팀을 선택할 수 있도록 등록하는 동안 참가한 팀의 목록을 제공합니다. 또는 전체 조직에 등록할 수 있습니다. | 사용자가 휴가 추적에 등록하는 경우(Microsoft Teams 전체 조직이 아닌) 선택한 팀에 대한 팀 ID를 저장합니다. 당사는 팀 ID를 사용하여 로그인한 사용자를 휴가 추적기에서 기존 계정과 연결합니다. | [eab5463e-8168-40ee-887a-7ac78de1d266](https://docs.microsoft.com/microsoft-365-app-certification/azure/eab5463e-8168-40ee-887a-7ac78de1d266) |
>| User.Read | 위임 | 이름, ID 및 테넌트 ID를 포함하여 기본 사용자 정보를 수집합니다. 이 데이터를 사용하여 로그인한 사용자를 휴가 추적기에서 조직에 연결합니다. | 사용자의 이름, ID 및 테넌트 ID를 저장합니다. 이 데이터를 사용하여 로그인한 사용자를 휴가 추적기에서 조직에 연결합니다. | [eab5463e-8168-40ee-887a-7ac78de1d266](https://docs.microsoft.com/microsoft-365-app-certification/azure/eab5463e-8168-40ee-887a-7ac78de1d266) |
>| User.Read.All | 위임 | 사용자는 자신의 조직 또는 팀에서 모든 Microsoft 365 가져올 Microsoft Teams 있습니다. 이 사용 권한을 사용하여 선택한 팀 또는 조직에 대해 사용이 허가된 사용자만 Microsoft Teams 수 있습니다. | 가져온 사용자에 대한 기본 정보(이름, 전자 메일 주소 및 사용자 ID 포함)를 저장합니다. | [eab5463e-8168-40ee-887a-7ac78de1d266](https://docs.microsoft.com/microsoft-365-app-certification/azure/eab5463e-8168-40ee-887a-7ac78de1d266) |
>| User.ReadBasic.All | 위임 | 사용자가 조직 또는 조직 팀에서 다른 사용자를 가져올 Microsoft Teams 있습니다. 이 사용 권한을 사용하여 사용 가능한 사용자 및 해당 전자 메일 주소를 가져오기 팝업에 나열합니다. | 사용자가 휴가 추적으로 가져올 동료를 선택하면 이름, 전자 메일 주소 및 사용자 ID를 포함하여 가져온 사용자에 대한 기본 정보가 저장됩니다. | [eab5463e-8168-40ee-887a-7ac78de1d266](https://docs.microsoft.com/microsoft-365-app-certification/azure/eab5463e-8168-40ee-887a-7ac78de1d266) |
>| 전자 메일 | 위임 | 사용자가 Microsoft AAD를 사용하여 로그인하면 전자 메일 주소가 고유 식별자로 저장됩니다. | 사용자의 전자 메일을 고유 식별자으로 저장합니다. 통신에는 이 전자 메일을 사용하지 않습니다. 사용자는 등록 중에 통신에 사용하는 비즈니스 전자 메일 주소를 입력합니다. | [eab5463e-8168-40ee-887a-7ac78de1d266](https://docs.microsoft.com/microsoft-365-app-certification/azure/eab5463e-8168-40ee-887a-7ac78de1d266) |
>| offline_access | 위임 | 이 사용 권한이 있는 데이터는 수집하지 않습니다. 액세스 권한이 있는 데이터에 대한 액세스를 유지 관리하는 데 사용됩니다. | 이 사용 권한이 있는 데이터는 저장하지 않습니다. | [eab5463e-8168-40ee-887a-7ac78de1d266](https://docs.microsoft.com/microsoft-365-app-certification/azure/eab5463e-8168-40ee-887a-7ac78de1d266) |
>| openid | 위임 | 이 사용 권한을 사용하여 사용자를 휴가 추적에 로그인하거나 등록합니다. 이 사용 권한이 있는 특정 데이터는 수집하지 않습니다. | 이 사용 권한을 사용하여 사용자를 휴가 추적에 로그인하거나 등록합니다. 이 사용 권한이 있는 특정 데이터는 저장하지 않습니다. | [eab5463e-8168-40ee-887a-7ac78de1d266](https://docs.microsoft.com/microsoft-365-app-certification/azure/eab5463e-8168-40ee-887a-7ac78de1d266) |
>| 프로필 | 위임 | 이름, ID 및 테넌트 ID를 포함하여 기본 사용자 정보를 수집합니다. 이 데이터를 사용하여 로그인한 사용자를 휴가 추적기에서 조직에 연결합니다. | 사용자의 이름, ID 및 테넌트 ID를 저장합니다. 이 데이터를 사용하여 로그인한 사용자를 휴가 추적기에서 조직에 연결합니다. | [eab5463e-8168-40ee-887a-7ac78de1d266](https://docs.microsoft.com/microsoft-365-app-certification/azure/eab5463e-8168-40ee-887a-7ac78de1d266) |


#### <a name="non-microsoft-services-used"></a>비영구 Microsoft 서비스

앱이 Microsoft가 아닌 서비스로 조직 데이터를 전송하거나 공유하는 경우 앱에서 사용하는 비 Microsoft 서비스, 전송되는 데이터를 나열하고 앱이 이 정보를 전송해야 하는 이유에 대한 사유를 포함합니다.

>| **모든 비 Microsoft 서비스 OII가 다음으로 전송됩니다.** |  **전송되는 OII는 무엇입니까?** | **OII 전송의 사당성** |
>|:-----------------------------------------------------|:------------------------------|:----------------------------------------|
>| Stripe, AWS, Crisp, Customer.io, Segment, Amplitude, Google Tag Manager | 회사 이름(사용자가 입력한 경우) | 사용자가 등록하면 회사 이름을 입력하고 이 이름을 제품 내부의 조직 이름으로 사용 |

#### <a name="data-access-via-bots"></a>봇을 통한 데이터 액세스

이 앱에 봇 또는 메시징 확장이 포함되어 있는 경우 팀 구성원의 명단(이름, 성, 표시 이름, 전자 메일 주소)이나 팀 구성원이 추가된 채팅의 최종 사용자 식별 정보(EUII)에 액세스할 수 있습니다. 이 앱이 이 기능을 사용하나요?

>| **EUII 액세스의 사유는 무엇입니까?**  | **EUII가 데이터베이스에 저장되어 있나요?** | **EUII 저장의 사유는 무엇입니까?** |
>|:---------------------------------------|:-----------------------------------|:------------------------------------|
>| 봇은 봇과 통신하는 사용자에 대한 기본 정보를 볼 수 있습니다. 그러나 이 정보는 저장하거나 사용하지 않습니다. 사용자의 ID, 대화 ID 및 봇에 전송된 메시지만 사용할 수 있습니다. | Microsoft는 사용자의 전자 메일 주소, 사용자 이름(Microsoft AAD에 정의되어 있는 경우) 및 사용자의 프로필 사진(Microsoft AAD에서)을 저장합니다. | 동일한 회사의 관리자와 승인자가 대시보드에서 직원을 인식할 수 있도록 전자 메일 주소를 사용자 고유 식별자 및 사용자의 이름 및 프로필 사진으로 사용 합니다.  |


#### <a name="telemetry-data"></a>원격 분석 데이터

이 응용 프로그램의 원격 분석 또는 로그에 OII(조직 식별 정보) 또는 EUII(최종 사용자 식별 정보)가 나타나나요? 그렇다면 저장되는 데이터와 보존 및 제거 정책에 대해 설명하세요.

>회사 이름 및 이 유형의 데이터에 대한 표준 1년 보존 정책에 따라 보존되고 제거됩니다.

#### <a name="organizational-controls-for-data-stored-by-partner"></a>파트너가 저장한 데이터에 대한 조직 제어

조직의 관리자가 파트너 시스템에서 정보를 제어하는 방법에 대해 설명하는 방법 삭제, 보존, 감사, 보관, 최종 사용자 정책 등

>시작하려면 사용자로부터 필요한 최소 데이터 양을 수집합니다. 그런 다음 가능한 최소 데이터를 파트너와 공유하고 마지막으로 데이터 보존 정책이 있으므로 해당하는 경우 1년 내에 모든 데이터가 제거됩니다.

#### <a name="human-review-of-organizational-information"></a>조직 정보의 인적 검토

사람이 이 앱에서 수집하거나 저장하는 OII(조직 식별 정보) 데이터를 검토하거나 분석하는 데 관여하나요?

>예

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

이 정보는 휴가 추적기에서 이 앱이 인증, 권한 부여, 응용 프로그램 등록 모범 사례 및 기타 ID 조건을 처리하는 방법에 대해 제공했습니다.

| **정보** | **응답** |
|:----------------|:-------------|
| Microsoft Identify Platform(Azure AD)과 통합하나요?  | 아니요 |

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end
