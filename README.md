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

- Why is Agile so popular in the software development world? 
_I beleive **Agile Development** is popular because its customer its flexible, the choice of Software working over documentation the having customer collaboration, and its more customer driven development._

- Explain the difference between plan-driven and Agile development?

_The idea behind **Plan-Driven** is that the better the planning and the better you understand the plan, the better the execution of the plan and the outcome. Plan-driven development is often called sequential or waterfall -> because tasks are performed in a sequence. E.g. you first write the requirements, you complete the design, you implement the design, then you do the testing and ship the product._

_More specifically, **Agile** is a set of values and principles, which describe a culture in which change is welcome and the customer is the focus of the work. Agile advocates adaptive planning, iterative and incremental development, close collaboration with the customer, and cross-functional teams to build working software. Agile values and principles, as outlined in the Agile Manifesto, underpin a lot of software development methods and practices, such as Scrum or Extreme Programming (XP).

- [ ] What are some of the most important Agile values and principles?
- [ ] Name and explain the purpose of at least 2 Agile methods or tools.

### Refactoring
- [ ] What is the point of refactoring?
- [ ] When should you refactor?  When shouldn't you?
- [ ] What are some potential impacts of refactoring?

### Functional Programming
Describe the uses of these functional programming methods:
- [ ] map
- [ ] filter
- [ ] reduce
- [ ] mutation

### Optimization
- [ ] explain caching
- [ ] explain minification

## Submitting your assessment
- [ ] Put your completed assessment text in a GitHub Gist, and send the link to your Program Manager.
