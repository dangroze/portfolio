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
    * [I can justify the way I work in a business context](#business-context)
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
[Airport Challenge](https://github.com/dangroze/airport_challenge_ruby)<br>
This first weekend project set the tone of the following challenges because here I've learnt how to use doubles, stubbing and mocking and got to grips with the concepts of unit and feature tests. From google searches and asking lots of questions to coaches and colleagues, I've come to the realisation that unit tests make sure that each unit functions correctly in isolation, meaning that if every part does its job like intended, it will be easy to concatenate units together. Feature tests make sure that the system is functioning as the user expects it to. Unit tests are written from the perspective of the programmer, while feature tests are from the perspective of the user.

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

This means that I am comfortable solving a problem and translating it into a computer language. Also to be agile in moving between the states of writing code and fixing problems that may arise while doing so. Fluency in this instance means to either read a code base and understand the inner workings of the program, what each class and method is trying to achieve. Carrying on from being able to read a codebase you should be able to create a function or achieve the outcome of the application in a structurally correct manner without any major stumbles. This means when changing between languages being able to recall each languages structures and functions.


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

[Quiz Tech Test](https://www.youtube.com/watch?v=M7HyzBaxBmo&t=934s)<br>
This was the Maker’s week 10 process review. I want to showcase this example where, under pressure, I've navigated through bugs and error messages, and I've methodically worked them out.
### Feedback

From Nikhil: "Your methodical approach in testing our controllers, and patiently checking each variable was great to experience."

Alice on debugging workshop: "Good understanding of the error messages. Well done!"

Adrien Fabre: "We did debugging together on the What Zen project and I found that he was very good at following the flow of the code, he was able to express clearly that some expected behaviour was not right and he was asking very relevant questions that helped us move forward."

# I can model anything<a name="model-anything" />

### What does it mean to be able to do this?
Being able to model anything is the process of breaking down a system, and represent it as a graphic ecosystem with all the parts that are interacting with each other. Modelling, or diagramming in a programming language context helps with adhering to the encapsulation and single responsibility principle of objects.

When building applications, I have always found modeling and diagramming to be very useful, they are now part of my process. I am a visual learner, so having a clear image of the task is important to me. I always start tackling a problem by trying my best to understand it, either drawing a quick diagram, writing up user stories when needed, or just mentally visualizing the requirements and how would I go about solving it.

### Example repos
[Airport challenge in ruby](https://github.com/dangroze/airport_challenge_ruby)<br>
This minimalistic diagram is a good example of the utility of modelling as it leads the construction of the app, the structure of objects and their responsibilities.

[Takeaway challenge](https://github.com/dangroze/takeaway-challenge)<br>
Here the diagram displays each class with its methods. The flow of actions can be clearly seen, good tool to help me model my thought process.

[Bookmark Manager](https://github.com/dangroze/bookmark_manager)<br>
MVC model can be seen in the readme file.

### Feedback

From J. Park: "I was pairing with Dan during the Oyster Card week and we came across some difficulty whilst carrying out encapsulation and abstraction practices. After a few minutes of trying to hack our way through Dan took a step back and suggested we re-model our code based on the changes that we made across the steps we worked together on through a basic domain model diagram. This simple action immediately allowed us to get a better picture on how our code was working and which dependencies needed some refactoring and allowed us to successfully move on to the next step."

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

Sophie said on Bank Test that I can clearly use the SOLID principles to improve the readability and design of the code.
From J.Park: "I had the pleasure of working with Dan during the MakersBnB week. It was our first time using Ruby on Rails and needless to say our initial code was quite all over the place. Dan's growth in his refactoring skills over the past few weeks clearly shone through when he utilised aspects of polymorphism to refactor some of our controller functions to execute the appropriate actions based on the user_ids which are sent through session objects without breaking the single responsibility principle."

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

[Rock Paper Scissors](https://github.com/dangroze/rps-challenge)<br>
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

From Sherif Shendidy: "During our final project, What-Zen, Dan was strictly committed to following an agile process, where we had stand ups twice a day to discuss each one’s progress with the task in hand, and to make sure our objectives and following tasks are clear. During those stand ups, Dan had very clear and organised thoughts and managed to contribute to the team with very constructive ideas and his contribution definitely helped us deliver the final project on time. It was a real pleasure working with him."

From James Rudrum: “Having worked with Dan on Acebook I feel that he really adopted the agile working mindset. He was consciously measuring against sprint goals and contributing within stand ups and retros. He also ensured we continuously added small features that we could iterate from”

## I write code that is easy to change<a name="easy-to-change" />

### What does it mean to be able to do this?

Having the ability to write easy to change code is very important for a developer at any stage, and I think that's why our coaches enforced this throughout the course. I believe this will be even more important when working in a big company with large code bases.<br>
When writing code I have the following principles in mind:
- Dependency injection: What this does is providing the objects that an object needs (its dependencies) instead of having it construct them itself. It's a very useful technique for testing, since it allows dependencies to be mocked or stubbed out.
- Single responsibility principle: Every object should have responsibility over a single part of functionality.
- Encapsulation: as mentioned before, the less each object knows about the others, the better since they will depend less on them. As explained in the refactoring goal, whenever possible, I delegate internal behaviour to private functions, use setter methods instead of giving multiple objects access to another object’s properties, etc.
- Naming functions and objects properly: this makes the code easier to change 

### Example repos

[Chitter](https://github.com/dangroze/chitter_challenge)<br>
Each unit was fully isolated, including the associated tests, through the use of mocking and dependency injection, which we had learned during the week.

[Bowling](https://github.com/dangroze/bowling-challenge_forked)<br>
I had to refactor some code in order for the back end to match with the front end, so having adhered to the above principles, it was pretty straight-forward to do.

### Feedback

From Sherif Shendidy: "I worked with Dan Groze on 2 projects, Makers B&B and on the final project What-Zen, on both projects Dan should great skills when it can to writing a clean and easy to read code that can easily be changed when the project requirements change."

## I can justify the way I work in a business context<a name="business-context" />

### What does it mean to be able to do this?

This means that you can communicate clearly to your team your approach and how you want to go about doing it. If you have a different, better idea than what was previously suggested, then explain the advantages of going with it.

### Example repos

[Acebook](https://github.com/dangroze/acebook-team-name-undefined)<br>
During this group project I suggested to my team that we should use the Devise gem in order to rapidly implement the user authentication and that the gem would build all the scaffolds that go around it, including password encryption. The team thought this was a good idea and it saved us critical time.

[What Zen](https://github.com/dangroze/what-zen-app)<br>
In our final project, I've communicated to my team that we should choose a project that we could all be passionate about and suggested that we could build a Task Manager using technologies that we haven't used before. This would exercise our ability to learn.

### Feedback

Adrien Fabre on final project: "I really appreciated how Dan was eager to learn and to contribute to different aspects of the project. I could see that during our standups and retros he was clear about what was right for him and he shared his ideas clearly while he was letting everyone space to express their ideas, too."

## I can grow collaboratively<a name="grow-collaboratively" />

### What does it mean to be able to do this?

From the time I've spent at Makers and after talking to a few IT professionals I came to realise that most of a developer's work will be done in teams. Apparently pairing is widely practiced within IT firms, which is why I'm grateful that this has been heavily emphasised during the course.<br>
I've learned how to give constructive feedback and also how to receive it, I've learned not to take it personal, because 99% of the time feedback is benefitting the receiver.<br>
I love working with others and doing so with such a wide variety of people at Makers has enriched my knowledge and communication skills by a lot.

### Feedback

From Nikhil: "I really enjoyed working with you. You're the perfect team player and you're able to effortlessly switch between supporting the driver, or quickly researching new techniques we could use. Having spent 3 difficult days debugging controller tests on the Acebook project, I really appreciate the support and let's not forget about the tips on getting better at table tennis."

# I am equipped for long term growth<a name="longterm-growth" />

## I manage my own well being<a name="well-being" />

### What does this mean?

In my perspective this has everything to do with a balanced life. Being an extremist, I always either work a lot or not at all, so being able to balance the two makes the difference between having a healthy mind and body or not.<br>
A few habits and rituals I try to maintain for my well being:
- Exercise is an important factor in someone's overall condition, so I made a conscious decision to cycle everyday to work and basically everywhere. In addition to that, I lift weights every once in a while, not for a vanity reason, but because it just makes me feel good.
- Always have a project to work on. This is important to me, because I like improving and progressing every day, and it's a good habit to have.
- Take time off. Having a separation between work and leisure is the key factor in overall happiness and well being. Specially for me, because I tend to be a bit obsessive about something once I set my mind on that. So when I feel like I've worked too much, I just take a day off, even two, without doing anything work related. This recharges my batteries and prepares me to go at again with a clear mind.
- Play. I like sports and the ocasional video game. During the 3 months I've spent at Makers, I played table tennis almost every day. It's such a good way to refresh the mind and take a break, and it's a social activity as well, I've made quite a few friends.

### Feedback

Jake Atkin: "I love that you are always in such a good mood, that it's contageous. It always feels good to be around you, you always seem to be focused and positive."
Luca said when watching me play an intense table tennis match that it was the first time he's seen me without smiling, he jokingly said that the determined look on my face was almost scary to watch.


## I can learn anything by myself<a name="learn-anything" />

### What does this mean?

To learn anything by myself means to have the ability to pick up something new and become comfortable and fluid in using it. This means to know what keywords to use when utilising a search engine, where to look for documentation(most of the time the official docs provide the best answers) and most importantly to utilise the current knowledge, applying the same process. I generally believe that you can learn anything on your own, it's not hard, it's new, but of course, never underestimate advice/help from someone who is already an expert. 

### Example repos

[What Zen](https://github.com/dangroze/what-zen-app)<br>
In our final project we decided as a group that this was a good opportunity to explore and learn new technologies, which was scary at first, because of the short timeframe, but by splitting responsibilities between team members and filling each other in, thus making sure we were all on the same page, we managed to build this great app.<br>
[Catch of the day](https://github.com/dangroze/catch-of-the-day-react)<br>
Here is an example where I've learned a bit more about React, in order to help me with my final project. I've learned the basics about components, state, props, JSX, etc.<br>
[Rock Paper Scissors](https://github.com/dangroze/rps-challenge)<br>
Here I've learned how to use heroku for app deployment.

### Feedback

Adrien Fabre on the final project: "Working directly with Dan, I was that he was very focused, we've spent time to explore and learn a technology we haven't used before. With a clear goal, balancing this movement of focus and learning carefully, we succeeded to learn and implement new features at the same time. He was very good at maintaining high productivity work."
