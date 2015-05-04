# Workshop: Customizing Your Stylesheets: An Advanced Sass Workshop

So you’ve heard of Sass. In fact, you're probably using it. You write variables and use predefined mixins like a pro. But are you using Sass to its full potential?

This workshop will explore advanced Sass functionality. We’ll talk about the fundamental differences in lists, maps, extends, and mixins, and will dive deep into writing custom mixins. We’ll discuss partials and how to further DRY out our Sass by leveraging available functions, then writing our own custom functions, documenting the process, and architecting a fluid system.

### Pre-requisites:

  1. Before getting started, please make sure to have [node](https://nodejs.org/download/) installed onto your system. [This](https://github.com/joyent/node/wiki/Installing-Node.js-via-package-manager#osx) is a great set of instructions for installing node with a package manager. I would highly recommend using [Homebrew](http://brew.sh) to install node on a Mac.
  2. Optionally, for scss linting within the terminal, have [Ruby](https://www.ruby-lang.org/en/documentation/installation/) installed.
  3. Download [this](https://github.com/una/gulp-starter-env) starter environment.

### Tools and Resources

- [Slide Deck](http://una.github.io/adv-sass-workshop/slides/)
- [Sassmeister](http://sassmeister.com/)
- [Sass Documentation](http://sass-lang.com/documentation/file.SASS_REFERENCE.html)

### Gameplan

The way this workshop will run is as follows:

**Overview**
  - Quick Sass review
  - Syntax
  - Variables
  - Variable Abstraction
  - Nesting

**The Almighty Ampersand**

  - Nesting with the ampersand
  - Naming with the ampersand
  - The trailing ampersand
  - The Double Ampersand
  - *01 - Walkthrough: Ampersand*

**Beyond Basics**

  - @extend
  - Placeholder Selectors
  - @mixin
  - @include

**Control Directives**

  - Lists
  - List Functions
  - *02 - List Exercise*
  - Maps
  - Map Functions
  - @each loop
  - @for loop
  - @while loop
  - *03 - Grid Exercise*


**Let's Do Some Math and Play With Colors**

  - Supported Operators
  - Sass Math
  - Color functions
  - Playing with Color
  - *05 - Color Generation*

**Mixin Deep Dive**

  - Mixin + @content
  - Mixins + Maps
  - *04 - Breakpoint Mixin*
  - Default arguments
  - Null Defaults
  - Sassy Shape Mixin
  - Using Sassy Shapes
  - SVG Fallback Mixin
  - *Walkthrough: Recreating contrasted()*

**Functions**
  - Writing custom functions
  - Px to Rem Function
  - Property Getter
  - *06 - Color Function*
  - Arglists

**Theming**

  - !default
  - @warn and @error
  - Theming with Maps
  - *Walkthrough: Modular Animations*

**Sass++**

    - File Organization
    - SassDoc
    - *Advanced Example: Pixel Art&

**Final Challenge: Putting it All Together**
