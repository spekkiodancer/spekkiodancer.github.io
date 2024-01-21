# Day 1: Conducting Research for RuinReader

On my journey to create a pdf reader, I have been researching about regular expressions. My thought process was that I want the end-users to be able to conduct query searches. Since I am using Python, I looked at the Python docs for the *re* module (regular expressions) and the  *HOW TO* section.

Software development has a lot of research involved. Planning is the most important part in development. Yes we can do sloppy code last minute, but some things take time. Sloppy work lead to problems in the future. However, sometimes sloppy work is needed for a quick fix. Research is especially important to the beginner. What separates the beginner from the expert is that the expert has more information stored in their long-term memory; the expert does not need to rely on short-term memory as much as the beginner. To catch up, the beginner must do research. Not only must the novice practice the fundamentals, but they need to accumulate experience that they can retrieve from long-term memory. I strongly recommend reading *The Programmer's Brain by Felienne Hermans*. Without further ado, let me expound on what I learn about regular expressions.

## Regular Expressions: RE Module

While researching regular expressions, I learned a lot about how regular expressions are used in Python. First, the library for the regular expressions for Python is a C extension. The Python interpreter cannot understand C language. Therefore, the code must be compile in order for Python to use the re module. This is done by `re.compile()` which compiles a regular expression patterns. These patterns are special characters that allows for different searches and string patterns. Regular expressions is mainly used to find patterns, matches, and searches for strings:

```Python
import re.compile('ab*') #ab* are special search patterns.
```

`re.compile()` is the most important expressions since you cannot use regex without compiling the re module into Python code.

## Regular Expression Syntax

















