---
title: 광범위한 아이디어별 광범위한 아이디어에 대한 응용 프로그램 정보
ms.author: elmalova
author: elenamalova
ms.date: 06/03/2020
ms.topic: article
ms.service: attestation
certification_type: attested
description: 광범위한 아이디어, 데이터 처리 정책, CSA STAR 레지스트리의 Microsoft Cloud App Security 앱 카탈로그 정보 및 보안/규정 준수 정보에 사용할 수 있는 모든 보안 및 규정 준수 정보
zone_pivot_groups: app-info-data-mcas
ms.openlocfilehash: 1e73a7aebbaaffa12572717f7a4a9968fd5667f7
ms.sourcegitcommit: d85595f6518d8d05f0aee75380f51659908b6bcb
ms.translationtype: MT
ms.contentlocale: ko-KR
ms.lasthandoff: 09/12/2021
ms.locfileid: "59286853"
---
# <a name="wide-ideas"></a>Wide Ideas

<p></p>
<img alt="Publisher Attestation: The information on this page is based on a self-assessment report provided by the app developer on the security, compliance, and data handling practices followed by this app. Microsoft makes no guarantees regarding the accuracy of the information." src="../media/attested.png" width="650" />
<p>개발자가 마지막으로 업데이트한 날짜: 2020년 6월 3일</p>

* <a href="https://teams.microsoft.com/l/app/2a64f929-bed9-44d9-aa65-d7b921889959" target="_blank">저장소의 Teams 보기</a>
* <a href="https://appsource.microsoft.com/product/office/WA200000819" target="_blank">AppSource의 보기</a>

::: zone pivot="general"

### <a name="general-information"></a>일반 정보

광범위한 아이디어가 Microsoft에 제공하는 정보:

| **정보** | **응답** |
|:----------------|:-------------|
| 앱 이름 | Wide Ideas |
| ID | WA200000819 |
| Office 365 클라이언트 지원 | Microsoft Teams |
| 파트너 회사 이름 | Wide Ideas |
| 파트너 웹 사이트의 URL | [https://getwideideas.com](https://getwideideas.com) |
| 개인 정보 취급 방침의 URL | [https://getwideideas.com/privacy-policy/](https://getwideideas.com/privacy-policy/) |
| 사용 약관 URL | [https://pinpointprod.blob.core.windows.net/marketing/Partne...](https://pinpointprod.blob.core.windows.net/marketing/Partner_21474849364/Product_42949683744/Asset_0831a14b-e5df-4f0b-8385-3c06edaeceeb/GENERALTERMSANDCONDITIONSWideI.pdf) |

 [!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="data"

### <a name="how-the-app-handles-data"></a>앱이 데이터를 처리하는 방법

이 정보는 이 앱이 조직 데이터를 수집 및 저장하는 방법 및 앱이 수집하는 데이터를 통해 조직이 가지는 컨트롤에 대한 광범위한 아이디어를 통해 제공됩니다.

#### <a name="data-access-using-microsoft-graph"></a>Microsoft 365를 사용한 데이터 Graph

이 앱에 [Graph Microsoft 사용자 권한을](https://docs.microsoft.com/graph/permissions-reference) 나열합니다.

>| **사용 권한**  | **사용 권한 유형(위임/ 응용 프로그램)** | **데이터가 수집하나요? 수집의 사당성** | **데이터가 저장되어 있나요? 저장 사정이 있나요?** | **Azure AD 앱 ID** |
>|:----------------|:------------------------------------------------|:--------------------------------------------------------|:--------------------------------------------------|:--------------------|
>| Directory.Read.All | application | 그룹 ID 및 어떤 사용자가 어떤 그룹에 속하는지 저장 | 앱이 고객 조직 디렉터리(예: 사용자 및 그룹)의 데이터를 읽을 수 있도록 허용합니다.  | [77baef51-6387-4aff-9b3f-23e4654c30cd](https://docs.microsoft.com/microsoft-365-app-certification/azure/77baef51-6387-4aff-9b3f-23e4654c30cd) |
>| Group.ReadWrite.All | application | 그룹과 연결된 채널 ID를 저장합니다. | 사용자가 고객 포털에서 팀, 채널 및 탭을 Microsoft Teams 수 있습니다. 이렇게 하면 사용자가 기존 팀을 고객 포털에 Microsoft Teams 수 있습니다. | [77baef51-6387-4aff-9b3f-23e4654c30cd](https://docs.microsoft.com/microsoft-365-app-certification/azure/77baef51-6387-4aff-9b3f-23e4654c30cd) |
>| User.Read | 위임 | 이름 전자 메일을 &amp; 저장합니다. | 사용자를 대신하여 Microsoft Graph 액세스 권한을 부여할 수 있습니다. | [77baef51-6387-4aff-9b3f-23e4654c30cd](https://docs.microsoft.com/microsoft-365-app-certification/azure/77baef51-6387-4aff-9b3f-23e4654c30cd) |


#### <a name="non-microsoft-services-used"></a>비영구 Microsoft 서비스

앱이 Microsoft가 아닌 서비스로 조직 데이터를 전송하거나 공유하는 경우 앱에서 사용하는 비 Microsoft 서비스, 전송되는 데이터를 나열하고 앱이 이 정보를 전송해야 하는 이유에 대한 사유를 포함합니다.

>| **모든 비 Microsoft 서비스 OII가 다음으로 전송됩니다.** |  **전송되는 OII는 무엇입니까?** | **OII 전송의 사당성** |
>|:-----------------------------------------------------|:------------------------------|:----------------------------------------|
>| Mailjet 전자 메일 알림에 사용되는 전자 메일입니다. |  | 해당 없음 |

#### <a name="data-access-via-bots"></a>봇을 통한 데이터 액세스

이 앱에 봇 또는 메시징 확장이 포함되어 있는 경우 팀 구성원의 명단(이름, 성, 표시 이름, 전자 메일 주소)이나 팀 구성원이 추가된 채팅의 최종 사용자 식별 정보(EUII)에 액세스할 수 있습니다. 이 앱이 이 기능을 사용하나요?

>| **EUII 액세스의 사유는 무엇입니까?**  | **EUII가 데이터베이스에 저장되어 있나요?** | **EUII 저장의 사유는 무엇입니까?** |
>|:---------------------------------------|:-----------------------------------|:------------------------------------|
>| 백비에서 사용자를 만들고 팀에 연결된 콘텐츠에 액세스할 수 있는 권한을 부여하기 위해 | We store: Name - 사용자의 이름을 표시하기 위해 전자 메일 주소 - 사용자를 식별하기 위해 |  |


#### <a name="telemetry-data"></a>원격 분석 데이터

이 응용 프로그램의 원격 분석 또는 로그에 OII(조직 식별 정보) 또는 EUII(최종 사용자 식별 정보)가 나타나나요? 그렇다면 저장되는 데이터와 보존 및 제거 정책에 대해 설명하세요.

>로그에 IP 번호만 저장합니다. 

조직은 데이터를 삭제하려는 경우 공급자로 요청을 보낼 수 있습니다.

#### <a name="organizational-controls-for-data-stored-by-partner"></a>파트너가 저장한 데이터에 대한 조직 제어

조직의 관리자가 파트너 시스템에서 정보를 제어하는 방법에 대해 설명하는 방법 삭제, 보존, 감사, 보관, 최종 사용자 정책 등

>데이터 저장소: 모든 고객 데이터는 Microsoft Azure 저장됩니다. 사용자는 Azure AD를 통해 인증된 2개 요소로 인증해야 합니다. RBAC(역할 기반 액세스)가 있습니다. 모든 Microsoft Azure 액세스는 암호화된 연결을 통해 엄격하게 설정됩니다. 모든 데이터는 미사시로 암호화됩니다. 모든 서비스는 Azure 보안 센터의 모범 사례에 의해 보호됩니다. 

또한 최소 권한 원칙에 따라 액세스 정책이 있습니다. 


#### <a name="human-review-of-organizational-information"></a>조직 정보의 인적 검토

사람이 이 앱에서 수집하거나 저장하는 OII(조직 식별 정보) 데이터를 검토하거나 분석하는 데 관여하나요?

>아니요

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="mcas"

Microsoft Cloud App Security [카탈로그의](https://www.microsoft.com/enterprise-mobility-security/cloud-app-security) 정보가 아래에 표시됩니다.

<iframe height='1020' title='Microsoft Cloud App Security 정보' src='https://appmcasinfoprod.azurewebsites.net/#/dashboard/35870' frameborder='no' style='width: 100%;'></iframe>

<a href="https://appmcasinfoprod.azurewebsites.net/#/dashboard/35870" target="_blank">새 탭에서 보기</a>

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

