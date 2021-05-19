---
title: 참여 제곱에 의해 커넥트 보드신청 정보
ms.author: elmalova
author: elenamalova
ms.date: 02/16/2021
ms.topic: article
ms.service: attestation
certification_type: attested
description: 이사회 커넥트 가능한 모든 보안 및 규정 준수 정보 정보, 데이터 처리 정책, Microsoft Cloud App Security 앱 카탈로그 정보 및 CSA STAR 레지스트리의 보안/규정 준수 정보.
zone_pivot_groups: app-info-data-mcas-identity
ms.openlocfilehash: 6b314c6cc51515efced101ba986555d859dc4182
ms.sourcegitcommit: a44420a99a1a3a9d0e49f4be66f266e2d4ca7bbb
ms.translationtype: MT
ms.contentlocale: ko-KR
ms.lasthandoff: 05/19/2021
ms.locfileid: "52553189"
---
# <a name="board-connect"></a>Board Connect

<p></p>
<img alt="Publisher Attestation: The information on this page is based on a self-assessment report provided by the app developer on the security, compliance, and data handling practices followed by this app. Microsoft makes no guarantees regarding the accuracy of the information." src="../media/attested.png" width="650" />
<p>최종 업데이트: 2021년 2월 16일</p>

* <a href="https://teams.microsoft.com/l/app/e8f06a4e-cefe-4b1e-a24b-c97bea471130" target="_blank">Teams 스토어에서 보기</a>
* <a href="https://appsource.microsoft.com/product/office/WA200001955" target="_blank">앱소스에서 보기</a>

::: zone pivot="general"

### <a name="general-information"></a>일반 정보

Microsoft에 제곱된 참여에서 제공하는 정보:

