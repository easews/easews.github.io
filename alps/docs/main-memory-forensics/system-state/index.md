---
layout: default
title: System State
nav_order: 1
parent: Main Memory Forensics
has_children: true
---

# System State Active Lesson Plan
This active lesson plan considers analysis of system state using volatile main memory. The active lesson plan is designed to support individuals in developing an initial awareness of how the value of system state to an investigation. An [overview video](../resources/memory.m4v) outlines the structure of the active lesson plan.

> The early view of best forensic practices was to literally pull the plug on a machine that was to be impounded. The rationale was that this would remove any possibility of alerting the processes running on the host and would preempt any attempts to hide information. Over time, experience has shown that these concerns were largely exaggerated and that the substantial and irreversible loss of important forensic information such as open connections and encryption keys was rarely justified. [CyBOK Forensics Knowledge Area P(21)](https://www.cybok.org/media/downloads/Forensics_v1.0.1.pdf)


## Structure
Learners complete **THREE** blocks of activities that are designed to support them in appreciating the benefits as well as risks in analysing volatile memory. Using a real-world case as a staring point, instructors support learning through the following activity blocks:

1. **Memory Analysis.** The first block of activities supports learners in appreciating the benefit and risks to memory analysis.

2. **Investigation of System Run-time State.** The second block of activities will afford learners the opportunity to apply knowledge from the CyBOK.

3. **Summary of System State Analysis.** The third and final block is used to conclude the active lesson plan and relate activities back to material in the [CyBOK](https://www.cybok.org).  

### Qualification Level
The active lesson plan can be adjusted to accommodate many of the United Kingdom qualification levels. In its current form the active lesson plan is targeting learners at Levels 6 and 7 on the Regulated Qualifications Framework (RQF) and Credit and Qualifications Framework (CQFW) in England and Wales, Levels 10 and 11 on the Scottish Credit and Qualifications Framework (SCQF) and Levels 6 and 7 on European Qualifications Framework (EQF).

The active lesson plan does not expect nor require an individual to posses significant knowledge in Computing Science, Mathematics or Law.

---

## Main Memory Analysis
The **FIRST** block of activities supports learners in appreciating the benefit and risks to memory analysis.

### Block Structure
The block is structured as follows:

* **Overview of Memory Analysis.** The session begins with a brief lecture on the theory and relevant concepts related to volatile memory analysis.

* **Produce Summary of Case Study.** The lecturer or instructor should advise learners to produce a summary of the case that will act as the foundation for activities.

* **Overview of In re Boucher.** The lecturer or instructor at this point should provide a brief summary of the *In re Boucher* case to the class.  

* **Class Debate: In re Boucher.** A practice debate in preparation for a more significant subsequent classroom debate.

* **Consideration and Selection of Case Study.** Learners are to consider and select an appropriate case study.

* **Class Debate: Pulling the Plug.** Structured classroom debate around the concerns of conducting live analysis of main memory or not.

* **Personal Reflection on Pulling the Plug class debate.** Opportunity for individual learners to reflect on the structured classroom debate.

* **Collective Reflection on Pulling the Plug class debate.** Class-wide consideration and reflection of the structured classroom debate.

* **Summary of Risks and Benefits of Memory Analysis.** Conclude the session and motivate learners to consider the evidence collected by the class as whole as well as relate it back to the CyBOK.

---


### Overview of Main Memory Analysis

The session begins with a brief lecture on the theory and relevant concepts related to volatile memory analysis.

Learners will use this knowledge to appreciate the upcoming challenges in securing viable evidence and how this contrasts to the traditional mindset in Forensics of operating on non-live systems.

#### Instructions
The lecturer or instructor should:

1. Present their own lecture on memory analysis as an approach to secure evidence valuable and relevant to a Forensics investigation.

2. Permit time for questions to address any misconceptions or issues with the material presented.

---
### Produce Summary of Case Study
The lecturer or instructor should advise learners to produce a summary of the case that will act as the foundation for activities.

Optional: the lecturer or instructor can set this as an *entry ticket activity* as in they are required to complete in advance of session.

#### Materials
* [Activity Sheet](produceSummary)

---

### Overview of In re Boucher
The lecturer or instructor at this point should provide a brief summary of the *In re Boucher* case to the class.

The motivation for providing the overview is:

* address any misconceptions or gaps in understanding that students may have developed when considering the case in advance.

* support those students that have no adequately considered the case in advance as to ensure they can effectively contribute to the activity.

#### Materials
* [Case Summary](caseSummary)

---
### Class Debate: In re Boucher
The aim is for the present activity to act as practice for a subsequent structured classroom debate.

#### Instructions
The lecturer or instructor should:

1. Advise learners that the class is going to debate the merits of whether Boucher should surrender his password or not.

2. Issue the practice debate activity sheet.

3. Issue summary previously collected from learners that they generated from summarising the case.

4. Randomly label learners, either A or B, and advise them to self-organise into pairs of A and B.

5. Advise all learners labelled 'A' that they have to advocate the affirmative position. Consequently, all learners labelled 'B' are to adopt the negative position.

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
* [Practice Debate Activity Sheet](practiceDebate)
* [Random Number Generator](https://www.google.com/search?q=random+number+generator)

---

### Consideration and Selection of Case Study
Learners will consider **THREE** scenarios where consideration of volatile memory may be valuable as part of the forensics investigation.

The aim is to provide learners an opportunity to develop insight into the different scenarios where consideration of volatile memory may be valuable but also the risks involved in conducting such analysis, in terms of compromising a forensics investigation.

#### Instructions
The lecturer or instructor should:

1. Advise learners they are going to independently consider a number of case studies and select one for further inquiry.

2. Advise learners to consider or focus on the significance of live analysis, whether it was optimal or necessary in the given context and whether risks were considered in adopting the approach. Advise learners they should source high-quality evidence to support their critique.

3. Advise learners they should produce a summary of no more than **250** word as well as additional sources of evidence to support their position.

4. Advise learners to produce the summary in-time for the next activity either physical or via an appropriate virtual learning platform.

#### Materials
* [Case Studies](caseStudies)

---

### Class Debate: Pulling the Plug
Learners will form teams and participate in a class debate. The aim is to provide an opportunity for learners to develop skills and gain insight into the risks and benefits of valuing system state and the contents volatile system elements, such as memory.

#### Instructions
The lecturer or instructor should:

1. Advise teams they are going to organise into teams focused on the case study they selected for further inquiry from the prior activity.

2. Allocate learners to teams or advise them to self-organise into teams of no more than **FOUR** members and no less than **THREE** members. The teams must organise around the case studies they selected in the prior activity. Assign each team a number, for example a number between 100 to 199 for topic one, 200 to 299 for case study two etc and issue the [Class Debate Activity Task Sheet](classDebateActivitySheet).

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

9. Invite the class to clap the team off the floor and then advise the odd numbered team to take the floor for the last time. Advise the team they also have **THREE** minutes to respond directly to the points made by the opposing team and present their closing arguments.

10. Thank both teams and repeat the process with different teams for a few more cycles until the central learning outcomes have been achieved.

11. Invite the class to clap and thank the presenters one more time. Advise the class they have **TEN** minutes to consolidate any ideas and notes from the session as such notes will support subsequent activities.

12. Collect all the evidence and summaries from the remaining teams that did not present in the session. The material will be made available to the class as a whole for subsequent activities.

#### Materials
* [Class Debate Activity Sheet](classDebateActivitySheet)
* [Random Number Generator](https://www.google.com/search?q=random+number+generator)

---

### Personal Reflection on Pulling the Plug class debate
Learners are given the opportunity to reflect on the class debate as to reflect on the skills develop but also to mitigate against the *free-rider* problem.

#### Instructions
The lecturer or instructor should:

1. Advise learners they are going to reflect on the activities they have completed so far in the lesson plan and are expected to submit an individual reflective essay of no more than **1500** words.

2. The individual reflection should reflect their own position on the topic tackled in prior sessions. Individuals are expected to drawn on the experience of the debates as well as the evidence they collected as part of a team, the evidence collected by their team as a whole as well as the evidence collected by other teams.

3. Advise learners that all the evidence collected from teams will be available via the virtual learning environment or appropriate service. Advise learners they should exhibit independent and critical thought by contrasting the evidence provided by others with the evidence they sourced.

4. Advise learners submission instructions and process are detailed in the [debate reflection specification](debateReflectionSpecification).   

#### Materials

* [Debate Reflection Specification](debateReflectionSpecification)

---

### Collective Reflection on Pulling the Plug class debate
Learners are exposed to different perspectives and opinions in terms of the material presented, evidence sourced as well as remarks made by peers. The expectation is the opportunities the activity presents will further develop learner skills as well as widen understanding of the problem.

#### Instructions
The lecturer or instructor should:

1. Summarises the central arguments presented during the debate as well as present some of the evidence submitted by the cohort.

2. Critique the evidence supplied by teams in terms of relevance, source, and overall quality.

3. Expose and emphasise the different remarks made by teams during the debate session.

4. Provide space as well as opportunity for learners to present their own questions or opinions and remarks.

5. Provide an opportunity for learners to ask any remaining questions or concerns regarding the debate itself.

---

### Summary of Risks and Benefits of Memory Analysis

The aim is to conclude the session and motivate learners to consider the evidence collected by the class as whole as well as relate it back to the [CyBOK](https://www.cybok.org/media/downloads/Forensics_v1.0.1.pdf).

#### Instructions
The lecturer or instructor should:

1. Briefly present again their own lecture on the use of hash functions to identify contraband or provide it in advance for students to consider.

2. Relate the presented material to the arguments, remarks and evidence provided by learners during the class debate.

3. Provide an opportunity for learners to address questions and/or address any misconceptions.

#### Useful links
* [CyBOK](https://www.cybok.org/media/downloads/Forensics_v1.0.1.pdf)

---

## System State Analysis
The **THIRD** and final block of activities affords learners the opportunity to gain insight into the analysis of system state and how that can contribute to an investigation in forensics.

The activities are structured in-line with material from the [CyBOK](https://www.cybok.org), specifically in terms of system run-time state, i.e. processes, network connections, artifacts and fragments as well as file information.

The activity block is based off of [several documented](../../general/sources) texts, tutorials and workshops around using the open-source [Volatility Framework](https://www.volatilityfoundation.org) analysing a capture of a memory file containing the Cridex malware. The activity block is designed so that it can be executed without the lecturer or instructor using any framework or tool. Alternatively, the lecturer or instructor may act as a ***puppet instructor*** and perform live analysis or configure a lab to allow a focused technical class centred around the material.

### Block structure
The block is structured as follows:

* **Overview of System State Analysis.** Instructor provides a brief lecture on the significant concepts of system state analysis and relevance in digital investigations.

* **Produce Summary of Case Study.** Learners are required to produce a summary of the case being considered in the class.

* **Overview of Case.** Instructor provides an overview of the case to the class to ensure every learner is starting from the same point.

* **Processes.** Class first considers the processes that were executing on the system when an image of main memory was captured.

* **Network Connections.** Class then considers the open network connections that were utilised by the processes that were identified as interesting from the previous block of activities.

* **Artifacts and Fragments.** Class then considers the artifacts and fragments relevant to the processes and open network connections previously identified.

* **File Information.** Class lastly considers the extracted executable itself that has been identified from previously considered processes, network connections and relevant artifacts as well as fragments.

---

### Overview of System State Analysis
The session begins with a brief lecture on the significant concepts of information processing, in terms of triaging information as well as how to reduce and expand data where relevant within the context of digital investigations.

Learners will use this material as well as consideration of the case study to intimately consider the major information processing steps in digital investigations.

#### Instructions
The lecturer or instructor should:

1. Present their own information processing lecture or provide it in advance for students to consider.

2. Permit time for questions to address any misconceptions or issues with the material presented.
---

### Produce Summary of Case Study
The lecturer or instructor should advise learners to produce a summary of the case that will act as the foundation for activities.

Optional: the lecturer or instructor can set this as an *entry ticket activity* as in they are required to complete in advance of session.

#### Materials
* [Activity Sheet](produceSummary1)

---

### Overview of Case
The lecturer or instructor at this point should provide a brief summary of the *Gordon v. Chipotle Mexican Grill, Inc.* case to the class.

The motivation for providing the overview is:

* address any misconceptions or gaps in understanding that students may have developed when considering the case in advance.

* support those students that have no adequately considered the case in advance as to ensure they can effectively contribute to the activity.

#### Materials
* [Case Summary](caseSummary1)

---
### Processes
The aim of the block of activities if for the class to consider the processes that were executing at the point when an image of volatile memory was captured from the system. There are several tutorials and resources available to support such activity and this activity is based on these [sources](../about/references.html).

The expectation is that learners will come to learn how to use such information to set and steer investigations of system state.

#### Instructions
The lecturer or instructor should:

1. Advise learners that the class is going to consider a previously capture image of volatile memory from a system. The first step will be to consider the processes that were executing on the system at the point of capture.

2. Either demonstrate live analysis of the image using the [Volatility Framework](https://www.volatilityfoundation.org) and  ```pslist``` or inform this has been done in advance of the session.

3. Issue the [Process List Activity Sheet](processList) to learners and advise them they have **15** minutes to research and investigate the processes and identify any aspects that are curious or would prompt further investigation.  

4. After time has elapsed advise learners to self-organise into pairs and spend **10** minutes compare their investigations of the processes, share insights as well as tackle any misconceptions.

5. After time has elapsed, use an audience response system, such as [Mentimeter](https://www.mentimeter.com), and ask pairs to suggest any interesting aspects.

6. Advise the class, if it has not surfaced from the audience, that:
 - The majority of processes are either system critical or relevant to the Microsoft Windows Operating System, for example ```Explorer.exe``` with Process ID ```1484```.
 - The process are executing in session ```0``` which would indicate an older version of the Microsoft Windows Operating System.
 - There is seemingly only one potential process from an external vendor, i.e. ```reader_sl.exe``` with Process ID ```1640```, that has a Parent Process ID of ```1484```.


5. Advise the class that the next step will be to visualise the processes in terms of parent and child relationships. Either demonstrate live analysis of the image using the [Volatility Framework](https://www.volatilityfoundation.org) and  ```pstree``` or inform this has been done in advance of the session.

6. Advise learners to remain in pairs and issue the [Process Tree Activity Tree](processTree). Advise pairs they have **15** minutes to document the relationships between the processes. Advise pairs they will be given a **ONE** minute warning before time elapses and that a pair will be selected at random to present.  

7. Wander between the pairs of learners to gain insight as well as offer any help and support.

8. After time has elapsed, use a [random number generator](https://www.google.com/search?q=random+number+generator) to randomly select pairs to present. The lecturer may favour to select pairs on what they have observed, rather than randomly, to demonstrate and discuss with the entire class any novel insights or gaps in understanding.

9. Advise class at this stage, if the opportunity has not happened from class discussion, the most interesting aspect from consideration of process relationships. Advise the class the **OUTCOME** for the block of activities is ```reader_sl.exe``` with Process ID ```1640``` is child, to parent process ```Explorer.exe``` with Process ID ```1484```.

10. Advise the class to note down the primary outcome of the block of activities as well as any other thoughts. Permit time for questions to address any misconceptions or issues with the material presented.

#### Materials
* [Process List Activity Sheet](processList)
* [Process Tree Activity Tree](processTree)
* [Volatility Framework](https://www.volatilityfoundation.org)
* [Mentimeter](https://www.mentimeter.com)
* [Random Number Generator](https://www.google.com/search?q=random+number+generator)

---

### Network Connections
The aim of the block of activities if for the class to consider the network connections initiated by processes as well as considering what connections remained open at the point of image capture.

#### Instructions
The lecturer or instructor should:

1. Advise learners that the class is going to continue to consider the same image of volatile memory from a system. The second step is to consider the network connections that were initiated by processes and those that remained open at the point of capture.

2. Either demonstrate live analysis of the image using the [Volatility Framework](https://www.volatilityfoundation.org) and  ```connscan``` or inform this has been done in advance of the session.

3. Issue the [TCP Connections](TCPConnections) information sheet that contains the console output for the ```connscan``` command. A command that lists logged TCP connections.

4. Advise learners that next stage is to consider the open network connections at the point of memory image capture.

5. Either demonstrate live analysis of the image using the [Volatility Framework](https://www.volatilityfoundation.org) and  ```sockets``` or inform this has been done in advance of the session.

6. Issue the [Open Sockets](openSockets) information sheet that contains the console output for the ```sockets``` command. A command that lists logged sockets and their activity.

7. Issue the [Network Connections Activity Sheet](networkConnectionsActivitySheet). Advise pairs they have **15** minutes identify interesting information that emerges from consideration the [TCP Connections](TCPConnections) output and [Open Sockets](openSockets) output related to the outcome of the previous block of activities on processes. Advise pairs they will be given a **ONE** minute warning before time elapses and that a pair will be selected at random to present.  

8. Wander between the pairs of learners to gain insight as well as offer any help and support.

9. After time has elapsed, use a [random number generator](https://www.google.com/search?q=random+number+generator) to randomly select pairs to present. The lecturer may favour to select pairs on what they have observed, rather than randomly, to demonstrate and discuss with the entire class any novel insights or gaps in understanding.

10. Advise the class, if it has not surfaced from the audience, that:
 - That ```Explorer.exe``` process with Process ID ```1484``` has used **TWO** TCP connections when referring to [TCP Connections](TCPConnections) output.
 - That one of the TCP connections is open using port ```1038``` with connection to ```41.168.5.140``` when referring to [Open Sockets](openSockets) output.


11. Advise class at this stage, if the opportunity has not happened from class discussion, the most interesting aspect from consideration of network connections. Advise the class, the **OUTCOME** for the block of activities is an opened connection on ```41.168.5.140:8080``` utilised by the processes we found interesting previously, that is the critical ```Explorer.exe``` process with Process ID ```1484```.

12. Advise the class to note down the primary outcome of the block of activities as well as any other thoughts. Permit time for questions to address any misconceptions or issues with the material presented.

#### Materials
* [TCP Connections](TCPConnections)
* [Open Sockets](openSockets)
* [Network Connections Activity Sheet](networkConnectionsActivitySheet)
* [Process List Activity Sheet](processList)
* [Process Tree Activity Tree](processTree)
* [Random Number Generator](https://www.google.com/search?q=random+number+generator)
---

### Artifacts and Fragments
The aim of the block of activities if for the class to consider the artifacts and fragments generated by processes and individual users of the system at the point of image capture.

#### Instructions

1. Advise learners that the class is going to continue to consider the same image of volatile memory from a system. The third step is to consider the artifacts and fragments generated by the system and users that may inform the investigation.

2. Either demonstrate live analysis of the image using the [Volatility Framework](https://www.volatilityfoundation.org) and  ```cmdline``` or inform this has been done in advance of the session.

3. Issue the [Command Line Sheet](commandLineSheet) information sheet that contains the console output for the ```cmdline``` command. A command that lists arguments supplied processes to the command line.

4. Advise learners to spend a few minutes considering the [Command Line Sheet](commandLineSheet) output and their notes from previous activity blocks to identify any interesting aspects.

4. Use an audience response system, such as [Mentimeter](https://www.mentimeter.com), to gain insight from the class.

5. Advise the class, if it has not surfaced from the audience, that:
 - The path ```C:\Program Files\Adobe\Reader 9.0\Reader\Reader_sl.exe``` is observable for the ```reader_sl.exe``` process that was previously identified with Process ID ```1640```, child to the ```Explorer.exe``` process with Process ID ```1484```.
 - The path would appear to suggest the executable is from ```Adobe``` and is reputable, but it have also previously identified that the process may have made use of an open network connection.

6. Use an audience response system, such as [Mentimeter](https://www.mentimeter.com), and ask learners to suggest what the next action or step should be taken at this point.

7. Advise the class, if it has not surfaced from the audience, that the next two steps are:
 - Extract the contents of memory used by the process ```1640```.
 - Extract the executable itself for inspection, specifically ```reader_sl.exe```.

8. Advise learners that actions to do with the executable will be considered in the next block of activities. The focus at this stage is the memory dump extracted for the ```1640``` process itself.

9. Either demonstrate live analysis of the image using the [Volatility Framework](https://www.volatilityfoundation.org) and  ```memdump``` or inform this has been done in advance of the session.

10. Advise the class that the memory dump for ```1640``` is very large and contains many sequence of bytes, some that will contain human-readable characters that could be processed efficiently, i.e. through searching.

11. Use an audience response system, such as [Mentimeter](https://www.mentimeter.com), and ask learners to suggest what the next action or step should be taken at this point with the large memory dump, in terms of trying to efficiently navigating such a large volume of information. Advise learners to consider the notes and areas of interest from previous activity blocks.

12. Advise the class, if it has not surfaced from the audience, that searching the memory dump for references to the previously identified open connection, i.e. ```41.168.5.140```, may surface interesting data.

13. Either demonstrate live analysis of the image using the [Volatility Framework](https://www.volatilityfoundation.org) and  ```strings``` and ```grep``` or inform this has been done in advance of the session.

14. Issue the [Memory Dump Analysis](memoryDumpAnalysis) information sheet that contains the console output for the ```strings``` and ```grep``` command.

15. Use an audience response system, such as [Mentimeter](https://www.mentimeter.com), and ask learners to communicate what the information suggests from the memory dump.

16. Advise the class, if it has not surfaced from the audience, that:
 - The process is ```POST```ing information through the open network connection, suggesting data is being exfiltrated from the system.
 - The ```URL``` list of financial organisations would suggest the process is potentially malicious.


17. Advise class at this stage, if the opportunity has not happened from class discussion, the most interesting aspect from consideration of network connections. Advise the class, the **OUTCOME** for the block of activities is URLs that relate to financial organisations, false or otherwise, have been identified in the memory dump of the ```reader_sl.exe``` process with process ID ```1640```.

18. Advise the class to note down the primary outcome of the block of activities as well as any other thoughts. Permit time for questions to address any misconceptions or issues with the material presented.

#### Materials
* [Command Line Sheet](commandLineSheet)
* [Memory Dump Analysis](memoryDumpAnalysis)
* [Mentimeter](https://www.mentimeter.com)
---

### File Information
The aim of the block of activities if for the class to consider executable itself and whether it is malicious or not.

#### Instructions
The lecturer or instructor should:

1. Advise learners that the class is going to continue to consider the same image of volatile memory from a system. The fourth and final step to consider the executable itself.

2. Advise learners to spend **FIVE** minutes considering what an investigator could do with the executable extracted in the previous block of activities.

3. After time has elapsed, advise learners they are to self-organise into pairs and spend **FIVE** minutes discussing the different actions they could take as investigators to learn more from the executable.

4. Wander between the pairs of learners to gain insight as well as offer any help and support.

5. After time has elapsed, use a [random number generator](https://www.google.com/search?q=random+number+generator) to randomly select pairs to present. The lecturer may favour to select pairs on what they have observed, rather than randomly, to demonstrate and discuss with the entire class any novel insights or gaps in understanding.

6. Advise the class, if it has not surfaced from the audience, that:
 - An option is to perform significance analysis on the executable itself to determine if it contains any malicious content.
 - Another option is that the executable could be checked with a repository of known malicious files to assess if it is malicious or not.

7. Either demonstrate checking the executable against the [Virus Total](https://www.virustotal.com/gui/home/upload) repository or inform this has been done in advance of the session.

8. Advise the class, the **OUTCOME** for the block of activities is executable has been deemed malicious, specifically a malicious Trojan, by the repository.

9. Advise the class to note down the primary outcome of the block of activities as well as any other thoughts. Permit time for questions to address any misconceptions or issues with the material presented.

#### Materials
* [Virus Total](https://www.virustotal.com/gui/home/upload)
* [Hybrid Analysis](https://www.hybrid-analysis.com)
* [Random Number Generator](https://www.google.com/search?q=random+number+generator)
---

## Summary of System State Analysis.
The **FOURTH** block is used to conclude the active lesson plan and is focused on aligning the outcomes of the activities with material presented in the [CyBOK](https://www.cybok.org).

#### Instructions
The lecturer or instructor should:

1. Present their own summary of system state analysis using volatile memory and relate it back to the material in the [CyBOK](https://www.cybok.org).

2. Permit time for questions to address any misconceptions or issues with the material presented.

2. Ask the class if they have any questions or do not any aspect of what was covered in the session.

3. Ask learners to complete the Quad Fold Activity.

#### Materials
* [Quad Fold Activity](../../general/quadFold.html)
* [CyBOK](https://www.cybok.org)
---
