---
title: 주식회사 AvePoint의 AVA 신청 정보
ms.author: elmalova
author: elenamalova
ms.date: 03/23/2020
ms.topic: article
ms.service: attestation
certification_type: attested
description: AVA에 대한 사용 가능한 모든 보안 및 규정 준수 정보 정보, 데이터 처리 정책, Microsoft Cloud App Security 앱 카탈로그 정보, CSA STAR 레지스트리의 보안/규정 준수 정보.
zone_pivot_groups: app-info-data-mcas
ms.openlocfilehash: 6176bc86a6d382285623d3e3286852afd4a4ff96
ms.sourcegitcommit: a44420a99a1a3a9d0e49f4be66f266e2d4ca7bbb
ms.translationtype: MT
ms.contentlocale: ko-KR
ms.lasthandoff: 05/19/2021
ms.locfileid: "52552369"
---
# <a name="ava"></a>AVA

<p></p>
<img alt="Publisher Attestation: The information on this page is based on a self-assessment report provided by the app developer on the security, compliance, and data handling practices followed by this app. Microsoft makes no guarantees regarding the accuracy of the information." src="../media/attested.png" width="650" />
<p>최종 업데이트: 2020년 3월 23일</p>

* <a href="https://teams.microsoft.com/l/app/93106045-6f96-41e3-8a9d-694b6bbcac60" target="_blank">Teams 스토어에서 보기</a>
* <a href="https://appsource.microsoft.com/product/office/WA104381883" target="_blank">앱소스에서 보기</a>

::: zone pivot="general"

### <a name="general-information"></a>일반 정보

AvePoint, Inc.에서 마이크로소프트에 제공 하는 정보:

| **정보** | **응답** |
|:----------------|:-------------|
| 앱 이름 | AVA |
| ID | WA104381883 |
| 지원되는 Office 365 클라이언트 | Microsoft Teams |
| 파트너 회사 이름 | AvePoint, Inc. |
| 파트너 웹사이트의 URL | [https://www.avepoint.com](https://www.avepoint.com) |
| Teams 응용 프로그램 정보 페이지의 URL | [https://www.avepoint.com/support/](https://www.avepoint.com/support/) |
| 개인정보 처리방침의 URL | [https://www.avepoint.com/privacy-policy](https://www.avepoint.com/privacy-policy) |
| 이용 약관의 URL | [https://www.avepoint.com/company/terms-of-use](https://www.avepoint.com/company/terms-of-use) |

 [!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="data"

### <a name="how-the-app-handles-data"></a>앱이 데이터를 처리하는 방법

이 정보는 AvePoint, Inc.에서 이 앱이 조직 데이터를 수집하고 저장하는 방법과 앱이 수집하는 데이터에 대한 조직이 가질 수 있는 제어에 대해 제공했습니다.

#### <a name="data-access-using-microsoft-graph"></a>Microsoft Graph 을 사용하여 데이터 액세스

이 [앱에서 필요한 Microsoft Graph 권한을 나열합니다.](https://docs.microsoft.com/graph/permissions-reference)

>| **사용 권한**  | **권한 유형(위임/응용 프로그램)** | **데이터가 수집되고 있습니까? 그것을 수집하기위한 정당화?** | **데이터가 저장되어 있습니까? 그것을 저장하는 정당화?** | **Azure AD 앱 ID** |
>|:----------------|:--------------------|:---------------------------------------------------|:--------------------------|:--------------------------|
>| 메일.읽기 쓰기.공유 | 위임 | 없음 | 사용자의 전자 메일을 검색하고 이메일을 지정된 폴더로 이동 | 6f30434d-3cfa-4cfa-4cf8-9810-6fcf79ae750a |
>| User.Read | 위임 |  사용자 액세스 토큰 - 사용자의 데이터 검색 및 복원에 사용 | 사용자가 로그인하여 앱에 액세스 토큰을 제공할 수 있습니다. | 6f30434d-3cfa-4cfa-4cf8-9810-6fcf79ae750a |
>| User.ReadWrite | 위임 | 디스플레이 이름, 사용자 PrincipalName, JobTitle, 조직, 국가, MySiteUrl - 응용 프로그램을 사용하는 사용자의 기본 정보를 기록 | 사용자의 기본 프로필 정보 얻기 | 6f30434d-3cfa-4cfa-4cf8-9810-6fcf79ae750a |

#### <a name="data-access-using-other-microsoft-apis"></a>다른 Microsoft API를 사용한 데이터 액세스

Microsoft 365 기반으로 구축된 앱 및 추가 기능을 사용하면 Microsoft Graph 이외의 추가 Microsoft API를 사용하여 조직 식별 정보(OII)를 수집하거나 처리할 수 있습니다. 이 응용 프로그램이 사용하는 마이크로 소프트 이외의 마이크로 소프트 API를 나열할 Graph.

>| **API** |  **OII가 수집되고 있습니까?** |  **어떤 OII가 수집됩니까?** | **OII수집을 위한 정당성?** | **OII가 저장되어 있습니까?** | **OII를 저장하는 정당화?** |
>|:-------------------|:-------------------|:--------------------------|:--------------------------|:---------------------------------------------------|:--------------------------|
>| SharePoint REST API | 예 | 사용자의 개인 사이트에서 파일을 검색하고 이러한 파일을 복원합니다. AllSites.관리 권한이 필요합니다. |  | 없음 |  |

#### <a name="non-microsoft-services-used"></a>사용되지 Microsoft 서비스

앱이 Microsoft 가 아닌 서비스와 조직 데이터를 전송하거나 공유하는 경우 앱에서 사용하는 비Microsoft 서비스, 전송되는 데이터를 나열하고 앱이 이 정보를 전송해야 하는 이유에 대한 명분을 포함합니다.

>비Microsoft 서비스 사용되지 않습니다.

#### <a name="data-access-via-bots"></a>봇을 통한 데이터 액세스

이 앱에 봇 또는 메시징 확장 프로그램이 포함된 경우 최종 사용자 식별 정보(EUII): 팀의 모든 팀 구성원의 명단(이름, 성, 표시 이름, 이메일 주소)에 액세스하거나 추가된 채팅을 할 수 있습니다. 이 응용 프로그램은이 기능을 사용합니까?

>EUII에 액세스할 수 없습니다.


#### <a name="telemetry-data"></a>원격 분석 데이터

조직 식별 정보(OII) 또는 최종 사용자 식별 정보(EUII)가 이 응용 프로그램의 원격 분석 또는 로그에 표시됩니까? 그렇다면 저장되는 데이터와 보존 및 제거 정책은 무엇입니까?

>예, 사용자의 이메일 및 테넌트 ID가 로그에 나타납니다. 로그는 보안 위치에 저장되며 문제 해결 중에 권한이 있는 직원만 액세스할 수 있습니다. 로그는 보안 감사 목적으로 60일 후에 보관되며 1년 후에 삭제됩니다.

#### <a name="organizational-controls-for-data-stored-by-partner"></a>파트너가 저장한 데이터에 대한 조직 제어

조직의 관리자가 파트너 시스템에서 자신의 정보를 제어하는 방법을 설명해 보세요. 예를 들어 삭제, 보존, 감사, 보관, 최종 사용자 정책 등

>응용 프로그램의 데이터는 Azure SQL Database Azure Storage 저장됩니다. Azure SQL 및 Azure Storage 암호화가 활성화됩니다.
권한이 있는 관리자만 데이터에 액세스할 수 있습니다. 관리자가 로그인하려면 MFA가 필요합니다. 작업이 감사됩니다. IP 화이트리스팅은 데이터에 대한 액세스를 제한하는 데도 사용됩니다.

#### <a name="human-review-of-organizational-information"></a>조직 정보의 인간 검토

이 앱에서 수집하거나 저장되는 조직 식별 정보(OII) 데이터를 검토하거나 분석하는 데 관여하는 사람이 있습니까?

>아니요

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="mcas"

[Microsoft Cloud App Security](https://www.microsoft.com/enterprise-mobility-security/cloud-app-security) 카탈로그의 정보는 아래에 나타납니다.

<iframe height='1020' title='Microsoft Cloud App Security 정보' src='https://appmcasinfoprod.azurewebsites.net/#/dashboard/35842' frameborder='no' style='width: 100%;'></iframe>

<a href="https://appmcasinfoprod.azurewebsites.net/#/dashboard/35842" target="_blank">새 탭에서 보기</a>

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

