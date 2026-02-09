# operating Systems

operating system software manages computer hardware ,software resources and provides common services
so it manages computers memory,processes,devices,files and security aspects

# Socket

socket is a OS level communication endpoint
it is used to send and recieve data between to programs

ex: consider a phone call
    phone number=IP address+port
    phone=SOCKET
    call = connection

defination:
    A software endpoint created by the operating system that allows processes to communicate over a network or within the same machine.

types of socktes: TCP,UDP (we discussed)
think about zoom meeting link--->click--->browser--->redirects to app

# Kernal

what we can say about kernal , it is core part of the operating systems think baout linux kernal it is its heart
it manages communication between the os and user applications
manages memory and cpu time ,controls disk, task management

# Monolithic Kernal
it is same as kernal but all important OS services run inside kernal space
All of them are:
    In one big kernel
    Running in kernel mode
    Calling each other directly

like extension of kernal eith fats I/O operations and it is very fast

it is a very complex code

# process ,Program and Thread
    process:
        insatnce of a program
        code--->excutes-->(become process) perform all tasks in it
    Program:
        set of instructions to perform a task
        eg: chrome.exe
    Thread:
        it is a lightweight process
        parallelism ----> dividing the process into multiple threads
    
# Virtual Memory
    -> used as a extension of the physical memory
    -> 
