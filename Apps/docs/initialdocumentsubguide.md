---
ms.author: oromalle
title: Microsoft 365 인증 - 초기 문서 제출 가이드
author: orionomalley
manager: tonybal
description: 초기 문서 제출은 인증의 사전 평가 단계의 일부입니다.
keywords: 앱 인증 팀 Microsoft 365 보안 규정 준수 m365 초기 문서 제출
ms.topic: conceptual
ms.service: certification
ms.openlocfilehash: 23c3cf7a64025bb7269adb35175e8d87bc64224e
ms.sourcegitcommit: ec1d4f7013722fe672830e3664b0fb8b0f33bd37
ms.translationtype: MT
ms.contentlocale: ko-KR
ms.lasthandoff: 04/12/2022
ms.locfileid: "64784507"
---
# <a name="microsoft-365-ceritification---initial-document-submission-guide"></a>Microsoft 365 인증 - 초기 문서 제출 가이드

초기 문서 제출은 인증의 사전 평가 단계의 일부입니다. 제공된 정보는 인증 분석가에게 평가 범위에 포함되는 제어 및 시스템 구성 요소를 식별하는 데 필요한 배경을 제공합니다. 이 문서는 초기 문서 제출에 대해 예상되는 사항의 예로만 사용됩니다. 제공하는 설명서는 솔루션을 설계, 구현 및 관리하는 방법에 따라 달라집니다.

## <a name="what-is-the-hosting-environment-or-service-model-used-to-run-your-app"></a>앱을 실행하는 데 사용되는 호스팅 환경 또는 서비스 모델은 무엇인가요?
- IaaS(Infrastructure as a Service)는 클라우드 서비스 공급자가 인프라 구성 요소를 호스트하지만 ISV는 Virtual Machines/운영 체제, 데이터 저장소 및 네트워킹 구성 요소와 같은 구성 요소를 개별적으로 배포하고 관리하는 클라우드 서비스 모델입니다. 예를 들어 Azure Virtual Machine 및 Azure Disk Storage 있습니다.
- PaaS(Platform as a Service)는 클라우드 서비스 공급자가 인프라 구성 요소를 관리하는 클라우드 서비스 모델입니다. ISV는 자체 애플리케이션 및 서비스 배포만 담당합니다. 이 예제는 Azure 앱 Services, Azure Functions 및 Azure CDN.
- 이 컨텍스트에서 호스팅되는 ISV는 클라우드 서비스 공급자가 사용되지 않음을 의미합니다. ISV는 자체 서버, 디스크, 네트워킹을 온-프레미스에서 독립적으로 물리적으로 관리합니다.
- 이 컨텍스트의 하이브리드는 위의 모델 중 하나 이상이 사용됨을 의미합니다. 예를 들어 일부 ISV는 IaaS 서비스 및 PaaS 서비스를 혼합하여 앱을 지원하도록 선택하거나 일부 온-프레미스 ISV 호스트 구성 요소가 있고 다른 ISV는 클라우드 서비스 공급자에게 아웃소싱할 수 있습니다. 더 많은 서비스 모델 중 하나를 사용하는 경우 하이브리드를 선택합니다.

## <a name="penetration-test-report"></a>침투 테스트 보고서

지난 12개월 이내에 완료된 날짜가 포함된 전체 침투 테스트 보고서를 포함하세요. 
-   이 보고서는 수동 침투 테스트에서 생성되어야 하며 자동화된 검사/테스트 도구의 출력일 수 없습니다.
-   이 보고서에는 앱/추가 기능의 작업을 지원하는 추가 환경과 함께 앱/추가 배포를 지원하는 환경이 포함되어야 합니다.


## <a name="system-component-inventory"></a>시스템 구성 요소 인벤토리

지원 인프라에서 사용하는 모든 시스템 구성 요소의 최신 발명품입니다. 평가 단계를 수행할 때 샘플링에 도움이 됩니다. 사용자 환경에 PaaS가 포함된 경우 사용된 모든 PaaS 서비스에 대한 세부 정보를 제공할 수 있는 경우에 유용합니다.

**참고:** IaaS/PaaS에는 ISV 제어 하에 있는 하드웨어가 없습니다.  이 경우 모든 바이러스 리소스의 목록 또는 스크린샷을 제공하세요.

**예제:**

|자산 이름|자산 유형|설명|제조업체|모델|
|---|---|---|---|---|
|D212|Windows 컴퓨터|가상 컴퓨터|해당 없음|해당 없음|
|LT101|랩톱|워크스테이션|Microsoft|Surface 3|
|C2938|스위치|스위치|해당 없음|해당 없음|
|LXM2|Linux 컴퓨터|테스트 컴퓨터|해당 없음|해당 없음|


