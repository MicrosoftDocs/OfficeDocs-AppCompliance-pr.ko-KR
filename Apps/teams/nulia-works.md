---
title: Nulia Works by Nulia의 응용 프로그램 정보
ms.author: elmalova
author: elenamalova
ms.date: 03/11/2021
ms.topic: article
ms.service: attestation
certification_type: attested
description: Nulia Works에 사용할 수 있는 모든 보안 및 규정 준수 정보, 데이터 처리 정책, CSA STAR 레지스트리의 Microsoft Cloud App Security 앱 카탈로그 정보 및 보안/규정 준수 정보
zone_pivot_groups: app-info-data-mcas-identity
ms.openlocfilehash: 4d176b18a8089d9107f30b7581bcca69daf0871e
ms.sourcegitcommit: d85595f6518d8d05f0aee75380f51659908b6bcb
ms.translationtype: MT
ms.contentlocale: ko-KR
ms.lasthandoff: 09/12/2021
ms.locfileid: "59288082"
---
# <a name="nulia-works"></a>Nulia Works

<p></p>
<img alt="Publisher Attestation: The information on this page is based on a self-assessment report provided by the app developer on the security, compliance, and data handling practices followed by this app. Microsoft makes no guarantees regarding the accuracy of the information." src="../media/attested.png" width="650" />
<p>개발자가 마지막으로 업데이트한 날짜: 2021년 3월 11일</p>

* <a href="https://teams.microsoft.com/l/app/e49e0f69-600c-460c-80b3-8809a9d97a4c" target="_blank">저장소의 Teams 보기</a>
* <a href="https://appsource.microsoft.com/product/office/WA200002051" target="_blank">AppSource의 보기</a>

::: zone pivot="general"

### <a name="general-information"></a>일반 정보

Nulia에서 Microsoft에 제공한 정보:

