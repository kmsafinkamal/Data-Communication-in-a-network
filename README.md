1. Problem Statement
Three routers and three switches are available. I will design a network using these networking devices, 
proper wires and 6 PCs. PCs are indexed from 1 to 6. Adapt EIGRP as networking protocol in this case. 
Here, class C IP address will be used to assign all host address and network address. After completing the 
network, I will PING between 1no. PC from first router and 5no. PC from third router.
2. Design
In this network, the initial router connects to the second router, and the second router links to the third 
router via copper crossover cables. Each of these routers has a connected switch, and two PCs are connected 
to each switch using copper straight-through cables. All devices in this setup, including both host and 
network addresses, is assigned Class C IP addresses. In total, this design has five distinct networks.
2.2. Implementation 
In this project, I have used Cisco Packet Tracer (version 8.2.1.0118) to implement the design. The 
components or devices are used in this project is listed below. 
Components:
• Three PT routers
• Copper cross over cables
• Three 2950-24 Switches
• Straight Through Cables
• Six PCs
2.3. IP addresses
The design has total 5 networks. There are: 192.172.10.0; 192.172.20.0; 192.172.30.0; 192.172.40.0; and 
192.172.50.0. The table in the below showing IPs of the different interface in each router. 
3. Experimental Results
After doing the ping operation between PC1(192.172.10.10) from first router and PC5 (192.172.50.10) 
from third router, we can see that the ping is successful and there is 0% loss.
4. Conclusion
The network setup is fully configured, with all end devices, routers, and switches interconnected. Effective 
communication has been established among all devices throughout the network. As a successful test, we 
can confirm that PC1 can be pinged from the first router to the third router, including PC5.
