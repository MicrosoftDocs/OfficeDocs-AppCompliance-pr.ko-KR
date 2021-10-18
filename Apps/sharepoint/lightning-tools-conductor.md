---
title: 번개 도구로 번개 도우미에 대한 응용 프로그램 정보
ms.author: elmalova
author: elenamalova
ms.date: 09/29/2021
ms.topic: article
ms.service: attestation
certification_type: attested
description: Lightning Tools Lightning Conductor, 데이터 처리 정책, CSA STAR 레지스트리의 Microsoft Cloud App Security 앱 카탈로그 정보 및 보안/규정 준수 정보에 사용할 수 있는 모든 보안 및 규정 준수 정보
zone_pivot_groups: app-info-data-identity
ms.openlocfilehash: 9f597f25df7b000d3d98a2dfbc4fe3c34fef7842
ms.sourcegitcommit: 983ed1755036e92d99745770f82f33417b21efec
ms.translationtype: MT
ms.contentlocale: ko-KR
ms.lasthandoff: 10/18/2021
ms.locfileid: "60430528"
---
# <a name="lightning-tools-lightning-conductor"></a>번개 도구 번개 도우미

<p></p>
<img alt="Publisher Attestation: The information on this page is based on a self-assessment report provided by the app developer on the security, compliance, and data handling practices followed by this app. Microsoft makes no guarantees regarding the accuracy of the information." src="../media/attested.png" width="650" />
<p>개발자가 마지막으로 업데이트한 날짜: 2021년 7월 12일</p>

* <a href="https://appsource.microsoft.com/product/office/WA200001926" target="_blank">AppSource의 보기</a>

::: zone pivot="general"

### <a name="general-information"></a>일반 정보

Lightning Tools에서 Microsoft에 제공하는 정보:

| **정보** | **응답** |
|:----------------|:-------------|
| 앱 이름 | 번개 도구 번개 도우미 |
| ID | WA200001926 |
| Office 365 클라이언트 지원 | SharePoint 2016 이상 |
| 파트너 회사 이름 | 번개 도구 |
| 파트너 웹 사이트의 URL | [https://lightningtools.com](https://lightningtools.com) |
| 개인 정보 취급 방침의 URL | [https://lightningtools.com/lightning-conductor-cswp-privacy...](https://lightningtools.com/lightning-conductor-cswp-privacy-policy) |
| 사용 약관 URL | [https://lightningtools.com/lightning-tools-lightning-conduc...](https://lightningtools.com/lightning-tools-lightning-conductor-client-side-web-part-software-license-agreement) |

 [!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="data"

### <a name="how-the-app-handles-data"></a>앱이 데이터를 처리하는 방법

이 정보는 Lightning Tools에서 이 앱이 조직 데이터를 수집하고 저장하는 방법 및 앱이 수집하는 데이터를 통해 조직이 가지는 컨트롤에 대해 제공됩니다.

#### <a name="data-access-using-microsoft-graph"></a>Microsoft 365를 사용한 데이터 Graph

이 앱에 [Graph Microsoft 사용자 권한을](https://docs.microsoft.com/graph/permissions-reference) 나열합니다.

>| **사용 권한**  | **사용 권한 유형(위임/ 응용 프로그램)** | **데이터가 수집하나요? 수집의 사당성** | **데이터가 저장되어 있나요? 저장 사정이 있나요?** | **Azure AD 앱 ID** |
>|:----------------|:------------------------------------------------|:--------------------------------------------------------|:--------------------------------------------------|:--------------------|
>| Calendars.Read | application | 달력 정보를 쿼리하고 보고하기 위해 | 번개 도우미는 데이터베이스 또는 데이터를 저장하지 않습니다. | [a96cbd10-e960-47b8-855b-3af4b5dbd6f4](https://docs.microsoft.com/microsoft-365-app-certification/azure/a96cbd10-e960-47b8-855b-3af4b5dbd6f4) |
>| Contacts.Read | application | 데이터가 수집되거나 저장되지 않습니다. 데이터는 현재 사용자 연락처의 DisplayName을 표시하는 데 사용됩니다. | 번개 도우미는 데이터베이스 또는 데이터를 저장하지 않습니다. | [a96cbd10-e960-47b8-855b-3af4b5dbd6f4](https://docs.microsoft.com/microsoft-365-app-certification/azure/a96cbd10-e960-47b8-855b-3af4b5dbd6f4) |
>| Directory.Read.All | application | 번개 도우미에 사용자 표시 | 번개 도우미는 데이터베이스 또는 데이터를 저장하지 않습니다. | [a96cbd10-e960-47b8-855b-3af4b5dbd6f4](https://docs.microsoft.com/microsoft-365-app-certification/azure/a96cbd10-e960-47b8-855b-3af4b5dbd6f4) |
>| Files.Read.All | application | 번 OneDrive 파일 표시 | 번개 도우미는 데이터베이스 또는 데이터를 저장하지 않습니다. | [a96cbd10-e960-47b8-855b-3af4b5dbd6f4](https://docs.microsoft.com/microsoft-365-app-certification/azure/a96cbd10-e960-47b8-855b-3af4b5dbd6f4) |
>| Mail.Read | application | 번개 도우미의 쿼리에 현재 사용자 사서함의 메시지가 표시되는 경우 | 번개 도우미는 데이터베이스 또는 데이터를 저장하지 않습니다. | [a96cbd10-e960-47b8-855b-3af4b5dbd6f4](https://docs.microsoft.com/microsoft-365-app-certification/azure/a96cbd10-e960-47b8-855b-3af4b5dbd6f4) |
>| People.Read.All | application | 사용자를 사이트의 구성원으로 쿼리하는 경우 번개 실행자에 사용자 보기를 표시하는 경우 | 번개 도우미는 데이터베이스 또는 데이터를 저장하지 않습니다. | [a96cbd10-e960-47b8-855b-3af4b5dbd6f4](https://docs.microsoft.com/microsoft-365-app-certification/azure/a96cbd10-e960-47b8-855b-3af4b5dbd6f4) |
>| Presence.Read.All | application | 사용자 카드에 사용자 현재 상태 표시 | 번개 도우미는 데이터베이스 또는 데이터를 저장하지 않습니다. | [a96cbd10-e960-47b8-855b-3af4b5dbd6f4](https://docs.microsoft.com/microsoft-365-app-certification/azure/a96cbd10-e960-47b8-855b-3af4b5dbd6f4) |
>| Sites.Read.All | application | 번개 도우미 트리뷰에서 사이트를 열00 | 번개 도우미는 데이터베이스 또는 데이터를 저장하지 않습니다. | [a96cbd10-e960-47b8-855b-3af4b5dbd6f4](https://docs.microsoft.com/microsoft-365-app-certification/azure/a96cbd10-e960-47b8-855b-3af4b5dbd6f4) |


#### <a name="non-microsoft-services-used"></a>비영구 Microsoft 서비스

앱이 Microsoft가 아닌 서비스로 조직 데이터를 전송하거나 공유하는 경우 앱에서 사용하는 비 Microsoft 서비스, 전송되는 데이터를 나열하고 앱이 이 정보를 전송해야 하는 이유에 대한 사유를 포함합니다.

>비영구 Microsoft 서비스 사용되지 않습니다.



#### <a name="telemetry-data"></a>원격 분석 데이터

이 응용 프로그램의 원격 분석 또는 로그에 OII(조직 식별 정보) 또는 EUII(최종 사용자 식별 정보)가 나타나나요? 그렇다면 저장되는 데이터와 보존 및 제거 정책에 대해 설명하세요.

>응용 프로그램 원격 분석 또는 로그에 OII 또는 EUII가 나타나지 않습니다.

#### <a name="organizational-controls-for-data-stored-by-partner"></a>파트너가 저장한 데이터에 대한 조직 제어

조직의 관리자가 파트너 시스템에서 정보를 제어하는 방법에 대해 설명하는 방법 삭제, 보존, 감사, 보관, 최종 사용자 정책 등

>앱 내의 데이터는 고객 테넌트 내에 있습니다. 번개 도구는 고객 테넌트 외부의 데이터를 저장하거나 처리하지 않습니다. 

#### <a name="human-review-of-organizational-information"></a>조직 정보의 인적 검토

사람이 이 앱에서 수집하거나 저장하는 OII(조직 식별 정보) 데이터를 검토하거나 분석하는 데 관여하나요?

>예

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end


::: zone pivot="identity"

### <a name="identity-information"></a>ID 정보

이 정보는 Lightning Tools에서 이 앱이 인증, 권한 부여, 응용 프로그램 등록 모범 사례 및 기타 ID 조건을 처리하는 방법에 대해 제공했습니다.

| **정보** | **응답** |
|:----------------|:-------------|
| Microsoft Identify Platform(Azure AD)과 통합하나요?  | 아니요 |

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end
