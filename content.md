In Python, loops can be nested. The level of indentation is syntactically important and signifies which loop a line a code is part of the body of.

```py-cell
for i in range(0, 3):
    for j in range(0, 2):
        print(i * j)
```

In the example above, the line `print(i * j)`{.python} is indented twice to show it is part of the inner loop.
