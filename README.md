# ${1:D3 SVG Symbol Web Component}

# \<d3-svg-symbol\>

Basic svg symbol using the [D3.js](https://d3js.org/) framework. Component uses specifically: [d3.symbols](https://github.com/d3/d3/blob/master/API.md#symbols)

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
<d3-svg-symbol size="50" symbol-scale="50"></d3-svg-symbol>
<d3-svg-symbol symbol="circle" size="100" primary-color="gold" secondary-color="aqua" bounce color-toggle on-click></d3-svg-symbol>
<d3-svg-symbol symbol="triangle" size="200" symbol-scale="50" primary-color="orange" secondary-color="green" color-toggle on-mouse-over on-mouse-out transition-duration="1500"></d3-svg-symbol>
<d3-svg-symbol symbol="star" size="100" symbol-scale="30" primary-color="purple" secondary-color="silver" bounce on-click></d3-svg-symbol>
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
