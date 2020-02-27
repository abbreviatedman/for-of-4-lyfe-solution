# For Of 4 Lyfe

### Introduction

This will be an exercise in using function expressions and `for of` loops.

Most times you iterate through an array, you don't need the index you're currently on, so `for of` loops are the simpler and nicer-looking choice.

And every function should be declared with a function expression, because it keeps our functions from being reassigned, preventing many a potential bug.

Together, they make a dynamic duo, serving up simpler and safer syntax for solution-slingers!

That one got away from me. Sorry.


### Setup

1. Fork and clone.
2. Navigate into the directory.
3. `npm install` and `npm test`.
4. Code away in `main.test.js`, NOT `main.js`. (There isn't one for annoying technical test-related reasons.)
5. Read the tests further down in `main.test.js` for function usage examples!


### Guidelines

* Although we won't be testing for what kind of loop you'll be using, this isn't just an exercise in solving problems. Let's use our new `for of` loop!
* We WILL be testing for function expressions using `const`. If you aren't passing that particular test, look up function expressions again, or refer to our example!


### Challenge Descriptions

##### Warmups

* `addAll` - given an array of numbers, returns the sum of all numbers added together.
* `countSpaces` - given a string, returns the number of characters that are spaces.
* `countTrues` - given an array of booleans, returns the number of `true` values.


##### Maps

* `cubeAll` - given an array of numbers, returns an array where each number has been cubed (a.k.a. raised to the third power).
* `addNoises` - given an array of strings, returns an array where each string has appended to it that animal's noise. See tests for examples!
* `makeFriendly` - given an array of paragraphs, returns an array where, for each paragraph, every second sentence ends with an exclamation point instead of the punctuation mark it held before.


##### Filters

* `removeTrolls` - given an array of strings, returns an array where any string in the original that was exclusively in upper case has been removed.
* `onlyDoggos` - given an array of strings, returns an array where any string in the original that didn't represent a dog's name has been removed (same rules as `addNoises`, see examples from either).
