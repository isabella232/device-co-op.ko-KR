---
description: Device Co-op(Identity Services Cooperative 및 Identity Graph)에 대한 일반적인 질문에 대한 답변입니다.
title: Device Co-op FAQ
uuid: 490566e1-4d35-468c-8389-678f9ff02cc8
exl-id: 6511e247-76a7-4960-944c-b49fd046fb28
source-git-commit: 399a4fe2d34957eafe8c4eebed465df8770a9239
workflow-type: tm+mt
source-wordcount: '477'
ht-degree: 1%

---

# FAQ{#faq}

ID 서비스 조합 및 ID 그래프와 관련된 일반적인 질문에 대한 설명 및 답변입니다.

**그게  [!DNL Device Co-op]뭐죠?**

Device Co-op는 참여하는 Adobe Experience Cloud 고객이 다양한 디바이스에서 소비자를 보다 효과적으로 식별할 수 있도록 협력할 수 있는 디지털 협력입니다.

**Device Co-op에서 사용되는 기술은 무엇입니까?**

Device Co-op는 다음 두 가지 기술로 구성됩니다.

* **Experience Cloud ID 서비스:** Adobe Experience Cloud의 이 핵심 서비스는 솔루션, 채널, 경험 및 장치 간에 소비자를 일관되게 식별하기 위한 공통 ID를 제공합니다.
* **Adobe Experience Cloud Device Co-op:** 이 기술은 소비자 또는 가정에서 사용하는 다양한 장치를 연결합니다.

**일은  [!DNL Device Co-op] 어떻습니까?**

브랜드들이 익명화된 로그인 및 사이트 방문을 통해 크로스 디바이스 퍼즐의 일부를 광고하면서 Adobe은 이 데이터를 처리하여 알려지지 않은 사람이 사용하는 장치 그룹을 나타내는 장치 클러스터를 형성합니다. 이러한 장치 클러스터는 Device Co-op 멤버에게 제공되며 소비자에게 보다 효율적이고 일관된 크로스 디바이스 경험을 제공하는 데 사용됩니다.

**링크 장치의  [!DNL Device Co-op] 작동 방식**

[결정적 및 확률적 링크](processes/links.md#concept-58bb7ab25f904f5f98d645e35205c931)를 참조하십시오.

**참가자가 제공하는 데이터는 무엇입니까 [!DNL Adobe]?**

[소비자 옵트아웃 도구, 개인 정보 및 장치 그래프](privacy.md#concept-fa1346e6b95a484eaeafc9bebe3cd6be)를 참조하십시오.

**멤버 간에 어떤 데이터가  [!DNL Device Co-op] 공유됩니까?**

장치 그래프의 [링크 공유](processes/link-sharing.md#concept-7168053105a94649a3f092d375d79eaf)를 참조하십시오.

<!--
Removed at Asa's request.
<p><b>What does <span class="keyword"> Adobe </span> see via the <span class="wintitle"> Device Graph </span>?</b> </p>
<p>Adobe can see which devices are most likely being used by the same person, using probabilistic and deterministic device graph algorithms. This match between a group of devices and a person is really two numbers that are linked to each other. One number represents a group of devices believed to belong to the same person while the other number represents a person. Adobe makes this linked device information available to consumers as well, so they can correct misinformation and/or opt-out one or all devices from the Device Co-op. </p>
-->

**회원이 이전에  [!DNL Device Co-op] 보지 못했던 디바이스에 대한 링크를 볼 수 있습니까?**

아니요. Device Co-op 멤버는 브랜드의 웹 속성 중 하나를 방문한 장치를 기반으로 데이터를 얻을 수 있습니다. [알려진 장치](processes/known-device.md#concept-8e87c276819a48bfac5cef10b45216d1) 및 [알 수 없는 장치](processes/unknown-device.md#concept-95090d341cdc4c22ba4319d79d8f6e40)를 참조하십시오.

**회사의 마케팅 정보를 공유해야 합니까?**

아니요. 브랜드는 Adobe에 익명 장치 데이터만 제공합니다.

**에서 PII(개인 식별 정보)를  [!DNL Adobe] 사용합니까 [!DNL Device Co-op]?**

아니요. 모든 개인 식별 정보는 Adobe 시스템으로 가져오기 전에 해시 처리되므로 고객의 정보는 Adobe 시스템으로 전송되지 않습니다.

**디바이스 데이터를 Device Co-op에 적게 기여하는 작은 브랜드가 자사의 큰 브랜드보다 더 높은 가치를 제공합니까?**

아니요. 조합의 모든 조합원은 그들이 넣은 것에 비례하여 가치가 회복된다. 예를 들어 브랜드가 10,000개의 장치를 기부하는 경우 해당 10,000개의 장치에 연결된 추가 장치 정보를 수신할 수 있게 됩니다. 큰 그림을 보면, 이 기여는 최소로 보일 수 있다.그러나 모든 크기의 브랜드가 점점 더 많이 참여함에 따라 집계된 기여도는 중요하며, 많은 다른, 아마도 더 큰 브랜드의 많은 디바이스에서 누락된 링크가 제공될 것입니다. [공정성과 알려진 장치](processes/known-device.md#section-0543188729d845d6b95db70b8b25e9f8)를 참조하십시오.

**일부 국가에서 IP 주소를 개인 정보로 간주하는 경우 IP 주소는 어떻게  [!DNL Adobe] 관리됩니까?**

Device Co-op는 IP 주소가 개인 정보로 간주되지 않는 미국과 캐나다에서 처음 출시됩니다. IP 주소가 개인 정보로 간주되는 국가에서 협업이 릴리스되면 IP 주소가 사용되지 않습니다.
