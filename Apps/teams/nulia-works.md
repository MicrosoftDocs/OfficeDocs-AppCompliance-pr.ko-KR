---
title: Nulia의 Nulia 저작물에 대한 응용 프로그램 정보
ms.author: elmalova
author: elenamalova
ms.date: 03/11/2021
ms.topic: article
ms.service: attestation
certification_type: attested
description: Nulia Works의 모든 사용 가능한 보안 및 규정 준수 정보 정보, 데이터 처리 정책, Microsoft Cloud App Security 앱 카탈로그 정보 및 CSA STAR 레지스트리의 보안/규정 준수 정보.
zone_pivot_groups: app-info-data-mcas-identity
ms.openlocfilehash: 4471074b2e15b41894f709cb2a25dee1d0dc5187
ms.sourcegitcommit: a44420a99a1a3a9d0e49f4be66f266e2d4ca7bbb
ms.translationtype: MT
ms.contentlocale: ko-KR
ms.lasthandoff: 05/19/2021
ms.locfileid: "52552899"
---
# <a name="nulia-works"></a>Nulia Works

<p></p>
<img alt="Publisher Attestation: The information on this page is based on a self-assessment report provided by the app developer on the security, compliance, and data handling practices followed by this app. Microsoft makes no guarantees regarding the accuracy of the information." src="../media/attested.png" width="650" />
<p>최종 업데이트: 2021년 3월 11일</p>

* <a href="https://teams.microsoft.com/l/app/e49e0f69-600c-460c-80b3-8809a9d97a4c" target="_blank">Teams 스토어에서 보기</a>
* <a href="https://appsource.microsoft.com/product/office/WA200002051" target="_blank">앱소스에서 보기</a>

::: zone pivot="general"

### <a name="general-information"></a>일반 정보

Nulia에서 Microsoft에 제공한 정보:

| **정보** | **응답** |
|:----------------|:-------------|
| 앱 이름 | Nulia Works |
| ID | WA200002051 |
| 지원되는 Office 365 클라이언트 | Microsoft Teams |
| 파트너 회사 이름 | Nulia |
| 파트너 웹사이트의 URL | [https://nulia.com](https://nulia.com) |
| Teams 응용 프로그램 정보 페이지의 URL | [https://nulia.com/product](https://nulia.com/product) |
| 개인정보 처리방침의 URL | [https://nulia.com/privacy](https://nulia.com/privacy) |
| 이용 약관의 URL | [https://nulia.com/terms](https://nulia.com/terms) |

 [!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="data"

### <a name="how-the-app-handles-data"></a>앱이 데이터를 처리하는 방법

이 정보는 Nulia에서 이 앱이 조직 데이터를 수집하고 저장하는 방법과 앱이 수집하는 데이터에 대한 조직이 가질 수 있는 제어에 대해 제공했습니다.

#### <a name="data-access-using-microsoft-graph"></a>Microsoft Graph 을 사용하여 데이터 액세스

이 [앱에서 필요한 Microsoft Graph 권한을 나열합니다.](https://docs.microsoft.com/graph/permissions-reference)

>| **사용 권한**  | **권한 유형(위임/응용 프로그램)** | **데이터가 수집되고 있습니까? 그것을 수집하기위한 정당화?** | **데이터가 저장되어 있습니까? 그것을 저장하는 정당화?** | **Azure AD 앱 ID** |
>|:----------------|:--------------------|:---------------------------------------------------|:--------------------------|:--------------------------|
>| Calendars.Read | 신청 | 수집된 데이터를 사용하여 기술 및 결과에 대한 사용자 진행 상황을 평가합니다. 우리는 여러 O365 워크로드에 걸쳐 사용 수를 수집합니다. | 우리는 우리가 수집하는 모든 데이터를 Blob 스토리지에 저장합니다. 이 데이터를 사용하여 기술 및 결과 진행 상황을 사용자에게 점수를 매습니다. 예를 들어 사용자가 가지고 있는 캘린더 이벤트 수를 계산합니다. 그 값은 기술 진행 에 영향을 미칩니다. | 각 고객에 대한 새 응용 프로그램 ID를 만듭니다. 예를 들어, 우리의 Nulia 테넌트는 응용 프로그램 ID를 사용하고 있습니다 : 623B1D5D-6D82-493E-9990-1FBFE82ED046 |
>| 연락처.읽기 | 신청 | 수집된 데이터를 사용하여 기술 및 결과에 대한 사용자 진행 상황을 평가합니다. 우리는 여러 O365 워크로드에 걸쳐 사용 수를 수집합니다. | 우리는 우리가 수집하는 모든 데이터를 Blob 스토리지에 저장합니다. 이 데이터를 사용하여 기술 및 결과 진행 상황을 사용자에게 점수를 매습니다. 예를 들어 사용자가 만든 연락처 수를 계산합니다. 그 값은 기술 진행 에 영향을 미칩니다. | 각 고객에 대한 새 응용 프로그램 ID를 만듭니다. 예를 들어, 우리의 Nulia 테넌트는 응용 프로그램 ID를 사용하고 있습니다 : 623B1D5D-6D82-493E-9990-1FBFE82ED046 |
>| Files.Read.All | 신청 | 수집된 데이터를 사용하여 기술 및 결과에 대한 사용자 진행 상황을 평가합니다. 우리는 여러 O365 워크로드에 걸쳐 사용 수를 수집합니다. | 우리는 우리가 수집하는 모든 데이터를 Blob 스토리지에 저장합니다. 이 데이터를 사용하여 기술 및 결과 진행 상황을 사용자에게 점수를 매습니다. 예를 들어 사용자가 컴퓨터와 동기화하는 파일 수를 계산합니다. 그 값은 기술 진행 에 영향을 미칩니다. | 각 고객에 대한 새 응용 프로그램 ID를 만듭니다. 예를 들어, 우리의 Nulia 테넌트는 응용 프로그램 ID를 사용하고 있습니다 : 623B1D5D-6D82-493E-9990-1FBFE82ED046 |
>| Group.Read.All | 신청 | 수집된 데이터를 사용하여 기술 및 결과에 대한 사용자 진행 상황을 평가합니다. 우리는 여러 O365 워크로드에 걸쳐 사용 수를 수집합니다. | 우리는 우리가 수집하는 모든 데이터를 Blob 스토리지에 저장합니다. 이 데이터를 사용하여 기술 및 결과 진행 상황을 사용자에게 점수를 매습니다. 예를 들어 그룹에서 사용자가 속한 Teams 수를 검색합니다. 그 값은 기술 진행 에 영향을 미칩니다. | 각 고객에 대한 새 응용 프로그램 ID를 만듭니다. 예를 들어, 우리의 Nulia 테넌트는 응용 프로그램 ID를 사용하고 있습니다 : 623B1D5D-6D82-493E-9990-1FBFE82ED046 |
>| Mail.Read | 신청 | 수집된 데이터를 사용하여 기술 및 결과에 대한 사용자 진행 상황을 평가합니다. 우리는 여러 O365 워크로드에 걸쳐 사용 수를 수집합니다. | 우리는 우리가 수집하는 모든 데이터를 Blob 스토리지에 저장합니다. 이 데이터를 사용하여 기술 및 결과 진행 상황을 사용자에게 점수를 매습니다. 예를 들어 사용자가 만든 사용자 지정 메일 폴더 수를 계산합니다. 그 값은 기술 진행 에 영향을 미칩니다. | 각 고객에 대한 새 응용 프로그램 ID를 만듭니다. 예를 들어, 우리의 Nulia 테넌트는 응용 프로그램 ID를 사용하고 있습니다 : 623B1D5D-6D82-493E-9990-1FBFE82ED046 |
>| 사서함 설정.읽기 | 신청 | 수집된 데이터를 사용하여 기술 및 결과에 대한 사용자 진행 상황을 평가합니다. 우리는 여러 O365 워크로드에 걸쳐 사용 수를 수집합니다. | 우리는 우리가 수집하는 모든 데이터를 Blob 스토리지에 저장합니다. 이 데이터를 사용하여 기술 및 결과 진행 상황을 사용자에게 점수를 매습니다. 예를 들어 사용자가 사무실 외 회신 집합이 있는지 확인합니다. 그 값은 기술 진행 에 영향을 미칩니다. | 각 고객에 대한 새 응용 프로그램 ID를 만듭니다. 예를 들어, 우리의 Nulia 테넌트는 응용 프로그램 ID를 사용하고 있습니다 : 623B1D5D-6D82-493E-9990-1FBFE82ED046 |
>| 참고.읽기 | 신청 | 수집된 데이터를 사용하여 기술 및 결과에 대한 사용자 진행 상황을 평가합니다. 우리는 여러 O365 워크로드에 걸쳐 사용 수를 수집합니다. | 우리는 우리가 수집하는 모든 데이터를 Blob 스토리지에 저장합니다. 이 데이터를 사용하여 기술 및 결과 진행 상황을 사용자에게 점수를 매습니다. 예를 들어 사용자가 공유한 전자 필기장 수를 계산합니다. 그 값은 기술 진행 에 영향을 미칩니다. | 각 고객에 대한 새 응용 프로그램 ID를 만듭니다. 예를 들어, 우리의 Nulia 테넌트는 응용 프로그램 ID를 사용하고 있습니다 : 623B1D5D-6D82-493E-9990-1FBFE82ED046 |
>| 보고서.읽기.모든 것 | 신청 | 수집된 데이터를 사용하여 기술 및 결과에 대한 사용자 진행 상황을 평가합니다. 우리는 여러 O365 워크로드에 걸쳐 사용 수를 수집합니다. | 우리는 우리가 수집하는 모든 데이터를 Blob 스토리지에 저장합니다. 이 데이터를 사용하여 기술 및 결과 진행 상황을 사용자에게 점수를 매습니다. 예를 들어 사용자가 하루에 보낸 Teams 메시지 수를 보고합니다. 그 값은 기술 진행 에 영향을 미칩니다. | 각 고객에 대한 새 응용 프로그램 ID를 만듭니다. 예를 들어, 우리의 Nulia 테넌트는 응용 프로그램 ID를 사용하고 있습니다 : 623B1D5D-6D82-493E-9990-1FBFE82ED046 |
>| Sites.Read.All | 신청 | 수집된 데이터를 사용하여 기술 및 결과에 대한 사용자 진행 상황을 평가합니다. 우리는 여러 O365 워크로드에 걸쳐 사용 수를 수집합니다. | 우리는 우리가 수집하는 모든 데이터를 Blob 스토리지에 저장합니다. 이 데이터를 사용하여 기술 및 결과 진행 상황을 사용자에게 점수를 매습니다. 예를 들어 사용자가 만든 사이트 모음 수를 계산합니다. 그 값은 기술 진행 에 영향을 미칩니다. | 각 고객에 대한 새 응용 프로그램 ID를 만듭니다. 예를 들어, 우리의 Nulia 테넌트는 응용 프로그램 ID를 사용하고 있습니다 : 623B1D5D-6D82-493E-9990-1FBFE82ED046 |
>| User.Read | 신청 | 사용자의 표시 이름, 부서 및 프로필 사진을 표시합니다. | 데이터베이스에서 디스플레이 이름과 부서를 저장하므로 매번 Graph 공격할 필요가 없습니다. 프로필 사진은 저장하지 않습니다. | 각 고객에 대한 새 응용 프로그램 ID를 만듭니다. 예를 들어, 우리의 Nulia 테넌트는 응용 프로그램 ID를 사용하고 있습니다 : 623B1D5D-6D82-493E-9990-1FBFE82ED046 |
>| 조직.읽기.모든 것 | 신청 | 테넌트의 이름과 기본 URL을 Yammer. 사용자가 &quot; Yammer 활동과 관련된 앱에서 Try It 버튼을 클릭하면 Yammer &quot; 시작합니다. | 우리는 우리가 수집하는 모든 데이터를 Blob 스토리지에 저장합니다. 예를 들어 사용자가 &quot; Yammer 활동과 관련된 앱에서 Try It 버튼을 클릭하면 Yammer &quot; 시작합니다. | 수집된 데이터를 사용하여 기술 및 결과에 대한 사용자 진행 상황을 평가합니다. 우리는 여러 O365 워크로드에 걸쳐 사용 수를 수집합니다. |


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

>파트너 시스템의 데이터를 제어하지 않습니다.

#### <a name="human-review-of-organizational-information"></a>조직 정보의 인간 검토

이 앱에서 수집하거나 저장되는 조직 식별 정보(OII) 데이터를 검토하거나 분석하는 데 관여하는 사람이 있습니까?

>아니요

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="mcas"

[Microsoft Cloud App Security](https://www.microsoft.com/enterprise-mobility-security/cloud-app-security) 카탈로그의 정보는 아래에 나타납니다.

<iframe height='1020' title='Microsoft Cloud App Security 정보' src='https://appmcasinfoprod.azurewebsites.net/#/dashboard/36557' frameborder='no' style='width: 100%;'></iframe>

<a href="https://appmcasinfoprod.azurewebsites.net/#/dashboard/36557" target="_blank">새 탭에서 보기</a>

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="identity"

### <a name="identity-information"></a>신원 정보

이 정보는 이 앱이 인증, 권한 부여, 응용 프로그램 등록 모범 사례 및 기타 ID 기준을 처리하는 방법에 대해 Nulia에서 제공했습니다.

| **정보** | **응답** |
|:----------------|:-------------|
| Microsoft 식별 플랫폼(Azure AD)과 통합합니까?  | 예 |
| Microsoft ID 플랫폼 통합 검사 목록에 설명된 모든 적용 가능한 모범 사례를 검토하고 준수했습니까?  | 예 |
| 앱에서 인증에 MSAL(Microsoft 인증 라이브러리)을 사용합니까? | 예 |
| 앱이 조건부 액세스 정책을 지원합니까? | 아니요 |
| 앱에서 시나리오에 대한 최소 권한 권한을 요청합니까? | 예 |
| 앱의 정적 등록 권한은 앱이 동적으로 점진적으로 요청하는 권한을 정확하게 반영합니까? | 예 |
| 앱이 다중 테넌션을 지원합니까? | 예 |
| 앱에 기밀 클라이언트가 있습니까? | 예 |
| 앱에 등록된 URI(리디렉션 통합 리소스 식별자)를 모두 소유하고 있습니까? | 예 |
| 앱의 경우 무엇을 사용하지 않으려습니까? | - 와일드카드 리디렉션 URI,<br/>- OAuth2 암시적 Flow, SPA에 필요한 경우가 아니면<br/>- 리소스 소유자 암호 자격 증명(ROPC) 흐름 |
| 앱에서 웹 API가 노출됩니까? | 예 |
| 권한 모델은 클라이언트 앱이 적절한 동의를 받는 경우에만 호출을 성공시킬 수 있습니까? | 예 |
| 앱에서 미리 보기 API를 사용합니까? | 아니요 |
| 앱에서 비하 API를 사용합니까? | 아니요 |

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end
