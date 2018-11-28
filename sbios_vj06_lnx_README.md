Hewlett Packard Enterprise Support Center Hewlett Packard Enterprise Support Center	

Drivers & software
** CRITICAL ** Online ROM Flash Component for Linux - HP ProLiant MicroServer Gen8 (J06) Servers
Type:	BIOS (Entitlement Required) - System ROM
Version:	2018.05.21(25 Jun 2018)
Operating System(s):	
Red Hat Enterprise Linux 6 Server (x86)
Red Hat Enterprise Linux 6 Server (x86-64)
Red Hat Enterprise Linux 7 Server
SUSE Linux Enterprise Server 11 (AMD64/EM64T)
SUSE Linux Enterprise Server 11 (x86)
SUSE Linux Enterprise Server 12
Description
This component provides updated system firmware that can be installed directly on supported Operating Systems. Additionally, when used in conjunction with Smart Update Manager (SUM), this Component allows the user to update firmware on remote servers from a central location. This remote deployment capability eliminates the need for the user to be physically present at the server in order to perform a firmware update.
Installation Instructions
To ensure the integrity of your download, HPE recommends verifying your results with this SHA-256 Checksum value:

bb50b75cf41046800f7d7af5f2b9e95e007fda324f45e56f6c3c38be30963e44	RPMS/i386/firmware-system-j06-2018.05.21-1.1.i386.rpm
Reboot Requirement:
Reboot is required after installation for updates to take effect and hardware stability to be maintained.

Installation:

IMPORTANT: This component will fail if it is unable to communicate with iLO.  This can occur if HP ProLiant Agentless Management Service (hp-ams) and HP SNMP Agents (hp-snmp-agents) are both running.  HP does not recommend running AMS and the SNMP Agents at the same time.  If an "iLO device not found" error occurs, stop AMS or the SNMP Agents, and run the flash component again.

To update firmware from Linux operating system on target server:
 
Install the RPM package
> rpm -Uvh <filename>.rpm
 
See where the files land
> rpm -qlp <filename>.rpm
 
Change to the directory you see in the previous step and run hpsetup by typing ‘./hpsetup’ at the command prompt.


Supplemental updates for supported ProLiant servers and options can be done by using HP Smart Update Manager, which is found on the Service Pack for ProLiant ISO.

Place the Service Pack for ProLiant on a USB key using the USB Key Creator Utility.
Place the desired components to be updated in the directory, \hp\swpackages on the USB key.
Update the firmware and software in the usual manner.

 

Release Notes
End User License Agreements:
HPE Software License Agreement v1

Upgrade Requirement:
Critical - HPE requires users update to this version immediately.

Important:

Important Notes:

This revision of the System ROM includes the latest revision of the Intel microcode which, in combination with operating system and hypervisor updates, provides mitigation for the L1 Terminal Fault – OS/SMM (CVE-2018-3620) and L1 Terminal Fault – VMM (CVE-2018-3646) security vulnerabilities.  These vulnerabilities may allow unauthorized disclosure of information residing in the L1 data cache to an attacker with local user access via a side-channel analysis.  These security vulnerabilities are not unique to HPE servers and impact any servers utilizing impacted processors.  Note that this server is NOT vulnerable to L1 Terminal Fault – SGX (CVE-2018-3615), also known as Foreshadow, because this server does NOT support SGX.

This revision of the System ROM includes the latest revision of the Intel microcode which, in combination with operating system updates, provides mitigation for the Speculative Store Bypass (also known as Variant 4) security vulnerability. A Medium level CVE has been assigned to this issue with ID CVE-2018-3639. Systems with microprocessors utilizing speculative execution and speculative execution of memory reads before the addresses of all prior memory writes are known may allow unauthorized disclosure of information to an attacker with local user access via a side-channel analysis. This security vulnerability is not unique to HPE servers and impacts any systems utilizing impacted processors.

