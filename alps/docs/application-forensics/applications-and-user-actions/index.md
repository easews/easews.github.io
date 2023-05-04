---
layout: default
title: Applications and User Actions
nav_order: 1
parent: Application Forensics
has_children: true
---

# Applications and User Actions Lesson Plan
The lesson plan considers the significance of applications as valuable sources of user interactions that can act as valuable and powerful evidence within the legal process. The active lesson plan scaffolds leaners in developing understanding and awareness around the **value of applications** in terms of **user interactions** and this is relevant to Forensics. A [overview video](../resources/application.m4v) outlines the structure of the active lesson plan.

> Application forensics is the process of establishing a data-centric theory of operation for a specific application. The goal of the analysis is to objectively establish causal dependencies between data input and output, as a function of the user interactions with the application. Depending on whether an application is an open or closed source and on the level of the accompanying documentation, the analytical effort required can vary from reading detailed specifications to reverse engineering code, data structures and communication protocols, to performing time-consuming black box differential analysis experiments. Alternatively, forensic tool vendors may license code from the application vendor to gain access to the proprietary data structures. The big advantage of analysing applications is that we have a better chance of observing and documenting direct evidence of user actions, which is of primary importance to the legal process.
[CyBOK Forensic Knowledge Area. Pg 23.](https://www.cybok.org/media/downloads/Forensics_v1.0.1.pdf)

## Structure
Learners complete **FOUR** blocks of activities that are designed to support them in appreciating the significance of applications in terms of repositories of user interactions. Using real-world applications and a relevant case, instructors support learners through the following activity blocks:

1. **Application Forensics.** The first block of activities supports learners in appreciating the benefit and risks to application forensics.

2. **Case Study: Web Browser.** The second block of activities supports learners in the valuable information that can be learned from a popular application with individuals.

3. **Study of Web Search History.** The third and block of activities will afford learners the opportunity to apply knowledge from prior activities and relate to a relevant case.

4. **Application Usage as Evidence.** The fourth and final block is used to conclude the active lesson plan and is focused on aligning the outcomes of the activities with material presented in the CyBOK.

### Qualification Level
The active lesson plan can be adjusted to accommodate many of the United Kingdom qualification levels. In its current form the active lesson plan is targeting learners at Levels 6 and 7 on the Regulated Qualifications Framework (RQF) and Credit and Qualifications Framework (CQFW) in England and Wales, Levels 10 and 11 on the Scottish Credit and Qualifications Framework (SCQF) and Levels 6 and 7 on European Qualifications Framework (EQF).

The active lesson plan does not expect nor require an individual to posses significant knowledge in Computing Science, Mathematics or Law.

---

## Application Forensics
The **FIRST** block of activities supports learners in appreciating the benefit and risks to application forensics.

### Block Structure
The block is structured as follows:

* **User Interactions and Applications.** The lecturer or instructor provides a brief lecture or overview on the significance of user interactions with application as they relate to the legal process.

* **Unicorn Pitch.** Learners will form teams and pitch a successful application that will enable to become a Unicorn start-up, that is a rare and valuable company.

* **Blueprint for Good Applications from the Forensic Investigator Perspective.** Learners will form new teams to identify common criteria for permitting applications in an Enterprise from the perspective of a Forensics investigator.

* **Unicorns vs Investigators.** Learners will identify the opportunities and obstacles in using application data as part of a forensics investigation.

* **Class Discussion on Using Application Data.** The class will consider and discuss some of the common potential opportunities and obstacles identified by teams.

* **Opportunities and Obstacles in using Application Data.** The activity block will conclude by relating activity outputs with material in the CyBOK.

---
### User Interactions and Applications.
The session begins with a brief lecture or overview on the significance of user interactions with application as they relate to the legal process.

Learners will use this material to appreciate the opportunities and challenges around application forensics.

#### Instructions
The lecturer or instructor should:

1. Present their own admissibility lecture or provide in advance for students to consider.

2. Permit time for questions to address any misconceptions or issues with the material presented.

---

### Unicorn Pitch
The aim of the activity is to focus learners on considering their prior knowledge and thoughts, in terms of building a successful start-up application. The expectation is that learners will come to consider applications from primarily two perspectives: that of the user and that of the provider.

In terms of the user, in what the qualities and feature they seek and what would engage them with the application. In terms of the business, what drives individuals to engage with their application and business model they will employ. These aspects relate back to the CyBOK in terms of ensuring learners appreciate that while valuable user data may be generated it may not be easily accessible due to business model choices.

#### Instructions
The lecturer or instructor should:

1. Advise learners they have to self-organise into teams of no more than **FOUR** members and no less than **THREE** members.

2. Advise teams they have **30** minutes to produce a **TWO** minute pitch with accompanying single presentation slide for an application for a given market that will enable them as start-up to be classed as a Unicorn. A company that is effectively rare given its perceived value. Advise learners they have few restrictions, other than the application must be focused at the consumer market and most be realistic in its claims and benefits, for example the application can not predict future lottery results.

3. Wander between teams as they form and create their ideas and companies. Motivate learners to consider the perspective of users and of business owners.

4. Collect the presentation slides from teams and collate them.

5. Use a [random number generator](https://www.google.com/search?q=random+number+generator) to randomly select teams to present. The lecturer may favour to select teams on what they have observed as to shape the discussion in a particular direction.

6. Remind teams they have **TWO** minutes to present and led the class in applause by clapping the teams off when time has elapsed.

7. Continue to call teams until a sufficient number of pitches have been presented.

8. Advise teams to spend **10** minutes reflecting on the pitches they have observed as well as their pitch. Advise them to identify **FIVE** qualities that make for a successful application, either from the perspective of user engagement or business rationale.

9. Issue a **ONE** minute warning before time elapses.

10. Collect the **FIVE** qualities from teams and advise them the material will be used in subsequent activities.

11. Permit time for questions to address any misconceptions or issues that emerged during the session.

#### Useful links

* [Random Number Generator](https://www.google.com/search?q=random+number+generator)

---

### Blueprint for Good Applications from the Forensic Investigator Perspective
The aim of the activity is to motivate learners to consider what would make a good application from the perspective of a forensic investigator. The expectation is that learners will come to consider that will extensive user engagement and logging may prove valuable data, gaining access to that data, how it is generated and the level of volume also presents challenges.

#### Instructions
The lecturer or instructor should:

1. Advise learners they have to self-organise into teams of no more than **FOUR** members and no less than **THREE** members. The members of the team should be different than the prior activity. The rationale is this will afford learners an opportunity to interact with other members of the class but also present a break from the though-process in the previous activity.

2. Advise teams they have **30** minutes to produce a **TWO** minute pitch with accompanying single presentation slide for criteria for permissible applications for a large multinational company. Emphasise to teams they are producing criteria from the perspective of a forensics investigator, not from the perspective of a manager or security engineer.

3. Wander between teams as they form and create their ideas and companies. Support learners in reflecting and balancing the challenge of extensive user engagement data and gaining accessing it.

4. Collect the presentation slides from teams and collate them.

5. Use a [random number generator](https://www.google.com/search?q=random+number+generator) to randomly select teams to present. The lecturer may favour to select teams on what they have observed as to shape the discussion in a particular direction.

6. Remind teams they have **TWO** minutes to present and led the class in applause by clapping the teams off when time has elapsed.

7. Continue to call teams until a sufficient number of pitches have been presented.

8. Advise teams to spend **10** minutes reflecting on the pitches they have observed as well as their pitch. Advise them to identify **FIVE** common criteria that would satisfy most of the pitches they observed.

9. Issue a **ONE** minute warning before time elapses.

10. Collect the **FIVE** common criteria  from teams and advise them the material will be used in subsequent activities.

11. Permit time for questions to address any misconceptions or issues that emerged during the session.

#### Useful links
* [Random Number Generator](https://www.google.com/search?q=random+number+generator)

---

### Unicorns vs Investigators
Teams will use their collective notes, their own research and other team pitches to identify the opportunities and challenges around using application data as part of a forensics investigation.

#### Instructions
The lecturer or instructor should:

1. Advise teams that they are to produce a **ONE** slide presentation that covers **THREE** opportunities for application data in forensics and **THREE** obstacles or challenges in using that application.

2. Issue the start-up pitches and common criteria produced by all teams from the prior activities to the class. Advise teams they have **30** minutes to produce their slides and can use their own research, collective notes and outputs from prior activities to produce the slide.

3. As teams produce their slides, the lecturer should wander between groups to observe discussion and actions.

4. Collect the presentation slides from teams in preparation of the next activity.

#### Materials
* [Activity Sheet](identifyOpportunitiesAndChallenges)

---

### Class Discussion on Using Application Data
Teams will present the opportunities and obstacles they have identified from the previous activity as well as engage in a discussion with the rest of the class.

#### Instructions
The lecturer or instructor should:

1. Use a [random number generator](https://www.google.com/search?q=random+number+generator) to randomly select teams to present. The lecturer may favour to select teams on what they have observed as to shape the discussion in a particular direction.

2. Advise teams they have **TWO** minutes to present and they are only expected to present a **SINGLE** opportunity or obstacle, but not one that has already been raised.

3. Teams that do not have a unique opportunity or obstacle should be clapped-off without presenting to inject some engagement and humour into the session.

4. After a sufficient number of presentations, for example **THREE** presentations, pause and engage the wider class and discuss some of what has been presented.

5. Continue to ask for teams to present either based on the discussion or what they have observed when teams were producing their slides or using a [random number generator](https://www.google.com/search?q=random+number+generator).

#### Useful links

* [Random Number Generator](https://www.google.com/search?q=random+number+generator)

---

### Opportunities and Obstacles in using Application Data
The lecturer should provide a brief overview of the themes identified in the prior activities and relate them to material presented in the [CyBOK](https://www.cybok.org).

#### Instructions
The lecturer or instructor should:

1. Advise learners of some of the themes that have emerged from consideration of the opportunities and obstacles in using application data for forensic purposes.

2. Relate the material to that discussed in the CyBOK.

3. Provide space for learners to raise any questions or address any gaps in understanding.

#### Useful links
* [CyBOK](https://www.cybok.org)

---

## Case Study: Web Browser
The **SECOND** block of activities is designed to support learners in the valuable information that can be learned from a popular application with individuals.

### Block structure
The block is structured as follows:

* **History of the Web Browser.** Instructor provides a brief lecture on the significant concepts of admissibility of evidence.

* **Produce Summary of Case.** Learners produce a summary of two cases that will act as the basis for subsequent activities.

* **Overview of Case.** Lecturer or instructor to provide an overview of the cases as to ensure all learners are starting with the same knowledge.

* **Friend Flummox**. Learners are required to devise an exam question that will challenge a peer in the class on the topic of what are the sources of forensically interesting material from a web browser.

* **Themes from Friend Flummox Activity**. Instructor leads class discussion and activity on the themes that emerged from the exam questions.

* **Web Browser Forensic Sources**. Instructor provides brief lecture on six main sources of forensic relevant data for web browsers.

---
### History of the Web Browser
The session begins with a brief lecture on the evolution and changes web browsers. The expectation is that learners will come to appreciate that the aspects that are valuable to forensic investigators, such as capturing user engagement, have been fairly consistent over a number of years and have only increased.

Learners will use this material to appreciate the opportunities and challenges in using such application data.

#### Instructions
The lecturer or instructor should:

1. Present their own admissibility lecture or provide in advance for students to consider.

2. Permit time for questions to address any misconceptions or issues with the material presented.

---

### Produce Summary of Case
The lecturer or instructor should advise learners to produce a summary of the case that will act as the foundation for activities.

Optional: the lecturer or instructor can set this as an entry ticket activity as in they are required to complete in advance of session.

#### Materials
* [Activity Sheet](produceSummary)

---

### Overview of Case
The lecturer or instructor should provide a brief summary of the *Commonwealth of Massachusetts v Brain Walshe* case to the class.

The motivation for providing the overview is to:

* address any misconceptions or gaps in understanding that students may have developed when considering the case in advance.

* support those students that have no adequately considered the case in advance as to ensure they can effectively contribute to the activity.

#### Materials
* [Case Summary](caseSummary)

---

### Search History of Brain Walshe
The lecture or instructor will show a video of search history being read to the defendant Brain Walshe. Learners will watch the video and note down some of the search history.

The rationale is to captivate and engage learners with the value of search history and what it can contribute to the legal process.

#### Instructions
The lecturer or instructor should:

1. Advise learners they are going to watch a video clip of Brain Walshe being read his search history. Learners should note the search history mentioned and will form pairs and discuss the search history.

2. Issue the [Search History Activity Sheet](searchHistoryActivitySheet) to learners.

2. Play the [Brain Walshe Search History](https://www.youtube.com/watch?v=wUFT99Pw0IY) video clip. Advise learners to reflect on the search history as they watch the video.

3. Advise learners to form pairs and spend **10** minutes comparing search history and discussing any notes and thoughts they had on the recovered search history.

4. Open an audience response system activity, such as [Mentimeter](https://www.mentimeter.com), ask learners to submit some of the themes of the discussion had between pairs.

5. Steer the conversation towards the significance of application data being used to signal individual intention, but also how data could be interpreted and if there are other explanations.

6. Advise learners they have **FIVE** minutes to reflect on the activity and should make notes. Suggest to learners to reflect on that search history is just one aspect of a web browser and to consider what other aspects may provide valuable data.

#### Materials
* [Brain Walshe Search History](https://www.youtube.com/watch?v=wUFT99Pw0IY)
* [Search History Activity Sheet](searchHistoryActivitySheet)
* [Mentimeter](https://www.mentimeter.com)

---

### Friend Flummox
An engaging activity to motivate learners to engage with the different potential sources of data from web browsers that may be valuable to a forensics investigation. Learners are required to devise an exam question that will challenge a peer in the class on the topic.

The goal of the activity is to focus learners and to generate curiosity as well as to provide an opportunity for learners to develop interpersonal and communication skills.

#### Instructions
The lecturer or instructor should:

1. Advise class that they are required to create an exam question that probes understanding of sources of relevant data from a web browser to a forensics investigation. The question should challenge peers.

Learners can be as creative as they want in the design of the question, for example they do not need to restrict themselves to text.

2. Give the learners around **TEN** minutes to create the question.

3. Maintain and ensure energy in the room by walking through the class and advising when time is running out.

4. Instruct learners to form pairs or trios and exchange their exam questions. The pairs or trios then have **TEN** minutes to tackle the question. The questions do not need to be in exam conditions, learners can have fun and help each other out.

5. Collect all the exam questions from the learners.

#### Materials

* [Activity Sheet](../../general/friendFlummox)

---

### Themes from Friend Flummox Activity
The aim of the prior activity is to drive curiosity and interest in the challenge of sources of relevant data from a web browser to a forensics investigation. The lecturer should now focus the class by considering the themes that emerged in the exam questions and steer learners to areas of focus.

#### Instructions
The lecturer or instructor should:

1. Ask learners to nominate any particular good exam questions. Nominators should present the exam question to the class and state the advantages of the approach.

2. Open the question to the class and ask them to comment on the question and how they would approach it.

3. Repeat process until a number of questions have been considered. Open an audience response system activity, such as [Mentimeter](https://www.mentimeter.com), ask learners to submit some of the themes that emerge from these questions in terms of areas of focus.

4. Steer the consideration of themes along the significance of the different sources, such as *search history*, *form data*, *temporary files*, *downloaded files*, *HTML5 local storage* and *cookies*.

5. Permit time for questions to address any misconceptions or issues with the material presented.

#### Useful links
* [Mentimeter](https://www.mentimeter.com)

---
### Web Browser Forensic Sources
The block should conclude by relating the outcomes from the prior activities to material in the [CyBOK](https://www.cybok.org).

#### Instructions
The lecturer or instructor should:

1. Present their own lecture on the importance of guidelines or provide material in advance for learners to consider.

2. Relate the material presented back to the forensic sources interesting to forensics investigators documented in the [CyBOK](https://www.cybok.org).

3. Permit time for questions to address any misconceptions or issues with the material presented.

---
## Study of Web Search History
The **THIRD** and block of activities will afford learners the opportunity to apply knowledge from prior activities and relate to a relevant case.

### Block Structure
The block is structured as follows:

* **Produce Summary of Case Study.** Learners are required to produce a summary of the case being considered in the class.

* **Overview of State of Indiana vs Gaylyn Morris** Instructor provides an overview of the case to the class to ensure every learner is starting from the same point.

* **Gathering and Interpreting Application Usage as Evidence.**
Learners then have to extract fictional evidence from application usage for the case study, that has been generated by their peers.

* **Practice Sharing.**
Learners nominate and share strong or interesting examples they observed from the previous activity.

* **Class Collective Identification of Emerging Themes of Using Application Usage Data.**
Learners consider as a class the emerging themes that comes from using application usage as evidence.

---
### Using Application Usage Data as Evidence
The session begins with a brief lecture or overview on using application usage data as evidence as part of the legal process.

Learners will use this material to appreciate the opportunities and challenges around application forensics.

#### Instructions
The lecturer or instructor should:

1. Present their own using application usage data as evidence lecture or provide in advance for students to consider.

2. Permit time for questions to address any misconceptions or issues with the material presented.

---
### Produce Summary of Case Study
The lecturer or instructor should advise learners to produce a summary of the case that will act as the foundation for activities.

Optional: the lecturer or instructor can set this as an entry ticket activity as in they are required to complete in advance of session.

#### Materials
* [Activity Sheet](produceSummary2)

---

### Overview of State of Indiana vs Gaylyn Morris
The lecturer or instructor should provide a brief summary of the *State of Indiana vs Gaylyn Morris* case to the class.

The motivation for providing the overview is to:

* address any misconceptions or gaps in understanding that students may have developed when considering the case in advance.

* support those students that have no adequately considered the case in advance as to ensure they can effectively contribute to the activity.

#### Materials
* [Case Summary](caseSummary2)

---

### Gathering and Interpreting Application Usage as Evidence
The aim of the activity is for the learners to gain insight into how to analysis and consider the search history of an individual from the perspective of a forensics investigation.

#### Instructions
The lecturer or instructor should:

1. Issue the [Stump Activity Sheet](stumpActivitySheet) to learners.

1. Advise learners they are going to create an application usage trail using
a web browser for the accused in the case study. Advise learners that in generating the trail they should aspects that have been previously considered, such as misinterpretation of data points, i.e. interpreting data of usage from one perspective without considering an alternative, as well as anti-forensics techniques, i.e. purposely counterfeiting exculpatory evidence.

2. Advise learners that the class will vote on particularly creative, engaging and intelligent attempts at the activity.

3. Advise learners they have **30** minutes to generate the application usage data. Inform learners they will be issued a **FIVE** minute warning when time is nearly elapsed. Learners can generate the application data usage trail via:

  - **Pen and paper.** Learners can generate the application usage data using pen and paper and completing a [Mock Application Data Usage Sheet](mockApplicationDataUsageSheet) by hand.
  - **Spreadsheet.** Learns can generate the application usage data using a digital system, such as a laptop or tablet, and completing a [Mock Application Data Usage Sheet](mockApplicationDataUsageSheet) using a device.
  - **Web browser and appropriate tool.** Learners can use a web browser, but should be advised to wipe to factory settings and generate the data and use an appropriate tool to generate the data, such as [Hindsight](https://github.com/obsidianforensics/hindsight).

4. Walk through the class as learners perform their task and discuss the topic and the approach they are adopting. Issue each learner with a piece of paper and pen as they perform the task.

5. After time has elapsed, advise learners to write their favourite colour on the paper in big lettering.

5. Advise learners they are going to pair-up with another learner after time has elapsed. Inform them to wander around the class and pair-up with another learner that has the same favourite colour. If there any remaining learners, assign them to each other.

6. Advise learners to swap their application usage data with their new partner.

7. Advise learners they have **15** minutes to assemble a convincing trail of usage data from the data providing, keeping in mind the tactics the other learner may have performed to **stump** them. Inform learners they will be issued a **ONE** minute warning when time is nearly elapsed.

8. Advise pairs they have **10** minutes to exchange outlines of the trails uncovered and their interpretation of the data. Respective partners should communicate if this is correct or what the other has missed. Inform learners they will be issued a **FIVE** minute warning to swap around during the time.

8. Advise learners they can now choose to nominate their partner's stump, either because they observed a quality they would like to share with the class or discuss with the class. Advise learners if no-one nominates, pairs will be selected at random. Use an audience response system, such as [Mentimeter](https://www.mentimeter.com), or paper to collect nominations.

9. Select learners to present based on nominations or select learners if no nominations are received. Ask the learners to present their partner's stump and describe how they uncovered the trail, what their interpretation of it was and whether it is correct. Advise other learners to take notes as they observe the presentations.

#### Materials
* [Stump Activity Sheet](stumpActivitySheet)
* [Mock Application Data Usage Sheet](mockApplicationDataUsageSheet)
* [Mentimeter](https://www.mentimeter.com)
* [Hindsight](https://github.com/obsidianforensics/hindsight)
* Pen and paper

---

### Class Collective Identification of Emerging Themes of Using Application Usage Data
The aim is for the class to broadly identify emerging themes of using application data, specifically the elements of data that are valuable but also in terms of how these data points can be connected, in such a way that may be inaccurate and so must be carefully considered.

#### Instructions

The lecturer or instructor should:

1. Use a [random number generator](https://www.google.com/search?q=random+number+generator) to randomly select pairs to present. The lecturer may favour to select pairs on what they have observed, rather than randomly, to demonstrate and discuss with the entire class any novel insights or gaps in understanding.

2. Briefly refresh the class on cases considered across the prior activities, emphasising examples of the data collected and how this has been interpreted.

3. Advise pairs they have **FIVE** minutes to reflect on the notes they have made from the prior activities. Advise them to speak to their partner to resolve any misconceptions and gaps.

4. After the time has elapsed, advise pairs they have **10** minutes to generate a shared note that highlights the key elements of application usage that can be learned from application forensics, concerns around interpretation and any misconceptions that neither can satisfactorily resolve.

5. Identify pairs at to random to stand-up and discuss **ONE** key element of application usage and concerns around interpretation of such usage from a forensics perspective. Ask one member of the pair to present it to the class while the other acts as note taker and writes the heading or name for the element on a white board.

5. Use an audience response system, such [Mentimeter](https://www.mentimeter.com), and ask the class if they have any additional thoughts around the strengths and concerns of using such elements of application usage data from a forensics perspective. Request the note taker to add some of the comments to the whiteboard.

6. Thank the pair of learners and identify another pair of learners. Advise the pair to share an element and concern, not previously discussed. Similarly, one learner should present while the other notes the heading on the whiteboard. The class should then be asked via an audience response system for any additional thoughts that the note taker can add to the board. Continue in this fashion until a sufficient number of elements have been considered.

7. Summaries the key elements devised by the class and emphasise the more significant elements provided by leaners.

#### Useful links
* [Mentimeter](https://www.mentimeter.com)
* [Random Number Generator](https://www.google.com/search?q=random+number+generator)

---

## Application Usage as Evidence
The **FOURTH** and final block is used to conclude the active lesson plan and is focused on aligning the outcomes of the activities with material presented in the [CyBOK](https://www.cybok.org/media/downloads/Forensics_v1.0.1.pdf).

#### Instructions
The lecturer or instructor should:

1. Briefly present again their own lecture on the use of hash functions to identify contraband or provide it in advance for students to consider.

2. Relate the presented material to the arguments, remarks and evidence provided by learners during the class debate to relevant material in the [CyBOK](https://www.cybok.org/media/downloads/Forensics_v1.0.1.pdf).

3. Provide an opportunity for learners to address questions and/or address any misconceptions.

3. Ask learners to complete the Quad Fold Activity.

#### Materials
* [Quad Fold Activity](../general/quadFold)
* [CyBOK](https://www.cybok.org/media/downloads/Forensics_v1.0.1.pdf)
