# Cybersecurity Analyst

### Education
- M.S.c Industrial & Systems Engineering | North Carolina A&T State University (_Dec 2024_)

### Professional Certification
- Google Cybersecurity - 2025 
- AWS Certified Solutions Architect Associate - 2024 
- AWS Certified Cloud Practitioner - 2022
- CompTIA Security+- 2021

### Work Experience
**Cybersecurity Analyst @ Thomas Jefferson University Hospital (_May 2024 - Present_)**
- Conducted regular monitoring and analysis of network traffic, system logs, and SIEM alerts to identify potential threats and vulnerabilities in real-time
- Utilized intrusion detection, scanning tools, log collection, and other security-related systems to perform triage, investigation, and incident response
- Perform root cause analysis and recommend security improvements to prevent an incident recurrence
- Ensure the SOC team documentation is up to date, including investigation playbooks and Standard Operating Procedures (SOPs)
- Communicated effectively with internal teams and clients to provide timely and accurate incident reports.
- Performed daily monitoring of security consoles for potential hacking, malware, and malicious/suspicious activity on the external and internal corporate network using in-house solutions
- Planned for disaster recovery and created contingency plans in the event of any security breaches 
- Worked with different departments and stakeholders within an organization to draft and review security policies and processes 
- Identified potential weaknesses and implemented measures, such as firewalls, access gates, encryption, and general security hardening 
- Wrote powershell script to deploy several resources on azure 
- Used Terraform to deploy some virtual machines 
- Created several Private and Public VPCs and subnets for enterprise use. 
- Created IAM Roles and Policies in AWS 
- Configured Transit Gatway in AWS cloud
- Analyzed logs and alerts to identify and troubleshoot connectivity, performance and security issues
- Deployed and managed AWS WAF solution to protect web applications on application load balancer
- Configured cross-site scripting, SQL injection, Geographic match, ip address ACL rules to allow, block and monitor web requests.

**IT Operations Technician (Security Team) @ North Carolina A&T State University	(_Jan 2021 - Aug 2024_)**
- Participated in on-call rotation every 3 weeks
- Served as an escalation point for IPS/Cybersecurity issues within IST
- Demonstrated ability to document processes and procedures
- Troubleshoot firewall/access issues and resolve or escalate to proper operational teams
- Monitored network flows for network anomalies and access failure 
- Responded to tickets every day on ServiceNow to solve user 
- Installed updates, security patches, and software upgrades to keep systems secure and functional.
- Created, modified, and managed user accounts, permissions, and access control in IT systems.
- Orchestrated CI/CD pipelines for seamless integration of systems, ensuring secure and efficient software delivery
- Continuously monitored IT systems, servers, and networks to ensure uptime and optimal performance.
- I identified, analyzed, and resolved system failures, network outages, or security incidents.
- Maintained records of system configurations, incidents, and resolutions for future reference.
- Worked closely with system administrators, network engineers, and security teams to resolve technical challenges.
- Provided assistance to employees or customers by troubleshooting hardware, software, and network-related issues.
- Leveraged our AWS cloud platforms for deploying and managing financial applications with a focus on security and compliance.

**Linux System Administrator @ Perdue Farms (_Mar 2020 - Jun 2021_)**
- Installation, configuration, Linux (RedHat 7/8, CentOS, Debian, Ubuntu), UNIX, Windows, and Hardening of standalone Linux servers.
- Conducted regular audits of system logs to identify potential vulnerabilities or unauthorized activities within the IT environment.
- Led capacity planning efforts to anticipate future hardware requirements based on trends in resource usage, preventing bottlenecks in system performance down the line. 
- Monitored Linux server for CPU, Memory, and Disk utilization for system performance and assistance in implementing performance tuning. 
- Implemented security hardening measures on RHEL 7 servers by configuring firewalls, enabling SELinux, setting up user authentication, and applying security patches regularly. 
- Resolved a diverse range of technical issues across multiple systems and applications for customers and end-users across various time zones. 
- Assisted customers in identifying issues and explained solutions to restore service and functionality.
- Documented support interactions for future reference. 
- Collaborated with supervisors to escalate and address customer inquiries or technical issues. Installed and configured operating systems and applications. 
- Translated complex technical issues into digestible language for non-technical users.

## Projects
Project description
My organization is working to make their system more secure. It is my job to ensure the system is safe, investigate all potential security issues, and update employee computers as needed. The following steps provide examples of how I used SQL with filters to perform security-related tasks.
Retrieve after hours failed login attempts
There was a potential security incident that occurred after business hours (after 18:00). All after hours login attempts that failed need to be investigated.

