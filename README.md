# ilib-common

Various utility classes for the ilib packages.

## Installation

```
npm install ilib-common

or

yarn add ilib-common
```

## API Reference

You can see the [generated API reference docs](./docs/ilibCommon.md)
for full details.

## License

Copyright © 2021-2022, JEDLSoft

Licensed under the Apache License, Version 2.0 (the "License");
you may not use this file except in compliance with the License.
You may obtain a copy of the License at

    http://www.apache.org/licenses/LICENSE-2.0

Unless required by applicable law or agreed to in writing, software
distributed under the License is distributed on an "AS IS" BASIS,
WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.

See the License for the specific language governing permissions and
limitations under the License.

## Release Notes

### v1.1.0

* Now ships both the ES6 modules in the src directory and the commonjs code
  (transpiled with babel) in the lib directory. Callers can choose which one
  they would like to use.

### v1.0.3

* updated dependencies
* make sure to target node 10 and older browser when running babel and adding
  polyfills

### v1.0.2

* updated dependencies
* updated docs
* add log4js library support

### v1.0.1

- API documentation updates
- now can test on web browsers easily
- fixed bug in `MathUtils.significant()` where it was calling functions
  using the "MathUtils" namespace instead of local functions
- fixed tests for hash codes to work inside of a webpacked test

### v1.0.0

- initial version
- copied from ilib 14.7.0