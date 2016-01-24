# iOS resizer
Resize application icon and set icon to Contents.json file using command line. 
Bulk resize @3x to @2x and @2x to @1x images.

<h3>Getting started</h3>
This script depends on imagemagic program
To install imagemagic please run ```brew install imagemagick ``` <br>
Make sure to put imagemagick is in your path

You can put this script in path also or you can copy the script and run it from there.

<h3>Usage</h3>

<h5>Create app icon</h5>
```
ios_resize -ai your_icon_.png xcassets_folder_name
```

<h5>Bulk resize images</h5>
This function will go from current folder to all subfolder, so make sure you are on a right path.
```
ios_resize to2x
ios_resize to1x
```

<br>
<br>
<h5>Next steps</h5>
Make support for launch images
Catch imagemagic errors, and better error handling as well as returning signals from functions
