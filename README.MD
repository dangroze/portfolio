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

### What does it mean to be able to do this?

This means to have a clear process, which starts with planning. I have to fully understand what I'm building, before writing any code. This includes:
1. Write the user stories if they have not been provided already
2. Create a diagram of the classes, properties and functions needed for the first feature
3. To follow the red, green, refactor cycle:<br>
`Red phase`
- Write a failing feature test
- Write a failing unit test, matching the feature test<br>
`Green phase`
- Write the least amount of code to make the unit test pass
- Run the tests and check if unit test passes. If not, repeat green phase<br>
`Refactor phase`
- Refactor code without adding new features
- Run tests again to check that the refactoring did not break the tests
4. No code should be written unless if it is to make a failing unit test pass
5. Unit tests should be specific and precise<br>

Throughout Makers I have used a number of different testing frameworks and I am comfortable working with them: RSpec, Capybara, Jasmine, Cypress, etc.<br>
### Example repos:<br>
[Takeaway Challenge](https://github.com/dangroze/takeaway-challenge)<br>
- Test frameworks: RSpec, SimpleCov
- Here I've learned how to use stack trace to guide me through, had 92% test coverage.<br>

[Bowling Challenge](https://github.com/dangroze/bowling_challenge) + [Thermostat Challenge](https://github.com/dangroze/thermostat) <br>
- Test framework: Jasmine
- Both of these challenges were completed with technologies I have not used before, which demonstrated the power and utility of testing and the red-green-refactor cycle.<br>
### Feedback

I've spent the first 4-5 weeks of the course trying to get a grasp on the concepts of TDD, through self learning, getting feedback from colleagues and coaches.<br>
Katerina's feedback on testing behaviour vs. state in week 3 made testing as a whole a bit more elegant and precise. <br>
Nikhil Vijayan on Acebook group project: "I can't thank you enough for your help on testing and debugging, specifically your research on testing controllers was key in unblocking us."

## I can program fluently<a name="program-fluently" />

### What does it mean to be able to do this?

This means that I am comfortable solving a problem and translating it into a computer language. Also to be agile in moving between the states of writing code and fixing problems that may arise while doing so.

### Example repos:<br>
[Airport challenge in Javascript](https://github.com/dangroze/airport_challenge_js.git)

Airport challenge in JS was the first app I did outside of Ruby. Despite the fact that I've used a new language and testing framework, it was relatively easy to understand. Having applied strict TDD and by following the red-green-refactor process, I felt comfortable in a new environment.

[Chitter challenge](https://github.com/dangroze/chitter_challenge)

In this weekend project I've applied the knowledge acquired during the week to build a functional CRUD app, comprehensively tested.

[Bank tech test](https://github.com/dangroze/bank_tech_test.git)

Here I've used dependency injection and delegation, this was a really interesting mini-challenge, all the requirements have been met using TDD, which can be seen in the frequent commits.

### Feedback

Sam J said on Bowling that this was a good go at the challenge, objects have clear responsibilities and looks well tested.

## I can debug anything<a name="debug-anything" />

# What does it mean to be able to do this?

This means to have a clear process, a process that can be applied in any language or technology used, and stick to it. I've come to realise that you can't stay blocked forever. Each and every bug can be resolved, there is a good chance that someone in this world came across the same thing while programming, you just have to know where to look and how to explain the problem to someone else. My process includes following strict TDD, as explained earlier, then if an error message occurs:
1. Read and understand the error message
2. Follow the stack trace
3. Get more visibility ( irb, p, console.log(), etc )
4. Identify where the problem is
5. Use current knowledge and available tools ( google, StackOverflow, friends' advice, etc ) to fix it

### Example repos:

[Week 3 Debugging 2](https://github.com/makersacademy/skills-workshops/tree/master/week-3/debugging_2)

This week's exercise was resolved using a methodical approach and a thorough process:
- Tightened the loop by looking at each test separately
- When the error message and stack trace were not conclusive and descriptive enough, sinatra gave me more clues

[Acebook group project](https://github.com/dangroze/acebook-team-name-undefined)

Having chosen a technology that we haven't used before, when we got to testing, we thought we were in over our heads. With extensive research and lots of trial and error, tightening the loop and gaining visibility, our tests were finally green.

### Feedback

From Nikhil: "Your methodical approach in testing our controllers, and patiently checking each variable was great to experience."
