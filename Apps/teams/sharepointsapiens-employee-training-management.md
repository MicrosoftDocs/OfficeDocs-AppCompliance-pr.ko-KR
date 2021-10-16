---
title: 직원 교육 관리에 대한 응용 프로그램 SharePoint| Sapiens
ms.author: elmalova
author: elenamalova
ms.date: 07/27/2021
ms.topic: article
ms.service: attestation
certification_type: attested
description: 직원 교육 관리, 데이터 처리 정책, CSA STAR 레지스트리의 Microsoft Cloud App Security 앱 카탈로그 정보 및 보안/규정 준수 정보에 사용할 수 있는 모든 보안 및 규정 준수 정보
zone_pivot_groups: app-info-data-mcas-identity
ms.openlocfilehash: 37505e2f1ba531b3aa1a03a3fb8c93e6da8f121a
ms.sourcegitcommit: 9dab9c9dacb9c6daaa6b0041ccc8a49bafdad331
ms.translationtype: MT
ms.contentlocale: ko-KR
ms.lasthandoff: 10/16/2021
ms.locfileid: "60410922"
---
# <a name="employee-training-management"></a>직원 교육 관리

<p></p>
<img alt="Publisher Attestation: The information on this page is based on a self-assessment report provided by the app developer on the security, compliance, and data handling practices followed by this app. Microsoft makes no guarantees regarding the accuracy of the information." src="../media/attested.png" width="650" />
<p>개발자가 마지막으로 업데이트한 날짜: 2021년 5월 31일</p>

* <a href="https://teams.microsoft.com/l/app/17b6b751-7463-4afd-a3ae-ad26a20c8904" target="_blank">저장소의 Teams 보기</a>
* <a href="https://appsource.microsoft.com/product/office/WA200001512" target="_blank">AppSource의 보기</a>

::: zone pivot="general"

### <a name="general-information"></a>일반 정보

SharePoint| Sapiens에서 Microsoft로:

