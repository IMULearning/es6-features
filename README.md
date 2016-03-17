# ES6 Features

ES6 features that I myself found useful and would like to remember.

## block scope

```javascript

let a = 0

const b = {
	foo: bar
}

```

## import and export

```javascript

import React, { Component } from 'react'

export default MyComponent

export default function (props) {
	...
}

export function multiple() {
	...
}

```

## destructuring

```javascript

const { onChangeEmail, email, onChangePassword, password, submit } = props;

function render({foo, bar}) {
	...
}

```

## concise objects

```javascript

const actions = {
	sayName() {
		...
	},
	doSomething() {
		...
	},
	foo: bar
}

const map = {
	item1,
	item2
}

```

## arrow functions

```javascript

this.friends.map((friend) => {
	return friend.firstName + ' ' + friend.lastName
})

this.friends.map((friend) => friend.age)

```

## template string

```javascript

const hello = `hello, ${name}!`

```

## default parameters

```javascript

function add(number1 = 0, number2 = 0) {
	return number1 + number2
}

```

## async / await

```javascript

async function handleGetUser() {
	try {
    	var user = await getUser()
    	console.log(user)
  	} catch (error) {
    	console.log('Error in handleGetUser', error)
  	}
}

```

## class

```javascript

class TodoApp extends Component {
	constructor() {
		super()
		this.state = { foo: bar}
	}

	render() {
		return (<div></div>)
	}
}

```