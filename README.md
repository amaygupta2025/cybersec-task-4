# cybersec-task-4

# Task 4: Setup and Use a Firewall on Windows/Linux

##  Objective

Configure and test basic firewall rules using **Windows Defender Firewall with Advanced Security** to block and allow specific network traffic.


##  Platform

- **Operating System**: Windows 10/11
- **Tool Used**: Windows Defender Firewall (wf.msc)


##  Steps Performed

1. Opened 'wf.msc' to access firewall settings.
2. Viewed and documented current **Inbound Rules**.
3. Created a new rule to **block inbound traffic on port 23 (Telnet)**.
4. Installed and used **Telnet Client** to test blocked connection.
5. Verified that Telnet was blocked (connection failed).
6. Removed the rule to restore original firewall state.


##  Firewall Concepts

- **Firewall**: A system that monitors and controls network traffic based on security rules.
- **Inbound Rule**: Controls traffic coming *into* your system.
- **Port 23 (Telnet)**: Insecure protocol, commonly blocked.
- **Why Block Port 23**: Telnet transmits data unencrypted, making it vulnerable to interception.


##  Screenshots

All screenshots are stored in the screenshots-task-4 folder:

inbound_rules_part1.jpg	:                       Initial list of inbound rules
inbound_rule_block_telnet_list.jpg:             New rule visible in the list
block_telnet_properties_general.jpg:          	General tab of the rule
block_telnet_properties_ports.jpg:            	Protocols and Ports tab showing port 23
telnet_test_blocked_port23.jpg:                 Telnet test showing connection failed
inbound_rules_after_removal.jpg:                Rules list after deleting the rule



##  Outcome

- Gained hands-on experience managing Windows Firewall rules.
- Understood how to inspect, create, test, and remove rules.
- Practiced network traffic filtering using port-level access control.
