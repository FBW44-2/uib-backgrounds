# UIB Backgrounds

`background` is a shorthand property that helps us set all background related properties in one go.

## `background-image`

- [`url()`](https://developer.mozilla.org/en-US/docs/Web/CSS/url)
    
    Add a path to your image
- [`linear-gradient()`](https://developer.mozilla.org/en-US/docs/Web/CSS/linear-gradient)
- [`radial-gradient()`](https://developer.mozilla.org/en-US/docs/Web/CSS/radial-gradient)

## `background-size`

You can specify the size of the background in both horizonal and vertical direction.
You can use the usual CSS units, like percentage, or pixel.
There are also few useful keywords: `cover` and `contain`.
With `background-size: cover;` the image will cover the entire container, but it might be cut off in the horizonal or vertical direction.
With contain, the image might not cover the entire container, as it should fit inside both horizonally and vertically.

## `background-repeat`

By default backgrounds repeat in both horizonal and vertical direction.
You might want to reset this by: `background-repeat: no-repeat`;
