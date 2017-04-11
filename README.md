# array-behavior

A set of common utility functions that handle arrays.

Function Name | Parameters | Returns
--------------|------------|---------
DigBehaviors.ArrayBehavior.buildArray | One or more of any types | Returns an array of all the non-null/non-undefined arguments.  Concatenates the array arguments.
DigBehaviors.ArrayBehavior.buildArrayIfAllExist | One or more of any types | Returns an array of all the arguments if all are non-null/non-undefined; otherwise returns an empty array.  Concatenates the array arguments.

### Dependencies

Dependencies are installed using [Bower](http://bower.io/):

    npm install -g bower
    bower install

### Testing

Tests are run using [web-component-tester](https://github.com/Polymer/web-component-tester):

    npm install -g web-component-tester
    wct

