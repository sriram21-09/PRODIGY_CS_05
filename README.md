*Packet Sniffer Tool Using tcpdump and awk*

*Purpose*:
- This tool captures and analyzes network packets to display source and destination IP addresses, protocols, and payload data. 

*Key Components*:
- *tcpdump*: Command-line packet analyzer tool used to capture network packets.
- *awk*: Utility for pattern scanning and processing. Used here to extract and format relevant information from the packet capture.
- *trap and stop_capture*: Ensures graceful termination of the packet capture process when the user interrupts (e.g., pressing CTRL+C).

*How It Works*:
1. *Check for tcpdump*: Ensures tcpdump is installed.
2. *Capture Packets*: Uses tcpdump to capture network traffic, displaying data in a readable format.
3. *Logging*: Logs captured packets to a specified file (packet_log.txt).
4. *Handle Interrupt*: Gracefully stops the packet capture when interrupted.

*Usage*:
1. Make the script executable and run it with superuser privileges.
2. Capture network traffic, analyze and log it.
3. Terminate logging with CTRL+C.

*Ethics*:
Always use this tool on networks where you have explicit permission to monitor traffic. Unauthorized use can lead to legal consequences and breaches of privacy.
This tool provides a hands-on way to learn about network traffic and packet analysis, but remember to use it responsibly.
