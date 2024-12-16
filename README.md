
# Intrusion Prevention System (IFS)

## Description

IFS (Intrusion-Prevention-System) is a network security solution created using Cisco Packet Tracer to simulate and prevent network intrusions in real-time. It leverages various network devices and configurations to monitor network traffic, detect malicious activities, and take proactive measures to secure the network infrastructure.

## Features
	•	Real-time Intrusion Detection and Prevention: Detects and blocks malicious activity in real-time using Cisco devices.
	•	Packet Filtering and Rules: Configurable rules to filter out potentially harmful network traffic.
	•	Network Traffic Simulation: Simulates network devices such as routers, switches, and firewalls for realistic intrusion detection.
	•	Alerting Mechanism: Logs and alerts for detected intrusions.
	•	Customizable Security Policies: Allows for the creation of custom security policies to address different types of attacks.

## Technologies Used
	•	Cisco Packet Tracer: A network simulation tool used to create the virtual network environment and simulate intrusion prevention.
	•	Network Devices: Routers, Switches, Firewalls, and PCs to set up the network infrastructure.
	•	Security Tools: Basic security configurations such as Access Control Lists (ACLs), port security, and firewall rules.

## Installation
	1.	Download Cisco Packet Tracer:
	•	You need Cisco Packet Tracer to open and run the .pkt file.
	•	You can download Cisco Packet Tracer from the Cisco Networking Academy website.
	2.	Clone the Repository:

git clone https://github.com/your-username/IFS-Intrusion-Prevention-System.git


	3.	Open the Project in Cisco Packet Tracer:
	•	Locate the IFS.pkt file in the project folder.
	•	Open the .pkt file in Cisco Packet Tracer to view and interact with the simulation.

## Usage
	1.	Start the Simulation:
	•	Open Cisco Packet Tracer and load the IFS.pkt file.
	•	Start the simulation by clicking the “Play” button in Cisco Packet Tracer.
	2.	Monitor Intrusions:
	•	Watch the real-time simulation of network traffic.
	•	The system will automatically detect and block malicious packets based on the configured rules.
	3.	View Logs and Alerts:
	•	Check the simulated device logs (e.g., router or firewall logs) for any detected intrusion attempts.

## Configuration
	•	The configuration is done directly within the Cisco Packet Tracer environment using the device configuration panels.
	•	Security rules are configured on devices such as routers and firewalls using ACLs, IP filtering, and other security features available in Packet Tracer.

Example Configuration (ACL)

On a router, an Access Control List (ACL) may look like this:

ip access-list extended BLOCK_SUSPECTED_TRAFFIC
 permit ip any host 192.168.1.100
 deny ip any any

This ACL blocks all traffic except for specific traffic that is allowed based on the defined rules.

## Contributing

Feel free to fork this repository and submit pull requests. If you’d like to add new features or improve the project, please discuss the changes by opening an issue first.


