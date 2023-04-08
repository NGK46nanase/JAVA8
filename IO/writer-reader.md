# Writer

`abstract class Writer`

| Modified abd Type | Method |
| ----------------- |--------|
|Writer             |append(char c)|
|Write              | append(CharSequence csq) |
|Write              | append(CharSequence csq, int start, int end) |
|abstract void      | close() |
|abstract void.     | flush() |
|static Writer.     |nullWriter() |
|void               |write(char\[\] cbuf) |
|abstract void      |write(char\[\] cbuf, int off, int len)        |
|void | write(int c) |
|void | write(String str) |
|void               | write(String str, int off, int len) |

# Reader

`abstract class Reader`

| Modified abd Type | Method |
| ----------------- |--------|
|abstract void            |close()|
|void              | mark(int readAheadLimit) |
|boolean              | markSupported() |
|static Reader      | nullReader() |
|int     | read() |
|int    | read(char\[\] cbuf) |
|abstract int              | read(char\[\] cbuf, int off, int len) |
|int     | read(CharBuffer target)        |
|boolean | ready() |
|void | reset() |
|long             | skip(long n) |
|long     | tramsferTo(Writer out) |
