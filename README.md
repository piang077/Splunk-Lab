Splunk SOC Lab – Hungry Hustle

This lab demonstrates practical use of Splunk for security monitoring, log analysis, and incident response. The goal was to investigate network activity, identify security incidents, and implement strategic security planning using the “hungryhustle” dataset.

Lab Activities
1. Log Analysis and Questions

Top 10 IPs for unauthorized access: Queried index="hungryhustle" and filtered for 403 Forbidden responses to identify frequent unauthorized attempts.

Country analysis: Used iplocation clientip to identify countries with the most unauthorized access.

Account monitoring: Investigated Sam Muller’s machine and discovered a private key (empe.ppk) leaked to another user.

Email and file analysis: Found evidence of sensitive file transfers (e.g., payslips and recipe files) and potential insider misuse.

Vulnerability detection: Identified a Cross-Site Scripting (XSS) vulnerability on the website.

Bandwidth & performance: Analysed Rick’s workstation to see high YouTube bandwidth consumption affecting performance.

Website downtime & maintenance: Calculated downtime and verified causes using HTTP status codes.

Customer activity: Determined the most visited food items using log extraction and statistics.

2. Strategic Security Planning

Developed an Incident Response Plan (IRP) for Hungry Hustle:

Preparation, Identification, Containment, Eradication, Recovery, Lessons Learned

Defined immediate and long-term actions to contain breaches, improve web application security, and implement threat monitoring.

3. Threat Intelligence

Collected and analysed internal logs and external threat feeds.

Developed rules and processes to detect attack patterns such as SQL injection, XSS, and credential stuffing.

Recommendations include continuous threat hunting, OSINT monitoring, and machine learning-based threat detection.

4. Dashboard Development

Created a Splunk dashboard with four panels:

Top 10 IPs generating 403 errors

Countries with most unauthorized attempts

Web downtime events

Rick’s top bandwidth usage

Dashboard enables real-time threat monitoring, incident response, and strategic decision-making.

Outcome

Demonstrated hands-on capability in Splunk for SOC operations.

Successfully analysed network traffic, user activity, vulnerabilities, and security incidents.

Applied knowledge in incident response, threat intelligence, and security dashboards for actionable insights.
