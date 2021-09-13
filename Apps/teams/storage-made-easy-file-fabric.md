---
title: 간편한 구성을 통해 파일 패브릭에 Storage 정보
ms.author: elmalova
author: elenamalova
ms.date: 06/30/2021
ms.topic: article
ms.service: attestation
certification_type: attested
description: CSA STAR 레지스트리의 파일 패브릭, 데이터 처리 정책, Microsoft Cloud App Security 앱 카탈로그 정보 및 보안/규정 준수 정보에 대해 사용 가능한 모든 보안 및 규정 준수 정보입니다.
zone_pivot_groups: app-info-data-identity
ms.openlocfilehash: 3070723eecc0e7dda11aff31da6b20a785f558b5
ms.sourcegitcommit: d85595f6518d8d05f0aee75380f51659908b6bcb
ms.translationtype: MT
ms.contentlocale: ko-KR
ms.lasthandoff: 09/12/2021
ms.locfileid: "59287314"
---
# <a name="file-fabric"></a>File Fabric

<p></p>
<img alt="Publisher Attestation: The information on this page is based on a self-assessment report provided by the app developer on the security, compliance, and data handling practices followed by this app. Microsoft makes no guarantees regarding the accuracy of the information." src="../media/attested.png" width="650" />
<p>개발자가 마지막으로 업데이트한 날짜: 2021년 6월 30일</p>

* <a href="https://teams.microsoft.com/l/app/bd063a87-1e4d-42cf-baea-8cab71839e35" target="_blank">저장소의 Teams 보기</a>
* <a href="https://appsource.microsoft.com/product/office/WA200003017" target="_blank">AppSource의 보기</a>

::: zone pivot="general"

### <a name="general-information"></a>일반 정보

Microsoft에서 제공하는 Storage 쉽게 사용할 수 있습니다.