| **정보** | **응답** |
|:----------------|:-------------|
| 앱 이름 | Nulia Works |
| ID | WA200002051 |
| Office 365 클라이언트 지원 | Microsoft Teams |
| 파트너 회사 이름 | Nulia |
| 파트너 웹 사이트의 URL | [https://nulia.com](https://nulia.com) |
| 응용 프로그램 Teams 페이지의 URL입니다. | [https://nulia.com/product](https://nulia.com/product) |
| 개인 정보 취급 방침의 URL | [https://nulia.com/privacy](https://nulia.com/privacy) |
| 사용 약관 URL | [https://nulia.com/terms](https://nulia.com/terms) |

 [!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="data"

### <a name="how-the-app-handles-data"></a>앱이 데이터를 처리하는 방법

이 정보는 Nulia에서 이 앱이 조직 데이터를 수집하고 저장하는 방법 및 앱이 수집하는 데이터를 통해 조직에서 제공하는 컨트롤에 대해 제공됩니다.

#### <a name="data-access-using-microsoft-graph"></a>Microsoft 365를 사용한 데이터 Graph

이 앱에 [Graph Microsoft 사용자 권한을](https://docs.microsoft.com/graph/permissions-reference) 나열합니다.

>| **사용 권한**  | **사용 권한 유형(위임/ 응용 프로그램)** | **데이터가 수집하나요? 수집의 사당성** | **데이터가 저장되어 있나요? 저장 사정이 있나요?** | **Azure AD 앱 ID** |
>|:----------------|:------------------------------------------------|:--------------------------------------------------------|:--------------------------------------------------|:--------------------|
>| Calendars.Read | application | 수집된 데이터를 사용하여 기술 및 결과의 사용자 진행 상황을 점수로 넣습니다. 여러 O365 워크로드에서 사용 횟수를 수집합니다. | Blob 저장소에 수집하는 모든 데이터를 저장합니다. 이 데이터를 사용하여 기술 및 결과 진행률에 대한 사용자 점수를 제공합니다. 예를 들어 사용자가 가지는 일정 이벤트 수를 계산합니다. 이 값은 기술 진행률에 영향을 미치게 됩니다. | [각 고객에 대해 새 응용 프로그램 ID를 생성합니다. 예를 들어 Nulia 테넌트가 응용 프로그램 ID를 사용 중입니다. 623B1D5D-6D82-493E-9990-1FBFE82ED046](https://docs.microsoft.com/microsoft-365-app-certification/azure/We create a new application ID for each customer. For example, our Nulia tenant is using application ID: 623B1D5D-6D82-493E-9990-1FBFE82ED046) |
>| Contacts.Read | application | 수집된 데이터를 사용하여 기술 및 결과의 사용자 진행 상황을 점수로 넣습니다. 여러 O365 워크로드에서 사용 횟수를 수집합니다. | Blob 저장소에 수집하는 모든 데이터를 저장합니다. 이 데이터를 사용하여 기술 및 결과 진행률에 대한 사용자 점수를 제공합니다. 예를 들어 사용자가 만든 연락처 수를 계산합니다. 이 값은 기술 진행률에 영향을 미치게 됩니다. | [각 고객에 대해 새 응용 프로그램 ID를 생성합니다. 예를 들어 Nulia 테넌트가 응용 프로그램 ID를 사용 중입니다. 623B1D5D-6D82-493E-9990-1FBFE82ED046](https://docs.microsoft.com/microsoft-365-app-certification/azure/We create a new application ID for each customer. For example, our Nulia tenant is using application ID: 623B1D5D-6D82-493E-9990-1FBFE82ED046) |
>| Files.Read.All | application | 수집된 데이터를 사용하여 기술 및 결과의 사용자 진행 상황을 점수로 넣습니다. 여러 O365 워크로드에서 사용 횟수를 수집합니다. | Blob 저장소에 수집하는 모든 데이터를 저장합니다. 이 데이터를 사용하여 기술 및 결과 진행률에 대한 사용자 점수를 제공합니다. 예를 들어 사용자가 컴퓨터와 동기화하는 파일의 수를 계산합니다. 이 값은 기술 진행률에 영향을 미치게 됩니다. | [각 고객에 대해 새 응용 프로그램 ID를 생성합니다. 예를 들어 Nulia 테넌트가 응용 프로그램 ID를 사용 중입니다. 623B1D5D-6D82-493E-9990-1FBFE82ED046](https://docs.microsoft.com/microsoft-365-app-certification/azure/We create a new application ID for each customer. For example, our Nulia tenant is using application ID: 623B1D5D-6D82-493E-9990-1FBFE82ED046) |
>| Group.Read.All | application | 수집된 데이터를 사용하여 기술 및 결과의 사용자 진행 상황을 점수로 넣습니다. 여러 O365 워크로드에서 사용 횟수를 수집합니다. | Blob 저장소에 수집하는 모든 데이터를 저장합니다. 이 데이터를 사용하여 기술 및 결과 진행률에 대한 사용자 점수를 제공합니다. 예를 들어 사용자가 속한 Teams 그룹에서 검색합니다. 이 값은 기술 진행률에 영향을 미치게 됩니다. | [각 고객에 대해 새 응용 프로그램 ID를 생성합니다. 예를 들어 Nulia 테넌트가 응용 프로그램 ID를 사용 중입니다. 623B1D5D-6D82-493E-9990-1FBFE82ED046](https://docs.microsoft.com/microsoft-365-app-certification/azure/We create a new application ID for each customer. For example, our Nulia tenant is using application ID: 623B1D5D-6D82-493E-9990-1FBFE82ED046) |
>| Mail.Read | application | 수집된 데이터를 사용하여 기술 및 결과의 사용자 진행 상황을 점수로 넣습니다. 여러 O365 워크로드에서 사용 횟수를 수집합니다. | Blob 저장소에 수집하는 모든 데이터를 저장합니다. 이 데이터를 사용하여 기술 및 결과 진행률에 대한 사용자 점수를 제공합니다. 예를 들어 사용자가 만든 사용자 지정 메일 폴더의 수를 계산합니다. 이 값은 기술 진행률에 영향을 미치게 됩니다. | [각 고객에 대해 새 응용 프로그램 ID를 생성합니다. 예를 들어 Nulia 테넌트가 응용 프로그램 ID를 사용 중입니다. 623B1D5D-6D82-493E-9990-1FBFE82ED046](https://docs.microsoft.com/microsoft-365-app-certification/azure/We create a new application ID for each customer. For example, our Nulia tenant is using application ID: 623B1D5D-6D82-493E-9990-1FBFE82ED046) |
>| MailboxSettings.Read | application | 수집된 데이터를 사용하여 기술 및 결과의 사용자 진행 상황을 점수로 넣습니다. 여러 O365 워크로드에서 사용 횟수를 수집합니다. | Blob 저장소에 수집하는 모든 데이터를 저장합니다. 이 데이터를 사용하여 기술 및 결과 진행률에 대한 사용자 점수를 제공합니다. 예를 들어 사용자에게 부재 중 회신 집합이 있는 경우를 볼 수 있습니다. 이 값은 기술 진행률에 영향을 미치게 됩니다. | [각 고객에 대해 새 응용 프로그램 ID를 생성합니다. 예를 들어 Nulia 테넌트가 응용 프로그램 ID를 사용 중입니다. 623B1D5D-6D82-493E-9990-1FBFE82ED046](https://docs.microsoft.com/microsoft-365-app-certification/azure/We create a new application ID for each customer. For example, our Nulia tenant is using application ID: 623B1D5D-6D82-493E-9990-1FBFE82ED046) |
>| Notes.Read | application | 수집된 데이터를 사용하여 기술 및 결과의 사용자 진행 상황을 점수로 넣습니다. 여러 O365 워크로드에서 사용 횟수를 수집합니다. | Blob 저장소에 수집하는 모든 데이터를 저장합니다. 이 데이터를 사용하여 기술 및 결과 진행률에 대한 사용자 점수를 제공합니다. 예를 들어 사용자가 공유한 전자 필기장 수를 계산합니다. 이 값은 기술 진행률에 영향을 미치게 됩니다. | [각 고객에 대해 새 응용 프로그램 ID를 생성합니다. 예를 들어 Nulia 테넌트가 응용 프로그램 ID를 사용 중입니다. 623B1D5D-6D82-493E-9990-1FBFE82ED046](https://docs.microsoft.com/microsoft-365-app-certification/azure/We create a new application ID for each customer. For example, our Nulia tenant is using application ID: 623B1D5D-6D82-493E-9990-1FBFE82ED046) |
>| Reports.Read.All | application | 수집된 데이터를 사용하여 기술 및 결과의 사용자 진행 상황을 점수로 넣습니다. 여러 O365 워크로드에서 사용 횟수를 수집합니다. | Blob 저장소에 수집하는 모든 데이터를 저장합니다. 이 데이터를 사용하여 기술 및 결과 진행률에 대한 사용자 점수를 제공합니다. 예를 들어 사용자 보고서에서 하루 동안 보낸 Teams 수를 보고합니다. 이 값은 기술 진행률에 영향을 미치게 됩니다. | [각 고객에 대해 새 응용 프로그램 ID를 생성합니다. 예를 들어 Nulia 테넌트가 응용 프로그램 ID를 사용 중입니다. 623B1D5D-6D82-493E-9990-1FBFE82ED046](https://docs.microsoft.com/microsoft-365-app-certification/azure/We create a new application ID for each customer. For example, our Nulia tenant is using application ID: 623B1D5D-6D82-493E-9990-1FBFE82ED046) |
>| Sites.Read.All | application | 수집된 데이터를 사용하여 기술 및 결과의 사용자 진행 상황을 점수로 넣습니다. 여러 O365 워크로드에서 사용 횟수를 수집합니다. | Blob 저장소에 수집하는 모든 데이터를 저장합니다. 이 데이터를 사용하여 기술 및 결과 진행률에 대한 사용자 점수를 제공합니다. 예를 들어 사용자가 만든 사이트 모음의 수를 계산합니다. 이 값은 기술 진행률에 영향을 미치게 됩니다. | [각 고객에 대해 새 응용 프로그램 ID를 생성합니다. 예를 들어 Nulia 테넌트가 응용 프로그램 ID를 사용 중입니다. 623B1D5D-6D82-493E-9990-1FBFE82ED046](https://docs.microsoft.com/microsoft-365-app-certification/azure/We create a new application ID for each customer. For example, our Nulia tenant is using application ID: 623B1D5D-6D82-493E-9990-1FBFE82ED046) |
>| User.Read | application | 사용자의 표시 이름, 부서 및 프로필 사진을 표시합니다. | 매월 표시 이름 및 부서를 데이터베이스에 저장하여 매 Graph 않습니다. 프로필 사진은 저장하지 않습니다. | [각 고객에 대해 새 응용 프로그램 ID를 생성합니다. 예를 들어 Nulia 테넌트가 응용 프로그램 ID를 사용 중입니다. 623B1D5D-6D82-493E-9990-1FBFE82ED046](https://docs.microsoft.com/microsoft-365-app-certification/azure/We create a new application ID for each customer. For example, our Nulia tenant is using application ID: 623B1D5D-6D82-493E-9990-1FBFE82ED046) |
>| Organization.Read.All | application | 테넌트의 이름과 기본 YAMMER 수집합니다. 이 기능을 사용하여 Yammer 활동과 관련된 앱에서 Try It(시도) 단추를 클릭하면 Yammer &quot; &quot; 실행됩니다. | Blob 저장소에 수집하는 모든 데이터를 저장합니다. 예를 들어 이 기능을 사용하여 Yammer 활동과 관련된 앱에서 시도 단추를 클릭할 때 Yammer &quot; &quot; 실행합니다. | [수집된 데이터를 사용하여 기술 및 결과의 사용자 진행 상황을 점수로 넣습니다. 여러 O365 워크로드에서 사용 횟수를 수집합니다.](https://docs.microsoft.com/microsoft-365-app-certification/azure/We use the data collected to score user progress on skills and Outcomes. We collect usage counts across multiple O365 workloads.) |


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

>파트너 시스템에서는 데이터를 제어하지 않습니다.

#### <a name="human-review-of-organizational-information"></a>조직 정보의 인적 검토

사람이 이 앱에서 수집하거나 저장하는 OII(조직 식별 정보) 데이터를 검토하거나 분석하는 데 관여하나요?

>아니요

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="mcas"

Microsoft Cloud App Security [카탈로그의](https://www.microsoft.com/enterprise-mobility-security/cloud-app-security) 정보가 아래에 표시됩니다.

<iframe height='1020' title='Microsoft Cloud App Security 정보' src='https://appmcasinfoprod.azurewebsites.net/#/dashboard/36557' frameborder='no' style='width: 100%;'></iframe>

<a href="https://appmcasinfoprod.azurewebsites.net/#/dashboard/36557" target="_blank">새 탭에서 보기</a>

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="identity"

### <a name="identity-information"></a>ID 정보

이 정보는 Nulia에서 이 앱이 인증, 권한 부여, 응용 프로그램 등록 모범 사례 및 기타 ID 조건을 처리하는 방법에 대해 제공했습니다.

| **정보** | **응답** |
|:----------------|:-------------|
| Microsoft Identify Platform(Azure AD)과 통합하나요?  | 예 |
| 통합 검사 목록에 설명된 적용 가능한 모든 모범 사례를 Microsoft ID 플랫폼 준수하나요?  | 예 |
| 앱에서 인증에 MSAL(Microsoft 인증 라이브러리)을 사용하나요? | 예 |
| 앱에서 조건부 액세스 정책을 지원하나요? | 아니요 |
| 앱에서 시나리오에 대한 최소 권한 권한을 요청하나요? | 예 |
| 앱의 정적으로 등록된 사용 권한은 앱이 동적으로 그리고 증분적으로 요청하는 권한을 정확하게 반영하나요? | 예 |
| 앱에서 다중 테넌시를 지원하나요? | 예 |
| 앱에 기밀 클라이언트가 있나요? | 예 |
| 앱에 등록된 리디렉션 URI(통합 리소스 식별자)를 모두 소유하고 있나요? | 예 |
| 앱의 경우 어떻게 사용하지 않도록 해야 하나요? | - 와일드카드 리디렉션 URIS,<br/>- OAuth2 암시적 Flow SPA에 필요하지 않은 경우<br/>- 리소스 소유자 암호 자격 증명(ROPC) 흐름 |
| 앱에서 웹 API를 노출하나요? | 예 |
| 사용 권한 모델에서 클라이언트 앱이 적절한 동의를 받은 경우 통화 성공만 허용하나요? | 예 |
| 앱에서 미리 보기 API를 사용하나요? | 아니요 |
| 앱에서 사용되지 않는 API를 사용하나요? | 아니요 |

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end
