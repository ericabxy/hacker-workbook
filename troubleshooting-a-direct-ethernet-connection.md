Troubleshooting a Direct Ethernet Connection
============================================

Enable Sharing IPv4 Settings
----------------------------

What does "Shared to other computer" mean?

Where can we change this setting?

- GNOME Wired Settings
- Settings on filesystem?
- Ways to do it on other computers? (Windows, Mac)


Find Ethernet Port IP Address
-----------------------------

    sudo ifconfig
    

Find Remote IP Address
----------------------

    nmap -sn 10.42.0.1/23


Connect to Remote Computer
--------------------------

    ssh username@10.42.0.120
