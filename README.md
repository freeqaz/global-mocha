# global-mocha
Require mocha global variables.

```javascript
// Require the globals and write your test like you normally would.
// No more need to define globals at the top of every test for linting!
import {because, before, it} from 'global-mocha';

because('this is a test', function testFn() {
  before(function setupFn() {
    // Do things.
  });

  it('should pass', function assertFn() {
   // Run asserts.
  });
});

```
