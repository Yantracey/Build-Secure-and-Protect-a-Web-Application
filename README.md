# Build-Secure-and-Protect-a-Web-Application (Technical Brief attached as a PDF file)

### Day 1: Building and Hosting Web Application

#### Part 1: Create an Azure Web App
1. **Azure Web App Creation:**
   - Logged into Azure portal: [https://portal.azure.com](https://portal.azure.com).
   - Selected "App Services" and clicked "+ Create."
   - Configured settings for subscription, resource group, instance name, etc.
   - Created a Linux plan named "project1plan" with Basic B1 pricing.
   - Successfully created the web app.

2. **Custom Domain Configuration:**
   - Accessed "Custom domains."
   - Obtained a free domain, accessible on the internet.

#### Part 2: Deploy a Container on the Web App
1. **Azure Cloud Shell Setup:**
   - Accessed Azure Cloud Shell.
   - Selected "Bash" and created persistent storage.

2. **Container Deployment:**
   - Deployed a Docker container using Azure Cloud Shell.
   - Verified deployment on the unique domain.

#### Part 3: Design Your Custom Web Application
1. **Customization of Webpage:**
   - Modified HTML pages to personalize content.
   - Altered elements, added custom blog posts.

2. **Backup Procedure:**
   - Implemented a backup strategy for HTML files.
   - Used `cp` command to back up the index.html file.

3. **Webpage Verification:**
   - Refreshed the webpage to ensure successful changes.

#### Part 4: Answer Review Questions
1. **Documentation:**
   - Answered Day 1 review questions.

#### Day 1 Milestone
- **Achievements:**
   - Created Azure web app, deployed a container, designed a custom web application.
   - Answered review questions.
- **Skills Utilized:**
   - Terminal, systems administration, cloud, automation.

---

### Day 2: Securing with SSL Certificates

#### Part 1: Create a Key Vault
- Logged in, selected "Key vaults," created "project1-KeyVault" with standard pricing.
  
#### Part 2: Create a Self-Signed Certificate
- Used Azure Cloud Shell to generate and encrypt a self-signed certificate.
- Viewed, downloaded the PFX certificate.

#### Part 3: Analyze a Self-Signed Certificate
- Imported the self-signed certificate into the key vault.
- Checked certificate operation on https://self-signed.badssl.com/.

#### Part 4: Analyze a Trusted SSL Certificate
- Verified the Azure free domain's trusted SSL certificate.

#### Part 5: Answer Review Questions
- Answered Day 2 review questions.

#### Day 2 Milestone
- **Achievements:**
   - Created key vault, self-signed certificate.
   - Analyzed self-signed and trusted certificates.
   - Answered review questions.
- **Skills Utilized:**
   - Terminal, systems administration, cloud, cryptography, networking.

---

### Day 3: Protecting with Azure's Security Features

#### Part 1: Create a Front Door Instance
1. **Azure Front Door Creation:**
   - Logged in, accessed app service.
   - Created "project1-FrontDoor" with Endpoint "Project1-FD" in "Red-Team."

2. **Verification of Front Door:**
   - Checked confirmation message.
   - Took a screenshot.

#### Part 2: Analyze WAF Rule Sets
1. **WAF Rule Sets Analysis:**
   - Searched for "web app," selected WAF.
   - Explored managed rules for application vulnerabilities.

#### Part 3: Configure Custom WAF Rules
1. **Custom WAF Rules Configuration:**
   - Created "Project1rule" to allow traffic from the US, Canada, and Australia.
   - Denied traffic from other locations.
   - Took a screenshot.

2. **Checkpoint:**
   - Ensured completion of critical tasks.

#### Part 4: Analyze and Fix a Defender for Cloud Recommendation
1. **Defender for Cloud Analysis:**
   - Accessed Defender for Cloud, reviewed recommendations.
   - Addressed the "Web apps should request an SSL certificate" recommendation.

#### Part 5: Answer Review Questions
1. **Documentation:**
   - Answered Day 3 review questions.

### Conclusion
Successfully completed the assignment, showcasing proficiency in Azure services, web application development, and security implementation.
