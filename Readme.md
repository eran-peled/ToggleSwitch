# Create a Toggle Switch in React as a Reusable Component

An iOS-inspired toggle switch using React.

This code accompanies the following tutorial: [Create a Toggle Switch in React as a Reusable Component](https://www.sitepoint.com/react-toggle-switch-reusable-component/)

## Requirements

* [A working React project](https://reactjs.org/)

## Installation Steps (if applicable)

1. Clone repo

2. Add files to existing React project

3. Include `ToggleSwitch` component like so: 


   ```js

   import React, { useState } from 'react';

   export default function App() {
     const [checked, setChecked] = useState(true);

     return (
       <ToggleSwitch id="switch" checked={checked} onChange={checked => setChecked(checked)} />`
     );
   }

   ```

## License


SitePoint's code archives and code examples are licensed under the MIT license.

Copyright © 2020 SitePoint

Permission is hereby granted, free of charge, to any person obtaining a copy of this software and associated documentation files (the "Software"), to deal in the Software without restriction, including without limitation the rights to use, copy, modify, merge, publish, distribute, sublicense, and/or sell copies of the Software, and to permit persons to whom the Software is furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY, FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM, OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE SOFTWARE.

