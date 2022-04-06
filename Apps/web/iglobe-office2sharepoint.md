---
title: iGlobe의 Office2SharePoint에 대한 응용 프로그램 정보
ms.author: elmalova
author: elenamalova
ms.date: 06/22/2021
ms.topic: article
ms.service: attestation
certification_type: attested
description: Office2SharePoint에 사용할 수 있는 모든 보안 및 규정 준수 정보, 데이터 처리 정책, CSA STAR 레지스트리의 Microsoft Cloud App Security 앱 카탈로그 정보 및 보안/규정 준수 정보
zone_pivot_groups: app-info-data-mcas-identity
ms.openlocfilehash: 9be661602c6f4d586c615ff06b2642f892e0c085
ms.sourcegitcommit: ddedb98532d7cef5cff47b137aa0ad87494b163d
ms.translationtype: MT
ms.contentlocale: ko-KR
ms.lasthandoff: 04/02/2022
ms.locfileid: "64627060"
---
# <a name="office2sharepoint"></a>Office2SharePoint

<p></p>
<img alt="Publisher Attestation: The information on this page is based on a self-assessment report provided by the app developer on the security, compliance, and data handling practices followed by this app. Microsoft makes no guarantees regarding the accuracy of the information." src="../media/attested.png" width="650" />
<p>개발자가 마지막으로 업데이트한 날짜: 2021년 6월 22일</p>

* <a href="https://appsource.microsoft.com/product/web-apps/17859280.o2s" target="_blank">AppSource의 보기</a>

::: zone pivot="general"

### <a name="general-information"></a>일반 정보

iGlobe에서 Microsoft에 제공한 정보:

| **정보** | **응답** |
|:----------------|:-------------|
| 앱 이름 | Office2SharePoint |
| ID | 17859280.o2s |
| 파트너 회사 이름 | iGlobe |
| 파트너 웹 사이트의 URL | [https://www.iglobecrm.com](https://www.iglobecrm.com) |
| 개인 정보 취급 방침의 URL | [https://www.iglobecrm.com/content/legal-information](https://www.iglobecrm.com/content/legal-information) |
| 사용 약관 URL | [https://www.iglobecrm.com/content/end-user-license-agreemen...](https://www.iglobecrm.com/content/end-user-license-agreement-office2sharepoint) |

 [!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="data"

### <a name="how-the-app-handles-data"></a>앱이 데이터를 처리하는 방법

이 정보는 iGlobe에서 이 앱이 조직 데이터를 수집 및 저장하는 방법 및 앱이 수집하는 데이터를 통해 조직에서 제공하는 컨트롤에 대해 제공됩니다.

#### <a name="data-access-using-microsoft-graph"></a>Microsoft 365를 사용하여 데이터 Graph

이 앱에 [Graph Microsoft 사용자 권한을](/graph/permissions-reference) 나열합니다.

>| **사용 권한**  | **사용 권한 유형(위임/응용 프로그램)** | **데이터가 수집하나요? 수집의 사당성** | **데이터가 저장되어 있나요? 저장 사정이 있나요?** | **Azure AD 앱 ID** |
>|:----------------|:--------------------|:---------------------------------------------------|:--------------------------|:--------------------------|
>| Directory.AccessAsUser.All | 위임 | 응용 프로그램 데이터베이스에 데이터가 저장되지 않습니다. | 앱에서 로그인한 사용자와 디렉터리의 정보에 동일한 액세스 권한을 부여할 수 있습니다. | 5971c986-9d39-409c-a6f8-1385b1f690ef |
>| Directory.Read.All | 위임 | 응용 프로그램 데이터베이스에 데이터가 저장되지 않습니다. | 사용 권한을 확인하고 사이트 및 목록을 얻습니다. 폴더를 만들고, 파일을 다운로드하고, 파일을 저장합니다. | 5971c986-9d39-409c-a6f8-1385b1f690ef |
>| Directory.ReadWrite.All | 위임 | 응용 프로그램 데이터베이스에 데이터가 저장되지 않습니다. | 사용 권한을 확인하고 사이트 및 목록을 얻습니다. 폴더를 만들고, 파일을 다운로드하고, 파일을 저장합니다. | 5971c986-9d39-409c-a6f8-1385b1f690ef |
>| Group.Read.All | 위임 | 응용 프로그램 데이터베이스에 데이터가 저장되지 않습니다. | 사용자 그룹 사이트를 얻습니다. | 5971c986-9d39-409c-a6f8-1385b1f690ef |
>| Group.ReadWrite.All | 위임 | 응용 프로그램 데이터베이스에 데이터가 저장되지 않습니다. | 선택한 메일/s에 액세스하고 첨부 파일을 얻습니다. 메일 또는 그룹 SharePoint 메일에 추가합니다. | 5971c986-9d39-409c-a6f8-1385b1f690ef |
>| Sites.Manage.All | 위임 | 응용 프로그램 데이터베이스에 데이터가 저장되지 않습니다. | 응용 프로그램에서 로그인한 사용자를 대신하여 모든 사이트 모음의 문서 라이브러리 및 목록을 만들거나 삭제할 수 있도록 합니다. | 5971c986-9d39-409c-a6f8-1385b1f690ef |
>| Sites.Read.All | 위임 | 응용 프로그램 데이터베이스에 데이터가 저장되지 않습니다. | 사용자가 사이트를 SharePoint. 선택한 메일에서 파일을 다운로드하고 첨부 파일을 저장합니다. | 5971c986-9d39-409c-a6f8-1385b1f690ef |
>| Sites.ReadWrite.All | 위임 | 응용 프로그램 데이터베이스에 데이터가 저장되지 않습니다. | 목록 SharePoint 라이브러리 및 파일을 다운로드합니다. 파일을 목록에 SharePoint 저장합니다. | 5971c986-9d39-409c-a6f8-1385b1f690ef |
>| User.Read | 위임 | 응용 프로그램 데이터베이스에 데이터가 저장되지 않습니다. | 사용자가 사이트, SharePoint 사이트 및 OneDrive 사이트를 만들 수 있도록 합니다. | 5971c986-9d39-409c-a6f8-1385b1f690ef |

#### <a name="data-access-using-other-microsoft-apis"></a>다른 Microsoft API를 사용한 데이터 액세스

기본 제공 앱 및 추가 Microsoft 365 Microsoft API를 사용하여 OII(조직 식별 가능 Graph)를 수집하거나 처리합니다. 이 앱에서 사용하는 Microsoft API를 Graph Microsoft API를 나열합니다.

>| **API** |  **OII가 수집하나요?** |  **수집되는 OII는 무엇입니까?** | **OII 수집의 사당성** | **OII가 저장되어 있나요?** | **OII 저장의 사당성** |
>|:-------------------|:-------------------|:--------------------------|:--------------------------|:---------------------------------------------------|:--------------------------|
>| Exchange - EWS. AccessAsUser.All | 아니요 |  |  |  |  |
>| Exchange - Mail.ReadWrite | 아니요 |  |  |  |  |
>| Exchange - MailboxSettings.ReadWrite | 아니요 |  |  |  |  |
>| SharePoint- AllSites.Manage | 아니요 |  |  |  |  |
>| SharePoint - AllSites.Write | 아니요 |  |  |  |  |
>| SharePoint - MyFiles.Write | 아니요 |  |  |  |  |
>| SharePoint - User.Read.All | 아니요 |  |  |  |  |

#### <a name="non-microsoft-services-used"></a>비영구 Microsoft 서비스

앱이 Microsoft가 아닌 서비스로 조직 데이터를 전송하거나 공유하는 경우 앱에서 사용하는 비 Microsoft 서비스, 전송되는 데이터를 나열하고 앱이 이 정보를 전송해야 하는 이유에 대한 사유를 포함합니다.

>비영구 Microsoft 서비스 사용되지 않습니다.



#### <a name="telemetry-data"></a>원격 분석 데이터

이 응용 프로그램의 원격 분석 또는 로그에 OII(조직 식별 정보) 또는 EUII(최종 사용자 식별 정보)가 나타나나요? 그렇다면 저장되는 데이터와 보존 및 제거 정책에 대해 설명하세요.

>iGlobe는 효과적으로 작동하고 제품 및 서비스에 대한 최상의 환경을 제공하기 위해 데이터를 수집합니다. 라이선스의 경우: 무료 추가 기능을&#8217;평가판 구독을 만들거나 구독을 구매하는 경우와 같이 조직을 관리하기 위해 수집된 데이터와 라이선스 계정이 필요합니다. 다음 정보는 수집됩니다. 재무 목적: 회사 이름 및 주소 구독 사용자: 사용자 이름 및 전자 메일

#### <a name="organizational-controls-for-data-stored-by-partner"></a>파트너가 저장한 데이터에 대한 조직 제어

조직의 관리자가 파트너 시스템에서 정보를 제어하는 방법에 대해 설명하는 방법 삭제, 보존, 감사, 보관, 최종 사용자 정책 등

>모든 응용 프로그램 데이터는 고객의 자체 테넌트에 있으며 테넌트 관리자가 조직의 다른 모든 서비스로 Office 365. 추가 기능에는 응용 프로그램 데이터가 저장되지 않습니다. 최신 추가 기능을 샌드박스 브라우저에서 실행하고 &#8220;실행되지&#8221;. 추가 기능에서 사용자가 작업하는 데이터에만 액세스할 수 있습니다. 이 매니지타는 사용자 데이터를 사용하여 사용자 데이터와 상호 작용할 Microsoft 서비스.

#### <a name="human-review-of-organizational-information"></a>조직 정보의 인적 검토

사람이 이 앱에서 수집하거나 저장하는 OII(조직 식별 정보) 데이터를 검토하거나 분석하는 데 관여하나요?

>아니요

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="mcas"

Microsoft Cloud App Security [카탈로그의](https://www.microsoft.com/enterprise-mobility-security/cloud-app-security) 정보가 아래에 표시됩니다.

<iframe height='1020' title='Microsoft Cloud App Security 정보' src='https://appmcasinfoprod.azurewebsites.net/#/dashboard/35747' frameborder='no'></iframe>

<a href="https://appmcasinfoprod.azurewebsites.net/#/dashboard/35747" target="_blank">새 탭에서 보기</a>

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
