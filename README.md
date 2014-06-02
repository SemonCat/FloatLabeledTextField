Float Labeled EditText
==============

This is a simple implementation of a Float Labeled EditText forked on [floatlabelededittext](https://github.com/wrapp/floatlabelededittext).

I push it to Maven central for include easier more and making a example project.

![Android Version](http://i.imgur.com/ucRd1jm.gif)

Usage
=====

Add dependency to your build.gradle file:

```groovy
dependencies {
    compile "com.github.semoncat.floatlabelededittext:library:+"
}
``` 

And then insert the view in XML:

```xml
<LinearLayout 
    xmlns:android="http://schemas.android.com/apk/res/android"
    xmlns:tools="http://schemas.android.com/tools"
    android:layout_width="match_parent"
    android:layout_height="match_parent"
    android:orientation="vertical">

    <com.semoncat.FloatLabeledEditText
            xmlns:app="http://schemas.android.com/apk/res-auto"
            android:layout_height="wrap_content"
            android:layout_width="match_parent"
            app:fletFloatingHint="Normal"/>
</LinearLayout>
```

