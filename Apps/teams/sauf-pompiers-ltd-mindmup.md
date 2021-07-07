---
title: Sauf Pompiers Ltd의 MindMup에 대한 응용 프로그램 정보
ms.author: elmalova
author: elenamalova
ms.date: 08/06/2020
ms.topic: article
ms.service: attestation
certification_type: attested
description: MindMup, 데이터 처리 정책, CSA STAR 레지스트리의 Microsoft Cloud App Security 앱 카탈로그 정보 및 보안/규정 준수 정보에 사용할 수 있는 모든 보안 및 규정 준수 정보
zone_pivot_groups: app-info-data-mcas
ms.openlocfilehash: 0bf09c9e6a144fb4415879577af4debcc5fc6713
ms.sourcegitcommit: 65d4afba6f46d45315b2a90d2b21ce1737707e7b
ms.translationtype: MT
ms.contentlocale: ko-KR
ms.lasthandoff: 07/02/2021
ms.locfileid: "53283062"
---
# <a name="mindmup"></a>MindMup

<p></p>
<img alt="Publisher Attestation: The information on this page is based on a self-assessment report provided by the app developer on the security, compliance, and data handling practices followed by this app. Microsoft makes no guarantees regarding the accuracy of the information." src="../media/attested.png" width="650" />
<p>개발자가 마지막으로 업데이트한 날짜: 2020년 8월 6일</p>

* <a href="https://teams.microsoft.com/l/app/c12a3d54-d294-4a51-8cd3-4a48b6c7e6f2" target="_blank">저장소의 Teams 보기</a>
* <a href="https://appsource.microsoft.com/product/office/WA200001759" target="_blank">AppSource의 보기</a>

::: zone pivot="general"

### <a name="general-information"></a>일반 정보

Sauf Pompiers Ltd에서 Microsoft에 제공한 정보:

| **정보** | **응답** |
|:----------------|:-------------|
| 앱 이름 | MindMup |
| ID | WA200001759 |
| Office 365 클라이언트 지원 | Microsoft Teams |
| 파트너 회사 이름 | Sauf Pompiers Ltd |
| 파트너 웹 사이트의 URL | [https://www.mindmup.com](https://www.mindmup.com) |
| 개인 정보 취급 방침의 URL | [https://www.mindmup.com/resources/privacy_policy.html](https://www.mindmup.com/resources/privacy_policy.html) |
| 사용 약관 URL | [https://www.mindmup.com/resources/terms_mindmup.html](https://www.mindmup.com/resources/terms_mindmup.html) |

 [!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="data"

### <a name="how-the-app-handles-data"></a>앱이 데이터를 처리하는 방법

이 정보는 Sauf Pompiers Ltd에서 이 앱이 조직 데이터를 수집하고 저장하는 방법 및 앱이 수집하는 데이터를 통해 조직이 제어할 수 있는 컨트롤에 대해 제공됩니다.

#### <a name="data-access-using-microsoft-graph"></a>Microsoft 365를 사용한 데이터 Graph

이 앱에 [Graph Microsoft 사용자 권한을](https://docs.microsoft.com/graph/permissions-reference) 나열합니다.

>이 응용 프로그램은 Microsoft 응용 프로그램을 Graph.


#### <a name="non-microsoft-services-used"></a>비영구 Microsoft 서비스

앱이 Microsoft가 아닌 서비스로 조직 데이터를 전송하거나 공유하는 경우 앱에서 사용하는 비 Microsoft 서비스, 전송되는 데이터를 나열하고 앱이 이 정보를 전송해야 하는 이유에 대한 사유를 포함합니다.

>| **모든 비 Microsoft 서비스 OII가 다음으로 전송됩니다.** |  **전송되는 OII는 무엇입니까?** | **OII 전송의 사당성** |
>|:-------------------|:--------------------------|:--------------------------|
>| MindMup에서 문서 공유 및 사용자 문서에 대한 보안 액세스를 지원하기 위해 기본 사용자 프로필 정보를 유지 하는 데 사용되는 AWS 저장소 시스템 |  | 해당 없음 |

#### <a name="data-access-via-bots"></a>봇을 통한 데이터 액세스

이 앱에 봇 또는 메시징 확장이 포함되어 있는 경우 팀 구성원의 명단(이름, 성, 표시 이름, 전자 메일 주소)이나 팀 구성원이 추가된 채팅의 최종 사용자 식별 정보(EUII)에 액세스할 수 있습니다. 이 앱이 이 기능을 사용하나요?

>EUII에 액세스하지 않습니다.


#### <a name="telemetry-data"></a>원격 분석 데이터

이 응용 프로그램의 원격 분석 또는 로그에 OII(조직 식별 정보) 또는 EUII(최종 사용자 식별 정보)가 나타나나요? 그렇다면 저장되는 데이터와 보존 및 제거 정책에 대해 설명하세요.

>보안 액세스 로그는 사용자 ID, office 365 테넌트 ID 및 액세스 타임스탬프를 기록합니다. 사기 및 남용을 방지하기 위해 지속됩니다.

#### <a name="organizational-controls-for-data-stored-by-partner"></a>파트너가 저장한 데이터에 대한 조직 제어

조직의 관리자가 파트너 시스템에서 정보를 제어하는 방법에 대해 설명하는 방법 삭제, 보존, 감사, 보관, 최종 사용자 정책 등

>사용자 문서는 AWS(us-east-1)에 저장되며 전송 시 암호화되고 미사용 암호화됩니다. 데이터는 문서를 만든 사용자와 소유자가 문서를 명시적으로 공유한 모든 사용자가 사용할 수 있습니다.

모든 운영자/관리자 액세스는 2FA로 보호됩니다.

사용자 및 클라이언트 관리자 액세스는 Microsoft/Azure AD 통합 인증에서 제공하며, 2FA 옵션은 SSO를 통해 직접 사용할 수 있습니다.

#### <a name="human-review-of-organizational-information"></a>조직 정보의 인적 검토

사람이 이 앱에서 수집하거나 저장하는 OII(조직 식별 정보) 데이터를 검토하거나 분석하는 데 관여하나요?

>아니요

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="mcas"

Microsoft Cloud App Security [카탈로그의](https://www.microsoft.com/enterprise-mobility-security/cloud-app-security) 정보가 아래에 표시됩니다.

<iframe height='1020' title='Microsoft Cloud App Security 정보' src='https://appmcasinfoprod.azurewebsites.net/#/dashboard/35953' frameborder='no' style='width: 100%;'></iframe>

<a href="https://appmcasinfoprod.azurewebsites.net/#/dashboard/35953" target="_blank">새 탭에서 보기</a>

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

