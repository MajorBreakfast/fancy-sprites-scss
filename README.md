SCSS Mixin for [grunt-fancy-sprites](https://github.com/MajorBreakfast/grunt-fancy-sprites) with support for high resolution devices.

# Usage
Use the mixin like this:
``` SCSS
$sprites-path: "/assets/sprites/";
@import "fancy-sprites";

.something {
  @include sprite($sprite-first);
}
```
Uses the '1x' sprite sheet and the '2x' sprite sheet on high resolution devices

Having a css class for every sprite can come in handy:
``` SCSS
...
@include sprite-classes; // .sprite-first, .sprite-second
```