## <a name="software-inventory"></a>소프트웨어 인벤토리

버전과 함께 범위 내 환경 내에서 사용되는 모든 소프트웨어를 포함하여 모든 소프트웨어 자산의 최신 인벤토리입니다.

**예:**

|소프트웨어|게시자|버전|용도|
|---|---|---|---|
|Windows Server|Microsoft 2016 |빌드 14393|프로덕션 환경에 대한 서버 운영 체제|
|Linux Ubuntu|해당 없음|16.04(제니얼)|DMZ 내에서 사용 중인 서버 운영 체제입니다.|
|Esxi|Vm 웨어|6.5.0(빌드 13004031)|가상 서버를 지원하는 데 사용됩니다.|
|Mysql(Windows)|해당 없음|8.0.2.1|채팅 기록을 저장할 데이터베이스 서버입니다.|
|톰캣|아파치|7.0.92|고객 포털.|
|IIS|Microsoft|10.0|API를 지원합니다.|


## <a name="third-party-dependencies"></a>타사 종속성

현재 실행 중인 버전에서 앱/추가 기능에서 사용하는 모든 종속성을 나열하는 설명서입니다.

**예:**

|웹 종속성|사용 중인 현재 버전|
|----|----|
|Jquery|3.5.1|
|React|16.13.1|
|부트스트랩|4.5.2|
|Express|4.17.1|
|Angular|10.0.14|
|AngularJS|1.8.0|


## <a name="public-ip-addresses"></a>공용 IP 주소

지원 인프라에서 사용하는 모든 공용 IP 주소 및 URL을 자세히 설명합니다. 사용 중인 범위를 분할하기 위해 적절한 구분이 구현되지 않는 한 환경에 할당된 전체 라우팅 가능한 IP 범위를 포함해야 합니다(분할에 대한 적절한 증거가 필요함).

**예제:**

|URL|IP 주소|
|-|-|
|https://portal.contoso.com |40.113.200.201 |
|https://filesapi.contoso.com|40.113.200.201|
|https://customerapi.contoso.com|40.113.200.202|
|https://bot.contoso.com|40.113.200.202|
|N/A(점프 서버)|40.113.200.200|


## <a name="resource-endpoints"></a>리소스 엔드포인트

API 이름 엔드포인트 주소 Contoso 고객 API https://customerapi.contoso.com Contoso Bot Service https://bot.contoso.com Contoso Files APIhttps://filesapi.contoso.com

내부적으로 개발된 리소스 엔드포인트 및 외부 리소스 엔드포인트를 포함하여 앱에서 사용하는 모든 API 엔드포인트의 전체 목록입니다. 환경 범위를 이해하려면 환경 내에서 API 엔드포인트 위치를 제공합니다.

**예:**

|API 이름|  엔드포인트 주소|
|-|-|
|Contoso 고객 API|  https://customerapi.contoso.com|
|Contoso Bot Service|   https://bot.contoso.com|
|Contoso Files API| https://filesapi.contoso.com|
|Microsoft Graph| https://graph.microsoft.com/v1.0/|


## <a name="architectural-diagram"></a>아키텍처 다이어그램

앱/추가 기능의 지원 인프라에 대한 개략적인 개요를 나타내는 논리 아키텍처 다이어그램입니다. 여기에는 앱/추가 기능을 지원하는 모든 호스팅 환경 및 지원 인프라가 포함되어야 합니다. 이 다이어그램은 인증 분석가가 범위 내 시스템을 이해하고 샘플링을 결정하는 데 도움이 되도록 환경 내의 다양한 지원 시스템 구성 요소를 모두 보여 주어야 합니다. 사용되는 호스팅 환경 유형도 지정하세요. ISV Hosted, IaaS, PaaS 또는 Hybrid. PaaS가 사용되는 경우 환경 내에서 지원 서비스를 제공하는 데 사용되는 다양한 PaaS 서비스를 지정하세요.

![아키텍처 다이어그램](../media/Architecturaldiagram.png)

## <a name="data-flow-diagram"></a>Data Flow 다이어그램

다음을 자세히 설명하는 다이어그램을 Flow.
-   앱/추가 기능(고객 데이터 포함)을 오가는 데이터입니다.
-   지원 인프라 내의 데이터 흐름(해당하는 경우)
-   데이터가 저장되는 위치와 위치, 외부 타사에 데이터가 전달되는 방법(타사에 대한 세부 정보 포함), 개방형/공용 네트워크 및 미사용 데이터를 전송할 때 데이터를 보호하는 방법을 강조 표시하는 다이어그램

![Data Flow 다이어그램](../media/Dataflowdiagram.png)



