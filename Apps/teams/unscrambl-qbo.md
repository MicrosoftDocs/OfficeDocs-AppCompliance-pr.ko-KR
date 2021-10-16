---
title: Unscrambl의 qbo에 대한 응용 프로그램 정보
ms.author: elmalova
author: elenamalova
ms.date: 09/28/2021
ms.topic: article
ms.service: attestation
certification_type: attested
description: qbo에 사용할 수 있는 모든 보안 및 규정 준수 정보, 데이터 처리 정책, CSA STAR 레지스트리의 Microsoft Cloud App Security 앱 카탈로그 정보 및 보안/규정 준수 정보
zone_pivot_groups: app-info-data-mcas-identity
ms.openlocfilehash: 74734019fc35da357552739b3ddabbd223cf541d
ms.sourcegitcommit: 9dab9c9dacb9c6daaa6b0041ccc8a49bafdad331
ms.translationtype: MT
ms.contentlocale: ko-KR
ms.lasthandoff: 10/16/2021
ms.locfileid: "60410812"
---
# <a name="qbo"></a>qbo

<p></p>
<img alt="Publisher Attestation: The information on this page is based on a self-assessment report provided by the app developer on the security, compliance, and data handling practices followed by this app. Microsoft makes no guarantees regarding the accuracy of the information." src="../media/attested.png" width="650" />
<p>개발자가 마지막으로 업데이트한 날짜: 2021년 9월 28일</p>

* <a href="https://teams.microsoft.com/l/app/834c6939-152c-450b-a305-c65b4dd5d1c7" target="_blank">저장소의 Teams 보기</a>
* <a href="https://appsource.microsoft.com/product/office/WA200001708" target="_blank">AppSource의 보기</a>

::: zone pivot="general"

### <a name="general-information"></a>일반 정보

Unscrambl에서 Microsoft에 제공한 정보:

