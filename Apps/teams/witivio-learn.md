---
title: Witivio에서 학습할 수 있는 응용 프로그램 정보
ms.author: elmalova
author: elenamalova
ms.date: 03/31/2020
ms.topic: article
ms.service: attestation
description: Learn, 데이터 처리 정책, CSA STAR 레지스트리의 Microsoft Cloud App Security 앱 카탈로그 정보 및 보안/규정 준수 정보에 대해 사용 가능한 모든 보안 및 규정 준수 정보입니다.
zone_pivot_groups: app-info-data-mcas
ms.openlocfilehash: e7ebfb89a25634fb1691df9eaa9182334278726a
ms.sourcegitcommit: e97156a6eaf1d5ec5c26fd14add210a92bacd944
ms.translationtype: MT
ms.contentlocale: ko-KR
ms.lasthandoff: 04/30/2021
ms.locfileid: "52094793"
---
# <a name="learn"></a>학습

<p></p>
<img alt="Publisher Attestation: The information on this page is based on a self-assessment report provided by the app developer on the security, compliance, and data handling practices followed by this app. Microsoft makes no guarantees regarding the accuracy of the information." src="../media/attested.png" width="650" />
<p>개발자가 마지막으로 업데이트한 날짜: 2020년 3월 31일</p>

* <a href="https://teams.microsoft.com/l/app/2d96b540-aa26-431b-bc31-222321c762e3" target="_blank">저장소의 Teams 보기</a>
* <a href="https://appsource.microsoft.com/product/office/WA200001308" target="_blank">AppSource의 보기</a>

::: zone pivot="general"

### <a name="general-information"></a>일반 정보

Witivio에서 Microsoft에 제공하는 정보:

| **정보** | **응답** |
|:----------------|:-------------|
| 앱 이름 | 학습 |
| ID | WA200001308 |
| 기능 | 봇, 탭 |
| Office 365 클라이언트 지원 | Microsoft Teams |
| 파트너 회사 이름 | Witivio |
| 파트너 웹 사이트의 URL | [https://www.witivio.com/learn](https://www.witivio.com/learn) |
| 개인 정보 취급 방침의 URL | [https://www.witivio.com/en/privacy](https://www.witivio.com/en/privacy) |
| 사용 약관 URL | [https://witivio.com/en/terms-of-use](https://witivio.com/en/terms-of-use) |

 [!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="data"

### <a name="how-the-app-handles-data"></a>앱이 데이터를 처리하는 방법

이 정보는 Witivio에서 이 앱이 조직 데이터를 수집하고 저장하는 방법 및 앱이 수집하는 데이터를 통해 조직에서 제공하는 컨트롤에 대해 제공됩니다.

#### <a name="data-access-using-microsoft-graph"></a>Microsoft 365를 사용한 데이터 Graph

이 앱에 [Graph Microsoft 사용자 권한을](https://docs.microsoft.com/graph/permissions-reference) 나열합니다.

>| **사용 권한**  | **사용 권한 유형(위임/응용 프로그램)** | **데이터가 수집하나요? 수집의 사당성** | **데이터가 저장되어 있나요? 저장 사정이 있나요?** | **Azure AD 앱 ID** |
>|:----------------|:--------------------|:---------------------------------------------------|:--------------------------|:--------------------------|
>| User.Read | 위임 | 해당 없음 | 권한 부여에 대한 UPN 및 AAD ID를 수집합니다. | 8c5c0060-2892-4355-b0db-661f206028a9 |
>| User.ReadBasic.All | 위임 | 해당 없음 | 권한 부여에 대한 UPN 및 AAD ID를 수집합니다. | 8c5c0060-2892-4355-b0db-661f206028a9 |
>| openid | 위임 | 해당 없음 | 권한 부여에 대한 UPN 및 AAD ID를 수집합니다. | 8c5c0060-2892-4355-b0db-661f206028a9 |
>| profile | 위임 | 해당 없음 | 권한 부여에 대한 UPN 및 AAD ID를 수집합니다. | 8c5c0060-2892-4355-b0db-661f206028a9 |


#### <a name="non-microsoft-services-used"></a>비영구 Microsoft 서비스

앱이 Microsoft가 아닌 서비스로 조직 데이터를 전송하거나 공유하는 경우 앱에서 사용하는 비 Microsoft 서비스, 전송되는 데이터를 나열하고 앱이 이 정보를 전송해야 하는 이유에 대한 사유를 포함합니다.

>비영구 Microsoft 서비스 사용되지 않습니다.

#### <a name="data-access-via-bots"></a>봇을 통한 데이터 액세스

이 앱에 봇 또는 메시징 확장이 포함되어 있는 경우 팀 구성원의 명단(이름, 성, 표시 이름, 전자 메일 주소)이나 팀 구성원이 추가된 채팅의 최종 사용자 식별 정보(EUII)에 액세스할 수 있습니다. 이 앱이 이 기능을 사용하나요?

>| **EUII 액세스의 사유는 무엇입니까?**  | **EUII가 데이터베이스에 저장되어 있나요?** | **EUII 저장의 사유는 무엇입니까?** |
>|:--------------------------------|:---------------------|:--------------------------|
>| We use the roster for: 1) authorization (grant access to the bot), 2) detect the firstname to provide a friendly UX, 3) To manage the chatlogs for the business admin of the bot. | N/A. 또는 봇은 개인 전용입니다. |  |



#### <a name="telemetry-data"></a>원격 분석 데이터

이 응용 프로그램의 원격 분석 또는 로그에 OII(조직 식별 정보) 또는 EUII(최종 사용자 식별 정보)가 나타나나요? 그렇다면 저장되는 데이터와 보존 및 제거 정책에 대해 설명하세요.

>봇의 원격 분석에는 UPN 및 AAD ID fr 진단이 포함되어 있습니다.
PROD/Run 관리자만 프로덕션 원격 분석에 액세스할 수 있습니다. 로그는 90일 동안 저장되고 요청 시 전용 포털 사이트 또는 전자 메일로 support.witivio.com 삭제할 수 dpo@witivio.com

#### <a name="organizational-controls-for-data-stored-by-partner"></a>파트너가 저장한 데이터에 대한 조직 제어

조직의 관리자가 파트너 시스템에서 정보를 제어하는 방법에 대해 설명하는 방법 삭제, 보존, 감사, 보관, 최종 사용자 정책 등

>Witivio는 북유럽 지역에 배포된 Azure 구성 요소만 사용 합니다. 데이터 분석 및 Cosmos 데 응용 프로그램 정보를 활용하고 DB를 지원합니다.
Witivio는 관리자를 포함하여 모든 사용자에 대해 MFA를 사용 합니다. 관리자는 사용자 계정(Workstation용)과 Azure 리소스에 액세스하기 위한 권한이 부여된 계정이 있습니다.

#### <a name="human-review-of-organizational-information"></a>조직 정보의 인적 검토

사람이 이 앱에서 수집하거나 저장하는 OII(조직 식별 정보) 데이터를 검토하거나 분석하는 데 관여하나요?

>예

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="mcas"

Microsoft Cloud App Security [카탈로그의](https://www.microsoft.com/enterprise-mobility-security/cloud-app-security) 정보가 아래에 표시됩니다.

<iframe height='1020' title='Microsoft Cloud App Security 정보' src='https://appmcasinfoprod.azurewebsites.net/#/dashboard/35854' frameborder='no' style='width: 100%;'></iframe>

<a href="https://appmcasinfoprod.azurewebsites.net/#/dashboard/35854" target="_blank">새 탭에서 보기</a>

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

