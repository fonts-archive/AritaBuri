# 아리따 부리

[배포처 바로가기](https://www.apgroup.com/int/ko/about-us/visual-identity/arita-typeface/arita-typeface.html)

&nbsp;

## 웹 폰트

사용하는 `font-family`의 이름은 `Arita Buri`입니다.

### HTML

```html
<link rel="stylesheet" href="https://cdn.jsdelivr.net/gh/fonts-archive/AritaBuri/AritaBuri.css" type="text/css"/>
```

### CSS `@Import`

```css
@import url('https://cdn.jsdelivr.net/gh/fonts-archive/AritaBuri/AritaBuri.css');
```

### CSS `@font-face`

```css
@font-face {
    font-family: 'Arita Buri';
    font-weight: 100;
    font-style: normal;
    font-display: swap;
    src: url('https://cdn.jsdelivr.net/gh/fonts-archive/AritaBuri/AritaBuri-Thin.woff2') format('woff2'),
         url('https://cdn.jsdelivr.net/gh/fonts-archive/AritaBuri/AritaBuri-Thin.otf') format('opentype');
}
@font-face {
    font-family: 'Arita Buri';
    font-weight: 300;
    font-style: normal;
    font-display: swap;
    src: url('https://cdn.jsdelivr.net/gh/fonts-archive/AritaBuri/AritaBuri-Light.woff2') format('woff2'),
         url('https://cdn.jsdelivr.net/gh/fonts-archive/AritaBuri/AritaBuri-Light.otf') format('opentype');
}
@font-face {
    font-family: 'Arita Buri';
    font-weight: 500;
    font-style: normal;
    font-display: swap;
    src: url('https://cdn.jsdelivr.net/gh/fonts-archive/AritaBuri/AritaBuri-Medium.woff2') format('woff2'),
         url('https://cdn.jsdelivr.net/gh/fonts-archive/AritaBuri/AritaBuri-Medium.otf') format('opentype');
}
@font-face {
    font-family: 'Arita Buri';
    font-weight: 600;
    font-style: normal;
    font-display: swap;
    src: url('https://cdn.jsdelivr.net/gh/fonts-archive/AritaBuri/AritaBuri-SemiBold.woff2') format('woff2'),
         url('https://cdn.jsdelivr.net/gh/fonts-archive/AritaBuri/AritaBuri-SemiBold.otf') format('opentype');
}
@font-face {
    font-family: 'Arita Buri';
    font-weight: 700;
    font-style: normal;
    font-display: swap;
    src: url('https://cdn.jsdelivr.net/gh/fonts-archive/AritaBuri/AritaBuri-Bold.woff2') format('woff2'),
         url('https://cdn.jsdelivr.net/gh/fonts-archive/AritaBuri/AritaBuri-Bold.otf') format('opentype');
}
```

&nbsp;

## 다이나믹 서브셋

웹폰트의 최적화를 위해 모던 브라우저에서는 글리프를 여러개로 나누어 필요한 부분만 동적으로 파싱하는 다이나믹 서브셋을 제공합니다. 폰트의 용량이 부담된다면 아래 코드를 사용하는 걸 추천합니다.

### HTML

```html
<link rel="stylesheet" href="https://cdn.jsdelivr.net/gh/fonts-archive/AritaBuri/subsets/AritaBuri-dynamic-subset.css" type="text/css"/>
```

### CSS

```css
@import url('https://cdn.jsdelivr.net/gh/fonts-archive/AritaBuri/subsets/AritaBuri-dynamic-subset.css');
```

&nbsp;

## font-family

어느 브라우저나 시스템 환경에서도 동일한 폰트가 적용되어야 한다면 아래와 같이 구성하는 걸 추천합니다. `-apple-system`과 `BlinkMacSystemFont`는 맥, `Segoe UI`는 윈도우, `Roboto`는 안드로이드의 기본 폰트입니다.



```css
font-family: "Arita Buri", -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, Oxygen, Ubuntu, Cantarell, "Open Sans", "Helvetica Neue", sans-serif;
```

&nbsp;

## 라이선스

라이선스는 언제든지 변경될 수 있습니다. 변경사항을 확인하려면 배포처를 방문해 주세요.

```
사용이 금지되는 상업적 사용의 예 
1. 판매용 제품 및 포장용 상자에의 사용 
2. CI 또는 BI로의 사용 
 
저작권자를 밝히고 사용이 가능한 예 
1. 출판용 서책 
2. 판매용이 아닌 각종 인쇄물 
3. 기업을 대표하는 Website 디자인 
“이 제작물은 아모레퍼시픽의 아리따글꼴을 사용하여 디자인 되었습니다.” 
라는 문안을 6px 이상의 size로 명기하시면 사용이 가능합니다.
```
