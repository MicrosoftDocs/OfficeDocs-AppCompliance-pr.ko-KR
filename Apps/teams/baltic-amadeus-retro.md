---
title: 발트어(Baltic Amadeus)에 의해 고가용성에 대한 응용 프로그램 정보
ms.author: elmalova
author: elenamalova
ms.date: 11/03/2020
ms.topic: article
ms.service: attestation
certification_type: attested
description: 인바우트, 데이터 처리 정책, CSA STAR 레지스트리의 Microsoft Cloud App Security 앱 카탈로그 정보 및 보안/규정 준수 정보에 대해 사용 가능한 모든 보안 및 규정 준수 정보입니다.
zone_pivot_groups: app-info-data-mcas
ms.openlocfilehash: 49b17e202fb358284b9a36ed33646926d649afe3
ms.sourcegitcommit: a44420a99a1a3a9d0e49f4be66f266e2d4ca7bbb
ms.translationtype: MT
ms.contentlocale: ko-KR
ms.lasthandoff: 05/19/2021
ms.locfileid: "52553459"
---
# <a name="retro"></a>Retro

<p></p>
<img alt="Publisher Attestation: The information on this page is based on a self-assessment report provided by the app developer on the security, compliance, and data handling practices followed by this app. Microsoft makes no guarantees regarding the accuracy of the information." src="../media/attested.png" width="650" />
<p>개발자가 마지막으로 업데이트한 날짜: 2020년 11월 3일</p>

* <a href="https://teams.microsoft.com/l/app/434e1a1a-2ed7-4e45-9588-04f5099fd876" target="_blank">저장소의 Teams 보기</a>
* <a href="https://appsource.microsoft.com/product/office/WA200001892" target="_blank">AppSource의 보기</a>

::: zone pivot="general"

### <a name="general-information"></a>일반 정보

Baltic Amadeus에서 Microsoft에 제공한 정보:

