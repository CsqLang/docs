# Control Structures

Csq supports most of control structures present in Python.

:warning: Be aware of the indentation, Csq doesn't consider tabs as indents.

## If

The if statement will execute a block of statements only when the condition is true.

```csq
a := 334
b := 334
if a == b:
    print 'equal'
```

The output of the program will be:

```bash
equal
```

## Else

The else statement will execute a block of statements only when the condition is false.

```csq
a := 334
b := 3334
if a == b:
    print 'equal'
else:
    print 'not equal'
```

The output of the program will be:

```bash
not equal
```

## Elif

The elif statement will execute a block of statements only when the condition is false and the condition of the elif statement is true.

```csq
a := 334
b := 3334
if a == b:
    print 'equal'
elif a < b:
    print 'done'
```

The output of the program will be:

```bash
done
```
