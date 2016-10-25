# MaterialNumberPad
Material-style numberpad widget useful for enetring phone numbers and other digit-only input.

![MaterialNumberPad](https://raw.github.com/sbakhtiarov/MaterialNumberPad/master/numpad.png)

Usage
-----
```xml
<com.basv.materialnumpad.MaterialNumberpad
    android:layout_width="match_parent"
    android:layout_height="wrap_content"
    app:mnp_text_color="#fff"
    app:mnp_show_done_action="false" />
```
Gradle
------
Add JitPack repository to root build.gradle
```
allprojects {
    repositories {
        jcenter()
        maven { url "https://jitpack.io" }
    }
}
```

Add the dependency
```
dependencies {
    ...
    compile 'com.github.sbakhtiarov:MaterialNumberPad:1.0'
}
```
