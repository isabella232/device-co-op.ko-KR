---
description: 사람 지표는 Adobe의 Device Graph를 기반으로 하는 사람(또는 장치 그룹) 수입니다. 사람 지표를 적용하여 Analysis Workspace에서 장치 간에 방문자를 식별할 수 있습니다.
seo-description: 사람 지표는 Adobe의 Device Graph를 기반으로 하는 사람(또는 장치 그룹) 수입니다. 사람 지표를 적용하여 Analysis Workspace에서 장치 간에 방문자를 식별할 수 있습니다.
seo-title: 사람 지표
title: 사람 지표
uuid: 8e731779-044d-4d31-a19a-f579a9c8c471
translation-type: tm+mt
source-git-commit: c1d0bc05d3f211fa3e899e98fbcc908be7399031

---


# 사람 지표{#people-metric}

사람 지표는 Adobe의 Device Graph를 기반으로 하는 사람(또는 장치 그룹) 수입니다. 사람 지표를 적용하여 Analysis Workspace에서 장치 간에 방문자를 식별할 수 있습니다.

## People Metric Prerequisites and Considerations {#section-34551d0435fb4b3cb3fad736b7961541}

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
   <td colname="col2"> <p> To use the People metric, become a member of the <a href="http://landing.adobe.com/en/na/events/summit/275658-summit-co-op.html" format="html" scope="external"> Adobe Experience Cloud Device Co-op</a>. Co-op는 개인의 여러 장치(또는 Experience Cloud ID)를 식별합니다. Analytics에서는 이 정보를 활용하여 브랜드와 상호 작용하는 사람들의 수를 통계적으로 유추합니다. 지표는 5% 이내로 정확합니다. </p> <p><b>지역</b>: Device Co-op는 현재 미국과 캐나다에서만 사용할 수 있습니다. 따라서 사람 지표를 평가할 때는 미국과 캐나다에 대한 데이터만 필터링하는 분석에 세그먼트를 적용해야 합니다. </p> <p>매주 Device Graph에서는 협업의 새 버전을 계산하고 사용할 수 있도록 게시합니다. 화요일에는 시스템이 최신 데이터를 수집하고 업데이트된 그래프 버전을 게시합니다. Adobe Experience Cloud 솔루션은 그래프의 최신 버전을 사용합니다. 특히 Analytics의 경우, 변경 내용은 수요일에 읽히고, 변경 사항은 일반적으로 영업일 기준 1일에서 2일 사이에 발생합니다. </p> <p> <p>중요: 그래프가 매주 업데이트되면 사람 지표에 영향을 줄 수 있습니다. 즉, 그래프가 학습되고 업데이트되면 시간 경과에 따라 사람 수가 변경될 수 있습니다. 예를 들어, 오늘 보고서를 실행하여 지난 달에 사람을 카운트한 다음 그래프가 업데이트된 후 1주일 후에 동일한 보고서를 실행하는 경우 내역 사람 수는 약간 변경될 수 있습니다. </p> </p> </td> 
  </tr> 
  <tr> 
   <td colname="col1"> 지표 권한 </td> 
   <td colname="col2"> <p>사람 지표에 대한 액세스 권한이 부여된 경우에만 사람 지표를 사용할 수 있습니다. 관리자는<a href="https://marketing.adobe.com/resources/help/en_US/reference/groups-metrics.html" format="html" scope="external"> 관리 도구에서 지표 권한을</a> 사용자 지정할 수 있습니다. </p> </td> 
  </tr> 
  <tr> 
   <td colname="col1"> IMS 조직에 매핑 </td> 
   <td colname="col2"> <p>사람 지표는 IMSORG에 매핑되는 모든 보고서 세트에 대해 <a href="https://marketing.adobe.com/resources/help/en_US/mcloud/map-report-suite.html" format="html" scope="external"> 활성화됩니다</a>. </p> </td> 
  </tr> 
  <tr> 
   <td colname="col1"> <p>분석 프로젝트/도구 </p> </td> 
   <td colname="col2"> <p><span class="wintitle">Analysis Workspace</span>, <span class="wintitle">애드혹 분석</span>, <span class="wintitle">Report Builder</span>에서 API를 통해 사람 지표를 사용하십시오.  계산된 지표를 포함하여 고유 방문자 수 지표를 사용하는 곳이라면 어디에서든 사용할 수 있습니다.  </p> <p>예를 들어 고유 방문자당 수입 지표를 대체할 인당 수입 지표를 만드십시오.  </p> <p><a href="https://marketing.adobe.com/resources/help/en_US/analytics/analysis-workspace/starter_projects.html" format="html" scope="external">사람 프로젝트 템플릿</a>을 사용하여 Analysis Workspace에서 사람 지표 사용을 시작할 수 있습니다. </p> </td> 
  </tr> 
  <tr> 
   <td colname="col1"> <p>보트 규칙 켜기 </p> </td> 
   <td colname="col2"> <p>특히 사람 지표를 사용할 때 <a href="https://marketing.adobe.com/resources/help/en_US/reference/bot_rules.html" format="html" scope="external">보트 규칙</a>을 켜는 것이 좋습니다. </p> <p>보트가 웹 사이트를 크롤할 때, 보트는 고유 방문자 수를 인위적으로 늘립니다. 보고서 세트에서 보트 트래픽을 제거하면 고유 방문자 수와 사람이라는 지표 모두에서 디지털 속성에 대한 활동을 보다 정확하게 측정할 수 있습니다. </p> <p>그렇게 하려면, <span class="uicontrol">Analytics</span> &gt; <span class="uicontrol">관리</span> &gt; <span class="uicontrol">보고서 세트</span>로 이동합니다. 올바른 보고서 세트를 선택한 다음 <span class="uicontrol">설정 편집</span> &gt; <span class="uicontrol">일반</span> &gt; <span class="uicontrol">보트 규칙</span>으로 이동합니다. </p> </td> 
  </tr> 
  <tr> 
   <td colname="col1"> <p>세그멘테이션 고려 사항 </p> </td> 
   <td colname="col2"> <p> 사람 지표와 함께 세그먼트를 사용할 때 지표 보고는 예상보다 매우 낮을 수 있습니다. </p> <p><a href="../other-solutions/people.md#section-d03525420dbe48379fd95b230ef05885" format="dita" scope="local">세그먼트와 사람 지표 사용</a>을 참조하십시오. </p> </td> 
  </tr> 
 </tbody> 
