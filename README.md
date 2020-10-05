<p align="center">
<h1 align="center">Tom Select</h1>
</p>

<p align="center">
<a href="https://github.com/orchidjs/tom-select" class="m-1 d-inline-block"><img alt="GitHub forks" src="https://img.shields.io/github/forks/orchidjs/tom-select?label=Github%20forks&style=&color=007ec6"></a>
<a href="https://www.npmjs.com/package/tom-select" class="m-1 d-inline-block"><img alt="npmjs.org" src="https://img.shields.io/npm/v/tom-select.svg?style=&color=007ec6"></a>
<a href="https://travis-ci.org/orchidjs/tom-select" class="m-1 d-inline-block"><img alt="Travis.org" src="https://img.shields.io/travis/orchidjs/tom-select?style="></a>
<a href="https://coveralls.io/github/orchidjs/tom-select" class="m-1 d-inline-block"><img alt="Coveralls Coverage" src="https://img.shields.io/coveralls/github/orchidjs/tom-select?color=4c1&style="></a>
<a href="https://github.com/orchidjs/tom-select/issues" class="m-1 d-inline-block"><img alt="GitHub Issues" src="https://img.shields.io/github/issues/orchidjs/tom-select?style="></a>
<a href="https://automate.browserstack.com/public-build/QXZ2Z2JUaUlSV2REcHRZYzIzQThxemRnNXNQZ0c3Lzh3d01FWE4vSk1oMD0tLVFFTGlUdmxaMWNIL3hCTUJXZk1qanc9PQ==--f7c82c941ca5c14a22f826b97bc02da17c071d5e"><img src='https://automate.browserstack.com/badge.svg?badge_key=QXZ2Z2JUaUlSV2REcHRZYzIzQThxemRnNXNQZ0c3Lzh3d01FWE4vSk1oMD0tLVFFTGlUdmxaMWNIL3hCTUJXZk1qanc9PQ==--f7c82c941ca5c14a22f826b97bc02da17c071d5e'/></a></p>


Tom Select is an extensible and dynamic &lt;select&gt; UI control.
With autocomplete and native-feeling keyboard navigation, it's useful for tagging, contact lists, country selectors, and so on.
Tom Select was forked from [Selectize.js](https://tom-select.js.org/docs/selectize.js/) to provide the same powerful UI and API but with a framework agnostic approach.

### Browser Support

[![Sauce Test Status](https://saucelabs.com/browser-matrix/tom-select.svg)](https://saucelabs.com/u/tom-select) (coming soon)

### Features

- **Smart Option Searching / Ranking**<br>Options are efficiently scored and sorted on-the-fly (using [sifter](https://github.com/brianreavis/sifter.js)). Want to search an item's title *and* description? No problem.
- **Caret between items**<br>Order matters sometimes. Use the <kbd>&larr;</kbd> and <kbd>&rarr;</kbd> arrow keys to move between selected items.</li>
- **Select &amp; delete multiple items at once**<br>Hold down <kbd>option</kbd> on Mac or <kbd>ctrl</kbd> on Windows to select more than one item to delete.
- **Díåcritîçs supported**<br>Great for international environments.
- **Item creation**<br>Allow users to create items on the fly (async saving is supported; the control locks until the callback is fired).
- **Remote data loading**<br>For when you have thousands of options and want them provided by the server as the user types.
- **Clean API &amp; code**<br>Interface with it and make modifications easily. Pull requests welcome!
- **Extensible**<br> [Plugin API](https://tom-select.js.org/docs/plugins/) for developing custom features (uses [microplugin](https://github.com/brianreavis/microplugin.js)).
- **Touch Support**<br> Plays nice with iOS 5+ devices.

## Usage

```html
<input id="tom-select-it" />
<link rel="stylesheet" href="/css/tom-select.default.css">
<script src="/js/tom-select.complete.js"></script>
<script>
var config = {};
tomSelect('#tom-select-it',config);
</script>
```

The available options are [documented here](https://tom-select.js.org/docs).


## Installation and files

All pre-built files needed to use Tom Select can be found in the "dist" folder on [GitHub](https://github.com/orchidjs/tom-select/tree/master/dist) or [jsDelivr](https://www.jsdelivr.com/package/npm/tom-select?path=dist).

<!--and at [cdnjs](https://cdnjs.com/libraries/selectize.js). -->


- [**JavaScript**](https://github.com/orchidjs/tom-select/tree/master/dist/js)
	- [tom-select.complete.js](https://github.com/orchidjs/tom-select/tree/master/dist/js/tom-select.complete.js) — Includes dependencies and plugins
	- [tom-select.js](https://github.com/orchidjs/tom-select/tree/master/dist/js/tom-select.js) — Does not include sifter or microplugin
- **Themes**
	- [CSS](https://github.com/orchidjs/tom-select/tree/master/dist/css) — Compiled themes
	- [SCSS](https://github.com/orchidjs/tom-select/tree/master/dist/scss) — Uncompiled theme sources

## License

Copyright &copy; 2013–2020 [Contributors](https://github.com/orchidjs/tom-select/graphs/contributors)

Licensed under the Apache License, Version 2.0 (the "License"); you may not use this file except in compliance with the License. You may obtain a copy of the License at: http://www.apache.org/licenses/LICENSE-2.0

Unless required by applicable law or agreed to in writing, software distributed under the License is distributed on an "AS IS" BASIS, WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied. See the License for the specific language governing permissions and limitations under the License.
