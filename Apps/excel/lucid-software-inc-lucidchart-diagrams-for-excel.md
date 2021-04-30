---
title: Lucid Software Inc의 Lucidchart 다이어그램에 Excel 응용 프로그램 정보
ms.author: elmalova
author: elenamalova
ms.date: 12/16/2019
ms.topic: article
ms.service: attestation
description: CSA STAR 레지스트리의 lucidchart 다이어그램, 데이터 Excel 정책, Microsoft Cloud App Security 앱 카탈로그 정보 및 보안/규정 준수 정보에 대해 사용 가능한 모든 보안 및 규정 준수 정보입니다.
zone_pivot_groups: app-info-data-mcas
ms.openlocfilehash: 42bb36d92b71f3ca303fe924ea3ac260854ac03f
ms.sourcegitcommit: e97156a6eaf1d5ec5c26fd14add210a92bacd944
ms.translationtype: MT
ms.contentlocale: ko-KR
ms.lasthandoff: 04/30/2021
ms.locfileid: "52094606"
---
# <a name="lucidchart-diagrams-for-excel"></a>Excel

<p></p>
<img alt="Publisher Attestation: The information on this page is based on a self-assessment report provided by the app developer on the security, compliance, and data handling practices followed by this app. Microsoft makes no guarantees regarding the accuracy of the information." src="../media/attested.png" width="650" />
<p>개발자가 마지막으로 업데이트한 날짜: 2019년 12월 16일</p>

* <a href="https://appsource.microsoft.com/product/office/WA104380194" target="_blank">AppSource의 보기</a>

::: zone pivot="general"

### <a name="general-information"></a>일반 정보

Lucid Software Inc에서 Microsoft에 제공하는 정보:

| **정보** | **응답** |
|:----------------|:-------------|
| 앱 이름 | Excel |
| ID | WA104380194 |
| Office 365 클라이언트 지원 | Excel 2016 Mac, Excel 2013 이상을 Windows 웹용 Excel |
| 파트너 회사 이름 | Lucid Software Inc |
| 파트너 웹 사이트의 URL | [https://www.lucidchart.com/](https://www.lucidchart.com/) |
| 개인 정보 취급 방침의 URL | [https://www.lucidchart.com/pages/privacy](https://www.lucidchart.com/pages/privacy) |
| 사용 약관 URL | [https://go.microsoft.com/fwlink/?LinkID=521715&amp;omkt=en-US](https://go.microsoft.com/fwlink/?LinkID=521715&amp;omkt=en-US) |

 [!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="data"

### <a name="how-the-app-handles-data"></a>앱이 데이터를 처리하는 방법

이 정보는 Lucid Software Inc.에서 이 앱이 조직 데이터를 수집 및 저장하는 방법 및 앱이 수집하는 데이터를 통해 조직이 제어할 수 있는 컨트롤에 대해 제공됩니다.

#### <a name="data-access-using-microsoft-graph"></a>Microsoft 365를 사용한 데이터 Graph

이 앱에 [Graph Microsoft 사용자 권한을](https://docs.microsoft.com/graph/permissions-reference) 나열합니다.

>| **사용 권한**  | **사용 권한 유형(위임/응용 프로그램)** | **데이터가 수집하나요? 수집의 사당성** | **데이터가 저장되어 있나요? 저장 사정이 있나요?** | **Azure AD 앱 ID** |
>|:----------------|:--------------------|:---------------------------------------------------|:--------------------------|:--------------------------|
>| 전자 메일 | 위임 | 이름 및 전자 메일 주소입니다. | 전자 메일, openid 및 프로필 권한을 통해 Lucidchart는 사용자에 대한 열린 토큰을 생성하고 필요한 경우 Lucidchart 계정을 등록할 수 있는 충분한 기본 정보를 얻을 수 있습니다. Microsoft에서 제공된 데이터를 확인하기 위해 응답이 서명된 공개 키를 요청합니다. SSO 흐름의 일부로 다른 데이터는 Microsoft로부터 수신되거나 Microsoft로 전송되지 않습니다. |  |
>| openid | 위임 | 이름 및 전자 메일 주소입니다. | 전자 메일, openid 및 프로필 권한을 통해 Lucidchart는 사용자에 대한 열린 토큰을 생성하고 필요한 경우 Lucidchart 계정을 등록할 수 있는 충분한 기본 정보를 얻을 수 있습니다. Microsoft에서 제공된 데이터를 확인하기 위해 응답이 서명된 공개 키를 요청합니다. SSO 흐름의 일부로 다른 데이터는 Microsoft로부터 수신되거나 Microsoft로 전송되지 않습니다. |  |
>| profile | 위임 | 이름 및 전자 메일 주소입니다. | 전자 메일, openid 및 프로필 권한을 통해 Lucidchart는 사용자에 대한 열린 토큰을 생성하고 필요한 경우 Lucidchart 계정을 등록할 수 있는 충분한 기본 정보를 얻을 수 있습니다. Microsoft에서 제공된 데이터를 확인하기 위해 응답이 서명된 공개 키를 요청합니다. SSO 흐름의 일부로 다른 데이터는 Microsoft로부터 수신되거나 Microsoft로 전송되지 않습니다. |  |

#### <a name="data-access-using-other-microsoft-apis"></a>다른 Microsoft API를 사용한 데이터 액세스

기본 제공 앱 및 추가 Microsoft 365 Microsoft Graph 기타 Microsoft API를 사용하여 OII(조직 식별 가능 정보)를 수집하거나 처리합니다. 이 앱에서 사용하는 Microsoft API를 Graph Microsoft API를 나열합니다.

>| **API** |  **OII가 수집하나요?** |  **수집되는 OII는 무엇입니까?** | **OII 수집의 사당성** | **OII가 저장되어 있나요?** | **OII 저장의 사당성** |
>|:-------------------|:-------------------|:--------------------------|:--------------------------|:---------------------------------------------------|:--------------------------|
>| JavaScript API for Office | 예 | Office OneDrive javascript SDK를 사용하여 OneDrive.open()을 사용하여 OneDrive 파일 선택기 열 수 있습니다. 액세스 토큰을 생성하지는 않습니다. 이러한 액세스 토큰은 생성되지 OneDrive 요청하지 않습니다. OneDrive 파일 선택기 SDK가 이 옵션을 사용할 수 있습니다. 사용자가 선택한 파일 이름만 표시됩니다. |  | 사용자가 파일 선택기에서 파일을 OneDrive 경우 파일 이름을 저장합니다. |  |

#### <a name="non-microsoft-services-used"></a>비영구 Microsoft 서비스

앱이 Microsoft가 아닌 서비스로 조직 데이터를 전송하거나 공유하는 경우 앱에서 사용하는 비 Microsoft 서비스, 전송되는 데이터를 나열하고 앱이 이 정보를 전송해야 하는 이유에 대한 사유를 포함합니다.

>| **모든 비 Microsoft 서비스 OII가 다음으로 전송됩니다.** |  **전송되는 OII는 무엇입니까?** | **OII 전송의 사당성** |
>|:-------------------|:--------------------------|:--------------------------|
>| Lucidchart 데이터는 AWS에 저장됩니다. |  | Microsoft API는 사용하지 않습니다. OpenID를 사용하여 SSO를 수행하기 위해 기본 사용자 데이터를 얻습니다. 파일 선택기 API를 사용하지만 선택을 통해 제출한 파일 외의 사용자 파일에 대한 액세스 권한을 부여하지는 않습니다. |



#### <a name="add-in-data-access"></a>추가 기능 데이터 액세스

이 앱이 조직의 데이터에 액세스하는 데 필요한 사용 권한, 이 사용 권한의 사당성 및 목적(앱에서 이 정보를 어떤 용도로 사용하나요?) 및 앱에서 해당 데이터베이스에 이 정보를 저장하는지 여부를 나열합니다.

>| **사용 권한**  | **설명** |
>|:----------------|:----------------|
>| ReadWrite Document | 문서를 읽고 변경할 수 있습니다. |
>| 데이터 보내기 | 인터넷을 통해 데이터를 보낼 수 있습니다. |

#### <a name="telemetry-data"></a>원격 분석 데이터

이 응용 프로그램의 원격 분석 또는 로그에 OII(조직 식별 정보) 또는 EUII(최종 사용자 식별 정보)가 나타나나요? 그렇다면 저장되는 데이터와 보존 및 제거 정책에 대해 설명하세요.

>보안 및 지원상의 이유로 전자 메일 및 IP 주소를 기록합니다. 로그에 대한 모든 액세스는 타사 시스템에서 실제로는 로그를 사용할 &amp; 수 없습니다. 로그에 액세스하려면 MFA가 필요합니다.

#### <a name="organizational-controls-for-data-stored-by-partner"></a>파트너가 저장한 데이터에 대한 조직 제어

조직의 관리자가 파트너 시스템에서 정보를 제어하는 방법에 대해 설명하는 방법 삭제, 보존, 감사, 보관, 최종 사용자 정책 등

>Lucidchart 데이터는 AWS에 저장됩니다. 미사일 및 전송 중으로 암호화됩니다. Lucidchart는 최소 권한 및 MFA의 규칙을 사용 합니다.

#### <a name="human-review-of-organizational-information"></a>조직 정보의 인적 검토

사람이 이 앱에서 수집하거나 저장하는 OII(조직 식별 정보) 데이터를 검토하거나 분석하는 데 관여하나요?

>아니요

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="mcas"

Microsoft Cloud App Security [카탈로그의](https://www.microsoft.com/enterprise-mobility-security/cloud-app-security) 정보가 아래에 표시됩니다.

<iframe height='1020' title='Microsoft Cloud App Security 정보' src='https://appmcasinfoprod.azurewebsites.net/#/dashboard/12761' frameborder='no' style='width: 100%;'></iframe>

<a href="https://appmcasinfoprod.azurewebsites.net/#/dashboard/12761" target="_blank">새 탭에서 보기</a>

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

