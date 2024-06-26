# TheInquisitor
This PowerShell script has been carefully crafted to assist IT auditors in extracting information from Windows workstations and servers during technical audits. It aims to automate repetitive tasks, streamlining the auditing process. Please note that explicit permission is required before running this script on any server that you do not own.

The inquisitor is a PwoerShell script designed to help IT auditor to perform simple tasks when auditing such as Retrieving host name, IP address, processor info, Used storage, Last Security update and free memory.
To properly run this script you may need the PowerShell version of '5' or later, to exactly know the version of your PowerShell you can run the following command and refer to the img folder > knowing the powershell version for a clear example:

---- $PSVersionTable.PSVersion.ToString()

This script includes information about the last 5 security updates in the HTML report. Please ensure you run this script in an environment where PowerShell script execution is allowed.

Please note that the accuracy of this information depends on the availability and accuracy of hotfix data on the system. Additionally, execution of PowerShell scripts may require appropriate execution policies to be set on the system.

Note that this script has a limitation when it is ran on a Virtual machine, it may not provide accurate information regarding the RAM and total storage. Please dowload the The_Inquistor.rar file to access the Script itself and further useful information. 

To avoid any disruption, please ensure that you run the script in a controlled environment. 

 ###This script was developed by Manuel Santos, a Senior IT Auditor.
