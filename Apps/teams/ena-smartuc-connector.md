---
title: ENA의 ENA SmartUC 커넥터에 대한 응용 프로그램 정보
ms.author: elmalova
author: elenamalova
manager: tonybal
ms.date: 03/11/2022
ms.topic: article
ms.service: attestation
certification_type: attested
description: ENA SmartUC Connector에 사용할 수 있는 모든 보안 및 규정 준수 정보, 데이터 처리 정책, CSA STAR 레지스트리의 Microsoft Cloud App Security 앱 카탈로그 정보 및 보안/규정 준수 정보
zone_pivot_groups: app-info-data-security-compliance-privsection-zerotrust
ms.openlocfilehash: 4f3825a2a210998277fcf00634fc8e78679ff6a5
ms.sourcegitcommit: 58c50d1704196178455927329748485b40dd7880
ms.translationtype: MT
ms.contentlocale: ko-KR
ms.lasthandoff: 03/17/2022
ms.locfileid: "63548886"
---
# <a name="ena-smartuc-connector"></a>ENA SmartUC Connector

<p></p>
<img alt="Publisher Attestation: The information on this page is based on a self-assessment report provided by the app developer on the security, compliance, and data handling practices followed by this app. Microsoft makes no guarantees regarding the accuracy of the information." src="../media/attested.png" width="650" />
<p>개발자가 마지막으로 업데이트한 날짜: 2022년 3월 11일</p>

* <a href="https://teams.microsoft.com/l/app/029cfd5a-4413-499d-bda6-a2a0a3f5e70e" target="_blank">저장소의 Teams 보기</a>
* <a href="https://appsource.microsoft.com/product/office/WA200003354" target="_blank">AppSource의 보기</a>

::: zone pivot="general"

### <a name="general-information"></a>일반 정보

ENA가 Microsoft에 제공하는 정보:

| **정보** | **응답** |
|:----------------|:-------------|
| 앱 이름 | ENA SmartUC Connector |
| ID | WA200003354 |
| Office 365 클라이언트 지원 | Microsoft Teams |
| 파트너 회사 이름 | ENA |
| 회사의 웹 사이트 | [https://www.ena.com](https://www.ena.com) |
| 앱 사용 약관 | [https://www.ena.com/legal/aup/](https://www.ena.com/legal/aup/) |
| 앱의 핵심 기능 | 앱은 ENA SmartUC 제품 집합을 Teams App에 연결하여 최종 사용자가 ENA SmartUC 지원 전화 통화를 Teams. |
| 회사 본사 위치 | 미국 |
| 앱 정보 페이지 | |
| 앱을 실행하기 위해 사용되는 호스팅 환경 또는 서비스 모델은 무엇입니까? | 하이브리드 |
| 앱에서 어떤 호스팅 클라우드 공급자를 사용하나요? | 다른, 메타스위치에서 운영하는 서비스의 부분은 Azure에서 호스트됩니다. 또한 자체 인프라(예: EAS 서버)를 호스팅하는 방법에 대한 세부 정보도 포함해야 합니다. |

 [!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="data"

### <a name="how-the-app-handles-data"></a>앱이 데이터를 처리하는 방법

이 정보는 ENA에서 이 앱이 조직 데이터를 수집 및 저장하는 방법 및 앱이 수집하는 데이터를 통해 조직이 제어할 수 있는 방법에 대해 제공했습니다.

| **정보** | **응답** |
|:----------------|:-------------|
| 앱 또는 기반 인프라가 Microsoft 고객 또는 장치와 관련된 데이터를 처리하나요? | 예 |
| 앱에서 처리되는 데이터는 무엇입니까? | Microsoft.Ingestion.Attestation.DocsPublishingCommon.AppInfos.DataProcess |
| 앱에서 TLS 1.1 이상을 지원하나요? | 예 |
| 앱 또는 기반 인프라에 Microsoft 고객 데이터가 저장하나요? | 아니요 |

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="security"

Microsoft Cloud App Security [카탈로그의](https://www.microsoft.com/enterprise-mobility-security/cloud-app-security) 정보가 아래에 표시됩니다.

| **정보** | **응답** |
|:----------------|:-------------|
| 앱에서 연간 침투 테스트를 수행하나요? | 아니요 |
| 앱에 백업 및 복원 전략을 포함하여 문서화된 재해 복구 계획이 있나요? | 아니요 |
| 환경에서 기존의 맬웨어 방지 보호 또는 응용 프로그램 제어를 사용하나요? | TraditionalAntiMalware |
| 보안 취약점을 식별하고 위험 순위를 정한 프로세스가 있습니까? | 예 |
| 패치 적용을 위한 SLA(서비스 수준 계약)를 관리하는 정책이 있나요? | 예 |
| 패치 정책 SLA에 따라 패치 관리 활동을 수행하나요? | 예 |
| 지원되지 않는 운영 체제 또는 소프트웨어가 있나요? | 아니요 |
| 앱 및 이를 지원하는 구조에서 분기별 취약점 검색을 수행하나요? | 예 |
| 외부 네트워크 경계에 방화벽이 설치되어 있습니까? | 예 |
| 변경 요청을 프로덕션에 배포하기 전에 검토하고 승인하는 데 사용되는 변경 관리 프로세스가 설정 있습니까? | 예 |
| 원래 개발자가 프로덕션에 제출한 모든 코드 변경 요청을 검토하고 추가 인가? | 예 |
| 보안 코딩 방법은 OWASP 상위 10과 같은 일반적인 취약성 클래스를 고려하나요? | 아니요 |
| MFA(다단계 인증)를 사용할 수 있습니다. | CodeRepositories, DNSManagement |
| 직원 계정을 프로비저닝, 수정 및 지우기 위한 프로세스를 설정하고 있나요? | 예 |
| 앱을 지원하는 네트워크 경계에 배포된 IDPS(침입 감지 및 방지) 소프트웨어가 있습니까? | 아니요 |
| 앱을 지원하는 모든 시스템 구성 요소에 이벤트 로깅이 설정되어 있나요? | 예 |
| 잠재적인 보안 이벤트를 감지하기 위해 수동 또는 자동화된 도구에서 정기적으로 모든 로그를 검토하나요? | 아니요|
| 보안 이벤트가 감지되면 직원에게 경고가 자동으로 발송되어 Triage가 발생하나요? | 아니요 |
| 공식적인 정보 보안 위험 관리 프로세스를 설정하고 있습니까? | 예 |
| 공식적인 보안 인시던트 대응 프로세스를 문서화하고 설정하고 있습니까? |  |
| 감지 후 72시간 이내에 해당 위반의 영향을 받는 감독 기관 및 개인에게 앱 또는 서비스 데이터 위반을 보고하나요?| |

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="compliance"

| **정보** | **응답** |
|:----------------|:-------------|
| 앱이 HIPAA(Health Insurance Portability and Accounting Act)를 준수하나요? | 아니요 |
| 앱이 HITRUST CSF(Common Security Framework)인 Health Information Trust Alliance를 준수하나요? | 아니요 |
| 앱이 SOC(서비스 조직 제어)를 준수하나요? | 아니요 |
| 가장 최근 SOC1 인증 날짜 |   |
| 앱이 SOC(서비스 조직 제어)를 준수하나요? | 아니요 |
| 어떤 SOC 2 인증을 획득했나요? | |
| 가장 최근 SOC2 인증 날짜 | |
| 앱이 SOC(서비스 조직 제어)를 준수하나요? | 아니요 |
| 가장 최근 SOC3 인증 날짜 | |
| 앱 및 해당 지원 환경에 대해 연간 PCI DSS 평가를 수행하나요? | 아니요 |
| 앱이 국제 표준화 기구(ISO 27001) 인증을 받나요? | 아니요 |
| 앱이 국제 표준화 기구(ISO 27018)를 준수하나요? | 아니요 |
| 앱이 국제 표준화 기구(ISO 27017)를 준수하나요? | 아니요 |
| 앱이 국제 표준화 기구(ISO 27002)를 준수하나요? | 아니요 |
| 앱이 FedRAMP(Federal Risk and Authorization Management Program)를 준수하나요? | 아니요 |
| 앱이 FERPA(가족 교육권 및 개인 정보 보호법)를 준수하나요? | 해당 없음 |
| 앱이 COPPA(온라인 개인 정보 보호법)를 준수하나요? | 해당 없음 |
| 앱이 SOX(Sarbanes-Oxley Act)를 준수하나요? | 아니요 |
| 앱이 NIST 800-171을 준수하나요? | 아니요 |
| 앱이 CSA Star(Cloud Security Alliance) 인증을 받은가요? | 아니요 |

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="privsection"

| **정보** | **응답** |
|:----------------|:-------------|
| GDPR 또는 기타 개인 정보 보호 또는 데이터 보호 요구 사항 또는 의무(예: CCPA)가 있습니까? | 아니요 |
| 앱에 고객 데이터를 수집, 사용, 공유 및 저장하는 방법을 설명하는 외부 연결 개인 정보 취급 방침이 있나요? | 아니요 |
| 앱이 법적 영향이나 유사한 영향을 미칠 수 있는 프로파일링을 포함하여 자동화된 의사 결정을 수행하나요? | 아니요 |
| 앱이 개인 정보 취급 방침(즉, 마케팅, 분석)에 설명되지 않은 보조 목적으로 고객 데이터를 처리하나요? | 아니요 |
| 특정 범주의 중요한 데이터(예: 인종 또는 민족, 정치적 의견, 종교적 또는 철학적 신념, 유전적 또는 생체 인식 데이터, 건강 데이터) 또는 위반 알림 법률이 적용된 데이터 범주를 처리하나요? | 아니요 |
| 앱이 미성년자(예: 16세 미만의 개인)로부터 데이터를 수집하거나 처리하나요? | 아니요 |
| 앱에 요청 시 개인의 개인 데이터를 삭제할 수 있는 기능이 있나요? |  |
| 앱에 요청 시 개인의 개인 데이터 처리를 제한하거나 제한할 수 있는 기능이 있나요? |  |
| 앱이 개인 데이터를 수정하거나 업데이트할 수 있는 기능을 개인에게 제공하나요? |  |
| 앱의 개인 데이터 처리와 관련된 위험을 식별하기 위해 정기적인 데이터 보안 및 개인 정보 보호 검토(예: 데이터 보호 영향 평가 또는 개인 정보 보호 위험 평가)가 수행하나요? |  |

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="zerotrust"

| **정보** | **응답** |
|:----------------|:-------------|
| Single Sign-On, API 액세스 등을 위해 응용 프로그램이 Microsoft Id 플랫폼(Azure AD)과 통합하나요? | 예 |
| 통합 검사 목록에 설명된 적용 가능한 모든 모범 사례를 Microsoft ID 플랫폼 준수하나요? | 아니요 |
| 앱에서 최신 버전의 MSAL(Microsoft 인증 라이브러리) 또는 Microsoft Identity Web을 인증에 사용하나요? | 예 |
| 앱에서 위의 라이브러리 중 하나를 사용하지 않는 경우 어떤 인증 라이브러리 또는 라이브러리를 사용하나요? |  |
| 앱에서 조건부 액세스 정책을 지원하나요? | 아니요 |
| 앱에서 CAE(연속 액세스 평가)를 지원하지 않는지 확인 | 아니요 |
| 앱에서 코드에 자격 증명을 저장하나요? | 예 |
| 앱 및 추가 Microsoft 365 Microsoft 앱 외부에서 추가 Microsoft API를 사용할 Graph. 앱 또는 추가 기능에서 추가 Microsoft API를 사용하나요? | 예 |

#### <a name="data-access-using-microsoft-graph"></a>Microsoft 365를 사용하여 데이터 Graph

>|   **Graph 권한**  | **사용 권한 유형** |          **사리**          | **Azure AD 앱 ID** |
>|:------------------------|:--------------------|:------------------------------------|:--------------------|
>| ChannelMember.Read.All | 위임 | 사용자 ID 및 현재 채널/채팅의 구성원 이름을 표시합니다. 앱은 이를 사용하여 사용자에게 통화할 채널/채팅 구성원 목록을 제공합니다. | [029cfd5a-4413-499d-bda6-a2a0a3f5e70e](../azure/029cfd5a-4413-499d-bda6-a2a0a3f5e70e.md) |
>| Chat.ReadBasic | 위임 | 사용자 ID 및 현재 채팅 구성원의 이름을 표시합니다. 앱은 이를 사용하여 사용자에게 통화할 채팅 구성원 목록을 제공합니다. | [029cfd5a-4413-499d-bda6-a2a0a3f5e70e](../azure/029cfd5a-4413-499d-bda6-a2a0a3f5e70e.md) |
>| People.Read.All | 위임 | 사용자 ID 및 현재 팀 구성원의 이름을 표시합니다. 앱은 이를 사용하여 사용자에게 통화할 팀 구성원 목록을 제공합니다. | [029cfd5a-4413-499d-bda6-a2a0a3f5e70e](../azure/029cfd5a-4413-499d-bda6-a2a0a3f5e70e.md) |
>| User.Read.All | 위임 | 사용자의 업무 및 휴대폰 번호입니다. 이러한 번호로의 전화 통화를 시작할 수 있도록 이 작업을 시작해야 합니다. | [029cfd5a-4413-499d-bda6-a2a0a3f5e70e](../azure/029cfd5a-4413-499d-bda6-a2a0a3f5e70e.md) |
>| offline_access | 위임 | 사용자를 대신하여 나열된 다른 Graph API 끝점에 액세스하도록 앱에 권한을 부여하는 사용자에 대한 권한 부여 토큰입니다. Microsoft Identity 플랫폼 응용 프로그램이 작동하려면 이러한 액세스 권한이 필요합니다. | [029cfd5a-4413-499d-bda6-a2a0a3f5e70e](../azure/029cfd5a-4413-499d-bda6-a2a0a3f5e70e.md) |
>| openid | 위임 | 사용자를 대신하여 나열된 다른 Graph API 끝점에 액세스하도록 앱에 권한을 부여하는 사용자에 대한 권한 부여 토큰입니다. Microsoft Identity 플랫폼 응용 프로그램이 작동하려면 이러한 액세스 권한이 필요합니다. | [029cfd5a-4413-499d-bda6-a2a0a3f5e70e](../azure/029cfd5a-4413-499d-bda6-a2a0a3f5e70e.md) |
>| 프로필 | 위임 | 사용자를 대신하여 나열된 다른 Graph API 끝점에 액세스하도록 앱에 권한을 부여하는 사용자에 대한 권한 부여 토큰입니다. Microsoft Identity 플랫폼 응용 프로그램이 작동하려면 이러한 액세스 권한이 필요합니다. | [029cfd5a-4413-499d-bda6-a2a0a3f5e70e](../azure/029cfd5a-4413-499d-bda6-a2a0a3f5e70e.md) |

>이 응용 프로그램에는 추가 API가 없습니다.

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

