Enhanced Angular Image Map
--------------------------
This repository is just a mirror of the original repository https://github.com/jasonroyle/ng2-img-map by **[jasonroyle](https://github.com/jasonroyle)** but with enhanced features.


----------
## Description ##
Responsive image mapping interface for Angular.

## New Features ##

 1. Added `[titles]` input, to type title beside hotspot
 2. Added `[pixelMarker]`  flag input, to use `[markers]`  input whether as percentage values or pixel  values.

## Example of Usage ##
`<img-map`

`#imgMap`

`src="YOUR_IMAGE_URL"`

`[markers]="HOTSPOT_ARRAY"`

` [titles]="TITLES_ARRAY"`

`[pixelMarker]=true>`

`</img-map>`

**HOTSPOT_ARRAY** should be in type of `markersArr: number[x][y]`

**TITLES_ARRAY** should be in type of `titlesArr: string[]`

**pixelMarker** by default is false, which means values of X and Y should be in percentage values [0,0] is the top left of the image, [100,100] is the down right of the image. If this flag is true, `[markers]` will place the hotspots in pixel value related to image width and height.
