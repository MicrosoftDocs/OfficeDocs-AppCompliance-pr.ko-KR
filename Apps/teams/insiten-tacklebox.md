---
title: Insiten의 TackleBox에 대한 응용 프로그램 정보
ms.author: elmalova
author: elenamalova
ms.date: 01/12/2021
ms.topic: article
ms.service: attestation
certification_type: attested
description: TackleBox에 사용할 수 있는 모든 보안 및 규정 준수 정보, 데이터 처리 정책, CSA STAR 레지스트리의 Microsoft Cloud App Security 앱 카탈로그 정보 및 보안/규정 준수 정보
zone_pivot_groups: app-info-data-mcas-identity
ms.openlocfilehash: bf5841d5b51470b6aaab29f303b1ee1c5c5a0141
ms.sourcegitcommit: a613e40971c8b48fa2b7a35039b4331a8116763b
ms.translationtype: MT
ms.contentlocale: ko-KR
ms.lasthandoff: 07/22/2021
ms.locfileid: "53521469"
---
# <a name="tacklebox"></a>TackleBox

<p></p>
<img alt="Publisher Attestation: The information on this page is based on a self-assessment report provided by the app developer on the security, compliance, and data handling practices followed by this app. Microsoft makes no guarantees regarding the accuracy of the information." src="../media/attested.png" width="650" />
<p>개발자가 마지막으로 업데이트한 날짜: 2021년 1월 12일</p>

* <a href="https://teams.microsoft.com/l/app/dc37dab6-b497-4259-9aad-e40bfa023796" target="_blank">저장소의 Teams 보기</a>
* <a href="https://appsource.microsoft.com/product/office/WA200002310" target="_blank">AppSource의 보기</a>

::: zone pivot="general"

### <a name="general-information"></a>일반 정보

Microsoft에 Insiten에서 제공하는 정보:

