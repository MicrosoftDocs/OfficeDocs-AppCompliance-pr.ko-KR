---
title: Yucca Technologies GmbH의 yuccaHR에 대한 응용 프로그램 정보
ms.author: elmalova
author: elenamalova
ms.date: 07/05/2021
ms.topic: article
ms.service: attestation
certification_type: attested
description: yuccaHR, 데이터 처리 정책, CSA STAR 레지스트리의 Microsoft Cloud App Security 앱 카탈로그 정보 및 보안/규정 준수 정보에 대해 사용 가능한 모든 보안 및 규정 준수 정보
zone_pivot_groups: app-info-data-identity
ms.openlocfilehash: f8c41d6300413db28561f03a71d62c48e52bb63f
ms.sourcegitcommit: d5c60e66355ffa8fb84565e565f8bb15a665a099
ms.translationtype: MT
ms.contentlocale: ko-KR
ms.lasthandoff: 09/24/2021
ms.locfileid: "59785685"
---
# <a name="yuccahr"></a>yuccaHR

<p></p>
<img alt="Publisher Attestation: The information on this page is based on a self-assessment report provided by the app developer on the security, compliance, and data handling practices followed by this app. Microsoft makes no guarantees regarding the accuracy of the information." src="../media/attested.png" width="650" />
<p>개발자가 마지막으로 업데이트한 날짜: 2021년 7월 5일</p>

* <a href="https://teams.microsoft.com/l/app/c3c1cd11-5b38-4de4-9081-44573d9383bf" target="_blank">저장소의 Teams 보기</a>
* <a href="https://appsource.microsoft.com/product/office/WA200003242" target="_blank">AppSource의 보기</a>

::: zone pivot="general"

### <a name="general-information"></a>일반 정보

Yucca Technologies GmbH에서 Microsoft에 제공하는 정보:

