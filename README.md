# Nanum Square Neo WebFont

[![pages-build-deployment](https://github.com/eunchurn/NanumSquareNeo/actions/workflows/pages/pages-build-deployment/badge.svg)](https://github.com/eunchurn/NanumSquareNeo/actions/workflows/pages/pages-build-deployment) [![Publish Package to npmjs](https://github.com/eunchurn/NanumSquareNeo/actions/workflows/publish.yml/badge.svg)](https://github.com/eunchurn/NanumSquareNeo/actions/workflows/publish.yml)

2022.10.07 네이버에서 발표한 새로운 폰트 [나눔스퀘어 네오](https://campaign.naver.com/nanumsquare_neo) 웹폰트 패키지.

## Usage

### `link` tag

- Fixed weight

```html
<link
  rel="stylesheet"
  type="text/css"
  href="https://cdn.jsdelivr.net/npm/nanumsquareneo@0.0.5/nanumsquareneo.css"
/>
```

- Variable weight

```html
<link
  rel="stylesheet"
  type="text/css"
  href="https://cdn.jsdelivr.net/npm/nanumsquareneo@0.0.5/nanumsquareneovar.css"
/>
```

### `import`

- Fixed weight

```css
@import url(https://cdn.jsdelivr.net/npm/nanumsquareneo@0.0.5/nanumsquareneo.css);
```

- Variable weight

```css
@import url(https://cdn.jsdelivr.net/npm/nanumsquareneo@0.0.5/nanumsquareneovar.css);
```

## Font Family

- Fixed weight

```css
body {
  font-family: "NanumSquareNeo", sans-serif;
}
.light {
  font-weight: 100;
}
.regular {
  font-weight: 300;
}
.bold {
  font-weight: 500;
}
.extra-bold {
  font-weight: 700;
}
.heavy {
  font-weight: 800;
}
```

- Variable weight

```css
body {
  font-family: "NanumSquareNeoVar", sans-serif;
}
.variable {
  font-weight: var(--text-weight);
  font-variation-settings: "wght" var(--text-weight);
}
```
