# \<plutonium-breadcrumbs\> [![Published on webcomponents.org](https://img.shields.io/badge/webcomponents.org-published-blue.svg)](https://www.webcomponents.org/element/lordoftheflies/plutonium-breadcrumbs)


A “breadcrumb” (or “breadcrumb trail”) is a type of secondary navigation scheme that reveals the user’s location in a website or Web application. The term comes from the Hansel and Gretel fairy tale in which the two title children drop breadcrumbs to form a trail back to their home. Just like in the tale, breadcrumbs in real-world applications offer users a way to trace the path back to their original landing point.

## Usage

<!--
```
    <plutonium-breadcrumbs id="bc" crumbs='[{ "href": "http://google.com", "label": "Google" }, {"href": "http://google.com", "label": "Google"}, {"href": "http://google.com", "label": "Google"}]'>
    
 <template>
    <link rel="import" href="plutonium-breadcrumbs.html">
    <next-code-block></next-code-block>
  </template>
     
    </plutonium-breadcrumbs>
```
-->
```html
<plutonium-breadcrumbs></plutonium-breadcrumbs>
```

## Install the Polymer-CLI

First, make sure you have the [Polymer CLI](https://www.npmjs.com/package/polymer-cli) installed. Then run `polymer serve` to serve your application locally.

## Viewing Your Application

```
$ polymer serve
```

## Building Your Application

```
$ polymer build
```

This will create a `build/` folder with `bundled/` and `unbundled/` sub-folders
containing a bundled (Vulcanized) and unbundled builds, both run through HTML,
CSS, and JS optimizers.

You can serve the built versions by giving `polymer serve` a folder to serve
from:

```
$ polymer serve build/bundled
```

## Running Tests

```
$ polymer test
```

Your application is already set up to be tested via [web-component-tester](https://github.com/Polymer/web-component-tester). Run `polymer test` to run your application's test suite locally.
