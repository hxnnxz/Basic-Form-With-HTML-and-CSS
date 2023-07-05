# Basic Form - Created with HTML and CSS

## Table of contents

- [Overview](#overview)
  - [About the Project](#About-the-Project)
  - [Screenshot](#screenshot)
  - [Links](#links)
- [My process](#my-process)
  - [Built with](#built-with)
  - [What I learned](#what-i-learned)
  - [Useful resources](#useful-resources)
- [Author](#author)
    - [Acknowledgement](#Acknowledgement)


## Overview
---

### About the Project
this is a project to see how much do I understand HTML and CSS. Imma check the list and see what course should I take next time to make any improvements.\
I havent yet given it mobile view, I also want to store or save the data but idk how yet. this project will be upgraded over time. <July sixth>

### Screenshot
![Contact page](<src/screenshots/Screen Shot 2023-07-06 at 00.17.46.png>)
![Additional Design page](<src/screenshots/Screen Shot 2023-07-06 at 00.17.31.png>)
![Finish page](<src/screenshots/Screen Shot 2023-07-06 at 01.51.56.png>)

### Links

- [solution URL](https://github.com/hxnnxz/Basic-Form-With-HTML-and-CSS)
- [Live Site URL](https://hxnnxz.github.io/Basic-Form-With-HTML-and-CSS/index.html)


## My process
---

### Built with

- Semantic HTML5 markup
- CSS
- Flexbox
- CSS Grid
- Web-first workflow

### What I learned

- html form types
- how to style input types
- use outline instead of border when you want to style the field
- finally understand the use of flex-wrap and
```css
form .center {
    display: flex;
    flex-wrap: wrap;
    justify-content: space-between;
}
```

- the use of calc in width property

```css
/* GIVING THE INPUT WIDTH */
form .center .inputs {
    margin: 20px 0 12px 0;
    width: calc(100% / 2 - 20px);
}
```
- knowing the difference between all css pseudo-selectors
- how to write .md file haha
- it's good to have a style guide
- there are lots of useful sources on the internet. try to understand the source code doesnt mean Im cheating :)


### Useful resources

- [YT - Responsive html form tutorial](https://youtu.be/okbByPWS1Xc) - This helped me understand the use of flex-wrap and width: calc();
- [pure css custom checkbox style](https://moderncss.dev/pure-css-custom-checkbox-style/) - mostly helped me to understand the css pseudo-selectors like :before and :focus. this helped me know how to custom the checkbox input with only pure css (using pseudo-selector ahaha).
- [YT - CSS Custom Checkbox List Design | Html CSS](https://youtu.be/jtf6NESiXW8) - helped me to create the checkboxes :))). I was frustrated with creating the checkboxes and styling it according to my initial design. the code (from addInfo.html) :
```html
<div class="checks">
    <label>
        <input type="checkbox" name="skill" value="on">
        <span>FrontEnd</span>
    </label>
</div>
```

## Author
---

- GitHub - [hxxnxz](https://github.com/hxnnxz)
- Frontend Mentor - [@meantoes](https://www.frontendmentor.io/profile/meantoes)

### Acknowledgement
this readme is made with FrontendMentor.io's readme-template
