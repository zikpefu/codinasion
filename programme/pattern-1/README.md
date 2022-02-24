## Write a program to print the given pattern

```
* * * * *
  * * * *
    * * *
      * *
        *
```

---

<CodeBlock slots="heading, code" repeat="1" languages="Python" />

#### Python

```python
# print pattern function
def printPattern(n):
    for i in reversed(range(1,n+1)):
        print((i*" *").rjust(2*n))

# test
printPattern(5)
```