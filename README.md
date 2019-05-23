# wpa_decrypt



This script allows you to decrypt and sniff packets for a specific WPA2 network based on BSSID  you passed in input.

**Features :**

- Detect automatically the presence of monitor mode cards
- Detect all wireless cards in the system (less than when the script starts monitor mode cards are present)
- Possibility to choose the frequency (2.4 or 5GHz)
- Traffic filter by packets and/or host
- Capture all stations connected to specified AP
- Deauthentication of all stations or selected stations
- Capture station handshake 
- Sniff  traffic with tcpdump  and save it in a pcap file 

**Dependencies :**

- aircrack-ng
- dot11decrypt
- tcpdump

**Examples :**
	
	   wpa_decrypt -t BSSID+PSK -p http,pop3 -c -F

	   wpa_decrypt -t BSSID+PSK -p get,post  -v t192.168.1.1
	
	   Use -h options to get more information



**Before start the script you should capture information about BSSID and frequency(2.4 or 5) of the target AP. Airodump with --band option will help you.**
