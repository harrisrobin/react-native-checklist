### Generate App Icon & Splash-screen Manually {#generate-app-icon--splash-screen-manually}

Of course, you can still do all of this manually.

There are several easy to use packages that do it for you, however I recommend the [makeicon](https://github.com/beplus/makeicon) and [makesplash](https://github.com/beplus/makesplash) generator to get both icons and splash screens for both iOS and Android.

# iOS

1. Set `AppIcon` in `Images.xcassets`
2. Add 9 different size icons:

3. 29pt

4. 29pt\*2

5. 29pt\*3

6. 40pt\*2

7. 40pt\*3
8. 57pt
9. 57pt\*2
10. 60pt\*2
11. 60pt\*3.

Accessing Images.xcassets on iOS will look like this:  
![](/assets/Screenshot 2017-11-28 19.28.46.png)

# Android

Put`ic_launcher.png`to folder`[$PrjDir]/android/app/src/main/res/mipmap-*`

* 72\*72
  `ic_launcher.png`to `mipmap-hdpi`
  .
* 48\*48`ic_launcher.png`to`mipmap-mdpi`
  .
* 96\*96`ic_launcher.png`to`mipmap-xhdpi`
  .
* 144\*144`ic_launcher.png`to`mipmap-xxhdpi`
  .
* 192\*192`ic_launcher.png`to`mipmap-xxxhdpi`
  .



