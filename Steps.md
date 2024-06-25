# Steps for Counter App

## Step: 1
- Delete unecessary files: right click setupTests.js -> reveal in file explorer -> delete setupTests.js, reportWebVitals.js, logo.svg, App.test.js

## Step: 2
- install Material UI: npm install @mui/material @emotion/react @emotion/styled

## Step: 3
- Delete header in App.js file

#### Notes
### useState hook:
- The useState hook is a powerful addition to React, introduced in version 16.8. It allows you to manage state within functional components without the need for class-based components.
- In React, useState is a special function that lets you add state to functional components. It provides a way to declare and manage state variables directly within a function component. It should be noted that one use of useState() can only be used to declare one state variable.

### About code:
```js
const [counter, setCounter] = useState(0);
```
- whatever value is set in useState() will be the value of counter

- we have to bind the counter in order for the '+' and '-' button to work, therefore write 'counter' (js code written in {}) 
```js
{/* card text */}
<div className="card_text">
  <h3 className='total_amount_heading'>{counter}</h3>
</div>
```
