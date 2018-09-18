# List of Helpful FEND JS Terms

## Table of Contents
- [Constructor Function](#constructor-function)
- [Prototypal Inheritance](#prototypal-inheritance)
- [Class Keyword](#class-keyword)
- [Set Object](#set-object)
- [Map and Weak Map Objects](#map-and-weak-map-objects)
- [Promise Object](#promise-object)
- [Generator Functions](#generator-functions)
- [Jasmine Testing](#jasmine-testing)


## Constructor Function
- `new` keyword
- `this` keyword (ES5)
  - `call()` method
  - `apply()` method
  - `bind()` method
- `arguments` keyword

## Prototypal Inheritance
- prototype chain
- `.prototype` property
- `.__proto__` property // dunder proto
- `hasOwnProperty` method
- `isPrototypeOf` method
- `Object.getPrototypeOf` method
- `Object.create` function

## Class Keyword
- `constructor()` method
- instance methods
- class methods
- `static` method
- subclass
  - `extends` keyword
  - `super` keyword

## Set Object
- `add()` method
- `delete()` method
- `clear()` method
- `size` property
- `has()` method
- `values()` method
- `Symbol.iterator` property
- `for of` loop
- `WeakSet` constructor

## Map and Weak Map Objects
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

## Promise Object
- `new Promise()` constructor function
- `callback` function
- `resolve` parameter
- `reject` parameter
- `then()` method
- `catch()` method
- `setTimeOut()` method
- `Promise` chaining
- `then()` method
- return `data`
- `promise.all`

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
