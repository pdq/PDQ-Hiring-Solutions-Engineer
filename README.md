# System Administrator (Solutions Engineer) Homework

Please read the instructions and questions *carefully*. This is an open-book assignment, so feel free to use your highly honed Google-Fu skills, but please don't copy the work of others or have anyone else help you. The entire team will evaluate your homework, which means you are free to use acronyms and technical/industry-specific language where appropriate and expedient.

Create/open a plain .txt file and answer the following:

1. Briefly describe your experience using PDQ Deploy and PDQ Inventory.

2. List at least one case where it's likely better to use GPO to accomplish a task than PDQ Deploy. Why is it better to use GPO in this/these case(s)?

3. Explain why machines lose trust with Active Directory and the most efficient and least impactful way to resolve this issue.

4. You have a machine that responds to ping, but when you try to access it you discover you're accessing another machine entirely. Why? How do you troubleshoot and resolve this issue?

5. Explain Heartbeat and Heartbeat Trigger as used in PDQ.com products.

6. Explain Distributed Wake-on-LAN as used in PDQ products and list the requirements for Distributed WOL to work.

7. What are some common ways to make sure an application installation runs silently?

8. What is the most difficult application you have had to deploy? What made it difficult?

9. What command would you use to silently install an MSI file called MyApp.msi. (Do not allow a reboot after the install.)

10. In your AD domain, you have computers frequently switching between different networks: VPN, wireless, wired, and VLANs. You are using Microsoft’s implementation of DHCP and DNS. Describe how you would configure DHCP or DNS (or both) to handle those computers.

11. Briefly describe your experience with scripting and automation.

12. What is your preferred scripting language?

13. What do you like about that language?

14. What do you dislike about that language?

### For the following, please submit the respective XML files in the same .zip archive used for the scripting exercises at the end of this assessment.

1. In PDQ Inventory, create a registry scanner that checks for the default RDP port. Create two collections based on the results: one collection for machines with the default port and one collection for machines not using the default port. Please include the XML files for the scanner and both collections.

2. In PDQ Inventory, create a report that lists the computer name and any users in the local Administrators group. The local Administrator account, Domain Admins, and Backup Operators should be excluded in the report. Please include the XML file of the report.

3. In PDQ Inventory, create a report that displays all machines that do not have PDF24Creator installed. Please include the XML file of the report you created.

4. Using PDQ Deploy, create a package to deploy Office 365. Please include any config files you would use and the XML of the package.

5. Using PDQ Deploy, install MPC-HC on all Windows 7 machines on the first Tuesday of the month regardless of whether the machine has received the deployment or not. Please include the XML files for the package and schedule.

6. Using PDQ Deploy, install 7-Zip on all Windows 10 machines every Saturday, when the machine comes back into the network after being off or out of the network, and only on machines where the package has never been deployed. Please include the XML files for the package and schedule.

7. Using PDQ Deploy, deploy Java with an approved site list of pdq.com, weather.com, and fancyurl.com with a security level that is set to High and Locked. The approval must apply to all users. Please include the XML file of the deployment package you created.

### Scripting exercise:
Write a script (PowerShell preferred, but certainly not required) that does the following: 
* Find all json files located within each user's %AppData% directory.
* Output to the console in the following format: ".json found in "

## Final Step:
When finished, zip up your plain text file ensuring that the .zip file name contains your name, and upload the .zip file to https://link.pdq.com/application (no account required). Submissions are reviewed within 3 - 6 business days and considered for an interview.

## Important
Please do not include anything in your homework submission (other than your name as the zip file) that could identify you. Submissions are anonymized on receipt so our team does not know whose homework they are evaluating.
