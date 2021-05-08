---
title: Zoho Corporation Private Limited의 전자 메일용 Zoho CRM에 대한 응용 프로그램 정보
ms.author: elmalova
author: elenamalova
ms.date: 12/16/2019
ms.topic: article
ms.service: attestation
certification_type: attested
description: 전자 메일용 Zoho CRM, 데이터 처리 정책, CSA STAR 레지스트리의 Microsoft Cloud App Security 앱 카탈로그 정보 및 보안/규정 준수 정보에 대해 사용할 수 있는 모든 보안 및 규정 준수 정보입니다.
zone_pivot_groups: app-info-data-mcas
ms.openlocfilehash: 730750ad7dddfcccaa9f940e88e34793d4e35869
ms.sourcegitcommit: 50bd8e07d9355ae65935767a34aca39c46ade8f4
ms.translationtype: MT
ms.contentlocale: ko-KR
ms.lasthandoff: 05/06/2021
ms.locfileid: "52252898"
---
# <a name="zoho-crm-for-email"></a>전자 메일용 Zoho CRM

<p></p>
<img alt="Publisher Attestation: The information on this page is based on a self-assessment report provided by the app developer on the security, compliance, and data handling practices followed by this app. Microsoft makes no guarantees regarding the accuracy of the information." src="../media/attested.png" width="650" />
<p>개발자가 마지막으로 업데이트한 날짜: 2019년 12월 16일</p>

* <a href="https://appsource.microsoft.com/product/office/WA104379468" target="_blank">AppSource의 보기</a>

::: zone pivot="general"

### <a name="general-information"></a>일반 정보

Microsoft에 대한 Zoho Corporation Private Limited에서 제공하는 정보:

| **정보** | **응답** |
|:----------------|:-------------|
| 앱 이름 | 전자 메일용 Zoho CRM |
| ID | WA104379468 |
| Office 365 클라이언트 지원 | Outlook 2013 이상을 Windows, Outlook 2016 Mac 이상, Outlook 웹용 |
| 파트너 회사 이름 | Zoho Corporation Private Limited |
| 파트너 웹 사이트의 URL | [https://www.zoho.com/](https://www.zoho.com/) |
| 개인 정보 취급 방침의 URL | [https://www.zoho.com/privacy.html](https://www.zoho.com/privacy.html) |
| 사용 약관 URL | [https://go.microsoft.com/fwlink/?LinkID=521715&amp;omkt=en-US](https://go.microsoft.com/fwlink/?LinkID=521715&amp;omkt=en-US) |

 [!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="data"

### <a name="how-the-app-handles-data"></a>앱이 데이터를 처리하는 방법

이 정보는 Zoho Corporation Private Limited에서 이 앱이 조직 데이터를 수집 및 저장하는 방법 및 앱이 수집하는 데이터에 대해 조직이 제어할 수 있는 컨트롤에 대해 제공됩니다.

#### <a name="data-access-using-microsoft-graph"></a>Microsoft 365를 사용한 데이터 Graph

이 앱에 [Graph Microsoft 사용자 권한을](https://docs.microsoft.com/graph/permissions-reference) 나열합니다.

>| **사용 권한**  | **사용 권한 유형(위임/응용 프로그램)** | **데이터가 수집하나요? 수집의 사당성** | **데이터가 저장되어 있나요? 저장 사정이 있나요?** | **Azure AD 앱 ID** |
>|:----------------|:--------------------|:---------------------------------------------------|:--------------------------|:--------------------------|
>| Calendars.ReadWrite | 위임 | 일정 폴더 ID는 Zoho CRM의 연락처를 Microsoft와 동기화하기 위해 &amp; 저장됩니다. 저장되는 event_name, event_location participant_details 정보입니다. | 사용자가 Office365 이벤트를 Zoho CRM과 동기화할 수 있습니다. | f6d7187a-b437-4eca-bbc5-c1331609fe07 |
>| Contacts.ReadWrite | 위임 | 연락처 폴더 ID는 Zoho CRM의 연락처를 Microsoft와 동기화하기 위해 &amp; 저장됩니다. 연락처 정보(first_name, last_name, 전자 메일 주소가 저장됩니다. | 사용자가 Office365 연락처를 Zoho CRM과 동기화할 수 있습니다. | f6d7187a-b437-4eca-bbc5-c1331609fe07 |
>| Files.Read | 위임 |  | 사용자가 Office365 파일을 Zoho CRM으로 가져올 수 있도록 허용합니다. | f6d7187a-b437-4eca-bbc5-c1331609fe07 |
>| Files.Read.All | 위임 |  | 사용자가 Office365 파일을 Zoho CRM으로 가져올 수 있도록 허용합니다. | f6d7187a-b437-4eca-bbc5-c1331609fe07 |
>| Files.Read.Selected | 위임 | UserPrincipalName은 사용자 식별을 위해 저장됩니다. | 사용자가 Office365 파일을 Zoho CRM으로 가져올 수 있도록 허용합니다. | f6d7187a-b437-4eca-bbc5-c1331609fe07 |
>| User.ReadBasic.All | 위임 | 사용자 속성(first_name, last_name, 전자 메일 주소) | 모든 사용자의 기본 프로필 읽기 | f6d7187a-b437-4eca-bbc5-c1331609fe07 |
>| 전자 메일 | 위임 | UserPrincipaName은 사용자 입력을 위해 저장됩니다. | 사용자의 전자 메일 주소 보기 | f6d7187a-b437-4eca-bbc5-c1331609fe07 |
>| offline_access | 위임 |  | 액세스 권한이 부여된 데이터에 대한 액세스 권한 유지 | f6d7187a-b437-4eca-bbc5-c1331609fe07 |
>| profile | 위임 |  | 사용자의 기본 프로필 보기 | f6d7187a-b437-4eca-bbc5-c1331609fe07 |


#### <a name="non-microsoft-services-used"></a>비영구 Microsoft 서비스

앱이 Microsoft가 아닌 서비스로 조직 데이터를 전송하거나 공유하는 경우 앱에서 사용하는 비 Microsoft 서비스, 전송되는 데이터를 나열하고 앱이 이 정보를 전송해야 하는 이유에 대한 사유를 포함합니다.

>비영구 Microsoft 서비스 사용되지 않습니다.



#### <a name="add-in-data-access"></a>추가 기능 데이터 액세스

이 앱이 조직의 데이터에 액세스하는 데 필요한 사용 권한, 이 사용 권한의 사당성 및 목적(앱에서 이 정보를 어떤 용도로 사용하나요?) 및 앱에서 해당 데이터베이스에 이 정보를 저장하는지 여부를 나열합니다.

>| **사용 권한**  | **설명** |
>|:----------------|:----------------|
>| 읽기 항목 | 이 추가 기능에서는 보낸 사람 이름, 받는 사람 이름, 전자 메일 주소, 메시지 본문 및 첨부 파일 정보와 같은 현재 메시지의 개인 정보에 액세스할 수 있습니다. 추가 기능에서 이 데이터를 타사 서비스로 보낼 수 있습니다. 사서함의 다른 항목은&#8217;수정할 수 없습니다. |
>| 데이터 보내기 | 인터넷을 통해 데이터를 보낼 수 있습니다. |

#### <a name="telemetry-data"></a>원격 분석 데이터

이 응용 프로그램의 원격 분석 또는 로그에 OII(조직 식별 정보) 또는 EUII(최종 사용자 식별 정보)가 나타나나요? 그렇다면 저장되는 데이터와 보존 및 제거 정책에 대해 설명하세요.

>원격 분석 및 로그에서 EUII/PII를 수집하지 않습니다. 이러한 데이터가 표시되고 있는 문제를 해결하기 위한 스크립트를 찾아서 경고합니다.

#### <a name="organizational-controls-for-data-stored-by-partner"></a>파트너가 저장한 데이터에 대한 조직 제어

조직의 관리자가 파트너 시스템에서 정보를 제어하는 방법에 대해 설명하는 방법 삭제, 보존, 감사, 보관, 최종 사용자 정책 등

>고객은 Certaat 제한을 사용하여 EAR(암호화 미사용 암호화)를 통해 암호화해야 하는 데이터를 선택할 수 있습니다. 암호는 기본적으로 해시됩니다. 서버에 대한 논리적 액세스는 격리된 전용 네트워크를 통해 제공되고 높은 보안 및 &amp;


[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="mcas"

Microsoft Cloud App Security [카탈로그의](https://www.microsoft.com/enterprise-mobility-security/cloud-app-security) 정보가 아래에 표시됩니다.

<iframe height='1020' title='Microsoft Cloud App Security 정보' src='https://appmcasinfoprod.azurewebsites.net/#/dashboard/22307' frameborder='no' style='width: 100%;'></iframe>

<a href="https://appmcasinfoprod.azurewebsites.net/#/dashboard/22307" target="_blank">새 탭에서 보기</a>

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

