# Variables

CSQ is dynamically typed so you don't need to specify the type of a variable. It will be determined automatically.

```csq
a := 10
print a
```

The output of the program will be:

```bash
10
```

CSQ also supports variable reassignment.

```csq
a := 10
a = 20
print a
```

The output of the program will be:

```bash
20
```

CSQ supports list (contiguous memory allocation)
As CSQ is dynamically typed so the elements can be of any type.
```csq
a := {1,'Hi'}
print a[0]
print a[1]
```
Output
```
1
Hi
```