This revision of the System ROM includes the latest revision of the Intel microcode which provides mitigation for the Rogue Register Read (also known as Variant 3a) security vulnerability. A Medium level CVE has been assigned to this issue with ID CVE-2018-3640. Systems with microprocessors utilizing speculative execution and that perform speculative reads of system registers may allow unauthorized disclosure of system parameters to an attacker with local user access via a side-channel analysis. This security vulnerability is not unique to HPE servers and impacts any systems utilizing impacted processors.

Deliverable Name:

HP ProLiant MicroServer Gen8 System ROM - J06

Release Version:

05/21/2018

Last Recommended or Critical Revision:

05/21/2018

Previous Revision:

01/22/2018

Firmware Dependencies:

None

Enhancements/New Features:

None

Problems Fixed:

This revision of the System ROM includes the latest revision of the Intel microcode which, in combination with operating system and hypervisor updates, provides mitigation for the L1 Terminal Fault – OS/SMM (CVE-2018-3620) and L1 Terminal Fault – VMM (CVE-2018-3646) security vulnerabilities.  These vulnerabilities may allow unauthorized disclosure of information residing in the L1 data cache to an attacker with local user access via a side-channel analysis.  These security vulnerabilities are not unique to HPE servers and impact any servers utilizing impacted processors.  Note that this server is NOT vulnerable to L1 Terminal Fault – SGX (CVE-2018-3615), also known as Foreshadow, because this server does NOT support SGX.

This revision of the System ROM includes the latest revision of the Intel microcode which, in combination with operating system updates, provides mitigation for the Speculative Store Bypass (also known as Variant 4) security vulnerability. A Medium level CVE has been assigned to this issue with ID CVE-2018-3639. Systems with microprocessors utilizing speculative execution and speculative execution of memory reads before the addresses of all prior memory writes are known may allow unauthorized disclosure of information to an attacker with local user access via a side-channel analysis. This security vulnerability is not unique to HPE servers and impacts any systems utilizing impacted processors.

This revision of the System ROM includes the latest revision of the Intel microcode which provides mitigation for the Rogue Register Read (also known as Variant 3a) security vulnerability. A Medium level CVE has been assigned to this issue with ID CVE-2018-3640. Systems with microprocessors utilizing speculative execution and that perform speculative reads of system registers may allow unauthorized disclosure of system parameters to an attacker with local user access via a side-channel analysis. This security vulnerability is not unique to HPE servers and impacts any systems utilizing impacted processors.

Known Issues:

None

Fixes
Upgrade Requirement:
Critical - HPE requires users update to this version immediately.

Important Notes:

This revision of the System ROM includes the latest revision of the Intel microcode which, in combination with operating system and hypervisor updates, provides mitigation for the L1 Terminal Fault – OS/SMM (CVE-2018-3620) and L1 Terminal Fault – VMM (CVE-2018-3646) security vulnerabilities.  These vulnerabilities may allow unauthorized disclosure of information residing in the L1 data cache to an attacker with local user access via a side-channel analysis.  These security vulnerabilities are not unique to HPE servers and impact any servers utilizing impacted processors.  Note that this server is NOT vulnerable to L1 Terminal Fault – SGX (CVE-2018-3615), also known as Foreshadow, because this server does NOT support SGX.

This revision of the System ROM includes the latest revision of the Intel microcode which, in combination with operating system updates, provides mitigation for the Speculative Store Bypass (also known as Variant 4) security vulnerability. A Medium level CVE has been assigned to this issue with ID CVE-2018-3639. Systems with microprocessors utilizing speculative execution and speculative execution of memory reads before the addresses of all prior memory writes are known may allow unauthorized disclosure of information to an attacker with local user access via a side-channel analysis. This security vulnerability is not unique to HPE servers and impacts any systems utilizing impacted processors.

This revision of the System ROM includes the latest revision of the Intel microcode which provides mitigation for the Rogue Register Read (also known as Variant 3a) security vulnerability. A Medium level CVE has been assigned to this issue with ID CVE-2018-3640. Systems with microprocessors utilizing speculative execution and that perform speculative reads of system registers may allow unauthorized disclosure of system parameters to an attacker with local user access via a side-channel analysis. This security vulnerability is not unique to HPE servers and impacts any systems utilizing impacted processors.

