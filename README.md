# GenJyuuGothic-webfont
---

- 字型來源：http://jikasei.me/font/genjyuu/
- demo: https://jsfiddle.net/OlgaH/ts4fxan2/

---
### 字重 font-weight

- ExtraLight : 100
- Light      : 200
- Normal     : 300
- Regular    : 400
- Medium     : 500
- Bold       : 700
- Heavy      : 900

### 已轉換類型
- Heavy

### webfont 用法

#### Heavy 900
```CSS
@font-face {
	font-family: 'GenJyuuGothic';
  font-style: normal;
  font-weight: 900;
  font-display: swap;
	src: url(https://cdn.jsdelivr.net/gh/marsnow/GenJyuuGothic-webfont@1.0/Heavy/GenJyuuGothic-Heavy.eot); /* IE9 Compat Modes */
	src: url(https://cdn.jsdelivr.net/gh/marsnow/GenJyuuGothic-webfont@1.0/Heavy/GenJyuuGothic-Heavy.eot?#iefix) format("embedded-opentype"), /* IE6-IE8 */
	url(https://cdn.jsdelivr.net/gh/marsnow/GenJyuuGothic-webfont@1.0/Heavy/GenJyuuGothic-Heavy.woff) format("woff"), /* Modern Browsers */
	url(https://cdn.jsdelivr.net/gh/marsnow/GenJyuuGothic-webfont@1.0/Heavy/GenJyuuGothic-Heavy.ttf) format("truetype"), /* Safari, Android, iOS */
	url(https://cdn.jsdelivr.net/gh/marsnow/GenJyuuGothic-webfont@1.0/Heavy/GenJyuuGothic-Heavy.svg#SealmemoryHeader) format("svg"); /* Legacy iOS */
}

.class {
  font-family: 'GenJyuuGothic';
  font-weight: 900;
}
```
