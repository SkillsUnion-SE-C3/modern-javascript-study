[<img src="assets/images/su-logo.png" alt="Skills Union Logo" height="80px" />](https://www.skillsunion.com/)

# Modern JavaScript & Iteration Methods: Study

Use [DuckDuckGo](https://duckduckgo.com/) or your preferred search engine along with the provided resources to research and answer the [questions below](#questions).

## Required Reading

- [Introduction to Arrow Function](https://www.youtube.com/watch?v=22fyYvxz-do)
- Array's functions:
  - [Array iteration methods](https://www.youtube.com/watch?v=Urwzk6ILvPQ&ab_channel=freeCodeCamp.orgfreeCodeCamp.orgVerified)
  - [.forEach](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Array/forEach)
  - [.map](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Array/map)
  - [.filter](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Array/filter)
  - [.reduce](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Array/Reduce)
- [Destructuring](https://www.youtube.com/watch?v=-vR3a11Wzt0&ab_channel=freeCodeCamp.orgfreeCodeCamp.orgVerified)
- [Spread Syntax & Rest Syntax](https://www.youtube.com/watch?v=iLx4ma8ZqvQ&ab_channel=freeCodeCamp.orgfreeCodeCamp.orgVerified)
- [Enhanced Object Literal](https://www.youtube.com/watch?v=Zk6oYqu3tsw&ab_channel=TheNetNinjaTheNetNinjaVerified)

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
    "Paul",
    "Fatima",
    "Anna",
    "Silver",
  ]

  const renderGuest = (guests) => {
    const guestList = document.querySelector('guests')
  
    for(let i = 0; i < guests.length; i++) {
      const guest = guests[i]
      guestList.innerHTML += `<p>${guest}</p>`
    }
  }

  const removeGuest = (guests, name) => {
    const updatedGuestList = []

    for(let i = 0; i < guests.length; i++) {
      const guest = guests[i]
      
      if (guest != name) {
        updatedGuestList.push(guest)
      }
    }
    
    return updatedGuestList
  }

  const checkInAllGuests = (guests) => {
    const checkedInGuests = []

    for(let i = 0; i < guests.length; i++) {
      guest = guests[i]
      checkedInGuests.push(`${guest} - Has checked in`)
    }

    return checkedInGuests
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
  const name = "Mary"
  const age = 22
  const gender = "f"


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
