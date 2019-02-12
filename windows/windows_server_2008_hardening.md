1. Configuring dcpromo
Domain Controller Promoter/demoter utility for Microsoft's Active Directory Services
It's function is to change (Promote) a member server into a domain controller or to demote a domain controller to a member server in the active directory.

2. Configuring a Password GPO Policy
Creating Users and using dsquery
Group Policy Management --> Edit "Allow log on locally" Policy
Computer Configuration --> Windows Settings --> Security Settings --> Local Policies
 Add user group 

3. Creating Groups and using dsquery

4. Creating Directories, ACLs, and using the icacls command
Active directory command called icacls (Displays or modifies discretionary access control lists (DACLs) on specified files, and applies stored DACLs to files in specified directories.)

5. Using Windows Basic Encryption

6. Setting Up Audit Account Logon Events
Allows the administrators log events that deal with the following items:
Audit account logon events
Audit logon events
Audit account management
Audit policy change
Audit privilege use
Audit system events
terminal: gpupdate /force
terminal: gpresult utility /V | more #see all configuration 
Displays Group Policy settings and Resultant Set of Policy (RSOP) for a user or a computer

7. Configuring Internet Explorer Group Policy
search for in terminal gpedit.msc
configuring history 
turn off "delete history functionality"
prevent the deletion of temporary files

8. Configuring Remote Desktop Users
a lot of steps
computer and gpedit.msc --> built --> add users

9. Installing Microsoft Security Baseline Analyzer 
	
10. Add a computer to your domain

11. Remotely Backup a Windows 2008 Server

12. Killing off suspicious tasks
Open up command prompt and type “tasklist”
Go through each task, (if you don’t know what it is google it) and use the command taskkill -PID [PID # of malicious task] -f to forcefully remove the task

13. Download malwarebytes and do basic scan


