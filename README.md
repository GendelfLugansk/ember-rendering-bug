# ember-rendering-bug

This repo demonstrates a bug in ember 3.3 - buttons rendered in `each` loop
break application. Following template works fine in 3.2.2.

```handlebars
{{#each buttons as |button|}}
  <button>{{button}}</button>
{{/each}}
```

## Installation

* `git clone <repository-url>` this repository
* `cd ember-rendering-bug`
* `npm install`

## Running / Development

* `ember serve`
* Visit your app at [http://localhost:4200](http://localhost:4200).
* Visit your tests at [http://localhost:4200/tests](http://localhost:4200/tests).
