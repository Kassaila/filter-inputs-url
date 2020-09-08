# Filtering data with < input >, < select > & URLSearchParams

Make easy way for filtering data with URLSearchParams & different types of inputs, selects.

## Example

A simple [demo](https://kassaila.github.io/filter-inputs-url/) of usage `filter-inputs-url`

See the code of an example - [HTML](https://github.com/Kassaila/filter-inputs-url/blob/master/docs/index.html), [JS](https://github.com/Kassaila/filter-inputs-url/blob/master/examples/src/js/app.js)

## Overview

### HTML structure

Minimal structure for `filter-inputs-url` initializing:

```
<form data-filter-form="form-example">
  <input value="value-example" data-filter="type-example" type="checkbox">
</form>
```

### Usage

Please import `Filter` from [file](https://github.com/Kassaila/filter-inputs-url/blob/master/dist/filter-inputs-url.js) or [file.min](https://github.com/Kassaila/filter-inputs-url/blob/master/dist/filter-inputs-url.min.js) and initialize:

```
import Filter from 'dist/filter-inputs-url';

const filterExample = new Filter({
  formAttr: 'data-filter-form="form-example"',
  filterAttr: 'data-filter',
});

filterExample.initFilters();
```
