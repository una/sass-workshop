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

### Gameplan

The way this workshop will run is as follows:

### Overview
  - Quick Sass review

**The Almighty Ampersand**

  - Nesting with the ampersand
  - Naming with the ampersand
  - The trailing ampersand
  - The Double Ampersand
  - *Challenge: Use the Ampersand in 3 different ways*

**Beyond Basics**

  - @extend
  - Placeholder Selectors
  - @mixin
  - @include

**Control Directives**

  - Lists
  - List Functions
  - Maps
  - Map Functions
  - @each loop
  - @for loop
  - @while loop

**Mixin Deep Dive**

  - Mixin arguments
  - Arglists
  - @content blocks
  - Default arguments
  - Using [null](http://blog.teamtreehouse.com/smarter-sass-mixins-null)
  - *Challenge: Write a breakpoint mixin that reads from a map of breakpoints*

**Functions**

  - Number functions <
  - String functions <
  - Color functions (tips: mix > lighten or darken)
  - Writing custom functions
  - @warn, @debug, @error
  - *Challenge: Write a custom function to ____*

**Final Challenge: Building an on-the-fly Pattern Library**

  - Color map
  - map-get() color function
  - Separation of files
  - Manifest file
  - Bonus: SassDoc
  - Html output to build blocks with pseudo elements based on color map

**Bonus: Getting Organized **
  - File Organization
  - Partials