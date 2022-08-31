# responsive-web-content

## Using media queries

[Media queries](https://developer.mozilla.org/en-US/docs/Web/CSS/Media_Queries/Using_media_queries) are useful when you want to modify your site or app depending on a device's general type (such as print vs. screen) or specific characteristics and parameters (such as screen resolution or browser viewport width).

## @ Media Rule

```css
@media () {
  // CSS rules
}
```

## Common Breakpoints

* 320px — 480px: Mobile devices
* 481px — 768px: iPads, Tablets
* 769px — 1024px: Small screens, laptops
* 1025px — 1200px: Desktops, large screens
* 1201px and more —  Extra large screens, TV

## Media Types

If we don’t apply a media type, the @ media rule selects all types of devices by default. Otherwise, Media types come right after the @ media rule. There are many kinds of devices but we can group them into 4 categories:

* all — for all media types
* print — for printers
* screen — for computer screens, tablets and, smart-phones
* speech — for screen readers that “read” the page out loud

```css
@media screen and (max-width: 480px) {
  .text {
    font-size: 16px;
  }
}
```