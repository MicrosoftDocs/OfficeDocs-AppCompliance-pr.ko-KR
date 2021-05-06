---
title: 스택 오버플로에 의해 Teams 스택 오버플로에 대한 응용 프로그램 정보
ms.author: elmalova
author: elenamalova
ms.date: 08/06/2020
ms.topic: article
ms.service: attestation
certification_type: attested
description: CSA STAR 레지스트리의 Teams, 데이터 처리 정책, Microsoft Cloud App Security 앱 카탈로그 정보 및 보안/규정 준수 정보에 대해 사용할 수 있는 모든 보안 및 규정 준수 정보입니다.
zone_pivot_groups: app-info-data-mcas
ms.openlocfilehash: fbc9cc478287f752b14f47a4c4769e14eb96ff0b
ms.sourcegitcommit: 50bd8e07d9355ae65935767a34aca39c46ade8f4
ms.translationtype: MT
ms.contentlocale: ko-KR
ms.lasthandoff: 05/06/2021
ms.locfileid: "52248316"
---
# <a name="stack-overflow-for-teams"></a>Stack Overflow for Teams

<p></p>
<img alt="Publisher Attestation: The information on this page is based on a self-assessment report provided by the app developer on the security, compliance, and data handling practices followed by this app. Microsoft makes no guarantees regarding the accuracy of the information." src="../media/attested.png" width="650" />
<p>개발자가 마지막으로 업데이트한 날짜: 2020년 8월 6일</p>

* <a href="https://teams.microsoft.com/l/app/4783e622-5303-4ea7-a211-ef0dd405da73" target="_blank">저장소의 Teams 보기</a>
* <a href="https://appsource.microsoft.com/product/office/WA200000739" target="_blank">AppSource의 보기</a>

::: zone pivot="general"

### <a name="general-information"></a>일반 정보

Microsoft에 대한 스택 오버플로에서 제공하는 정보:

| **정보** | **응답** |
|:----------------|:-------------|
| 앱 이름 | Stack Overflow for Teams |
| ID | WA200000739 |
| 기능 | 봇, 탭, 메시징 익스텐션 |
| Office 365 클라이언트 지원 | Microsoft Teams |
| 파트너 회사 이름 | Stack Overflow |
| 파트너 웹 사이트의 URL | [https://stackoverflow.com](https://stackoverflow.com) |
| 개인 정보 취급 방침의 URL | [https://stackoverflow.com/legal/privacy-policy](https://stackoverflow.com/legal/privacy-policy) |
| 사용 약관 URL | [https://stackoverflow.com/legal/terms-of-service/public](https://stackoverflow.com/legal/terms-of-service/public) |

 [!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="data"

### <a name="how-the-app-handles-data"></a>앱이 데이터를 처리하는 방법

이 정보는 이 앱이 조직 데이터를 수집 및 저장하는 방법 및 앱이 수집하는 데이터를 통해 조직이 가지는 컨트롤에 대한 스택 오버플로에서 제공했습니다.

#### <a name="data-access-using-microsoft-graph"></a>Microsoft 365를 사용한 데이터 Graph

이 앱에 [Graph Microsoft 사용자 권한을](https://docs.microsoft.com/graph/permissions-reference) 나열합니다.

>이 응용 프로그램은 Microsoft 응용 프로그램을 Graph.


#### <a name="non-microsoft-services-used"></a>비영구 Microsoft 서비스

앱이 Microsoft가 아닌 서비스로 조직 데이터를 전송하거나 공유하는 경우 앱에서 사용하는 비 Microsoft 서비스, 전송되는 데이터를 나열하고 앱이 이 정보를 전송해야 하는 이유에 대한 사유를 포함합니다.

>비영구 Microsoft 서비스 사용되지 않습니다.

#### <a name="data-access-via-bots"></a>봇을 통한 데이터 액세스

이 앱에 봇 또는 메시징 확장이 포함되어 있는 경우 팀 구성원의 명단(이름, 성, 표시 이름, 전자 메일 주소)이나 팀 구성원이 추가된 채팅의 최종 사용자 식별 정보(EUII)에 액세스할 수 있습니다. 이 앱이 이 기능을 사용하나요?

>| **EUII 액세스의 사유는 무엇입니까?**  | **EUII가 데이터베이스에 저장되어 있나요?** | **EUII 저장의 사유는 무엇입니까?** |
>|:--------------------------------|:---------------------|:--------------------------|
>| 봇은 대화 API를 사용하여 팀 채팅에 직접 메시지를 게시합니다. 또한 봇은 이 로스터를 사용하여 사용자에게 직접 메시지를 보낼 수 있습니다. | 로스터의 데이터는 저장하지 않습니다. |  |



#### <a name="telemetry-data"></a>원격 분석 데이터

이 응용 프로그램의 원격 분석 또는 로그에 OII(조직 식별 정보) 또는 EUII(최종 사용자 식별 정보)가 나타나나요? 그렇다면 저장되는 데이터와 보존 및 제거 정책에 대해 설명하세요.

>아니요. MS Teams 및 SO Teams 매핑은 SO Teams 제품에서 발생합니다.
MS Teams 식별 가능 ID를 보내주며 사용자를 매핑하기 위해 내부적으로 저장합니다.
또한 MS Teams 봇 요청에 대한 JWT(위조 금지) 및 Tab 요청은 SO 쿠키를 사용하여 유효성을 검사합니다.

#### <a name="organizational-controls-for-data-stored-by-partner"></a>파트너가 저장한 데이터에 대한 조직 제어

조직의 관리자가 파트너 시스템에서 정보를 제어하는 방법에 대해 설명하는 방법 삭제, 보존, 감사, 보관, 최종 사용자 정책 등

>ISO27001을 기반으로 보안 프로그램을 구축합니다. 데이터는 논리적으로 자체 SQL 분리되고 별도의 데이터베이스 집합에 저장됩니다. 데이터는 팀 요청에서만 액세스할 수 있는 논리적으로 별도의 데이터 저장소에 저장됩니다.

#### <a name="human-review-of-organizational-information"></a>조직 정보의 인적 검토

사람이 이 앱에서 수집하거나 저장하는 OII(조직 식별 정보) 데이터를 검토하거나 분석하는 데 관여하나요?

>아니요

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="mcas"

Microsoft Cloud App Security [카탈로그의](https://www.microsoft.com/enterprise-mobility-security/cloud-app-security) 정보가 아래에 표시됩니다.

<iframe height='1020' title='Microsoft Cloud App Security 정보' src='https://appmcasinfoprod.azurewebsites.net/#/dashboard/23308' frameborder='no' style='width: 100%;'></iframe>

<a href="https://appmcasinfoprod.azurewebsites.net/#/dashboard/23308" target="_blank">새 탭에서 보기</a>

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

