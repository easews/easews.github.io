---
layout: default
title: Bifragmented file content carving
nav_order: 2
parent: Content Carving
has_children: false
---

# Bifragmented file content carving

## Overview
Pairs should now form groups and for the second task pairs will consider and devise an algorithm to *carve* file content that is **bifragmented** on a file system.

|![image](../resources/bifragmentation.png)|
|:--:|
|Figure 1: File A is an example of a Bifragmented file|

### Materials
* [File A](../fileA)
* [File B](../fileB)
* [File C](../fileC)
* [File D](../fileD)
* [File Signatures](../fileSignatures)

### Task 1: Preparing the file system.
If pairs have completed Task 1.1, then they can skip to Step 4.

1. Divide the files between partners. One of the partners should take File A and C and the other pair should take File B and D. Pairs should use the scissors and follow the cutting guidelines to segment the files into `file blocks`.

2. Pairs should then identify the **FIRST** file block for each file, flip each of them over and write the label `FF D8` on the back. Similarly, partners should then identify the **LAST** file block for each file, flip them over and write the label `FF D9`.

3. Pairs should then take all the remaining file blocks for each file, ensure they are in sequence and flip them over and write their corresponding number on the back, for example: the second file block for each file should be labelled `2`, the third `3` and so and so forth until the penultimate file block for each file.

4. Pairs should then arrange each of the file blocks on a mock file system container as illustrated in **Figure 1**. Pairs should place them in the correct sequence and then flip each over so that the file content is visible.

### Task 2: Devising and executing a file content carving algorithm.
Pairs are now ready to consider and devise an algorithm to carve file content. Pairs should:

1. Exchange their completed mock file system containers with file blocks with the other pair.

2. Pairs should spend no more than **15 minutes** devising an algorithm with their partner to recover the first file, i.e. File A or File C, from the received file system container.

3. After **15 minutes** pairs should exchange their algorithm and file system container with the other pair. Pairs should ensure the file system container is returned the same as they received it.

4. Pairs should spend no more than **5 minutes** slavishly follow the algorithm and recover the files from a file system containers.
