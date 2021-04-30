---
title: Medxnote의 Medxnote MT에 대한 응용 프로그램 정보
ms.author: elmalova
author: elenamalova
ms.date: 09/28/2020
ms.topic: article
ms.service: attestation
description: Medxnote MT, 데이터 처리 정책, CSA STAR 레지스트리의 Microsoft Cloud App Security 앱 카탈로그 정보 및 보안/규정 준수 정보에 대해 사용할 수 있는 모든 보안 및 규정 준수 정보
zone_pivot_groups: app-info-data-mcas
ms.openlocfilehash: c76c9e0fe6166bf3acc8c2d48abb8172583d8dc9
ms.sourcegitcommit: e97156a6eaf1d5ec5c26fd14add210a92bacd944
ms.translationtype: MT
ms.contentlocale: ko-KR
ms.lasthandoff: 04/30/2021
ms.locfileid: "52094497"
---
# <a name="medxnote-mt"></a>Medxnote MT

<p></p>
<img alt="Publisher Attestation: The information on this page is based on a self-assessment report provided by the app developer on the security, compliance, and data handling practices followed by this app. Microsoft makes no guarantees regarding the accuracy of the information." src="../media/attested.png" width="650" />
<p>개발자가 마지막으로 업데이트한 날짜: 2020년 9월 28일</p>

* <a href="https://teams.microsoft.com/l/app/02ffb7cc-5fcd-4b31-bcbd-b24bbca74cc7" target="_blank">저장소의 Teams 보기</a>
* <a href="https://appsource.microsoft.com/product/office/WA200001823" target="_blank">AppSource의 보기</a>

::: zone pivot="general"

### <a name="general-information"></a>일반 정보

Medxnote에서 Microsoft에 제공하는 정보:

| **정보** | **응답** |
|:----------------|:-------------|
| 앱 이름 | Medxnote MT |
| ID | WA200001823 |
| 기능 | 봇 |
| Office 365 클라이언트 지원 | Microsoft Teams |
| 파트너 회사 이름 | Medxnote |
| 파트너 웹 사이트의 URL | [https://medxnote.com](https://medxnote.com) |
| 개인 정보 취급 방침의 URL | [https://medxnote.com/privacy-policy/](https://medxnote.com/privacy-policy/) |
| 사용 약관 URL | [https://medxnote.com/terms-conditions/](https://medxnote.com/terms-conditions/) |

 [!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="data"

### <a name="how-the-app-handles-data"></a>앱이 데이터를 처리하는 방법

이 정보는 Medxnote에서 이 앱이 조직 데이터를 수집하고 저장하는 방법 및 앱이 수집하는 데이터에 대해 조직에서 사용할 컨트롤에 대해 제공됩니다.

#### <a name="data-access-using-microsoft-graph"></a>Microsoft 365를 사용한 데이터 Graph

이 앱에 [Graph Microsoft 사용자 권한을](https://docs.microsoft.com/graph/permissions-reference) 나열합니다.

>| **사용 권한**  | **사용 권한 유형(위임/응용 프로그램)** | **데이터가 수집하나요? 수집의 사당성** | **데이터가 저장되어 있나요? 저장 사정이 있나요?** | **Azure AD 앱 ID** |
>|:----------------|:--------------------|:---------------------------------------------------|:--------------------------|:--------------------------|
>| User.Read.All | application | 당사는 사용자의 권한을 검사하는 데 병원 쪽에서 사용되는 이름 및 전자 메일을 캐싱하고 있습니다. | 메시지를 보낼 때 이름 및 전자 메일 주소가 추가된 경우 서버 쪽에서 데이터를 캐싱하고 있으며, 병원 쪽에서 선택적 권한 검사에도 사용됩니다. | fc70bbbe-91c4-4d8f-a9c9-a022068d5752 |
>| openid | 위임 | 작업 모듈에서 사용자 로그인에 사용되는 세션 ID, 사용자 ID, 전달자 토큰 및 전자 메일을 캐싱하고 있습니다. | 작업 모듈에서 사용자를 로그인하는 데 사용, 세션 ID, userid, 전자 메일, 전달자 토큰을 저장하고 있습니다. | fc70bbbe-91c4-4d8f-a9c9-a022068d5752 |


#### <a name="non-microsoft-services-used"></a>비영구 Microsoft 서비스

앱이 Microsoft가 아닌 서비스로 조직 데이터를 전송하거나 공유하는 경우 앱에서 사용하는 비 Microsoft 서비스, 전송되는 데이터를 나열하고 앱이 이 정보를 전송해야 하는 이유에 대한 사유를 포함합니다.

>비영구 Microsoft 서비스 사용되지 않습니다.

#### <a name="data-access-via-bots"></a>봇을 통한 데이터 액세스

이 앱에 봇 또는 메시징 확장이 포함되어 있는 경우 팀 구성원의 명단(이름, 성, 표시 이름, 전자 메일 주소)이나 팀 구성원이 추가된 채팅의 최종 사용자 식별 정보(EUII)에 액세스할 수 있습니다. 이 앱이 이 기능을 사용하나요?

>EUII에 액세스하지 않습니다.



#### <a name="telemetry-data"></a>원격 분석 데이터

이 응용 프로그램의 원격 분석 또는 로그에 OII(조직 식별 정보) 또는 EUII(최종 사용자 식별 정보)가 나타나나요? 그렇다면 저장되는 데이터와 보존 및 제거 정책에 대해 설명하세요.

>전자 메일 주소, 이름, 테넌트 ID, 채널 ID가 로그에 표시될 수 있습니다. 모든 로그 데이터는 1개월 후 최신 버전에서 자동으로 삭제됩니다.
이러한 관리에 대한 액세스는 2FA가 적용된 액세스 권한을 가진 일부 조직 관리자로 제한됩니다.

#### <a name="organizational-controls-for-data-stored-by-partner"></a>파트너가 저장한 데이터에 대한 조직 제어

조직의 관리자가 파트너 시스템에서 정보를 제어하는 방법에 대해 설명하는 방법 삭제, 보존, 감사, 보관, 최종 사용자 정책 등

>액세스는 2FA가 적용된 일부 조직 관리자로 제한됩니다.
중요 시스템은 특정 IP 주소에서만 액세스할 수 있습니다.

#### <a name="human-review-of-organizational-information"></a>조직 정보의 인적 검토

사람이 이 앱에서 수집하거나 저장하는 OII(조직 식별 정보) 데이터를 검토하거나 분석하는 데 관여하나요?

>예

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="mcas"

Microsoft Cloud App Security [카탈로그의](https://www.microsoft.com/enterprise-mobility-security/cloud-app-security) 정보가 아래에 표시됩니다.

<iframe height='1020' title='Microsoft Cloud App Security 정보' src='https://appmcasinfoprod.azurewebsites.net/#/dashboard/36056' frameborder='no' style='width: 100%;'></iframe>

<a href="https://appmcasinfoprod.azurewebsites.net/#/dashboard/36056" target="_blank">새 탭에서 보기</a>

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