| **정보** | **응답** |
|:----------------|:-------------|
| 앱 이름 | TackleBox |
| ID | WA200002310 |
| Office 365 클라이언트 지원 | Microsoft Teams |
| 파트너 회사 이름 | Insiten |
| 파트너 웹 사이트의 URL | [https://insiten.com](https://insiten.com) |
| 응용 프로그램 Teams 페이지의 URL입니다. | [https://tacklebox.app](https://tacklebox.app) |
| 개인 정보 취급 방침의 URL | [https://tacklebox.app/privacy/](https://tacklebox.app/privacy/) |
| 사용 약관 URL | [https://tacklebox.app/terms/](https://tacklebox.app/terms/) |

 [!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="data"

### <a name="how-the-app-handles-data"></a>앱이 데이터를 처리하는 방법

이 정보는 이 앱이 조직 데이터를 수집 및 저장하는 방법 및 앱이 수집하는 데이터를 통해 조직에서 제공하는 컨트롤에 대해 Insiten에서 제공했습니다.

#### <a name="data-access-using-microsoft-graph"></a>Microsoft 365를 사용한 데이터 Graph

이 앱에 [Graph Microsoft 사용자 권한을](https://docs.microsoft.com/graph/permissions-reference) 나열합니다.

>| **사용 권한**  | **사용 권한 유형(위임/ 응용 프로그램)** | **데이터가 수집하나요? 수집의 사당성** | **데이터가 저장되어 있나요? 저장 사정이 있나요?** | **Azure AD 앱 ID** |
>|:----------------|:------------------------------------------------|:--------------------------------------------------------|:--------------------------------------------------|:--------------------|
>| Files.ReadWrite.All | 위임 | 사용자가 드라이브, 폴더 OneDrive 찾아볼 수 있습니다. TackleBox에 파일 링크 차트Excel, 표, 인쇄 영역 및 명명된 범위의 자동 추출을 위해 파일 읽기 이러한 PowerPoint 시각적으로 파일 만들기 및 Excel 업데이트 | 드라이브 ID, 폴더 ID, 파일 ID, 링크 보기, 만든 날짜, 수정한 날짜, 수정한 날짜, 버전 ID, 파일 이름 | [485936ec-d15d-4a17-9f7d-2eeb5ea43b94](https://docs.microsoft.com/microsoft-365-app-certification/azure/485936ec-d15d-4a17-9f7d-2eeb5ea43b94) |
>| Sites.Read.All | 위임 | 사용자가 개인 Excel 채널에 있는 파일을 찾아서 연결하도록 Teams 수 있습니다. | 없음 | [485936ec-d15d-4a17-9f7d-2eeb5ea43b94](https://docs.microsoft.com/microsoft-365-app-certification/azure/485936ec-d15d-4a17-9f7d-2eeb5ea43b94) |
>| User.Read | 위임 | 앱에서 로그인한 사용자의 프로필을 읽고 알림에 대한 전자 메일 주소를 읽습니다. | 전자 메일 | [485936ec-d15d-4a17-9f7d-2eeb5ea43b94](https://docs.microsoft.com/microsoft-365-app-certification/azure/485936ec-d15d-4a17-9f7d-2eeb5ea43b94) |
>| openid | 위임 | 사용자가 계정으로 응용 프로그램에 로그인할 Microsoft 365 있습니다. | 사용자의 테넌트 ID 및 개체 ID | [485936ec-d15d-4a17-9f7d-2eeb5ea43b94](https://docs.microsoft.com/microsoft-365-app-certification/azure/485936ec-d15d-4a17-9f7d-2eeb5ea43b94) |
>| profile | 위임 | 앱에서 사용자의 기본 프로필(이름, 사용자 이름)을 표시하여 공동 작업을 표시하도록 허용합니다. | UPN, 이름, 성 | [485936ec-d15d-4a17-9f7d-2eeb5ea43b94](https://docs.microsoft.com/microsoft-365-app-certification/azure/485936ec-d15d-4a17-9f7d-2eeb5ea43b94) |


#### <a name="non-microsoft-services-used"></a>비영구 Microsoft 서비스

앱이 Microsoft가 아닌 서비스로 조직 데이터를 전송하거나 공유하는 경우 앱에서 사용하는 비 Microsoft 서비스, 전송되는 데이터를 나열하고 앱이 이 정보를 전송해야 하는 이유에 대한 사유를 포함합니다.

>비영구 Microsoft 서비스 사용되지 않습니다.

#### <a name="data-access-via-bots"></a>봇을 통한 데이터 액세스

이 앱에 봇 또는 메시징 확장이 포함되어 있는 경우 팀 구성원의 명단(이름, 성, 표시 이름, 전자 메일 주소)이나 팀 구성원이 추가된 채팅의 최종 사용자 식별 정보(EUII)에 액세스할 수 있습니다. 이 앱이 이 기능을 사용하나요?

>EUII에 액세스하지 않습니다.


#### <a name="telemetry-data"></a>원격 분석 데이터

이 응용 프로그램의 원격 분석 또는 로그에 OII(조직 식별 정보) 또는 EUII(최종 사용자 식별 정보)가 나타나나요? 그렇다면 저장되는 데이터와 보존 및 제거 정책에 대해 설명하세요.

>전자 메일 주소 및 계정 이름입니다. 비활성화된 계정 및 연결된 사용자 세부 정보는 3개월 후에 제거됩니다.

#### <a name="organizational-controls-for-data-stored-by-partner"></a>파트너가 저장한 데이터에 대한 조직 제어

조직의 관리자가 파트너 시스템에서 정보를 제어하는 방법에 대해 설명하는 방법 삭제, 보존, 감사, 보관, 최종 사용자 정책 등

>해당되지 않습니다. 모든 데이터가 Microsoft Azure

#### <a name="human-review-of-organizational-information"></a>조직 정보의 인적 검토

사람이 이 앱에서 수집하거나 저장하는 OII(조직 식별 정보) 데이터를 검토하거나 분석하는 데 관여하나요?

>아니요

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="mcas"

Microsoft Cloud App Security [카탈로그의](https://www.microsoft.com/enterprise-mobility-security/cloud-app-security) 정보가 아래에 표시됩니다.

<iframe height='1020' title='Microsoft Cloud App Security 정보' src='https://appmcasinfoprod.azurewebsites.net/#/dashboard/35957' frameborder='no' style='width: 100%;'></iframe>

<a href="https://appmcasinfoprod.azurewebsites.net/#/dashboard/35957" target="_blank">새 탭에서 보기</a>

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="identity"

### <a name="identity-information"></a>ID 정보

이 정보는 Insiten에서 이 앱이 인증, 권한 부여, 응용 프로그램 등록 모범 사례 및 기타 ID 조건을 처리하는 방법에 대해 제공했습니다.

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
| 앱에서 웹 API를 노출하나요? | 예 |
| 사용 권한 모델에서 클라이언트 앱이 적절한 동의를 받은 경우 통화 성공만 허용하나요? | 예 |
| 앱에서 미리 보기 API를 사용하나요? | 아니요 |
| 앱에서 사용되지 않는 API를 사용하나요? | 아니요 |

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end
