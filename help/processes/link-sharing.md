---
description: 장치 그래프의 링크 공유 정보.
seo-description: 장치 그래프의 링크 공유 정보.
seo-title: 장치 그래프의 링크 공유
title: 장치 그래프의 링크 공유
uuid: 6c7202f0-c6d9-48a4-82ad-ee57d7a518a0
translation-type: tm+mt
source-git-commit: c1d0bc05d3f211fa3e899e98fbcc908be7399031

---


# Link sharing in the Device Graph{#link-sharing-in-the-device-graph}

장치 그래프의 링크 공유 정보.

The [!DNL Device Graph] shares deterministic and probabilistic links with different members of the Adobe Experience Cloud Device Co-op. Link sharing is what makes the [!DNL Device Co-op] so powerful. 이 기능은 익명의 사용자와 연결된 장치에 대해 각 구성원이 알고 있는 정보를 확장하지만, 이것은 그 전에 해당 익명 사용자의 장치를 하나 이상 본 적이 있는 경우에만 해당합니다.

## Device Graph summary review {#section-7858e9f61b5644c981ffb53626fcc19d}

시작하기 전에 잠시 [!DNL Device Graph]가 작동하는 방식을 검토해 보겠습니다. Members of the [!DNL Device Co-op] send data to the [!DNL Device Graph]. 이 [!DNL Device Graph] 데이터는 장치 간의 [결정적 링크와 확률적 링크에서](../processes/links.md#concept-58bb7ab25f904f5f98d645e35205c931) 개인의 신원을 구성하는 데 사용됩니다. [!DNL Device Co-op] 참가자의 경우 이 링크는 인증된 사용자, 다른 사용자 및 이들의 장치 간 관계에 대한 통찰력을 제공합니다. 아래 섹션에서는 그 작동 방식에 대해 살펴보겠습니다.

## Link sharing example {#section-cb410d827cf14f76bc9b0bd4d31ed767}

다음 예에서는 Device Co-op에서 링크 공유가 갖는 힘을 보여줍니다. 이 예에는 뉴스 회사와 금융 회사, 이렇게 2개의 가상 회사가 있습니다. Both companies are members of the [!DNL Device Co-op]. 사람 A는 여러 장치에서 각 회사의 웹 사이트에 로그온하거나 탐색하는 소비자입니다.

![](assets/share1.png)

사람 A는 휴대폰과 태블릿으로 뉴스 사이트에 인증했으므로, 뉴스 회사는 이러한 장치를 소비자 ID로 식별하고 해당 ID를 암호화 해시로 [!DNL Device Graph]에 보냅니다. 금융 회사는 이전에 이러한 장치를 본 적은 있지만, 사람 A가 해당 사이트에 로그온한 적은 없습니다. 그 결과, 금융 회사는 이 장치들이 서로 관계가 있는지 여부나 관계를 맺는 방식 또는 사람 A와 연결된 방식을 알지 못합니다.

![](assets/share2.png)

소비자 ID에 대한 암호화 해시가 있을 경우, [!DNL Device Graph]는 이 장치들이 서로 관련되어 있고 특정 사람과도 관련되어 있음을 인식합니다. [!DNL Device Co-op]에 참여하지 않는 회사에게 이러한 사이트 방문은 별도의 임의 장치에서 방문하는 것으로 나타납니다. 어떠한 경우든, [!DNL Device Graph]에 해시된 ID가 있으면 그래프는

* 휴대폰과 랩톱이 연결된 것을 알게 됩니다.
* 휴대폰과 랩톱이 연결되어 있는지 여부를 금융 회사가 알고 싶어한다는 것을 알게 됩니다.

이제 이러한 조건을 고려하여, [!DNL Device Graph]는 뉴스 회사용으로 이러한 장치를 연결하는 링크를 금융 회사와 공유합니다. 이러한 프로세스를 통해 [!DNL Device Graph]는 하나의 협업 구성원의 링크를 복제하여 다른 구성원에게 공유합니다.

![](assets/share3.png)

At this point, the [!DNL Device Graph] performed its role successfully. 뉴스 회사와 금융 회사는 모두 ID에 대한 명확한 그림을 가지게 됩니다. 두 회사는 모든 장치에서 사람 A에게 정확하게 도달할 수 있습니다.

## Privacy and link sharing {#section-7b566018b3304420a4b3e4c079826110}

[!DNL Device Co-op] 구성원에 대해 소비자 개인 정보 보호와 데이터 무결성을 유지하는 것은 전체 링크 공유 프로세스에서 매우 중요합니다. 이러한 고객 식별 및 링크 공유 프로세스 동안 [!DNL Device Graph]는 다음을 준수합니다.

* 해당 링크를 뉴스 회사에서 가져왔다는 사실을 금융 회사에 알리지 않습니다.
* 하나의 [!DNL Device Co-op] 구성원이 사용한 고객 ID를 다른 구성원과 공유하지 않습니다.
* 모바일 장치와 랩톱이 공동으로 링크를 공유한다는 것 이외에 다른 정보를 제공하지 않습니다.

## 다음 단계 {#section-ac6e61f1eb6e45b1bb4be8ece39147c7}

ID, 링크 연결, 링크 공유에 대한 설명서를 읽으면 [!DNL Device Graph]가 어떻게 데이터를 내부적으로 결합하는지 잘 알 수 있습니다. 다음 단계로, Device Co-op 구성원에게 장치 간 링크를 어떻게 *`known device`* 제공하는지 설명하는 설명서를 살펴보는 것이 좋습니다. 알려진 [장치](../processes/known-device.md#concept-8e87c276819a48bfac5cef10b45216d1) 및 알 수 [없는 장치를 참조하십시오](../processes/unknown-device.md#concept-95090d341cdc4c22ba4319d79d8f6e40).
