---
description: Adobe Target 활동에서 Device Co-op 데이터를 사용하는 방법을 알아봅니다.
seo-description: Adobe Target 활동에서 Device Co-op 데이터를 사용하는 방법을 알아봅니다.
seo-title: Target - A/B 테스트, 다변량 테스트 및 경험 타깃팅
title: Target - A/B 테스트, 다변량 테스트 및 경험 타깃팅
uuid: c1b478a4-812e-41ee-913f-29666c5c7ec4
translation-type: tm+mt
source-git-commit: c1d0bc05d3f211fa3e899e98fbcc908be7399031

---


# Target - A/B tests, multivariate tests, and experience targeting{#target-a-b-tests-multivariate-tests-and-experience-targeting}

Adobe Target 활동에서 Device Co-op 데이터를 사용하는 방법을 알아봅니다.

A/B 테스트, 다변수(MVT) 테스트 및 경험 타깃팅 활동에서 Device Co-op 데이터를 사용할 수 있습니다. The Device Co-op option is available during activity creation on the [!DNL Goals & Settings] page in the [!DNL Target] three-step guided workflow.

You cannot use Device Co-op data in Automated Personalization activities, Recommendation activities, or activities using [!DNL Adobe Analytics] as the reporting source (the [!DNL Target] and [!DNL Analytics] integration, known as A4T).

>[!NOTE]
>
>Ensure that you have the required version of `mbox.js`. 임의의 `at.js` 버전을 사용할 수 있습니다. 자세한 내용은 멤버십 [요구 사항을 참조하십시오](../about/requirements.md#concept-31d3d165d22546afbedf023d32ad3a43).

## Deliver relevant content regardless of the device {#section-bba8d41e96914c82a6d267a54f776354}

마케터는 방문자가 현재 회사나 브랜드와 상호 작용하는 데 사용 중인 장치에 상관없이 각 방문자에게 가장 적절한 환경을 제공하고 싶어 합니다.

사용자는 회사 랩톱, 집 컴퓨터, iPad, iPhone, 다양한 브라우저 등 서로 다른 많은 장치에서 동일한 회사나 브랜드와 상호 작용합니다. 각각의 특정 장치나 브라우저가 이전에 다른 장치나 브라우저에서 브랜드와 상호 작용한 동일한 사람에 의해 사용되고 있음을 인식할 수 없다면, 그 사람에게 일관되고 타깃팅된 환경을 제공할 수 없습니다.

Device Co-op를 사용하는 경우 사용자의 다양한 장치를 동일한 사용자가 사용하는 것으로 식별할 수 있습니다. When that user sees a page with [!DNL Target] activities—either activities or targeted content— [!DNL Target] can ensure that the user sees the same experience seen on another device.

## Analyze Target activities by people instead of by visitors {#section-c25cf4f8483942d7836d60756235e62c}

Marketers want to analyze [!DNL Target] activities by “people” instead of “visitors.”

Each person is likely interacting with the same company or brand across devices and browsers, but without the Device Co-op, each individual device or browser is considered a separate “visitor” in [!DNL Target] reports.

개별 장치와 브라우저별 보고서를 보면 &quot;방문자&quot; 수가 해당 회사나 브랜드와 상호 작용하는 서로 다른 사람의 수보다 높은 수로 부풀려집니다. 이러한 사람들은 일반적으로 이렇게 다양한 장치와 브라우저 간에 한 번만 전환하며, 따라서 더 많은 &quot;방문자&quot;가 하나의 전환에 대해 계산되므로 실제 전환율은 더 낮습니다.

Device Co-op를 사용할 경우 컨텐츠 제공과 보고는 &quot;사람&quot; 수준에서 수행되며, 따라서 보고서는 활동을 본 서로 다른 사람의 수와 전환된 사람의 수를 정확하게 보여줍니다.

Device Co-op 데이터를 사용하지 않을 경우 특정 활동이 우승자가 되는 것으로 파악될 수 있습니다. 하지만 Device Co-op를 사용하는 보고가 더 정확하므로 사실 다른 활동의 전환율이 더 클 수 있고, 따라서 이 활동이 우승자가 될 수 있습니다.

이 개념에 대한 자세한 내용은 Analytics [:사람 지표](../other-solutions/people.md#concept-8c57cd3904974e078d7fbf84ac9c2d63).

## Use Device Co-op data per activity {#section-fb46fae482654023abb1a1e26564db9a}

마케터는 활동에 Device Co-op 데이터를 사용하도록 선택할 수 있습니다. Certain [!DNL Target] activities might not be appropriate for Device Co-op data, such as:

* iPad 사용자에게 적절한 특정 컨텐츠.

   먼저 iPad에서 어떤 환경을 보는 사용자는 집 컴퓨터에서 해당 환경을 계속 보게 됩니다.

* 엄격한 방문자 세그먼트에 대해서만 사용 가능한 제공 금리.
* 특정 상태에서만 광고할 수 있는 제품(예: 라이선스 제한이 있는 보험 정책).

When marketers create audiences in [!DNL Target], they are alerted if the audience is not appropriate for Device Co-op data-enabled activities. 적절한 대상에는 모든 방문자, 새 방문자 및 재방문자가 포함됩니다.
