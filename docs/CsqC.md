# CsqC
CsqC is an api which is the reason behind the execution of Csq code.
### Process
Csq Code => C/C++ Code => Machine code
<br>
During this middle process C/C++ code is generated which consists of functions required to work with memory.

## Allocation of Var
In Csq code
```
a := 1000
print a
```
C/C++ code 
```
allocateVar("a","any",i_val(1000));
print(id("a"));
```
Here as you can see a C function is called to allocate variable. it allocates the required memory and list the variable according to it's nature.
id function access the value of memory referenced by the variable
<br>
To use Csq runtime from C/C++ do
```
#include <Csq/Runtime/memory.h>
#include <Csq/Runtime/core.h>
```
After you have included you are good to go.
