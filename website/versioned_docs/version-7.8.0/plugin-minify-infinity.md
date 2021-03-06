---
id: version-7.8.0-babel-plugin-minify-infinity
title: babel-plugin-minify-infinity
sidebar_label: minify-infinity
original_id: babel-plugin-minify-infinity
---

**In**

```javascript
Infinity;
```

**Out**

```javascript
1 / 0;
```

## Installation

```sh
npm install babel-plugin-minify-infinity --save-dev
```

## Usage

### With a configuration file (Recommended)

```json
{
  "plugins": ["minify-infinity"]
}
```

### Via CLI

```sh
babel --plugins minify-infinity script.js
```

### Via Node API

```javascript
require("@babel/core").transform("code", {
  plugins: ["minify-infinity"]
});
```

