# Questions

1. What is a stream?
A stream is an ordered sequence of bytes of an arbitrary length.

3. What is the purpose of OutputStream’s flush() method?
4. True or false: OutputStream’s close() method automatically
flushes the output stream.
4. What is the purpose of InputStream’s mark(int) and reset() methods?
5. How would you access a copy of a ByteArrayOutputStream instance’s internal byte array?
6. True or false: FileOutputStream and FileInputStream provide internal buffers to improve the performance of write and read operations.
7. Why would you use PipedOutputStream and PipedInputStream?
8. Define filter stream.
9. What does it mean for two streams to be chained together?
10. How do you improve the performance of a file output stream or a file input stream?
11. How do DataOutputStream and DataInputStream support FileOutputStream and FileInputStream?
12. What is object serialization and deserialization?
13. What three forms of serialization and deserialization does Java
support?
14. What is the purpose of the Serializable interface?
15. What does the serialization mechanism do when it encounters an object whose class doesn’t implement Serializable?
16. Identify the three stated reasons for Java not supporting unlimited serialization.
17. How do you initiate serialization? How do you initiate deserialization?
18. True or false: Class fields are automatically serialized.
19. What is the purpose of the transient reserved word?
20. 20. What does the deserialization mechanism do when it attempts to deserialize an object whose class has changed?
21. How does the deserialization mechanism detect that a serialized object’s class has changed?
22. How can you add an instance field to a class and avoid trouble when deserializing an object that was serialized before the instance field was added? What JDK tool can you use to help with this task?
23. How do you customize the default serialization and deserialization mechanisms without using externalization?
24. How do you tell the serialization and deserialization mechanisms to serialize or deserialize the object’s normal state before serializing or deserializing additional data items?
25. How does externalization differ from default and custom serialization and deserialization?
26. How does a class indicate that it supports externalization?
27. True or false: During externalization, the deserialization mechanism throws InvalidClassException with a “no valid constructor” message when it doesn’t detect a public noargument constructor.
28. What is the difference between PrintStream’s print() and println() methods?
29. What does PrintStream’s noargument void println() method accomplish?
30. How do you redirect the standard input, standard output, and standard error streams?
31. Improve Listing 4-1’s Copy application (performance wise) by using BufferedInputStream and BufferedOutputStream. Copy should read the bytes to be copied from the buffered input stream and write these bytes to the buffered output stream.
32. Create a Java application named Split for splitting a large file into a number of smaller partx files (where x starts at 0 and increments; for example, part0, part1, part2, and so on). Each partx file (except possibly the last partx file, which holds the remaining bytes) will have the same size. This application has the following usage syntax: java Split path. Furthermore, your implementation must use the BufferedInputStream, BufferedOutputStream, File, FileInputStream, and FileOutputStream classes.
