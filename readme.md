# Awesome Micro npm Packages [![Awesome](https://cdn.rawgit.com/sindresorhus/awesome/d7305f38d29fed78fa85652e3a63e154dd8e8829/media/badge.svg)](https://github.com/sindresorhus/awesome)

> A curated list of small, focused Node.js modules.

*Inspired by the [awesome](https://github.com/sindresorhus/awesome) list thing.*


## Articles

* [One-line node modules](https://github.com/sindresorhus/ama/issues/10)
* [Module best practices](https://github.com/mattdesl/module-best-practices)
* [Evaluating Packages Part 1 - Turn to community](http://bytearcher.com/articles/evaluating-packages-1-check-community/) 
* [Evaluating Packages Part 2 - Review repository](http://bytearcher.com/articles/evaluating-packages-2-review-repository/)
* [Small modules: it’s not quite that simple](https://medium.com/@Rich_Harris/small-modules-it-s-not-quite-that-simple-3ca532d65de4)
* [In Defense of Hyper Modular JavaScript](https://medium.freecodecamp.com/in-defense-of-hyper-modular-javascript-33934c79e113)
* [Tiny npm package: Guidelines to create a Node.js module following the small package philosophy](http://g14n.info/2015/12/tiny-npm-package/)
* [The cost of small modules](https://nolanlawson.com/2016/08/15/the-cost-of-small-modules/)

## Modules

### Array

* [is-sorted](https://github.com/dcousens/is-sorted) - A small module to check if an Array is sorted.
* [array-first](https://github.com/jonschlinkert/array-first) - Get the first element or first n elements of an array.
* [array-last](https://github.com/jonschlinkert/array-last) - Return the last element in an array.
* [arr-flatten](https://github.com/jonschlinkert/arr-flatten) - Recursively flatten an array or arrays.
* [dedupe](https://github.com/seriousManual/dedupe) - Remove duplicates from an array.
* [array-range](https://github.com/mattdesl/array-range) - Creates a new array with given range.
* [arr-diff](https://github.com/jonschlinkert/arr-diff) - Returns an array with only the unique values from the first array, by excluding all values from additional arrays using strict equality for comparisons.
* [filled-array](https://github.com/sindresorhus/filled-array) - Returns an array filled with the specified input
* [map-array](https://github.com/parro-it/map-array) - Map object keys and values into an array.
* [in-array](https://github.com/jonschlinkert/in-array) - Return true if any of passed values exists in array - faster than using indexOf.
* [unordered-array-remove](https://github.com/mafintosh/unordered-array-remove) - Efficiently remove an element from an unordered array without doing a splice.
* [array-swap](https://github.com/michaelzoidl/swap-array) - Swap position of two items in an array.
* [mirrarray](https://github.com/johnwquarles/mirrarray) - Creates a keymirror object from an array of valid keys.
* [group-array](https://github.com/doowb/group-array) - Group array of objects into lists.
* [array.chunk](https://github.com/zhiyelee/array.chunk) - Split array/TypedArray to chunks of given size.
* [fast-cartesian](https://github.com/ehmicky/fast-cartesian) - Fast cartesian product.

### String

* [decamelize](https://github.com/sindresorhus/decamelize) - Convert a camelized string into a lowercased one with a custom separator: unicornRainbow → unicorn_rainbow.
* [pad-left](https://github.com/jonschlinkert/pad-left) - Left pad a string with zeros or a specified string.
* [to-camel-case](https://github.com/ianstormtaylor/to-camel-case) - Convert a string to a camel case.
* [to-capital-case](https://github.com/ianstormtaylor/to-capital-case) - Convert a string to a capital case.
* [to-constant-case](https://github.com/ianstormtaylor/to-constant-case) - Convert a string to a constant case.
* [to-dot-case](https://github.com/ianstormtaylor/to-dot-case) - Convert a string to a dot case.
* [to-no-case](https://github.com/ianstormtaylor/to-no-case) - Remove an existing case from a string.
* [to-pascal-case](https://github.com/ianstormtaylor/to-pascal-case) - Convert a string to a pascal case.
* [to-sentence-case](https://github.com/ianstormtaylor/to-sentence-case) - Convert a string to a sentence case.
* [to-snake-case](https://github.com/ianstormtaylor/to-snake-case) - Convert a string to a snake case.
* [to-space-case](https://github.com/ianstormtaylor/to-space-case) - Convert a string to a space case.
* [to-title-case](https://github.com/ianstormtaylor/to-title-case) - Convert a string to a title case.
* [node-slug](https://github.com/dodo/node-slug) - slugifies even utf-8 chars.
* [rtrim](https://github.com/sergejmueller/rtrim) - Strip whitespace - or other characters - from the end of a string.
* [slice.js](https://github.com/hustcc/slice.js) - Javascript library to enhance String.substring / Array.slice with python slice style.
* [strip-ansi](https://github.com/chalk/strip-ansi) - Strip ANSI escape codes.
* [striptags](https://github.com/ericnorris/striptags) - An implementation of PHP's strip_tags in Node.js.
* [parse-next-json-value](https://github.com/ErikOnBike/parse-next-json-value) - Parse next JSON value from string allowing extraneous characters after value.
* [pluralize](https://github.com/DaniAkash/pluralizer) - A very tiny library to pluralize words


### Date & Time

* [pretty-ms](https://github.com/sindresorhus/pretty-ms) - Convert milliseconds to a human readable string: 1337000000 → 15d 11h 23m 20s.
* [hirestime](https://github.com/seriousManual/hirestime) - A wrapper around the built-in high resolution timer which simplifies the calculation of timestamps.
* [periods](https://github.com/timruffles/periods) - Defined time-periods constants for Javascript, in milliseconds.
* [fecha](https://github.com/taylorhakes/fecha) - Javascript Date formatting and parsing.
* [akamai-time-reference](https://github.com/jucrouzet/akamai-time-reference) - Get reference time using Akamai's time reference service.
* [timeago.js](https://github.com/hustcc/timeago.js) - A tiny(~1.7kb) library used to format date with `*** time ago` statement.
* [count-days-in-month](https://github.com/shinnn/count-days-in-month) - Get the number of days in a given month.
* [time-stamp](https://github.com/jonschlinkert/time-stamp) - Get a formatted timestamp.
* [twas](https://github.com/vutran/twas) - Generate a relative time string (Example: "3 seconds ago")

### Object

* [map-obj](https://github.com/sindresorhus/map-obj) - Map object keys and values into a new object.
* [filter-obj](https://github.com/sindresorhus/filter-obj) - Filter object keys and values into a new object.
* [object-values](https://github.com/sindresorhus/object-values) - Get the values of an object.
* [object-pairs](https://github.com/eush77/object-pairs) - Turn an object into list of [key, value] pairs for mapping, iterating or other purposes.
* [zipmap](https://github.com/landau/zipmap) - Returns a map with the keys mapped to the corresponding vals. zipmap also accepts a single value of objects or pairs.
* [just-pluck](https://github.com/jarofghosts/just-pluck) - Pluck without the madness.
* [deep-equal](https://github.com/substack/node-deep-equal) - Node's assert.deepEqual() algorithm as a standalone module.
* [deep-assign](https://github.com/sindresorhus/deep-assign) - Recursive Object.assign().
* [set-value](https://github.com/jonschlinkert/set-value) - Create nested values and any intermediaries dot notation (`'a.b.c'`) paths.
* [get-value](https://github.com/jonschlinkert/get-value) - Use property paths (a.b.c) to get a nested value from an object.
* [has-value](https://github.com/jonschlinkert/has-value) - Returns true if a value exists, false if empty. Works with deeply nested values using dot notation (`'a.b.c'`) paths.
* [has-key-deep](https://github.com/ryanaghdam/has-key-deep) - Deep-search objects for keys. Keys can be searched by providing an array of keys, or using a dot-notiation.
* [flatkeys](https://github.com/ricardobeat/flatkeys) - Flatten object key hierarchies into a list of strings using a custom separator.
* [flatten-obj](https://github.com/watson/flatten-obj) - Converts an object literal with deeply nested nodes to a simple key/value object.
* [is-empty-object](https://github.com/gummesson/is-empty-object) - Check if an object is empty.
* [stringify-object](https://github.com/yeoman/stringify-object) - Stringify an object/array like JSON.stringify just without all the double-quotes.
* [sorted-object](https://github.com/domenic/sorted-object) - Returns a copy of an object with its keys sorted.
* [static-props](https://github.com/fibo/static-props) - Defines static object attributes using `Object.defineProperties`
* [missing-deep-keys](https://github.com/vladgolubev/missing-deep-keys) - Returns an array of keys from first object that are missing in second.
* [has-own-property](https://github.com/LinusU/has-own-property) - Check if an object has a local property. 
* [merge-objects](https://github.com/shevaroller/node-merge-objects) - Deep-merge two objects. Arrays that are values of the same object key get concatenated.
* [deep-object-diff](https://github.com/mattphillips/deep-object-diff) - Deep diff two JavaScript Objects while preserving the data structure. Including nested structures of Arrays and Objects.

### Function

* [compose-function](https://github.com/stoeffel/compose-function) - Compose a new function from smaller functions `f(g(x))`.
* [curry](https://github.com/dominictarr/curry) - A curry function without anything too clever.
* [once](https://github.com/isaacs/once) - Run a function exactly one time.
* [deep-bind](https://github.com/jonschlinkert/deep-bind) - Bind a context to all functions in an object, including deeply nested functions.
* [identity-function](https://github.com/substack/identity-function) - Always return the input argument. 
* [mem](https://github.com/sindresorhus/mem) - An optimization technique used to speed up consecutive function calls by caching the result of calls with identical input.
* [throttle-debounce](https://github.com/niksy/throttle-debounce) - Throttle/debounce your functions.
* [compose-tiny](https://github.com/hipstersmoothie/compose-tiny) - A very tiny and fast compose function.

### Math

* [is-even](https://github.com/jonschlinkert/is-even) - A good way to tell if a number is even or not (avoids type issues). Uses `is-odd` and `is-number` under the hood.
* [is-number](https://github.com/jonschlinkert/is-number) - Returns `true` if the value is a number.
* [is-odd](https://github.com/jonschlinkert/is-odd) - A good way to tell if a number is odd or not (avoids type issues). Uses `is-number` under the hood.
* [easy-math.js](https://github.com/kingzez/easy-math.js) - A tiny easy math library including addition, multiplication, subtraction, and division.
* [my-prime](https://github.com/jinnatul/my-prime) - A good way to tell if a number is prime or not.
* [fun-gcd](https://github.com/zubayerhimel/fun-gcd) - A tiny math library to get gcd of two numbers using Euclidean algorithm

### Stream
* [through2](https://github.com/rvagg/through2) - Tiny wrapper around Node streams2 Transform to avoid explicit subclassing noise.
* [through2-filter](https://github.com/brycebaril/through2-filter) - A through2 to create an Array.prototype.filter analog for streams.
* [through2-map](https://github.com/brycebaril/through2-map) - A through2 to create an Array.prototype.map analog for streams.
* [stream-spigot](https://github.com/brycebaril/node-stream-spigot) - A readable stream generator, useful for testing or converting simple functions into Readable streams.
* [concat-stream](https://github.com/maxogden/concat-stream) - writable stream that concatenates strings or data and calls a callback with the result.
* [JSONStream](https://github.com/dominictarr/JSONStream) - streaming JSON.parse and stringify
* [through2-map-promise](https://github.com/RangerMauve/through2-map-promise) - A small promise-based wrapper for through2.
* [pump](https://github.com/mafintosh/pump) - pipe streams together and close all of them if one of them closes.
* [split](https://github.com/dominictarr/split) - Break up a stream and reassemble it so that each line is a chunk.
* [is-stream](https://github.com/sindresorhus/is-stream) - Check if something is a Node.js stream.
* [syncthrough](https://github.com/mcollina/syncthrough) - Transform your data as it pass by, synchronously.


### Promise

* [pify](https://github.com/sindresorhus/pify) - Promisify a callback-style function.
* [promise-all-props](https://github.com/Siilwyn/promise-all-props) - Like `Promise.all` but for object properties.
* [sleep-promise](https://github.com/brummelte/sleep-promise) - Resolves a promise after a specified delay.
* [is-promise](https://github.com/then/is-promise) - Test whether an object looks like a promises-a+ promise.

### Data Structure

* [quetie](https://github.com/TomerAberbach/quetie) - Just the cutest and tiniest queue/deque implementation!

### File System

* [rimraf](https://github.com/isaacs/rimraf) - A deep deletion module for node (like rm -rf).
* [mkdirp](https://github.com/substack/node-mkdirp) - Recursively mkdir, like mkdir -p.
* [du](https://github.com/rvagg/node-du) - A simple JavaScript implementation of du -sb.
* [file-size](https://github.com/Nijikokun/file-size) - Lightweight filesize to human-readable / proportions w/o dependencies.
* [tmp](https://github.com/raszi/node-tmp) - Temporary file and directory creator for node.js.
* [fs-promise](https://github.com/kevinbeaty/fs-promise) - Node fs methods as Promise/A+ (optional fs-extra, graceful-fs).
* [read-git-user](https://github.com/RocktimSaikia/read-git-user) - Reads the username and email from `.gitconfig` :wrench: and returns it as json object.

### Browser

* [delegate](https://github.com/zenorocha/delegate) - Lightweight event delegation.
* [insert-css](https://github.com/substack/insert-css) - Insert a string of css into the head
* [dom-element-value](https://github.com/crysalead-js/dom-element-value) - DOM element value getter/setter.
* [image-promise](https://github.com/bfred-it/image-promise) - Load one or more `<img>`s in a Promise.
* [get-media-size](https://github.com/bfred-it/get-media-size) - Get the original size of any `img`/`video`/`svg`/`canvas` tags or canvas context.
* [document-ready](https://github.com/bendrucker/document-ready) - Document ready listener for modern browsers.
* [copee](https://github.com/styfle/copee) - Copy text from browser to clipboard...natively!

### Semver

* [semver](https://github.com/npm/node-semver) - The semantic version parser used by npm.
* [semver-max](https://github.com/eush77/semver-max) - Find maximum (or minimum) version according to semver.
* [semver-first-satisfied](https://github.com/parro-it/semver-first-satisfied) - Find minimum in an array of version that satisfies a semver range.



### CLI

* [abbrev](https://github.com/isaacs/abbrev-js) - Calculate the set of unique abbreviations for a given set of strings.
* [glob](https://github.com/isaacs/node-glob) - Glob functionality for node.js.
* [username](https://github.com/sindresorhus/username) - Get the username of the current user.
* [minimist](https://github.com/substack/minimist) - Parse argument options.
* [png-to-ico](https://github.com/steambap/png-to-ico) - Convert png to windows ico format.
* [help-version](https://github.com/eush77/help-version) - Easily handle --help and --version arguments in your CLI application

### Module management

* [pkg-conf](https://github.com/sindresorhus/pkg-conf) - Get namespaced config from the closest package.json.
* [normalize-pkg](https://github.com/jonschlinkert/normalize-pkg) - Normalize values in package.json to improve compatibility, programmatic readability and usefulness with third party libs.

### Generators

* [is-generator](https://github.com/blakeembrey/is-generator) - Check whether a given value is a generator function.

### Other

* [uuid](https://github.com/kelektiv/node-uuid) - Generate RFC-compliant UUIDs in JavaScript.
* [node-mime](https://github.com/broofa/node-mime) - Comprehensive MIME type mapping API based on mime-db module.
* [not-defined](https://github.com/fibo/not-defined) - Checks if foo is not defined, i.e. undefined, null, an empty string, array or object.
* [is-fqdn](https://github.com/parro-it/is-fqdn) - Check if a string represent a fully qualified domain name.
* [shurley](https://github.com/BrunoBernardino/shurley) - Parses URLs from user input (with potential typos in protocols, bad copy+paste, etc.) and returns a proper URL.
* [mime-type-check](https://github.com/RocktimSaikia/mime-type-check) - Get the MIME type of a file by its extension.
* [nanoid](https://github.com/ai/nanoid) - A tiny (130 bytes), secure, URL-friendly, unique string ID generator for JavaScript

### Tools

* [npm-deprecated-check](https://github.com/KID-joker/npm-deprecated-check) - Check for deprecated packages and recommend alternative packages.

## Related lists

This section contains awesome lists that you may find useful if you use or write small NPM modules.

* [awesome-nodejs](https://github.com/sindresorhus/awesome-nodejs) - A curated list of delightful Node.js packages and resources.
* [awesome-npm](https://github.com/sindresorhus/awesome-npm) - Awesome npm resources and tips.

## Small modules rockstars to follow

These people are used to develop awesome NPM modules that follows the single responsibility philosophy.
Follow them to discover new great modules:

[![Sindre Sorhus](https://avatars.githubusercontent.com/u/170270?s=130)](https://github.com/sindresorhus) | [![James Halliday](https://avatars1.githubusercontent.com/u/12631?s=130)](https://github.com/substack) | [![Eugene Sharygin](https://avatars3.githubusercontent.com/u/4472489?s=130)](https://github.com/eush77) | [![Isaac Z. Schlueter](https://avatars3.githubusercontent.com/u/9287?s=130)](https://github.com/isaacs) | [![Jon Schlinkert](https://avatars1.githubusercontent.com/u/383994?s=130)](https://github.com/jonschlinkert) | [![Dominic Tarr](https://avatars3.githubusercontent.com/u/259374?s=130)](https://github.com/dominictarr)
---|---|---|---|---|---
[Sindre Sorhus](https://github.com/sindresorhus) | [James Halliday](https://github.com/substack) | [Eugene Sharygin](https://github.com/eush77) | [Isaac Z. Schlueter](https://github.com/isaacs) | [Jon Schlinkert](https://github.com/jonschlinkert) | [Dominic Tarr](https://github.com/dominictarr)

[![Rod Vagg](https://avatars0.githubusercontent.com/u/495647?s=130)](https://github.com/rvagg) | [![Max Ogden](https://avatars3.githubusercontent.com/u/39759?s=130)](https://github.com/maxogden) | [![Brian Woodward](https://avatars1.githubusercontent.com/u/995160?s=130)](https://github.com/doowb)
---|---|---
[Rod Vagg](https://github.com/rvagg) | [Max Ogden](https://github.com/maxogden) | [Brian Woodward](https://github.com/doowb)


## Contribute

Contributions welcome! Read the [contribution guidelines](contributing.md) first.


## License

[![CC0](http://i.creativecommons.org/p/zero/1.0/88x31.png)](http://creativecommons.org/publicdomain/zero/1.0/)

To the extent possible under law, [Andrea Parodi](https://github.com/parro-it) has waived all copyright and related or neighboring rights to this work.