Firmware Dependencies:

None

Problems Fixed:

This revision of the System ROM includes the latest revision of the Intel microcode which, in combination with operating system and hypervisor updates, provides mitigation for the L1 Terminal Fault – OS/SMM (CVE-2018-3620) and L1 Terminal Fault – VMM (CVE-2018-3646) security vulnerabilities.  These vulnerabilities may allow unauthorized disclosure of information residing in the L1 data cache to an attacker with local user access via a side-channel analysis.  These security vulnerabilities are not unique to HPE servers and impact any servers utilizing impacted processors.  Note that this server is NOT vulnerable to L1 Terminal Fault – SGX (CVE-2018-3615), also known as Foreshadow, because this server does NOT support SGX.

This revision of the System ROM includes the latest revision of the Intel microcode which, in combination with operating system updates, provides mitigation for the Speculative Store Bypass (also known as Variant 4) security vulnerability. A Medium level CVE has been assigned to this issue with ID CVE-2018-3639. Systems with microprocessors utilizing speculative execution and speculative execution of memory reads before the addresses of all prior memory writes are known may allow unauthorized disclosure of information to an attacker with local user access via a side-channel analysis. This security vulnerability is not unique to HPE servers and impacts any systems utilizing impacted processors.

This revision of the System ROM includes the latest revision of the Intel microcode which provides mitigation for the Rogue Register Read (also known as Variant 3a) security vulnerability. A Medium level CVE has been assigned to this issue with ID CVE-2018-3640. Systems with microprocessors utilizing speculative execution and that perform speculative reads of system registers may allow unauthorized disclosure of system parameters to an attacker with local user access via a side-channel analysis. This security vulnerability is not unique to HPE servers and impacts any systems utilizing impacted processors.

Known Issues:

None

Important
Important Notes:

This revision of the System ROM includes the latest revision of the Intel microcode which, in combination with operating system and hypervisor updates, provides mitigation for the L1 Terminal Fault – OS/SMM (CVE-2018-3620) and L1 Terminal Fault – VMM (CVE-2018-3646) security vulnerabilities.  These vulnerabilities may allow unauthorized disclosure of information residing in the L1 data cache to an attacker with local user access via a side-channel analysis.  These security vulnerabilities are not unique to HPE servers and impact any servers utilizing impacted processors.  Note that this server is NOT vulnerable to L1 Terminal Fault – SGX (CVE-2018-3615), also known as Foreshadow, because this server does NOT support SGX.

This revision of the System ROM includes the latest revision of the Intel microcode which, in combination with operating system updates, provides mitigation for the Speculative Store Bypass (also known as Variant 4) security vulnerability. A Medium level CVE has been assigned to this issue with ID CVE-2018-3639. Systems with microprocessors utilizing speculative execution and speculative execution of memory reads before the addresses of all prior memory writes are known may allow unauthorized disclosure of information to an attacker with local user access via a side-channel analysis. This security vulnerability is not unique to HPE servers and impacts any systems utilizing impacted processors.

This revision of the System ROM includes the latest revision of the Intel microcode which provides mitigation for the Rogue Register Read (also known as Variant 3a) security vulnerability. A Medium level CVE has been assigned to this issue with ID CVE-2018-3640. Systems with microprocessors utilizing speculative execution and that perform speculative reads of system registers may allow unauthorized disclosure of system parameters to an attacker with local user access via a side-channel analysis. This security vulnerability is not unique to HPE servers and impacts any systems utilizing impacted processors.

Deliverable Name:

HP ProLiant MicroServer Gen8 System ROM - J06

Release Version:

05/21/2018

Last Recommended or Critical Revision:

05/21/2018

Previous Revision:

01/22/2018

Firmware Dependencies:

None

Enhancements/New Features:

None

Problems Fixed:

