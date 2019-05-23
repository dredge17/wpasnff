# wpa_decrypt



This script allows you to decrypt packets for a specific WPA2 network.

Dependencies:

-aircrack-ng

-dot11decrypt

-tcpdump

-iw

Examples : 
	
	   wpa_decrypt -t BSSID+PSK -p http,pop3 -c -F

	   wpa_decrypt -t BSSID+PSK -p get,post  -v t192.168.1.1
	
	   Use -h options to get more information
