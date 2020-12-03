---
description: Adobe Target 활동에서 Device Co-op 데이터를 사용하는 방법을 알아봅니다.
seo-description: Adobe Target 활동에서 Device Co-op 데이터를 사용하는 방법을 알아봅니다.
seo-title: Target - A/B 테스트, 다변량 테스트 및 경험 타깃팅
title: Target - A/B 테스트, 다변량 테스트 및 경험 타깃팅
uuid: c1b478a4-812e-41ee-913f-29666c5c7ec4
translation-type: tm+mt
source-git-commit: c1d0bc05d3f211fa3e899e98fbcc908be7399031
workflow-type: tm+mt
source-wordcount: '586'
ht-degree: 0%

---


# Target - A/B 테스트, 다변량 테스트 및 경험 타깃팅{#target-a-b-tests-multivariate-tests-and-experience-targeting}

Adobe Target 활동에서 Device Co-op 데이터를 사용하는 방법을 알아봅니다.

A/B 테스트, MVT(다변수) 테스트 및 경험 타깃팅 활동에서 장치 협력 데이터를 사용할 수 있습니다. The Device Co-op option is available during activity creation on the [!DNL Goals & Settings] page in the [!DNL Target] three-step guided workflow.

보고 소스로 사용하는 Automated Personalization 활동, 권장 사항 활동 또는 활동 [!DNL Adobe Analytics] 에 장치 협력 데이터를 사용할 수 없습니다(A4T로 알려진 [!DNL Target] 및 [!DNL Analytics] 통합).

>[!NOTE]
>
>필요한 버전의 가 있는지 확인합니다 `mbox.js`. 어떤 버전의 버전이든 사용할 수 있습니다 `at.js`. 자세한 내용은 [멤버십 요구 사항을 참조하십시오](../about/requirements.md#concept-31d3d165d22546afbedf023d32ad3a43).

## 디바이스에 상관없이 연관성 있는 컨텐츠 전달 {#section-bba8d41e96914c82a6d267a54f776354}

마케터는 방문자가 회사 또는 브랜드와 상호 작용하기 위해 현재 사용하고 있는 장치에 상관없이 각 방문자에게 가장 연관성 높은 경험을 전달하고자 합니다.

사용자는 다양한 장치에서 동일한 회사 또는 브랜드와 상호 작용합니다.랩탑, 가정용 컴퓨터, iPad, iPhone, 다양한 브라우저 등을 사용할 수 있습니다. 다른 장치 또는 브라우저에서 이전에 브랜드와 상호 작용한 동일한 사용자가 각각의 특정 장치나 브라우저를 사용하고 있다는 사실을 인식할 수 없는 경우 해당 사용자에게 일관되고 타깃팅된 경험을 제공할 수 없습니다.

Device Co-op을 사용하면 사용자의 다양한 장치를 동일한 사용자가 사용하고 있는 것으로 식별할 수 있습니다. 사용자가 [!DNL Target] 활동(활동 또는 타깃팅된 컨텐츠)이 있는 페이지를 보게 되면 [!DNL Target] 사용자가 다른 장치에서 보는 것과 동일한 경험을 보게 될 수 있습니다.

## 방문자가 아닌 사람별 Target 활동 분석 {#section-c25cf4f8483942d7836d60756235e62c}

마케터는 &quot;방문자&quot; 대신 &quot;사람&quot;별로 활동을 분석하기를 원합니다. [!DNL Target]

장치 및 브라우저에서 각 사용자가 동일한 회사 또는 브랜드와 상호 작용할 가능성이 있지만, 장치 협력 없이도 각 개별 장치 또는 브라우저는 보고서에서 별도의 &quot;방문자&quot;로 간주됩니다. [!DNL Target]

개별 장치 및 브라우저별 보고서를 보면 &quot;방문자&quot; 수가 회사 또는 브랜드와 상호 작용하는 다른 사람의 수보다 더 높은 수로 부풀려집니다. 이러한 사람들은 일반적으로 이러한 다양한 장치 및 브라우저에서 한 번만 전환하므로 단일 전환에 대해 더 많은 &quot;방문자&quot;가 카운트되기 때문에 전환율이 실제보다 낮아집니다.

Device Co-op을 사용하면 컨텐츠 전달 및 보고는 &quot;사람&quot; 수준에서 수행되므로 보고서는 얼마나 많은 다른 사람들이 활동을 보았는지 및 얼마나 많은 사람들이 전환했는지를 정확하게 보여줍니다.

Device Co-op 데이터가 없으면 특정 활동이 우승자임을 확인할 수 있습니다.그러나 Device Co-op에서 보고가 더 정확하므로 다른 활동이 실제로 더 높은 전환율을 가질 수 있으므로 우승자가 될 수 있습니다.

이 개념에 대한 자세한 내용은 [분석을 참조하십시오.사람 지표](../other-solutions/people.md#concept-8c57cd3904974e078d7fbf84ac9c2d63).

## 활동당 장치 협력 데이터 사용 {#section-fb46fae482654023abb1a1e26564db9a}

마케터는 활동당 장치 협력 데이터를 사용하도록 선택할 수 있습니다. 다음과 같은 특정 [!DNL Target] 활동이 장치 협력 데이터에 적합하지 않을 수 있습니다.

* iPad 사용자에게 적합한 특정 내용.

   iPad에서 경험을 처음 보는 사용자는 홈 컴퓨터에서 해당 경험을 계속 볼 수 있습니다.

* 엄격한 방문자 세그먼트에서만 사용할 수 있는 이자율 오퍼입니다.
* 특정 상태에서만 광고를 할 수 있는 제품(예: 라이센스 제한이 있는 보험 정책)

마케터가 대상을 만들 때 [!DNL Target]대상이 Device Co-op 데이터 지원 활동에 적합하지 않으면 경고가 표시됩니다. 적절한 대상에는 모든 방문자, 새 방문자 및 돌아온 방문자가 포함됩니다.
