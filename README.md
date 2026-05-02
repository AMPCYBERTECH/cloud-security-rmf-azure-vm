# Cloud Security & RMF-Based Risk Assessment (Azure VM)

## 📌 Overview

This project demonstrates the application of Governance, Risk, and Compliance (GRC) principles using the NIST Risk Management Framework (RMF) within a Microsoft Azure environment.

A virtual machine (VM) was deployed and treated as a real-world system, with defined system boundaries, identified dependencies, and assessed security risks.

---

## 🎯 Objectives

* Apply RMF concepts to a cloud-based system
* Define system boundaries and dependencies
* Identify and assess security risks
* Implement and recommend security controls
* Demonstrate shared responsibility in cloud security

---

## 🏗️ Architecture

The system consists of:

* Azure Virtual Machine (VM)
* Network Interface (NIC)
* Public IP Address
* Network Security Group (NSG)
* OS Disk

---

## 🔐 Security & Risk Analysis

### Identified Risks:

* Open RDP port (3389) exposed to the internet
* Public IP accessibility
* Potential unauthorized access

### Mitigation Strategies:

* Restrict inbound traffic by IP address
* Implement least privilege access
* Use secure access solutions (VPN / Bastion)

---

## ☁️ Shared Responsibility Model

* Azure: Physical infrastructure, hardware, data center security
* Customer: OS security, access control, network configuration

---

## 📊 GRC Concepts Applied

* NIST RMF lifecycle
* System boundary definition
* Risk assessment (Likelihood × Impact)
* Control implementation
* Continuous monitoring concepts

---

## 📁 Artifacts Included

* Mini System Security Plan (SSP)
* Risk Assessment
* Plan of Action & Milestones (POA&M)
* Control Mapping

---

## 🚀 Outcome

This project demonstrates hands-on experience applying GRC principles to a cloud environment, including risk identification, control implementation, and system documentation.

---

## 🔗 Author

Andre Penny
Cybersecurity / GRC | Cloud Security | Risk Management
