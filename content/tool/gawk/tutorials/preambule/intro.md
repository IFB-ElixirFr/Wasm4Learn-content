---
title: 'Les premier pas en gawk'
description: 'meta description of the page'
---

## From biowasm examples 

https://biowasm.com/cdn/v3/gawk/5.1.0

### Example 1

Retrieve 2nd column (note that we use an array of inputs to properly escape the arguments)

::Awk
---
text: |
    column1	column2	column3
    1	2	3
    4	5	6
    7	8	9
command: |
   gawk 'BEGIN{sum = 0; }{ print $2; sum += $2; } END { print("Total of column 2 = " sum) }' data.txt
---
