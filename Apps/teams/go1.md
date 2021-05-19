---
title: Go1에 의해 Go1에 대한 응용 프로그램 정보
ms.author: elmalova
author: elenamalova
ms.date: 06/03/2020
ms.topic: article
ms.service: attestation
certification_type: attested
description: Go1에 대한 사용 가능한 모든 보안 및 규정 준수 정보 정보, 데이터 처리 정책, Microsoft Cloud App Security 앱 카탈로그 정보 및 CSA STAR 레지스트리의 보안/규정 준수 정보.
zone_pivot_groups: app-info-data-mcas
ms.openlocfilehash: f812e25e3e5b894d7b54da886637513cb677702a
ms.sourcegitcommit: a44420a99a1a3a9d0e49f4be66f266e2d4ca7bbb
ms.translationtype: MT
ms.contentlocale: ko-KR
ms.lasthandoff: 05/19/2021
ms.locfileid: "52553119"
---
# <a name="go1"></a>Go1

<p></p>
<img alt="Publisher Attestation: The information on this page is based on a self-assessment report provided by the app developer on the security, compliance, and data handling practices followed by this app. Microsoft makes no guarantees regarding the accuracy of the information." src="../media/attested.png" width="650" />
<p>최종 업데이트: 2020년 6월 3일</p>

* <a href="https://teams.microsoft.com/l/app/c859de61-8a6b-42e6-ba88-f639df33bc72" target="_blank">Teams 스토어에서 보기</a>
* <a href="https://appsource.microsoft.com/product/office/WA200001484" target="_blank">앱소스에서 보기</a>

::: zone pivot="general"

### <a name="general-information"></a>일반 정보

Go1에서 Microsoft에 제공하는 정보:

| **정보** | **응답** |
|:----------------|:-------------|
| 앱 이름 | Go1 |
| ID | WA200001484 |
| 지원되는 Office 365 클라이언트 | Microsoft Teams |
| 파트너 회사 이름 | Go1 |
| 파트너 웹사이트의 URL | [https://www.go1.com/](https://www.go1.com/) |
| 개인정보 처리방침의 URL | [https://www.go1.com/en-au/terms/privacy-policy](https://www.go1.com/en-au/terms/privacy-policy) |
| 이용 약관의 URL | [https://www.go1.com/en-au/terms/user-terms](https://www.go1.com/en-au/terms/user-terms) |

 [!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="data"

### <a name="how-the-app-handles-data"></a>앱이 데이터를 처리하는 방법

이 정보는 Go1에서 이 앱이 조직 데이터를 수집하고 저장하는 방법과 앱이 수집하는 데이터에 대한 조직이 가질 수 있는 제어에 대해 제공했습니다.

#### <a name="data-access-using-microsoft-graph"></a>Microsoft Graph 을 사용하여 데이터 액세스

이 [앱에서 필요한 Microsoft Graph 권한을 나열합니다.](https://docs.microsoft.com/graph/permissions-reference)

>| **사용 권한**  | **권한 유형(위임/응용 프로그램)** | **데이터가 수집되고 있습니까? 그것을 수집하기위한 정당화?** | **데이터가 저장되어 있습니까? 그것을 저장하는 정당화?** | **Azure AD 앱 ID** |
>|:----------------|:--------------------|:---------------------------------------------------|:--------------------------|:--------------------------|
>| Files.ReadWrite.All | 신청 | 앱은 파일 데이터를 저장하지 않습니다. | 사용자가 원드라이브에서 파일을 업로드하고 공유할 수 있습니다. | c859de61-8a6b-42e6-ba88-f639df3bc72 |
>| Group.ReadWrite.All | 신청 | Teams 및 채널 이름과 고유 ID의 학습 환경을 관리하는 응용 프로그램을 지원하기 위해 저장 | 앱이 Teams 및 채널을 동적으로 설정하여 Teams 환경에서 구조화 된 학습을 지원할 수 있습니다. | c859de61-8a6b-42e6-ba88-f639df3bc72 |
>| User.Read.All | 신청 | 사용자 이름 및 이메일 및 UPN은 직접 개인 학습자 경험을 제공하기 위해 저장 | 팀 구성원 간의 학습 리소스 공유에 서명하고 지원할 수 있습니다. | c859de61-8a6b-42e6-ba88-f639df3bc72 |


#### <a name="non-microsoft-services-used"></a>사용되지 Microsoft 서비스

앱이 Microsoft 가 아닌 서비스와 조직 데이터를 전송하거나 공유하는 경우 앱에서 사용하는 비Microsoft 서비스, 전송되는 데이터를 나열하고 앱이 이 정보를 전송해야 하는 이유에 대한 명분을 포함합니다.

>| **모든 Microsoft 서비스 OII가** |  **어떤 OII가 전송됩니까?** | **OII 전송에 대한 정당화?** |
>|:-------------------|:--------------------------|:--------------------------|
>| 코스 콘텐츠를 플레이할 때 사용자의 성 및 성은 GO1의 콘텐츠 제공업체와 공유할 수 있습니다. 이는 콘텐츠 공급자가 개인화된 학습 환경을 공급자에게 요구하는 경우에만 공유됩니다. |  | 해당 없음 |

#### <a name="data-access-via-bots"></a>봇을 통한 데이터 액세스

이 앱에 봇 또는 메시징 확장 프로그램이 포함된 경우 최종 사용자 식별 정보(EUII): 팀의 모든 팀 구성원의 명단(이름, 성, 표시 이름, 이메일 주소)에 액세스하거나 추가된 채팅을 할 수 있습니다. 이 응용 프로그램은이 기능을 사용합니까?

>EUII에 액세스할 수 없습니다.


#### <a name="telemetry-data"></a>원격 분석 데이터

조직 식별 정보(OII) 또는 최종 사용자 식별 정보(EUII)가 이 응용 프로그램의 원격 분석 또는 로그에 표시됩니까? 그렇다면 저장되는 데이터와 보존 및 제거 정책은 무엇입니까?

>GO1은 개인 또는 조직 식별 가능한 정보의 저장을 최소화합니다. 이 데이터를 저장하는 세부 정보 응용 프로그램 로그는 생성 후 90일 이내에 삭제됩니다.

#### <a name="organizational-controls-for-data-stored-by-partner"></a>파트너가 저장한 데이터에 대한 조직 제어

조직의 관리자가 파트너 시스템에서 자신의 정보를 제어하는 방법을 설명해 보세요. 예를 들어 삭제, 보존, 감사, 보관, 최종 사용자 정책 등

>모든 직원 시스템에 2FA가 필요합니다. GO1 시스템 액세스는 역할에 의해 관리됩니다. 작업을 수행하기 위해 액세스해야 하는 역할만 프로덕션 시스템에 액세스할 수 있습니다. 내부 정책에 따라 데이터는 항상 전송 및 사용 중에 암호화해야 합니다.

#### <a name="human-review-of-organizational-information"></a>조직 정보의 인간 검토

이 앱에서 수집하거나 저장되는 조직 식별 정보(OII) 데이터를 검토하거나 분석하는 데 관여하는 사람이 있습니까?

>예

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="mcas"

[Microsoft Cloud App Security](https://www.microsoft.com/enterprise-mobility-security/cloud-app-security) 카탈로그의 정보는 아래에 나타납니다.

<iframe height='1020' title='Microsoft Cloud App Security 정보' src='https://appmcasinfoprod.azurewebsites.net/#/dashboard/16262' frameborder='no' style='width: 100%;'></iframe>

<a href="https://appmcasinfoprod.azurewebsites.net/#/dashboard/16262" target="_blank">새 탭에서 보기</a>

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

