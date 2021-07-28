---
title: SalesTim의 판매에 대한 응용 프로그램 정보
ms.author: elmalova
author: elenamalova
ms.date: 10/27/2020
ms.topic: article
ms.service: attestation
certification_type: certified
description: CSA STAR 레지스트리의 SalesTim, 데이터 처리 정책, Microsoft Cloud App Security 앱 카탈로그 정보 및 보안/규정 준수 정보에 대해 사용할 수 있는 모든 보안 및 규정 준수 정보
zone_pivot_groups: app-info-data-mcas
ms.openlocfilehash: b15cf2f87b6707b6fa82dfc3968444d7cad85e8a
ms.sourcegitcommit: a613e40971c8b48fa2b7a35039b4331a8116763b
ms.translationtype: MT
ms.contentlocale: ko-KR
ms.lasthandoff: 07/22/2021
ms.locfileid: "53524761"
---
# <a name="salestim"></a>SalesTim

<p></p><a href="https://aka.ms/appcertification" alt="This Microsoft 365 Certified app has been reviewed by Microsoft against industry standards and controls for security, compliance, and data handling practices. Where applicable, Microsoft has verified the developer's claims of compliance with reasonable and effective practices." target="_blank"><img alt="Click here for more information on the Microsoft Certified app program." src="../media/certified.png" width="650" /></a>
<p>개발자가 마지막으로 업데이트한 날짜: 2020년 10월 27일</p>

* <a href="https://teams.microsoft.com/l/app/589748de-ec98-4616-9063-e91c629bd1a4" target="_blank">저장소의 Teams 보기</a>
* <a href="https://appsource.microsoft.com/product/office/WA200001393" target="_blank">AppSource의 보기</a>

::: zone pivot="general"

### <a name="general-information"></a>일반 정보

SalesTim에서 Microsoft에 제공하는 정보:

| **정보** | **응답** |
|:----------------|:-------------|
| 앱 이름 | SalesTim |
| ID | WA200001393 |
| Office 365 클라이언트 지원 | Microsoft Teams |
| 파트너 회사 이름 | SalesTim |
| 파트너 웹 사이트의 URL | [https://www.salestim.com/](https://www.salestim.com/) |
| 개인 정보 취급 방침의 URL | [https://www.salestim.com/legal/privacy/](https://www.salestim.com/legal/privacy/) |
| 사용 약관 URL | [https://www.salestim.com/legal/tos/](https://www.salestim.com/legal/tos/) |

 [!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="data"

### <a name="how-the-app-handles-data"></a>앱이 데이터를 처리하는 방법

이 정보는 이 앱이 조직 데이터를 수집 및 저장하는 방법 및 앱이 수집하는 데이터에 대해 조직이 제어할 수 있는 제어에 대해 SalesTim에서 제공했습니다.

#### <a name="data-access-using-microsoft-graph"></a>Microsoft 365를 사용한 데이터 Graph

이 앱에 [Graph Microsoft 사용자 권한을](https://docs.microsoft.com/graph/permissions-reference) 나열합니다.

>| **사용 권한**  | **사용 권한 유형(위임/ 응용 프로그램)** | **데이터가 수집하나요? 수집의 사당성** | **데이터가 저장되어 있나요? 저장 사정이 있나요?** | **Azure AD 앱 ID** |
>|:----------------|:------------------------------------------------|:--------------------------------------------------------|:--------------------------------------------------|:--------------------|
>| AppCatalog.ReadWrite.All | 위임 | 아니요 | 앱이 회사 앱 카탈로그에 자체 패키지를 설치하고 업데이트할 수 있도록 허용합니다. | [2a651f59-97ce-42bb-97d7-cf7a2af4b635](https://docs.microsoft.com/microsoft-365-app-certification/azure/2a651f59-97ce-42bb-97d7-cf7a2af4b635) |
>| Directory.AccessAsUser.All | 위임 | 일부&#8217;데이터만 저장하지 않습니다. | 사용자가 워크플로에서 승인자를 선택하는 등 응용 프로그램의 다양한 장소에서 다른 사용자를 선택할 수 있습니다. | [2a651f59-97ce-42bb-97d7-cf7a2af4b635](https://docs.microsoft.com/microsoft-365-app-certification/azure/2a651f59-97ce-42bb-97d7-cf7a2af4b635) |
>| Group.ReadWrite.All | 위임 | 그룹&#8217;/팀&#8217;다시 저장하지 않을 수 있습니다. | 앱에서 그룹을 만들고, 로그인한 사용자를 대신하여 모든 그룹 속성 및 구성원 자격을 읽을 수 있도록 허용합니다. 또한 그룹 소유자가 그룹을 관리할 수 있도록 허용하고 그룹 구성원이 그룹 콘텐츠를 업데이트할 수 있습니다. | [2a651f59-97ce-42bb-97d7-cf7a2af4b635](https://docs.microsoft.com/microsoft-365-app-certification/azure/2a651f59-97ce-42bb-97d7-cf7a2af4b635) |
>| Mail.Send | 위임 | 알림&#8217;, 받는 사람(ID만), 요청 ID와 같은 이 작업의 메타데이터를 다시 저장할 수 있습니다. | 앱이 승인 워크플로 중에 알림 전자 메일을 보낼 수 있습니다. | [2a651f59-97ce-42bb-97d7-cf7a2af4b635](https://docs.microsoft.com/microsoft-365-app-certification/azure/2a651f59-97ce-42bb-97d7-cf7a2af4b635) |
>| Sites.ReadWrite.All | 위임 | 일부 Azure 서비스를 사용하여 데이터를 저장하고 있습니다. 특히 Azure 및 Cosmos DB에 Redis | 팀 프로비전 프로세스 중에 앱에서 팀과 연결된 드라이브(파일 및 폴더)를 관리할 수 있습니다. | [2a651f59-97ce-42bb-97d7-cf7a2af4b635](https://docs.microsoft.com/microsoft-365-app-certification/azure/2a651f59-97ce-42bb-97d7-cf7a2af4b635) |
>| User.Read.All | 위임 | 일부&#8217;데이터만 저장하지 않습니다. | 앱에서 모든 사용자의 프로필 속성, 보고서 및 관리자의 전체 집합을 읽을 수 있도록 허용합니다. 특히 대상 지정 프로세스 중에 현재 사용자 프로필을 기준으로 일부 콘텐츠를 필터링하는 데 사용됩니다. | [2a651f59-97ce-42bb-97d7-cf7a2af4b635](https://docs.microsoft.com/microsoft-365-app-certification/azure/2a651f59-97ce-42bb-97d7-cf7a2af4b635) |
>| offlineaccess | 위임 | 아니요 | 앱에서 일부 백그라운드 작업 및 작업을 사용자로 수행할 수 있도록 허용합니다. | [2a651f59-97ce-42bb-97d7-cf7a2af4b635](https://docs.microsoft.com/microsoft-365-app-certification/azure/2a651f59-97ce-42bb-97d7-cf7a2af4b635) |


#### <a name="non-microsoft-services-used"></a>비영구 Microsoft 서비스

앱이 Microsoft가 아닌 서비스로 조직 데이터를 전송하거나 공유하는 경우 앱에서 사용하는 비 Microsoft 서비스, 전송되는 데이터를 나열하고 앱이 이 정보를 전송해야 하는 이유에 대한 사유를 포함합니다.

>| **모든 비 Microsoft 서비스 OII가 다음으로 전송됩니다.** |  **전송되는 OII는 무엇입니까?** | **OII 전송의 사당성** |
>|:-----------------------------------------------------|:------------------------------|:----------------------------------------|
>| Intercom을 기본 지원 응용 프로그램으로 사용하고 있습니다. Intercom에는 다음과 같은 몇 가지 기본 사용자 프로필 정보가 포함될 수 있습니다. https://developers.salestim.com/platform/datamanagement.html#support-data |  | 프로덕션 환경에서 GitHub API를 사용하여 문제를 자동으로 생성하고 있습니다. 또한 에 설명된 일부 기술 GitHub 저장하고 https://developers.salestim.com/platform/datamanagement.html#error-reporting-data) 있습니다. 이러한 문제 및 로그에는 몇 가지 기본 사용자 프로필 정보가 포함될 수 있습니다. 이러한 문제 및 로그는 15일마다 자동으로 삭제됩니다. |

#### <a name="data-access-via-bots"></a>봇을 통한 데이터 액세스

이 앱에 봇 또는 메시징 확장이 포함되어 있는 경우 팀 구성원의 명단(이름, 성, 표시 이름, 전자 메일 주소)이나 팀 구성원이 추가된 채팅의 최종 사용자 식별 정보(EUII)에 액세스할 수 있습니다. 이 앱이 이 기능을 사용하나요?

>EUII에 액세스하지 않습니다.


#### <a name="telemetry-data"></a>원격 분석 데이터

이 응용 프로그램의 원격 분석 또는 로그에 OII(조직 식별 정보) 또는 EUII(최종 사용자 식별 정보)가 나타나나요? 그렇다면 저장되는 데이터와 보존 및 제거 정책에 대해 설명하세요.

>수집된 모든 데이터는 여기에 설명되어 있습니다. 설명된 바와 같이 로그는 15일 동안 일시적으로 저장된 다음 https://developers.salestim.com/platform/datamanagement.html#application-data 자동으로 삭제됩니다.

#### <a name="organizational-controls-for-data-stored-by-partner"></a>파트너가 저장한 데이터에 대한 조직 제어

조직의 관리자가 파트너 시스템에서 정보를 제어하는 방법에 대해 설명하는 방법 삭제, 보존, 감사, 보관, 최종 사용자 정책 등

>대부분의 데이터는 Azure 및 DB에 Cosmos 저장됩니다.
프로덕션 환경에 대한 액세스는 두 명으로 제한되고 이러한 관리자 계정은 MFA가 적용됩니다.
이러한 계정은 전용 계정으로 회사 계정과 다릅니다.
데이터는 사용 중이지 않은 모든 Azure 서비스에서 암호화됩니다.
프로덕션 환경에 대한 배포는 두 사용자만 변경을 승인할 수 있는 GitHub 환경의 전용 보호된 분기를 통해 자동화됩니다.

#### <a name="human-review-of-organizational-information"></a>조직 정보의 인적 검토

사람이 이 앱에서 수집하거나 저장하는 OII(조직 식별 정보) 데이터를 검토하거나 분석하는 데 관여하나요?

>예

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="mcas"

Microsoft Cloud App Security [카탈로그의](https://www.microsoft.com/enterprise-mobility-security/cloud-app-security) 정보가 아래에 표시됩니다.

<iframe height='1020' title='Microsoft Cloud App Security 정보' src='https://appmcasinfoprod.azurewebsites.net/#/dashboard/35853' frameborder='no' style='width: 100%;'></iframe>

<a href="https://appmcasinfoprod.azurewebsites.net/#/dashboard/35853" target="_blank">새 탭에서 보기</a>

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

