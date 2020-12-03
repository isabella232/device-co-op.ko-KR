---
description: 장치 그래프의 알려진 장치 정보.
seo-description: 장치 그래프의 알려진 장치 정보.
seo-title: 알려진 장치
title: 알려진 장치
uuid: 53c21105-45b1-4bed-a473-d3ccc4bae965
translation-type: tm+mt
source-git-commit: 4f972a4ae3f0c5ee11b21876bd8a6966cad90371
workflow-type: tm+mt
source-wordcount: '571'
ht-degree: 1%

---


# 알려진 장치{#known-devices}

장치 그래프의 알려진 장치 정보.

Device Graph에서 우리는 A라는 개념을 가지고 있습니다 *`known device`*. 알려진 장치는 고객이 브랜드와 상호 작용하기 위해 사용하는 장치입니다.

>[!NOTE]
>
>용어 [!DNL Adobe Experience Cloud Device Co-op](예: *`device`*, *`person`*&#x200B;등) *`identity`* 에서 특정 의미를 가집니다. 예를 들어, &quot;장치&quot;는 휴대폰이나 태블릿과 같은 물리적 하드웨어 및 해당 하드웨어에서 실행되는 응용 프로그램을 나타낼 수 있습니다. 정의는 [용어집을](../glossary.md#glossgroup-0f47d7fbd76c4759801f565f341a386c) 참조하십시오.

## 알려진 디바이스에서 목표 지원 {#section-80deae33660e4280ac65c659ceff5601}

알려진 디바이스 개념은 효과적인 [!DNL Device Co-op] 프로그램 제작 및 유지 관리에 필요한 몇 가지 목표를 지원합니다. 알려진 장치는 [!DNL Device Co-op] 회원이 소비자와 일부 상호 작용에서(예: 사이트 방문 또는 모바일 앱 사용)에 대해 알고 있는 장치입니다. 이러한 작업을 기반으로 [!DNL Device Graph] 멤버의 알려진 장치가 다른 구성원이 만든 장치에 [!DNL Device Co-op] [!DNL Device Co-op] 연결됩니다. 이러한 링크는 [결정론적이거나 확률론일 수 있습니다](../processes/links.md#concept-58bb7ab25f904f5f98d645e35205c931). 이 혜택은 다음과 같은 혜택을 [!DNL Device Co-op] 받게 됩니다.

* 알려진 장치에 대한 추가 데이터
* 다른 연결된 장치에 대한 새로운 정보입니다.

![](assets/known-device.png)

Device Co-op 구성원이 보지 못한 장치 클러스터에 대한 정보는 [!DNL Device Graph] 제공되지 않습니다.

## 장치 협력 목표 {#section-75aea5a102d54733aae2a7c6ee9ec6c7}

세 가지 주요 목표에 애니메이션을 줍니다 [!DNL Device Co-op]. 다음과 같은 보고서가 포함됩니다.

* **비율:** 다양한 사용 사례에서 가능한 최대 링크 수를 공유합니다.
* **공정성:** 각 회원에게 기여도에 [!DNL Device Co-op] 상응하는 방식으로 혜택을 주도록 하십시오.

* **소비자 신뢰:** 소비자의 다양한 디바이스 경험을 통해 이미 알고 있고 신뢰할 수 있는 브랜드로 고객 신뢰도를 유지하고 구축할 수 있습니다.

## 크기 조절 및 알려진 장치 {#section-67f734109762457ca62ec306284ea082}

다음 방법은 장치가 알려진 장치로 자격을 얻는 더 일반적인 방법입니다. 이러한 방법을 사용할 경우 [!DNL Device Co-op] 구성원에 알려진 장치가 거의 항상 1개 이상 있습니다. 따라서 모든 구성원에 대해 최대 크기를 제공하는 목표를 지원합니다 [!DNL Device Co-op].

**유기**

* 고객의 사이트 방문 또는 앱을 사용하여 이는 자사 데이터에서 얻을 수 있는 자격입니다.
* CRM 시스템에서 온-보딩 고객

**Marketplace를**

* Audience Marketplace에서 세그먼트 데이터 구매
* 제3자 데이터 제공업체의 데이터 구매부터

**광고**

경매에서 인벤토리를 확보하고 디바이스에 광고를 제공하는 등 광고에 [!DNL Audience Manager] 픽셀이 포함된 경우 장치가 알려진 장치가 됩니다.

## 알려진 장치 및 공정성 사용 사례 {#section-0543188729d845d6b95db70b8b25e9f8}

그 회원들은 [!DNL Device Co-op] 자신들의 기여에 상응하는 링크를 받는다 [!DNL Device Graph]. 적은 수의 회원보다 많은 링크를 받는 데 많은 디바이스를 제공하는 [!DNL Device Graph] 회사입니다. 우리는 이것이 모든 회원들에게 [!DNL Device Co-op] 공평함을 가져다 줄 것이라고 믿는다. 아래에 설명된 크고 작은 사용 사례와 함께 이 기능이 어떻게 작동하는지 살펴보겠습니다.

**브랜드 A:대규모 사용 사례**

이 예에서는 브랜드 A에 매달 100명의 사이트 방문자가 있으며 새로운 크로스 디바이스 브랜드 캠페인을 시작합니다. 간단하게 볼 때 브랜드 A의 모든 방문자가 1개의 추가 장치에 연결되어 있음을 알고 있다고 가정합니다. [!DNL Device Graph] 이는 브랜드 A가 다른 100개의 장치에 도달할 수 있음을 의미합니다. 게다가, 이 장치에는 [!DNL Device Graph] 약 200개의 장치들이 함께 연결되어 있다.

<table id="table_78C38DC522F94BC38C1DB73740C058AC"> 
 <thead> 
  <tr> 
   <th colname="col1" class="entry"> 알려진 장치/월 </th> 
   <th colname="col2" class="entry"> Device Co-op에서 수신한 연결된 장치 </th> 
   <th colname="col3" class="entry"> 캠페인에 대한 총 장치 </th> 
  </tr>
 </thead>
 <tbody> 
  <tr> 
   <td colname="col1"> <p>100 </p> </td> 
   <td colname="col2"> <p>100 </p> </td> 
   <td colname="col3"> <p>200 </p> </td> 
  </tr> 
 </tbody> 
</table>

**브랜드 B:소규모 사용 사례**

이 예에서 브랜드 B는 매달 100명의 사이트 방문자를 운영하고 있으며 새로운 크로스 디바이스 브랜드 캠페인을 시작합니다. 간단하게 볼 때 브랜드 B의 모든 방문자가 50개의 추가 장치에 연결되어 있음을 알고 있다고 가정합니다. [!DNL Device Graph] 이는 브랜드 B가 150개 디바이스에 도달할 수 있음을 의미합니다. 게다가, 그 [!DNL Device Graph] 에는 약 1,000개의 장치들이 함께 연결되어 있다.

<table id="table_A6C9CCF9C6564A89BA7060E075A8E73C"> 
 <thead> 
  <tr> 
   <th colname="col1" class="entry"> 알려진 장치/월 </th> 
   <th colname="col2" class="entry"> Device Co-op에서 수신한 연결된 장치 </th> 
   <th colname="col3" class="entry"> 캠페인에 대한 총 장치 </th> 
  </tr>
 </thead>
 <tbody> 
  <tr> 
   <td colname="col1"> <p>100 </p> </td> 
   <td colname="col2"> <p>50 </p> </td> 
   <td colname="col3"> <p>150 </p> </td> 
  </tr> 
 </tbody> 
</table>

>[!MORELIKETHIS]
>
>* [알 수 없는 장치](../processes/unknown-device.md#concept-95090d341cdc4c22ba4319d79d8f6e40)

