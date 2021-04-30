---
title: Wrike Inc.Office 문서에 대한 Wrike에 대한 응용 프로그램 정보
ms.author: elmalova
author: elenamalova
ms.date: 03/23/2020
ms.topic: article
ms.service: attestation
description: CSA STAR 레지스트리의 Office 문서, 데이터 처리 정책, Microsoft Cloud App Security 앱 카탈로그 정보 및 보안/규정 준수 정보에 대해 Wrike에 사용할 수 있는 모든 보안 및 규정 준수 정보입니다.
zone_pivot_groups: app-info-data-mcas
ms.openlocfilehash: 6ecbf74b4ef8e3f4203e01d0039b0573070e071e
ms.sourcegitcommit: e97156a6eaf1d5ec5c26fd14add210a92bacd944
ms.translationtype: MT
ms.contentlocale: ko-KR
ms.lasthandoff: 04/30/2021
ms.locfileid: "52095779"
---
# <a name="wrike-for-office-documents"></a>Office 문서용 Wrike

<p></p><a href="https://aka.ms/appcertification" alt="This Microsoft 365 Certified app has been reviewed by Microsoft against industry standards and controls for security, compliance, and data handling practices. Where applicable, Microsoft has verified the developer's claims of compliance with reasonable and effective practices." target="_blank"><img alt="Click here for more information on the Microsoft Certified app program." src="../media/certified.png" width="650" /></a>
<p>개발자가 마지막으로 업데이트한 날짜: 2020년 3월 23일</p>

* <a href="https://appsource.microsoft.com/product/office/WA104379841" target="_blank">AppSource의 보기</a>

::: zone pivot="general"

### <a name="general-information"></a>일반 정보

Wrike Inc.에서 Microsoft에 제공한 정보:

| **정보** | **응답** |
|:----------------|:-------------|
| 앱 이름 | Office 문서용 Wrike |
| ID | WA104379841 |
| Office 365 클라이언트 지원 | Excel 2016 Windows, Word 201 Windows 3 이상, Windows, PowerPoint 2013 이상에 있는 Windows, Excel 2016 이상, mac, 웹용 Excel, Word 2016 or later on Mac, 웹용 Word, PowerPoint 2016 or later on Mac, 웹용 PowerPoint |
| 파트너 회사 이름 | Wrike Inc. |
| 파트너 웹 사이트의 URL | [https://wrike.com/](https://wrike.com/) |
| 개인 정보 취급 방침의 URL | [https://www.wrike.com/privacy](https://www.wrike.com/privacy) |
| 사용 약관 URL | [https://go.microsoft.com/fwlink/?LinkID=521715&amp;omkt=en-US](https://go.microsoft.com/fwlink/?LinkID=521715&amp;omkt=en-US) |

 [!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="data"

### <a name="how-the-app-handles-data"></a>앱이 데이터를 처리하는 방법

이 정보는 Wrike Inc.에서 이 앱이 조직 데이터를 수집 및 저장하는 방법과 조직에서 수집하는 데이터를 통해 조직이 하게 될 컨트롤에 대해 제공합니다.

#### <a name="data-access-using-microsoft-graph"></a>Microsoft 365를 사용한 데이터 Graph

이 앱에 [Graph Microsoft 사용자 권한을](https://docs.microsoft.com/graph/permissions-reference) 나열합니다.

>이 응용 프로그램은 Microsoft 응용 프로그램을 Graph.

#### <a name="data-access-using-other-microsoft-apis"></a>다른 Microsoft API를 사용한 데이터 액세스

기본 제공 앱 및 추가 Microsoft 365 Microsoft Graph 기타 Microsoft API를 사용하여 OII(조직 식별 가능 정보)를 수집하거나 처리합니다. 이 앱에서 사용하는 Microsoft API를 Graph Microsoft API를 나열합니다.

>| **API** |  **OII가 수집하나요?** |  **수집되는 OII는 무엇입니까?** | **OII 수집의 사당성** | **OII가 저장되어 있나요?** | **OII 저장의 사당성** |
>|:-------------------|:-------------------|:--------------------------|:--------------------------|:---------------------------------------------------|:--------------------------|
>| JavaScript API for Office | 예 | 추가 기능에서는 Office.js API를 사용하여 응용 프로그램과 Office 통합합니다. |  | Wrike의 데이터베이스에는 조직 데이터가 저장되지 않습니다. |  |

#### <a name="non-microsoft-services-used"></a>비영구 Microsoft 서비스

앱이 Microsoft가 아닌 서비스로 조직 데이터를 전송하거나 공유하는 경우 앱에서 사용하는 비 Microsoft 서비스, 전송되는 데이터를 나열하고 앱이 이 정보를 전송해야 하는 이유에 대한 사유를 포함합니다.

>| **모든 비 Microsoft 서비스 OII가 다음으로 전송됩니다.** |  **전송되는 OII는 무엇입니까?** | **OII 전송의 사당성** |
>|:-------------------|:--------------------------|:--------------------------|
>| Wrike는 일부 데이터에 액세스할 수 있는 다음 공급업체와 통합됩니다. Marketo는 서비스를 전자 메일로 캡처하는 전자 메일입니다. 이름과 전자 메일만 제공됩니다. Outreach는 클라우드 기반 판매 계약입니다. 이름과 전자 메일만 제공됩니다. Salesforce CRM 시스템 - 고객의 연락처 정보 및 대금 청구(중요한 데이터 없음)가 있습니다. Zuora - 청구 및 인보이스 고객. 모든 공급업체에 DPA가 있습니다. |  | JS Office API를 사용하나 조직 정보를 수집/처리/저장하지는 않습니다. |



#### <a name="add-in-data-access"></a>추가 기능 데이터 액세스

이 앱이 조직의 데이터에 액세스하는 데 필요한 사용 권한, 이 사용 권한의 사당성 및 목적(앱에서 이 정보를 어떤 용도로 사용하나요?) 및 앱에서 해당 데이터베이스에 이 정보를 저장하는지 여부를 나열합니다.

>| **사용 권한**  | **설명** |
>|:----------------|:----------------|
>| ReadWrite Document | 문서를 읽고 변경할 수 있습니다. |
>| 데이터 보내기 | 인터넷을 통해 데이터를 보낼 수 있습니다. |

#### <a name="telemetry-data"></a>원격 분석 데이터

이 응용 프로그램의 원격 분석 또는 로그에 OII(조직 식별 정보) 또는 EUII(최종 사용자 식별 정보)가 나타나나요? 그렇다면 저장되는 데이터와 보존 및 제거 정책에 대해 설명하세요.

>아니요

#### <a name="organizational-controls-for-data-stored-by-partner"></a>파트너가 저장한 데이터에 대한 조직 제어

조직의 관리자가 파트너 시스템에서 정보를 제어하는 방법에 대해 설명하는 방법 삭제, 보존, 감사, 보관, 최종 사용자 정책 등

>Wrike에는 고객 메타데이터를 기반으로 액세스 제어를 통해 데이터를&#8217; 데이터를 논리적으로 분할 수 있는 다중 테넌트 아키텍처가 있습니다. 이 메타데이터는 특정 Wrike 계정 내의 역할 기반 액세스 규칙에 따라 특정 테넌트 및 해당 액세스 권한과 연결됩니다. 데이터는 논리적으로 격리되고 분리되어 있으며, 데이터 액세스는 보안 및 개인 정보를 보장하기 위해 응용 프로그램을 통해서만 사용할 수 있습니다. 응용 프로그램 수준의 보안은 테넌트가 다른 테넌트가 소유한 응용 프로그램 데이터에 액세스하거나 수정하지 않습니다. Wrike의 응용 프로그램에는 광범위한 인증, 역할 기반 액세스 제어, 권한 부여 및 데이터 공유 및 제어 메커니즘이 있습니다(권한 있는 사용자에 대한 데이터 액세스만 허용 https://help.wrike.com/hc/en-us/articles/209603589-Access-Roles https://help.wrike.com/hc/en-us/articles/209602969) 참조). 또한 웹 응용 프로그램과 API를 통해 파일 저장소의 Wrike 서버에 업로드된 사용자 파일에 대해 미사용 암호화가 적용됩니다. 파일은 AES 256비트 암호화를 사용하여 자동으로 암호화됩니다. 또한 모든 서버는 파일 시스템 암호화를 사용하여 미사용으로 암호화되며, Wrike는 고객이 관리하는 암호화 키에 대해 Wrike 잠금 추가 기능을 제공합니다. 및 를 https://www.wrike.com/add-on-wrike-lock/ https://help.wrike.com/hc/en-us/articles/360012347934-Wrike-Lock 참조하세요. Wrike는 데이터 보안의 추가 계층으로 감사 및 보고 기능을 제공합니다. 이 기능을 사용하면 관리자가 전체 보안 검토를 수행하면서 Wrike 계정에서 진행되는 내용을 보다 쉽게 볼 수 있습니다. 자세한 내용은 에서 찾을 수 https://help.wrike.com/hc/en-us/articles/209606309-Audit-Reports 있습니다. 마지막으로 Wrike는 액세스 역할을 세분화하여 고객이 기존 데이터 공유를 완전히 감사할 수 있도록 하는 기능을 제공합니다. 자세한 내용은 를 https://help.wrike.com/hc/en-us/articles/360002004534-Access-Reports 참조하세요.
고객 데이터에 대한 액세스는 다음 두 가지 경우에 고려할 수 있습니다.
- Wrike 지원 팀의 액세스: 문제 해결 또는 확인 시 계정에 액세스하려면 지원이 필요합니다. 해당 액세스 권한은 사용자만 부여할 수 있습니다. 이 설정은 지원 팀에 대역을 능가하는 시스템 생성 보안 토큰을 통해 설정되므로 지원 팀이 제한된 시간 동안 문제를 더욱 깊이 있게 해결해 나아가야 합니다. 이 시스템 방식은 Wrike에 저장된 데이터에 대한 추가 기밀성을 보장합니다.
- Wrike 운영 팀의 액세스: Wrike 운영 팀은 모니터링, 패치 및 업데이트, 새 빌드를 프로덕션으로 배달 등의 프로덕션 환경을 유지 관리하고 지원할 책임이 있습니다. 이 경우 액세스는 프로시저 및 기술 측면 모두에서 엄격히 금지되고, VPN, 2FA 및 개인 인증서를 비롯한 강력한 권한 부여 제어가 설정되어 있으며 HIDS(호스트 기반 침입 감지 시스템)를 사용하여 자세히 모니터링하고 Wrike 운영 보안 팀에서 검토합니다. Amazon KMS(Wrike 잠금 기능)의 경우 고객 데이터는 Wrike 데이터베이스에 암호화되어 저장되어 Wrike Operational 팀에서 직접 또는 간접적으로 사용할 수 없습니다. 이는 고객이 관리하고 제어하는 고객의 Amazon KMS 액세스를 사용하여 암호를 해독할 수 있기 때문에입니다.

#### <a name="human-review-of-organizational-information"></a>조직 정보의 인적 검토

사람이 이 앱에서 수집하거나 저장하는 OII(조직 식별 정보) 데이터를 검토하거나 분석하는 데 관여하나요?

>아니요

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="mcas"

Microsoft Cloud App Security [카탈로그의](https://www.microsoft.com/enterprise-mobility-security/cloud-app-security) 정보가 아래에 표시됩니다.

<iframe height='1020' title='Microsoft Cloud App Security 정보' src='https://appmcasinfoprod.azurewebsites.net/#/dashboard/21522' frameborder='no' style='width: 100%;'></iframe>

<a href="https://appmcasinfoprod.azurewebsites.net/#/dashboard/21522" target="_blank">새 탭에서 보기</a>

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

