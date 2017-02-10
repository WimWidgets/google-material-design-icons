# Google's Material Design Icons:<br>Font Awesome style
## Usage
Use the material icons in the Font Awesome class style, next to Google's semantic notation:
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
The sizing works a bit different than Font Awesome. The default size for material icons is [24px, with three extra sizes](http://google.github.io/material-design-icons/#sizing). So the sizing works with the following extra classes:
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

## Version
The icons are up to date with v2.0.0 of the material set.