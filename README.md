Install with the command:

````
npm install --save res-js-footer
```

Add to a JavaScript Project with the following code:

```javascript
import { footer } from 'res-js-footer'

footer('Some Name);
```

import React, { Component } from 'react';
import { footer } from 'jdh-npm-footer-renderer';

export default class App extends Component {
  render() {
    return (
      <div>
        <h1>DevCamp React Starter</h1>
        { footer('DevCamp') }
      </div>
    );
  }
}