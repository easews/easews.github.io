---
layout: default
title: File Carving and Fragmentation activity
nav_order: 2
parent: Content Carving
has_children: false
---

# File Carving and Fragmentation activity

The aim of the activity pack is for individuals to develop an initial awareness of the fundamental theory and concepts surrounding **file or content carving**.  

> File (content) carving is the process of recovering and reconstructing file content directly from block storage without using the filesystem metadata. More generally, data (structure) carving is the process of reconstructing logical objects (such as files and database records) from a bulk data capture (disk/RAM image) without using metadata that describes the location and layout of the artifacts. [CyBOK Forensics Knowledge Area P(19)](https://www.cybok.org/media/downloads/Forensics_v1.0.1.pdf)

## Aims, outcomes and opportunities

### Aims

The aim of the activity pack is for individuals to develop an initial awareness of the fundamental theory and concepts surrounding file or content carving.  

### Intended Learning Outcomes

Intended Learning Outcomes

The expectation is that by the end of this activity, individuals will be able to:

1. demonstrate an awareness of how files are represented conceptually in a filesystem; 

2. devise algorithms for the storage, retrieval, deletion and insertion of file elements; 

3. anticipate the significance of understanding file system utilised by a system in terms of recovery of data for forensic purposes.

### Skills development

The expectation is that this activity will afford the following skills development opportunities:

1. to be completed.

2. to be completed.

## Activity
To be completed

### Materials
* Files (File A, File B, File C)
* File System Containers

### Preparation
Learners are required to form pairs.

### Task 1: No fragmentation file content carving.
Learners should form pairs, but for the first task partners will individually consider and devise an algorithm to *carve* file content from a file system that exhibits no fragmentation.

#### 1.1: Preparing the file system.
In advance of devising a solution to carve such a file, pairs should:

1. A partner should take File A, B and C and the other partner should take File D, E and F. Each partner should use the scissors and follow the cutting guidelines to segment the files into `file blocks`.

2. Partners should then identify the **FIRST** file block for each file, flip each of them over and write the label `FF D8 FF` on the back. Similarly, partners should then identify the **LAST** file block for each file, flip them over and write the label `FF D9`.

3. Partners should then take all the remaining file blocks for each file, ensure they are in sequence and flip them over and write their corresponding number on the back, for example: the second file block for each file should be labelled `2`, the third `3` and so and so forth until the penultimate file block for each file.

4. Partners should then arrange each of the file blocks on the *File System Container* as illustrated in **Figure 1**. Partners should place them in the correct sequence and then flip each over so that the file content is visible.

#### 1.2: Devising and executing a file content carving algorithm.
Learners are now ready to consider and devise an algorithm to carve file content. Learners should:

1. Learners exchange their completed File System Containers with file blocks with their partners.

2. Learners should spend no more than **15 minutes** devising an algorithm alone to recover each of the files from the received File System Container.

3. After **15 minutes** learners should exchange their algorithm and File System Container with partners. Learners should ensure the File System Container is returned the same as they received it.

4. Learners should spend no more than **5 minutes** slavishly follow the algorithm and recover the files from the File System Containers.


### Task 2: Bifragmented file content carving
Pairs should now form groups, but for the second task pairs will consider and devise an algorithm to *carve* file content that is bifragmented on a file system.

#### 2.1: Preparing the file system.
If pairs have completed Task 1.1, then they can skip to Step 4.

1. One of the pairs should take File A and C and the other pair should take File B and D. Pairs should use the scissors and follow the cutting guidelines to segment the files into `file blocks`.

2. Pairs should then identify the **FIRST** file block for each file, flip each of them over and write the label `FF D8` on the back. Similarly, partners should then identify the **LAST** file block for each file, flip them over and write the label `FF D9`.

3. Pairs should then take all the remaining file blocks for each file, ensure they are in sequence and flip them over and write their corresponding number on the back, for example: the second file block for each file should be labelled `2`, the third `3` and so and so forth until the penultimate file block for each file.

4. Pairs should then arrange each of the file blocks on the *File System Container* as illustrated in **Figure 2**. Pairs should place them in the correct sequence and then flip each over so that the file content is visible.

#### 2.2: Devising and executing a file content carving algorithm.
Pairs are now ready to consider and devise an algorithm to carve file content. Pairs should:

1. Pairs exchange their completed File System Containers with file blocks with the other pair.

2. Pairs should spend no more than **15 minutes** devising an algorithm with their partner to recover the first file, i.e. File A or File C, from the received File System Container. Hint: consider and focus presented by irrelevant file content.

3. After **15 minutes** pairs should exchange their algorithm and File System Container with the other pair. Pairs should ensure the File System Container is returned the same as they received it.

4. Pairs should spend no more than **5 minutes** slavishly follow the algorithm and recover the files from the File System Containers.

### Task 3 : Interleaved file content carving.
For the third task, groups will consider and devise an algorithm to *carve* file content that is interleaved with multiple files.

#### 3.1: Preparing the file system.
If groups have completed Task 1.1, then they can skip to Step 4. JPEG and RTF

1. Groups should take File A and B. Groups should use the scissors and follow the cutting guidelines to segment the files into `file blocks`.

2. Groups should then identify the **FIRST** file block for each file, flip each of them over and write the label `FF D8 FF` on the back. Similarly, groups should then identify the **LAST** file block for each file, flip them over and write the label `FF D9`.

3. Groups should then take all the remaining file blocks for each file, ensure they are in sequence and flip them over and write their corresponding number on the back, for example: the second file block for each file should be labelled `2`, the third `3` and so and so forth until the penultimate file block for each file.

4. Groups should then arrange each of the file blocks on the *File System Container* as illustrated in **Figure 3**. Groups should place them in the correct sequence and then flip each over so that the file content is visible.

#### 2.3: Devising and executing a file content carving algorithm.
Groups are now ready to consider and devise an algorithm to carve file content. Groups should:

1. Groups should spend no more than **15 minutes** devising an algorithm to recover each of the files from the prepared File System Container. Hint: recognise that in this example each file block can only belong to one file.

2. Groups should produce a slide that outlines their algorithm and any assumptions the decisions you have made.

### Task 4: Firm stump stump

the aim is for the group to stump others

select four files from the set

produce a realistic system, document and provide rationale

exchange with another group

15 minutes

recover the files

document and write what you think about the scenario

teams present their solition and other groups feedback what they think about

class vote on the best one
