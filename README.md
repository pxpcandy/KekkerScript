﻿# Compiling KekkerScript
* First, run `npm i -g .` to globally install KekkerScript - do not include: examples dir, main.kek, main.kek.js
* After, you can then use `kekkerscript` or `kek`. Default file will be `main.kek` and use strict will be set to `false`
* To change these values, use `kek --set-file [path] --use-strict [true/false]`

# KekkerScript Documentation
v. rw1.0.1

For now, our documentation will be held on
GitHub. We will, later on in the future, migrate to
[ReadTheDocs](https://www.readthedocs.io)

KekkerScript is a transpiler that transpiles to JavaScript.

**File extension is .kek**<br>
`()`: brackets

(examples will be shown)<br>
`set variable -> 12.5`: assign a variable to a value, this is how you set and make new variables<br>
`print: 'hello world'`: print given parameters to console<br>
`while variable <= 12.5`: while a condition is true, loop over body<br>
`<< mainfile >>`: comments, will be transpiled and generated in ast<br>
`true/false`: these are booleans, yes or no values basically<br>
`return: fn()`: return something<br>
`"hello world" or 'hello world'`: string values, strings are text. duh.<br>
`import "export" as "thing" from "module"`: import an export from a module, **these are node modules**<br>
`foo()`: call a function, actually creating functions are being worked on as we speak<br>