---
description: Experience Cloud Device Co-op을 사용하려면 먼저 회사가 이러한 최소 표준을 충족해야 합니다.
seo-description: Experience Cloud Device Co-op을 사용하려면 먼저 회사가 이러한 최소 표준을 충족해야 합니다.
seo-title: 멤버십 요구 사항
title: 멤버십 요구 사항
uuid: 4295fa4e-1b9e-4323-bb79-48e548ca1167
translation-type: tm+mt
source-git-commit: 1ab7be570ea63645c6d6065341d31bf170f79715
workflow-type: tm+mt
source-wordcount: '434'
ht-degree: 16%

---


# 멤버십 요구 사항{#membership-requirements}

Experience Cloud Device Co-op을 사용하려면 먼저 회사가 이러한 최소 표준을 충족해야 합니다.

## 요구 사항 {#section-9cbcee3c7b4e4c49b4c0e2b26aec5fe9}

[!DNL Adobe representative to get started]에 문의하십시오. Adobe이 잠재 고객의 Device Co-op에 참여하는 것이 해당 법률을 위반하는 것이라고 판단하는 경우, Adobe은 Experience Cloud 장치 Co-op에 대한 잠재 고객의 멤버쉽을 거부할 권리를 가집니다.(2) Adobe 또는 그 고객의 보안 또는 운영에 중대한 위험을 초래합니다.

## Experience Cloud 요구 사항 {#section-76218a50385d43e6b9323e49f598394a}

[!DNL Adobe Experience Cloud]에 대해 활성화되고 다음 솔루션 및 서비스를 사용하여 Co-op에 참여해야 합니다.

**솔루션**

지원자는 다음 [!DNL Adobe]해결 방법 중 적어도 하나를 사용해야 합니다.

* [Analytics](http://www.adobe.com/kr/marketing-cloud/web-analytics.html)
* [Audience Manager](http://www.adobe.com/kr/marketing-cloud/data-management-platform.html)
* [Media Optimizer](http://www.adobe.com/marketing-cloud/online-advertising-management.html)
* [Target](http://www.adobe.com/marketing-cloud/testing-targeting.html)

**핵심 서비스**

지원자는 [Experience Cloud ID 서비스](https://docs.adobe.com/content/help/ko-KR/id-service/using/home.html)를 구현해야 합니다.

## Adobe 코드 라이브러리 요구 사항 {#section-931a3fca1ce54afd90b88ba032e75f05}

다음 표는 다양한 [!DNL Experience Cloud] 솔루션 및 서비스에서 사용하는 코드 라이브러리 또는 SDK의 최소 버전을 보여 줍니다. 이 코드를 사용하고 Device Co-op에 참여하려면 이러한 최소 요구 사항을 충족해야 합니다.

>[!TIP]
>
>우수 사례로, 필수 최소 버전이 아닌 최신 코드 버전을 사용하는 것이 좋습니다.

**AppMeasurement(Flash)**

버전 4.1이 필요합니다. Flash, Flex 및 AIR](https://github.com/AdobeDocs/analytics-1.4-apis/blob/master/docs/data-insertion-api/index.md)에 대한 [AppMeasurement를 참조하십시오.

**AppMeasurement(JavaScript)**

버전 1.5.4이 필요합니다. Flash, Flex 및 AIR](https://docs.adobe.com/content/help/ko-KR/analytics/implementation/js/migrate-from-hcode.html)에 대한 [AppMeasurement를 참조하십시오.

**Mobile SDK**

최소 모바일 SDK 요구 사항:

* Android 버전 4.8.3.
* iOS 버전 4.8.5.

SDK 코드가 [!DNL Experience Cloud] ID 서비스에 대해 활성화되어 있어야 합니다. [Adobe Mobile Services](https://mobilemarketing.adobe.com/) 계정에서 각 앱에 대한 최신 SDK 코드를 활성화하고 다운로드합니다. [SDK 방문자 ID 서비스 옵션 구성](https://docs.adobe.com/content/help/ko-KR/mobile-services/using/manage-app-settings-ug/configuring-app/t-config-visitor.html)을 참조하십시오.

각 SDK에 대해 필요에 맞는 적절한 `visitorSyncIdentifier` 메서드를 사용합니다. 다음을 참조하십시오.

* [Android Experience Cloud ID 서비스 메서드](https://docs.adobe.com/content/help/en/mobile-services/android/experience-cloud-android/mcvid.html)
* [iOS Experience Cloud ID 서비스 메서드](https://docs.adobe.com/content/help/en/mobile-services/ios/exp-cloud-ios/mcvid.html)

**VisitorAPI.js**

1.5.4 버전이 필요합니다.

[!DNL Analytics] 고객은 VisitorAPI.js 라이브러리를  [!DNL Code Manager] JavaScript(신규) 또는 JavaScript(기존) 파일에 있습니다. [!DNL Code Manager]에 대한 액세스 권한이 없는 경우 [고객 지원 센터](https://helpx.adobe.com/kr/marketing-cloud/contact-support.html)에 문의하십시오.

**Target 라이브러리**

다음 [!DNL Target] JavaScript 라이브러리 중 하나가 필요합니다.

* at.js(모든 버전)
* mbox.js 버전 58 이상

