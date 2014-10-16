# WebStorm snippets (live templates) for CoffeeScript

Forked from [https://github.com/swizard/idea-coffee-live-templates](swizard/idea-coffee-live-templates)

## Installation

Copy coffee.xml  to the templates folder in your WebStorm settings

### Mac OS X and WebStorm 9

``` bash
cp coffee.xml ~/Library/Preferences/WebStorm9/templates/
```

## Snippets

### General

| Shortcut | Snippet |
|:--------:|---------|
| `req`    | **require**: `<foo> = require <<foo>>` |
| `cl`     | **Class definition:** `class <ClassName> \n constructor: (<params>) ->` |
| `fun`    | **Function:** `(<params>) ->` |
| `for`    | **Array-Loop:** `for <item> in <array>` |
| `foro`   | **Object-Loop:** `for <key>, <value> of <obj>` |
| `log`    | **console.log:** `console.log "<obj> is #{<obj>}"` |
| `swi`    | **Switch:** `switch <something> \n then` |
| `:`      | **Object-Parameter:** `<parameter>: <value>` |

### Testing

| Shortcut | Snippet |
|:--------:|---------|
| `desc`   | `describe` |
| `it`     | `it "should ..."` |
| `ae`     | `assert.equal` |
| `aem`    | `assert.equal with message` |

### jQuery

| Shortcut | Snippet |
|:--------:|---------|
| `dele`   | `delegate jquery event binding` |

 
