---
description: Adobe Target 활동에서 Device Co-op 데이터를 사용하는 방법을 알아봅니다.
seo-description: Learn how to use Device Co-op data in Adobe Target activities.
seo-title: Target - A/B tests, multivariate tests, and experience targeting
title: Target - A/B 테스트, 다변량 테스트 및 경험 타기팅
uuid: c1b478a4-812e-41ee-913f-29666c5c7ec4
exl-id: 6e630adf-faff-4fe4-b560-febd59964a5f
source-git-commit: 573744525fcc00f35540af9ffec46530111940ed
workflow-type: tm+mt
source-wordcount: '566'
ht-degree: 0%

---

# Target - A/B 테스트, 다변량 테스트 및 경험 타기팅{#target-a-b-tests-multivariate-tests-and-experience-targeting}

Adobe Target 활동에서 Device Co-op 데이터를 사용하는 방법을 알아봅니다.

A/B 테스트, 다변량(MVT) 테스트 및 경험 타깃팅 활동에서 Device Co-op 데이터를 사용할 수 있습니다. Device Co-op 선택 사항은 에서 활동을 생성하는 동안 사용할 수 있습니다. [!DNL Goals & Settings] 페이지의 [!DNL Target] 안내가 있는 3단계 워크플로.

Automated Personalization 활동, 권장 사항 활동 또는 를 사용하는 활동에서는 Device Co-op 데이터를 사용할 수 없습니다. [!DNL Adobe Analytics] 를 보고 소스로 사용(다음 작업 수행) [!DNL Target] 및 [!DNL Analytics] 통합(A4T)이라고도 합니다.

>[!NOTE]
>
>필요한 버전이 있는지 확인합니다. `mbox.js`. 의 모든 버전을 사용할 수 있습니다 `at.js`. 자세한 내용은 [멤버십 요구 사항](../about/requirements.md#concept-31d3d165d22546afbedf023d32ad3a43).

## 장치에 관계없이 관련 콘텐츠 전달 {#section-bba8d41e96914c82a6d267a54f776354}

마케터는 방문자가 현재 회사 또는 브랜드와 상호 작용하기 위해 사용 중인 장치에 관계없이 각 방문자에게 가장 관련성이 높은 경험을 전달하려고 합니다.

사용자는 회사 노트북, 가정용 컴퓨터, iPad, iPhone, 다양한 브라우저 등 다양한 장치에서 동일한 회사 또는 브랜드와 상호 작용합니다. 이전에 다른 디바이스 또는 브라우저에서 브랜드와 상호 작용한 적이 있는 동일한 사람이 각 특정 디바이스 또는 브라우저를 사용하고 있음을 인식할 수 없는 경우 해당 사람에게 일관되고 타깃팅된 경험을 제공할 수 없습니다.

Device Co-op을 사용하면 사용자의 다양한 장치를 동일한 사용자가 사용하는 것으로 식별할 수 있습니다. 해당 사용자가 다음 항목이 있는 페이지를 볼 때 [!DNL Target] 활동(활동 또는 타겟팅된 콘텐츠) [!DNL Target] 는 사용자가 다른 디바이스에서 본 것과 동일한 경험을 보도록 할 수 있습니다.

## 방문자 대신 사람별로 Target 활동 분석 {#section-c25cf4f8483942d7836d60756235e62c}

마케터는 분석하기를 원합니다 [!DNL Target] 활동은 &quot;방문자&quot; 대신 &quot;사람&quot;으로 표시됩니다.

각 사용자는 장치 및 브라우저에서 동일한 회사 또는 브랜드와 상호 작용할 가능성이 있지만, Device Co-op가 없을 경우에서 각 개별 장치 또는 브라우저는 별도의 &quot;방문자&quot;로 간주됩니다 [!DNL Target] 보고서.

개별 디바이스 및 브라우저별로 보고서를 보면 회사 또는 브랜드와 상호 작용하는 다양한 사용자 수보다 &quot;방문자&quot; 수가 더 많이 증가합니다. 이러한 사람들은 일반적으로 이러한 다양한 디바이스 및 브라우저에서 한 번만 전환하므로, 단일 전환에 대해 더 많은 &quot;방문자&quot;가 계산되므로, 전환율은 실제보다 낮을 것입니다.

Device Co-op을 사용하면, 콘텐츠 전달 및 보고가 &quot;사람&quot; 수준에서 수행되므로 보고서는 활동을 본 다른 사람의 수와 전환한 사람의 수를 정확하게 보여 줍니다.

Device Co-op 데이터가 없으면 특정 활동이 우승자라고 결정할 수 있습니다. 하지만, Device Co-op를 통한 보고가 더 정확하기 때문에 다른 활동이 실제로 전환율이 더 높을 수 있으므로 우승자가 될 수 있습니다.

이 개념에 대한 자세한 내용은 [Analytics: 사용자 지표](../other-solutions/people.md#concept-8c57cd3904974e078d7fbf84ac9c2d63).

## 활동당 Device Co-op 데이터 사용 {#section-fb46fae482654023abb1a1e26564db9a}

마케터는 활동당 Device Co-op 데이터를 사용하도록 선택할 수 있습니다. 확실하 [!DNL Target] 활동은 다음과 같이 Device Co-op 데이터에 적합하지 않을 수 있습니다.

* iPad의 사용자에게 적합한 특정 콘텐츠.

   iPad에서 경험을 처음 보는 사용자는 홈 컴퓨터에서 해당 경험을 계속 볼 수 있습니다.

* 엄격한 방문자에게만 제공되는 금리 오퍼입니다.
* 특정 상태에서만 광고를 할 수 있는 제품(예: 라이선스 제한이 있는 보험 증권).

마케터가에서 대상을 만들 때 [!DNL Target]대상자가 Device Co-op 데이터 사용 활동에 적합하지 않으면 경고 메시지가 표시됩니다. 적절한 대상에는 모든 방문자, 새 방문자 및 재방문자가 포함됩니다.
