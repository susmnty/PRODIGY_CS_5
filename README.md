# PRODIGY_CS_5
Network Packet Analyzer


This Python packet sniffer captures and analyzes network packets using the scapy library. The script defines a function 'packet_callback' that processes each packet, extracting and printing the source and destination IP addresses, protocol number, and payload data. It checks for IP, TCP, and UDP layers in the packets and prints relevant details such as source and destination ports for TCP and UDP packets. The sniff function is used to start capturing IP packets and calls packet_callback to handle each packet, displaying the information in real-time. To run this script, save it as 'packet_sniffer.py' and execute it with administrative privileges. 

Instruction to use the code -

 1. Run the pip install first so that it collects its files.
 2. Then Run the main code.

Notice - You can use Jupyter Notebook for better clear results.
