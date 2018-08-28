# swappy-image-view
An image change/sort view for editing profile, image slider, product slider etc.

![alt tag](https://github.com/abalta/swappy-image-view/blob/develop/assets/bottomify.gif)
![alt tag](https://github.com/abalta/swappy-image-view/blob/develop/assets/spotify_bottom.png)

## Download

### Step 1. Add the JitPack repository to your build file

```
allprojects {
    repositories {
	    ...
	    maven { url 'https://jitpack.io' }
	}
}

```

### Step 2. Add the dependency

```
dependencies {
	        implementation 'com.github.abalta:swappy-image-view:master-SNAPSHOT'
	}

```

## Usage

Add swappy image view to your layout xml

```xml
    <com.abdullahbalta.swappy.SwappyImageView
            android:id="@+id/swappy_view"
            android:layout_width="match_parent"
            android:layout_height="240dp"/>
```

## Features

```kotlin
       /**
         * app:add_icon -> customize add icon (vector supported)
         * app:remove_icon -> customize remove icon (vector supported)
         * app:placeholder -> customize empty imageview background (solid color supported)
         * app:item_padding -> padding imageviews
         * app:main_image -> pre-defined main image (vector supported)
         * app:first_image -> pre-defined first image (vector supported)
         * app:second_image -> pre-defined second image (vector supported)
         * app:third_image -> pre-defined third image (vector supported)
         */
```

### Thanks to

Sample app uses following libraries demostrates demo, you may use different way to show swappy image view

* [alhazmy13 - MediaPicker](https://github.com/alhazmy13/MediaPicker)
* [bumptech - glide](https://github.com/bumptech/glide)