---
title: RingCentral, 커넥트 TELUS Business 응용 프로그램에 대한 응용 프로그램 정보
ms.author: elmalova
author: elenamalova
ms.date: 08/19/2021
ms.topic: article
ms.service: attestation
certification_type: attested
description: CSA STAR 레지스트리의 TELUS Business 커넥트, 데이터 처리 정책, Microsoft Cloud App Security 앱 카탈로그 정보 및 보안/규정 준수 정보에 대해 사용할 수 있는 모든 보안 및 규정 준수 정보입니다.
zone_pivot_groups: app-info-data-identity
ms.openlocfilehash: d39d9d969d09d711de1d879dd869543e06d3a596
ms.sourcegitcommit: 983ed1755036e92d99745770f82f33417b21efec
ms.translationtype: MT
ms.contentlocale: ko-KR
ms.lasthandoff: 10/18/2021
ms.locfileid: "60431000"
---
# <a name="telus-business-connect"></a>TELUS Business Connect

<p></p>
<img alt="Publisher Attestation: The information on this page is based on a self-assessment report provided by the app developer on the security, compliance, and data handling practices followed by this app. Microsoft makes no guarantees regarding the accuracy of the information." src="../media/attested.png" width="650" />
<p>개발자가 마지막으로 업데이트한 날짜: 2021년 6월 4일</p>

* <a href="https://teams.microsoft.com/l/app/d5001eed-f63e-4a7d-9b49-bf8272c934cd" target="_blank">저장소의 Teams 보기</a>
* <a href="https://appsource.microsoft.com/product/office/WA200002300" target="_blank">AppSource의 보기</a>

::: zone pivot="general"

### <a name="general-information"></a>일반 정보

RingCentral, Inc.에서 Microsoft에 제공한 정보:

| **정보** | **응답** |
|:----------------|:-------------|
| 앱 이름 | TELUS Business Connect |
| ID | WA200002300 |
| Office 365 클라이언트 지원 | Microsoft Teams |
| 파트너 회사 이름 | RingCentral, Inc. |
| 파트너 웹 사이트의 URL | [https://www.ringcentral.com](https://www.ringcentral.com) |
| 응용 프로그램 Teams 페이지의 URL입니다. | [https://appsource.microsoft.com/en-us/product/office/WA2000...](https://appsource.microsoft.com/en-us/product/office/WA200002300) |
| 개인 정보 취급 방침의 URL | [https://www.telus.com/en/about/privacy/](https://www.telus.com/en/about/privacy/) |
| 사용 약관 URL | [https://telus.com/BusinessConnect/ServiceTerms](https://telus.com/BusinessConnect/ServiceTerms) |

 [!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="data"

### <a name="how-the-app-handles-data"></a>앱이 데이터를 처리하는 방법

이 정보는 이 앱이 조직 데이터를 수집 및 저장하는 방법 및 앱이 수집하는 데이터를 통해 조직이 하게 될 컨트롤에 대해 RingCentral, Inc.에서 제공했습니다.

#### <a name="data-access-using-microsoft-graph"></a>Microsoft 365를 사용한 데이터 Graph

이 앱에 [Graph Microsoft 사용자 권한을](https://docs.microsoft.com/graph/permissions-reference) 나열합니다.

>| **사용 권한**  | **사용 권한 유형(위임/ 응용 프로그램)** | **데이터가 수집하나요? 수집의 사당성** | **데이터가 저장되어 있나요? 저장 사정이 있나요?** | **Azure AD 앱 ID** |
>|:----------------|:------------------------------------------------|:--------------------------------------------------------|:--------------------------------------------------|:--------------------|
>| Calendars.ReadWrite | 위임 |  응용 프로그램에서 일정을 통해 모임 초대 이벤트를 보낼 수 있도록 허용 | 없음 | [e601bd6e-0476-4d66-bd57-a9d13c207f0b](https://docs.microsoft.com/microsoft-365-app-certification/azure/e601bd6e-0476-4d66-bd57-a9d13c207f0b) |
>| User.Read | 위임 |  앱에서 기본 프로필(전자 메일&#8217;이름)을 통해 사용자에게 연락처 일치를 할 수 있도록 허용합니다. 또한 사용자가 링 센터 계정으로 로그인하고 O365 계정을 연결하도록 허용합니다. |  전자 메일, 이름, 성 | [e601bd6e-0476-4d66-bd57-a9d13c207f0b](https://docs.microsoft.com/microsoft-365-app-certification/azure/e601bd6e-0476-4d66-bd57-a9d13c207f0b) |
>| User.Read.All | 위임 | 응용 프로그램에서 서비스에서 전화를 걸기 위해 전화 번호가 있는 사용자의 전체 프로필을 읽을 수 있도록 허용합니다. | 없음 | [e601bd6e-0476-4d66-bd57-a9d13c207f0b](https://docs.microsoft.com/microsoft-365-app-certification/azure/e601bd6e-0476-4d66-bd57-a9d13c207f0b) |
>| offline_access | 위임 |  응용 프로그램에서 oauth 토큰을 다운로드하고 업데이트할 수 있습니다. |  MS Graph API에 액세스하기 위한 액세스 토큰, 새로 고침 토큰 | [e601bd6e-0476-4d66-bd57-a9d13c207f0b](https://docs.microsoft.com/microsoft-365-app-certification/azure/e601bd6e-0476-4d66-bd57-a9d13c207f0b) |


#### <a name="non-microsoft-services-used"></a>비영구 Microsoft 서비스

앱이 Microsoft가 아닌 서비스로 조직 데이터를 전송하거나 공유하는 경우 앱에서 사용하는 비 Microsoft 서비스, 전송되는 데이터를 나열하고 앱이 이 정보를 전송해야 하는 이유에 대한 사유를 포함합니다.

>비영구 Microsoft 서비스 사용되지 않습니다.

#### <a name="data-access-via-bots"></a>봇을 통한 데이터 액세스

이 앱에 봇 또는 메시징 확장이 포함되어 있는 경우 팀 구성원의 명단(이름, 성, 표시 이름, 전자 메일 주소)이나 팀 구성원이 추가된 채팅의 최종 사용자 식별 정보(EUII)에 액세스할 수 있습니다. 이 앱이 이 기능을 사용하나요?

>EUII에 액세스하지 않습니다.


#### <a name="telemetry-data"></a>원격 분석 데이터

이 응용 프로그램의 원격 분석 또는 로그에 OII(조직 식별 정보) 또는 EUII(최종 사용자 식별 정보)가 나타나나요? 그렇다면 저장되는 데이터와 보존 및 제거 정책에 대해 설명하세요.

>응용 프로그램 원격 분석 또는 로그에 OII 또는 EUII가 나타나지 않습니다.

#### <a name="organizational-controls-for-data-stored-by-partner"></a>파트너가 저장한 데이터에 대한 조직 제어

조직의 관리자가 파트너 시스템에서 정보를 제어하는 방법에 대해 설명하는 방법 삭제, 보존, 감사, 보관, 최종 사용자 정책 등

>다른 조직을 사용하는 경우 여전히 귀하의 개인 정보를 제어합니다. 또한 제대로 보호되지 않을 수 있도록 엄격한&#8217;있습니다. 마지막으로 위의 섹션에서는 개인 정보가 다른 조직, 정부 기관 및 사법 기관과 공유되는 상황에 대해 설명합니다.  다른 조직과 정보를 공유하는 경우&#8217;가능한 한&#8217;보호할 수 있도록 할 것입니다.

#### <a name="human-review-of-organizational-information"></a>조직 정보의 인적 검토

사람이 이 앱에서 수집하거나 저장하는 OII(조직 식별 정보) 데이터를 검토하거나 분석하는 데 관여하나요?

>아니요

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end


::: zone pivot="identity"

### <a name="identity-information"></a>ID 정보

이 정보는 이 앱이 인증, 권한 부여, 응용 프로그램 등록 모범 사례 및 기타 ID 기준을 처리하는 방법에 대해 RingCentral, Inc.에서 제공했습니다.

| **정보** | **응답** |
|:----------------|:-------------|
| Microsoft Identify Platform(Azure AD)과 통합하나요?  | 아니요 |

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end
