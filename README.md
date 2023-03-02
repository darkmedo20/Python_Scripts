# Python_Scripts
penetration testing tools
#!/usr/bin/env python3
#Use these commands in Kali to install required software:
#  sudo apt install python3-pip
#  pip install python-nmap

# Import nmap so we can use it for the scan

# We need to create regular expressions to ensure that the input is correctly formatted.

# This port scanner uses the Python nmap module.
# You'll need to install the following to get it work on Linux:
# Step 1: sudo apt install python3-pip
# Step 2: pip install python-nmap

# You can scan 0-65535 ports. This scanner is basic and doesn't use multithreading so scanning 
    # all the ports is not advised.
# The result is quite interesting to look at. You may want to inspect the dictionary it returns. 
        # It contains what was sent to the command line in addition to the port status we're after. 
        # For in nmap for port 80 and ip 10.0.0.2 you'd run: nmap -oX - -p 89 -sV 10.0.0.2
