---
title: 동적 신호로 동적 신호에 대한 응용 프로그램 정보
ms.author: elmalova
author: elenamalova
ms.date: 12/16/2019
ms.topic: article
ms.service: attestation
certification_type: attested
description: 동적 신호, 데이터 처리 정책, Microsoft Cloud App Security 앱 카탈로그 정보 및 CSA STAR 레지스트리의 보안/규정 준수 정보에 대한 사용 가능한 모든 보안 및 규정 준수 정보.
zone_pivot_groups: app-info-data-mcas
ms.openlocfilehash: 0d3c59f6809bafe16eec2a1d709f40a980576b1b
ms.sourcegitcommit: a44420a99a1a3a9d0e49f4be66f266e2d4ca7bbb
ms.translationtype: MT
ms.contentlocale: ko-KR
ms.lasthandoff: 05/19/2021
ms.locfileid: "52552229"
---
# <a name="dynamic-signal"></a>Dynamic Signal

<p></p>
<img alt="Publisher Attestation: The information on this page is based on a self-assessment report provided by the app developer on the security, compliance, and data handling practices followed by this app. Microsoft makes no guarantees regarding the accuracy of the information." src="../media/attested.png" width="650" />
<p>최종 업데이트: 2019년 12월 16일</p>

* <a href="https://teams.microsoft.com/l/app/6f98619e-a822-4a74-8ee9-af6a358f2750" target="_blank">Teams 스토어에서 보기</a>
* <a href="https://appsource.microsoft.com/product/office/WA200000102" target="_blank">앱소스에서 보기</a>

::: zone pivot="general"

### <a name="general-information"></a>일반 정보

동적 신호에서 Microsoft에 제공한 정보:

| **정보** | **응답** |
|:----------------|:-------------|
| 앱 이름 | Dynamic Signal |
| ID | WA200000102 |
| 지원되는 Office 365 클라이언트 | Microsoft Teams |
| 파트너 회사 이름 | Dynamic Signal |
| 파트너 웹사이트의 URL | [https://dynamicsignal.com](https://dynamicsignal.com) |
| Teams 응용 프로그램 정보 페이지의 URL | [https://support.dynamicsignal.com/hc/en-us/requests/new?tic...](https://support.dynamicsignal.com/hc/en-us/requests/new?ticket_form_id=360000290032) |
| 개인정보 처리방침의 URL | [https://dynamicsignal.com/privacy/](https://dynamicsignal.com/privacy/) |
| 이용 약관의 URL | [https://dynamicsignal.com/terms-of-use/platform-terms-of-us...](https://dynamicsignal.com/terms-of-use/platform-terms-of-use/) |

 [!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="data"

### <a name="how-the-app-handles-data"></a>앱이 데이터를 처리하는 방법

이 정보는 동적 신호에서 이 앱이 조직 데이터를 수집하고 저장하는 방법과 앱이 수집하는 데이터에 대해 조직이 가질 수 있는 제어에 대해 제공했습니다.

#### <a name="data-access-using-microsoft-graph"></a>Microsoft Graph 을 사용하여 데이터 액세스

이 [앱에서 필요한 Microsoft Graph 권한을 나열합니다.](https://docs.microsoft.com/graph/permissions-reference)

>| **사용 권한**  | **권한 유형(위임/응용 프로그램)** | **데이터가 수집되고 있습니까? 그것을 수집하기위한 정당화?** | **데이터가 저장되어 있습니까? 그것을 저장하는 정당화?** | **Azure AD 앱 ID** |
>|:----------------|:--------------------|:---------------------------------------------------|:--------------------------|:--------------------------|
>| User.Read | 위임 | 동적 신호는 Azure AD에서 플랫폼으로 사용자를 동기화하여 사용자의 간소화된 활성화 및 비활성화를 실시간으로 허용합니다. 데이터는 동적 신호 내에 저장되어 사용자가 동기화가 진행되는 동안 해당 응용 프로그램을 사용할 수 있도록 합니다. | 동적 신호 플랫폼 사용자를 Azure AD와 동기화하려면 특정 사용자의 권한을 읽습니다. | 79ff4a2a-e22b-47d5-94dc-ef76fe46af75 |
>| User.Read.All | 위임 | 동적 신호는 Azure AD에서 플랫폼으로 사용자를 동기화하여 사용자의 간소화된 활성화 및 비활성화를 실시간으로 허용합니다. 데이터는 동적 신호 내에 저장되어 사용자가 동기화가 진행되는 동안 해당 응용 프로그램을 사용할 수 있도록 합니다. | 동적 신호 플랫폼 사용자를 Azure AD와 동기화하려면 특정 사용자의 권한을 읽습니다. | 79ff4a2a-e22b-47d5-94dc-ef76fe46af75 |
>| offline_access | 위임 | 동적 신호는 Azure AD에서 플랫폼으로 사용자를 동기화하여 사용자의 간소화된 활성화 및 비활성화를 실시간으로 허용합니다. 데이터는 동적 신호 내에 저장되어 사용자가 동기화가 진행되는 동안 해당 응용 프로그램을 사용할 수 있도록 합니다. | 테넌트의 그룹 및 팀에 대한 액세스를 유지합니다. | 79ff4a2a-e22b-47d5-94dc-ef76fe46af75 |
>| 오픈 ID | 위임 | 동적 신호는 Azure AD에서 플랫폼으로 사용자를 동기화하여 사용자의 간소화된 활성화 및 비활성화를 실시간으로 허용합니다. 데이터는 동적 신호 내에 저장되어 사용자가 동기화가 진행되는 동안 해당 응용 프로그램을 사용할 수 있도록 합니다. | 동적 신호 응용 프로그램으로 사용자를 인증합니다. | 79ff4a2a-e22b-47d5-94dc-ef76fe46af75 |


#### <a name="non-microsoft-services-used"></a>사용되지 Microsoft 서비스

앱이 Microsoft 가 아닌 서비스와 조직 데이터를 전송하거나 공유하는 경우 앱에서 사용하는 비Microsoft 서비스, 전송되는 데이터를 나열하고 앱이 이 정보를 전송해야 하는 이유에 대한 명분을 포함합니다.

>비Microsoft 서비스 사용되지 않습니다.

#### <a name="data-access-via-bots"></a>봇을 통한 데이터 액세스

이 앱에 봇 또는 메시징 확장 프로그램이 포함된 경우 최종 사용자 식별 정보(EUII): 팀의 모든 팀 구성원의 명단(이름, 성, 표시 이름, 이메일 주소)에 액세스하거나 추가된 채팅을 할 수 있습니다. 이 응용 프로그램은이 기능을 사용합니까?

>| **EUII에 액세스할 수 있는 정당성?**  | **EUII는 데이터베이스에 저장되어 있습니까?** | **EUII를 저장하는 정당화?** |
>|:--------------------------------|:---------------------|:--------------------------|
>| openid directory.readwrite.all 테넌트의 도메인 및 그룹에 대한 액세스를 사용하여 공개 로그인하고, 테넌트의 그룹 및 팀에 대한 액세스를 유지하기 offline_access 팀에 앱을 추가합니다. | 개방형 은 독립적 인 인증을 허용합니다. 디렉터리.readwrite.all 테넌트의 도메인 및 그룹에 대한 액세스, 테넌트의 그룹 및 팀 노트에 대한 액세스를 유지하기 offline_access 팀에 앱을 추가: 동적 신호의 응용 프로그램은 동적 신호 내에서 만든 그룹 및 권한을 적용하기 위해 팀 봇을 사용하여 동적 신호에서 활성화된 사용자가 Teams 내에서 동일한 그룹과 사용자에 액세스할 수 있도록 Teams. |  |


#### <a name="telemetry-data"></a>원격 분석 데이터

조직 식별 정보(OII) 또는 최종 사용자 식별 정보(EUII)가 이 응용 프로그램의 원격 분석 또는 로그에 표시됩니까? 그렇다면 저장되는 데이터와 보존 및 제거 정책은 무엇입니까?

>동적 신호 앱 및 플랫폼은 사용자 정보를 활용하여 Microsoft Teams 통합을 용이하게 합니다. 이 정보는 동적 신호 플랫폼 내에서 적절한 권한을 가진 사용자가 사용할 수 있습니다. 관련 정보는 이름, 표시 이름 및 이메일입니다. 이 정보는 동적 신호 라이센스가 있는 각 조직의 정책에 따라 동적 신호 플랫폼 로그 내에 저장됩니다.

#### <a name="organizational-controls-for-data-stored-by-partner"></a>파트너가 저장한 데이터에 대한 조직 제어

조직의 관리자가 파트너 시스템에서 자신의 정보를 제어하는 방법을 설명해 보세요. 예를 들어 삭제, 보존, 감사, 보관, 최종 사용자 정책 등

>등록 중에 수집되고 동적 신호 플랫폼에 저장된 PII 데이터에는 이름, 성, 이메일/식별자 및 브랜드 및/또는 대행사 파트너가 설정한 사용자 지정 필드가 포함됩니다. 회원이 oAuth 등록을 사용하여 Facebook 이나 트위터를 사용하는 경우 노출 된 사용자 데이터의 일부가 동적 신호 플랫폼에 제시되어 데이터를 미리 채웁니다. 이 데이터에는 이름, 위치 및 사진이 포함됩니다. 사용자는 커뮤니티용 바이오 페이지에서 사용자에게 제공되는 정보와 데이터를 제어할 수 있습니다. 회원은 개인 또는 브랜드 사진 로드, 소셜 계정/채널 연결, 프로그램의 사용/포인트를 바이오 페이지에 표시할 수 있습니다.

#### <a name="human-review-of-organizational-information"></a>조직 정보의 인간 검토

이 앱에서 수집하거나 저장되는 조직 식별 정보(OII) 데이터를 검토하거나 분석하는 데 관여하는 사람이 있습니까?

>아니요

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="mcas"

[Microsoft Cloud App Security](https://www.microsoft.com/enterprise-mobility-security/cloud-app-security) 카탈로그의 정보는 아래에 나타납니다.

<iframe height='1020' title='Microsoft Cloud App Security 정보' src='https://appmcasinfoprod.azurewebsites.net/#/dashboard/35740' frameborder='no' style='width: 100%;'></iframe>

<a href="https://appmcasinfoprod.azurewebsites.net/#/dashboard/35740" target="_blank">새 탭에서 보기</a>

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

