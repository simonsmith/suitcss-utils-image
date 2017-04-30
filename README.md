# SUIT CSS utilities: image

[![Build Status](https://travis-ci.org/simonsmith/suitcss-utils-image.svg?branch=master)](https://travis-ci.org/simonsmith/suitcss-utils-image)

SUIT CSS image utilities

* Read more about [SUIT CSS's design principles](https://github.com/suitcss/suit/).

## Installation

* [npm](http://npmjs.org/): `npm install suitcss-utils-image`
* Download: [zip](https://github.com/simonsmith/suitcss-utils-image/releases/latest)

## Available classes

* `u-imgResponsive` - Allow an image to respond to its container size

## Usage

```html
<img class="u-imgResponsive" src="{src}" />
```

### Configuration

#### Overriding the display property

By default images are set to `display: block` but this can be overridden with
another utility, such as [suitcss-utils-display](https://github.com/suitcss/utils-display)

```css
<img class="u-imgResponsive u-inline" src="{src}" />
```

Please refer to the README for [SUIT CSS utils](https://github.com/suitcss/utils/)

## Testing

Install [Node](http://nodejs.org) (comes with npm).

```
npm install
```

To generate a build:

```
npm run build
```

To lint code with [postcss-bem-linter](https://github.com/postcss/postcss-bem-linter) and [stylelint](http://stylelint.io/)

```
npm run lint
```

To generate the testing build.

```
npm run build-test
```

To watch the files for making changes to test:

```
npm run watch
```

Basic visual tests are in `test/index.html`.

## Browser support

* Google Chrome
* Opera
* Firefox
* Safari
* Internet Explorer 8+
