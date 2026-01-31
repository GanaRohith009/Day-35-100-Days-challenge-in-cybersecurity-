# Day-35-100-Days-challenge-in-cybersecurity-
### Day 23: Automated Vulnerability Scanning with OWASP ZAP

**Focus:** Automating reconnaissance and understanding the "Attacker's Eye" view of an application.

#### 🛠 Tools Used
* **OWASP ZAP (Zed Attack Proxy):** Used as a Man-in-the-Middle proxy to intercept traffic and automate vulnerability detection.

#### 📝 Key Learnings
1.  **The Proxy Model:** Configured ZAP to sit between the browser and the target app. This revealed hidden traffic (headers, cookies) invisible to the standard UI.
2.  **Spidering (Recon):** Demonstrated how automated tools "crawl" a target to build a site map, discovering hidden endpoints and assets (e.g., `.bak` files, `/admin` directories).
3.  **Attack Surface Visualization:** The automated scan highlighted that every input field is a potential entry point.
    * *Observation:* Automation generates significant "noise," making it easily detectable by WAFs, but highly effective for rapid mapping.

#### ⚠️ Note
* *Always ensure you have explicit permission before running active scans, as the traffic volume can degrade server performance.*
