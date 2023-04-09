=============================================================================
=============================================================================

###Welcome, this is an introductory tutorial codespace for the book titled "Regular Expression Puzzles and AI coding assistants" by Author "David Mertz".
===============================================================================

# INTRODUCTION

This tutorial involves Python programming and ChatGPT to create AI coding asistants to improve upon productivity during development.

Other open source projects which also provide AI coding assistance along with chatGPT or CoPilot:  
+ **Tabnine** (`https://www.tabnine.com/getting-started`)  
+ **K-Explorer** (`https://k-explorer.com/`)  
+ **CodeGeex** (`https://github.com/THUDM/CodeGeeX`)  

===============================================================================

### Chapter 1 - The map and the territory.

A typical AI codign assistant operates on the user prompts which can be anything from a function, to classes, data structures or package modules. This tutorial discusses practically how such assistance can be used to finish mind-numbing tasks which generally are the boilerplates.

#### About Regular Expressions

Regex are pattern matching expressions described through texts. They are helpful in searching patterns, modifying them to create further more functionalities.  
For an instance, the below example show:  

`/[A-Z]+(abc|xyz)*/`  

The actual regular expression is contained between the slashes.  
The concise style of such tools focuses on just the regex better than surrounding it with Python code, such as:  

```
import re  
    pat = re.compile(r"[A-Z]+(abc_xyz)*")
    results = re.match(pat, s)
```

-------------------------------------------------------------------------------

#### Matching text patterns: The basics  

##### Character literals  

* /a/ or /Zebra/
: the simplest pattern matched by regex, the character literal or sequence of literal characters.  
The characters are matched exactly in the order they appear listed.  
Case-sensitive, spaces are included as regex.  

##### Escaped Character literals

 

