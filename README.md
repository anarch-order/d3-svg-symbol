
[![Published on webcomponents.org](https://img.shields.io/badge/webcomponents.org-published-blue.svg)](https://www.webcomponents.org/element/anarch-order/d3-svg-symbol)
## \<d3-svg-symbol\>

Basic svg symbol using the [D3.js](https://d3js.org/) framework. Component uses specifically: [d3.symbols](https://github.com/d3/d3/blob/master/API.md#symbols)

## Installation
bower install d3-svg-symbol

## Usage
<!--
```
<custom-element-demo>
  <template>
    <link rel="import" href="d3-svg-symbol.html">
    <next-code-block></next-code-block>
  </template>
</custom-element-demo>
```
-->
```html
<link rel="import" href="../../iron-demo-helpers/demo-pages-shared-styles.html">
<link rel="import" href="../../iron-demo-helpers/demo-snippet.html">
<link rel="import" href="../d3-svg-symbol.html">

<custom-style>
    <style is="custom-style" include="demo-pages-shared-styles">
    </style>
</custom-style>
<d3-svg-symbol symbol="circle" size="100" primary-color="gold" secondary-color="aqua" bounce color-toggle on-click></d3-svg-symbol>
```


## Install the Polymer-CLI

First, make sure you have the [Polymer CLI](https://www.npmjs.com/package/polymer-cli) installed. Then run `polymer serve` to serve your element locally.

## Viewing Your Element

```
$ polymer serve
```

## Running Tests

```
$ polymer test
```

Your application is already set up to be tested via [web-component-tester](https://github.com/Polymer/web-component-tester). Run `polymer test` to run your application's test suite locally.
