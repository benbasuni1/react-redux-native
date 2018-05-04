# Hello World
---
* Building blocks of React are Elements and Components.

# Introducing JSX
---
```js
// 1. Function abc to return first + last name
function abc(user) { return user.first + user.last }

// 2. User object
const user = {
	firstName : 'Ben',
	lastName  : 'Basuni'
};

// 3. Uses the function from #1 to manipulate obj from #2 in React
const elem = <h1>{formatName(user)}</h1>

// 4. The ReactDOM renders onto the page, 1st param is variable, 2nd element is querySelector
ReactDOM.render(
	element,
	document.querySelector('#root')
);
```