This revision of the System ROM includes the latest revision of the Intel microcode which, in combination with operating system and hypervisor updates, provides mitigation for the L1 Terminal Fault – OS/SMM (CVE-2018-3620) and L1 Terminal Fault – VMM (CVE-2018-3646) security vulnerabilities.  These vulnerabilities may allow unauthorized disclosure of information residing in the L1 data cache to an attacker with local user access via a side-channel analysis.  These security vulnerabilities are not unique to HPE servers and impact any servers utilizing impacted processors.  Note that this server is NOT vulnerable to L1 Terminal Fault – SGX (CVE-2018-3615), also known as Foreshadow, because this server does NOT support SGX.

This revision of the System ROM includes the latest revision of the Intel microcode which, in combination with operating system updates, provides mitigation for the Speculative Store Bypass (also known as Variant 4) security vulnerability. A Medium level CVE has been assigned to this issue with ID CVE-2018-3639. Systems with microprocessors utilizing speculative execution and speculative execution of memory reads before the addresses of all prior memory writes are known may allow unauthorized disclosure of information to an attacker with local user access via a side-channel analysis. This security vulnerability is not unique to HPE servers and impacts any systems utilizing impacted processors.

This revision of the System ROM includes the latest revision of the Intel microcode which provides mitigation for the Rogue Register Read (also known as Variant 3a) security vulnerability. A Medium level CVE has been assigned to this issue with ID CVE-2018-3640. Systems with microprocessors utilizing speculative execution and that perform speculative reads of system registers may allow unauthorized disclosure of system parameters to an attacker with local user access via a side-channel analysis. This security vulnerability is not unique to HPE servers and impacts any systems utilizing impacted processors.

Known Issues:

None

Revision History
Version:2018.05.21 (25 Jun 2018)
Fixes
Upgrade Requirement:
Critical - HPE requires users update to this version immediately.

Important Notes:

This revision of the System ROM includes the latest revision of the Intel microcode which, in combination with operating system and hypervisor updates, provides mitigation for the L1 Terminal Fault – OS/SMM (CVE-2018-3620) and L1 Terminal Fault – VMM (CVE-2018-3646) security vulnerabilities.  These vulnerabilities may allow unauthorized disclosure of information residing in the L1 data cache to an attacker with local user access via a side-channel analysis.  These security vulnerabilities are not unique to HPE servers and impact any servers utilizing impacted processors.  Note that this server is NOT vulnerable to L1 Terminal Fault – SGX (CVE-2018-3615), also known as Foreshadow, because this server does NOT support SGX.

This revision of the System ROM includes the latest revision of the Intel microcode which, in combination with operating system updates, provides mitigation for the Speculative Store Bypass (also known as Variant 4) security vulnerability. A Medium level CVE has been assigned to this issue with ID CVE-2018-3639. Systems with microprocessors utilizing speculative execution and speculative execution of memory reads before the addresses of all prior memory writes are known may allow unauthorized disclosure of information to an attacker with local user access via a side-channel analysis. This security vulnerability is not unique to HPE servers and impacts any systems utilizing impacted processors.

This revision of the System ROM includes the latest revision of the Intel microcode which provides mitigation for the Rogue Register Read (also known as Variant 3a) security vulnerability. A Medium level CVE has been assigned to this issue with ID CVE-2018-3640. Systems with microprocessors utilizing speculative execution and that perform speculative reads of system registers may allow unauthorized disclosure of system parameters to an attacker with local user access via a side-channel analysis. This security vulnerability is not unique to HPE servers and impacts any systems utilizing impacted processors.

Firmware Dependencies:

None

Problems Fixed:

This revision of the System ROM includes the latest revision of the Intel microcode which, in combination with operating system and hypervisor updates, provides mitigation for the L1 Terminal Fault – OS/SMM (CVE-2018-3620) and L1 Terminal Fault – VMM (CVE-2018-3646) security vulnerabilities.  These vulnerabilities may allow unauthorized disclosure of information residing in the L1 data cache to an attacker with local user access via a side-channel analysis.  These security vulnerabilities are not unique to HPE servers and impact any servers utilizing impacted processors.  Note that this server is NOT vulnerable to L1 Terminal Fault – SGX (CVE-2018-3615), also known as Foreshadow, because this server does NOT support SGX.

