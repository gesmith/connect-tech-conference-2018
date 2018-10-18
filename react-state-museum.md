## React State Museum

[React State Museum - examples by GantMan](https://github.com/GantMan/ReactStateMuseum)

State isn't solved AND accepted.

State needs to work in both web, and React Native. It's actually easy to do:
`import { PackingList } from 'packing-list';`
`import { PackingList } from 'packing-list/native';`

### React Context API
Is React Context a Redux killer? No.

### Redux

One of the best things about using redux vs context is middleware.

Redux is:
* scalable
* popular
* functional
* flexible
* time travel

### MobX

Decorators!
`@observer`
Q: What is @observer?
A: It's just a HOC wrap

MobX kind of stays out of your way.

Cool:

  * small code
  * efficient
  * easy
  * mutable

Uncool:

  * decorator magic?
  * Middleware-ish
  * No prescription (no "standard" way of really doing things.)
  * no state-tree (though it has a way to merge redux-like things via MobX-state-tree library)

That's the classics.

# Less Common
## Unstated

## react-automata
Not really a state management solution.
Based on xstate - CS finite state machines.

Finite State Machines:
  * Can't get in an unplanned state.
  * are Graphable
  * are iteraitevely testable
  * sequence

State snapshot testing.
Using FSMs (finite state machines)
  * Means looking ahead
  * means lots of automation benefits
  * means lots of analytic benefits
  * means visual way to identify late changes
  * means integrating with other state managers

## GraphQL with Apollo (apollo-link-state)
General feeling... "meh"... but look into it because it will probably eventually swallow state management.
  * dispatch action -> mutation/query
  * reducer -> resolver