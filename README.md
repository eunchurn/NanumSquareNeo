# Nanum Square Neo Font

2022.10.07 네이버에서 발표한 새로운 폰트 [나눔스퀘어 네오](https://campaign.naver.com/nanumsquare_neo) 웹폰트 패키지.

## Usage

### `link` tag

- Fixed weight

```html
<link
  rel="stylesheet"
  type="text/css"
  href="https://cdn.jsdelivr.net/gh/eunchurn/NanumSquareNeo@0.0.1/nanumsquareneo.css"
/>
```

- Variable weight

```html
<link
  rel="stylesheet"
  type="text/css"
  href="https://cdn.jsdelivr.net/gh/eunchurn/NanumSquareNeo@0.0.1/nanumsquareneovar.css"
/>
```

### `import`

- Fixed weight

```css
@import url(https://cdn.jsdelivr.net/gh/eunchurn/NanumSquareNeo@0.0.1/nanumsquareneo.css);
```

- Variable weight

```css
@import url(https://cdn.jsdelivr.net/gh/eunchurn/NanumSquareNeo@0.0.1/nanumsquareneovar.css);
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