| **정보** | **응답** |
|:----------------|:-------------|
| 앱 이름 | Board Connect |
| ID | WA200001955 |
| 지원되는 Office 365 클라이언트 | Microsoft Teams |
| 파트너 회사 이름 | Engage Squared |
| 파트너 웹사이트의 URL | [https://boardconnect.app](https://boardconnect.app) |
| Teams 응용 프로그램 정보 페이지의 URL | [https://boardconnect.app](https://boardconnect.app) |
| 개인정보 처리방침의 URL | [https://boardconnect.app/privacy](https://boardconnect.app/privacy) |
| 이용 약관의 URL | [https://boardconnect.app/terms](https://boardconnect.app/terms) |

 [!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="data"

### <a name="how-the-app-handles-data"></a>앱이 데이터를 처리하는 방법

이 정보는 이 앱이 조직 데이터를 수집하고 저장하는 방법과 앱이 수집하는 데이터에 대한 조직에서 가질 수 있는 제어에 대해 Engage Squared에서 제공했습니다.

#### <a name="data-access-using-microsoft-graph"></a>Microsoft Graph 을 사용하여 데이터 액세스

이 [앱에서 필요한 Microsoft Graph 권한을 나열합니다.](https://docs.microsoft.com/graph/permissions-reference)

>| **사용 권한**  | **권한 유형(위임/응용 프로그램)** | **데이터가 수집되고 있습니까? 그것을 수집하기위한 정당화?** | **데이터가 저장되어 있습니까? 그것을 저장하는 정당화?** | **Azure AD 앱 ID** |
>|:----------------|:--------------------|:---------------------------------------------------|:--------------------------|:--------------------------|
>| 캘린더.읽기 쓰기 | 위임 | 앱이 앱을 통해 제출된 이사회 회의 출석 응답을 반영하도록 사용자 캘린더를 업데이트할 수 있도록 합니다. | Azure 테이블 저장소 내에 데이터가 저장되지 않습니다. | 4a6873f6-8360-4023-bd6f-2923d1eb2e94 |
>| Group.ReadWrite.All | 위임 | 앱이 그룹 캘린더 이벤트를 만들, 업데이트 및 삭제할 수 있도록 합니다. | 우리는 테넌트 ID와 함께 그룹의 ID를 저장합니다 - 이것은 조직이 이사회 커넥트 대한 허가를 받았으며 이를 검증 할 수 있도록 라이센스 관점에서 저장되고 사용됩니다. 또한 이 응용 프로그램의 설치 수를 추적하여 라이선스 모델에 인라인으로 테넌트 내에 있는 응용 프로그램의 설치 수를 추적합니다. | 4a6873f6-8360-4023-bd6f-2923d1eb2e94 |
>| 사이트.관리.모든 것 | 위임 | 앱이 목록 및 라이브러리를 만들 수 있도록 하려면 목록 항목을 관리하고 팀 사이트 컬렉션에서 문서를 관리합니다. | 없음 | 4a6873f6-8360-4023-bd6f-2923d1eb2e94 |
>| User.Read | 위임 | 사용자가 앱에 로그인하고 앱이 현재 로그인한 사용자의 프로필을 읽을 수 있도록 합니다. | 이 끝점의 데이터는 Azure 테이블 저장소에 저장되지 않습니다. | 4a6873f6-8360-4023-bd6f-2923d1eb2e94 |
>| User.ReadBasic.All | 위임 | 앱이 앱에 표시하기 위해 로그인 한 사용자를 대신하여 다른 사용자의 기본 프로필 속성 집합을 읽을 수 있도록합니다. 여기에는 표시 이름, 이름과 성, 이메일 주소 및 사진이 포함됩니다. | 없음, 데이터는 Azure 테이블 저장소에 저장되지 않습니다. | 4a6873f6-8360-4023-bd6f-2923d1eb2e94 |
>| offline_access | 위임 | 앱이 새로 고침 토큰을 얻을 수 있도록 하려면 현재 토큰이 만료되면 새 액세스 토큰을 얻는 데 사용할 수 있습니다. | 없음, 데이터는 Azure 테이블 저장소 내에 저장되지 않습니다. | 4a6873f6-8360-4023-bd6f-2923d1eb2e94 |


#### <a name="non-microsoft-services-used"></a>사용되지 Microsoft 서비스

앱이 Microsoft 가 아닌 서비스와 조직 데이터를 전송하거나 공유하는 경우 앱에서 사용하는 비Microsoft 서비스, 전송되는 데이터를 나열하고 앱이 이 정보를 전송해야 하는 이유에 대한 명분을 포함합니다.

>비Microsoft 서비스 사용되지 않습니다.

#### <a name="data-access-via-bots"></a>봇을 통한 데이터 액세스

이 앱에 봇 또는 메시징 확장 프로그램이 포함된 경우 최종 사용자 식별 정보(EUII): 팀의 모든 팀 구성원의 명단(이름, 성, 표시 이름, 이메일 주소)에 액세스하거나 추가된 채팅을 할 수 있습니다. 이 응용 프로그램은이 기능을 사용합니까?

>EUII에 액세스할 수 없습니다.


#### <a name="telemetry-data"></a>원격 분석 데이터

조직 식별 정보(OII) 또는 최종 사용자 식별 정보(EUII)가 이 응용 프로그램의 원격 분석 또는 로그에 표시됩니까? 그렇다면 저장되는 데이터와 보존 및 제거 정책은 무엇입니까?

>응용 프로그램 원격 분석 또는 로그에 OII 또는 EUII가 나타나지 않습니다.

#### <a name="organizational-controls-for-data-stored-by-partner"></a>파트너가 저장한 데이터에 대한 조직 제어

조직의 관리자가 파트너 시스템에서 자신의 정보를 제어하는 방법을 설명해 보세요. 예를 들어 삭제, 보존, 감사, 보관, 최종 사용자 정책 등

>모든 관리자에 대한 2FA, 두 개의 참여 제곱 사용자가 액세스 할 수 있습니다

#### <a name="human-review-of-organizational-information"></a>조직 정보의 인간 검토

이 앱에서 수집하거나 저장되는 조직 식별 정보(OII) 데이터를 검토하거나 분석하는 데 관여하는 사람이 있습니까?

>아니요

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="mcas"

[Microsoft Cloud App Security](https://www.microsoft.com/enterprise-mobility-security/cloud-app-security) 카탈로그의 정보는 아래에 나타납니다.

<iframe height='1020' title='Microsoft Cloud App Security 정보' src='https://appmcasinfoprod.azurewebsites.net/#/dashboard/36435' frameborder='no' style='width: 100%;'></iframe>

<a href="https://appmcasinfoprod.azurewebsites.net/#/dashboard/36435" target="_blank">새 탭에서 보기</a>

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="identity"

### <a name="identity-information"></a>신원 정보

이 정보는 이 앱이 인증, 권한 부여, 응용 프로그램 등록 모범 사례 및 기타 ID 기준을 처리하는 방법에 대해 Engage Squared에서 제공했습니다.

| **정보** | **응답** |
|:----------------|:-------------|
| Microsoft 식별 플랫폼(Azure AD)과 통합합니까?  | 예 |
| Microsoft ID 플랫폼 통합 검사 목록에 설명된 모든 적용 가능한 모범 사례를 검토하고 준수했습니까?  | 예 |
| 앱에서 인증에 MSAL(Microsoft 인증 라이브러리)을 사용합니까? | 예 |
| 앱이 조건부 액세스 정책을 지원합니까? | 아니요 |
| 앱에서 시나리오에 대한 최소 권한 권한을 요청합니까? | 예 |
| 앱의 정적 등록 권한은 앱이 동적으로 점진적으로 요청하는 권한을 정확하게 반영합니까? | 예 |
| 앱이 다중 테넌션을 지원합니까? | 예 |
| 앱에 기밀 클라이언트가 있습니까? | 아니요 |
| 앱에 등록된 URI(리디렉션 통합 리소스 식별자)를 모두 소유하고 있습니까? | 예 |
| 앱의 경우 무엇을 사용하지 않으려습니까? | - 와일드카드 리디렉션 URI,<br/>- OAuth2 암시적 Flow, SPA에 필요한 경우가 아니면<br/> |
| 앱에서 웹 API가 노출됩니까? | 예 |
| 권한 모델은 클라이언트 앱이 적절한 동의를 받는 경우에만 호출을 성공시킬 수 있습니까? | 예 |
| 앱에서 미리 보기 API를 사용합니까? | 아니요 |
| 앱에서 비하 API를 사용합니까? | 아니요 |

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end
