---
title: Plumm Health LTD의 Plumm에 대한 응용 프로그램 정보
ms.author: elmalova
author: elenamalova
ms.date: 10/14/2021
ms.topic: article
ms.service: attestation
certification_type: attested
description: Plumm, 데이터 처리 정책, CSA STAR 레지스트리의 Microsoft Cloud App Security 앱 카탈로그 정보 및 보안/규정 준수 정보에 사용할 수 있는 모든 보안 및 규정 준수 정보
zone_pivot_groups: app-info-data-identity
ms.openlocfilehash: 47a0607828ff96d92cea8be21819fa9e4680f0b4
ms.sourcegitcommit: 9dab9c9dacb9c6daaa6b0041ccc8a49bafdad331
ms.translationtype: MT
ms.contentlocale: ko-KR
ms.lasthandoff: 10/16/2021
ms.locfileid: "60412177"
---
# <a name="plumm"></a>Plumm

<p></p>
<img alt="Publisher Attestation: The information on this page is based on a self-assessment report provided by the app developer on the security, compliance, and data handling practices followed by this app. Microsoft makes no guarantees regarding the accuracy of the information." src="../media/attested.png" width="650" />
<p>개발자가 마지막으로 업데이트한 날짜: 2021년 8월 18일</p>

* <a href="https://teams.microsoft.com/l/app/d66da813-3337-4f88-8e08-f01c0bbb8f34" target="_blank">저장소의 Teams 보기</a>
* <a href="https://appsource.microsoft.com/product/office/WA200003326" target="_blank">AppSource의 보기</a>

::: zone pivot="general"

### <a name="general-information"></a>일반 정보

Plumm Health LTD에서 Microsoft에 제공한 정보:

| **정보** | **응답** |
|:----------------|:-------------|
| 앱 이름 | Plumm |
| ID | WA200003326 |
| Office 365 클라이언트 지원 | Microsoft Teams |
| 파트너 회사 이름 | Plumm Health LTD |
| 파트너 웹 사이트의 URL | [https://www.plummhealth.com](https://www.plummhealth.com) |
| 응용 프로그램 Teams 페이지의 URL입니다. | [https://www.plummhealth.com/about-us](https://www.plummhealth.com/about-us) |
| 개인 정보 취급 방침의 URL | [https://www.plummhealth.com/privacy-policy](https://www.plummhealth.com/privacy-policy) |
| 사용 약관 URL | [https://www.plummhealth.com/terms-of-use](https://www.plummhealth.com/terms-of-use) |

 [!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="data"

### <a name="how-the-app-handles-data"></a>앱이 데이터를 처리하는 방법

이 정보는 Plumm Health LTD에서 이 앱이 조직 데이터를 수집하고 저장하는 방법 및 앱이 수집하는 데이터를 통해 조직에서 제공하는 컨트롤에 대해 제공됩니다.

#### <a name="data-access-using-microsoft-graph"></a>Microsoft 365를 사용한 데이터 Graph

이 앱에 [Graph Microsoft 사용자 권한을](https://docs.microsoft.com/graph/permissions-reference) 나열합니다.

>| **사용 권한**  | **사용 권한 유형(위임/ 응용 프로그램)** | **데이터가 수집하나요? 수집의 사당성** | **데이터가 저장되어 있나요? 저장 사정이 있나요?** | **Azure AD 앱 ID** |
>|:----------------|:------------------------------------------------|:--------------------------------------------------------|:--------------------------------------------------|:--------------------|
>| TeamsActivity.Send | application | 이 사용 권한에서 userID를 사용 합니다. 이 서비스는 서비스 사용 현황에 따라 사용자에게 요청 알림을 보내는 데 사용됩니다. 이는 사용자가 앱에서 계정에 대한 적절한 알림을 받기 위해 중요합니다. | 이 사용 권한에서는 데이터베이스에 데이터를 저장하지 않습니다. 실제로 userID를 사용하여 각 개별 사용자에게 사용 현황에 따라 적절한 알림을 보내고 있습니다. | [b1d1c038-a1f3-4802-be93-0f4a66589e73](https://docs.microsoft.com/microsoft-365-app-certification/azure/b1d1c038-a1f3-4802-be93-0f4a66589e73) |
>| TeamsAppInstallation.ReadWriteForUser.All | application | 이 사용 권한을 사용하여 설치 ID를 받게 됩니다. 이는 각 개별 사용자에 대해 적절하고 올바른 알림을 보낼 수 있도록 하는 데 중요합니다. | 이 사용 권한을 사용하여 앱에 데이터를 저장하지 않습니다. userID를 제공하여 런타임에 얻은 설치 ID만 필요하기 때문에 필요하지 않습니다. 이 설정은 런타시에 동적으로 얻을 수 따라서 설치 ID를 저장할 필요가 없습니다. | [b1d1c038-a1f3-4802-be93-0f4a66589e73](https://docs.microsoft.com/microsoft-365-app-certification/azure/b1d1c038-a1f3-4802-be93-0f4a66589e73) |
>| User.Read | 위임 | 이 사용 권한을 통해 사용자에 대한 이름, 사진 및 전자 메일을 수집하고 있습니다. 이는 개별 사용자를 식별할 수 있도록 하는 데 필요하며, 이러한 데이터 지점은 개별 프로필 페이지와 전자 메일/알림 통신과 같이 필요한 모든 곳에 표시해야 합니다. | 이 사용 권한을 통해 앱에서 사용자의 기본 프로필(이름, 사진, 전자 메일)을 볼 수 있습니다. 이 데이터는 사용자 이름 및/또는 프로필 사진을 앱 계정과 전자 메일 통신 및/또는 알림에 표시하는 데 사용됩니다. | [b1d1c038-a1f3-4802-be93-0f4a66589e73](https://docs.microsoft.com/microsoft-365-app-certification/azure/b1d1c038-a1f3-4802-be93-0f4a66589e73) |
>| User.Read.All | application | 이 사용 권한은 앱에서 로그인한 사용자 없이 사용자 프로필을 읽을 수 있도록 허용합니다. 현재 이름, 프로필 사진 및 전자 메일만 수집하고 있습니다. 이는 개별 사용자를 식별할 수 있도록 하는 데 필요하며, 이러한 데이터 지점은 개별 프로필 페이지와 전자 메일/알림 통신과 같이 필요한 모든 곳에 표시해야 합니다. | 이 사용 권한을 통해 앱에서 사용자의 기본 프로필(이름, 사진, 전자 메일)을 볼 수 있습니다. 이 데이터는 사용자 이름 및/또는 프로필 사진을 앱 계정과 전자 메일 통신 및/또는 알림에 표시하는 데 사용됩니다. | [b1d1c038-a1f3-4802-be93-0f4a66589e73](https://docs.microsoft.com/microsoft-365-app-certification/azure/b1d1c038-a1f3-4802-be93-0f4a66589e73) |
>| 전자 메일 | 위임 | 사용자의 전자 메일 ID가 수집됩니다. 서비스에 대한 액세스 권한을 사용자에게 부여하고 앱에 로그인하고 해당 계정 및 이 전자 메일 ID에 대한 서비스 관련 알림을 받으기 위해 이 데이터가 요구됩니다.  | 전자 메일 ID는 데이터베이스에 저장됩니다. 사용자를 고유하게 식별하고, 앱에 대한 액세스 권한을 제공하고, 로그인하고, 사용자 계정에 대한 알림을 받을 수 있도록 지원하기 위해 전자 메일 ID를 저장해야 합니다. 예를 들어 전자 메일 ID가 abc@xyz.com 사용자가 이 전자 메일 ID로 로그인하면 앱 및 &quot; &quot; Teams 액세스할 수 있습니다. 사용 현황에 따라 이 사용자에게 자신의 전자 메일 ID에 대한 알림을 보낼 수 있습니다. | [b1d1c038-a1f3-4802-be93-0f4a66589e73](https://docs.microsoft.com/microsoft-365-app-certification/azure/b1d1c038-a1f3-4802-be93-0f4a66589e73) |
>| openid | 위임 | 이 사용 권한의 경우 데이터를 수집하지 않습니다.  | 이 사용 권한의 경우 데이터를 수집하지 않습니다. 이 사용 권한은 사용자가 작업 전자 메일 ID로 앱에 로그인할 수 있도록 허용하고 앱에서 기본 사용자 프로필 정보를 볼 수 있도록 합니다. | [b1d1c038-a1f3-4802-be93-0f4a66589e73](https://docs.microsoft.com/microsoft-365-app-certification/azure/b1d1c038-a1f3-4802-be93-0f4a66589e73) |
>| 프로필 | 위임 | 이 사용 권한을 통해 사용자에 대한 이름, 사진 및 전자 메일을 수집하고 있습니다. 이는 개별 사용자를 식별할 수 있도록 하는 데 필요하며, 이러한 데이터 지점은 개별 프로필 페이지와 전자 메일/알림 통신과 같이 필요한 모든 곳에 표시해야 합니다. | 이 사용 권한을 통해 앱에서 사용자의 기본 프로필(이름, 사진, 전자 메일)을 볼 수 있습니다. 이 데이터는 사용자 이름 및/또는 프로필 사진을 앱 계정과 전자 메일 통신 및/또는 알림에 표시하는 데 사용됩니다. | [b1d1c038-a1f3-4802-be93-0f4a66589e73](https://docs.microsoft.com/microsoft-365-app-certification/azure/b1d1c038-a1f3-4802-be93-0f4a66589e73) |


#### <a name="non-microsoft-services-used"></a>비영구 Microsoft 서비스

앱이 Microsoft가 아닌 서비스로 조직 데이터를 전송하거나 공유하는 경우 앱에서 사용하는 비 Microsoft 서비스, 전송되는 데이터를 나열하고 앱이 이 정보를 전송해야 하는 이유에 대한 사유를 포함합니다.

>| **모든 비 Microsoft 서비스 OII가 다음으로 전송됩니다.** |  **전송되는 OII는 무엇입니까?** | **OII 전송의 사당성** |
>|:-----------------------------------------------------|:------------------------------|:----------------------------------------|
>| Intercom | 이름, 성, 전자 메일 | Intercom은 모든 사용자와의 통신을 관리하는 데 도움이 되는 CRM입니다. 따라서 적절한 메시지/전자 메일을 사용자에게 보낼 수 있도록 사용자의 이름, 성 및 전자 메일 ID를 CRM으로 보내야 합니다. |

#### <a name="data-access-via-bots"></a>봇을 통한 데이터 액세스

이 앱에 봇 또는 메시징 확장이 포함되어 있는 경우 팀 구성원의 명단(이름, 성, 표시 이름, 전자 메일 주소)이나 팀 구성원이 추가된 채팅의 최종 사용자 식별 정보(EUII)에 액세스할 수 있습니다. 이 앱이 이 기능을 사용하나요?

>EUII에 액세스하지 않습니다.


#### <a name="telemetry-data"></a>원격 분석 데이터

이 응용 프로그램의 원격 분석 또는 로그에 OII(조직 식별 정보) 또는 EUII(최종 사용자 식별 정보)가 나타나나요? 그렇다면 저장되는 데이터와 보존 및 제거 정책에 대해 설명하세요.

>사용되는 세션 수, 본 과정, 본 명상, 세션 날짜 등의 서비스 사용 데이터를 저장합니다. 사용자가 계정을 삭제하거나 '잊어버린' 계정을 요청할 때까지 사용자에 대한 데이터를 보존합니다.

#### <a name="organizational-controls-for-data-stored-by-partner"></a>파트너가 저장한 데이터에 대한 조직 제어

조직의 관리자가 파트너 시스템에서 정보를 제어하는 방법에 대해 설명하는 방법 삭제, 보존, 감사, 보관, 최종 사용자 정책 등

>서버를 통해 CRM으로 전송되는 데이터를 관리합니다. 작동에 필요한 최소 데이터는 CRM(Intercom)으로 전달됩니다. Plumm은 CRM에 전달되는 데이터, Intercom의 데이터 보존 및 삭제에 대한 모든 제어를 보유합니다. Intercom의 고객 데이터 정책을 검토하기 위한 링크는 다음과 같습니다. https://www.intercom.com/legal/terms-and-policies#customer-data

#### <a name="human-review-of-organizational-information"></a>조직 정보의 인적 검토

사람이 이 앱에서 수집하거나 저장하는 OII(조직 식별 정보) 데이터를 검토하거나 분석하는 데 관여하나요?

>예

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end


::: zone pivot="identity"

### <a name="identity-information"></a>ID 정보

이 정보는 Plumm Health LTD에서 이 앱이 인증, 권한 부여, 응용 프로그램 등록 모범 사례 및 기타 ID 조건을 처리하는 방법에 대해 제공했습니다.

| **정보** | **응답** |
|:----------------|:-------------|
| Microsoft Identify Platform(Azure AD)과 통합하나요?  | 예 |
| 통합 검사 목록에 설명된 적용 가능한 모든 모범 사례를 Microsoft ID 플랫폼 준수하나요?  | 예 |
| 앱에서 인증에 MSAL(Microsoft 인증 라이브러리)을 사용하나요? | 예 |
| 앱에서 조건부 액세스 정책을 지원하나요? | 아니요 |
| 앱에서 시나리오에 대한 최소 권한 권한을 요청하나요? | 예 |
| 앱의 정적으로 등록된 사용 권한은 앱이 동적으로 그리고 증분적으로 요청하는 권한을 정확하게 반영하나요? | 예 |
| 앱에서 다중 테넌시를 지원하나요? | 아니요 |
| 앱에 기밀 클라이언트가 있나요? | 예 |
| 앱에 등록된 리디렉션 URI(통합 리소스 식별자)를 모두 소유하고 있나요? | 예 |
| 앱의 경우 어떻게 사용하지 않도록 해야 하나요? | ,<br/><br/>- 리소스 소유자 암호 자격 증명(ROPC) 흐름 |
| 앱에서 웹 API를 노출하나요? | 예 |
| 사용 권한 모델에서 클라이언트 앱이 적절한 동의를 받은 경우 통화 성공만 허용하나요? | 예 |
| 앱에서 미리 보기 API를 사용하나요? | 아니요 |
| 앱에서 사용되지 않는 API를 사용하나요? | 아니요 |

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

