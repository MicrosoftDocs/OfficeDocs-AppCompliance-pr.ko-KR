---
title: OnePlace 솔루션용 OnePlaceMail의 Outlook 정보
ms.author: elmalova
author: elenamalova
ms.date: 09/30/2021
ms.topic: article
ms.service: attestation
certification_type: attested
description: CSA STAR 레지스트리의 Outlook OnePlaceMail, 데이터 처리 정책, Microsoft Cloud App Security 앱 카탈로그 정보 및 보안/규정 준수 정보에 대해 사용할 수 있는 모든 보안 및 규정 준수 정보입니다.
zone_pivot_groups: app-info-data-mcas-identity
ms.openlocfilehash: 196720a00525971f29618d48436cf11b37a3aaac
ms.sourcegitcommit: 874e586a5a9a5eb0c5c5aae0c59f7c75c0742ec4
ms.translationtype: MT
ms.contentlocale: ko-KR
ms.lasthandoff: 10/01/2021
ms.locfileid: "60080649"
---
# <a name="oneplacemail-for-outlook"></a>OnePlaceMail for Outlook

<p></p>
<img alt="Publisher Attestation: The information on this page is based on a self-assessment report provided by the app developer on the security, compliance, and data handling practices followed by this app. Microsoft makes no guarantees regarding the accuracy of the information." src="../media/attested.png" width="650" />
<p>개발자가 마지막으로 업데이트한 날짜: 2021년 9월 30일</p>

* <a href="https://appsource.microsoft.com/product/office/WA104380723" target="_blank">AppSource의 보기</a>

::: zone pivot="general"

### <a name="general-information"></a>일반 정보

OnePlace 솔루션에서 Microsoft에 제공하는 정보:

| **정보** | **응답** |
|:----------------|:-------------|
| 앱 이름 | OnePlaceMail for Outlook |
| ID | WA104380723 |
| Office 365 클라이언트 지원 | Outlook 2013 이상은 Windows, Outlook 2016 이상, Outlook iOS, android, Outlook 웹용 Outlook |
| 파트너 회사 이름 | OnePlace 솔루션 |
| 파트너 웹 사이트의 URL | [https://www.oneplacesolutions.com](https://www.oneplacesolutions.com) |
| 개인 정보 취급 방침의 URL | [https://www.oneplacesolutions.com/oneplacemailapp-privacy](https://www.oneplacesolutions.com/oneplacemailapp-privacy) |
| 사용 약관 URL | [https://www.oneplacesolutions.com/eula.html](https://www.oneplacesolutions.com/eula.html) |

 [!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="data"

### <a name="how-the-app-handles-data"></a>앱이 데이터를 처리하는 방법

이 정보는 이 앱이 조직 데이터를 수집 및 저장하는 방법 및 앱이 수집하는 데이터를 통해 조직이 가지는 컨트롤에 대한 OnePlace 솔루션에서 제공됩니다.

#### <a name="data-access-using-microsoft-graph"></a>Microsoft 365를 사용한 데이터 Graph

이 앱에 [Graph Microsoft 사용자 권한을](https://docs.microsoft.com/graph/permissions-reference) 나열합니다.

>| **사용 권한**  | **사용 권한 유형(위임/ 응용 프로그램)** | **데이터가 수집하나요? 수집의 사당성** | **데이터가 저장되어 있나요? 저장 사정이 있나요?** | **Azure AD 앱 ID** |
>|:----------------|:------------------------------------------------|:--------------------------------------------------------|:--------------------------------------------------|:--------------------|
>| Group.ReadWrite.All | 위임 | 현재 Teams 구성원인지 확인하는 데 필요합니다. | 없음 | [44a72516-136f-4a55-ae26-ef09977230be](https://docs.microsoft.com/microsoft-365-app-certification/azure/44a72516-136f-4a55-ae26-ef09977230be) |
>| Mail.ReadWrite.Shared | 위임 | 메일 속성에 액세스하여 SharePoint 열을 설정하고 메일 항목에 전송된 SharePoint 범주를 추가하는 데 필요합니다. | 없음 | [44a72516-136f-4a55-ae26-ef09977230be](https://docs.microsoft.com/microsoft-365-app-certification/azure/44a72516-136f-4a55-ae26-ef09977230be) |
>| MailboxSettings.ReadWrite | 위임 | 수집되거나 사용되지 않습니다. 사용자 사서함의 마스터 범주 목록에 범주를 추가하는 데 사용됩니다. | 없음 | [44a72516-136f-4a55-ae26-ef09977230be](https://docs.microsoft.com/microsoft-365-app-certification/azure/44a72516-136f-4a55-ae26-ef09977230be) |
>| Sites.ReadWrite.All | 위임 | 앱이 앱에 업로드한 항목에 대한 속성을 설정하는 데 SharePoint. | 없음 | [44a72516-136f-4a55-ae26-ef09977230be](https://docs.microsoft.com/microsoft-365-app-certification/azure/44a72516-136f-4a55-ae26-ef09977230be) |
>| User.Read | 위임 | Microsoft 365에 대한 인증에 Graph. | 다음 데이터는 앱에서 데이터베이스에 저장하며, 구독 및 사용자 라이선스 추적에 사용됩니다. 사용자 ID, 전자 메일, 이름, 성. | [44a72516-136f-4a55-ae26-ef09977230be](https://docs.microsoft.com/microsoft-365-app-certification/azure/44a72516-136f-4a55-ae26-ef09977230be) |
>| User.ReadBasic.All | 위임 | 사용자 선택 필드에 사용자 프로필 이미지를 표시하는 데 필요합니다. | 없음 | [44a72516-136f-4a55-ae26-ef09977230be](https://docs.microsoft.com/microsoft-365-app-certification/azure/44a72516-136f-4a55-ae26-ef09977230be) |
>| User.ReadBasic.All | 위임 | 사용자 선택 필드에 사용자 프로필 이미지를 표시하는 데 필요합니다. | 없음 | [44a72516-136f-4a55-ae26-ef09977230be](https://docs.microsoft.com/microsoft-365-app-certification/azure/44a72516-136f-4a55-ae26-ef09977230be) |
>| User.ReadWrite.All | 위임 | 테넌시의 사용자 내에서 Teams 서비스를 사용할 수 있는지 여부를 Office 365 필요합니다. | 없음 | [44a72516-136f-4a55-ae26-ef09977230be](https://docs.microsoft.com/microsoft-365-app-certification/azure/44a72516-136f-4a55-ae26-ef09977230be) |

#### <a name="data-access-using-other-microsoft-apis"></a>다른 Microsoft API를 사용한 데이터 액세스

기본 제공 앱 및 추가 Microsoft 365 Microsoft Graph 기타 Microsoft API를 사용하여 OII(조직 식별 가능 정보)를 수집하거나 처리합니다. 이 앱에서 사용하는 Microsoft API를 Graph Microsoft API를 나열합니다.

>| **API** |  **OII가 수집하나요?** |  **수집되는 OII는 무엇입니까?** | **OII 수집의 사당성** | **OII가 저장되어 있나요?** | **OII 저장의 사당성** |
>|:--------|:-----------------------|:----------------------------|:--------------------------------------|:-------------------|:-----------------------------------|
>| SharePoint | 예 | SharePoint URL, 라이브러리/목록/폴더 이름 | 액세스하는 관리 정보는 전자 메일 및 첨부 파일을 전자 메일 및 첨부 파일을 저장하는 프로세스를 Exchange SharePoint. 이 추가 데이터는 미사시에 저장되지 않습니다. 전송 중 암호화됩니다. 이 데이터의 예로는 선택 열 값, SharePoint, 콘텐츠 형식 이름, 폴더 이름, 사이트 이름 등의 열 값이 포함됩니다.  | 이 데이터는 앱에서 저장 또는 수집되지 않는 동안 원격 분석/로그에 표시되어 90일 동안 보존될 수 있습니다. | 데이터가 저장되지 않습니다. |

#### <a name="non-microsoft-services-used"></a>비영구 Microsoft 서비스

앱이 Microsoft가 아닌 서비스로 조직 데이터를 전송하거나 공유하는 경우 앱에서 사용하는 비 Microsoft 서비스, 전송되는 데이터를 나열하고 앱이 이 정보를 전송해야 하는 이유에 대한 사유를 포함합니다.

>| **모든 비 Microsoft 서비스 OII가 다음으로 전송됩니다.** |  **전송되는 OII는 무엇입니까?** | **OII 전송의 사당성** |
>|:-----------------------------------------------------|:------------------------------|:----------------------------------------|
>| Chargify 서비스는 구독 관리 및 청구에 사용됩니다. 앱 내(무료) 구독 만들기의 경우 사용자의 이름, 성, 전자 메일 주소가 Chargify와 공유됩니다. 구입한 구독(라이선스가 있는 여러 사용자 지원)의 경우 개별 사용자 세부 정보는 Chargify 서비스와 공유되지 않습니다. | 전자 메일 주소 | 사용자에게 구독 수명 주기 이벤트를 전달할 수 있도록 설정하려면 |



#### <a name="telemetry-data"></a>원격 분석 데이터

이 응용 프로그램의 원격 분석 또는 로그에 OII(조직 식별 정보) 또는 EUII(최종 사용자 식별 정보)가 나타나나요? 그렇다면 저장되는 데이터와 보존 및 제거 정책에 대해 설명하세요.

>EUII 및 OII는 원격 분석에 표시됩니다. 이 정보는 응용 프로그램 Insights 저장되고, 미사용, 액세스 제어 및 90일 후에 삭제됩니다.

#### <a name="organizational-controls-for-data-stored-by-partner"></a>파트너가 저장한 데이터에 대한 조직 제어

조직의 관리자가 파트너 시스템에서 정보를 제어하는 방법에 대해 설명하는 방법 삭제, 보존, 감사, 보관, 최종 사용자 정책 등

>응용 프로그램에 저장된 데이터는 전송 중 및 미사일 시 암호화됩니다. 앱의 Office 365 자격 증명을 사용하여 시스템에 사용자 암호를 저장하지 않습니다. 저장된 데이터/로그/원격 분석에 대한 액세스는 앱의 실행 및 모니터링을 위해 정보에 액세스해야 하는 내부 관리 직원에게 긴밀하게 제어됩니다. Two-Factor 모든 내부 관리 직원에 대해 인증이 적용됩니다.

#### <a name="human-review-of-organizational-information"></a>조직 정보의 인적 검토

사람이 이 앱에서 수집하거나 저장하는 OII(조직 식별 정보) 데이터를 검토하거나 분석하는 데 관여하나요?

>예

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="mcas"

Microsoft Cloud App Security [카탈로그의](https://www.microsoft.com/enterprise-mobility-security/cloud-app-security) 정보가 아래에 표시됩니다.

<iframe height='1020' title='Microsoft Cloud App Security 정보' src='https://appmcasinfoprod.azurewebsites.net/#/dashboard/35746' frameborder='no' style='width: 100%;'></iframe>

<a href="https://appmcasinfoprod.azurewebsites.net/#/dashboard/35746" target="_blank">새 탭에서 보기</a>

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="identity"

### <a name="identity-information"></a>ID 정보

이 정보는 OnePlace Solutions에서 이 앱이 인증, 권한 부여, 응용 프로그램 등록 모범 사례 및 기타 ID 조건을 처리하는 방법에 대해 제공했습니다.

| **정보** | **응답** |
|:----------------|:-------------|
| Microsoft Identify Platform(Azure AD)과 통합하나요?  | 예 |
| 통합 검사 목록에 설명된 적용 가능한 모든 모범 사례를 Microsoft ID 플랫폼 준수하나요?  | 예 |
| 앱에서 인증에 MSAL(Microsoft 인증 라이브러리)을 사용하나요? | 아니요 |
| 앱에서 조건부 액세스 정책을 지원하나요? | 아니요 |
| 앱에서 시나리오에 대한 최소 권한 권한을 요청하나요? | 예 |
| 앱의 정적으로 등록된 사용 권한은 앱이 동적으로 그리고 증분적으로 요청하는 권한을 정확하게 반영하나요? | 예 |
| 앱에서 다중 테넌시를 지원하나요? | 예 |
| 앱에 기밀 클라이언트가 있나요? | 예 |
| 앱에 등록된 리디렉션 URI(통합 리소스 식별자)를 모두 소유하고 있나요? | 예 |
| 앱의 경우 어떻게 사용하지 않도록 해야 하나요? | - 와일드카드 리디렉션 URIS,<br/>- OAuth2 암시적 Flow SPA에 필요하지 않은 경우<br/>- 리소스 소유자 암호 자격 증명(ROPC) 흐름 |
| 앱에서 웹 API를 노출하나요? | 예 |
| 사용 권한 모델에서 클라이언트 앱이 적절한 동의를 받은 경우 통화 성공만 허용하나요? | 예 |
| 앱에서 미리 보기 API를 사용하나요? | 아니요 |
| 앱에서 사용되지 않는 API를 사용하나요? | 아니요 |

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end
