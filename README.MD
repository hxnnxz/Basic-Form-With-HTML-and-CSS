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
    - [Useful resources](#useful-resources)


## Overview
---

### About the Project
this is a project to see how much do I understand HTML and CSS. Imma check on the list and see what course should I take next time to make any improvement.\
I havent yet give it mobile view, I also want to store or save the data but idk how yet. this project will be upgraded by time. <July sixth>

### Screenshot

![Contact Page](<Screen Shot 2023-07-06 at 00.17.46.png>)
![Additional Page](<Screen Shot 2023-07-06 at 00.17.31.png>)
![Finish Page](<Screen Shot 2023-07-06 at 00.17.01.png>)


### Links

- Solution URL: [Add solution URL here](https://your-solution-url.com)
- Live Site URL: [Add live site URL here](https://your-live-site-url.com)


## My process
---

### Built with

- Semantic HTML5 markup
- CSS
- Flexbox
- CSS Grid
- Web-first workflow
- [Styled Components](https://styled-components.com/) - For styles

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
- it's good to have style guide
- there are lots of helpful source on the internet. try to understand the source code doesnt mean Im cheating :)


### Useful resources

- [YT - Responsive html form tutorial](https://youtu.be/okbByPWS1Xc) - This helped me understand the use of flex-wrap and width: calc();
- [pure css custom checkbox style](https://moderncss.dev/pure-css-custom-checkbox-style/) - mostly helped me to understand the css pseudo-selectors like :before and :focus. this helped understand how to custom the checkbox input with only pure css (using pseudo-selector ahaha).
- [YT - CSS Custom Checkbox List Design | Html CSS](https://youtu.be/jtf6NESiXW8) - helped me to create the checkboxes :))). I was frustrated on how to create the checkbox and style it acording to my initial design. the code (from addInfo.html) :
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

- Github - [hxxnxz](https://github.com/hxnnxz)
- Frontend Mentor - [@meantoes](https://www.frontendmentor.io/profile/meantoes)

### Acknowledgement
this readme is made with FrontendMentor.io's readme-template