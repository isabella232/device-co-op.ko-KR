---
description: 사람 지표는 Adobe의 장치 그래프를 기반으로 하는 사람(또는 장치 그룹)의 수입니다. 사람 지표를 적용하여 Analysis Workspace에 있는 해당 디바이스에서 방문자를 식별할 수 있습니다.
seo-description: The People metric is the count of people (or groups of devices) based on Adobe's Device Graph. You can apply the People metric to identify visitors across their devices in Analysis Workspace.
seo-title: People metric
title: 인물 지표
uuid: 8e731779-044d-4d31-a19a-f579a9c8c471
exl-id: e2e70461-19ab-49db-bd65-a3eb26c2d4a8
source-git-commit: 573744525fcc00f35540af9ffec46530111940ed
workflow-type: tm+mt
source-wordcount: '1374'
ht-degree: 4%

---

# 인물 지표{#people-metric}

사람 지표는 Adobe의 장치 그래프를 기반으로 하는 사람(또는 장치 그룹)의 수입니다. 사람 지표를 적용하여 Analysis Workspace에 있는 해당 디바이스에서 방문자를 식별할 수 있습니다.

## 사용자 지표 사전 요구 사항 및 고려 사항 {#section-34551d0435fb4b3cb3fad736b7961541}

<table id="table_120F7EF50042485391E58B22DD00A2A8"> 
 <thead> 
  <tr> 
   <th colname="col1" class="entry"> 전제 조건 또는 고려 사항 </th> 
   <th colname="col2" class="entry"> 설명 </th> 
  </tr>
 </thead>
 <tbody> 
  <tr> 
   <td colname="col1"> <p>Device Co-op </p> </td> 
   <td colname="col2"> <p> 사람 지표를 사용하려면 의 구성원이 됩니다. <a href="http://landing.adobe.com/en/na/events/summit/275658-summit-co-op.html" format="html" scope="external"> Adobe Experience Cloud Device Co-op</a>. co-op는 개인의 여러 디바이스(또는 Experience Cloud ID)를 식별합니다. Analytics는 이 정보를 활용하여 브랜드와 상호 작용하는 사람의 수를 통계적으로 도출합니다. 지표는 5% 이내로 정확합니다. </p> <p><b>지역</b>: Device Co-op는 현재 미국과 캐나다에서만 사용할 수 있습니다. 따라서 사람 지표를 평가할 때는 미국 및 캐나다에 대해서만 데이터를 필터링하는 세그먼트를 분석에 적용해야 합니다. </p> <p>매주 Device Graph에서 새 버전의 co-op를 계산하고 사용할 수 있도록 게시합니다. 화요일에 시스템은 최신 데이터를 수집하고 그래프의 업데이트된 버전을 게시합니다. 그런 다음 Experience Cloud 솔루션은 최신 버전의 그래프를 사용합니다. 특히 Analytics의 경우 수요일에 변경 사항이 읽혀지며 변경 사항 처리에는 일반적으로 1일에서 2영업일 사이가 소요됩니다. </p> <p> <p>중요: 그래프가 매주 업데이트되면 지금까지 사람 지표에 영향을 줄 수 있습니다. 즉, 그래프가 학습하고 업데이트됨에 따라 시간 경과에 따라 과거 사람 수가 변경될 수 있습니다. 예를 들어, 지난 달에 인원을 계산하는 보고서를 오늘 실행한 다음, 그래프가 업데이트된 후 1주일 후에 동일한 보고서를 실행하는 경우 과거 인원 수가 약간 변경될 수 있습니다. </p> </p> </td> 
  </tr> 
  <tr> 
   <td colname="col1"> 지표 권한 </td> 
   <td colname="col2"> <p>사람 지표에 대한 액세스 권한이 부여된 경우에만 사용할 수 있습니다. 관리자는<a href="https://docs.adobe.com/content/help/en/analytics/admin/user-product-management/customize-report-access/groups-metrics.html" format="html" scope="external"> 지표 권한 사용자 지정</a> 을 참조하십시오. </p> </td> 
  </tr> 
  <tr> 
   <td colname="col1"> IMS 조직에 매핑 </td> 
   <td colname="col2"> <p>다음의 모든 보고서 세트에 대해 사람 지표가 활성화됩니다. <a href="https://docs.adobe.com/content/help/ko-KR/core-services/interface/about-core-services/report-suite-mapping.html" format="html" scope="external"> IMSORG에 매핑</a>. </p> </td> 
  </tr> 
  <tr> 
   <td colname="col1"> <p>Analysis 프로젝트/도구 </p> </td> 
   <td colname="col2"> <p>에서 사람 지표 사용 <span class="wintitle"> Analysis Workspace</span>, <span class="wintitle"> Ad Hoc Analysis</span>, <span class="wintitle"> Report Builder</span>및 를 API를 통해 계산된 지표를 포함하여 고유 방문자 수 지표를 사용할 때마다 이 지표를 사용할 수 있습니다. </p> <p>예를 들어, 사람당 매출 지표를 만들어 고유 방문자당 매출 지표를 바꿉니다. </p> <p>A <a href="https://docs.adobe.com/content/help/ko-KR/analytics/analyze/analysis-workspace/build-workspace-project/starter-projects.html" format="html" scope="external"> 사람 프로젝트 템플릿</a> Analysis Workspace에서 사람 지표 사용을 시작할 수 있습니다. </p> </td> 
  </tr> 
  <tr> 
   <td colname="col1"> <p>보트 규칙 켜기 </p> </td> 
   <td colname="col2"> <p>Adobe은 를 사용하도록 권장합니다. <a href="https://docs.adobe.com/content/help/en/analytics/admin/admin-tools/bot-removal/bot-rules.html" format="html" scope="external"> 보트 규칙</a>특히 사람 지표를 사용할 때 그렇습니다. </p> <p>봇이 웹 사이트를 크롤링할 때 고유 방문자 수가 인위적으로 증가합니다. 보고서 세트에서 보트 트래픽을 제거하면 고유 방문자 수 및 사용자 측면에서 디지털 속성에 대한 활동을 보다 정확하게 측정할 수 있습니다. </p> <p>이렇게 하려면 다음으로 이동합니다. <span class="uicontrol"> 분석</span> &gt; <span class="uicontrol"> 관리자</span> &gt; <span class="uicontrol"> 보고서 세트</span>. 올바른 보고서 세트를 선택한 다음 로 이동합니다. <span class="uicontrol"> 설정 편집</span> &gt; <span class="uicontrol"> 일반</span> &gt; <span class="uicontrol"> 보트 규칙</span>. </p> </td> 
  </tr> 
  <tr> 
   <td colname="col1"> <p>세그먼테이션 고려 사항 </p> </td> 
   <td colname="col2"> <p> 사람 지표와 함께 세그먼트를 사용할 경우 지표 보고가 예상보다 크게 낮아질 수 있습니다. </p> <p>다음을 참조하십시오 <a href="../other-solutions/people.md#section-d03525420dbe48379fd95b230ef05885" format="dita" scope="local"> 세그먼트를 포함하는 사람 지표 사용</a>. </p> </td> 
  </tr> 
 </tbody> 
