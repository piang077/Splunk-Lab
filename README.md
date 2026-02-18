# Splunk SOC Lab 
# Overview

This lab simulates a security operations centre (SOC) investigation for a fictional company, Hungry Hustle. The objective is to analyse web traffic, employee activity, and network logs to detect suspicious behaviour, investigate potential security incidents, and implement strategic security measures. All analysis follows standard SOC procedures and best practices, ensuring findings are well-documented and structured.

**The lab focuses on:**

Identifying unauthorized access attempts to the company website

Analysing employee actions and data transfers

Investigating website vulnerabilities and downtime

Applying strategic security planning and threat intelligence

Developing a dashboard for monitoring security events

# Investigation Tasks

**Unauthorized Access Analysis**
: Analysed HTTP GET requests and 403 Forbidden responses to identify the top 10 IP addresses responsible for unauthorized access.

**Geolocation Analysis**
: Used IP addresses to determine which countries had the most unauthorized access attempts.

**Account Monitoring**
: Investigated Sam Muller’s account for leaks. Discovered a private key file (empe.ppk) sent externally.

**Email and File Transfers**
: Identified suspicious file transfers, including sensitive documents sent to unintended recipients.

**Vulnerability Detection**
: Detected a Cross-Site Scripting (XSS) vulnerability on the website that allowed external data exfiltration.

**Bandwidth and Performance Analysis**
: Examined Rick’s workstation activity and identified high non-work-related bandwidth usage affecting performance.

**Website Downtime and Maintenance**
: Calculated downtime and determined causes using HTTP status codes (503 Service Unavailable).

**Customer Activity**
: Analysed product search logs to determine the most frequently visited food items.

**Strategic Security Planning**

- Developed an Incident Response Plan (IRP) for Hungry Hustle covering:

- Preparation, Identification, Containment, Eradication, Recovery, Lessons Learned

**Recommended immediate and long-term actions for:**

- Containing breaches and data leaks

- Improving web application security

- Implementing monitoring, alerting, and threat intelligence

# Dashboard Overview

The lab includes a Splunk dashboard providing real-time security monitoring:

**Top 10 IPs generating 403 Forbidden errors**

**Countries with the most unauthorized access attempts**

**Website downtime incidents**

**Employee bandwidth consumption**

The dashboard supports proactive threat detection, incident response, and data-driven decision-making.

# [Full Report](Splunk-For-Security-Monitoring.pdf) – Detailed investigation, methodology, and supporting screenshots

# Outcome

- Applied hands-on Splunk skills for SOC operations

- Investigated unauthorized access, data leaks, and website vulnerabilities

- Developed structured documentation and dashboards suitable for professional reporting
