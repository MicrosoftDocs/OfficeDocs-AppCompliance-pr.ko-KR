---
title: 동적 신호로 동적 신호에 대한 응용 프로그램 정보
ms.author: elmalova
author: elenamalova
ms.date: 12/16/2019
ms.topic: article
ms.service: attestation
certification_type: attested
description: 동적 신호, 데이터 처리 정책, CSA STAR 레지스트리의 Microsoft Cloud App Security 앱 카탈로그 정보 및 보안/규정 준수 정보에 사용할 수 있는 모든 보안 및 규정 준수 정보
zone_pivot_groups: app-info-data-mcas
ms.openlocfilehash: 5b5906e8eee51821481de11c3cbd720600d4c36e
ms.sourcegitcommit: d85595f6518d8d05f0aee75380f51659908b6bcb
ms.translationtype: MT
ms.contentlocale: ko-KR
ms.lasthandoff: 09/12/2021
ms.locfileid: "59288237"
---
# <a name="dynamic-signal"></a>Dynamic Signal

<p></p>
<img alt="Publisher Attestation: The information on this page is based on a self-assessment report provided by the app developer on the security, compliance, and data handling practices followed by this app. Microsoft makes no guarantees regarding the accuracy of the information." src="../media/attested.png" width="650" />
<p>개발자가 마지막으로 업데이트한 날짜: 2019년 12월 16일</p>

* <a href="https://teams.microsoft.com/l/app/6f98619e-a822-4a74-8ee9-af6a358f2750" target="_blank">저장소의 Teams 보기</a>
* <a href="https://appsource.microsoft.com/product/office/WA200000102" target="_blank">AppSource의 보기</a>

::: zone pivot="general"

### <a name="general-information"></a>일반 정보

동적 신호에서 Microsoft에 제공하는 정보:

| **정보** | **응답** |
|:----------------|:-------------|
| 앱 이름 | Dynamic Signal |
| ID | WA200000102 |
| Office 365 클라이언트 지원 | Microsoft Teams |
| 파트너 회사 이름 | Dynamic Signal |
| 파트너 웹 사이트의 URL | [https://www.dynamicsignal.com](https://www.dynamicsignal.com) |
| 응용 프로그램 Teams 페이지의 URL입니다. | [https://support.dynamicsignal.com/hc/en-us/requests/new?tic...](https://support.dynamicsignal.com/hc/en-us/requests/new?ticket_form_id=360000290032) |
| 개인 정보 취급 방침의 URL | [https://dynamicsignal.com/privacy/](https://dynamicsignal.com/privacy/) |
| 사용 약관 URL | [https://dynamicsignal.com/terms-of-use/platform-terms-of-us...](https://dynamicsignal.com/terms-of-use/platform-terms-of-use/) |

 [!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="data"

### <a name="how-the-app-handles-data"></a>앱이 데이터를 처리하는 방법

이 정보는 이 앱이 조직 데이터를 수집 및 저장하는 방법 및 앱이 수집하는 데이터를 통해 조직이 하게 될 컨트롤에 대한 동적 신호에 의해 제공됩니다.

#### <a name="data-access-using-microsoft-graph"></a>Microsoft 365를 사용한 데이터 Graph

이 앱에 [Graph Microsoft 사용자 권한을](https://docs.microsoft.com/graph/permissions-reference) 나열합니다.

>| **사용 권한**  | **사용 권한 유형(위임/ 응용 프로그램)** | **데이터가 수집하나요? 수집의 사당성** | **데이터가 저장되어 있나요? 저장 사정이 있나요?** | **Azure AD 앱 ID** |
>|:----------------|:------------------------------------------------|:--------------------------------------------------------|:--------------------------------------------------|:--------------------|
>| User.Read | 위임 | 동적 신호는 실시간으로 사용자의 활성화 및 비활성화를 간소화하기 위해 Azure AD에서 해당 플랫폼으로 사용자를 동기화합니다. 동기화가 진행되는 동안 사용자가 해당 응용 프로그램을 사용할 수 있도록 데이터는 동적 신호 내에 저장됩니다. | 동적 신호 플랫폼 사용자를 Azure AD와 동기화하기 위한 특정 사용자의 읽기 권한 | [79ff4a2a-e22b-47d5-94dc-ef76fe46af75](https://docs.microsoft.com/microsoft-365-app-certification/azure/79ff4a2a-e22b-47d5-94dc-ef76fe46af75) |
>| User.Read.All | 위임 | 동적 신호는 실시간으로 사용자의 활성화 및 비활성화를 간소화하기 위해 Azure AD에서 해당 플랫폼으로 사용자를 동기화합니다. 동기화가 진행되는 동안 사용자가 해당 응용 프로그램을 사용할 수 있도록 데이터는 동적 신호 내에 저장됩니다. | 동적 신호 플랫폼 사용자를 Azure AD와 동기화하기 위한 특정 사용자의 읽기 권한 | [79ff4a2a-e22b-47d5-94dc-ef76fe46af75](https://docs.microsoft.com/microsoft-365-app-certification/azure/79ff4a2a-e22b-47d5-94dc-ef76fe46af75) |
>| offline_access | 위임 | 동적 신호는 실시간으로 사용자의 활성화 및 비활성화를 간소화하기 위해 Azure AD에서 해당 플랫폼으로 사용자를 동기화합니다. 동기화가 진행되는 동안 사용자가 해당 응용 프로그램을 사용할 수 있도록 데이터는 동적 신호 내에 저장됩니다. | 테넌트의 그룹 및 팀에 대한 액세스 권한을 보유합니다. | [79ff4a2a-e22b-47d5-94dc-ef76fe46af75](https://docs.microsoft.com/microsoft-365-app-certification/azure/79ff4a2a-e22b-47d5-94dc-ef76fe46af75) |
>| openid | 위임 | 동적 신호는 실시간으로 사용자의 활성화 및 비활성화를 간소화하기 위해 Azure AD에서 해당 플랫폼으로 사용자를 동기화합니다. 동기화가 진행되는 동안 사용자가 해당 응용 프로그램을 사용할 수 있도록 데이터는 동적 신호 내에 저장됩니다. | 동적 신호 응용 프로그램을 통해 사용자를 인증합니다. | [79ff4a2a-e22b-47d5-94dc-ef76fe46af75](https://docs.microsoft.com/microsoft-365-app-certification/azure/79ff4a2a-e22b-47d5-94dc-ef76fe46af75) |


#### <a name="non-microsoft-services-used"></a>비영구 Microsoft 서비스

앱이 Microsoft가 아닌 서비스로 조직 데이터를 전송하거나 공유하는 경우 앱에서 사용하는 비 Microsoft 서비스, 전송되는 데이터를 나열하고 앱이 이 정보를 전송해야 하는 이유에 대한 사유를 포함합니다.

>비영구 Microsoft 서비스 사용되지 않습니다.

#### <a name="data-access-via-bots"></a>봇을 통한 데이터 액세스

이 앱에 봇 또는 메시징 확장이 포함되어 있는 경우 팀 구성원의 명단(이름, 성, 표시 이름, 전자 메일 주소)이나 팀 구성원이 추가된 채팅의 최종 사용자 식별 정보(EUII)에 액세스할 수 있습니다. 이 앱이 이 기능을 사용하나요?

>| **EUII 액세스의 사유는 무엇입니까?**  | **EUII가 데이터베이스에 저장되어 있나요?** | **EUII 저장의 사유는 무엇입니까?** |
>|:---------------------------------------|:-----------------------------------|:------------------------------------|
>| openid 테넌트의 도메인 및 그룹에 대한 openid directory.readwrite.all 액세스 권한을 사용하여 로그인하고, 테넌트의 그룹 및 팀에 대한 액세스 offline_access 보존할 수 있도록 팀에 앱을 추가합니다. | openid 독립 인증을 허용합니다. 테넌트의 도메인 및 그룹에 대한 디렉터리.readwrite.all 액세스, 테넌트의 그룹 및 팀에 대한 액세스 offline_access 팀에 앱을 추가합니다. 동적 신호의 응용 프로그램은 팀 봇을 사용하여 동적 신호 내에서 만든 그룹 및 사용 권한을 Teams 동적 신호에서 활성 상태인 사용자가 테넌트 내의 동일한 그룹 및 사용자에 액세스할 수 있도록 Teams. |  |


#### <a name="telemetry-data"></a>원격 분석 데이터

이 응용 프로그램의 원격 분석 또는 로그에 OII(조직 식별 정보) 또는 EUII(최종 사용자 식별 정보)가 나타나나요? 그렇다면 저장되는 데이터와 보존 및 제거 정책에 대해 설명하세요.

>동적 신호 앱 및 플랫폼은 사용자 정보를 활용하여 사용자와 통합을 Microsoft Teams. 이 정보는 동적 신호 플랫폼 내에서 적절한 사용 권한이 있는 사용자가 사용할 수 있습니다. 관련 정보는 이름, 표시 이름 및 전자 메일입니다. 이 정보는 동적 신호 라이선스를 사용하여 각 조직의 정책에 따라 동적 신호 플랫폼 로그 내에 저장됩니다.

#### <a name="organizational-controls-for-data-stored-by-partner"></a>파트너가 저장한 데이터에 대한 조직 제어

조직의 관리자가 파트너 시스템에서 정보를 제어하는 방법에 대해 설명하는 방법 삭제, 보존, 감사, 보관, 최종 사용자 정책 등

>등록 중에 수집되고 동적 신호 플랫폼 내에 저장되는 PII 데이터에는 이름, 성, 전자 메일/식별자 및 브랜드 및/또는 대리점 파트너가 설정한 모든 사용자 정의 필드가 포함됩니다. 구성원이 oAuth 등록을 사용하여 Facebook 또는 Twitter를 사용하는 경우 노출된 사용자 데이터의 일부가 동적 신호 플랫폼에 표시되어 데이터를 미리 채울 수 있습니다. 이 데이터에는 이름, 위치 및 사진이 포함됩니다. 사용자는 커뮤니티의 Bio 페이지에서 사용자에게 어떤 정보 및 데이터를 표시하는지 제어할 수 있습니다. 구성원은 개인 또는 브랜드 사진 로드, 소셜 계정/채널 연결 및 프로그램의 사용/지점을 Bio 페이지에 표시하는 데 옵트인(opt in)할 수 있습니다.

#### <a name="human-review-of-organizational-information"></a>조직 정보의 인적 검토

사람이 이 앱에서 수집하거나 저장하는 OII(조직 식별 정보) 데이터를 검토하거나 분석하는 데 관여하나요?

>아니요

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="mcas"

Microsoft Cloud App Security [카탈로그의](https://www.microsoft.com/enterprise-mobility-security/cloud-app-security) 정보가 아래에 표시됩니다.

<iframe height='1020' title='Microsoft Cloud App Security 정보' src='https://appmcasinfoprod.azurewebsites.net/#/dashboard/35740' frameborder='no' style='width: 100%;'></iframe>

<a href="https://appmcasinfoprod.azurewebsites.net/#/dashboard/35740" target="_blank">새 탭에서 보기</a>

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

