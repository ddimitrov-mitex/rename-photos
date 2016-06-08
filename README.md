# rename-photos
Renames all JPEG photos in a directory so their names start with date and time, followed by the original names

Requires ImageMagick to be installed.

## Usage:

```rename-photos [-nokeep] file(s)```

 ```-nokeep```    do not keep original filenames

The following example will rename all images such as IMG_1234.JPG, DSC12345.JPG, etc. to YYYYMMDD_HHMMSS_????????.jpg:

```rename-photos '????????.JPG'```
