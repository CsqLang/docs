# Loops

To repeat a piece of code, we use loops. In Csq, there are two types of loops: while and for.

## While

The while loop will execute a block of statements until the condition is true.

```csq
i := 0
while i < 5:
    print i
    i = i + 1
```

## For Loop

Csq supports for loops which is an iterator based loop just like Python.
To use it you can either use existing functions like range or create a list to traverse.

Using range function

```csq
for i in range(10):
 print i 
 print '\n'
```
Output:
```
0.000000
1.000000
2.000000
3.000000
4.000000
5.000000
6.000000
7.000000
8.000000
9.000000
```

Using list

```
a := {1,2,3,4,5,6}
for i in a:
 print i
 print '\n'
```
Output:
```
1.000000
2.000000
3.000000
4.000000
5.000000
6.000000
```
