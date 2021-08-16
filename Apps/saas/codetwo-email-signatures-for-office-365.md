---
title: CodeTwo에서 사용할 수 있는 CodeTwo 전자 메일 서명에 대한 Office 365 정보
ms.author: elmalova
author: elenamalova
ms.date: 08/02/2021
ms.topic: article
ms.service: attestation
certification_type: attested
description: CSA STAR 레지스트리의 Office 365, 데이터 처리 정책, Microsoft Cloud App Security 앱 카탈로그 정보 및 보안/규정 준수 정보에 대한 CodeTwo 전자 메일 서명에 사용할 수 있는 모든 보안 및 규정 준수 정보입니다.
zone_pivot_groups: app-info-data-mcas-identity
ms.openlocfilehash: 79db12fe65495df15e21b46e810abd8bbd017359
ms.sourcegitcommit: 7ef4a79aa28ac4dcce067b1f6f8693eeec6335e9
ms.translationtype: MT
ms.contentlocale: ko-KR
ms.lasthandoff: 08/13/2021
ms.locfileid: "58245313"
---
# <a name="codetwo-email-signatures-for-office-365"></a>CodeTwo Email Signatures for Office 365

<p></p>
<img alt="Publisher Attestation: The information on this page is based on a self-assessment report provided by the app developer on the security, compliance, and data handling practices followed by this app. Microsoft makes no guarantees regarding the accuracy of the information." src="../media/attested.png" width="650" />
<p>개발자가 마지막으로 업데이트한 날짜: 2021년 8월 2일</p>

* <a href="https://appsource.microsoft.com/product/web-apps/codetwo.3d2daeb9-a008-4070-a35c-cda39bd30a69" target="_blank">AppSource의 보기</a>

::: zone pivot="general"

### <a name="general-information"></a>일반 정보

CodeTwo에서 Microsoft에 제공하는 정보:

| **정보** | **응답** |
|:----------------|:-------------|
| 앱 이름 | CodeTwo Email Signatures for Office 365 |
| ID | codetwo.3d2daeb9-a008-4070-a35c-cda39bd30a69 |
| 파트너 회사 이름 | CodeTwo |
| 파트너 웹 사이트의 URL | [https://www.codetwo.com](https://www.codetwo.com) |
| 개인 정보 취급 방침의 URL | [https://www.codetwo.com/regulations/privacy](https://www.codetwo.com/regulations/privacy) |
| 사용 약관 URL | [https://www.codetwo.com/license-agreement](https://www.codetwo.com/license-agreement) |

 [!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="data"

### <a name="how-the-app-handles-data"></a>앱이 데이터를 처리하는 방법

이 정보는 CodeTwo에서 이 앱이 조직 데이터를 수집 및 저장하는 방법 및 앱이 수집하는 데이터를 통해 조직에서 제공하는 컨트롤에 대해 제공됩니다.

#### <a name="data-access-using-microsoft-graph"></a>Microsoft 365를 사용한 데이터 Graph

이 앱에 [Graph Microsoft 사용자 권한을](https://docs.microsoft.com/graph/permissions-reference) 나열합니다.

>| **사용 권한**  | **사용 권한 유형(위임/ 응용 프로그램)** | **데이터가 수집하나요? 수집의 사당성** | **데이터가 저장되어 있나요? 저장 사정이 있나요?** | **Azure AD 앱 ID** |
>|:----------------|:------------------------------------------------|:--------------------------------------------------------|:--------------------------------------------------|:--------------------|
>| User.Read | 위임 | 사용자가 앱에 로그인할 수 있도록 허용하고 앱에서 로그인한 사용자의 프로필을 읽을 수 있도록 허용합니다. 또한 앱에서 로그인한 사용자의 기본 조직 정보를 읽을 수 있습니다. | 데이터가 저장되지 않습니다. | [2a93620e-4345-4e3b-9bae-0195f08aab69](https://docs.microsoft.com/microsoft-365-app-certification/azure/2a93620e-4345-4e3b-9bae-0195f08aab69) |
>| User.Read | 위임 | 사용자가 앱에 로그인할 수 있도록 허용하고 앱에서 로그인한 사용자의 프로필을 읽을 수 있도록 허용합니다. 또한 앱에서 로그인한 사용자의 기본 회사 정보를 읽을 수 있습니다. | 데이터가 저장되지 않습니다. | [7afd058a-f568-4496-96b1-28d06ab3500f](https://docs.microsoft.com/microsoft-365-app-certification/azure/7afd058a-f568-4496-96b1-28d06ab3500f) |
>| Directory.AccessAsUser.All | 위임 | 앱에서 로그인한 사용자와 디렉터리의 정보에 동일한 액세스 권한을 부여할 수 있습니다. | 데이터가 저장되지 않습니다. | [cb657bc2-9910-4b9c-82a0-6f4f3a47006b](https://docs.microsoft.com/microsoft-365-app-certification/azure/cb657bc2-9910-4b9c-82a0-6f4f3a47006b) |
>| Directory.Read.All | 둘 다 | 앱이 사용자, 그룹 및 앱과 같은&#8217;조직의 데이터를 읽을 수 있도록 허용합니다. | 데이터가 저장되지 않습니다. | [cb657bc2-9910-4b9c-82a0-6f4f3a47006b](https://docs.microsoft.com/microsoft-365-app-certification/azure/cb657bc2-9910-4b9c-82a0-6f4f3a47006b) |
>| User.ReadBasic.All | 위임 | 앱에서 로그인한 사용자를 대신하여 조직의 다른 사용자의 기본 프로필 속성 집합을 읽을 수 있도록 합니다. 여기에는 표시 이름, 이름 및 성, 전자 메일 주소 및 사진이 포함됩니다. 정보는 사용자의 전자 메일 서명을 자동으로 개인 설정하는 데 사용됩니다. | 데이터가 저장되지 않습니다. | [cb657bc2-9910-4b9c-82a0-6f4f3a47006b](https://docs.microsoft.com/microsoft-365-app-certification/azure/cb657bc2-9910-4b9c-82a0-6f4f3a47006b) |
>| User.Read | 위임 | 사용자가 앱에 로그인할 수 있도록 허용하고 앱에서 로그인한 사용자의 프로필을 읽을 수 있도록 허용합니다. 또한 앱에서 로그인한 사용자의 기본 회사 정보를 읽을 수 있습니다. CodeTwo 서비스에 사용자를 등록하는 데 사용됩니다. | 데이터가 저장되지 않습니다. | [ce60db2f-439f-4e45-bfdc-d4c827c1820d](https://docs.microsoft.com/microsoft-365-app-certification/azure/ce60db2f-439f-4e45-bfdc-d4c827c1820d) |
>| 전자 메일 | 위임 | 앱에서 사용자의 기본 전자 메일 주소를 읽을 수 있도록 허용합니다. CodeTwo 서비스에 사용자를 등록하는 데 사용됩니다. | 데이터가 저장되지 않습니다. | [ce60db2f-439f-4e45-bfdc-d4c827c1820d](https://docs.microsoft.com/microsoft-365-app-certification/azure/ce60db2f-439f-4e45-bfdc-d4c827c1820d) |
>| offline_access | 위임 | 사용자가 현재 앱을 사용하지 않는 경우에도 앱에서 액세스 권한을 부여한 데이터를 보고 업데이트할 수 있습니다. 이렇게 해서 앱에 추가 사용 권한이 부여되지는 않습니다. | 데이터가 저장되지 않습니다. | [ce60db2f-439f-4e45-bfdc-d4c827c1820d](https://docs.microsoft.com/microsoft-365-app-certification/azure/ce60db2f-439f-4e45-bfdc-d4c827c1820d) |
>| openid | 위임 | 사용자가 자신의 직장 또는 학교 계정으로 앱에 로그인할 수 있도록 허용하고 앱에서 기본 사용자 프로필 정보를 볼 수 있습니다. CodeTwo 서비스에 사용자를 등록하는 데 사용됩니다. | 데이터가 저장되지 않습니다. | [ce60db2f-439f-4e45-bfdc-d4c827c1820d](https://docs.microsoft.com/microsoft-365-app-certification/azure/ce60db2f-439f-4e45-bfdc-d4c827c1820d) |
>| 프로필 | 위임 | 앱에서 사용자의 기본 프로필(이름, 사진, 사용자 이름)을 볼 수 있습니다. CodeTwo 서비스에 사용자를 등록하는 데 사용됩니다. | 데이터가 저장되지 않습니다. | [ce60db2f-439f-4e45-bfdc-d4c827c1820d](https://docs.microsoft.com/microsoft-365-app-certification/azure/ce60db2f-439f-4e45-bfdc-d4c827c1820d) |


#### <a name="non-microsoft-services-used"></a>비영구 Microsoft 서비스

앱이 Microsoft가 아닌 서비스로 조직 데이터를 전송하거나 공유하는 경우 앱에서 사용하는 비 Microsoft 서비스, 전송되는 데이터를 나열하고 앱이 이 정보를 전송해야 하는 이유에 대한 사유를 포함합니다.

>비영구 Microsoft 서비스 사용되지 않습니다.



#### <a name="telemetry-data"></a>원격 분석 데이터

이 응용 프로그램의 원격 분석 또는 로그에 OII(조직 식별 정보) 또는 EUII(최종 사용자 식별 정보)가 나타나나요? 그렇다면 저장되는 데이터와 보존 및 제거 정책에 대해 설명하세요.

>응용 프로그램 원격 분석 또는 로그에 OII 또는 EUII가 나타나지 않습니다.

#### <a name="organizational-controls-for-data-stored-by-partner"></a>파트너가 저장한 데이터에 대한 조직 제어

조직의 관리자가 파트너 시스템에서 정보를 제어하는 방법에 대해 설명하는 방법 삭제, 보존, 감사, 보관, 최종 사용자 정책 등

>고객은 CodeTwo 관리 패널을 통해 연락처 조직 데이터 및 서비스 설정에 액세스하고 해당 설정을 &amp; 시정할 수 있습니다. 또한 CodeTwo 정보 보안 팀에 전용 양식(을 통해 CodeTwo 약관 및 개인 정보 보호에 설명된 모든 권한을 행사할 수 있습니다. 즉, 데이터 액세스, 데이터 변경, 처리 삭제 및 제한, 동의 철회 및 처리 이의제기 및 처리 이의제기권)에 설명된 모든 권한을 행사할 수 https://www.codetwo.com/form/security-officer/) https://www.codetwo.com/regulations/privacy) 있습니다.

#### <a name="human-review-of-organizational-information"></a>조직 정보의 인적 검토

사람이 이 앱에서 수집하거나 저장하는 OII(조직 식별 정보) 데이터를 검토하거나 분석하는 데 관여하나요?

>아니오

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="mcas"

Microsoft Cloud App Security [카탈로그의](https://www.microsoft.com/enterprise-mobility-security/cloud-app-security) 정보가 아래에 표시됩니다.

<iframe height='1020' title='Microsoft Cloud App Security 정보' src='https://appmcasinfoprod.azurewebsites.net/#/dashboard/36503' frameborder='no' style='width: 100%;'></iframe>

<a href="https://appmcasinfoprod.azurewebsites.net/#/dashboard/36503" target="_blank">새 탭에서 보기</a>

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="identity"

### <a name="identity-information"></a>ID 정보

이 정보는 CodeTwo에서 이 앱이 인증, 권한 부여, 응용 프로그램 등록 모범 사례 및 기타 ID 조건을 처리하는 방법에 대해 제공했습니다.

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
