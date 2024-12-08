# swe-sr-1-2

For guidance on setting up and submitting this assignment, refer to the Marcy lab School Docs How-To guide for [Working with Short Response and Coding Assignments](https://marcylabschool.gitbook.io/marcy-lab-school-docs/fullstack-curriculum/how-tos/working-with-assignments#how-to-work-on-assignments).

## Prompt 1

Watch this (10 minute video on JSON)[https://www.youtube.com/watch?v=iiADhChRriM].

Explain what JSON is and explain why the example below is not valid JSON.

```js
{
  name: "Zo",
  isCool: true,
  age: 28
}
```

### Response 1

Add your response here...

## Prompt 2

Explain what a pure function is. Use the example below to help you with your explanation, making sure to indicate why it is (or is not) a pure function. Feel free to add comments to the example to enhance your explanation.

```js
const favoriteLocations = ["New York City", "Jersey City"];
const addBostonToList = (list) => {
  list.unshift("Boston");
};
addBostonToList(favoriteLocations);
console.log(favoriteLocations);
```

### Response 2

Add your response here...

## Prompt 3

Check out [the docs for the rest operator](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Functions/rest_parameters).

Explain what the "rest" operator `...` is and when you would use the rest operator in a function. Provide an example to enhance your explanation.

### Response 3

Add your response here...

## Prompt 4

You are building an app and have to store data about user profiles. Each user profile is represented by an Object with an `id`, `username` and `password` like this:

```js
{
  id: 1234,
  username: 'SpongeBob',
  password: 'dandelion'
}
```

Now, imagine you had hundreds of these user profiles and you want to be able to find any one of those objects by its `id` or `username`. Would it be better to store all of those objects in an array of objects, or in an object of objects? Why?

### Response 4

Add your response here...

## Prompt 5

Imagine you are teaching a brand new programmer a brief lesson about `while` loops. Your lesson should have the following components:
* An explanation of the concept, when it is appropriate to be used, and an analogy ("A `while` loop is a ... It is like a ...")
* An example of the syntax for a `while` loop using a JavaScript code block (triple back ticks)
* An explanation of the syntax using the terms **`while` keyword**, **code block**, and **stop condition**

Below, we've provided an outline for your response but feel free to modify it as you see fit.

### Response 5

Explanation of the concept with an analogy.

Check out this example:

```js
// Add your example here
```

Explanation of the syntax.