| **정보** | **응답** |
|:----------------|:-------------|
| 앱 이름 | Retro |
| ID | WA200001892 |
| Office 365 클라이언트 지원 | Microsoft Teams |
| 파트너 회사 이름 | Baltic Amadeus |
| 파트너 웹 사이트의 URL | [https://www.ba.lt/en/](https://www.ba.lt/en/) |
| 개인 정보 취급 방침의 URL | [https://retro.ba.lt/privacypolicy](https://retro.ba.lt/privacypolicy) |
| 사용 약관 URL | [https://retro.ba.lt/termsandconditions](https://retro.ba.lt/termsandconditions) |

 [!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="data"

### <a name="how-the-app-handles-data"></a>앱이 데이터를 처리하는 방법

이 정보는 Baltic Amadeus에서 이 앱이 조직 데이터를 수집하고 저장하는 방법 및 앱이 수집하는 데이터를 통해 조직이 사용할 컨트롤에 대해 제공됩니다.

#### <a name="data-access-using-microsoft-graph"></a>Microsoft 365를 사용한 데이터 Graph

이 앱에 [Graph Microsoft 사용자 권한을](https://docs.microsoft.com/graph/permissions-reference) 나열합니다.

>이 응용 프로그램은 Microsoft 응용 프로그램을 Graph.


#### <a name="non-microsoft-services-used"></a>비영구 Microsoft 서비스

앱이 Microsoft가 아닌 서비스로 조직 데이터를 전송하거나 공유하는 경우 앱에서 사용하는 비 Microsoft 서비스, 전송되는 데이터를 나열하고 앱이 이 정보를 전송해야 하는 이유에 대한 사유를 포함합니다.

>| **모든 비 Microsoft 서비스 OII가 다음으로 전송됩니다.** |  **전송되는 OII는 무엇입니까?** | **OII 전송의 사당성** |
>|:-------------------|:--------------------------|:--------------------------|
>| 평가 앱에는 Microsoft 서비스로 간주되지 않는 자체 웹 API가 있습니다. 앞에서 설명한처럼 식별 및 적절한 콘텐츠 표시를 위해 Email 및 Fullname을 저장합니다. 이 데이터는 다른 곳에서 전송되지 않습니다. 또한 Sprint 데이터를 Atlassian의 통합 공간으로 내보낼 수 있는 선택적 기능이 있습니다. 이렇게 하도록 사용자는 confluence 사용자 이름과 암호를 입력해야 합니다. 이 데이터는 사용자를 대신하여 confluence api에 대한 인증된 요청을 만드는 데만 사용되고 저장 또는 기록되지 않습니다. |  | 회피에는 Azure에도 등록된 자체 웹 API가 있습니다. 이 기능을 사용하려면 Microsoft Identity Platform을 통해 사용자를 인증해야 합니다. 소수 앱으로 사용자 특정 콘텐츠를 서버할 수 있도록 사용자를 인증해야 합니다. |

#### <a name="data-access-via-bots"></a>봇을 통한 데이터 액세스

이 앱에 봇 또는 메시징 확장이 포함되어 있는 경우 팀 구성원의 명단(이름, 성, 표시 이름, 전자 메일 주소)이나 팀 구성원이 추가된 채팅의 최종 사용자 식별 정보(EUII)에 액세스할 수 있습니다. 이 앱이 이 기능을 사용하나요?

>| **EUII 액세스의 사유는 무엇입니까?**  | **EUII가 데이터베이스에 저장되어 있나요?** | **EUII 저장의 사유는 무엇입니까?** |
>|:--------------------------------|:---------------------|:--------------------------|
>| 봇은 팀에 참가하거나 팀에서 나선 구성원을 확인하기 위해 로스터에 액세스합니다. 이를 기반으로 사용자가 더 이상 스프린트 참가자 목록에 표시되지 못하도록 프로젝트에서 해당 사용자를 추가하거나 비활성화합니다. | 전자 메일과 FullName은 함께 연결되고 데이터베이스에 저장됩니다. 전자 메일은 로그인한 사용자에게 적절한 콘텐츠를 표시하기 위해 사용자 식별에 사용됩니다. FullName은 puproses를 표시하는 데 사용 하여 다른 사용자가 평가하거나 피드백을 작성하고 있는 사용자를 알 수 있습니다.  |  |


#### <a name="telemetry-data"></a>원격 분석 데이터

이 응용 프로그램의 원격 분석 또는 로그에 OII(조직 식별 정보) 또는 EUII(최종 사용자 식별 정보)가 나타나나요? 그렇다면 저장되는 데이터와 보존 및 제거 정책에 대해 설명하세요.

>아니요. 표시 앱에서 원격 분석/로그를 생성하는 프로세스는 오류 로깅뿐입니다. 오류 로그에 EUII 또는 OII가 포함되지 않습니다.

#### <a name="organizational-controls-for-data-stored-by-partner"></a>파트너가 저장한 데이터에 대한 조직 제어

조직의 관리자가 파트너 시스템에서 정보를 제어하는 방법에 대해 설명하는 방법 삭제, 보존, 감사, 보관, 최종 사용자 정책 등

>데이터는 Azure sql Server 데이터베이스에 저장됩니다. 소수점 앱 및 봇을 통해 저장됩니다.
기본적으로 azure sql 데이터베이스는 투명한 데이터 암호화를 사용하도록 설정되어 있습니다.
데이터베이스가 기본 인증에 잠겨 있습니다.

#### <a name="human-review-of-organizational-information"></a>조직 정보의 인적 검토

사람이 이 앱에서 수집하거나 저장하는 OII(조직 식별 정보) 데이터를 검토하거나 분석하는 데 관여하나요?

>예

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="mcas"

Microsoft Cloud App Security [카탈로그의](https://www.microsoft.com/enterprise-mobility-security/cloud-app-security) 정보가 아래에 표시됩니다.

<iframe height='1020' title='Microsoft Cloud App Security 정보' src='https://appmcasinfoprod.azurewebsites.net/#/dashboard/36148' frameborder='no' style='width: 100%;'></iframe>

<a href="https://appmcasinfoprod.azurewebsites.net/#/dashboard/36148" target="_blank">새 탭에서 보기</a>

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

