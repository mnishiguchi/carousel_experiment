# carousel_experiment

- Create a stack of images using z-index.
- Give each image title and short text.
- Show and hide using ".active" class.

## responsive image
- Must center the images, rather than stretch them.

## Some techniques

### Center the image by applying contradictory left:0 and right:0.
```css
.carousel-item {
  position: absolute;
  left: 0;
  right: 0;
  top: 0;
  ...
}
```
