---
title: 'Les premier pas en Sed'
description: 'meta description of the page'
---

## From biowasm examples 

https://biowasm.com/cdn/v3/sed/4.8

### Simple find/replace

::Sed
---
text: |
    @read1
    ACGTACGACTAGCAG
    +
    JJJJJJJJJJJJJJJ
    @read2
    ACGATCATACCAGCA
    +
    JJJJJJJJJJJJJJJ
command: "sed s/GACT/----/ data.txt "
---
::

### Convert FASTQ to FASTA

From https://github.com/stephenturner/oneliners#awk--sed-for-bioinformatics

::Sed
---
text: |
    @read1
    ACGTACGACTAGCAG
    +
    JJJJJJJJJJJJJJJ
    @read2
    ACGATCATACCAGCA
    +
    JJJJJJJJJJJJJJJ
command: "sed -n 1~4s/^@/>/p;2~4p data.txt"
---
::