Task 4 – Firewall Configuration (Windows)
🔧 Objective
Configure Windows Defender Firewall to block and allow specific ports and understand how traffic is filtered.

🛠 Steps Performed
Opened Windows Defender Firewall > Advanced Settings
Created a new Inbound Rule to block port 23 (Telnet):
Protocol: TCP
Port: 23
Action: Block the connection
Enabled the rule for Domain, Private, and Public networks
Verified rule creation in the Inbound Rules list
Took screenshots for documentation
Deleted the rule to restore the original firewall state
📸 Screenshots
Screenshot of rule setup
Screenshot showing rule in the Inbound list
📚 Learnings
Learned how to block and allow specific ports
Understood how firewalls filter inbound traffic
