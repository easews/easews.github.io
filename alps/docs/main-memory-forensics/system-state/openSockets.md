---
layout: default
title: Open Sockets
nav_order: 2
parent: System State
has_children: false
---

# Open Sockets
The **CONSOLE OUPUT** from [Volatility Framework](https://www.volatilityfoundation.org) is generated after executing the ```sockets``` plugin on the captured memory image.

### Console Output

```
Volatility Foundation Volatility Framework 2.6
Offset(V)       PID   Port  Proto Protocol        Address         
---------- -------- ------ ------ --------------- ---------------
0x81ddb780      664    500     17 UDP             0.0.0.0         
0x82240d08     1484   1038      6 TCP             0.0.0.0         
0x81dd7618     1220   1900     17 UDP             172.16.112.128  
0x82125610      788   1028      6 TCP             127.0.0.1       
0x8219cc08        4    445      6 TCP             0.0.0.0         
0x81ec23b0      908    135      6 TCP             0.0.0.0         
0x82276878        4    139      6 TCP             172.16.112.128  
0x82277460        4    137     17 UDP             172.16.112.128  
0x81e76620     1004    123     17 UDP             127.0.0.1       
0x82172808      664      0    255 Reserved        0.0.0.0         
0x81e3f460        4    138     17 UDP             172.16.112.128  
0x821f0630     1004    123     17 UDP             172.16.112.128  
0x822cd2b0     1220   1900     17 UDP             127.0.0.1       
0x82172c50      664   4500     17 UDP             0.0.0.0         
0x821f0d00        4    445     17 UDP             0.0.0.0    
```
