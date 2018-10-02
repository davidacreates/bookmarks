# List of Helpful FEND JS Terms

## Table of Contents
- [Class Keyword](#class-keyword)
- [Constructor Function](#constructor-function)
- [Fetch API](#fetch-api)
- [Generator Functions](#generator-functions)
- [Jasmine Testing](#jasmine-testing)
- [Map and Weak Map](#map-and-weak-map)
- [Promises](#promises)
- [Prototypes](#prototypes)
- [React](#react)
- [Service Workers](#service-workers)
- [Set](#set)

## Class Keyword
- `constructor()` method
- instance methods
- class methods
- `static` method
- subclass
  - `extends` keyword
  - `super` keyword

## Constructor Function
- `new` keyword
- `this` keyword (ES5)
  - `call()` method
  - `apply()` method
  - `bind()` method
- `arguments` keyword

## Fetch API
- `then()`
- `res` - response
- `res.json()`
- `res.text()`
- `data`
- `catch`
- `method`
- `headers`
- `body`
- `JSON.stringify`

## Generator Functions
- `yield` keyword
- `next()` method
- `value` property
- `Symbol.iterator`
- `for of` loop
- async generators

## Jasmine Testing
- `describe` function
  - suite
  - `it` function
  - `expect` function
  - actual
- matchers
  - `toBe` / `not.toBe`
  - `toBeCloseTo`
  - `toBeDefined`
  - `toBeFalsey` / `toBeTruthy`
  - `toBeGreaterThan` / `toBeLessThan`
  - `toContain`
  - `toEqual`
  - `.not`
- `jasmine.any()`
- `beforeEach` / `afterEach` functions
- `beforeAll` / `afterAll` functions
- spies
  - `createSpy`
  - `addSpy`
  - `spyOn`
  - `toHaveBeenCalled` / `toHaveBeenCalledWith`
  - `callThrough`
- clock
  - `jasmine.clock().install()` / `jasmine.clock().uninstall()` functions
  - `tick` function
  - `done` parameter

## Map and Weak Map
- `set()` method
- `delete()` method
- `clear()` method
- `has()` method
- `get()` method
- `forEach()` method
- `for of` loop
- `Map.iterator` property
- `keys()` method
- `values()` method
- `size` property

## Promises
- `new Promise()` constructor function
  - `resolve` parameter
  - `reject` parameter
  - `then()` method
  - `catch()` method
  - `setTimeOut()` method
- `Promise.all`
  - values
  - fetch
- `async`/ `await`
  - object async
  - class async
  - `await fetch`
  - `try`
  - `catch`
  - `await Promise.all([])`

## Prototypes
- prototype chain
- `.prototype` property
- `.__proto__` property // dunder proto
- `hasOwnProperty` method
- `isPrototypeOf` method
- `Object.getPrototypeOf` method
- `Object.create` function

## React
- `componentWillMount()`
- `componentDidMount()`
- `componentWillUnmount()`
- `componentWillReceiveProps()`

## Service Workers
- progressive web apps
- network proxy
- promises
- background sync
- lifecycle
  - register
  - install
  - activate
  - e.waitUntil

## Set
- `add()` method
- `delete()` method
- `clear()` method
- `size` property
- `has()` method
- `values()` method
- `Symbol.iterator` property
- `for of` loop
- `WeakSet` constructor
