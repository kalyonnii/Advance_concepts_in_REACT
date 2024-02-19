## What is Emmet?

- https://docs.emmet.io/
- https://medium.com/@kartik2406/web-development-with-vs-code-part-1-emmet-6af80f0f630c

## Difference between a Library and Framework?

- https://www.geeksforgeeks.org/software-framework-vs-library/

## What is CDN? Why do we use it?

- https://www.cloudflare.com/learning/cdn/what-is-a-cdn/#:~:text=At%20its%20core%2C%20a%20CDN,exchange%20points%20between%20different%20networks.

##  What is crossorigin in script tag?
- https://developer.mozilla.org/en-US/docs/Web/HTML/Attributes/crossorigin

## What is diference between React and ReactDOM
React and ReactDOM are two different libraries that are used together to build user interfaces with React. React is responsible for creating views and ReactDOM library is responsible to actually render UI in the browser.
React is a declarative JavaScript library for building user interfaces. It lets you compose complex UIs from small and isolated pieces of code called components.
ReactDOM is the glue between React and the DOM. It takes care of updating the DOM when your data changes, and it also provides a number of helper methods for working with the DOM.
Here is a table that summarizes the key differences between React and ReactDOM:
(image.png)
Here is an example of how React and ReactDOM are used together:
import React from 'react';
import ReactDOM from 'react-dom';

const App = () => {
  const [count, setCount] = useState(0);

  return (
    <div>
      <h1>Count: {count}</h1>
      <button onClick={() => setCount(count + 1)}>Increment</button>
    </div>
  );
};

ReactDOM.render(<App />, document.getElementById('root'));


## What is difference between react.development.js and react.production.js files via CDN?

- In development mode, we can enable and utilize React developer tools, devtools profiler, debugging environment attached with source code. We can utilize various functionalities such as **Hot Module Replacement,** diagnostics so that development environment will help to debug code.

In production mode, **compression and minification** of Javascript and other resources happens to reduce size of the code which is not the case when it comes to development mode. Performance will be much faster in production mode when compared to development mode.

## What is async and defer? 
- https://codedamn.com/news/javascript/async-and-defer-in-script-tag
