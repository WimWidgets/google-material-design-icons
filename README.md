# Google's Material Design Icons:<br>Font Awesome style
## Usage
You can now use the material icons in the Font Awesome class style, next to Google's semantic notation:
````
<span class="gmdi gmdi-thumb_up"></span>
<span class="gmdi">thumb_up</span>
````
The **gmdi** namespace can easily be adjusted to your taste by overriding the `@gmdi-css-prefix` variable after importing:
````
@import '[path to LESS files]/google-material-design-icons';

@gmdi-css-prefix: mi;
````
## Sizing
The sizing works a bit different than Font Awesome. The default size for material icons is [24px, with three extra sizes](http://google.github.io/material-design-icons/#sizing). Because of this fixed size constraint instead of relative units, some things work differently (see the Notes section). So the sizing works with the following extra classes:
* `.gmdi-sm` = 18px
* `.gmdi-lg` = 36px
* `.gmdi-2x` = 48px

## Font Awesomeness
The following extra's from Font Awesome are supported:
* [fixed width](http://fontawesome.io/examples/#fixed-width)
* [list icons](http://fontawesome.io/examples/#list)
* [bordered &amp; pulled icons](http://fontawesome.io/examples/#bordered-pulled)
* [animated icons](http://fontawesome.io/examples/#animated)
* [rotated &amp; flipped](http://fontawesome.io/examples/#rotated-flipped)
* [stacked icons](http://fontawesome.io/examples/#stacked)

## Notes
### Vertical alignment
Setting vertical align to middle works well for centering icons with fixed font sizes. This is enabled by default, but can be disbaled by overriding a variable after import:
````
@import '[path to LESS files]/google-material-design-icons';

@gmdi-vertical-center: 0; // default is 1
````
### List Icons
Although list icons are supported, the icons will usually not come out right due to font sizing issues. Unless you use a text font size of 18/24/etc. Adding size classes to list icons is not supported, because of the pixel value constraint on the font sizes.
### Stacked Icons
Although the stacking mechanism works, there aren't many useful basic shapes available to make good use of it.

## Version
The icons are up to date with v2.0.0 of the material set.