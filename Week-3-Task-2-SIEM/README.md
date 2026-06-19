# Security Information and Event Management (SIEM) Systems

## Objective

The objective of this task is to understand how Security Information and Event Management (SIEM) systems collect, analyze, and correlate logs from multiple sources to detect security threats and support incident response.

---

# What is a SIEM?

A Security Information and Event Management (SIEM) system is a security platform that collects logs from various devices and applications, analyzes them, and generates alerts when suspicious activities are detected.

## Common SIEM Solutions

* Splunk
* Elastic Stack (ELK)
* IBM QRadar
* Microsoft Sentinel
* LogRhythm

---

# SIEM Architecture

## Log Sources

A SIEM can collect logs from:

* Windows Event Logs
* Linux System Logs
* Firewalls
* Web Servers
* Antivirus Software
* Network Devices

## Process

1. Logs are collected from multiple sources.
2. Logs are normalized into a common format.
3. Events are analyzed and correlated.
4. Alerts are generated when suspicious activity is detected.

---

# Sample SIEM Configuration

## Log Collection Configuration

### Windows Logs

* Security Events
* Login Events
* Account Management Events

### Linux Logs

* Authentication Logs
* System Logs
* SSH Access Logs

### Firewall Logs

* Blocked Connections
* Allowed Connections
* Port Scan Attempts

---

# Detection Rules and Alerts

## Rule 1: Multiple Failed Login Attempts

### Condition

More than 5 failed login attempts from the same IP address within 10 minutes.

### Alert

Possible brute-force attack detected.

### Severity

High

---

## Rule 2: Administrator Account Login Outside Business Hours

### Condition

Administrator account login between 11 PM and 6 AM.

### Alert

Unusual privileged account activity.

### Severity

Medium

---

## Rule 3: Port Scanning Activity

### Condition

Single IP address attempts connections to multiple ports in a short period.

### Alert

Potential reconnaissance activity detected.

### Severity

High

---

# Sample Log Analysis Observations

## Observation 1

Several failed login attempts were detected from a single IP address.

### Analysis

This may indicate a password guessing or brute-force attack.

---

## Observation 2

Repeated connections to multiple ports were observed.

### Analysis

This behavior resembles network scanning activity.

---

## Observation 3

Successful login after multiple failures.

### Analysis

Requires investigation to determine whether account compromise occurred.

---

# Benefits of SIEM

* Centralized log management
* Real-time monitoring
* Threat detection
* Incident investigation
* Compliance reporting

---

# Challenges of SIEM

* Large volume of logs
* False positive alerts
* Complex configuration
* Storage requirements

---

# Conclusion

SIEM systems play a critical role in modern cybersecurity operations by collecting and analyzing security events from multiple sources. Through log correlation and alerting, SIEM platforms help organizations detect threats, investigate incidents, and improve overall security visibility.

## Learning Outcome

Through this task, I learned how SIEM systems collect logs, how security alerts are generated, and how organizations use SIEM solutions to monitor and respond to cybersecurity threats.
