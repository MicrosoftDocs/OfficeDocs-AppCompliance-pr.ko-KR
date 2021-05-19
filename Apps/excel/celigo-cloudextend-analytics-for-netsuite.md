---
title: 셀리고 클라우드익스텐션에 의해 넷스위트에 대한 클라우드 확장 분석을 위한 애플리케이션 정보
ms.author: elmalova
author: elenamalova
ms.date: 04/09/2021
ms.topic: article
ms.service: attestation
certification_type: attested
description: NetSuite용 CloudExtend Analytics, 데이터 처리 정책, Microsoft Cloud App Security 앱 카탈로그 정보 및 CSA STAR 레지스트리의 보안/규정 준수 정보에 대한 사용 가능한 모든 보안 및 규정 준수 정보.
zone_pivot_groups: app-info-data-mcas-identity
ms.openlocfilehash: 12a973e35124a98ab2e284b40c536dabc8ae21a0
ms.sourcegitcommit: a44420a99a1a3a9d0e49f4be66f266e2d4ca7bbb
ms.translationtype: MT
ms.contentlocale: ko-KR
ms.lasthandoff: 05/19/2021
ms.locfileid: "52549708"
---
# <a name="cloudextend-analytics-for-netsuite"></a>넷스위트용 클라우드익스텐션

<p></p>
<img alt="Publisher Attestation: The information on this page is based on a self-assessment report provided by the app developer on the security, compliance, and data handling practices followed by this app. Microsoft makes no guarantees regarding the accuracy of the information." src="../media/attested.png" width="650" />
<p>최종 업데이트: 2021년 4월 9일</p>

* <a href="https://appsource.microsoft.com/product/office/WA200002784" target="_blank">앱소스에서 보기</a>

::: zone pivot="general"

### <a name="general-information"></a>일반 정보

셀리고 클라우드에서 제공하는 정보 마이크로 소프트에 확장 :

