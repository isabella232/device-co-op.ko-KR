---
keywords: adobe experience cloud;Adobe Experience Cloud;device co-op;Device Co-op;수명 종료
solution: Adobe Experience Cloud
title: Device Co-op 사용 종료 FAQ
description: 장치 Co-op의 수명 종료 계획에 대해 알아봅니다.
source-git-commit: b9e21ba2f749b7a4ad69c122e2273b7f3309da58
workflow-type: tm+mt
source-wordcount: '1017'
ht-degree: 2%

---

# Device Co-op 사용 종료 FAQ

이 문서에서는 Adobe Experience Cloud Device Co-op 수명 종료(EOL) 계획에 대해 자주 묻는 질문에 대한 답변을 제공합니다. 이 계획이 실행되면 Adobe은 [Experience Cloud 릴리스 노트](https://experienceleague.adobe.com/docs/release-notes/experience-cloud/current.html) 및 [우선 순위 제품 업데이트](https://www.adobe.com/kr/subscription/priority-product-update.html)에 고급 알림을 제공합니다.

## FAQ

다음은 [!DNL Device Co-op] EOL 계획에 대해 자주 묻는 질문에 대한 답변 목록입니다.

## [!DNL Device Co-op]이 더 이상 사용되지 않는 이유는 무엇입니까?

AdTech 환경에서 예정된 변경 사항은 앞으로 [!DNL Device Co-op]이 더 이상 쓸모가 없는 솔루션이 될 것으로 예상됩니다. [!DNL Device Co-op] 는 대부분 타사 쿠키로 구성되며,  [!DNL Google's] 2022년까지 타사 쿠키를 차단한다는  [!DNL Google Chrome] 발표가 있으면  [!DNL Device Co-op]의 효율성이 저하됩니다. [!DNL Chrome] 에는 브라우저 시장 공유의 65%가 포함되어 있으며 기타 주요 브라우저는 이미 타사 쿠키 차단을 구현했습니다. [!DNL Chrome]이 타사 쿠키를 차단하면 대부분의 타사 쿠키가 차단되고 [!DNL Device Co-op]이(가) 더 이상 사용되지 않습니다.

## Adobe이 지금 [!DNL Device Co-op] 등록을 종료하는 이유는 무엇입니까?

타사 쿠키와 관련한 예정된 업계 변화로 인해 고객 기대를 충족하지 못할 위험을 방지하기 위해 등록이 종료됩니다. [!DNL Device Co-op] 준비하는 데 몇 달이 걸리고 서비스에서 가치를 추출하는 데 몇 달이 걸립니다. 이 시점에서 추가로 등록하면 브랜드에 [!DNL Device Co-op] 전체 값이 표시되지 않을 수 있습니다.

## 신규 고객이 등록할 수 있습니까?

2021년 6월 11일부터 Adobe은 더 이상 [!DNL Device Co-op]에 대한 새 가입을 수락하지 않습니다.

## 기존 계약이 갱신됩니까?

2021년 6월 11일부터 Adobe은 더 이상 [!DNL Device Co-op] 계약을 갱신하지 않습니다. [!DNL Device Co-op] 서비스를 계속 사용하려면 프로그램이 종료될 때까지 현재 사용 약관에 따라 계속 사용할 수 있습니다.

## [!DNL Device Co-op] 프로그램의 정확한 종료 날짜는 언제입니까?

[!DNL Device Co-op] 프로그램은 2022년에 종료됩니다. 특정 시간 및 날짜는 [!DNL Google]이 타사 쿠키를 차단하는 시작 시기에 따라 다릅니다.

## Device Co-op 수명 종료 시 어떤 애플리케이션이 영향을 받습니까?

다음 응용 프로그램은 [!DNL Device Co-op] 수명 종료 절차의 영향을 받습니다.

- [Adobe Analytics](https://experienceleague.adobe.com/docs/analytics.html?lang=en)
- [Adobe Audience Manager](https://experienceleague.adobe.com/docs/audience-manager/user-guide/overview/aam-overview.html?lang=en)
- [Adobe Advertising Cloud](https://experienceleague.adobe.com/docs/advertising-cloud.html?lang=en)
- [Adobe Target](https://experienceleague.adobe.com/docs/target/using/introduction/intro.html?lang=en)

## [!DNL Device Co-op]에 대한 대안으로 어떤 옵션이 있습니까?

### [!DNL Analytics]

[!DNL Analytics] [Cross-Device Analytics(CDA)](https://experienceleague.adobe.com/docs/analytics/components/cda/overview.html) 기능은 Adobe Experience Platform Identity 서비스 [Private Graph](https://experienceleague.adobe.com/docs/analytics/components/cda/device-graph.html?lang=en) 및 [필드 기반 결합](https://experienceleague.adobe.com/docs/analytics/components/cda/field-based-stitching.html?lang=en)을 모두 지원하므로 사용할 수 있습니다.

### [!DNL Audience Manager]

[!DNL Audience Manager] 을 활용하려면 그래프 파트너와의 상업적 관계를 직접 설정해야 하지만  [!DNL LiveRamp] 및  [!DNL Tapad]을 비롯한 타사 장치 그래프 파트너와의 통합을 유지 관리합니다. 이 경우 그래프 파트너와의 상업적 관계를 직접 설정해야  [!DNL Audience Manager]합니다.

### [!DNL Real-time Customer Data Platform]

현재 [!DNL Audience Manager Data Management Platform](DMP)을 수정할 계획이 없습니다. 그러나 타사 쿠키를 사용하지 않으면 대부분의 DMP 사용자에게 대규모 문제가 발생할 수 있습니다. 고객이 데이터 관리 방식을 발전시킬 수 있도록 지원하기 위해 Adobe은 향후 제한 사항에 직면하게 될 식별자에 대한 종속성을 줄이도록 권장하고 있습니다. 마케팅 팀은 [!DNL Real-time Customer Data Platform](실시간 CDP)로 해결할 수 있는 PII(개인 식별 정보)를 포함하는 영구 식별자를 기반으로 하는 자사 데이터 전략을 구축해야 합니다.

[!DNL Real-time CDP] 대상을 만들 수 있는 식별자 세트를 PII를 포함하도록 확장하여 타사 쿠키 및 장치 ID에 대한 종속성을 줄입니다. [!DNL Real-time CDP]의 기본 사항은 실시간 고객 프로필입니다. 이 프로필은 개인 특성 데이터와 행동 데이터를 실시간으로 결합하고 마케터가 특허를 획득한 데이터 거버넌스 제어를 사용하여 풍부한 대상 세그먼트를 만들 수 있도록 합니다. [!DNL Audience Manager] 과 마찬가지로, [!DNL Real-time CDP]은(는) 통찰력 및 개인화 사용 사례를 강화하지만 보다 세부적인 개인 수준 인사이트를 생성하고 유료 미디어, 소셜 미디어, 이메일 및 고객 시스템을 포함한 광고 기술 및 마케팅 기술에 걸쳐 대상을 광범위한 대상으로 대상을 활성화할 수도 있습니다.

[!DNL Real-time CDP] 또한  [Adobe Experience Platform 세그먼트 일치(알파)](https://experienceleague.adobe.com/docs/experience-platform/segmentation/ui/segment-match.html?lang=en)에 대한 액세스 권한을 포함하게 되므로 브랜드는 파트너십을 통해 자사 데이터 세트를 확장하고 통찰력과 개인화를 향상시킬 수 있습니다.

### [!DNL Target]

현재 [!DNL Target] 에는 Adobe의 고객 ID와 유사하게 작동하는 `mbox3rdPartyId`라는 결정론적 교차 장치 ID 결합 기능을 제공하므로 사용할 수 있는 대체 요소가 없습니다. [!DNL Target] 이 기능을 사용하면 [!DNL Target] 고객이 [!DNL Target] 테스트 및 개인화가 인바운드 채널에서 수행되는 동안 프로필 및 활동 기여도를 병합할 수 있습니다.

### Adobe Advertising Cloud

[!DNL Advertising Cloud] 고객은 더 이상 교차 장치 대상 타깃팅 및 측정 [!DNL Device Co-op] 에 을 사용할 수 없습니다. [!DNL Advertising Cloud]을 사용하면 Adobe의 [!DNL Device Graph] 파트너 관계를 [!DNL LiveRamp]와 활용하여 [!DNL LiveRamp’s] 기능 및 규모에 따라 이러한 기능을 계속 수행할 수 있습니다. [!DNL Device Co-op]을 사용 중인 캠페인을 종료하도록 허용했다가 [!DNL LiveRamp] 장치 그래프 제공자로 전환하거나 더 이상 사용자 기반 타깃팅을 활용하지 않도록 해야 합니다.

## 쿠키가 없는 미래를 준비하는 데 도움이 되는 기존 기능 및 구현은 무엇입니까?

기존 방문자 ID 서비스 구현에서 Analytics [CDA](https://experienceleague.adobe.com/docs/analytics/components/cda/overview.html)를 지원합니다. 기존 선언된 ID가 해시된 이메일인 경우 다음 기능을 수행하는 데 사용할 수 있습니다.

- [!DNL Audience Manager] [사용자 기반 대상](https://experienceleague.adobe.com/docs/audience-manager/user-guide/features/destinations/people-based/people-based-destinations-overview.html).
- [Experience Platform 세그먼트 일치(알파)](https://experienceleague.adobe.com/docs/experience-platform/segmentation/ui/segment-match.html?lang=en).

## 데이터를 [!DNL Device Co-op]에서 보관해야 합니까?

[!DNL Audience Manager] 및 [!DNL Advertising Cloud] 사용자의 경우 [!DNL Device Co-op]의 데이터를 타사 그래프로 전송할 수 없습니다. [!DNL Device Co-op] 데이터는 필드 기반 결합으로  [!DNL Analytics Ultimate] 전환하는 CDA를 사용하는  [!DNL Device Co-op] 사용자에게만 마이그레이션됩니다. 다른 모든 솔루션에는 해당 데이터가 마이그레이션되지 않습니다.

## 다른 기능을 반드시 채택해야 합니까?

다른 Adobe 기능을 채택하는 것이 필수는 아니지만 [!DNL Device Co-op] 사용 중단 전에 시간과 적절한 조정을 허용하려면 가능한 한 빨리 다른 기능 구현을 시작해야 합니다.

## 선택한다면 대체 솔루션을 언제 채택해야 합니까?

다른 기능을 채택하는 것은 필수가 아닙니다. [!DNL Device Co-op]에서 지정한 사용 사례 주소를 계속 지정하려는 경우에만 권장합니다. 다른 기능을 채택하도록 선택하는 경우 [!DNL Device Co-op] 프로그램이 종료되기 전에 2022년까지(정확히 알릴 수 있는 시기)에 맞춰 해야 합니다.

## 입양이 얼마나 걸릴까요?

이 작업은 기능에 따라 다릅니다. 예를 들어, [!DNL Device Co-op]과 함께 교차 장치 분석을 사용하는 Analytics Ultimate 고객이 실시간 개인 장치 그래프 또는 필드 기반 결합으로 마이그레이션해야 하는 경우 채택에 시간이 다소 걸릴 수 있습니다.