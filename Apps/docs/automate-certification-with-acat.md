---
title: Microsoft 365 App Compliance Automation Tool을 사용하여 Microsoft 365 인증 자동화
description: ACAT(Microsoft 365용 앱 준수 자동화 도구)를 사용하여 Microsoft 365 인증을 자동화합니다.
author: yjin81
ms.author: yajin1
manager: zhshang
ms.service: certification
ms.topic: how-to
ms.date: 04/13/2022
ms.custom: template-how-to
ms.openlocfilehash: c81ccf3626d6039333f52a487e98233364f7174e
ms.sourcegitcommit: 785d1c5d829e44e0ad696b85c92be81f549b989e
ms.translationtype: MT
ms.contentlocale: ko-KR
ms.lasthandoff: 05/17/2022
ms.locfileid: "65433499"
---
# <a name="automate-microsoft-365-certification-with-app-compliance-automation-tool-for-microsoft-365"></a>Microsoft 365 App Compliance Automation Tool을 사용하여 Microsoft 365 인증 자동화

ACAT(Microsoft 365 앱 준수 자동화 도구)는 Microsoft 365 앱 준수 프로그램과 협력하여 Microsoft 365 인증에 필요한 몇 가지 컨트롤을 충족합니다. 이 문서는 ACAT를 시작하고 Microsoft 365 인증과 함께 준수 평가를 사용하는 데 도움이 됩니다.

