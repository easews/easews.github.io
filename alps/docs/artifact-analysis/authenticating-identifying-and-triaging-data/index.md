---
layout: default
title: Authenticating, Identifying and Triaging Data
nav_order: 2
parent: Artifact Analysis
has_children: true
---

# Authenticating, Identifying and Triaging Data Active Lesson Plan
This active lesson plan considers artifact analysis from the perspective of applying hash functions to authenticate evidence and identify contraband as well as how hash functions can be used to filter and triage data as part of an investigation. A [overview video](../resources/artifact.m4v) outlines the structure of the active lesson plan.

> Cryptographic hashing is the first tool of choice when investigating any case; it provides a basic means of validating data integrity and identifying known artifacts. Recall that a hash function takes an arbitrary string of binary data and produces a number, often referred to as a digest, within a predefined range. Ideally, given a set of different inputs, the hash function will map them onto different outputs. [CyBOK Forensics Knowledge Area P(28)](https://www.cybok.org/media/downloads/Forensics_v1.0.1.pdf)

### Structure
Learners complete **FIVE** blocks of activities that are designed to support them in developing understanding and awareness of applying hash functions in forensics. Using a real-world case as a staring point, instructors support learning through the following activity blocks:

1. **Overview of Hash Functions.** The first block of activities supports learners in understanding some of the applications and qualities of hash functions from consideration of actual cases.

2. **Authentication of Evidence.** The second block of activities supports learners in appreciating the use of hash function in terms of authentication of evidence.

3. **Identification of Contraband.** The third block of activities are designed around supporting learners in appreciating how hash functions can be used in forensics to identify contraband.

4. **Same vs Similar.** The fourth block of activities are designed to support learners in appreciating the opportunities and challenges in applying hash functions to support digital investigations.

5. **Hash Functions in Forensics.** The fifth and final block is designed to conclude the active lesson plan and align material with that presented in the CyBOK.

### Qualification Level
The active lesson plan can be adjusted to accommodate many of the United Kingdom qualification levels. In its current form the active lesson plan is targeting learners at Levels 6 and 7 on the Regulated Qualifications Framework (RQF) and Credit and Qualifications Framework (CQFW) in England and Wales, Levels 10 and 11 on the Scottish Credit and Qualifications Framework (SCQF) and Levels 6 and 7 on European Qualifications Framework (EQF).

The active lesson plan does not expect nor require an individual to posses significant knowledge in Computing Science, Mathematics or Law.

---

## Overview of Hash Functions

The **FIRST** block of activities supports learners in understanding some of the applications and qualities of hash functions from consideration of actual cases.

### Block structure
The block is structured as follows:

* **Hash Function.** Instructor provides a brief lecture on the significant concepts of hash functions and how they relate to forensics.

* **Produce Summary of Case and Use of Hash Functions.** Learners are required to produce a summary of a selected case and its use of hash function(s).

* **Presentation to Class.** Teams are to present a summary of their selected case and its use of hash function(s).

* **Identify Application and Qualities of Hash Functions discussed in Cases.** Teams are required to identify common applications and qualities of hash function(s) across the cases presented.

* **Class Collective on Application and Qualities of Hash Functions.** The class collectively discuss and debate the various applications and qualities of hash functions prior to agreeing on a set of applications and qualities.

* **Summary on Applications and Qualities of Hash functions.** The lecturer or instructor provides an overview of the applications and qualities of hash functions as they relate to forensics.

---

### Hash Functions
The session begins with a brief lecture on the significant concepts of hash functions in forensics, in terms of the ability to take an arbitrary- element in the world and compress it to a fixed-length string.

Learners will use this knowledge in the consideration of court cases to begin to consider what the potential applications are for such a function in the world of digital forensics.

#### Instructions
The lecturer or instructor should:

1. Present their own hash function lecture or provide it in advance for students to consider.

2. Permit time for questions to address any misconceptions or issues with the material presented.
---

### Produce Summary of Case and Use of Hash Functions
The lecturer or instructor should advise learners to select a case and produce a summary of the case, in terms of relevance to hash function. The summaries generated by the class will act as the foundation for activities.

Optional: the lecturer or instructor can set this as an *entry ticket activity* as in they are required to complete in advance of session.

#### Materials
* [Activity Sheet](../artifact/produceSummary.html)


### Presentation to Class
The class will learn about the various different cases from the perspective of how hash functions are used as part of court cases.

The class should take notes during the session to support a subsequent activity in identifying emerging themes.

#### Instructions
The lecturer or instructor should:

1. Prepare the presentations collected from teams, produce a running order and advise teams in advance.

2. Advise teams they have **FIVE** minutes to give their presentation. The team will be given a **ONE** minute warning and will be clapped off at the end of their allocated time. Teams should be advised they will not be expected to take questions but may be called upon in subsequent discussions.

3. Advise teams that they all have to speak and to consider how they will pass between members efficiently.

4. Advise teams that presentation slide decks will be made available after the session, but learners should still take notes to support subsequent activities.

5. Use a stopwatch and commence the presentations with teams.

#### Materials
* [Activity Sheet](../artifact/presentationToClass.html)

---
### Identify Application and Qualities of Hash Functions discussed in Cases
Teams will use their collective notes and other team presentations to identify the different applications in terms of how hash functions are used as part of court cases.

#### Instructions
The lecturer or instructor should:

1. Advise teams to identify at least **TWO** common applications of how hash function are used in cases that the team has devised from watching the presentations.

2. As teams discuss, the lecturer or instructor should wander between them to observe discussion and actions.

3. Issue a **ONE** minute warning that teams should finalise their identified applications. Pause the discussion and convene the class after the time has elapsed.

4. Advise teams now they have to identify at least **THREE** desirable qualities that such hash function should exhibit that would underpin the applications they have identified.

5. As teams discuss, the lecturer or instructor should wander between them to observe discussion and actions.

6. Advise teams, they should now spend **FIVE** minutes produce a single presentation slide that briefly captures the applications and qualities.

7. Issue a **ONE** minute warning that teams should finalise their identified presentation slide.

8. As teams discuss, the lecturer or instructor should wander between them to observe discussion and actions.

3. Collect the presentation slides from teams in preparation of the next activity.

#### Materials
* [Activity Sheet](../artifact/identifyThemes.html)

---

### Class Collective on Application and Qualities of Hash Functions
Teams will present the themes they have identified from the previous activity as well as engage in a discussion with the rest of the class.

#### Instructions
The lecturer or instructor should:

1. Use a [random number generator](https://www.google.com/search?q=random+number+generator) to randomly select pairs to present. The lecturer may favour to select pairs on what they have observed as to shape the discussion in a particular direction.

2. Advise teams have **TWO** minutes to present the applications they have identified from the prior presentation as well as desirable qualities.

3. Select **ONE** of the applications OR qualities to discuss with the wider class and ask for their comments and thoughts.

4. Continue to ask for teams to present either based on the discussion or what they have observed when teams were producing their slides or using a [random number generator](https://www.google.com/search?q=random+number+generator). The instructor should osciliate between considering of hash applications and qualities.

#### Useful links
* [Random Number Generator](https://www.google.com/search?q=random+number+generator)

---

### Summary of Applications and Qualities of Hash functions
The lecturer or instructor should provide a brief overview of the themes identified in the prior activities and relate them to the already established material that is presented and discussed in the CyBOK.

#### Instructions
The lecturer or instructor should:

1. Advise learners of some of the application and qualities of hash functions that have emerged from consideration of all the various cases.

2. Relate the applications and qualities of hash functions to those presented and discussed in CyBOK.

3. Provide space for learners to raise any questions or address any gaps in understanding.

#### Useful links
* [CyBOK](https://www.cybok.org)

---

## Authentication of Evidence

The **SECOND** block of activities supports learners in appreciating the use of hash function in terms of authentication of evidence.

### Block structure

The block is structured as follows:

* **Overview of Using Hash Functions for Authentication.** Instructor provides a brief lecture on the use of hash function for the authentication of evidence.

* **Mapping to a Fixed-space.** Learners participate in an activity that afford understanding of how many elements in the world are mapped to a fixed-space for various reason.

* **Limits of Fixed-space.** Learners participate in an activity design to appreciate the limits of a fixed-space and the probability of collisions.

* **Overview of Richard Miller Vs State of Missouri.** Learners consider a legal case that highlights the limits of DNA testing.  

* **Reflecting on the Limits of Fixed-space.** Learners are expected to reflect on previous activities to appreciate the concept of collisions and significance for forensics.

* **Collisions.** The lecturer or instructor provides an overview of the concept of collisions and relates it back to the CyBOK.

---

### Overview of Using Hash Functions for Authentication of Evidence
The session begins with a brief lecture on the significant concepts of using hash functions for authentication of evidence.

Learners will use this material as well as consideration of other traditional evidence in physical crimes to appreciate the use of hash functions for authentication of evidence.

#### Instructions
The lecturer or instructor should:

1. Present their own using hash functions for authentication of evidence lecture or provide it in advance for students to consider.

2. Permit time for questions to address any misconceptions or issues with the material presented.
---
### Mapping to a Fixed-space
The class will learn about the long established concept of discerning one element of evidence from another and how authentication is a central aspect of any court case.

The present block will support learners in making connections between common elements and relating to the present topic.

#### Instructions

The lecturer or instructor should:

1. The lecturer should gather together ***common*** items that employ unique identifies and place them in a bag.

  Examples include:
    - Book (International Standard Book Number)
    - Toy Gun (Firearm serial number)
    - National Insurance Card (NI Number)
    - Currency note (Currency cypher or serial number)
    - Toy Car (Vehicle Identification Number)


2. The lecturer should then advise that they have a bag of goodies that relates to the topic.

3. Assign a number to each learner in the class (e.g. attendance list with number assigned to each student). Use a [random number generator](https://www.google.com/search?q=random+number+generator) to select a learner.

4. Advise the randomly selected learner that they can identify two peers to join them.

5. The randomly selected student is then advised to draw an item from the bag.

6. The trio are then permitted **ONE** minute to huddle and determine how the object relates to the topic.

7. After time has elapsed, advise the trio of learners to tell the class how the item relates to the topic today and to sit down.

8. The instructor should continue until the bag is empty or cease when it has became obvious what the common theme is between the items.

9. The instructor should advise how each item they placed in the bag relates to the topic.

#### Useful links
* [Random Number Generator](https://www.google.com/search?q=random+number+generator)

---

### Limits of Fixed-space
The following activity is designed to focus the attention of learners on the limits of mapping to a fixed-space and concern of collisions.

Learners will use the experience of the activity as a foundation for subsequent activities that are designed to cement the concept of collision-resistance and significance in forensics.

#### Instructions
The lecturer or instructor should:

1. Advise learners to form groups of no less than **FIVE** members and no more than **SIX** members.

2. Advise the self-organised teams to identify a leader.

3. Advise team leaders that they have to assign roles of writer, runner and point manager.

4. Issue each team with a distinct number.

5. Ask the class a trivia question from the collection. Advise teams they have **ONE** minute to determine their answer, write it on the sticky note, write their group number on the back and get it to the front of the room.

6. Use a stopwatch, issue a **10** second warning prior to the time ending. Any team not able to get their stick note on the board before time has elapsed receives **ZERO** points for that question.

7. Advise the class of the answer and then review the answers as well as allocating points.

8. Continue until all questions are complete or the primary lesson (regarding probability of collisions of collisions has been made).

9. Upon completion of activity relate the questions and answer back to the concept of probability of collisions.

10. Tally points, identify winners and allow them, in descending order, to select their prizes.

#### Materials
* [Trivia Questions](../artifact/trivia.html)
* Sticky Notes
* Pens
* Prize(s)

---
### Overview of Richard Miller Vs State of Missouri

The lecturer or instructor at this point should provide a brief summary of the Richard Miller Vs State of Missouri case to the class.

The motivation for providing the overview is:

* relate the activities considered previously to the limits of mapping to a fixed-space as well as significance to forensics.

* address any misconceptions or gaps in understanding that students may have developed so far in the lesson.

#### Materials
* [Case Summary](../artifact/caseSummary.html)

---
### Reflecting on the Limits of Fixed-space
The aim is for learners to consolidate the outcomes of the prior blocks and relate them back to using hash functions to authenticate evidence and primary conceptual concerns in the application of hash functions.

#### Instructions

The lecturer or instructor should:

1. Issue the reflection questions to learners.

2. Advise students that they are expected to answer **TWO** questions and have **FIVE** minute window to do so, and that a **ONE** minute warning will be advised at the end of each window.

3. Ask the learners to anonymously write their answers on a piece of A4 paper.

4. Advise that you want learners that both answers must not exceed a single-side of the A4 page.

5. Advise learners are expected to reflect on the prior activities and consider how they relate to the concept of using hash functions to authenticate evidence.

6. After time has elapsed, advise the learners to discuss their answers with their peers in groups.

7. As the groups discuss, wander between groups and discuss the answers produced by individuals in the group.

8. Convene the class and briefly discuss the questions and the answers you have observed while wandering between groups.

9. Collect the answers generated by learners.

#### Materials
* [Reflection Questions](../artifact/reflection.html)

---

### Collision Resistance

The aim is to familiarise learners with the collision resistant and the significance to hash functions and forensics.

#### Instructions

The lecturer or instructor should:

* Present material around the concept of collisions and hash functions.

* Provide an opportunity for learners to address questions and/or address any misconceptions.

#### Useful links
* [CyBOK](https://www.cybok.org/media/downloads/Forensics_v1.0.1.pdf)

---

## Identification of Contraband
The **THIRD** block of activities are designed around supporting learners in appreciating how hash functions can be used in forensics to identify contraband.

### Block structure
The block is structured as follows:

* **Overview of Using Hash Functions to Search for Contraband.** Instructor provides a brief lecture on the significant concepts on the application of hash function to identify contrabands in corpora.

* **Case Study: Apple Inc Child Sex Abuse Material (CSAM) solution.** Instructor progresses the session with a video to engage in the difficult topic of contraband, searching and identification.

* **Produce Summary of Research Paper.** Learners are required to produce a summary of the research paper being considered in the class.

* **Overview of Research Paper.** Instructor provides an overview of the research paper to the class to ensure every learner is starting from the same point.

* **Class Debate: Digital Dog Sniff.** Structured classroom debate around the concerns of conducting live analysis of main memory or not.

* **Personal Reflection on Digital Dog Sniff Class Debate.** Opportunity for individual learners to reflect on the structured classroom debate.

* **Collective Reflection on the Digital Dog Sniff debate.** Class-wide consideration and reflection of the structured classroom debate.

* **Summary on Using Hash Functions to Search for Contraband.** Conclude the session and motivate learners to consider the evidence collected by the class as whole as well as relate it back to the CyBOK.

---

### Overview of Using Hash Functions to Search for Contraband

The session begins with a brief lecture on the significant concepts of using hash functions to search or identify contraband within corpora.

Learners will use this knowledge to appreciate the upcoming challenges in terms of legal and privacy concerns as part of digital investigations.

#### Instructions
The lecturer or instructor should:

1. Present their own lecture on the use of hash functions to identify contraband or provide it in advance for students to consider.

2. Permit time for questions to address any misconceptions or issues with the material presented.
---

### Case Study: Apple Inc Child Sex Abuse Material (CSAM) solution
The aim is for learners to engage with the topic of identifying contraband in corpora and consider aspects such as appropriate consent and authorisation, searching and identification as well as legal protections from possessing contraband.


#### Instructions
The lecturer or instructor should:

1. Advise learners they are going to watch an interview between a journalist and Apple Inc representative on the deployment of a solution that, in-part, identifies contraband with corpora using hash functions.

2. Advise learners to consider or focus on the approach of the Apple Inc representative to maintain audience focus on the concept of contraband, privacy protection and the difference between searching and identification.

3. Advise learners they have **FIVE** minutes to reflect on the interview and to make some notes in terms of immediate observations both the perspectives of individual users and from wider society in terms of detecting contraband on devices.

4. Collect notes from learners via an appropriate platform, such as a virtual learning environment, or physical notes. Advise students to ensure they have identified themselves on the notes, so that they can be returned.

#### Materials
* [Apple’s Software Chief Explains ‘Misunderstood’ iPhone Child-Protection Features.](https://youtu.be/OQUO1DSwYN0) Wall Street Journal.

---

## Class Debate: Apple Inc Child Sex Abuse Material (CSAM) solution.
The aim is for the present activity to act as practice for a structured classroom debate.

#### Instructions
The lecturer or instructor should:

1. Advise learners that the class is going to debate the merits of the solution proposed by Apple Inc to detect contraband.

2. Issue the practice debate activity sheet.

3. Issue notes previously collected from learners that they generated from reflecting on the prior interview with the Apple representative.

4. Randomly label learners, either A or B, and advise them to self-organise into pairs of A and B.

5. Advise all learners labelled 'A' that they have to advocate the position that such a system should be deployed. Consequently, all learners labelled 'B' are to adopt the position that such a system should not be deployed.

6. Advise the class that pairs they have **30** minutes to prepare their arguments for their position and they will be provided with a **FIVE** warning before time elapses. After time has elapsed pairs will be numbered and selected at random to make their position clear to the class. Each learner will have **FOUR** minutes to make their argument to the class. Their partner will review and provide feedback to their partner before the wider class to do the same.

7. Use a [random number generator](https://www.google.com/search?q=random+number+generator) to randomly select pairs to present. The lecturer may favour to select pairs on what they have observed, rather than randomly, to demonstrate and discuss with the entire class any novel insights or gaps in understanding.

8. Ask the partner of the leaner to provide feedback inline with guidance on the activity sheet.

9. Open the question to the wider class, do not use an audience response system for the activity. Ask the class to raise their hand to offer any feedback to the learner in line with the guidance on the activity sheet.

10. Advise the partner of the learner, it is now their time to provide their position.

11. Repeat process of asking the respective partner to provide feedback and then the class.

12. Identify another pair to perform the debate, continue in this fashion until a sufficient number of perspectives and positions have been considered.

13. Reflect on the debate as a whole with the class. Provide general feedback in terms of the debate that has been so far witnessed.

14. Conclude activity by advising learners the present activity was a practice debate to get feedback and will be helpful for subsequent activities.

#### Materials
* [Practice Debate Activity Sheet](../artifact/practiceDebate.html)
* [Random Number Generator](https://www.google.com/search?q=random+number+generator)

---

### Produce Summary of Research Paper
The lecturer or instructor should advise learners to produce a summary of the research paper that will act as the foundation for activities.

Optional: the lecturer or instructor can set this as an *entry ticket activity* as in they are required to complete in advance of session.

#### Materials
* [Produce Summary of Research Paper Activity Sheet](produceSummaryOfResearchPaper.html)

---

### Overview of Research Paper
The lecturer or instructor at this point should provide a brief summary of the *Fourth Amendment Search and the Power of the Hash* research paper to the class.

The motivation for providing the overview is:

* address any misconceptions or gaps in understanding that students may have developed when considering the case in advance.

* support those students that have no adequately considered the case in advance as to ensure they can effectively contribute to the activity.

#### Materials
* [Research Paper Summary](summaryOfResearchPaper.html)

---

### Class Debate: Digital Dog Sniff
Learners will form teams and participate in a class debate. The aim is to provide an opportunity for learners to develop skills and gain insight into the nuances and legal concerns when applying hash functions in the context of forensics.

#### Instructions
The lecturer or instructor should:

1. Allocate learners to teams or advise them to self-organise into teams of no more than **FOUR** members and no less than **THREE** members. Assign each team a number and issue the [class debate activity task sheet](classDebateActivitySheet.html).

2. Advise teams of the position and inform teams that odd numbered teams should tackle the affirmative position while even numbered teams have to adopt the negative position.

3. After teams have been given sufficient time and space to prepare for the debate use a [random number generator](https://www.google.com/search?q=random+number+generator) to randomly select an odd and even team to present.

4. Advise teams that the broad structure of the debate. Teams will initially present primary arguments, followed by secondary arguments and then rebuttals.

5. Inform the class that they are expected to listen respectfully to the arguments presented by both teams and they should make notes to support subsequent activities.

4. Advise the odd numbered team to take the floor, collect their evidence for their primary arguments and advise them to provide a copy for the opposing team. Inform the presenting team they have **THREE** minutes to present primary arguments and they will receive a **30** second warning when time is about to elapse.

5. Invite the class to clap the team off the flour and then advise the even numbered team to take the floor collect their evidence for their arguments and advise them to provide a copy for the opposing team. Inform the presenting team they have **THREE** minutes to present primary arguments and they will receive a **30** second warning when time is about to elapse.

6. Advise the odd numbered team to retake the floor, collect their evidence for secondary arguments and advise them to provide a copy to the opposing team.
Inform the presenting team they have **THREE** minutes to present secondary arguments and they will receive a **30** second warning when time is about to elapse. Advise the team they may also want to start rebuttal of some of the primary points of the opposing team, but do not tackle the points directly at this stage.

7. Invite the class to clap the team off the flour and then advise the even numbered team to take the floor collect their evidence for their arguments and advise them to provide a copy for the opposing team. Inform the presenting team they have **THREE** minutes to present primary arguments and they will receive a **30** second warning when time is about to elapse. Advise the team they may also want to start rebuttal of some of the primary points of the opposing team, but do not tackle the points directly at this stage.

8. Advise the even numbered team to take the floor for the last time. Advise the team they have **THREE** minutes to respond directly to the points made by the opposing team and present their closing arguments.

9. Invite the class to clap the team off the flour and then advise the odd numbered team to take the floor for the last time. Advise the team they also have **THREE** minutes to respond directly to the points made by the opposing team and present their closing arguments.

10. Thank both teams and repeat the process with different teams for a few more cycles until the central learning outcomes have been achieved.

11. Invite the class to clap and thank the presenters one more time. Advise the class they have **TEN** minutes to consolidate any ideas and notes from the session as such notes will support subsequent activities.

12. Collect all the evidence and summaries from the remaining teams that did not present in the session. The material will be made available to the class as a whole for subsequent activities.

#### Materials
* [Class Debate Activity Sheet](classDebateActivitySheet.html)
* [Random Number Generator](https://www.google.com/search?q=random+number+generator)

---

### Personal Reflection on Digital Dog Sniff
Learners are given the opportunity to reflect on the class debate as to reflect on the skills develop but also to mitigate against the *free-rider* problem.

#### Instructions
The lecturer or instructor should:

1. Advise learners they are going to reflect on the activities they have completed so far in the lesson plan and are expected to submit an individual essay of no more than **1500** words.

2. The individual essay should reflect their own position on the topic tackled in prior sessions. Individuals are expected to drawn on the experience of the debates as well as the evidence they collected as part of a team, the evidence collected by their team as a whole as well as the evidence collected by other teams.

3. Advise learners that all the evidence collected from teams will be available via the virtual learning environment or appropriate service. Advise learners they should exhibit independent and critical thought by contrasting the evidence provided by others with the evidence they sourced.

4. Advise learners submission instructions and process are detailed in the [debate reflection specification](debateReflection.html).   

#### Materials
* [Debate Reflection Specification](debateReflectionSpecification.html)

---

### Collective Reflection on the Digital Dog Sniff debate
Learners are exposed to different perspectives and opinions in terms of the material presented, evidence sourced as well as remarks made by peers. The expectation is the opportunities the activity presents will further develop learner skills as well as widen understanding of the problem.

#### Instructions
The lecturer or instructor should:

1. Summarises the central arguments presented during the debate as well as present some of the evidence submitted by the cohort.

2. Critique the evidence supplied by teams in terms of relevance, source, and overall quality.

3. Expose and emphasise the different remarks made by teams during the debate session.

4. Provide space as well as opportunity for learners to present their own questions or opinions and remarks.

5. Provide an opportunity for learners to ask any remaining questions or concerns regarding the debate itself.

---

### Summary on Using Hash Functions to Search for Contraband
The aim is to conclude the session and motivate learners to consider the evidence collected by the class as whole as well as relate it back to the [CyBOK](https://www.cybok.org/media/downloads/Forensics_v1.0.1.pdf).

#### Instructions
The lecturer or instructor should:

1. Briefly present again their own lecture on the use of hash functions to identify contraband or provide it in advance for students to consider.

2. Relate the presented material to the arguments, remarks and evidence provided by learners during the class debate.

3. Provide an opportunity for learners to address questions and/or address any misconceptions.

#### Useful links
* [CyBOK](https://www.cybok.org/media/downloads/Forensics_v1.0.1.pdf)

---

## Same vs Similar
The **FOURTH** block of activities are designed to support learners in appreciating the opportunities and challenges in applying hash functions to support digital investigations.

### Block structure
The block is structured as follows:

* **Avalanche Effect.** Instructor provides a brief lecture on the concept of the avalanche effect and its relevance to the use of hash functions in digital forensics.

* **Block v File Analysis.** Learners consider the application of hash functions to identify fragments of files as well as complete files.

* **Produce Summary of Case.** Learners produce a summary of two cases that will act as the basis for subsequent activities.

* **Overview of Case.** Lecturer or instructor to provide an overview of the cases as to ensure all learners are starting with the same knowledge.

* **Approximate Matching.** Learners then consider the concept of using hash functions to identify potentially similar files.

* **Resemblance and Containment.** Learners consider the significant concepts of resemblance and containment as it relates to approximate matching.

* **Tailoring to the Task.** Teams then tailor matching solutions to the given task.

---

### Avalanche Effect
Instructor provides a brief lecture on the concept of the avalanche effect and its relevance to the use of hash functions in digital forensics.

Learners will use this material to appreciate the limitations of hash function regards considering a single file or exact match.

#### Instructions
The lecturer or instructor should:

1. Present their own admissibility lecture or provide in advance for students to consider.

2. Permit time for questions to address any misconceptions or issues with the material presented.

### Produce Summary of Case
The lecturer or instructor should advise learners to produce a summary of the case that will act as the foundation for activities.

Optional: the lecturer or instructor can set this as an entry ticket activity as in they are required to complete in advance of session.

#### Materials
* [Activity Sheet](../artifact/produceSummary2.html)

---
### File and Block Analysis
Pairs are going to manually execute a process to confirm if a file exists within a corpus. Pairs will then manually execute a process to determine if any *very similar* files exist in the corpus.

#### Instructions
The lecturer or instructor should:

1. Advise learners they are to self-organise into pairs.

2. Issue the [File Analysis Activity Sheet](../artifact/fileAnalysisActivitySheet.html) that will support and guide learners.

3. Advise pairs they have **TEN** minutes to manually step through the first algorithm and determine if the given file exists. Issue a **ONE** minute warning when time has nearly elapsed.

4. As pairs execute the process and execute them, wander between them and identifying interesting points being raised in activity.

5. Open an audience response system activity, such as [Mentimeter](https://www.mentimeter.com), ask pairs to vote whether the file exists in the corpus or not.

6. The class poll is expected to confirm the file is not in corpus as strictly speaking the final is not present. The expectation is that some pairs will state the file is present as a very similar file is present in the corpus.

7. Ask the class if any of the pairs did identify the file or believe it is in the corpus. If not pair engages then initiate a discussion to tease out comments from the audience regarding the fact that a very similar file exists but the exact file.

8. Issue the [Block Analysis Activity Sheet](../artifact/blockAnalysisActivitySheet.html) that will support and guide learners.

9. Advise pairs they have **30** minutes to manually step through the first algorithm and determine if the given file exists. Issue a **FIVE** minute warning when time has nearly elapsed.  

10. As pairs devise algorithms and execute them, wander between them and identifying interesting points being raised in activity.

11. Open an audience response system activity, such as [Mentimeter](https://www.mentimeter.com), ask pairs to vote whether the file exists in the corpus or not.

12. Advise learners they have **FIVE** minutes to reflect on the activity, relate back to prior activity and make notes. Suggest to learners they reflect on the significance of the *avalanche effect* and the impact it has in terms of file and block analysis.

13. Permit time for questions to address any misconceptions or issues with the material presented.

#### Materials
* [File Analysis Activity Sheet](../artifact/fileAnalysisActivitySheet.html)
* [Block Analysis Activity Sheet](../artifact/blockAnalysisActivitySheet.html)
* [Mentimeter](https://www.mentimeter.com)

---
### Overview of Case
The lecturer or instructor should provide a brief summary of the
*Temple Island Collections Limited and (1) New English Teas Limited (2) Nicholas John Houghton* case to the class.

The motivation for providing the overview is to:

* address any misconceptions or gaps in understanding that students may have developed when considering the case in advance.

* support those students that have no adequately considered the case in advance as to ensure they can effectively contribute to the activity.

#### Materials
* [Case Summary](../artifact/caseSummary2.html)


---
### Devise Approximate Matching Algorithm
Learners will form firms recruited by the case prosecutor. Firms have been tasked with devising and communicating an algorithm that will confirm that a given image is approximately similar to the one in the question.

The expectation the activity will scaffold learners to gain insight into the different types of approximate matching.

#### Instructions
The lecturer or instructor should:

1. Issue the activity sheet that will support and guide learners.

2. Advise learners to self-organise into groups of no more than **FOUR** members.

3. Advise teams they have to devise an algorithm to demonstrates that the images in question are approximately very similar.

4. Advise teams that they have to produce a slide detailing their solution that they will subsequently present to class.

5. Advise teams to exchange their solution with another group. Groups should execute the solution they receive from the other group.

6. As groups devise algorithms and execute them, wander between groups and identifying interesting points being raised in activity.


---
### Presentation to Class
The class will learn about the different algorithms devised by groups to demonstrate that the images in question are approximately similar.

The class should take notes during the session to support a subsequent activity in identifying emerging themes.

#### Instructions
The lecturer or instructor should:

1. Prepare the presentations collected from teams, produce a running order and advise teams in advance.

2. Advise teams they have **FIVE** minutes to give their presentation. The team will be given a **ONE** minute warning and will be clapped off at the end of their allocated time. Teams should be advised they will not be expected to take questions but may be called upon in subsequent discussions.

3. Advise teams that they all have to speak and to consider how they will pass between members efficiently.

4. Advise teams that presentation slide decks will be made available after the session, but learners should still take notes to support subsequent activities.

5. Use a stopwatch and commence the presentations with teams.

#### Materials
* [Activity Sheet](../artifact/presentationToClass0.html)
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
* [Activity Sheet](../artifact/identifyThemes0.html)

### Emerging Themes Discussion
Teams will present the themes they have identified from the previous activity as well as engage in a discussion with the rest of the class.

#### Instructions
The lecturer or instructor should:

1. Use a [random number generator](https://www.google.com/search?q=random+number+generator) to randomly select pairs to present. The lecturer may favour to select pairs on what they have observed as to shape the discussion in a particular direction.

2. Advise teams have **TWO** minutes to present the themes they have identified as well as any divergences.

3. Select **ONE** of the themes or divergences to discuss with the wider class and ask for their comments and thoughts.

4. Continue to ask for teams to present either based on the discussion or what they have observed when teams were producing their slides or using a random number generator.

5. Shape discussion around the concepts of *resemblance* and *containment* as well as how different similarity classification approaches can be broadly categorised as *bytewise*, *syntactic* and *semantic*.

6. Open an audience response system activity, such as [Mentimeter](https://www.mentimeter.com). For each presented solution ask teams to vote whether the solution can be categorised as an of *bytewise*, *syntactic* and *semantic* matching or something else.

7. Review results of class and discuss results with the cohort. Advise learners to spend **FIVE** minutes reflecting on the activities and to make notes.

8. Permit time for questions to address any misconceptions or issues with the material presented.

#### Materials
* [Random Number Generator](https://www.google.com/search?q=random+number+generator).


---
### Tailoring to the Task
The block should conclude by relating the outcomes from the prior activities to material in the [CyBOK](https://www.cybok.org). Specifically, the lecturer or instructor should cover the significant concepts of *resemblance* and *containment* as well as how different approximate matching algorithms can be classed.

#### Instructions
The lecturer or instructor should:

1. Present their own lecture on the importance of guidelines or provide material in advance for learners to consider.

2. Relate the material presented back to the forensic sources interesting to forensics investigators documented in the [CyBOK](https://www.cybok.org).

3. Consolidate themes from the prior activities and frame in the context of *resemblance* and *containment*. Highlight classification of approaches based on *bytewise*, *syntactic* and *semantic* and how all these factors have to be considered and tailored to the specific investigation and/or context.

3. Permit time for questions to address any misconceptions or issues with the material presented.

---

## Hash Functions in Forensics
The **FIFTH** block is designed to conclude the active lesson plan and align material with that presented in the [CyBOK](https://www.cybok.org/media/downloads/Forensics_v1.0.1.pdf).

#### Instructions
The lecturer or instructor should:

1. Present the guidelines in greater depth that are presented and discussed in the [CyBOK](https://www.cybok.org/media/downloads/Forensics_v1.0.1.pdf).

2. Ask the class if they have any questions or do not any aspect of what was covered in the session.

3. Ask learners to complete the Quad Fold Activity.

#### Materials

* [Quad Fold Activity](../general/quadFold.html)
* [CyBOK](https://www.cybok.org/media/downloads/Forensics_v1.0.1.pdf)
