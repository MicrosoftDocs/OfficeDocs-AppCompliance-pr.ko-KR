---
title: Application Information for atSpoke by Townsend Street Labs, Inc.
ms.author: elmalova
author: elenamalova
ms.date: 04/14/2020
ms.topic: article
ms.service: attestation
certification_type: attested
description: atSpoke에 사용할 수 있는 모든 보안 및 규정 준수 정보, 데이터 처리 정책, Microsoft Cloud App Security 앱 카탈로그 정보 및 CSA STAR 레지스트리의 보안/규정 준수 정보
zone_pivot_groups: app-info-data-mcas
ms.openlocfilehash: 17fc89d254fd558c318c48de53456e9fa23054f7
ms.sourcegitcommit: 983ed1755036e92d99745770f82f33417b21efec
ms.translationtype: MT
ms.contentlocale: ko-KR
ms.lasthandoff: 10/18/2021
ms.locfileid: "60429826"
---
# <a name="atspoke"></a>atSpoke

<p></p>
<img alt="Publisher Attestation: The information on this page is based on a self-assessment report provided by the app developer on the security, compliance, and data handling practices followed by this app. Microsoft makes no guarantees regarding the accuracy of the information." src="../media/attested.png" width="650" />
<p>개발자가 마지막으로 업데이트한 날짜: 2020년 6월 3일</p>

* <a href="https://teams.microsoft.com/l/app/dfaf15dc-4e94-4484-a25d-79358fe70d8b" target="_blank">저장소의 Teams 보기</a>
* <a href="https://appsource.microsoft.com/product/office/WA200001454" target="_blank">AppSource의 보기</a>

::: zone pivot="general"

### <a name="general-information"></a>일반 정보

Street Labs, Inc.에서 Microsoft에 제공한 정보:

| **정보** | **응답** |
|:----------------|:-------------|
| 앱 이름 | atSpoke |
| ID | WA200001454 |
| Office 365 클라이언트 지원 | Microsoft Teams |
| 파트너 회사 이름 | Townsend Street Labs, Inc. |
| 파트너 웹 사이트의 URL | [https://www.atspoke.com/](https://www.atspoke.com/) |
| 개인 정보 취급 방침의 URL | [https://www.atspoke.com/privacy-policy/](https://www.atspoke.com/privacy-policy/) |
| 사용 약관 URL | [https://www.atspoke.com/terms-of-service/](https://www.atspoke.com/terms-of-service/) |

 [!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="data"

### <a name="how-the-app-handles-data"></a>앱이 데이터를 처리하는 방법

이 정보는 Street Labs, Inc.에서 이 앱이 조직 데이터를 수집 및 저장하는 방법과 앱이 수집하는 데이터를 통해 조직에서 제공하는 컨트롤에 대해 제공됩니다.

#### <a name="data-access-using-microsoft-graph"></a>Microsoft 365를 사용한 데이터 Graph

이 앱에 [Graph Microsoft 사용자 권한을](https://docs.microsoft.com/graph/permissions-reference) 나열합니다.

>| **사용 권한**  | **사용 권한 유형(위임/ 응용 프로그램)** | **데이터가 수집하나요? 수집의 사당성** | **데이터가 저장되어 있나요? 저장 사정이 있나요?** | **Azure AD 앱 ID** |
>|:----------------|:------------------------------------------------|:--------------------------------------------------------|:--------------------------------------------------|:--------------------|
>| Group.ReadWrite.All | 위임 | atSpoke는 Microsoft 그룹 ID를 저장합니다. | atSpoke와 atSpoke 간에 그룹 정보를 읽고 쓸 수 Microsoft Teams.  | [dfaf15dc-4e94-4484-a25d-79358fe70d8b](https://docs.microsoft.com/microsoft-365-app-certification/azure/dfaf15dc-4e94-4484-a25d-79358fe70d8b) |
>| User.ReadWrite.All | 위임 | atSpoke는 사용자 전자 메일 및 사용자 ID를 저장합니다. | atSpoke와 atSpoke 간에 사용자 정보를 읽고 쓸 수 Microsoft Teams. | [dfaf15dc-4e94-4484-a25d-79358fe70d8b](https://docs.microsoft.com/microsoft-365-app-certification/azure/dfaf15dc-4e94-4484-a25d-79358fe70d8b) |
>| offline_access | 위임 | atSpoke는 이에 대한 데이터를 저장하지 않습니다. | 백그라운드 동기화에 사용됩니다. | [dfaf15dc-4e94-4484-a25d-79358fe70d8b](https://docs.microsoft.com/microsoft-365-app-certification/azure/dfaf15dc-4e94-4484-a25d-79358fe70d8b) |


#### <a name="non-microsoft-services-used"></a>비영구 Microsoft 서비스

앱이 Microsoft가 아닌 서비스로 조직 데이터를 전송하거나 공유하는 경우 앱에서 사용하는 비 Microsoft 서비스, 전송되는 데이터를 나열하고 앱이 이 정보를 전송해야 하는 이유에 대한 사유를 포함합니다.

>| **모든 비 Microsoft 서비스 OII가 다음으로 전송됩니다.** |  **전송되는 OII는 무엇입니까?** | **OII 전송의 사당성** |
>|:-----------------------------------------------------|:------------------------------|:----------------------------------------|
>| 예, 운영 효율성을 위해 타사 서비스를 사용 합니다. Google, Inc.: 논리 볼륨에 저장된 데이터, 기본 Google 클라우드 네트워크의 저장소 백업, 서비스 및 API 로그 또는 응용 프로그램 로그. 기록된 트랜잭션 이벤트에는 사용자 식별자, 연락처 정보 및 고객 콘텐츠가 포함될 수 있습니다. MongoDB, Inc.: 클라우드 기반 데이터베이스 컬렉션에 저장된 데이터입니다. - 사용자가 제출한 요청, 사용자가 추가한 요청에 대한 응답, 사용자가 추가한 기술 문서가 포함된 고객 콘텐츠 - 사용자 식별자(Spoke 사용자 계정을 만드는 데 사용되는 이름, 전자 메일, 아바타 및 전화 번호). Mailgun Technologies, Inc.: 전자 메일 통신(예: 이름 및 전자 메일)을 보낼 사용자 식별자 및 연락처 정보입니다. Twilio, Inc.: 사용자 전화 번호 및 고객 콘텐츠: 텍스트, 메시지 본문&#8217;음성 및 비디오 미디어, 이미지, 소리 등 Twilio&#8217;서비스를 사용하여 교환되는 콘텐츠입니다. Mixpanel, Inc.: 전송되는 개인 데이터에는 메시지 콘텐츠에 포함된 이름, 전자 메일, IP 주소 및 개인 데이터가 포함됩니다. Cloudinary, Inc.: 최종 사용자가 제출한 파일 기반 고객 콘텐츠입니다. Elasticsearch, Inc.: 기록된 응용 프로그램 트랜잭션 이벤트에는 고객 콘텐츠의 텍스트가 소진될 수 있습니다. Stitch, Inc.: 연락처 정보, 사용 현황 정보, 구독자의 권한이 부여된 사용자의 일반 식별자 외의 모든 개인 데이터 구독자 또는 권한이 부여된 사용자가 플랫폼에 제출합니다. Mode Analytics, Inc.: 사용자당 분석을 제공하는 사용자 식별자 정보입니다. DataDog: 기록된 응용 프로그램 트랜잭션 이벤트에 고객 콘텐츠의 텍스트가 일부 포함되어 있을 수 있습니다. 로그 보존 기간은 14일입니다. Fullstory, Inc.: 웹 사용자 인터페이스에서 수행된 작업 기록 식별을 위해 Spoke의 사용자 계정을 포함합니다. |  | Bot Framework REST API를 사용하고 있습니다. 이 API를 사용하여 askSpoke 봇 서비스에 메시지를 보내고 받을 수 있습니다. |

#### <a name="data-access-via-bots"></a>봇을 통한 데이터 액세스

이 앱에 봇 또는 메시징 확장이 포함되어 있는 경우 팀 구성원의 명단(이름, 성, 표시 이름, 전자 메일 주소)이나 팀 구성원이 추가된 채팅의 최종 사용자 식별 정보(EUII)에 액세스할 수 있습니다. 이 앱이 이 기능을 사용하나요?

>| **EUII 액세스의 사유는 무엇입니까?**  | **EUII가 데이터베이스에 저장되어 있나요?** | **EUII 저장의 사유는 무엇입니까?** |
>|:---------------------------------------|:-----------------------------------|:------------------------------------|
>| atSpoke는 atSpoke에서 사용자를 동기화하여 사용자를 Microsoft Teams 권한을 정의할 수 있습니다. | atSpoke는 사용자가 atSpoke에 Microsoft Teams 수 있도록 전자 메일만 저장합니다. |  |


#### <a name="telemetry-data"></a>원격 분석 데이터

이 응용 프로그램의 원격 분석 또는 로그에 OII(조직 식별 정보) 또는 EUII(최종 사용자 식별 정보)가 나타나나요? 그렇다면 저장되는 데이터와 보존 및 제거 정책에 대해 설명하세요.

>응용 프로그램 로그에 포함된 사용자의 이름과 성, 사용자의 전자 메일 주소 및 사용자 및 그룹에 대한 Azure 할당 개체 ID가 있습니다. 로그는 자동으로 만료되는 시점에서 14일 동안만 보존됩니다. 로그 액세스는 변조로부터 보호하며 특정 직원만 로그를 볼 수 있습니다.

#### <a name="organizational-controls-for-data-stored-by-partner"></a>파트너가 저장한 데이터에 대한 조직 제어

조직의 관리자가 파트너 시스템에서 정보를 제어하는 방법에 대해 설명하는 방법 삭제, 보존, 감사, 보관, 최종 사용자 정책 등

>응용 프로그램 데이터는 관리되는 MongoDB 인스턴스에 저장됩니다. 관리 서비스 Atlas MongoDB 데이터베이스에 대한 액세스는 승인이 필요한 표준화된 사용자 액세스 요청 프로세스를 통해 프로비전됩니다. 주기적인 사용자 액세스 검토는 관리 서명을 통해 수행됩니다. 중요한 고객 데이터에 액세스할 수 있는 직원 수를 제한하며 모든 컴퓨터의 데이터를 직접 수정할 수 없습니다.&#8232; 원격 액세스에는 다단계 인증이 필요합니다. 데이터베이스 및 모든 백업은 AES-256 비트 암호화를 사용하여 미사용으로 암호화됩니다.


#### <a name="human-review-of-organizational-information"></a>조직 정보의 인적 검토

사람이 이 앱에서 수집하거나 저장하는 OII(조직 식별 정보) 데이터를 검토하거나 분석하는 데 관여하나요?

>예

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="mcas"

Microsoft Cloud App Security [카탈로그의](https://www.microsoft.com/enterprise-mobility-security/cloud-app-security) 정보가 아래에 표시됩니다.

<iframe height='1020' title='Microsoft Cloud App Security 정보' src='https://appmcasinfoprod.azurewebsites.net/#/dashboard/35866' frameborder='no' style='width: 100%;'></iframe>

<a href="https://appmcasinfoprod.azurewebsites.net/#/dashboard/35866" target="_blank">새 탭에서 보기</a>

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