This revision of the System ROM includes the latest revision of the Intel microcode which, in combination with operating system updates, provides mitigation for the Speculative Store Bypass (also known as Variant 4) security vulnerability. A Medium level CVE has been assigned to this issue with ID CVE-2018-3639. Systems with microprocessors utilizing speculative execution and speculative execution of memory reads before the addresses of all prior memory writes are known may allow unauthorized disclosure of information to an attacker with local user access via a side-channel analysis. This security vulnerability is not unique to HPE servers and impacts any systems utilizing impacted processors.

This revision of the System ROM includes the latest revision of the Intel microcode which provides mitigation for the Rogue Register Read (also known as Variant 3a) security vulnerability. A Medium level CVE has been assigned to this issue with ID CVE-2018-3640. Systems with microprocessors utilizing speculative execution and that perform speculative reads of system registers may allow unauthorized disclosure of system parameters to an attacker with local user access via a side-channel analysis. This security vulnerability is not unique to HPE servers and impacts any systems utilizing impacted processors.

Known Issues:

None


Version:2018.01.22 (5 Mar 2018)
Fixes
Upgrade Requirement:
Critical - HPE requires users update to this version immediately.

Important Notes:

This revision of the System ROM includes the latest revision of the Intel microcode which, in combination with operating system updates, provides mitigation for Variant 2 of the Side Channel Analysis vulnerability, also known as Spectre. The revision of the microcode included in this System ROM does NOT have issues with more frequent reboots and unpredictable system behavior which impacted the previous Intel microcode which was part of the Spectre Variant 2 mitigation. Additional information is available from Intel’s Security Exploit Newsroom, https://newsroom.intel.com/press-kits/security-exploits-intel-products/.

Firmware Dependencies:

None

Problems Fixed:

Updated the Intel processor microcode to the latest version.

Known Issues:

None


Version:2015.11.02 (24 Oct 2016)
Enhancements
Upgrade Requirement:
Optional - Users should update to this version if their system is affected by one of the documented fixes or if there is a desire to utilize any of the enhanced functionality provided by this version.

Important Notes:

None
Firmware Dependencies:

None
Enhancements/New Features:

Added support for Intel Xeon E3-1220 v2 processors. Previous revisions of the System ROM should NOT be used with this processor as they did not support an appropriate thermal solution for it.
Known Issues:

None

Version:2015.07.16 (1 Oct 2015)
Enhancements
Upgrade Requirement:
Optional - Users should update to this version if their system is affected by one of the documented fixes or if there is a desire to utilize any of the enhanced functionality provided by this version.

Important Notes:

None

Firmware Dependencies:

iLO Chassis Manager (CM) 1.30 is required for changing the hyperthreading setting from the iLO CM command-line.

Enhancements/New Features:

Added support for Intel i3-2130 and i3-3240 processors.

Known Issues:

None


Version:2014.06.06 (15 Jun 2015)
Fixes
Upgrade Requirement:
Optional - Users should update to this version if their system is affected by one of the documented fixes or if there is a desire to utilize any of the enhanced functionality provided by this version.

Important Notes:

None
Firmware Dependencies:

None
Problems Fixed:

Resolved an issue with excessively loud fan noise when either SATA AHCI support is enabled in the Embedded SATA Configuration menu in RBSU (ROM-Based Setup Utility) or when Dynamic HP Smart Array B120i RAID Support is enabled in the Embedded SATA Configuration menu in RBSU (ROM-Based Setup Utility) and the Dynamic HP Smart Array B120i RAID operating system driver is not loaded.
Known Issues:

None

Version:2013.11.09 (21 Feb 2014)
Enhancements
Upgrade Requirement:
Optional - Users should update to this version if their system is affected by one of the documented fixes or if there is a desire to utilize any of the enhanced functionality provided by this version.

