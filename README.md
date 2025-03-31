
# Simulated Healthcare Incident Response Report  
*A hands-on project demonstrating threat intelligence and incident response skills*  


## 📌 Overview  
This repository contains a detailed **Incident Response Report** for a simulated healthcare incident scenario, created as part of the CLIKED-IBM Mini Sprint. The report showcases skills in log analysis, threat intelligence correlation, MITRE ATT&CK mapping, and incident response planning using the NIST framework.  

**Purpose**:  
- Demonstrate practical cybersecurity skills for roles in **Threat Intelligence**, **Incident Response**, or **SOC Analysis**.  
- Highlight the ability to analyze logs, identify IOCs, and map attacks to MITRE ATT&CK tactics.  
- Showcase structured reporting and actionable recommendations.  

---

## 🛠️ Project Details  
### **Scenario**:  
- **Organization**: Maven Clinic 
- **Incident**: Unusual network activity suggesting brute-force attacks, lateral movement, and potential data compromise (simulated incident)
- **Data Provided**:  
  - Windows Event Logs (e.g., failed logins, firewall changes).  
  - 100+ suspicious IP addresses for threat intelligence analysis.  

### **Tasks Completed**:  
1. **Log Analysis**: Identified brute-force attempts, privilege escalation, and lateral movement.  
2. **Threat Intelligence**: Researched IPs using VirusTotal, AbuseIPDB, OTX AlienVault, and Maltego.  
3. **MITRE ATT&CK Mapping**: Linked attacker actions to techniques like T1110 (Brute Force) and T1562.004 (Firewall Disabling).  
4. **Containment/Eradication Plans**: Short-term isolation and long-term hardening measures.  
5. **Post-Incident Review**: Lessons learned and budgeted recommendations.

## Key Features  
- **Tools**: Used Maltego for IP mapping, VirusTotal/AbuseIPDB for reputation checks, DNSlytics for domain analysis, OTX AlienVault: Correlated IPs with known threat actor TTPs and MaxMind/Ipinfo.io: Geolocated IPs and identified high-risk networks.
- **Actionable Insights**: Budget proposal ($262K) for preventative measures (XDR, MFA, PAM).  
- **Visualizations**: Timeline of events, MITRE ATT&CK mappings, and Maltego graphs showing IP relationships.  
