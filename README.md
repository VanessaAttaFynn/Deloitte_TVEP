# Deloitte Australia Technology Virtual Experience Program
![HEADER](https://github.com/VanessaAttaFynn/Deloitte_TVEP/blob/main/assets/Deloitte3.png)

## Table of Contents
<ul>
<a href = '#code'><li>Coding</li></a>
<a href = '#da'><li>Data Analysis</li></a>
<a href = '#dev'><li>Development</li></a>
<a href = '#cs'><li>Cyber Security</li></a>
<a href = '#ftech'><li>Forensic Technology</li></a>
</ul>



## Project Motivation
Cyber technology, forensic investigations, data analytics, platform engineering and code.
We designed this Virtual Experience Program to help you build the skills and confidence to pursue a career in STEM.
It comprises of 5 modules. See more info for program details [here](https://www.theforage.com/virtual-internships/prototype/YPWCiGNTkr6QxcpEu/Technology?ref=PksPiAxPT6YSn9ZYc)

## Tasks

<a id='code'></a>
<details>
<summary>Coding</summary>
<br>
We have signed a new account - Daikibo Industrials, a global leader in the manufacturing of heavy machinery, founded and headquartered in Tokyo, Japan. They needed assistance with a variety of problems and were impressed to find out Deloitte could help in all verticals.

Daikibo is in the process of integrating IIoT (Industrial Internet-of-Things) devices to monitor, measure and analyze their manufacturing processes. Half of their infrastructure uses devices streaming telemetry data in one format, and the other half - in another. They need your help to combine the two.
</details>

<a id='da'></a>
<details>
<summary>Data Analysis</summary>
<br>
Having your data unification algorithm, Daikibo's tech team has converted all telemetry data collected from the 4 factories of the company:

- Daikibo Factory Meiyo (Tokyo, Japan)
- Daikibo Factory Seiko (Osaka, Japan)
- Daikibo Berlin (Berlin, Germany)
- Daikibo Shenzhen (Shenzhen, China)
  
Each location has 9 types of machines, sending a message every 10 min. Daikibo has been collecting this data for 1 month (May 2021) and they've just shared this data in the form of a single JSON file.

The reason this client wanted to collect telemetry was to answer 2 questions:

- In which location did machines break the most?
- What are the machines that broke most often in that location?
  
The second task is to analyse the telemetry data collected by Daikibo (and unified with your algorithm) in a software called **Tableau**.
</details>

<a id='dev'></a>
<details>
<summary>Development</summary>
<br>
Analyzing offline data is great, but having a real-time overview of processes and smart alerts when things break is even better. Our client would like us to build a real-time manufacturing status dashboard. The first task of this process is drafting a development proposal.
  
Write a formal & informative, but short development proposal for the following project:

- Private dashboard with health status of the 9 machines in each of Daikibo's 4 factories, for which they collect telemetry.
- Access to the page happens only within client's Intranet.
- Authentication is synced to internal authentication server (users can leverage their company-wide accounts).
- The dashboard consists of a single page, listing the current statuses of all monitored devices.
- The view is collapsible/expandable at a factory level, as well as device level (showing history of statuses)
</details>

<a id='cs'></a>
<details>
<summary>Cyber Security</summary>
<br>
A big news publication has revealed sensitive private information of Daikibo Industrials' – a production problem has caused their assembly lines to stop, threatening the smooth operation of supply chains relying on Daikibo’s products. The client suspects the security of their new status board may have been breached.

In this task you will be joining our Cyber Security team. Your job is to:

- Determine if the alleged breach could have happened from an attacker on the Internet, directly (no access to Daikibo's VPN).
Hint: go back to the scope requirements of the status dashboard (previous task) and look for the answer there
  
- Inspect a web_requests.log file (listing only data from a period when the alleged attack has to have happened). Try to spot suspicious requests
 
If you've identified such requests - make sure to write down the id of the user (it's part of the requests)
  
Here is how the web_requests.log file is structured:

- There is a sequence of blocks of text, divided by an empty line
- Each block represents the activity of a unique IP address (no 2 blocks have the same IP)
- The block starts with the IP address followed by a table of the requests made to Daikibo's telemetry dashboard by the device with this IP address, sorted by time
- The IP addresses are from the internal Daikibo's network and are static
- 1 block can represent 1 or multiple browsing sessions
- Sessions made on different dates require new login
- There is **no continuous polling/pushing of data** between client & server - the users need to refresh the page to get the latest
</details>


<a id='ftech'></a>
<details>
<summary>Forensic Technology</summary>
<br>
After a worrisome number of internal complaints on gender inequality (in terms of pay), Daikibo Industrials wants us to help them investigate.

The Forensic Tech team has built an algorithm to quantify “level of gender pay equality” for most/all job roles within the company, in all company locations. Our Forensics lead thinks it will be a great welcoming task for you to finish the job.
  
We have processed all data on employee compensation and we've generated an excel file (Equality Table.xlsx, available in the Resources) containing 3 columns:

- Factory
- Job Role
- Equality Score (integer; ranging between -100 and +100; 0 is ideal)
  
Here is your final task:

Create a 4th column (Equality class), classifying the equality score in those 3 types:
- Fair (+-10)
- Unfair (<-10 AND >10)
- Highly Discriminative (<-20 AND >20)
  
</details>

  
[<kbd> <br> View Certification <br> </kbd>][Link]
  
[Link]: https://forage-uploads-prod.s3.amazonaws.com/completion-certificates/Deloitte%20Australia/YPWCiGNTkr6QxcpEu_Deloitte%20Australia_PksPiAxPT6YSn9ZYc_1667239142307_completion_certificate.pdf
