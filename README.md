# Vulnerability Assessment

## Objective

The main objective of this lab is to identify, analyze, and assess security vulnerabilities in systems, applications, and network services. This includes determining the severity of discovered vulnerabilities, validating findings, and recommending appropriate remediation to reduce security risks.

### Skills Learned

- Perform vulnerability scans using Nessus Essentials.
- Identify security vulnerabilities and system misconfigurations.
- Analyze and interpret vulnerability scan results.
- Understand CVE and CVSS severity ratings.
- Differentiate between Critical, High, Medium, Low, and Informational findings.
- Prioritize vulnerabilities based on their risk level.
- Review remediation recommendations provided by Nessus.
- Generate and analyze vulnerability assessment reports.

### Tools Used

- Nessus
  
## Steps
==> This lab was completed as part of a hands-on exercise on TryHackMe, where I practiced vulnerability assessment techniques using Nessus.

1. After starting the lab, the IP address of the TryHackMe machine will be displayed.
   
    <img width="1907" height="938" alt="Screenshot 2026-06-26 151949" src="https://github.com/user-attachments/assets/97ab0d56-056b-4d3c-aa37-a18f6ee554c8" />
   
  **Note:** Verify that you can connect to the TryHackMe machine before starting the vulnerability assessment.

  <img width="952" height="458" alt="Screenshot 2026-06-26 152727" src="https://github.com/user-attachments/assets/380c0240-7633-4040-bb95-b5d740b5bf14" />

2. Open Nessus
   
    <img width="2352" height="1221" alt="Screenshot 2026-06-26 153459" src="https://github.com/user-attachments/assets/4e579e69-bb4a-4861-adf8-471292ade325" />

3. Start New Scan
   
    <img width="2345" height="1137" alt="Screenshot 2026-06-26 153708" src="https://github.com/user-attachments/assets/ae9dd22a-46d0-465e-81e5-2eb5cc1f390f" />

    Nessus provides a variety of scan templates. Select the template that best matches the type of assessment you want to perform.
   
5. Start a Host Discovery Scan

   The **Host Discovery** template performs a task similar to an Nmap host discovery scan. With **Nmap**, you manually execute scan commands, whereas **Nessus** automates the discovery process and generates a detailed report with     minimal manual effort.

   <img width="2354" height="1129" alt="Screenshot 2026-06-26 155236" src="https://github.com/user-attachments/assets/bdcb2214-2c80-43ce-9ebd-318a741dcb8b" />

 **Configure the Host Discovery Scan**

  **General**

  * Enter the **Name**, **Description**, and **Target** for the scan.
  * **Schedule:** Enable this option only if you want the scan to run automatically at a specified time. Otherwise, leave it disabled.
  * **Notifications (Optional):** Enable notifications if you want Nessus to send you an alert when the scan is complete.

  **Discovery**

  * Select the type of discovery scan you want to perform based on your assessment requirements.

    After configuring the scan settings, click **Save** to create the scan.

    <img width="2358" height="602" alt="Screenshot 2026-06-26 160206" src="https://github.com/user-attachments/assets/52dbed85-6907-429b-b066-bcbff407bd6d" />

    Next, start running the scan task that was created earlier.

    The results will display active hosts and any detected open ports, if available.


6. Start a Web Application Test

   <img width="2343" height="1119" alt="Screenshot 2026-06-26 161218" src="https://github.com/user-attachments/assets/2eb2e6d1-ab65-48b4-bb35-45e9787a1a2d" />

   Then click Start Scan to begin the assessment.
   
   <img width="2356" height="1007" alt="Screenshot 2026-06-26 161343" src="https://github.com/user-attachments/assets/97144229-c318-4229-a82f-b90316ced026" />

   After the scan completes, Nessus will display all identified vulnerabilities in the target web application, if any are present.

   <img width="2151" height="853" alt="Screenshot 2026-06-26 161924" src="https://github.com/user-attachments/assets/0e0be3f7-f127-4096-af55-680435354121" />


   

   
 


   
   
   




   
   



