
# How to Annoy Scammers :computer::boom:

## Introduction :bulb:
Tired of online scammers? Fight back! This guide outlines a step-by-step method to identify, report, and potentially disrupt scam websites.

<p align="center">
  <img src="ScamMascot.png" alt="Alt Text">
</p>


## Steps to Annoy Scammers :footprints:

### Step 1: Identifying Scam Text Messages
- Browse through Facebook community groups.
- Look for posts about scam text messages.

### Step 2: Domain Analysis
- Use [Security Trails](https://securitytrails.com) to investigate the domain of the scam site (remove any subdomains).
- Make sure you look at domains on the same server as chances are they are scam domains as well.

### Step 3: Subdomain Extraction
- Extract all subdomains listed on Security Trails.
- Check the hosting server of each subdomain.

### Step 4: Domain Exploration
- Check each subdomain and related domains for more shared domains.

### Step 5: Reporting
- Report all scam sites to Google and their hosting providers.

### Step 6: Directory Scanning
- Use directory scanning tools like `dirsearch`:
  ```bash
  dirsearch -u scamsite.com -w /usr/share/wordlists/dirb/common.txt
  ```

### Step 7: Admin Panel Access
- Identify the admin panel and try default credentials.

**Note:** Always operate within legal boundaries and never engage in illegal activities.

## Advanced Tips :gear:
- Check error pages for exposed log file names.
- If you gain access, consider deleting phished customer data.
- Investigate backup file names for patterns.

## Disclaimers :warning:
- This guide is for educational purposes only.
- Do not engage in any illegal activities.
- Always respect privacy and data protection laws.

## Support :star:
If you find this guide helpful, consider starring the repo!
