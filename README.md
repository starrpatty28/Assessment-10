# Assessment #10: Advanced Methods

### Languages
- JS

### Tools & Methods
- Agile Project Management
- GitHub Gist
- Heroku

### Primary Goals
Demonstrate understanding of Week 10 concepts.

### Overview
In this project, you will create a text file and describe this week's concepts in your own words. You have 2 hours.

## Basic Requirements

### Deploying to Heroku

Clich [here](https://eventonica-recat-api.herokuapp.com/) for live site

### Recursion

Recursion is a function calling itself, until it cant call itself anymore. In the below example, the function will continue to loop throuh until it reaches 0.

```function countDownFrom (num) {
  if (num === 0) return;     
  countDownFrom(num -1);

}
countDownFrom(10);
```

### Memoization

Memoization is a programming technique with the purpose of improving the functions performance, by caching results, so if the same input value is provided you can return results quickly without going through the **Heavy Computations**.

Memoization is best used on **Pure Functions** With pure functions, each time the same input value is provided it will return the same output value. Please see example below of **Pure Function**

```let fun = function (x) {
  return x * x;
};
```
**Not Pure Function*** relies on data outside of itself and that data can change and affect the results

```let num = 5;

let fun = function (x) {
  return num * x;
};
```
### Agile Development
- [ ] Why is Agile so popular in the software development world?
- [ ] Explain the difference between plan-driven and Agile development?
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
