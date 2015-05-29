# global-mocha
Require mocha global variables.

```javascript
'use strict';
// Require the globals and write your test like your normally would.
// No more need to define globals at the top of every test for linting!
var because = require('global-mocha').because;
var before = require('global-mocha').before;
var it = require('global-mocha').it;

because('this is a test', function testFn() {
  before(function setupFn() {
    // Do things.
  });

  it('should pass', function assertFn() {
   // Run asserts.
  });
});

```
