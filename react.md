# React Documentation

## Quick Start
---
#### Hello World
---
* Building blocks of React are Elements and Components.

#### Introducing JSX
---
* Instead of separating technologies by putting markup and logic in separate files, React separates concerns by components.
```js
// 1. Function abc to return first + last name
function abc(user) { return user.first + user.last }

// 2. User object
const user = {
	firstName : 'Ben',
	lastName  : 'Basuni'
};

// 3. JSX Elements
const elem = <h1>{formatName(user)}</h1>
const elem = React.createElement(
	'h1',
	{ className : 'greeting' },
	'Hello world!'
);

// 4. The ReactDOM renders onto the page, 1st param is variable, 2nd element is querySelector
ReactDOM.render(
	element,
	document.querySelector('#root')
);

#### Rendering Elements
--- // 05/04/18
#### Components and Props
--- // 05/05/18
#### State and Lifecycle
--- // 05/06/18
#### Handling Events
--- // 05/07/18
#### Conditional Rendering
--- // 05/08/18
#### Lists and Keys
--- // 05/09/18
#### Forms
--- // 05/10/18
#### Lifting State Up
--- // 05/11/18
#### Composition vs Inheritance
--- // 05/12/18
#### Thinking in React
--- // 05/13/18

## Advanced Guides
---
#### JSX In Depth
--- // 05/14/18
#### Typechecking With PropTypes
--- // 05/15/18
#### Static Type Checking
--- // 05/16/18
#### Refs and the DOM
--- // 05/17/18
#### Uncontrolled Components
--- // 05/18/18
#### Optimizing Performance
--- // 05/19/18
#### React Without ES6
--- // 05/20/18
#### React Without JSX
--- // 05/21/18
#### Reconciliation
--- // 05/22/18
#### Context
--- // 05/23/18
#### Fragments
--- // 05/24/18
#### Portals
--- // 05/25/18
#### Error Boundaries
--- // 05/26/18
#### Web Components
--- // 05/27/18
#### Higher-Order Components
--- // 05/28/18
#### Forwarding Refs
--- // 05/29/18
#### Render Props
--- // 05/30/18
#### Integrating with Other Libraries
--- // 05/31/18
#### Accessibility
--- // 06/01/18
#### Code-Splitting
--- // 06/02/18
#### Strict Mode
--- // 06/03/18

## Reference
---
#### React
--- // 06/04/18
#### React.Component
--- // 06/05/18
#### ReactDOM
--- // 06/06/18
#### ReactDOMServer
--- // 06/07/18
#### DOM Elements
--- // 06/08/18
#### SyntheticEvent
--- // 06/09/18
#### Test Utilities
--- // 06/10/18
#### Shallow Renderer
--- // 06/11/18
#### Test Renderer
--- // 06/12/18
#### JS Environment Requirements
--- // 06/13/18
#### Glossary
--- // 06/14/18