</table>

## 사람 지표란? {#section-89e2b8f5e80f480391449fc8d1117a6a}

사람 지표는 장치를 사람과 연관시키는 데 도움이 되는 Analytics 보고 지표입니다. 이 지표는 사람 기반 마케팅 보기를 제공하여 모든 장치에서 이루어지는 방문자 활동을 측정할 수 있게 합니다. 이 지표를 고유 방문자 수의 중복 제거 버전으로 생각하십시오. 그러면 이전에 고유 방문자 수를 사용한 분석에 대해 사람 지표를 사용할 수 있습니다.

**장치가 사람입니다**

사람 지표가 이용 가능해지기 전에, 예를 들어 사람이 사이트를 방문하고 세 가지 서로 다른 장치에서 캠페인 또는 브랜드에 참여하고 구매 행위를 할 수 있습니다. 이러한 과정은 수 분 내에 이루어질 수도 있습니다. 구현에 따라 Analytics에서는 각 장치를 고유한 방문자로 보고하고 $30 구매에서 $10를 세 개의 장치에서 발생한 것으로 볼 수 있습니다.

사람 지표를 사용하면 이러한 $30의 구매 행위를 그림과 같이 정확히 한 사람의 구매 결과로 볼 수 있습니다.

![](assets/people-centric-results.png)

**보고서의 정확도 증가**

사람 지표는 여러 장치를 단일 개체로 생각할 수 있도록 해줍니다. 다음의 Analysis Workspace 프로젝트에서는 고유 방문자 수 보고와 사람 보고 간에 증가된 정확도 비교를 보여줍니다.

![](assets/people_report.png)

사람과 고유 방문자 수를 나란히 비교하십시오.

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
   <td colname="col2"> <p>사람 지표는 소비자가 여러 장치를 사용하여 브랜드와 상호 작용한다는 아이디어를 기반으로 합니다. 데이터를 더 많이 분할하거나 세그먼트화할수록 해당 데이터 구획 내에서 동일한 사람이 여러 장치를 사용할 가능성이 작아집니다. </p> </td> 
  </tr> 
  <tr> 
   <td colname="col1"> <p>고유 방문자 수 </p> </td> 
   <td colname="col2"> <p>예를 들어 데이터를 날짜나 시간으로 더 많이 분할할수록 사람과 고유 방문자 수 간의 차이는 작아집니다. Device Co-op의 전체적인 영향을 잘 이해하려면 지난 90일의 날짜 범위를 사용하는 것이 좋습니다 </p> </td> 
  </tr> 
  <tr> 
   <td colname="col1"> <p>압축 </p> </td> 
   <td colname="col2"> <p>단순 계산된 지표를 사용하면 사람 지표가 고유 방문자 수의 백분율로서 얼마나 작은지를 확인할 수 있습니다. 이 지표를 생성하는 방법을 확인하려면 위 표의 "압축" 옆에 있는 정보 아이콘을 클릭하십시오. </p> <p>고유 방문자 수 대신 다른 계산된 지표에서 사람을 사용할 수 있습니다. </p> </td> 
  </tr> 
 </tbody> 
