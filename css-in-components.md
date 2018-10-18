## CSS in a component based world

By Alice Brosey @ambroseya

"Which is more important... ease of writing code or the ease of maintaining and extending the code?"

Typical problems:
  * developer mindset: time spent making javascript pretty, use css until it works.
  * modularity/extensibility
  * parent class scoping problems

Typical strategies:
  * SASS/LESS
  * BEM (Block Element Modifier) - but it's not a technology, it's just a naming convention.

## Strategies
CSS Modules
__CSS-in-JS__

Referencing Chris Chedeau's (Facebook) talk from 2015
### Problems with CSS at Scale
  * Global Namespace
  * Dependencies
  * Dead Code Elimination (hard to tell when pure CSS classes/etc are dead)
  * Minification
  * Sharing constants
  * Non-deterministic Resolution (file load order, etc)
  * Isolution

### Frameworks
  * Radium
  * Aphrodite
  * Emotion
  * styled-components

Pros:
  * Unified source for reusable pieces
  * Scoped selectors

Cons
  * Styles use size increases with size of app

### Embrace it
  * Good CSS architecture saves dev time
  * A preventative measure for future headaches
  * Every project needs a proper approach
  
