# Browser Hack Mixins for Sass
Browser-hack sass mixins: Apply your CSS to a specific browser

![Browser Hack Mixins for Sass](https://lh3.googleusercontent.com/-lCHyETA5vtw/Vv7N8psFLDI/AAAAAAAACPg/0aPgHIty5YQ9Tp-eubIPgox5oBcWTJJNgCCo/s1024-Ic42/browser-logos.png)

## How To Use

1. Import `_hacks.scss` file to your SCSS code : `@import "hacks";`
2. Use the mixin you want:
  - `@include [Mixin_Name]{ selector, property, value }`
  - For example: `@include only_ie9_below { .my_div, background-color, red }`
 
## List of Mixins
1. Internet Explorer CSS Hacks
  - only_edge
  - only_ie6
  - only_ie7
  - only_ie7_below
  - only_ie8
  - only_ie8_below
  - only_ie9
  - only_ie9_below
  - only_ie10
  - only_ie10_above
  - only_ie11
  - only_ie11_above
  - no_ie6
  - only_ie9_saf4_above
2. Firefox CSS Hacks
  - only_ff
  - only_ff2
  - only_ff2_above
  - only_ff3_above
  - only_ff6_above
  - only_ff16_above
  - only_ff21_above
  - only_ff24_above
  - only_ff25_above
  - only_ff26_above
  - only_ff27_above
  - only_ff28_above
  - only_ff30_above
3. Webkit CSS Hacks
  - only_webkit
  - only_chrome
  - only_safari
  - only_safari9
  - only_ios
  - only_safari_no_ios
  - only_opera9_safari2
4. Opera CSS Hacks
  - only_opera
  - only_opera11
5. Other CSS Hacks
  - no_ie_safari6

## What's New
  - Added Microsoft Edge Mixin

## Thanks to
  - [marknotton](https://github.com/marknotton)
