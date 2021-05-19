---
title: 토니 샤에 의해 럭키 드에 대한 응용 프로그램 정보
ms.author: elmalova
author: elenamalova
ms.date: 07/21/2020
ms.topic: article
ms.service: attestation
certification_type: attested
description: LuckyDraw에 대한 사용 가능한 모든 보안 및 규정 준수 정보 정보, 데이터 처리 정책, Microsoft Cloud App Security 앱 카탈로그 정보 및 CSA STAR 레지스트리의 보안/규정 준수 정보.
zone_pivot_groups: app-info-data-mcas
ms.openlocfilehash: 5ba1afff33ce27c6f520b34f73423c734c8859ec
ms.sourcegitcommit: a44420a99a1a3a9d0e49f4be66f266e2d4ca7bbb
ms.translationtype: MT
ms.contentlocale: ko-KR
ms.lasthandoff: 05/19/2021
ms.locfileid: "52551268"
---
# <a name="luckydraw"></a>LuckyDraw

<p></p>
<img alt="Publisher Attestation: The information on this page is based on a self-assessment report provided by the app developer on the security, compliance, and data handling practices followed by this app. Microsoft makes no guarantees regarding the accuracy of the information." src="../media/attested.png" width="650" />
<p>최종 업데이트: 2020년 7월 21일</p>

* <a href="https://teams.microsoft.com/l/app/75c676b5-be32-430e-acee-71bcb929b297" target="_blank">Teams 스토어에서 보기</a>
* <a href="https://appsource.microsoft.com/product/office/WA200000091" target="_blank">앱소스에서 보기</a>

::: zone pivot="general"

### <a name="general-information"></a>일반 정보

토니 샤가 마이크로소프트에 제공한 정보:

| **정보** | **응답** |
|:----------------|:-------------|
| 앱 이름 | LuckyDraw |
| ID | WA200000091 |
| 지원되는 Office 365 클라이언트 | Microsoft Teams |
| 파트너 회사 이름 | Tony Xia |
| 파트너 웹사이트의 URL | [https://luckydraw.teetee365.com](https://luckydraw.teetee365.com) |
| Teams 응용 프로그램 정보 페이지의 URL | [https://luckydraw4web4prd.z7.web.core.windows.net/](https://luckydraw4web4prd.z7.web.core.windows.net/) |
| 개인정보 처리방침의 URL | [https://luckydraw.teetee365.com/privacy](https://luckydraw.teetee365.com/privacy) |
| 이용 약관의 URL | [https://luckydraw.teetee365.com/terms](https://luckydraw.teetee365.com/terms) |

 [!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="data"

### <a name="how-the-app-handles-data"></a>앱이 데이터를 처리하는 방법

이 정보는 이 앱이 조직 데이터를 수집하고 저장하는 방법과 앱이 수집하는 데이터를 통해 조직이 가질 수 있는 제어에 대해 Tony Xia에 의해 제공되었습니다.

#### <a name="data-access-using-microsoft-graph"></a>Microsoft Graph 을 사용하여 데이터 액세스

이 [앱에서 필요한 Microsoft Graph 권한을 나열합니다.](https://docs.microsoft.com/graph/permissions-reference)

>이 응용 프로그램은 Microsoft Graph 사용하지 않습니다.


#### <a name="non-microsoft-services-used"></a>사용되지 Microsoft 서비스

앱이 Microsoft 가 아닌 서비스와 조직 데이터를 전송하거나 공유하는 경우 앱에서 사용하는 비Microsoft 서비스, 전송되는 데이터를 나열하고 앱이 이 정보를 전송해야 하는 이유에 대한 명분을 포함합니다.

>비Microsoft 서비스 사용되지 않습니다.

#### <a name="data-access-via-bots"></a>봇을 통한 데이터 액세스

이 앱에 봇 또는 메시징 확장 프로그램이 포함된 경우 최종 사용자 식별 정보(EUII): 팀의 모든 팀 구성원의 명단(이름, 성, 표시 이름, 이메일 주소)에 액세스하거나 추가된 채팅을 할 수 있습니다. 이 응용 프로그램은이 기능을 사용합니까?

>| **EUII에 액세스할 수 있는 정당성?**  | **EUII는 데이터베이스에 저장되어 있습니까?** | **EUII를 저장하는 정당화?** |
>|:--------------------------------|:---------------------|:--------------------------|
>| LuckyDraw는 명단에 액세스하지 않습니다. | LuckyDraw는 명단에 액세스하지 않습니다. |  |


#### <a name="telemetry-data"></a>원격 분석 데이터

조직 식별 정보(OII) 또는 최종 사용자 식별 정보(EUII)가 이 응용 프로그램의 원격 분석 또는 로그에 표시됩니까? 그렇다면 저장되는 데이터와 보존 및 제거 정책은 무엇입니까?

>EUII는 일부 상황에서 기록됩니다. 예를 들어 사용자는 행운의 그리기 활동을 시작합니다. 앱은 데이터 보존이 기본 90일인 Azure 응용 프로그램 인사이트를 사용하고 있습니다.

#### <a name="organizational-controls-for-data-stored-by-partner"></a>파트너가 저장한 데이터에 대한 조직 제어

조직의 관리자가 파트너 시스템에서 자신의 정보를 제어하는 방법을 설명해 보세요. 예를 들어 삭제, 보존, 감사, 보관, 최종 사용자 정책 등

>데이터는 테이블 Storage 저장됩니다. 저장소 계정의 키는 MSI(관리 시스템 ID)를 통해 앱 서비스(봇 앱)에서 액세스하는 KeyVault에 저장됩니다. 이 앱 서비스는 KeyVault 액세스 정책 목록에서 허용되는 유일한 ID입니다. PROD 환경에서 이 앱의 모든 Azure 리소스가 생성되어 ARM을 통해 연결되었습니다. 수동 작업이 없습니다.

#### <a name="human-review-of-organizational-information"></a>조직 정보의 인간 검토

이 앱에서 수집하거나 저장되는 조직 식별 정보(OII) 데이터를 검토하거나 분석하는 데 관여하는 사람이 있습니까?

>아니요

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="mcas"

[Microsoft Cloud App Security](https://www.microsoft.com/enterprise-mobility-security/cloud-app-security) 카탈로그의 정보는 아래에 나타납니다.

<iframe height='1020' title='Microsoft Cloud App Security 정보' src='https://appmcasinfoprod.azurewebsites.net/#/dashboard/35696' frameborder='no' style='width: 100%;'></iframe>

<a href="https://appmcasinfoprod.azurewebsites.net/#/dashboard/35696" target="_blank">새 탭에서 보기</a>

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

