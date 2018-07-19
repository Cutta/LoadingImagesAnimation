# LoadingImagesAnimation
Android loading animation with images changing


### SCREENS

![](https://raw.githubusercontent.com/Cutta/LoadingImagesAnimation/master/gifs/ezgif-1-5f0618240d.gif)  |  ![](https://raw.githubusercontent.com/Cutta/LoadingImagesAnimation/master/gifs/ezgif-1-9350f2aa6c.gif)

### PROPERTIES
- imagesArray
- duration
- dividerColor
- backgroundColor

### USAGE

``` xml
 <com.cunoraz.loadingimages.LoadingImagesView
        android:layout_width="wrap_content"
        android:layout_height="wrap_content"
        app:imagesArray="@array/your_image_array" />

```
### IMPORT

Project build.gradle
```
	allprojects {
		repositories {
			...
			maven { url 'https://jitpack.io' }
		}
	}
```

App build.gradle
```
implementation 'com.github.Cutta:LoadingImagesAnimation:1.1'
```
