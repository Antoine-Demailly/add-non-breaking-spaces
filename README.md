# add-non-breaking-spaces

> Set of useful functions to handle non-breaking spaces in character strings


## Available languages

- FR (French/France)
- EN (English) **TODO**

## FR (French/France)

### Import/require the method

``` javascript
// ES6 modules
import addNonBreakingSpaces from 'add-non-breaking-spaces/fr';

// node.js way
const addNonBreakingSpaces = require('add-non-breaking-spaces/fr');
```

### Usage

``` javascript
const str = `
  Caius : Hé les connards ! Vous pouvez faire griller un porcelet s’il vous plaît ?
  Arthur : Les connards ?
  Léodagan : S’il vous plaît ?
`;

addNonBreakingSpaces(str);
// will return:
/*
  Caius&nbsp;: Hé les connards&nbsp;! Vous pouvez faire griller un porcelet s’il vous plaît&nbsp;?
  Arthur&nbsp;: Les connards&nbsp;?
  Léodagan&nbsp;: S’il vous plaît&nbsp;?
*/
```

## License

[MIT](http://opensource.org/licenses/MIT)

**Copyright (c) 2020-present — Antoine Demailly**
