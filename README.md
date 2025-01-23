# CLOUD-MONITORING-AND-ALERTS

**COMPANY**: CODTECH IT SOLUTIONS

**NAME**: ADARSH VERMA

**INTERN ID**: CT6WGGP

**DOMAIN**: CLOUD COMPUTING 

**BATCH DURATION**: DECEMBER 25TH,2024 to FEBURARY 10TH,2025

**MENTOR NAME**: NEELA SANTOSH

**DESCRIPTION** 

This deliverable includes a comprehensive monitoring solution using AWS CloudWatch for a cloud-based application. The setup ensures real-time tracking of application performance, health, and operational insights. Below is a detailed description of what the deliverable entails:

1. Configured Alerts
   
Purpose: To notify the operations team when critical thresholds are breached or specific events occur in the application.

Features:
1.Alarms are configured for key metrics such as:
  a)Application Metrics: Request latency, error rates.
  b)Infrastructure Metrics: CPU utilization, memory usage, disk space.
2.Notifications are sent via Amazon SNS to predefined email addresses or SMS for immediate action.
3.Anomaly detection is enabled for selected metrics to identify unusual trends.

Example Alerts:
1.High CPU Utilization Alarm: Notifies when EC2 instance CPU usage exceeds 80% for 5 consecutive minutes.
2.Error Log Alarm: Triggers when the count of errors in application logs exceeds 5 occurrences in 10 minutes.
3.RDS Connection Threshold: Alerts when database connections surpass a defined limit.

2. CloudWatch Dashboard Showcasing Metrics
   
Purpose: To provide a centralized, real-time view of application and infrastructure metrics for monitoring and decision-making.
Features:
1.Custom dashboard displaying visualized metrics in an organized layout.
@ Widgets for:
a)Key Performance Indicators (KPIs):
b)CPU Utilization
c)Disk Reads/Writes
d)Request Count

@Logs Insights:
a)Error rates from application logs.
b)Alarm Status: Real-time view of active and resolved alarms.
c)Interactive widgets with adjustable time ranges for detailed analysis.

@Dashboard Example Layout:
a)Top Section: Overview of application health (e.g., request count, latency).
b)Middle Section: Infrastructure metrics (e.g., EC2 CPU utilization, RDS connections).
c)Bottom Section: Log insights and alarm statuses.

3. Log Monitoring
   
Purpose: To capture and analyze application logs for troubleshooting and trend analysis.
Features:
a)CloudWatch Logs is configured to collect logs from the application, such as errors or warnings.
b)Queries to filter and count specific log patterns, such as "ERROR" or "WARN" messages.
c)Logs are visualized in the dashboard and integrated with alarms for proactive alerts.


**OUTPUT**
![Image](https://github.com/user-attachments/assets/660c2820-384d-4e79-9182-9f2ce631ced2)
![Image](https://github.com/user-attachments/assets/ceef519d-1d5e-40a4-8bdd-286cdbbddee1)