The following code demonstrates how I created a SQL query to filter for failed login attempts that occurred after business hours.

 ![image](https://github.com/user-attachments/assets/522e7794-2485-4913-b325-24487205e39b)


The first part of the screenshot is my query, and the second part is a portion of the output. This query filters for failed login attempts that occurred after 18:00. First, I started by selecting all data from the log_in_attempts table. Then, I used a WHERE clause with an AND operator to filter my results to output only login attempts that occurred after 18:00 and were unsuccessful. The first condition is login_time > '18:00', which filters for the login attempts that occurred after 18:00. The second condition is success = FALSE, which filters for the failed login attempts. 
Retrieve login attempts on specific dates
A suspicious event occurred on 2022-05-09. Any login activity that happened on 2022-05-09 or on the day before needs to be investigated.

The following code demonstrates how I created a SQL query to filter for login attempts that occurred on specific dates.

 ![image](https://github.com/user-attachments/assets/697bb458-5b64-4c80-9c6d-2f8c7af2ebd0)


The first part of the screenshot is my query, and the second part is a portion of the output. This query returns all login attempts that occurred on 2022-05-09 or 2022-05-08. First, I started by selecting all data from the log_in_attempts table. Then, I used a WHERE clause with an OR operator to filter my results to output only login attempts that occurred on either 2022-05-09 or 2022-05-08. The first condition is login_date = '2022-05-09', which filters for logins on 2022-05-09. The second condition is login_date = '2022-05-08', which filters for logins on 2022-05-08.
Retrieve login attempts outside of Mexico
After investigating the organization’s data on login attempts, I believe there is an issue with the login attempts that occurred outside of Mexico. These login attempts should be investigated.

The following code demonstrates how I created a SQL query to filter for login attempts that occurred outside of Mexico. 

 ![image](https://github.com/user-attachments/assets/d179078b-f375-4c38-b7a2-50581389de84)


The first part of the screenshot is my query, and the second part is a portion of the output. This query returns all login attempts that occurred in countries other than Mexico. First, I started by selecting all data from the log_in_attempts table. Then, I used a WHERE clause with NOT to filter for countries other than Mexico. I used LIKE with MEX% as the pattern to match because the dataset represents Mexico as MEX and MEXICO. The percentage sign (%) represents any number of unspecified characters when used with LIKE. 
Retrieve employees in Marketing
My team wants to update the computers for certain employees in the Marketing department. To do this, I have to get information on which employee machines to update.

The following code demonstrates how I created a SQL query to filter for employee machines from employees in the Marketing department in the East building.

 ![image](https://github.com/user-attachments/assets/8a721b9f-60af-4f08-bf43-39e5881cf404)


The first part of the screenshot is my query, and the second part is a portion of the output. This query returns all employees in the Marketing department in the East building. First, I started by selecting all data from the employees table. Then, I used a WHERE clause with AND to filter for employees who work in the Marketing department and in the East building. I used LIKE with East% as the pattern to match because the data in the office column represents the East building with the specific office number. The first condition is the department = 'Marketing' portion, which filters for employees in the Marketing department. The second condition is the office LIKE 'East%' portion, which filters for employees in the East building.
Retrieve employees in Finance or Sales
The machines for employees in the Finance and Sales departments also need to be updated. Since a different security update is needed, I have to get information on employees only from these two departments.

The following code demonstrates how I created a SQL query to filter for employee machines from employees in the Finance or Sales departments.

 ![image](https://github.com/user-attachments/assets/55679068-4017-4461-851e-39b62f8c3aa7)


The first part of the screenshot is my query, and the second part is a portion of the output. This query returns all employees in the Finance and Sales departments. First, I started by selecting all data from the employees table. Then, I used a WHERE clause with OR to filter for employees who are in the Finance and Sales departments. I used the OR operator instead of AND because I want all employees who are in either department. The first condition is department = 'Finance', which filters for employees from the Finance department. The second condition is department = 'Sales', which filters for employees from the Sales department.
Retrieve all employees not in IT
My team needs to make one more security update on employees who are not in the Information Technology department. To make the update, I first have to get information on these employees.

The following demonstrates how I created a SQL query to filter for employee machines from employees not in the  Information Technology department.

 ![image](https://github.com/user-attachments/assets/26bfffcf-04f6-4e98-b8d8-0f823f18e661)


The first part of the screenshot is my query, and the second part is a portion of the output. The query returns all employees not in the Information Technology department. First, I started by selecting all data from the employees table. Then, I used a WHERE clause with NOT to filter for employees not in this department.
Summary
I applied filters to SQL queries to get specific information on login attempts and employee machines. I used two different tables, log_in_attempts and employees. I used the AND, OR, and NOT operators to filter for the specific information needed for each task. I also used LIKE and the percentage sign (%) wildcard to filter for patterns.





