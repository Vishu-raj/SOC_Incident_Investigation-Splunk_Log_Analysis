# 🔎 SOC Incident Investigation: Splunk Log Analysis

**Author:** Vishu_Raj  
**Project Type:** Security Operations Center (SOC) Log Analysis & Threat Hunting

## 📌 Overview
This repository documents a comprehensive Security Operations Center (SOC) incident response investigation. The primary objective of this project was to utilize **Splunk SIEM** to ingest, parse, and analyze server logs to investigate a series of suspicious failed login attempts, indicative of a targeted brute-force attack.

*Architected and executed independently as part of my practical training with the Future CS Cybersecurity Internship.*

## 🎯 Investigation Objectives
*   **Log Ingestion & Parsing:** Configure Splunk to properly ingest and normalize the provided sample auth logs.
*   **Threat Hunting (SPL):** Write effective Splunk Search Processing Language (SPL) queries to filter noise and identify failed authentication events.
*   **Data Extraction:** Identify the targeted user accounts, the frequency/timeline of the attacks, and the originating IP addresses of the threat actor.
*   **Incident Reporting:** Compile the findings into a professional SOC incident report with actionable mitigation strategies.

## 🛠️ Tools & Technologies Used
*   **Splunk Enterprise** (SIEM)
*   **Splunk SPL** (Search Processing Language)
*   **Linux Auth Logs** (Data Source)
*   **Log Analysis & Event Correlation**

## 📸 Visual Evidence & Splunk Dashboards

Below are key moments from the investigation, showcasing the SPL queries and log analysis process within the Splunk environment:

### 1. Identifying Failed Login Spikes
*Analyzing the initial log data to spot anomalies in authentication attempts.*
![Failed Logins](./Screenshots/Screenshot%202025-08-31%20233052.png)

### 2. Tracking the Attacker IP
*Using SPL to isolate the specific source IP addresses generating the brute-force traffic.*
![Attacker IP Tracking](./Screenshots/Screenshot%202025-08-31%20234351.png)

### 3. Analyzing Targeted Accounts
*Determining which user accounts the threat actor was attempting to compromise.*
![Targeted Accounts](./Screenshots/Screenshot%202025-09-01%20011834.png)

### 4. Timeline & Frequency Correlation
*Mapping the attack over time to understand the automated nature of the script.*
![Timeline Analysis](./Screenshots/Screenshot%202025-09-01%20013910.png)

*(Note: Additional investigation screenshots are available in the `/Screenshots/` directory).*

## 📂 Repository Structure

*   `📂 Report/` – Contains the final detailed Incident Investigation Report.
*   `📂 Screenshots/` – Contains visual evidence of the Splunk dashboard, active SPL queries, and event logs[cite: 4].
*   `📄 .gitignore` – Standard Git ignore configurations[cite: 4].
*   `📄 LICENSE` – MIT License for open-source sharing[cite: 4].

## 🔗 Quick Links
*   [📄 Read the Final SOC Investigation Report (PDF)](./Report/SOC_Task2_Incident_Investigation_Report.pdf)
