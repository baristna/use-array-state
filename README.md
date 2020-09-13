# useStateAsArray react hook

<a href="https://www.npmjs.com/package/use-state-as-array"><img alt="npm" src="https://img.shields.io/npm/v/use-state-as-array.svg"></a>

A <a href="https://reactjs.org/docs/hooks-intro.html">React Hook</a> to create multiple react `useState` states as an array. 

<hr />

<a href="#installation">Installation</a>

<hr/>

### Installation
```
$ yarn add use-state-as-array
```

Import
```js
import useStateAsArray from 'use-state-as-array';
```

Usage
```js
const [stateAsArray, setStateAsArray] = useStateAsArray(['first', 'second'])

setStateAsArray(0, 'new value')
```
