---
title: 게시자 Attestation이란?
author: LGerrard
ms.author: legerrar
description: Publisher Attestation 프로그램에 대한 자세한 정보
keywords: 앱 증명 인증 365 설문지 앱소싱 게시자
ms.topic: conceptual
ms.service: attestation
ms.openlocfilehash: 44ccc49f229ac6881d6626b7e3b63f83100b8227
ms.sourcegitcommit: e97156a6eaf1d5ec5c26fd14add210a92bacd944
ms.translationtype: MT
ms.contentlocale: ko-KR
ms.lasthandoff: 04/28/2021
ms.locfileid: "52071327"
---
# <a name="what-is-publisher-attestation"></a>게시자 Attestation이란?

게시자 Attestation은 Microsoft 365 앱 준수 프로그램의 다음 계층입니다. 앱 개발자는 앱의 보안 및 규정 준수를 평가할 때 고객 또는 IT 관리자가 자주 묻는 질문이 포함된 자체 평가를 완료하도록 요청합니다. 그런 다음 Microsoft는 보다 쉽고 시기적인 평가를 위해 이 정보를 게시합니다.

> [!IMPORTANT]
> Microsoft는 제공된 정보의 유효성을 검사하지 않습니다. 앱 개발자는 게시 에세이션에서 제공하는 정보에 대해 전적으로 책임을 져야 합니다. 

게시자 Attestation은 다음 Microsoft 플랫폼과 통합되는 앱에 적용됩니다.
- Teams
- Word
- Excel
- PowerPoint 
- Outlook
- SharePoint
- Project
- OneNote

### <a name="benefits-for-it-admins"></a>IT 관리자를 위한 혜택
IT 관리자를 위한 게시자 Attestation을 완료하면의 이점은 다음과 같습니다.
-   조직에서 사용하도록 설정된 응용 프로그램의 보안 및 규정 준수 조치에 대한 신뢰도 추가
-   앱의 보안 및 규정 준수 자세를 검토하는 데 들이는 시간 단축

### <a name="benefits-for-app-developers"></a>앱 개발자를 위한 이점 
개발자를 위한 Publisher Attestation을 완료하면 다음과 같은 이점이 있습니다. 
-   시간 절약. 자주 묻는 질문에 대한 자세한 내용은 앱의 Microsoft Docs 페이지 보기
-   엔터프라이즈 조직의 보안 및 규정 준수 내부 검토 타임라인 가속화
-   투명도 증가
- Microsoft는 추가 비용 없는 이 서비스를 제공합니다.
-   스토어의 다른 앱과의 차별화
-   AppSource의 항목에서 docs 페이지로 연결
-   Microsoft 365 인증 시작 자격


## <a name="publisher-attestation-scope"></a>게시자 Attestation 범위

설명 프로세스는 앱의 보안, 데이터 처리 및 규정 준수 특성을 자세히 설명하는 광범위한 설문 조사를 중심으로 합니다. 제공된 정보는 조직의 Microsoft 365 플랫폼에서 앱이 활성화될 때 노출되는 전체 앱 기능에 대해 설명하고 다음을 포함합니다.

- 데이터 처리: 앱이 조직 데이터를 수집 및 저장하는 방법 및 조직이 해당 데이터에 대한 제어를 제어하는 방법
- 보안: 앱이 데이터를 보호하고 사이버 공격을 감지 및 재개해야 하는 프로토콜, 프로세스 및 절차
- 규정 준수: 앱이 필수 산업 표준 및 사양을 준수합니다.
- 법적: 앱의 적용 가능한 입법 규정 준수 및 규정

### <a name="confirmation-criteria"></a>확인 조건

이 설명은 Microsoft Cloud App Security로 식별된 80개 이상의 위험 요인에 대해 앱의 보안, 데이터 처리 및 규정 준수 [관행을 반영합니다.](https://www.microsoft.com/microsoft-365/enterprise-mobility-security/cloud-app-security) 초기 테스트 설명서 제출이 기본 일관성 테스트 조건에 실패하면 응용 프로그램이 승인되지 않습니다. 승인 후 설명서 제출 또는 앱 실패가 보고되거나 검색된 경우 확정 확인 상태가 다시 사용되지 않습니다. 어느 경우든 개발자는 수정 프로세스를 지원하기 위해 관련성 있는 자세한 정보를 받게 됩니다.

### <a name="confirmation-time-frame"></a>확인 시간 프레임

의거는 제출 시간부터 1년 동안 유효합니다. 그러나 중간 기간 동안 앱이 업데이트 또는 수정되는 경우 개발자는 의거를 수정하고 다시 제출해야 합니다.

## <a name="reviewing-an-apps-publisher-attestation"></a>앱의 게시자 Attestation 검토

개발자는 앱에 대해 만든 Microsoft docs 페이지에서 앱의 Publisher Attestation 결과에 대한 자세한 정보를 검토할 수 있습니다. 게시자 증명 또는 Microsoft 365 인증을 완료한 모든 앱이 나열되고, 각 목록에는 준수 프로그램의 달성된 수준이 명확하게 표시됩니다.

**Publisher Attestation을 완료한 앱의 예는 [MIPA](https://docs.microsoft.com/microsoft-365-app-certification/teams/iglobe-mipa-your-personal-assistant?pivots=mcas) 목록을 참조하세요.** 

## <a name="learn-more"></a>자세한 정보

* [Microsoft 365 앱 준수 프로그램 개요](~/overview.md)
* [게시자 확인](https://docs.microsoft.com/azure/active-directory/develop/publisher-verification-overview)
* [게시자 Attestation 완료](~/docs/attestation.md)  
* [Microsoft 365 인증이란? ](~/docs/enterprise-app-certification-guide.md)
