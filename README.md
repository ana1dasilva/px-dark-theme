# px-dark-theme

## Overview

`Px-dark-theme` is a Predix UI component which is the starting point for theming other Predix UI components. It is based loosely on the concepts outlined [here](https://www.polymer-project.org/1.0/docs/devguide/styling.html#xscope-styling).


## Usage

### Prerequisites
1. node.js
2. npm
3. bower
4. [webcomponents-lite.js polyfill](https://github.com/webcomponents/webcomponentsjs)

Node, npm and bower are necessary to install the component and dependencies. webcomponents.js adds support for web components and custom elements to your application.

### Getting Started

First, install the style module via bower on the command line.

```
bower install px-dark-theme --save
```

Second, import the style module to your application with the following tag in your head.

```
<link rel="import" href="/bower_components/px-dark-theme/px-dark-theme-styles.html"/>
```

Finally, use the style module in your application.

```
<style include="px-dark-theme-styles"></style>
```

Click [here](https://www.polymer-project.org/2.0/docs/devguide/style-shadow-dom#style-modules) to read more about Polymer style modules.

## Local Development

From the component's directory...

```
$ npm install
$ bower install
$ gulp sass
```

From the component's directory, to start a local server run:

```
$ gulp serve
```

The root of that server (e.g. http://localhost:8080/) will automatically open in your default browser with the API documentation page and interactive working examples.

`gulp serve` also runs `gulp watch` concurrently so that when you make a change to your source files and save them, your preview will be updated in any browsers you have opened and turned on in LiveReload.

### GE Coding Style Guide
[GE JS Developer's Guide](https://github.com/GeneralElectric/javascript)

<br />
<hr />

## Known Issues

Please use [Github Issues](https://github.com/PredixDev/px-dark-theme/issues) to submit any bugs you might find.
