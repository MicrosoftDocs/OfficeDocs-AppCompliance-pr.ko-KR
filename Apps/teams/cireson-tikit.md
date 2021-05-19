---
title: 순환에 의해 티킷에 대한 응용 프로그램 정보
ms.author: elmalova
author: elenamalova
ms.date: 03/11/2021
ms.topic: article
ms.service: attestation
certification_type: attested
description: Tikit에 대한 사용 가능한 모든 보안 및 규정 준수 정보 정보, 데이터 처리 정책, Microsoft Cloud App Security 앱 카탈로그 정보, CSA STAR 레지스트리의 보안/규정 준수 정보.
zone_pivot_groups: app-info-data-mcas-identity
ms.openlocfilehash: de10b787d3e4100972e46efe76050ed0c7df31fd
ms.sourcegitcommit: a44420a99a1a3a9d0e49f4be66f266e2d4ca7bbb
ms.translationtype: MT
ms.contentlocale: ko-KR
ms.lasthandoff: 05/19/2021
ms.locfileid: "52553249"
---
# <a name="tikit"></a>Tikit

<p></p>
<img alt="Publisher Attestation: The information on this page is based on a self-assessment report provided by the app developer on the security, compliance, and data handling practices followed by this app. Microsoft makes no guarantees regarding the accuracy of the information." src="../media/attested.png" width="650" />
<p>최종 업데이트: 2021년 3월 11일</p>

* <a href="https://teams.microsoft.com/l/app/b13c40ee-e073-459e-96b5-3f3cca046a37" target="_blank">Teams 스토어에서 보기</a>
* <a href="https://appsource.microsoft.com/product/office/WA200002602" target="_blank">앱소스에서 보기</a>

::: zone pivot="general"

### <a name="general-information"></a>일반 정보

Cireson에서 Microsoft에 제공한 정보:

| **정보** | **응답** |
|:----------------|:-------------|
| 앱 이름 | Tikit |
| ID | WA200002602 |
| 지원되는 Office 365 클라이언트 | Microsoft Teams |
| 파트너 회사 이름 | Cireson |
| 파트너 웹사이트의 URL | [https://tikit.ai](https://tikit.ai) |
| Teams 응용 프로그램 정보 페이지의 URL | [https://tikit.ai](https://tikit.ai) |
| 개인정보 처리방침의 URL | [https://tikit.ai/privacy-statement](https://tikit.ai/privacy-statement) |
| 이용 약관의 URL | [https://tikit.ai/terms-service](https://tikit.ai/terms-service) |

 [!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="data"

### <a name="how-the-app-handles-data"></a>앱이 데이터를 처리하는 방법

이 정보는 이 앱이 조직 데이터를 수집하고 저장하는 방법과 조직에서 앱이 수집하는 데이터에 대한 제어에 대해 Cireson에서 제공했습니다.

#### <a name="data-access-using-microsoft-graph"></a>Microsoft Graph 을 사용하여 데이터 액세스

이 [앱에서 필요한 Microsoft Graph 권한을 나열합니다.](https://docs.microsoft.com/graph/permissions-reference)

>| **사용 권한**  | **권한 유형(위임/응용 프로그램)** | **데이터가 수집되고 있습니까? 그것을 수집하기위한 정당화?** | **데이터가 저장되어 있습니까? 그것을 저장하는 정당화?** | **Azure AD 앱 ID** |
>|:----------------|:--------------------|:---------------------------------------------------|:--------------------------|:--------------------------|
>| 장치.읽기 | 신청 | 팀 봇 통신을 통해 단일 사인온에 사용되는 사용자 그래프 정보  | 우리는 사용자 역할, 가족 이름, 주어진 이름, 이메일, AAD ID, Teams 사용자 ID를 저장합니다. 이 정보는 응용 프로그램 인증, 보안, RBAC, 팀 통합, 팀 알림 및 사용자 관계 매핑에 사용됩니다.   | b13c40ee-e073-459e-96b5-3f3cca046a37 |
>| Directory.AccessAsUser.All | 위임 | RBAC의 그룹 이름 및 역할 | 그룹 이름 &amp; 역할 이름, 보안 매핑된 액세스 제어를 제공해야 합니다. | b13c40ee-e073-459e-96b5-3f3cca046a37 |
>| Directory.Read.All | 위임 | RBAC의 그룹 이름 및 역할 | 그룹 이름 &amp; 역할 이름, 보안 매핑된 액세스 제어를 제공해야 합니다. | b13c40ee-e073-459e-96b5-3f3cca046a37 |
>| Group.Read.All | 둘다 | RBAC의 그룹 이름 및 역할 | RBAC의 그룹 이름 및 역할 | b13c40ee-e073-459e-96b5-3f3cca046a37 |
>| User.Read | 위임 | 인증에 사용되는 사용자 역할, 가족 이름, 지정된 이름, 이메일, AAD ID Teams 사용자 ID  | 인증에 사용되는 사용자 역할, 가족 이름, 지정된 이름, 이메일, AAD ID Teams 사용자 ID  | b13c40ee-e073-459e-96b5-3f3cca046a37 |
>| User.Read.All | 신청 | 인증에 사용되는 사용자 역할, 가족 이름, 지정된 이름, 이메일, AAD ID Teams 사용자 ID  | 인증에 사용되는 사용자 역할, 가족 이름, 지정된 이름, 이메일, AAD ID Teams 사용자 ID  | b13c40ee-e073-459e-96b5-3f3cca046a37 |
>| User.ReadBasic.All | 위임 | 인증에 사용되는 사용자 역할, 가족 이름, 지정된 이름, 이메일, AAD ID Teams 사용자 ID  | 인증에 사용되는 사용자 역할, 가족 이름, 지정된 이름, 이메일, AAD ID Teams 사용자 ID  | b13c40ee-e073-459e-96b5-3f3cca046a37 |
>| 전자 메일 | 위임 | 로그인 및 관련 엔터티의 관련 식별에 사용되는 사용자 전자 메일입니다. &quot;할당된 사용자&quot; | 로그인 및 관련 엔터티의 관련 식별에 사용되는 사용자 전자 메일입니다. &quot;할당된 사용자&quot; | b13c40ee-e073-459e-96b5-3f3cca046a37 |
>| 오픈 ID | 위임 | 요구 사항당 MSAL을 통한 인증에 사용  | 요구 사항당 MSAL을 통한 인증에 사용  | b13c40ee-e073-459e-96b5-3f3cca046a37 |
>| 윤곽 | 위임 | 요구 사항당 MSAL을 통한 인증에 사용  | 요구 사항당 MSAL을 통한 인증에 사용  | b13c40ee-e073-459e-96b5-3f3cca046a37 |

#### <a name="data-access-using-other-microsoft-apis"></a>다른 Microsoft API를 사용한 데이터 액세스

Microsoft 365 기반으로 구축된 앱 및 추가 기능을 사용하면 Microsoft Graph 이외의 추가 Microsoft API를 사용하여 조직 식별 정보(OII)를 수집하거나 처리할 수 있습니다. 이 응용 프로그램이 사용하는 마이크로 소프트 이외의 마이크로 소프트 API를 나열할 Graph.

>| **API** |  **OII가 수집되고 있습니까?** |  **어떤 OII가 수집됩니까?** | **OII수집을 위한 정당성?** | **OII가 저장되어 있습니까?** | **OII를 저장하는 정당화?** |
>|:-------------------|:-------------------|:--------------------------|:--------------------------|:---------------------------------------------------|:--------------------------|
>| QnA 메이커 | 아니요 |  |  |  |  |

#### <a name="non-microsoft-services-used"></a>사용되지 Microsoft 서비스

앱이 Microsoft 가 아닌 서비스와 조직 데이터를 전송하거나 공유하는 경우 앱에서 사용하는 비Microsoft 서비스, 전송되는 데이터를 나열하고 앱이 이 정보를 전송해야 하는 이유에 대한 명분을 포함합니다.

>비Microsoft 서비스 사용되지 않습니다.

#### <a name="data-access-via-bots"></a>봇을 통한 데이터 액세스

이 앱에 봇 또는 메시징 확장 프로그램이 포함된 경우 최종 사용자 식별 정보(EUII): 팀의 모든 팀 구성원의 명단(이름, 성, 표시 이름, 이메일 주소)에 액세스하거나 추가된 채팅을 할 수 있습니다. 이 응용 프로그램은이 기능을 사용합니까?

>| **EUII에 액세스할 수 있는 정당성?**  | **EUII는 데이터베이스에 저장되어 있습니까?** | **EUII를 저장하는 정당화?** |
>|:--------------------------------|:---------------------|:--------------------------|
>| 사용자 엔터티 관계 티켓 요청자를 위한 이름 및 이메일 &quot;&quot;  | 이름 및 이메일  | 사용자 엔터티 관계 &quot; 티켓 요청자&quot;  |


#### <a name="telemetry-data"></a>원격 분석 데이터

조직 식별 정보(OII) 또는 최종 사용자 식별 정보(EUII)가 이 응용 프로그램의 원격 분석 또는 로그에 표시됩니까? 그렇다면 저장되는 데이터와 보존 및 제거 정책은 무엇입니까?

>회사 이름, 테넌트 ID, 이메일, 봇 클라이언트 ID를 앱 인사이트(30d 보존 정책)에 저장합니다.

#### <a name="organizational-controls-for-data-stored-by-partner"></a>파트너가 저장한 데이터에 대한 조직 제어

조직의 관리자가 파트너 시스템에서 자신의 정보를 제어하는 방법을 설명해 보세요. 예를 들어 삭제, 보존, 감사, 보관, 최종 사용자 정책 등

>파트너 시스템에는 데이터가 없습니다.

#### <a name="human-review-of-organizational-information"></a>조직 정보의 인간 검토

이 앱에서 수집하거나 저장되는 조직 식별 정보(OII) 데이터를 검토하거나 분석하는 데 관여하는 사람이 있습니까?

>예

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="mcas"

[Microsoft Cloud App Security](https://www.microsoft.com/enterprise-mobility-security/cloud-app-security) 카탈로그의 정보는 아래에 나타납니다.

<iframe height='1020' title='Microsoft Cloud App Security 정보' src='https://appmcasinfoprod.azurewebsites.net/#/dashboard/36548' frameborder='no' style='width: 100%;'></iframe>

<a href="https://appmcasinfoprod.azurewebsites.net/#/dashboard/36548" target="_blank">새 탭에서 보기</a>

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="identity"

### <a name="identity-information"></a>신원 정보

이 정보는 이 앱이 인증, 권한 부여, 응용 프로그램 등록 모범 사례 및 기타 ID 기준을 처리하는 방법에 대해 Cireson에서 제공했습니다.

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
| 앱에서 미리 보기 API를 사용합니까? | 예 |
| 앱에서 비하 API를 사용합니까? | 아니요 |

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end