| **정보** | **응답** |
|:----------------|:-------------|
| 앱 이름 | 넷스위트용 클라우드익스텐션 |
| ID | WA200002784 |
| 지원되는 Office 365 클라이언트 | Excel 2016 또는 그 이후에 는 맥, Excel 2016 또는 Windows 이후, 웹용 Excel |
| 파트너 회사 이름 | 셀리고 클라우드익스텐더 |
| 파트너 웹사이트의 URL | [https://appsource.microsoft.com/marketplace/apps?product=of...](https://appsource.microsoft.com/marketplace/apps?product=office) |
| 개인정보 처리방침의 URL | [https://www.celigo.com/privacy](https://www.celigo.com/privacy) |
| 이용 약관의 URL | [https://www.cloudextend.io/agreements/ssa/2019-12](https://www.cloudextend.io/agreements/ssa/2019-12) |

 [!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="data"

### <a name="how-the-app-handles-data"></a>앱이 데이터를 처리하는 방법

이 정보는 Celigo CloudExtend에서 이 앱이 조직 데이터를 수집하고 저장하는 방법과 앱이 수집하는 데이터에 대한 조직이 가질 수 있는 제어에 대해 제공했습니다.

#### <a name="data-access-using-microsoft-graph"></a>Microsoft Graph 을 사용하여 데이터 액세스

이 [앱에서 필요한 Microsoft Graph 권한을 나열합니다.](https://docs.microsoft.com/graph/permissions-reference)

>| **사용 권한**  | **권한 유형(위임/응용 프로그램)** | **데이터가 수집되고 있습니까? 그것을 수집하기위한 정당화?** | **데이터가 저장되어 있습니까? 그것을 저장하는 정당화?** | **Azure AD 앱 ID** |
>|:----------------|:--------------------|:---------------------------------------------------|:--------------------------|:--------------------------|
>| Directory.Read.All | 둘다 | 사용자가 사이트를 통해 공유된 통합 문서 정보를 얻을 수 있는 액세스 권한이 있는 사이트 모음 읽기 | 사이트 저장소를 저장하여 통합 문서오프라인으로 액세스할 수 있습니다. | 7040f194-bf08-400e-acb1-69df7939416a |
>| Files.ReadWrite.All | 둘다 | 테이블 및 시트와 같은 통합 문서 콘텐츠를 읽고 해당 테이블에 콘텐츠를 쓸 수 있습니다. | 웹 URL, 통합 문서 ID 및 오프라인으로 액세스할 수 있는 통합 문서의 위치와 같은 통합 문서 세부 정보 | 7040f194-bf08-400e-acb1-69df7939416a |


#### <a name="non-microsoft-services-used"></a>사용되지 Microsoft 서비스

앱이 Microsoft 가 아닌 서비스와 조직 데이터를 전송하거나 공유하는 경우 앱에서 사용하는 비Microsoft 서비스, 전송되는 데이터를 나열하고 앱이 이 정보를 전송해야 하는 이유에 대한 명분을 포함합니다.

>| **모든 Microsoft 서비스 OII가** |  **어떤 OII가 전송됩니까?** | **OII 전송에 대한 정당화?** |
>|:-------------------|:--------------------------|:--------------------------|
>| 충전비, 넷스위트, 세일즈포스, 인터콤, 로그로켓, 아마존 AWS | Org 이름, NetSuite 계정 번호, 조직 이메일 주소의 도메인, 청구 연락처 정보 | 라이선스 프로비저닝, 유효성 검사 및 청구 고객 지원, 문제 해결 및 계정 관리 |



#### <a name="telemetry-data"></a>원격 분석 데이터

조직 식별 정보(OII) 또는 최종 사용자 식별 정보(EUII)가 이 응용 프로그램의 원격 분석 또는 로그에 표시됩니까? 그렇다면 저장되는 데이터와 보존 및 제거 정책은 무엇입니까?

>이메일 주소, 

#### <a name="organizational-controls-for-data-stored-by-partner"></a>파트너가 저장한 데이터에 대한 조직 제어

조직의 관리자가 파트너 시스템에서 자신의 정보를 제어하는 방법을 설명해 보세요. 예를 들어 삭제, 보존, 감사, 보관, 최종 사용자 정책 등

>해당 없음

#### <a name="human-review-of-organizational-information"></a>조직 정보의 인간 검토

이 앱에서 수집하거나 저장되는 조직 식별 정보(OII) 데이터를 검토하거나 분석하는 데 관여하는 사람이 있습니까?

>아니요

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="mcas"

[Microsoft Cloud App Security](https://www.microsoft.com/enterprise-mobility-security/cloud-app-security) 카탈로그의 정보는 아래에 나타납니다.

<iframe height='1020' title='Microsoft Cloud App Security 정보' src='https://appmcasinfoprod.azurewebsites.net/#/dashboard/14008' frameborder='no' style='width: 100%;'></iframe>

<a href="https://appmcasinfoprod.azurewebsites.net/#/dashboard/14008" target="_blank">새 탭에서 보기</a>

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="identity"

### <a name="identity-information"></a>신원 정보

이 정보는 Celigo Cloud에서 이 앱이 인증, 권한 부여, 응용 프로그램 등록 모범 사례 및 기타 ID 기준을 처리하는 방법에 대해 제공했습니다.

| **정보** | **응답** |
|:----------------|:-------------|
| Microsoft 식별 플랫폼(Azure AD)과 통합합니까?  | 예 |
| Microsoft ID 플랫폼 통합 검사 목록에 설명된 모든 적용 가능한 모범 사례를 검토하고 준수했습니까?  | 예 |
| 앱에서 인증에 MSAL(Microsoft 인증 라이브러리)을 사용합니까? | 아니요 |
| 앱이 조건부 액세스 정책을 지원합니까? | 아니요 |
| 앱에서 시나리오에 대한 최소 권한 권한을 요청합니까? | 예 |
| 앱의 정적 등록 권한은 앱이 동적으로 점진적으로 요청하는 권한을 정확하게 반영합니까? | 예 |
| 앱이 다중 테넌션을 지원합니까? | 예 |
| 앱에 기밀 클라이언트가 있습니까? | 아니요 |
| 앱에 등록된 URI(리디렉션 통합 리소스 식별자)를 모두 소유하고 있습니까? | 예 |
| 앱의 경우 무엇을 사용하지 않으려습니까? | - 와일드카드 리디렉션 URI,<br/>- OAuth2 암시적 Flow, SPA에 필요한 경우가 아니면<br/>- 리소스 소유자 암호 자격 증명(ROPC) 흐름 |
| 앱에서 웹 API가 노출됩니까? | 예 |
| 권한 모델은 클라이언트 앱이 적절한 동의를 받는 경우에만 호출을 성공시킬 수 있습니까? | 예 |
| 앱에서 미리 보기 API를 사용합니까? | 아니요 |
| 앱에서 비하 API를 사용합니까? | 아니요 |

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end
