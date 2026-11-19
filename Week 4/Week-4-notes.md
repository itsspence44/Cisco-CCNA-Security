
# Data and Tools for defense analysts 

--- 

**transaction**

- The transaction command is handy when you need to group related events together, based on a common field, or even a set of fields.


**First and Last**

- The "**first"** and "**last**" SPL commands are useful for analysts investigating an activity's first or last incidence
 

# Lookup command

- allows you to add data to Splunk, like a CSV file of known indicators, and then use that data to enhance your Splunk searches. 



# The Eval command

- can help you analyze and calculate results for mathematical, string, and boolean expressions.



# Risk analysis 
individuals conduct comprehensive analysis of  impacts of attacks on core company assets and functioning 


# Vulnerability assessments 
Patch management hosts scans, port scanning and any other vulnerability scans and services. 

# Penetration testing 
Use of hacking techniques and tools to penetrate network defenses and identify depth of potential penetration 
 

# Extra notes 
--- 

- **user=BruceGist**: This filters all events to those with a user of BruceGist. 

- **stats count by user dh:** The stats command with a count grouped by the user (Bruce) and the field dh (which is the destination host in this case).

- **sort -count:** The count is then sorted from largest to smallest 


# Tools for analysts 


- **Splunk Enterprise Security**

- **Splunk SOAR**

- **Wireshark/Tshark**

- **Tcpdump**

- **CyberChef**

# Database for Defense 

authentication data, network traffic proxy or gateway logs, and application, endpoint, or server logs. 


# Cyber Threat Intelligence 

**different specialized sources in the intelligence community or from internal ones, like the work you do as an analyst**.


Indicators of Compromise, Tactics, Techniques, and Procedures


NOT finding a match doesn't mean a threat is not lurking in an environment
