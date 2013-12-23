SCSS Mixin for [grunt-fancy-sprites](https://github.com/MajorBreakfast/grunt-fancy-sprites) with support for high resolution devices.

[Tutorial for Fancy Sprites on YouTube](http://youtu.be/xD8DW6IQ6r0) (Note: The SCSS has changed slightly since)

Installation: `bower install --save fancy-sprites-scss`

Use the mixin like this:
``` SCSS
$sprites-path: "/assets/sprites/"; // URL
@import "path/to/fancy-sprites";

.something {
  @include sprite($sprite-first);
}
```
Uses the '1x' and '2x' sprite sheet on low and high resolution devices respectively.

Having a css class for every sprite can come in handy:
``` SCSS
// ...
@include sprite-classes; // .sprite-first, .sprite-second
```
