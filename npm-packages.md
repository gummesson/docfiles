# npm-packages

A collection of useful and/or interesting [npm](https://npmjs.com/) packages.

## Async

- [step.js](https://www.npmjs.com/package/step.js): small step library.
- [run-parallel](https://www.npmjs.com/package/run-parallel): run an array of
  functions in parallel.
- [run-parallel-limit](https://www.npmjs.com/package/run-parallel-limit): run an
  array of functions in parallel, but limit the number of tasks executing at the
  same time.
- [run-waterfall](https://www.npmjs.com/package/run-waterfall): run an array of
  functions in series, each passing its results to the next function.
- [run-series](https://www.npmjs.com/package/run-series): run an array of
  functions in series.
- [run-auto](https://www.npmjs.com/package/run-auto): determine the best order
  for running async functions, and run them.
- [queuealot](https://www.npmjs.com/package/queuealot): bike shed queing module
  using closures for augmenting each result.

## Browserify

- [browserify](https://www.npmjs.com/package/browserify): use `require` in the
  browser.
- [brfs](https://www.npmjs.com/package/brfs): `fs.readFileSync()` static asset
  inliner.
- [babelify](https://npmjs.com/package/babelify): transpile your code with
  [Babel](https://babeljs.io/).
- [uglifyify](https://npmjs.com/package/uglifyify): minify your code using
  [UglifyJS](https://www.npmjs.com/package/uglify-js).
- [budo](https://www.npmjs.com/package/budo): a browserify server for rapid
  prototyping.

## CLI

- [irish-pub](https://www.npmjs.com/package/irish-pub): verify what gets
  published via `npm publish`.
- [internal-ip](https://www.npmjs.com/package/internal-ip): get your internal
  IPv4 address.
- [xit](https://www.npmjs.com/package/xit): configure an external display on
  Linux.
- [gh-pages](https://www.npmjs.com/package/gh-pages): publish files to a
  `gh-pages` branch on GitHub.

## Client

- [layzr.js](https://www.npmjs.com/package/layzr.js): small, fast, modern, and
  dependency-free library for lazy loading.
- [headhesive](https://www.npmjs.com/package/headhesive): on-demand sticky
  header.
- [whatwg-fetch](https://www.npmjs.com/package/whatwg-fetch): `window.fetch`
  JavaScript polyfill.
- [hyperglue](https://www.npmjs.com/package/hyperglue): update HTML elements in
  the browser by mapping query selectors to attributes, text and hypertext.
- [deku](https://www.npmjs.com/package/deku): functional view library for
  building UI components.
- [get-form-data](https://www.npmjs.com/package/get-form-data): get form data
  via `form.elements`.
- [hyperd](https://www.npmjs.com/package/hyperd):
  [virtual-dom](https://www.npmjs.com/package/virtual-dom) based, template
  engine agnostic, lightweight view library.
- [maquette](https://www.npmjs.com/package/maquette): minimalistic virtual DOM
  implementation with support for animated transitions.
- [virtual-html](https://www.npmjs.com/package/virtual-html): convert given HTML
  into [virtual-dom](https://www.npmjs.com/package/virtual-dom) object.
- [virtual-glue](https://www.npmjs.com/package/virtual-glue): render HTML with
  [hyperglue](https://www.npmjs.com/package/hyperglue) and
  [virtual-dom](https://www.npmjs.com/package/virtual-dom).
- [html-patcher](https://www.npmjs.com/package/html-patcher):
  [virtual-dom](https://www.npmjs.com/package/virtual-dom) diff and patch with
  HTML templates.
- [render-loop](https://www.npmjs.com/package/render-loop): build HTML/DOM
  layouts that gets patched automatically with
  [virtual-dom](https://www.npmjs.com/package/virtual-dom).
- [custom-element](https://www.npmjs.com/package/custom-element): light wrapper
  for creating custom element prototypes.
- [custom-element-styles](https://www.npmjs.com/package/custom-element-styles):
  automatically inject styles into a custom element's Shadow DOM.
- [document-register-element](https://www.npmjs.com/package/document-register-element):
  standalone working lightweight version of the W3C Custom Elements
  specification.
- [cyclejs](https://www.npmjs.com/package/cyclejs): honestly reactive framework
  for web user interfaces.
- [flyd](https://www.npmjs.com/package/flyd): less is more, modular, functional
  reactive programming library.

## Color

- [chroma-js](https://www.npmjs.com/package/chroma-js): JavaScript library for
  color conversions.

## CSS

- [cssnext](https://npmjs.com/package/cssnext): use tomorrow's CSS syntax today.
- [normalize.css](https://www.npmjs.com/package/normalize.css): make browsers
  render all elements more consistently and in line with modern standards.

## CSV

- [csv-parser](https://www.npmjs.com/package/csv-parser): streaming CSV parser
  that aims for maximum speed.
- [csv-write-stream](https://www.npmjs.com/package/csv-write-stream): CSV
  encoder stream that produces properly escaped CSVs.

## Databases

- [level](https://www.npmjs.com/package/level): convenience package that bundles
  [levelup](https://www.npmjs.com/package/levelup) and
  [leveldown](https://www.npmjs.com/package/leveldown).
- [super-level](https://www.npmjs.com/package/superlevel): minimalist CLI
  utility for leveldb databases.
- [level-superlevel](https://www.npmjs.com/package/level-superlevel): create
  seperate sections of a levelup database.
- [level-mapped-index](https://www.npmjs.com/package/level-mapped-index): simple
  and flexible indexer for LevelDB.
- [level-browserify](https://www.npmjs.com/package/level-browserify):
  convenience package that bundles [levelup](https://github.com/level/levelup)
  and
  [leveldown](https://github.com/level/leveldown)/[level.js](https://github.com/maxogden/level.js).
- [memdb](https://www.npmjs.com/package/memdb): convenience package that bundles
  [levelup](https://www.npmjs.com/package/levelup) and
  [memdown](https://www.npmjs.com/package/memdown).
- [multilevel-http](https://www.npmjs.com/package/multilevel-http): access a
  leveldb instance from multiple processes via HTTP.
- [level-scout](https://www.npmjs.com/package/level-scout): range search with a
  query plan.
- [level-glob](https://www.npmjs.com/package/level-glob): create a read stream
  filtered and ordered by glob patterns.
- [level-indexer](https://www.npmjs.com/package/level-indexer): generic indexer
  for LevelDB.

## Data structures

- [seamless-immutable](https://www.npmjs.com/package/seamless-immutable):
  Immutable data structures for JavaScript which are backwards-compatible with
  normal arrays and objects.

## DOM

- [tiny-element](https://www.npmjs.com/package/tiny-element): tiny DOM element
  selector.
- [domify](https://www.npmjs.com/package/domify): turn HTML into DOM elements
  x-browser.
- [dombo](https://www.npmjs.com/package/dombo): limited subset of
  [jQuery](https://jquery.com/).
- [scroll-to-element](https://www.npmjs.com/package/scroll-to-element): smooth
  scrolling to an element via selector or node reference.
- [get-anchor](https://www.npmjs.com/package/get-anchor): get an anchor by href
  and optional query.

## Filesystem

- [sane](https://www.npmjs.com/package/sane): aims to be fast, small, and
  reliable file system watcher.

## Functional

- [continuous-stream](https://www.npmjs.com/package/continuous-stream): Streams
  for JavaScript, also known as lazy sequences.
- [fast.js](https://github.com/codemix/fast.js): faster user-land
  reimplementations for several common builtin native JavaScript functions.
- [streamjs](https://www.npmjs.com/package/streamjs): lazy object streaming
  pipeline for JavaScript.
- [1-liners](https://www.npmjs.com/package/1-liners): useful oneliners and
  shorthand functions.

## Functions

- [xtend](https://www.npmjs.com/package/xtend): extend an object by appending
  all of the properties from each object in a list.
- [split-object](https://github.com/timoxley/split-object): work with objects
  using built-in functional array methods.
- [curry](https://www.npmjs.com/package/curry): flexible but simple curry
  function.
- [array-shuffle](https://www.npmjs.com/package/array-shuffle): randomize the
  order of items in an array.
- [arraymax](https://www.npmjs.com/package/arraymax): get maximum value of
  collection.
- [sliced](https://www.npmjs.com/package/sliced): A faster alternative to
  `Array.prototype.slice.call(arguments)`.
- [unique-now](https://www.npmjs.com/package/unique-now): generate unique UNIX
  times.
- [stats-mean](https://www.npmjs.com/package/stats-mean): calculate mean of
  data.
- [stats-median](https://www.npmjs.com/package/stats-median): calculate median
  of data.
- [stats-percentile](https://www.npmjs.com/package/stats-percentile): calculate
  nth percentile of a list of values.
- [stats-variance](https://www.npmjs.com/package/stats-variance): calculate
  variance of data.
- [range](https://www.npmjs.com/package/range): simple library for `range(a, b,
  step)`.
- [queso](https://www.npmjs.com/package/queso): turn a plain object into a query
  string.
- [fuzzysearch](https://www.npmjs.com/package/fuzzysearch): tiny and
  blazing-fast fuzzy search in JavaScript.
- [as-array](https://www.npmjs.com/package/as-array): make any value an array.
- [sluggish](https://www.npmjs.com/package/sluggish): sluggish slug generator
  that works universally.

## HTTP

- [ecstatic](https://www.npmjs.com/package/ecstatic): simple static file server
  middleware.
- [http-server](https://www.npmjs.com/package/http-server): simple
  zero-configuration command-line http server.
- [request](https://www.npmjs.com/package/request): simplified HTTP request
  client.
- [response](https://www.npmjs.com/package/response): streaming and mutation API
  for HTTP responses.
- [nets](http://npmjs.com/package/nets): HTTP client that works the same in
  Node.js and browsers. Uses [xhr](https://www.npmjs.org/package/xhr) for
  browsers and [request](https://www.npmjs.org/package/request) for Node.js.

## Images

- [imagemin](https://www.npmjs.com/package/imagemin): minify images seamlessly.

## JSON

- [is-my-json-valid](https://www.npmjs.com/package/is-my-json-valid): A
  JSONSchema validator that uses code generation to be extremely fast.

## Linting

- [eslint](https://npmjs.com/package/eslint): pluggable linting utility.
- [stylelint](https://www.npmjs.com/package/stylelint): modern CSS linter.

## POSIX

- [cpy](https://www.npmjs.com/package/cpy): copy files and folders using globs.
- [del](https://www.npmjs.com/package/del): delete files and folders using
  globs.
- [mkdirp](https://www.npmjs.com/package/mkdirp): create directories
  recursively.
- [rimraf](https://www.npmjs.com/package/rimraf): remove directories
  recursively.
- [ncp](https://github.com/AvianFlu/ncp): copy files and folders recursively.

## Server

- [root](https://www.npmjs.com/package/root): lightweight prototypical
  middleware web framework.
- [brick-router](https://www.npmjs.com/package/brick-router): modular router for
  serving static assets.
- [brick-server](https://www.npmjs.com/package/brick-server): Create an http
  handler for [brick-server](https://www.npmjs.com/package/brick-router).
- [hyperstream](https://www.npmjs.com/package/hyperstream): stream HTML into
  html at a CSS selector.
- [methodist](https://www.npmjs.com/package/methodist): HTTP method matching.

## Streams

- [through2](https://www.npmjs.com/package/through2): tiny wrapper around
  Node.js `Transform` streams.
- [concat-stream](https://www.npmjs.com/package/concat-stream): concatenates
  strings or binary data and calls a callback with the result.
- [multipipe](https://www.npmjs.com/package/multipipe): better `Stream#pipe`
  that creates duplex streams and lets you handle errors in one place.
- [split](https://www.npmjs.com/package/split): break up a stream and reassemble
  it so that each line is a chunk.
- [stream-iterate](https://www.npmjs.com/package/stream-iterate): iterate
  through the values in a stream.
- [single-line-log](https://www.npmjs.com/package/single-line-log): keep writing
  to the same line in the terminal.

## Strings

- [patterns](https://www.npmjs.com/package/patterns): match a string against a
  list of patterns.

## Testing

- [tape](https://npmjs.com/package/tape): TAP-producing test harness for Node.js
  and browsers.
- [covert](https://www.npmjs.com/package/covert): code coverage command.
- [smokestack](https://www.npmjs.com/package/smokestack): pipe your JavaScript
  into a browser, logging console output in Node.js.
- [tap-closer](https://www.npmjs.com/package/tap-closer): call `window.close` or
  `process.exit` when TAP output is complete.
- [browser-test-helpers](https://www.npmjs.com/package/browser-test-helpers):
  small set of generic test helpers for browser interaction tests.

## Tools

- [napa](http://npmjs.com/package/napa): helper for installing repos without a
  `package.json`.
- [linklocal](https://www.npmjs.com/package/linklocal): install local
  dependencies as symlinks.
- [bulk](https://www.npmjs.com/package/bulk): run a command in every directory
  within a directory.
- [nodemon](https://www.npmjs.com/package/nodemon): simple monitor script for
  use during development.
- [psy](https://www.npmjs.com/package/psy): process monitor command.
- [meow](https://npmjs.com/package/meow): command line application helper.
- [npm-check-updates](https://npmjs.org/package/npm-check-updates): find the
  latest versions of dependencies.
- [cut-release](https://www.npmjs.com/package/cut-release): make faster npm
  releases.
- [npm-run-all](https://www.npmjs.com/package/npm-run-all): run multiple
  npm-scripts sequentially or in parallel.
- [parallelshell](https://www.npmjs.com/package/parallelshell): invoke multiple
  commands, running in parallel.
- [rm-modules](https://www.npmjs.com/package/rm-modules): recursively remove all
  `node_modules` directories within the chosen root directory

## Visualization

- [yako](https://npmjs.com/package/yako): tiny DOM-less graph library.
- [chart.js](https://www.npmjs.com/package/chart.js): simple HTML5 charts using
  the canvas element.
- [chartist.js](https://www.npmjs.com/package/chartist): simple responsive
  charts.
- [d3-bundler](https://www.npmjs.com/package/d3-bundler):
  [Rollup](https://www.npmjs.com/package/rollup)-based bundler for
  [D3](http://d3js.org/) modules.
- [rickshaw](https://www.npmjs.com/package/rickshaw): toolkit for creating
  interactive time series graphs.
