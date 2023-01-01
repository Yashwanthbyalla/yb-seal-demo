# yb-seal-demo

# SEAL - Scroll Effect Animation Library

This is a light weight Scroll Effect Animation Library.

Lightweight, performance focused (**2.3 kb**) scroll effect animation library, written in Typescript and compiled to JavaScript. No dependencies!

**Seal** (_Scroll Effect Animation Library_) was created to provide a lightweight solution for animating elements upon scroll. It's based on DOM objects which gives amazing performance in terms of checking the element's presence in the viewport.

### 🚀 [Demo](https://yashwanthbyalla.github.io/yb-seal-demo/)
### 🚀 [npm library](https://www.npmjs.com/package/yb-seal)

## Table of Contents
- [Install](#install)
- [Usage](#usage)
- [Animations](#animations)

## Install

```sh
# Usage with NPM
$ npm install yb-seal

```

Load it with your favorite module loader or use as a global variable

```js
// ES6 modules
import seal from 'yb-seal';

or
// CommonJS modules
var seal = require('yb-seal');

or
//simply add below line in angular.json file under scripts array:

"node_modules/yb-seal/src/index.js"

```

And remember to add styles

```scss
@import '~yb-seal/src/yb-seal.css';

or

// add below line in angular.json file under styles array:
"node_modules/yb-seal/src/yb-seal.css"
```

## Usage

In HTML, add a `yb-seal` class to make sure it tracks the respective element and behave accordingly with the scroll. Along with this add the animation name as value, for example:

```html
<div class="yb-seal yb-seal-slide-right"></div>
```

It will look for all classes with a `yb-seal` class and launch it's respective animation based on viewport scroll.

## Animations
In **seal** you can easily change animation's classes, by adding a proper `yb-seal` classes:
- `yb-seal-duration` - changes duration of the animation (enter value in seconds)

For example:
```html
<div
    class="yb-seal yb-seal-slide-right" yb-seal-duration="2"
></div>
```

The library supports several animations:
- `yb-seal-slide-up`
- `yb-seal-slide-down`
- `yb-seal-slide-right`
- `yb-seal-slide-left`
- `yb-seal-zoom-in`
- `yb-seal-zoom-out`
- `yb-seal-flip-left`
- `yb-seal-flip-right`
- `yb-seal-flip-up`
- `yb-seal-flip-down`
