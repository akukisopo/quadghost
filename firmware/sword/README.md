sword
=====

SWORD: A GUI for zer0byte's DropBox
===================================
* * *
NOTE: The initial repository was missing and the stolen clones around the net had inaccurate information. I had to recreate this repository from the only know zip file I could find. The commit history is gone because of these events. If you can find a correct repository with the history incact I will update it here.
* * * 

Misc notes I found that supposedly went with this repository. They do make sense and will be left.

##HOW TO INSTALL
1. Extract these files /www directory of your router
2. Make sure you have bash installed on your router otherwise the scripts wont work (opkg update; opkg install bash –force-depends)‏
3. Give 655 to the /cgi-bin directory (chmod -R 655 /www/cgi-bin/*
4. When done simply navigate to it by typing “yourrouterip/SWORD” in your web browser (192.168.1.1/SWORD)

####Pre- Reqs
Make sure you have aircrack-ng, ettercap-ng , reaver, tcpdump, urlsnarf, ettercap, nmap , mk3 installed on your router using opkg install <<tool>>.