> [!IMPORTANT]
> ACAT는 현재 비공개 미리 보기로 제공됩니다. 프라이빗 미리 보기 프로그램에 참여하려면 [여기에서](https://aka.ms/acat/private/signup) 등록하세요.

## <a name="create-your-first-compliance-report-to-onboard-acat"></a>ACAT를 온보딩하는 첫 번째 준수 보고서 만들기

ACAT를 사용하면 애플리케이션의 규정 준수 또는 애플리케이션의 특정 환경(예: 프로덕션, 스테이징 등)에 집중할 수 있습니다. 이를 통해 애플리케이션의 클라우드 인프라 또는 애플리케이션의 특정 환경에 따라 규정 준수 경계를 정의할 수 있는 **규정 준수 보고서를** 만들 수 있습니다.

> [!IMPORTANT]
> ACAT는 프라이빗 미리 보기에 있으므로 직접 검색할 *https://portal.azure.com* 수 없습니다. ACAT를 시작하려면 아래 옵션을 사용하세요.

- ***Azure Portal Microsoft 365 앱 준수 자동화 도구를*** 검색하고 시작하거나 [ACAT의 딥 링크를](https://portal.azure.com/#blade/Microsoft_Azure_AppComplianceAutomation/AcatMenuBlade/overview) 사용하여 직접 시작합니다.[](https://portal.azure.com/?microsoft_azure_appcomplianceautomation_assettypeoptions=%7B%22AppComplianceAutomation%22:%7B%22options%22:%22%22%7D%7D&microsoft_azure_marketplace_ItemHideKey=Microsoft_Azure_AppComplianceAutomationHidden)
- 왼쪽에서 ***보고서*** 로 이동합니다.

:::image type="complex" source="../media/ACAT/getstarted-create-report-inline.png" lightbox="../media/ACAT/getstarted-create-report.png" alt-text="준수 보고서 만들기":::
   보고서로 이동하여 새 준수 보고서 만들기 :::image-end:::

- ***새 보고서 만들기*** 를 선택하여 적절한 구성으로 첫 번째 준수 보고서를 만들기 시작합니다. 
    - **기본 사항**
        - **보고서 이름**: 준수 보고서의 이름이 필요하며 테넌트 내에서 복제할 수 없습니다. 숫자, 알파벳 및 밑줄의 조합일 수 있습니다. 예를 들어 특정 애플리케이션 또는 환경을 나타내는 규정 준수 보고서에 의미 있는 이름을 사용하는 것이 좋습니다.
        - **트리거 시간**: ACAT는 매일 준수 보고서에 대한 규정 준수 평가를 생성합니다. 이 구성은 생성을 트리거해야 하는 시기를 지정하는 데 사용됩니다. 
        - **구독 선택**: 프라이빗 미리 보기에서 ACAT를 사용하면 특정 구독에서 Azure 리소스를 선택하여 규정 준수 보고서의 범위를 정의할 수 있습니다. 클라우드 인프라에 따라 적절한 구독을 선택할 수 있습니다. 애플리케이션에 대한 구독이 목록에 없는 경우 관리자에게 권한을 요청해야 합니다. 
        - **리소스 선택**: 구독이 지정되면 클라우드 인프라에 따라 적절한 리소스를 선택합니다. 기본적으로 모든 리소스가 자동으로 선택됩니다. 필터(예: 리소스 그룹, 태그 등)로 리소스를 검색한 다음 리소스를 선택할 수도 있습니다. 
    
    :::image type="complex" source="../media/ACAT/getstarted-report-config-basic-inline.png" lightbox="../media/ACAT/getstarted-report-config-basic.png" alt-text="기본 구성":::
       규정 준수 보고서에 대한 기본 구성 :::image-end:::

    - **Microsoft 365 인증**: Microsoft 365 인증 구성은 만드는 동안 선택 사항입니다.  앱 게시를 시작하면 나중에 구성할 수 있습니다.
        - **제품 GUID**: 제품 GUID는 [Microsoft 파트너 네트워크의](https://partner.microsoft.com/dashboard) 마켓플레이스 제품에 대한 고유 식별자입니다. *자세한 내용을* 선택하여 고유 식별자를 가져오는 방법에 대한 단계별 지침을 가져옵니다.
    
    :::image type="complex" source="../media/ACAT/getstarted-report-config-m365-inline.png" lightbox="../media/ACAT/getstarted-report-config-m365.png" alt-text="Microsoft 365 인증 구성":::
       Microsoft 365 인증에 대한 구성:::image-end:::

구성을 확인하고 규정 준수 보고서를 만들면 ACAT는 아래 원본에서 규정 준수 관련 데이터를 자동으로 수집합니다. 

- 구독에 [대한 클라우드용 Microsoft Defender](https://azure.microsoft.com/services/defender-for-cloud/)(무료 계층)를 사용하도록 설정합니다. 
- 구독에 대한 일부 사용자 지정 정책을 사용하도록 설정합니다. 

> [!NOTE]
> 만들기에 성공하면 ACAT는 다음 날부터 준수 보고서에 대한 준수 평가를 수집하고 생성하기 시작합니다. 

## <a name="audit-the-compliance-assessments-with-your-compliance-report"></a>규정 준수 보고서를 사용하여 규정 준수 평가 감사

ACAT를 사용하면 규정 준수 보고서의 런타임 상태를 알아보고 규정 준수 평가를 쉽게 감사할 수 있습니다. 

- 왼쪽에서 ***보고서*** 로 이동합니다. 기존 규정 준수 보고서에 대한 간략한 요약을 얻을 수 있습니다.
    - **런타임 상태**: 런타임 상태는 ACAT가 마지막 세대에서 준수 보고서를 올바르게 관리하는지 여부를 나타냅니다. 런타임 상태에는 세 가지 상태가 있습니다. 
        - **활성**: 준수 보고서가 지속적으로 성공적으로 실행되고 있습니다. 
        - **실패**: ACAT가 마지막 세대에 대한 이 준수 보고서에 대한 규정 준수 평가를 생성하지 못했습니다. 이 상태는 여러 가지 이유로 발생할 수 있습니다. 예를 들어 구독에서 ACAT로 라우팅된 규정 준수 데이터를 차단하기 위한 구성이 잘못되었거나, ACAT에서 시스템 오류 또는 중단이 발생했습니다. 
        - **사용 안 함**: 이 준수 보고서는 수동으로 사용하지 않도록 설정(일시 중지)됩니다. 이 기능은 프라이빗 미리 보기에서 사용할 수 없습니다. 
    - **마지막 트리거 시간** 및 **다음 트리거 시간**: ACAT는 매일 준수 보고서에 대한 규정 준수 평가를 생성합니다. *마지막 트리거 시간은* 마지막 생성이 트리거된 시간을 나타내고 *, 다음 트리거 시간은* 다음 세대의 트리거 시간을 나타냅니다. 
    - **Microsoft 365 인증**: Microsoft 365 인증 컨트롤에 대한 준수 보고서의 상태를 이해합니다. Microsoft 365 인증 준수 상태의 세 가지 상태는 다음과 같습니다.
        - **전달됨**: 완전히 자동화된 Microsoft 365 인증 제어에 대한 오류는 없습니다.
        - **실패**: 완전히 자동화된 Microsoft 365 인증 컨트롤에 대한 고객 책임이 검색되지 않았습니다.
        - **수동**: 이 상태에는 ACAT에서 부분적으로 자동화되고 여전히 규정 준수 증거를 수집하기 위한 수동 노력이 필요한 *부분 자동화된 수동 제어* 와 규정 준수 증거를 수집하기 위한 모든 수동 노력이 필요한 *수동 제어* 라는 두 가지 종류의 컨트롤이 포함됩니다. ACAT는 부분적으로 자동화된 제어에 대한 고객 책임의 일부를 자동화합니다. 규정 준수 상태를 참조에 사용할 수 있지만 Microsoft 365 인증 감사에 직접 사용할 수는 없습니다.
    
    :::image type="complex" source="../media/ACAT/getstarted-report-list-inline.png" lightbox="../media/ACAT/getstarted-report-list.png" alt-text="준수 보고서 목록":::
       기존 준수 보고서 목록입니다.
    :::image-end:::

기존 규정 준수 보고서의 개략적인 요약을 학습하는 것 외에도 ACAT의 팀과 함께 규정 준수 평가 세부 정보를 감사할 수도 있습니다. 보고서 이름을 클릭하여 특정 준수 보고서에 대한 규정 준수 평가 세부 정보를 가져옵니다. ACAT는 아래와 같이 세부 정보를 표시합니다.

- **설정**: *설정* 사용하여 규정 준수 보고서의 구성을 변경할 수 있습니다. 프라이빗 미리 보기에서 Microsoft 365 인증 관련 구성을 변경할 수 있습니다. 
- **보고서 다운로드**: ACAT를 사용하면 공동 작업을 위해 파트너와 공유할 수 있는 형식으로 규정 준수 보고서의 평가를 csv 파일로 다운로드할 수 있습니다.
    - **클라우드 인프라 인벤토리**: 이 파일에는 이 준수 보고서의 리소스 세부 정보가 포함되어 있습니다. 애플리케이션의 클라우드 인벤토리를 설명하는 데 사용할 수 있습니다. 
    - **Microsoft 365 인증 준수 평가**: 이 파일에는 Microsoft 365 인증 제어 보기에서 규정 준수 보고서의 준수 평가가 포함되어 있습니다. 

:::image type="complex" source="../media/ACAT/getstarted-report-detail-toolbar-inline.png" lightbox="../media/ACAT/getstarted-report-detail-toolbar.png" alt-text="준수 보고서 도구 모음":::
    규정 준수 보고서에 대한 도구 모음입니다.
:::image-end:::

- **Essentials**: 이 섹션에서는 준수 보고서의 상태 및 구성을 나타냅니다. 

:::image type="complex" source="../media/ACAT/getstarted-report-detail-essential-inline.png" lightbox="../media/ACAT/getstarted-report-detail-essential.png" alt-text="규정 준수 보고서 필수 사항":::
    규정 준수 보고서의 필수 요소입니다.
:::image-end:::

- **평가 결과**
    - Microsoft 365 인증 제어의 준수 상태는 5가지 범주로 분류됩니다. 
        - **전달됨**: 완전히 자동화된 Microsoft 365 인증 제어에 대한 오류는 없습니다.
        - **실패**: 완전히 자동화된 Microsoft 365 인증 컨트롤에 대한 고객 책임이 검색되지 않았습니다.
        - **통과됨 - 추가 증거 필요**: 부분적으로 자동화된 Microsoft 365 인증 컨트롤에 대한 오류가 없습니다. 컨트롤에 대한 추가 증명 정보를 수동으로 수집해야 합니다.
        - **실패 - 추가 증명 필요**: 부분적으로 자동화된 Microsoft 365 인증 제어에 대한 고객 책임이 검색되지 않았습니다.
        - **수동 제어**: ACAT는 Microsoft 365 인증 컨트롤에 대한 고객의 책임을 자동화하지 않습니다. 
    - 규정 준수 평가는 Microsoft 365 인증 제어 제품군 및 제어에 의해 구성됩니다. 
        - 규정 준수 컨트롤의 세부 정보 및 컨트롤 이름을 클릭하여 수동 제어에 대한 규정 준수 증거를 수집하는 방법에 대해 자세히 알아봅니다. 
        - 완전히 자동화된 제어 및 부분적으로 자동화된 제어를 확장하면 해당 컨트롤의 고객 책임에 대한 규정 준수 세부 정보를 자세히 알아볼 수 있습니다. 
        - 각 고객 책임에 대해 작업 단추를 클릭하여 관련 리소스의 준수 상태 및 실패한 리소스에 대한 수정 단계를 검색할 수도 있습니다. 
            - **비정상 리소스**: 비정상 리소스를 수정하려면 수정 단계를 따라야 합니다. 
            - **해당되지 않는 리소스**: 리소스를 설정하는 N/A 이유를 따라야 하며 ACAT는 리소스에 대한 규정 준수 평가를 수집할 수 있습니다.

:::image type="complex" source="../media/ACAT/getstarted-report-detail-assessment-inline.png" lightbox="../media/ACAT/getstarted-report-detail-assessment.png" alt-text="준수 보고서 평가":::
    규정 준수 보고서에 대한 규정 준수 평가입니다.
:::image-end:::

## <a name="use-your-first-compliance-report-with-microsoft-r365-certification-audit"></a>Microsoft r365 인증 감사에서 첫 번째 규정 준수 보고서 사용

규정 준수 보고서를 Microsoft 365 인증과 함께 사용하기 전에 준수 보고서를 마켓플레이스 제품과 연결하도록 제품 GUID를 구성해야 합니다. 다음 두 가지 옵션이 있습니다. 

- 규정 준수 보고서를 만드는 동안 *Microsoft 365 인증* 탭에서 제품 GUID를 구성합니다. 
- 준수 보고서를 이미 만든 경우 이 준수 보고서의 *설정* 이동하여 제품 GUID를 구성합니다.

제품 GUID가 구성되면 [Microsoft 파트너 네트워크](https://partner.microsoft.com/dashboard) 로 이동하여 앱 준수를 시작합니다. *초기 설명서는* Microsoft 365 인증의 첫 번째 단계입니다. 이 단계에서 ACAT를 사용하는지 여부에 대한 질문에 *대해 예를* 선택하는 경우 이 감사에 대한 적절한 준수 보고서를 선택할 수 있습니다. Microsoft 365 인증은 완전히 자동화된 컨트롤의 규정 준수 평가를 감사관에게 자동으로 제출하여 시간과 노력을 절약합니다. 

## <a name="get-high-level-overview-of-your-compliance-reports"></a>규정 준수 보고서에 대한 개략적인 개요 가져오기 

***개요*** 를 통해 규정 준수 보고서에 대한 높은 수준의 상태를 더 잘 이해할 수 있습니다. 

- **준수 보고서 런타임 상태**: 이 개요는 규정 준수 보고서의 런타임 상태에 대한 통계를 제공합니다.
    - **활성**: 준수 보고서가 지속적으로 성공적으로 실행되고 있습니다. 
    - **실패**: ACAT가 마지막 세대에서 이 준수 보고서에 대한 규정 준수 평가를 생성하지 못했습니다. 이 상태는 여러 가지 이유로 발생할 수 있습니다. 예를 들어 구독에서 ACAT로 라우팅된 규정 준수 데이터를 차단하기 위한 구성이 잘못되었거나, ACAT에서 시스템 오류 또는 중단이 발생했습니다. 
    - **사용 안 함**: 이 준수 보고서는 수동으로 사용하지 않도록 설정(일시 중지)됩니다. 이 기능은 프라이빗 미리 보기에서 사용할 수 없습니다. 

:::image type="complex" source="../media/ACAT/getstarted-overview-runtime-inline.png" lightbox="../media/ACAT/getstarted-overview-runtime.png" alt-text="런타임 상태 개요":::
    준수 보고서 런타임 상태 개요입니다.
:::image-end:::

- **활성 규정 준수 보고서**: 이 개요는 각 *활성* 규정 준수 보고서에 대한 규정 준수 결과 통계를 제공합니다.
    - **전달됨**: 완전히 자동화된 Microsoft 365 인증 제어에 대한 오류는 없습니다.
    - **실패**: 완전히 자동화된 Microsoft 365 인증 컨트롤에 대한 고객 책임이 검색되지 않았습니다.
    - **수동**: 이 상태에는 ACAT에서 부분적으로 자동화되고 여전히 규정 준수 증거를 수집하기 위한 수동 노력이 필요한 *부분 자동화된 수동 제어* 와 규정 준수 증거를 수집하기 위한 모든 수동 노력이 필요한 *수동 제어* 라는 두 가지 종류의 컨트롤이 포함됩니다. ACAT는 부분적으로 자동화된 제어에 대한 고객 책임의 일부를 자동화합니다. 규정 준수 상태를 참조에 사용할 수 있지만 Microsoft 365 인증 감사에 직접 사용할 수는 없습니다.

:::image type="complex" source="../media/ACAT/getstarted-overview-compliance-inline.png" lightbox="../media/ACAT/getstarted-overview-compliance.png" alt-text="준수 상태 개요":::
    활성 규정 준수 보고서의 준수 상태 개요입니다.
:::image-end:::

## <a name="troubleshooting"></a>문제 해결 

### <a name="why-is-the-compliance-report-created-failed-due-to-authorization-error"></a>권한 부여 오류로 인해 규정 준수 보고서를 만들지 못한 이유는 무엇인가요? 

규정 준수 보고서를 만들 때 ACAT는 규정 준수 데이터를 자동으로 수집하도록 구독으로 환경을 설정하며, 이 작업을 수행하려면 구독에 대한 특정 권한이 필요합니다. 아래와 같이 구독 권한을 확인할 수 있습니다. 

- [Azure Portal](https://portal.azure.com/?microsoft_azure_appcomplianceautomation_assettypeoptions=%7B%22AppComplianceAutomation%22:%7B%22options%22:%22%22%7D%7D) **구독을** 검색하고 시작합니다.
- 준수 보고서를 만드는 데 사용할 구독으로 이동합니다. 
- 왼쪽의 **액세스 제어(IAM)** 로 이동합니다. 
- **내 액세스 권한 보기를** 선택하여 사용 권한을 확인합니다.
    - 조직 [에서 Azure 기본 제공 역할을](/azure/role-based-access-control/built-in-roles) 사용하는 경우 역할 할당에는 다음 역할 중 하나 이상이 포함되어야 합니다.
        - [리소스 정책 기여자](/azure/role-based-access-control/built-in-roles#resource-policy-contributor) 및 [보안 관리자](/azure/role-based-access-control/built-in-roles#security-admin)
        - 더 높은 권한이 있는 기타 역할 할당(예: [소유자](/azure/role-based-access-control/built-in-roles#owner) 등)

### <a name="how-to-report-an-acat-issue-or-warning"></a>ACAT 문제 또는 경고를 보고하는 방법 

ACAT에서 문제가 발생하고 [ACAT 프라이빗 미리 보기 프로그램에](mailto:acatprivatepreview@microsoft.com) 문의하여 도움을 받으려면 시나리오를 더 잘 이해하기 위해 증거를 수집하는 데 도움이 필요합니다.

- ACAT 오류 또는 경고의 세부 정보 가져오기
    - [Azure Portal](https://portal.azure.com/?microsoft_azure_appcomplianceautomation_assettypeoptions=%7B%22AppComplianceAutomation%22:%7B%22options%22:%22%22%7D%7D) 위에 있는 **알림** 으로 이동합니다.
    - **활동 로그에서 추가 이벤트** 선택 
    
    :::image type="complex" source="../media/ACAT/getstarted-troubleshoot-activitylog.png" alt-text="ACAT 알림":::
        활동 로그로 이동하여 ACAT 알림을 확인합니다.
    :::image-end:::
    
    - 활동 로그에서 ACAT 오류 또는 경고를 필터링하도록 **타임스팬** 을 올바르게 변경합니다. 
    - ACAT 오류 또는 경고를 찾아 세부 정보를 가져와서 세부 정보를 파일로 저장합니다.
    
- ACAT에서 구독을 올바르게 설정했는지 확인합니다. 
    - [Azure Portal](https://portal.azure.com/?microsoft_azure_appcomplianceautomation_assettypeoptions=%7B%22AppComplianceAutomation%22:%7B%22options%22:%22%22%7D%7D) **구독을** 검색하고 시작합니다.
    - 준수 보고서를 만드는 데 사용할 구독으로 이동합니다. 
    - **리소스 공급자** 를 선택하여 이러한 공급자의 상태가 *등록되었는지* 확인합니다.
        - Microsoft.Security
        - Microsoft.ResourceGraph
    - Azure Portal [돌아가기 Resource Graph](https://portal.azure.com/?microsoft_azure_appcomplianceautomation_assettypeoptions=%7B%22AppComplianceAutomation%22:%7B%22options%22:%22%22%7D%7D) **탐색기를 시작합니다**.
    - **새 쿼리** 선택
    - 이 쿼리를 실행하여 정책 할당을 확인하고 결과를 CSV로 다운로드합니다. 

    ```kusto
    resourcecontainers
    | where type == "microsoft.resources/subscriptions/resourcegroups"
    | where name contains "acat"
    ```

    - 이 쿼리를 실행하여 자동화를 확인하고 결과를 CSV로 다운로드합니다.

    ```kusto
    resources
    | where type == "microsoft.security/automations"
    | where name contains "acat"
    ```

    - 이 쿼리를 실행하여 평가를 확인하고 결과를 CSV로 다운로드합니다. 자리 표시자 ***your-subscriptionId*** 를 쿼리하려는 특정 구독으로 바꿔야 합니다.

    ```kusto
    SecurityResources
      | where type == 'microsoft.security/assessments'
      | where subscriptionId == "your-subscriptionId"
      | extend metadata=properties.metadata,
      status=properties.status,
      links=properties.links,
      displayName=properties.displayName,
      resourceDetails=properties.resourceDetails,
      description=properties.metadata.description
      | project type, id, name, description, metadata, status, resourceDetails, links, displayName
    ```