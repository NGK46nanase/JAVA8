# Cookbook

## Q1:

You want to break a string apart, either by indexing positions or by using fixed token characters ( e.g., break on spaces to get words).

## A1:

For substrings, use the `String` object's `sugstrinf()` method.
For tokenizing, construct a `StringTokenizer` around your string and call its method `hasMoreTokens()` and `nextToken()`.
Or, use regular expressions 
