---
title: Microsoft 365 대한 앱 준수 자동화 도구
author: xu-hong
ms.author: hongxu6
manager: zhshang
description: Microsoft 365용 앱 준수 자동화 도구 개요
keywords: 앱 인증 자동화 Microsoft 365
ms.topic: conceptual
ms.service: certification
ms.openlocfilehash: bd570496ce11bf72270cb18542846140122efb8b
ms.sourcegitcommit: 3931a0f41e8a6637cd1ce0a7c5273dabf592e475
ms.translationtype: MT
ms.contentlocale: ko-KR
ms.lasthandoff: 05/17/2022
ms.locfileid: "65441994"
---
# <a name="app-compliance-automation-tool-for-microsoft-365"></a>Microsoft 365 대한 앱 준수 자동화 도구
이 문서에서는 ACAT(App Compliance Automation Tool for Microsoft 365)가 무엇인지, 규정 준수를 간소화하고 Microsoft 365 인증을 얻는 방법을 알아봅니다.

> [!IMPORTANT]
> ACAT는 현재 비공개 미리 보기로 제공됩니다. 프라이빗 미리 보기 프로그램에 참여하려면 [여기에서](https://aka.ms/acat/private/signup) 등록하세요.

## <a name="what-is-app-compliance-automation-tool-for-microsoft-365"></a>Microsoft 365 대한 앱 준수 자동화 도구란?
ACAT(App Compliance Automation Tool for Microsoft 365)는 Azure Portal의 서비스로, Microsoft 365 고객 데이터를 사용하고 파트너 센터를 통해 게시되는 모든 앱의 규정 준수 과정을 간소화하는 데 도움이 됩니다. Microsoft 365 앱 준수 자동화 도구는 더 쉽고 편리하게 Microsoft 365 인증을 완료하는 데 도움이 되는 애플리케이션 중심 규정 준수 자동화 도구입니다. 프라이빗 미리 보기에서 ACAT는 Azure에서 실행되는 앱에서 사용할 수 있습니다.

이 도구를 사용하면 애플리케이션에 대한 규정 준수 경계를 빠르게 정의하고, 규정 준수 결과를 자동으로 모니터링하고, 규정 준수 감사를 보다 쉽게 완료할 수 있습니다. 규정 준수 경계는 앱 및 앱이 통신할 수 있는 백 엔드 시스템의 배달을 지원하는 클라우드 인프라입니다.

ACAT는 Microsoft 365 인증에 대해 더 빠른 추적을 제공하는 것 외에도 Microsoft 365 애플리케이션에 대한 다양한 규정 준수 시나리오를 지원합니다.

- Microsoft 365 인증 책임에 대한 자세한 보기 및 수정 단계입니다.
- 규정 준수 결과를 지속적으로 가져오는 데 도움이 되는 자동 일일 보고서입니다.
- 애플리케이션 수명 주기의 초기 단계에서 지침으로 사용할 수 있는 보안 및 규정 준수 모범 사례입니다.

## <a name="benefits-of-acat"></a>ACAT의 이점
애플리케이션 중심 규정 준수 경험
- ACAT는 현재 클라우드 인프라 준수 전략과 통합할 수 있는 애플리케이션의 클라우드 환경에 대해 매일 규정 준수 상태를 보고합니다.
- 개발자는 앱 개발 단계에서도 ACAT를 호출할 수 있습니다.

Microsoft 365 인증을 받는 프로세스를 가속화합니다.
- ACAT는 특정 Microsoft 365 인증 제어를 완전히 자동화합니다.
- Microsoft에서 적극적으로 개발 중인 자동화 목록이 지속적으로 증가하고 있습니다.

Microsoft 365 인증 워크플로와 네이티브 통합
- ACAT는 Microsoft 365 인증 목적으로 파트너 센터와 완전히 통합됩니다.

## <a name="concepts-of-acat"></a>ACAT의 개념
### <a name="regulatory-compliance-report"></a>규정 준수 보고서 
ACAT에서 애플리케이션에 대한 준수 보고서를 만들어 애플리케이션의 준수 상태를 감사할 수 있습니다. 애플리케이션을 빌드하는 Azure 리소스를 지정하여 애플리케이션의 규정 준수 경계를 정의할 수 있습니다. 여러 개발 환경 및 단계에 따라 하나의 애플리케이션에 대해 여러 보고서를 만듭니다.

보고서가 만들어지면 ACAT는 미리 정의된 트리거 시간에 규정 준수 데이터를 수집한 다음 규정 준수 결과를 보고서로 생성합니다. 한편, ACAT는 보고서를 삭제하도록 선택할 때까지 규정 준수 보고서에 대한 규정 준수 변경 내용을 지속적으로 모니터링합니다.

### <a name="microsoft-365-certification-control-results"></a>인증 제어 결과 Microsoft 365
규정 준수 보고서에서 규정 준수 결과는 ACAT에 의해 플래그가 지정된 해당 상태의 컨트롤별로 구성됩니다.
- **전달됨**: 완전히 자동화된 Microsoft 365 인증 제어에 대한 오류는 없습니다.
- **실패**: 완전히 자동화된 Microsoft 365 인증 컨트롤에 대한 고객 책임이 검색되지 않았습니다.
- **통과됨 - 추가 증거 필요**: *부분적으로 자동화된* Microsoft 365 인증 컨트롤에 대한 오류가 없습니다.
- **실패 - 추가 증명 필요**: *부분적으로 자동화* 된 Microsoft 365 인증 제어에 대한 고객 책임이 검색되지 않았습니다.
- **수동 제어**: ACAT는 Microsoft 365 인증 컨트롤에 대한 고객의 책임을 자동화하지 않습니다.

### <a name="customer-responsibility"></a>고객 책임
충족해야 하는 각 컨트롤과 관련된 고객 책임 집합이 있습니다. 데이터, 엔드포인트, 계정, 액세스 관리 등의 영역에서 사용자가 보유하는 책임입니다.

ACAT는 각 고객 책임에 대한 데이터를 수집하고 이에 대한 평가 결과를 반환합니다. 또한 Microsoft 365 인증 표준에 부합하는 데 도움이 되는 지침인 수정 작업을 제공합니다.


## <a name="faq"></a>FAQ
### <a name="what-are-manual-controls-and-partially-automated-controls"></a>수동 컨트롤 및 부분적으로 자동화된 컨트롤이란?
각 규정 준수 제어는 ACAT가 규정 준수 데이터를 수집하는 고객 책임 집합과 연결됩니다. 그러나 현재 Microsoft 365 인증에 대한 모든 컨트롤이 ACAT에서 적용되는 것은 아닙니다(적용 범위를 확장하기 위한 지속적인 노력이 있습니다). 부분적으로 자동화된 제어의 경우 ACAT는 고객 책임의 일부를 자동화합니다. 규정 준수 상태를 참조에 사용할 수 있지만 Microsoft 365 인증 감사에 직접 사용할 수는 없습니다. 수동 제어의 경우 ACAT는 현재 고객의 책임을 자동화하지 않습니다.

### <a name="i-made-the-suggested-changes-base-on-the-remediation-suggestion-yet-the-control-is-still-failing"></a>수정 제안에 따라 제안된 변경 내용을 만들었지만 컨트롤은 여전히 실패합니다.
오류를 해결하기 위한 조치를 취한 후 ACAT가 새로 고친 평가 결과를 가져와 컨트롤 상태를 업데이트할 때까지 기다려야 합니다. 평가는 미리 설정된 트리거 시간에 24시간마다 실행됩니다.

### <a name="how-is-the-compliance-report-used-in-the-certification-process"></a>인증 프로세스에서 규정 준수 보고서는 어떻게 사용하나요?
ACAT는 [파트너 센터](https://partner.microsoft.com/dashboard)와 원활하게 통합되어 Microsoft 365 인증 과정을 완료합니다. 규정 준수 보고서를 만드는 동안 Microsoft 365 인증 구성( 제품 GUID)을 편집할 수 있습니다. 만드는 동안 선택 사항이며 나중에 애플리케이션 게시를 시작할 때 구성할 수 있습니다.

## <a name="learn-more"></a>자세히 알아보기

* [ACAT를 사용하여 시작](https://aka.ms/acat/getstarted)
* [Microsoft 365 인증에 대해 자세히 알아보기](https://aka.ms/acat/m365cert)
