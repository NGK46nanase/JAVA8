# String

## Taking Strings Apart with Substrings or Tokenizing

StringTokenizer or Regular Expression ? 

## Putting Strings Together with StringBuilder

Q: You need to put some `String` pieces (back) together.

A: Use string concatenation: the + operator. The compiler implicitly constructs
a `StringBuilder` for you and uses its `append()` methods (unless all the string parts are known
at compile time). Better yet, construct and use a  `StringBuilder` yourself.

## Processing a String One Character at a Time

Q: You want to process the contents of a string, one character at a time

A: Use a `for` loop and the  `String`'s `charAt()` or `codePointAt()` method. Or use a
`for each` loop and the `String`s `toCharArray` method

## Aligning, Indenting, and Unindenting Strings

Q: You want to align strings to the left, right, or center

A: Do the math yourself, and use `substring` and a `stringBuilder`. For left or right alignment, use `String.format()`
Java 12 introduced a new method `public String indent(int n)` that prepends `n` spaces to the string, which is treated as
a sequence of lines with line separators. This works well in conjunction with the Java 11 `Stream<String> lines()` method.

## Converting Between Unicode Characters and Strings

Q: You want to convert between Unicode characters and `String`s.

A: Use Java `char` or `String` data types to deal with charcters; these intrinsically support Unicode. Print characters as
integers to display their raw value if needed.

## Reversing a String by Word or by Character


# Pattern Matching with Regular Expressions

Q: You wish to reverse a string, a character at a time or a word at a time

A: You can reverse a string by character easily, using a `StringBuilder`. There are several ways to
reverse a string a word at a time. One natural way is to use a `StringTokenizer` and a stack. `stack` is a
class that implements an easy-to-use last-in, first-out stack of object.

## Expanding and Compressing Tabs

Q: You need to convert space characters to tab characters in a file, or vice versa. You might want to
replace spaces with tabs to save space on disk or go the other way to deal with a device or program that
can't handle tabs.

A: 

## Controlling Case

Q: You need to either convert strings to uppercase or lowercase or compare settings without regard for case.

A: The `String` class has a number of methods for dealing with documents in a particular case `toUpperCase()`
and `toLowerCase()` each return a new string that is a copy of the current string but converted, as the name 
implies. Each can be called either with no arguments or with a `Locale` argument specifying the conversion rule.

## Entering Nonprintable Characters

Q: You need to put nonprintable characters into strings

A: Use the backslash character and one of the Java string escapes.

## Trimming Blanks from the End of a String

Q: You need to work on a string without regard for extra leading or trailing spaces a user may have typed

A: use the `String` class `strip()` or `trim()` methods.

## Creating a Message with I18N Resources

Q: You want your program to take sensitivity training so that it can communicate well internationally

A

## Using a Particular Locale

Q: You want to use a locale other than the default in a particular operation

A: Obtain a `Locale` by using a predefined instance or the `Locale` constructor.
Optionally make it globla to your application by using `Local.setDefault(newLocale)`



