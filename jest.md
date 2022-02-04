# jest

# install

``` bash
npm i --save-dev jest
```
edit in package.json (scripts/test)
 
``` json
"scripts": {
    "test": "jest"
},
```
OR
``` json
  "scripts": {
    "test": "jest --coverage"
  },
```


# in the file to be tested (jest_test.js)
``` javascript
const add = (num1, num2) => {
    return (num1 + num2);
};
// console.log(add(5,6)); // returns 11
module.exports = {
    add,
};
```

# in the test file (jest_test.test.js)
``` js
const {add} = require("./jest_test");

test("two numbers add up", () => {
    expect(add(1, 2)).toBe(3);
});
```

# running tests
``` bash
```