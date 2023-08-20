# Page 2

## Another heading

Some text

### codeblocks

Some `code` goes here

### plain codeblock

A plain codeblock:

```
Some code here
def myfunction()
// some comment
```

#### code for a specific language

some more code with the `py` at the start:

```py title="bubble_sort.py"
import tensorflow as tf
def bubble_sort(items):
    for i in range(len(items)):
        for j in range(len(items) - 1 - i):
            if items[j] > items[j + 1]:
                items[j], items[j + 1] = items[j + 1], items[j]
```

#### code with line numbers

```py linenums="1"
import tensorflow as tf
def bubble_sort(items):
    for i in range(len(items)):
        for j in range(len(items) - 1 - i):
            if items[j] > items[j + 1]:
                items[j], items[j + 1] = items[j + 1], items[j]
```

#### highlighting lines

```py hl_lines="2 3"
import tensorflow as tf
def bubble_sort(items):
    for i in range(len(items)):
        for j in range(len(items) - 1 - i):
            if items[j] > items[j + 1]:
                items[j], items[j + 1] = items[j + 1], items[j]
```