Important Notes:

None
Firmware Dependencies:

None
Enhancements/New Features:

Added additional options to the ROM Based Setup Utility (RBSU) Power-On Delay Option for delay times of 15, 30, 40 and 60 seconds (in addition to the previous options of No Delay and Random Delay). For these new selections to function, the system must be using Integrated Lights-Out (iLO) Firmware version 1.20 or later. If the system is configured to one of the new options without having iLO Firmware version 1.20 or later, the Power-On Delay Option will function as if the No Delay option were chosen.
Enhanced the System ROM's detection of valid boot devices such as USB Drive Keys or Hard Drives. Previously, the System ROM may have attempted to boot certain bootable media with invalid boot records resulting in a Non-System Disk error. In some cases, the System ROM will now be able to detect the invalid boot record and skip attempting to boot the device. This allows the System ROM to attempt to boot the next device in the boot order.

Added the latest product names of optional expansion cards and updated language translations (for non-English modes) in the ROM-Based Setup Utility (RBSU).

Known Issues:

None

Version:2013.08.24 (14 Aug 2013)
Fixes
Upgrade Requirement:
Critical - HP requires users update to this version immediately.

Important Notes:

None
Firmware Dependencies:

None
Problems Fixed:

Addressed a processor issue under which a rare and complex sequence of internal processor microarchitecture events that occur in specific operating environments could cause a server system to experience unexpected page faults, general protection faults, or machine check exceptions or other unpredictable system behavior. While all processors supported by this server have this issue, to be affected by this issue the server must be operating in a virtualized environment, have Intel Hyperthreading enabled, have a hypervisor that enables Intel VT FlexPriority and Extended Page Tables, and have a guest OS utilizing 32-bit PAE Paging Mode. This issue is not unique to HP ProLiant servers and could impact any system utilizing affected processors operating with the conditions listed above. This revision of the System ROM contains an updated version of Intel's microcode that addresses this issue. Due to the potential severity of the issue addressed in this revision of the System ROM, this System ROM upgrade is considered a critical fix.
Addressed an issue where the system experienced unexpected system behavior or report ACPI issues through the OS boot logs (such as Linux DMESG) when IOMMU was enabled in a virtualized operating system environment.

Addressed an issue where Linux Operating Systems reported the following message: ERST: Failed to get Error Log Address Range, in the Linux DMESG log.

Addressed an issue where the server's Legacy USB support would not properly report the drive capacity of a USB Drive Key that was larger than 8GB resulting in an inability to boot USB Drive Keys larger than 8 GB.

Addressed an issue where the system may not be able to properly execute the HP SmartStart Scripting Toolkit (SSSTK) under Linux based Operating Systems. In some cases, executing the HP SSSTK would result in a segfault error message being reported by the Linux kernel.

Known Issues:

None
Enhancements
Added the latest product names of optional expansion cards and updated language translations (for non-English modes) in the ROM-Based Setup Utility (RBSU).

Added support to allow industry standard utilities to display the operating voltage of installed DIMMs as well as the minimum and maximum voltage supported by installed DIMMs. This System ROM revision supports newly defined industry standard fields in the industry standard SMBIOS tables. Utilities to display this information may not yet be available.

Added support to allow industry standard utilities to display the HP DIMM Part Number for HP SmartMemory DIMMs. This information will also be displayed in the HP iLO GUI interface when using an updated revision of iLO Firmware.


Version:2013.04.02 (24 Jun 2013)
Enhancements
Upgrade Requirement:
Recommended - HP recommends users update to this version at their earliest convenience.

Important Notes:

None
Firmware Dependencies:

None
Enhancements/New Features:

This is the initial version of the firmware.
Known Issues:

None

Legal Disclaimer: Products sold prior to the November 1, 2015 separation of Hewlett-Packard Company into Hewlett Packard Enterprise Company and HP Inc. may have older product names and model numbers that differ from current models.
