# Page test

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

!!! example "Read anch link"

    === "Unordered List"

        ``` markdown
        * Sed sagittis eleifend rutrum
        * Donec vitae suscipit est
        * Nulla tempor lobortis orci
        ```

    === "Ordered List"

        ``` markdown
        1. Sed sagittis eleifend rutrum
        2. Donec vitae suscipit est
        3. Nulla tempor lobortis orci
        ```

!!! note

    Lorem ipsum dolor sit amet, consectetur adipiscing elit.

<table>
<capital>如何在Markdown里面画这样的表格：</capital>
<tr>
<th>普通表头</th>
<th align="right"><i>斜体表头而且居右</th>
<th colspan=2>表头横向合并单元格</th>
</tr>
<tr>
<th>左边也可以有表头</th>
<td bgcolor=#ffffcc>涂个颜色</td>
<td><mark>高亮文本</mark>但不全高亮</td>
<td><b>有时候加粗</b><i>有时候斜体</i></td>
</tr>
<tr>
<td>表头不一定是一整行或者一整列的</td>
<td rowspan=2>纵向合并单元格要注意<br>下一行少一个单元格<br>字太多必要时我会换行</td>
<td rowspan=2 colspan=2>单元格也可以从两个方向合并</td>
</tr>
<td align="left"> 简单做个居左 </td>
</tr>
</table>
