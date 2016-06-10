# trungnt-android3-assignment18

##Yêu cầu
![BTVN Animation](http://i477.photobucket.com/albums/rr132/trungepu/BTVN-Animation-CanhBX_zpscxd6xa2o.jpg)
![BTVN Animation - Button biến hình](http://i477.photobucket.com/albums/rr132/trungepu/BTVN-Button%20bien%20hinh%20va%20di%20chuyen_zpsmhjbyfeu.jpg)
![Java Reffection](http://i477.photobucket.com/albums/rr132/trungepu/Java-Reffection_zpspula4ylp.jpg)


##Tham khảo:
### Lý thuyết
+ [Overview](https://developer.android.com/guide/topics/graphics/overview.html)
+ [View Animation](https://developer.android.com/guide/topics/graphics/view-animation.html)
+ [Property Animation](https://developer.android.com/guide/topics/graphics/prop-animation.html)
+ [Drawable Animation](https://developer.android.com/guide/topics/graphics/drawable-animation.html)

### Ví dụ:
+ [Property Animation](http://www.101apps.co.za/articles/a-property-animation-tutorial.html)
+ [Property Animation](http://cogitolearning.co.uk/?p=1366)
+ [View Animation](http://www.tutorialspoint.com/android/android_animations.htm)
+ [Drawable Animation](http://www.101apps.co.za/articles/frame-by-frame-animation-tutorial.html)

##Chú ý khi học
```
Property Animation: Time interpolation: khoang cach/ duration; khoang cach = |x - next.X| / 4000
- Frame refresh delay
Animator sets
- repeat count and behavior

+ non-linear animation
+ linear animation
- valueAnimator

Propertiy Ani - View Ani
Java Reffection
- View animation ---> khi click vao button o vi tri thu 2 thi ko duoc, con dung Propertie Ani co the thao tac duoc khi button di chuyen o vi tri moi
- View Ani thao tac nhanh (kieu anh ao) >< Propertiy Ani thao tac cham hon chut
- View Ani code it hon >< Properti Ani code nhieu hon 
android.animation
+ Api Overview: Animaotor classs, Evaluators, time interpolator
ObjectAnimator.ofFloat(foo, "alpha", 0f, 1f)
+ Animator.AnimatorListener
+ LayoutTranstition class => setVisible 
ArgbEvaluator => evaluate(), Point
<objectAnimatio => chi dung duoc tu Android 3.0 tro len ()
ValueAnimator (trong xml)
Animatorset => Aninatoriinflater.loadAnimmator


```

##Tham khảo ngoài
+ [Dynamically change backgroudn color with animated transition](http://stackoverflow.com/questions/18818611/dynamically-change-background-color-with-animated-transition)
+ [Library Android Material Info Turtorial](https://riggaroo.co.za/github-library-android-material-info-tutorial/)
+ [Animations](https://guides.codepath.com/android/Animations)
+ [Android Arsenal](https://android-arsenal.com/tag/13)

