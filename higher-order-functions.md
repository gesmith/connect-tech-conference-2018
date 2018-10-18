## Do Iterate or: how I learned to stop worrying and love higher-order functions

By Tim Roberts - staff software engineer @circleci

Higher Order Function: is a function that takes a function as an arg or returns a function as a value.

* `promise.then(handleResolved).catch(handleError)` is a HOF

Scope: The values that our worker has access to at any given time.

Closure: The code between curly brackets and its accompanying scope.

The underlying algorithm: 
  * iterate over our internal data structure
  * pass each item to the given item

But why:
  * Seperation: Each method knows just enough to finish its job
  * Testability

Seperate the 'what' from the 'how'