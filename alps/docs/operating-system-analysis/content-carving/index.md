---
layout: default
title: Content Carving
nav_order: 2
parent: Operating System Analysis
has_children: true
---

# Content Carving Active Lesson Plan

## Overview
The lesson plan considers data acquisition challenges in terms of content carving. The activity plan is for individuals to develop an initial awareness of the fundamental theory and concepts surrounding **file and content carving**. A [overview video](../resources/carving.m4v) outlines the structure of the active lesson plan.

> File (content) carving is the process of recovering and reconstructing file content directly from block storage without using the filesystem metadata. More generally, data (structure) carving is the process of reconstructing logical objects (such as files and database records) from a bulk data capture (disk/RAM image) without using metadata that describes the location and layout of the artifacts. [CyBOK Forensics Knowledge Area P(19)](https://www.cybok.org/media/downloads/Forensics_v1.0.1.pdf)

## Structure
Learners complete **FOUR** blocks of activities that are designed to support them in appreciating the significant challenging in recovering and reconstructing files. Instructors support learners through the following activity blocks:

1. **Data Acquisition in Untrusted and Unknown Environments.** The first block is a brief lecture on the significant concepts of file and content carving, in terms of when the file system can not be trusted, relied upon or is unknown. in the situation when the file system is unknown.

2. **No fragmentation, Bifragmented and Interleaved file content carving.** The second block considers the different arrangements of file blocks on the file system. It is important for investigators to be aware of the arrangement of file blocks on the file system as it informs the approach to recover them.

3. **Multiple Interleaved File Fragementation.** The third block of activities supports learners in considering the challenge of multiple interleaved file fragments in more depth.


4. **Content carving.** The fourth block is used to conclude the active lesson plan and is focused on aligning the outcomes of the activities with material presented in the CyBOK.

### Qualification Level
The active lesson plan can be adjusted to accommodate many of the United Kingdom qualification levels. In its current form the active lesson plan is targeting learners at Levels 6 and 7 on the Regulated Qualifications Framework (RQF) and Credit and Qualifications Framework (CQFW) in England and Wales, Levels 10 and 11 on the Scottish Credit and Qualifications Framework (SCQF) and Levels 6 and 7 on European Qualifications Framework (EQF).

The active lesson plan does not expect nor require an individual to posses significant knowledge in Computing Science, Mathematics or Law.

---
## Data Acquisition in Untrusted and Unknown Environments
The **FIRST** block is a brief lecture on the significant concepts of file and content carving, in terms of when the file system can not be trusted, relied upon or is unknown. in the situation when the file system is unknown.

The session will also cover concepts such as file blocks and fragmentation.

##### Instructions
The lecturer or instructor should:

1. Present their own file and content carving lecture or provide in advance for students to consider.

2. Permit time for questions to address any misconceptions or issues with the material presented.

---
## No fragmentation, Bifragmented and Interleaved file content carving
The **SECOND** block considers the different arrangements of file blocks on the file system. It is important for investigators to be aware of the arrangement of file blocks on the file system as it informs the approach to recover them.

### Block structure
The block is structured as follows:

* **No fragmentation file content carving.** Pairs devise an algorithm to recover contiguous file blocks when there is no file fragmentation.

* **Bifragmented file content carving.** Pairs devise an algorithm to recover contiguous file blocks when some files are stored in two file fragments.

* **Interleaved file content carving.** Groups devise an algorithm to recover contiguous file blocks when some are stored in file fragments that are interleaved.

* **Presentation to class.** Teams will present the solution they have generated to the class.

---

### No fragmentation file content carving
Pairs are to formulate the key steps in devising an algorithm to extract file blocks from a system in the ideal scenario, i.e. a system that exhibits no fragmentation and file blocks are stored contiguously.

#### Instructions
The lecturer or instructor should:

1. Issue the activity sheet that will support and guide learners.

2. Advise learners they are to form pairs and devise an algorithm to recover file blocks from an ideal system.

3. Advise learners that in their pairs, they will individually devise algorithms, exchange solutions and then execute them.

4. As pairs devise algorithms and execute them, wander between them and identifying interesting points being raised in activity.

#### Materials
* [Activity Sheet](noFragmentation)

---

### Bifragmented file content carving
Pairs are to formulate the key steps in devising an algorithm to extract file blocks from a system in a more likely scenario, i.e. a system that exhibits some files that comprise of two file fragments that are stored contiguously.

#### Instructions
The lecturer or instructor should:

1. Issue the activity sheet that will support and guide learners.

2. Advise pairs they have to collectively devise an algorithm to recover file blocks stored contiguously from a system that exhibits files that comprise of two fragments.

3. Advise pairs to exchange their solution with another pair. Pairs should execute the solution they receive from the other pair.

4. As pairs devise algorithms and execute them, wander between them and identifying interesting points being raised in activity.

#### Materials
* [Activity Sheet](bifragmentation)

---

### Interleaved file content carving
Pairs are to self-organise into groups and formulate an algorithm to extract file blocks from a system in a more likely scenario, i.e. a system that exhibits file blocks that are stored contiguously but are interleaved.

#### Instructions
The lecturer or instructor should:

1. Issue the activity sheet that will support and guide learners.

2. Advise pairs to self-organise into groups of no more than **FOUR** members.

3. Advise groups they have to devise an algorithm to recover file blocks from a system that exhibits files that comprise of multiple fragments from multiple files, stored contiguously but interleaved.

3. Advise groups that they have to produce a slide detailing their solution that they will subsequently present to class.

4. Advise groups to exchange their solution with another group. Groups should execute the solution they receive from the other group.

4. As groups devise algorithms and execute them, wander between groups and identifying interesting points being raised in activity.

#### Materials
* [Activity Sheet](interleavedFragmentation)

---
### Presentation to Class
The class will learn about the different approaches devised by groups as well as assumptions they have made to recover file blocks from a system that exhibits files that comprise of multiple fragments that are interleaved.

The class should take notes during the session to support a subsequent activity in identifying emerging themes.

#### Instructions
The lecturer or instructor should:

1. Prepare the presentations collected from teams, produce a running order and advise teams in advance.

2. Advise teams they have **FIVE** minutes to give their presentation. The team will be given a **ONE** minute warning and will be clapped off at the end of their allocated time. Teams should be advised they will not be expected to take questions but may be called upon in subsequent discussions.

3. Advise teams that they all have to speak and to consider how they will pass between members efficiently.

4. Advise teams that presentation slide decks will be made available after the session, but learners should still take notes to support subsequent activities.

5. Use a stopwatch and commence the presentations with teams.

#### Materials
* [Activity Sheet](presentationToClass)
* Stopwatch

---
## Multiple Interleaved File Fragmentation
The **THIRD** block of activities supports learners in considering the challenge of multiple interleaved file fragments in more depth.

### Block structure
The block is structured as follows:

* **Stump Group with Multiple Interleaved File Fragmentation.** Teams are to devise an arrangement of file blocks that will *stump* another group to recover.

* **Presentation to Class.** Teams will present the guidelines they have generated to the class.

* **Identify Emerging Themes**. Teams to consider the common themes in the solutions devised by teams.

---
### Stump Group with Multiple Interleaved File Fragmentation
Learners are to form teams and devise an arrangement of file blocks that will stump another group trying to recover the file fragments.

#### Instructions
The lecturer or instructor should:

1. Issue the activity sheet that will support and guide learners.

2. Advise learners that in groups they have to devise a mock arrangement of file blocks that will effectively *stump* another group. The mock arrangement should be challenging but realistic.

3. Groups will then exchange the mock arrangement with another group.

4. Groups are then to devise a solution to recover the file blocks and document their solution for subsequent presentation to the class.

#### Materials
* [Activity Sheet](presentationToClass)

---
### Presentation to Class
The class will learn about the different algorithms devised by groups to recover multiple files that are fragmented.

The class should take notes during the session to support a subsequent activity in identifying emerging themes.

#### Instructions
The lecturer or instructor should:

1. Prepare the presentations collected from teams, produce a running order and advise teams in advance.

2. Advise teams they have **FIVE** minutes to give their presentation. The team will be given a **ONE** minute warning and will be clapped off at the end of their allocated time. Teams should be advised they will not be expected to take questions but may be called upon in subsequent discussions.

3. Advise teams that they all have to speak and to consider how they will pass between members efficiently.

4. Advise teams that presentation slide decks will be made available after the session, but learners should still take notes to support subsequent activities.

5. Use a stopwatch and commence the presentations with teams.

#### Materials
* [Activity Sheet](presentationToClass)
* Stopwatch

---
### Identify Emerging Themes and Novel aspects in Solutions
Teams will use collective notes, the team solution and the solutions presented from other teams to identify themes and distinct aspects of solutions to the problem.

#### Instructions
The lecturer or instructor should:

1. Advise teams that they are to produce a **ONE** slide presentation that covers at least **THREE** emerging themes that the team has devised from watching the presentations.

2. Advise teams they should also identify at least **ONE** novel aspect or divergence between the different solutions.

3. As teams produce their slides, the lecturer should wander between groups to observe discussion and actions.

4. Collect the presentation slides from teams in preparation of the next activity.

#### Materials
* [Activity Sheet](identifyThemes)

---
### Emerging Themes Discussion
Teams will present the themes they have identified from the previous activity as well as engage in a discussion with the rest of the class.

#### Instructions
The lecturer or instructor should:

1. Use a [random number generator](https://www.google.com/search?q=random+number+generator) to randomly select pairs to present. The lecturer may favour to select pairs on what they have observed as to shape the discussion in a particular direction.

2. Advise teams have **TWO** minutes to present the themes they have identified as well as any divergences.

3. Select **ONE** of the themes or divergences to discuss with the wider class and ask for their comments and thoughts.

4. Continue to ask for teams to present either based on the discussion or what they have observed when teams were producing their slides or using a random number generator.

#### Useful links
* [Random Number Generator](https://www.google.com/search?q=random+number+generator).

---

## File and Content carving
The **FOURTH** block is used to conclude the active lesson plan and is focused on aligning the outcomes of the activities with material presented in the CyBOK.

#### Instructions
The lecturer or instructor should:

1. Present the guidelines in greater depth that are presented and discussed in the CyBOK.

2. Ask the class if they have any questions or do not any aspect of what was covered in the session.

3. Ask learners to complete the Quad Fold Activity.

#### Materials

* [Quad Fold Activity](../../general/quadFold)
