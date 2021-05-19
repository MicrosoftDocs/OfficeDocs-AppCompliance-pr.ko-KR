---
title: 인사이트앤드에 의해 태클 박스에 대한 응용 프로그램 정보
ms.author: elmalova
author: elenamalova
ms.date: 01/12/2021
ms.topic: article
ms.service: attestation
certification_type: attested
description: TackleBox에 대한 사용 가능한 모든 보안 및 규정 준수 정보 정보, 데이터 처리 정책, Microsoft Cloud App Security 앱 카탈로그 정보 및 CSA STAR 레지스트리의 보안/규정 준수 정보.
zone_pivot_groups: app-info-data-mcas-identity
ms.openlocfilehash: 6d521b6172e4915d6ce10ea493069355ce3abfdf
ms.sourcegitcommit: a44420a99a1a3a9d0e49f4be66f266e2d4ca7bbb
ms.translationtype: MT
ms.contentlocale: ko-KR
ms.lasthandoff: 05/19/2021
ms.locfileid: "52552069"
---
# <a name="tacklebox"></a>TackleBox

<p></p>
<img alt="Publisher Attestation: The information on this page is based on a self-assessment report provided by the app developer on the security, compliance, and data handling practices followed by this app. Microsoft makes no guarantees regarding the accuracy of the information." src="../media/attested.png" width="650" />
<p>최종 업데이트: 2021년 1월 12일</p>

* <a href="https://teams.microsoft.com/l/app/dc37dab6-b497-4259-9aad-e40bfa023796" target="_blank">Teams 스토어에서 보기</a>
* <a href="https://appsource.microsoft.com/product/office/WA200002310" target="_blank">앱소스에서 보기</a>

::: zone pivot="general"

### <a name="general-information"></a>일반 정보

인사이트른에서 마이크로소프트에 제공한 정보:

| **정보** | **응답** |
|:----------------|:-------------|
| 앱 이름 | TackleBox |
| ID | WA200002310 |
| 지원되는 Office 365 클라이언트 | Microsoft Teams |
| 파트너 회사 이름 | Insiten |
| 파트너 웹사이트의 URL | [https://tacklebox.app/](https://tacklebox.app/) |
| Teams 응용 프로그램 정보 페이지의 URL | [https://tacklebox.app](https://tacklebox.app) |
| 개인정보 처리방침의 URL | [https://tacklebox.app/privacy/](https://tacklebox.app/privacy/) |
| 이용 약관의 URL | [https://tacklebox.app/terms/](https://tacklebox.app/terms/) |

 [!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="data"

### <a name="how-the-app-handles-data"></a>앱이 데이터를 처리하는 방법

이 정보는 Insiten에서 이 앱이 조직 데이터를 수집하고 저장하는 방법과 앱이 수집하는 데이터에 대한 조직이 가질 수 있는 제어에 대해 제공했습니다.

#### <a name="data-access-using-microsoft-graph"></a>Microsoft Graph 을 사용하여 데이터 액세스

이 [앱에서 필요한 Microsoft Graph 권한을 나열합니다.](https://docs.microsoft.com/graph/permissions-reference)

>| **사용 권한**  | **권한 유형(위임/응용 프로그램)** | **데이터가 수집되고 있습니까? 그것을 수집하기위한 정당화?** | **데이터가 저장되어 있습니까? 그것을 저장하는 정당화?** | **Azure AD 앱 ID** |
>|:----------------|:--------------------|:---------------------------------------------------|:--------------------------|:--------------------------|
>| Files.ReadWrite.All | 위임 | 사용자가 OneDrive 드라이브, 폴더 및 파일을 탐색할 수 있습니다. 파일을 태클박스에 연결합니다. 차트, 그래프, 테이블, 인쇄 영역 및 명명된 범위를 자동 추출하기 위해 파일을 Excel 읽는다. 이러한 Excel 시각적 개체로 PowerPoint 파일 만들기 및 업데이트 | 드라이브 ID, 폴더 ID, 파일 ID, 보기 링크, 생성됨, 생성된 날짜, 수정된 날짜, 버전 ID, 파일 이름 | 485936ec-d15d-4a17-9f7d-2eeb5ea43b94 |
>| Sites.Read.All | 위임 | 사용자가 개인 Teams 채널에 있는 Excel 파일을 찾아보고 연결할 수 있도록 허용 | 없음 | 485936ec-d15d-4a17-9f7d-2eeb5ea43b94 |
>| User.Read | 위임 | 앱이 로그인한 사용자의 프로필을 읽고 알림을 위해 이메일 주소를 다시 볼 수 있습니다. | 전자 메일 | 485936ec-d15d-4a17-9f7d-2eeb5ea43b94 |
>| 오픈 ID | 위임 | 사용자가 Microsoft 365 계정을 사용하여 응용 프로그램에 로그인할 수 있습니다. | 사용자를 위한 테넌트 ID 및 개체 ID | 485936ec-d15d-4a17-9f7d-2eeb5ea43b94 |
>| 윤곽 | 위임 | 앱이 사용자의 기본 프로필(이름, 사용자 이름)을 표시하여 공동 작업을 용이하게 할 수 있습니다. | UPN, 이름, 성, 이름, | 485936ec-d15d-4a17-9f7d-2eeb5ea43b94 |


#### <a name="non-microsoft-services-used"></a>사용되지 Microsoft 서비스

앱이 Microsoft 가 아닌 서비스와 조직 데이터를 전송하거나 공유하는 경우 앱에서 사용하는 비Microsoft 서비스, 전송되는 데이터를 나열하고 앱이 이 정보를 전송해야 하는 이유에 대한 명분을 포함합니다.

>비Microsoft 서비스 사용되지 않습니다.

#### <a name="data-access-via-bots"></a>봇을 통한 데이터 액세스

이 앱에 봇 또는 메시징 확장 프로그램이 포함된 경우 최종 사용자 식별 정보(EUII): 팀의 모든 팀 구성원의 명단(이름, 성, 표시 이름, 이메일 주소)에 액세스하거나 추가된 채팅을 할 수 있습니다. 이 응용 프로그램은이 기능을 사용합니까?

>EUII에 액세스할 수 없습니다.


#### <a name="telemetry-data"></a>원격 분석 데이터

조직 식별 정보(OII) 또는 최종 사용자 식별 정보(EUII)가 이 응용 프로그램의 원격 분석 또는 로그에 표시됩니까? 그렇다면 저장되는 데이터와 보존 및 제거 정책은 무엇입니까?

>이메일 주소 및 계정 이름입니다. 비활성화된 계정 및 관련 사용자 세부 정보는 3개월 후에 제거됩니다.

#### <a name="organizational-controls-for-data-stored-by-partner"></a>파트너가 저장한 데이터에 대한 조직 제어

조직의 관리자가 파트너 시스템에서 자신의 정보를 제어하는 방법을 설명해 보세요. 예를 들어 삭제, 보존, 감사, 보관, 최종 사용자 정책 등

>적용 할 수 없습니다 - 모든 데이터는 Microsoft Azure 저장됩니다.

#### <a name="human-review-of-organizational-information"></a>조직 정보의 인간 검토

이 앱에서 수집하거나 저장되는 조직 식별 정보(OII) 데이터를 검토하거나 분석하는 데 관여하는 사람이 있습니까?

>아니요

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="mcas"

[Microsoft Cloud App Security](https://www.microsoft.com/enterprise-mobility-security/cloud-app-security) 카탈로그의 정보는 아래에 나타납니다.

<iframe height='1020' title='Microsoft Cloud App Security 정보' src='https://appmcasinfoprod.azurewebsites.net/#/dashboard/35957' frameborder='no' style='width: 100%;'></iframe>

<a href="https://appmcasinfoprod.azurewebsites.net/#/dashboard/35957" target="_blank">새 탭에서 보기</a>

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="identity"

### <a name="identity-information"></a>신원 정보

이 정보는 이 앱이 인증, 권한 부여, 응용 프로그램 등록 모범 사례 및 기타 ID 기준을 처리하는 방법에 대해 Insiten에서 제공했습니다.

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
| 앱에서 웹 API가 노출됩니까? | 예 |
| 권한 모델은 클라이언트 앱이 적절한 동의를 받는 경우에만 호출을 성공시킬 수 있습니까? | 예 |
| 앱에서 미리 보기 API를 사용합니까? | 아니요 |
| 앱에서 비하 API를 사용합니까? | 아니요 |

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end
