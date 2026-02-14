# steps how a computer starts

BIOS/UEFI
Bootloader->GRUB->loads the operating system
kernal loading
initialization(init)
system and services initalization
user login

Deadlocks prevention:
    1 mututal exclusion
    2 hold and wait
    3 no preemptiom
    4 circular wait

resource allocation graph
cycle is necessary for deadlock but it is not necessary that if there is a cycle there is deadlock


strategies used by OS employees..
1. ignore the problem all together
2. deadlock prevention and avoidance
3. deadlock detection and recovery

Deadlock Avoidance:
![alt text](image-25.png)

bankers algorithm


deadlock recovery:

process and thread termination:
1. abort all deadlocked processes
2. abort one process at a time

resource preemption