# <%= name %>
<% if (features.includes('test')) { %>
[![Build Status][actions-img]][actions-url]
[![Coverage Status][codecov-img]][codecov-url]<% } %>
[![License][license-img]][license-url]
[![NPM Downloads][downloads-img]][downloads-url]
[![NPM Version][version-img]][version-url]
[![Dependency Status][dependency-img]][dependency-url]
[![devDependency Status][devdependency-img]][devdependency-url]
[![Code Style][style-img]][style-url]

> <%= description %>

## Installation

```shell
$ npm install <%= name %>

# or yarn
$ yarn add <%= name %>
```

## Usage

```javascript
const <%= _.camelCase(name) %> = require('<%= name %>')
const result = <%= _.camelCase(name) %>('w')
```

## API


