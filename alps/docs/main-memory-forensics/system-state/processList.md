---
layout: default
title: Process List
nav_order: 2
parent: System State
has_children: false
---

## Process List Activity Sheet
Learners are to complete the following:

1. Consider the **CONSOLE OUPUT** from [Volatility Framework](https://www.volatilityfoundation.org) below after executing the ```pslist``` plugin on the captured memory image.

2. Spend **15** minutes considering, researching and investigating each of the processes. Learners should complete the **PROCESS LIST TABLE** below as the information will be valuable in subsequent activities.

3. After time has elapsed, self-organise into pairs with another learner.

4. Spend **10** minutes with your partner comparing research of processes, sharing insights as well as debating any misconceptions.

### Process List Table

| Process Identification (PID) | Parent Process Identification (PPID) | Process Name | Long Process Name | Notes |
| -----------------------------| -------------------------------------| ------------ | ------------------| ------|
| 1484 | 1464 | Explorer.exe | Windows Explorer | Responsible for managing interaction with individual user, has access to several sensitive systems areas (such as files) and there is typically one process for each authenticated system user.|
| ... | ... | ... | ... | ...|


### Console Output
```
Volatility Foundation Volatility Framework 2.6
Offset(V)  Name                    PID   PPID   Thds     Hnds   Sess                    
---------- -------------------- ------ ------ ------ -------- ------
0x823c89c8 System                    4      0     53      240 ------                                                              
0x822f1020 smss.exe                368      4      3       19 ------                                     
0x822a0598 csrss.exe               584    368      9      326      0                                    
0x82298700 winlogon.exe            608    368     23      519      0                                 
0x81e2ab28 services.exe            652    608     16      243      0                                     
0x81e2a3b8 lsass.exe               664    608     24      330      0                                    
0x82311360 svchost.exe             824    652     20      194      0                                    
0x81e29ab8 svchost.exe             908    652      9      226      0                                    
0x823001d0 svchost.exe            1004    652     64     1118      0                                    
0x821dfda0 svchost.exe            1056    652      5       60      0                                    
0x82295650 svchost.exe            1220    652     15      197      0                                   
0x821dea70 explorer.exe           1484   1464     17      415      0                                    
0x81eb17b8 spoolsv.exe            1512    652     14      113      0                                    
0x81e7bda0 reader_sl.exe          1640   1484      5       39      0                     
0x820e8da0 alg.exe                 788    652      7      104      0                                 
0x821fcda0 wuauclt.exe            1136   1004      8      173      0                                     
0x8205bda0 wuauclt.exe            1588   1004      5      132      0
```
