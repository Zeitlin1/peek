# peek
# a simple python script for scanning open network ports

# useful for checking open network ports simply run the script from terminal using the command: 
$python3 peek.py

# This will bring up the prompt asking for an ip address:
"Enter a remote host to scan:" 

# Add whichever IP address you would like to scan.  Settings can be configured for which ports to scan, it defaults to the first 1024 (well known ports).
# You should see the following as ports are scanned:

------------------------------------------------------------
Please wait, scanning remote host 18.188.226.149
------------------------------------------------------------
Port 21: 	 Open
Port 22: 	 Open
Scanning Completed in:  0:03:11.519555

# To exit out of the scan early simply press CTRL+C
