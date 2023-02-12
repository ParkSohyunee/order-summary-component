# Frontend Mentor - Order summary card

[Frontend Mentor](https://www.frontendmentor.io) challenge를 위해 만들어 본 item card project

## Table of contents

- [Overview](#overview)
  - [The challenge](#the-challenge)
  - [Screenshot](#screenshot)
- [My process](#my-process)
  - [Built with](#built-with)
  - [What I learned](#what-i-learned)
- [Author](#author)

## Overview

### The challenge

- style guid, image 재료들을 사용하여 주어진 디자인과 가깝게 build (desktop & mobile)
- CSS를 이용한 hover 효과 적용하기
- only HTML/CSS use

### Screenshot

![desktop_design_completed version](./images/final_desktop_screenshot.jpg)
![mobile_design_completed version](./images/final_mobile_screenshot.jpg)

## My process

### Built with

- Semantic HTML5 markup
- CSS custom properties
- CSS grid and mediaquery
- Desktop-first workflow

### What I learned

- google font 적용 시 (HTML)link tag 또는 (CSS style)@import 코드작성하고, 사용할 font option 모두 명시 
- body에 적용한 font size, font family가 button tag에 상속되지 않아서 inherit 키워드를 사용

```html
<h1><button class="payment-button" style="font: inherit;">#</button></h1>
```

- css flex, space-between 사용하여 contents 정렬하고, 'margrin'으로 space간격 조정

```css
.item {
  display: flex;
  flex-direction: row;
  justify-content: space-between;
  align-items: center;
}
```
## Author

- GitHub - [GitHub](https://github.com/ParkSohyunee)
- Frontend Mentor - [@yParkSohyunee](https://www.frontendmentor.io/profile/ParkSohyunee)
