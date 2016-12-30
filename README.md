# \<fs-life-sketch\>

## Intro

Anelement for displaying and editing a person's life sketch.

## Utilization

Example 1:


```html
<fs-life-sketch person-id='L2Q8-R9Q'></fs-life-sketch>
```

## Properties

- `full-person`

  Read only! This does not need to be included on the element as it is implied. It tells the fs-person-data-service to request the full person data.

## Running the app locally

### Install the Polymer-CLI

First, make sure you have the [Polymer CLI](https://www.npmjs.com/package/polymer-cli) installed (`npm i -g polymer-cli`). Run `bower i` to load all of the dependencies. Then run `polymer serve` to serve your application locally.

### Viewing Your Application

```bash
polymer serve
```

### Building Your Application

```bash
polymer build
```

This will create a `build/` folder with `bundled/` and `unbundled/` sub-folders
containing a bundled (Vulcanized) and unbundled builds, both run through HTML,
CSS, and JS optimizers.

You can serve the built versions by giving `polymer serve` a folder to serve
from:

```bash
polymer serve build/bundled
```

### Running Tests

```bash
polymer test
```

Your application is set up to be tested via [web-component-tester](https://github.com/Polymer/web-component-tester). Run `polymer test` to run your application's test suite locally.
