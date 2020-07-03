# image-gallery

CSS Grid image gallery

This project explored several properties of `CSS Grid` and how it allows responsive layouts. Images are added dynamically with a random size via `JavaScript` and using `grid-auto-flow: dense` to fill in holes in the grid if smaller items come up later.

Also took into account how the use of images affect the page's performance and explored tools to detect and solve issues with the images.

![GitHub code size in bytes](https://img.shields.io/github/languages/code-size/jpmti2016/image-gallery)
![GitHub last commit](https://img.shields.io/github/last-commit/jpmti2016/image-gallery)
![GitHub top language](https://img.shields.io/github/languages/top/jpmti2016/image-gallery)
![GitHub language count](https://img.shields.io/github/languages/count/jpmti2016/image-gallery)
![W3C Validation](https://img.shields.io/w3c-validation/default?targetUrl=https%3A%2F%2Fjpmti2016.github.io%2Fimage-gallery%2F)
![Website](https://img.shields.io/website?url=https%3A%2F%2Fjpmti2016.github.io%2Fimage-gallery%2F)

## CSS Grid properties used

1. Properties
   1. grid-template-columns
   2. grid-template-rows
   3. grid-auto-rows
   4. grid-auto-flow: dense
   5. justify-items
   6. align-items
   7. gap
   8. grid-column
   9. grid-row
2. Special Functions and Keywords
   1. repeat()
   2. fr
   3. auto-fill

## Image processing tools

1. Gimp used to
   1. Scale the image to the needed dimensions.
   2. Reduce the image size.
2. imageoptim used to
   1. Compress the image taking into account factors like
      1. Quality
      2. Format
      3. DPI mode
      4. Color quality

## Page auditing tools

1. Lighthouse
   1. Used to check the overall quality of the webpage
      1. Performance
      2. Accesibility
      3. SEO
      4. Best practices
2. RespImageLint
   1. Used to detect images's issues.

### The idea came from the Wes Bos's great course [CSS Grid](https://courses.wesbos.com/).
