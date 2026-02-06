--> what is a webpage?

# Servers
    web servers -> on that serves the web pages
    application servers -> hold the application base code
    Database servers --> holds a databse

# IP address is a unique address of the computer in the world

# protocols
    TCP protocol:

        TCP devlivers the data in the form of small packets you can see them in downloading a file 
        when there is no internet the download is paused but not restared this is bcz of TCP

        but it is slower due to checking of whether a packet is delivered or not

    UDP(Datagram control protocol):

        -> it is used to serve the live videos and online games bcz it is faster
        -> UDP is ony cares about sending the information but not cared about whether it is deelivered or not

URL -> uniform resource locator

# What Happens when you open an URL?
    1. Broweser look up for cache to see website is visted or not and IP address is known

    2.if not find the IP address then it ask ur OS to locate the website ,it checks for the address of url in host file
    if URL is not found then OS makes dns request to find IP address of webpage

    3. Then ISP server look up its cache to find IP address, if it si not found  then it asks TLD(top level domain)
    then it will see in its cache

    4. if not,it will have at least one of the authoritative name servers associated with that URL, and after going to the Name Server, it will return the IP Address associated with your URL.
    (it was done in milliseconds)

    5. Then os gives this ip address to the browser then it makes a HTTP get request and again request the os then i turn packs the requesst in the TCP traffic protocol and sent to the IP address

    6.on the way it is checked by both os and the servers frimwalll to check no security violations

    7. upon recieving the request teh server sends a response with IP address to teh choosen server along with SSL certificate to inititate the Secure connection

    8. Finally choosen server sends the HTML and CSS and JS files back to os Then OS gives it to the browser to interpret it
    and you get websites