---
title: 트라이안 분석용 응용 프로그램 정보
ms.author: elmalova
author: elenamalova
ms.date: 09/28/2020
ms.topic: article
ms.service: attestation
certification_type: attested
description: Tryane Analytics, 데이터 처리 정책, Microsoft Cloud App Security 앱 카탈로그 정보 및 CSA STAR 레지스트리의 보안/규정 준수 정보에 대한 사용 가능한 모든 보안 및 규정 준수 정보.
zone_pivot_groups: app-info-data-mcas
ms.openlocfilehash: 265fa798414c907f25690252e1714bebfdbdde1b
ms.sourcegitcommit: a44420a99a1a3a9d0e49f4be66f266e2d4ca7bbb
ms.translationtype: MT
ms.contentlocale: ko-KR
ms.lasthandoff: 05/19/2021
ms.locfileid: "52551108"
---
# <a name="tryane-analytics"></a>Tryane Analytics

<p></p>
<img alt="Publisher Attestation: The information on this page is based on a self-assessment report provided by the app developer on the security, compliance, and data handling practices followed by this app. Microsoft makes no guarantees regarding the accuracy of the information." src="../media/attested.png" width="650" />
<p>최종 업데이트: 2020년 9월 28일</p>

* <a href="https://teams.microsoft.com/l/app/87631b95-fcd9-46e9-8d86-3d5205c04fec" target="_blank">Teams 스토어에서 보기</a>
* <a href="https://appsource.microsoft.com/product/office/WA200001827" target="_blank">앱소스에서 보기</a>

::: zone pivot="general"

### <a name="general-information"></a>일반 정보

트리안이 마이크로소프트에 제공한 정보:

| **정보** | **응답** |
|:----------------|:-------------|
| 앱 이름 | Tryane Analytics |
| ID | WA200001827 |
| 지원되는 Office 365 클라이언트 | Microsoft Teams |
| 파트너 회사 이름 | Tryane |
| 파트너 웹사이트의 URL | [https://tryane.com/en/produit/tat/](https://tryane.com/en/produit/tat/) |
| 개인정보 처리방침의 URL | [https://tryane.com/tryane-analytics/privacy_policy.html](https://tryane.com/tryane-analytics/privacy_policy.html) |
| 이용 약관의 URL | [https://tryane.com/tryane-analytics/terms_of_use.html](https://tryane.com/tryane-analytics/terms_of_use.html) |

 [!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="data"

### <a name="how-the-app-handles-data"></a>앱이 데이터를 처리하는 방법

이 정보는 이 앱이 조직 데이터를 수집하고 저장하는 방법과 조직에서 앱이 수집하는 데이터에 대한 제어에 대해 Tryane에서 제공했습니다.

#### <a name="data-access-using-microsoft-graph"></a>Microsoft Graph 을 사용하여 데이터 액세스

이 [앱에서 필요한 Microsoft Graph 권한을 나열합니다.](https://docs.microsoft.com/graph/permissions-reference)

>| **사용 권한**  | **권한 유형(위임/응용 프로그램)** | **데이터가 수집되고 있습니까? 그것을 수집하기위한 정당화?** | **데이터가 저장되어 있습니까? 그것을 저장하는 정당화?** | **Azure AD 앱 ID** |
>|:----------------|:--------------------|:---------------------------------------------------|:--------------------------|:--------------------------|
>| 액티비티피드.읽기 | 신청 |  | 팀의 모든 사용자 활동 읽기 | 9b03f15d-1219-4b2f-9699-640be54e1319 |
>| 채널.읽기기본.모든 것 | 신청 |  | 이름, 설명이 있는 모든 채널 목록 | 9b03f15d-1219-4b2f-9699-640be54e1319 |
>| 채널 메시지.읽기.모든 | 신청 |  | 메타데이터에&#8217; 모든 채널 메시지 목록 | 9b03f15d-1219-4b2f-9699-640be54e1319 |
>| Directory.Read.All | 신청 |  | 테넌트에서 팀 라이선스를 가진 사용자 식별 | 9b03f15d-1219-4b2f-9699-640be54e1319 |
>| 회원.읽기.숨겨진 | 신청 |  | 모든 팀, 팀&#8217;멤버 및 숨겨진 멤버십 목록 받기 | 9b03f15d-1219-4b2f-9699-640be54e1319 |
>| 보고서.읽기.모든 것 | 신청 |  | 팀의 모든 사용자 활동 읽기 | 9b03f15d-1219-4b2f-9699-640be54e1319 |
>| 팀.읽기 기본.모든 | 신청 |  | 모든 채널 및 팀 속성 목록 | 9b03f15d-1219-4b2f-9699-640be54e1319 |
>| User.Read | 위임 | 사용자 ID, 이름, 이메일 주소, 생성 날짜. 우리는 Teams 사용 분석을 제공하기 위해이 데이터를 저장 | 구독 중 현재 사용자 식별 | 9b03f15d-1219-4b2f-9699-640be54e1319 |


#### <a name="non-microsoft-services-used"></a>사용되지 Microsoft 서비스

앱이 Microsoft 가 아닌 서비스와 조직 데이터를 전송하거나 공유하는 경우 앱에서 사용하는 비Microsoft 서비스, 전송되는 데이터를 나열하고 앱이 이 정보를 전송해야 하는 이유에 대한 명분을 포함합니다.

>비Microsoft 서비스 사용되지 않습니다.

#### <a name="data-access-via-bots"></a>봇을 통한 데이터 액세스

이 앱에 봇 또는 메시징 확장 프로그램이 포함된 경우 최종 사용자 식별 정보(EUII): 팀의 모든 팀 구성원의 명단(이름, 성, 표시 이름, 이메일 주소)에 액세스하거나 추가된 채팅을 할 수 있습니다. 이 응용 프로그램은이 기능을 사용합니까?

>EUII에 액세스할 수 없습니다.


#### <a name="telemetry-data"></a>원격 분석 데이터

조직 식별 정보(OII) 또는 최종 사용자 식별 정보(EUII)가 이 응용 프로그램의 원격 분석 또는 로그에 표시됩니까? 그렇다면 저장되는 데이터와 보존 및 제거 정책은 무엇입니까?

>IT 보안 정책 및 코딩 표준에 설명된 조직 규칙은 EUII 및 OII가 로그에 나타나지 않도록 합니다.

#### <a name="organizational-controls-for-data-stored-by-partner"></a>파트너가 저장한 데이터에 대한 조직 제어

조직의 관리자가 파트너 시스템에서 자신의 정보를 제어하는 방법을 설명해 보세요. 예를 들어 삭제, 보존, 감사, 보관, 최종 사용자 정책 등

>위치/방법: PostgreSQL 서버용 Azure/Azure 데이터베이스 Who 액세스할 수 있습니다: 응용 프로그램 및 데이터베이스 관리자 권한 부여 제어: 
 - 개별 권한 부여 제어: RBAC
 - 시스템 권한 부여 제어: azure 가상 네트워크의 개인 끝점

#### <a name="human-review-of-organizational-information"></a>조직 정보의 인간 검토

이 앱에서 수집하거나 저장되는 조직 식별 정보(OII) 데이터를 검토하거나 분석하는 데 관여하는 사람이 있습니까?

>아니요

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="mcas"

[Microsoft Cloud App Security](https://www.microsoft.com/enterprise-mobility-security/cloud-app-security) 카탈로그의 정보는 아래에 나타납니다.

<iframe height='1020' title='Microsoft Cloud App Security 정보' src='https://appmcasinfoprod.azurewebsites.net/#/dashboard/36057' frameborder='no' style='width: 100%;'></iframe>

<a href="https://appmcasinfoprod.azurewebsites.net/#/dashboard/36057" target="_blank">새 탭에서 보기</a>

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

