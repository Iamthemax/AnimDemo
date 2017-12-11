Simple rotate animation is added to an imageView. 

An animation is defined in XML that can performs transitions such as rotating, fading, moving, and stretching on a graphic.

The view animation framework supports both tween and frame by frame animations, which can both be declared in XML.

We can also add same animations to android programatically.

Reference

<strong><rotate></strong>

A rotation animation. Represents a RotateAnimation.
attributes:

<strong>android:fromDegrees</strong><br>
Float. Starting angular position, in degrees.

<strong>android:toDegrees</strong><br>
Float. Ending angular position, in degrees.

<strong>android:pivotX</strong><br>
Float or percentage. The X coordinate of the center of rotation. Expressed either: in pixels relative to the object's left edge (such as "5"), in percentage relative to the object's left edge (such as "5%"), or in percentage relative to the parent container's left edge (such as "5%p").

<strong>android:pivotY</strong><br>
Float or percentage. The Y coordinate of the center of rotation. Expressed either: in pixels relative to the object's top edge (such as "5"), in percentage relative to the object's top edge (such as "5%"), or in percentage relative to the parent container's top edge (such as "5%p").

https://developer.android.com/guide/topics/resources/animation-resource.html
