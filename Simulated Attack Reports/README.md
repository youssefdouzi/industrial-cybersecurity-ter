# Simulated Attack Reports – Industrial Cybersecurity Research Project

This folder contains three technical reports written with my colleagues as part of my Master’s research project (TER) in the FSI (Reliability and IT Security) program at Aix-Marseille University.

These documents present **simulated cyberattacks** against virtual industrial environments, aiming to assess the vulnerabilities of SCADA/ICS systems through concrete, hands-on scenarios.

---

## Contents

### 1. **DDoS Attack on ICSSIM**
- Simulation of a distributed denial-of-service attack on a simulated ICS environment using ICSSIM
- Analysis of the impact on PLCs and supervisory systems
- Tools: ICSSIM, Python

### 2. **Man-in-the-Middle (MITM) Attack on Factory IO**
- Interception and modification of communication between a PLC and the HMI (simulated by Codesys)
- Exploitation of unsecured Modbus TCP traffic
- Demonstrates the lack of encryption/authentication in industrial protocols

### 3. **Script Injection Attack on Factory IO**
- Injection of malicious logic into the process simulation
- Disruption of normal automation behavior
- Illustrates application-layer vulnerabilities in industrial control logic

---

## Purpose

These simulated attacks aim to highlight:
- The exposure of OT environments to common cyber threats
- The importance of network segmentation, encryption, and intrusion detection in industrial contexts
- The need for awareness and protection in critical infrastructure

---

## Tools & Technologies

- ICSSIM
- Python
- Factory IO
- Codesys 
- Modbus TCP  
- Kali Linux, Wireshark, Scapy
