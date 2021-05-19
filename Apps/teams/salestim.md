---
title: SalesTim에 의한 SalesTim용 신청 정보
ms.author: elmalova
author: elenamalova
ms.date: 10/27/2020
ms.topic: article
ms.service: attestation
certification_type: certified
description: SalesTim에 대한 사용 가능한 모든 보안 및 규정 준수 정보 정보, 데이터 처리 정책, Microsoft Cloud App Security 앱 카탈로그 정보 및 CSA STAR 레지스트리의 보안/규정 준수 정보.
zone_pivot_groups: app-info-data-mcas
ms.openlocfilehash: c9094f50723c7094f895d21f8a9569dedbb5863b
ms.sourcegitcommit: a44420a99a1a3a9d0e49f4be66f266e2d4ca7bbb
ms.translationtype: MT
ms.contentlocale: ko-KR
ms.lasthandoff: 05/19/2021
ms.locfileid: "52553919"
---
# <a name="salestim"></a>SalesTim

<p></p><a href="https://aka.ms/appcertification" alt="This Microsoft 365 Certified app has been reviewed by Microsoft against industry standards and controls for security, compliance, and data handling practices. Where applicable, Microsoft has verified the developer's claims of compliance with reasonable and effective practices." target="_blank"><img alt="Click here for more information on the Microsoft Certified app program." src="../media/certified.png" width="650" /></a>
<p>최종 업데이트: 2020년 10월 27일</p>

* <a href="https://teams.microsoft.com/l/app/589748de-ec98-4616-9063-e91c629bd1a4" target="_blank">Teams 스토어에서 보기</a>
* <a href="https://appsource.microsoft.com/product/office/WA200001393" target="_blank">앱소스에서 보기</a>

::: zone pivot="general"

### <a name="general-information"></a>일반 정보

SalesTim에서 Microsoft에 제공한 정보:

| **정보** | **응답** |
|:----------------|:-------------|
| 앱 이름 | SalesTim |
| ID | WA200001393 |
| 지원되는 Office 365 클라이언트 | Microsoft Teams |
| 파트너 회사 이름 | SalesTim |
| 파트너 웹사이트의 URL | [https://www.salestim.com](https://www.salestim.com) |
| 개인정보 처리방침의 URL | [https://www.salestim.com/legal/privacy](https://www.salestim.com/legal/privacy) |
| 이용 약관의 URL | [https://www.salestim.com/legal/tos](https://www.salestim.com/legal/tos) |

 [!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="data"

### <a name="how-the-app-handles-data"></a>앱이 데이터를 처리하는 방법

이 정보는 SalesTim에서 이 앱이 조직 데이터를 수집하고 저장하는 방법과 앱이 수집하는 데이터에 대한 조직이 가질 수 있는 제어에 대해 제공했습니다.

#### <a name="data-access-using-microsoft-graph"></a>Microsoft Graph 을 사용하여 데이터 액세스

이 [앱에서 필요한 Microsoft Graph 권한을 나열합니다.](https://docs.microsoft.com/graph/permissions-reference)

>| **사용 권한**  | **권한 유형(위임/응용 프로그램)** | **데이터가 수집되고 있습니까? 그것을 수집하기위한 정당화?** | **데이터가 저장되어 있습니까? 그것을 저장하는 정당화?** | **Azure AD 앱 ID** |
>|:----------------|:--------------------|:---------------------------------------------------|:--------------------------|:--------------------------|
>| 앱카탈로그.읽기쓰기.모든 것 | 위임 | 아니요 | 앱이 회사 앱 카탈로그에 자체 패키지를 설치하고 업데이트하도록 허용합니다. | 2a651f59-97ce-42bb-97d7-cf7a2af4b635 |
>| Directory.AccessAsUser.All | 위임 | 프로필 데이터가 아닌 일부 사용자 아이디만 저장하는&#8217;. | 사용자가 워크플로에서 승인자를 선택하는 등 응용 프로그램의 여러 위치에서 다른 사용자를 선택할 수 있습니다. | 2a651f59-97ce-42bb-97d7-cf7a2af4b635 |
>| Group.ReadWrite.All | 위임 | 그룹/팀 아이디만 저장해야&#8217;그룹/팀 콘텐츠를 저장하지&#8217;. | 앱이 그룹을 만들고 로그인 한 사용자를 대신하여 모든 그룹 속성 및 멤버십을 읽을 수 있습니다. 또한 그룹 소유자가 그룹을 관리하고 그룹 구성원이 그룹 콘텐츠를 업데이트할 수 있도록 허용합니다. | 2a651f59-97ce-42bb-97d7-cf7a2af4b635 |
>| 메일.보내기 | 위임 | 알림 날짜, 받는 사람(ID만), 요청 ID와 같은 이 작업의 메타데이터를 다시 저장하는&#8217;있습니다. | 승인 워크플로우 중에 앱이 예를 들어 알림 이메일을 보낼 수 있습니다. | 2a651f59-97ce-42bb-97d7-cf7a2af4b635 |
>| Sites.ReadWrite.All | 위임 | 일부 Azure 서비스를 사용하여 데이터를 저장하고 있습니다( 특히 Azure의 Redis 및 DB Cosmos | 팀 프로비저닝 프로세스 중에 앱이 팀과 연결된 드라이브(파일 및 폴더)를 관리할 수 있습니다. | 2a651f59-97ce-42bb-97d7-cf7a2af4b635 |
>| User.Read.All | 위임 | 프로필 데이터가 아닌 일부 사용자 아이디만 저장하는&#8217;. | 앱이 모든 사용자의 프로필 속성, 보고서 및 관리자의 전체 집합을 읽을 수 있습니다. 특히 잠재고객 타겟팅 프로세스 중에 현재 사용자 프로필을 기반으로 일부 콘텐츠를 필터링하는 데 사용됩니다. | 2a651f59-97ce-42bb-97d7-cf7a2af4b635 |
>| 오프라인 액세스 | 위임 | 아니요 | 앱이 사용자로서 일부 백그라운드 작업 및 작업을 수행할 수 있습니다. | 2a651f59-97ce-42bb-97d7-cf7a2af4b635 |


#### <a name="non-microsoft-services-used"></a>사용되지 Microsoft 서비스

앱이 Microsoft 가 아닌 서비스와 조직 데이터를 전송하거나 공유하는 경우 앱에서 사용하는 비Microsoft 서비스, 전송되는 데이터를 나열하고 앱이 이 정보를 전송해야 하는 이유에 대한 명분을 포함합니다.

>| **모든 Microsoft 서비스 OII가** |  **어떤 OII가 전송됩니까?** | **OII 전송에 대한 정당화?** |
>|:-------------------|:--------------------------|:--------------------------|
>| 우리는 인터콤을 주요 지원 응용 프로그램으로 사용하고 있습니다. Intercom에는 여기에 설명된 몇 가지 기본 사용자 프로필 정보가 포함될 수 있습니다. https://developers.salestim.com/platform/datamanagement.html#support-data |  | 우리는 GitHub API를 사용하여 프로덕션 환경에서 자동으로 문제를 생성하고 있습니다. 여기에 설명된 대로 GitHub 기술 로그를 https://developers.salestim.com/platform/datamanagement.html#error-reporting-data) 저장합니다. 이러한 문제와 로그는 몇 가지 기본 사용자 프로필 정보를 포함할 수 있습니다. 이러한 문제와 로그는 15일마다 자동으로 삭제됩니다. |

#### <a name="data-access-via-bots"></a>봇을 통한 데이터 액세스

이 앱에 봇 또는 메시징 확장 프로그램이 포함된 경우 최종 사용자 식별 정보(EUII): 팀의 모든 팀 구성원의 명단(이름, 성, 표시 이름, 이메일 주소)에 액세스하거나 추가된 채팅을 할 수 있습니다. 이 응용 프로그램은이 기능을 사용합니까?

>EUII에 액세스할 수 없습니다.


#### <a name="telemetry-data"></a>원격 분석 데이터

조직 식별 정보(OII) 또는 최종 사용자 식별 정보(EUII)가 이 응용 프로그램의 원격 분석 또는 로그에 표시됩니까? 그렇다면 저장되는 데이터와 보존 및 제거 정책은 무엇입니까?

>수집된 모든 데이터는 여기에 https://developers.salestim.com/platform/datamanagement.html#application-data 설명되어 있습니다: 설명된 바와 같이 로그는 15일 동안 일시적으로 저장된 다음 자동으로 삭제됩니다.

#### <a name="organizational-controls-for-data-stored-by-partner"></a>파트너가 저장한 데이터에 대한 조직 제어

조직의 관리자가 파트너 시스템에서 자신의 정보를 제어하는 방법을 설명해 보세요. 예를 들어 삭제, 보존, 감사, 보관, 최종 사용자 정책 등

>대부분의 데이터는 Azure Cosmos DB에 저장됩니다.
프로덕션 환경에 대한 액세스는 두 명으로 제한되며 이러한 관리자 계정은 MFA가 적용됩니다.
이러한 계정은 회사 계정과 다르며 전념적입니다.
데이터는 사용 중인 모든 Azure 서비스에서 암호화됩니다.
프로덕션 환경에 대한 배포는 GitHub 환경에서 전용 보호 지점을 통해 자동화되며, 여기서 두 사람만 변경 사항을 승인할 수 있습니다.

#### <a name="human-review-of-organizational-information"></a>조직 정보의 인간 검토

이 앱에서 수집하거나 저장되는 조직 식별 정보(OII) 데이터를 검토하거나 분석하는 데 관여하는 사람이 있습니까?

>예

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="mcas"

[Microsoft Cloud App Security](https://www.microsoft.com/enterprise-mobility-security/cloud-app-security) 카탈로그의 정보는 아래에 나타납니다.

<iframe height='1020' title='Microsoft Cloud App Security 정보' src='https://appmcasinfoprod.azurewebsites.net/#/dashboard/35853' frameborder='no' style='width: 100%;'></iframe>

<a href="https://appmcasinfoprod.azurewebsites.net/#/dashboard/35853" target="_blank">새 탭에서 보기</a>

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

