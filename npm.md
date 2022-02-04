# npm


## npm init
in your project folder, run `npm init -y`
the -y flag create a default package.json file



## npm install

### installing a module
``` bash
npm install lodash
```
``` javascript
const _ = require("lodash");
```
### installing all the dependencies defined in package.json (eg in a recently cloned repo)
``` bash
npm install
```


adds it to the package.json
individual modules still need to be imported in your js