---
title: LiveTiles에 의한 도달을 위한 응용 프로그램 정보
ms.author: elmalova
author: elenamalova
ms.date: 03/22/2021
ms.topic: article
ms.service: attestation
certification_type: attested
description: REACH에 대한 사용 가능한 모든 보안 및 규정 준수 정보 정보, 데이터 처리 정책, Microsoft Cloud App Security 앱 카탈로그 정보 및 CSA STAR 레지스트리의 보안/규정 준수 정보.
zone_pivot_groups: app-info-data-mcas-identity
ms.openlocfilehash: 83df050a6f58bc1d0b7d49239b40ddf2ba80849a
ms.sourcegitcommit: a44420a99a1a3a9d0e49f4be66f266e2d4ca7bbb
ms.translationtype: MT
ms.contentlocale: ko-KR
ms.lasthandoff: 05/19/2021
ms.locfileid: "52551999"
---
# <a name="reach"></a>Reach

<p></p>
<img alt="Publisher Attestation: The information on this page is based on a self-assessment report provided by the app developer on the security, compliance, and data handling practices followed by this app. Microsoft makes no guarantees regarding the accuracy of the information." src="../media/attested.png" width="650" />
<p>최종 업데이트: 2021년 3월 22일</p>

* <a href="https://teams.microsoft.com/l/app/5df8ebd2-bf7b-4fb5-bb35-0bfbf5d10a23" target="_blank">Teams 스토어에서 보기</a>
* <a href="https://appsource.microsoft.com/product/office/WA200002045" target="_blank">앱소스에서 보기</a>

::: zone pivot="general"

### <a name="general-information"></a>일반 정보

LiveTiles에서 Microsoft에 제공하는 정보:

