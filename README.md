# PRODIGY_CS_05
As part of my cybersecurity internship at Prodigy InfoTech, 
I developed a simple packet sniffing tool using Python and the `scapy` library. 
This tool captures network packets, but due to ethical and privacy considerations, certain limitations are applied. 
By default, it captures only TCP packets, but this can be modified to capture all packets by changing the filter. 
The program is set to capture 10 packets unless manually adjusted or set to run indefinitely. 
Captured packet details are saved in `packet_sniffer_results.txt`. 
Running the script may require superuser or administrator privileges. 
I tested it on my Kali Linux virtual machine, where superuser access was necessary.
