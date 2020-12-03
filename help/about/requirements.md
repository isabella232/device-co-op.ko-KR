---
description: Experience Cloud Device Co-op을 사용하려면 먼저 회사에서 이러한 최소 기준을 충족해야 합니다.
seo-description: Experience Cloud Device Co-op을 사용하려면 먼저 회사에서 이러한 최소 기준을 충족해야 합니다.
seo-title: 멤버십 요구 사항
title: 멤버십 요구 사항
uuid: 4295fa4e-1b9e-4323-bb79-48e548ca1167
translation-type: tm+mt
source-git-commit: 822882d4f9bb9eed7cf116597b62d07bbe94376c
workflow-type: tm+mt
source-wordcount: '460'
ht-degree: 15%

---


# 멤버십 요구 사항{#membership-requirements}

Experience Cloud Device Co-op을 사용하려면 먼저 회사에서 이러한 최소 기준을 충족해야 합니다.

## 요구 사항 {#section-9cbcee3c7b4e4c49b4c0e2b26aec5fe9}

말하세요 [!DNL Adobe representative to get started]. Adobe 담당자가 없는 경우 [Device Co-op 멤버십 포털을](http://landing.adobe.com/en/na/events/summit/275658-summit-co-op.html) 방문하여 온라인 양식을 작성하십시오.

Adobe은 잠재 고객의 Device Co-op에 (1) 참여가 해당 법률을 위반한다고 Adobe이 판단하는 경우 Experience Cloud 장치 Co-op에 대한 잠재 고객의 멤버쉽을 거부할 권리가 있습니다.(2) Adobe 또는 그 고객의 보안 또는 운영에 중대한 위험을 초래합니다.

## Experience Cloud 요구 사항 {#section-76218a50385d43e6b9323e49f598394a}

Co-Op에 참여하려면 Co-Op에 대해 활성화되고 다음 솔루션 [!DNL Adobe Experience Cloud] 과 서비스를 사용해야 합니다.

**솔루션**

지원자는 다음 [!DNL Adobe]해결 방법 중 적어도 하나를 사용해야 합니다.

* [Analytics](http://www.adobe.com/kr/marketing-cloud/web-analytics.html)
* [Audience Manager](http://www.adobe.com/kr/marketing-cloud/data-management-platform.html)
* [Media Optimizer](http://www.adobe.com/marketing-cloud/online-advertising-management.html)
* [Target](http://www.adobe.com/kr/marketing-cloud/testing-targeting.html)

**핵심 서비스**

지원자는 [Experience Cloud ID 서비스를 구현해야 합니다](https://docs.adobe.com/content/help/ko-KR/id-service/using/home.html).

## Adobe 코드 라이브러리 요구 사항 {#section-931a3fca1ce54afd90b88ba032e75f05}

다음 표에는 다양한 [!DNL Experience Cloud] 솔루션 및 서비스에서 사용하는 코드 라이브러리 또는 SDK의 최소 버전이 나와 있습니다. 이 코드를 사용하고 Device Co-op에 참여하려면 이러한 최소 요구 사항을 충족해야 합니다.

>[!TIP]
>
>가장 좋은 방법은 필수 최소 버전이 아닌 최신 코드 버전을 사용하는 것입니다.

**AppMeasurement(Flash)**

버전 4.1이 필요합니다. Flash, [Flex 및 AIR용 AppMeasurement를 참조하십시오](https://github.com/AdobeDocs/analytics-1.4-apis/blob/master/docs/data-insertion-api/index.md).

**AppMeasurement(JavaScript)**

버전 1.5.4가 필요합니다. Flash, [Flex 및 AIR용 AppMeasurement를 참조하십시오](https://docs.adobe.com/content/help/ko-KR/analytics/implementation/js/migrate-from-hcode.html).

**Mobile SDK**

최소 모바일 SDK 요구 사항:

* Android 버전 4.8.3.
* iOS 버전 4.8.5.

Your SDK code must be enabled for the [!DNL Experience Cloud] ID service. Enable and download the latest SDK code for each app in your [Adobe Mobile Services](https://mobilemarketing.adobe.com/) account. See [Configure SDK Visitor ID Service Options](https://docs.adobe.com/content/help/ko-KR/mobile-services/using/manage-app-settings-ug/configuring-app/t-config-visitor.html).

각 SDK에 대해 자신의 요구 사항에 적합한 `visitorSyncIdentifier` 방법을 사용하십시오. 다음을 참조하십시오.

* [Android Experience Cloud ID 서비스 메서드](https://docs.adobe.com/content/help/en/mobile-services/android/experience-cloud-android/mcvid.html)
* [iOS Experience Cloud ID 서비스 메서드](https://docs.adobe.com/content/help/en/mobile-services/ios/exp-cloud-ios/mcvid.html)

**VisitorAPI.js**

버전 1.5.4가 필요합니다.

[!DNL Analytics] 고객은 VisitorAPI.js 라이브러리를 [!DNL Code Manager] JavaScript(신규) 또는 JavaScript(기존) 파일에 있습니다. 액세스 권한이 없는 경우 [고객](https://helpx.adobe.com/kr/marketing-cloud/contact-support.html) 지원 센터에 문의하십시오 [!DNL Code Manager].

**Target 라이브러리**

다음 JavaScript 라이브러리 중 하나가 [!DNL Target] 필요합니다.

* at.js(모든 버전)
* mbox.js 버전 58 이상

