---
title: Application Information for Salesforce by salesforce.com
ms.author: elmalova
author: elenamalova
ms.date: 12/16/2019
ms.topic: article
ms.service: attestation
certification_type: attested
description: Salesforce에 사용할 수 있는 모든 보안 및 규정 준수 정보, 데이터 처리 정책, CSA STAR 레지스트리의 Microsoft Cloud App Security 앱 카탈로그 정보 및 보안/규정 준수 정보
zone_pivot_groups: app-info-data-mcas
ms.openlocfilehash: b5999dd08ed27ce75bc958e431c0974e10830a3c
ms.sourcegitcommit: 65d4afba6f46d45315b2a90d2b21ce1737707e7b
ms.translationtype: MT
ms.contentlocale: ko-KR
ms.lasthandoff: 07/02/2021
ms.locfileid: "53281700"
---
# <a name="salesforce"></a>Salesforce

<p></p>
<img alt="Publisher Attestation: The information on this page is based on a self-assessment report provided by the app developer on the security, compliance, and data handling practices followed by this app. Microsoft makes no guarantees regarding the accuracy of the information." src="../media/attested.png" width="650" />
<p>개발자가 마지막으로 업데이트한 날짜: 2019년 12월 16일</p>

* <a href="https://appsource.microsoft.com/product/office/WA104379334" target="_blank">AppSource의 보기</a>

::: zone pivot="general"

### <a name="general-information"></a>일반 정보

Microsoft에 salesforce.com 정보:

