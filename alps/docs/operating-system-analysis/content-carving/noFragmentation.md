---
layout: default
title: No fragmentation file content carving.
nav_order: 2
parent: Content Carving
has_children: false
---


# No fragmentation file content carving.
## Overview
Learners are to form pairs and for the first task partners will individually consider and devise an algorithm to *carve* file content from a file system that exhibits **no fragmentation**.

|![image](../resources/noFragmentation.png)|
|:--:|
|Figure 1: Contiguous file content with no fragmentation|

### Materials

* [File A](../fileA)
* [File B](../fileB)
* [File C](../fileC)
* [File D](../fileD)
* [File E](../fileE)
* [File F](../fileF)
* [File Signatures](../fileSignatures)

### Task 1: Preparing the file system.
In advance of devising a solution to carve such a file, pairs should:

1. Divide the files between partner. One partner should take File A, B and C and the other partner should take File D, E and F. Each partner should use the scissors and follow the cutting guidelines to segment the files into `file blocks`.

2. Partners should identify the **FIRST** file block for each file, flip each of them over and write the label `FF D8 FF` on the back. Similarly, partners should then identify the **LAST** file block for each file, flip them over and write the label `FF D9`.

3. Partners should then take all the remaining file blocks for each file, ensure they are in sequence and flip them over and write their corresponding number in the sequence on the back, for example: the second file block for each file should be labelled `2`, the third `3` and so and so forth until the penultimate file block for each file.

4. Partners should then arrange each of the file blocks on a mock file system container as illustrated in **Figure 1**. Partners should place them in the correct sequence and then flip each over so that the file content is visible.

### Task 2: Devising and executing a file content carving algorithm.
Learners are now ready to consider and devise an algorithm to carve file content. Learners should:

1. Learners exchange their completed mock file system containers with file blocks with their partners.

2. Learners should spend no more than **15 minutes** devising an algorithm alone to recover each of the files from the received file system container.

3. After **15 minutes** learners should exchange their algorithm and file system container with partners. Learners should ensure the file system container is returned the same as they received it.

4. Learners should spend no more than **5 minutes** slavishly follow the algorithm and recover the files from the mock file system containers.
