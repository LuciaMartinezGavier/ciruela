# Ciruela

## Overview

Characteristics
+ Imperative
+ Compiled
+ Block Scope
+ Garbage Collector
+ Inmutable strings

Implementation details
+ Toolchain language: Rust | Kotlin
+ LLVM backend

## Syntax

```ciruela
fun function() -> int:
   return 3   

fun ciruela() -> nil: # entry point
    # this is a comment
    # blocks are defined with 4 spaces or tab
    int foo = 1
    
    int var
    var = 4
    var++

    bool condition = True
    if (condition):
       foo = 2
    else if (4 == 5):
        function(foo)
    else:
        return nil

    while (condition):
        # do nothing
        nope
    
    return nil   


```


### Operations and constants
```ciruela
or
and
not
xor
+
-
/
*
%
True
False
nil
==
!=
```

## types
+ int
+ float
+ bool
+ string
+ ...