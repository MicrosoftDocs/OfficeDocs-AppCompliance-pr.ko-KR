---
title: 모듈 Q에 의한 Q신청 정보
ms.author: elmalova
author: elenamalova
ms.date: 03/17/2020
ms.topic: article
ms.service: attestation
certification_type: attested
description: Q에 대한 사용 가능한 모든 보안 및 규정 준수 정보 정보, 데이터 처리 정책, Microsoft Cloud App Security 앱 카탈로그 정보 및 CSA STAR 레지스트리의 보안/규정 준수 정보.
zone_pivot_groups: app-info-data-mcas
ms.openlocfilehash: 3424ac372f46be0fc9834611fb1a0d57c69831a4
ms.sourcegitcommit: a44420a99a1a3a9d0e49f4be66f266e2d4ca7bbb
ms.translationtype: MT
ms.contentlocale: ko-KR
ms.lasthandoff: 05/19/2021
ms.locfileid: "52551908"
---
# <a name="q"></a>Q

<p></p>
<img alt="Publisher Attestation: The information on this page is based on a self-assessment report provided by the app developer on the security, compliance, and data handling practices followed by this app. Microsoft makes no guarantees regarding the accuracy of the information." src="../media/attested.png" width="650" />
<p>최종 업데이트: 2020년 3월 17일</p>

* <a href="https://teams.microsoft.com/l/app/72bb25c7-3644-4318-8249-a08e5493a520" target="_blank">Teams 스토어에서 보기</a>
* <a href="https://appsource.microsoft.com/product/office/WA104381433" target="_blank">앱소스에서 보기</a>

::: zone pivot="general"

### <a name="general-information"></a>일반 정보

모듈Q에서 Microsoft에 제공한 정보:

| **정보** | **응답** |
|:----------------|:-------------|
| 앱 이름 | Q |
| ID | WA1043814333 |
| 지원되는 Office 365 클라이언트 | Microsoft Teams |
| 파트너 회사 이름 | ModuleQ |
| 파트너 웹사이트의 URL | [https://moduleq.com](https://moduleq.com) |
| 개인정보 처리방침의 URL | [https://moduleq.com/privacy-policy/](https://moduleq.com/privacy-policy/) |
| 이용 약관의 URL | [https://moduleq.com/terms-of-service/](https://moduleq.com/terms-of-service/) |

 [!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="data"

### <a name="how-the-app-handles-data"></a>앱이 데이터를 처리하는 방법

이 정보는 이 앱이 조직 데이터를 수집하고 저장하는 방법과 앱이 수집하는 데이터에 대한 조직에 대한 제어에 대해 ModuleQ에서 제공되었습니다.

#### <a name="data-access-using-microsoft-graph"></a>Microsoft Graph 을 사용하여 데이터 액세스

이 [앱에서 필요한 Microsoft Graph 권한을 나열합니다.](https://docs.microsoft.com/graph/permissions-reference)

>| **사용 권한**  | **권한 유형(위임/응용 프로그램)** | **데이터가 수집되고 있습니까? 그것을 수집하기위한 정당화?** | **데이터가 저장되어 있습니까? 그것을 저장하는 정당화?** | **Azure AD 앱 ID** |
>|:----------------|:--------------------|:---------------------------------------------------|:--------------------------|:--------------------------|
>| Calendars.Read | 신청 | 메시지 본문 및 첨부 파일을 제외한 모임 데이터를 저장합니다. | 응용 프로그램이 사용자의 비즈니스 우선 순위를 지능적으로 이해하기 위해 사용자의 캘린더 이벤트를 읽을 수 있습니다. | 418a1ee4-ca76-4b38-b4b3-8cca25417a6c |
>| Group.Read.All | 위임 | 없음 | 앱이 콘텐츠를 공유하기 위해 팀에서 상호 작용할 수 있도록 합니다. | 418a1ee4-ca76-4b38-b4b3-8cca25417a6c |
>| Mail.Read | 신청 | 메시지 본문 및 첨부 파일을 제외한 전자 메일 데이터를 저장합니다. | 응용 프로그램이 사용자의 비즈니스 우선 순위를 지능적으로 이해하기 위해 사용자의 메일을 읽을 수 있습니다. | 418a1ee4-ca76-4b38-b4b3-8cca25417a6c |
>| User.Read | 위임 | 사용자 이메일 및 인증 토큰 | 사용자가 로그인하여 Office 365 계정을 ModuleQ 계정과 연결할 수 있습니다. | 418a1ee4-ca76-4b38-b4b3-8cca25417a6c |
>| User.Read.All | 위임 | 없음 | 앱이 사용자가 속한 Teams 목록을 얻을 수 있도록 허용합니다. 공유에만 사용  | 418a1ee4-ca76-4b38-b4b3-8cca25417a6c |


#### <a name="non-microsoft-services-used"></a>사용되지 Microsoft 서비스

앱이 Microsoft 가 아닌 서비스와 조직 데이터를 전송하거나 공유하는 경우 앱에서 사용하는 비Microsoft 서비스, 전송되는 데이터를 나열하고 앱이 이 정보를 전송해야 하는 이유에 대한 명분을 포함합니다.

>비Microsoft 서비스 사용되지 않습니다.

#### <a name="data-access-via-bots"></a>봇을 통한 데이터 액세스

이 앱에 봇 또는 메시징 확장 프로그램이 포함된 경우 최종 사용자 식별 정보(EUII): 팀의 모든 팀 구성원의 명단(이름, 성, 표시 이름, 이메일 주소)에 액세스하거나 추가된 채팅을 할 수 있습니다. 이 응용 프로그램은이 기능을 사용합니까?

>EUII에 액세스할 수 없습니다.


#### <a name="telemetry-data"></a>원격 분석 데이터

조직 식별 정보(OII) 또는 최종 사용자 식별 정보(EUII)가 이 응용 프로그램의 원격 분석 또는 로그에 표시됩니까? 그렇다면 저장되는 데이터와 보존 및 제거 정책은 무엇입니까?

>우리는 내부 사용자 GUID 및 조직 이름 및 도메인을 기록합니다. 현재 아카이브 또는 삭제 컨트롤이 없습니다.

#### <a name="organizational-controls-for-data-stored-by-partner"></a>파트너가 저장한 데이터에 대한 조직 제어

조직의 관리자가 파트너 시스템에서 자신의 정보를 제어하는 방법을 설명해 보세요. 예를 들어 삭제, 보존, 감사, 보관, 최종 사용자 정책 등

>데이터는 기능에 따라 여러 마이크로 서비스에 걸쳐 Microsoft Azure 클라우드에 저장됩니다. 모든 사용자 식별 가능한 데이터는 저장을 위해 전송하기 전에 AES-256 암호화와 함께 클라이언트 측으로 암호화됩니다. 데이터는 고위 경영진의 승인을 받아 디버깅 목적으로 엔지니어가 볼 수 있습니다. 데이터에 대한 액세스는 내부 VPN을 통해 제어됩니다.

#### <a name="human-review-of-organizational-information"></a>조직 정보의 인간 검토

이 앱에서 수집하거나 저장되는 조직 식별 정보(OII) 데이터를 검토하거나 분석하는 데 관여하는 사람이 있습니까?

>예

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="mcas"

[Microsoft Cloud App Security](https://www.microsoft.com/enterprise-mobility-security/cloud-app-security) 카탈로그의 정보는 아래에 나타납니다.

<iframe height='1020' title='Microsoft Cloud App Security 정보' src='https://appmcasinfoprod.azurewebsites.net/#/dashboard/35844' frameborder='no' style='width: 100%;'></iframe>

<a href="https://appmcasinfoprod.azurewebsites.net/#/dashboard/35844" target="_blank">새 탭에서 보기</a>

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

