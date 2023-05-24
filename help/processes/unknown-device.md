---
description: 사용자가 귀하의 브랜드와 상호 작용하는 데 사용되지 않는 장치를 가지고 있는 경우 해당 장치를 알 수 없는 장치라고 합니다.
seo-description: When a person has devices that are not used to interact with your brand, those devices are called unknown devices.
seo-title: Unknown devices
title: 알 수 없는 장치
uuid: 18e69dad-bdb3-4ac1-a690-374aba1aa0a6
exl-id: 7841bf32-7327-4981-86a2-600e2bfe5901
source-git-commit: 573744525fcc00f35540af9ffec46530111940ed
workflow-type: tm+mt
source-wordcount: '227'
ht-degree: 0%

---

# 알 수 없는 장치{#unknown-devices}

사용자가 귀하의 브랜드와 상호 작용하는 데 사용되지 않는 장치를 가지고 있는 경우 해당 장치를 알 수 없는 장치라고 합니다.

## 알 수 없는 장치 범주 {#section-014b83fd0f2e4d50aa19dd9fbb46f6ab}

디바이스를 &quot;알 수 없음&quot;으로 간주할 수 있는 몇 가지 방법 또는 범주가 있습니다. 다음과 같은 보고서가 포함됩니다.

* **다른 Device Co-op 구성원에 대한 자사 방문:** 기타 방문 수 [!DNL Device Co-op] 회원 사이트나 장치에 대한 광고는 그 자체로 귀하의 브랜드에 장치를 알려주지 않습니다.

* **추적되지 않는 광고 인벤토리:** 사용할 수 있지만 아직 제공되거나 수집되지 않은 광고 인벤토리는 장치를 브랜드에 알려주지 않습니다.
* **소비자 옵트아웃:** 소비자 욕구를 존중하기 위해, 옵트아웃된 디바이스는 알려진 디바이스로 간주되지 않는다.

알려진 장치와 달리 알 수 없는 장치는 다른 장치에 연결되어 있지 않거나 개별 사용자와 연결되어 있지 않습니다.

## 알려진/알 수 없는 상태 설정 규칙 {#section-fa5c85e59e2d4f88bb79f27f17f02344}

다음 [!DNL Device Graph] 는 알 수 없는 것과 비교하여 알려진 것으로 장치를 분류할 때 가능한 포괄적으로 하려고 합니다. 알려진/알 수 없는 상태를 판별하는 데 도움이 되는 규칙은 아래와 같이 우선 순위 순서로(1이 가장 높음) 작동합니다.

* **규칙 1:** 장치가 옵트아웃되었습니까? 그렇다면 디바이스를 알 수 없습니다.
* **규칙 2:** 장치가에 알려져 있습니까? *임의* 방법? 그렇다면 장치를 알 수 있습니다.

* **규칙 3: ** 이전 규칙이 적용되지 않으면 장치를 알 수 없습니다.

>[!MORELIKETHIS]
>
>* [알려진 장치](../processes/known-device.md#concept-8e87c276819a48bfac5cef10b45216d1)

