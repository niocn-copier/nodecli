# <%= name %>
<% if (features.includes('test')) { %>
![coverage](https://img.shields.io/badge/coverage-98.01%25-green) ![test](https://img.shields.io/badge/passed-tests-blue)
> <%= description %>

## Installation

```shell
$ npm install <%= name %> -D

# or yarn
$ yarn add <%= name %> -D
```

## Getting started

```javascript
const <%= _.camelCase(name) %> = require('<%= name %>')

```

## API


