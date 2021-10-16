---
title: 동료 동료를 위한 응용 프로그램 Insights Inc
ms.author: elmalova
author: elenamalova
ms.date: 06/16/2021
ms.topic: article
ms.service: attestation
certification_type: attested
description: 동료에 대해 사용 가능한 모든 보안 및 규정 준수 정보, 데이터 처리 정책, CSA STAR 레지스트리의 Microsoft Cloud App Security 앱 카탈로그 정보 및 보안/규정 준수 정보
zone_pivot_groups: app-info-data-mcas-identity
ms.openlocfilehash: 3dc9a5d3bcd6e5bbc356efab77ad15406e9fb772
ms.sourcegitcommit: 9dab9c9dacb9c6daaa6b0041ccc8a49bafdad331
ms.translationtype: MT
ms.contentlocale: ko-KR
ms.lasthandoff: 10/16/2021
ms.locfileid: "60414634"
---
# <a name="fellow"></a>동료

<p></p>
<img alt="Publisher Attestation: The information on this page is based on a self-assessment report provided by the app developer on the security, compliance, and data handling practices followed by this app. Microsoft makes no guarantees regarding the accuracy of the information." src="../media/attested.png" width="650" />
<p>개발자가 마지막으로 업데이트한 날짜: 2021년 5월 21일</p>

* <a href="https://teams.microsoft.com/l/app/f6671df0-1909-428c-91f7-1c42df04d3e4" target="_blank">저장소의 Teams 보기</a>
* <a href="https://appsource.microsoft.com/product/office/WA200002576" target="_blank">AppSource의 보기</a>

::: zone pivot="general"

### <a name="general-information"></a>일반 정보

동료 Insights Inc에서 Microsoft에 제공한 정보:

| **정보** | **응답** |
|:----------------|:-------------|
| 앱 이름 | 동료 |
| ID | WA200002576 |
| Office 365 클라이언트 지원 | Microsoft Teams |
| 파트너 회사 이름 | Fellow Insights Inc |
| 파트너 웹 사이트의 URL | [https://fellow.app](https://fellow.app) |
| 개인 정보 취급 방침의 URL | [https://fellow.app/privacy-policy/](https://fellow.app/privacy-policy/) |
| 사용 약관 URL | [https://fellow.app/terms-of-use/](https://fellow.app/terms-of-use/) |

 [!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="data"

### <a name="how-the-app-handles-data"></a>앱이 데이터를 처리하는 방법

이 정보는 동료 Insights Inc에서 이 앱이 조직 데이터를 수집하고 저장하는 방법 및 앱이 수집하는 데이터에 대해 조직에서 제공하는 컨트롤에 대해 제공합니다.

#### <a name="data-access-using-microsoft-graph"></a>Microsoft 365를 사용한 데이터 Graph

이 앱에 [Graph Microsoft 사용자 권한을](https://docs.microsoft.com/graph/permissions-reference) 나열합니다.

>| **사용 권한**  | **사용 권한 유형(위임/ 응용 프로그램)** | **데이터가 수집하나요? 수집의 사당성** | **데이터가 저장되어 있나요? 저장 사정이 있나요?** | **Azure AD 앱 ID** |
>|:----------------|:------------------------------------------------|:--------------------------------------------------------|:--------------------------------------------------|:--------------------|
>| Calendars.ReadWrite | 둘 다 | 동료는 사용자의 일정과 연결하여 데이터에 대한 메모를 작성하는 기능을 제공합니다. | 동료는 사용자의 기본 달력에 대한 모든 이벤트 데이터를 저장합니다. 첨부 파일이 저장되지 않습니다. 동료 내에서 달력 기반 메모 기록 환경을 제공하는 데 사용됩니다. | [f6671df0-1909-428c-91f7-1c42df04d3e4](https://docs.microsoft.com/microsoft-365-app-certification/azure/f6671df0-1909-428c-91f7-1c42df04d3e4) |
>| Channel.ReadBasic.All | 위임 | 메모를 보낼 수 있는 채널 목록을 표시하기 위해 사용자가 구성원인 채널의 이름을 수집합니다. | 사용자가 동료의 메모를 지정된 채널로 보낼 수 있도록 사용자가 구성원으로 있는 채널의 이름과 ID를 캐시합니다. | [f6671df0-1909-428c-91f7-1c42df04d3e4](https://docs.microsoft.com/microsoft-365-app-certification/azure/f6671df0-1909-428c-91f7-1c42df04d3e4) |
>| Directory.Read.All | application | 이 데이터는 전체 조직에 대해 관리자 설치가 수행된 경우만 수집됩니다. 디렉터리 데이터를 사용하여 사용자 목록을 동기화하고 계정을 자동으로 프로비전합니다. | 관리자가 동료 내부의 작업 영역 설정 내에서 관리자가 전체 설치를 수행한 경우 관리자는 Azure AD에서 동료로의 모든 사용자에 대한 자동 동기화(자동 프로비전)를 사용하도록 설정할 수 있습니다. 이 경우 ID, 이름, 전자 메일 및 관리자, 그룹 구성원 자격과 같은 사용자 정보를 저장합니다(팀 관리 기능용). | [f6671df0-1909-428c-91f7-1c42df04d3e4](https://docs.microsoft.com/microsoft-365-app-certification/azure/f6671df0-1909-428c-91f7-1c42df04d3e4) |
>| Group.Read.All | application | 이 데이터는 전체 조직에 대해 관리자 설치가 수행된 경우만 수집됩니다. 디렉터리 데이터를 사용하여 사용자 목록을 동기화하고 계정을 자동으로 프로비전합니다. | 관리자가 동료 내부의 작업 영역 설정 내에서 관리자가 전체 설치를 수행한 경우 관리자는 Azure AD에서 동료로의 모든 사용자에 대한 자동 동기화(자동 프로비전)를 사용하도록 설정할 수 있습니다. 이 경우 ID, 이름, 전자 메일 및 관리자, 그룹 구성원 자격과 같은 사용자 정보를 저장합니다(팀 관리 기능용). | [f6671df0-1909-428c-91f7-1c42df04d3e4](https://docs.microsoft.com/microsoft-365-app-certification/azure/f6671df0-1909-428c-91f7-1c42df04d3e4) |
>| People.Read | 위임 | 사용자의 연락처는 특정 연락처 displayNames 및 전자 메일 주소로 수집됩니다. 동료 내에서 메모에 초대할 사용자 목록을 제공하고 메모를 공유하는 데 사용됩니다. | 사용자의 연락처는 특정 연락처 displayNames 및 전자 메일 주소로 수집됩니다. 동료 내에서 메모에 초대할 사용자 목록을 제공하고 메모를 공유하는 데 사용됩니다. | [f6671df0-1909-428c-91f7-1c42df04d3e4](https://docs.microsoft.com/microsoft-365-app-certification/azure/f6671df0-1909-428c-91f7-1c42df04d3e4) |
>| People.Read.All | application | 이 데이터는 전체 조직에 대해 관리자 설치가 수행된 경우만 수집됩니다. 사용자의 연락처는 특정 연락처 displayNames 및 전자 메일 주소로 수집됩니다. 동료 내에서 메모에 초대할 사용자 목록을 제공하고 메모를 공유하는 데 사용됩니다. | 관리자가 동료 내부의 작업 영역 설정 내에서 관리자가 전체 설치를 수행한 경우 관리자는 Azure AD에서 동료로의 모든 사용자에 대한 자동 동기화(자동 프로비전)를 사용하도록 설정할 수 있습니다. 이 경우 사용자의 연락처는 특정 연락처 displayNames 및 전자 메일 주소로 수집됩니다. 동료 내에서 메모에 초대할 사용자 목록을 제공하고 메모를 공유하는 데 사용됩니다. | [f6671df0-1909-428c-91f7-1c42df04d3e4](https://docs.microsoft.com/microsoft-365-app-certification/azure/f6671df0-1909-428c-91f7-1c42df04d3e4) |
>| Team.ReadBasic.All | 위임 | 사용자가 일부인 팀 목록이 수집됩니다. 동료 내에서 사용자가 동료에게서 팀에 메모를 보낼 수 있도록 허용하는 데 사용됩니다. | 사용자가 동료의 메모를 지정된 팀 채널로 보낼 수 있도록 사용자가 구성원으로 있는 팀의 이름과 ID를 캐시합니다. | [f6671df0-1909-428c-91f7-1c42df04d3e4](https://docs.microsoft.com/microsoft-365-app-certification/azure/f6671df0-1909-428c-91f7-1c42df04d3e4) |
>| User.Read | 위임 | 기본 사용자 정보가 수집됩니다. 사용자 이름, 전자 메일, 직위. 이 정보는 동료 내에서 사용자 계정 및 회사 계정을 만드는 데 사용됩니다. | 기본 사용자 정보가 저장됩니다. 사용자 이름, 전자 메일, 직위. 이 정보는 동료 내에서 사용자 계정 및 회사 계정을 유지 관리하는 데 사용됩니다. | [f6671df0-1909-428c-91f7-1c42df04d3e4](https://docs.microsoft.com/microsoft-365-app-certification/azure/f6671df0-1909-428c-91f7-1c42df04d3e4) |
>| User.Read.All | application | 이 데이터는 전체 조직에 대해 관리자 설치가 수행된 경우만 수집됩니다. 디렉터리 데이터를 사용하여 사용자 목록을 동기화하고 계정을 자동으로 프로비전합니다. | 관리자가 동료 내부의 작업 영역 설정 내에서 관리자가 전체 설치를 수행한 경우 관리자는 Azure AD에서 동료로의 모든 사용자에 대한 자동 동기화(자동 프로비전)를 사용하도록 설정할 수 있습니다. 이 경우 ID, 이름, 전자 메일 및 관리자, 그룹 구성원 자격과 같은 사용자 정보를 저장합니다(팀 관리 기능용). | [f6671df0-1909-428c-91f7-1c42df04d3e4](https://docs.microsoft.com/microsoft-365-app-certification/azure/f6671df0-1909-428c-91f7-1c42df04d3e4) |
>| offline_access | 위임 | 다른 범위를 통해 수집된 데이터에 대한 액세스를 유지 관리하는 사용자의 새로 고침 토큰입니다. | 사용자의 새로 고침 토큰이 데이터베이스에 저장됩니다. 이 이벤트는 동료 내에서 일정 기반 메모 기록 환경과 예약된 이벤트에 대한 메모 기록 알림에 대해 백그라운드에서 이벤트를 동기화하는 데 사용됩니다. | [f6671df0-1909-428c-91f7-1c42df04d3e4](https://docs.microsoft.com/microsoft-365-app-certification/azure/f6671df0-1909-428c-91f7-1c42df04d3e4) |


#### <a name="non-microsoft-services-used"></a>비영구 Microsoft 서비스

앱이 Microsoft가 아닌 서비스로 조직 데이터를 전송하거나 공유하는 경우 앱에서 사용하는 비 Microsoft 서비스, 전송되는 데이터를 나열하고 앱이 이 정보를 전송해야 하는 이유에 대한 사유를 포함합니다.

>비영구 Microsoft 서비스 사용되지 않습니다.

#### <a name="data-access-via-bots"></a>봇을 통한 데이터 액세스

이 앱에 봇 또는 메시징 확장이 포함되어 있는 경우 팀 구성원의 명단(이름, 성, 표시 이름, 전자 메일 주소)이나 팀 구성원이 추가된 채팅의 최종 사용자 식별 정보(EUII)에 액세스할 수 있습니다. 이 앱이 이 기능을 사용하나요?

>EUII에 액세스하지 않습니다.


#### <a name="telemetry-data"></a>원격 분석 데이터

이 응용 프로그램의 원격 분석 또는 로그에 OII(조직 식별 정보) 또는 EUII(최종 사용자 식별 정보)가 나타나나요? 그렇다면 저장되는 데이터와 보존 및 제거 정책에 대해 설명하세요.

>동료는 개인 데이터를 포함하여 사용자가 직접 제공한 정보를 저장합니다. 또한 동료는 OAuth 데이터, 일정 데이터 및 PII(예: 이름 전자 메일)과 같은 타사 시스템의 일부 정보도 &amp; 저장합니다. 수집된 목적을 위해 필요한 경우 법적으로 사용할 수 있는 기간 동안 모든 데이터를 무기한 보존합니다. 사용자가 요청을 수신하면 이전 날짜에 이 정보를 안전하게 삭제합니다. 로그 데이터는 30일 동안 보존됩니다.

#### <a name="organizational-controls-for-data-stored-by-partner"></a>파트너가 저장한 데이터에 대한 조직 제어

조직의 관리자가 파트너 시스템에서 정보를 제어하는 방법에 대해 설명하는 방법 삭제, 보존, 감사, 보관, 최종 사용자 정책 등

>모든 데이터 전송은 보안 API를 통해 백end 시스템으로 전송됩니다. 동료는 AICPA에서 정의한 SOC 2 프레임워크에 따라 많은 컨트롤을 사용하여 시스템의 보안 및 기밀성을 보장합니다. 동료의 컨트롤은 지속적인 규정 준수를 보장하기 위해 매년 감사를 진행합니다. SOC 2 보고서는 요청 시와 NDA를 공유할 수 있습니다.

#### <a name="human-review-of-organizational-information"></a>조직 정보의 인적 검토

사람이 이 앱에서 수집하거나 저장하는 OII(조직 식별 정보) 데이터를 검토하거나 분석하는 데 관여하나요?

>아니요

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="mcas"

Microsoft Cloud App Security [카탈로그의](https://www.microsoft.com/enterprise-mobility-security/cloud-app-security) 정보가 아래에 표시됩니다.

<iframe height='1020' title='Microsoft Cloud App Security 정보' src='https://appmcasinfoprod.azurewebsites.net/#/dashboard/39739' frameborder='no' style='width: 100%;'></iframe>

<a href="https://appmcasinfoprod.azurewebsites.net/#/dashboard/39739" target="_blank">새 탭에서 보기</a>

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="identity"

### <a name="identity-information"></a>ID 정보

이 정보는 동료 Insights Inc에서 인증, 권한 부여, 응용 프로그램 등록 모범 사례 및 기타 ID 조건을 처리하는 방법에 대해 제공합니다.

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
| 앱의 경우 어떻게 사용하지 않도록 해야 하나요? | ,<br/><br/>- 리소스 소유자 암호 자격 증명(ROPC) 흐름 |
| 앱에서 웹 API를 노출하나요? | 아니요 |
| 앱에서 미리 보기 API를 사용하나요? | 아니요 |
| 앱에서 사용되지 않는 API를 사용하나요? | 아니요 |

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

