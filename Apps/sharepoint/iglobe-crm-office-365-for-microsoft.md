---
title: iGlobe의 iGlobe CRM Office 365 Microsoft Office 365 정보
ms.author: elmalova
author: elenamalova
ms.date: 11/17/2020
ms.topic: article
ms.service: attestation
certification_type: certified
description: cSA STAR 레지스트리의 iGlobe CRM Office 365 Microsoft Office 365, 데이터 처리 정책, Microsoft Cloud App Security 앱 카탈로그 정보 및 보안/규정 준수 정보에 대해 사용할 수 있는 모든 보안 및 규정 준수 정보입니다.
zone_pivot_groups: app-info-data-mcas-identity
ms.openlocfilehash: 5ec2f0c536f45192514218e7a0e5b7110fbfe650
ms.sourcegitcommit: 50bd8e07d9355ae65935767a34aca39c46ade8f4
ms.translationtype: MT
ms.contentlocale: ko-KR
ms.lasthandoff: 05/06/2021
ms.locfileid: "52251667"
---
# <a name="iglobe-crm-office-365-for-microsoft-office-365"></a>iGlobe CRM Office 365 Microsoft Office 365

<p></p><a href="https://aka.ms/appcertification" alt="This Microsoft 365 Certified app has been reviewed by Microsoft against industry standards and controls for security, compliance, and data handling practices. Where applicable, Microsoft has verified the developer's claims of compliance with reasonable and effective practices." target="_blank"><img alt="Click here for more information on the Microsoft Certified app program." src="../media/certified.png" width="650" /></a>
<p>개발자가 마지막으로 업데이트한 날짜: 2020년 11월 17일</p>

* <a href="https://appsource.microsoft.com/product/office/WA104379222" target="_blank">AppSource의 보기</a>

::: zone pivot="general"

### <a name="general-information"></a>일반 정보

iGlobe에서 Microsoft에 제공한 정보:

| **정보** | **응답** |
|:----------------|:-------------|
| 앱 이름 | iGlobe CRM Office 365 Microsoft Office 365 |
| ID | WA104379222 |
| Office 365 클라이언트 지원 | SharePoint 2013 이상 |
| 파트너 회사 이름 | iGlobe |
| 파트너 웹 사이트의 URL | [https://www.iglobecrm.com/](https://www.iglobecrm.com/) |
| 개인 정보 취급 방침의 URL | [https://www.iglobecrm.com/content/legal-information](https://www.iglobecrm.com/content/legal-information) |
| 사용 약관 URL | [https://www.iglobecrm.com/content/iglobe-crm-office-365-end...](https://www.iglobecrm.com/content/iglobe-crm-office-365-end-user-license-agreement) |

 [!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="data"

### <a name="how-the-app-handles-data"></a>앱이 데이터를 처리하는 방법

이 정보는 iGlobe에서 이 앱이 조직 데이터를 수집 및 저장하는 방법 및 앱이 수집하는 데이터를 통해 조직에서 제공하는 컨트롤에 대해 제공됩니다.

#### <a name="data-access-using-microsoft-graph"></a>Microsoft 365를 사용한 데이터 Graph

이 앱에 [Graph Microsoft 사용자 권한을](https://docs.microsoft.com/graph/permissions-reference) 나열합니다.

>| **사용 권한**  | **사용 권한 유형(위임/응용 프로그램)** | **데이터가 수집하나요? 수집의 사당성** | **데이터가 저장되어 있나요? 저장 사정이 있나요?** | **Azure AD 앱 ID** |
>|:----------------|:--------------------|:---------------------------------------------------|:--------------------------|:--------------------------|
>| Calendars.ReadWrite | 위임 | 응용 프로그램 데이터베이스에 데이터가 저장되지 않습니다. | canlendar에서 iGlobe로 모임 보고서를 드레킹할 때 사용자 일정에 액세스할 수 있습니다. | 0bb1641a-3b3b-47f7-a11e-01279d92abfb |
>| Contacts.ReadWrite | 위임 |  Directory.AccessAsUser.All | 앱에서 로그인한 사용자와 디렉터리의 정보에 동일한 액세스 권한을 부여할 수 있습니다. | 0bb1641a-3b3b-47f7-a11e-01279d92abfb |
>| Directory.Read.All | 위임 | 응용 프로그램 데이터베이스에 데이터가 저장되지 않습니다. | 사용 권한을 확인하고 사이트 및 목록을 얻습니다. 폴더를 만들고, 파일을 다운로드하고, 파일을 저장합니다. | 0bb1641a-3b3b-47f7-a11e-01279d92abfb |
>| Directory.ReadWrite.All | 위임 | 응용 프로그램 데이터베이스에 데이터가 저장되지 않습니다. | 앱에서 로그인한 사용자와 디렉터리의 정보에 동일한 액세스 권한을 부여할 수 있습니다. | 0bb1641a-3b3b-47f7-a11e-01279d92abfb |
>| Files.ReadWrite.All | 위임 | 응용 프로그램 데이터베이스에 데이터가 저장되지 않습니다. | Read, Update, Create Panner Tasks, Read the users recent and Shared files, To get SharePoint list, libraries and files. 파일 및 데이터를 목록에 SharePoint 저장합니다. | 0bb1641a-3b3b-47f7-a11e-01279d92abfb |
>| Group.Read.All | 위임 | 응용 프로그램 데이터베이스에 데이터가 저장되지 않습니다. | Read, Update, Create Panner Tasks, Read the users recent and Shared files, To get SharePoint list, libraries and files. 파일을 목록에 SharePoint 저장합니다. | 0bb1641a-3b3b-47f7-a11e-01279d92abfb |
>| Group.ReadWrite.All | 위임 | 응용 프로그램 데이터베이스에 데이터가 저장되지 않습니다. | Read, Update, Create Panner Tasks, Read the users recent and Shared files, To get SharePoint list, libraries and files. 파일을 목록에 SharePoint 저장합니다. iGlobe CRM에 Office 365 | 0bb1641a-3b3b-47f7-a11e-01279d92abfb |
>| Mail.ReadWrite | 위임 | 응용 프로그램 데이터베이스에 데이터가 저장되지 않습니다. | eamil을 iGlobe CRM으로 Svae 및 get informatiopn from iGlobe to a new e-amil | 0bb1641a-3b3b-47f7-a11e-01279d92abfb |
>| Sites.Manage.All | 위임 | 응용 프로그램 데이터베이스에 데이터가 저장되지 않습니다. | iGlobe CRM에서 항목 및 목록 만들기, 편집 및 삭제 | 0bb1641a-3b3b-47f7-a11e-01279d92abfb |
>| Sites.Read.All | 위임 | 응용 프로그램 데이터베이스에 데이터가 저장되지 않습니다. | iGlobe CRM의 항목 읽기 | 0bb1641a-3b3b-47f7-a11e-01279d92abfb |
>| Sites.ReadWrite.All | 위임 | 응용 프로그램 데이터베이스에 데이터가 저장되지 않습니다. |  iGlobe CRM에서 항목 및 목록 편집 및 삭제 | 0bb1641a-3b3b-47f7-a11e-01279d92abfb |
>| Tasks.ReadWrite | 위임 | 응용 프로그램 데이터베이스에 데이터가 저장되지 않습니다. | iGlobe CRM에서 플래너 작업 만들기 | 0bb1641a-3b3b-47f7-a11e-01279d92abfb |
>| User.Read | 위임 | 응용 프로그램 데이터베이스에 데이터가 저장되지 않습니다. | speficic 사용자에 대한 iGlobe CRM의 정보를 얻은 경우 | 0bb1641a-3b3b-47f7-a11e-01279d92abfb |

#### <a name="data-access-using-other-microsoft-apis"></a>다른 Microsoft API를 사용한 데이터 액세스

기본 제공 앱 및 추가 Microsoft 365 Microsoft Graph 기타 Microsoft API를 사용하여 OII(조직 식별 가능 정보)를 수집하거나 처리합니다. 이 앱에서 사용하는 Microsoft API를 Graph Microsoft API를 나열합니다.

>| **API** |  **OII가 수집하나요?** |  **수집되는 OII는 무엇입니까?** | **OII 수집의 사당성** | **OII가 저장되어 있나요?** | **OII 저장의 사당성** |
>|:-------------------|:-------------------|:--------------------------|:--------------------------|:---------------------------------------------------|:--------------------------|
>| Exchange - Calendars.ReadWrite.All | 아니요 |  |  |  |  |
>| Exchange - Mail.Read.All | 아니요 |  |  |  |  |
>| Exchange - Contacts.Read | 아니요 |  |  |  |  |
>| Exchange - EWS. AccessAsUser.All | 아니요 |  |  |  |  |
>| Exchange - Tasks.ReadWrite | 아니요 |  |  |  |  |
>| SharePoint - AllSites.Manage | 아니요 |  |  |  |  |
>| SharePoint - AllSites.Read | 아니요 |  |  |  |  |
>|  SharePoint -AllSites.Write | 아니요 |  |  |  |  |
>| SharePoint - MyFiles.Write | 아니요 |  |  |  |  |
>| SharePoint - Sites.Manage.All | 아니요 |  |  |  |  |
>| SharePoint - Sites.Read.All | 아니요 |  |  |  |  |
>| SharePoint - Sites.ReadWrite.All | 아니요 |  |  |  |  |
>| SharePoint - Sites.Search.All | 아니요 |  |  |  |  |
>|  SharePoint - TermStore.Read.All | 아니요 |  |  |  |  |
>| SharePoint - TermStore.ReadWrite.All | 아니요 |  |  |  |  |

#### <a name="non-microsoft-services-used"></a>비영구 Microsoft 서비스

앱이 Microsoft가 아닌 서비스로 조직 데이터를 전송하거나 공유하는 경우 앱에서 사용하는 비 Microsoft 서비스, 전송되는 데이터를 나열하고 앱이 이 정보를 전송해야 하는 이유에 대한 사유를 포함합니다.

>비영구 Microsoft 서비스 사용되지 않습니다.



#### <a name="add-in-data-access"></a>추가 기능 데이터 액세스

이 앱이 조직의 데이터에 액세스하는 데 필요한 사용 권한, 이 사용 권한의 사당성 및 목적(앱에서 이 정보를 어떤 용도로 사용하나요?) 및 앱에서 해당 데이터베이스에 이 정보를 저장하는지 여부를 나열합니다.

>| **사용 권한**  | **설명** |
>|:----------------|:----------------|
>| 기본 | 문서를&#8217;변경하지 못합니다. |
>| 데이터 보내기 | 인터넷을 통해 데이터를 보낼 수 있습니다. |

#### <a name="telemetry-data"></a>원격 분석 데이터

이 응용 프로그램의 원격 분석 또는 로그에 OII(조직 식별 정보) 또는 EUII(최종 사용자 식별 정보)가 나타나나요? 그렇다면 저장되는 데이터와 보존 및 제거 정책에 대해 설명하세요.

>iGlobe는 효과적으로 작동하고 제품 및 서비스에 대한 최상의 환경을 제공하기 위해 데이터를 수집합니다. 라이선스의 경우: 무료 추가 기능을&#8217;평가판 구독을 만들거나 구독을 구매하는 경우와 같이 조직을 관리하기 위해 수집된 데이터와 라이선스 계정이 필요합니다. 다음 정보는 수집됩니다. 
- 재무 목적: 회사 이름 및 주소
- 구독된 사용자: 사용자 이름 및 전자 메일

#### <a name="organizational-controls-for-data-stored-by-partner"></a>파트너가 저장한 데이터에 대한 조직 제어

조직의 관리자가 파트너 시스템에서 정보를 제어하는 방법에 대해 설명하는 방법 삭제, 보존, 감사, 보관, 최종 사용자 정책 등

>모든 데이터는 고객의 자체 테넌트에 있습니다. 응용 프로그램 데이터가 저장되지 않습니다. 최신 추가 기능을 샌드박스 브라우저에서 실행하고 &#8220;실행되지&#8221;. 사용자 데이터를 사용하여 사용자 데이터와 상호 작용합니다Microsoft 서비스. 추가 기능에서 사용자가 작업하는 데이터에만 액세스할 수 있습니다.

#### <a name="human-review-of-organizational-information"></a>조직 정보의 인적 검토

사람이 이 앱에서 수집하거나 저장하는 OII(조직 식별 정보) 데이터를 검토하거나 분석하는 데 관여하나요?

>아니요

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="mcas"

Microsoft Cloud App Security [카탈로그의](https://www.microsoft.com/enterprise-mobility-security/cloud-app-security) 정보가 아래에 표시됩니다.

<iframe height='1020' title='Microsoft Cloud App Security 정보' src='https://appmcasinfoprod.azurewebsites.net/#/dashboard/36163' frameborder='no' style='width: 100%;'></iframe>

<a href="https://appmcasinfoprod.azurewebsites.net/#/dashboard/36163" target="_blank">새 탭에서 보기</a>

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="identity"

### <a name="identity-information"></a>ID 정보

이 정보는 iGlobe에서 이 앱이 인증, 권한 부여, 응용 프로그램 등록 모범 사례 및 기타 ID 조건을 처리하는 방법에 대해 제공했습니다.

| **정보** | **응답** |
|:----------------|:-------------|
| Microsoft Identify Platform(Azure AD)과 통합하나요?  | 예 |
| 통합 검사 목록에 설명된 적용 가능한 모든 모범 사례를 Microsoft ID 플랫폼 준수하나요?  | 예 |
| 앱에서 인증에 MSAL(Microsoft 인증 라이브러리)을 사용하나요? | 아니요 |
| 앱에서 조건부 액세스 정책을 지원하나요? | 예 |
| 지원되는 정책 유형 나열 | 보안 기본값 및 레거시 인증 차단과 같은 다른 일반적인 정책* 관리자를 위한 MFA 필요* Azure 관리에 MFA 필요* 모든 사용자에 대해 MFA 필요* |
| 앱에서 시나리오에 대한 최소 권한 권한을 요청하나요? | 예 |
| 앱의 정적으로 등록된 사용 권한은 앱이 동적으로 그리고 증분적으로 요청하는 권한을 정확하게 반영하나요? | 예 |
| 앱에서 다중 테넌시를 지원하나요? | 예 |
| 앱에 기밀 클라이언트가 있나요? | 예 |
| 앱에 등록된 리디렉션 URI(통합 리소스 식별자)를 모두 소유하고 있나요? | 예 |
| 앱에서 웹 API를 노출하나요? | 아니요 |
| 앱에서 미리 보기 API를 사용하나요? | 아니요 |
| 앱에서 사용되지 않는 API를 사용하나요? | 아니요 |

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end
