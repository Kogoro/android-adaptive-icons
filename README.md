# android-adaptive-icons
An example for the adaptive icons feature in android O  

**Note: At the moment, devices will choose the rounded icon over the adaptive icon. This may change until the release of android O.**

<img src="/screenshots/screenshot1.png" width="256">

## Steps to reproduce

### 1. Create a project targeting android o (preview)
### 2. Create a resource for the launcher icon xml in the mipmap folder
### 3. Add the following code to the xml file and edit the locations to match your resources
```
<?xml version="1.0" encoding="utf-8"?>
<adaptive-icon xmlns:android="http://schemas.android.com/apk/res/android">
    <background android:drawable="@drawable/background"/>
    <foreground android:drawable="@mipmap/ic_foreground"/>
</adaptive-icon>
```
**NOTES:**  
* You can add all different drawable types: colors, drawables, mipmaps etc.  
* If a resource is a image, each file must have the size of 108x108dp in png format.  
* The foreground image is visible in an 72x72dp area from the center point.  
### 4. Add the resource to the launcher icon attribute in the manifest.


## Additional things
[Comment-Check-Outline](https://materialdesignicons.com/icon/comment-check-outline) icon used in the example is provided by [materialdesignicons.com](https://materialdesignicons.com/)
