---
title: 칸바 도구에 대한 응용 프로그램 정보(Lab Labs)
ms.author: elmalova
author: elenamalova
ms.date: 06/15/2021
ms.topic: article
ms.service: attestation
certification_type: attested
description: CSA STAR 레지스트리의 Kanban 도구, 데이터 처리 정책, Microsoft Cloud App Security 앱 카탈로그 정보 및 보안/규정 준수 정보에 대해 사용할 수 있는 모든 보안 및 규정 준수 정보
zone_pivot_groups: app-info-data-identity
ms.openlocfilehash: b73351d77f68cf00b904d95336f83d8089095791
ms.sourcegitcommit: d85595f6518d8d05f0aee75380f51659908b6bcb
ms.translationtype: MT
ms.contentlocale: ko-KR
ms.lasthandoff: 09/12/2021
ms.locfileid: "59286130"
---
# <a name="kanban-tool"></a>Kanban Tool

<p></p>
<img alt="Publisher Attestation: The information on this page is based on a self-assessment report provided by the app developer on the security, compliance, and data handling practices followed by this app. Microsoft makes no guarantees regarding the accuracy of the information." src="../media/attested.png" width="650" />
<p>개발자가 마지막으로 업데이트한 날짜: 2021년 6월 15일</p>

* <a href="https://teams.microsoft.com/l/app/b3c15d4f-1972-4836-a1eb-7575dd56a17e" target="_blank">저장소의 Teams 보기</a>
* <a href="https://appsource.microsoft.com/product/office/WA200002121" target="_blank">AppSource의 보기</a>

::: zone pivot="general"

### <a name="general-information"></a>일반 정보

Lab Labs에서 Microsoft에 제공하는 정보:

| **정보** | **응답** |
|:----------------|:-------------|
| 앱 이름 | Kanban Tool |
| ID | WA200002121 |
| Office 365 클라이언트 지원 | Microsoft Teams |
| 파트너 회사 이름 | Shore Labs |
| 파트너 웹 사이트의 URL | [https://www.shorelabs.com](https://www.shorelabs.com) |
| 응용 프로그램 Teams 페이지의 URL입니다. | [https://kanbantool.com](https://kanbantool.com) |
| 개인 정보 취급 방침의 URL | [https://kanbantool.com/policy/privacy](https://kanbantool.com/policy/privacy) |
| 사용 약관 URL | [https://kanbantool.com/policy/terms-of-service](https://kanbantool.com/policy/terms-of-service) |

 [!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="data"

### <a name="how-the-app-handles-data"></a>앱이 데이터를 처리하는 방법

이 정보는 이 앱이 조직 데이터를 수집하고 저장하는 방법 및 앱이 수집하는 데이터를 통해 조직이 제어할 수 있는 제어에 대해 랩 랩에서 제공됩니다.

#### <a name="data-access-using-microsoft-graph"></a>Microsoft 365를 사용한 데이터 Graph

이 앱에 [Graph Microsoft 사용자 권한을](https://docs.microsoft.com/graph/permissions-reference) 나열합니다.

>| **사용 권한**  | **사용 권한 유형(위임/ 응용 프로그램)** | **데이터가 수집하나요? 수집의 사당성** | **데이터가 저장되어 있나요? 저장 사정이 있나요?** | **Azure AD 앱 ID** |
>|:----------------|:------------------------------------------------|:--------------------------------------------------------|:--------------------------------------------------|:--------------------|
>| 전자 메일 | 위임 | 통신, ID 일치 및 알림 배달을 위한 사용자의 전자 메일 주소입니다. | 전자 메일 주소입니다. | [4e820d60-9e62-403c-accd-857b987cc13c](https://docs.microsoft.com/microsoft-365-app-certification/azure/4e820d60-9e62-403c-accd-857b987cc13c) |
>| Team.ReadBasic.All | 위임 | 사용자가 직접 구성원으로 있는 팀의 식별자 및 이름입니다. 사용자를 Kanban 도구에서 올바른 그룹에 자동으로 할당하는 데 사용됩니다. | 로그인한 사용자가 직접 구성원인 팀 식별자 및 이름은 Kanban 도구의 그룹에 매핑됩니다. 이렇게 하면 그룹 기반 액세스 관리 및 Kanban Boards 팀 간에 Kanban을 공유할 수 있습니다. | [a8ead1a3-85e1-42a3-9ed0-9afb97482b31](https://docs.microsoft.com/microsoft-365-app-certification/azure/a8ead1a3-85e1-42a3-9ed0-9afb97482b31) |
>| User.Read | 위임 | 로그인한 사용자의 기본 회사 정보입니다. 단일 계정 기능을 제공하기 위해 새 계정에 대한 계정 세부 정보를 채우고 조직에 속한 사용자를 인식하는 Sign-On 사용됩니다. | 조직의 이름 및 고유한 Microsoft 식별자입니다. | [a8ead1a3-85e1-42a3-9ed0-9afb97482b31](https://docs.microsoft.com/microsoft-365-app-certification/azure/a8ead1a3-85e1-42a3-9ed0-9afb97482b31) |
>| offline_access | 위임 | 사용자의 로그인 시 앱 액세스 권한을 부여한 데이터의 'Microsoft 로그인' 기능 및 동기화를 허용합니다. | 액세스 권한을 부여한 데이터에 대한 액세스를 유지 관리합니다. | [a8ead1a3-85e1-42a3-9ed0-9afb97482b31](https://docs.microsoft.com/microsoft-365-app-certification/azure/a8ead1a3-85e1-42a3-9ed0-9afb97482b31) |
>| openid | 위임 | 사용자가 'Microsoft로 로그인' 단추를 통해 직장 또는 학교 계정으로 앱에 로그인할 수 있도록 하는 ID 토큰을 열 수 있습니다. | Microsoft ID 시스템의 사용자 계정에 대한 변경이 불가능한 식별자입니다. | [a8ead1a3-85e1-42a3-9ed0-9afb97482b31](https://docs.microsoft.com/microsoft-365-app-certification/azure/a8ead1a3-85e1-42a3-9ed0-9afb97482b31) |
>| 프로필 | 위임 | Kanban 도구에서 자동 입력할 사용자 이름 및 Kanban 도구의 변경 내용과 Microsoft Teams. | 사용자의 전체 이름입니다. | [a8ead1a3-85e1-42a3-9ed0-9afb97482b31](https://docs.microsoft.com/microsoft-365-app-certification/azure/a8ead1a3-85e1-42a3-9ed0-9afb97482b31) |


#### <a name="non-microsoft-services-used"></a>비영구 Microsoft 서비스

앱이 Microsoft가 아닌 서비스로 조직 데이터를 전송하거나 공유하는 경우 앱에서 사용하는 비 Microsoft 서비스, 전송되는 데이터를 나열하고 앱이 이 정보를 전송해야 하는 이유에 대한 사유를 포함합니다.

>| **모든 비 Microsoft 서비스 OII가 다음으로 전송됩니다.** |  **전송되는 OII는 무엇입니까?** | **OII 전송의 사당성** |
>|:-----------------------------------------------------|:------------------------------|:----------------------------------------|
>| Kanban Tool은 서비스 성능을 위해 다음과 같은 하위 프로세서를 사용합니다. https://kanbantool.com/policy/privacy#appointed-subprocessors |   | 이러한 타사를 사용하여 기술 인프라를 제공하고 유지 관리하고 청구 및 결제 처리를 지원합니다. |

#### <a name="data-access-via-bots"></a>봇을 통한 데이터 액세스

이 앱에 봇 또는 메시징 확장이 포함되어 있는 경우 팀 구성원의 명단(이름, 성, 표시 이름, 전자 메일 주소)이나 팀 구성원이 추가된 채팅의 최종 사용자 식별 정보(EUII)에 액세스할 수 있습니다. 이 앱이 이 기능을 사용하나요?

>EUII에 액세스하지 않습니다.


#### <a name="telemetry-data"></a>원격 분석 데이터

이 응용 프로그램의 원격 분석 또는 로그에 OII(조직 식별 정보) 또는 EUII(최종 사용자 식별 정보)가 나타나나요? 그렇다면 저장되는 데이터와 보존 및 제거 정책에 대해 설명하세요.

>서비스에서 사용자 계정 및 활동에 대한 기술 정보를 자동으로 수집합니다. 이러한 정보는 내부 로그 파일에 저장되고 사용자가 만든 활동의 일부인 경우 OII 및 EUII 데이터를 포함할 수 있습니다. 타사와 로그 파일을 공유하지 않습니다. 로그 데이터 수집의 목적은 법적 및 규정상의 이유로, 잠재적인 보안 위반 또는 서비스 오용의 원본 식별, 요청 속도 제한 및 성능 프로파일링을 목표로 하는 것입니다.

#### <a name="organizational-controls-for-data-stored-by-partner"></a>파트너가 저장한 데이터에 대한 조직 제어

조직의 관리자가 파트너 시스템에서 정보를 제어하는 방법에 대해 설명하는 방법 삭제, 보존, 감사, 보관, 최종 사용자 정책 등

>계정 관리자는 계정과 관련된 개인 데이터를 수정 및 제거하는 기능을 포함하여 모든 권한을 가지며, 실제 데이터 컨트롤러입니다.

#### <a name="human-review-of-organizational-information"></a>조직 정보의 인적 검토

사람이 이 앱에서 수집하거나 저장하는 OII(조직 식별 정보) 데이터를 검토하거나 분석하는 데 관여하나요?

>아니요

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="mcas"

Microsoft Cloud App Security [카탈로그의](https://www.microsoft.com/enterprise-mobility-security/cloud-app-security) 정보가 아래에 표시됩니다.

<iframe height='1020' title='Microsoft Cloud App Security 정보' src='https://appmcasinfoprod.azurewebsites.net/#/dashboard/' frameborder='no' style='width: 100%;'></iframe>

<a href="https://appmcasinfoprod.azurewebsites.net/#/dashboard/" target="_blank">새 탭에서 보기</a>

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="identity"

### <a name="identity-information"></a>ID 정보

이 정보는 Lab Labs에서 이 앱이 인증, 권한 부여, 응용 프로그램 등록 모범 사례 및 기타 ID 조건을 처리하는 방법에 대해 제공했습니다.

| **정보** | **응답** |
|:----------------|:-------------|
| Microsoft Identify Platform(Azure AD)과 통합하나요?  | 예 |
| 통합 검사 목록에 설명된 적용 가능한 모든 모범 사례를 Microsoft ID 플랫폼 준수하나요?  | 예 |
| 앱에서 인증에 MSAL(Microsoft 인증 라이브러리)을 사용하나요? | 아니요 |
| 앱에서 조건부 액세스 정책을 지원하나요? | 아니요 |
| 앱에서 시나리오에 대한 최소 권한 권한을 요청하나요? | 예 |
| 앱의 정적으로 등록된 사용 권한은 앱이 동적으로 그리고 증분적으로 요청하는 권한을 정확하게 반영하나요? | 예 |
| 앱에서 다중 테넌시를 지원하나요? | 예 |
| 앱에 기밀 클라이언트가 있나요? | 예 |
| 앱에 등록된 리디렉션 URI(통합 리소스 식별자)를 모두 소유하고 있나요? | 예 |
| 앱의 경우 어떻게 사용하지 않도록 해야 하나요? | ,<br/>- OAuth2 암시적 Flow SPA에 필요하지 않은 경우<br/>- 리소스 소유자 암호 자격 증명(ROPC) 흐름 |
| 앱에서 웹 API를 노출하나요? | 예 |
| 사용 권한 모델에서 클라이언트 앱이 적절한 동의를 받은 경우 통화 성공만 허용하나요? | 예 |
| 앱에서 미리 보기 API를 사용하나요? | 아니요 |
| 앱에서 사용되지 않는 API를 사용하나요? | 아니요 |

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end
