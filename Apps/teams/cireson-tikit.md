---
title: Cireson의 Tikit에 대한 응용 프로그램 정보
ms.author: elmalova
author: elenamalova
ms.date: 03/11/2021
ms.topic: article
ms.service: attestation
certification_type: attested
description: Tikit에 사용할 수 있는 모든 보안 및 규정 준수 정보, 데이터 처리 정책, CSA STAR 레지스트리의 Microsoft Cloud App Security 앱 카탈로그 정보 및 보안/규정 준수 정보
zone_pivot_groups: app-info-data-mcas-identity
ms.openlocfilehash: c30afd0d75f8832bf94fedbf48cd64406a5a2a29
ms.sourcegitcommit: 50bd8e07d9355ae65935767a34aca39c46ade8f4
ms.translationtype: MT
ms.contentlocale: ko-KR
ms.lasthandoff: 05/06/2021
ms.locfileid: "52252718"
---
# <a name="tikit"></a>Tikit

<p></p>
<img alt="Publisher Attestation: The information on this page is based on a self-assessment report provided by the app developer on the security, compliance, and data handling practices followed by this app. Microsoft makes no guarantees regarding the accuracy of the information." src="../media/attested.png" width="650" />
<p>개발자가 마지막으로 업데이트한 날짜: 2021년 3월 11일</p>

* <a href="https://teams.microsoft.com/l/app/b13c40ee-e073-459e-96b5-3f3cca046a37" target="_blank">저장소의 Teams 보기</a>
* <a href="https://appsource.microsoft.com/product/office/WA200002602" target="_blank">AppSource의 보기</a>

::: zone pivot="general"

### <a name="general-information"></a>일반 정보

Cireson이 Microsoft에 제공한 정보:

| **정보** | **응답** |
|:----------------|:-------------|
| 앱 이름 | Tikit |
| ID | WA200002602 |
| 기능 | 봇, 메시징 익스텐션 |
| Office 365 클라이언트 지원 | Microsoft Teams |
| 파트너 회사 이름 | Cireson |
| 파트너 웹 사이트의 URL | [https://tikit.ai](https://tikit.ai) |
| 응용 프로그램 Teams 페이지의 URL입니다. | [https://tikit.ai](https://tikit.ai) |
| 개인 정보 취급 방침의 URL | [https://tikit.ai/privacy-statement](https://tikit.ai/privacy-statement) |
| 사용 약관 URL | [https://tikit.ai/terms-service](https://tikit.ai/terms-service) |

 [!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="data"

### <a name="how-the-app-handles-data"></a>앱이 데이터를 처리하는 방법

이 정보는 이 앱이 조직 데이터를 수집하고 저장하는 방법 및 앱이 수집하는 데이터를 통해 조직이 제어할 수 있는 방법에 대해 Cireson에서 제공했습니다.

#### <a name="data-access-using-microsoft-graph"></a>Microsoft 365를 사용한 데이터 Graph

이 앱에 [Graph Microsoft 사용자 권한을](https://docs.microsoft.com/graph/permissions-reference) 나열합니다.

>| **사용 권한**  | **사용 권한 유형(위임/응용 프로그램)** | **데이터가 수집하나요? 수집의 사당성** | **데이터가 저장되어 있나요? 저장 사정이 있나요?** | **Azure AD 앱 ID** |
>|:----------------|:--------------------|:---------------------------------------------------|:--------------------------|:--------------------------|
>| Device.Read | application | 팀 봇 통신을 통해 Single Sign-On에 사용되는 사용자 그래프 정보  | 사용자 역할, 가족 이름, 지정한 이름, 전자 메일, AAD ID, 사용자 ID Teams 저장합니다. 이 알림은 응용 프로그램 인증, 보안, RBAC, 팀 통합, 팀 알림 및 사용자 관계 매핑에 사용됩니다.   | b13c40ee-e073-459e-96b5-3f3cca046a37 |
>| Directory.AccessAsUser.All | 위임 | RBAC의 그룹 이름 및 역할 | 그룹 이름 &amp; 역할 이름, 보안 매핑된 액세스 제어를 제공해야 합니다. | b13c40ee-e073-459e-96b5-3f3cca046a37 |
>| Directory.Read.All | 위임 | RBAC의 그룹 이름 및 역할 | 그룹 이름 &amp; 역할 이름, 보안 매핑된 액세스 제어를 제공해야 합니다. | b13c40ee-e073-459e-96b5-3f3cca046a37 |
>| Group.Read.All | 둘 다 | RBAC의 그룹 이름 및 역할 | RBAC의 그룹 이름 및 역할 | b13c40ee-e073-459e-96b5-3f3cca046a37 |
>| User.Read | 위임 | 사용자 역할, 가족 이름, 지정한 이름, 전자 메일, AAD ID, Teams 사용자 ID, 인증에 사용됩니다.  | 사용자 역할, 가족 이름, 지정한 이름, 전자 메일, AAD ID, Teams 사용자 ID, 인증에 사용됩니다.  | b13c40ee-e073-459e-96b5-3f3cca046a37 |
>| User.Read.All | application | 사용자 역할, 가족 이름, 지정한 이름, 전자 메일, AAD ID, Teams 사용자 ID, 인증에 사용됩니다.  | 사용자 역할, 가족 이름, 지정한 이름, 전자 메일, AAD ID, Teams 사용자 ID, 인증에 사용됩니다.  | b13c40ee-e073-459e-96b5-3f3cca046a37 |
>| User.ReadBasic.All | 위임 | 사용자 역할, 가족 이름, 지정한 이름, 전자 메일, AAD ID, Teams 사용자 ID, 인증에 사용됩니다.  | 사용자 역할, 가족 이름, 지정한 이름, 전자 메일, AAD ID, Teams 사용자 ID, 인증에 사용됩니다.  | b13c40ee-e073-459e-96b5-3f3cca046a37 |
>| 전자 메일 | 위임 | 관련 엔터티의 로그인 및 관련 식별에 사용되는 사용자 전자 메일입니다. &quot;할당된 사용자&quot; | 관련 엔터티의 로그인 및 관련 식별에 사용되는 사용자 전자 메일입니다. &quot;할당된 사용자&quot; | b13c40ee-e073-459e-96b5-3f3cca046a37 |
>| openid | 위임 | 요구 사항당 MSAL을 통한 인증에 사용  | 요구 사항당 MSAL을 통한 인증에 사용  | b13c40ee-e073-459e-96b5-3f3cca046a37 |
>| profile | 위임 | 요구 사항당 MSAL을 통한 인증에 사용  | 요구 사항당 MSAL을 통한 인증에 사용  | b13c40ee-e073-459e-96b5-3f3cca046a37 |

#### <a name="data-access-using-other-microsoft-apis"></a>다른 Microsoft API를 사용한 데이터 액세스

기본 제공 앱 및 추가 Microsoft 365 Microsoft Graph 기타 Microsoft API를 사용하여 OII(조직 식별 가능 정보)를 수집하거나 처리합니다. 이 앱에서 사용하는 Microsoft API를 Graph Microsoft API를 나열합니다.

>| **API** |  **OII가 수집하나요?** |  **수집되는 OII는 무엇입니까?** | **OII 수집의 사당성** | **OII가 저장되어 있나요?** | **OII 저장의 사당성** |
>|:-------------------|:-------------------|:--------------------------|:--------------------------|:---------------------------------------------------|:--------------------------|
>| QnA Maker | 아니요 |  |  |  |  |

#### <a name="non-microsoft-services-used"></a>비영구 Microsoft 서비스

앱이 Microsoft가 아닌 서비스로 조직 데이터를 전송하거나 공유하는 경우 앱에서 사용하는 비 Microsoft 서비스, 전송되는 데이터를 나열하고 앱이 이 정보를 전송해야 하는 이유에 대한 사유를 포함합니다.

>비영구 Microsoft 서비스 사용되지 않습니다.

#### <a name="data-access-via-bots"></a>봇을 통한 데이터 액세스

이 앱에 봇 또는 메시징 확장이 포함되어 있는 경우 팀 구성원의 명단(이름, 성, 표시 이름, 전자 메일 주소)이나 팀 구성원이 추가된 채팅의 최종 사용자 식별 정보(EUII)에 액세스할 수 있습니다. 이 앱이 이 기능을 사용하나요?

>| **EUII 액세스의 사유는 무엇입니까?**  | **EUII가 데이터베이스에 저장되어 있나요?** | **EUII 저장의 사유는 무엇입니까?** |
>|:--------------------------------|:---------------------|:--------------------------|
>| 사용자 엔터티 관계 티켓 요청자에 대한 &quot; 이름 및 전자 메일&quot;  | 이름 및 전자 메일  | 사용자 엔터티 &quot; 관계의 경우 티켓 요청자&quot;  |



#### <a name="telemetry-data"></a>원격 분석 데이터

이 응용 프로그램의 원격 분석 또는 로그에 OII(조직 식별 정보) 또는 EUII(최종 사용자 식별 정보)가 나타나나요? 그렇다면 저장되는 데이터와 보존 및 제거 정책에 대해 설명하세요.

>30 dat 보존 정책과 함께 회사 이름, 테넌트 ID, 전자 메일, 봇 클라이언트 ID를 앱 인사이트에 저장합니다.

#### <a name="organizational-controls-for-data-stored-by-partner"></a>파트너가 저장한 데이터에 대한 조직 제어

조직의 관리자가 파트너 시스템에서 정보를 제어하는 방법에 대해 설명하는 방법 삭제, 보존, 감사, 보관, 최종 사용자 정책 등

>파트너 시스템에 데이터가 없습니다.

#### <a name="human-review-of-organizational-information"></a>조직 정보의 인적 검토

사람이 이 앱에서 수집하거나 저장하는 OII(조직 식별 정보) 데이터를 검토하거나 분석하는 데 관여하나요?

>예

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="mcas"

Microsoft Cloud App Security [카탈로그의](https://www.microsoft.com/enterprise-mobility-security/cloud-app-security) 정보가 아래에 표시됩니다.

<iframe height='1020' title='Microsoft Cloud App Security 정보' src='https://appmcasinfoprod.azurewebsites.net/#/dashboard/36548' frameborder='no' style='width: 100%;'></iframe>

<a href="https://appmcasinfoprod.azurewebsites.net/#/dashboard/36548" target="_blank">새 탭에서 보기</a>

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="identity"

### <a name="identity-information"></a>ID 정보

이 정보는 Cireson에서 이 앱이 인증, 권한 부여, 응용 프로그램 등록 모범 사례 및 기타 ID 조건을 처리하는 방법에 대해 제공했습니다.

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
| 앱에서 미리 보기 API를 사용하나요? | 예 |
| 앱에서 사용되지 않는 API를 사용하나요? | 아니요 |

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end
