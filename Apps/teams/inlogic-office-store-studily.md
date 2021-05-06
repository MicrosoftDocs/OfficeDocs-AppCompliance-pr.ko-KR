---
title: inLogic-Studi.ly 스토어의 응용 프로그램 Office 정보
ms.author: elmalova
author: elenamalova
ms.date: 08/24/2020
ms.topic: article
ms.service: attestation
certification_type: attested
description: CSA STAR 레지스트리의 Studi.ly, 데이터 처리 정책, Microsoft Cloud App Security 앱 카탈로그 정보 및 보안/규정 준수 정보에 대해 사용할 수 있는 모든 보안 및 규정 준수 정보입니다.
zone_pivot_groups: app-info-data-mcas
ms.openlocfilehash: e01185ce576f7326ddde227949c1dbbe1dfff583
ms.sourcegitcommit: 50bd8e07d9355ae65935767a34aca39c46ade8f4
ms.translationtype: MT
ms.contentlocale: ko-KR
ms.lasthandoff: 05/06/2021
ms.locfileid: "52251357"
---
# <a name="studily"></a>Studi.ly

<p></p>
<img alt="Publisher Attestation: The information on this page is based on a self-assessment report provided by the app developer on the security, compliance, and data handling practices followed by this app. Microsoft makes no guarantees regarding the accuracy of the information." src="../media/attested.png" width="650" />
<p>개발자가 마지막으로 업데이트한 날짜: 2020년 8월 24일</p>

* <a href="https://teams.microsoft.com/l/app/a1eca727-7b59-4439-b269-f4b800030518" target="_blank">저장소의 Teams 보기</a>
* <a href="https://appsource.microsoft.com/product/office/WA200001668" target="_blank">AppSource의 보기</a>

::: zone pivot="general"

### <a name="general-information"></a>일반 정보

inLogic-Office Microsoft에 제공되는 정보:

| **정보** | **응답** |
|:----------------|:-------------|
| 앱 이름 | Studi.ly |
| ID | WA200001668 |
| 기능 | 탭 |
| Office 365 클라이언트 지원 | Microsoft Teams |
| 파트너 회사 이름 | inLogic-Office Store |
| 파트너 웹 사이트의 URL | [https://www.studi.ly](https://www.studi.ly) |
| 개인 정보 취급 방침의 URL | [https://www.studi.ly/Studily_Privacy_Statement.pdf](https://www.studi.ly/Studily_Privacy_Statement.pdf) |
| 사용 약관 URL | [https://www.studi.ly/Studily_Terms_Of_Use_v1.pdf](https://www.studi.ly/Studily_Terms_Of_Use_v1.pdf) |

 [!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="data"

### <a name="how-the-app-handles-data"></a>앱이 데이터를 처리하는 방법

이 정보는 inLogic-Office 스토어에서 이 앱이 조직 데이터를 수집하고 저장하는 방법 및 앱이 수집하는 데이터를 통해 조직이 하게 될 컨트롤에 대해 제공됩니다.

#### <a name="data-access-using-microsoft-graph"></a>Microsoft 365를 사용한 데이터 Graph

이 앱에 [Graph Microsoft 사용자 권한을](https://docs.microsoft.com/graph/permissions-reference) 나열합니다.

>| **사용 권한**  | **사용 권한 유형(위임/응용 프로그램)** | **데이터가 수집하나요? 수집의 사당성** | **데이터가 저장되어 있나요? 저장 사정이 있나요?** | **Azure AD 앱 ID** |
>|:----------------|:--------------------|:---------------------------------------------------|:--------------------------|:--------------------------|
>| Calendars.ReadWrite | 위임 | Api에 교육 api의 수업, 학교 및 구성원 및 용어 정보를 저장하고 있으며, 응용 프로그램의 작동을 느리게 만드는 그래프 api에서 매시간 정보를 얻게 될 경우 이 정보가 필요하기 때문에 필요합니다. 교육 api에서 데이터베이스로 시간 기반 이벤트에 동기화합니다. |  | 917edb36-f047-45cf-ad96-0e7e9ec7d8af |
>| Directory.Read.All | 위임 | Api에 교육 api의 수업, 학교 및 구성원 및 용어 정보를 저장하고 있으며, 응용 프로그램의 작동을 느리게 만드는 그래프 api에서 매시간 정보를 얻게 될 경우 이 정보가 필요하기 때문에 필요합니다. 교육 api에서 데이터베이스로 시간 기반 이벤트에 동기화합니다. | 배정 및 자료에 대한 디렉터리를 그룹에 써야 합니다. | 917edb36-f047-45cf-ad96-0e7e9ec7d8af |
>| Directory.ReadWrite.All | application | Api에 교육 api의 수업, 학교 및 구성원 및 용어 정보를 저장하고 있으며, 응용 프로그램의 작동을 느리게 만드는 그래프 api에서 매시간 정보를 얻게 될 경우 이 정보가 필요하기 때문에 필요합니다. 교육 api에서 데이터베이스로 시간 기반 이벤트에 동기화합니다. | 배정 및 자료에 대한 디렉터리를 그룹에 써야 합니다. | 917edb36-f047-45cf-ad96-0e7e9ec7d8af |
>| EduRoster.Read.All | application | Api에 교육 api의 수업, 학교 및 구성원 및 용어 정보를 저장하고 있으며, 응용 프로그램의 작동을 느리게 만드는 그래프 api에서 매시간 정보를 얻게 될 경우 필요하기 때문에 필요합니다. 교육 api에서 데이터베이스로 시간 기반 이벤트에 동기화합니다. | 교육 수업, 학교, 구성원 및 용어를 읽습니다. 앱 데이터베이스에 동기화하기 위해 테넌트의 모든 클래스 및 학교를 다운로드합니다. | 917edb36-f047-45cf-ad96-0e7e9ec7d8af |
>| EduRoster.ReadBasic | 위임 | Api에 교육 api의 수업, 학교 및 구성원 및 용어 정보를 저장하고 있으며, 응용 프로그램의 작동을 느리게 만드는 그래프 api에서 매시간 정보를 얻게 될 경우 이 정보가 필요하기 때문에 필요합니다. 교육 api에서 데이터베이스로 시간 기반 이벤트에 동기화합니다. | 교육 수업, 학교, 구성원 및 용어를 읽습니다. 앱 데이터베이스에 동기화하기 위해 테넌트의 모든 클래스 및 학교를 다운로드합니다. | 917edb36-f047-45cf-ad96-0e7e9ec7d8af |
>| EduRoster.ReadWrite.All | application | Api에 교육 api의 수업, 학교 및 구성원 및 용어 정보를 저장하고 있으며, 응용 프로그램의 작동을 느리게 만드는 그래프 api에서 매시간 정보를 얻게 될 경우 이 정보가 필요하기 때문에 필요합니다. 교육 api에서 데이터베이스로 시간 기반 이벤트에 동기화합니다. | 교육 수업, 학교, 구성원 및 용어를 읽습니다. 앱 데이터베이스에 동기화하기 위해 테넌트의 모든 클래스 및 학교를 다운로드합니다. | 917edb36-f047-45cf-ad96-0e7e9ec7d8af |
>| Files.ReadWrite.All | 위임 | Api에 교육 api의 수업, 학교 및 구성원 및 용어 정보를 저장하고 있으며, 응용 프로그램의 작동을 느리게 만드는 그래프 api에서 매시간 정보를 얻게 될 경우 이 정보가 필요하기 때문에 필요합니다. 교육 api에서 데이터베이스로 시간 기반 이벤트에 동기화합니다. | One Drive에서 읽기Write 파일 | 917edb36-f047-45cf-ad96-0e7e9ec7d8af |
>| Group.Read.All | 위임 | Api에 교육 api의 수업, 학교 및 구성원 및 용어 정보를 저장하고 있으며, 응용 프로그램의 작동을 느리게 만드는 그래프 api에서 매시간 정보를 얻게 될 경우 이 정보가 필요하기 때문에 필요합니다. 교육 api에서 데이터베이스로 시간 기반 이벤트에 동기화합니다. | 이 사용 권한은 앱이 테넌트 그룹의 다른 클레더 이벤트를 받을 수 있도록 허용했습니다.,subject,start,end,extensions | 917edb36-f047-45cf-ad96-0e7e9ec7d8af |
>| Group.ReadWrite.All | 둘 다 | Api에 교육 api의 수업, 학교 및 구성원 및 용어 정보를 저장하고 있으며, 응용 프로그램의 작동을 느리게 만드는 그래프 api에서 매시간 정보를 얻게 될 경우 이 정보가 필요하기 때문에 필요합니다. 교육 api에서 데이터베이스로 시간 기반 이벤트에 동기화합니다. | 이 사용 권한은 앱이 테넌트 그룹의 다른 클레더 이벤트를 받을 수 있도록 허용했습니다.,subject,start,end,extensions | 917edb36-f047-45cf-ad96-0e7e9ec7d8af |
>| Member.Read.Hidden | application |  |  | 917edb36-f047-45cf-ad96-0e7e9ec7d8af |
>| Sites.ReadWrite.All | 둘 다 | Api에 교육 api의 수업, 학교 및 구성원 및 용어 정보를 저장하고 있으며, 응용 프로그램의 작동을 느리게 만드는 그래프 api에서 매시간 정보를 얻게 될 경우 이 정보가 필요하기 때문에 필요합니다. 교육 api에서 데이터베이스로 시간 기반 이벤트에 동기화합니다. | One Drive에서 읽기Write 파일 | 917edb36-f047-45cf-ad96-0e7e9ec7d8af |
>| User.Read | 위임 | Api에 교육 api의 수업, 학교 및 구성원 및 용어 정보를 저장하고 있으며, 응용 프로그램의 작동을 느리게 만드는 그래프 api에서 매시간 정보를 얻게 될 경우 이 정보가 필요하기 때문에 필요합니다. 교육 api에서 데이터베이스로 시간 기반 이벤트에 동기화합니다. | 사용자 정보 읽기 | 917edb36-f047-45cf-ad96-0e7e9ec7d8af |
>| User.ReadBasic.All | 위임 | Api에 교육 api의 수업, 학교 및 구성원 및 용어 정보를 저장하고 있으며, 응용 프로그램의 작동을 느리게 만드는 그래프 api에서 매시간 정보를 얻게 될 경우 이 정보가 필요하기 때문에 필요합니다. 교육 api에서 데이터베이스로 시간 기반 이벤트에 동기화합니다. | 사용자 정보 읽기 | 917edb36-f047-45cf-ad96-0e7e9ec7d8af |


#### <a name="non-microsoft-services-used"></a>비영구 Microsoft 서비스

앱이 Microsoft가 아닌 서비스로 조직 데이터를 전송하거나 공유하는 경우 앱에서 사용하는 비 Microsoft 서비스, 전송되는 데이터를 나열하고 앱이 이 정보를 전송해야 하는 이유에 대한 사유를 포함합니다.

>비영구 Microsoft 서비스 사용되지 않습니다.

#### <a name="data-access-via-bots"></a>봇을 통한 데이터 액세스

이 앱에 봇 또는 메시징 확장이 포함되어 있는 경우 팀 구성원의 명단(이름, 성, 표시 이름, 전자 메일 주소)이나 팀 구성원이 추가된 채팅의 최종 사용자 식별 정보(EUII)에 액세스할 수 있습니다. 이 앱이 이 기능을 사용하나요?

>EUII에 액세스하지 않습니다.



#### <a name="telemetry-data"></a>원격 분석 데이터

이 응용 프로그램의 원격 분석 또는 로그에 OII(조직 식별 정보) 또는 EUII(최종 사용자 식별 정보)가 나타나나요? 그렇다면 저장되는 데이터와 보존 및 제거 정책에 대해 설명하세요.

>이러한 데이터는 로그에 나타나지 않습니다.

#### <a name="organizational-controls-for-data-stored-by-partner"></a>파트너가 저장한 데이터에 대한 조직 제어

조직의 관리자가 파트너 시스템에서 정보를 제어하는 방법에 대해 설명하는 방법 삭제, 보존, 감사, 보관, 최종 사용자 정책 등

>이 데이터베이스는 Azure cosmos 데이터베이스에 저장되고 cosmos 데이터베이스에서 기본적으로 사용할 수 있는 암호화 및 저장소는 이 응용 프로그램에 적용됩니다.

#### <a name="human-review-of-organizational-information"></a>조직 정보의 인적 검토

사람이 이 앱에서 수집하거나 저장하는 OII(조직 식별 정보) 데이터를 검토하거나 분석하는 데 관여하나요?

>아니요

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="mcas"

Microsoft Cloud App Security [카탈로그의](https://www.microsoft.com/enterprise-mobility-security/cloud-app-security) 정보가 아래에 표시됩니다.

<iframe height='1020' title='Microsoft Cloud App Security 정보' src='https://appmcasinfoprod.azurewebsites.net/#/dashboard/35976' frameborder='no' style='width: 100%;'></iframe>

<a href="https://appmcasinfoprod.azurewebsites.net/#/dashboard/35976" target="_blank">새 탭에서 보기</a>

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