| **정보** | **응답** |
|:----------------|:-------------|
| 앱 이름 | qbo |
| ID | WA200001708 |
| Office 365 클라이언트 지원 | Microsoft Teams |
| 파트너 회사 이름 | Unscrambl |
| 파트너 웹 사이트의 URL | [https://unscrambl.com](https://unscrambl.com) |
| 응용 프로그램 Teams 페이지의 URL입니다. | [https://qbo.ai](https://qbo.ai) |
| 개인 정보 취급 방침의 URL | [https://qbo.ai/legal/](https://qbo.ai/legal/) |
| 사용 약관 URL | [https://qbo.ai/legal/#service](https://qbo.ai/legal/#service) |

 [!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="data"

### <a name="how-the-app-handles-data"></a>앱이 데이터를 처리하는 방법

이 정보는 Unscrambl에서 이 앱이 조직 데이터를 수집하고 저장하는 방법 및 앱이 수집하는 데이터를 통해 조직이 사용할 컨트롤에 대해 제공됩니다.

#### <a name="data-access-using-microsoft-graph"></a>Microsoft 365를 사용한 데이터 Graph

이 앱에 [Graph Microsoft 사용자 권한을](https://docs.microsoft.com/graph/permissions-reference) 나열합니다.

>이 응용 프로그램은 Microsoft 응용 프로그램을 Graph.

#### <a name="data-access-using-other-microsoft-apis"></a>다른 Microsoft API를 사용한 데이터 액세스

기본 제공 앱 및 추가 Microsoft 365 Microsoft Graph 기타 Microsoft API를 사용하여 OII(조직 식별 가능 정보)를 수집하거나 처리합니다. 이 앱에서 사용하는 Microsoft API를 Graph Microsoft API를 나열합니다.

>| **API** |  **OII가 수집하나요?** |  **수집되는 OII는 무엇입니까?** | **OII 수집의 사당성** | **OII가 저장되어 있나요?** | **OII 저장의 사당성** |
>|:--------|:-----------------------|:----------------------------|:--------------------------------------|:-------------------|:-----------------------------------|
>| 봇 프레임워크 API | 예 | 사용자의 전자 메일에서 식별된 도메인 이름 | 사용자가 원하는 경우 보고서를 보내기 위해 전자 메일을 수집합니다. | 전자 메일만 | 사용자 프로필의 일부로 저장 |

#### <a name="non-microsoft-services-used"></a>비영구 Microsoft 서비스

앱이 Microsoft가 아닌 서비스로 조직 데이터를 전송하거나 공유하는 경우 앱에서 사용하는 비 Microsoft 서비스, 전송되는 데이터를 나열하고 앱이 이 정보를 전송해야 하는 이유에 대한 사유를 포함합니다.

>비영구 Microsoft 서비스 사용되지 않습니다.

#### <a name="data-access-via-bots"></a>봇을 통한 데이터 액세스

이 앱에 봇 또는 메시징 확장이 포함되어 있는 경우 팀 구성원의 명단(이름, 성, 표시 이름, 전자 메일 주소)이나 팀 구성원이 추가된 채팅의 최종 사용자 식별 정보(EUII)에 액세스할 수 있습니다. 이 앱이 이 기능을 사용하나요?

>| **EUII 액세스의 사유는 무엇입니까?**  | **EUII가 데이터베이스에 저장되어 있나요?** | **EUII 저장의 사유는 무엇입니까?** |
>|:---------------------------------------|:-----------------------------------|:------------------------------------|
>| 사용자가 보고서의 PDF를 직접 전자 메일로 보낼 수 있도록 하는 앱 기능이 있습니다. | 전자 메일 주소 | 사용자가 보고서의 PDF를 직접 전자 메일로 보낼 수 있도록 하는 앱 기능이 있습니다. 이 기능은 사용자 프로필의 일부로 저장됩니다. |


#### <a name="telemetry-data"></a>원격 분석 데이터

이 응용 프로그램의 원격 분석 또는 로그에 OII(조직 식별 정보) 또는 EUII(최종 사용자 식별 정보)가 나타나나요? 그렇다면 저장되는 데이터와 보존 및 제거 정책에 대해 설명하세요.

>응용 프로그램 원격 분석 또는 로그에 OII 또는 EUII가 나타나지 않습니다.

#### <a name="organizational-controls-for-data-stored-by-partner"></a>파트너가 저장한 데이터에 대한 조직 제어

조직의 관리자가 파트너 시스템에서 정보를 제어하는 방법에 대해 설명하는 방법 삭제, 보존, 감사, 보관, 최종 사용자 정책 등

>이 데이터는 Azure의 VM(동남아시아)에서 호스트되는 MariaDB에 저장됩니다. VM에 대한 액세스는 IP가 제한되고 암호로 보호되고 DB에 대한 액세스도 암호로 보호됩니다.

#### <a name="human-review-of-organizational-information"></a>조직 정보의 인적 검토

사람이 이 앱에서 수집하거나 저장하는 OII(조직 식별 정보) 데이터를 검토하거나 분석하는 데 관여하나요?

>아니요

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="mcas"

Microsoft Cloud App Security [카탈로그의](https://www.microsoft.com/enterprise-mobility-security/cloud-app-security) 정보가 아래에 표시됩니다.

<iframe height='1020' title='Microsoft Cloud App Security 정보' src='https://appmcasinfoprod.azurewebsites.net/#/dashboard/36419' frameborder='no' style='width: 100%;'></iframe>

<a href="https://appmcasinfoprod.azurewebsites.net/#/dashboard/36419" target="_blank">새 탭에서 보기</a>

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="identity"

### <a name="identity-information"></a>ID 정보

이 정보는 Unscrambl에서 이 앱이 인증, 권한 부여, 응용 프로그램 등록 모범 사례 및 기타 ID 조건을 처리하는 방법에 대해 제공했습니다.

| **정보** | **응답** |
|:----------------|:-------------|
| Microsoft Identify Platform(Azure AD)과 통합하나요?  | 아니요 |

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

