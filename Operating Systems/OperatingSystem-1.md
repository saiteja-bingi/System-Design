user--->Application---->Operating System---->Hardware 
![alt text](image.png)

everything will interact with the OS to get output via output devices

OS most important piece of software
OS is the schema , it is implemented by others(windows by microsoft)

code->excutable binary-->OS(Process Manager)-->Kernal Space,Memory

something is running inside computer is called processes
OS open the kernal space using Dispatcher and send it to the CPU

OS has Bunch of other programs which interacts with applications and interacts with CPU and hardware (all these stuff)

![alt text](image-1.png)

OS itself also loads first when Computer is turned on
bootloader-->loasds the OS and its kernal

# process control block (PCB) contains
    1. process ID (unique id for program)
    2. Process State (whether program is running or closed)
    3. Program counter
    4. Registers-->(helps to snapshot of apps like when you have pausing an app and opening it again to use(resume) )
    5. Memory Limits(RAM is like a big array stores the limits of index (l,r) of the program that is running)
    6. List of Open Files (opens required files before running a program)


![alt text](image-2.png)
1. text--> Code segment (code is stored) (machine code)
2. data---> constant or global variables are stored 
3. heap-->malloc ,realloc operations
4. stack--> functions and local variables

when total memory is used -->stack overflow
local variabels are limited than global ones

memory->{
    {
        kernal space->{ memory parts}
    }
}
# content Switching
when a program is ruuning and another program is opened the previous program is taken as a snapshot and closed temporarily inside kernal space(PCB) and the new program is opened
(user friendly multitasking)

states of process?
1. Ready
2. Running


PCB
![alt text](image-3.png)

new->ready->running->{wait/block}->terminated

suspend==swap the program into harddisk from ram

![alt text](image-4.png)