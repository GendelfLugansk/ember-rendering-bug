# ember-rendering-bug

This repo demonstrates a bug in ember 3.2 and higher - buttons rendered in `each` loop
break application. 

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
