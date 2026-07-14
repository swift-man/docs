# Gorani Documentation

GitHub Pages에서 Gorani 프로젝트들의 DocC 및 Dokka API 문서를 배포하는 저장소입니다.

## Site

- https://docs.gorani.me

## Documentation

- [LaunchingView](https://docs.gorani.me/LaunchingView/documentation/launchingview/)
- [LaunchingService](https://docs.gorani.me/LaunchingService/documentation/launchingservice/)
- [LaunchingService Android](https://docs.gorani.me/LaunchingService-Android/)
- [KoreanLunarSolarConverter](https://docs.gorani.me/KoreanLunarSolarConverter/documentation/koreanlunarsolarconverter/)
- [JailbreakDetector](https://docs.gorani.me/JailbreakDetector/documentation/jailbreakdetector/)
- [MaterialDesignColor](https://docs.gorani.me/MaterialDesignColor/documentation/materialdesigncolorcore/)
- [AnimateNumberText](https://docs.gorani.me/AnimateNumberText/documentation/animatenumbertext/)
- [KoreanKeyboardCore](https://docs.gorani.me/KoreanKeyboardCore/documentation/koreankeyboardcore/)
- [AppIconChanger](https://docs.gorani.me/AppIconChanger/documentation/appiconchanger/)
- [LocaleSupport](https://docs.gorani.me/LocaleSupport/documentation/localesupport/)
- [OverflowMenuView](https://docs.gorani.me/OverflowMenuView/documentation/overflowmenuui/)
- [ShimmerUI](https://docs.gorani.me/ShimmerUI/documentation/shimmerui/)
- [RecordsCalendarUI](https://docs.gorani.me/RecordsCalendarUI/documentation/recordscalendarui/)
- [BlobBackgroundView](https://docs.gorani.me/BlobBackgroundView/documentation/blobbackgroundview/)
- [MailComposeView](https://docs.gorani.me/MailComposeView/documentation/mailcomposeview/)
- [WidgetGuideView](https://docs.gorani.me/WidgetGuideView/documentation/widgetguideview/)
- [GoogleStyleSwiftUI](https://docs.gorani.me/GoogleStyleSwiftUI/documentation/googlestyleswiftui/)
- [CurvedLabel](https://docs.gorani.me/CurvedLabel/documentation/curvedlabel/)

## Structure

각 프로젝트 문서는 저장소 루트의 프로젝트명 폴더 아래에 배포합니다.

```text
.
|-- index.html
|-- LaunchingView/
|   |-- documentation/
|   |-- data/
|   |-- css/
|   `-- js/
|-- LaunchingService/
|   |-- documentation/
|   |-- data/
|   |-- css/
|   `-- js/
|-- LaunchingService-Android/
|   |-- index.html
|   |-- scripts/
|   |-- styles/
|   `-- images/
|-- KoreanLunarSolarConverter/
|   |-- documentation/
|   |-- data/
|   |-- css/
|   `-- js/
|-- JailbreakDetector/
|   |-- documentation/
|   |-- data/
|   |-- css/
|   `-- js/
|-- MaterialDesignColor/
|   |-- documentation/
|   |-- data/
|   |-- css/
|   `-- js/
|-- AnimateNumberText/
|   |-- documentation/
|   |-- data/
|   |-- css/
|   `-- js/
|-- KoreanKeyboardCore/
|   |-- documentation/
|   |-- data/
|   |-- css/
|   `-- js/
|-- AppIconChanger/
|   |-- documentation/
|   |-- data/
|   |-- css/
|   `-- js/
|-- LocaleSupport/
|   |-- documentation/
|   |-- data/
|   |-- css/
|   `-- js/
|-- OverflowMenuView/
|   |-- documentation/
|   |-- data/
|   |-- css/
|   `-- js/
|-- ShimmerUI/
|   |-- documentation/
|   |-- data/
|   |-- css/
|   `-- js/
|-- RecordsCalendarUI/
|   |-- documentation/
|   |-- data/
|   |-- css/
|   `-- js/
|-- BlobBackgroundView/
|   |-- documentation/
|   |-- data/
|   |-- css/
|   `-- js/
|-- MailComposeView/
|   |-- documentation/
|   |-- data/
|   |-- css/
|   `-- js/
|-- WidgetGuideView/
|   |-- documentation/
|   |-- data/
|   |-- css/
|   `-- js/
|-- GoogleStyleSwiftUI/
|   |-- documentation/
|   |-- data/
|   |-- css/
|   `-- js/
`-- CurvedLabel/
    |-- documentation/
    |-- data/
    |-- css/
    `-- js/
```

루트 `index.html`은 각 문서 폴더의 시작 페이지로 연결하는 임시 허브입니다.

## Notes

- `.nojekyll`을 유지해서 DocC와 Dokka의 정적 파일이 GitHub Pages에서 그대로 제공되게 합니다.
- Swift 패키지는 DocC로, Android 라이브러리는 Dokka로 문서를 생성하며 각 원본 저장소의 배포 워크플로가 이 저장소의 전용 폴더를 갱신합니다.
- 이 저장소는 문서 배포 전용이므로 `.reviewbot.yml`에서 코드 리뷰를 비활성화합니다.