| **정보** | **응답** |
|:----------------|:-------------|
| 앱 이름 | yuccaHR |
| ID | WA200003242 |
| Office 365 클라이언트 지원 | Microsoft Teams |
| 파트너 회사 이름 | Yucca Technologies GmbH |
| 파트너 웹 사이트의 URL | [https://www.yuccahr.com](https://www.yuccahr.com) |
| 개인 정보 취급 방침의 URL | [https://www.yuccahr.com/privacy-policy](https://www.yuccahr.com/privacy-policy) |
| 사용 약관 URL | [https://www.yuccahr.com/privacy-policy](https://www.yuccahr.com/privacy-policy) |

 [!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="data"

### <a name="how-the-app-handles-data"></a>앱이 데이터를 처리하는 방법

이 정보는 Yucca Technologies GmbH에서 이 앱이 조직 데이터를 수집하고 저장하는 방법 및 앱이 수집하는 데이터를 통해 조직이 사용할 컨트롤에 대해 제공됩니다.

#### <a name="data-access-using-microsoft-graph"></a>Microsoft 365를 사용한 데이터 Graph

이 앱에 [Graph Microsoft 사용자 권한을](https://docs.microsoft.com/graph/permissions-reference) 나열합니다.

>| **사용 권한**  | **사용 권한 유형(위임/ 응용 프로그램)** | **데이터가 수집하나요? 수집의 사당성** | **데이터가 저장되어 있나요? 저장 사정이 있나요?** | **Azure AD 앱 ID** |
>|:----------------|:------------------------------------------------|:--------------------------------------------------------|:--------------------------------------------------|:--------------------|
>| Calendars.ReadWrite | application |  무료 슬롯을 기반으로 두 직원을 알 수 있는 약속 생성.  | - | [815a5165-fd61-44b8-be99-6301f780bd68](https://docs.microsoft.com/microsoft-365-app-certification/azure/815a5165-fd61-44b8-be99-6301f780bd68) |
>| Channel.ReadBasic.All | application | 캠페인 구성 (직원 네트워킹) | ObjectId. 채널 리소스를 요청합니다. | [815a5165-fd61-44b8-be99-6301f780bd68](https://docs.microsoft.com/microsoft-365-app-certification/azure/815a5165-fd61-44b8-be99-6301f780bd68) |
>| ChannelMember.Read.All | application | ObjectIds 일치하는 캠페인 만들기를 시작하는 채널의 구성원입니다. | ObjectId. 직원 간의 일치를 추적합니다. | [815a5165-fd61-44b8-be99-6301f780bd68](https://docs.microsoft.com/microsoft-365-app-certification/azure/815a5165-fd61-44b8-be99-6301f780bd68) |
>| Group.Read.All | application |   캠페인 구성(직원 네트워킹). | ObjectId. 팀 자원을 요청합니다. | [815a5165-fd61-44b8-be99-6301f780bd68](https://docs.microsoft.com/microsoft-365-app-certification/azure/815a5165-fd61-44b8-be99-6301f780bd68) |
>| MailboxSettings.Read | application | 원하는 언어 및 탐색을 결정하여 해당 직원과 채팅합니다. | - | [815a5165-fd61-44b8-be99-6301f780bd68](https://docs.microsoft.com/microsoft-365-app-certification/azure/815a5165-fd61-44b8-be99-6301f780bd68) |
>| User.Read.All | application | Name, ObjectId, UserPrinzipalName. 해당 직원과 채팅을 탐색합니다. | - | [815a5165-fd61-44b8-be99-6301f780bd68](https://docs.microsoft.com/microsoft-365-app-certification/azure/815a5165-fd61-44b8-be99-6301f780bd68) |


#### <a name="non-microsoft-services-used"></a>비영구 Microsoft 서비스

앱이 Microsoft가 아닌 서비스로 조직 데이터를 전송하거나 공유하는 경우 앱에서 사용하는 비 Microsoft 서비스, 전송되는 데이터를 나열하고 앱이 이 정보를 전송해야 하는 이유에 대한 사유를 포함합니다.

>비영구 Microsoft 서비스 사용되지 않습니다.

#### <a name="data-access-via-bots"></a>봇을 통한 데이터 액세스

이 앱에 봇 또는 메시징 확장이 포함되어 있는 경우 팀 구성원의 명단(이름, 성, 표시 이름, 전자 메일 주소)이나 팀 구성원이 추가된 채팅의 최종 사용자 식별 정보(EUII)에 액세스할 수 있습니다. 이 앱이 이 기능을 사용하나요?

>| **EUII 액세스의 사유는 무엇입니까?**  | **EUII가 데이터베이스에 저장되어 있나요?** | **EUII 저장의 사유는 무엇입니까?** |
>|:---------------------------------------|:-----------------------------------|:------------------------------------|
>| Using the email for scheduling und finding free timeslots. | 아니요 |  |


#### <a name="telemetry-data"></a>원격 분석 데이터

이 응용 프로그램의 원격 분석 또는 로그에 OII(조직 식별 정보) 또는 EUII(최종 사용자 식별 정보)가 나타나나요? 그렇다면 저장되는 데이터와 보존 및 제거 정책에 대해 설명하세요.

>응용 프로그램 원격 분석 또는 로그에 OII 또는 EUII가 나타나지 않습니다.

#### <a name="organizational-controls-for-data-stored-by-partner"></a>파트너가 저장한 데이터에 대한 조직 제어

조직의 관리자가 파트너 시스템에서 정보를 제어하는 방법에 대해 설명하는 방법 삭제, 보존, 감사, 보관, 최종 사용자 정책 등

>고객은 사용자에게 요청을 보내 서비스에 저장된 데이터의 support@yuccahr.com. 데이터는 1주일 이내에 삭제됩니다.

#### <a name="human-review-of-organizational-information"></a>조직 정보의 인적 검토

사람이 이 앱에서 수집하거나 저장하는 OII(조직 식별 정보) 데이터를 검토하거나 분석하는 데 관여하나요?

>아니요

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="mcas"

Microsoft Cloud App Security [카탈로그의](https://www.microsoft.com/enterprise-mobility-security/cloud-app-security) 정보가 아래에 표시됩니다.

<iframe height='1020' title='Microsoft Cloud App Security 정보' src='https://appmcasinfoprod.azurewebsites.net/#/dashboard/' frameborder='no' style='width: 100%;'></iframe>

<a href="https://appmcasinfoprod.azurewebsites.net/#/dashboard/" target="_blank">새 탭에서 보기</a>

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="identity"

### <a name="identity-information"></a>ID 정보

이 정보는 이 앱이 인증, 권한 부여, 응용 프로그램 등록 모범 사례 및 기타 ID 조건을 처리하는 방법에 대해 Yucca Technologies GmbH에서 제공했습니다.

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
| 앱에서 웹 API를 노출하나요? | 예 |
| 사용 권한 모델에서 클라이언트 앱이 적절한 동의를 받은 경우 통화 성공만 허용하나요? | 예 |
| 앱에서 미리 보기 API를 사용하나요? | 아니요 |
| 앱에서 사용되지 않는 API를 사용하나요? | 아니요 |

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end
