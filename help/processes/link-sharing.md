---
description: Device Graph에서 링크 공유 정보.
seo-description: About link sharing in the Device Graph.
seo-title: Link sharing in the Device Graph
title: Device Graph에서 링크 공유
uuid: 6c7202f0-c6d9-48a4-82ad-ee57d7a518a0
exl-id: 91ecc493-89d8-40d6-a98b-c2349e25c854
source-git-commit: 573744525fcc00f35540af9ffec46530111940ed
workflow-type: tm+mt
source-wordcount: '544'
ht-degree: 0%

---

# Device Graph에서 링크 공유{#link-sharing-in-the-device-graph}

Device Graph에서 링크 공유 정보.

다음 [!DNL Device Graph] Adobe Experience Cloud Device Co-op의 다른 멤버와 결정론적 및 확률론적 링크를 공유합니다. 링크 공유는 다음을 가능하게 합니다. [!DNL Device Co-op] 아주 강력해 익명 사용자와 관련된 장치에 대해 각 구성원이 알고 있는 내용을 확장하지만, 해당 익명 사용자의 장치 중 하나 이상을 이전에 본 적이 있는 경우에만 확장됩니다.

## Device Graph 요약 검토 {#section-7858e9f61b5644c981ffb53626fcc19d}

시작하기 전에 잠시 다음 방법을 살펴보겠습니다. [!DNL Device Graph] 효과가 있습니다. 의 멤버 [!DNL Device Co-op] 에 데이터 보내기 [!DNL Device Graph]. 다음 [!DNL Device Graph] 은 이 데이터를 사용하여 다음 위치에서 사용자의 ID를 구성합니다 [결정론적 링크 및 확률론적 링크](../processes/links.md#concept-58bb7ab25f904f5f98d645e35205c931) 디바이스 간. 로서의 [!DNL Device Co-op] 참여자, 이러한 링크는 인증된 사용자, 다른 사용자 및 해당 장치 간의 관계에 대한 통찰력을 제공합니다. 아래 섹션에서 이것이 어떻게 작동하는지 살펴보겠습니다.

## 링크 공유 예 {#section-cb410d827cf14f76bc9b0bd4d31ed767}

다음 예는 Device Co-op에서 링크 공유의 기능을 보여 줍니다. 이 예에는 두 개의 가상 회사인 뉴스 회사와 금융 회사가 있습니다. 두 회사 모두 의 구성원입니다. [!DNL Device Co-op]. 개인 A는 여러 디바이스에서 각 회사의 웹 사이트를 로그인하거나 탐색하는 소비자입니다.

![](assets/share1.png)

개인 A가 휴대폰과 태블릿으로 뉴스 사이트에 인증했으므로 뉴스 회사는 소비자 ID로 이를 식별합니다. 이 ID를에 보냅니다. [!DNL Device Graph] 암호화 해시로 사용됩니다. 금융 회사는 이러한 장치를 이전에 본 적이 있지만 A씨는 해당 사이트에 로그온하지 않았습니다. 따라서 금융 회사는 이러한 디바이스가 서로 어떤 관련이 있는지 또는 어떻게 연관되어 있는지 또는 개인 A와 어떻게 연관되어 있는지 알지 못합니다.

![](assets/share2.png)

소비자 ID의 암호화 해시가 주어지면 [!DNL Device Graph] 는 이러한 장치가 서로 및 특정 사용자와 관련이 있음을 인식합니다. 에 참여하지 않는 회사 [!DNL Device Co-op] 이러한 사이트 방문은 별도의 무작위 디바이스에서 이루어지는 것으로 보입니다. 어떤 경우든 [!DNL Device Graph] 이(가) 해시된 ID를 보유합니다.

* 휴대폰과 노트북이 연결되어 있다는 것을 알고 있습니다.
* 는 금융 회사가 휴대폰과 노트북이 연결되어 있는지 알고 싶어한다는 것을 인식합니다.

이러한 조건이 주어지면 [!DNL Device Graph] 이제 News Company의 이러한 장치를 연결하는 링크를 Finance Company와 공유합니다. 이 프로세스 중에 [!DNL Device Graph] 한 공동 작업 구성원의 링크를 복제하고 다른 공동 작업 구성원과 공유합니다.

![](assets/share3.png)

이 시점에서 [!DNL Device Graph] 이(가) 역할을 수행했습니다. 뉴스 회사와 금융 회사 모두 신원에 대한 명확한 그림을 가지고 있습니다. 모든 디바이스에서 개인 A에게 정확하게 도달할 수 있습니다.

## 개인 정보 보호 및 링크 공유 {#section-7b566018b3304420a4b3e4c079826110}

고객 개인정보 보호 및 데이터 무결성 유지 [!DNL Device Co-op] 구성원은 링크 공유 프로세스 전체에서 매우 중요합니다. 이 고객 식별 및 링크 공유 프로세스 중에 [!DNL Device Graph] 다음을 수행하지 않음:

* 금융 회사에 링크가 뉴스 회사에서 나왔다고 알려 주세요.
* 한 사용자가 사용한 고객 ID 공유 [!DNL Device Co-op] 다른 사용자와 함께 있는 멤버.
* 모바일 장치와 랩탑이 링크를 공유하는 것 이외의 모든 정보를 제공합니다.

## 다음 단계 {#section-ac6e61f1eb6e45b1bb4be8ece39147c7}

ID, 연결 및 링크 공유에 대한 설명서를 읽으면 가 [!DNL Device Graph] 데이터를 내부적으로 어셈블합니다. 다음 단계로, 의 개념을 설명하는 설명서를 살펴보는 것이 좋습니다. *`known device`* 는 Device Co-op 멤버로 장치 간 링크를 전달합니다. 다음을 참조하십시오 [알려진 장치](../processes/known-device.md#concept-8e87c276819a48bfac5cef10b45216d1) 및 [알 수 없는 장치](../processes/unknown-device.md#concept-95090d341cdc4c22ba4319d79d8f6e40).
