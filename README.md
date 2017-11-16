
- Install `Node.JS`
	- `brew install node`
- Install `npm react-heatpack` command
    - `npm install -g react-heatpack`
- Make a directory called `hello-react`
    - `mkdir hello-react`
    - `cd hello-react`
    - create `index.js` file with below code 
    
    `
    
      import React from 'react';
      export default React.createClass({
          render: function() {
            return <div>Hello React With heatpack!</div>
          }
        })
    
    `
    - now run `heatpack index.js` from `hello-react` folder.
    - Now Open a browser with `http://localhost:3000` url.

- Visit https://github.com/insin/react-heatpack for more information.     