| **정보** | **응답** |
|:----------------|:-------------|
| 앱 이름 | Salesforce |
| ID | WA104379334 |
| Office 365 클라이언트 지원 | Outlook 2013 이상은 Mac, Windows Outlook 2016 이상에서 웹용 Outlook |
| 파트너 회사 이름 | salesforce.com |
| 파트너 웹 사이트의 URL | [https://www.salesforce.com](https://www.salesforce.com) |
| 개인 정보 취급 방침의 URL | [https://www.salesforce.com/company/privacy/](https://www.salesforce.com/company/privacy/) |
| 사용 약관 URL | [https://store.office.com/en-us/WebAppLandingPage.aspx?p4=TC...](https://store.office.com/en-us/WebAppLandingPage.aspx?p4=TC&amp;p5=WA104379334&amp;cmu=en-US) |

 [!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="data"

### <a name="how-the-app-handles-data"></a>앱이 데이터를 처리하는 방법

이 정보는 이 salesforce.com 수집 및 저장하는 방법과 앱이 수집하는 데이터를 통해 조직이 하게 될 컨트롤에 대한 정보를 제공합니다.

#### <a name="data-access-using-microsoft-graph"></a>Microsoft 365를 사용한 데이터 Graph

이 앱에 [Graph Microsoft 사용자 권한을](https://docs.microsoft.com/graph/permissions-reference) 나열합니다.

>이 응용 프로그램은 Microsoft 응용 프로그램을 Graph.

#### <a name="data-access-using-other-microsoft-apis"></a>다른 Microsoft API를 사용한 데이터 액세스

기본 제공 앱 및 추가 Microsoft 365 Microsoft Graph 기타 Microsoft API를 사용하여 OII(조직 식별 가능 정보)를 수집하거나 처리합니다. 이 앱에서 사용하는 Microsoft API를 Graph Microsoft API를 나열합니다.

>| **API** |  **OII가 수집하나요?** |  **수집되는 OII는 무엇입니까?** | **OII 수집의 사당성** | **OII가 저장되어 있나요?** | **OII 저장의 사당성** |
>|:-------------------|:-------------------|:--------------------------|:--------------------------|:---------------------------------------------------|:--------------------------|
>| JavaScript API for Office | 예 | 추가 기능은 Office.js 및 EWS의 기능을 사용하여 사용자가 Salesforce에 로그인하기로 결정한 전자 메일에 대한 Outlook 첨부 파일을 복사합니다. 일정 쪽에서 유사한 기능을 사용하여 약속을 Salesforce에 기록합니다. |  | 추가 기능은 getUserIdentityTokenAsync와 같은 함수를 사용하여 현재 Outlook 사용자 ID, GetItem(.js 및 EWS)을 사용하여 Salesforce 레코드에 저장하는 경우 현재 전자 메일 메시지의 내용과 AdditionalProperties를 구하고 설정하며, EWS(GetAttachment)를 사용하여 Exchange 첨부 파일을 검색하고 쌍을 이루는 Salesforce 전자 메일인 UpdateItem(.js), GetFolder(.js)에 추가하여 초안 메시지를 만드는 데 사용되는 CreateItem(.js)을 가져올 수 있습니다. |  |
>| EWS(Exchange 웹 서비스) | 예 | 추가 기능은 Office.js 및 EWS의 기능을 사용하여 사용자가 Salesforce에 로그인하기로 결정한 전자 메일에 대한 Outlook 첨부 파일을 복사합니다. 일정 쪽에서 유사한 기능을 사용하여 약속을 Salesforce에 기록합니다. |  | 추가 기능은 getUserIdentityTokenAsync와 같은 함수를 사용하여 현재 Outlook 사용자 ID, GetItem(.js 및 EWS)을 사용하여 Salesforce 레코드에 저장하는 경우 현재 전자 메일 메시지의 내용과 AdditionalProperties를 구하고 설정하며, EWS(GetAttachment)를 사용하여 Exchange 첨부 파일을 검색하고 쌍을 이루는 Salesforce 전자 메일인 UpdateItem(.js), GetFolder(.js)에 추가하여 초안 메시지를 만드는 데 사용되는 CreateItem(.js)을 가져올 수 있습니다. |  |

#### <a name="non-microsoft-services-used"></a>비영구 Microsoft 서비스

앱이 Microsoft가 아닌 서비스로 조직 데이터를 전송하거나 공유하는 경우 앱에서 사용하는 비 Microsoft 서비스, 전송되는 데이터를 나열하고 앱이 이 정보를 전송해야 하는 이유에 대한 사유를 포함합니다.

>비영구 Microsoft 서비스 사용되지 않습니다.



#### <a name="telemetry-data"></a>원격 분석 데이터

이 응용 프로그램의 원격 분석 또는 로그에 OII(조직 식별 정보) 또는 EUII(최종 사용자 식별 정보)가 나타나나요? 그렇다면 저장되는 데이터와 보존 및 제거 정책에 대해 설명하세요.

>아니요

#### <a name="organizational-controls-for-data-stored-by-partner"></a>파트너가 저장한 데이터에 대한 조직 제어

조직의 관리자가 파트너 시스템에서 정보를 제어하는 방법에 대해 설명하는 방법 삭제, 보존, 감사, 보관, 최종 사용자 정책 등

>Salesforce 저장소에 대한 설명은 의 보안 가이드에 설명되어 있습니다. https://resources.docs.salesforce.com/222/latest/en-us/sfdc/pdf/salesforce_security_impl_guide.pdf

#### <a name="human-review-of-organizational-information"></a>조직 정보의 인적 검토

사람이 이 앱에서 수집하거나 저장하는 OII(조직 식별 정보) 데이터를 검토하거나 분석하는 데 관여하나요?

>아니요

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="mcas"

Microsoft Cloud App Security [카탈로그의](https://www.microsoft.com/enterprise-mobility-security/cloud-app-security) 정보가 아래에 표시됩니다.

<iframe height='1020' title='Microsoft Cloud App Security 정보' src='https://appmcasinfoprod.azurewebsites.net/#/dashboard/11114' frameborder='no' style='width: 100%;'></iframe>

<a href="https://appmcasinfoprod.azurewebsites.net/#/dashboard/11114" target="_blank">새 탭에서 보기</a>

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

