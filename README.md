# Gorani Documentation

GitHub Pages에서 Gorani 프로젝트들의 DocC 문서를 배포하는 저장소입니다.

## Site

- https://docs.gorani.me

## Documentation

- [LaunchingView](https://docs.gorani.me/LaunchingView/documentation/launchingview/)
- [LaunchingService](https://docs.gorani.me/LaunchingService/documentation/launchingservice/)
- [KoreanLunarSolarConverter](https://docs.gorani.me/KoreanLunarSolarConverter/documentation/koreanlunarsolarconverter/)
- [JailbreakDetector](https://docs.gorani.me/JailbreakDetector/documentation/jailbreakdetector/)
- [MaterialDesignColor](https://docs.gorani.me/MaterialDesignColor/documentation/materialdesigncolorcore/)

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
`-- MaterialDesignColor/
    |-- documentation/
    |-- data/
    |-- css/
    `-- js/
```

루트 `index.html`은 각 문서 폴더의 시작 페이지로 연결하는 임시 허브입니다.

## Notes

- `.nojekyll`을 유지해서 DocC의 `_` 경로와 정적 파일이 GitHub Pages에서 그대로 제공되게 합니다.
- 이 저장소는 문서 배포 전용이므로 `.reviewbot.yml`에서 코드 리뷰를 비활성화합니다.
