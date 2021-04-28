English | [简体中文](./README-zh-CN.md)

## Table of contents

- [Table of contents](#table-of-contents)
- [Official](#official)
- [Repository](#repository)
  - [Text](#text)
  - [Number](#number)
  - [Math](#math)
  - [Date & Time](#date--time)
  - [URL](#url)
  - [JSON](#json)
  - [Streams](#streams)
  - [Type Checking](#type-checking)
  - [Data Validation](#data-validation)
  - [Shell](#shell)
  - [Environment](#environment)
  - [Command-line Utilities](#command-line-utilities)
  - [Node.js Management](#nodejs-management)
  - [NPM](#npm)
  - [Filesystem](#filesystem)
  - [Git](#git)
  - [Logging](#logging)
  - [Process management](#process-management)
  - [Linter & Formatter](#linter--formatter)
  - [Build Tools](#build-tools)
  - [Templating](#templating)
  - [Web Frameworks](#web-frameworks)
  - [Static Site Generator & Blogging](#static-site-generator--blogging)
  - [Real-time](#real-time)
  - [Debugging / Profiling](#debugging--profiling)
  - [Forum](#forum)
  - [Database](#database)
  - [Automation & RPA](#automation--rpa)
  - [Testing](#testing)
  - [Office](#office)
  - [OS Identification](#os-identification)
  - [Email](#email)
  - [HTTP](#http)
  - [Crawler](#crawler)
  - [Job Scheduling](#job-scheduling)
  - [AST](#ast)
  - [Design To Code（D2C）](#design-to-coded2c)
  - [Sandbox](#sandbox)
  - [Machine learning](#machine-learning)
  - [Natural language processing](#natural-language-processing)

## Official
- [Website](https://nodejs.org)
- [Documentation](https://nodejs.org/dist/latest/docs/api/)
- [Repository](https://github.com/nodejs/node)

## Repository

### Text

- Common
  - [dedent](https://github.com/dmnd/dedent) - ES6 string tag that strips indentation from multi-line strings.
  - [camelcase](https://github.com/sindresorhus/camelcase) - Convert a dash/dot/underscore/space separated string to camelCase: foo-bar → fooBar.
  - [detect-indent](https://github.com/sindresorhus/detect-indent) - Detect the indentation of code.
  - [string-length](https://github.com/sindresorhus/string-length) - Get the real length of a string - by correctly counting astral symbols and ignoring ansi escape codes.
  - [strip-indent](https://github.com/sindresorhus/strip-indent) - Strip leading whitespace from every line in a string.
  - [indent-string](https://github.com/sindresorhus/indent-string) - Indent each line in a string.
  - [min-indent](https://github.com/jamiebuilds/min-indent) - Get the shortest leading whitespace from lines in a string.
  - [splice-string](https://github.com/sindresorhus/splice-string) - Remove or replace part of a string like `Array#splice`.

- i18n
  - [i18next](https://github.com/i18next/i18next) - Internationalization framework.
  - [i18n-node](https://github.com/mashpie/i18n-node) - Simple translation module with dynamic JSON storage.
  - [babelfish](https://github.com/nodeca/babelfish) - human friendly i18n for javascript (node.js + browser).

- Unique Id
  - [nanoid](https://github.com/ai/nanoid) - Tiny, secure, URL-friendly, unique string ID generator.
  - [uuid](https://github.com/uuidjs/uuid) - Generate RFC-compliant UUIDs in JavaScript.
  - [pure-uuid](https://github.com/rse/pure-uuid) - Pure JavaScript Based Universally Unique Identifiers (UUID).

- Encode/Decode
  - [he](https://github.com/mathiasbynens/he) - HTML entity encoder/decoder.
  - [iconv-lite](https://github.com/ashtuchkin/iconv-lite) - Convert character encodings.
  - [jschardet](https://github.com/aadsm/jschardet) - Character encoding auto-detection in JavaScript (port of python's chardet)

- RegExp/Glob
  - [minimatch](https://github.com/isaacs/minimatch) - A minimal matching utility.
  - [matcher](https://github.com/sindresorhus/matcher) - Simple wildcard matching.
  - [escape-string-regexp](https://github.com/sindresorhus/escape-string-regexp) - Escape RegExp special characters.
  - [execall](https://github.com/sindresorhus/execall) - Find multiple RegExp matches in a string.

- Other
  - [StegCloak](https://github.com/kurolabs/stegcloak) - Conceal secrets within strings, in plain sight.
  - [unhomoglyph](https://github.com/nodeca/unhomoglyph) - Normalize visually similar unicode characters.

### Number

- [Numeral.js](https://github.com/adamwdraper/Numeral-js) - A javascript library for formatting and manipulating numbers.
- [decimal.js](https://github.com/MikeMcl/decimal.js) - An arbitrary-precision Decimal type for JavaScript.
- [big.js](https://github.com/MikeMcl/big.js) - A small, fast JavaScript library for arbitrary-precision decimal arithmetic.
- [round-to](https://github.com/sindresorhus/round-to) - Round a number to a specific number of decimal places: `1.234` → `1.2`.
- [unique-random](https://github.com/sindresorhus/unique-random) - Generate random numbers that are consecutively unique.
- [random-int](https://github.com/sindresorhus/random-int) - Generate a random integer.
- [random-float](https://github.com/sindresorhus/random-float) - Generate a random float.

### Math

- [mathjs](https://github.com/josdejong/mathjs) - An extensive math library.
- [ndarray](https://github.com/scijs/ndarray) - Multidimensional arrays.
- [algebra](https://github.com/fibo/algebra) - Algebraic structures.
- [multimath](https://github.com/nodeca/multimath) - Core to create fast image math in WebAssembly and JS.

### Date & Time

- [moment](https://github.com/moment/moment) - Parse, validate, manipulate, and display dates in javascript.
- [dayjs](https://github.com/iamkun/dayjs) - Day.js 2KB immutable date-time library alternative to Moment.js with the same modern API.
- [date-fns](https://github.com/date-fns/date-fns) - Modern JavaScript date utility library.
- [luxon](https://github.com/moment/luxon) - Library for working with dates and times.
- [ms](https://github.com/vercel/ms) - Tiny millisecond conversion utility.
- [dateformat](https://github.com/felixge/node-dateformat) - A node.js package for Steven Levithan's excellent dateFormat() function.

### URL

- [URI.js](https://github.com/medialize/URI.js) - Javascript URL mutation library.
- [qs](https://github.com/ljharb/qs) - Querystring parser with nesting support.
- [query-string](https://github.com/sindresorhus/query-string) - Parse and stringify URL query strings.
- [url-parse](https://github.com/unshiftio/url-parse) - Small footprint URL parser that works seamlessly across Node.js and browser environments.
- [normalize-url](https://github.com/sindresorhus/normalize-url) - Normalize a URL.
- [url-pattern](https://github.com/snd/url-pattern) - Easier than regex string matching patterns for urls and other strings. turn strings into data or data into strings.
- [native-url](https://github.com/GoogleChromeLabs/native-url) - Node's url module implemented using the built-in URL API.
- [url-join](https://github.com/jfromaniello/url-join) - Join all arguments together and normalize the resulting url.
- [humanize-url](https://github.com/sindresorhus/humanize-url) - Humanize a URL: https://sindresorhus.com → sindresorhus.com.
- [parseurl](https://github.com/pillarjs/parseurl) - Parse a url with memoization.
- [file-url](https://github.com/sindresorhus/file-url) - Convert a file path to a file URL: `unicorn.jpg` → `file:///Users/sindresorhus/unicorn.jpg`
- [encodeurl](https://github.com/pillarjs/encodeurl) - Encode a URL to a percent-encoded form, excluding already-encoded sequences.

### JSON

- [json5](https://github.com/json5/json5) - JSON5 — JSON for humans.
- [fast-json-stringify](https://github.com/fastify/fast-json-stringify) - 2x faster than JSON.stringify()
- [jsonfile](https://github.com/jprichardson/node-jsonfile) - Easily read/write JSON files.
- [load-json-file](https://github.com/sindresorhus/load-json-file) - Read and parse a JSON file.
- [write-json-file](https://github.com/sindresorhus/write-json-file) - Stringify and write JSON to a file atomically.

### Streams

- [event-stream](https://github.com/dominictarr/event-stream) - EventStream is like functional programming meets IO.
- [through2](https://github.com/rvagg/through2) - Tiny wrapper around Node streams2 Transform to avoid explicit subclassing noise.
- [JSONStream](https://github.com/dominictarr/JSONStream) - streaming JSON.parse and stringify.
- [mississippi](https://github.com/maxogden/mississippi) - A collection of useful stream utility modules for writing better code using streams. 1k
- [readable-stream](https://github.com/nodejs/readable-stream) - Node-core streams for userland.
- [pump](https://github.com/mafintosh/pump) - pipe streams together and close all of them if one of them closes.
- [concat-stream](https://github.com/maxogden/concat-stream) - writable stream that concatenates strings or data and calls a callback with the result.
- [stream-json](https://github.com/uhop/stream-json) - stream-json is a collection of node.js stream components for creating custom standard-compliant JSON processors, which requires a minimal memory footprint. It can parse JSON files far exceeding available memory. Even individual primitive data items (keys, strings, and numbers) can be streamed piece-wise. Streaming SAX-inspired event-based API is included as well.
- [split](https://github.com/dominictarr/split) - Break up a stream and reassemble it so that each line is a chunk. matcher may be a String, or a RegExp.
- [tar-stream](https://github.com/mafintosh/tar-stream) - tar-stream is a streaming tar parser and generator.
- [node-byline](https://github.com/jahewson/node-byline) - Line-by-line Stream reader.
- [ndjson](https://github.com/maxogden/ndjson) - streaming line delimited json parser + serializer](https://github.com/mcollina/cloneable-readable).
- [oppressor](https://github.com/substack/oppressor) - streaming http compression response negotiator.
- [multistream](https://github.com/feross/multistream) - A stream that emits multiple other streams one after another (streams2).
- [get-stream](https://github.com/sindresorhus/get-stream) - Get a stream as a string, buffer, or array.
- [node-stream-buffer](https://github.com/samcday/node-stream-buffer) - Readable and Writable Streams that use backing Buffers.
- [split2](https://github.com/mcollina/split2) - Split streams3 style.
- [fstream](https://github.com/npm/fstream) - Advanced FS Streaming for Node.
- [pumpify](https://github.com/mafintosh/pumpify) - Combine an array of streams into a single duplex stream using pump and duplexify.
- [progress-stream](https://github.com/freeall/progress-stream) - Read the progress of a stream.
- [merge-stream](https://github.com/grncdr/merge-stream) - Merge multiple streams into one interleaved stream.
- [duplexify](https://github.com/mafintosh/duplexify) - Turn a writeable and readable stream into a streams2 duplex stream with support for async initialization and streams1/streams2 input.
- [into-stream](https://github.com/sindresorhus/into-stream) - Convert a buffer/string/array/object into a stream.
- [merge2](https://github.com/teambition/merge2) - Merge multiple streams into one stream in sequence or parallel.
- [end-of-stream](https://github.com/mafintosh/end-of-stream) - Call a callback when a readable/writable/duplex stream has completed or failed.
- [stream-to-promise](https://github.com/bendrucker/stream-to-promise) - Convert streams (readable or writable) to promises.
- [node-streamifier](https://github.com/gagle/node-streamifier) - Converts a Buffer/String to a readable stream.
- [stream-spec](https://github.com/dominictarr/stream-spec) - executable specification for Stream (make testing streams easy).
- [from2](https://github.com/hughsk/from2) - Convenience wrapper for ReadableStream, inspired by through2.
- [dmap-stream](https://github.com/dominictarr/map-stream) - refactored out of event-stream.
- [emit-stream](https://github.com/substack/emit-stream) - turn event emitters into streams and streams into event emitters.
- [stream-combiner](https://github.com/dominictarr/stream-combiner) - Turn a pipeline into a single stream. Combine returns a stream that writes to the first stream and reads from the last stream.
- [duplexer](https://github.com/raynos/duplexer) - Creates a duplex stream.
- [promise-streams](https://github.com/spion/promise-streams) - A collection of node.js streams that work well with promises (through, map, reduce, etc...).
- [binary-split](https://github.com/maxogden/binary-split) - A fast newline (or any delimiter) splitter stream.
- [stream-combiner2](https://github.com/substack/stream-combiner2) - stream-combiner for streams3.
- [through2-concurrent](https://github.com/almost/through2-concurrent) - Simple Node.JS stream (streams2) Transform that runs the transform functions concurrently (with a set max concurrency).
- [cloneable-readable](https://github.com/mcollina/cloneable-readable) - Clone a Readable stream, safely.
- [destroy](https://github.com/stream-utils/destroy) - destroy a stream if possible.
- [peek-stream](https://github.com/mafintosh/peek-stream) - Transform stream that lets you peek the first line before deciding how to parse it.
- [resumer](https://github.com/substack/resumer) - a through stream that starts paused and resumes on the next tick.
- [stream-each](https://github.com/mafintosh/stream-each) - Iterate all the data in a stream.
- [flush-write-stream](https://github.com/mafintosh/flush-write-stream) - A write stream constructor that supports a flush function that is called before finish is emitted.
- [multi-write-stream](https://github.com/mafintosh/multi-write-stream) - Create a writable stream that writes to multiple other writeable streams.
- [first-chunk-stream](https://github.com/sindresorhus/first-chunk-stream) - Buffer and transform the n first bytes of a stream.
- [multi-read-stream](https://github.com/mafintosh/multi-read-stream) - Readable stream that reads from multiple readable streams at the same time.
- [node-stream-reduce](https://github.com/parshap/node-stream-reduce) - Reduce stream data to a single value.
- [stream-shift](https://github.com/mafintosh/stream-shift) - Returns the next buffer/object in a stream's readable queue.
- [stream-assert](https://github.com/floatdrop/stream-assert) - Assertion library for streams.
- [stream-from-promise](https://github.com/schnittstabil/stream-from-promise) - Create streams from promises.
- [stromjs](https://github.com/lewisdiamond/stromjs) - Dependency-free stream utils. The Lodash of streams.
- [exec-stream](https://github.com/suarasaur/exec-stream) - stream to a child process.
- [stream-callback](https://github.com/kikobeats/stream-callback) – Turns a stream into a callback.

### Type Checking

- [is](https://github.com/enricomarino/is) - The definitive JavaScript type testing library.
- [is-type-of](https://github.com/node-modules/is-type-of) - Complete type checking for node.
- [is-stream](https://github.com/sindresorhus/is-stream) - Check if something is a Node.js stream.
- [core-util-is](https://github.com/isaacs/core-util-is) - The util.is* functions from Node core.
- [isstream](https://github.com/rvagg/isstream) - Determine if an object is a Node.js Stream.
- [is-class](https://github.com/miguelmota/is-class) - Check if function is an ES6 class.
- [is-type](https://github.com/juliangruber/is-type) - Type checking from node core.

### Data Validation

- [validator.js](https://github.com/validatorjs/validator.js) - A library of string validators and sanitizers.
- [joi](https://github.com/hapijs/joi) - Object schema description language and validator for JavaScript objects.
- [class-validator](https://github.com/typestack/class-validator) - Decorator-based property validation for classes.
- [ajv](https://github.com/epoberezkin/ajv) - The fastest JSON schema Validator. Supports JSON Schema draft-04/06/07/2019-09/2020-12 and JSON Type Definition (RFC8927).
- [Superstruct](https://github.com/ianstormtaylor/superstruct) - Simple and composable way to validate data in JavaScript (and TypeScript).
- [v8n](https://github.com/imbrn/v8n) - JavaScript fluent validation library
- [forgJs](https://github.com/oussamahamdaoui/forgJs) - Javascript lightweight object validator.
- [validatorjs](https://github.com/mikeerickson/validatorjs) - Data validation library in JavaScript for the browser and Node.js, inspired by Laravel's Validator.
- [is-my-json-valid](https://github.com/mafintosh/is-my-json-valid) - JSON Schema validator that uses code generation to be extremely fast.
- [property-validator](https://github.com/nettofarah/property-validator) - Easy property validation for JavaScript, Node and Express.
- [schema-inspector](https://github.com/Atinux/schema-inspector) - JSON API sanitization and validation.

### Shell

- [shelljs](https://github.com/shelljs/shelljs) - Cross-platform Unix shell commands.
- [execa](https://github.com/sindresorhus/execa) - Cross-platform implementation of `child_process.{execFile,exec}`.
- [node-windows](https://github.com/coreybutler/node-windows) - Windows support for Node.js scripts (daemons, eventlog, UAC, etc).
- [clipboardy](https://github.com/sindresorhus/clipboardy) - Cross-platform copy/paste.
- [cross-spawn](https://github.com/IndigoUnited/node-cross-spawn) - Cross-platform implementation of `child_process.spawn()`.
- [figures](https://github.com/sindresorhus/figures) - Unicode symbols with Windows fallbacks.
- [clipboard-cli](https://github.com/sindresorhus/clipboard-cli) - Cross-platform copy/paste.
- [gulp-execa](https://github.com/ehmicky/gulp-execa) - Cross-platform command execution in Gulp.js.
- [cross-spawn-promise](https://github.com/zentrick/cross-spawn-promise) - Promisified cross-spawn.

### Environment

- [cross-env](https://github.com/kentcdodds/cross-env) - Set environment variables cross-platform.
- [which](https://github.com/npm/node-which) - Cross-platform implementation of Unix's `which`.
- [user-home](https://github.com/sindresorhus/user-home) - Get the path to the user home directory. Cross-platform.
- [username](https://github.com/sindresorhus/username) - Get the current username.
- [osenv](https://github.com/npm/osenv) - Cross-platform environment variables.
- [is-elevated](https://github.com/sindresorhus/is-elevated) - Check if the process is running with elevated privileges.

### Command-line Utilities

- [Commander.js](https://github.com/tj/commander.js) - The complete solution for node.js command-line interfaces.
- [chalk](https://github.com/chalk/chalk) - Terminal string styling done right.
- [Inquirer.js](https://github.com/SBoudrias/Inquirer.js) - Collection of common interactive command line user interfaces.
- [yargs](https://github.com/yargs/yargs) - Collection of common interactive command line user interfaces.
- [ora](https://github.com/sindresorhus/ora) - Elegant terminal spinner.
- [Enquirer](https://github.com/enquirer/enquirer) - Stylish CLI prompts that are user-friendly, intuitive and easy to create.
- [minimist](https://github.com/substack/minimist) - Guts of optimist's argument parser without all the fanciful decoration.
- [concurrently](https://github.com/kimmobrunfeldt/concurrently) - Run commands concurrently. Like `npm run watch-js & npm run watch-less` but better.
- [colors.js](https://github.com/Marak/colors.js) - Get colors in your node.js console.
- [progress](https://github.com/visionmedia/node-progress) - Flexible ascii progress bar for nodejs.
- [depcheck](https://github.com/depcheck/depcheck) - Check your npm module for unused dependencies.
- [progress-estimator](https://github.com/bvaughn/progress-estimator) - Logs a progress bar and estimation for how long a Promise will take to complete.
- [update-notifier](https://github.com/yeoman/update-notifier) - Update notifications for your CLI app.
- [cac](https://github.com/cacjs/cac) - Simple yet powerful framework for building command-line apps.
- [log-symbols](https://github.com/sindresorhus/log-symbols) - Colored symbols for various log levels.
- [cli-progress](https://github.com/AndiDittrich/Node.CLI-Progress) - Easy to use progress-bar for command-line/terminal applications.
- [cli-table3](https://github.com/cli-table/cli-table3) - Pretty unicode tables for the command line.
- [common-bin](https://github.com/node-modules/common-bin) - Abstraction bin tool wrap yargs, to provide more convenient usage, support async / generator.
- [kolorist](https://github.com/marvinhagemeister/kolorist) - A tiny utility to colorize stdin/stdout.

### Node.js Management

- [nvm](https://github.com/nvm-sh/nvm) - Node Version Manager。
- [nvm for Windows](https://github.com/coreybutler/nvm-windows) - Version management for Windows.
- [n](https://github.com/tj/n) - Node.js version management.
- [fnm](https://github.com/Schniz/fnm) - 🚀 Fast and simple Node.js version manager, built in Rust.
- [nave](https://github.com/isaacs/nave) - Virtual Environments for Node.js.
- [nodenv](https://github.com/nodenv/nodenv) - Version manager that is similar to Ruby's rbenv. It supports auto version switching.
- [nodeenv](https://github.com/ekalinin/nodeenv) - Node.js virtual environment compatible to Python's virtualenv.

### NPM

- NPM Management
  - [npm](https://github.com/npm/cli) - The package manager for JavaScript.
  - [yarn](https://github.com/yarnpkg/berry) - A modern package manager split into various packages.
  - [nrm](https://github.com/Pana/nrm) - About NPM registry manager, fast switch between different registries: npm, cnpm, nj, taobao.
  - [cnpm](https://github.com/cnpm/cnpm) - Npm client for China mirror of npm.

- package.json
  - [read-pkg](https://github.com/sindresorhus/read-pkg) - Read a package.json file.
  - [write-pkg](https://github.com/sindresorhus/write-pkg) - Write a package.json file.

- Semantic Version
  - [semver](https://github.com/npm/node-semver) - The semver parser for node (the one npm uses).

- Utilities
  - [npm-check-updates](https://github.com/raineorshine/npm-check-updates) - Find newer versions of package dependencies than what your package.json allows.
  - [npm-run-all](https://github.com/mysticatea/npm-run-all) - A CLI tool to run multiple npm-scripts in parallel or sequential.
  - [npminstall](https://github.com/cnpm/npminstall) - Make `npm install` fast and easy.
  - [npm-home](https://github.com/sindresorhus/npm-home) - Open the npm page of a package.
  - [npm-name](https://github.com/sindresorhus/npm-name) - Check a package name's availability on npm.
  - [pacote](https://github.com/npm/pacote) - Fetches package manifests and tarballs from the npm registry.
  - [npm-package-arg](https://github.com/npm/npm-package-arg) - Parse the things that can be arguments to `npm install`.
  - [npm-registry-fetch](https://github.com/npm/npm-registry-fetch) - Like fetch() but for the npm registry
  - [npm-updater](https://github.com/node-modules/npm-updater) - Check update of npm package.

### Filesystem

- Common
  - [fs-extra](https://github.com/jprichardson/node-fs-extra) - Extra methods for the `fs` module.
  - [rimraf](https://github.com/isaacs/rimraf) - Recursively delete files like rm -rf.
  - [del](https://github.com/sindresorhus/del) - Delete files and directories.
  - [graceful-fs](https://github.com/isaacs/node-graceful-fs) - Graceful-fs functions as a drop-in replacement for the fs module, making various improvements.
  - [filesize.js](https://github.com/avoidwork/filesize.js) - Generate a human readable String describing the file size.
  - [make-dir](https://github.com/sindresorhus/make-dir) - Recursively create directories like mkdir -p.
  - [memfs](https://github.com/streamich/memfs) - In-memory filesystem with Node's API.
  - [temp](https://github.com/bruce/node-temp) - Temporary File, Directory, and Stream support for Node.js.
  - [cpy](https://github.com/sindresorhus/cpy) - Copy files.
  - [mkdirp](https://github.com/isaacs/node-mkdirp) - Recursively mkdir, like `mkdir -p`.

- Watch
  - [chokidar](https://github.com/paulmillr/chokidar) - Minimal and efficient cross-platform file watching library.
  - [watchpack](https://github.com/webpack/watchpack) - Wrapper library for directory and file watching.

- Glob
  - [glob](https://github.com/isaacs/node-glob) - Glob functionality for node.js.
  - [globby](https://github.com/sindresorhus/globby) - Based on fast-glob but adds a bunch of useful features.
  - [fast-glob](https://github.com/mrmlnc/fast-glob) - Very fast and efficient glob library for Node.js.

- Compression / Decompression
  - [jszip](https://github.com/Stuk/jszip) - Create, read and edit .zip files with Javascript.
  - [tar-fs](https://github.com/mafintosh/tar-fs) - Tar-fs allows you to pack directories into tarballs and extract tarballs into directories.
  - [7zip](https://github.com/fritx/win-7zip) - 7zip Windows Package via Node.js

### Git

- [nodegit](https://github.com/nodegit/nodegit) - Node bindings to the libgit2 project.
- [simple-git](https://github.com/steveukx/git-js) - A light weight interface for running git commands in any node.js application.
- [gitgraph-node](https://github.com/nicoespeon/gitgraph.js/tree/master/packages/gitgraph-node) - Draw pretty git graphs in your terminal.
- [git-url-parse](https://github.com/IonicaBizau/git-url-parse) - A high level git url parser for common git providers.
- [git-promise](https://github.com/piuccio/git-promise) - Simple wrapper to run any git command and process it's output using promises.
- [gittar](https://github.com/lukeed/gittar) - Download and/or Extract git repositories (GitHub, GitLab, BitBucket). Cross-platform and Offline-first.
- [remote-git-tags](https://github.com/sindresorhus/remote-git-tags) - Get tags from a remote git repo. Using only JS.
- [giturl](https://github.com/repo-utils/giturl) - Transfer git url to web url.
- [download-git-repo](https://gitlab.com/flippidippi/download-git-repo) - Download and extract a git repository (GitHub, GitLab, Bitbucket) from node.

### Logging

- [winston](https://github.com/winstonjs/winston) - Multi-transport async logging library.
- [pino](https://github.com/pinojs/pino) - Extremely fast logger inspired by Bunyan.
- [signale](https://github.com/klauscfhq/signale) - Highly configurable logging utility.
- [log4js-node](https://github.com/log4js-node/log4js-node) - A logging library which different from Java log4j.
- [consola](https://github.com/nuxt/consola) - Elegant Console Logger for Node.js and Browser.
- [storyboard](https://github.com/guigrpa/storyboard) - A library, plus a Chrome DevTools extension.
- [cabin](https://github.com/cabinjs/cabin) - Best JavaScript and Node.js logging service and logging npm package.
- [fancy-log](https://github.com/gulpjs/fancy-log) - Log things, prefixed with a timestamp.
- [captains-log](https://www.npmjs.com/package/captains-log) - Lightweight logger with a simple pass-through configuration for use with fancier logging librarie.

### Process management

- [PM2](https://github.com/Unitech/pm2) - Advanced Process Manager.
- [nodemon](https://github.com/remy/nodemon) - Monitor for changes in your app and automatically restart the server.
- [forever](https://github.com/foreversd/forever) - A simple CLI tool for ensuring that a given script runs continuously.
- [supervisor](https://github.com/petruisfan/node-supervisor) - Restart scripts when they crash or restart when a `*.js` file changes.
- [node-windows](https://github.com/coreybutler/node-windows) - Run scripts as a native Windows service and log to the Event viewer.
- [node-mac](https://github.com/coreybutler/node-mac) - Run scripts as a native Mac daemon and log to the console app.
- [node-linux](https://github.com/coreybutler/node-linux) - Run scripts as native system service and log to syslog.

### Linter & Formatter

- [prettier](https://github.com/prettier/prettier) - ❤Prettier is an opinionated code formatter.
- [standard](https://github.com/standard/standard) - JavaScript Style Guide, with linter & automatic code fixer.
- [eslint](https://github.com/eslint/eslint) - Find and fix problems in your JavaScript code.
- [stylelint](https://github.com/stylelint/stylelint) - Mighty, modern linter that helps you avoid errors and enforce conventions in your styles.
- [lint-staged](https://github.com/okonet/lint-staged) - Run linters on git staged files.
- [commitlint](https://github.com/conventional-changelog/commitlint) - Lint commit messages.
- [xo](https://github.com/xojs/xo) - JavaScript/TypeScript linter (ESLint wrapper) with great defaults
- [markdownlint](https://github.com/DavidAnson/markdownlint) - A Node.js style checker and lint tool for Markdown/CommonMark files.
- [textlint](https://github.com/textlint/textlint) - The pluggable natural language linter for text and markdown.

### Build Tools

- [webpack](https://github.com/webpack/webpack) - Packs modules and assets for the browser.
- [parcel](https://github.com/parcel-bundler/parcel) - Blazing fast, zero config web app bundler.
- [gulp](https://github.com/gulpjs/gulp) - Streaming and fast build system that favors code over config.
- [Vite](https://github.com/vitejs/vite) - Next Generation Frontend Tooling
- [rollup](https://github.com/rollup/rollup) - Next-generation ES2015 module bundler.
- [pkg](https://github.com/zeit/pkg) - Package your Node.js project into an executable.
- [Grunt](https://github.com/gruntjs/grunt) - JavaScript Task Runner
- [Brunch](https://github.com/brunch/brunch) - Front-end web app build tool with simple declarative config, fast incremental compilation, and an opinionated workflow.
- [FuseBox](https://github.com/fuse-box/fuse-box) - Fast build system that combines the power of webpack, JSPM and SystemJS, with first-class TypeScript support.
- [Broccoli](https://github.com/broccolijs/broccoli) - Fast, reliable asset pipeline, supporting constant-time rebuilds and compact build definitions.

### Templating

- [Pug](https://github.com/pugjs/pug) - High-performance template engine heavily influenced by Haml.
- [handlebars.js](https://github.com/wycats/handlebars.js) - Superset of Mustache templates which adds powerful features like helpers and more advanced blocks.
- [mustache.js](https://github.com/janl/mustache.js) - Minimal templating with {{mustaches}} in JavaScript.
- [marko](https://github.com/marko-js/marko) - HTML-based templating engine that compiles templates to CommonJS modules and supports streaming, async rendering and custom tags.
- [art-template](https://github.com/aui/art-template) - High performance JavaScript templating engine.
- [nunjucks](https://github.com/mozilla/nunjucks) - Templating engine with inheritance, asynchronous control, and more (jinja2 inspired).
- [EJS](https://github.com/mde/ejs) - Simple unopinionated templating language.
- [doT](https://github.com/olado/doT) - Fastest + concise javascript template engine for nodejs and browsers. Partials, custom delimiters and more.
- [Twig.js](https://github.com/twigjs/twig.js) - JS implementation of the Twig Templating Language.
- [hbs](https://github.com/pillarjs/hbs) - Express view engine wrapper for Handlebars.
- [xtemplate](https://github.com/xtemplate/xtemplate) - High Speed, eXtensible Template Engine lib on browser and nodejs. support async control, inheritance, include, logic expression, custom function and more.

### Web Frameworks

- [Express](https://github.com/expressjs/express) - Web application framework, providing a robust set of features for building single and multi-page, and hybrid web applications.
- [Next.js](https://github.com/zeit/next.js) - Minimalistic framework for server-rendered universal JavaScript web apps.
- [Meteor](https://github.com/meteor/meteor) - An ultra-simple, database-everywhere, data-on-the-wire, pure-Javascript web framework. *(You might like [awesome-meteor](https://github.com/Urigo/awesome-meteor))*
- [Nuxt.js](https://github.com/nuxt/nuxt.js) - Minimalistic framework for server-rendered Vue.js apps.
- [Nest](https://github.com/nestjs/nest) - Angular-inspired framework for building efficient and scalable server-side apps. *(You might like [awesome-nestjs](https://github.com/juliandavidmr/awesome-nestjs))*
- [Koa](https://github.com/koajs/koa) - Framework designed by the team behind Express, which aims to be a smaller, more expressive, and more robust foundation for web applications and APIs.
- [sails](https://github.com/balderdashy/sails) - Realtime MVC Framework for Node.js.
- [Fastify](https://github.com/fastify/fastify) - Fast and low overhead web framework.
- [Hapi](https://github.com/hapijs/hapi) - Framework for building applications and services.
- [Egg](https://github.com/eggjs/egg) - Born to build better enterprise frameworks and apps with Node.js & Koa.
- [Feathers](https://github.com/feathersjs/feathers) - Microservice framework built in the spirit of Express.
- [LoopBack](https://github.com/strongloop/loopback) - Powerful framework for creating REST APIs and easily connecting to backend data sources.
- [Restify](https://github.com/restify/node-restify) - Enables you to build correct REST web services.
- [ThinkJS](https://github.com/thinkjs/thinkjs) - Framework with ES2015+ support, WebSockets, REST API.
- [Midway](https://github.com/midwayjs/midway) - A Node.js framework for building Serverless services, traditional server-side applications, microservices, and small programs.
- [total.js](https://github.com/totaljs/framework) - A framework for Node.js platfrom written in pure JavaScript similar to PHP's Laravel or Python's Django or ASP.NET MVC
- [AdonisJs](http://adonisjs.com) - A true MVC framework for Node.js built on solid foundations of Dependency Injection and IoC container.
- [Micro](https://github.com/zeit/micro) - Minimalistic microservice framework with an async approach.
- [Moleculer](https://moleculer.services) - Fast & powerful microservices framework.
- [TypeGraphQL](https://github.com/19majkel94/type-graphql) - Modern framework for creating GraphQL APIs with TypeScript, using classes and decorators.
- [seneca](https://github.com/senecajs/seneca) - Toolkit for writing microservices.
- [beidou](https://github.com/alibaba/beidou) - Isomorphic framework for server-rendered React apps.
- [Marble.js](https://github.com/marblejs/marble) - Functional reactive framework for building server-side apps, based on TypeScript and RxJS.
- [ActionHero](https://github.com/actionhero/actionhero) - Framework for making reusable & scalable APIs for TCP sockets, WebSockets, and HTTP clients.
- [lad](https://github.com/ladjs/lad) - The best Node.js framework. Made by a former Express TC and Koa team member.
- [Tinyhttp](https://github.com/talentlessguy/tinyhttp) - Modern and fast Express-like web framework.
- [Hemera](https://github.com/hemerajs/hemera) - Write reliable and fault-tolerant microservices with [NATS](https://nats.io).
- [Zeronode](https://github.com/sfast/zeronode) - Minimal building block for reliable and fault-tolerant microservices.

### Static Site Generator & Blogging

- [gatsby](https://github.com/gatsbyjs/gatsby) - Build blazing fast, modern apps and websites with React.
- [hexo](https://github.com/hexojs/hexo) - A fast, simple & powerful blog framework, powered by Node.js.
- [vuepress](https://github.com/vuejs/vuepress) - Minimalistic Vue-powered static site generator.
- [netlify-cms](https://github.com/netlify/netlify-cms) - A Git-based CMS for Static Site Generators.
- [react-static](https://github.com/react-static/react-static) - A progressive static site generator for React.
- [gridsome](https://github.com/gridsome/gridsome) - The Jamstack framework for Vue.js.
- [vitepress](https://github.com/vuejs/vitepress) - Vite & Vue powered static site generator.

### Real-time

- [Socket.io](https://github.com/socketio/socket.io) - Enables real-time bidirectional event-based communication.
- [ws](https://github.com/websockets/ws) - Simple to use, blazing fast and thoroughly tested WebSocket client and server for Node.js.
- [µWebSockets](https://github.com/uWebSockets/uWebSockets) - Highly scalable WebSocket server & client library.
- [MQTT.js](https://github.com/mqttjs/MQTT.js) - Client for MQTT - Pub-sub based messaging protocol for use on top of TCP/IP.
- [SocketCluster](https://github.com/SocketCluster/socketcluster) - Scalable HTTP + WebSocket engine which can run on multiple CPU cores.
- [Faye](https://github.com/faye/faye) - Real-time client-server message bus, based on Bayeux protocol.
- [Primus](https://github.com/primus/primus) - An abstraction layer for real-time frameworks to prevent module lock-in.
- [engine.io](https://github.com/socketio/engine.io) - The implementation of transport-based cross-browser/cross-device bi-directional communication layer for Socket.IO.
- [SockJS-node](https://github.com/sockjs/sockjs-node) - WebSocket emulation - Node.js server.
- [Aedes](https://github.com/mcollina/aedes) - Barebone MQTT server that can run on any stream server.
- [rpc-websockets](https://github.com/elpheria/rpc-websockets) - JSON-RPC 2.0 implementation over WebSockets.
- [deepstream.io](https://github.com/deepstreamIO/deepstream.io-client-js) - Scalable real-time microservice framework.
- [Kalm](https://github.com/kalm/kalm.js) - Low-level socket router and middleware framework.

### Debugging / Profiling

- [node-inspector](https://github.com/node-inspector/node-inspector) - Debugger based on Blink Developer Tools.
- [ndb](https://github.com/GoogleChromeLabs/ndb) - Improved debugging experience, enabled by Chrome DevTools.
- [debug](https://github.com/visionmedia/debug) - Tiny debugging utility.
- [ironNode](https://github.com/s-a/iron-node) - Node.js debugger supporting ES2015 out of the box.
- [0x](https://github.com/davidmarkclements/0x) - Flamegraph profiling.
- [leakage](https://github.com/andywer/leakage) - Write memory leak tests.
- [why-is-node-running](https://github.com/mafintosh/why-is-node-running) - Node.js is running but you don't know why?
- [llnode](https://github.com/nodejs/llnode) - Post-mortem analysis tool which allows you to inspect objects and get insights from a crashed Node.js process.
- [swagger-stats](https://github.com/slanatech/swagger-stats) - Trace API calls and monitor API performance, health, and usage metrics.
- [njsTrace](https://github.com/valyouw/njstrace) - Instrument and trace your code, see all function calls, arguments, return values, as well as the time spent in each function.
- [locus](https://github.com/alidavut/locus) - Starts a REPL at runtime that has access to all variables.
- [stackman](https://github.com/watson/stackman) - Enhance an error stacktrace with code excerpts and other goodies.
- [NiM](https://github.com/june07/nim) - Manages DevTools debugging workflow.
- [thetool](https://github.com/sfninja/thetool) - Capture different CPU, memory, and other profiles for your app in Chrome DevTools friendly format.
- [ctrace](https://github.com/automation-stack/ctrace) - Well-formatted and improved trace system calls and signals.
- [vstream](https://github.com/joyent/node-vstream) - Instrumentable streams mix-ins to inspect a pipeline of streams.

### Forum

- [NodeBB](https://github.com/NodeBB/NodeBB) - Node.js based forum software built for the modern web
- [nodeclub](https://github.com/cnodejs/nodeclub/) - A forum software based on Node.js and MongoDB.

### Database

- Drivers
  - [MySQL](https://github.com/mysqljs/mysql) - A pure node.js JavaScript Client implementing the MySQL protocol.
  - [PostgreSQL](https://github.com/brianc/node-postgres) - PostgreSQL client for node.js.
  - [MongoDB](https://github.com/mongodb/node-mongodb-native) - The Official MongoDB Node.js Driver.
  - [ioredis](https://github.com/luin/ioredis) - A robust, performance-focused and full-featured Redis client for Node.js.
  - [LevelUP](https://github.com/Level/levelup) - A wrapper for abstract-leveldown compliant stores, for Node.js and browsers.
  - [couchdb-nano](https://github.com/apache/couchdb-nano) - Nano: The official Apache CouchDB library for Node.js.
  - [Couchbase](https://github.com/couchbase/couchnode) - Couchbase Node.js Client Library (Official).
  - [Aerospike](https://github.com/aerospike/aerospike-client-nodejs) - Node.js client for the Aerospike database.

- ODM / ORM
  - [Sequelize](https://github.com/sequelize/sequelize) - Multi-dialect ORM. Supports PostgreSQL, SQLite, MySQL, and more.
  - [TypeORM](https://github.com/typeorm/typeorm) - ORM for PostgreSQL, MariaDB, MySQL, SQLite, and more.
  - [Mongoose](https://github.com/Automattic/mongoose) - Elegant MongoDB object modeling.
  - [Prisma](https://github.com/prisma/prisma) - Modern database access (ORM alternative). Auto-generated and type-safe query builder in TypeScript. Supports PostgreSQL, MySQL & SQLite.
  - [Bookshelf](https://github.com/bookshelf/bookshelf) - ORM for PostgreSQL, MySQL and SQLite3 in the style of Backbone.js.
  - [Objection.js](https://github.com/Vincit/objection.js) - Lightweight ORM built on the SQL query builder Knex.
  - [Waterline](https://github.com/balderdashy/waterline) - Datastore-agnostic tool that dramatically simplifies interaction with one or more databases.
  - [pg-promise](https://github.com/vitaly-t/pg-promise) - PostgreSQL framework for native SQL using promises.
  - [MikroORM](https://github.com/mikro-orm/mikro-orm) - TypeScript ORM based on Data Mapper, Unit of Work and Identity Map patterns. Supports MongoDB, PostgreSQL, MySQL and SQLite.
  - [Massive](https://github.com/robconery/massive-js) - PostgreSQL data access tool.
  - [slonik](https://github.com/gajus/slonik) - PostgreSQL client with strict types, detailed logging and assertions.
  - [OpenRecord](https://github.com/PhilWaldmann/openrecord) - ORM for PostgreSQL, MySQL, SQLite3 and RESTful datastores. Similar to ActiveRecord.

- Query builder
  - [Knex](https://github.com/tgriesser/knex) - Query builder for PostgreSQL, MySQL and SQLite3, designed to be flexible, portable, and fun to use.

### Automation & RPA

- [puppeteer](https://github.com/puppeteer/puppeteer) - Headless Chrome Node.js API.
- [playwright](https://github.com/microsoft/playwright) - Automate Chromium, Firefox and WebKit with a single API.
- [phantomjs](https://github.com/ariya/phantomjs) - Scriptable Headless Browser.
- [appium](https://github.com/appium/appium) - Automation for iOS, Android, and Windows Apps.

### Testing

- Assertion
  - [chai](https://github.com/chaijs/chai) - BDD / TDD assertion framework for node.js and the browser that can be paired with any testing framework.
  - [power-assert](https://github.com/power-assert-js/power-assert) - Provides descriptive assertion messages through the standard assert interface.
  - [expect.js](https://github.com/Automattic/expect.js) - Minimalistic BDD-style assertions for Node.JS and the browser.
  - [should.js](https://github.com/shouldjs/should.js) - BDD style assertions for node.js.
  - [better-assert](https://github.com/tj/better-assert) - C-style assert() for nodejs, reporting the expression string as the error message.
  - [http-assert](https://github.com/jshttp/http-assert) - Assert with status codes.

- Mock
  - [Mock.js](https://github.com/nuysoft/Mock) - A simulation data generator.
  - [Nock](https://github.com/pgte/nock) - HTTP mocking and expectations.
  - [Sinon.JS](https://github.com/sinonjs/sinon) - Test spies, stubs and mocks.
  - [easy-mock](https://github.com/easy-mock/easy-mock) - A persistent service that generates mock data quickly and provids visualization view.
  - [mm](https://github.com/node-modules/mm) - An simple but flexible mock(or say stub) package, mock mate.
  - [smoke](https://github.com/sinedied/smoke) - 💨 Simple yet powerful file-based mock server with recording abilities.

- Testing Framework
  - [jest](https://github.com/facebook/jest) - Delightful JavaScript Testing.
  - [mocha](https://github.com/mochajs/mocha) - Simple, flexible, fun javascript test framework for node.js & the browser.
  - [ava](https://github.com/avajs/ava) - Node.js test runner that lets you develop with confidence 🚀.
  - [jasmine](https://github.com/jasmine/jasmine) - Simple JavaScript testing framework for browsers and node.js.
  - [supertest](https://github.com/visionmedia/supertest) - Super-agent driven library for testing node.js HTTP servers using a fluent API.

### Office

- Excel
  - [sheetjs](https://github.com/SheetJS/sheetjs) - Spreadsheet Data Toolkit.
  - [exceljs](https://github.com/exceljs/exceljs) - Excel Workbook Manager.
  - [xlsx-populate](https://github.com/dtjohnson/xlsx-populate) - Excel XLSX parser/generator written in JavaScript with Node.js and browser support.

- Word
  - [officegen](https://github.com/Ziv-Barber/officegen) - Standalone Office Open XML files (Microsoft Office 2007 and later) generator for Word (docx), PowerPoint (pptx) and Excell (xlsx) in javascript. The output is a stream.
  - [Mammoth](https://github.com/mwilliamson/mammoth.js) - Convert Word documents (.docx files) to HTML.
  - [docx](https://github.com/dolanmiu/docx) - Easily generate .docx files with JS/TS with a nice declarative API. Works for Node and on the Browser.

- PDF
  - [PDFKit](https://github.com/foliojs/pdfkit) - JavaScript PDF generation library for Node and the browser.
  - [percollate](https://github.com/danburzo/percollate) - A command-line tool to turn web pages into beautiful, readable PDF, EPUB, or HTML docs.
  - [pdf2json](https://github.com/modesty/pdf2json) - A PDF file parser that converts PDF binaries to text based JSON.

- PPT
  - [nodeppt](https://github.com/ksky521/nodeppt) - This is probably the best web presentation tool so far!

### OS Identification

- [systeminformation](https://github.com/sebhildebrandt/systeminformation) - Hardware/software system information.
- [is-wsl](https://github.com/sindresorhus/is-wsl) - Detect whether current platform is WSL (Windows Subsystem for Linux).
- [os-name](https://github.com/sindresorhus/os-name) - Get the name of the current operating system.
- [getos](https://github.com/retrohacker/getos) - Retrieve the current OS, including Linux distribution.
- [is-windows](https://github.com/jonschlinkert/is-windows) - Detect whether the current platform is Windows.

### Email

- [Nylas Mail](https://github.com/nylas/nylas-mail) - An extensible desktop mail app built on the modern web.
- [Nodemailer](https://github.com/nodemailer/nodemailer) - Send e-mails with Node.JS – easy as cake!
- [Email Templates](https://github.com/forwardemail/email-templates) - Create, preview, and send custom email templates for Node.js.
- [emailjs](https://github.com/eleith/emailjs) - Html emails and attachments to any smtp server with nodejs.
- [mjml](https://github.com/mjmlio/mjml) - Makes responsive-email easy.

### HTTP

- Request Client
  - [axios](https://github.com/mzabriskie/axios) - Promise based HTTP client (works in the browser too).
  - [request](https://github.com/request/request) - 🏊🏾 Simplified HTTP request client.
  - [superagent](https://github.com/visionmedia/superagent) - HTTP request library.
  - [http-proxy](https://github.com/nodejitsu/node-http-proxy) - HTTP proxy.
  - [got](https://github.com/sindresorhus/got) - Nicer interface to the built-in `http` module.
  - [node-fetch](https://github.com/bitinn/node-fetch) - `window.fetch` for Node.js.
  - [needle](https://github.com/tomas/needle) - Nimble, streamable HTTP client for Node.js. With proxy, iconv, cookie, deflate & multipart support.
  - [download](https://github.com/kevva/download) - Download and extract files effortlessly.
  - [urllib](https://github.com/node-modules/urllib) - Request HTTP(s) URLs in a complex world.
  - [gotql](https://github.com/khaosdoctor/gotql) - GraphQL request library built on [got](https://github.com/sindresorhus/got).
  - [wreck](https://github.com/hapijs/wreck) - HTTP Client Utilities.
  - [http-fake-backend](https://github.com/micromata/http-fake-backend) - Build a fake backend by providing the content of JSON files or JavaScript objects through configurable routes.
  - [cacheable-request](https://github.com/lukechilds/cacheable-request) - Wrap native HTTP requests with RFC compliant cache support.
  - [global-agent](https://github.com/gajus/global-agent) - Global HTTP/HTTPS proxy agent that is configurable using environment variables.
  - [gh-got](https://github.com/sindresorhus/gh-got) - Convenience wrapper for `got` to interact with the GitHub API.
  - [smoke](https://github.com/sinedied/smoke) - File-based HTTP mock server with recording abilities.
  - [flashheart](https://github.com/bbc/flashheart) - REST client.

- HTTP Server
  - [http-server](https://github.com/http-party/http-server) - A simple zero-configuration command-line http server.
  - [anywhere](https://github.com/JacksonTian/anywhere) - Running static file server anywhere.

### Crawler

- [node-crawler](https://github.com/bda-research/node-crawler) - Web Crawler/Spider for NodeJS + server-side jQuery.
- [Headless Chrome Crawler](https://github.com/yujiosaka/headless-chrome-crawler) - Distributed crawler powered by Headless Chrome.

### Job Scheduling

- [node-schedule](https://github.com/node-schedule/node-schedule) - A cron-like and not-cron-like job scheduler for Node.
- [agenda](https://github.com/agenda/agenda) - Lightweight job scheduling for Node.js.
- [node-cron](https://github.com/kelektiv/node-cron) - A tool that allows you to execute something on a schedule.
- [cron-parser](https://github.com/harrisiirak/cron-parser) - Node.js library for parsing crontab instructions.

### AST

- [babel-parser](https://github.com/babel/babel/tree/master/packages/babel-parser) - JavaScript parser.
- [antlr](https://github.com/antlr/antlr4) - ANTLR (ANother Tool for Language Recognition) is a powerful parser generator for reading, processing, executing, or translating structured text or binary files.
- [acorn](https://github.com/acornjs/acorn) - Small, fast, JavaScript-based JavaScript parser.
- [esprima](https://github.com/jquery/esprima) - High performance, standard-compliant ECMAScript parser.
- [astexplorer](https://github.com/fkling/astexplorer) - Web tool to explore the ASTs generated by various parsers.
- [espree](https://github.com/eslint/espree) - Esprima-compatible JavaScript parser.
- [csstree](https://github.com/csstree/csstree) - Tool set for CSS including fast detailed parser, walker, generator and lexer based on W3C specs and browser implementations.
- [es-module-lexer](https://github.com/guybedford/es-module-lexer) - Low-overhead lexer dedicated to ES module parsing for fast analysis.
- [estree-walker](https://github.com/Rich-Harris/estree-walker) - Traverse an ESTree-compliant AST.
- [periscopic](https://github.com/Rich-Harris/periscopic) - Utility for analyzing scopes belonging to an ESTree-compliant AST.

### Design To Code（D2C）
- [psd.js](https://github.com/meltingice/psd.js) - A Photoshop PSD file parser for NodeJS and browsers.

### Sandbox

- [vm2](https://github.com/patriksimek/vm2) - Advanced vm/sandbox for Node.js.
- [sandbox](https://github.com/gf3/sandbox) - A nifty javascript sandbox for node.js.

### Machine learning

- [tfjs](https://github.com/tensorflow/tfjs) - A WebGL accelerated JavaScript library for training and deploying ML models.
- [brain.js](https://github.com/BrainJS/brain.js) - GPU accelerated Neural networks in JavaScript for Browsers and Node.js.
- [pipcook](https://github.com/alibaba/pipcook) - Machine learning platform for Web developers.

### Natural language processing

- [natural](https://github.com/NaturalNode/natural) - Natural language facility.
- [nlp.js](https://github.com/axa-group/nlp.js) - Building bots, with entity extraction, sentiment analysis, automatic language identify, and more.
- [franc](https://github.com/wooorm/franc) - Detect the language of text.
- [sentiment](https://github.com/thisandagain/sentiment) - AFINN-based sentiment analysis for Node.js.
- [retext](https://github.com/wooorm/retext) - An extensible natural language system.
- [leven](https://github.com/sindresorhus/leven) - Measure the difference between two strings using the Levenshtein distance algorithm.
