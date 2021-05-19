---
title: 시트고 유럽 SL에 의해 시트고에 대한 응용 프로그램 정보
ms.author: elmalova
author: elenamalova
ms.date: 11/03/2020
ms.topic: article
ms.service: attestation
certification_type: attested
description: Sheetgo에 대한 사용 가능한 모든 보안 및 규정 준수 정보 정보, 데이터 처리 정책, Microsoft Cloud App Security 앱 카탈로그 정보 및 CSA STAR 레지스트리의 보안/규정 준수 정보.
zone_pivot_groups: app-info-data-mcas
ms.openlocfilehash: cba1d32ef248cc8228a0e38e1dc953dd07f4e5ad
ms.sourcegitcommit: a44420a99a1a3a9d0e49f4be66f266e2d4ca7bbb
ms.translationtype: MT
ms.contentlocale: ko-KR
ms.lasthandoff: 05/19/2021
ms.locfileid: "52548728"
---
# <a name="sheetgo"></a>Sheetgo

<p></p>
<img alt="Publisher Attestation: The information on this page is based on a self-assessment report provided by the app developer on the security, compliance, and data handling practices followed by this app. Microsoft makes no guarantees regarding the accuracy of the information." src="../media/attested.png" width="650" />
<p>최종 업데이트: 2020년 11월 3일</p>

* <a href="https://appsource.microsoft.com/product/office/WA200002128" target="_blank">앱소스에서 보기</a>

::: zone pivot="general"

### <a name="general-information"></a>일반 정보

마이크로 소프트에 시트고 유럽 SL에서 제공하는 정보 :

| **정보** | **응답** |
|:----------------|:-------------|
| 앱 이름 | Sheetgo |
| ID | WA200002128 |
| 지원되는 Office 365 클라이언트 | Excel 2016 또는 그 이후에 는 맥, Excel 2016 또는 Windows 이후, 웹용 Excel |
| 파트너 회사 이름 | SHEETGO EUROPE SL |
| 파트너 웹사이트의 URL | [https://appsource.microsoft.com/marketplace/apps?product=of...](https://appsource.microsoft.com/marketplace/apps?product=office) |
| 개인정보 처리방침의 URL | [https://www.sheetgo.com/legal/privacy](https://www.sheetgo.com/legal/privacy) |
| 이용 약관의 URL | [https://www.sheetgo.com/legal/terms](https://www.sheetgo.com/legal/terms) |

 [!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="data"

### <a name="how-the-app-handles-data"></a>앱이 데이터를 처리하는 방법

이 정보는 이 앱이 조직 데이터를 수집하고 저장하는 방법과 앱이 수집하는 데이터에 대한 조직이 가질 수 있는 제어에 대해 SHEETGO EUROPE SL에서 제공되었습니다.

#### <a name="data-access-using-microsoft-graph"></a>Microsoft Graph 을 사용하여 데이터 액세스

이 [앱에서 필요한 Microsoft Graph 권한을 나열합니다.](https://docs.microsoft.com/graph/permissions-reference)

>이 응용 프로그램은 Microsoft Graph 사용하지 않습니다.


#### <a name="non-microsoft-services-used"></a>사용되지 Microsoft 서비스

앱이 Microsoft 가 아닌 서비스와 조직 데이터를 전송하거나 공유하는 경우 앱에서 사용하는 비Microsoft 서비스, 전송되는 데이터를 나열하고 앱이 이 정보를 전송해야 하는 이유에 대한 명분을 포함합니다.

>| **모든 Microsoft 서비스 OII가** |  **어떤 OII가 전송됩니까?** | **OII 전송에 대한 정당화?** |
>|:-------------------|:--------------------------|:--------------------------|
>| MongoDB: 구글 빅쿼리: 기록 시스템 로그 사용, 구글 파이어 스토어: 마이크로 서비스의 상태를 유지 하 고 오케스트레이션 시스템, 스트라이프: 지불 시스템 |  | 이러한 응용 프로그램은 추가 Microsoft API를 사용하지 않습니다. |



#### <a name="telemetry-data"></a>원격 분석 데이터

조직 식별 정보(OII) 또는 최종 사용자 식별 정보(EUII)가 이 응용 프로그램의 원격 분석 또는 로그에 표시됩니까? 그렇다면 저장되는 데이터와 보존 및 제거 정책은 무엇입니까?

>원격 분석/로그는 최종 사용자 식별 정보로만 사용자의 전자 메일 주소를 포함합니다. 사용자가 요청하면 응용 프로그램 지원 팀은 원격 분석/로그 간에 전자 메일 주소를 흐리게 하고 사용자 데이터를 더 이상 식별할 수 없게 만드는 내부 자동 루틴을 실행합니다.

#### <a name="organizational-controls-for-data-stored-by-partner"></a>파트너가 저장한 데이터에 대한 조직 제어

조직의 관리자가 파트너 시스템에서 자신의 정보를 제어하는 방법을 설명해 보세요. 예를 들어 삭제, 보존, 감사, 보관, 최종 사용자 정책 등

>MongoDB: 구글 빅쿼리 기능을 위해 시스템 및 사용자 데이터를 기록: 기록 시스템 로그 사용 구글 파이어 스토어: 유지 하 고 우리의 마이크로 서비스의 상태를 오케스트레이션 시스템. 이 서비스 전송의 유일한 중요한 데이터는 AES256 Stripe: 결제 시스템을 사용하여 암호화된 사용자 자격 증명입니다.
 
전송 중의 모든 데이터는 안전한 연결을 위해 HTTPS를 사용하며 모든 중요한 데이터는 AES256을 사용하여 암호화됩니다.

#### <a name="human-review-of-organizational-information"></a>조직 정보의 인간 검토

이 앱에서 수집하거나 저장되는 조직 식별 정보(OII) 데이터를 검토하거나 분석하는 데 관여하는 사람이 있습니까?

>예

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="mcas"

[Microsoft Cloud App Security](https://www.microsoft.com/enterprise-mobility-security/cloud-app-security) 카탈로그의 정보는 아래에 나타납니다.

<iframe height='1020' title='Microsoft Cloud App Security 정보' src='https://appmcasinfoprod.azurewebsites.net/#/dashboard/36141' frameborder='no' style='width: 100%;'></iframe>

<a href="https://appmcasinfoprod.azurewebsites.net/#/dashboard/36141" target="_blank">새 탭에서 보기</a>

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

