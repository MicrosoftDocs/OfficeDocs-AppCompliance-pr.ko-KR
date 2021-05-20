---
title: Asana의 응용 프로그램 Outlook 대한 응용 프로그램 정보
ms.author: elmalova
author: elenamalova
ms.date: 11/02/2020
ms.topic: article
ms.service: attestation
certification_type: attested
description: CSA STAR 레지스트리의 Outlook, 데이터 처리 정책, Microsoft Cloud App Security 앱 카탈로그 정보 및 보안/규정 준수 정보에 대해 사용할 수 있는 모든 보안 및 규정 준수 정보입니다.
zone_pivot_groups: app-info-data-mcas
ms.openlocfilehash: cd3d403d7b25c1ad5dda60dff8d93c18dfe59c30
ms.sourcegitcommit: a44420a99a1a3a9d0e49f4be66f266e2d4ca7bbb
ms.translationtype: MT
ms.contentlocale: ko-KR
ms.lasthandoff: 05/19/2021
ms.locfileid: "52553749"
---
# <a name="asana-for-outlook"></a>아사나 for Outlook

<p></p>
<img alt="Publisher Attestation: The information on this page is based on a self-assessment report provided by the app developer on the security, compliance, and data handling practices followed by this app. Microsoft makes no guarantees regarding the accuracy of the information." src="../media/attested.png" width="650" />
<p>개발자가 마지막으로 업데이트한 날짜: 2020년 11월 2일</p>

* <a href="https://appsource.microsoft.com/product/office/WA104381833" target="_blank">AppSource의 보기</a>

::: zone pivot="general"

### <a name="general-information"></a>일반 정보

아사나가 Microsoft에 제공한 정보:

| **정보** | **응답** |
|:----------------|:-------------|
| 앱 이름 | 아사나 for Outlook |
| ID | WA104381833 |
| Office 365 클라이언트 지원 | Outlook 2016, mac, Windows Outlook 2016 이상, 웹에서 Outlook 이상 사용 |
| 파트너 회사 이름 | Asana |
| 파트너 웹 사이트의 URL | [https://asana.com/](https://asana.com/) |
| 개인 정보 취급 방침의 URL | [https://asana.com/terms#privacy-policy](https://asana.com/terms#privacy-policy) |
| 사용 약관 URL | [https://go.microsoft.com/fwlink/?LinkID=521715&amp;omkt=en-US](https://go.microsoft.com/fwlink/?LinkID=521715&amp;omkt=en-US) |

 [!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="data"

### <a name="how-the-app-handles-data"></a>앱이 데이터를 처리하는 방법

이 정보는 아사나에서 이 앱이 조직 데이터를 수집 및 저장하는 방법 및 조직이 수집하는 데이터를 통해 조직이 제공하는 컨트롤에 대해 제공됩니다.

#### <a name="data-access-using-microsoft-graph"></a>Microsoft 365를 사용한 데이터 Graph

이 앱에 [Graph Microsoft 사용자 권한을](https://docs.microsoft.com/graph/permissions-reference) 나열합니다.

>이 응용 프로그램은 Microsoft 응용 프로그램을 Graph.


#### <a name="non-microsoft-services-used"></a>비영구 Microsoft 서비스

앱이 Microsoft가 아닌 서비스로 조직 데이터를 전송하거나 공유하는 경우 앱에서 사용하는 비 Microsoft 서비스, 전송되는 데이터를 나열하고 앱이 이 정보를 전송해야 하는 이유에 대한 사유를 포함합니다.

>| **모든 비 Microsoft 서비스 OII가 다음으로 전송됩니다.** |  **전송되는 OII는 무엇입니까?** | **OII 전송의 사당성** |
>|:-------------------|:--------------------------|:--------------------------|
>| 추가 기능에서는 사용자가 요청한 경우 기본 전자 메일 정보(보낸 사람, 수신자, 제목, 본문) 및 첨부 파일을 Asana로 전송합니다. |  | 전자 메일 - 작업 창에 표시되는 경우 현재 열려 있는 전자 메일을 읽습니다. - 현재 열려 있는 전자 메일 첨부 파일을 읽어 아사나 작업에 업로드합니다. - 이를 통해 사용자는 전자 메일의 정보를 통해 아사나에서 작업을 신속하게 수행할 수 있습니다. |



#### <a name="telemetry-data"></a>원격 분석 데이터

이 응용 프로그램의 원격 분석 또는 로그에 OII(조직 식별 정보) 또는 EUII(최종 사용자 식별 정보)가 나타나나요? 그렇다면 저장되는 데이터와 보존 및 제거 정책에 대해 설명하세요.

>응용 프로그램은 아사나 데이터와 관련된 정보만 기록합니다. 사용자가 전자 메일을 명시적으로 Outlook 첨부하거나 첨부 파일을 아사나에 업로드한 다음 내용을 기록하지 않는 경우만 사용자 정보와 관련된 모든 내용을 기록할 수 있습니다. 일부 사용자 데이터를 포함할 수 있는 서버에는 단기 로그가 있지만 72시간 미만의 기간으로 제한됩니다.

#### <a name="organizational-controls-for-data-stored-by-partner"></a>파트너가 저장한 데이터에 대한 조직 제어

조직의 관리자가 파트너 시스템에서 정보를 제어하는 방법에 대해 설명하는 방법 삭제, 보존, 감사, 보관, 최종 사용자 정책 등

>Enterprise 고객이 AES-256을 사용하여 미사용 암호화를 보장했습니다. 데이터는 Amazon 웹 서비스에 저장되고 AWS는 키 관리 시스템을 사용하여 암호화 키를 관리합니다. 모든 관리자를 위한 2FA가 있습니다. 액세스 권한은 최소 권한 원칙에 따라 부여됩니다.
아사나 조직 관리자는 SAML, SCIM, 서비스 계정을 설정하고 도구에 추가된 데이터를 능가하는 보기를 할 수 있습니다. 관리자는 관리 콘솔 내에서 전체 조직 내보내기 및 필요한 경우 감사를 요청할 수 있습니다.

#### <a name="human-review-of-organizational-information"></a>조직 정보의 인적 검토

사람이 이 앱에서 수집하거나 저장하는 OII(조직 식별 정보) 데이터를 검토하거나 분석하는 데 관여하나요?

>아니요

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="mcas"

Microsoft Cloud App Security [카탈로그의](https://www.microsoft.com/enterprise-mobility-security/cloud-app-security) 정보가 아래에 표시됩니다.

<iframe height='1020' title='Microsoft Cloud App Security 정보' src='https://appmcasinfoprod.azurewebsites.net/#/dashboard/10417' frameborder='no' style='width: 100%;'></iframe>

<a href="https://appmcasinfoprod.azurewebsites.net/#/dashboard/10417" target="_blank">새 탭에서 보기</a>

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

