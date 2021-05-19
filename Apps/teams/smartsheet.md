---
title: 스마트 시트에 의해 스마트 시트에 대한 응용 프로그램 정보
ms.author: elmalova
author: elenamalova
ms.date: 12/16/2019
ms.topic: article
ms.service: attestation
certification_type: attested
description: SMARTsheet에 대한 사용 가능한 모든 보안 및 규정 준수 정보 정보, 데이터 처리 정책, Microsoft Cloud App Security 앱 카탈로그 정보, CSA STAR 레지스트리의 보안/규정 준수 정보.
zone_pivot_groups: app-info-data-mcas
ms.openlocfilehash: ddf77e7e73cc0bef1a21e72d1db328a4845a12f5
ms.sourcegitcommit: a44420a99a1a3a9d0e49f4be66f266e2d4ca7bbb
ms.translationtype: MT
ms.contentlocale: ko-KR
ms.lasthandoff: 05/19/2021
ms.locfileid: "52551528"
---
# <a name="smartsheet"></a>Smartsheet

<p></p>
<img alt="Publisher Attestation: The information on this page is based on a self-assessment report provided by the app developer on the security, compliance, and data handling practices followed by this app. Microsoft makes no guarantees regarding the accuracy of the information." src="../media/attested.png" width="650" />
<p>최종 업데이트: 2019년 12월 16일</p>

* <a href="https://teams.microsoft.com/l/app/f4d81e8e-4500-44c2-8328-9e06cbe037c5" target="_blank">Teams 스토어에서 보기</a>
* <a href="https://appsource.microsoft.com/product/office/WA104380975" target="_blank">앱소스에서 보기</a>

::: zone pivot="general"

### <a name="general-information"></a>일반 정보

스마트 시트에서 Microsoft에 제공하는 정보:

