# Material Design Hamburger

Android's Material Design hamburger animation built in CSS (with a sprinkle of JS).

### Browser Support

Currently supporting the 2 latest versions of each major browser (IE10+) with the aim to support IE8+ in the future.

### Example

See [this pen][1] for a styled example.

### Installation & Usage

#### NPM

__Install the package (use --save or --save-dev if required)__

`npm install material-design-hamburger`

__Include the CSS & JS where required__

`<link rel="stylesheet" href="./node_modules/material-design-hamburger/dist/material-design-hamburger.css">`

`<script src="./node_modules/material-design-hamburger/dist/material-design-hamburger.js"></script>`

__Add the following HTML elements__

	    <section class="material-design-hamburger">
	      <button class="material-design-hamburger__icon">
	        <span class="material-design-hamburger__layer"></span>
	      </button>
	    </section>

#### Bower

__Install the package (use --save or --save-dev if required)__

`bower install material-design-hamburger --save-dev`

__Include the CSS & JS where required__

`<link rel="stylesheet" href="./bower_components/material-design-hamburger/dist/material-design-hamburger.css">`

`<script src="./bower_components/material-design-hamburger/dist/material-design-hamburger.js"></script>`

__Add the following HTML elements__

	    <section class="material-design-hamburger">
	      <button class="material-design-hamburger__icon">
	        <span class="material-design-hamburger__layer"></span>
	      </button>
	    </section>

### Roadmap

* Better browser support
* Unit tests
* More examples
* Easier customisation

### License

Released under the MIT license: [opensource.org/licenses/MIT][2]

  [1]: http://codepen.io/swirlycheetah/pen/cFtzb
  [2]: http://opensource.org/licenses/MIT