</table>

## 사용자 지표란 무엇입니까? {#section-89e2b8f5e80f480391449fc8d1117a6a}

사람 지표는 장치를 사람에게 연결하는 데 도움이 되는 Analytics 보고 지표입니다. 사용자 기반 마케팅 보기를 제공하여 모든 장치에서 방문자의 활동을 측정할 수 있도록 합니다. 고유 방문자 수의 중복 제거된 버전이라고 가정하고, 이전에 고유 방문자 수를 사용한 분석에서 사람 지표를 사용할 수 있습니다.

**장치는 사람임**

사람 지표를 사용할 수 있게 되기 전에 사용자(예:)가 사이트를 방문하여 세 개의 다른 디바이스에서 캠페인 또는 브랜드에 참여하고 몇 분 내외로 구매하는 경우도 있습니다. 구현에 따라 Analytics는 각 디바이스를 고유 방문자로 보고하고 $30 구매 시 $10를 3개의 디바이스로 속성을 지정할 수 있습니다.

사람 지표를 사용하면 한 사람에게 30달러 상당의 구매를 정확하게 표시할 수 있습니다.

![](assets/people-centric-results.png)

**보고서의 정확도 향상**

사람 지표를 사용하면 여러 장치를 하나의 개체로 생각할 수 있습니다. 다음 Analysis Workspace 프로젝트는 고유 방문자 보고와 사용자 보고 간의 정확도 비교가 증가된 것을 보여 줍니다.

![](assets/people_report.png)

사람 및 고유 방문자 수 비교 나란히:

![](assets/people-report.png)

**정의**

<table id="table_F8171AF15DA64607B427E3739EF004D6"> 
 <thead> 
  <tr> 
   <th colname="col1" class="entry"> 항목 </th> 
   <th colname="col2" class="entry"> 설명 </th> 
  </tr>
 </thead>
 <tbody> 
  <tr> 
   <td colname="col1"> <p>사람 </p> </td> 
   <td colname="col2"> <p>사람 지표는 소비자가 여러 디바이스를 사용하여 브랜드와 상호 작용한다는 아이디어를 기반으로 합니다. 데이터를 더 많이 분할하거나 분할할수록 동일한 사람이 해당 데이터 조각 내에서 여러 장치를 사용했을 가능성은 더 작아집니다. </p> </td> 
  </tr> 
  <tr> 
   <td colname="col1"> <p>고유 방문자 수 </p> </td> 
   <td colname="col2"> <p>예를 들어, 날짜 또는 시간별로 데이터를 분할할수록 사용자와 고유 방문자 간의 차이는 줄어듭니다. Adobe Device Co-op의 전반적인 영향을 잘 이해하려면 최근 90일 동안의 날짜 범위를 사용하는 것이 좋습니다 </p> </td> 
  </tr> 
  <tr> 
   <td colname="col1"> <p>압축 </p> </td> 
   <td colname="col2"> <p>간단한 계산된 지표를 사용하면 사람 지표가 고유 방문자 수의 비율로서 얼마나 작은지 확인할 수 있습니다. 위의 표에서 "압축" 옆에 있는 정보 아이콘을 클릭하여 이 지표를 만드는 방법을 확인합니다. </p> <p>사용자는 고유 방문자 수 대신 다른 계산된 지표에서 사용할 수 있습니다. </p> </td> 
  </tr> 
 </tbody> 
