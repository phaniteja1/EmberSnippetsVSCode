# Ember JS (ES6) Snippets for Visual Studio Code
-------------------

[![Version](https://vsmarketplacebadge.apphb.com/version/phanitejakomaravolu.EmberES6Snippets.svg)](https://marketplace.visualstudio.com/items?itemName=phanitejakomaravolu.EmberES6Snippets)
[![Installs](https://vsmarketplacebadge.apphb.com/installs/phanitejakomaravolu.EmberES6Snippets.svg)](https://marketplace.visualstudio.com/items?itemName=phanitejakomaravolu.EmberES6Snippets)
[![Ratings](https://vsmarketplacebadge.apphb.com/rating/phanitejakomaravolu.EmberES6Snippets.svg)](https://marketplace.visualstudio.com/items?itemName=phanitejakomaravolu.EmberES6Snippets)

This extension contains Ember JS (ES6 syntax) and Handlebars snippets for [Vs Code][code] editor.

## Version 2.0.0
Contains Handlebars snippets for EmberJS

## Installation

In order to install an extension you need to launch the Command Pallete (Ctrl + Shift + P or Cmd + Shift + P) and type Extensions.
There you have either the option to show the already installed snippets or install new ones. Search for *EmberJS es6* and install it.

## Supported languages (file extensions)
* JavaScript (.js)

## Javascript(ES6) Snippets for EmberJS

Below is a list of all available javascript snippets and the triggers of each one. The **⇥** means the `TAB` key.
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
| `func→`   | function with no params `functionName() {}` |
| `func1→`  | function with 1 param `functionName(param) {}` |
| `func2→`  | function with 2 params `functionName(param1, param2) {}` |
| `func3→`  | function with 3 params `functionName(param1, param2, param3) {}` |

### Service
| Trigger  | Content |
| -------: | ------- |
| `serv→`  | destruncting a service `serviceName: service('serviceSlug')` |

### Import
| Trigger  | Content |
| -------: | ------- |
| `imp→`  | import a module `import moduleName from 'module';` |

### Super
| Trigger  | Content |
| -------: | ------- |
| `sup→`  | super context `this._super(...arguments);` |

### Computed Property
| Trigger  | Content |
| -------: | ------- |
| `comp→`  | computed property with one property `computedProperty: computed('property', { get() {} })` |

### Component Lifecycle Hooks
| Trigger  | Content |
| -------: | ------- |
| `chook→`  | component generic hook `hookName() { this._super(...arguments); }` |
| `cinit→`  | component init hook `init() { this._super(...arguments); }` |
| `cdra→`   | component didReceiveAttrs hook `didReceiveAttrs() { this._super(...arguments); }` |
| `cdr→`    | component didRender hook `didRender() { this._super(...arguments); }` |
| `cdua→`   | component didUpdateAttrs hook `didUpdateAttrs() { this._super(...arguments); }` |
| `cdie→`   | component didInsertElement hook `didInsertElement() { this._super(...arguments); }` |
| `cwde→`   | component willDestroyElement hook `willDestroyElement() { this._super(...arguments); }` |

### Ember Store Commands
| Trigger  | Content |
| -------: | ------- |
| `sinj→`  | inject store `store: inject.service()` |
| `sfr→`  | store find record `this.get('store).findRecord(model, id)` |
| `spr→`   | store peek record `this.get('store).peekRecord(model, id)` |
| `sfa→`   | store find all `this.get('store).findAll(model)` |
| `spa→`   | store peek all `this.get('store).peekAll(model)` |
| `sqa→`   | store query and then |

## Handlebars Snippets for EmberJS

Below is a list of all available handlebars snippets and the triggers of each one. The **⇥** means the `TAB` key.

| Trigger  | Content |
| -------: | ------- |
| `get→`   | get helper `{{get object "property"}}`|
| `act→`   | action helper `{{action "action-name"}}` |
| `act1→`  | action helper with one param `{{action "action-name" "param"}}` |
| `log→`   | log a message to console `{{log object}}}}` |
| `input→` | input component `{{input value=value}}` |
| `link→`  | link-to helper |
| `if→`    | block if helper |
| `inif→`  | inline if helper |
| `un→`    | block unless helper |
| `inun→`  | inline unless helper |
| `ifel→`  | if else block helper |
| `unel→`  | unless else block helper |
| `ifelif→`| if else-if block helper |
| `each→`  | each loop helper |
| `eachx→` | each loop with index helper |
| `eachin→`| each in loop helper to iterate through properties of a object |
| `eachinel→`| each in loop with else helper |

### Contribute
More snippets or any modifications to the existing ones are welcome!

[code]: https://code.visualstudio.com/
