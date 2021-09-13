---
title: Senso by Senso의 응용 프로그램 정보
ms.author: elmalova
author: elenamalova
ms.date: 08/02/2021
ms.topic: article
ms.service: attestation
certification_type: attested
description: CSA STAR 레지스트리의 Senso에 사용할 수 있는 모든 보안 및 규정 준수 정보, 데이터 처리 정책, Microsoft Cloud App Security 앱 카탈로그 정보 및 보안/규정 준수 정보
zone_pivot_groups: app-info-data-mcas-identity
ms.openlocfilehash: a44620633f9eee6c5d5e18997a58158a16c5e801
ms.sourcegitcommit: d85595f6518d8d05f0aee75380f51659908b6bcb
ms.translationtype: MT
ms.contentlocale: ko-KR
ms.lasthandoff: 09/12/2021
ms.locfileid: "59286917"
---
# <a name="senso"></a>Senso

<p></p>
<img alt="Publisher Attestation: The information on this page is based on a self-assessment report provided by the app developer on the security, compliance, and data handling practices followed by this app. Microsoft makes no guarantees regarding the accuracy of the information." src="../media/attested.png" width="650" />
<p>개발자가 마지막으로 업데이트한 날짜: 2021년 8월 2일</p>

* <a href="https://teams.microsoft.com/l/app/3973b9d4-b50e-472d-8145-8967e01379b4" target="_blank">저장소의 Teams 보기</a>
* <a href="https://appsource.microsoft.com/product/office/WA200002571" target="_blank">AppSource의 보기</a>

::: zone pivot="general"

### <a name="general-information"></a>일반 정보

Senso에서 Microsoft에 제공한 정보:

| **정보** | **응답** |
|:----------------|:-------------|
| 앱 이름 | Senso |
| ID | WA200002571 |
| Office 365 클라이언트 지원 | Microsoft Teams |
| 파트너 회사 이름 | Senso |
| 파트너 웹 사이트의 URL | [https://www.senso.cloud](https://www.senso.cloud) |
| 응용 프로그램 Teams 페이지의 URL입니다. | [https://www.senso.cloud/safeguarding-microsoft-teams/](https://www.senso.cloud/safeguarding-microsoft-teams/) |
| 개인 정보 취급 방침의 URL | [https://www.senso.cloud/privacy](https://www.senso.cloud/privacy) |
| 사용 약관 URL | [https://www.senso.cloud/eula](https://www.senso.cloud/eula) |

 [!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="data"

### <a name="how-the-app-handles-data"></a>앱이 데이터를 처리하는 방법

이 정보는 Senso에서 이 앱이 조직 데이터를 수집하고 저장하는 방법 및 앱이 수집하는 데이터를 통해 조직이 사용할 컨트롤에 대해 제공됩니다.

#### <a name="data-access-using-microsoft-graph"></a>Microsoft 365를 사용한 데이터 Graph

이 앱에 [Graph Microsoft 사용자 권한을](https://docs.microsoft.com/graph/permissions-reference) 나열합니다.

>| **사용 권한**  | **사용 권한 유형(위임/ 응용 프로그램)** | **데이터가 수집하나요? 수집의 사당성** | **데이터가 저장되어 있나요? 저장 사정이 있나요?** | **Azure AD 앱 ID** |
>|:----------------|:------------------------------------------------|:--------------------------------------------------------|:--------------------------------------------------|:--------------------|
>| Channel.ReadBasic.All | application | 모든 채널에 대한 채널 이름 및 설명을 읽어 위반이 플래그가 지정된 위치를 식별합니다.   | 위반이 발생하면 위반에 대한 컨텍스트를 제공하기 위해 보낸 사람(보낸 사람), 받는 사람의 이름(받는 사람), 채널 이름, 날짜, 시간 및 메시지가 기록됩니다.  | [a9d28fcf-036e-4a85-9003-332303e3a29b](https://docs.microsoft.com/microsoft-365-app-certification/azure/a9d28fcf-036e-4a85-9003-332303e3a29b) |
>| ChannelMember.Read.All | application | 모든 채널의 구성원 목록 및 채팅 메시지를 읽습니다. | 위반이 발생하면 위반에 대한 컨텍스트를 제공하기 위해 보낸 사람(보낸 사람), 받는 사람의 이름(받는 사람), 채널 이름, 날짜, 시간 및 메시지가 기록됩니다.  | [a9d28fcf-036e-4a85-9003-332303e3a29b](https://docs.microsoft.com/microsoft-365-app-certification/azure/a9d28fcf-036e-4a85-9003-332303e3a29b) |
>| ChannelMessage.Read.All | application | 모든 채널 메시지 읽기 | 위반이 발생하면 위반에 대한 컨텍스트를 제공하기 위해 보낸 사람(보낸 사람), 받는 사람의 이름(받는 사람), 채널 이름, 날짜, 시간 및 메시지가 기록됩니다.  | [a9d28fcf-036e-4a85-9003-332303e3a29b](https://docs.microsoft.com/microsoft-365-app-certification/azure/a9d28fcf-036e-4a85-9003-332303e3a29b) |
>| Chat.Read.All | application | 모든 채팅 메시지 읽기 | 위반이 발생하면 위반에 대한 컨텍스트를 제공하기 위해 보낸 사람(보낸 사람), 받는 사람의 이름(받는 사람), 채널 이름, 날짜, 시간 및 메시지가 기록됩니다.  | [a9d28fcf-036e-4a85-9003-332303e3a29b](https://docs.microsoft.com/microsoft-365-app-certification/azure/a9d28fcf-036e-4a85-9003-332303e3a29b) |
>| Directory.Read.All | application | 디렉터리 데이터 읽기 | 위반이 발생하면 위반에 대한 컨텍스트를 제공하기 위해 보낸 사람(보낸 사람), 받는 사람의 이름(받는 사람), 채널 이름, 날짜, 시간 및 메시지가 기록됩니다.  | [a9d28fcf-036e-4a85-9003-332303e3a29b](https://docs.microsoft.com/microsoft-365-app-certification/azure/a9d28fcf-036e-4a85-9003-332303e3a29b) |
>| Files.Read.All | application | 모든 사이트 모음의 파일 읽기 | 위반이 발생하면 위반에 대한 컨텍스트를 제공하기 위해 보낸 사람(보낸 사람), 받는 사람의 이름(받는 사람), 채널 이름, 날짜, 시간 및 메시지가 기록됩니다.  | [a9d28fcf-036e-4a85-9003-332303e3a29b](https://docs.microsoft.com/microsoft-365-app-certification/azure/a9d28fcf-036e-4a85-9003-332303e3a29b) |
>| User.Read | 위임 | 로그인 및 사용자 프로필 읽기 | Single Sign-On에 사용 | [a9d28fcf-036e-4a85-9003-332303e3a29b](https://docs.microsoft.com/microsoft-365-app-certification/azure/a9d28fcf-036e-4a85-9003-332303e3a29b) |
>| User.Read.All | application | 모든 사용자의 전체 프로필 읽기 | 위반이 발생하면 위반에 대한 컨텍스트를 제공하기 위해 보낸 사람(보낸 사람), 받는 사람의 이름(받는 사람), 채널 이름, 날짜, 시간 및 메시지가 기록됩니다.  | [a9d28fcf-036e-4a85-9003-332303e3a29b](https://docs.microsoft.com/microsoft-365-app-certification/azure/a9d28fcf-036e-4a85-9003-332303e3a29b) |


#### <a name="non-microsoft-services-used"></a>비영구 Microsoft 서비스

앱이 Microsoft가 아닌 서비스로 조직 데이터를 전송하거나 공유하는 경우 앱에서 사용하는 비 Microsoft 서비스, 전송되는 데이터를 나열하고 앱이 이 정보를 전송해야 하는 이유에 대한 사유를 포함합니다.

>| **모든 비 Microsoft 서비스 OII가 다음으로 전송됩니다.** |  **전송되는 OII는 무엇입니까?** | **OII 전송의 사당성** |
>|:-----------------------------------------------------|:------------------------------|:----------------------------------------|
>| Senso.cloud 성능에 대해 섹션 5의 하위 프로세서를 https://www.senso.cloud/privacy-policy/ 사용하게 됩니다. 개인 데이터의 공개. | 타사 계정 및 타사 공급자와 공유하는 데이터 형식은 표의 오른쪽 열인 5 섹션에서 https://www.senso.cloud/privacy-policy/) 설정됩니다. | 각 계약의 처리에 대한 적법한 기준은 사용자와의 계약 또는 정당한 이익(비즈니스 실행, 데이터 보관, 관리 및 IT 서비스 제공, 네트워크 보안, 사기 및 데이터 위반을 방지하기 위해 필요한 경우)을 기반으로 합니다. 예를 들어, 고객에게 청구 연락처 알림을 보내거나 신용 카드로 결제하는 경우 고객 지원에 액세스할 때 지원 티켓을 발생하기 위해 정보가 필요한 비즈니스 메일 주소와 전자 메일 주소가 필요합니다. |

#### <a name="data-access-via-bots"></a>봇을 통한 데이터 액세스

이 앱에 봇 또는 메시징 확장이 포함되어 있는 경우 팀 구성원의 명단(이름, 성, 표시 이름, 전자 메일 주소)이나 팀 구성원이 추가된 채팅의 최종 사용자 식별 정보(EUII)에 액세스할 수 있습니다. 이 앱이 이 기능을 사용하나요?

>| **EUII 액세스의 사유는 무엇입니까?**  | **EUII가 데이터베이스에 저장되어 있나요?** | **EUII 저장의 사유는 무엇입니까?** |
>|:---------------------------------------|:-----------------------------------|:------------------------------------|
>| Senso.cloud 성능에 대해 섹션 5의 하위 프로세서를 https://www.senso.cloud/privacy-policy/ 사용하게 됩니다. 개인 데이터의 공개. | 타사 계정 및 타사 공급자와 공유하는 데이터 형식은 표의 오른쪽 열인 5 섹션에서 https://www.senso.cloud/privacy-policy/) 설정됩니다. | 각 계약의 처리에 대한 적법한 기준은 사용자와의 계약 또는 정당한 이익(비즈니스 실행, 데이터 보관, 관리 및 IT 서비스 제공, 네트워크 보안, 사기 및 데이터 위반을 방지하기 위해 필요한 경우)을 기반으로 합니다. 예를 들어, 고객에게 청구 연락처 알림을 보내거나 신용 카드로 결제하는 경우 고객 지원에 액세스할 때 지원 티켓을 발생하기 위해 정보가 필요한 비즈니스 메일 주소와 전자 메일 주소가 필요합니다. |


#### <a name="telemetry-data"></a>원격 분석 데이터

이 응용 프로그램의 원격 분석 또는 로그에 OII(조직 식별 정보) 또는 EUII(최종 사용자 식별 정보)가 나타나나요? 그렇다면 저장되는 데이터와 보존 및 제거 정책에 대해 설명하세요.

>Senso는 키워드 및 이미지 위협 감지 라이브러리에 대해 채팅 메시지를 모니터링합니다.  일치하는 경우 위반 트리거에 대해 다음 정보를 기록합니다. 시간 및 날짜, 사이트 ID, 구/이미지, 심각도, From, To, 채널 이름, 상태 및 최종 사용자의 검토를 위해 라이브러리 트리거  법적, 운영, 회계 또는 보고 요구 사항을 충족하기 위해 수집한 목적을 이행하기 위해 필요한 기간 동안만 PII를 보존합니다.

#### <a name="organizational-controls-for-data-stored-by-partner"></a>파트너가 저장한 데이터에 대한 조직 제어

조직의 관리자가 파트너 시스템에서 정보를 제어하는 방법에 대해 설명하는 방법 삭제, 보존, 감사, 보관, 최종 사용자 정책 등

>선임 개발자, IP 잠겨 있는, 2단계 인증 및 감사 내선 정보에 제한적으로 액세스할 수 있습니다.

#### <a name="human-review-of-organizational-information"></a>조직 정보의 인적 검토

사람이 이 앱에서 수집하거나 저장하는 OII(조직 식별 정보) 데이터를 검토하거나 분석하는 데 관여하나요?

>예

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="mcas"

Microsoft Cloud App Security [카탈로그의](https://www.microsoft.com/enterprise-mobility-security/cloud-app-security) 정보가 아래에 표시됩니다.

<iframe height='1020' title='Microsoft Cloud App Security 정보' src='https://appmcasinfoprod.azurewebsites.net/#/dashboard/40112' frameborder='no' style='width: 100%;'></iframe>

<a href="https://appmcasinfoprod.azurewebsites.net/#/dashboard/40112" target="_blank">새 탭에서 보기</a>

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="identity"

### <a name="identity-information"></a>ID 정보

이 정보는 Senso에서 이 앱이 인증, 권한 부여, 응용 프로그램 등록 모범 사례 및 기타 ID 조건을 처리하는 방법에 대해 제공했습니다.

| **정보** | **응답** |
|:----------------|:-------------|
| Microsoft Identify Platform(Azure AD)과 통합하나요?  | 예 |
| 통합 검사 목록에 설명된 적용 가능한 모든 모범 사례를 Microsoft ID 플랫폼 준수하나요?  | 예 |
| 앱에서 인증에 MSAL(Microsoft 인증 라이브러리)을 사용하나요? | 예 |
| 앱에서 조건부 액세스 정책을 지원하나요? | 예 |
| 지원되는 정책 유형 나열 | 역할 기반 액세스 권한 |
| 앱에서 시나리오에 대한 최소 권한 권한을 요청하나요? | 예 |
| 앱의 정적으로 등록된 사용 권한은 앱이 동적으로 그리고 증분적으로 요청하는 권한을 정확하게 반영하나요? | 예 |
| 앱에서 다중 테넌시를 지원하나요? | 예 |
| 앱에 기밀 클라이언트가 있나요? | 예 |
| 앱에 등록된 리디렉션 URI(통합 리소스 식별자)를 모두 소유하고 있나요? | 예 |
| 앱의 경우 어떻게 사용하지 않도록 해야 하나요? | - 와일드카드 리디렉션 URIS,<br/><br/>- 리소스 소유자 암호 자격 증명(ROPC) 흐름 |
| 앱에서 웹 API를 노출하나요? | 아니요 |
| 앱에서 미리 보기 API를 사용하나요? | 아니요 |
| 앱에서 사용되지 않는 API를 사용하나요? | 아니요 |

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end
