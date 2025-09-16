# Detection Rules Implementation in Azure Sentinel

## 1. Custom Scheduled Analytics Rules
Developed custom **scheduled rules** to trigger incidents upon log ingestion, ensuring timely threat detection.

<img src="images/8.jpg" alt="Scheduled Rule Configuration" width="400"/>
<img src="images/10.jpg" alt="Scheduled Rule Details" width="400"/>
<img src="images/9.jpg" alt="Scheduled Rule Logic" width="400"/>
<img src="images/11.jpg" alt="Scheduled Rule Summary" width="400"/>

## 2. Near-Real-Time (NRT) Analytics Rules
Implemented **NRT rules** to facilitate rapid response to security events by running queries every minute, significantly reducing detection latency.

<img src="images/nrt.png" alt="NRT Rule Configuration" width="400"/>

## 3. Machine Learning-Based Detection Rules
Integrated **machine learning models** to identify anomalous RDP and SSH login activities, enhancing the detection of sophisticated threats.

<img src="images/13.png" alt="ML Rule Configuration" width="400"/>

---

**References:**  
- [Create scheduled analytics rules in Microsoft Sentinel](https://learn.microsoft.com/en-us/azure/sentinel/create-analytics-rules)  
- [Work with near-real-time (NRT) detection analytics rules in Microsoft Sentinel](https://learn.microsoft.com/en-us/azure/sentinel/create-nrt-rules)  
- [Threat detection in Microsoft Sentinel](https://learn.microsoft.com/en-us/azure/sentinel/threat-detection)
