---
title: 'Destructuring props in React'
date: '2020-10-10'
---

### What is Destructuring?

Destructuring was introduced in ES6 and is a very powerful JavaScript feature. Before going more in depth, I'd like to clarify that we can 
destructure objects and arrays. If you have used the UseState hook, for example, that is an example of array destructuring.However, I will focus more on
object destructuring. 

Consider the following object:

```javascript
const user = {
  name: "Bob",
  age: 20,
}
```

Destructuring allows us to extract values directly from this object and assign them
to variables:

```javascript
const { name, age } = user;
```

As opposed to: 

```javascript
const name = user.name; 
const age = user.age;
```


