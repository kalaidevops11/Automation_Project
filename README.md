# Automation_Project
The Bash file "automation.sh" will do the following process:
1. Do the apt update
2. Check of Apache2 Package installation
3. If the Package is not installed, then it will install it otherwise skip
4. Check the status of the Apache2 web server
5. Archiving the Apache log files from /var/log/apache2/ to /tmp/ folder
6. Will take a back up of the archieved folder in /tmp/ to S3 bucket
