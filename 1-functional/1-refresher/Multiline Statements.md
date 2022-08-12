## Python Programs

Consists of physical lines of code (that end with a physical newline character)

Logical lines of code (that with a logical NEWLINE token)

### physical newline vs logical newline

Sometimes, physical newlines are ignored in order to combine multiple physical lines into a single logical line of code terminated by a logical NEWLINE token.

This conversion can be **implicit** or **explicit**

*Implicit*

Expressions in:

list literals: []
tuple literals: ()
dictionary literals: {}
set literals: {}
function arguments/parameters

For example:

```python
[1,
2,
3]
```

You can write a list as the above and Python will remove the lines between each object implicitly.

*Explicit*

You can break up statements over multiple lines explicitly by using *\* character. Multi-line statements are not implicitly converted to a single logical line.
```python
if a \
and b \
and c:
```

### Multi-line String Literals

```python
'''This is 
a multi-line string'''
```

- non-visible characters such as newlines, tabs are actually part of the string.

Note: Docstrings are not the same as comments. They're actually compiled into bytecode.