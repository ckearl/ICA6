# ICA 6: SVGs and More
## Introduction
This ICA is about implementing SVGs and other visual HTML elements in a webpage. The goal is to implement these new elements in the base webpage.

## Instructions
 There will be five tasks to complete in this ICA. Each task will require you to implement a new visual element in the base webpage. Each task is worth two points. The tasks are as follows:
 - Q1. Draw an svg logo and put it as the .header-logo div. Wrap the svg in an `<a>` with href referencing this page 
 - Q2. use a `<video>` to insert a video to autoplay. 
 - Q2 cont. Add paragraph text to the div below about the video you choose. 
 - Q3. Style this button both for original styles and for the styles to change `:onhover`. 
 - Q4. Add a preformatted SVG image of a section break (some design) to make a more smooth transition between sections. Use an online SVG generator to create this SVG, and have the colors match the page.
 - Q5. Copy the webaddress or iframe architecture from a website of your choice and insert it to the content of the `.iframe` div

## Resources
 - [Haikei SVG Shape Generator](https://haikei.app/)
 - [Shape Divider SVG Generator](https://www.shapedivider.app/)

---
## SVG
SVG stands for Scalable Vector Graphics. It is a image format for two-dimensional graphics with support for interactivity and animation. 

There are many use cases for SVGs, some of the most common are:
 - Logos
 - Icons
 - Illustrations
 - Animations
 - Backgrounds

SVGs are a great way to add visual elements to a webpage. They are scalable, meaning they can be resized without losing quality. They are also lightweight, meaning they don't take up much space and don't require much computational power to render on a webpage.

### SVG Syntax
The SVG syntax is similar to HTML, but with some differences. The most important elements in SVG are:
 - `<svg>`: The root element of an SVG document.
 - `<rect>`: A rectangle.
 - `<circle>`: A circle.
 - `<ellipse>`: An ellipse.
 - `<line>`: A line.
 - `<polyline>`: A polyline.
 - `<polygon>`: A polygon.
 - `<path>`: A path.
 - `<text>`: Text.
 - `<g>`: A group of elements.

`<path>` is the most powerful and flexible element in SVG. It can be used to create complex shapes and designs. It uses a special syntax to define the shape of the path.


## Video
The `<video>` element is used to embed video content in a webpage. It is a relatively new element, and is supported by all modern browsers. The `<video>` element has many attributes and methods that can be used to control the video, such as `autoplay`, `controls`, `loop`, `muted`, `play()`, `pause()`, `currentTime`, and many more.

```html
<video width="320" height="240" controls>
  <source src="movie.mp4" type="video/mp4">
  <source src="movie.ogg" type="video/ogg">
  Your browser does not support the video tag.
</video>
  ```

## Iframe
The `<iframe>` element is used to embed another webpage into the current webpage. It is a powerful element that can be used to display content from other websites, such as maps, videos, and social media feeds. The `<iframe>` element has many attributes and methods that can be used to control the content, such as `src`, `width`, `height`, `sandbox`, `allow`, and many more.

```html
<iframe src="https://www.w3schools.com" title="W3Schools Free Online Web Tutorials"></iframe>
```

## :hover
The `:hover` pseudo-class is one of many CSS pseudo-classes that can be used within CSS to modify styles in response to user actions. The `:hover` pseudo-class is used to apply styles to an element when the user hovers over it with the mouse. It is a powerful tool that can be used to create interactive and engaging user interfaces. The `:hover` pseudo-class can be used to change the color, size, position, and many other properties of an element when the user hovers over it.

```css
.button {
  background-color: blue;
  color: white;
  padding: 10px 20px;
  border: none;
  cursor: pointer;
}
.button:hover {
  background-color: red;
  color: white;
}
```
