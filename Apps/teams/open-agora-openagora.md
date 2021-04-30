---
title: Open Agora의 OpenAgora에 대한 응용 프로그램 정보
ms.author: elmalova
author: elenamalova
ms.date: 12/16/2019
ms.topic: article
ms.service: attestation
description: OpenAgora, 데이터 처리 정책, CSA STAR 레지스트리의 Microsoft Cloud App Security 앱 카탈로그 정보 및 보안/규정 준수 정보에 사용할 수 있는 모든 보안 및 규정 준수 정보
zone_pivot_groups: app-info-data-mcas
ms.openlocfilehash: a5efd1086550f8ca6874503b48703775fdd3416b
ms.sourcegitcommit: e97156a6eaf1d5ec5c26fd14add210a92bacd944
ms.translationtype: MT
ms.contentlocale: ko-KR
ms.lasthandoff: 04/30/2021
ms.locfileid: "52094745"
---
# <a name="openagora"></a>OpenAgora

<p></p>
<img alt="Publisher Attestation: The information on this page is based on a self-assessment report provided by the app developer on the security, compliance, and data handling practices followed by this app. Microsoft makes no guarantees regarding the accuracy of the information." src="../media/attested.png" width="650" />
<p>개발자가 마지막으로 업데이트한 날짜: 2019년 12월 16일</p>

* <a href="https://teams.microsoft.com/l/app/cb6d958a-d969-4081-8272-71fa94f1697f" target="_blank">저장소의 Teams 보기</a>
* <a href="https://appsource.microsoft.com/product/office/WA104381473" target="_blank">AppSource의 보기</a>

::: zone pivot="general"

### <a name="general-information"></a>일반 정보

Open Agora에서 Microsoft에 제공한 정보:

| **정보** | **응답** |
|:----------------|:-------------|
| 앱 이름 | OpenAgora |
| ID | WA104381473 |
| 기능 | 봇, 탭 |
| Office 365 클라이언트 지원 | Microsoft Teams |
| 파트너 회사 이름 | Open Agora |
| 파트너 웹 사이트의 URL | [https://www.open-agora.com/en/products/teams](https://www.open-agora.com/en/products/teams) |
| 응용 프로그램 Teams 페이지의 URL입니다. | [https://www.open-agora.com/en/products/teams/support](https://www.open-agora.com/en/products/teams/support) |
| 개인 정보 취급 방침의 URL | [https://www.open-agora.com/en/products/teams/privacy-policy](https://www.open-agora.com/en/products/teams/privacy-policy) |
| 사용 약관 URL | [https://www.open-agora.com/en/terms](https://www.open-agora.com/en/terms) |

 [!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="data"

### <a name="how-the-app-handles-data"></a>앱이 데이터를 처리하는 방법

이 정보는 Open Agora에서 이 앱이 조직 데이터를 수집하고 저장하는 방법 및 앱이 수집하는 데이터를 통해 조직에서 제공하는 컨트롤에 대해 제공됩니다.

#### <a name="data-access-using-microsoft-graph"></a>Microsoft 365를 사용한 데이터 Graph

이 앱에 [Graph Microsoft 사용자 권한을](https://docs.microsoft.com/graph/permissions-reference) 나열합니다.

>| **사용 권한**  | **사용 권한 유형(위임/응용 프로그램)** | **데이터가 수집하나요? 수집의 사당성** | **데이터가 저장되어 있나요? 저장 사정이 있나요?** | **Azure AD 앱 ID** |
>|:----------------|:--------------------|:---------------------------------------------------|:--------------------------|:--------------------------|
>| User.Read | 위임 | 사용자&#8217;Azure Active Directory ID입니다. | 사용자에게 표시되는 데이터만 보고 관리할 수 있도록 하는 사용자 ID입니다. |  |


#### <a name="non-microsoft-services-used"></a>비영구 Microsoft 서비스

앱이 Microsoft가 아닌 서비스로 조직 데이터를 전송하거나 공유하는 경우 앱에서 사용하는 비 Microsoft 서비스, 전송되는 데이터를 나열하고 앱이 이 정보를 전송해야 하는 이유에 대한 사유를 포함합니다.

>비영구 Microsoft 서비스 사용되지 않습니다.

#### <a name="data-access-via-bots"></a>봇을 통한 데이터 액세스

이 앱에 봇 또는 메시징 확장이 포함되어 있는 경우 팀 구성원의 명단(이름, 성, 표시 이름, 전자 메일 주소)이나 팀 구성원이 추가된 채팅의 최종 사용자 식별 정보(EUII)에 액세스할 수 있습니다. 이 앱이 이 기능을 사용하나요?

>| **EUII 액세스의 사유는 무엇입니까?**  | **EUII가 데이터베이스에 저장되어 있나요?** | **EUII 저장의 사유는 무엇입니까?** |
>|:--------------------------------|:---------------------|:--------------------------|
>| **이름** - 투표자 이름을 표시하는 데 사용됩니다. **전자 메일** - 팀과 채팅에서 사용자를 식별하는 데 사용됩니다. 투표자 고유 식별자로 사용됩니다. 는 사용자 의견에 응답하는 데 Teams. 사용자에게 원치 않는 전자 메일이 전송되지 않습니다. | 이름 및 성, 표시 이름, 전자 메일 주소 |  |



#### <a name="telemetry-data"></a>원격 분석 데이터

이 응용 프로그램의 원격 분석 또는 로그에 OII(조직 식별 정보) 또는 EUII(최종 사용자 식별 정보)가 나타나나요? 그렇다면 저장되는 데이터와 보존 및 제거 정책에 대해 설명하세요.

>모든 EUII 및 OII는 응용 프로그램 로그를 통해 검색할 수 있으며, 모든 응용 프로그램 데이터(개인 소유 서버, 컨테이너 사용, 제한된 액세스)와 보안 수준이 동일합니다.
로그 데이터는 2년 후에 삭제됩니다.

#### <a name="organizational-controls-for-data-stored-by-partner"></a>파트너가 저장한 데이터에 대한 조직 제어

조직의 관리자가 파트너 시스템에서 정보를 제어하는 방법에 대해 설명하는 방법 삭제, 보존, 감사, 보관, 최종 사용자 정책 등

>요청이 있을 경우 고객 데이터를 감사하고 응용 프로그램 제거 후 삭제할 수 있습니다.


[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="mcas"

Microsoft Cloud App Security [카탈로그의](https://www.microsoft.com/enterprise-mobility-security/cloud-app-security) 정보가 아래에 표시됩니다.

<iframe height='1020' title='Microsoft Cloud App Security 정보' src='https://appmcasinfoprod.azurewebsites.net/#/dashboard/35694' frameborder='no' style='width: 100%;'></iframe>

<a href="https://appmcasinfoprod.azurewebsites.net/#/dashboard/35694" target="_blank">새 탭에서 보기</a>

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

