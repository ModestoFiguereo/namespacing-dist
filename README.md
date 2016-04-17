# namespacing

Is small tool to make easy implement the namespacing pattern.

## Installation

download `dist/namespacing.min.js` from this repo:
https://github.com/ModestoFiguereo/namespacing-dist

bower:
```sh
bower install --save namespacing
```

npm:
```sh
npm install --save namespacing
```

## Use

You can declare a `namespace` like this:
```js
namespace('app.ajax.http.engine');
```

And you import it like this:
```js
namespace.import('app.ajax.http.engine');
```
