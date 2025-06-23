# cyber-security-internship-task-1
Here's a GitHub repository structure and code for the task. This includes a script to automate the scan, documentation templates, and answers to interview questions: -


## Task Overview
- Perform TCP SYN scan of local network
- Identify open ports and services
- Analyze potential security risks

## How to Run
1. Make script executable:  
   `chmod +x run_scan.sh`
2. Execute script:  
   `./run_scan.sh`
3. Reports will be generated in:
   - Text format (`scan_*.nmap`)
   - HTML format (`report_*.html`)
   
## Required Tools
- Nmap
- xsltproc (for HTML conversion)

## Files
- `run_scan.sh` - Automated scanning script
- `FINDINGS.md` - Scan analysis and observations
- `INTERVIEW_ANSWERS.md` - Interview question responses

⚠️ **Caution:** Only scan networks you own or have permission to scan!
