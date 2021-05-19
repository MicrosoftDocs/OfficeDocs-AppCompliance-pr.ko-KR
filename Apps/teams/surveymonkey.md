---
title: SurveyMonkey에 의해 SurveyMonkey에 대한 응용 프로그램 정보
ms.author: elmalova
author: elenamalova
ms.date: 12/16/2019
ms.topic: article
ms.service: attestation
certification_type: attested
description: SurveyMonkey에 대한 사용 가능한 모든 보안 및 규정 준수 정보 정보, 데이터 처리 정책, Microsoft Cloud App Security 앱 카탈로그 정보 및 CSA STAR 레지스트리의 보안/규정 준수 정보.
zone_pivot_groups: app-info-data-mcas
ms.openlocfilehash: 57ba8ed84e0d9ea4101ea82ed5d92aef1f634ed1
ms.sourcegitcommit: a44420a99a1a3a9d0e49f4be66f266e2d4ca7bbb
ms.translationtype: MT
ms.contentlocale: ko-KR
ms.lasthandoff: 05/19/2021
ms.locfileid: "52552729"
---
# <a name="surveymonkey"></a>SurveyMonkey

<p></p>
<img alt="Publisher Attestation: The information on this page is based on a self-assessment report provided by the app developer on the security, compliance, and data handling practices followed by this app. Microsoft makes no guarantees regarding the accuracy of the information." src="../media/attested.png" width="650" />
<p>최종 업데이트: 2019년 12월 16일</p>

* <a href="https://teams.microsoft.com/l/app/0fd925a0-357f-4d25-8456-b3022aaa41a9" target="_blank">Teams 스토어에서 보기</a>
* <a href="https://appsource.microsoft.com/product/office/WA104381088" target="_blank">앱소스에서 보기</a>

::: zone pivot="general"

### <a name="general-information"></a>일반 정보

SurveyMonkey에서 마이크로소프트에 제공하는 정보:

