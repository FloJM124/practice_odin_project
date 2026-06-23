# Project - Recipes

## Live Demo
https://FloJM124.github.io/odin-recipes

## Static HTML 
Stage one of this project features only **HTML**. 

- The goal is to practice writing semantic HTML, build multi-page navigation using `anchor` links, and structure recipe content clearly with lists.
- The homepage introduces the website and links to three recipe web pages.
- To demonstrate heading order: `h1` element can be used to name the web pages and tell both visitors and search engines what the pages are about, `h2` element as a section heading within the web pages, and `h3` element as a sub-section heading.
- To link between the web pages, the `anchor` element can be used with the `href` attribute holding the destination.
- To upload images to the web pages, the `figure` element can be used as an image container to wrap the images together with their caption. The `figcaption` element can also be used to attribute photographers.
- For the `image` element: `src` attribute points the path to the image file; `alt` attribute describes the image, which is important for accessibility and for when the image fails to load; and `width` and `height` attributes prevent content layout shifts.
- Important text can be marked with the `strong` element and emphasis with the `em` element, which is essential for screen readers on how the text should be read.
- To generate dummy text for the web pages, `lorem` can be used with the paragraph element.

## CSS
Stage two is about styling the structure of a website with **CSS**.

- It's recommended to use an external stylesheet to style HTML elements because it's more flexible, and it allows styling of multiple web pages with just a single stylesheet.
- CSS can change how HTML elements behave in normal flow, for example, by using the `display` property.
- Understanding the box model is important because it shows how elements are structured individually, and also how they interact with one another.
- You can view the box model using the Chrome DevTools, where you can inspect the styles applied (or not applied) to each HTML element on the page.