| **정보** | **응답** |
|:----------------|:-------------|
| 앱 이름 | Reach |
| ID | WA200002045 |
| 지원되는 Office 365 클라이언트 | Microsoft Teams |
| 파트너 회사 이름 | LiveTiles |
| 파트너 웹사이트의 URL | [https://livetilesglobal.com](https://livetilesglobal.com) |
| Teams 응용 프로그램 정보 페이지의 URL | [https://livetilesglobal.com/products/livetiles-reach/](https://livetilesglobal.com/products/livetiles-reach/) |
| 개인정보 처리방침의 URL | [https://livetilesglobal.com/privacy-policy](https://livetilesglobal.com/privacy-policy) |
| 이용 약관의 URL | [https://livetilesglobal.com/eula](https://livetilesglobal.com/eula) |

 [!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="data"

### <a name="how-the-app-handles-data"></a>앱이 데이터를 처리하는 방법

이 정보는 LiveTiles에서 이 앱이 조직 데이터를 수집하고 저장하는 방법과 앱이 수집하는 데이터에 대한 조직에서 가질 수 있는 제어에 대해 제공했습니다.

#### <a name="data-access-using-microsoft-graph"></a>Microsoft Graph 을 사용하여 데이터 액세스

이 [앱에서 필요한 Microsoft Graph 권한을 나열합니다.](https://docs.microsoft.com/graph/permissions-reference)

>| **사용 권한**  | **권한 유형(위임/응용 프로그램)** | **데이터가 수집되고 있습니까? 그것을 수집하기위한 정당화?** | **데이터가 저장되어 있습니까? 그것을 저장하는 정당화?** | **Azure AD 앱 ID** |
>|:----------------|:--------------------|:---------------------------------------------------|:--------------------------|:--------------------------|
>| 팀활동.보내기 | 신청 | 없음 | 없음 | a7c1920d-3ac0-42db-9757-078a2b321fd8  |
>| User.Read | 위임 | 사용자 표시 이름, 사용자 이메일 주소, UPN. 사용자가 앱에 로그인하고 표시 이름과 같이 로그인한 사용자의 기본 정보를 얻을 수 있도록 하는 데 필요합니다. 이메일 주소는 이메일 알림을 보내는 데 사용됩니다.  | 사용자 표시 이름, 사용자 이메일 주소, UPN. 사용자가 앱에 로그인하고 표시 이름과 같이 로그인한 사용자의 기본 정보를 얻을 수 있도록 하는 데 필요합니다. 이메일 주소는 이메일 알림을 보내는 데 사용됩니다.  | d492530a-8cff-481c-90da-9c3c3f1be7da |
>| User.ReadBasic.All | 위임 | 사용자 표시 이름, 사용자 이메일 주소, UPN, 사용자 부서, 사용자 직무 제목, 사용자 모바일 전화 번호, 사용자 비즈니스 전화 번호, 사용자 Office 위치. 사용자가 앱(Phonebook) 내의 다른 사용자를 검색하고 다른 사용자의 기본 프로필 및 연락처 정보를 볼 수 있도록 하는 데 필요합니다.  | 없음 | d492530a-8cff-481c-90da-9c3c3f1be7da |
>| Directory.Read.All | 신청 | 그룹 멤버십, 디렉토리의 광고 그룹. 사용자의 그룹 구성원은 Microsoft Graph API에 대한 호출을 최소화하기 위해 캐시에 저장됩니다. 사용자가 Active Directory 그룹을 검색할 수 있도록 하는 데 필요합니다. 또한 백엔드의 웹 작업에서 사용자의 AD 그룹 구성원을 해결하기 위해 응용 프로그램에 이 권한이 필요합니다. | 사용자 그룹 구성원. 사용자의 그룹 구성원은 Microsoft Graph API에 대한 호출을 최소화하기 위해 캐시에 저장됩니다. 사용자가 Active Directory 그룹을 검색할 수 있도록 하는 데 필요합니다. 또한 백엔드의 웹 작업에서 사용자의 AD 그룹 구성원을 해결하기 위해 응용 프로그램에 이 권한이 필요합니다.  | d492530a-8cff-481c-90da-9c3c3f1be7da  |
>| User.Read.All | 신청 | 사용자 프로필에서 검색된 데이터는 앱 내에서 지정된 잠재고객 타겟팅 기능 구성에 따라 달라집니다. 앱이 로그인한 사용자 없이 사용자 프로필을 읽을 수 있도록 하는 데 필요합니다. 특정 프로필 속성 값을 기반으로 특정 사용자에게 정보가 표시되도록 응용 프로그램 내의 정보 타겟팅 기능에 프로필 데이터를 읽기가 필요합니다.  | 없음 | d492530a-8cff-481c-90da-9c3c3f1be7da  |


#### <a name="non-microsoft-services-used"></a>사용되지 Microsoft 서비스

앱이 Microsoft 가 아닌 서비스와 조직 데이터를 전송하거나 공유하는 경우 앱에서 사용하는 비Microsoft 서비스, 전송되는 데이터를 나열하고 앱이 이 정보를 전송해야 하는 이유에 대한 명분을 포함합니다.

>| **모든 Microsoft 서비스 OII가** |  **어떤 OII가 전송됩니까?** | **OII 전송에 대한 정당화?** |
>|:-------------------|:--------------------------|:--------------------------|
>| 센드그리드, 원시그널 | 이메일 주소, 표시 이름 | 이메일 및 모바일 푸시 알림을 통해 사용자에게 알림 보내기 |

#### <a name="data-access-via-bots"></a>봇을 통한 데이터 액세스

이 앱에 봇 또는 메시징 확장 프로그램이 포함된 경우 최종 사용자 식별 정보(EUII): 팀의 모든 팀 구성원의 명단(이름, 성, 표시 이름, 이메일 주소)에 액세스하거나 추가된 채팅을 할 수 있습니다. 이 응용 프로그램은이 기능을 사용합니까?

>EUII에 액세스할 수 없습니다.


#### <a name="telemetry-data"></a>원격 분석 데이터

조직 식별 정보(OII) 또는 최종 사용자 식별 정보(EUII)가 이 응용 프로그램의 원격 분석 또는 로그에 표시됩니까? 그렇다면 저장되는 데이터와 보존 및 제거 정책은 무엇입니까?

>이메일 주소, UPN. 최대 60일 보존, 그 후 제거

#### <a name="organizational-controls-for-data-stored-by-partner"></a>파트너가 저장한 데이터에 대한 조직 제어

조직의 관리자가 파트너 시스템에서 자신의 정보를 제어하는 방법을 설명해 보세요. 예를 들어 삭제, 보존, 감사, 보관, 최종 사용자 정책 등

>관리자는 모든 문의에 대한 지원에 문의할 수 있습니다.

#### <a name="human-review-of-organizational-information"></a>조직 정보의 인간 검토

이 앱에서 수집하거나 저장되는 조직 식별 정보(OII) 데이터를 검토하거나 분석하는 데 관여하는 사람이 있습니까?

>아니요

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="mcas"

[Microsoft Cloud App Security](https://www.microsoft.com/enterprise-mobility-security/cloud-app-security) 카탈로그의 정보는 아래에 나타납니다.

<iframe height='1020' title='Microsoft Cloud App Security 정보' src='https://appmcasinfoprod.azurewebsites.net/#/dashboard/36551' frameborder='no' style='width: 100%;'></iframe>

<a href="https://appmcasinfoprod.azurewebsites.net/#/dashboard/36551" target="_blank">새 탭에서 보기</a>

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="identity"

### <a name="identity-information"></a>신원 정보

이 정보는 LiveTiles에서 이 앱이 인증, 권한 부여, 응용 프로그램 등록 모범 사례 및 기타 ID 기준을 처리하는 방법에 대해 제공했습니다.

| **정보** | **응답** |
|:----------------|:-------------|
| Microsoft 식별 플랫폼(Azure AD)과 통합합니까?  | 예 |
| Microsoft ID 플랫폼 통합 검사 목록에 설명된 모든 적용 가능한 모범 사례를 검토하고 준수했습니까?  | 아니요 |
| 앱에서 인증에 MSAL(Microsoft 인증 라이브러리)을 사용합니까? | 예 |
| 앱이 조건부 액세스 정책을 지원합니까? | 예 |
| 지원되는 정책 유형 목록 | 다단계 인증, 사용자 위치 제한 및 IP 범위 제한 |
| 앱에서 시나리오에 대한 최소 권한 권한을 요청합니까? | 예 |
| 앱의 정적 등록 권한은 앱이 동적으로 점진적으로 요청하는 권한을 정확하게 반영합니까? | 예 |
| 앱이 다중 테넌션을 지원합니까? | 예 |
| 앱에 기밀 클라이언트가 있습니까? | 아니요 |
| 앱에 등록된 URI(리디렉션 통합 리소스 식별자)를 모두 소유하고 있습니까? | 예 |
| 앱의 경우 무엇을 사용하지 않으려습니까? | - 와일드카드 리디렉션 URI,<br/>- OAuth2 암시적 Flow, SPA에 필요한 경우가 아니면<br/>- 리소스 소유자 암호 자격 증명(ROPC) 흐름 |
| 앱에서 웹 API가 노출됩니까? | 예 |
| 권한 모델은 클라이언트 앱이 적절한 동의를 받는 경우에만 호출을 성공시킬 수 있습니까? | 예 |
| 앱에서 미리 보기 API를 사용합니까? | 예 |
| 앱에서 비하 API를 사용합니까? | 아니요 |

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end
