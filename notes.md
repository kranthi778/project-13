# Project 13 – Evading IDS, Firewalls and Honeypots

# Part 1 – Understanding IDS, Firewalls and Honeypots

## Objective

The main goal of this project is to learn about security devices like Intrusion Detection Systems, Firewalls and Honeypots. These devices help protect computer networks from cyber attacks. This project also talks about ways to evade th>

> **Note:** This project is for educational purposes and should only be done in a controlled laboratory environment.

---

# What is an Intrusion Detection System (IDS)?

An Intrusion Detection System is a security solution that watches network traffic or host activities for behavior. It looks for things that are not allowed by the rules or for known attack signatures.

Unlike a firewall an Intrusion Detection System does not block traffic. Instead it sends alerts to security analysts so they can look into threats.

![Alt text](screenshots/ids-firewall-honeypot-overview.png)

**IDS, Firewall and Honeypot Overview**

```text
ids-firewall-honeypot-overview.png
```


### Types of IDS

### Network-based IDS

- It monitors network traffic.

- It detects suspicious packets.

- It protects multiple devices.

**Examples**

- Snort

- Suricata

- Zeek

---

### Host-based IDS

- It is installed on computers.

- It monitors files, processes, logs and system activity.

- It detects changes.

**Examples**

- OSSEC

- Wazuh

---

# What is an Intrusion Prevention System (IPS)?

An Intrusion Prevention System is like an Intrusion Detection System. It also blocks or prevents malicious traffic from reaching the target system.

Unlike an Intrusion Detection System, an Intrusion Prevention System works inline with network traffic. Can stop attacks.

---

# IDS vs IPS

| Feature | IDS IPS |


| Detects Attacks | Yes | Yes |

| Blocks Attacks | No | Yes |

| Generates Alerts | Yes | Yes |

| Inline Protection | No | Yes |


![Alt text](screenshots/ids-vs-ips-comparison.png)

![Alt text](screenshots/ids-vs-ips-comparison2.png)

**IDS vs IPS Comparison**

```text
ids-vs-ips-comparison.png
```


---

# What is a Firewall?

A Firewall is a network security device or software that controls outgoing network traffic based on predefined rules.

Firewalls are the line of defense. They allow traffic and block bad traffic.

### Common Firewall Types

- Packet Filtering Firewall

- Stateful Inspection Firewall

- Proxy Firewall

- Next-Generation Firewall (NGFW)

---

# What is a Honeypot?

A Honeypot is a system that is set up to attract attackers. It is like a decoy.

Its purpose is to watch what attackers do gather information and learn about attack techniques without putting real systems at risk.

### Benefits

- It helps detect attackers

- It gathers threat information.

- It helps study attacker techniques.

- It improves incident response.

---

# What is a Honeynet?

A Honeynet is a group of Honeypots connected together. It simulates a network environment for security research and monitoring.

---
# Why Do Attackers Try to Evade Security Devices?

Attackers try to avoid being detected so they can:

- Remain hidden

- Bypass security controls

- Keep accessing systems without permission

- Steal sensitive information

- Keep attacking without triggering alerts

---

# Defensive Security Measures

To reduce the risk of evasion organizations do the following:

- They use Layered security

- They keep Intrusion Detection System and Intrusion Prevention System signatures up to date

- They use secure firewall rules

- They segment the network

- They use threat intelligence

- They monitor everything all the time

- They use Security Information and Event Management

- They do regular security audits

---

# SOC Analyst Perspective

SOC analysts watch Intrusion Detection System, Intrusion Prevention System, firewall logs and network events all the time. They look for behavior. They investigate alerts look at events across systems and respond to incidents before th>

SOC analysts do the following:

- They review Intrusion Detection System alerts

- They monitor firewall logs

- They investigate network traffic

- They identify Indicators of Compromise

- They escalate confirmed incidents

---
# Key Concepts Learned

- Intrusion Detection System

- Intrusion Prevention System

- Network-based IDS

- Host-based IDS

- Firewalls

- Honeypots

- Honeynets

- Defense in Depth

- Threat Detection

- SOC Monitoring

---

# conclusion

Understanding Intrusion Detection Systems, Intrusion Prevention Systems, Firewalls and Honeypots is very important, for cybersecurity professionals. These technologies help detect, prevent and analyze cyber threats.
Knowing how these security devices work helps SOC analysts find activity improve network security and respond to security incidents.

-------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------
