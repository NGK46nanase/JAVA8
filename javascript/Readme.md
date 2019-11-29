

The Foo.prototype object by default gets a public, nonenumerable property called '.constructor', and this property
is a reference back to the function that the object is associated with.

modify the prototype for method inheritance and use constructor stealing for properties

Explain 'pseudoclassical inheritance'

|Character | Matchers | Examples |
| ---- | ---- | ----|
| ^ | beginning of input | |
| $ | end of input||
| * |zero or more items||
|? |zero or one time||
|+ |one or more times||
|{n} |exactly n times||
|{n,} |n or more times||
|{n,m} |at least n, at most m times ||
| . | any character except newline||
| [...] |any character within brackets||
| [^ ...] |any character but those within brackets||
| \b | matches on word boundary||
| \B | matchers on nonword boundary||
|\d |digits from 0 to 9||
|\D |any nondigit chararcter||
| \w |matches word chracter||
|\W |any nonword character||
|\n |a line feed||
| \s |a single whitespace character||
| \S |a single character that is not whitespace||
| \t | a tab||
| (x) | capturing paraentheses||

|Flag|Meaning|
|----|----|
|g |matches across an entire string, rather than stopping at first match|
|i |ignores case|
|m |applies begin and end line special characters|
