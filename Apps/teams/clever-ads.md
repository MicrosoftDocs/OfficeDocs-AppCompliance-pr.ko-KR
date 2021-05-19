---
title: 영리한 광고에 의해 영리한 광고에 대한 응용 프로그램 정보
ms.author: elmalova
author: elenamalova
ms.date: 04/24/2020
ms.topic: article
ms.service: attestation
certification_type: attested
description: 영리한 광고, 데이터 처리 정책, Microsoft Cloud App Security 앱 카탈로그 정보, CSA STAR 레지스트리의 보안/규정 준수 정보에 대한 사용 가능한 모든 보안 및 규정 준수 정보.
zone_pivot_groups: app-info-data-mcas
ms.openlocfilehash: 0b092ef8ab27bec0a2f5c3bf294b301a71d1649a
ms.sourcegitcommit: a44420a99a1a3a9d0e49f4be66f266e2d4ca7bbb
ms.translationtype: MT
ms.contentlocale: ko-KR
ms.lasthandoff: 05/19/2021
ms.locfileid: "52552279"
---
# <a name="clever-ads"></a>Clever Ads

<p></p>
<img alt="Publisher Attestation: The information on this page is based on a self-assessment report provided by the app developer on the security, compliance, and data handling practices followed by this app. Microsoft makes no guarantees regarding the accuracy of the information." src="../media/attested.png" width="650" />
<p>최종 업데이트: 2020년 4월 24일</p>

* <a href="https://teams.microsoft.com/l/app/ac2b56c0-f2a5-4e90-b618-882f8d3596f0" target="_blank">Teams 스토어에서 보기</a>
* <a href="https://appsource.microsoft.com/product/office/WA200001182" target="_blank">앱소스에서 보기</a>

::: zone pivot="general"

### <a name="general-information"></a>일반 정보

영리한 광고가 Microsoft에 제공한 정보:

| **정보** | **응답** |
|:----------------|:-------------|
| 앱 이름 | Clever Ads |
| ID | WA200001182 |
| 지원되는 Office 365 클라이언트 | Microsoft Teams |
| 파트너 회사 이름 | Clever Ads |
| 파트너 웹사이트의 URL | [https://www.cleverads.com/](https://www.cleverads.com/) |
| 개인정보 처리방침의 URL | [https://www.cleverads.com/privacy-policy](https://www.cleverads.com/privacy-policy) |
| 이용 약관의 URL | [https://www.cleverads.com/terms-conditions](https://www.cleverads.com/terms-conditions) |

 [!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="data"

### <a name="how-the-app-handles-data"></a>앱이 데이터를 처리하는 방법

이 정보는 이 앱이 조직 데이터를 수집하고 저장하는 방법과 앱이 수집하는 데이터에 대한 조직에서 가질 수 있는 제어에 대한 영리한 광고에 의해 제공됩니다.

#### <a name="data-access-using-microsoft-graph"></a>Microsoft Graph 을 사용하여 데이터 액세스

이 [앱에서 필요한 Microsoft Graph 권한을 나열합니다.](https://docs.microsoft.com/graph/permissions-reference)

>| **사용 권한**  | **권한 유형(위임/응용 프로그램)** | **데이터가 수집되고 있습니까? 그것을 수집하기위한 정당화?** | **데이터가 저장되어 있습니까? 그것을 저장하는 정당화?** | **Azure AD 앱 ID** |
>|:----------------|:--------------------|:---------------------------------------------------|:--------------------------|:--------------------------|
>| User.Read | 위임 | 사용자.읽기: 사용자를 식별하기 위해 UPN, AzureObjectId를 저장합니다. | 사용자.Read, 사용자가 우리의 응용 프로그램 대시보드에 로그인 할 수 있습니다. 우리는 UPN, AzureObjectId를 사용하여 사용자 로그인을 사용합니다. | ac2b56c0-f2a5-4e90-b618-882f8d3596f0 |


#### <a name="non-microsoft-services-used"></a>사용되지 Microsoft 서비스

앱이 Microsoft 가 아닌 서비스와 조직 데이터를 전송하거나 공유하는 경우 앱에서 사용하는 비Microsoft 서비스, 전송되는 데이터를 나열하고 앱이 이 정보를 전송해야 하는 이유에 대한 명분을 포함합니다.

>비Microsoft 서비스 사용되지 않습니다.

#### <a name="data-access-via-bots"></a>봇을 통한 데이터 액세스

이 앱에 봇 또는 메시징 확장 프로그램이 포함된 경우 최종 사용자 식별 정보(EUII): 팀의 모든 팀 구성원의 명단(이름, 성, 표시 이름, 이메일 주소)에 액세스하거나 추가된 채팅을 할 수 있습니다. 이 응용 프로그램은이 기능을 사용합니까?

>| **EUII에 액세스할 수 있는 정당성?**  | **EUII는 데이터베이스에 저장되어 있습니까?** | **EUII를 저장하는 정당화?** |
>|:--------------------------------|:---------------------|:--------------------------|
>| 앱은 명단에 액세스하여 사용자가 팀에 속해 있는지 아닌지 확인하고 사용자가 팀에 보낸 메시지를 전송합니다. | 사용자 ID, azureObjectId, UPN, 테넌트Id, conversationId 및 serviceUrl을 저장하여 사용자 또는 팀에 메시지를 보내고 대시보드 탭에 액세스할 때 그를 식별할 수 있습니다. |  |


#### <a name="telemetry-data"></a>원격 분석 데이터

조직 식별 정보(OII) 또는 최종 사용자 식별 정보(EUII)가 이 응용 프로그램의 원격 분석 또는 로그에 표시됩니까? 그렇다면 저장되는 데이터와 보존 및 제거 정책은 무엇입니까?

>당사는 원격 분석 이나 로그에 조직 정보를 저장 하지 않습니다. 우리는 단지 봇에 메시지를 보내거나 버튼을 클릭하는 것과 같은 사용자 작업을 기록, 심지어 그 로그에서 사용자의 ID는 우리의 내부 사용자 ID입니다, 마이크로 소프트 팀 ID와 관련이 없습니다.

#### <a name="organizational-controls-for-data-stored-by-partner"></a>파트너가 저장한 데이터에 대한 조직 제어

조직의 관리자가 파트너 시스템에서 자신의 정보를 제어하는 방법을 설명해 보세요. 예를 들어 삭제, 보존, 감사, 보관, 최종 사용자 정책 등

>응용 프로그램 데이터는 Google 클라우드에서 호스팅되는 MySQL 데이터베이스에 저장되며, 백업 시스템은 데이터베이스에 추가되며 PMA 및 보호된 IP를 사용하여 처리됩니다.

#### <a name="human-review-of-organizational-information"></a>조직 정보의 인간 검토

이 앱에서 수집하거나 저장되는 조직 식별 정보(OII) 데이터를 검토하거나 분석하는 데 관여하는 사람이 있습니까?

>예

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="mcas"

[Microsoft Cloud App Security](https://www.microsoft.com/enterprise-mobility-security/cloud-app-security) 카탈로그의 정보는 아래에 나타납니다.

<iframe height='1020' title='Microsoft Cloud App Security 정보' src='https://appmcasinfoprod.azurewebsites.net/#/dashboard/35867' frameborder='no' style='width: 100%;'></iframe>

<a href="https://appmcasinfoprod.azurewebsites.net/#/dashboard/35867" target="_blank">새 탭에서 보기</a>

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

