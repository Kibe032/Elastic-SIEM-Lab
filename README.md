Elasric SIEM Lab

## Objective


For the Simple Elastic SIEM Lab project I aimed to establish a home lab environment for setting up and utilizing Elastic Stack for Security Information and Event Management (SIEM). The primary focus was to ingest and analyze security-related events generated from a Kali Linux VM, forwarding this data to the Elastic SIEM for monitoring and querying. This hands-on experience deepened my understanding of security event analysis, log management, and the operational capabilities of SIEM systems in detecting and responding to security incidents.

### Skills Learned


- Advanced understanding of SIEM concepts and practical application.
- Experience in configuring and maanaging Elastic stack for security monotoring.
- Proficiency in analyzing and interpreting network logs.
- Familiarity with using virtualiztion software(VirtualBox/VMware) for setting up lab environments.
- Ability to generate and recognize attack signatures and patterns.
- Creating visualizations and dashboards to monitor security events.
- Querying and analyzing logs in Elastic SIEM

### Tools Used


- Elastic stack (Elastic SIEM): for security and event management.
- Kali Linux: A penetration testing and ethical hacking linux distribution.
- Virtualization software: used both VirtualBox and VMware to set up Kali Linux virtual machine.
- Elastic Agents: deployed the agents to collect and foward logs from Kali VM to Elastic siem.
- N-map: to generate security events and scan the network identifying vulnerabilities.

## Steps
Set Up an Elastic Account:

Created a free account on Elastic Cloud.
Logged into the Elastic Cloud console and created a new Elasticsearch deployment.

Setting Up the Linux VM:
Downloaded the Kali Linux VM image.
Set up the Kali VM using VirtualBox or VMware.
Installed and logged into Kali Linux.

Setting Up the Agent to Collect Logs:
Navigated to the Integrations page in the Elastic SIEM.
Installed the Elastic Agent on the Kali VM and verified the installation.

Generating Security Events on the Kali VM:
Installed Nmap (if not pre-installed) and executed various Nmap scans to generate security-related events.

Querying for Security Events in the Elastic SIEM:
Accessed the logs section in the Elastic SIEM.
Executed search queries to filter and analyze logs related to Nmap scans.

Creating a Dashboard to Visualize Events:
Created a new dashboard and added visualizations to display security events over time.

Creating an Alert:
Set up a custom alert in the Elastic SIEM to detect Nmap scan events and defined the notification actions.
