---
title: Adobe Sign for Word 및 Adobe Inc.PowerPoint 응용 프로그램 정보
ms.author: elmalova
author: elenamalova
ms.date: 02/12/2021
ms.topic: article
ms.service: attestation
certification_type: certified
description: Adobe Sign for Word 및 PowerPoint, 데이터 처리 정책, CSA STAR 레지스트리의 Microsoft Cloud App Security 앱 카탈로그 정보 및 보안/규정 준수 정보에 대해 사용 가능한 모든 보안 및 규정 준수 정보입니다.
zone_pivot_groups: app-info-data-mcas-identity
ms.openlocfilehash: ca8f1f0aba2f18c81c76cb50d8d76cb2e86efa84
ms.sourcegitcommit: b1e752ea527ba6049cdc4f5d12cbd5b4dbd7f5b3
ms.translationtype: MT
ms.contentlocale: ko-KR
ms.lasthandoff: 08/27/2021
ms.locfileid: "58672495"
---
# <a name="adobe-sign-for-word-and-powerpoint"></a>Word 및 Word용 Adobe Sign for word PowerPoint

<p></p><a href="https://aka.ms/appcertification" alt="This Microsoft 365 Certified app has been reviewed by Microsoft against industry standards and controls for security, compliance, and data handling practices. Where applicable, Microsoft has verified the developer's claims of compliance with reasonable and effective practices." target="_blank"><img alt="Click here for more information on the Microsoft Certified app program." src="../media/certified.png" width="650" /></a>
<p>개발자가 마지막으로 업데이트한 날짜: 2021년 2월 12일</p>

* <a href="https://appsource.microsoft.com/product/office/WA104381155" target="_blank">AppSource의 보기</a>

::: zone pivot="general"

### <a name="general-information"></a>일반 정보

Adobe Inc.에서 Microsoft에 제공한 정보:

