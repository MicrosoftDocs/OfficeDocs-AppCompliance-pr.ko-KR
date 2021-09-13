---
title: RockDove 솔루션, Inc.의 위기 사례에 대한 응용 프로그램 정보
ms.author: elmalova
author: elenamalova
ms.date: 08/27/2021
ms.topic: article
ms.service: attestation
certification_type: attested
description: 위기 시, 해당 데이터 처리 정책, CSA STAR 레지스트리의 Microsoft Cloud App Security 앱 카탈로그 정보 및 보안/규정 준수 정보에 대해 사용 가능한 모든 보안 및 규정 준수 정보
zone_pivot_groups: app-info-data-identity
ms.openlocfilehash: 4671d37d77d16004c171887f101ade7506598614
ms.sourcegitcommit: d85595f6518d8d05f0aee75380f51659908b6bcb
ms.translationtype: MT
ms.contentlocale: ko-KR
ms.lasthandoff: 09/12/2021
ms.locfileid: "59287362"
---
# <a name="in-case-of-crisis"></a>위기 발생 시

<p></p>
<img alt="Publisher Attestation: The information on this page is based on a self-assessment report provided by the app developer on the security, compliance, and data handling practices followed by this app. Microsoft makes no guarantees regarding the accuracy of the information." src="../media/attested.png" width="650" />
<p>개발자가 마지막으로 업데이트한 날짜: 2021년 8월 27일</p>

* <a href="https://teams.microsoft.com/l/app/cf430644-447e-4572-8467-3892596d05c7" target="_blank">저장소의 Teams 보기</a>
* <a href="https://appsource.microsoft.com/product/office/WA200003194" target="_blank">AppSource의 보기</a>

::: zone pivot="general"

### <a name="general-information"></a>일반 정보

Microsoft에 대한 RockDove 솔루션, Inc.에서 제공하는 정보:

| **정보** | **응답** |
|:----------------|:-------------|
| 앱 이름 | 위기 발생 시 |
| ID | WA200003194 |
| Office 365 클라이언트 지원 | Microsoft Teams |
| 파트너 회사 이름 | RockDove Solutions, Inc. |
| 파트너 웹 사이트의 URL | [https://www.rockdovesolutions.com](https://www.rockdovesolutions.com) |
| 응용 프로그램 Teams 페이지의 URL입니다. | [https://www.rockdovesolutions.com/in-case-of-crisis/in-case...](https://www.rockdovesolutions.com/in-case-of-crisis/in-case-of-crisis-platform) |
| 개인 정보 취급 방침의 URL | [https://www.rockdovesolutions.com/privacy-policy](https://www.rockdovesolutions.com/privacy-policy) |
| 사용 약관 URL | [https://www.rockdovesolutions.com/terms-of-use](https://www.rockdovesolutions.com/terms-of-use) |

 [!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="data"

### <a name="how-the-app-handles-data"></a>앱이 데이터를 처리하는 방법

이 정보는 이 앱이 조직 데이터를 수집 및 저장하는 방법 및 앱이 수집하는 데이터를 통해 조직이 가지는 컨트롤에 대한 로크도브 솔루션, Inc.에서 제공합니다.

#### <a name="data-access-using-microsoft-graph"></a>Microsoft 365를 사용한 데이터 Graph

이 앱에 [Graph Microsoft 사용자 권한을](https://docs.microsoft.com/graph/permissions-reference) 나열합니다.

>| **사용 권한**  | **사용 권한 유형(위임/ 응용 프로그램)** | **데이터가 수집하나요? 수집의 사당성** | **데이터가 저장되어 있나요? 저장 사정이 있나요?** | **Azure AD 앱 ID** |
>|:----------------|:------------------------------------------------|:--------------------------------------------------------|:--------------------------------------------------|:--------------------|
>| Calendars.ReadWrite | 위임 | 이렇게 하면 사용자의 일정에 대한 모든 권한이 부여됩니다. 앱에 설명, 회의 링크 및 시작 및 종료 날짜가 표시됩니다. 또한 앱에서 Outlook 일정에 이벤트를 만들 수 있습니다. | 향후 이벤트 ID가 데이터베이스에 저장될 수 있습니다. | [6b4a2fee-5642-41a7-b452-d555fac690b0](https://docs.microsoft.com/microsoft-365-app-certification/azure/6b4a2fee-5642-41a7-b452-d555fac690b0) |
>| Channel.ReadBasic.All | 위임 | 사용자 채널에 대한 액세스 권한을 부여합니다.  채널의 사용자 목록은 파일을 업로드할 채널을 선택하는 데 사용됩니다. | 해당 없음 | [6b4a2fee-5642-41a7-b452-d555fac690b0](https://docs.microsoft.com/microsoft-365-app-certification/azure/6b4a2fee-5642-41a7-b452-d555fac690b0) |
>| Files.ReadWrite | 위임 | 해당 없음 | 해당 없음 | [6b4a2fee-5642-41a7-b452-d555fac690b0](https://docs.microsoft.com/microsoft-365-app-certification/azure/6b4a2fee-5642-41a7-b452-d555fac690b0) |
>| Files.ReadWrite.All | 위임 | 사용자가 문제 관리에서 파일로 업로드할 수 Teams | 해당 없음 | [6b4a2fee-5642-41a7-b452-d555fac690b0](https://docs.microsoft.com/microsoft-365-app-certification/azure/6b4a2fee-5642-41a7-b452-d555fac690b0) |
>| Sites.ReadWrite.All | 위임 | 비공개 채널에 업로드하는 데 필요합니다. | 해당 없음 | [6b4a2fee-5642-41a7-b452-d555fac690b0](https://docs.microsoft.com/microsoft-365-app-certification/azure/6b4a2fee-5642-41a7-b452-d555fac690b0) |
>| Team.ReadBasic.All | 위임 | 팀 목록은 사용자가 속한 채널 목록을 얻게 됩니다. 이렇게 하면 사용 가능한 업로드 채널 목록을 볼 수 있습니다. | 해당 없음 | [6b4a2fee-5642-41a7-b452-d555fac690b0](https://docs.microsoft.com/microsoft-365-app-certification/azure/6b4a2fee-5642-41a7-b452-d555fac690b0) |
>| 전자 메일 | 위임 | 인증 후 사용자의 전자 메일을 확인하여 데이터베이스의 전자 메일과 비교해야 합니다. 사용자에게 시스템에 계정이 없는 경우 계정을 생성합니다. | 메일 주소를 저장하고 앱 계정을 생성합니다. | [6b4a2fee-5642-41a7-b452-d555fac690b0](https://docs.microsoft.com/microsoft-365-app-certification/azure/6b4a2fee-5642-41a7-b452-d555fac690b0) |
>| offline_access | 위임 | 이를 통해 그래프 액세스 토큰을 새로 고칠 수 있습니다. | 해당 없음 | [6b4a2fee-5642-41a7-b452-d555fac690b0](https://docs.microsoft.com/microsoft-365-app-certification/azure/6b4a2fee-5642-41a7-b452-d555fac690b0) |
>| openid | 위임 | openid를 통해 인증하는 데 필요한 권한 | 해당 없음 | [6b4a2fee-5642-41a7-b452-d555fac690b0](https://docs.microsoft.com/microsoft-365-app-certification/azure/6b4a2fee-5642-41a7-b452-d555fac690b0) |


#### <a name="non-microsoft-services-used"></a>비영구 Microsoft 서비스

앱이 Microsoft가 아닌 서비스로 조직 데이터를 전송하거나 공유하는 경우 앱에서 사용하는 비 Microsoft 서비스, 전송되는 데이터를 나열하고 앱이 이 정보를 전송해야 하는 이유에 대한 사유를 포함합니다.

>| **모든 비 Microsoft 서비스 OII가 다음으로 전송됩니다.** |  **전송되는 OII는 무엇입니까?** | **OII 전송의 사당성** |
>|:-----------------------------------------------------|:------------------------------|:----------------------------------------|
>| AWS | 조직 사용자의 인증 및 통신용 전자 메일 주소 | 전자 메일 주소는 서비스 내에서 사용자 이름으로 사용 및 SMTP 응용 프로그램 전자 메일 서버에 AWS를 사용합니다. |

#### <a name="data-access-via-bots"></a>봇을 통한 데이터 액세스

이 앱에 봇 또는 메시징 확장이 포함되어 있는 경우 팀 구성원의 명단(이름, 성, 표시 이름, 전자 메일 주소)이나 팀 구성원이 추가된 채팅의 최종 사용자 식별 정보(EUII)에 액세스할 수 있습니다. 이 앱이 이 기능을 사용하나요?

>EUII에 액세스하지 않습니다.


#### <a name="telemetry-data"></a>원격 분석 데이터

이 응용 프로그램의 원격 분석 또는 로그에 OII(조직 식별 정보) 또는 EUII(최종 사용자 식별 정보)가 나타나나요? 그렇다면 저장되는 데이터와 보존 및 제거 정책에 대해 설명하세요.

>전자 메일 주소는 시스템 내에서 기본 사용자 이름으로 사용됩니다.  클라이언트의 사용자 정보 보존은 클라이언트가 현재인 동안 보존되고 서비스 계약 갱신이 중단된 후 제거됩니다.

#### <a name="organizational-controls-for-data-stored-by-partner"></a>파트너가 저장한 데이터에 대한 조직 제어

조직의 관리자가 파트너 시스템에서 정보를 제어하는 방법에 대해 설명하는 방법 삭제, 보존, 감사, 보관, 최종 사용자 정책 등

>당사는 클라이언트가 서비스 내에서 공유되는 보관 회사 정보를 관리(삽입, 바꾸기, 삭제, 감사, 보관)할 수 있는 파트너 관리 포털을 제공합니다.

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

이 정보는 인증, 권한 부여, 응용 프로그램 등록 모범 사례 및 기타 ID 기준을 처리하는 방법에 대한 로크도브 솔루션, Inc.에서 제공합니다.

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
| 앱의 경우 어떻게 사용하지 않도록 해야 하나요? | - 와일드카드 리디렉션 URIS,<br/><br/> |
| 앱에서 웹 API를 노출하나요? | 아니요 |
| 앱에서 미리 보기 API를 사용하나요? | 아니요 |
| 앱에서 사용되지 않는 API를 사용하나요? | 아니요 |

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end
