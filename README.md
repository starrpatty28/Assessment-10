# Assessment #10: Advanced Methods

### Deploying to Heroku

Clich [here](https://eventonica-recat-api.herokuapp.com/) for live site

### Recursion

Recursion is a function calling itself, until it cant call itself anymore. In the below example, the function will continue to loop throuh until it reaches 0.

```
function countDownFrom (num) {
  if (num === 0) return;     
  countDownFrom(num -1);

}
countDownFrom(10);
```

### Memoization

Memoization is a programming technique with the purpose of improving the functions performance, by caching results, so if the same input value is provided you can return results quickly without going through the **Heavy Computations**.

Memoization is best used on **Pure Functions** With pure functions, each time the same input value is provided it will return the same output value. Please see example below of **Pure Function**

```
let fun = function (x) {
  return x * x;
};
```
**Not Pure Function*** relies on data outside of itself and that data can change and affect the results

```
let num = 5;

let fun = function (x) {
  return num * x;
};
```
### Agile Development

## Why is Agile so popular in the software development world?<br>

_I beleive **Agile Development** is popular because its customer driven and its flexible. The choice of Software working over documentation, having customer collaboration, and its more customer driven development._

## Explain the difference between plan-driven and Agile development?<br>

_The idea behind **Plan-Driven** is that the better the planning and the better you understand the plan, the better the execution of the plan and the outcome. Plan-driven development is often called sequential or waterfall -> because tasks are performed in a sequence. E.g. you first write the requirements, you complete the design, you implement the design, then you do the testing and ship the product._

_More specifically, **Agile** is a set of values and principles, which describe a culture in which change is welcome and the customer is the focus of the work. Agile advocates adaptive planning, iterative and incremental development, close collaboration with the customer, and cross-functional teams to build working software. Agile values and principles, as outlined in the Agile Manifesto, underpin a lot of software development methods and practices, such as Scrum or Extreme Programming (XP)._

## What are some of the most important Agile values and principles?<br>

_Agile highest priority is to satisfy the customer through early and continuous delivery of valuable software. Welcome changing requirements, even late in development. Agile processes harness change for the customer's competitive advantage. Business people and developers must work together daily throughout the project. Build projects around motivated individuals. Give them the environment and support they need, and trust them to get the job done. Agile processes promote sustainable development. The sponsors, developers, and  users should be able to maintain a constant pace indefinitely._ 

## Name and explain the purpose of at least 2 Agile methods or tools.<br>

###### Extreme Programming (XP)<br>

_Is a software development methodology which is intended to improve software quality and responsiveness to changing customer requirements. As a type of agile software development,[1][2][3] it advocates frequent "releases" in short development cycles, which is intended to improve productivity and introduce checkpoints at which new customer requirements can be adopted. Other elements of extreme programming include: programming in pairs or doing extensive code review, unit testing of all code, avoiding programming of features until they are actually needed, a flat management structure, code simplicity and clarity, expecting changes in the customer's requirements as time passes and the problem is better understood, and frequent communication with the customer and among programmers._ 

###### Feature-Driven Development (FDD)<br>
_Feature-driven development (FDD) is an iterative and incremental software development process. It is a lightweight or Agile method for developing software. FDD blends a number of industry-recognized best practices into a cohesive whole. These practices are driven from a client-valued functionality (feature) perspective. Its main purpose is to deliver tangible, working software repeatedly in a timely manner in accordance with the Principles behind the Agile Manifesto._


### Refactoring<br>

## What is the point of refactoring?<br>

_**Refactoring** is the process of improving code quality by: Making it easier to read, Making it easier to extend / change later, Not changing the original behavior of the code. It reduces **Technical Dept** which is the cost of having to repeat work now because an easy, quick solution was chosen in the past, instead of a better solution that would have taken longer to complete.

## When should you refactor?  When shouldn't you?<br>

_Refactoring can be done at any time! You should refactor when writing new code, when fixing a bug, during code review._<br> 

_When you shouldnt refactor is when you havecomplicated code that was written for a reason or a significant amount of time was already spent trying to refactor with little results. When code in production has already gone through years of use in the real world and is fully tested._

## What are some potential impacts of refactoring?<br>

_Some potential impacts could be to weigh the cost and benefits of refactoring code. You may find that your refactored code could lead to mistakes and many bugs to fix._

### Functional Programming
Describe the uses of these functional programming methods:<br>
## map
## filter
## reduce
## mutation

### Optimization
- [ ] explain caching
- [ ] explain minification

## Submitting your assessment
- [ ] Put your completed assessment text in a GitHub Gist, and send the link to your Program Manager.
