Here,we have the linux commands to montior the health of the system and commands like rev,factor,yes,sl.

PROGRAM1:After executing program1.sh, package sl will be installed.sl command is a fun command.In the terminal a train structure will be moving.

PROGRAM2:In this file commands like rev,factor and yes are there.download and execute this file.
rev-reverse the input you have entered.eg:blessy output will be ysselb
factor-this command gives the factor of the numbers.if you enter any number it will show its factors as output.
yes-y will be printed continuously as an endless loop.

labhealth.sh:This file will help you to monitor the health of your computer.If you give the permission to access the .sh file the output of the this file will be updated in the vmstat1.data file which we create.

the vmstat 1200 – monitors every 24 hours and puts the data into the vmstat1.data.you can change the time to 2 days or one week anything.

grep “swap”- Actually the swap should always return zero,incase if its not zero, then some process has consumed massive memory. That will be monitored in this line

grep “r”- the running queue is constantly above process 1 it indicates the system is slow and some process is waiting to be executed. That will be monitored here.

Grep “cpu”- it indicates the cpu usage of the system. If the cpu usage is more it will be monitored and will alert in this line.
