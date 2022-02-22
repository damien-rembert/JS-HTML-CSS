# React

# components
names should begin with a capital letter

# controled component form in react
look into

# props

```js
ReactDOM.render(<App />, mountNode);
```


# jsx
syntax mixing JS and html

# Requirements for React.js
 our project to create a react
app:
NPM
Webpack
A compiler like Babel
React & React-Dom
A development server to use locally

# Passing 
We can pass a function to another component with props, if we want to pass a value to that function in an event (onClick), using anonymous function
``` jsx
    return (
        <div >
            <h1>Hello, Common here</h1>
            {numbers.map((number, index) => {
                // here we pass the index to that function using anonymous function
                return <h1 onClick={() => removeHandler(index)}key={index}>{number}</h1>
            })}
            <button onClick={addHandler}>add number</button>
        </div>
    );
```

# React.Fragment
<> or <React.Fragment>
to be used when you do not want to add a div to the dom
downside cannot use attributes

# testing

install:
``` bash
npm install --save @testing-library/react @testing-library/jest-dom
```

If you want to avoid boilerplate in your test files, you can create a src/setupTests.js file:
``` JS
// react-testing-library renders your components to document.body,
// this adds jest-dom's custom assertions
import '@testing-library/jest-dom';
```

Example to test App.js:
in src/App.test.js
``` JS
import React from 'react';
import ReactDOM from 'react-dom';
import App from './App';

it('renders without crashing', () => {
  const div = document.createElement('div');
  ReactDOM.render(<App />, div);
});
```
