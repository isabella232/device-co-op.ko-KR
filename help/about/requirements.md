---
description: Experience Cloud 장치 Co-op 사용을 시작하려면 먼저 귀사에서 이러한 최소 표준을 충족해야 합니다.
seo-description: Your company must meet these minimum standards before you can start using the Experience Cloud Device Co-op.
seo-title: Membership requirements
title: 멤버십 요구 사항
uuid: 4295fa4e-1b9e-4323-bb79-48e548ca1167
exl-id: 923ce9c5-7716-4c5a-95f2-05a81a05c9cf
source-git-commit: 573744525fcc00f35540af9ffec46530111940ed
workflow-type: tm+mt
source-wordcount: '415'
ht-degree: 17%

---

# 멤버십 요구 사항{#membership-requirements}

Experience Cloud 장치 Co-op 사용을 시작하려면 먼저 귀사에서 이러한 최소 표준을 충족해야 합니다.

## 요구 사항 {#section-9cbcee3c7b4e4c49b4c0e2b26aec5fe9}

다음 사용자에게 문의하십시오. [!DNL Adobe representative to get started]. Adobe은 Adobe이 잠재 고객의 장치 Co-op 참여가 (1) 관련 법을 위반하거나 (2) Adobe 또는 고객의 보안 또는 운영에 중대한 위험을 초래할 수 있다고 판단하는 경우, Experience Cloud 장치 Co-op에 대한 잠재 고객 멤버십을 거부할 권리를 보유합니다.

## Experience Cloud 요구 사항 {#section-76218a50385d43e6b9323e49f598394a}

다음에 대해 활성화되어야 합니다. [!DNL Adobe Experience Cloud] 다음 솔루션 및 서비스를 사용하여 co-op에 참여하십시오.

**솔루션**

지원자는 다음 중 하나 이상을 사용해야 합니다 [!DNL Adobe]솔루션:

* [Analytics](http://www.adobe.com/kr/marketing-cloud/web-analytics.html)
* [Audience Manager](http://www.adobe.com/kr/marketing-cloud/data-management-platform.html)
* [Media Optimizer](http://www.adobe.com/marketing-cloud/online-advertising-management.html)
* [Target](http://www.adobe.com/kr/marketing-cloud/testing-targeting.html)

**핵심 서비스**

지원자는 다음을 이행해야 합니다. [Experience Cloud ID 서비스](https://docs.adobe.com/content/help/ko/id-service/using/home.html).

## Adobe 코드 라이브러리 요구 사항 {#section-931a3fca1ce54afd90b88ba032e75f05}

다음 표에는 여러 코드에서 사용하는 코드 라이브러리 또는 SDK의 최소 버전이 나와 있습니다 [!DNL Experience Cloud] 솔루션 및 서비스 이 코드를 사용하고 Device Co-op에 참여하려는 경우 이러한 최소 요구 사항을 충족하는지 확인하십시오.

>[!TIP]
>
>필요한 최소 코드 버전보다 최신 코드 버전을 사용하는 것이 좋습니다.

**AppMeasurement(Flash)**

버전 4.1이 필요합니다. 다음을 참조하십시오 [Flash, Flex 및 AIR용 AppMeasurement](https://github.com/AdobeDocs/analytics-1.4-apis/blob/master/docs/data-insertion-api/index.md).

**AppMeasurement(JavaScript)**

버전 1.5.4가 필요합니다. 다음을 참조하십시오 [Flash, Flex 및 AIR용 AppMeasurement](https://docs.adobe.com/content/help/ko-KR/analytics/implementation/js/migrate-from-hcode.html).

**Mobile SDK**

최소 모바일 SDK 요구 사항:

* Android 버전 4.8.3.
* iOS 버전 4.8.5.

에 대해 SDK 코드를 활성화해야 합니다. [!DNL Experience Cloud] ID 서비스 의 각 앱에 대해 최신 SDK 코드를 활성화하고 다운로드합니다. [Adobe Mobile Services](https://mobilemarketing.adobe.com/) 계정입니다. 다음을 참조하십시오 [SDK 방문자 ID 서비스 옵션 구성](https://docs.adobe.com/content/help/ko-KR/mobile-services/using/manage-app-settings-ug/configuring-app/t-config-visitor.html).

각 SDK에 대해 적절한 를 사용합니다 `visitorSyncIdentifier` 필요에 맞는 방법입니다. 다음을 참조하십시오.

* [Android Experience Cloud ID 서비스 메서드](https://docs.adobe.com/content/help/en/mobile-services/android/experience-cloud-android/mcvid.html)
* [iOS Experience Cloud ID 서비스 메서드](https://docs.adobe.com/content/help/en/mobile-services/ios/exp-cloud-ios/mcvid.html)

**VisitorAPI.js**

버전 1.5.4가 필요합니다.

[!DNL Analytics] 고객은 다음 위치에서 VisitorAPI.js 라이브러리를 다운로드할 수 있습니다. [!DNL Code Manager]. JavaScript (신규) 또는 JavaScript (기존) 파일에 있습니다. 연락처 [고객 지원 센터](https://helpx.adobe.com/kr/marketing-cloud/contact-support.html) 에 대한 액세스 권한이 없는 경우 [!DNL Code Manager].

**Target 라이브러리**

다음 중 하나가 필요합니다. [!DNL Target] JavaScript 라이브러리:

* at.js(임의 버전)
* mbox.js 버전 58 이상
