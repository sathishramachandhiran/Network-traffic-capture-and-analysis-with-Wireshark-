# Network-traffic-capture-and-analysis-with-Wireshark
## AIM:
To capture and analyze network packets using Wireshark, in order to inspect data flows, identify protocols, and detect any suspicious or unusual network behavior.

## DESIGN STEPS:
### Step 1:
Install Wireshark using the command:

### Step 2:
Launch Wireshark and select the appropriate network interface for live traffic capture.

### Step 3:
Start the capture, apply filters (like http, tcp, ip.addr == x.x.x.x) to analyze specific traffic, and stop the capture after observing relevant data.


## PROCEDURE:
1. Open Wireshark and Select a Network Interface
• Launch Wireshark.
• Select an active interface (like Wi-Fi or Ethernet) to start capturing packets.

2. Start Capturing Packets
• Click the blue shark fin icon or double-click the interface.
• Wireshark will start capturing all real-time traffic.

3. Apply Filters to Focus on Specific Traffic
• Use filters like http, ip.addr == 192.168.1.1, or tcp.port == 80 in the top filter
bar to narrow down results.

4. Analyze Packet Details
• Click on a packet to view its detailed breakdown including frame, Ethernet,
IP, TCP/UDP layers, and data payload.

5. Export or Save the Capture
• Go to File > Save As to store the capture in .pcap format for future analysis.

## OUTPUT:
**Open Wireshark and Select a Network Interface**
![image](https://github.com/user-attachments/assets/dcf5450e-53da-4786-a67b-d9311eb0f57e)

**Start Capturing Packets**
![image](https://github.com/user-attachments/assets/f5a06090-c04e-48fd-b2c8-10c427992e44)

**Apply Filters to Focus on Specific Traffic**

![image](https://github.com/user-attachments/assets/f715376e-7349-440c-8579-0d86fecb319e)

**Analyze Packet Details**
![image](https://github.com/user-attachments/assets/c3167485-765c-4dd6-8e47-78ac20500351)

![image](https://github.com/user-attachments/assets/208ea0ca-9675-4069-8253-e99759139327)


**Export or Save the Capture**
![image](https://github.com/user-attachments/assets/582f1b2c-bdcc-48a9-90e5-1659f17f48be)


## RESULT:
Wireshark was used to successfully capture and analyze real-time network traffic.