| **정보** | **응답** |
|:----------------|:-------------|
| 앱 이름 | Smartsheet |
| ID | WA104380975 |
| 지원되는 Office 365 클라이언트 | Microsoft Teams |
| 파트너 회사 이름 | Smartsheet |
| 파트너 웹사이트의 URL | [https://help.smartsheet.com/articles/2476201](https://help.smartsheet.com/articles/2476201) |
| Teams 응용 프로그램 정보 페이지의 URL | [https://help.smartsheet.com/articles/2476201-interact-with-...](https://help.smartsheet.com/articles/2476201-interact-with-smartsheet-items-in-microsoft-teams) |
| 개인정보 처리방침의 URL | [https://www.smartsheet.com/privacy](https://www.smartsheet.com/privacy) |
| 이용 약관의 URL | [https://www.smartsheet.com/user-agreement](https://www.smartsheet.com/user-agreement) |

 [!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="data"

### <a name="how-the-app-handles-data"></a>앱이 데이터를 처리하는 방법

이 정보는 Smartsheet에서 이 앱이 조직 데이터를 수집하고 저장하는 방법과 앱이 수집하는 데이터에 대한 조직이 가질 수 있는 제어에 대해 제공했습니다.

#### <a name="data-access-using-microsoft-graph"></a>Microsoft Graph 을 사용하여 데이터 액세스

이 [앱에서 필요한 Microsoft Graph 권한을 나열합니다.](https://docs.microsoft.com/graph/permissions-reference)

>| **사용 권한**  | **권한 유형(위임/응용 프로그램)** | **데이터가 수집되고 있습니까? 그것을 수집하기위한 정당화?** | **데이터가 저장되어 있습니까? 그것을 저장하는 정당화?** | **Azure AD 앱 ID** |
>|:----------------|:--------------------|:---------------------------------------------------|:--------------------------|:--------------------------|
>| 앱카탈로그.읽기쓰기.모든 것 | 위임 | 없음 | 우리의 응용 프로그램은 사용자를 대신하여 응용 프로그램을 설치할 수 있습니다. | c68947ae-a07f-44ce-9a13-7b559251731d |
>| Directory.Read.All | 위임 | UI에 표시할 정보를 검색하기 위한 테넌트Id입니다. | 이 테넌트가 사용하는 앱을 읽을 수 있으므로 앱을 설치해야 하는지 확인할 수 있습니다. | c68947ae-a07f-44ce-9a13-7b559251731d |
>| Group.Read.All | 위임 | 메시지 배달을 위한 teamId/groupId입니다. | 앱에서 대화뿐만 아니라 그룹(또는 Teams 팀에 대한 기본 정보를 읽을 수 있습니다. | c68947ae-a07f-44ce-9a13-7b559251731d |
>| Group.ReadWrite.All | 위임 | 메시지 배달을 위한 teamId/groupId입니다. | 우리의 응용 프로그램은 팀에서 새로운 대화를 시작할 수 있습니다. 이 권한에는 위의 Read.All 범위도 포함되어 있지만 기술적 인 이유로이 권한이 필요합니다. | c68947ae-a07f-44ce-9a13-7b559251731d |
>| User.Read.All | 위임 | userId. | 우리는 auth 프로세스 동안 사용자에 대한 기본 정보를 읽을 수 있습니다. | c68947ae-a07f-44ce-9a13-7b559251731d |
>| offline_access | 위임 | 새로 고침토큰. | 앱에서 새로 고침 토큰을 수신하고 앱을 사용할 때 사용자를 대신하여 auth 토큰을 새로 고칠 수 있습니다. | c68947ae-a07f-44ce-9a13-7b559251731d |

#### <a name="data-access-using-other-microsoft-apis"></a>다른 Microsoft API를 사용한 데이터 액세스

Microsoft 365 기반으로 구축된 앱 및 추가 기능을 사용하면 Microsoft Graph 이외의 추가 Microsoft API를 사용하여 조직 식별 정보(OII)를 수집하거나 처리할 수 있습니다. 이 응용 프로그램이 사용하는 마이크로 소프트 이외의 마이크로 소프트 API를 나열할 Graph.

>| **API** |  **OII가 수집되고 있습니까?** |  **어떤 OII가 수집됩니까?** | **OII수집을 위한 정당성?** | **OII가 저장되어 있습니까?** | **OII를 저장하는 정당화?** |
>|:-------------------|:-------------------|:--------------------------|:--------------------------|:---------------------------------------------------|:--------------------------|
>| 봇 프레임워크 API | 예 | 봇 프레임워크 API를 사용하여 팀 앱용 앱으로 메시지를 전달합니다. Smartsheet는 사용자Id 정보를 저장하여 스마트 시트 봇이 누구와 이야기하고 있는지 추적합니다. |  | 없음 |  |

#### <a name="non-microsoft-services-used"></a>사용되지 Microsoft 서비스

앱이 Microsoft 가 아닌 서비스와 조직 데이터를 전송하거나 공유하는 경우 앱에서 사용하는 비Microsoft 서비스, 전송되는 데이터를 나열하고 앱이 이 정보를 전송해야 하는 이유에 대한 명분을 포함합니다.

>| **모든 Microsoft 서비스 OII가** |  **어떤 OII가 전송됩니까?** | **OII 전송에 대한 정당화?** |
>|:-------------------|:--------------------------|:--------------------------|
>| Smartsheet는 Equinix와 AWS S3에서 호스팅되는 프로덕션 데이터 센터 환경 내에서 암호화된 휴식 상태로 정보를 저장하여 고객 첨부 파일을 개인 암호화 버킷에 저장합니다. |  | 봇 프레임워크 API를 사용하여 팀 앱용 앱으로 메시지를 전달합니다. Smartsheet는 사용자Id 정보를 저장하여 스마트 시트 봇이 누구와 이야기하고 있는지 추적합니다. |

#### <a name="data-access-via-bots"></a>봇을 통한 데이터 액세스

이 앱에 봇 또는 메시징 확장 프로그램이 포함된 경우 최종 사용자 식별 정보(EUII): 팀의 모든 팀 구성원의 명단(이름, 성, 표시 이름, 이메일 주소)에 액세스하거나 추가된 채팅을 할 수 있습니다. 이 응용 프로그램은이 기능을 사용합니까?

>| **EUII에 액세스할 수 있는 정당성?**  | **EUII는 데이터베이스에 저장되어 있습니까?** | **EUII를 저장하는 정당화?** |
>|:--------------------------------|:---------------------|:--------------------------|
>| Smartsheet는 봇이 누구와도 이야기하고 있는지 추적하는 데 도움이 됩니다. 초기 auth 흐름 중에 Smartsheet 알림 시스템에서 사용자에 대한 봇 레코드를 만듭니다. | Teams 봇용 Smartsheet의 경우 봇이 누구와 이야기하고 있는지 추적하기 위해 Teams 사용자 이메일 및 userId를 저장합니다.  Smartsheet는 테넌트Id를 저장하여 사용자가 디렉터리에 속한 그룹을 나열하고 메시지 배달을 위한 groupId를 나열합니다. |  |


#### <a name="telemetry-data"></a>원격 분석 데이터

조직 식별 정보(OII) 또는 최종 사용자 식별 정보(EUII)가 이 응용 프로그램의 원격 분석 또는 로그에 표시됩니까? 그렇다면 저장되는 데이터와 보존 및 제거 정책은 무엇입니까?

>아니요

#### <a name="organizational-controls-for-data-stored-by-partner"></a>파트너가 저장한 데이터에 대한 조직 제어

조직의 관리자가 파트너 시스템에서 자신의 정보를 제어하는 방법을 설명해 보세요. 예를 들어 삭제, 보존, 감사, 보관, 최종 사용자 정책 등

>Smartsheet는 저장된 모든 사용자 정보를 암호화하며 관리자는 2FA를 사용해야 합니다. Smartsheet는 노뷰 SaaS 공급자로 운영되며 기본적으로 고객이 업로드하거나 플랫폼에 입력하기로 선택한 콘텐츠를 검토하지 않습니다.

#### <a name="human-review-of-organizational-information"></a>조직 정보의 인간 검토

이 앱에서 수집하거나 저장되는 조직 식별 정보(OII) 데이터를 검토하거나 분석하는 데 관여하는 사람이 있습니까?

>아니요

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="mcas"

[Microsoft Cloud App Security](https://www.microsoft.com/enterprise-mobility-security/cloud-app-security) 카탈로그의 정보는 아래에 나타납니다.

<iframe height='1020' title='Microsoft Cloud App Security 정보' src='https://appmcasinfoprod.azurewebsites.net/#/dashboard/11934' frameborder='no' style='width: 100%;'></iframe>

<a href="https://appmcasinfoprod.azurewebsites.net/#/dashboard/11934" target="_blank">새 탭에서 보기</a>

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

