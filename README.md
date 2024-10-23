**Packet Sniffer Tool (Python & Scapy)**

This Python-based packet sniffer leverages the power of the Scapy library to capture and analyze network traffic at Layer 3 (IP layer). It provides key insights into network data by displaying source and destination IP addresses, ports, protocols (TCP/UDP), and raw packet payloads in both hexadecimal and ASCII formats. The tool is designed for educational purposes and works without requiring Npcap on Windows by using Layer 3 sockets.

**Key Features**:
- Captures and analyzes TCP/UDP network traffic in real-time.
- Displays source and destination IP addresses, along with protocol-specific details.
- Extracts and decodes raw packet payloads into both hex and ASCII formats for deeper analysis.
- Customizable packet filtering options to focus on specific traffic (e.g., TCP only).
- Works without Npcap on Windows by utilizing Layer 3 sockets, making it easy to run on most systems.

**Usage**:
This tool is ideal for those learning about network traffic, cybersecurity, or anyone needing to analyze network data for educational purposes. Ensure that packet capturing is performed ethically and with permission, as this tool can access live network traffic.

**How to Use**:
1. Install the required libraries: `pip install scapy`
2. Run the script with administrative privileges to capture network traffic.
3. Modify the script to filter specific protocols or ports if needed.

