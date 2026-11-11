# animated_image

Modified version of the
[`Image`](https://api.flutter.dev/flutter/widgets/Image-class.html) widget from
https://github.com/flutter/flutter/blob/3.50.0/packages/flutter/lib/src/widgets/image.dart
so that it does not pause the animation of the image even if animations are
disabled via
[`MediaQueryData.disableAnimations`](https://api.flutter.dev/flutter/widgets/MediaQueryData/disableAnimations.html).
