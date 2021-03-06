<!-- Logo -->
<p align="center">
  <img height="128" width="128" src="https://github.com/cerner/browserslist-config-terra/raw/master/terra.png">
</p>

<!-- Name -->
<h1 align="center">
  Terra Browserslist Shared Config
</h1>

[![NPM version](https://badgen.net/npm/v/browserslist-config-terra)](https://www.npmjs.org/package/browserslist-config-terra)
[![License](https://badgen.net/github/license/cerner/browserslist-config-terra)](https://github.com/cerner/browserslist-config-terra/blob/master/LICENSE)
[![Build Status](https://badgen.net/travis/cerner/browserslist-config-terra)](https://travis-ci.com/cerner/browserslist-config-terra)
[![Dependencies status](https://badgen.net/david/dep/cerner/browserslist-config-terra)](https://david-dm.org/cerner/browserslist-config-terra)
[![devDependencies status](https://badgen.net/david/dev/cerner/browserslist-config-terra)](https://david-dm.org/cerner/browserslist-config-terra?type=dev)


This configuration reflects Terra's supported browser policy for their UI library and build tools.

## What is Browserslist?

[Browserslist](https://github.com/ai/browserslist) is a library to share a browsers list between different front-end tools, like Autoprefixer, Eslint, and Stylelint.

* Valid Browserslist query syntax validation [browserl.ist](http://browserl.ist)
* ["Browserslist is a Good Idea"](https://css-tricks.com/browserlist-good-idea/) (blog post by [@chriscoyier](https://github.com/chriscoyier))

## Supported Browsers

| Browser                     | Version |
|-----------------------------|---------|
| Chrome & Chrome for Android | Current |
| Edge                        | Current |
| Firefox                     | Current |
| Internet Explorer           | 10 & 11 |
| Safari & Mobile Safari      | Current |

## Installation

Install the module

```shell
$ npm install browserslist-config-terra --save-dev
```


## Usage

### package.json

```json
{
  "browserslist": [
    "extends browserslist-config-terra"
  ]
}
```

## Versioning

browserslist-config-terra is considered to be stable and will follow [SemVer](http://semver.org/) for versioning.
1. MAJOR versions represent breaking changes.
2. MINOR versions represent added functionality in a backwards-compatible manner.
3. PATCH versions represent backwards-compatible bug fixes.

Consult the component CHANGELOGs, related issues, and PRs for more information.

## Contributing

Please read through our [contributing guidelines](CONTRIBUTING.md). Included are directions for issue reporting and pull requests.

## LICENSE

Copyright 2018 - 2020 Cerner Innovation, Inc.

Licensed under the Apache License, Version 2.0 (the "License"); you may not use this file except in compliance with the License. You may obtain a copy of the License at

&nbsp;&nbsp;&nbsp;&nbsp;http://www.apache.org/licenses/LICENSE-2.0

Unless required by applicable law or agreed to in writing, software distributed under the License is distributed on an "AS IS" BASIS, WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied. See the License for the specific language governing permissions and limitations under the License.
