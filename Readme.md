*This repository is a mirror of the [component](http://component.io) module [ianstormtaylor/to-capital-case](http://github.com/ianstormtaylor/to-capital-case). It has been modified to work with NPM+Browserify. You can install it using the command `npm install npmcomponent/ianstormtaylor-to-capital-case`. Please do not open issues or send pull requests against this repo. If you have issues with this repo, report it to [npmcomponent](https://github.com/airportyh/npmcomponent).*
# to-capital-case

  Convert a string to a capital case.

## Installation

    $ component install ianstormtaylor/to-capital-case
    $ npm install to-capital-case

## Example

```js
var capital = require('to-capital-case');

capital('camelCase');       // "Camel Case"
capital('space case');      // "Space Case"
capital('snake_case');      // "Snake Case"
capital('dot.case');        // "Dot Case"
capital('some*weird[case'); // "Some Weird Case"
```

## API

### toCapitalCase(string)
  
  Returns the capital-case variant of a `string`.

## License

  MIT
