# ast

## Terminology

### Node
Simple objects.
No methods.
Commonly referred to as "AST nodes"

### Node-path
AST nodes that have additional information included regarding scope. (Provided by `ast-types` )
Includes several methods for changing underlying code.
Commonly referred to as "paths"

### Collections

Zero or more Node-paths returned from a jscodeshift query

## Useful Links

### Getting Familiar with AST's
* https://astexplorer.net/
* https://www.toptal.com/javascript/write-code-to-rewrite-your-code
* https://github.com/jhgg/js-transforms

### Working with AST's

* https://github.com/cpojer/js-codemod
* https://www.npmjs.com/package/jscodeshift-helper

### Advanced Links

* https://github.com/benjamn/ast-types/
## Possibly Useful Links

* https://github.com/elliottsj/jscodeshift-typescript-example
* https://github.com/reactjs/react-codemod

## Tools

### jscodeshift

Project: https://github.com/facebook/jscodeshift

Installation
```
# Globally
npm install -g jscodeshift
```