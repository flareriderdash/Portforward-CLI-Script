# Portforward-CLI-Script
A script that has the ability to add, delete ,  and list the current services with ports and ips on the router port forward table

This Script was built for and tested on the  Xfinity  TG1682G router with the http web server version  

eMTA & DOCSIS Software Version: 10.1.11.SIP.PC20.CT
Software Image Name: TG1682_2.7p6s2_PROD_sey
Advanced Services: TG1682G   #Model number
Packet Cable: 2.0 

You will most likey have to adapt this script to your router or this script may not even work for you
But this scirpt will save the hassle of having to go to the gateway and login. NOTE  youre credentials have to be
hardcoded into the script already urlencoded otherwise the script WILL NOT WORK. Although this can be easily adpated. THIS SCRIPT ASSUMES YOUR ROUTER DOES NOT HAVE
SSL/TLS CERTIFICATES. I do not know how to implement ssl/tls cert handling and probably will never add that. There is X-Csrf-Token 
capture and respond functions in this script to by pass any X-Csrf restrictions built into the web server. Happy forwarding!

P.S. I recommend putting it in your $PATH directory(s)
