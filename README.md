# {display: nice}
## CSS Utility Class Mashup

Taking the parts I liked most in [Tachyons](http://tachyons.io/), [Shed CSS](http://tedconf.github.io/shed-css/) and [Beard](http://buildwithbeard.com/) and mashing up my own set of utility classes.

Under active development, please don't use anything and rely on it, it can and it will break.

## Ideas
- I love the general concept of Tachyons' feature set and the overall naming conventions, but I miss easy ways to extend the core features
- I like Beard's easy extendability, especially when it comes to custom breakpoints, but I'm not too fond of class names and breakpoint prefixes
- I prefer Shed's method to trigger responsive states using the _at-syntax_ (`@xxl`)
- I need an easy way to change and add new breakpoints
- I need to be able to drop the framework into existing Sass projects
- I want to use [Mappy Breakpoints](https://github.com/zellwk/mappy-breakpoints) to manage and apply breakpoints

## Roadmap
- [ ] Use a global Sass map for all breakpoints
- [ ] Replace hard-coded breakpoint classes with dynamicly generated ones
- [ ] Adapt @-syntax for breakpoint classes (eG `.foo@xl`)
- [ ] Make all values customizable by variables that can easily be overridden
- [ ] Make breakpoint classes optional on a per-utility basis
- [ ] Refactor class names for clearer distinction between properties and values
- [ ] Separate the Sass library from the demo content and make it easily usable in any project
- [ ] Proper documentation