---
title: 제곱을 커넥트 게시판에 대한 응용 프로그램 정보
ms.author: elmalova
author: elenamalova
ms.date: 07/05/2021
ms.topic: article
ms.service: attestation
certification_type: attested
description: Board 커넥트, 데이터 처리 정책, CSA STAR 레지스트리의 Microsoft Cloud App Security 앱 카탈로그 정보 및 보안/규정 준수 정보에 대해 사용할 수 있는 모든 보안 및 규정 준수 정보입니다.
zone_pivot_groups: app-info-data-mcas-identity
ms.openlocfilehash: c04b8be94b4d9a6367c8baa2b3370d82c2bdff5c
ms.sourcegitcommit: a613e40971c8b48fa2b7a35039b4331a8116763b
ms.translationtype: MT
ms.contentlocale: ko-KR
ms.lasthandoff: 07/22/2021
ms.locfileid: "53525672"
---
# <a name="board-connect"></a>Board Connect

<p></p>
<img alt="Publisher Attestation: The information on this page is based on a self-assessment report provided by the app developer on the security, compliance, and data handling practices followed by this app. Microsoft makes no guarantees regarding the accuracy of the information." src="../media/attested.png" width="650" />
<p>개발자가 마지막으로 업데이트한 날짜: 2021년 7월 5일</p>

* <a href="https://teams.microsoft.com/l/app/e8f06a4e-cefe-4b1e-a24b-c97bea471130" target="_blank">저장소의 Teams 보기</a>
* <a href="https://appsource.microsoft.com/product/office/WA200001955" target="_blank">AppSource의 보기</a>

::: zone pivot="general"

### <a name="general-information"></a>일반 정보

Microsoft에 제곱하여 제공되는 정보:

