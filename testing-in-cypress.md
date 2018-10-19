## Test driven development in React with Cypress

By Josh Justice @Big Nerd Ranch

Avoid spaghetti code.
Testing first helps you figure out implementation.
Most of the final implementation will have been written already in the test.
1. Build the bare minimum of what you need right now.
2. Make the code easy to change for when you need something else.

Visualize the payoff.

__TDD__ = Write a failing unit test -> make the test pass -> refactor

#### Outside-in TDD
Write a failing acceptance test -> Write a failing unit test -> make the test pass -> refactor

#### Cypress.io
Ton of benefits, ton of speed. Built for E2E tests but can be used for component tests.

#### Demo
Requirement: As a user, I want to be able to send a message.