---
description: 장치 그래프의 알려진 장치 정보.
seo-description: 장치 그래프의 알려진 장치 정보.
seo-title: 알려진 디바이스
title: 알려진 디바이스
uuid: 53c21105-45b1-4bed-a473-d3ccc4bae965
translation-type: tm+mt
source-git-commit: 4f972a4ae3f0c5ee11b21876bd8a6966cad90371

---


# Known devices{#known-devices}

장치 그래프의 알려진 장치 정보.

Device Graph에서 Adobe는 *`known device`*. 알려진 장치는 고객이 브랜드와 상호 작용하는 데 사용하는 장치입니다.

>[!NOTE]
>
>용어(예: [!DNL Adobe Experience Cloud Device Co-op]*`device`*&#x200B;등) *`person`**`identity`* 에서 같은 용어에는 특정한 의미가 있습니다. 예를 들어 &quot;장치&quot;는 휴대폰이나 태블릿과 같은 물리적 하드웨어 및 해당 하드웨어에서 실행되는 애플리케이션을 가리킬 수 있습니다. 이에 대한 정의는 [용어집](../glossary.md#glossgroup-0f47d7fbd76c4759801f565f341a386c)을 참조하십시오.

## Supporting goals with the known device {#section-80deae33660e4280ac65c659ceff5601}

알려진 장치 개념은 효과적인 [!DNL Device Co-op] 프로그램의 생성과 유지 관리에 필수적인 몇 가지 목표를 지원합니다. 알려진 장치는 [!DNL Device Co-op] 구성원이 소비자와의 상호 작용(예: 사이트 방문이나 모바일 앱 사용)을 통해 알게 되는 장치입니다. Based on these actions, the [!DNL Device Graph] links the known devices of a [!DNL Device Co-op] member to devices contributed by other [!DNL Device Co-op] members. 이러한 링크는 [결정적이거나 확률적일 수 있습니다](../processes/links.md#concept-58bb7ab25f904f5f98d645e35205c931). This benefits [!DNL Device Co-op] members because they receive:

* 알려진 장치에 대한 더 많은 데이터.
* 연결된 다른 장치에 대한 새로운 정보.

![](assets/known-device.png)

[!DNL Device Graph]는 Device Co-op 구성원이 보지 않은 장치 클러스터에 대한 정보를 제공하지 않습니다.

## Device Co-op goals {#section-75aea5a102d54733aae2a7c6ee9ec6c7}

Three main goals animate the [!DNL Device Co-op]. 목표는 다음과 같습니다.

* **규모:** 다양한 사용 사례에서 최대 개수의 가능한 링크를 공유합니다.
* **공정성:** [!DNL Device Co-op]의 각 구성원이 자신의 기여도에 비례하여 혜택을 받도록 합니다.

* **소비자 신뢰:** 소비자 크로스 디바이스 환경에 이미 알고 신뢰하는 브랜드가 포함되도록 하여 소비자 신뢰를 구축하고 유지 관리합니다.

## Scale and the known device {#section-67f734109762457ca62ec306284ea082}

다음 방법은 장치가 알려진 장치로 자격이 되는 일반적인 방법입니다. 이 방법을 통해 [!DNL Device Co-op] 구성원은 거의 항상 1개 이상의 알려진 장치를 갖게 됩니다. 이것은 [!DNL Device Co-op]의 모든 구성원에게 최대 규모를 제공하는 목표를 지원합니다.

**유기적**

* 고객의 사이트 방문이나 앱 사용. 퍼스트 파티 데이터로부터 나오는 자격 요건입니다.
* CRM 시스템에서 고객 온보딩.

**Marketplace를**

* Audience Marketplace로부터 세그먼트 데이터 구입.
* 타사 데이터 제공업체로부터 데이터 구입.

**광고**

경매에서 재고를 획득하고 광고를 장치에 제공. 해당 광고에 [!DNL Audience Manager] 픽셀이 포함되어 있을 경우 장치는 알려진 장치가 됩니다.

## Known devices and fairness use cases {#section-0543188729d845d6b95db70b8b25e9f8}

Members of the [!DNL Device Co-op] get links commensurate with their contributions to the [!DNL Device Graph]. 많은·장치를·[!DNL Device Graph]에 제공하는 회사는 적게 제공하는 구성원보다 더 많은 링크를 받습니다. 이 방법은 [!DNL Device Co-op]가 해당하는 모든 구성원에 대한 공정성을 유지하는 데 도움이 됩니다. 아래 설명된 크고 작은 사용 사례에서 이 방법이 어떻게 작동하는지를 살펴보겠습니다.

**브랜드 A:대규모 사용 사례**

이 예에서는 매달 100명의 사이트 방문자가 있는 브랜드 A가 새로운 크로스 디바이스, 브랜드 캠페인을 시작합니다. For simplicity, assume the [!DNL Device Graph] knows all of the visitors to Brand A are linked to 1 additional device. 즉, 브랜드 A가 다른 100개의 디바이스에 도달할 수 있습니다. Additionally, the [!DNL Device Graph] contains about 200 devices linked together.

<table id="table_78C38DC522F94BC38C1DB73740C058AC"> 
 <thead> 
  <tr> 
   <th colname="col1" class="entry"> 알려진 장치 수/월 </th> 
   <th colname="col2" class="entry"> Device Co-op에서 받은 연결된 장치 수 </th> 
   <th colname="col3" class="entry"> 캠페인에 대한 총 장치 수 </th> 
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

**브랜드 B: 작은 사용 사례**

이 예에서는 매달 100명의 사이트 방문자가 있는 브랜드 B가 새로운 크로스 디바이스, 브랜드 캠페인을 시작합니다. For simplicity, assume the [!DNL Device Graph] knows all of the visitors to Brand B are linked to 50 additional devices. 이것은 브랜드 B가 150개의 장치에 도달할 수 있음을 의미합니다. Additionally, the [!DNL Device Graph] contains about 1,000 devices linked together.

<table id="table_A6C9CCF9C6564A89BA7060E075A8E73C"> 
 <thead> 
  <tr> 
   <th colname="col1" class="entry"> 알려진 장치 수/월 </th> 
   <th colname="col2" class="entry"> Device Co-op에서 받은 연결된 장치 수 </th> 
   <th colname="col3" class="entry"> 캠페인에 대한 총 장치 수 </th> 
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
>* [알려지지 않은 장치](../processes/unknown-device.md#concept-95090d341cdc4c22ba4319d79d8f6e40)를 참조하십시오

