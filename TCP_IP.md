# Transmission control Protocol or Internet Protocol

![alt text](image-3.png)

# Types of TCP model

    Physical Layer:
        -> translates message bits into signals
        -> signals are generated based on the type of media used
        ex: light for optical fibers
        -> road in real life
        
    Data Link Layer(DLL):
        -> its all about moving the data safely between two devices which are connected
        -> traffic police in real life
        -> data is devided into frames(packet) using MAC layer and checks for errors
        -> LLC deals with flow and error control

    Network Layer:
        -> it adds IP address to the all divided segemnets and finds best possible path to deliver
        -> ARP is used to find the MAC from IP
        -> ICMP for error reporting

    Transport Layer:
        -> It handles the end to end communication between apllications
        -> data to segments

    Application Layer:
        it is combination of all the layers so the user interact with application and access network resources


# Application Layer protocols:
    HTTP(Hypertext Transfer Protocol): Protocol used to access data on the World Wide Web.
    DNS(Domain Name System): This protocol translates domain names to IP addresses.
    SMTP(Simple Mail Transfer Protocol): This protocol is used to send Email messages.
    FTP(File Transfer Protocol): This protocol is used to transfer files between computers.
    TELNET(Telecommunication Network): It is a two-way communication protocol connecting a local machine to a remote machine.