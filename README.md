# TC Loading

This is a simple pure CSS loading animation. It is also possible to customize the size, color, thickness and timing of the animation.

## Supported browsers

Due to the use of simple CSS codes, different browsers have no problem to displaying it.

## Installation

- Include the CSS stylesheet at the end of `<head>` element:

```html
<link rel="stylesheet" href="/path/to/style.css" />
```

- If you want to use as a page loading, put this `HTML` codes at the end of `<body>` tag in the page want:

```html
<div id="tc_loading">
  <div class="tc_loading"></div>
</div>
```

- But if you want to use as inline loading, put this `HTML` codes in the place you want:

```html
<div class="tc_loading"></div>
```

## Settings:

- You can simply set the size of loading in the first block of the CSS file.

```css
:root {
  --tc-loading-size: 50px;
}
```

- Another setting we have is the timing of animation. You can set this variable in the first block of the css file.

```css
:root {
  --tc-loading-speed: 1s;
}
```

- You can set the thickness of borders too. You can set this variable in the first block of the css file.

```css
:root {
  --tc-loading-thickness: 5px;
}
```

- To change the color of the borders, you can set this variable in the first block of the css file.

```css
:root {
  --tc-loading-color: gray;
}
```
