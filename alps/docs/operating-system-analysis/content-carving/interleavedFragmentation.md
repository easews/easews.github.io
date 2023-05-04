---
layout: default
title: Interleaved file content carving.
nav_order: 2
parent: Content Carving
has_children: false
---

# Interleaved file content carving.

## Overview
For the third task, groups will consider and devise an algorithm to *carve* file content that is interleaved with multiple files.

|![image](../resources/interleaved.png)|
|:--:|
|Figure 1: Contiguous interleaved files|

### Materials
* [File A](../fileA)
* [File B](../fileB)
* [File Signatures](../fileSignatures)

### Task 1: Preparing the file system.

1. Groups should take File A and B. Groups should use the scissors and follow the cutting guidelines to segment the files into `file blocks`.

2. Groups should then identify the **FIRST** file block for each file, flip each of them over and write the label `FF D8 FF` on the back. Similarly, groups should then identify the **LAST** file block for each file, flip them over and write the label `FF D9`.

3. Groups should then take all the remaining file blocks for each file, ensure they are in sequence and flip them over and write their corresponding number on the back, for example: the second file block for each file should be labelled `2`, the third `3` and so and so forth until the penultimate file block for each file.

4. Groups should then arrange each of the file blocks on a mock file system container as illustrated in **Figure 1**. Groups should place them in the correct sequence and then flip each over so that the file content is visible.

### Task 2: Devising and executing a file content carving algorithm.
Groups are now ready to consider and devise an algorithm to carve file content. Groups should:

1. Groups should spend no more than **15 minutes** devising an algorithm to recover each of the files from the prepared file system container. Hint: recognise that in this example each file block can only belong to one file.

2. Groups should produce **ONE** presentation slide that outlines their algorithm and any assumptions the decisions taken.
