# Network-Analyzer


The Network Analyzer is a tool designed to help users analyze and monitor network activity. Here's a brief overview of its usage and functions:


### Functions:

1. **Discover Devices**: The tool can scan the network using ARP to discover active hosts and gather information about them, such as IP addresses, MAC addresses, and vendor information.

2. **Analyze Traffic**: It can analyze network traffic patterns to identify devices on the network based on their communication patterns. This can help in understanding the roles of different devices.

3. **Detect Rogue Access Points**: The tool can detect rogue access points by comparing discovered access points against a list of known access points. It alerts if any unauthorized access points are found.

4. **Detect Rogue Devices**: It can also detect rogue devices by comparing discovered devices with a list of known devices. This helps in identifying devices that are not recognized as part of the network.

5. **Check for DNS Spoofing and Poisoning**: The tool can check for DNS spoofing and poisoning by comparing DNS query results with known legitimate IP addresses. It alerts if any discrepancies are found.

6. **Monitor Network for Suspicious Activity**: It can monitor the network for suspicious activity by analyzing packet patterns. This helps in detecting potential security threats or unusual behavior on the network.

Overall, the Network Analyzer provides a comprehensive set of tools for network analysis and monitoring, helping users to better understand and secure their networks.




**Contributing:**

Contributions, bug reports, and feature requests are welcome! Feel free to fork the repository, make your changes, and submit a pull request.



### Getting Started

Clone the repository.
    
    git clone https://github.com/kassam-99/Network-Analyzer.git


Install dependencies

    pip install -r requirements.txt


### Usage Examples


    cd Network-Analyzer

    python Analyzer.py
