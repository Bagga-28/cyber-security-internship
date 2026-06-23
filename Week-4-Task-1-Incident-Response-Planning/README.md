# Malware Analysis Fundamentals

## Objective

The objective of this task is to understand the fundamentals of malware analysis, including malware classification, static analysis, dynamic analysis, and the identification of Indicators of Compromise (IOCs).

---

# Introduction to Malware

Malware is malicious software designed to damage, disrupt, or gain unauthorized access to computer systems.

## Common Types of Malware

* Virus
* Worm
* Trojan
* Ransomware
* Spyware
* Adware

---

# Malware Analysis Techniques

## Static Analysis

Static analysis involves examining a file without executing it.

### Activities

* Reviewing file properties
* Calculating hashes
* Examining strings
* Checking VirusTotal results

### Tools

* VirusTotal
* Ghidra
* PEStudio
* Strings Utility

---

## Dynamic Analysis

Dynamic analysis involves observing malware behavior in a controlled environment.

### Activities

* Monitoring processes
* Observing network activity
* Tracking file modifications
* Monitoring registry changes

### Tools

* Virtual Machine
* Process Monitor
* Wireshark

---

# Case Study: WannaCry Ransomware

## Overview

WannaCry was a ransomware campaign discovered in 2017 that affected organizations worldwide.

## Behavior

* Exploited a Windows vulnerability.
* Spread across networks automatically.
* Encrypted user files.
* Displayed a ransom demand.

## Impact

* Disrupted hospitals, businesses, and government organizations.
* Caused significant financial and operational damage.

---

# Indicators of Compromise (IOCs)

Indicators of Compromise are artifacts that help identify malicious activity.

## Common IOCs

### File Hashes

Unique values used to identify files.

Examples:

* MD5 Hash
* SHA-256 Hash

### Suspicious IP Addresses

Unexpected connections to unknown external servers.

### Domain Names

Malicious domains contacted by infected systems.

### File Names

Unexpected executable files appearing on systems.

### Registry Changes

Unauthorized modifications to system settings.

---

# Sample IOC Table

| IOC Type     | Example                            |
| ------------ | ---------------------------------- |
| File Hash    | SHA-256 Example Hash               |
| IP Address   | Suspicious External IP             |
| Domain       | Malicious Domain Example           |
| File Name    | Suspicious Executable              |
| Registry Key | Unauthorized Registry Modification |

---

# Analysis Summary

### Malware Type

Ransomware

### Primary Goal

Encrypt files and demand payment.

### Infection Method

Exploitation of software vulnerabilities and network propagation.

### Key Behaviors

* File encryption
* Network communication
* System modification

### Risk Level

High

---

# Best Practices for Malware Defense

* Keep systems updated.
* Use antivirus and endpoint protection.
* Perform regular backups.
* Restrict administrative privileges.
* Monitor system logs.
* Conduct security awareness training.

---

# Conclusion

Malware analysis helps security professionals understand malicious software behavior and identify indicators of compromise. Through static and dynamic analysis techniques, organizations can improve detection capabilities and strengthen their security posture.

## Learning Outcome

Through this task, I learned the basics of malware analysis, the differences between static and dynamic analysis, and how indicators of compromise can help identify and investigate malware infections.