| **정보** | **응답** |
|:----------------|:-------------|
| 앱 이름 | File Fabric |
| ID | WA200003017 |
| Office 365 클라이언트 지원 | Microsoft Teams |
| 파트너 회사 이름 | Storage Made Easy |
| 파트너 웹 사이트의 URL | [https://storagemadeeasy.com](https://storagemadeeasy.com) |
| 응용 프로그램 Teams 페이지의 URL입니다. | [https://docs.storagemadeeasy.com/microsoft-teams](https://docs.storagemadeeasy.com/microsoft-teams) |
| 개인 정보 취급 방침의 URL | [https://www.storagemadeeasy.com/privacy](https://www.storagemadeeasy.com/privacy) |
| 사용 약관 URL | [https://www.storagemadeeasy.com/terms](https://www.storagemadeeasy.com/terms) |

 [!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="data"

### <a name="how-the-app-handles-data"></a>앱이 데이터를 처리하는 방법

이 정보는 Storage 앱이 조직 데이터를 수집하고 저장하는 방법과 앱이 수집하는 데이터를 통해 조직에서 제공하는 컨트롤에 대해 쉽게 알 수 있습니다.

#### <a name="data-access-using-microsoft-graph"></a>Microsoft 365를 사용한 데이터 Graph

이 앱에 [Graph Microsoft 사용자 권한을](https://docs.microsoft.com/graph/permissions-reference) 나열합니다.

>| **사용 권한**  | **사용 권한 유형(위임/ 응용 프로그램)** | **데이터가 수집하나요? 수집의 사당성** | **데이터가 저장되어 있나요? 저장 사정이 있나요?** | **Azure AD 앱 ID** |
>|:----------------|:------------------------------------------------|:--------------------------------------------------------|:--------------------------------------------------|:--------------------|
>| Files.ReadWrite | application | 사용자가 앱을 통해 지정된 파일을 다운로드, 업로드 또는 편집할 때 읽거나 쓰는 파일 데이터입니다. | 파일 데이터가 저장되지 않습니다. | [0752d800-857f-49bd-87eb-e60985516c67](https://docs.microsoft.com/microsoft-365-app-certification/azure/0752d800-857f-49bd-87eb-e60985516c67) |
>| Sites.ReadWrite.All | application | 모든 파일 서비스에서&#8217;보기를 제공하는 모든 사용자에 대해 수집된 메타데이터입니다. | 더 빠른 검색 및 검색을 제공하기 위해 캐시된 메타데이터입니다. | [0752d800-857f-49bd-87eb-e60985516c67](https://docs.microsoft.com/microsoft-365-app-certification/azure/0752d800-857f-49bd-87eb-e60985516c67) |

#### <a name="data-access-using-other-microsoft-apis"></a>다른 Microsoft API를 사용한 데이터 액세스

기본 제공 앱 및 추가 Microsoft 365 Microsoft Graph 기타 Microsoft API를 사용하여 OII(조직 식별 가능 정보)를 수집하거나 처리합니다. 이 앱에서 사용하는 Microsoft API를 Graph Microsoft API를 나열합니다.

>| **API** |  **OII가 수집하나요?** |  **수집되는 OII는 무엇입니까?** | **OII 수집의 사당성** | **OII가 저장되어 있나요?** | **OII 저장의 사당성** |
>|:--------|:-----------------------|:----------------------------|:--------------------------------------|:-------------------|:-----------------------------------|
>| Azure Blob 저장소 | 예 | 개체 메타데이터 및 데이터 | 모든 파일 서비스에서&#8217;보기를 제공하는 모든 사용자에 대해 수집된 메타데이터입니다. 사용자가 앱을 통해 지정된 개체를 다운로드, 업로드 또는 편집할 때 읽거나 쓰는 개체입니다. | 개체 메타데이터가 저장됩니다. | 더 빠른 검색 및 검색을 제공하기 위해 캐시된 메타데이터입니다. |
>| 웹용 Office | 아니요 |  |  |  |  |

#### <a name="non-microsoft-services-used"></a>비영구 Microsoft 서비스

앱이 Microsoft가 아닌 서비스로 조직 데이터를 전송하거나 공유하는 경우 앱에서 사용하는 비 Microsoft 서비스, 전송되는 데이터를 나열하고 앱이 이 정보를 전송해야 하는 이유에 대한 사유를 포함합니다.

>| **모든 비 Microsoft 서비스 OII가 다음으로 전송됩니다.** |  **전송되는 OII는 무엇입니까?** | **OII 전송의 사당성** |
>|:-----------------------------------------------------|:------------------------------|:----------------------------------------|
>| 사용자는 인증을 통해 제어하는 저장소 서비스에 연결할 수 있습니다. | 파일 및 개체 메타데이터는 페더링된 검색 및 검색을 위해 캐시됩니다. 특정 파일 또는 개체를 읽고 업데이트하면 데이터가 전송됩니다. | 메타데이터는 저장소에 페더전된 보기를 제공합니다. 데이터 전송을 통해 안전한 유니버설 액세스를 허용합니다. |

#### <a name="data-access-via-bots"></a>봇을 통한 데이터 액세스

이 앱에 봇 또는 메시징 확장이 포함되어 있는 경우 팀 구성원의 명단(이름, 성, 표시 이름, 전자 메일 주소)이나 팀 구성원이 추가된 채팅의 최종 사용자 식별 정보(EUII)에 액세스할 수 있습니다. 이 앱이 이 기능을 사용하나요?

>EUII에 액세스하지 않습니다.


#### <a name="telemetry-data"></a>원격 분석 데이터

이 응용 프로그램의 원격 분석 또는 로그에 OII(조직 식별 정보) 또는 EUII(최종 사용자 식별 정보)가 나타나나요? 그렇다면 저장되는 데이터와 보존 및 제거 정책에 대해 설명하세요.

>응용 프로그램 원격 분석 또는 로그에 OII 또는 EUII가 나타나지 않습니다.

#### <a name="organizational-controls-for-data-stored-by-partner"></a>파트너가 저장한 데이터에 대한 조직 제어

조직의 관리자가 파트너 시스템에서 정보를 제어하는 방법에 대해 설명하는 방법 삭제, 보존, 감사, 보관, 최종 사용자 정책 등

>GDPR에 따라 데이터 처리 계약

#### <a name="human-review-of-organizational-information"></a>조직 정보의 인적 검토

사람이 이 앱에서 수집하거나 저장하는 OII(조직 식별 정보) 데이터를 검토하거나 분석하는 데 관여하나요?

>아니요

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="mcas"

Microsoft Cloud App Security [카탈로그의](https://www.microsoft.com/enterprise-mobility-security/cloud-app-security) 정보가 아래에 표시됩니다.

<iframe height='1020' title='Microsoft Cloud App Security 정보' src='https://appmcasinfoprod.azurewebsites.net/#/dashboard/' frameborder='no' style='width: 100%;'></iframe>

<a href="https://appmcasinfoprod.azurewebsites.net/#/dashboard/" target="_blank">새 탭에서 보기</a>

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="identity"

### <a name="identity-information"></a>ID 정보

이 정보는 Storage, 권한 부여, 응용 프로그램 등록 모범 사례 및 기타 ID 기준을 처리하는 방법에 대해 쉽게 확인할 수 있습니다.

| **정보** | **응답** |
|:----------------|:-------------|
| Microsoft Identify Platform(Azure AD)과 통합하나요?  | 예 |
| 통합 검사 목록에 설명된 적용 가능한 모든 모범 사례를 Microsoft ID 플랫폼 준수하나요?  | 예 |
| 앱에서 인증에 MSAL(Microsoft 인증 라이브러리)을 사용하나요? | 아니요 |
| 앱에서 조건부 액세스 정책을 지원하나요? | 아니요 |
| 앱에서 시나리오에 대한 최소 권한 권한을 요청하나요? | 예 |
| 앱의 정적으로 등록된 사용 권한은 앱이 동적으로 그리고 증분적으로 요청하는 권한을 정확하게 반영하나요? | 예 |
| 앱에서 다중 테넌시를 지원하나요? | 예 |
| 앱에 기밀 클라이언트가 있나요? | 예 |
| 앱에 등록된 리디렉션 URI(통합 리소스 식별자)를 모두 소유하고 있나요? | 예 |
| 앱의 경우 어떻게 사용하지 않도록 해야 하나요? | - 와일드카드 리디렉션 URIS,<br/>- OAuth2 암시적 Flow SPA에 필요하지 않은 경우<br/>- 리소스 소유자 암호 자격 증명(ROPC) 흐름 |
| 앱에서 웹 API를 노출하나요? | 예 |
| 사용 권한 모델에서 클라이언트 앱이 적절한 동의를 받은 경우 통화 성공만 허용하나요? | 예 |
| 앱에서 미리 보기 API를 사용하나요? | 아니요 |
| 앱에서 사용되지 않는 API를 사용하나요? | 아니요 |

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end
