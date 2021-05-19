---
title: 발트 성 Amadeus에 의해 복고풍에 대 한 응용 프로그램 정보
ms.author: elmalova
author: elenamalova
ms.date: 11/03/2020
ms.topic: article
ms.service: attestation
certification_type: attested
description: Retro에 대한 사용 가능한 모든 보안 및 규정 준수 정보 정보, 데이터 처리 정책, Microsoft Cloud App Security 앱 카탈로그 정보 및 CSA STAR 레지스트리의 보안/규정 준수 정보.
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
<p>최종 업데이트: 2020년 11월 3일</p>

* <a href="https://teams.microsoft.com/l/app/434e1a1a-2ed7-4e45-9588-04f5099fd876" target="_blank">Teams 스토어에서 보기</a>
* <a href="https://appsource.microsoft.com/product/office/WA200001892" target="_blank">앱소스에서 보기</a>

::: zone pivot="general"

### <a name="general-information"></a>일반 정보

발트 마데우스에서 마이크로소프트에 제공 하는 정보:

| **정보** | **응답** |
|:----------------|:-------------|
| 앱 이름 | Retro |
| ID | WA200001892 |
| 지원되는 Office 365 클라이언트 | Microsoft Teams |
| 파트너 회사 이름 | Baltic Amadeus |
| 파트너 웹사이트의 URL | [https://www.ba.lt/en/](https://www.ba.lt/en/) |
| 개인정보 처리방침의 URL | [https://retro.ba.lt/privacypolicy](https://retro.ba.lt/privacypolicy) |
| 이용 약관의 URL | [https://retro.ba.lt/termsandconditions](https://retro.ba.lt/termsandconditions) |

 [!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="data"

### <a name="how-the-app-handles-data"></a>앱이 데이터를 처리하는 방법

이 정보는 이 앱이 조직 데이터를 수집하고 저장하는 방법과 앱이 수집하는 데이터를 통해 조직이 가질 수 있는 제어에 대해 발트 Amadeus에서 제공되었습니다.

#### <a name="data-access-using-microsoft-graph"></a>Microsoft Graph 을 사용하여 데이터 액세스

이 [앱에서 필요한 Microsoft Graph 권한을 나열합니다.](https://docs.microsoft.com/graph/permissions-reference)

>이 응용 프로그램은 Microsoft Graph 사용하지 않습니다.


#### <a name="non-microsoft-services-used"></a>사용되지 Microsoft 서비스

앱이 Microsoft 가 아닌 서비스와 조직 데이터를 전송하거나 공유하는 경우 앱에서 사용하는 비Microsoft 서비스, 전송되는 데이터를 나열하고 앱이 이 정보를 전송해야 하는 이유에 대한 명분을 포함합니다.

>| **모든 Microsoft 서비스 OII가** |  **어떤 OII가 전송됩니까?** | **OII 전송에 대한 정당화?** |
>|:-------------------|:--------------------------|:--------------------------|
>| 레트로 앱에는 Microsoft 서비스로 간주되지 않는 자체 웹 API가 있습니다. 앞서 언급했듯이, 이메일과 전체 이름을 식별하고 적절한 콘텐츠 표시 목적으로 저장합니다. 이 데이터는 다른 곳에서는 전송되지 않습니다. 또한 Retro는 스프린트 데이터를 아틀라시안 합류 공간으로 내보내는 선택적 기능을 가지고 있습니다. 이렇게 하려면 사용자가 가입 사용자 이름과 암호를 입력해야 합니다. 이 데이터는 사용자를 대신하여 Api에 가입하기 위한 인증된 요청을 하는 데만 사용되며 어디서나 저장하거나 기록되지 않습니다. |  | Retro에는 azure에도 등록된 자체 웹 API가 있습니다. 이를 사용하려면 사용자가 Microsoft ID 플랫폼을 통해 인증해야 합니다. 레트로 앱이 사용자 특정 콘텐츠를 서버할 수 있도록 사용자를 인증해야 합니다. |

#### <a name="data-access-via-bots"></a>봇을 통한 데이터 액세스

이 앱에 봇 또는 메시징 확장 프로그램이 포함된 경우 최종 사용자 식별 정보(EUII): 팀의 모든 팀 구성원의 명단(이름, 성, 표시 이름, 이메일 주소)에 액세스하거나 추가된 채팅을 할 수 있습니다. 이 응용 프로그램은이 기능을 사용합니까?

>| **EUII에 액세스할 수 있는 정당성?**  | **EUII는 데이터베이스에 저장되어 있습니까?** | **EUII를 저장하는 정당화?** |
>|:--------------------------------|:---------------------|:--------------------------|
>| 봇은 팀에 합류하거나 팀을 떠난 멤버를 확인하기 위해 명단에 액세스합니다. 이를 기반으로 사용자가 더 이상 스프린트 참가자 목록에 표시되지 않도록 프로젝트에서 해당 사용자를 추가하거나 비활성화합니다. | 이메일과 전체 이름은 함께 연결되어 데이터베이스에 저장됩니다. 전자 메일은 로그인한 사용자에게 적절한 콘텐츠를 표시하기 위해 사용자 식별에 사용됩니다. FullName은 새끼를 표시하는 데 사용되므로 다른 사용자가 누가 피드백을 평가하거나 작성하는지 알 수 있습니다.  |  |


#### <a name="telemetry-data"></a>원격 분석 데이터

조직 식별 정보(OII) 또는 최종 사용자 식별 정보(EUII)가 이 응용 프로그램의 원격 분석 또는 로그에 표시됩니까? 그렇다면 저장되는 데이터와 보존 및 제거 정책은 무엇입니까?

>아니요. 레트로 앱에서 원격 분석/로그를 생성하는 유일한 프로세스는 오류 로깅입니다. 오류 로그는 EUII 또는 OII를 포함하지 않습니다.

#### <a name="organizational-controls-for-data-stored-by-partner"></a>파트너가 저장한 데이터에 대한 조직 제어

조직의 관리자가 파트너 시스템에서 자신의 정보를 제어하는 방법을 설명해 보세요. 예를 들어 삭제, 보존, 감사, 보관, 최종 사용자 정책 등

>데이터는 azure SQL 서버 데이터베이스에 저장됩니다. 그것은 복고풍 응용 프로그램과 복고풍 봇을 통해 저장됩니다.
기본적으로 azure SQL 데이터베이스에는 투명한 데이터 암호화가 활성화되어 있습니다.
데이터베이스는 기본 인증 뒤에 잠겨 있습니다.

#### <a name="human-review-of-organizational-information"></a>조직 정보의 인간 검토

이 앱에서 수집하거나 저장되는 조직 식별 정보(OII) 데이터를 검토하거나 분석하는 데 관여하는 사람이 있습니까?

>예

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="mcas"

[Microsoft Cloud App Security](https://www.microsoft.com/enterprise-mobility-security/cloud-app-security) 카탈로그의 정보는 아래에 나타납니다.

<iframe height='1020' title='Microsoft Cloud App Security 정보' src='https://appmcasinfoprod.azurewebsites.net/#/dashboard/36148' frameborder='no' style='width: 100%;'></iframe>

<a href="https://appmcasinfoprod.azurewebsites.net/#/dashboard/36148" target="_blank">새 탭에서 보기</a>

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