| **정보** | **응답** |
|:----------------|:-------------|
| 앱 이름 | 직원 교육 관리 |
| ID | WA200001512 |
| Office 365 클라이언트 지원 | Microsoft Teams |
| 파트너 회사 이름 | SharePoint|사피엔스 |
| 파트너 웹 사이트의 URL | [https://www.sharepointsapiens.com](https://www.sharepointsapiens.com) |
| 응용 프로그램 Teams 페이지의 URL입니다. | [https://www.sharepointsapiens.com/employee-training-managem...](https://www.sharepointsapiens.com/employee-training-management-office365/documentation/teams/) |
| 개인 정보 취급 방침의 URL | [https://www.sharepointsapiens.com/privacy/](https://www.sharepointsapiens.com/privacy/) |
| 사용 약관 URL | [https://addins.sharepointsapiens.com/licensing/services-agr...](https://addins.sharepointsapiens.com/licensing/services-agreement.html) |

 [!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="data"

### <a name="how-the-app-handles-data"></a>앱이 데이터를 처리하는 방법

이 정보는 사용자들이 SharePoint| Sapiens는 이 앱이 조직 데이터를 수집하고 저장하는 방법 및 앱이 수집하는 데이터를 통해 조직이 제어할 수 있는 제어에 대해 다산합니다.

#### <a name="data-access-using-microsoft-graph"></a>Microsoft 365를 사용한 데이터 Graph

이 앱에 [Graph Microsoft 사용자 권한을](https://docs.microsoft.com/graph/permissions-reference) 나열합니다.

>| **사용 권한**  | **사용 권한 유형(위임/ 응용 프로그램)** | **데이터가 수집하나요? 수집의 사당성** | **데이터가 저장되어 있나요? 저장 사정이 있나요?** | **Azure AD 앱 ID** |
>|:----------------|:------------------------------------------------|:--------------------------------------------------------|:--------------------------------------------------|:--------------------|
>| User.ReadBasic.All | 위임 | 회의실 및 리소스 예약을 Exchange 회의실 및 리소스의 전자 메일 주소 및 이름 | 데이터가 저장되지 않습니다. | [9e8e113c-8a08-4606-b08a-de4decc7252f](https://docs.microsoft.com/microsoft-365-app-certification/azure/9e8e113c-8a08-4606-b08a-de4decc7252f) |

#### <a name="data-access-using-other-microsoft-apis"></a>다른 Microsoft API를 사용한 데이터 액세스

기본 제공 앱 및 추가 Microsoft 365 Microsoft Graph 기타 Microsoft API를 사용하여 OII(조직 식별 가능 정보)를 수집하거나 처리합니다. 이 앱에서 사용하는 Microsoft API를 Graph Microsoft API를 나열합니다.

>| **API** |  **OII가 수집하나요?** |  **수집되는 OII는 무엇입니까?** | **OII 수집의 사당성** | **OII가 저장되어 있나요?** | **OII 저장의 사당성** |
>|:--------|:-----------------------|:----------------------------|:--------------------------------------|:-------------------|:-----------------------------------|
>| Office 365 Exchange Online | 아니요 |  |  |  |  |

#### <a name="non-microsoft-services-used"></a>비영구 Microsoft 서비스

앱이 Microsoft가 아닌 서비스로 조직 데이터를 전송하거나 공유하는 경우 앱에서 사용하는 비 Microsoft 서비스, 전송되는 데이터를 나열하고 앱이 이 정보를 전송해야 하는 이유에 대한 사유를 포함합니다.

>| **모든 비 Microsoft 서비스 OII가 다음으로 전송됩니다.** |  **전송되는 OII는 무엇입니까?** | **OII 전송의 사당성** |
>|:-----------------------------------------------------|:------------------------------|:----------------------------------------|
>| Mailgun.com(선택 사항), Stripe.com(선택 사항) | 메일 서비스로 사용되는 경우 Stripe.com 청구, 일정 초대 및 사용자 전자 메일 주소로의 답장 및 전자 메일 주소에 사용되는 경우의 회사 이름 및 주소 | 온라인 전자 메일 서비스 대신 메일 서비스를 Exchange 서비스에서는 메일건의 API 및 인프라를 통해 전자 메일을 보내고 받을 수 있습니다. 사서함에서 자체 사서함을 Exchange 메일건에 의해 데이터가 처리되지 않습니다. 신용 카드를 사용하여 구독 요금을 결제하는 경우 수집된 데이터는 신용 카드로 stripe.com. 신용 카드 대신 PO 및 송장을 통해 구매하기로 선택한 경우 모든 사용자가 데이터를 stripe.com. |

#### <a name="data-access-via-bots"></a>봇을 통한 데이터 액세스

이 앱에 봇 또는 메시징 확장이 포함되어 있는 경우 팀 구성원의 명단(이름, 성, 표시 이름, 전자 메일 주소)이나 팀 구성원이 추가된 채팅의 최종 사용자 식별 정보(EUII)에 액세스할 수 있습니다. 이 앱이 이 기능을 사용하나요?

>EUII에 액세스하지 않습니다.


#### <a name="telemetry-data"></a>원격 분석 데이터

이 응용 프로그램의 원격 분석 또는 로그에 OII(조직 식별 정보) 또는 EUII(최종 사용자 식별 정보)가 나타나나요? 그렇다면 저장되는 데이터와 보존 및 제거 정책에 대해 설명하세요.

>EUII는 저장되지 않습니다. TenantID 및 SharePoint 도메인은 앱의 원격 분석에 저장됩니다. 로그 및 원격 분석 데이터는 90일 동안 저장됩니다.

#### <a name="organizational-controls-for-data-stored-by-partner"></a>파트너가 저장한 데이터에 대한 조직 제어

조직의 관리자가 파트너 시스템에서 정보를 제어하는 방법에 대해 설명하는 방법 삭제, 보존, 감사, 보관, 최종 사용자 정책 등

>모든 데이터는 고객의 웹 사이트에 SharePoint 저장됩니다. 앱 설정, 라이선스 및 사용 정보를 제외하고 고객 데이터는 다른 곳에 저장하지 않습니다.

#### <a name="human-review-of-organizational-information"></a>조직 정보의 인적 검토

사람이 이 앱에서 수집하거나 저장하는 OII(조직 식별 정보) 데이터를 검토하거나 분석하는 데 관여하나요?

>예

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="mcas"

Microsoft Cloud App Security [카탈로그의](https://www.microsoft.com/enterprise-mobility-security/cloud-app-security) 정보가 아래에 표시됩니다.

<iframe height='1020' title='Microsoft Cloud App Security 정보' src='https://appmcasinfoprod.azurewebsites.net/#/dashboard/36018' frameborder='no' style='width: 100%;'></iframe>

<a href="https://appmcasinfoprod.azurewebsites.net/#/dashboard/36018" target="_blank">새 탭에서 보기</a>

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="identity"

### <a name="identity-information"></a>ID 정보

이 정보는 사용자들이 SharePoint| Sapiens는 이 앱이 인증, 권한 부여, 응용 프로그램 등록 모범 사례 및 기타 ID 기준을 처리하는 방법에 대해 다루고 있습니다.

| **정보** | **응답** |
|:----------------|:-------------|
| Microsoft Identify Platform(Azure AD)과 통합하나요?  | 예 |
| 통합 검사 목록에 설명된 적용 가능한 모든 모범 사례를 Microsoft ID 플랫폼 준수하나요?  | 예 |
| 앱에서 인증에 MSAL(Microsoft 인증 라이브러리)을 사용하나요? | 예 |
| 앱에서 조건부 액세스 정책을 지원하나요? | 아니요 |
| 앱에서 시나리오에 대한 최소 권한 권한을 요청하나요? | 예 |
| 앱의 정적으로 등록된 사용 권한은 앱이 동적으로 그리고 증분적으로 요청하는 권한을 정확하게 반영하나요? | 예 |
| 앱에서 다중 테넌시를 지원하나요? | 예 |
| 앱에 기밀 클라이언트가 있나요? | 예 |
| 앱에 등록된 리디렉션 URI(통합 리소스 식별자)를 모두 소유하고 있나요? | 예 |
| 앱의 경우 어떻게 사용하지 않도록 해야 하나요? | - 와일드카드 리디렉션 URIS,<br/><br/> |
| 앱에서 웹 API를 노출하나요? | 아니요 |
| 앱에서 미리 보기 API를 사용하나요? | 아니요 |
| 앱에서 사용되지 않는 API를 사용하나요? | 아니요 |

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

