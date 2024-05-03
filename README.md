# Mi Frontend Mentor - Blog preview card solution 😊

This is a solution to the [Blog preview card challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/blog-preview-card-ckPaj01IcS). Frontend Mentor challenges help you improve your coding skills by building realistic projects.

## Table of contents

-   [Overview](#overview)
    -   [The challenge](#the-challenge)
    -   [Screenshot](#screenshot)
    -   [Links](#links)
-   [My process](#my-process)
    -   [Built with](#built-with)
    -   [What I learned](#what-i-learned)
    -   [Continued development](#continued-development)
-   [Author](#author)
-   [Acknowledgments](#acknowledgments)

## Overview

### The challenge

Users should be able to:

-   See hover and focus states for all interactive elements on the page

### Screenshot 📸

#### Desktop

![](/screenshots/desktop-design.jpeg)

#### Mobile

![](/screenshots/mobile-design.jpeg)

### Links

-   Solution URL: [@Pepekid_blog-preview-card-project](https://github.com/Pepekid/frontendMentor-blog-preview-card)
-   Live Site URL: [@Pepekid_blog-preview-card-page](https://frontend-mentor-pepekid-blog-preview.netlify.app/)

## My process

### Built with

-   Semantic HTML5 markup
-   CSS custom properties
-   Flexbox
-   CSS Grid

### What I learned

Thi project has been built with HTML and CSS, but this time working with the professional tool **Figma**. It has been a little difficult but I've never worked with Figma. This tool seems very powerful tool to create the entire or parts of the web page design.

I've add _tabindex_ attributes to improve accessibility for keyboard users that need to use it.

```html
<section class="content">
	<div class="category" tabindex="0">
		<p class="learning">Learning</p>
	</div>
	<p class="publish-date" tabindex="0">Published 21 Dec 2023</p>
	<h1 class="title" tabindex="0">HTML & CSS foundations</h1>
	<p class="description" tabindex="0">
		These languages are the backbone of every website, defining structure,
		content, and presentation.
	</p>
</section>
```

And then I write some lines in css to stylize the elements when they are focussed or hovered

```css
*:focus {
	border: 1px solid var(--yellow);
}
.content *:not(:first-child):hover,
.author-name:hover {
	cursor: pointer;
	color: var(--yellow);
}
```

### Continued development 🧠🚀

I want to focussed in learning to improve my _CSS_ and useful _HTML_ labels and attributes to do my pages more well-structured.

I also want to practice _Javascript_ and starting learn _React_.

## Author

-   Frontend Mentor - [@Pepekid](https://www.frontendmentor.io/profile/Pepekid)

## Acknowledgments

-   I would like to thank frontend mentor for doing these exercises that help so many people to improve and refine their code for a better future.

-   I would also like to thank Miki for motivating me and for his support.😘

-   I would also like to thank my family for their support and for let me **_"play"_** so many time with the computer. `:)`🤣
