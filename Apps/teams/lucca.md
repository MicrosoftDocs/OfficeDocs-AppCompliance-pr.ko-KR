---
title: Lucca의 Lucca에 대한 응용 프로그램 정보
ms.author: elmalova
author: elenamalova
ms.date: 09/20/2021
ms.topic: article
ms.service: attestation
certification_type: attested
description: Lucca에 사용할 수 있는 모든 보안 및 규정 준수 정보, 데이터 처리 정책, CSA STAR 레지스트리의 Microsoft Cloud App Security 앱 카탈로그 정보 및 보안/규정 준수 정보
zone_pivot_groups: app-info-data-identity
ms.openlocfilehash: c0ca2e6c6d07dd80afff02a4d9e5081e55633637
ms.sourcegitcommit: 983ed1755036e92d99745770f82f33417b21efec
ms.translationtype: MT
ms.contentlocale: ko-KR
ms.lasthandoff: 10/18/2021
ms.locfileid: "60423170"
---
# <a name="lucca"></a>Lucca

<p></p>
<img alt="Publisher Attestation: The information on this page is based on a self-assessment report provided by the app developer on the security, compliance, and data handling practices followed by this app. Microsoft makes no guarantees regarding the accuracy of the information." src="../media/attested.png" width="650" />
<p>개발자가 마지막으로 업데이트한 날짜: 2021년 8월 23일</p>

* <a href="https://teams.microsoft.com/l/app/53628f6a-ac66-4fde-8945-d639c8da4c0d" target="_blank">저장소의 Teams 보기</a>
* <a href="https://appsource.microsoft.com/product/office/WA200001650" target="_blank">AppSource의 보기</a>

::: zone pivot="general"

### <a name="general-information"></a>일반 정보

Lucca가 Microsoft에 제공하는 정보:

| **정보** | **응답** |
|:----------------|:-------------|
| 앱 이름 | Lucca |
| ID | WA200001650 |
| Office 365 클라이언트 지원 | Microsoft Teams |
| 파트너 회사 이름 | Lucca |
| 파트너 웹 사이트의 URL | [https://www.lucca.fr](https://www.lucca.fr) |
| 개인 정보 취급 방침의 URL | [https://www.lucca.fr/privacy-policy](https://www.lucca.fr/privacy-policy) |
| 사용 약관 URL | [https://cdn2.hubspot.net/hubfs/1582050/3-DOWNLOAD_FILES/Ter...](https://cdn2.hubspot.net/hubfs/1582050/3-DOWNLOAD_FILES/TermsAndConditions.pdf) |

 [!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="data"

### <a name="how-the-app-handles-data"></a>앱이 데이터를 처리하는 방법

이 정보는 Lucca에서 이 앱이 조직 데이터를 수집하고 저장하는 방법 및 앱이 수집하는 데이터를 통해 조직에서 제공하는 컨트롤에 대해 제공합니다.

#### <a name="data-access-using-microsoft-graph"></a>Microsoft 365를 사용한 데이터 Graph

이 앱에 [Graph Microsoft 사용자 권한을](https://docs.microsoft.com/graph/permissions-reference) 나열합니다.

>| **사용 권한**  | **사용 권한 유형(위임/ 응용 프로그램)** | **데이터가 수집하나요? 수집의 사당성** | **데이터가 저장되어 있나요? 저장 사정이 있나요?** | **Azure AD 앱 ID** |
>|:----------------|:------------------------------------------------|:--------------------------------------------------------|:--------------------------------------------------|:--------------------|
>| ChannelMember.Read.All | 위임 | 데이터가 수집되지 않습니다. 이를 사용하여 표시할 계획을 필터링합니다. 채널에 있는 사용자만 계획이 표시됩니다. | 데이터가 저장되지 않습니다. | [53628f6a-ac66-4fde-8945-d639c8da4c0d](https://docs.microsoft.com/microsoft-365-app-certification/azure/53628f6a-ac66-4fde-8945-d639c8da4c0d) |
>| Chat.ReadWrite | application | 데이터가 수집되거나 사용되지 않습니다. 앱은 하루 중 어미가 포함된 메시지만 게시합니다. | 데이터가 저장되지 않습니다. | [53628f6a-ac66-4fde-8945-d639c8da4c0d](https://docs.microsoft.com/microsoft-365-app-certification/azure/53628f6a-ac66-4fde-8945-d639c8da4c0d) |
>| Group.Read.All | application | 앱이 무단으로 메시지를 보내야 하는 그룹을 알기 위해 GroupId를 수집합니다.  | 사용자가 만든 구성을 저장하기 위해 GroupId만 저장합니다. 메시지를 보낼 그룹을 알 수 있습니다. | [53628f6a-ac66-4fde-8945-d639c8da4c0d](https://docs.microsoft.com/microsoft-365-app-certification/azure/53628f6a-ac66-4fde-8945-d639c8da4c0d) |
>| User.Read | 위임 | 사용자 로그인에 사용됩니다. | 데이터가 저장되지 않습니다. | [53628f6a-ac66-4fde-8945-d639c8da4c0d](https://docs.microsoft.com/microsoft-365-app-certification/azure/53628f6a-ac66-4fde-8945-d639c8da4c0d) |
>| User.Read.All | application | 사용자 프로필을 읽는 데 사용됩니다. | 데이터가 저장되지 않습니다. | [53628f6a-ac66-4fde-8945-d639c8da4c0d](https://docs.microsoft.com/microsoft-365-app-certification/azure/53628f6a-ac66-4fde-8945-d639c8da4c0d) |
>| 전자 메일 | 위임 | 앱 탭에 사용자 전자 메일을 표시하는 데 사용됩니다. | 데이터가 저장되지 않습니다. | [53628f6a-ac66-4fde-8945-d639c8da4c0d](https://docs.microsoft.com/microsoft-365-app-certification/azure/53628f6a-ac66-4fde-8945-d639c8da4c0d) |
>| openid | 위임 | 사용자 로그인에 사용됩니다. | 데이터가 저장되지 않습니다. | [53628f6a-ac66-4fde-8945-d639c8da4c0d](https://docs.microsoft.com/microsoft-365-app-certification/azure/53628f6a-ac66-4fde-8945-d639c8da4c0d) |
>| 프로필 | 위임 | 앱 탭에 사용자 프로필을 표시하는 데 사용됩니다. | 데이터가 저장 안 됩니다. | [53628f6a-ac66-4fde-8945-d639c8da4c0d](https://docs.microsoft.com/microsoft-365-app-certification/azure/53628f6a-ac66-4fde-8945-d639c8da4c0d) |


#### <a name="non-microsoft-services-used"></a>비영구 Microsoft 서비스

앱이 Microsoft가 아닌 서비스로 조직 데이터를 전송하거나 공유하는 경우 앱에서 사용하는 비 Microsoft 서비스, 전송되는 데이터를 나열하고 앱이 이 정보를 전송해야 하는 이유에 대한 사유를 포함합니다.

>비영구 Microsoft 서비스 사용되지 않습니다.

#### <a name="data-access-via-bots"></a>봇을 통한 데이터 액세스

이 앱에 봇 또는 메시징 확장이 포함되어 있는 경우 팀 구성원의 명단(이름, 성, 표시 이름, 전자 메일 주소)이나 팀 구성원이 추가된 채팅의 최종 사용자 식별 정보(EUII)에 액세스할 수 있습니다. 이 앱이 이 기능을 사용하나요?

>EUII에 액세스하지 않습니다.


#### <a name="telemetry-data"></a>원격 분석 데이터

이 응용 프로그램의 원격 분석 또는 로그에 OII(조직 식별 정보) 또는 EUII(최종 사용자 식별 정보)가 나타나나요? 그렇다면 저장되는 데이터와 보존 및 제거 정책에 대해 설명하세요.

>응용 프로그램 원격 분석 또는 로그에 OII 또는 EUII가 나타나지 않습니다.

#### <a name="organizational-controls-for-data-stored-by-partner"></a>파트너가 저장한 데이터에 대한 조직 제어

조직의 관리자가 파트너 시스템에서 정보를 제어하는 방법에 대해 설명하는 방법 삭제, 보존, 감사, 보관, 최종 사용자 정책 등

>최종 사용자 정책

#### <a name="human-review-of-organizational-information"></a>조직 정보의 인적 검토

사람이 이 앱에서 수집하거나 저장하는 OII(조직 식별 정보) 데이터를 검토하거나 분석하는 데 관여하나요?

>아니요

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end


::: zone pivot="identity"

### <a name="identity-information"></a>ID 정보

이 정보는 Lucca에서 이 앱이 인증, 권한 부여, 응용 프로그램 등록 모범 사례 및 기타 ID 조건을 처리하는 방법에 대해 제공했습니다.

| **정보** | **응답** |
|:----------------|:-------------|
| Microsoft Identify Platform(Azure AD)과 통합하나요?  | 아니요 |

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end
