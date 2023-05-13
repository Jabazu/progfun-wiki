---
layout: page
title: Scala Style Guide
---

On this page we will periodically publish feedback specific to individual assignments. For feedback which applies to coding style in general, visit the [Scala Style Guide](?page=ScalaStyleGuide) wiki page.

<!--

to unpack multiple submissions into a subfolder each, you can place all the "output" files in
a folder and use these commands

  i=0;for f in *; do ((i += 1)) && mkdir s$i && unzip "$f" -d s$i; done

open all files in sublime
  
  find . -name Huffman.scala | xargs sb


some regular expressions to detect common issues. example usage (should also work in sublime,
open all files and use cmd-shift-f)

  find . -name Huffman.scala | xargs grep ";"
  find . -name Huffman.scala | xargs grep -l ";" | wc -l


#1 "InstanceOf"
#3 ".{123,}"  |  (".\{123,\}" for grep)
#5 "temp", "tmp", "iter", "loop", "test", "help"
#8 ";"
#9 "print"
#10 "return"
#11 "var"

#4.2: ":::"
#4.3: "tail.head"
#4.5: "case.*[^:]:[^:].*=>"

-->


### Week 4: Types and Pattern Matching (Huffman Coding)

The following table indicates how often each of the issues occurred during this assignment (the [Scala Style Guide](?page=ScalaStyleGuide) describes the first 12 issues).

<!--
    #issue    lukas  heather
    #1         2/23    1/40
    #2         3/23    7/40
    #3        12/23   21/40
    #4         9/23   17/40
    #5         7/23    9/40
    #6         0/23    1/40
    #7         0/23    0/40
    #8         7/23    7/40
    #9         1/23    3/40
    #10        0/23    0/40
    #11        2/23    0/40
    #12        1/23    2/40

    #4.1      11/23   15/40
    #4.2      23/23   40/40
    #4.3      10/23   24/40
    #4.4       5/23    6/40
    #4.5       5/23    6/40
-->

