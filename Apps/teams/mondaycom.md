---
title: 응용 프로그램 monday.com 대한 monday.com
ms.author: elmalova
author: elenamalova
ms.date: 09/28/2020
ms.topic: article
ms.service: attestation
certification_type: attested
description: CSA STAR 레지스트리의 monday.com, 데이터 처리 정책, Microsoft Cloud App Security 앱 카탈로그 정보 및 보안/규정 준수 정보에 대해 사용할 수 있는 모든 보안 및 규정 준수 정보입니다.
zone_pivot_groups: app-info-data-mcas
ms.openlocfilehash: 64fc8e948618b760a3f82ee9c1ac67a32de9afb6
ms.sourcegitcommit: a44420a99a1a3a9d0e49f4be66f266e2d4ca7bbb
ms.translationtype: MT
ms.contentlocale: ko-KR
ms.lasthandoff: 05/19/2021
ms.locfileid: "52552929"
---
# <a name="mondaycom"></a>monday.com

<p></p>
<img alt="Publisher Attestation: The information on this page is based on a self-assessment report provided by the app developer on the security, compliance, and data handling practices followed by this app. Microsoft makes no guarantees regarding the accuracy of the information." src="../media/attested.png" width="650" />
<p>개발자가 마지막으로 업데이트한 날짜: 2020년 9월 28일</p>

* <a href="https://teams.microsoft.com/l/app/eab2d3ce-6d6a-4415-abc4-5f40a8317b1f" target="_blank">저장소의 Teams 보기</a>
* <a href="https://appsource.microsoft.com/product/office/WA200001798" target="_blank">AppSource의 보기</a>

::: zone pivot="general"

### <a name="general-information"></a>일반 정보

Microsoft에 monday.com 정보:

| **정보** | **응답** |
|:----------------|:-------------|
| 앱 이름 | monday.com |
| ID | WA200001798 |
| Office 365 클라이언트 지원 | Microsoft Teams |
| 파트너 회사 이름 | monday.com |
| 파트너 웹 사이트의 URL | [https://monday.com](https://monday.com) |
| 개인 정보 취급 방침의 URL | [https://monday.com/privacy](https://monday.com/privacy) |
| 사용 약관 URL | [https://monday.com/terms/tos](https://monday.com/terms/tos) |

 [!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="data"

### <a name="how-the-app-handles-data"></a>앱이 데이터를 처리하는 방법

이 정보는 monday.com 수집 및 저장하는 방법과 앱이 수집하는 데이터를 통해 조직이 제어할 수 있는 컨트롤에 대한 정보를 제공합니다.

#### <a name="data-access-using-microsoft-graph"></a>Microsoft 365를 사용한 데이터 Graph

이 앱에 [Graph Microsoft 사용자 권한을](https://docs.microsoft.com/graph/permissions-reference) 나열합니다.

>이 응용 프로그램은 Microsoft 응용 프로그램을 Graph.


#### <a name="non-microsoft-services-used"></a>비영구 Microsoft 서비스

앱이 Microsoft가 아닌 서비스로 조직 데이터를 전송하거나 공유하는 경우 앱에서 사용하는 비 Microsoft 서비스, 전송되는 데이터를 나열하고 앱이 이 정보를 전송해야 하는 이유에 대한 사유를 포함합니다.

>| **모든 비 Microsoft 서비스 OII가 다음으로 전송됩니다.** |  **전송되는 OII는 무엇입니까?** | **OII 전송의 사당성** |
>|:-------------------|:--------------------------|:--------------------------|
>| monday.com 서비스 성능에 대해 다음과 같은 하위 프로세서를 &#160;https://monday.com/terms/subprocessors |  | monday.com API를 사용하지 않습니다. Microsoft는 서비스 성능에 대해 다음 Microsoft 프레임워크를 사용(위의 응답에 자세히 설명됨): &#8216;botbuilder&#8217; &#8216;botframework-connector&#8217; &#8216;@micorosft/teams-js&#8217; |

#### <a name="data-access-via-bots"></a>봇을 통한 데이터 액세스

이 앱에 봇 또는 메시징 확장이 포함되어 있는 경우 팀 구성원의 명단(이름, 성, 표시 이름, 전자 메일 주소)이나 팀 구성원이 추가된 채팅의 최종 사용자 식별 정보(EUII)에 액세스할 수 있습니다. 이 앱이 이 기능을 사용하나요?

>EUII에 액세스하지 않습니다.


#### <a name="telemetry-data"></a>원격 분석 데이터

이 응용 프로그램의 원격 분석 또는 로그에 OII(조직 식별 정보) 또는 EUII(최종 사용자 식별 정보)가 나타나나요? 그렇다면 저장되는 데이터와 보존 및 제거 정책에 대해 설명하세요.

>monday.com R D 담당자가 버그 및 사용자가 보고한 문제를 해결할 수 있도록 사용자가 생성한 콘텐츠를 제한된 기간 동안 포함하는 응용 프로그램 로그를 &amp; 저장합니다. IP 주소를 포함하는 보안 로그는 데이터 보존 정책에 따라 좀 더 연장된 기간 동안 보존됩니다.

#### <a name="organizational-controls-for-data-stored-by-partner"></a>파트너가 저장한 데이터에 대한 조직 제어

조직의 관리자가 파트너 시스템에서 정보를 제어하는 방법에 대해 설명하는 방법 삭제, 보존, 감사, 보관, 최종 사용자 정책 등

>monday.com 서비스는 여러 가용성 영역의 AWS 인프라에서 호스팅되는데, DR 사이트는 다른 지역에 설정됩니다. 특정 백업 데이터는 GCP(미국, 다중 지역)에 저장됩니다. monday.com 서비스에 대한 액세스는 사용자 조직의 관리자가 제어하며 다음 기능을 활용하여 달성됩니다.
- 사용자 유형
- 계정 수준 사용 권한
- 작업 영역
- 보드 유형
- 보드 수준 사용 권한
- 열 수준 사용 권한은 monday.com 인증 방법을 지원합니다.
- 자격 증명
- Google SSO(Pro 계획)
- Okta, OneLogin 및 사용자 지정 SAML 2.0(Enterprise 계획용) 2FA는 SMS 또는 인증자 앱을 통해 선택적으로 계정 관리자가 플랫폼의 관리 패널을 통해 사용하도록 설정될 수 있습니다.
미사용 모든 데이터는 AES-256을 사용하여 암호화됩니다. 열려 있는 네트워크를 통해 전송되는 모든 데이터는 TLS 1.3(TLS 1.2 이상)을 사용하여 암호화됩니다.

#### <a name="human-review-of-organizational-information"></a>조직 정보의 인적 검토

사람이 이 앱에서 수집하거나 저장하는 OII(조직 식별 정보) 데이터를 검토하거나 분석하는 데 관여하나요?

>예

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="mcas"

Microsoft Cloud App Security [카탈로그의](https://www.microsoft.com/enterprise-mobility-security/cloud-app-security) 정보가 아래에 표시됩니다.

<iframe height='1020' title='Microsoft Cloud App Security 정보' src='https://appmcasinfoprod.azurewebsites.net/#/dashboard/35338' frameborder='no' style='width: 100%;'></iframe>

<a href="https://appmcasinfoprod.azurewebsites.net/#/dashboard/35338" target="_blank">새 탭에서 보기</a>

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

