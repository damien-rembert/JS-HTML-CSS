# Export and Require

# in the file with the variables/
``` javascript
// declaring multiple variables at once
let name_of_the_var, name_of_another_var, name_of_third_var;
// assigning values


module.exports = {
    name_of_the_var,
    name_of_another_var,
    name_of_third_var,
}
```

# in the file that requires the variables
``` javascript
/// importing the whole object (the two variables)
const importedFunctions = require('./path/to/the/file.js');
// OR, to import only that one var
const {name_of_the_var} = require('./path/to/the/file.js');
```
