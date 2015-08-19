AUTOMATED SYSTEM MAINTENANCE SCRIPT (ASMS) V1.0a
by Tudor Laptes
https://github.com/PlainIntricacy

README

========================================

1) ABOUT
2) VERSION HISTORY
3) INSTALL/UNINSTALL

========================================

1 - ABOUT

Welcome to the System Maintenance Script v1.0a

This is a .bat file I wrote to automate the process of running multiple cleaning and software update programs, as part of the regular maintenance of a Windows PC.

The goal of this project is to fully automate the process of system maintenance and relevant software update, in order to easily maintain a clean and up-to-date system.

This script requires several key software programs specifically chosen for their cleaning and automation abilities, in order to make the maintenance of a system as easy and hassle free as possible.

REQUIRED SOFTWARE:

- Windows 7/8/10 64-bit OS
- Ninite
- CCleaner
- Malwarebytes AntiMalware
- AMD Video Drivers (and compatible GPU card)

All links and information on how to prepare the software for this file are provided in the INSTALL/UNINSTALL section below

========================================

2 - VERSION HISTORY

v1.0
	- Initial release
	- ASMS automates the opening of listed maintenance software. User must complete and exit each listed maintenance software manually.
	- ASMS depends on offline availability of listed maintenance software. User must install listed maintenance software manually according to the INSTALL/UNINSTALL section guide.
	- ASMS indirectly requires an active connection to the Internet (in order to complete listed maintenance software update)
	
========================================

3 - INSTALL/UNINSTALL

The following steps will ensure the proper setup for ASMS:

1) Download your customized Ninite installer from https://ninite.com/
2) Rename the Ninite installer to "Ninite.exe" (without quotes)
3) Move Ninite.exe to "C:\Program Files\Ninite\" (without quotes) - create a new folder named Ninite in Program Files if one does not already exist
4) Download and install CCleaner using default settings from https://www.piriform.com/ccleaner/download - make sure the install folder is "C:\Program Files\CCleaner\" (without quotes)
5) Download and install Malwarebytes AntiMalware using default settings from https://www.malwarebytes.org/mwb-download/ - make sure the install folder is "C:\Program Files\Malwarebytes Anti-Malware\" (without quotes)
6) Download and install AMD Drivers using default settings from http://support.amd.com/en-us/download - make sure the install folder is "C:\Program Files\AMD" (without quotes)
7) Download and extract the ASMS archive from https://github.com/PlainIntricacy/ASMS
8) Open ASMS.bat and run the script to completion
9) You can now access all your maintenance software via the ASMS.bat file
10) You can schedule regular system maintenance with ASMS by using it with Windows Task Scheduler

If you have issues opening the ASMS.bat file (UAC, admin privileges), run the file as an administrator (right click on ASMS.bat and select "Run as administrator")

To uninstall ASMS, simply delete the ASMS folder from your computer.
For a complete removal, also uninstall Ninite, CCleaner, Malwarebytes AntiMalware and AMD Drivers.