| **정보** | **응답** |
|:----------------|:-------------|
| 앱 이름 | Board Connect |
| ID | WA200001955 |
| Office 365 클라이언트 지원 | Microsoft Teams |
| 파트너 회사 이름 | Engage Squared |
| 파트너 웹 사이트의 URL | [https://engagesq.com](https://engagesq.com) |
| 응용 프로그램 Teams 페이지의 URL입니다. | [https://boardconnect.app](https://boardconnect.app) |
| 개인 정보 취급 방침의 URL | [https://boardconnect.app/privacy/](https://boardconnect.app/privacy/) |
| 사용 약관 URL | [https://boardconnect.app/terms](https://boardconnect.app/terms) |

 [!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="data"

### <a name="how-the-app-handles-data"></a>앱이 데이터를 처리하는 방법

이 정보는 Engage Squared에서 이 앱이 조직 데이터를 수집하고 저장하는 방법 및 앱이 수집하는 데이터를 통해 조직이 하게 될 컨트롤에 대해 제곱에서 제공했습니다.

#### <a name="data-access-using-microsoft-graph"></a>Microsoft 365를 사용한 데이터 Graph

이 앱에 [Graph Microsoft 사용자 권한을](https://docs.microsoft.com/graph/permissions-reference) 나열합니다.

>| **사용 권한**  | **사용 권한 유형(위임/ 응용 프로그램)** | **데이터가 수집하나요? 수집의 사당성** | **데이터가 저장되어 있나요? 저장 사정이 있나요?** | **Azure AD 앱 ID** |
>|:----------------|:------------------------------------------------|:--------------------------------------------------------|:--------------------------------------------------|:--------------------|
>| Calendars.ReadWrite | 위임 | 앱이 앱을 통해 제출된 보드 모임 참석 응답을 반영하도록 사용자 일정을 업데이트할 수 있도록 허용합니다. | Azure 테이블 저장소 내에 데이터가 저장되지 않습니다. | [4a6873f6-8360-4023-bd6f-2923d1eb2e94](https://docs.microsoft.com/microsoft-365-app-certification/azure/4a6873f6-8360-4023-bd6f-2923d1eb2e94) |
>| Group.ReadWrite.All | 위임 | 앱에서 그룹 일정 이벤트를 만들고 업데이트하고 삭제할 수 있도록 허용합니다. | 테넌트 ID와 함께 그룹의 ID를 저장합니다. 이 ID는 라이선스 관점에서 저장되고 사용되어 조직이 보드 라이선스를 취득할 수 커넥트. 또한 이 라이선스 모델에 인라인으로 테넌트 내에 있는 응용 프로그램의 설치 수를 추적하는 데도 사용됩니다. | [4a6873f6-8360-4023-bd6f-2923d1eb2e94](https://docs.microsoft.com/microsoft-365-app-certification/azure/4a6873f6-8360-4023-bd6f-2923d1eb2e94) |
>| Sites.Manage.All | 위임 | 앱에서 목록 및 라이브러리를 만들 수 있도록 허용하기 위해 목록 항목을 관리하고 팀 사이트 모음에서 문서를 관리합니다. | 없음 | [4a6873f6-8360-4023-bd6f-2923d1eb2e94](https://docs.microsoft.com/microsoft-365-app-certification/azure/4a6873f6-8360-4023-bd6f-2923d1eb2e94) |
>| User.Read | 위임 | 사용자가 앱에 로그인하고 앱이 현재 로그인한 사용자의 프로필을 읽을 수 있도록 허용합니다. | 이 끝점의 데이터가 Azure 테이블 저장소에 저장되지 않습니다. | [4a6873f6-8360-4023-bd6f-2923d1eb2e94](https://docs.microsoft.com/microsoft-365-app-certification/azure/4a6873f6-8360-4023-bd6f-2923d1eb2e94) |
>| User.ReadBasic.All | 위임 | 앱에서 로그인한 사용자를 대신하여 다른 사용자의 기본 프로필 속성 집합을 읽을 수 있도록 허용하려면 이 속성을 앱에 표시합니다. 여기에는 표시 이름, 이름 및 성, 전자 메일 주소 및 사진이 포함됩니다. | 없음, 데이터가 Azure 테이블 저장소에 저장되지 않습니다. | [4a6873f6-8360-4023-bd6f-2923d1eb2e94](https://docs.microsoft.com/microsoft-365-app-certification/azure/4a6873f6-8360-4023-bd6f-2923d1eb2e94) |
>| offline_access | 위임 | 앱이 새로 고침 토큰을 얻을 수 있도록 설정하려면 현재 액세스 토큰이 만료될 때 새 액세스 토큰을 다운로드하는 데 사용할 수 있습니다. | 없음, 데이터가 Azure 테이블 저장소 내에 저장되지 않습니다. | [4a6873f6-8360-4023-bd6f-2923d1eb2e94](https://docs.microsoft.com/microsoft-365-app-certification/azure/4a6873f6-8360-4023-bd6f-2923d1eb2e94) |


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

>모든 관리자에 대한 2FA, 참여하는 두 사용자만 액세스할 수 있습니다.

#### <a name="human-review-of-organizational-information"></a>조직 정보의 인적 검토

사람이 이 앱에서 수집하거나 저장하는 OII(조직 식별 정보) 데이터를 검토하거나 분석하는 데 관여하나요?

>아니요

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="mcas"

Microsoft Cloud App Security [카탈로그의](https://www.microsoft.com/enterprise-mobility-security/cloud-app-security) 정보가 아래에 표시됩니다.

<iframe height='1020' title='Microsoft Cloud App Security 정보' src='https://appmcasinfoprod.azurewebsites.net/#/dashboard/36435' frameborder='no' style='width: 100%;'></iframe>

<a href="https://appmcasinfoprod.azurewebsites.net/#/dashboard/36435" target="_blank">새 탭에서 보기</a>

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="identity"

### <a name="identity-information"></a>ID 정보

이 정보는 Engage Squared에서 이 앱이 인증, 권한 부여, 응용 프로그램 등록 모범 사례 및 기타 ID 조건을 처리하는 방법에 대해 제공했습니다.

| **정보** | **응답** |
|:----------------|:-------------|
| Microsoft Identify Platform(Azure AD)과 통합하나요?  | 예 |
| 통합 검사 목록에 설명된 적용 가능한 모든 모범 사례를 Microsoft ID 플랫폼 준수하나요?  | 예 |
| 앱에서 인증에 MSAL(Microsoft 인증 라이브러리)을 사용하나요? | 예 |
| 앱에서 조건부 액세스 정책을 지원하나요? | 아니요 |
| 앱에서 시나리오에 대한 최소 권한 권한을 요청하나요? | 예 |
| 앱의 정적으로 등록된 사용 권한은 앱이 동적으로 그리고 증분적으로 요청하는 권한을 정확하게 반영하나요? | 예 |
| 앱에서 다중 테넌시를 지원하나요? | 예 |
| 앱에 기밀 클라이언트가 있나요? | 아니요 |
| 앱에 등록된 리디렉션 URI(통합 리소스 식별자)를 모두 소유하고 있나요? | 예 |
| 앱의 경우 어떻게 사용하지 않도록 해야 하나요? | - 와일드카드 리디렉션 URIS,<br/>- OAuth2 암시적 Flow SPA에 필요하지 않은 경우<br/> |
| 앱에서 웹 API를 노출하나요? | 예 |
| 사용 권한 모델에서 클라이언트 앱이 적절한 동의를 받은 경우 통화 성공만 허용하나요? | 예 |
| 앱에서 미리 보기 API를 사용하나요? | 아니요 |
| 앱에서 사용되지 않는 API를 사용하나요? | 아니요 |

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end
