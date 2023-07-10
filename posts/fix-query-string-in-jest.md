---
title: How to make the query-string package work in Jest
description: Make the query-string package work with Jest
date: 2023-07-10
tags:
  - Jest
layout: layouts/post.njk
---

Since the query-string package only supports ESM (ECMAScript Modules), it may not work correctly with Jest. This can result in an error message like `SyntaxError: Cannot use import statement outside a module` when running tests.

Add the following code to the `jest.config.js` file to fix this issue.

```js
 "transformIgnorePatterns": [
    "node_modules/(?!(decode-uri-component|filter-obj|split-on-first|query-string)/)"
  ],
```
