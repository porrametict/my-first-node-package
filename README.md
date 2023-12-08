# @porrametict/my-node-package

A simple Node.js package for greeting users.

## Installation

```bash
npm install @porrametict/my-node-package
```

## Usage

```js
const myNodePackage = require("@porrametict/my-node-package");

// Use the greet function
console.log(myNodePackage.greet("John"));
```

## API

`greet(name:string): string`
Generates a greeting for the specified name.

- `name` (string): The name to greet.
  Returns a greeting message.

## Example

```js
const myNodePackage = require("@porrametict/my-node-package");

// Use the greet function
console.log(myNodePackage.greet("Alice"));
```
