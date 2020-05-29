# Python

## Shebang

[PEP 263](https://www.python.org/dev/peps/pep-0263/) itself mentions the regex it follows:

> To define a source code encoding, a magic comment must be placed into the source files either as first or second line in the file, such as:

```
# coding=<encoding name>
```

> or (using formats recognized by popular editors):

```
#!/usr/bin/python
# -*- coding: <encoding name> -*-
```
>or:

```
#!/usr/bin/python
# vim: set fileencoding=<encoding name> : 
```

>More precisely, the first or second line must match the following regular expression:

```
^[ \t\f]*#.*?coding[:=][ \t]*([-_.a-zA-Z0-9]+)
```

