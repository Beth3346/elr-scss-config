# Default Site Config

[![npm version](http://img.shields.io/npm/v/elr-scss-config.svg)](https://www.npmjs.org/package/elr-scss-config)
[![CI](https://github.com/Beth3346/elr-scss-config/actions/workflows/node.js.yml/badge.svg)](https://github.com/Beth3346/elr-scss-config/actions/workflows/node.js.yml)
[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)
[![npm](https://img.shields.io/npm/dm/elr-scss-config.svg?style=flat)](https://npmjs.com/package/elr-scss-config)

A base config for scss based projects

## Installation

Download node at [nodejs.org](http://nodejs.org) and install it, if you haven't already.

```sh
npm install elr-scss-config
```

or

```sh
yarn add elr-scss-config
```

## Implementation

### Colors

```scss
$white: #fff;
$eggshell: #f2f2f2;
$lightest-gray: #e2e2e2;
$lighter-gray: #ddd;
$light-gray: #ccc;
$gray: #999;
$dark-gray: #666;
$black: #111;
$seafoam: #3fb8af;
$blue: #1976d2;
$dark-blue: #005ebd;
$light-blue: lighten($blue, 15%);
$lightest-blue: #dfecf9;
$salmon: #ff9e9d;
$pink: #f81190;
$dark-pink: #e3037e;
$light-pink: #ffc3e4;
$magenta: #bf10a0;
$orange: #e0432b;
$taupe: #dad8a7;
```

```scss
$instagram-color: #5380a6;
$google-color: #dd4b38;
$twitter-color: #25aae1;
$pinterest-color: #ce2128;
$facebook-color: #3c5b9a;
$linkedin-color: #128fc3;
```

### Fonts

```scss
$roboto: "Roboto", sans-serif;
```

```scss
$noto: "Noto Sans", sans-serif;
```

```scss
$nunito: "Nunito", sans-serif;
```

```scss
$playfair: "Playfair Display", serif;
```

```scss
$source-code: "Source Code Pro", monospace;
```

```scss
$noto-serif: "Noto Serif", serif;
```

### HTML for Fonts

```html
<link
  href="https://fonts.googleapis.com/css?family=Roboto:400,700,900"
  rel="stylesheet"
/>
```

```html
<link
  href="https://fonts.googleapis.com/css?family=Noto+Serif:400,700,900"
  rel="stylesheet"
/>
```

```html
<link
  href="https://fonts.googleapis.com/css?family=Nunito:400,700,900"
  rel="stylesheet"
/>
```

```html
<link
  href="https://fonts.googleapis.com/css?family=Fira+Code:400,700,900"
  rel="stylesheet"
/>
```

### Template Settings

```scss
$background-color: $lightest-gray;
$main-background: $white;
$background-light: $lightest-blue;
$hero-unit-background: $background-light;
```

```scss
$primary-gradient: linear-gradient($light-blue, $seafoam);
$secondary-gradient: linear-gradient($pink, $salmon);
```

```scss
$sans-font: $roboto;
$serif-font: $noto-serif;
$rounded-font: $nunito;
$mono-font: "Fira Code";
```

```scss
$heading-font: $sans-font;
$code-font: $mono-font;
$article-font: $noto;
$callout-font: $serif-font;
```

```scss
$base-fontsize: 16px;
$font-family: $sans-font;
$h1-fontsize: 3rem;
$h2-fontsize: 2.25rem;
$h3-fontsize: 1.5rem;
$h4-fontsize: 1.125rem;
$h5-fontsize: 1rem;
$h6-fontsize: 0.875rem;
$line-height: 1.6;
```

```scss
$text-color: $black;
$text-color-light: $background-light;
```

```scss
$link-color: $blue;
```

```scss
$primary-color-dark: $dark-blue;
$primary-color: $blue;
$primary-color-light: $light-blue;
$primary-text-light: $background-light;
$secondary-color: $pink;
$secondary-color-dark: $dark-pink;
$secondary-color-light: $light-pink;
$tertiary-color: $seafoam;
```

```scss
$danger-color: #af100d;
$danger-background-color: #fddbdb;

$warning-color: #ca9626;
$warning-background-color: #fff2da;

$success-color: #337234;
$success-background-color: #dcf3dc;

$info-color: $blue;

$muted-color: $gray;
$muted-background-color: $eggshell;
```

```scss
$border-color: $light-gray;

$border: 1px solid $border-color;
$border-dark: 1px solid $text-color;
$border-light: 1px solid $lightest-gray;

$border-primary: 1px solid $primary-color;
$border-secondary: 1px solid $secondary-color;

$border-success: 1px solid $success-color;
$border-danger: 1px solid $danger-color;
$border-warning: 1px solid $warning-color;
$border-muted: 1px solid $muted-color;
$border-link: 1px solid $link-color;
```

```scss
$content-width: 1400px;
$max-width: 1400px;
$desktop-width: 1200px;
$landscape-width: 1024px;
$tablet-width: 768px;
$landscape-min-width: $tablet-width + 1;
$tablet-max-width: $tablet-width - 1;
$mobile-width: 568px;
```

```scss
// $shadow: 0 2px 5px rgba(0, 0, 0, .2);
$shadow: 1px 1px 5px rgba(0, 0, 0, 0.1), -1px -1px 5px rgba(0, 0, 0, 0.1);
$button-shadow: 0 1px 3px rgba(0, 0, 0, 0.4);
$text-shadow: 0 1px 2px rgba(0, 0, 0, 0.3);
$focus-shadow: 0 0 2px $link-color;
$border-radius: 5px;
$header-shadow: 0 1px 4px rgba(0, 0, 0, 0.2);
```

## Implementation

```scss
@import "elr-scss-config/src/main";
```

Now you can just use these variables in your stylesheet. You can also override them locally.

## License

SEE LICENSE IN LICENSE.md
