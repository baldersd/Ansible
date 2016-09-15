# Ansible
My Work Notes, Playbooks and Scripts

See OneNote file.

------------------------------
Windows Remote Nodes Pre-Reqs:
------------------------------
PRE-Windows 2012 there are some requirements:
-	Needs Winrm Core Framework installed.
-	Needs Powershell 3.0 min installed.
-	(above have dependency on .NET4 framework) – bulky install.

General Requirements (all Windows):
-	If we want to use WinRM over HTTPS --- needs a non-self-signed “server auth” certificate installed into localmachine\my
----can generate this with powershell or a windows CA.
-	Needs the winrm qc issued to open firewall ports
-	If we want to add ports manually need tcp 5985-5986
-	+Need to open icmp v4 echo.

