# 롯데리아 촵땡겨체

[배포처 바로가기](https://www.lotteriafont.com/)

&nbsp;

## 웹 폰트

사용하는 `font-family`의 이름은 `LOTTERIA CHAB`입니다.

### HTML

```html
<link rel="stylesheet" href="https://cdn.jsdelivr.net/gh/fonts-archive/LOTTERIACHAB/LOTTERIACHAB.css" type="text/css"/>
```

### CSS `@Import`

```css
@import url('https://cdn.jsdelivr.net/gh/fonts-archive/LOTTERIACHAB/LOTTERIACHAB.css');
```

### CSS `@font-face`

```css
@font-face {
    font-family: 'LOTTERIA CHAB';
    font-weight: normal;
    font-style: normal;
    font-display: swap;
    src: url('https://cdn.jsdelivr.net/gh/fonts-archive/LOTTERIACHAB/LOTTERIACHAB.woff2') format('woff2'),
         url('https://cdn.jsdelivr.net/gh/fonts-archive/LOTTERIACHAB/LOTTERIACHAB.woff') format('woff'),
         url('https://cdn.jsdelivr.net/gh/fonts-archive/LOTTERIACHAB/LOTTERIACHAB.otf') format('opentype'),
         url('https://cdn.jsdelivr.net/gh/fonts-archive/LOTTERIACHAB/LOTTERIACHAB.ttf') format('truetype');
}
```

&nbsp;

## 다이나믹 서브셋

웹폰트의 최적화를 위해 모던 브라우저에서는 글리프를 여러개로 나누어 필요한 부분만 동적으로 파싱하는 다이나믹 서브셋을 제공합니다. 폰트의 용량이 부담된다면 아래 코드를 사용하는 걸 추천합니다.

### HTML

```html
<link rel="stylesheet" href="https://cdn.jsdelivr.net/gh/fonts-archive/LOTTERIACHAB/subsets/LOTTERIACHAB-dynamic-subset.css" type="text/css"/>
```

### CSS

```css
@import url('https://cdn.jsdelivr.net/gh/fonts-archive/LOTTERIACHAB/subsets/LOTTERIACHAB-dynamic-subset.css');
```

&nbsp;

## font-family

어느 브라우저나 시스템 환경에서도 동일한 폰트가 적용되어야 한다면 아래와 같이 구성하는 걸 추천합니다. `-apple-system`과 `BlinkMacSystemFont`는 맥, `Segoe UI`는 윈도우, `Roboto`는 안드로이드의 기본 폰트입니다.


```css
font-family: "LOTTERIA CHAB", -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, Oxygen, Ubuntu, Cantarell, "Open Sans", "Helvetica Neue", sans-serif;
```

&nbsp;

## 라이선스

라이선스는 언제든지 변경될 수 있습니다. 변경사항을 확인하려면 배포처를 방문해 주세요.

```
저작권 
롯데리아 촵땡겨체(LOTTERIA CHAB), 롯데리아 딱붙어체(LOTTERIA 
DDAG)의 지적 재산권을 포함한 모든 권리는 롯데GRS에 있습니다. 
 
사용 범위 
개인 및 기업 사용자를 포함한 모든 사용자에게 무료로 제공합니다. 
(아래 사용 범위 참조) 
 
제한 사항 
서체 파일을 유료로 판매, 임의 수정 및 개작하여 재배포하는 것을 금지하며, 
당사의 이미지를 훼손할 수 있는 불법 사이트나 허위과장 광고, 
기타 공서양속에 반하는 인쇄/광고물에 사용을 금지합니다. 
 
기타 
롯데리아 촵땡겨체, 롯데리아 딱붙어체를 사용한 인쇄물, 광고물(온/오프라인) 등의 
이미지는 롯데GRS 마케팅을 위해 활용될 수 있습니다.
```
