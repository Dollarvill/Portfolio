## Cybersecurity Analyst
Cybersecurity Specialist with a strong foundation in threat detection, incident response, and cloud security. Proficient in SIEM tools, IDS/IPS, and compliance frameworks (NIST, SOC, ISO 27001) to safeguard enterprise networks. Experienced in log analysis, vulnerability assessments, and security automation using Python and PowerShell. Skilled in securing cloud environments (AWS, Azure, GCP) through IAM policies, network segmentation, and WAF solutions. Adept at collaborating with cross-functional teams to develop and implement security policies, mitigate risks, and enhance system resilience. Committed to continuous learning and innovation in cybersecurity

### Education
- M.S.c Industrial & Systems Engineering | North Carolina A&T State University (_Dec 2024_)

### Professional Certification
- Google Cybersecurity - 2025 
- AWS Certified Solutions Architect Associate - 2024 
- AWS Certified Cloud Practitioner - 2022
- CompTIA Security+- 2021

### Skills Summary
Python | SQL | Siem Tools | IDSP/IPS | Network Security | Information Security | NIST - Cybersecurity Framework | Operating Systems | Cloud Computing |Infrastructure as Code | Configuration Management | Azure | AWS| GCP | Problem-Solving | Collaboration & Communication | Containerization & Orchestration | Version Control | Networking & Security | Monitoring |, Databases & Storage | Logging Adaptability | Continuous Learning | Project Management | IT Support Tools | Scripting & Automation | DEVOPS Tools |

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
**Update a file through a Python algorithm
Project description
At my organization, access to restricted content is controlled with an allow list of IP addresses. The "allow_list.txt" file identifies these IP addresses. A separate remove list identifies IP addresses that should no longer have access to this content. I created an algorithm to automate updating the "allow_list.txt" file and remove these IP addresses that should no longer have access. 
Open the file that contains the allow list
For the first part of the algorithm, I opened the "allow_list.txt" file. First, I assigned this file name as a string to the import_file variable:
 ![image](https://github.com/user-attachments/assets/582163d2-fdb6-4689-8adf-797abf5ca498)

Then, I used a with statement to open the file:

  ![image](https://github.com/user-attachments/assets/1faaffd2-2a45-4d76-bfae-71110c9c99d1)

In my algorithm, the with statement is used with the .open() function in read mode to open the allow list file for the purpose of reading it. The purpose of opening the file is to allow me to access the IP addresses stored in the allow list file. The with keyword will help manage the resources by closing the file after exiting the with statement. In the code with open(import_file, "r") as file:, the open() function has two parameters. The first identifies the file to import, and then the second indicates what I want to do with the file. In this case, "r" indicates that I want to read it. The code also uses the as keyword to assign a variable named file; file stores the output of the .open() function while I work within the with statement.

Read the file contents
In order to read the file contents, I used the .read() method to convert it into the string.

 ![image](https://github.com/user-attachments/assets/db6121af-f4fc-4ac3-a414-60d5dd0faf14)


When using an .open() function that includes the argument "r" for “read,” I can call the .read() function in the body of the with statement. The .read() method converts the file into a string and allows me to read it. I applied the .read() method to the file variable identified in the with statement. Then, I assigned the string output of this method to the variable ip_addresses. 

In summary, this code reads the contents of the "allow_list.txt" file into a string format that allows me to later use the string to organize and extract data in my Python program.
Convert the string into a list
In order to remove individual IP addresses from the allow list, I needed it to be in list format. Therefore, I next used the .split() method to convert the ip_addresses string into a list:

 ![image](https://github.com/user-attachments/assets/68615d1d-a536-419f-89ad-8425c7768d1f)


The .split() function is called by appending it to a string variable. It works by converting the contents of a string to a list. The purpose of splitting ip_addresses into a list is to make it easier to remove IP addresses from the allow list. By default, the .split() function splits the text by whitespace into list elements. In this algorithm, the .split() function takes the data stored in the variable ip_addresses, which is a string of IP addresses that are each separated by a whitespace, and it converts this string into a list of IP addresses. To store this list, I reassigned it back to the variable ip_addresses. 
Iterate through the remove list
A key part of my algorithm involves iterating through the IP addresses that are elements in the remove_list. To do this, I incorporated a for loop:

 ![image](https://github.com/user-attachments/assets/8c97b4be-957d-4a64-82d6-dd945fa3ae97)


The for loop in Python repeats code for a specified sequence. The overall purpose of the for loop in a Python algorithm like this is to apply specific code statements to all elements in a sequence. The for keyword starts the for loop. It is followed by the loop variable element and the keyword in. The keyword in indicates to iterate through the sequence ip_addresses and assign each value to the loop variable element. 
Remove IP addresses that are on the remove list
My algorithm requires removing any IP address from the allow list, ip_addresses, that is also contained in remove_list.  Because there were not any duplicates in ip_addresses, I was able to use the following code to do this:

 ![image](https://github.com/user-attachments/assets/f4dd6ae0-3252-47b9-8874-831513f41128)

First, within my for loop, I created a conditional that evaluated whether or not the loop variable element was found in the ip_addresses list. I did this because applying .remove() to elements that were not found in ip_addresses would result in an error. 

Then, within that conditional, I applied .remove() to ip_addresses. I passed in the loop variable element as the argument so that each IP address that was in the remove_list would be removed from ip_addresses.

![image](https://github.com/user-attachments/assets/f4c917ec-119d-4775-98ad-58c53379786b)

Update the file with the revised list of IP addresses 
As a final step in my algorithm, I needed to update the allow list file with the revised list of IP addresses. To do so, I first needed to convert the list back into a string. I used the .join() method for this:

![image](https://github.com/user-attachments/assets/254e2663-9c6e-4ab4-89dd-f202d07d9bf8)
 
The .join() method combines all items in an iterable into a string. The .join() method is applied to a string containing characters that will separate the elements in the iterable once joined into a string. In this algorithm, I used the .join() method to create a string from the list ip_addresses so that I could pass it in as an argument to the .write() method when writing to the file "allow_list.txt". I used the string ("\n") as the separator to instruct Python to place each element on a new line. 

Then, I used another with statement and the .write() method to update the file:

 ![image](https://github.com/user-attachments/assets/813f0a63-9536-4790-b71d-078bd79baaf4)

This time, I used a second argument of "w" with the open() function in my with statement. This argument indicates that I want to open a file to write over its contents. When using this argument "w", I can call the .write() function in the body of the with statement. The .write() function writes string data to a specified file and replaces any existing file content. 
In this case I wanted to write the updated allow list as a string to the file "allow_list.txt". This way, the restricted content will no longer be accessible to any IP addresses that were removed from the allow list. To rewrite the file, I appended the .write() function to the file object file that I identified in the with statement. I passed in the ip_addresses variable as the argument to specify that the contents of the file specified in the with statement should be replaced with the data in this variable.
Summary
I created an algorithm that removes IP addresses identified in a remove_list variable from the "allow_list.txt" file of approved IP addresses. This algorithm involved opening the file, converting it to a string to be read, and then converting this string to a list stored in the variable ip_addresses. I then iterated through the IP addresses in remove_list. With each iteration, I evaluated if the element was part of the ip_addresses list. If it was, I applied the .remove() method to it to remove the element from ip_addresses.. After this, I used the .join() method to convert the ip_addresses back into a string so that I could write over the contents of the "allow_list.txt" file with the revised list of IP addresses.


**2. File permissions in Linux
Project description
The research team at my organization needs to update the file permissions for certain files and directories within the projects directory. The permissions do not currently reflect the level of authorization that should be given. Checking and updating these permissions will help keep their system secure. To complete this task, I performed the following tasks:

Check file and directory details
The following code demonstrates how I used Linux commands to determine the existing permissions set for a specific directory in the file system.

 ![image](https://github.com/user-attachments/assets/553c7e23-49a8-42c3-8940-b8810791917b)

The first line of the screenshot displays the command I entered, and the other lines display the output. The code lists all contents of the projects directory. I used the ls command with the -la option to display a detailed listing of the file contents that also returned hidden files. The output of my command indicates that there is one directory named drafts, one hidden file named .project_x.txt, and five other project files. The 10-character string in the first column represents the permissions set on each file or directory.
Change file permissions on a hidden file
The research team at my organization recently archived project_x.txt. They do not want anyone to have write access to this project, but the user and group should have read access. 

The following code demonstrates how I used Linux commands to change the permissions:

 ![image](https://github.com/user-attachments/assets/b2ffd23d-33ea-4887-9375-ea848bceaeef)

The first two lines of the screenshot display the commands I entered, and the other lines display the output of the second command. I know .project_x.txt is a hidden file because it starts with a period (.). In this example, I removed write permissions from the user and group, and added read permissions to the group. I removed write permissions from the user with u-w. Then, I removed write permissions from the group with g-w, and added read permissions to the group with g+r. 
Change directory permissions
My organization only wants the researcher2 user to have access to the drafts directory and its contents. This means that no one other than researcher2 should have execute permissions.

The following code demonstrates how I used Linux commands to change the permissions:

 ![image](https://github.com/user-attachments/assets/d3b4512a-f06d-4f66-95f9-cd5dc6cd1735)

The first two lines of the screenshot display the commands I entered, and the other lines display the output of the second command. I previously determined that the group had execute permissions, so I used the chmod command to remove them. The researcher2 user already had execute permissions, so they did not need to be added.
Summary
I changed multiple permissions to match the level of authorization my organization wanted for files and directories in the projects directory. The first step in this was using ls -la to check the permissions for the directory. This informed my decisions in the following steps. I then used the chmod command multiple times to change the permissions on files and directories.

**3. Applying filters to SQL queries to get specific information on login attempts and employee machines
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





