---
title: Agile-IS를 통해 온라인 SharePoint Agile 작업 보드에 대한 응용 프로그램 정보
ms.author: elmalova
author: elenamalova
ms.date: 11/03/2020
ms.topic: article
ms.service: attestation
certification_type: attested
description: SharePoint Online용 Agile 작업 보드, 데이터 처리 정책, CSA STAR 레지스트리의 Microsoft Cloud App Security 앱 카탈로그 정보 및 보안/규정 준수 정보에 대해 사용할 수 있는 모든 보안 및 규정 준수 정보입니다.
zone_pivot_groups: app-info-data-mcas
ms.openlocfilehash: 26b19e5ce6563f49a5e76bf40e5422e43c5f804b
ms.sourcegitcommit: 50bd8e07d9355ae65935767a34aca39c46ade8f4
ms.translationtype: MT
ms.contentlocale: ko-KR
ms.lasthandoff: 05/06/2021
ms.locfileid: "52251687"
---
# <a name="agile-task-board-for-sharepoint-online"></a>Agile Task Board for SharePoint Online

<p></p>
<img alt="Publisher Attestation: The information on this page is based on a self-assessment report provided by the app developer on the security, compliance, and data handling practices followed by this app. Microsoft makes no guarantees regarding the accuracy of the information." src="../media/attested.png" width="650" />
<p>개발자가 마지막으로 업데이트한 날짜: 2020년 11월 3일</p>

* <a href="https://appsource.microsoft.com/product/office/WA200002087" target="_blank">AppSource의 보기</a>

::: zone pivot="general"

### <a name="general-information"></a>일반 정보

Agile-IS에서 Microsoft에 제공한 정보:

| **정보** | **응답** |
|:----------------|:-------------|
| 앱 이름 | Agile Task Board for SharePoint Online |
| ID | WA200002087 |
| Office 365 클라이언트 지원 | SharePoint 2016 이상 |
| 파트너 회사 이름 | Agile-IS |
| 파트너 웹 사이트의 URL | [https://appsource.microsoft.com/marketplace/apps?product=of...](https://appsource.microsoft.com/marketplace/apps?product=office) |
| 개인 정보 취급 방침의 URL | [https://www.agile-is.de/en/telemetry](https://www.agile-is.de/en/telemetry) |
| 사용 약관 URL | [https://go.microsoft.com/fwlink/?linkid=2041178](https://go.microsoft.com/fwlink/?linkid=2041178) |

 [!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="data"

### <a name="how-the-app-handles-data"></a>앱이 데이터를 처리하는 방법

이 정보는 Agile-IS에서 이 앱이 조직 데이터를 수집하고 저장하는 방법 및 앱이 수집하는 데이터를 통해 조직에서 사용할 컨트롤에 대해 제공됩니다.

#### <a name="data-access-using-microsoft-graph"></a>Microsoft 365를 사용한 데이터 Graph

이 앱에 [Graph Microsoft 사용자 권한을](https://docs.microsoft.com/graph/permissions-reference) 나열합니다.

>이 응용 프로그램은 Microsoft 응용 프로그램을 Graph.


#### <a name="non-microsoft-services-used"></a>비영구 Microsoft 서비스

앱이 Microsoft가 아닌 서비스로 조직 데이터를 전송하거나 공유하는 경우 앱에서 사용하는 비 Microsoft 서비스, 전송되는 데이터를 나열하고 앱이 이 정보를 전송해야 하는 이유에 대한 사유를 포함합니다.

>비영구 Microsoft 서비스 사용되지 않습니다.



#### <a name="add-in-data-access"></a>추가 기능 데이터 액세스

이 앱이 조직의 데이터에 액세스하는 데 필요한 사용 권한, 이 사용 권한의 사당성 및 목적(앱에서 이 정보를 어떤 용도로 사용하나요?) 및 앱에서 해당 데이터베이스에 이 정보를 저장하는지 여부를 나열합니다.

>| **사용 권한**  | **설명** |
>|:----------------|:----------------|
>| 기본 | 문서를&#8217;변경하지 못합니다. |
>| 데이터 보내기 | 인터넷을 통해 데이터를 보낼 수 있습니다. |

#### <a name="telemetry-data"></a>원격 분석 데이터

이 응용 프로그램의 원격 분석 또는 로그에 OII(조직 식별 정보) 또는 EUII(최종 사용자 식별 정보)가 나타나나요? 그렇다면 저장되는 데이터와 보존 및 제거 정책에 대해 설명하세요.

>응용 프로그램 인사이트 원격 분석 데이터 내에서 도메인 이름 및 해시된 사용자 ID를 수집합니다. 각 앱 인스턴스 내에서 원격 분석 데이터의 전송을 제어하고 해제할 수 있습니다. 데이터 후속적으로 데이터를 요청해야 합니다.

#### <a name="organizational-controls-for-data-stored-by-partner"></a>파트너가 저장한 데이터에 대한 조직 제어

조직의 관리자가 파트너 시스템에서 정보를 제어하는 방법에 대해 설명하는 방법 삭제, 보존, 감사, 보관, 최종 사용자 정책 등

>응용 프로그램은 앱의 SharePoint 실행되는 동일한 사이트에 모든 데이터를 SharePoint 온라인 목록 및 문서 라이브러리에 저장합니다. 이 데이터에 대한 액세스 제어는 고객의 테넌트 구성에 따라 다릅니다. 

라이선스 제어를 위해 도메인 및 UPN은 Azure에서 호스트되는 서비스로 전송됩니다. 이 정보는 Azure AD 인증을 통해 보호됩니다.


#### <a name="human-review-of-organizational-information"></a>조직 정보의 인적 검토

사람이 이 앱에서 수집하거나 저장하는 OII(조직 식별 정보) 데이터를 검토하거나 분석하는 데 관여하나요?

>아니요

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="mcas"

Microsoft Cloud App Security [카탈로그의](https://www.microsoft.com/enterprise-mobility-security/cloud-app-security) 정보가 아래에 표시됩니다.

<iframe height='1020' title='Microsoft Cloud App Security 정보' src='https://appmcasinfoprod.azurewebsites.net/#/dashboard/36140' frameborder='no' style='width: 100%;'></iframe>

<a href="https://appmcasinfoprod.azurewebsites.net/#/dashboard/36140" target="_blank">새 탭에서 보기</a>

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

