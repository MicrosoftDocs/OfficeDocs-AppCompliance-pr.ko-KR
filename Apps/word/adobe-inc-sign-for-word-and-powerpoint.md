---
title: Adobe Sign for Word 및 Adobe Inc.PowerPoint 응용 프로그램 정보
ms.author: elmalova
author: elenamalova
ms.date: 12/16/2019
ms.topic: article
ms.service: attestation
certification_type: certified
description: Adobe Sign for Word 및 PowerPoint, 데이터 처리 정책, CSA STAR 레지스트리의 Microsoft Cloud App Security 앱 카탈로그 정보 및 보안/규정 준수 정보에 대해 사용 가능한 모든 보안 및 규정 준수 정보입니다.
zone_pivot_groups: app-info-data-mcas
ms.openlocfilehash: cdb2750d21967d83ad40710a5b6888f11ca945e1
ms.sourcegitcommit: 50bd8e07d9355ae65935767a34aca39c46ade8f4
ms.translationtype: MT
ms.contentlocale: ko-KR
ms.lasthandoff: 05/06/2021
ms.locfileid: "52251597"
---
# <a name="adobe-sign-for-word-and-powerpoint"></a>Word 및 Word용 Adobe Sign for word PowerPoint

<p></p><a href="https://aka.ms/appcertification" alt="This Microsoft 365 Certified app has been reviewed by Microsoft against industry standards and controls for security, compliance, and data handling practices. Where applicable, Microsoft has verified the developer's claims of compliance with reasonable and effective practices." target="_blank"><img alt="Click here for more information on the Microsoft Certified app program." src="../media/certified.png" width="650" /></a>
<p>개발자가 마지막으로 업데이트한 날짜: 2019년 12월 16일</p>

* <a href="https://appsource.microsoft.com/product/office/WA104381155" target="_blank">AppSource의 보기</a>

::: zone pivot="general"

### <a name="general-information"></a>일반 정보

Adobe Inc.에서 Microsoft에 제공한 정보:

| **정보** | **응답** |
|:----------------|:-------------|
| 앱 이름 | Word 및 Word용 Adobe Sign for word PowerPoint |
| ID | WA104381155 |
| Office 365 클라이언트 지원 | Word 2016 Mac의 PowerPoint 2013 서비스 팩 1 이상, Windows, Windows, 웹용 Word, 웹용 PowerPoint, PowerPoint 2016 이상에 있는 Word 2013 서비스 팩 1 이상 |
| 파트너 회사 이름 | Adobe Inc. |
| 파트너 웹 사이트의 URL | [https://www.adobe.com/](https://www.adobe.com/) |
| 개인 정보 취급 방침의 URL | [https://www.adobe.com/privacy/policies-business/esign.html](https://www.adobe.com/privacy/policies-business/esign.html) |
| 사용 약관 URL | [https://support.office.com/client/61994a3b-2c87-41c4-a88d-a...](https://support.office.com/client/61994a3b-2c87-41c4-a88d-a6455efa362d?omkt=en) |

 [!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="data"

### <a name="how-the-app-handles-data"></a>앱이 데이터를 처리하는 방법

이 정보는 Adobe Inc.에서 이 앱이 조직 데이터를 수집 및 저장하는 방법 및 앱이 수집하는 데이터를 통해 조직이 하게 될 컨트롤에 대해 제공됩니다.

#### <a name="data-access-using-microsoft-graph"></a>Microsoft 365를 사용한 데이터 Graph

이 앱에 [Graph Microsoft 사용자 권한을](https://docs.microsoft.com/graph/permissions-reference) 나열합니다.

>| **사용 권한**  | **사용 권한 유형(위임/응용 프로그램)** | **데이터가 수집하나요? 수집의 사당성** | **데이터가 저장되어 있나요? 저장 사정이 있나요?** | **Azure AD 앱 ID** |
>|:----------------|:--------------------|:---------------------------------------------------|:--------------------------|:--------------------------|
>| Mail.ReadWrite | application | 모든 거래에 대한 Adobe Sign History 및 감사 내역 보고서를 끌어오기 위해 전자 메일의 데이터가 필요합니다. https://helpx.adobe.com/sign/using/audit-reports-transaction-history.html | 첨부된 문서, 보낸 사람 및 받는 사람 전자 메일, 전자 메일에서 Adobe로 보내는 메시지 콘텐츠를 채우기 위해 서명을 위해 보낼 수 있습니다. 이 경우 Adobe Sign에서 해당 필드를 다시 입력할 수 있는 시간을 절약할 수 있습니다. 계약이 서명된 후 사용자가 거래가 완료된 것으로 받는 사람에게 알리는 전자 메일을 보낼 수 있도록 자동으로 새 전자 메일을 작성합니다. |  |
>| People.Read | 위임 |  | 서명을 위해 보내기 환경의 전자 메일 주소를 자동 입력하려면 일부 초기 문자를 입력하여 사용자가 전체 전자 메일을 입력할 &quot; &quot; 필요가 없습니다. |  |
>| User.Read | 위임 |  | 사용자의 프로필을 읽고 Adobe Sign을 사용할 수 있도록 자신의 프로필(기본적으로 전자 메일)을 데이터베이스에 일치합니다. |  |
>| offline_access | 위임 |  | 액세스 토큰을 새로 고치기 위해 현재 토큰이 만료된 경우 예를 들어 사용자가 서명을 위해 보내기 창에 있는 경우 너무 오래 비활성 상태인 경우 사용자가 활성 상태일 때 새 토큰을 &quot; &quot; 새로 고쳐야 합니다. |  |
>| openid | 위임 | 전자 메일은 Adobe Sign의 사용자에 대한 고유 식별자입니다. 해당 사용자의 모든 활동을 Adobe Sign 레코드에 매핑할 수 있도록 전자 메일 ID를 저장합니다.  | 사용자를 로그인하여 Adobe Sign 앱 사용 권한에 대한 동의를 보장합니다. |  |


#### <a name="non-microsoft-services-used"></a>비영구 Microsoft 서비스

앱이 Microsoft가 아닌 서비스로 조직 데이터를 전송하거나 공유하는 경우 앱에서 사용하는 비 Microsoft 서비스, 전송되는 데이터를 나열하고 앱이 이 정보를 전송해야 하는 이유에 대한 사유를 포함합니다.

>비영구 Microsoft 서비스 사용되지 않습니다.



#### <a name="add-in-data-access"></a>추가 기능 데이터 액세스

이 앱이 조직의 데이터에 액세스하는 데 필요한 사용 권한, 이 사용 권한의 사당성 및 목적(앱에서 이 정보를 어떤 용도로 사용하나요?) 및 앱에서 해당 데이터베이스에 이 정보를 저장하는지 여부를 나열합니다.

>| **사용 권한**  | **설명** |
>|:----------------|:----------------|
>| ReadWrite Document | 문서를 읽고 변경할 수 있습니다. |
>| 데이터 보내기 | 인터넷을 통해 데이터를 보낼 수 있습니다. |

#### <a name="telemetry-data"></a>원격 분석 데이터

이 응용 프로그램의 원격 분석 또는 로그에 OII(조직 식별 정보) 또는 EUII(최종 사용자 식별 정보)가 나타나나요? 그렇다면 저장되는 데이터와 보존 및 제거 정책에 대해 설명하세요.

>없음 당사는 원격 분석 또는 로그에 EUII 또는 OII를 기록하지 않습니다. 이 프로세스는 이 작업을 수행하지 않는지 검사하는 자체 보안 검토입니다.

#### <a name="organizational-controls-for-data-stored-by-partner"></a>파트너가 저장한 데이터에 대한 조직 제어

조직의 관리자가 파트너 시스템에서 정보를 제어하는 방법에 대해 설명하는 방법 삭제, 보존, 감사, 보관, 최종 사용자 정책 등

>앱 응용 프로그램에 대한 고객 관리자 상호 작용은 Microsoft Teams 없습니다.

#### <a name="human-review-of-organizational-information"></a>조직 정보의 인적 검토

사람이 이 앱에서 수집하거나 저장하는 OII(조직 식별 정보) 데이터를 검토하거나 분석하는 데 관여하나요?

>아니요

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="mcas"

Microsoft Cloud App Security [카탈로그의](https://www.microsoft.com/enterprise-mobility-security/cloud-app-security) 정보가 아래에 표시됩니다.

<iframe height='1020' title='Microsoft Cloud App Security 정보' src='https://appmcasinfoprod.azurewebsites.net/#/dashboard/11641' frameborder='no' style='width: 100%;'></iframe>

<a href="https://appmcasinfoprod.azurewebsites.net/#/dashboard/11641" target="_blank">새 탭에서 보기</a>

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