| **정보** | **응답** |
|:----------------|:-------------|
| 앱 이름 | Word 및 Word용 Adobe Sign for word PowerPoint |
| ID | WA104381155 |
| Office 365 클라이언트 지원 | Word 2016 Mac, 웹용 Word, Word 2013 서비스 팩 1 이상은 Windows, PowerPoint 2016(Mac, 웹용 PowerPoint, PowerPoint 2013 서비스 팩 1 이상)의 Windows |
| 파트너 회사 이름 | Adobe Inc. |
| 파트너 웹 사이트의 URL | [https://acrobat.adobe.com/us/en/sign.html](https://acrobat.adobe.com/us/en/sign.html) |
| 개인 정보 취급 방침의 URL | [https://www.adobe.com/privacy/policy.html](https://www.adobe.com/privacy/policy.html) |
| 사용 약관 URL | [https://www.adobe.com/legal/licenses-terms.html](https://www.adobe.com/legal/licenses-terms.html) |

 [!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="data"

### <a name="how-the-app-handles-data"></a>앱이 데이터를 처리하는 방법

이 정보는 Adobe Inc.에서 이 앱이 조직 데이터를 수집 및 저장하는 방법 및 앱이 수집하는 데이터를 통해 조직이 하게 될 컨트롤에 대해 제공됩니다.

#### <a name="data-access-using-microsoft-graph"></a>Microsoft 365를 사용한 데이터 Graph

이 앱에 [Graph Microsoft 사용자 권한을](https://docs.microsoft.com/graph/permissions-reference) 나열합니다.

>| **사용 권한**  | **사용 권한 유형(위임/ 응용 프로그램)** | **데이터가 수집하나요? 수집의 사당성** | **데이터가 저장되어 있나요? 저장 사정이 있나요?** | **Azure AD 앱 ID** |
>|:----------------|:------------------------------------------------|:--------------------------------------------------------|:--------------------------------------------------|:--------------------|
>| Mail.ReadWrite | 위임 | 첨부된 문서, 보낸 사람 및 받는 사람 전자 메일, 전자 메일에서 Adobe로 보내는 메시지 콘텐츠를 채우기 위해 서명을 위해 보낼 수 있습니다. 이 경우 Adobe Sign에서 해당 필드를 다시 입력할 수 있는 시간을 절약할 수 있습니다. 계약이 서명된 후 사용자가 거래가 완료된 것으로 받는 사람에게 알리는 전자 메일을 보낼 수 있도록 자동으로 새 전자 메일을 작성합니다. | Adobe Sign은 첨부 파일을 임시 파일로 저장하여 24시간이 만료됩니다. | [72d5ac5d-a427-408b-907d-72da3f33ddd1](https://docs.microsoft.com/microsoft-365-app-certification/azure/72d5ac5d-a427-408b-907d-72da3f33ddd1) |
>| People.Read | 위임 | 서명을 위해 보내기 환경의 전자 메일 주소를 자동 입력하려면 일부 초기 문자를 입력하여 사용자가 전체 전자 메일을 입력할 &quot; &quot; 필요가 없습니다. | Adobe Sign은 받는 사람 전자 메일과 displayName만 계약에 저장합니다. | [72d5ac5d-a427-408b-907d-72da3f33ddd1](https://docs.microsoft.com/microsoft-365-app-certification/azure/72d5ac5d-a427-408b-907d-72da3f33ddd1) |
>| User.Read | 위임 | 사용자의 프로필을 읽고 자신의 프로필(기본적으로 전자 메일 및 userId)을 Adobe Sign을 사용할 수 있도록 데이터베이스에 일치합니다. | 사용자의 프로필을 읽고 자신의 프로필(기본적으로 전자 메일 및 userId)을 Adobe Sign을 사용할 수 있도록 데이터베이스에 일치합니다. | [72d5ac5d-a427-408b-907d-72da3f33ddd1](https://docs.microsoft.com/microsoft-365-app-certification/azure/72d5ac5d-a427-408b-907d-72da3f33ddd1) |
>| offline_access | 위임 | 액세스 토큰을 새로 고치기 위해 현재 토큰이 만료된 경우 예를 들어 사용자가 서명을 위해 보내기 창에 있는 경우 너무 오래 비활성 상태인 경우 사용자가 활성 상태일 때 새 토큰을 &quot; &quot; 새로 고쳐야 합니다. | 액세스 토큰을 새로 고치기 위해 현재 토큰이 만료된 경우 예를 들어 사용자가 서명을 위해 보내기 창에 있는 경우 너무 오래 비활성 상태인 경우 사용자가 활성 상태일 때 새 토큰을 &quot; &quot; 새로 고쳐야 합니다. | [72d5ac5d-a427-408b-907d-72da3f33ddd1](https://docs.microsoft.com/microsoft-365-app-certification/azure/72d5ac5d-a427-408b-907d-72da3f33ddd1) |
>| openid | 위임 | 전자 메일 및 UserId. 사용자를 로그인하여 Adobe Sign 앱 사용 권한에 대한 동의를 보장합니다.  | 전자 메일은 Adobe Sign의 사용자에 대한 고유 식별자입니다. 해당 사용자의 모든 활동을 Adobe Sign 레코드에 매핑할 수 있도록 전자 메일 ID를 저장합니다.  | [72d5ac5d-a427-408b-907d-72da3f33ddd1](https://docs.microsoft.com/microsoft-365-app-certification/azure/72d5ac5d-a427-408b-907d-72da3f33ddd1) |


#### <a name="non-microsoft-services-used"></a>비영구 Microsoft 서비스

앱이 Microsoft가 아닌 서비스로 조직 데이터를 전송하거나 공유하는 경우 앱에서 사용하는 비 Microsoft 서비스, 전송되는 데이터를 나열하고 앱이 이 정보를 전송해야 하는 이유에 대한 사유를 포함합니다.

>비영구 Microsoft 서비스 사용되지 않습니다.



#### <a name="telemetry-data"></a>원격 분석 데이터

이 응용 프로그램의 원격 분석 또는 로그에 OII(조직 식별 정보) 또는 EUII(최종 사용자 식별 정보)가 나타나나요? 그렇다면 저장되는 데이터와 보존 및 제거 정책에 대해 설명하세요.

>로그에는 고객 문제를 식별하고 해결할 수 있는 충분한 정보가 포함되어 있습니다. 로그는 90일 동안 보존되고 액세스가 제한됩니다. 사용자가 오프라인 상태일 때 인증을 위한 데이터베이스 저장소 해시된 ID 정보입니다. 데이터베이스 보존 정책은 마지막으로 사용된 날로부터 30일입니다.

#### <a name="organizational-controls-for-data-stored-by-partner"></a>파트너가 저장한 데이터에 대한 조직 제어

조직의 관리자가 파트너 시스템에서 정보를 제어하는 방법에 대해 설명하는 방법 삭제, 보존, 감사, 보관, 최종 사용자 정책 등

>앱 응용 프로그램에 대한 고객 관리자 상호 작용은 Microsoft Teams 없습니다.

#### <a name="human-review-of-organizational-information"></a>조직 정보의 인적 검토

사람이 이 앱에서 수집하거나 저장하는 OII(조직 식별 정보) 데이터를 검토하거나 분석하는 데 관여하나요?

>예

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="mcas"

Microsoft Cloud App Security [카탈로그의](https://www.microsoft.com/enterprise-mobility-security/cloud-app-security) 정보가 아래에 표시됩니다.

<iframe height='1020' title='Microsoft Cloud App Security 정보' src='https://appmcasinfoprod.azurewebsites.net/#/dashboard/11641' frameborder='no' style='width: 100%;'></iframe>

<a href="https://appmcasinfoprod.azurewebsites.net/#/dashboard/11641" target="_blank">새 탭에서 보기</a>

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="identity"

### <a name="identity-information"></a>ID 정보

이 정보는 Adobe Inc.에서 이 앱이 인증, 권한 부여, 응용 프로그램 등록 모범 사례 및 기타 ID 조건을 처리하는 방법에 대해 제공했습니다.

| **정보** | **응답** |
|:----------------|:-------------|
| Microsoft Identify Platform(Azure AD)과 통합하나요?  | 예 |
| 통합 검사 목록에 설명된 적용 가능한 모든 모범 사례를 Microsoft ID 플랫폼 준수하나요?  | 예 |
| 앱에서 인증에 MSAL(Microsoft 인증 라이브러리)을 사용하나요? | 아니오 |
| 앱에서 조건부 액세스 정책을 지원하나요? | 아니오 |
| 앱에서 시나리오에 대한 최소 권한 권한을 요청하나요? | 예 |
| 앱의 정적으로 등록된 사용 권한은 앱이 동적으로 그리고 증분적으로 요청하는 권한을 정확하게 반영하나요? | 예 |
| 앱에서 다중 테넌시를 지원하나요? | 예 |
| 앱에 기밀 클라이언트가 있나요? | 아니오 |
| 앱에 등록된 리디렉션 URI(통합 리소스 식별자)를 모두 소유하고 있나요? | 예 |
| 앱의 경우 어떻게 사용하지 않도록 해야 하나요? | - 와일드카드 리디렉션 URIS,<br/>- OAuth2 암시적 Flow SPA에 필요하지 않은 경우<br/>- 리소스 소유자 암호 자격 증명(ROPC) 흐름 |
| 앱에서 웹 API를 노출하나요? | 예 |
| 사용 권한 모델에서 클라이언트 앱이 적절한 동의를 받은 경우 통화 성공만 허용하나요? | 예 |
| 앱에서 미리 보기 API를 사용하나요? | 아니오 |
| 앱에서 사용되지 않는 API를 사용하나요? | 아니요 |

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end
