[<img src="assets/images/su-logo.png" alt="Skills Union Logo" height="80px" />](https://www.skillsunion.com/)

# Modern JavaScript & Iteration Methods: Study

Use [DuckDuckGo](https://duckduckgo.com/) or your preferred search engine along with the provided resources to research and answer the [questions below](#questions).

## Required Reading

- [Introduction to Arrow Function](https://www.javascripttutorial.net/es6/javascript-arrow-function/)
- Array's functions:
  - [.forEach](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Array/forEach)
  - [.map](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Array/map)
  - [.filter](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Array/filter)
  - [.reduce](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Array/Reduce)
- [Destructuring](https://medium.com/poka-techblog/destructuring-in-javascript-f4f56d5cbd80)
- [Spread Syntax & Rest Syntax](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Operators/Spread_syntax)
- [Enhanced Object Literal](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Operators/Object_initializer#description) - Read through to "Property Definition" part.

## Questions

1. Re-write the following code by using the arrow function syntax:

   ```js
   function addToCart(item) {
     cart.add(item);
   }
   ```

   ```js
   // Please write your answer here
   ```

2. Consider the functions `renderGuest`, `getGuestsWithChildTicket` and `getGuestsWithChildTicket` functions. Which array iteration methods would you use instead of the for loops?

  ```js
  const guests = [
    {name: "Paul", age: 9, checkIn: false}, 
    {name: "Fatima", age: 46, checkIn: false}, 
    {name: "Anna", age: 16, checkIn: false}, 
    {name: "Silver", age: 50, checkIn: false}
  ]

  const renderGuest = (guests) => {
    for(let i = 0; i < guests.length; i++) {
     document.querySelector('guests').innerHTML += 
      `<p>${guest[i].name} - ${guests[i].age}</p>`
    }
  }

  const getGuestsWithChildTicket = (guests) => {
    const guestsWithChildTicket = []

    for(let i = 0; i < guests.length; i++) {
      if (guests[i].age <= 18) {
        guestsWithChildTicket.push(guests[i])
      }
    }

    return guestsWithChildTicket
  }

  const checkGuestsIn = (guests) => {
    const checkedInGuests = []

    for(let i = 0; i < guests.length; i++) {
      guestsWithChildTicket.push({...guests[i], checkedIn: false})
    }

    return guestsWithChildTicket
  }
  ```

  ```js
   // Please write your answer here
  ```  

2. Write js code to destructure this object:

```js
const person = {
  name: "John",
  age: 21,
  gender: "m",
};

// Add your code here to destructure the object 'person'.
```


3. Edit the code below to use enhanced object literal approach to assign properties.

```js
  const name = "Mary",
  const age = 22,
  const gender = "f",


// Edit this object
const mary = {
  name: person.name,
  age: person.age,
  gender: person.gender,
};
```

### Response Guidelines

Please follow these guidelines as you answers these questions:

- Cite any relevant sources consulted during your research
- Do not reply using direct quotes from the source material
- Provide an answer using your own words and voice