</table>

## 사람 지표는 어떻게 계산됩니까? {#section-0dfb762867e14a7f927796ef3c50592b}

<!--
<p>Analytics uses the HyperLogLog statistical algorithm to calculate People. This means that the smaller the data set, the margin for error may increase. No more than 5% of the numbers should be off by more than 5% </p>
-->

다음 이미지는 사람 지표가 계산되는 방식 및 과거와 동일한 보고서 날짜 범위 내에서 시간이 지남에 따라 사람 지표가 어떻게 감소할 수 있는지 보여줍니다.

![](assets/people-calculations.png)

이 예에서는 고정 방문자 세트가 있다고 가정합니다. 과거의 고정 기간 동안 보고서를 실행하는 경우, 방문자의 고정 세트가 표시됩니다. Device Graph가 첫 번째 주에 왼쪽 그래픽에 표시된 데이터를 출력하는 경우, 90명이 결과로 계산됩니다. 1주일 후 Device Graph의 다음 실행이 수행되면, 계정에 새 정보가 생깁니다. 1주일 전에 수행한 것과 동일한 보고서를 실행하면 사람 수가 84명으로 줄어듭니다. Device Graph가 그룹화해야 하는 장치에 대한 새로운 정보를 제공했으므로 내역이 변경되었습니다.

## 세그먼트와 사람 지표 사용 {#section-d03525420dbe48379fd95b230ef05885}

사람 지표와 함께 세그먼트를 사용할 때 지표 결과는 예상보다 매우 낮을 수 있습니다. 이 문제는 세그멘테이션에 *`person`* 컨테이너가 없기 때문에 발생합니다. 세그멘테이션에서는 방문자 컨테이너를 사용합니다. 방문자 컨테이너는 정의에서 가장 높은 수준의 컨테이너이고 사람이 아니라 장치를 기반으로 합니다.

이 문제는 사람 지표로 세그먼트를 스택할 때 주로 발생합니다.

![](assets/people-stacked-segments.png)

세그먼트 스택을 수행하면 세그먼트의 조합을 나타내는 새로운 세그먼트가 만들어집니다. 세그먼트 스택은 다음의 경우 항상 발생합니다.

* Analysis Workspace에서 다른 세그먼트의 맨 위에 세그먼트를 놓을 때. (이것은 *`And`* 연산자를 포함하는 단일 세그먼트를 적용할 때.)
* Apply a single segment that contains the *`And`* operator.
* 프로젝트 수준과 테이블 수준 모두에서 세그먼트를 적용할 때.
* 다른 세그먼트에서 가상 보고서 세트를 사용할 때.

예를 들어 사람 지표에 대해 다음의 세그먼트를 스택한다고 가정하십시오.

* `Campaign = Spring Promotion`
* `Site Section = Product Overview`

Only the number of people who qualify in both segments *`using a single device`* are counted. (사람 지표는 장치 간에 자격이 되는 사람의 수를 표시하지 않습니다.)

또한 *`Or`* 연산자를 사용하는 것은 이 상황에서는 권장되지 않습니다. 그렇게 하면 두 세그먼트 모두에 대해 자격이 되는 사람의 수를 계산하는 방법이 없어서 어느 한쪽을 본 사람의 수가 생성됩니다.

자세한 내용은 세그멘테이션 도움말에서 [세그먼트 작성](https://marketing.adobe.com/resources/help/en_US/analytics/segment/seg_build.html)을 참조하십시오.

## 장치 유형 {#section-8ab378c84ff34574b9c20fecb3848a86}

Device Co-op와 사람 지표는 보고서 세트에 여러 장치 유형의 데이터가 포함되어 있을 때 Adobe Analytics에서 가장 잘 작동합니다. 예를 들어 동일한 보고서 세트에서 웹과 앱 데이터를 조합하면 사람 지표가 더 강력하고 효과적이 됩니다. 데이터에 장치 크로스오버가 많을수록 복수의 고유 방문자 수가 한 사람으로 그룹화될 가능성이 커집니다.

![](assets/people-device-types.png)

## Experience Cloud ID Service Coverage {#section-bbf0098cac2e467289e7a644a1dea05c}

Device Co-op를 사용하려면 Experience Cloud ID(MCID) 서비스를 사용하여 디지털 속성을 구현해야 합니다. 보고서 세트에 있는 데이터가 MCID 없이 상당한 수의 방문자를 포함하는 경우, Device Co-op와 사람 지표의 효과가 약화됩니다.

<!--
mcdc-people-metric-apply.xml
-->

In Analysis Workspace, create a [project](https://marketing.adobe.com/resources/help/en_US/analytics/analysis-workspace/t_freeform_project.html), then drag the **[!UICONTROL People]** metric to the project table:

![](assets/people-metric.png)

