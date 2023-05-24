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

ID 서비스 협동조합 및 ID 그래프에 대한 일반적인 질문에 대한 설명 및 답변입니다.

**이란? [!DNL Device Co-op]?**

Device Co-op은 참여하는 Adobe Experience Cloud 고객이 디바이스 간에 소비자를 더 잘 식별할 수 있도록 함께 협력하는 디지털 협력체입니다.

**Device Co-op에 사용되는 기술은 무엇입니까?**

Device Co-op는 두 가지 기술로 구성됩니다.

* **Experience Cloud ID 서비스:** Adobe Experience Cloud의 이 핵심 서비스는 솔루션, 채널, 경험 및 장치 간에 일관되게 소비자를 식별하기 위한 공통 ID를 제공합니다.
* **Adobe Experience Cloud Device Co-op:** 이 기술은 소비자 또는 가정에서 사용하는 다양한 장치를 연결합니다.

**은(는) 어떻게 합니까 [!DNL Device Co-op] 일?**

브랜드가 익명으로 로그인 및 사이트 방문을 통해 교차 장치 퍼즐의 조각에 매핑되면 Adobe은 이 데이터를 처리하여 알 수 없는 사람이 사용하는 장치 그룹을 나타내는 장치 클러스터를 형성합니다. 이러한 장치 클러스터는 Device Co-op 구성원에게 제공되며 소비자에게 더 나은 일관된 교차 장치 경험을 제공하는 데 사용됩니다.

**은(는) 어떻게 합니까 [!DNL Device Co-op] 장치를 연결하시겠습니까?**

다음을 참조하십시오 [결정론적 및 확률론적 링크](processes/links.md#concept-58bb7ab25f904f5f98d645e35205c931).

**참가자가 제공하는 데이터 [!DNL Adobe]?**

다음을 참조하십시오 [소비자 옵트아웃 도구, 개인 정보 보호 및 장치 그래프](privacy.md#concept-fa1346e6b95a484eaeafc9bebe3cd6be).

**다음 기간 동안 공유된 데이터 [!DNL Device Co-op] 회원?**

다음을 참조하십시오 [Device Graph에서 링크 공유](processes/link-sharing.md#concept-7168053105a94649a3f092d375d79eaf).

<!--
Removed at Asa's request.
<p><b>What does <span class="keyword"> Adobe </span> see via the <span class="wintitle"> Device Graph </span>?</b> </p>
<p>Adobe can see which devices are most likely being used by the same person, using probabilistic and deterministic device graph algorithms. This match between a group of devices and a person is really two numbers that are linked to each other. One number represents a group of devices believed to belong to the same person while the other number represents a person. Adobe makes this linked device information available to consumers as well, so they can correct misinformation and/or opt-out one or all devices from the Device Co-op. </p>
-->

**할 수 있음 [!DNL Device Co-op] 회원은 전에 본 적이 없는 장치에 대한 링크를 볼 수 있습니까?**

아니요. Device Co-op 구성원은 해당 브랜드의 웹 속성 중 하나를 방문한 디바이스를 기반으로 한 데이터만 가져올 수 있습니다. 다음을 참조하십시오 [알려진 장치](processes/known-device.md#concept-8e87c276819a48bfac5cef10b45216d1) 및 [알 수 없는 장치](processes/unknown-device.md#concept-95090d341cdc4c22ba4319d79d8f6e40).

**회사의 마케팅 정보를 공유해야 합니까?**

아니요. 브랜드는 Adobe에 익명 장치 데이터만 제공합니다.

**다음과 같음 [!DNL Adobe] 에서 PII(개인 식별 정보) 사용 [!DNL Device Co-op]?**

아니요. 모든 개인 식별 정보는 Adobe 시스템으로 전송되기 전에 해시되므로 고객의 정보가 Adobe 시스템으로 전송되지 않습니다.

**Device Co-op에 장치 데이터를 더 적게 기여하는 소규모 브랜드는 대규모 브랜드에 비해 더 많은 가치를 얻을 수 있습니까?**

아니요. 협동조합의 모든 구성원들은 그들이 투입한 것에 비해 가치를 돌려받는다. 예를 들어 브랜드가 10,000개의 장치에 기여하는 경우 해당 10,000개와 연결된 추가 장치 정보를 받을 수 있습니다. 큰 그림을 보면, 이 기여도는 최소한으로 보일 수 있습니다. 하지만 모든 크기의 브랜드가 참여함에 따라, 집계된 기여도는 중요하며, 다른 많은 브랜드, 아마도 더 큰 브랜드가 찾고 있는 많은 디바이스에 누락된 링크를 제공합니다. 다음을 참조하십시오 [공정성 및 알려진 장치](processes/known-device.md#section-0543188729d845d6b95db70b8b25e9f8).

**은(는) 어떻게 합니까? [!DNL Adobe] 일부 국가에서 IP 주소를 개인 정보로 간주하는 경우 IP 주소를 관리하시겠습니까?**

Device Co-op은 IP 주소가 개인 정보로 간주되지 않는 미국 및 캐나다에서 처음 출시됩니다. IP 주소가 개인 정보로 간주되는 국가에서 Cooperative가 출시되면 해당 IP 주소는 사용되지 않습니다.
