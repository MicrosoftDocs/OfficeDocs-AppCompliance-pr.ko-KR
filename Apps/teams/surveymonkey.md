---
title: SurveyMonkey의 SurveyMonkey에 대한 응용 프로그램 정보
ms.author: elmalova
author: elenamalova
ms.date: 12/16/2019
ms.topic: article
ms.service: attestation
certification_type: attested
description: SurveyMonkey에 사용할 수 있는 모든 보안 및 규정 준수 정보, 데이터 처리 정책, CSA STAR 레지스트리의 Microsoft Cloud App Security 앱 카탈로그 정보 및 보안/규정 준수 정보
zone_pivot_groups: app-info-data-mcas
ms.openlocfilehash: daf5de5437a08ca8b748157a5e136bbe7b114122
ms.sourcegitcommit: 65d4afba6f46d45315b2a90d2b21ce1737707e7b
ms.translationtype: MT
ms.contentlocale: ko-KR
ms.lasthandoff: 07/02/2021
ms.locfileid: "53280820"
---
# <a name="surveymonkey"></a>SurveyMonkey

<p></p>
<img alt="Publisher Attestation: The information on this page is based on a self-assessment report provided by the app developer on the security, compliance, and data handling practices followed by this app. Microsoft makes no guarantees regarding the accuracy of the information." src="../media/attested.png" width="650" />
<p>개발자가 마지막으로 업데이트한 날짜: 2019년 12월 16일</p>

* <a href="https://teams.microsoft.com/l/app/0fd925a0-357f-4d25-8456-b3022aaa41a9" target="_blank">저장소의 Teams 보기</a>
* <a href="https://appsource.microsoft.com/product/office/WA104381088" target="_blank">AppSource의 보기</a>

::: zone pivot="general"

### <a name="general-information"></a>일반 정보

SurveyMonkey에서 Microsoft에 제공하는 정보:

