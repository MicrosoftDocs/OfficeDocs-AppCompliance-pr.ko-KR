---
ms.author: oromalle
title: Microsoft 365 인증 - 초기 문서 제출 가이드
author: orionomalley
description: Microsoft 365 인증 제출 가이드 세분화 보기
keywords: 앱 인증 팀 Microsoft 365 준수 m365 초기 문서 제출
ms.topic: conceptual
ms.service: certification
ms.openlocfilehash: 0352b64649d87b40d185a2bc06ce23da6cf341ef
ms.sourcegitcommit: d67be08c82a50cc263a4bdeb176f41dd60716159
ms.translationtype: MT
ms.contentlocale: ko-KR
ms.lasthandoff: 10/15/2021
ms.locfileid: "60378816"
---
# <a name="microsoft-365-ceritification---initial-document-submission-guide"></a>Microsoft 365 작성 - 초기 문서 제출 가이드

초기 문서 제출은 인증의 사전 평가 단계의 일부입니다. 제공된 정보는 인증 분석가에게 평가 범위 내 컨트롤 및 시스템 구성 요소를 식별하는 데 필요한 배경 정보를 제공합니다. 이 문서는 초기 문서 전송에 대해 예상되는 예제로만 사용할 수 있습니다. 제공하는 설명서는 솔루션의 설계, 구현 및 관리 방식에 따라 달라집니다.

## <a name="penetration-test-report"></a>침투 테스트 보고서

지난 12개월 내에 완료된 날짜가 포함된 전체 침투 테스트 보고서를 포함하십시오. 
-   이 보고서는 수동 침투 테스트에서 생성해야 하지만 자동화된 검사/테스트 도구의 출력이 될 수 없습니다.
-   이 보고서에는 앱/추가 기능의 작동을 지원하는 추가 환경과 함께 앱/추가 배포를 지원하는 환경이 포함되어야 합니다.


## <a name="system-component-inventory"></a>시스템 구성 요소 인벤토리

지원 인프라에서 사용하는 모든 시스템 구성 요소의 최신 인벤트로이트입니다. 평가 단계를 수행할 때 샘플링에 도움이 됩니다. 환경에 PaaS가 포함되어 있는 경우 사용된 모든 PaaS 서비스에 대한 세부 정보를 제공할 수 있는 경우 유용합니다.

**참고:** IaaS/PaaS에는 ISV 제어에 있는 하드웨어가 없습니다.  이 경우 모든 바이루어 리소스의 목록 또는 스크린샷을 제공하세요.

**예제:**

|자산 이름|    자산 유형| 설명|    제조업체|   모델|
|-|-|-|-|-|
|D212|  Windows  컴퓨터|   가상 컴퓨터|    해당 없음| 해당 없음|
|LT101| 랩톱| Workstation|    Microsoft|  Surface 3|
|C2938| 스위치| 스위치|해당 없음|해당 없음|     
|LXM2|  Linux 컴퓨터|  테스트 컴퓨터|해당 없음|해당 없음|       


## <a name="software-inventory"></a>소프트웨어 인벤토리

범위 내 환경에서 사용되는 모든 소프트웨어를 포함하여 버전과 함께 모든 소프트웨어 자산의 최신 인벤토리입니다.

**예제:**

|소프트웨어|  게시자|  버전|     용도|
|-|-|-|-|
|Windows Server|    Microsoft 2016 | 빌드 14393| 프로덕션 환경용 서버 운영 체제|.
|Linux Ubuntu|  해당 없음|    16.04(Xenial)| DMZ 내에서 사용 중인 서버 운영 체제입니다.|
|ESXi|  VMWare| 6.5.0(빌드 13004031)| 가상 서버를 지원하는 데 사용됩니다.|
|Mysql(Windows)|   해당 없음|    8.0.2.1|    채팅 기록을 저장할 데이터베이스 서버입니다.|
|Tomcat|        아파치| 7.0.92| 고객 포털.|
|IIS|   Microsoft|  10.0|   API를 지원합니다.|


## <a name="third-party-dependencies"></a>타사 종속성

현재 실행 중인 버전에서 앱/추가 기능에서 사용하는 모든 종속성 목록을 표시하는 설명서입니다.

**예:**

|웹 종속성|  현재 사용 중인 버전|
|-|-|
|JQuery|    3.5.1|
|React| 16.13.1|
|부트스트ap| 4.5.2|
|Express|   4.17.1|
|Angular|   10.0.14|
|AngularJS| 1.8.0|


## <a name="public-ip-addresses"></a>공용 IP 주소

지원 인프라에서 사용하는 모든 공용 IP 주소 및 URL에 대한 세부 정보 사용 범위를 분할하기 위해 적절한 분할을 구현하지 않는 한 환경에 할당된 전체 라우팅 가능 IP 범위를 포함해야 합니다(적절한 분할 증거가 필요합니다).

**예:**

|URL|  IP 주소|
|-|-|
|https://portal.contoso.com |40.113.200.201 |
|https://filesapi.contoso.com|  40.113.200.201|
|https://customerapi.contoso.com|   40.113.200.202|
|https://bot.contoso.com|   40.113.200.202|
|N/A(점프 서버)| 40.113.200.200|


## <a name="resource-endpoints"></a>리소스 끝점

API 이름 끝점 주소 Contoso Customer API    https://customerapi.contoso.com Contoso Bot Service https://bot.contoso.com Contoso Files API   https://filesapi.contoso.com

내부적으로 개발된 외부 리소스 끝점을 포함하여 앱에서 사용하는 모든 API 끝점의 전체 목록입니다. 환경 범위를 이해하기 위해 환경 내의 API 끝점 위치를 제공합니다.

**예:**

|API 이름|  끝점 주소|
|-|-|
|Contoso 고객 API|  https://customerapi.contoso.com|
|Contoso Bot Service|   https://bot.contoso.com|
|Contoso Files API| https://filesapi.contoso.com|
|Microsoft Graph| https://graph.microsoft.com/v1.0/|


## <a name="architectural-diagram"></a>아키텍처 다이어그램

앱/추가 기능의 지원 인프라에 대한 개략적인 개요를 나타내는 논리 아키텍처 다이어그램입니다. 여기에는 모든 호스팅 환경과 앱/추가 기능을 지원하는 지원 인프라가 포함되어야 합니다. 이 다이어그램은 인증 분석가가 범위 내의 시스템을 이해하고 샘플링을 결정하는 데 도움이 될 수 있도록 환경 내의 모든 지원 시스템 구성 요소를 표시해야 합니다. 또한 사용되는 호스팅 환경 유형을 표시하십시오. ISV Hosted, IaaS, PaaS 또는 Hybrid. PaaS가 사용되는 경우 환경 내에서 지원 서비스를 제공하는 데 사용되는 다양한 PaaS 서비스를 표시하십시오.

![아키텍처 다이어그램](../media/Architecturaldiagram.png)

## <a name="data-flow-diagram"></a>데이터 Flow 다이어그램

Flow 설명하는 다이어그램을 참조합니다.
-   데이터 흐름은 앱/추가 기능(고객 데이터 포함)과/에서 전송됩니다.
-   지원 인프라 내의 데이터 흐름(해당되는 경우)
-   저장되는 데이터 위치 및 데이터, 외부 제3자에 데이터를 전달하는 방법(타사에 대한 세부 정보 포함) 및 개방형/공용 네트워크 및 미사용 데이터를 통해 전송되는 데이터를 보호하는 방법을 강조하는 다이어그램입니다.

![데이터 Flow 다이어그램](../media/Dataflowdiagram.png)



