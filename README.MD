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
[Airport challenge in Javascript](https://github.com/dangroze/airport_challenge_js.git)<br>
Airport challenge in JS was the first app I did outside of Ruby. Despite the fact that I've used a new language and testing framework, it was relatively easy to understand. Having applied strict TDD and by following the red-green-refactor process, I felt comfortable in a new environment.

[Chitter challenge](https://github.com/dangroze/chitter_challenge)<br>
In this weekend project I've applied the knowledge acquired during the week to build a functional CRUD app, comprehensively tested.

[Bank tech test](https://github.com/dangroze/bank_tech_test.git)<br>
Here I've used dependency injection and delegation, this was a really interesting mini-challenge, all the requirements have been met using TDD, which can be seen in the frequent commits.

### Feedback

Sam J said on Bowling that this was a good go at the challenge, objects have clear responsibilities and looks well tested.

## I can debug anything<a name="debug-anything" />

### What does it mean to be able to do this?

This means to have a clear process, a process that can be applied in any language or technology used, and stick to it. I've come to realise that you can't stay blocked forever. Each and every bug can be resolved, there is a good chance that someone in this world came across the same thing while programming, you just have to know where to look and how to explain the problem to someone else. My process includes following strict TDD, as explained earlier, then if an error message occurs:
1. Read and understand the error message
2. Follow the stack trace
3. Get more visibility ( irb, p, console.log(), etc )
4. Identify where the problem is
5. Use current knowledge and available tools ( google, StackOverflow, friends' advice, etc ) to fix it

### Example repos:

[Week 3 Debugging 2](https://github.com/makersacademy/skills-workshops/tree/master/week-3/debugging_2)<br>
This week's exercise was resolved using a methodical approach and a thorough process:
- Tightened the loop by looking at each test separately
- When the error message and stack trace were not conclusive and descriptive enough, sinatra gave me more clues

[Acebook group project](https://github.com/dangroze/acebook-team-name-undefined)<br>
Having chosen a technology that we haven't used before, when we got to testing, we thought we were in over our heads. With extensive research and lots of trial and error, tightening the loop and gaining visibility, our tests were finally green.

### Feedback

From Nikhil: "Your methodical approach in testing our controllers, and patiently checking each variable was great to experience."

Alice on debugging workshop: "Good understanding of the error messages. Well done!"

Adrien Fabre: "We did debugging together on the What Zen project and I found that he was very good at following the flow of the code, he was able to express clearly that some expected behaviour was not right and he was asking very relevant questions that helped us move forward."

# I can model anything<a name="model-anything" />

### What does it mean to be able to do this?
Being able to model anything is the process of breaking down a system, and represent it as a graphic ecosystem with all the parts that are interacting with each other. Modelling, or diagramming in a programming language context helps with adhering to the encapsulation and single responsibility principle of objects.

When building applications, I have always found modeling and diagramming to be very useful, they are now part of my process. I am a visual learner, so having a clear image of the task is important to me.

### Example repos
[Airport challenge in ruby](https://github.com/dangroze/airport_challenge_ruby)<br>
This minimalistic diagram is a good example of the utility of modelling as it leads the construction of the app, the structure of objects and their responsibilities.

[Takeaway challenge](https://github.com/dangroze/takeaway-challenge)<br>
Here the diagram displays each class with its methods. The flow of actions can be clearly seen, good tool to help me model my thought process.

### Feedback



# I can refactor anything<a name="refactor-anything" />

### What does it mean to be able to do this?

Refactoring means to change the existing code, without changing its behaviour(no added functionality). It means to make sure that the code adheres to the SOLID and DRY principles.

A few guidlines I use when refactoring:
- Make the code cleaner, more readable for any other developers who might want to use the app
- Rename methods for clearness
- Encapsulation(combining data and methods into one unit or class) and delegation of concerns

### Example repos

[Oystercard](https://github.com/dangroze/oystercard)<br>
This challenge helped me get to grips with refactoring and it gave me the guidlines for extracting a class from another one. In order to do this, I've developed a process which starts with diagramming the current class and the encapsulated class. Then I draw arrows pointing from which methods I want to move from the current class to the other. After that, I implement it and refactor so that the tests pass.

[Bowling challenge](https://github.com/dangroze/bowling_challenge)<br>
Here I had to refactor my app so that the back end would match the front end. This was not an easy task at first, but after a few trial and error cycles, I managed to make it work. This is highlighted in this [commit](https://github.com/dangroze/bowling_challenge/commit/fb973950b667fd5066809b726a09c3313ac5537e).

### Feedback



# I have a methodical approach to solving problems<a name="methodical-approach" />

### What does it mean to be able to do this?

My approach/process has improved so much since being a student at Makers. I was always impulsive and whenever a problem arose, I always dove head first into it. Now I take a step back, analyze the situation and plan a lot before I start implementing.<br>
My process of problem solving consists of:
- Make sure I understand the problem
- If something is not clear about it, I read documentations and other resources
- Ask a friend for advice
- Can I solve it right away? Do it. If not, go to next step
- Break it down into smaller problems and tackle them each one by one

### Example repos

[Rock Paper Scissors](https://github.com/dangroze/rps-challenge/tree/master/lib)<br>
Here my thought process was as follows: A player could roll rock, paper or scissors and play vs a computer which will choose one of the weapons at random and a winner will be declared.<br>
I solved this by breaking the system down into objects with a single responsibility, so 3 classes were created, player, computer and game.

### Feedback

Katerina gave me some very useful feedback when doing the process workshop which was to spend more time planning in order to have a general idea of what to implement and how to go about it.

# I help my teams succeed<a name="teams-succeed" />

## I use an agile product development process<a name="agile-process" />

### What does it mean to be able to do this?

The agile process is a repetitive, incremental approach to developing software. It focuses on teamwork, communication between peers and lots of planning.<br>
I came to appreciate the agile process a lot, it just makes sense when working in a team to have everyone on the same page, for everyone to take code ownership and to feel like they have a set role in the project.

### Example repos

[Acebook](https://github.com/dangroze/acebook-team-name-undefined)<br>
During this group project we really put our agile skills to use:
- We've had standups every morning and evening
- We used a sprint driven development. We've had 2-day sprints and managed to deliver our MVP by the end of day 3
- Retrospective at the end of each sprint
- We used a trello board to organize our sprints
- Worked in pairs for the whole duration of the project
- Our pull requests had to be reviewed by 2 other members

[What Zen](https://github.com/dangroze/what-zen-app)<br>
This is our Makers final project, where we made sure we used the agile process to the maximum. Just as with Acebook, we had standups every start and end of day, 2 day sprints and retros at the end of each sprint. We ensured that everyone was up to speed with the progress any one of us made.<br>
Although we picked several technologies that none of us used before, our excellent communication and team dynamic helped us deliver an awesome app.

### Feedback


## I write code that is easy to change<a name="easy-to-change" />

### What does it mean to be able to do this?

Having the ability to write easy to change code is very important for a developer at any stage, and I think that's why our coaches enforced this throughout the course. I believe this will be even more important when working in a big company with large code bases.<br>
When writing code I have the following principles in mind:
- Dependency injection: What this does is providing the objects that an object needs (its dependencies) instead of having it construct them itself. It's a very useful technique for testing, since it allows dependencies to be mocked or stubbed out.
- Single responsibility principle: Every object should have responsibility over a single part of functionality.
- Encapsulation: as mentioned before, the less each object knows about the others, the better since they will depend less on them. As explained in the refactoring goal, whenever possible, I delegate internal behaviour to private functions, use setter methods instead of giving multiple objects access to another object’s properties, etc.
- Naming functions and objects properly: this makes the code easier to change 

