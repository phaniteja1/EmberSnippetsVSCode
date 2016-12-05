# JavaScript
## VS Code JavaScript (ES6) snippets
-------------------

[![Version](http://vsmarketplacebadge.apphb.com/version/phanitejakomaravolu.EmberES6Snippets.svg)](https://marketplace.visualstudio.com/items?itemName=phanitejakomaravolu.EmberES6Snippets)
[![Installs](http://vsmarketplacebadge.apphb.com/installs/phanitejakomaravolu.EmberES6Snippets.svg)](https://marketplace.visualstudio.com/items?itemName=phanitejakomaravolu.EmberES6Snippets)
[![Ratings](http://vsmarketplacebadge.apphb.com/rating/phanitejakomaravolu.EmberES6Snippets.svg)](https://marketplace.visualstudio.com/items?itemName=phanitejakomaravolu.EmberES6Snippets)

This extension contains Ember JS (ES6 syntax) for [Vs Code][code] editor.

### Coming Soon
Handlebar templates for Ember JS. I am super excited about this update as they've increased my productivity greatly!

## Installation

In order to install an extension you need to launch the Command Pallete (Ctrl + Shift + P or Cmd + Shift + P) and type Extensions.
There you have either the option to show the already installed snippets or install new ones. Search for *EmberJS es6* and install it.

## Supported languages (file extensions)
* JavaScript (.js)

## Snippets

Below is a list of all available snippets and the triggers of each one. The **⇥** means the `TAB` key.
All the snippets are indented as per ESLint

### Console Log Statements
| Trigger  | Content |
| -------: | ------- |
| `clg→`   | console log `console.log(object);`|
| `clg2→`  | console log `console.log('tag', object);` |

### Get and Set
| Trigger  | Content |
| -------: | ------- |
| `tgt→`   | get object `this.get(object)`|
| `tst`    | set object`this.set(object)` |
| `cgt→`   | get object from controller (used in model hooks) `controller.get(object)` |
| `cst→`   | set object on controller (used in model hooks) `controller.set('tag', object)` |
| `tcgt`   | get object from controller `this.controller.get(object)` |
| `tcst→`  | set object on controller `this.controller.set('tag', object)` |

### Functions
| Trigger  | Content |
| -------: | ------- |
| `func`   | function with no params `functionName() {}` |
| `func1`  | function with 1 param `functionName(param) {}` |
| `func2`  | function with 2 params `functionName(param1, param2) {}` |
| `func3`  | function with 3 params `functionName(param1, param2, param3) {}` |

### Service
| Trigger  | Content |
| -------: | ------- |
| `serv→`  | destruncting a service `serviceName: service('serviceSlug')` |

### Service
| Trigger  | Content |
| -------: | ------- |
| `serv→`  | destruncting a service `serviceName: service('serviceSlug'),` |

### Super
| Trigger  | Content |
| -------: | ------- |
| `sup`  | super context `this._super(...arguments);` |

### Import
| Trigger  | Content |
| -------: | ------- |
| `imp`  | computed property watching one property `computedPropertyName: computed('propertyToBeWatched', { get() {} })` |

### Super
| Trigger  | Content |
| -------: | ------- |
| `sup`  | super context `this._super(...arguments);` |

### Component Lifecycle Hooks
| Trigger  | Content |
| -------: | ------- |
| `chook`  | component generic hook `hookName() { this._super(...arguments); }` |
| `cinit`  | component init hook `init() { this._super(...arguments); }` |
| `cdra`   | component didReceiveAttrs hook `didReceiveAttrs() { this._super(...arguments); }` |
| `cdr`    | component didRender hook `didRender() { this._super(...arguments); }` |
| `cdua`   | component didUpdateAttrs hook `didUpdateAttrs() { this._super(...arguments); }` |
| `cdie`   | component didInsertElement hook `didInsertElement() { this._super(...arguments); }` |
| `cwde`   | component willDestroyElement hook `willDestroyElement() { this._super(...arguments); }` |

### Contribute
More snippets or any modifications to the existing ones are welcome!

[code]: https://code.visualstudio.com/
