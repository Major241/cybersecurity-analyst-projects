### **🎯 Case Study: Deconstructing a Phishing Attack with MITRE ATT&CK**

#### 🔹 Objective
Simulate a phishing email attack, collect forensic evidence, and map the adversary behaviors to the MITRE ATT&CK framework.

---

#### 🔹 Tools Used
*   **Canarytokens:** Generated trackable URL and captured forensic data.
*   **MITRE ATT&CK Navigator:** Mapped techniques to the framework.
*   **Browser & Email Client:** Simulated user interaction.

---

#### 🔹 Investigation Steps

**1. Setup & Simulation**
*   Generated a trackable phishing URL using Canarytokens.
*   Crafted a phishing email and executed a controlled click to trigger the alert.
*   ![Screenshot: Canarytoken Generation](https://github.com/Major241/cyber-portfolio/blob/main/images/canarytoken.png.png?raw=true)

**2. Evidence Collection**
*   Captured timestamp, source IP, and user-agent data from the alert.
*   ![Screenshot: Forensic Alert Data](https://github.com/Major241/cyber-portfolio/blob/main/images/mail.png.png?raw=true)

**3. ATT&CK Mapping**
Mapped the attack lifecycle to the following techniques:
*   **Resource Development:** T1583 (Acquire Infrastructure)
*   **Initial Access:** T1566.002 (Spearphishing Link)
*   **Execution:** T1204.002 (User Execution)
*   **Command & Control:** T1102 (Web Service)
*   **Collection:** T1114.003 (Email Collection)
*   **Impact:** T1498 (Network Denial of Service)
*   ![Screenshot: ATT&CK Navigator Layer](https://github.com/Major241/cyber-portfolio/blob/main/images/mitre_mapping.png.png?raw=true)

**4. Visualization**
*   Documented the attack flow: `Email → Malicious Link → User Click → C2 Beacon → Data Collection`

---

#### 🔹 Outcome
This project transformed MITRE ATT&CK from theory into practice. By simulating an attack and mapping it to the framework, I demonstrated how to:
*   Translate evidence into standardized threat language.
*   Visualize adversary behavior across the kill chain.
*   Use ATT&CK to guide detection engineering and threat hunting.
