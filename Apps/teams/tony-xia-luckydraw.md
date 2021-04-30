---
title: Tony Xia의 LuckyDraw에 대한 응용 프로그램 정보
ms.author: elmalova
author: elenamalova
ms.date: 07/21/2020
ms.topic: article
ms.service: attestation
description: LuckyDraw, 데이터 처리 정책, CSA STAR 레지스트리의 Microsoft Cloud App Security 앱 카탈로그 정보 및 보안/규정 준수 정보에 사용할 수 있는 모든 보안 및 규정 준수 정보
zone_pivot_groups: app-info-data-mcas
ms.openlocfilehash: 9b37d6e8730580ad04b69061587038957a85a2d4
ms.sourcegitcommit: e97156a6eaf1d5ec5c26fd14add210a92bacd944
ms.translationtype: MT
ms.contentlocale: ko-KR
ms.lasthandoff: 04/30/2021
ms.locfileid: "52094846"
---
# <a name="luckydraw"></a>LuckyDraw

<p></p>
<img alt="Publisher Attestation: The information on this page is based on a self-assessment report provided by the app developer on the security, compliance, and data handling practices followed by this app. Microsoft makes no guarantees regarding the accuracy of the information." src="../media/attested.png" width="650" />
<p>개발자가 마지막으로 업데이트한 날짜: 2020년 7월 21일</p>

* <a href="https://teams.microsoft.com/l/app/75c676b5-be32-430e-acee-71bcb929b297" target="_blank">저장소의 Teams 보기</a>
* <a href="https://appsource.microsoft.com/product/office/WA200000091" target="_blank">AppSource의 보기</a>

::: zone pivot="general"

### <a name="general-information"></a>일반 정보

Tony Xia가 Microsoft에 제공한 정보:

| **정보** | **응답** |
|:----------------|:-------------|
| 앱 이름 | LuckyDraw |
| ID | WA20000091 |
| 기능 | 봇, 메시징 익스텐션 |
| Office 365 클라이언트 지원 | Microsoft Teams |
| 파트너 회사 이름 | Tony Xia |
| 파트너 웹 사이트의 URL | [https://luckydraw.teetee365.com](https://luckydraw.teetee365.com) |
| 응용 프로그램 Teams 페이지의 URL입니다. | [https://luckydraw4web4prd.z7.web.core.windows.net/](https://luckydraw4web4prd.z7.web.core.windows.net/) |
| 개인 정보 취급 방침의 URL | [https://luckydraw.teetee365.com/privacy](https://luckydraw.teetee365.com/privacy) |
| 사용 약관 URL | [https://luckydraw.teetee365.com/terms](https://luckydraw.teetee365.com/terms) |

 [!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="data"

### <a name="how-the-app-handles-data"></a>앱이 데이터를 처리하는 방법

이 정보는 Tony Xia에서 이 앱이 조직 데이터를 수집하고 저장하는 방법 및 앱이 수집하는 데이터를 통해 조직이 제어할 수 있는 방법에 대해 제공했습니다.

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
>| LuckyDraw는 로스터에 액세스하지 않습니다. | LuckyDraw는 로스터에 액세스하지 않습니다. |  |



#### <a name="telemetry-data"></a>원격 분석 데이터

이 응용 프로그램의 원격 분석 또는 로그에 OII(조직 식별 정보) 또는 EUII(최종 사용자 식별 정보)가 나타나나요? 그렇다면 저장되는 데이터와 보존 및 제거 정책에 대해 설명하세요.

>EUII는 경우에 따라 기록됩니다. 예를 들어 사용자는 다행히 그리기 활동을 시작합니다. 앱은 데이터 보존이 기본값인 Azure Application Insights를 사용하고 있습니다.

#### <a name="organizational-controls-for-data-stored-by-partner"></a>파트너가 저장한 데이터에 대한 조직 제어

조직의 관리자가 파트너 시스템에서 정보를 제어하는 방법에 대해 설명하는 방법 삭제, 보존, 감사, 보관, 최종 사용자 정책 등

>데이터는 Table 2013에 Storage. 저장소 계정의 키는 MSI(관리되는 시스템 ID)를 통해 앱 서비스(봇 앱)에서 액세스하는 KeyVault에 저장됩니다. KeyVault 액세스 정책 목록에서 이 앱 서비스가 허용되는 유일한 ID입니다. PROD 환경에서 이 앱의 모든 Azure 리소스가 생성 및 유선으로 ARM. 수동 작업이 없습니다.

#### <a name="human-review-of-organizational-information"></a>조직 정보의 인적 검토

사람이 이 앱에서 수집하거나 저장하는 OII(조직 식별 정보) 데이터를 검토하거나 분석하는 데 관여하나요?

>아니요

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="mcas"

Microsoft Cloud App Security [카탈로그의](https://www.microsoft.com/enterprise-mobility-security/cloud-app-security) 정보가 아래에 표시됩니다.

<iframe height='1020' title='Microsoft Cloud App Security 정보' src='https://appmcasinfoprod.azurewebsites.net/#/dashboard/35696' frameborder='no' style='width: 100%;'></iframe>

<a href="https://appmcasinfoprod.azurewebsites.net/#/dashboard/35696" target="_blank">새 탭에서 보기</a>

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