</table>

## 사람 지표는 어떻게 계산됩니까? {#section-0dfb762867e14a7f927796ef3c50592b}

<!--
<p>Analytics uses the HyperLogLog statistical algorithm to calculate People. This means that the smaller the data set, the margin for error may increase. No more than 5% of the numbers should be off by more than 5% </p>
-->

다음 이미지는 사람 지표가 계산되는 방식과 과거의 동일한 보고서 날짜 범위에 대해 시간이 지남에 따라 줄어드는 방식을 보여 줍니다.

![](assets/people-calculations.png)

이 예에서는 고정된 방문자 세트가 있다고 가정합니다. 과거에 고정된 시간대에 대해 보고서를 실행하면 고정된 방문자 집합이 표시됩니다. Device Graph에서 1주차 왼쪽 그래픽에 표시된 데이터를 출력하는 경우 90명이 표시됩니다. 1주일 후, Device Graph가 다시 실행된 후 새로운 정보가 고려됩니다. 일주일 전에 했던 것과 같은 보고서를 실행하면, 그 사람의 수는 84명으로 줄어들었습니다. Device Graph에서 그룹화해야 하는 장치에 대한 새 정보를 제공했기 때문에 기록이 변경되었습니다.

## 세그먼트를 포함하는 사람 지표 사용 {#section-d03525420dbe48379fd95b230ef05885}

사람 지표와 함께 세그먼트를 사용할 경우 지표 결과가 예상보다 크게 낮아질 수 있습니다. 이 문제는 세그먼테이션에서 이 없기 때문에 발생합니다. *`person`* 컨테이너. 세그먼테이션은 방문자 컨테이너를 사용하며, 방문자 컨테이너는 정의에서 가장 높은 수준의 컨테이너이며 개인이 아닌 디바이스를 기반으로 합니다.

이 문제는 주로 사람 지표로 세그먼트를 스택할 때 발생합니다.

![](assets/people-stacked-segments.png)

세그먼트를 스택하면 세그먼트의 조합을 나타내는 새 세그먼트가 만들어집니다. 다음과 같은 경우 항상 세그먼트 스택이 수행됩니다.

* Analysis Workspace의 다른 세그먼트 맨 위에 세그먼트를 배치합니다. (이러한 연결은 *`And`* 연산자.)
* 다음을 포함하는 단일 세그먼트 적용 *`And`* 연산자.
* 프로젝트 수준 및 테이블 수준 모두에서 세그먼트를 적용합니다.
* 다른 세그먼트와 함께 가상 보고서 세트를 사용합니다.

예를 들어 사람 지표에 다음 세그먼트를 스택한다고 가정해 보겠습니다.

* `Campaign = Spring Promotion`
* `Site Section = Product Overview`

두 세그먼트 모두에 해당하는 사람 수만 *`using a single device`* 카운트됩니다. (사람 지표에는 장치 간에 자격 있는 사람 수가 표시되지 않습니다.)

또한 *`Or`* 연산자는 이 상황에서 권장되지 않습니다. 이렇게 하면 두 세그먼트에 해당하는 사람이 몇 명인지 셀 수 없이 한 사람이나 다른 사람을 본 사람의 수가 생성됩니다.

다음을 참조하십시오 [세그먼트 작성](https://docs.adobe.com/content/help/ko-KR/analytics/components/segmentation/segmentation-workflow/seg-build.html) 을 참조하십시오.

## 장치 유형 {#section-8ab378c84ff34574b9c20fecb3848a86}

Device Co-op 및 People 지표는 보고서 세트에 여러 장치 유형의 데이터가 포함된 경우 Adobe Analytics에서 가장 잘 작동합니다. 예를 들어 동일한 보고서 세트에 웹과 앱 데이터를 결합하면 사용자 지표가 더 강력하고 효과적으로 만들어집니다. 데이터에 디바이스 크로스오버가 많을수록 여러 고유 방문자가 한 사람으로 그룹화될 가능성이 커집니다.

![](assets/people-device-types.png)

## Experience Cloud ID 서비스 범위 {#section-bbf0098cac2e467289e7a644a1dea05c}

Device Co-op를 사용하려면 MCID(Experience Cloud ID) 서비스를 사용하여 디지털 속성을 계측해야 합니다. 보고서 세트의 데이터에 MCID가 없는 방문자가 상당히 포함된 경우 Device Co-op 및 사용자 지표의 효과가 감소됩니다.

<!--
mcdc-people-metric-apply.xml
-->

Analysis Workspace에서 [프로젝트](https://docs.adobe.com/content/help/ko-KR/analytics/analyze/analysis-workspace/build-workspace-project/t-freeform-project.html)을(를) 클릭한 다음 을(를) 드래그합니다. **[!UICONTROL People]** 프로젝트 테이블에 대한 지표:

![](assets/people-metric.png)
