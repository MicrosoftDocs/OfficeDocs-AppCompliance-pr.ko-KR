---
title: 스마트시트의 응용 프로그램 정보
ms.author: elmalova
author: elenamalova
ms.date: 12/16/2019
ms.topic: article
ms.service: attestation
certification_type: attested
description: Smartsheet, 데이터 처리 정책, CSA STAR 레지스트리의 Microsoft Cloud App Security 앱 카탈로그 정보 및 보안/규정 준수 정보에 사용할 수 있는 모든 보안 및 규정 준수 정보
zone_pivot_groups: app-info-data-mcas
ms.openlocfilehash: 063dd29aea9265d89eb3ba735a376c7b1f0b64e3
ms.sourcegitcommit: 50bd8e07d9355ae65935767a34aca39c46ade8f4
ms.translationtype: MT
ms.contentlocale: ko-KR
ms.lasthandoff: 05/06/2021
ms.locfileid: "52251127"
---
# <a name="smartsheet"></a>Smartsheet

<p></p>
<img alt="Publisher Attestation: The information on this page is based on a self-assessment report provided by the app developer on the security, compliance, and data handling practices followed by this app. Microsoft makes no guarantees regarding the accuracy of the information." src="../media/attested.png" width="650" />
<p>개발자가 마지막으로 업데이트한 날짜: 2019년 12월 16일</p>

* <a href="https://teams.microsoft.com/l/app/f4d81e8e-4500-44c2-8328-9e06cbe037c5" target="_blank">저장소의 Teams 보기</a>
* <a href="https://appsource.microsoft.com/product/office/WA104380975" target="_blank">AppSource의 보기</a>

::: zone pivot="general"

### <a name="general-information"></a>일반 정보

Smartsheet에서 Microsoft에 제공하는 정보:

| **정보** | **응답** |
|:----------------|:-------------|
| 앱 이름 | Smartsheet |
| ID | WA104380975 |
| 기능 | 봇, 탭 |
| Office 365 클라이언트 지원 | Microsoft Teams |
| 파트너 회사 이름 | Smartsheet |
| 파트너 웹 사이트의 URL | [https://help.smartsheet.com/articles/2476201](https://help.smartsheet.com/articles/2476201) |
| 응용 프로그램 Teams 페이지의 URL입니다. | [https://help.smartsheet.com/articles/2476201-interact-with-...](https://help.smartsheet.com/articles/2476201-interact-with-smartsheet-items-in-microsoft-teams) |
| 개인 정보 취급 방침의 URL | [https://www.smartsheet.com/privacy](https://www.smartsheet.com/privacy) |
| 사용 약관 URL | [https://www.smartsheet.com/user-agreement](https://www.smartsheet.com/user-agreement) |

 [!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="data"

### <a name="how-the-app-handles-data"></a>앱이 데이터를 처리하는 방법

이 정보는 Smartsheet에서 이 앱이 조직 데이터를 수집하고 저장하는 방법 및 앱이 수집하는 데이터를 통해 조직이 사용할 컨트롤에 대해 제공됩니다.

#### <a name="data-access-using-microsoft-graph"></a>Microsoft 365를 사용한 데이터 Graph

이 앱에 [Graph Microsoft 사용자 권한을](https://docs.microsoft.com/graph/permissions-reference) 나열합니다.

>| **사용 권한**  | **사용 권한 유형(위임/응용 프로그램)** | **데이터가 수집하나요? 수집의 사당성** | **데이터가 저장되어 있나요? 저장 사정이 있나요?** | **Azure AD 앱 ID** |
>|:----------------|:--------------------|:---------------------------------------------------|:--------------------------|:--------------------------|
>| AppCatalog.ReadWrite.All | 위임 | 없음 | 앱이 사용자를 대신하여 앱을 설치할 수 있도록 허용합니다. | c68947ae-a07f-44ce-9a13-7b559251731d |
>| Directory.Read.All | 위임 | tenantId UI에 표시하기 위해 정보를 검색하는 데 사용할 수 있습니다. | 이 테넌트가 사용하는 앱을 읽을 수 있으므로 해당 앱을 설치해야 하는지 확인할 수 있습니다. | c68947ae-a07f-44ce-9a13-7b559251731d |
>| Group.Read.All | 위임 | teamId/groupId 메시지 배달을 위한Id입니다. | 앱에서 대화뿐만 아니라 그룹(또는 Teams 팀)에 대한 기본 정보를 읽을 수 있습니다. | c68947ae-a07f-44ce-9a13-7b559251731d |
>| Group.ReadWrite.All | 위임 | teamId/groupId 메시지 배달을 위한Id입니다. | 앱에서 팀에서 새 대화를 시작할 수 있습니다. 이 사용 권한에는 위의 Read.All 범위도 포함되어 있지만 기술적인 이유로 이 범위도 필요합니다. | c68947ae-a07f-44ce-9a13-7b559251731d |
>| User.Read.All | 위임 | userId. | 사용자에 대한 기본 정보를 읽은 후, Auth 프로세스 중에 읽을 수 있습니다. | c68947ae-a07f-44ce-9a13-7b559251731d |
>| offline_access | 위임 | refreshToken. | 앱에서 새로 고침 토큰을 수신하고 사용자가 앱을 사용할 때 사용자를 대신하여 auth 토큰을 새로 고칠 수 있도록 허용합니다. | c68947ae-a07f-44ce-9a13-7b559251731d |

#### <a name="data-access-using-other-microsoft-apis"></a>다른 Microsoft API를 사용한 데이터 액세스

기본 제공 앱 및 추가 Microsoft 365 Microsoft Graph 기타 Microsoft API를 사용하여 OII(조직 식별 가능 정보)를 수집하거나 처리합니다. 이 앱에서 사용하는 Microsoft API를 Graph Microsoft API를 나열합니다.

>| **API** |  **OII가 수집하나요?** |  **수집되는 OII는 무엇입니까?** | **OII 수집의 사당성** | **OII가 저장되어 있나요?** | **OII 저장의 사당성** |
>|:-------------------|:-------------------|:--------------------------|:--------------------------|:---------------------------------------------------|:--------------------------|
>| 봇 프레임워크 API | 예 | Bot Framework API를 사용하여 메시지를 팀 앱의 앱으로 배달합니다. 스마트시트는 사용자 ID 정보를 저장하여 스마트시트 봇이 대화하는 사용자를 추적합니다. |  | 없음 |  |

#### <a name="non-microsoft-services-used"></a>비영구 Microsoft 서비스

앱이 Microsoft가 아닌 서비스로 조직 데이터를 전송하거나 공유하는 경우 앱에서 사용하는 비 Microsoft 서비스, 전송되는 데이터를 나열하고 앱이 이 정보를 전송해야 하는 이유에 대한 사유를 포함합니다.

>| **모든 비 Microsoft 서비스 OII가 다음으로 전송됩니다.** |  **전송되는 OII는 무엇입니까?** | **OII 전송의 사당성** |
>|:-------------------|:--------------------------|:--------------------------|
>| 스마트시트는 Equinix로 호스트되는 프로덕션 데이터 센터 환경 내의 암호화된 보관 상태로 정보를 저장하고 AWS S3에서는 고객 첨부 파일을 개인 암호화된 버킷에 저장합니다. |  | 봇 프레임워크 API를 사용하여 메시지를 팀 앱의 앱으로 배달합니다. 스마트시트는 사용자 ID 정보를 저장하여 스마트시트 봇이 대화하는 사용자를 추적합니다. |

#### <a name="data-access-via-bots"></a>봇을 통한 데이터 액세스

이 앱에 봇 또는 메시징 확장이 포함되어 있는 경우 팀 구성원의 명단(이름, 성, 표시 이름, 전자 메일 주소)이나 팀 구성원이 추가된 채팅의 최종 사용자 식별 정보(EUII)에 액세스할 수 있습니다. 이 앱이 이 기능을 사용하나요?

>| **EUII 액세스의 사유는 무엇입니까?**  | **EUII가 데이터베이스에 저장되어 있나요?** | **EUII 저장의 사유는 무엇입니까?** |
>|:--------------------------------|:---------------------|:--------------------------|
>| 스마트시트는 이 기능을 사용하여 봇이 말하는 사람도 추적할 수 있습니다. 초기 등록 흐름 동안 스마트시트 알림 시스템에서 사용자에 대한 봇 레코드를 생성합니다. | Teams 봇용 Smartsheet의 경우 봇이 Teams 추적하는 데 도움이 하도록 사용자 전자 메일과 userId를 저장합니다.  스마트시트는 tenantIds를 저장하여 사용자가 디렉터리에 있는 그룹과 메시지 배달을 위한 groupIds를 저장합니다. |  |



#### <a name="telemetry-data"></a>원격 분석 데이터

이 응용 프로그램의 원격 분석 또는 로그에 OII(조직 식별 정보) 또는 EUII(최종 사용자 식별 정보)가 나타나나요? 그렇다면 저장되는 데이터와 보존 및 제거 정책에 대해 설명하세요.

>아니요

#### <a name="organizational-controls-for-data-stored-by-partner"></a>파트너가 저장한 데이터에 대한 조직 제어

조직의 관리자가 파트너 시스템에서 정보를 제어하는 방법에 대해 설명하는 방법 삭제, 보존, 감사, 보관, 최종 사용자 정책 등

>스마트시트는 저장된 모든 사용자 정보를 암호화하며 관리자가 2FA를 사용하는 데 필요합니다. 스마트시트는 보기가 없는 SaaS 공급자로 작동하며 기본적으로 고객이 플랫폼에 업로드하거나 입력하기로 선택한 콘텐츠를 검토하지 않습니다.

#### <a name="human-review-of-organizational-information"></a>조직 정보의 인적 검토

사람이 이 앱에서 수집하거나 저장하는 OII(조직 식별 정보) 데이터를 검토하거나 분석하는 데 관여하나요?

>아니요

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="mcas"

Microsoft Cloud App Security [카탈로그의](https://www.microsoft.com/enterprise-mobility-security/cloud-app-security) 정보가 아래에 표시됩니다.

<iframe height='1020' title='Microsoft Cloud App Security 정보' src='https://appmcasinfoprod.azurewebsites.net/#/dashboard/11934' frameborder='no' style='width: 100%;'></iframe>

<a href="https://appmcasinfoprod.azurewebsites.net/#/dashboard/11934" target="_blank">새 탭에서 보기</a>

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

