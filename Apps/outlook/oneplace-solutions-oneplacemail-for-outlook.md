---
title: OnePlace 솔루션으로 Outlook 위한 OnePlaceMail용 애플리케이션 정보
ms.author: elmalova
author: elenamalova
ms.date: 01/31/2021
ms.topic: article
ms.service: attestation
certification_type: attested
description: Outlook 위한 OnePlaceMail의 모든 사용 가능한 보안 및 규정 준수 정보 정보, 데이터 처리 정책, Microsoft Cloud App Security 앱 카탈로그 정보, CSA STAR 레지스트리의 보안/규정 준수 정보.
zone_pivot_groups: app-info-data-mcas-identity
ms.openlocfilehash: 5094d1ad5e7b028ac115529de16ddb9cbef2086f
ms.sourcegitcommit: a44420a99a1a3a9d0e49f4be66f266e2d4ca7bbb
ms.translationtype: MT
ms.contentlocale: ko-KR
ms.lasthandoff: 05/19/2021
ms.locfileid: "52552499"
---
# <a name="oneplacemail-for-outlook"></a>Outlook 위한 원플레이스메일

<p></p>
<img alt="Publisher Attestation: The information on this page is based on a self-assessment report provided by the app developer on the security, compliance, and data handling practices followed by this app. Microsoft makes no guarantees regarding the accuracy of the information." src="../media/attested.png" width="650" />
<p>최종 업데이트: 2021년 1월 31일</p>

* <a href="https://appsource.microsoft.com/product/office/WA104380723" target="_blank">앱소스에서 보기</a>

::: zone pivot="general"

### <a name="general-information"></a>일반 정보

Microsoft에 OnePlace 솔루션에서 제공하는 정보:

| **정보** | **응답** |
|:----------------|:-------------|
| 앱 이름 | Outlook 위한 원플레이스메일 |
| ID | WA104380723 |
| 지원되는 Office 365 클라이언트 | Outlook 2013 년 이후 Windows, Outlook 2016 또는 이후 Mac에서 iOS, 안드로이드Outlook 웹 Outlook Outlook |
| 파트너 회사 이름 | 원플레이스 솔루션 |
| 파트너 웹사이트의 URL | [https://www.oneplacesolutions.com/](https://www.oneplacesolutions.com/) |
| 개인정보 처리방침의 URL | [https://www.oneplacesolutions.com/oneplacemailapp-privacy](https://www.oneplacesolutions.com/oneplacemailapp-privacy) |
| 이용 약관의 URL | [https://www.oneplacesolutions.com/oneplacemailapp-eula](https://www.oneplacesolutions.com/oneplacemailapp-eula) |

 [!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="data"

### <a name="how-the-app-handles-data"></a>앱이 데이터를 처리하는 방법

이 정보는 OnePlace Solutions에서 이 앱이 조직 데이터를 수집하고 저장하는 방법과 앱이 수집하는 데이터에 대한 조직에서 가질 수 있는 제어에 대해 제공했습니다.

#### <a name="data-access-using-microsoft-graph"></a>Microsoft Graph 을 사용하여 데이터 액세스

이 [앱에서 필요한 Microsoft Graph 권한을 나열합니다.](https://docs.microsoft.com/graph/permissions-reference)

>| **사용 권한**  | **권한 유형(위임/응용 프로그램)** | **데이터가 수집되고 있습니까? 그것을 수집하기위한 정당화?** | **데이터가 저장되어 있습니까? 그것을 저장하는 정당화?** | **Azure AD 앱 ID** |
>|:----------------|:--------------------|:---------------------------------------------------|:--------------------------|:--------------------------|
>| Group.ReadWrite.All | 위임 | 현재 사용자가 Teams 결정하는 데 필요합니다. | 없음 | 44a72516-136f-4a55-ae26-ef09977230be |
>| 메일.읽기 쓰기.공유 | 위임 | 메일 속성에 액세스하여 SharePoint 열을 설정하고 메일 항목의 SharePoint 범주에 전송을 추가하는 데 필요한 경우 | 없음 | 44a72516-136f-4a55-ae26-ef09977230be |
>| 사서함 설정.읽기 | 위임 | 수집하거나 사용되지 않는 이 데이터는 사용자 사서함의 마스터 범주 목록에 범주를 추가하는 데 사용됩니다. | 없음 | 44a72516-136f-4a55-ae26-ef09977230be |
>| Sites.ReadWrite.All | 위임 | 앱이 업로드한 항목에 대한 속성을 설정하는 데 필요한 항목이 SharePoint. | 없음 | 44a72516-136f-4a55-ae26-ef09977230be |
>| User.Read | 위임 | Microsoft Graph 인증에 필요합니다. | 다음 데이터는 데이터베이스에 있는 앱에 저장되며 구독 및 사용자 라이선스 추적에 사용됩니다: 사용자 ID, 이메일, 이름, 성. | 44a72516-136f-4a55-ae26-ef09977230be |
>| User.ReadBasic.All | 위임 | 사용자 프로필 이미지를 사람 선택 필드에 표시하는 데 필요합니다. | 없음 | 44a72516-136f-4a55-ae26-ef09977230be |
>| User.ReadBasic.All | 위임 | 사용자 프로필 이미지를 사람 선택 필드에 표시하는 데 필요합니다. | 없음 | 44a72516-136f-4a55-ae26-ef09977230be |
>| User.ReadWrite.All | 위임 | Teams 서비스가 사용자 내에서 사용할 수 있는지 확인하는 데 필요합니다 Office 365. | 없음 | 44a72516-136f-4a55-ae26-ef09977230be |

#### <a name="data-access-using-other-microsoft-apis"></a>다른 Microsoft API를 사용한 데이터 액세스

Microsoft 365 기반으로 구축된 앱 및 추가 기능을 사용하면 Microsoft Graph 이외의 추가 Microsoft API를 사용하여 조직 식별 정보(OII)를 수집하거나 처리할 수 있습니다. 이 응용 프로그램이 사용하는 마이크로 소프트 이외의 마이크로 소프트 API를 나열할 Graph.

>| **API** |  **OII가 수집되고 있습니까?** |  **어떤 OII가 수집됩니까?** | **OII수집을 위한 정당성?** | **OII가 저장되어 있습니까?** | **OII를 저장하는 정당화?** |
>|:-------------------|:-------------------|:--------------------------|:--------------------------|:---------------------------------------------------|:--------------------------|
>| SharePoint | 예 | SharePoint URL, 라이브러리/목록/폴더 이름 | 액세스하는 조직 정보는 Exchange SharePoint 이메일 및 첨부 파일을 저장하는 프로세스를 용이하게 하는 데 사용됩니다. 이 추가 데이터는 미사용 으로 저장되지 않으며 전송 중에 암호화됩니다. 이 데이터의 예로는 선택 열 값, 분류값, 콘텐츠 유형 이름, 폴더 이름, 사이트 이름과 같은 SharePoint 열 값이 포함됩니다.  | 이 데이터는 앱에서 저장하거나 수집되지 않지만 90일 동안 보관되는 원격 분석/로그에 나타날 수 있습니다. | 데이터가 저장되지 않음 |

#### <a name="non-microsoft-services-used"></a>사용되지 Microsoft 서비스

앱이 Microsoft 가 아닌 서비스와 조직 데이터를 전송하거나 공유하는 경우 앱에서 사용하는 비Microsoft 서비스, 전송되는 데이터를 나열하고 앱이 이 정보를 전송해야 하는 이유에 대한 명분을 포함합니다.

>| **모든 Microsoft 서비스 OII가** |  **어떤 OII가 전송됩니까?** | **OII 전송에 대한 정당화?** |
>|:-------------------|:--------------------------|:--------------------------|
>| Chargify 서비스는 구독 관리 및 청구에 사용됩니다. 인앱(무료) 구독 생성의 경우 이름, 성, 사용자의 이메일 주소가 Chargify와 공유됩니다. 구매한 구독(라이선스가 있는 여러 사용자를 지원하는)의 경우 개별 사용자 세부 정보는 Chargify 서비스와 공유되지 않습니다. | 전자 메일 주소 | 사용자에게 구독 수명 주기 이벤트를 전달할 수 있도록 하려면 |



#### <a name="telemetry-data"></a>원격 분석 데이터

조직 식별 정보(OII) 또는 최종 사용자 식별 정보(EUII)가 이 응용 프로그램의 원격 분석 또는 로그에 표시됩니까? 그렇다면 저장되는 데이터와 보존 및 제거 정책은 무엇입니까?

>EUII 및 OII는 원격 분석에 나타납니다. 이 정보는 응용 프로그램 인사이트에 저장되며, 사용 중 암호화되어 90일 후에 액세스 제어 및 삭제됩니다.

#### <a name="organizational-controls-for-data-stored-by-partner"></a>파트너가 저장한 데이터에 대한 조직 제어

조직의 관리자가 파트너 시스템에서 자신의 정보를 제어하는 방법을 설명해 보세요. 예를 들어 삭제, 보존, 감사, 보관, 최종 사용자 정책 등

>응용 프로그램에 저장된 데이터는 전송 및 나머지에 암호화됩니다. 우리는 우리의 애플 리 케이 션에 대 한 Office 365 자격 증명에 의존, 그래서 우리는 우리의 시스템에 사용자 암호를 저장 하지 않습니다. 저장된 데이터/로그/원격 분석에 대한 액세스는 앱의 상태를 실행하고 모니터링하기 위한 목적으로 정보에 액세스할 필요가 있는 내부 관리 직원에게 엄격하게 제어됩니다. Two-Factor 모든 내부 관리 직원에 대해 적용된 인증입니다.

#### <a name="human-review-of-organizational-information"></a>조직 정보의 인간 검토

이 앱에서 수집하거나 저장되는 조직 식별 정보(OII) 데이터를 검토하거나 분석하는 데 관여하는 사람이 있습니까?

>예

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="mcas"

[Microsoft Cloud App Security](https://www.microsoft.com/enterprise-mobility-security/cloud-app-security) 카탈로그의 정보는 아래에 나타납니다.

<iframe height='1020' title='Microsoft Cloud App Security 정보' src='https://appmcasinfoprod.azurewebsites.net/#/dashboard/35746' frameborder='no' style='width: 100%;'></iframe>

<a href="https://appmcasinfoprod.azurewebsites.net/#/dashboard/35746" target="_blank">새 탭에서 보기</a>

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="identity"

### <a name="identity-information"></a>신원 정보

이 정보는 이 앱이 인증, 권한 부여, 응용 프로그램 등록 모범 사례 및 기타 ID 기준을 처리하는 방법에 대해 OnePlace Solutions에서 제공했습니다.

| **정보** | **응답** |
|:----------------|:-------------|
| Microsoft 식별 플랫폼(Azure AD)과 통합합니까?  | 예 |
| Microsoft ID 플랫폼 통합 검사 목록에 설명된 모든 적용 가능한 모범 사례를 검토하고 준수했습니까?  | 예 |
| 앱에서 인증에 MSAL(Microsoft 인증 라이브러리)을 사용합니까? | 예 |
| 앱이 조건부 액세스 정책을 지원합니까? | 아니요 |
| 앱에서 시나리오에 대한 최소 권한 권한을 요청합니까? | 예 |
| 앱의 정적 등록 권한은 앱이 동적으로 점진적으로 요청하는 권한을 정확하게 반영합니까? | 예 |
| 앱이 다중 테넌션을 지원합니까? | 예 |
| 앱에 기밀 클라이언트가 있습니까? | 예 |
| 앱에 등록된 URI(리디렉션 통합 리소스 식별자)를 모두 소유하고 있습니까? | 예 |
| 앱의 경우 무엇을 사용하지 않으려습니까? | - 와일드카드 리디렉션 URI,<br/>- OAuth2 암시적 Flow, SPA에 필요한 경우가 아니면<br/>- 리소스 소유자 암호 자격 증명(ROPC) 흐름 |
| 앱에서 웹 API가 노출됩니까? | 예 |
| 권한 모델은 클라이언트 앱이 적절한 동의를 받는 경우에만 호출을 성공시킬 수 있습니까? | 예 |
| 앱에서 미리 보기 API를 사용합니까? | 아니요 |
| 앱에서 비하 API를 사용합니까? | 아니요 |

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end
