# Material Design Hamburger

Android's Material Design hamburger animation built in CSS (with a sprinkle of JS).

![Material Design Hamburger](https://i.imgur.com/B0PT1Lb.gif)

### Example Usage

See [this pen](http://codepen.io/swirlycheetah/pen/cFtzb) for a styled example.

### Browser Support

Currently supporting the 2 latest versions of each major browser (IE10+) with the aim to support IE8+ in the future.

### Installation & Usage

#### Download

__Download the [latest release](https://github.com/swirlycheetah/material-design-hamburger/releases/latest).__

__Include the CSS & JS files from the `dist` folder where desired within your project.__

__Add the following HTML elements.__

```html
<section class="material-design-hamburger">
  <button class="material-design-hamburger__icon">
    <span class="material-design-hamburger__layer">
    </span>
  </button>
</section>
```

#### npm

__Install the package (use --save or --save-dev if required).__

`npm install material-design-hamburger`

__Include the CSS & JS where required.__

```html
<link rel="stylesheet" href="./node_modules/material-design-hamburger/dist/material-design-hamburger.css">
```

```html
<script src="./node_modules/material-design-hamburger/dist/material-design-hamburger.js"></script>

<script>materialDesignHamburger()</script>
```

__Add the following HTML elements.__

```html
<section class="material-design-hamburger">
  <button class="material-design-hamburger__icon">
    <span class="material-design-hamburger__layer">
    </span>
  </button>
</section>
```

#### Bower

__Install the package (use --save or --save-dev if required).__

`bower install material-design-hamburger --save-dev`

__Include the CSS & JS where required.__

```html
<link rel="stylesheet" href="./bower_components/material-design-hamburger/dist/material-design-hamburger.css">
```
```html
<script src="./bower_components/material-design-hamburger/dist/material-design-hamburger.js"></script>

<script>materialDesignHamburger()</script>
```

__Add the following HTML elements.__

```html
<section class="material-design-hamburger">
  <button class="material-design-hamburger__icon">
    <span class="material-design-hamburger__layer">
    </span>
  </button>
</section>
```

### Contributing

All contributions, no matter how big or small, are welcome. Follow these steps to contribute.

* Clone the repository

`git clone git@github.com:swirlycheetah/material-design-hamburger.git && cd material-design-hamburger`

* Install the required dependencies

`npm install`

* Make amendments in the `src` folder followed by running `gulp build` (or `./node_modules/gulp/bin/gulp.js build`) to build the changes in the dist folder

* Ensure there are no lint errors

* Ensure the example in the `examples/basic-example` folder still works as required

* Push your changes and submit a pull request
    
### In The Wild

* [APK Mirror](http://www.apkmirror.com/) (only at viewport widths smaller than 993px)

### Roadmap

* Better browser support
* Unit tests
* More examples
* Easier customisation

### License

Released under the MIT license: [opensource.org/licenses/MIT](http://opensource.org/licenses/MIT)
