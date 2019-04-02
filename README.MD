# Table of Contents
* [I can make anything](#make-anything)
    * [I can TDD anything](#tdd-anything)
    * [I can program fluently](#program-fluently)
    * [I can debug anything](#debug-anything)
    * [I can model anything](#model-anything)
    * [I can refactor anything](#refactor-anything)
    * [I have a methodical approach to solving problems](#methodical-approach)
* [I help my teams succeed](#teams-succeed)
    * [I use an agile product development process](#agile-process)
    * [I write code that is easy to change](#easy-to-change)
    * [I can justify the way I work in a business context](#buisness-context)
    * [I can grow collaboratively](#grow-collaboratively)
* [I am equipped for long term growth](#longterm-growth)
    * [I manage my own well-being](#well-being)
    * [I can learn anything by myself](#learn-anything)

# I can make anything<a name="make-anything" />

## I can TDD anything<a name="tdd-anything" />

### What does it mean to be able to TDD anything?

To be able to do this means to have a clear process, which starts with planning. I have to fully understand what I'm building, before writing any code. This includes:
1. Write the user stories if they have not been provided already
2. Create a diagram of the classes, properties and functions needed for the first feature
3. To follow the red, green refactor cycle:<br>
`Red phase`
- Write a failing feature test
- Write a failing unit test (matching the feature test)<br>
`Green phase`
- Write code to make the unit test pass (and not more than that!)
- Run the tests and check if unit test passes. If not, repeat step 5
- Repeat steps 4-6 until the feature test passes
4. Refactor code accordingly (no new functionalities added!)
5. Run tests again to check that the refactoring did not break the tests
6. No code should be written unless if it is to make a failing unit test pass
7. Unit tests should be specific and precise

Throughout Makers I have used a number of different testing frameworks and I am comfortable working with them: RSpec, Capybara, Jasmine, Cypress, etc.

