# Problem
The Java documentation doesn't have methods for opening files. How do I open and read a text file and then either process it a line at a time, or
get a collection of all the lines?

# Solution

use the `Files::lines()` method, which returns a stream of `String`s. Or use `Files.newBufferedReader()`, `Files.newBuffereedWriter()`,
 `Files.newInputStream()`, and `Files.newOutputStream()`. Or constructor a `FileReader` or a `FileInputStream`. Once you have that, construct a 
 `BufferedReader`, and use the older `while ( (line == readLine()) != null)` pattern
 
 
