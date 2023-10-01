# Importing Modules
In Csq we have two statement to import existing code import and cimport.
# Import
It's used to import csq modules with extension .csq
```
import <path>
```

module.csq
```
def fizz();
 print 'Buzz Buzz'
```

main.csq
```
import module
fizz()
```
# CImport
It's used to import existing C/C++ code which can be used directly from csq source.
```
cimport <path>
```

module.cpp
```
#include <Csq/memory.h>
#include <Csq/core.h>

auto fizz=[&](){
    printf("Buzz Buzz");
};
```

main.csq
```
cimport module
fizz()
```
When we use cimport in our code then it directly copy and paste code into the converted C++ code due to which we are able to use it without any #include.
