# Reading Class 02

Introduction to NodeJS and Express

1) Middleware is some sort of function that takes in some data, makes some changes if needed, and passes the transformed data onto the next function.

2) Node web framework

3) Express is agnostic to the right way to handle some tasks. The user is able to use whatever combination of middleware to achieve the task, at the cost of making or finding the component.

4) A module is a self-contained code, which allows reusability, managability and debug-ability.

NPM

1) 9.5.1

2) `npm install jshint`

Test Driven Development (TDD)

1) Testing is important because it forces modularity of the code. The test should test a specific piece of code to succesfully do what it is supposed to do. If the test was to test the a large portion of the code that required multiple external factors, it would be hard to debug and figure out where and what went wrong.

2) 1: Reudction of bugs 2: Reduce final phase development 3: Ruggedness of design is asserted

3) Individually: Forgeting to write unit test first and write trivial test that does not produce any value/assertion. Team: Unit test not written across the team, and upkeep of testing suite as the project grows.

CI/CD

1) Bugs are addressed constantly, instead of accumulating. Customers can receive updates more frequently. Code conflict during merge is easier to handle with no feature breaking differences.

2) Continuous delivery is the practice of constantly improving the code through building and testing. Continious deployment is the deployment as code is being delivered.

3) GitHub is a repository to keep track of the code in a project. It allows constant updates to the code without everyone invovled to go through the changes piecewise. It also allows checks and tests in place.

Reflection

1) I still don't have a strong grasp of everyting in Express.js. It seems simplistic enough, but I probably don't understand how powerful it is.