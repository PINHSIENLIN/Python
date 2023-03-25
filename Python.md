---
title: "Python"
author: "Alvin, Lin"
date: "2023-03-24"
date-format: full
format:
   html:
     code-fold: show
     theme: flatly
     embed-resources: true
toc: true
toc-depth: 3
toc-location: left
execute:
  warning: false 
  eval: false
  keep-md: true
---


::: {.cell}

:::


## Control Flow

::: {.cell}

```{.python .cell-code}
# For Loop
x = int(input("Please Enter a Number:"))
for i in range(x):
  for j in range(x):
    print(str(i+1) + "*" + str(j+1) + "=" + str((i+1)*(j+1)))
```
:::

::: {.cell}

```{.python .cell-code}
# while
x = int(input("Please Enter a Number:"))
i = 1
j = 1
while i <= x:
  while j <=x:
    print(str(i) + "*" + str(j) + "=" + str((i)*(j)))
    j+=1
  i+=1
  j = 1
```
:::
