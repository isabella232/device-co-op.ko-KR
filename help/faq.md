---
description: Identity Services Cooperative 및 Identity Graph와 관련된 일반적인 질문에 대한 설명과 답변.
seo-description: Identity Services Cooperative 및 Identity Graph와 관련된 일반적인 질문에 대한 설명과 답변.
seo-title: FAQ
title: FAQ
uuid: 490566e1-4d35-468c-8389-678f9ff02cc8
translation-type: tm+mt
source-git-commit: c1d0bc05d3f211fa3e899e98fbcc908be7399031

---


# FAQ{#faq}

Identity Services Cooperative 및 Identity Graph와 관련된 일반적인 질문에 대한 설명과 답변.

**이게[!DNL Device Co-op]뭐야?**

Device Co-op는 Adobe Experience Cloud 고객이 협업하여 다양한 디바이스에서 소비자를 보다 효과적으로 식별할 수 있도록 지원하는 디지털 협력업체입니다.

**Device Co-op에는 어떤 기술이 사용됩니까?**

Device Co-op는 다음 두 가지 기술로 구성됩니다.

* **Experience Cloud ID 서비스:** Adobe Experience Cloud의 이 핵심 서비스는 솔루션, 채널, 경험 및 디바이스에서 일관되게 소비자를 식별하기 위한 공통 ID를 제공합니다.
* **Adobe Experience Cloud Device Co-op:** 이 기술은 소비자나 가정에서 사용하는 다양한 장치를 연결합니다.

**일은 어떻게[!DNL Device Co-op]하나요?**

브랜드들이 익명의 로그인 및 사이트 방문을 통해 얻은 여러 장치 간의 퍼즐 조각을 제공하면, Adobe가 이 데이터를 처리하여 알려지지 않은 사람이 사용한 장치 그룹을 나타내는 장치 클러스터를 형성합니다. 이러한 장치 클러스터는 Device Co-op 구성원에게 제공되며 소비자에게 보다 일관성 있고 더 나은 크로스 디바이스 환경을 제공하는 데 사용됩니다.

**링크 장치의[!DNL Device Co-op]작동 방식**

See [Deterministic and Probabilistic Links](processes/links.md#concept-58bb7ab25f904f5f98d645e35205c931).

**참가자가 제공하는 데이터는[!DNL Adobe]무엇입니까?**

[소비자 옵트아웃 도구, 개인 정보 및 Device Graph](privacy.md#concept-fa1346e6b95a484eaeafc9bebe3cd6be)를 참조하십시오.

**어떤 데이터가[!DNL Device Co-op]멤버 간에 공유됩니까?**

See [Link Sharing in the Device Graph](processes/link-sharing.md#concept-7168053105a94649a3f092d375d79eaf).

<!--
Removed at Asa's request.
<p><b>What does <span class="keyword"> Adobe </span> see via the <span class="wintitle"> Device Graph </span>?</b> </p>
<p>Adobe can see which devices are most likely being used by the same person, using probabilistic and deterministic device graph algorithms. This match between a group of devices and a person is really two numbers that are linked to each other. One number represents a group of devices believed to belong to the same person while the other number represents a person. Adobe makes this linked device information available to consumers as well, so they can correct misinformation and/or opt-out one or all devices from the Device Co-op. </p>
-->

**[!DNL Device Co-op]구성원은 전에 본 적이 없는 장치에 연결된 링크를 볼 수 있습니까?**

아니요. Device Co-op 구성원은 해당 브랜드의 웹 속성 중 하나를 방문한 장치를 기반으로만 데이터를 얻을 수 있습니다. 자세한 내용은 알려진 [장치](processes/known-device.md#concept-8e87c276819a48bfac5cef10b45216d1) 및 [알 수 없는 장치](processes/unknown-device.md#concept-95090d341cdc4c22ba4319d79d8f6e40).

**회사의 마케팅 정보를 공유해야 합니까?**

아니요. 브랜드는 익명 장치 데이터만 Adobe에 제공합니다.

**에서 PII(개인 식별 정보)를[!DNL Adobe]사용합니까[!DNL Device Co-op]?**

아니요. 모든 개인 식별 정보는 Adobe 시스템에 가져오기 전에 해시되므로 Adobe 시스템에 고객 정보가 전송되지 않습니다.

**큰 브랜드에 비해, Device Co-op에 장치 데이터를 더 적게 제공하는 작은 브랜드는 제공하는 것 보다 더 많은 가치를 얻습니까?**

아니요. 협업의 모든 구성원은 제공하는 것과 비례하여 가치를 돌려받습니다. 예를 들어 어떤 한 브랜드가 10,000개의 장치를 제공하는 경우, 해당하는 10,000개의 장치와 관련하여 링크로 연결된 추가 장치 정보를 받을 수 있습니다. 큰 그림을 볼 때, 이러한 기여도는 미미해 보이지만 다양한 크기의 브랜드가 점점 더 많이 참여함에 따라 집계되는 기여도가 의미를 갖게 되며, 이러한 과정을 통해 또 다른 많은 혹은 더 큰 브랜드가 찾고 있는 많은 장치에 대한 누락된 링크가 제공됩니다. 공정성과 [알려진 장치를 참조하십시오](processes/known-device.md#section-0543188729d845d6b95db70b8b25e9f8).

**일부 국가에서 IP 주소를 개인 정보로 간주하는 경우[!DNL Adobe]는 IP 주소를 어떻게 관리합니까?**

Device Co-op는 IP 주소가 개인 정보로 간주되지 않는 미국과 캐나다에서 먼저 릴리스됩니다. 이 협업이 IP 주소가 개인 정보로 간주되는 국가에서 릴리스되면 IP 주소가 사용되지 않습니다.