| **정보** | **응답** |
|:----------------|:-------------|
| 앱 이름 | SurveyMonkey |
| ID | WA104381088 |
| Office 365 클라이언트 지원 | Microsoft Teams |
| 파트너 회사 이름 | SurveyMonkey |
| 파트너 웹 사이트의 URL | [https://www.surveymonkey.com](https://www.surveymonkey.com) |
| 응용 프로그램 Teams 페이지의 URL입니다. | [https://help.surveymonkey.com/articles/en_US/kb/Microsoft-T...](https://help.surveymonkey.com/articles/en_US/kb/Microsoft-Teams-Integration) |
| 개인 정보 취급 방침의 URL | [https://www.surveymonkey.com/mp/legal/privacy-policy/](https://www.surveymonkey.com/mp/legal/privacy-policy/) |
| 사용 약관 URL | [https://www.surveymonkey.com/mp/legal/terms-of-use/](https://www.surveymonkey.com/mp/legal/terms-of-use/) |

 [!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="data"

### <a name="how-the-app-handles-data"></a>앱이 데이터를 처리하는 방법

이 정보는 SurveyMonkey에서 이 앱이 조직 데이터를 수집하고 저장하는 방법과 조직에서 수집하는 데이터를 통해 조직에서 제공하는 컨트롤에 대해 제공됩니다.

#### <a name="data-access-using-microsoft-graph"></a>Microsoft 365를 사용한 데이터 Graph

이 앱에 [Graph Microsoft 사용자 권한을](https://docs.microsoft.com/graph/permissions-reference) 나열합니다.

>| **사용 권한**  | **사용 권한 유형(위임/응용 프로그램)** | **데이터가 수집하나요? 수집의 사당성** | **데이터가 저장되어 있나요? 저장 사정이 있나요?** | **Azure AD 앱 ID** |
>|:----------------|:--------------------|:---------------------------------------------------|:--------------------------|:--------------------------|
>| Group.ReadWrite.All | 위임 | 아니요 | 설문 조사를 공유할 그룹/채널 목록을 제공 |  |


#### <a name="non-microsoft-services-used"></a>비영구 Microsoft 서비스

앱이 Microsoft가 아닌 서비스로 조직 데이터를 전송하거나 공유하는 경우 앱에서 사용하는 비 Microsoft 서비스, 전송되는 데이터를 나열하고 앱이 이 정보를 전송해야 하는 이유에 대한 사유를 포함합니다.

>| **모든 비 Microsoft 서비스 OII가 다음으로 전송됩니다.** |  **전송되는 OII는 무엇입니까?** | **OII 전송의 사당성** |
>|:-------------------|:--------------------------|:--------------------------|
>| 응답 및 설문 조사를 팀 사용자와 연결하기 위해 MS 사용자 ID만 SurveyMonkey에 저장됩니다. |  | 팀의 경우 만들기에서 Microsoft Teams javascript SDK를 사용하여 설문 조사 및 설문 조사 결과 작업 모듈 모달을 사용합니다. |

#### <a name="data-access-via-bots"></a>봇을 통한 데이터 액세스

이 앱에 봇 또는 메시징 확장이 포함되어 있는 경우 팀 구성원의 명단(이름, 성, 표시 이름, 전자 메일 주소)이나 팀 구성원이 추가된 채팅의 최종 사용자 식별 정보(EUII)에 액세스할 수 있습니다. 이 앱이 이 기능을 사용하나요?

>| **EUII 액세스의 사유는 무엇입니까?**  | **EUII가 데이터베이스에 저장되어 있나요?** | **EUII 저장의 사유는 무엇입니까?** |
>|:--------------------------------|:---------------------|:--------------------------|
>| v3/conversations/{id}/pagedmembers를 호출하여 앱이 팀에 추가되어 구성원 수를 구합니다. 이는 사용 현황을 내부적으로 추적하기 위한 것이고, 채팅 로스터의 크기만 살펴보고, 다른 정보는 무시됩니다. | 예, 채팅 크기가 저장됩니다(정수 하나). |  |


#### <a name="telemetry-data"></a>원격 분석 데이터

이 응용 프로그램의 원격 분석 또는 로그에 OII(조직 식별 정보) 또는 EUII(최종 사용자 식별 정보)가 나타나나요? 그렇다면 저장되는 데이터와 보존 및 제거 정책에 대해 설명하세요.

>EUII - 설문 조사가 응답을 받을 때마다 성공/실패 로그가 생성됩니다. 이 로그에는 user_id, survey_id, integration_id(데이터베이스에서 MS 팀 ID, MS 사용자 ID를 검색하는 데 사용할 수 있는) Teams 응답을 전송하려고 합니다.

#### <a name="organizational-controls-for-data-stored-by-partner"></a>파트너가 저장한 데이터에 대한 조직 제어

조직의 관리자가 파트너 시스템에서 정보를 제어하는 방법에 대해 설명하는 방법 삭제, 보존, 감사, 보관, 최종 사용자 정책 등

>기본 데이터 센터는 라스베이거스, NV에 있으며 보조 데이터 센터는 CA의 샌프라자이클라라에 있습니다. SurveyMonkey는 이러한 위치에서 모든 서버 및 인프라를 소유하고 운영합니다. 또한 캐나다에 있는 특정 SurveyMonkey 고객에 대해 캐나다 Enterprise 상주를 사용할 수 있습니다. 모든 데이터는 AES256에서 TDE를 사용하여 미사용으로 암호화되고 전송되는 데이터는 TLS 1.2를 사용하여 암호화됩니다.

SurveyMonkey는 중앙 사용자 인증을 사용하여 ID 및 액세스 관리를 유지 관리합니다. 이 시스템은 모든 회사 및 프로덕션 인프라, 시스템 및 서비스에 대한 모든 인증 및 권한 부여를 관리합니다. 엄격한 액세스 정책은 분기별 기준으로 유지 관리 및 검토됩니다. 리뷰에는 사용자 액세스 목록, 정책 그룹 및 제3자 액세스 검토가 포함됩니다. 프로덕션 환경(예: 권한 있는 계정을 얻기 위해)에 액세스하려면 관리자 승인을 획득하고, 필요한 여러 교육을 완료하고, 보안 팀의 승인을 얻어야 합니다. 이때 추가 VPN 계정이 프로비전되어 &#8216;일반&#8217; 계정과 &#8216;계정과&#8217; 있습니다.

회사에서 발급한 디바이스만 프로덕션 네트워크에 액세스할 수 있습니다. 기본 무선 암호화 키, 암호 및 SNMP 커뮤니티 문자열을 포함하여 설치 전에 모든 무선 공급업체 기본값이 변경됩니다. 원격으로 2FA 및 VPN을 설치해야 합니다. 회사 사무실에는 게스트 액세스를 위한 별도의 Wi-Fi 네트워크가 있습니다.

모든 서비스, 프로토콜 및 허용된 포트에는 안전하지 것으로 간주되는 프로토콜에 대해 구현된 보안 기능 사용을 포함하여 문서화된 업무 정당성 및 승인이 있어야 합니다. 라우터 및 방화벽은 권한이 없는 사용자나 의도하지 않은 사용자로 IP 공개를 제한하고 DMZ 방화벽 내의 IP 주소에 대한 인바운드 인터넷 액세스를 제한하도록 구성됩니다. 라우터 규칙은 최소 6개월마다 검토됩니다.

#### <a name="human-review-of-organizational-information"></a>조직 정보의 인적 검토

사람이 이 앱에서 수집하거나 저장하는 OII(조직 식별 정보) 데이터를 검토하거나 분석하는 데 관여하나요?

>예

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="mcas"

Microsoft Cloud App Security [카탈로그의](https://www.microsoft.com/enterprise-mobility-security/cloud-app-security) 정보가 아래에 표시됩니다.

<iframe height='1020' title='Microsoft Cloud App Security 정보' src='https://appmcasinfoprod.azurewebsites.net/#/dashboard/12024' frameborder='no' style='width: 100%;'></iframe>

<a href="https://appmcasinfoprod.azurewebsites.net/#/dashboard/12024" target="_blank">새 탭에서 보기</a>

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