| **정보** | **응답** |
|:----------------|:-------------|
| 앱 이름 | SurveyMonkey |
| ID | WA104381088 |
| 지원되는 Office 365 클라이언트 | Microsoft Teams |
| 파트너 회사 이름 | SurveyMonkey |
| 파트너 웹사이트의 URL | [https://www.surveymonkey.com](https://www.surveymonkey.com) |
| Teams 응용 프로그램 정보 페이지의 URL | [https://help.surveymonkey.com/articles/en_US/kb/Microsoft-T...](https://help.surveymonkey.com/articles/en_US/kb/Microsoft-Teams-Integration) |
| 개인정보 처리방침의 URL | [https://www.surveymonkey.com/privacy](https://www.surveymonkey.com/privacy) |
| 이용 약관의 URL | [https://www.surveymonkey.com/mp/policy/terms-of-use/](https://www.surveymonkey.com/mp/policy/terms-of-use/) |

 [!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="data"

### <a name="how-the-app-handles-data"></a>앱이 데이터를 처리하는 방법

이 정보는 SurveyMonkey에서 이 앱이 조직 데이터를 수집하고 저장하는 방법과 앱이 수집하는 데이터에 대한 조직이 가질 수 있는 제어에 대해 제공했습니다.

#### <a name="data-access-using-microsoft-graph"></a>Microsoft Graph 을 사용하여 데이터 액세스

이 [앱에서 필요한 Microsoft Graph 권한을 나열합니다.](https://docs.microsoft.com/graph/permissions-reference)

>| **사용 권한**  | **권한 유형(위임/응용 프로그램)** | **데이터가 수집되고 있습니까? 그것을 수집하기위한 정당화?** | **데이터가 저장되어 있습니까? 그것을 저장하는 정당화?** | **Azure AD 앱 ID** |
>|:----------------|:--------------------|:---------------------------------------------------|:--------------------------|:--------------------------|
>| Group.ReadWrite.All | 위임 | 아니요 | 설문조사를 공유할 그룹/채널 목록을 제공하려면 |  |


#### <a name="non-microsoft-services-used"></a>사용되지 Microsoft 서비스

앱이 Microsoft 가 아닌 서비스와 조직 데이터를 전송하거나 공유하는 경우 앱에서 사용하는 비Microsoft 서비스, 전송되는 데이터를 나열하고 앱이 이 정보를 전송해야 하는 이유에 대한 명분을 포함합니다.

>| **모든 Microsoft 서비스 OII가** |  **어떤 OII가 전송됩니까?** | **OII 전송에 대한 정당화?** |
>|:-------------------|:--------------------------|:--------------------------|
>| MS 사용자 ID만 SurveyMonkey에 저장되어 응답 및 설문조사를 팀 사용자와 연결합니다. |  | Microsoft Teams 자바스크립트 SDK를 사용하여 작성, 설문조사 및 설문조사 결과 작업 모듈 모달을 사용합니다. |

#### <a name="data-access-via-bots"></a>봇을 통한 데이터 액세스

이 앱에 봇 또는 메시징 확장 프로그램이 포함된 경우 최종 사용자 식별 정보(EUII): 팀의 모든 팀 구성원의 명단(이름, 성, 표시 이름, 이메일 주소)에 액세스하거나 추가된 채팅을 할 수 있습니다. 이 응용 프로그램은이 기능을 사용합니까?

>| **EUII에 액세스할 수 있는 정당성?**  | **EUII는 데이터베이스에 저장되어 있습니까?** | **EUII를 저장하는 정당화?** |
>|:--------------------------------|:---------------------|:--------------------------|
>| v3/대화/{id}/pagedmember에 전화를 걸어 앱이 팀에 추가되어 있는지 확인하고 멤버 수를 가져옵니다. 그것은 사용의 내부 추적을위한 것입니다, 우리는 단지 채팅 명단의 크기를 보고, 다른 정보는 무시됩니다. | 예, 채팅의 크기가 저장됩니다(단일 정수) |  |


#### <a name="telemetry-data"></a>원격 분석 데이터

조직 식별 정보(OII) 또는 최종 사용자 식별 정보(EUII)가 이 응용 프로그램의 원격 분석 또는 로그에 표시됩니까? 그렇다면 저장되는 데이터와 보존 및 제거 정책은 무엇입니까?

>EUII - 설문조사에 응답할 때마다 성공/실패 로그가 생성되며 커넥터를 통해 Teams 응답을 보내려고 하면 이 로그는 user_id, survey_id, integration_id(데이터베이스에서 MS 팀 ID, MS 사용자 ID를 조회하는 데 사용할 수 있음)가 포함됩니다.

#### <a name="organizational-controls-for-data-stored-by-partner"></a>파트너가 저장한 데이터에 대한 조직 제어

조직의 관리자가 파트너 시스템에서 자신의 정보를 제어하는 방법을 설명해 보세요. 예를 들어 삭제, 보존, 감사, 보관, 최종 사용자 정책 등

>주요 데이터 센터는 라스베이거스, NV에 위치하고 있으며 보조 데이터 센터는 캘리포니아 주 산타클라라에 있습니다. SurveyMonkey는 이러한 위치에서 모든 서버와 인프라를 소유하고 운영합니다. 또한 캐나다에 위치한 특정 SurveyMonkey Enterprise 고객에게 캐나다 데이터 레지던시를 사용할 수 있습니다. 모든 데이터는 AES256을 사용하여 TDE를 사용하여 사용 중지된 암호화되며 전송 중 의 데이터는 TLS 1.2를 사용하여 암호화됩니다.

SurveyMonkey는 중앙 사용자 인증을 사용하여 ID 및 액세스 관리를 유지합니다. 이 시스템은 모든 기업 및 생산 인프라, 시스템 및 서비스에 대한 모든 인증 및 승인을 관리합니다. 엄격한 액세스 정책은 분기별로 유지 관리 되고 검토됩니다. 리뷰에는 사용자 액세스 목록, 정책 그룹 및 제3자 액세스 리뷰가 포함되나 이에 국한되지 않습니다. 프로덕션 환경(예: 권한 있는 계정을 얻기 위해)에 액세스하려면 관리자 승인을 받고 필요한 교육을 수번 완료하고 보안 팀의 승인을 받아야 합니다. 이 때 추가 VPN 계정이 프로비저닝되어 &#8216;일반&#8217; 계정을 &#8216;권한 있는&#8217; 계정과 차별화합니다.

회사에서 발급한 장치만 프로덕션 네트워크에 액세스할 수 있습니다. 모든 무선 공급업체 기본값은 설치 전에 기본 무선 암호화 키, 암호 및 SNMP 커뮤니티 문자열을 포함하되 이에 국한되지 않고 변경됩니다. 2FA 및 VPN은 원격으로 그렇게해야 합니다. 우리는 우리의 회사 사무실에서 손님 액세스를위한 별도의 무선 랜 네트워크를 가지고있다.

모든 서비스, 프로토콜 및 허용된 포트에는 안전하지 않은 것으로 간주되는 프로토콜에 대해 구현된 보안 기능 의 사용을 포함하여 문서화된 비즈니스 명분 및 승인이 있어야 합니다. 라우터와 방화벽은 IP 공개를 무단 또는 의도하지 않은 당사자로 제한하고 DMZ 방화벽 내의 IP 주소에 대한 인바운드 인터넷 액세스를 제한하도록 구성되며 라우터 규칙 집합은 적어도 6개월마다 검토됩니다.

#### <a name="human-review-of-organizational-information"></a>조직 정보의 인간 검토

이 앱에서 수집하거나 저장되는 조직 식별 정보(OII) 데이터를 검토하거나 분석하는 데 관여하는 사람이 있습니까?

>예

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="mcas"

[Microsoft Cloud App Security](https://www.microsoft.com/enterprise-mobility-security/cloud-app-security) 카탈로그의 정보는 아래에 나타납니다.

<iframe height='1020' title='Microsoft Cloud App Security 정보' src='https://appmcasinfoprod.azurewebsites.net/#/dashboard/12024' frameborder='no' style='width: 100%;'></iframe>

<a href="https://appmcasinfoprod.azurewebsites.net/#/dashboard/12024" target="_blank">새 탭에서 보기</a>

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

