# Network Security Fundamentals: Firewalls and Intrusion Detection

## Objective

The objective of this task is to understand how firewalls, Intrusion Detection Systems (IDS), and Intrusion Prevention Systems (IPS) help protect computer networks from unauthorized access and cyber threats.

---

# Firewalls

A firewall is a network security device or software that monitors and controls incoming and outgoing network traffic based on predefined security rules.

## Types of Firewalls

### 1. Packet Filtering Firewall

Examines packets and allows or blocks them based on IP addresses, ports, and protocols.

**Uses:**

* Basic network protection
* Blocks unauthorized traffic

### 2. Stateful Inspection Firewall

Tracks active connections and makes decisions based on the state of network traffic.

**Uses:**

* More secure than packet filtering
* Monitors established sessions

### 3. Proxy Firewall

Acts as an intermediary between users and the internet.

**Uses:**

* Hides internal network details
* Filters web traffic

### 4. Next-Generation Firewall (NGFW)

Combines traditional firewall functions with advanced security features.

**Uses:**

* Deep packet inspection
* Application awareness
* Malware detection

---

# Intrusion Detection System (IDS)

An IDS monitors network traffic and system activities to detect suspicious behavior or security threats.

## How IDS Works

1. Monitors network traffic.
2. Compares activities against known attack signatures or behavior patterns.
3. Generates alerts when suspicious activity is detected.

### Advantages

* Detects attacks and unusual activity.
* Helps security teams investigate incidents.
* Provides visibility into network threats.

---

# Intrusion Prevention System (IPS)

An IPS not only detects threats but also takes action to stop them automatically.

## How IPS Works

1. Inspects network traffic.
2. Detects malicious activity.
3. Blocks or drops harmful traffic.
4. Prevents attacks from reaching systems.

### Advantages

* Real-time threat prevention.
* Automatic response to attacks.
* Improves overall network security.

---

# Difference Between IDS and IPS

| Feature          | IDS        | IPS               |
| ---------------- | ---------- | ----------------- |
| Detect Threats   | Yes        | Yes               |
| Generates Alerts | Yes        | Yes               |
| Blocks Attacks   | No         | Yes               |
| Position         | Monitoring | Inline Protection |

---

# Conclusion

Firewalls, IDS, and IPS are essential components of network security. Firewalls control network access, IDS detects suspicious activities, and IPS actively blocks threats. Together, they help protect organizations from cyber attacks and unauthorized access.

## Learning Outcome

Through this task, I learned the different types of firewalls, how IDS and IPS function, and their importance in securing modern computer networks.
