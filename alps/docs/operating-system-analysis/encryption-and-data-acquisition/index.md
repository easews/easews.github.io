---
layout: default
title: Encryption and Data Acquisition
nav_order: 1
parent: Operating System Analysis
has_children: true
---

# Encryption and Data Acquisition Active Lesson Plan

## Overview
This active lesson plan considers the data acquisition challenges for evidence in terms of encryption. The active lesson plan specifically considers the different **legal** and **technical** approaches to overcome encryption. An [overview video](../resources/encryption.m4v) outlines the structure of the active lesson plan.

The *legal* approach as defined:

> The legal approach relies on compelling the person with knowledge of the relevant encryption keys to surrender them. This is relatively new legal territory and its treatment varies across jurisdictions. In the UK, the Regulation of Investigatory Powers Act 2000 specifies the circumstances under which individuals are legally required to disclose the keys. Disclosure may run counter the legal right against self-incrimination and in some jurisdictions, such as in the United States, it is not yet definitively resolved. [CyBOK Forensics Knowledge Area P(17)](https://www.cybok.org/media/downloads/Forensics_v1.0.1.pdf)

The *technical* approach as defined:

> The technical approach relies on finding algorithmic, implementation, or administrative errors, which allow the data protection to be subverted. Although it is nearly impossible to create a complex IT system that has no bugs, the discovery and exploitation of such deficiencies is becoming increasingly more difficult and resource intensive. [CyBOK Forensics Knowledge Area P(17)](https://www.cybok.org/media/downloads/Forensics_v1.0.1.pdf)

## Structure
Learners complete **FOUR** blocks of activities that are designed to support them in appreciating the significant challenging in overcoming encryption. Using real-world cases staring points, instructors support learners through the following activity blocks:

1. **Overcoming Encryption.** The first block of activities is designed to motivate learners to consider the different routes to overcome encryption for the purposes of digital investigation.

2. **Legal Approaches to overcome Encryption.** The second block of activities is designed to motivate learners to consider the different legal approaches to overcoming encryption used across the world.

3. **Technical Approaches to overcome Encryption.** The third block of activities is designed to motivate learners to consider the different technical approaches to overcoming encryption.

4. **Acquisition.** The fourth block is used to conclude the active lesson plan and is focused on aligning the outcomes of the activities with material presented in the CyBOK.

### Qualification Level
The active lesson plan can be adjusted to accommodate many of the United Kingdom qualification levels. In its current form the active lesson plan is targeting learners at Levels 6 and 7 on the Regulated Qualifications Framework (RQF) and Credit and Qualifications Framework (CQFW) in England and Wales, Levels 10 and 11 on the Scottish Credit and Qualifications Framework (SCQF) and Levels 6 and 7 on European Qualifications Framework (EQF).

The active lesson plan does not expect nor require an individual to posses significant knowledge in Computing Science, Mathematics or Law.

### Case

The basis of the activities in the lesson plan is the In re Boucher case.

Sebastien Boucher crossed the border between Canada and the United States. Boucher was in possession of a laptop that was powered-on when he crossed the border. Inspection of the laptop suggested that Boucher was transporting child exploitation images. The laptop was powered down and Boucher was arrested. The laptop was subsequently powered-on but the contents were encrypted and material could not be decrypted. Unable to inspect the drive there was no way to locate and identify the child exploitation images on the laptop. Boucher was asked to provide the password that would grant access to key to decrypt the drive.

---

## Overcoming Encryption
The **FIRST** block of activities is designed to motivate learners to consider the different routes to overcome encryption for the purposes of digital investigation.

### Block structure
The block is structured as follows:

* **Encryption.** Instructor provides a brief lecture on the significant concepts of encryption.

* **Produce Summary of Case.** Learners to produce a summary of the case that will be used in subsequent activities.

* **Overview of Case.** Lecturer or instructor to provide an overview of the case as to ensure all learners are starting with the same knowledge.

* **Discussion on the routes to overcome Encryption.** Class to have discussion on the potential different routes to overcome encryption.

---

### Encryption
The session begins with a brief lecture on the significant concepts of *encryption*, in terms of the challenges it represents to digital investigations.

Learners will use this material to appreciate the challenges around expert evidence and handling evidence.

#### Instructions
The lecturer or instructor should:

1. Present their own encryption lecture or provide it in advance for students to consider.

2. Permit time for questions to address any misconceptions or issues with the material presented.

---

### Produce Summary of Case Study

The lecturer or instructor should advise learners to produce a summary of the case that will act as the foundation for activities.

Optional: the lecturer or instructor can set this as an entry ticket activity as in they are required to complete in advance of session.

#### Materials
* [Activity Sheet](legal/produceSummary)

---

### Overview of Boucher Case

The lecturer or instructor should provide a brief summary of the *Boucher* case to the class.

The motivation for providing the overview is to:

* address any misconceptions or gaps in understanding that students may have developed when considering the case in advance.

* support those students that have no adequately considered the case in advance as to ensure they can effectively contribute to the activity.

#### Materials

* [Case summary](legal/caseSummary)

---

### Discussion on the routes to overcome Encryption

Learners are going to consider the various possible routes that could be used to overcome encryption for the purposes of digital investigations.

#### Instructions
The lecturer or instructor should:

1. Instruct learners to gather into groups of **FOUR** members and to assign each other a number between the range.

2. Learners are then set the task of considering the different approaches that can be used to overcome encryption for data at rest.

3. State a number and state that for the learner that is assigned that number they will be given a few minutes to consider the problem, write down the answer and pass it to their neighbour.

4. The process should continue until all group members have completed the task and no longer than **20** minutes total, representing a **FIVE** minute block for each student.

5. Chair a discussion and ask learners to provide different possible routes to overcoming encryption for the purposes of digital investigations.

6. Consolidate and advise learners that there are two broad routes, *legal* and *technical*, and these will now be considered in more depth over various activities.

---

## Legal Approaches to overcome Encryption

The **SECOND** block of activities is designed to motivate learners to consider the different legal approaches to overcoming encryption used across the world.

### Block structure
The block is structured as follows:

* **Research Compelled Decryption and Key Disclosure Approaches for Country or Region.** Team members research and teach each other about legal approaches to overcoming encryption across the world.

* **Presentation to Class.** Teams will present thee guidelines they have generated to the class.

* **Identify Emerging Themes in Legal Approaches to Compelled Decryption.** Teams to consider the common themes as well as any divergences between the legal approaches presented by teams.

* **Emerging Themes in Legal Approaches to Compelled Decryption Discussion.** Class to have discussion on the common themes that emerge from the legal approaches presented by teams.

* **Themes in Legal Approaches to Compelled Decryption**. Lecturer provides their own lecture on the similarities between legal approaches used across the world.

---

### Research Compelled Decryption and Key Disclosure Approaches for Country or Region
Learners will teach each other about the legal approaches employed to compelled decryption using the [Jigsaw Active Learning approach](https://www.jigsaw.org).

Teams are to consider the legal approaches for a specific country. Each team member is to consider a specific aspect, consequently they are the *expert* for that particular aspect.
Experts from each team are to meet and discuss their aspect, before returning to their team and teaching them about the aspect. The team as a whole will then devise a presentation.

The team presentation will be given to the rest of the class to support a subsequent activity that afford learners in understanding the similar themes that all such legal approaches exhibit across the world.

#### Instructions
The lecturer or instructor should:

1. Advise learners to self-organise into teams of **FIVE** or **FOUR** members.

2. Issue the activity sheet and explain that teams are required to investigate in detail the legal approaches to compelled decryption for a specific county.

2. Teams are to identify a country they want to investigate and confirm it with the lecturer. If they do not have an agreed country then one should be allocated.

3. Teams should consider the legal approaches from specific perspectives with each member of the team acting as an expert for that perspective and accepted to consider it in more detail and educate the rest of the team on that perspective.

4. Experts should spend time considering the aspect in more detail before meeting with the same experts from other teams, i.e. experts are those considering the same perspective but for a different country.

5. Experts should discuss their perspective, share research and consolidate understanding before returning to their own teams and teaching them on the specific perspective.

6. Advise teams they are required to produce a presentation.

7. Collect presentation from teams.

#### Materials
* [Activity Sheet](legal/activity_01)

---
### Presentation to Class
The class will learn about the different legal approaches used across the world to overcome encryption from specific perspectives.

The class should take notes during the session to support a subsequent activity in identifying emerging themes.

#### Instructions
The lecturer or instructor should:

1. Prepare the presentations collected from teams, produce a running order and advise teams in advance.

2. Advise teams they have FIVE minutes to give their presentation. The team will be given a ONE minute warning and will be clapped off at the end of their allocated time. Teams should be advised they will not be expected to take questions but may be called upon in subsequent discussions.

3. Advise teams that they all have to speak and to consider how they will pass between members efficiently.

4. Advise teams that presentation slide decks will be made available after the session, but learners should still take notes to support subsequent activities.

5. Use a stopwatch and commence the presentations with teams.

#### Materials
* [Activity Sheet](legal/presentationToClass)
* Stopwatch

---
### Identify Emerging Themes in Guidelines
Teams will use their collective notes, their own research and other team presentations to identify themes and divergences in guidelines in legal approaches to compelled decryption.

#### Instructions
The lecturer or instructor should:

1. Advise teams that they are to produce a **ONE** slide presentation that covers at least **THREE** emerging themes that the team has devised from watching the presentations.

2. Advise teams they should also identify at least ONE novel aspect or divergence between the different guidelines to support the admission of expert evidence.

3. As teams produce their slides, the lecturer should wander between groups to observe discussion and actions.

4. Collect the presentation slides from teams in preparation of the next activity.

#### Materials

* [Activity Sheet](legal/identifyThemes)

---

### Emerging Themes in Legal Approaches to Compelled Decryption Discussion

Teams will present the themes they have identified from the previous activity as well as engage in a discussion with the rest of the class.

#### Instructions
The lecturer or instructor should:

1. Use a [random number generator](https://www.google.com/search?q=random+number+generator) to randomly select pairs to present. The lecturer may favour to select pairs on what they have observed as to shape the discussion in a particular direction.

2. Advise teams have **TWO** minutes to present the themes they have identified as well as any divergences.

3. Select **ONE** of the themes or divergences to discuss with the wider class and ask for their comments and thoughts.

4. Continue to ask for teams to present either based on the discussion or what they have observed when teams were producing their slides or using a [random number generator](https://www.google.com/search?q=random+number+generator).

#### Useful links

* [Random Number Generator](https://www.google.com/search?q=random+number+generator)

---
### Themes in Legal Approaches to Compelled Decryption
The lecturer should provide a brief overview of the themes identified in legal approaches to compelled decryption that is informed by the prior activities.

#### Instructions
The lecturer or instructor should:

1. Ensure they cover the perspectives of *self incrimination*, *right to silence*, *key disclosure versus decrypted data*, *deniable encryption*, *time limited decryption* and *torture* as well as any other interesting perspectives that have previously been raised.

2. Provide space for learners to ask questions or to address any misunderstandings.  

---
## Technical Approaches to overcome Encryption

The **THIRD** block of activities is designed to motivate learners to consider the different technical approaches to overcoming encryption.

### Block structure
The block is structured as follows:

* **Identify and Confirm Case.** Learners in advance identify a case and source material where a technical approach has been used to overcome encryption.

* **Research Case.** Learners self-organise into teams and research the case selected in the prior activity.

* **Presentation to Class.** Teams will present thee guidelines they have generated to the class.

* **Categorising technical approaches.** Teams categorise the different technical approaches into different categories.

* **Identify Emerging themes.** Teams consider the common themes as well as any divergences between the technical approaches presented by teams.

* **Emerging Themes in Technical Approaches to Compelled Decryption Discussion.** Class to have discussion on the common themes that emerge from the technical approaches presented by teams.

* **Themes in Technical Approaches to Compelled Decryption.** Lecturer provides their own lecture on the similarities between technical approaches used across the world.

---
### Identify and Confirm Case Study
Learners are to identify a case study in advance of the session where a technical approach has been used to overcome encryption.

Learners are required to produce a summary and at provide least **FIVE** artefacts that can act as source material.

Learners will then form teams and select one of the case studies to consider in more depth.

#### Instructions
The lecturer or instructor should:

1. Advise learners they should self-organise into teams. Learners should share their summaries and artefacts with other team members.

2. Advise teams that through discussion and ranking they should identify a case that they want to consider in more depth and share with the wider class.

3. As teams produce discuss cases, the lecturer should wander between groups to observe discussion.

#### Materials

* [Activity Sheet](technical/identifyCase)

---
### Research Case
Teams are to research the case (selected in prior activity) and produce a presentation that will be given to the class.

The learner responsible for the selected case becomes the leader of the team and they steer the presentation.

#### Instructions
The lecturer or instructor should:

1. Issue the activity sheet to guide and support the teams.

2. Advise teams that the learner responsible for the proposed case is the team leader and that the team should produce a **FIVE** minute presentation of the case.

3. Collect the presentations from the teams, for example using a virtual learning environment (VLE).

#### Materials
* [Activity Sheet](technical/activity_01)

---
### Presentation to Class
The class will learn about the various different cases and technical approaches to overcome encryption from the rest of the class.

The class should take notes during the session to support a subsequent activity in identifying emerging themes.

#### Instructions
The lecturer or instructor should:

1. Prepare the presentations collected from teams, produce a running order and advise teams in advance.

2. Advise teams they have **FIVE** minutes to give their presentation. The team will be given a **ONE** minute warning and will be clapped off at the end of their allocated time. Teams should be advised they will not be expected to take questions but may be called upon in subsequent discussions.

3. Advise teams that they all have to speak and to consider how they will pass between members efficiently.

4. Advise teams that presentation slide decks will be made available after the session, but learners should still take notes to support subsequent activities.

5. Use a stopwatch and commence the presentations with teams.

#### Materials
* [Activity Sheet](technical/presentationToClass)
* Stopwatch

---

### Categorising technical approaches
Teams will use their collective notes, their own research and other presentations from the class to classify each of the case studies in terms of whether they are technical examples of: exploitation of *algorithmic*, *administrative*, *implementation* errors or *some other type* of error.

The lecturer will then use an audience response system, such as [Mentimeter](https://www.mentimeter.com), to collect class wide responses to the categorisation of cases.

The class should be advised that they will receive the slide deck and categorisation after the session.

#### Instructions
The lecturer or instructor should:

1. Issue the activity sheet to the teams to support them in completing the activity.

2. Advise teams to discuss and consider the previously present cases and categorise them in terms of exploitation of *algorithmic*, *administrative*, *implementation* errors or *some other type* of error.

3. As teams discuss the cases, the lecturer should wander between groups to observe discussion and actions.

4. Return to the centre and advise the class that an audience response system will be to collect categorisations.

5. Progress through each case and ask the leader of the presenting case, what category they would place the case *in* and ask them to provide a rationale.

6. Open the discussion up to the class and ask if any team disagrees with the classification and rationale.

7. Continue until all cases have been considered by the class.

8. Open the audience response system and ask each team to enter their categorisation of the cases.

9. Present the result of the categorisation and provide slides to class.

#### Materials
* [Activity Sheet](technical/activity_02)
* [Mentimeter](https://www.mentimeter.com)

---
### Identify Emerging themes
Teams will use their collective notes, their own research and other team presentations to identify themes and divergences in technical approaches to compelled decryption.

#### Instructions
The lecturer or instructor should:

1. Advise teams that they are to produce a **ONE** slide presentation that covers at least **THREE** emerging themes that the team has devised from watching the presentation.

2. Advise teams they should also identify at least **ONE** novel aspect or divergence between the different technical approaches.

3. As teams produce their slides, the lecturer should wander between groups to observe discussion and actions.

4. Collect the presentation slides from teams in preparation of the next activity.

#### Materials
* [Activity Sheet](technical/identifyThemes)

---

### Emerging Themes in Technical Approaches to Compelled Decryption Discussion
Teams will present the themes they have identified from a previous activity as well as engage in a discussion with the rest of the class.

#### Instructions
The lecturer or instructor should:

1. Use a [random number generator](https://www.google.com/search?q=random+number+generator) to randomly select pairs to present. The lecturer may favour to select pairs on what they have observed as to shape the discussion in a particular direction.

2. Advise teams have **TWO** minutes to present the themes they have identified as well as any divergences.

3. Select **ONE** of the themes or divergences to discuss with the wider class and ask for their comments and thoughts.

4. Continue to ask for teams to present either based on the discussion or what they have observed when teams were producing their slides or using a [random number generator](https://www.google.com/search?q=random+number+generator).

#### Useful links
* [Random Number Generator](https://www.google.com/search?q=random+number+generator).

---

### Themes in Technical Approaches to Compelled Decryption
The lecturer should provide a brief overview of the themes identified in technical approaches to compelled decryption that is informed by the prior activities.

#### Instructions
The lecturer or instructor should:

1. Ensure coverage of *oscillating popularity over time of favoured category approach*, *popularity of favoured category approach varies by context* and *platform influences popularity of favoured category approach*.

2. Provide space for learners to ask questions or to address any misunderstandings.

---
## Acquisition
The **FOURTH** block is used to conclude the active lesson plan and is focused on aligning the outcomes of the activities with material presented in the CyBOK.

#### Instructions
The lecturer or instructor should:

1. Present the routes to overcome encryption in greater depth that are presented and discussed in the CyBOK.

2. Ask the class if they have any questions or do not any aspect of what was covered in the session.

3. Ask learners to complete the Quad Fold Activity.

#### Materials
* [Quad Fold Activity](../../general/quadFold)
