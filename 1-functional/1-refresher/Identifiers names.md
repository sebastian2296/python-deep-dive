## Rules when creeating identifier names

Identifiers are case sensitive.

Rules:

1. Start with *_* or **a-z** **A-Z**. Followed by any number of underscores (*_*),letters (**a-z** **A-Z**), or digits (0-9).

* There specific naming conventions with specific meaning attached to them, for example `_var` `__var` `__lt__`

* Cannot use reserved words

2. Conventions

`_my_var`: This is a convention to indicate "internal use" or "private" objects. *Objects named this way will not get imported by a statement such as:* from module import * (there're still other ways of import them)

`__my_var`: Use to "mangle" class attributes-useful in inheritance chains.

`__my_var__`: Used for system-defined names that have a special meaning to the interpreter.

*Other naming conventions*

**Packages**: short names, all-lowercase names. Preferably no underscores.

**Modules**: short, all-lowercase names. Can have underscores.

**Classes**: CamelCase
 
**Functions**: snake_case

**Variables**: snale_case

**Constants**: all-uppercase, words separated by underscores.

