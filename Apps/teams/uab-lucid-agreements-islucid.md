---
title: UAB Lucid 계약에 의해 isLucid에 대한 응용 프로그램 정보
ms.author: elmalova
author: elenamalova
ms.date: 08/09/2021
ms.topic: article
ms.service: attestation
certification_type: attested
description: isLucid, 데이터 처리 정책, CSA STAR 레지스트리의 Microsoft Cloud App Security 앱 카탈로그 정보 및 보안/규정 준수 정보에 대해 사용 가능한 모든 보안 및 규정 준수 정보
zone_pivot_groups: app-info-data-identity
ms.openlocfilehash: d29616471c22a2fd4f01a849d14b965ae106aa80
ms.sourcegitcommit: 23a1fdeaf3905ab5f7acfbb378c7c23aaedcdc29
ms.translationtype: MT
ms.contentlocale: ko-KR
ms.lasthandoff: 09/03/2021
ms.locfileid: "58872083"
---
# <a name="islucid"></a>isLucid

<p></p>
<img alt="Publisher Attestation: The information on this page is based on a self-assessment report provided by the app developer on the security, compliance, and data handling practices followed by this app. Microsoft makes no guarantees regarding the accuracy of the information." src="../media/attested.png" width="650" />
<p>개발자가 마지막으로 업데이트한 날짜: 2021년 8월 9일</p>

* <a href="https://teams.microsoft.com/l/app/a5711b63-5e70-4e4e-b040-0d714b64f684" target="_blank">저장소의 Teams 보기</a>
* <a href="https://appsource.microsoft.com/product/office/WA200002385" target="_blank">AppSource의 보기</a>

::: zone pivot="general"

### <a name="general-information"></a>일반 정보

Microsoft에 대한 UAB Lucid 계약에서 제공하는 정보:

| **정보** | **응답** |
|:----------------|:-------------|
| 앱 이름 | isLucid |
| ID | WA200002385 |
| Office 365 클라이언트 지원 | Microsoft Teams |
| 파트너 회사 이름 | UAB Lucid Agreements |
| 파트너 웹 사이트의 URL | [https://islucid.com](https://islucid.com) |
| 응용 프로그램 Teams 페이지의 URL입니다. | [https://islucid.com](https://islucid.com) |
| 개인 정보 취급 방침의 URL | [https://islucid.com/privacy-policy/](https://islucid.com/privacy-policy/) |
| 사용 약관 URL | [https://islucid.com/eula/](https://islucid.com/eula/) |

 [!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="data"

### <a name="how-the-app-handles-data"></a>앱이 데이터를 처리하는 방법

이 정보는 이 앱이 조직 데이터를 수집하고 저장하는 방법 및 앱이 수집하는 데이터에 대해 조직이 제어할 수 있는 제어에 대한 UAB Lucid 계약에 의해 제공됩니다.

#### <a name="data-access-using-microsoft-graph"></a>Microsoft 365를 사용한 데이터 Graph

이 앱에 [Graph Microsoft 사용자 권한을](https://docs.microsoft.com/graph/permissions-reference) 나열합니다.

>| **사용 권한**  | **사용 권한 유형(위임/ 응용 프로그램)** | **데이터가 수집하나요? 수집의 사당성** | **데이터가 저장되어 있나요? 저장 사정이 있나요?** | **Azure AD 앱 ID** |
>|:----------------|:------------------------------------------------|:--------------------------------------------------------|:--------------------------------------------------|:--------------------|
>| Calls.AccessMedia.All | 둘 다 | 각 통화에 대한 사용자별 동의(시작된 녹음)를 통해 오디오 스트림에 액세스합니다. 오디오 스트림은 사용자가 추가 기능을 사용할 수 있도록 녹음 서비스로 전달됩니다. | 앱은 Azure의 분리된 컨테이너에 저장됩니다(blob storage 및 Cosmos DB를 개별적으로 사용) 전사 및 관련 메타 정보. 응용 프로그램을 사용하며 특정 모임에 참석한 사용자에 대한 모임 정보에 대한 추가 액세스를 제공하는 데 필요합니다. | [98b70422-b0b2-41bf-8673-60d85f5d38c7](https://docs.microsoft.com/microsoft-365-app-certification/azure/98b70422-b0b2-41bf-8673-60d85f5d38c7) |
>| Calls.JoinGroupCall.All | 둘 다 | 각 통화에 대한 사용자별 동의(시작된 녹음)를 통해 오디오 스트림에 액세스합니다. 오디오 스트림은 사용자가 추가 기능을 사용할 수 있도록 녹음 서비스로 전달됩니다. | 앱은 Azure의 분리된 컨테이너에 저장됩니다(blob storage 및 Cosmos DB를 개별적으로 사용) 전사 및 관련 메타 정보. 응용 프로그램을 사용하며 특정 모임에 참석한 사용자에 대한 모임 정보에 대한 추가 액세스를 제공하는 데 필요합니다. | [98b70422-b0b2-41bf-8673-60d85f5d38c7](https://docs.microsoft.com/microsoft-365-app-certification/azure/98b70422-b0b2-41bf-8673-60d85f5d38c7) |
>| Group.ReadWrite.All | 둘 다 | 사용자가 Microsoft Planner와의 통합을 사용하여 통화에서 작업을 만들고 MS Planner에 자동으로 저장하는 경우 isLucid는 해당 사용자 사용 가능한 그룹, 계획, 담당자에 대해 수집합니다. 이 권한이 없는 사용자는 isLucid를 사용하여 전사에서 작업을 만들 수 없습니다. | 작업 제목, 작업 작성자, 작업 타임스탬프, 작업 설명이 저장되어 사용자가 특정 모임에서 수행한 작업 기록에 액세스할 수 있습니다. | [98b70422-b0b2-41bf-8673-60d85f5d38c7](https://docs.microsoft.com/microsoft-365-app-certification/azure/98b70422-b0b2-41bf-8673-60d85f5d38c7) |
>| OnlineMeetings.Read.All | 둘 다 | 응용 프로그램은 모임 제목을 수집하여 나중에 사용자가 이전 대화 및 작업을 더 쉽게 찾을 수 있도록 합니다. | 모임 제목, 모임의 타임스탬프, 모임 이끌이 | [98b70422-b0b2-41bf-8673-60d85f5d38c7](https://docs.microsoft.com/microsoft-365-app-certification/azure/98b70422-b0b2-41bf-8673-60d85f5d38c7) |
>| Tasks.ReadWrite | 둘 다 | 사용자가 Microsoft Planner와의 통합을 사용하여 통화에서 작업을 만들고 MS Planner에 자동으로 저장하는 경우 isLucid는 해당 사용자 사용 가능한 그룹, 계획, 담당자에 대해 수집합니다. 이 권한이 없는 사용자는 isLucid를 사용하여 전사에서 작업을 만들 수 없습니다. | 작업 제목, 작업 작성자, 작업 타임스탬프, 작업 설명이 저장되어 사용자가 특정 모임에서 수행한 작업 기록에 액세스할 수 있습니다. | [98b70422-b0b2-41bf-8673-60d85f5d38c7](https://docs.microsoft.com/microsoft-365-app-certification/azure/98b70422-b0b2-41bf-8673-60d85f5d38c7) |
>| User.ReadWrite.All | 둘 다 | 사용자가 Microsoft Planner와의 통합을 사용하여 통화에서 작업을 만들고 MS Planner에 자동으로 저장하는 경우 isLucid는 해당 사용자 사용 가능한 그룹, 계획, 담당자에 대해 수집합니다. 이 권한이 없는 사용자는 isLucid를 사용하여 전사에서 작업을 만들 수 없습니다. | 작업 제목, 작업 작성자, 작업 타임스탬프, 작업 설명이 저장되어 사용자가 특정 모임에서 수행한 작업 기록에 액세스할 수 있습니다. | [98b70422-b0b2-41bf-8673-60d85f5d38c7](https://docs.microsoft.com/microsoft-365-app-certification/azure/98b70422-b0b2-41bf-8673-60d85f5d38c7) |
>| openid | 둘 다 | 사용자 ID, 사용자에 대한 Azure Active Directory 기능을 제공하기 위해 수집된 테넌트 ID | 추가 권한 관리를 위한 사용자 ID, 테넌트 ID | [98b70422-b0b2-41bf-8673-60d85f5d38c7](https://docs.microsoft.com/microsoft-365-app-certification/azure/98b70422-b0b2-41bf-8673-60d85f5d38c7) |


#### <a name="non-microsoft-services-used"></a>비영구 Microsoft 서비스

앱이 Microsoft가 아닌 서비스로 조직 데이터를 전송하거나 공유하는 경우 앱에서 사용하는 비 Microsoft 서비스, 전송되는 데이터를 나열하고 앱이 이 정보를 전송해야 하는 이유에 대한 사유를 포함합니다.

>| **모든 비 Microsoft 서비스 OII가 다음으로 전송됩니다.** |  **전송되는 OII는 무엇입니까?** | **OII 전송의 사당성** |
>|:-----------------------------------------------------|:------------------------------|:----------------------------------------|
>| hubspot.com | 새로 등록된 전화 이름, 성, 전자 메일 및 메일 수 | 판매 관련 정보를 유지 관리하는 데 Hubspot CRM을 사용하고 있습니다. |

#### <a name="data-access-via-bots"></a>봇을 통한 데이터 액세스

이 앱에 봇 또는 메시징 확장이 포함되어 있는 경우 팀 구성원의 명단(이름, 성, 표시 이름, 전자 메일 주소)이나 팀 구성원이 추가된 채팅의 최종 사용자 식별 정보(EUII)에 액세스할 수 있습니다. 이 앱이 이 기능을 사용하나요?

>| **EUII 액세스의 사유는 무엇입니까?**  | **EUII가 데이터베이스에 저장되어 있나요?** | **EUII 저장의 사유는 무엇입니까?** |
>|:---------------------------------------|:-----------------------------------|:------------------------------------|
>| 봇은 녹음 서비스에 오디오 스트림을 보낼 수 있도록 설정하고 있습니다. 읽을 수 있는 전사 기능을 제공하려면 오디오를 사용자(스피커)와 연결해야 합니다. 이러한 정보를 제공하지 않으면 사용되지 않습니다. | 이름, 성, 게스트 계정 또는 Microsoft 계정인 경우 상태 | 봇은 녹음 서비스에 오디오 스트림을 보낼 수 있도록 설정하고 있습니다. 읽을 수 있는 전사 기능을 제공하려면 오디오를 사용자(스피커)와 연결해야 합니다. 모임 참가자 정보는 모임에 참석한 사용자가 볼 수 있도록 설정하는 데에도 관련이 있습니다. |


#### <a name="telemetry-data"></a>원격 분석 데이터

이 응용 프로그램의 원격 분석 또는 로그에 OII(조직 식별 정보) 또는 EUII(최종 사용자 식별 정보)가 나타나나요? 그렇다면 저장되는 데이터와 보존 및 제거 정책에 대해 설명하세요.

>서비스를 사용하는 동안 사용자는 스크립트를 생성합니다. 기록 모임 참가자(이름, 성)가 나타남 통화 중에 모든 것을 언급할 수 있습니다. 사용자가 서비스를 사용하는 한 이 데이터를 저장합니다. 클라이언트가 사용을 종료하면 30일 이내에 모든 관련 데이터를 폐기합니다.

#### <a name="organizational-controls-for-data-stored-by-partner"></a>파트너가 저장한 데이터에 대한 조직 제어

조직의 관리자가 파트너 시스템에서 정보를 제어하는 방법에 대해 설명하는 방법 삭제, 보존, 감사, 보관, 최종 사용자 정책 등

>클라이언트 구매가 호스팅 솔루션으로 IsLucid인 경우 클라이언트의 데이터는 제어하지 않습니다. SaaS 솔루션의 경우 사용자가 서비스를 사용하여 취소한 다음 파트너와 연결된 Cosmos DB Cosmos 삭제할 수 있습니다. 규정 준수 API로도 정보를 보내고 있습니다.

#### <a name="human-review-of-organizational-information"></a>조직 정보의 인적 검토

사람이 이 앱에서 수집하거나 저장하는 OII(조직 식별 정보) 데이터를 검토하거나 분석하는 데 관여하나요?

>예

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

이 정보는 이 앱이 인증, 권한 부여, 응용 프로그램 등록 모범 사례 및 기타 ID 기준을 처리하는 방법에 대한 UAB Lucid 계약에 의해 제공됩니다.

| **정보** | **응답** |
|:----------------|:-------------|
| Microsoft Identify Platform(Azure AD)과 통합하나요?  | 예 |
| 통합 검사 목록에 설명된 적용 가능한 모든 모범 사례를 Microsoft ID 플랫폼 준수하나요?  | 예 |
| 앱에서 인증에 MSAL(Microsoft 인증 라이브러리)을 사용하나요? | 예 |
| 앱에서 조건부 액세스 정책을 지원하나요? | 아니요 |
| 앱에서 시나리오에 대한 최소 권한 권한을 요청하나요? | 예 |
| 앱의 정적으로 등록된 사용 권한은 앱이 동적으로 그리고 증분적으로 요청하는 권한을 정확하게 반영하나요? | 예 |
| 앱에서 다중 테넌시를 지원하나요? | 예 |
| 앱에 기밀 클라이언트가 있나요? | 아니요 |
| 앱에 등록된 리디렉션 URI(통합 리소스 식별자)를 모두 소유하고 있나요? | 예 |
| 앱의 경우 어떻게 사용하지 않도록 해야 하나요? | - 와일드카드 리디렉션 URIS,<br/>- OAuth2 암시적 Flow SPA에 필요하지 않은 경우<br/>- 리소스 소유자 암호 자격 증명(ROPC) 흐름 |
| 앱에서 웹 API를 노출하나요? | 예 |
| 사용 권한 모델에서 클라이언트 앱이 적절한 동의를 받은 경우 통화 성공만 허용하나요? | 예 |
| 앱에서 미리 보기 API를 사용하나요? | 예 |
| 앱에서 사용되지 않는 API를 사용하나요? | 예 |

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end
