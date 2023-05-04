---
layout: default
title: Process Tree
nav_order: 2
parent: System State
has_children: false
---

# Process Tree Activity Sheet
Learners are to complete the following:

1. Consider the **CONSOLE OUPUT** from [Volatility Framework](https://www.volatilityfoundation.org) below after executing the ```pstree``` plugin on the captured memory image.

2. Remain in pairs from prior activity. Pairs have **15** minutes to document the relationships between the processes. The instructor will issue a **ONE** minute warning when time is nearly elapsed.

3. Use the scissors to segment the **VISUAL MAP ELEMENTS**. Use the elements to visualise the processes in terms of parent and child relationships.

### Visual Map Elements
The following elements can be used to visualise the relationship between the different processes.

| Description | Image |
| - | - |
| Running Process |![image](resources/process_4.png) |
| Running Process |![image](resources/process_368.png) |
| Running Process |![image](resources/process_608.png) |
| Running Process |![image](resources/process_652.png) |
| Running Process |![image](resources/process_1056.png) |
| Running Process |![image](resources/process_1512.png) |
| Running Process |![image](resources/process_908.png) |
| Running Process |![image](resources/process_1004.png) |
| Running Process |![image](resources/process_1588.png) |
| Running Process |![image](resources/process_1136.png) |
| Running Process |![image](resources/process_824.png) |
| Running Process |![image](resources/process_788.png) |
| Running Process |![image](resources/process_1220.png) |
| Running Process |![image](resources/process_664.png) |
| Running Process |![image](resources/process_584.png) |
| Running Process |![image](resources/process_1484.png) |
| Running Process |![image](resources/process_1640.png) |
| Parent Process |![image](resources/parent_process_0.png) |
| Parent Process |![image](resources/parent_process_4.png) |
| Parent Process |![image](resources/parent_process_368.png)![image](resources/parent_process_368.png) |
| Parent Process |![image](resources/parent_process_608.png) ![image](resources/parent_process_608.png)|
| Parent Process |![image](resources/parent_process_652.png)![image](resources/parent_process_652.png)![image](resources/parent_process_652.png)![image](resources/parent_process_652.png)![image](resources/parent_process_652.png)![image](resources/parent_process_652.png)![image](resources/parent_process_652.png)|
| Parent Process |![image](resources/parent_process_1004.png) ![image](resources/parent_process_1004.png)|
| Parent Process |![image](resources/parent_process_1464.png) |
| Parent Process |![image](resources/parent_process_1484.png) |
| Arrow |![image](resources/arrow.png)![image](resources/arrow.png)![image](resources/arrow.png)![image](resources/arrow.png)![image](resources/arrow.png) ![image](resources/arrow.png)![image](resources/arrow.png)![image](resources/arrow.png)![image](resources/arrow.png)![image](resources/arrow.png) ![image](resources/arrow.png)![image](resources/arrow.png)![image](resources/arrow.png)![image](resources/arrow.png)![image](resources/arrow.png) ![image](resources/arrow.png)![image](resources/arrow.png)![image](resources/arrow.png)![image](resources/arrow.png)![image](resources/arrow.png) |




### Console Output
```
Volatility Foundation Volatility Framework 2.6
Name                                                  Pid   PPid
-------------------------------------------------- ------ ------
 0x823c89c8:System                                      4      0     
. 0x822f1020:smss.exe                                 368      4      
.. 0x82298700:winlogon.exe                            608    368     
... 0x81e2ab28:services.exe                           652    608     
.... 0x821dfda0:svchost.exe                          1056    652      
.... 0x81eb17b8:spoolsv.exe                          1512    652     
.... 0x81e29ab8:svchost.exe                           908    652      
.... 0x823001d0:svchost.exe                          1004    652     
..... 0x8205bda0:wuauclt.exe                         1588   1004      
..... 0x821fcda0:wuauclt.exe                         1136   1004      
.... 0x82311360:svchost.exe                           824    652     
.... 0x820e8da0:alg.exe                               788    652      
.... 0x82295650:svchost.exe                          1220    652     
... 0x81e2a3b8:lsass.exe                              664    608     
.. 0x822a0598:csrss.exe                               584    368      
 0x821dea70:explorer.exe                             1484   1464     
. 0x81e7bda0:reader_sl.exe                           1640   1484  
```

### Materials
* Scissors
