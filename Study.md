[<img src="assets/images/su-logo.png" alt="Skills Union Logo" height="80px" />](https://www.skillsunion.com/)

# Lorem ipsum: Study

Use [DuckDuckGo](https://duckduckgo.com/) or your preferred search engine along with the provided resources to research and answer the [questions below](#questions).

## Required Reading

- [Strict Mode in JavaScript](https://www.geeksforgeeks.org/strict-mode-javascript)
- [Introduction to Arrow Function](https://www.javascripttutorial.net/es6/javascript-arrow-function/)

## Questions

1. What are the differences between strict mode and sloppy mode?

   ```
   Please write your answer here.
   ```

2. Turn on strict mode for this function by editing the code in the following block:

   ```js
   // Turn on strict mode for this function
   function sayHi() {
     console.log("hi");
   }
   ```

3. Re-write the following code by using the arrow function syntax:

   ```js
   function addToCart(item) {
     cart.add(item);
   }
   ```

   ```js
   // Please write your answer here
   ```

4. Explain why is the following code not going to work?

   ```js
   class CartClass {
     constructor() {
       this.cart = [];
     }

     add(item) {
       this.cart.push(item);
     }

     print() {
       setTimeout(function () {
         console.log(this.cart);
       }, 500);
     }
   }

   const cart = new CartClass();
   cart.add({ id: 1, name: "toy" });
   cart.print(); // undefined
   ```

   ```
   Please write your answer here
   ```

### Response Guidelines

Please follow these guidelines as you answers these questions:

- Cite any relevant sources consulted during your research
- Do not reply using direct quotes from the source material
- Provide an answer using your own words and voice
