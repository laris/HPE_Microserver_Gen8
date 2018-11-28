Hewlett Packard Enterprise Support Center Hewlett Packard Enterprise Support Center	

Drivers & software
* RECOMMENDED * Online ROM Flash Component for Linux - HPE Integrated Lights-Out 4
Type:	Firmware - Lights-Out Management
Version:	2.61(6 Aug 2018)
Operating System(s):	
Red Hat Enterprise Linux 6 Server (x86)
Red Hat Enterprise Linux 6 Server (x86-64)
Red Hat Enterprise Linux 7 Server
SUSE Linux Enterprise Server 10 (AMD64/EM64T)
SUSE Linux Enterprise Server 11 (AMD64/EM64T)
SUSE Linux Enterprise Server 11 (x86)
SUSE Linux Enterprise Server 12
Description
This component provides updated iLO firmware that can be installed directly on supported Linux Operating Systems. This component can also be used to obtain the firmware image for updating via iLO user interface, utilities, or through the scripting interface. Additionally, this component can be used with the HPE Smart Update Manager.
Enhancements
None

Installation Instructions
Prerequisites:

Hewlett Packard Enterprise recommends the following or greater versions of iLO utilities
for best performance:

RESTful Interface Tool (iLOREST) 2.3
HPQLOCFG v5.2 
Lights-Out XML Scripting Sample bundle 5.10.0
HPONCFG Windows 5.2.0
HPONCFG Linux 5.3.0 (A)
LOCFG v5.10.0
HPLOMIG 5.2.0
To ensure the integrity of your download, HPE recommends verifying your results with the following SHA-256 Checksum values:

1adf1ff2e66c7b7aede3858cd9dd324fd62ac2d44d0a983503af4f02b825f922	RPMS/i386/firmware-ilo4-2.61-1.1.i386.rpm
ede345eb91c7e06b0c51fbc0faf6c2b4cf72b26aa379b0eb65fd713316711f05	CP036949.scexe
Reboot Requirement:
Reboot is not required after installation for updates to take effect and hardware stability to be maintained.

Installation:

To update firmware from the Linux operating system on target server:
Download the SCEXE file to the target server.
Execute: sh CP0xxxxx.scexe

 To obtain firmware image for updating via iLO user interface, utilities, or scripting interface:
Download the SCEXE file to a client running a Linux operating system.  Execute: sh  CP0xxxxx.scexe --unpack=directory
This command will unpack the ilo4_1XX.bin into a user specified "directory". If the directory does not exist, the unpacker will attempt to create it.

To use HPE Smart Update Manager on the Firmware Maintenance CD:
Place the Firmware Maintenance CD on a USB key using the HPE USB Key Creator Utility. 
Copy  CP0xxxxx.scexe to /compaq/swpackages directory on the USB Key.
Follow HPE Smart Update Manager steps to complete firmware update.

Release Notes
End User License Agreements:
HPE Software License Agreement v1

Upgrade Requirement:
Recommended - HPE recommends users update to this version at their earliest convenience.

Important:

IPv6 network communications - Dedicated network connection only
     Supported Networking Features
                IPv6 Static Address Assignment
                IPv6 SLAAC Address Assignment
                IPv6 Static Route Assignment
                IPv6 Static Default Gateway Entry
                DHCPv6 Stateful Address Assignment
                DHCPv6 Stateless DNS, Domain Name, and NTP Configuration
                Integrated Remote Console
                OA Single Sign-On
                HP-SIM Single Sign-On
                Web Server
                SSH Server
                SNTP Client
                DDNS Client
                RIBCL over IPv6
                SNMP
                AlertMail
                Remote Syslog
                WinDBG Support
                CPQLOCFG/HPLOMIG over an IPv6 connection
                Scriptable Virtual Media
                CLI/RIBCL Key Import over IPv6
                Authentication using LDAP and Kerberos over IPv6
                iLO Federation
     Networking Features not supported by IPv6 in this release
                IPv6 Over Shared Network Port Connections
                IPMI
                NETBIOS-WINS
                Enterprise Secure Key Manager (ESKM) Support
                Embedded Remote Support (ERS)

Notes:

 

iLO 4 User Guide and Lights-Out Scripting Guide can also be found by following the links at:

http://www.hpe.com/info/ilo

Select your lights-out product, then support & documents, then manuals.
 

Check the online help for additional information about how to use features. 
Online help can be accessed from within the browser web pages by clicking the question mark in the upper right-hand corner of each page.
Fixes
Upgrade Requirement:
Recommended - HPE recommends users update to this version at their earliest convenience.

The following issues are resolved in this version:

Intermittent boot failures encountered when server boots from MicroSD card.
Fixed problem with AHS download that might have unreadable data for the current day.
iLO Web GUI sessions might not logoff at the end of timeout period.
Incorrect information displayed for Power Supply Bay in AHS viewer.
License hyperlink in Access Settings page of GUI leads to Page Not Found.
Unable to login to iLO CLI after setting iLO to factory defaults, requiring an additional iLO reset.
Unable to delete REST interface sessions with users having certain special characters.
SNMP may become unresponsive over a period of time.
SECURITY: 

  For the latest security bulletins and vulnerabilities, please visit: 
  https://support.hpe.com/hpesc/public/home

Security bulletins:

HPESBHF03866
Security best practices:

  Please refer to the HPE Integrated Lights-Out Security Technology Brief for the latest on security best practices at:
  http://www.hpe.com/support/iLO4_security_en
 

Important
IPv6 network communications - Dedicated network connection only
     Supported Networking Features
                IPv6 Static Address Assignment
                IPv6 SLAAC Address Assignment
                IPv6 Static Route Assignment
                IPv6 Static Default Gateway Entry
                DHCPv6 Stateful Address Assignment
                DHCPv6 Stateless DNS, Domain Name, and NTP Configuration
                Integrated Remote Console
                OA Single Sign-On
                HP-SIM Single Sign-On
                Web Server
                SSH Server
                SNTP Client
                DDNS Client
                RIBCL over IPv6
                SNMP
                AlertMail
                Remote Syslog
                WinDBG Support
                CPQLOCFG/HPLOMIG over an IPv6 connection
                Scriptable Virtual Media
                CLI/RIBCL Key Import over IPv6
                Authentication using LDAP and Kerberos over IPv6
                iLO Federation
     Networking Features not supported by IPv6 in this release
                IPv6 Over Shared Network Port Connections
                IPMI
                NETBIOS-WINS
                Enterprise Secure Key Manager (ESKM) Support
                Embedded Remote Support (ERS)

Revision History
Version:2.61 (6 Aug 2018)
Fixes
Upgrade Requirement:
Recommended - HPE recommends users update to this version at their earliest convenience.

The following issues are resolved in this version:

Intermittent boot failures encountered when server boots from MicroSD card.
Fixed problem with AHS download that might have unreadable data for the current day.
iLO Web GUI sessions might not logoff at the end of timeout period.
Incorrect information displayed for Power Supply Bay in AHS viewer.
License hyperlink in Access Settings page of GUI leads to Page Not Found.
Unable to login to iLO CLI after setting iLO to factory defaults, requiring an additional iLO reset.
Unable to delete REST interface sessions with users having certain special characters.
SNMP may become unresponsive over a period of time.
SECURITY: 

  For the latest security bulletins and vulnerabilities, please visit: 
  https://support.hpe.com/hpesc/public/home

Security bulletins:

HPESBHF03866
Security best practices:

  Please refer to the HPE Integrated Lights-Out Security Technology Brief for the latest on security best practices at:
  http://www.hpe.com/support/iLO4_security_en
 

Enhancements
None


Version:2.60 (30 May 2018)
Fixes
Upgrade Requirement:
Critical - HPE requires users update to this version immediately.


Install this update to take advantage of significant improvements to the write algorithm for the embedded 4 GB non-volatile flash memory (also known as the NAND). These improvements increase the NAND lifespan.

The following issues are resolved in this version:

 iLO 4 unexpectedly restored itself to factory default settings when an user did not initiate the process. 
When Auto Power-On is set to Always Power On to Restore Last Power State, the server might not power on after a cold reset. 
False nonvolatile flash memory (NAND) test failures might occur after a firmware upgrade.
Incorrect RAM and Storage values are displayed on the HPE OneView for VMware vCenter tab.
Remote Support disk events include the text “Not Available” for the variables when data is missing.
Some Power Supply information is missing from the iLO web interface.
iLO displays Failed status instead of Disabled status when the Smart Array Cache Module battery is disconnected.
An iLO SSH port disconnection issue was observed after more than two days of continuous operation.
Values do not move up when the preceding entries in the Directory User Context fields are cleared.
Boot failures might occur when booting with a MicroSD card in Legacy mode.
Changed the resolution of a Redfish SSD wear field to display in percentage.
The date and time settings are reset after a firmware update.
The server powers on instead of shutting down when multiple power-on requests are sent.
SECURITY FIXES: 

  For the latest security bulletins and vulnerabilities addressed in this version, please visit: 
  https://support.hpe.com/hpesc/public/home  

Security best practices:

  Please refer to the HPE Integrated Lights-Out Security Technology Brief for the latest on security best practices at:
  http://www.hpe.com/support/iLO4_security_en

Enhancements
This version adds support for the following features and enhancements:

IPMI/DCMI over LAN access is disabled by default on new servers with iLO 4 2.60.
IPMI/DCMI over LAN access is disabled after you reset iLO 4 2.60 to the factory default settings. 
Each time iLO starts, it backs up the iLO configuration to the nonvolatile flash memory (NAND). If the SRAM is erased, the configuration is automatically restored.
Improved Active Health System logging efficiency to prolong the NAND lifespan. 
Added iLO health status to the Overview page. If the status is Degraded, this value is also displayed on the Login page.  
Added an SNMP trap for a power fault condition on Gen8 servers.
Added the list of open source licenses to the login page.  
Added a Format Embedded Flash and reset iLO button to the Diagnostics page. When directed by Hewlett Packard Enterprise support, you can use this feature to recover Active Health System functionality.
Re-signed the Java IRC to extend the certificate expiration date. 
Re-signed the .NET IRC to extend the certificate expiration date.
With this enhancement, the .NET IRC requires version 4.5.1 or later of the .NET Framework.
Added the ability to remove a SSL certificate and regenerate the iLO self-signed certificate.
Note: HPE recommends using a CA signed certificate.

Version:2.55 (15 Sep 2017)
Fixes
Upgrade Requirement:
Recommended - HPE recommends users update to this version at their earliest convenience.

The following issues are resolved in this version:

Masked out errant failures due to charging of storage battery.
Implemented cell voltage separation pre-failure warning for storage battery.
iLO RESTful API output might display incorrect power supply information.
iLO Federation group authentication errors might occur if you repeatedly add and remove groups during a query.
An iLO RESTful API event subscription might be lost when DELETE and CREATE subscriptions occur at the same time that the transmitter waits to retry an action.
During CAC smartcard authentication, the iLO RESTful API returns a session URI that incorrectly contains uppercase letters.
In certain conditions, the Rest server becomes unavailable during a GET of the IELs.
The iLO web interface language pack redirects to English.
The iLO RESTful API output text represents upper threshold values as lower thresholds.
The Linux openipmi driver does not poll the receive message queue if KCS host irq not enabled.
The iLO RESTful API EthernetInterfaces link should be under the system/1 root resource, and not in the OEM section.
SNMPv3 Engine Boot is not getting incremented on iLO reset.
IPMI FRU read returns incorrect completion code for response too long.
IPMI Get PEF Capabilities returns the number of valid table entries instead of the total number of table entries.  
IPMI Set Boot Options for one time change for boot mode UEFI/Legacy fixed.  
iLO restserver suspends when patching bad payload to external provider array.
iLO REST API returned 500 internal error for a GET of systems/1/ leading to failed One View Profile Apply.
iLO RESfulT API events are sending incorrect "Host" header when using IPv6.
iLO time becomes Unset after update from 2.50 or prior to 2.54.
Enhancements
This version adds support for the following features and enhancements:

The Self-signed SSL certificate can now be regenerated.
New iLO RESTful API command to allow an auxiliary power cycle of the server on the next host power down.
Added THERM_TRIP events, OS_STOP_SHUTDOWN, OS_NMI, ACPI, PCI-E Bus Error and CPU error logs to the SEL. 
Added OEM type SEL event with IML info on critical events.
Improved reliability of Embedded Media attach and diagnostics.

Version:2.54 (7 Jul 2017)
Fixes
Upgrade Requirement:
Recommended - HPE recommends users update to this version at their earliest convenience.

The following issues are resolved in this version:

Resolved an issue where in some cases iLO configuration data could be reset to default values after an iLO firmware upgrade (only affects Gen8 servers).
Improved the mechanism to reset communication to the non-volatile storage (NAND) upon a warm reboot of the server (to reset an inaccessible NAND)
NOTE: If the NAND is inaccessible when upgrading to iLO 4 2.54 firmware, an AC power pull may be necessary to reset an inaccessible NAND.
The following issues are resolved in version 2.53 (replaced by 2.54):

Fixed an issue that led to POST Error: 333-iLO RESTful API Error - Unable to communicate with the iLO firmware when an SD card is was installed.
Fix handling of logical drive indexing, found in cases where logical drives are not contiguous.
Power loss occurs when hot-plugging RPS backplane during runtime.
High fan noise occurs during ML110 Gen9 server system startup.
IPMI Drive fault is incorrectly mapped to “In Failed Array” on drive sensors.
Target node iLO is unavailable when an HPE OneView server profile is applied.
The iLO RESTful API Software Inventory is incomplete when compared to the iLO web interface.
The iLO RESTful API does not return complete version strings for all software components.
Unable to use IPMI to “Set Serial Number” and “Set Product ID”.
Fan failure and server shutdown occur on SL230s Gen8 servers.
Reverse Address Translate returns bad values when called with hponcfg.
The iLO RESTful API does not return the exact PCI device location for PCIe components.
An incorrect device type is reported for the embedded SATA controller.
Performing a NAND format may leave the REST provider registration in an unstable state.
Solid state drives are intermittently reported as hard disk drives.   
Fixed SNMP configuration read failure issue due to wrong FQDN trap destination configuration.  
Fixed an issue that could lead to distorted video after setting boot mode to UEFI via RIBCL.
False Self-Test error on USB port may be reported when an HPE ProLiant Gen8-Series server is powered Off (Advisory found at: http://h20565.www2.hpe.com/hpsc/doc/public/display?docId=emr_na-a00007681en_us)
Improved error handling of option card AHS data that could result in excessive descriptor growth resulting in large AHS data files.
Enhancements
This version adds support for the following features and enhancements:

iLO Amplifier Pack - Advanced Server Firmware/Driver and License Management Solution
OpenLDAP
OpenSSL 1.0.1u FIPS
PSRT 301
CSRs no longer include the iLO IP address by default. To include the iLO IP address in the CSR, enable the include iLO IP Address(es) option in the iLO web interface.
Added an iLO RESTful API option to include the iLO IP address in SSL certificate CSRs.
AlertMail formatting improvements.

Version:2.53 (5 May 2017)
Fixes
Upgrade Requirement:
Recommended - HPE recommends users update to this version at their earliest convenience.

REMOVED - iLO 4 firmware version 2.53 is NO LONGER AVAILABLE for download due to an issue found where settings may reset to factory defaults on HPE ProLiant Gen8-series servers.  The replacement version is iLO 4 v2.54.  For additional information, refer to the Customer Advisory at: http://h20566.www2.hpe.com/hpsc/doc/public/display?docId=a00019947. 

The following issues are resolved in version 2.53:
  • Fixed an issue that led to POST Error: 333-iLO RESTful API Error - Unable to communicate with the iLO firmware when an SD card is was installed.
  • Fix handling of logical drive indexing, found in cases where logical drives are not contiguous.
  • Power loss occurs when hot-plugging RPS backplane during runtime.
  • High fan noise occurs during ML110 Gen9 server system startup.
  • IPMI Drive fault is incorrectly mapped to “In Failed Array” on drive sensors.
  • Target node iLO is unavailable when an HPE OneView server profile is applied.
  • The iLO RESTful API Software Inventory is incomplete when compared to the iLO web interface.
  • The iLO RESTful API does not return complete version strings for all software components.
  • Unable to use IPMI to “Set Serial Number” and “Set Product ID”.
  • Fan failure and server shutdown occur on SL230s Gen8 servers.
  • Reverse Address Translate returns bad values when called with hponcfg.
  • The iLO RESTful API does not return the exact PCI device location for PCIe components.
  • An incorrect device type is reported for the embedded SATA controller.
  • Performing a NAND format may leave the REST provider registration in an unstable state.
  • Solid state drives are intermittently reported as hard disk drives.   
  • Fixed SNMP configuration read failure issue due to wrong FQDN trap destination configuration.  
  • Fixed an issue that could lead to distorted video after setting boot mode to UEFI via RIBCL.
  • False Self-Test error on USB port may be reported when an HPE ProLiant Gen8-Series server is powered Off.
  • Insight Online direct connect registration might fail and display the error “No Server Certificate.”
  • Some IML and iLO Event Log entries are excluded when the Active Health System Log is downloaded with iLO 4 2.50.
  • Fixed an issue that causes a burden on the Active Health System when too many logs are recorded.

Enhancements
REMOVED - iLO 4 firmware version 2.53 is NO LONGER AVAILABLE for download due to an issue found where settings may reset to factory defaults on HPE ProLiant Gen8-series servers.  The replacement version is iLO 4 v2.54.

iLO 4 firmware version 2.53 adds support for the following features and enhancements:
  • iLO Amplifier Pack - Advanced Server Firmware/Driver and License Management Solution
  • OpenLDAP
  • OpenSSL 1.0.1u FIPS
  • PSRT 301
  • CSRs no longer include the iLO IP address by default. To include the iLO IP address in the CSR, enable
    the include iLO IP Address(es) option in the iLO web interface.
  • Added an iLO RESTful API option to include the iLO IP address in SSL certificate CSRs.
  • AlertMail formatting improvements.


Version:2.50 (24 Oct 2016)
Fixes
Upgrade Requirement:
Recommended - HPE recommends users update to this version at their earliest convenience.


Note for ESXi users: If you are booted from the Embedded SD Card, it is strongly
Recommended that you reboot the server immediately after updating to iLO 4 v2.50.

The following issues are resolved in this version:

Dynamic Power Capping still works when set to disabled.
Server may shut down after repeated insertion and removal of hot-plug power input modules for RPS backplanes. 
Repeated LDAP tests cause iLO LDAP User Authentication to fail.
The reporting of location discovery services data via the RESTful API on ML/DL servers failed even with iLO Advanced license installed.
Rare memory leak that could lead to slow or failed iLO interfaces due to unverified data returns from unregistered providers.
Corrected the link on the direct connect registration page to point to www.hpe.com/support/hpesc instead of www.hpe.com/services/hpesc.
OA communication issue after OneView SPP update.
Status of pure Fibre Channel cards show up as Unknown in Network Tab of iLO System Information.
External Rest Providers removed after upgrading BIOS, booting, and then resetting iLO.
Rarely a GET to the SNMP MIB will fail.
Rarely updates using HPSUT fail.
iLOs won't join Federation group or respond to SSDP requests if DHCPv4 is configured but an IP address is not obtained at iLO boot time.
Prev/Next links and list behavior of iLO federation are not consistent.
Security fixes/enhancements:
Improved AlertMail message body encoding.
CBC Mode ciphers disabled in FIPS/AES Modes (both Webserver and SSH).
RC4 has been removed from the default cipher list.
3DES and SHA-1 are disabled in FIPS mode.
Enhancements
This version adds support for the following features and enhancements:

Implemented Garbage collection on the RESTful API allowing for automatic recovery in the case of bad or missing data.
Updates to the enclosure connection status (CPQSTSYS cpqSsBoxConnectionStatus) now correctly report when an enclosure is disconnected or reconnected, and sends trap cpqSsConnectionStatusChange where appropriate.
This version adds protection to the lifespan of the embedded 4GB non-volatile storage (NAND) by implementing a daily write count limit that is well above the normal daily activity.  This ensures a runaway process will not inadvertently write to the NAND excessively leading to eventual failure.
Changed the default SSL certificate signing to SHA-256.
Added support for IP addresses in the SubjectAltName field of the iLO SSL certificate.

Version:2.44 (25 Jul 2016)
Fixes
Upgrade Requirement:
Optional - Users should update to this version if their system is affected by one of the documented fixes or if there is a desire to utilize any of the enhanced functionality provided by this version.

This release is based on the 2.40 iLO 4 FW Release and contains all the fixes and enhancements included in that version. 

Also included in this release:

Gen 8 systems no longer include unnecessary wait for MCTP device discovery in order to initialize sensors.
Fixed issue where intermittently the IPMI SDRR initialization would take up to 120 seconds.
Added iLO event log entry for IPMI PEF actions.
Enhanced disk drive status to include controller failure status.
Addressed an issue where a Smart Array battery failure could trigger excessive SMI interrupts when NVDIMMs are not present in the system. This could cause a server hang.
Auto Power On not working on SL/XL servers.
Fixed iLO 4 in Gen9 erasing ServerName EV in non-Virtual Connect environments. This caused them to show as "host is unnamed" in the Onboard Administrator GUI.
Fixed iLO 4 SNMP returning wrong IP address when snmpbulkget was used.
Fixed Remote Support 'Data Package Validation failed' error message.
Unable to remove Active Directory Groups via RIBCL.
Fixed RIS data storage file path validation and recovery.
Fixed unnecessary clearing of the RESTful API as a result of BIOS upgrade/downgrade.
Fixed setting of SET_PERSISTENT_BOOT bootorder for systems with a long boot order list.
Fixed support for systems with much larger overall SMBIOS records.
Fixed HP RESTful tool errors. BIOS registration could produce empty entries.
Fixed loss of communication with Onboard Administrator.
Removed font download from external source at login.
Fixed problems associated with Apollo 4200 with 25 drives. Needed to support more internal platform definitions.
Security fixes/enhancements:
Modified "Enforce AES/3DES Encryption" setting to only allow TLS 1.2 protocol.
Security fix. See HP Security Bulletin HPSBHF03441.
Enhancements
Enhancements:
• Performance improvements - fewer SMIs.
• Enhanced MCTP, PMCI and I2C code used to gather information.


Version:2.40 (1 Apr 2016)
Fixes
Upgrade Requirement:
Optional - Users should update to this version if their system is affected by one of the documented fixes or if there is a desire to utilize any of the enhanced functionality provided by this version.

The following issues are resolved in this version:

  • NIC auto-selection can be configured via RIBCL on DL60 and DL80 servers. These servers do not support the iLO Dedicated Network Port or NIC auto-selection.
  • There is no POST error after one or more fans are removed.
  • iLO does not collect and delete out of date or unused BIOS provider schemas and registries.
  • The iLO 4 web server might stop responding after an invalid file is submitted on the firmware update page.
  • When system throttling occurs on Gen8 servers, the duration is longer than necessary.
  • Cookies set by older versions of iLO were not understood correctly and might cause problems when you try to select iLO Federation groups.
  • The chassis firmware version number is not displayed consistently in the web interface.
  • Sorting by column does not work in some iLO web interface tables.
  • The language icon at the bottom of the browser window is not displayed in Internet Explorer.
  • The domain name cannot be set via the CLP when the Shared Network Port is enabled.
  • A drive failure does not trigger an action when IPMI PEF is enabled. 
  • The json/power_alert API returns an incorrect error (HTTP error 500) for bad parameters.
  • The wrong iLO self-test name "UnknownSelfTest" is displayed for the NVRAM space test in Redfish output.
  • The UID Indicator status does not change to BLINK when the Integrated Remote Console is active.
  • Kerberos authentication cannot be enabled when FIPS mode is enabled.
  • Keystrokes are repeated in the Integrated Remote Console when the server is in the UEFI Shell.
  • Data is not displayed in the power meter 20 minute or 24 hour graph.
  • The License page does not refresh to update the status after an iLO Advanced license is installed.
  • Redfish output does not group the Average, Minimum, and Peak values together in the Fast Power Meter output.
  • The NIC Information page displays the address 0.0.0.0 when the IPv6 address is the only IP address available for the iLO NIC.
  • Duplicate entries for network cards are displayed on the Device Inventory page.
  • Redfish output displays an incorrect memory type for non-HPE memory.
  • The NIC Information page displays the value N/A when a NIC team is configured.
  • An incorrect error message is displayed for the TESTTRAP command after SNMP alerts are disabled.
  • Power consumption values are incorrect in Redfish Chassis/1/Power/FastPowerMeter/ output.
  • Power supply bay numbering is inconsistent between the web interface and RESTful API output.
  • If an SNMP test alert is sent when SNMPv1 traps are disabled and SNMPv3 users are not defined, iLO reports a successful test when an error should be displayed.
  • An event log message is not logged when an SSL certificate is imported via the RESTful API.
  • A password that contains the equals sign (=) cannot be set when a user is added by using the CLI.
  • The value null is displayed for all RESTful API NetworkAdapters packet statistics.
  • The RESTful API schema file does not include the supported values for SpeedMbps.
  • An infinite loop in the file system check utility causes slow system performance.
  • DL580 Gen9 servers might fail to boot from an SD card.
  • The 53-Sensor LOM is displayed as missing on the Temperatures page for DL580 Gen8 servers.
  • After a vulnerability scan, iLO 4 might be left doing ACK flood with the scanner software.
  • iLO 4 might become unresponsive when attempting to delete an old AHS file with an invalid character in its name.
  • AlertMail rejects email addresses with hyphen characters.
  • Only one LDAP server can be configured by using RIBCL.
  • Insight Remote Support is not alerted if a failed hard drive is on a bay number above 18.
 

Enhancements
This version adds support for the following features and enhancements:

  • The iLO web interface has been updated to support the Hewlett Packard Enterprise style, URLs, and company information.
  • The Java IRC now includes two alternatives: A Java Web Start console and a Java applet-based console. The Java Web Start option works in newer browsers that do not allow the applet version to run.
    On systems with OpenJDK, you must use the Java applet-based console with a browser (such as Firefox) that supports a Java plug-in.
  • The new Critical Temperature Remain Off setting can be configured via RIBCL for all nonblade servers.  This setting controls system behavior when the system is shut down due to thermal protection circuitry.
    This is a different protection mechanism for thermal events, and it is not based on temperature sensor thresholds, OS policy, or the environmental abnormality automatic shutdown configuration. 
  • The following service events are now supported with embedded Remote Support registration:
    - ATA Disk Drive Status Changed Event
    - Fibre Channel Host Controller Status Changed Event
  • The Server Reset button is now available on the Boot Order page when the Boot Mode is modified.
  • The NVMe Backplane PIC firmware can now be updated via iLO.
  • The logical drive label and ID were added to the RESTful API.
  • NIC auto-selection can now be configured to search both Shared Network Ports on servers that support this hardware configuration. This feature can be configured via the CLI and RIBCL.
  • NIC auto-selection can now be configured to support NIC failover. When enabled, iLO automatically begins searching for a NIC connection when the current connection fails. This
    feature can be configured via the CLI and RIBCL.


Version:2.30 (1 Oct 2015)
Fixes
Upgrade Requirement:
Optional - Users should update to this version if their system is affected by one of the documented fixes or if there is a desire to utilize any of the enhanced functionality provided by this version.

The following issues are resolved in this version:

The iLO Federation group licensing feature does not decode license keys.
A RESTful API Power Supply Health Status Warning occurs when no power supply is installed.
License keys are displayed when snmpwalk is used.
An incorrect URL is displayed for newly-registered providers.
On Gen8 servers, when a TPM is present and enabled, the displayed TPM Module value is incorrect.
On blade servers that support UEFI, an iLO CLI session hangs while executing the "show system1/bootconfig1" command.
An incorrect error message is displayed when a user tries to edit a deleted user account.
An LDAP login causes an invalid session URI.
iLO hangs when a directory user tries to log in with encryption enabled.
iLO Federation group power caps cannot be set or edited by using the RESTful API.
On DL20 servers, MULTICAST_FEDERATION_ENABLED can be configured when the Shared Network Port is enabled.
In Internet Explorer 11, the iLO Event Log and IML Last Update and Initial Update filter shows a blank filter option.
A .NET IRC session closes when it is accessed by three different browser sessions.
The wrong PSU firmware version is displayed in the iLO web interface and SNMP.
A RESTful API Property Unknown Response message occurs during a firmware update.
A RESTful API Property Unknown Response message occurs when iLO Functionality is set to Disabled.
A RESTful API Property Unknown Response message occurs when the Virtual Power Press And Hold option is used.
The RESTful API cannot be used to set iLO to the factory default settings.
An error occurs when the Set_Persistent_Boot_Order.xml script is used on servers that support UEFI.
A 500 Internal Server Error occurs when an Email Address, Sender Domain, or SMTP Server value with 63 characters is entered on the AlertMail page.
The AlertMailEmail parameter does not display complete email addresses.
External Storage trap events are not sent to the HP Support Center.
The following error occurs during POST: 338-HP RESTful API Error - Unable to communicate with iLO FW.
Test events can be sent when HP remote support is not configured.
The Get_TPM_Status.xml script returns incorrect XML.
Product names might be appended to version numbers on the Software Inventory page.
An incorrect message is displayed when AES encryption is re-enabled by using the Mod_Global_Settings.xml script.
When using the RESTful API, the SNMP AlertDestination does not validate the IP address.
Acceptance of the SNMP Alert Destination IP address in the CLI and iLO web interface is inconsistent.
Incorrect status information is displayed for empty PCI slots.
The P840ar is displayed as a P840.
False errors were reported after a successful Power Management Controller firmware update, and were followed by an inability to communicate with a rebooting Power Management Controller.
Reduced the frequency of iLO Event Log additions for IPMI session login/logouts.
Enhancements
This version adds support for the following features and enhancements:

IPMI Platform Event traps can now be sent to IPv6 destinations.
The Smart Array drive media type is now available via SNMP, RESTful API, iLO web interface, and RIBCL.
The Smart Array drive RPM is now available via SNMP and the RESTful API.
Power capping can now be enabled via the RESTful API when the feature is disabled by the ROM settings.
Support for new Access Settings options has been added to the RESTful API.
Security enhancements:
Removed export ciphers from the default configuration to address false positives reported by scanning tools.
Disabled TLS v1.0 in FIPS Mode and Enforce AES/3DES Encryption mode.
Added SSH support for aes256-ctr cipher and hmac-sha2-256 mac to fix a connection issue in some default SSH configurations.
The Affected Systems list on iLO Federation pages can be exported to a CSV file.
The iLO Event Log is now searchable and can be filtered by event severity, last update, or initial update.
The IML is now searchable and can be filtered by event severity, class, last update, or initial update.
The following service event types are now supported by HP remote support:
SAS Physical Drive Status Changed Event
Storage System Fan Status Changed Event
Storage System Power Supply Status Changed Event
The new Chassis Information page is displayed for Apollo servers and SL and XL servers. For these server types, some information from the System Information > Power page has been moved to this page.
The new Software Information page displays HP and HP-recommended third-party software, running software, and installed software.
Troubleshooting information is available for selected IML events. Supported events are displayed as links in the Description column on the IML page.
Servers with a TPM or TM display the module type on the iLO Overview page.
Added a new IPMI OEM command to change channel assignments.
Increased the number of concurrent IPMI sessions.
Updated to DCMI 1.1, parameter revision 2.
Added IPMI over IPv6 support.
IPMI memory events in SEL now include the DIMM number.
 


Version:2.22 (18 Aug 2015)
Fixes
Upgrade Requirement:
Recommended - HPE recommends users update to this version at their earliest convenience.

The following issues are resolved in this version:

  • When the iLO 4 firmware is updated to version 2.20, the iLO security settings might be
    reset to the default values.
  • Embedded media handling was updated to reduce embedded media errors.
  • Addressed SSRT102184
 
The following issues are resolved in version 2.20 (replaced by 2.22):
 
  • Fixed detection of the Intel GPU sensor in Gen9 servers with the GPU. This allows
    fans to be controlled more reasonably.
  • Staged ROM settings might be lost after CONREP is run if the server was reset before
    iLO was reset.
  • The correct number of license seats is not displayed when 256 or more seats are
    licensed.
  • Fixed an IPMI driver issue for Linux.
  • Fixed a Virtual Media disconnect issue.
  • Fixed a DHCP client renewal issue.
  • The Alertmail page in the iLO web interface rejects email addresses with the following
    format: wwww@xxxx.yyy.zz.
  • Fixed an IPMI boot option issue when IPMI tool is used.
  • The set command in the iLO CLI does not finish on DL380 Gen9 servers.
  • The iLO IPv6 options are set to the default values when FIPS mode is enabled.
  • The iLO web interface hangs for a few minutes when a long string is entered in the
    Firmware URL box on the Group Firmware Update page.
  • Added an iLO workaround for IPMI tool boot parameter command options.
  • LDAP authentication fails when a password contains diacritic characters.
  • iLO sends several multicast join/leave requests when disabling multicast.
  • iLO event logs that contain an IP address are dropped if the DNS lookup queue is
    full. These events are now logged with (DNS name not found) in place of the DNS name.
  • The iLO web interface allows an iLO Federation Group Key with more than 32 characters
    when the character limit is 31.
  • The set_Boot_Mode.xml script fails when you use HPONCFG to set legacy mode for Gen8
    servers.
  • The Firmware page incorrectly displays slot 0 for HP220i Host adapters.
  • The Asset Tag can be set via XML when the server is powered off, except for when
    the server is in UEFI mode.
  • An Embedded Flash/SD-Card subsystem failure is not logged in the iLO Event Log. 
  • iLO does not reset when Active Health System logging is enabled via XML.
  • An iLO Event Log entry is not recorded when network settings are modified
    by using the CLI.
  • The floppy disc boot options always, never, and once are displayed in the Gen9 CLI,
    but these features are not supported.
  • A TPM Caution message is not displayed when a new language pack is installed.
  • The tooltip on the Device Inventory page does not disappear when you click
    outside the table.

 

Enhancements
This version adds support for the following features and enhancements from version 2.20:

  • The Remote Console security settings were moved from the Administration >
    Security > Remote Console page to the Remote Console > Security page.
  • The new Authentication Failure Delay Time setting allows users to
    configure the duration of the iLO login delay after a failed login attempt.
    This setting can be configured on the Access Settings page.
  • The new Authentication Failures Before Delay setting allows users to configure
    the number of failed login attempts that are allowed before iLO imposes a
    login delay. This setting can be configured on the Access Settings page.
  • iLO 4 2.20 and later allows you to install multiple language packs.
      - For iLO 4 2.10 and earlier—You can install one language pack.
        Installing a new language pack replaces the currently installed language
        pack, regardless of the language pack version.
      - For iLO 4 2.20 and later—Language packs are not supported on servers that
        do not have a NAND. To continue using language packs on servers without a NAND
        use iLO 4 2.10 or earlier.
      - When you upgrade from an earlier version of iLO 4 to version 2.20 or
        later, previously installed language packs are deleted.
      - iLO 4 2.20 or later requires version 2.20 or later of the iLO language
        pack.
      - When version 2.20 or later of a language pack is installed, installing a new
        language pack of the same language (version 2.20 or later) replaces the currently
        installed language pack.
      - The following language packs are available: Japanese and Simplified
        Chinese.
  • The HP ProLiant Agentless Management Service status is now listed on the
    Information > System Information > Summary page.
  • Trusted Module status is now displayed on the Information > Overview page.
  • RIBCL scripts and the CLP can now be used to send a test trap to test the
    SNMP configuration.
  • Added support for IPv6 in IPMI LAN Configuration Command Parameters.


Version:2.11 (18 Aug 2015)
Enhancements
Upgrade Requirement:
Optional - Users should update to this version if their system is affected by one of the documented fixes or if there is a desire to utilize any of the enhanced functionality provided by this version.

This release is intended for FIPS 140-2 level 1 validation and Common Criteria EAL2+ certification and is based from the iLO 4 v2.10 Release. All bug fixes and enhancements related to v2.10 have also been included in this release.  The current status of iLO 4 firmware v2.11 for these two certifications can be found at ttp://h10038.www1.hp.com/certifications.aspx?agencyid=89
 


Version:2.20 (15 Jun 2015)
Fixes
Upgrade Requirement:
Optional - Users should update to this version if their system is affected by one of the documented fixes or if there is a desire to utilize any of the enhanced functionality provided by this version.

REMOVED: iLO4 firmware version 2.20 is NO LONGER AVAILABLE for download due to an issue found when upgrading to version 2.20 that results in resetting iLO security settings to default values. Click the 'Obtain software' link to open the HP Support Center download web page for iLO 4 firmware version 2.22, which is the replacement for version 2.20. Refer to HP Customer Advisory c04760191 for more details.

iLO4 firmware version 2.20 resolved the following issues:

Fixed detection of the Intel GPU sensor in Gen9 servers with the GPU. This allows fans to be controlled more reasonably.
Staged ROM settings might be lost after CONREP is run if the server was reset before iLO was reset.
The correct number of license seats is not displayed when 256 or more seats are licensed.
Fixed an IPMI driver issue for Linux.
Fixed a Virtual Media disconnect issue.
Fixed a DHCP client renewal issue.
Alertmail webpage rejects email addresses with wwww@xxxx.yyy.zz format.
Fixed an IPMI boot option issue when using IPMI tool.
The set command in the iLO CLI does not finish on DL380 Gen9 servers.
The iLO IPv6 options are set to the default values when FIPS mode is enabled.
The iLO web interface hangs for a few minutes when a long string is entered for a group firmware update.
Added an iLO workaround for IPMI tool boot parameter command options.
LDAP authentication fails when a password contains diacritic characters.
LDAP authentication might fail against a properly configured OpenLDAP server due to protocol version restrictions.
iLO sends several multicast join/leave requests when disabling multicast.
iLO event logs that contain an IP address are dropped if the DNS lookup queue is full. These events are now logged with (DNS name not found) in place of the DNS name.
The iLO web interface allows an iLO Federation Group Key with more than 32 characters when the character limit is 31.
The set_Boot_Mode.xml script fails when you use HPONCFG to set legacy mode for Gen8 servers.
The Firmware page incorrectly displays slot 0 for HP220i Host adapters.
The Asset Tag can be set via XML when the server is powered off, except for when the server is in UEFI mode.
An Embedded Flash/SD-Card subsystem failure is not logged in iLO Event log. 
iLO does not reset when Active Health System logging is enabled via XML.
An iLO event log entry is not recorded when network settings are modified by using the CLI.
The floppy disc boot options always, never, and once are displayed in the Gen9 CLI, but these features are not supported.
A TPM Caution message is not displayed when a new language pack is installed.
The tooltip on the Device Inventory page does not disappear when you click outside the table.
Enhancements
REMOVED: iLO 4 firmware version 2.20 is NO LONGER AVAILABLE for download due to an issue found when upgrading to version 2.20 that results in resetting iLO security settings to default values. Click the 'Obtain software' link to open the HP Support Center download web page for iLO 4 firmware version 2.22, which is the replacement for version 2.20. Refer to HP Customer Advisory c04760191 for more details.

iLO 4 firmware version 2.20 adds support for the following features and enhancements:

The Remote Console security settings were moved from the Administration > Security > Remote Console page to the Remote Console > Security page.
The new Authentication Failure Delay Time setting allows users to configure the duration of the iLO login delay after a failed login attempt. This setting can be configured on the Access Settings page.
The new Authentication Failures Before Delay setting allows users to configure the number of failed login attempts that are allowed before iLO imposes a login delay. This setting can be configured on the Access Settings page.
iLO 4 version 2.20 and later allows you to install more than one language pack.
For iLO 4 version 2.10 and earlier—You can install one language pack at a time. Installing a new language pack replaces the currently installed language pack, regardless of the language pack version.
For iLO 4 version 2.20 and later—Language packs are not supported on servers that do not have a NAND. Servers without a NAND should continue to use iLO 4 version 2.10.
iLO 4 version 2.20 or later requires version 2.20 or later of the iLO language pack.
When you upgrade from an earlier version of iLO 4 to version 2.20 or later, previously installed language packs are deleted.
The following language packs are available: Japanese and Simplified Chinese.
The HP ProLiant Agentless Management Service status is now listed on the Information > System Information > Summary page.
Trusted Module status is now displayed on the Information > Overview page.
RIBCL scripts and the CLP can now be used to send a test trap to test the SNMP configuration.
Added support for IPv6 in IPMI LAN Configuration Command Parameters.
 


Version:2.10 (30 Mar 2015)
Fixes
Upgrade Requirement:
Recommended - HPE recommends users update to this version at their earliest convenience.

The following issues are resolved in this version:
• Addressed SSRT101886
• An iLO kernel crash after 40 or more days of uptime under certain operating systems can lead to an operating system crash. When this occurs, the iLO Event Log records a “Power restored to iLO” event at the time of the OS crash.
• iLO might send multiple SNMP traps that show the Smart Array battery falsely changing status (SNMP trap ID 11020).
• iLO firmware updates might stay at 1% and never finish.
• ADH ciphers are accepted in iLO 4 when AES is enabled.
• Incorrect information is displayed on the Information > System Information > Network page when there are similar MAC addresses.
• SSDP advertisements have bad signatures and iLO Federation groups don't display all peers.
• Power supply sensors are not illustrated in the Temperature graph.
• The iLO Event Log reports that a firmware update failed even though the firmware was updated successfully with the HP SUM Scalable Update feature.
• The .NET IRC disconnects unexpectedly when playing a captured video file.
• The Ping Gateway on Startup network setting does not work.
• In some cases, running the Advanced Power Capping Microcontroller Firmware causes future component updates to fail.
• The UID LED might stop blinking when the Remote Console is still open after a system power cycle.
• The invalid error "Duplicate record exists" occurs while adding a new directory group.
• A user with the Virtual Power and Reset privilege cannot use the Swap ROM feature.
• DL580 servers report an incorrect Power Redundancy state on removal of a power supply cable.
• Intermittent missing OS name and version in get_server_name response.
• iLO Dedicated Network Port options are displayed on DL60 servers, which support only the Shared Network Port configuration.
• An incorrect error message is displayed when auto power-off is set via XML scripting during POST.
• The Get_Embedded_Health.xml output displays incorrect iLO NIC information.
• The user name is not displayed in the iLO Event Log when a Language Pack is uninstalled.
• There is a discrepancy between the iLO web interface and XML scripting when an HP SSO record is added by DNS name.
• The Serial Command Line Speed setting is not saved when the speed is changed in the iLO 4 Configuration Utility.
• LDAP does not work after updating from iLO firmware version 1.40 to 1.50.
• New iLO Federation groups default to the power capping value from a previously deleted group.
• The Link State NIC setting is displayed on the Network General Settings page for BL460t servers when this setting is not supported on server blades.
• SNMP and SNMP trap ports cannot be set without the SNMP_ACCESS tag.
• The iLO Event Log does not record an event when the AlertMail settings are changed via RIBCL and CLP.
• The power redundancy status is incorrect when a mismatched power supply is inserted without a power cord.
• The iLO Event Log does not record an event when the Remote Syslog settings are changed via RIBCL.
• An incorrect error message occurs when the server name is set via XML during POST.
• The Asset Tag can be configured via XML when the server is off.
• An invalid domain name can be configured in the iLO 4 Configuration Utility.
• The iLO 4 Configuration Utility prompts the user to save and reset iLO when no change was made.
• Cert_Request.xml does not display an error when invalid characters are used for the state, country and locality.
• If the Delete SSH Key button is clicked when no SSH key is installed, the message "Public Key deleted" is displayed even though there was no installed SSH key.
• When the RESTful Interface Tool is used to display the system ROM version, the output incorrectly displays the backup system ROM version.
• The CLI does not display the oemhp_powercap information when power capping is disabled.
• Multiple incorrect "faulty/unsupported power supply" messages are recorded in configurations that use the HP 800W/900W Gold AC Power Input Module or the HP Server RPS Backplane Kit.
• Pwrstat displays incorrect power supply status information for the HP 800W/900W Gold AC Power Input Module and the HP Server RPS Backplane Kit.
• An intermittent virtual CD disconnection occurs during a system reboot.
 
 Note: To address the “POODLE” security vulnerability, the iLO security policy has changed in version 2.03 and SSLv3 is now disabled. You might need to enable TLS (Transport Layer Security) in your browser in order to access the iLO web interface.  TLS is the successor to SSL (Secure Sockets Layer

Enhancements
This version adds support for the following features and enhancements:

• New CLI and RIBCL commands for sending SNMP test traps.
• Agentless Management support for standup storage card firmware versions.
• The iLO IP address can now be used as the SubjectAltName in a certificate signing request.
• IPMI transport over IPv6.
• HP RESTful API updates, including support for:
  - Mezz and base FRUs
  - GET of data to retrieve the Active Health System log
  - Support Logs
• Flex Slot Battery Backup Unit information is displayed on the Information > System Information > Power page.
• Physical and logical network adapters are displayed on the Information > System Information > Network page.
• NIC teaming information is displayed on the Information > System Information > Network page.
• Information about devices installed on the system board, such as adapters, PCI devices,  SATA controllers, and Smart Storage Batteries is displayed on the new Information > System Information > Device Inventory page.
• HP and third-party storage controllers that manage direct-attached storage and the attached physical drives are displayed on the Information > System
  Information > Storage page.
• HP Smart Storage Battery information is displayed on the Information > System Information > Summary, Information > System Information > Power, and Information > System Information > Device Inventory pages.
• In addition to the supported OEM parameters, the IPMI boot options for UEFI now support the standard parameters.
• Extended the functionality of Lock_Configuration.xml to include restricting the IPMI interface from the system channel.
• Added support for IPMI 2.0 PEF and PET generation to the IPMI interface.


Version:2.03 (10 Nov 2014)
Fixes
Upgrade Requirement:
Recommended - HPE recommends users update to this version at their earliest convenience.

Improved the reliability of DIMM SPD read/write operations.
A timing issue could cause intermittent Windows Hardware Error Architecture (WHEA) test failures.
Booting from an SD card with ESXi could fail.
AMD-based HP ProLiant Gen 8 servers with iLO 4 2.00 or 2.02 might report incorrect processor temperatures.
HP ProLiant Gen 8 servers with iLO 4 2.00 or 2.02 might report an incorrect value for the temp1 sensor.
HP ProLiant Gen8 servers with iLO 4 2.00 or 2.02 might display an incorrectly lit FAN1 Systems Insight Display (SID) LED when no FAN1 is installed.
Partitions on the NAND device might fail to mount.  In some cases, this could result in Active Health System download failures or the Embedded User Partition might not be available.
Addressed SSRT101745
Addressed SSRT101790
Note: To address the “POODLE” security vulnerability, the iLO security policy has changed and SSLv3 is now disabled. You may need to enable TLS (Transport Layer Security) in your browser in order to access the iLO web interface.  TLS is the successor to SSL (Secure Sockets Layer).
 
 
 

Enhancements
Added support for TLS v1.1 and TLS v1.2 when using HTTPS URLs with iLO scripted virtual media, firmware update, certificate import, SSH key import, and for HP remote support registration and data collection.

Version:2.02 (6 Oct 2014)
Fixes
Upgrade Requirement:
Optional - Users should update to this version if their system is affected by one of the documented fixes or if there is a desire to utilize any of the enhanced functionality provided by this version.

The iLO Link-Local IPv6 address is displayed during POST when iLO is using the Shared Network Port, but the Shared Network Port does not support IPv6.
The inlet air sensor is not displayed on the temperature graph.
The Memory page is displayed incorrectly on ProLiant DL580 Gen8 servers.
The following message appears during POST after RBSU changes are made and the IML is cleared: iLO FW communication issue-Unable to communicate with iLO FW.
A “repaired” message is automatically posted to the IML after a Critical Fan Event.
Power button actions do not respond in the HP RESTful API.
IPMI Alert Immediate (Get Alert Status) always returns an error completion code.
Component firmware flash status is not shown at the bottom of the iLO web interface window.
The Remote Console crashes when a URL greater than 256 bytes is mounted.
Multiple 6064 SNMP Correctable Memory Error Trap occur when only one is expected.
iLO RBSU incorrectly provides the Transceiver Speed Autoselect menu option when the server uses Shared Network Port mode.
An incorrect error message is displayed when the boot order is changed by a user without the Configure iLO Settings privilege.
The Enable Active Health System logging check box and Apply button are active when the Active Health System has been disabled in hardware by using a motherboard switch.
Fan Blowout during POST due to a jammed rotor  continues to occur when the OS is running and the rotor has been repaired.
 iLO RBSU does not correctly check user privileges.
iLO RBSU incorrectly uses a maximum of 19 characters for user names.
The embedded Remote Support services fails to detect an Uncorrectable memory error event.
Cache module status is displayed for HP Dynamic Smart Array B140i Controllers.
Storage configuration changes are not updated in iLO until the server OS is started.
There are virtual media mounting problems when using the HP RESTful API.
Multiple mismatched power supplies are not detected.
The Active Health System page shows the estimated size of entire log file as Unknown.
The iLO web interface crashes when a user browses to the Memory page.
The Join Group button on the Administration > iLO Federation page is unavailable until the browser is refreshed.
A 404 error occurs when the HP RESTful API is used to access any path underneath /rest/v1/systems/1/bios.
 
Enhancements
The following condition was added for DIMMs: "Good, Partially in Use.”
The RIBCL Get Embedded Health has been updated for the following AMP modes: Channel Sparing, Rank Sparing, Intrasocket Mirroring, and Intersocket Mirroring.

Version:2.00 (9 Sep 2014)
Fixes
Upgrade Requirement:
Optional - Users should update to this version if their system is affected by one of the documented fixes or if there is a desire to utilize any of the enhanced functionality provided by this version.

Fixes:
• The error "Max number of certificates has been reached" occurs when SSO certificates are imported.
• The iLO Shared Network Port cannot be enabled for embedded LOM via the ROM-based setup utility or iLO web interface.
• iLO cannot be enabled via the iLO RBSU if it was disabled by using the iLO 4 Configuration Utility in the UEFI System Utilities.
• DHCP options can be modified via the ROM-based setup utility when DHCP is disabled.
• The System Information Health Summary page shows an Undefined error message on DL380p Gen8 servers.
• iLO requires a reset for IPv6 Multicast Scope changes.
• The iLO clock is one hour fast during Daylight Savings Time when it is configured by the ROM-based setup utility or the Insight Management Agents.
• The power supply status for an installed power supply is incorrectly displayed as "Not installed" on the System Information Power Information page in the iLO web interface.
• An error message is not displayed when an invalid Gateway IPv4 address is configured. 
• Users without the Configure iLO Settings privilege can modify iLO ROM-based setup utility settings. 
• The character limit for the Server Name is inconsistent between the iLO web interface and the CLI.
• The power supply status shows Failed/Good, In Use when the power cord is removed from the server.
• Embedded Remote Support fails after sending a second test service event.
• The iLO Firmware cannot be updated via the Group Firmware Update feature.
• The 24-hour power graph does not include all available power data.
• Characters are missing on the Group Virtual Media page after a disk image is connected through a URL.
• The Login Security Banner display on the Login page is incomplete.
• The CLI hangs after Virtual Media is mounted through a URL.
Enhancements
Enhancements:
 
Gen 9 ProLiant Servers Only
• Manual iLO reboot via the server UID button—Allows you to use the server UID button to initiate a graceful iLO reboot or a hardware iLO reboot.
• HP ProLiant Pre-boot Health Summary—Displays diagnostic information on the server monitor when the server is off and power is available.
• 1 GB Embedded User Partition—Allows you to use a 1 GB non-volatile flash memory partition as if it was an SD-card attached to the server.
 
Gen 8 and Gen 9 ProLiant Servers
• iLO Federation Group License Activation—Supports license key installation on multiple systems.
• Group configuration for iLO Federation Groups—Allows you to configure groups for the systems in an iLO Federation Management group. Configuring the group memberships of individual systems is still supported.
• HP RESTful API—The HP RESTful API is a management interface that server management tools can use to perform configuration, inventory, and monitoring of an HP ProLiant server via iLO.
 

Feature previews:
• Shared Network Port port selection—Allows you to choose between port 1 and port 2 for Shared Network Port functionality. You can configure this setting on the Network > Shared Network Port > General page in the iLO web interface.
    NOTE: Not all sideband NICs are supported. In some cases, port 2 might not be fully functional.
   
• iLO network connection auto-select—Allows you to configure iLO to automatically select the iLO Dedicated Network Port or Shared Network Port, based on the detected network activity. This feature can be configured by using the iLO CLI or XML scripting.


Version:1.51 (23 Jun 2014)
Fixes
Upgrade Requirement:
Critical - HPE requires users update to this version immediately.

Intermittent Non-Maskable Interrupt (NMI) Events May Occur on HP ProLiant Gen8 Servers running HP Integrated Lights-Out 4 Firmware Versions 1.30, 1.32, 1.40 and 1.50.

1.51 Fixes:
- Intermittent Non-Maskable Interrupt (NMI) Events May Occur on HP ProLiant Gen8 Servers running HP Integrated Lights-Out 4 Firmware Versions 1.30, 1.32, 1.40 and 1.50.

1.50 Fixes:
- Auto Power On does not work on server blades after upgrading to iLO 4 v1.40.
- SSH keys cannot be imported by using XML after upgrading to iLO 4 v1.40.
- Random "Embedded Flash/SD-CARD: Failed restart" errors appear in the iLO 4 Event Log after server shutdown.
- The Windows Server 2008 or 2012 installer might fail with the following error message when used with Virtual Media on iLO 4 1.32 and 1.40: “A required CD/DVD drive device driver is missing."
- If you create a disk image when Virtual Media is mounted in the Java IRC, an invalid message is displayed.
- The keyboard doesn't work when you use the Java IRC to mount an image file through a URL.
- When using the Java IRC in Linux, some characters cannot be entered from a Japanese keyboard when the Japanese layout is selected.
- iLO might stop responding if the DNS server fails to respond when iLO is trying to log multiple entries that require DNS reverse lookup.
- Time zones that are south of the Equator and use DST are handled incorrectly.
- An incomplete Japanese message is displayed in the Set to factory defaults interface when the Japanese Language Pack is loaded.
- AlertMail implementation is inconsistent between the iLO web interface and the CLI.
- iLO does not always respond to multicast M-SEARCH requests.
- Multicast replies display an incorrect iLO version number.
- iLO requires a reset when the IPv6 Multicast Scope is changed for iLO Federation discovery.
- The SERVER_POST_STATE element is missing from RIBCL output.
- iLO Virtual Media CD-ROM connect says “ok” when http://name is unreachable.
- Multiple iLO Federation Management groups cannot be deleted in a certain order.
- Menu and Title area return to English characters when the Japanese Language Pack is loaded.
- EBIPA IPv6 settings not always updated on iLO when iLO DHCP IPv4 is disabled.
- iLO WEB page could stop responding after a firmware update via the group firmware update in iLO Federation Management.

 



Enhancements
1.50 Enhancements:
- Added an SNMP trap for Uncorrectable Machine Check Error.
- Added the ability for iLO to get Domain name to Get or Display from DHCPv6
  server.
- Implemented significant performance improvements in iLO Federation Management
  queries.

Version:1.50 (12 May 2014)
Fixes
Upgrade Requirement:
Recommended - HPE recommends users update to this version at their earliest convenience.

Fixes:
- Auto Power On does not work on server blades after upgrading to iLO 4 v1.40.
- SSH keys cannot be imported by using XML after upgrading to iLO 4 v1.40.
- Random "Embedded Flash/SD-CARD: Failed restart" errors appear in the iLO 4 Event Log after server shutdown.
- The Windows Server 2008 or 2012 installer might fail with the following error message when used with Virtual Media on iLO 4 1.32 and 1.40: “A required CD/DVD drive device driver is missing."
- If you create a disk image when Virtual Media is mounted in the Java IRC, an invalid message is displayed.
- The keyboard doesn't work when you use the Java IRC to mount an image file through a URL.
- When using the Java IRC in Linux, some characters cannot be entered from a Japanese keyboard when the Japanese layout is selected.
- iLO might stop responding if the DNS server fails to respond when iLO is trying to log multiple entries that require DNS reverse lookup.
- Time zones that are south of the Equator and use DST are handled incorrectly.
- An incomplete Japanese message is displayed in the Set to factory defaults interface when the Japanese Language Pack is loaded.
- AlertMail implementation is inconsistent between the iLO web interface and the CLI.
- iLO does not always respond to multicast M-SEARCH requests.
- Multicast replies display an incorrect iLO version number.
- iLO requires a reset when the IPv6 Multicast Scope is changed for iLO Federation discovery.
- The SERVER_POST_STATE element is missing from RIBCL output.
- iLO Virtual Media CD-ROM connect says “ok” when http://name is unreachable.
- Multiple iLO Federation Management groups cannot be deleted in a certain order.
- Menu and Title area return to English characters when the Japanese Language Pack is loaded.
- EBIPA IPv6 settings not always updated on iLO when iLO DHCP IPv4 is disabled.
- iLO WEB page could stop responding after a firmware update via the group firmware update in iLO Federation Management.

 



Enhancements
Enhancements:
- Added an SNMP trap for Uncorrectable Machine Check Error.
- Added the ability for iLO to get Domain name to Get or Display from DHCPv6
  server.
- Implemented significant performance improvements in iLO Federation Management
  queries.

Version:1.40 (18 Feb 2014)
Fixes
Upgrade Requirement:
Optional - Users should update to this version if their system is affected by one of the documented fixes or if there is a desire to utilize any of the enhanced functionality provided by this version.

 FIXES:
The following issues are resolved in this firmware version:
 
- Server Auto Power-On might be triggered when iLO is reset through IPMI.
 
- Firmware updates that use USB Virtual Media might fail due to secure flash image corruption.
 
- SSH sockets might take 30 seconds to close.
 
- The GET_OA_INFO command output does not include the OA IPv6 address.
 
- The iLO 4 SNMP stack might become unresponsive to SNMP requests.
 
- The file upload section is not displayed on the iLO web interface Firmware page.
 
- The Integrated Remote Console (IRC) stops working when iLO is busy.
 
- The .NET Integrated Remote Console (IRC) fails to start in Chrome if a trusted certificate is not installed.
 
- Kerberos Keytab files cannot be added from the iLO web interface.
 
- An error occurs if you register for Remote Support with proxy settings, and then you delete the proxy settings.
 
- Directory settings information is not consistent between the iLO web interface and the scripting interfaces.
 
- The server shuts down when a user exits the system RBSU during an iLO reset.
 
- Kerberos Keytab files cannot be added when FIPS mode is enabled.
 
- A service event is not generated when a hard disk drive fails during boot.
 
- The Acquire dialog box is displayed when the remote console is started, but there is no active
  session to acquire.
 
- The status of a spare drive changes to inactive when the spare drive is in use.
 
- When the security override switch is enabled, long login names might fail.
 
- TPM status cannot be viewed by using XML scripts.
 
- The IPv6 default gateway might be saved as a static default gateway.
 
- When configured for FIPS mode/AES-DES the key exchange method ‘diffie-hellman group1 sha1’ should not be supported.
 
- The iLO clock fails to synchronize with NTP when a Primary Time Server is not entered.
 
- The iLO webserver unexpectedly quits after the NVRAM is cleared.
 
- The iLO DHCPv6/EBIPA address is not displayed in OA when OA is configured on an IPv6-only network.
 
- The Backup ROM date is displayed incorrectly on the Diagnostics page in the iLO web interface.
 
- The IPMI Get Sensor Reading command returns incorrect data for the Inlet Ambient sensor.
 
- Auto Power-On takes two minutes when the delay is set to 15, 30, 45, or 60 seconds.
 
- Some Power On Self Test (POST) errors might be truncated in the Integrated Management Log (IML).
 
- The output of the RIBCL GET_POST_STATE command shows the output for the HOST_POWER command.
 
- If the Shared Remote Console feature is not licensed, an error message should be displayed when a user
  clicks the Share button.
 
- iLO cannot be configured to propagate the NTP or OA time setting to the host.
 
- An SSH session is not logged out when AES/3DES is enabled or disabled by using the CLI.
 
- The iLO CLI and web interface have different length requirements for the FQDN.
 
- There is no warning message in the CLI when the power mode is set to OS control.
 
- The Login Security Banner does not work consistently between the iLO web interface and iLO scripts.
 
- The remote console displays multiple CD-ROM drives with the same drive letter.
 
- The SSH interface might freeze after multiple back-to-back connections.
 
- An iLO system with no installed certificates reports that the maximum number of certificates is reached.
 
- The temperature graph in the iLO web interface shows details for only one sensor when multiple sensors have
  the same coordinates.
 
- The SNTP settings are not displayed in the iLO web interface after a firmware update.
 
- An error occurs when the iLO firmware is updated by using the CLI.
 
- The CPU temperature is reported incorrectly.
 
- An event is not generated when the default language is changed by using scripts or the CLI.
 
- An error message is not displayed when an incorrect firmware URL is entered.
 
- The Integrated Management Log (IML) displays an error when a maintenance note is entered.
 
- An event is not generated when a power-on error occurs.
 
- The VLAN tag cannot be configured by using the iLO RBSU.
 
- The iLO firmware date is displayed incorrectly in the iLO RBSU.
 
- A warning message does not occur when the Local User Accounts setting is changed to Disabled for an iLO system that does not have a configured directory.
 
- The power-on delay options are inconsistent between the iLO web interface and the CLI.
 
- The Intelligent Provisioning version is not displayed on the iLO System Information > Firmware page.
 
- The Enterprise Secure Key Manager (ESKM) certificate is deleted if no certificate name is entered.
 
- The CLI labels a mismatched power supply with OK status.
 
- An event is not generated when a language pack update fails.
 
- An event is not generated when the Power Regulator settings are modified.
 
- WINDBG with port number 65535 cannot be enabled from the iLO CLI.
 
- Duplicate IP addresses are not detected.
 
- iLO 4 1.20 and later does not send ARP before replying to a ping request. This causes iLO 4 to be unreachable to pings from clients with teamed NICs.
 
- Solaris 10 and 11 cannot be installed by using Virtual Media
 
- The SNTP time zone offset is incorrectly applied to the time provided by the OA when c-Class blade servers are inserted into the enclosure or are e-fused.
 
- When the server serial number is updated in the BIOS, the system board FRU data is not updated.

Enhancements
 ENHANCEMENTS:
 
This version adds support for the following features and enhancements:
 
- iLO Federation Management
  NOTE: iLO Federation Management is supported on IPv4 and IPv6 networks on the iLO Dedicated     Network Port.  It is not supported on iLO Shared Network Port.
 
- Insight Remote Support Direct Connect configuration is available in iLO 4 1.40 and later.
 
- iLO 4 1.40 and later supports the HP Enterprise Secure Key Manager ESKM 3.1 and later,
  which can be used in conjunction with HP Secure Encryption.
 
- Improved Java Integrated Remote Console (IRC)
 
- UEFI System Utilities support on the HP ProLiant DL580 Gen8 server.



Version:1.32 (11 Nov 2013)
Fixes
Upgrade Requirement:
Recommended - HPE recommends users update to this version at their earliest convenience.

A security vulnerability related to SSRT101323 has been addressed.
A security vulnerability related to SSRT101336 has been addressed.
The iLO ROM-Based Setup Utility (RBSU), which is accessed via F8 at Power On, was reduced in fit in a 64KB size limit.
iLO allowed some ciphers other than AES/3DES to be used when the AES/3DES Encryption Enforcement Settings were enabled.
Firmware upgrades were slow or problematic following a failed URL-based/scriptable virtual media floppy drive session.
A boot issue might occur if embedded media was not ready during POST due to an unexpected power event.
iLO might crash when the Import Direct DNS Name button is clicked on the Security - Single Sign-On Settings page or when a certificate is imported by using RIBCL.
Blade servers might hang during POST if a smart component tries to cold-boot the system.
IPMI transactions to read the power consumption from Power Supplies P/N 499250-201 might report an incorrect value of zero watts.
CPU overheating messages could be incorrectly detected and logged in the IML and causing iLO to initiate a server shutdown.
SSH Channel could close unexpectedly after one command is executed.
SSH interface could lock up after multiple back to back connections.

Version:1.30 (10 Sep 2013)
Fixes
Upgrade Requirement:
Optional - Users should update to this version if their system is affected by one of the documented fixes or if there is a desire to utilize any of the enhanced functionality provided by this version.

The following issues are resolved in this firmware version:
 

A possible security vulnerability related to SSRT101250 existed.
The Integrated Remote Console (IRC) playback video could stop responding after recording.
An incorrect entry was logged to the iLO Event Log when the IRC was launched to join a Shared Remote Console session.
The iLO firmware replaced the server Real Time Clock (RTC) time with the iLO Network Time Protocol (NTP) time on every server reboot. The RTC is now set with the NTP time only when the server is plugged in and returns from an unpowered state.
No SNMP alert was logged in HP SIM on failed iLO login attempts.
The JAVA Integrated Remote console (JIRC) could not launch with HP SIM Single Sign On (SSO).
The iLO SSH Server disconnected sessions during re-key operations.
When importing new HP SSO certificates, a “Certificate Could Not Be Stored” error might occur.
The Integrated Remote Console (IRC) might not be able to play a Pre-failure video downloaded from a web server.
Mismatched Power Supply entries in the Integrated Management Log (IML) were not repaired after the correct power supply was installed.
The Event log failed to display the user name when Lock_Config was enabled.
No XML Logout iLO Event Log entry is recorded when a user logged out via HPONCFG.
No iLO Event Log entries are recorded when IPMI/DCMI is set to Enabled or Disabled by using Mod_Global_Settings.xml.
No iLO Event Log entries are recorded when Directory settings are modified through the CLI and XML scripts.
No CLI option is provided to change the SNMP port and the SNMP trap port.
The Power-On Delay cannot be set to Minimum Delay or Random up to 120 seconds on the Server Power page.
Enhancements
This version adds support for the following features and enhancements:
 
 

System ROM, Chassis Manager, CPLD, and Power Management Controller firmware can be updated in the iLO web interface and via RIBCL scripts.
IPv6 network communications (dedicated network connection only). In addition to the features supported in iLO 4 1.2x, the following features are supported:
RIBCL/XML scripting
SNMPv3
Additional IPv6 functionality was added to the iLO utilities.
The following Server Power-On Delay options are available: 15, 30, 45, and 60 seconds.
RIBCL can be used with Single Sign-On (SSO).
New web server with improved performance and reliability.
New SSH server with improved performance and reliability.
The System Information > Memory page displays the HP part number for DIMMs.
The supported size for Encoded Kerberos tickets increased to 16 KB.
SNMP trap 9001 covers all server reset cases instead of only cases in which iLO governs the reset.
SNMP Traps are sent if communication between iLO and Insight Remote Support or iLO and Insight Online fails.
Improved download performance for the Active Health System log.
 


Version:1.22 (23 Apr 2013)
Fixes
Upgrade Requirement:
Recommended - HPE recommends users update to this version at their earliest convenience.

Corrected an issue where a spurious power supply event could cause a system to shutdown and record an IML entry due to noise in the power supply presence and status signals.
iLO 4 will no longer incorrectly report a failed power supply in the IML  when some power supply insertions are conducted with mismatched power supplies.
Corrected a General Power Supply failure message in the IML when there is a power loss or the power cord was not attached to one of the power supplies.
Fixed an issue in which iLO Virtual Serial Port Log playback ends too early or too late, preventing logged data from  being displayed, or displaying old data in the wrong location.  The iLO Virtual Serial Port Log playback now stops at the end of the stored data.
Corrected a Self-Signed certificate expiration date issue that occurred when iLO is set to the factory default settings after the year 2012.  This may occur if iLO generates a new SSL self-signed certificate after January 18th, 2013.
Resolved an issue in which SSH sessions could be abruptly closed, leaving the server side socket in an undetected error condition.  This could lead to no more available SSH sockets until the next iLO reset.
Enhancements
Improved Active Health System logging for newly added log entries.
The persistent mouse and keyboard setting can now be configured by using the set_persmouse_status.xml script.  

Version:1.20 (19 Feb 2013)
Fixes
Upgrade Requirement:
Optional - Users should update to this version if their system is affected by one of the documented fixes or if there is a desire to utilize any of the enhanced functionality provided by this version.

- The HTTP TRACE method in the iLO 4 webserver is now disabled. Having
  this feature enabled caused some security scanners to report it as a
  vulnerability.

- iLO 4 no longer fails to synchronize the date and time with the Onboard Administrator.

- The iLO 4 Certificate Signing Request countryName object was changed from a UTF8 object to
  a printable string. This will prevent some Certificate Authorities from rejecting the iLO 4 CSR.

- The Integrated Remote Console will now disconnect Virtual Media when the USB flash drive is
  physically removed.

- The Integrated Remote Console no longer fails to open and displays “HTTP error: The operation
  has timed out”.

- iLO 4 will no longer become inaccessible for 40 minutes after an unreachable SNMP alert destination
  is entered.

- iLO 4 on BL460c Gen8 servers will no longer log the random event "System Overheating (Temperature
  Sensor 3, Location CPU, Temperature 0C)" in the IML if the second processor isn’t populated.

- The SNMP tags have been removed from the MOD_GLOBAL_SETTINGS command. TO modify the SNMP
  parameters, you must now use the MOD_SNMP_IM_SETTINGS command.

- The pre-failure video playback will no longer end without showing video.

- A user with insufficient privileges can no longer modify the network settings by using the
  iLO command line interface.

- Increased buffer size to allow the importing of a X.509 certificate file up to 3072 bytes long (Base64 encoded).

Enhancements
- IPv6 support for web GUI and Integrated Remote Console on iLO dedicated network

- Support for SNMP v3

- Location Discovery Services (BL/SL)

- 3D temp graph

- Support for Remote Syslog of server events

- Support for e-Mail alerting of server events

- Serial Console Record/Playback

- Support for new iLO Essentials license option

- Support for new iLO Scale-Out license option

- FIPS  (Federal Information Processing Standard) Mode compliance support**

- Integrated Remote Console now supports .NET Framework v4.0

 


Version:1.13 (13 Nov 2012)
Fixes
Upgrade Requirement:
Recommended - HPE recommends users update to this version at their earliest convenience.

Fixed a possible security vulnerability when using Integrated Lights-Out (iLO's) Integrated Remote Console. Please see Security Bulletin SSRT100934 for more information.

Enhancements
Condensed the Active Health System (AHS) log data to enhance iLO memory capabilities


Version:1.10 (4 Sep 2012)
Fixes
Upgrade Requirement:
Optional - Users should update to this version if their system is affected by one of the documented fixes or if there is a desire to utilize any of the enhanced functionality provided by this version.

Fixed an issue where updating iLO 4 firmware could stay at 1% and not complete correctly

Fixed issue in which fan speed/airflow impedance occurs in certain situations.

Updated the Factory_Defaults.xml script to include clearing the iLO and IML logs.

Fixed an issue in which the server would auto power-on unexpectedly when iLO defaults were set using RIBCL.

The iLO web interface and XML now show N/A for Total Memory Size, Operating Frequency, and Operating Voltage for empty processor sockets.

Updated SET_HOST_APO.XML to use iLO user permissions.

Changes to boot order in the iLO web interface and XML scripts now require the Virtual Power and Reset permission.

Fixed Get_All_Languages.xml to work with CPQLOCFG.

Fixed an issue where the iLO web interface displays the wrong message for an invalid SID.

Fixed an issue where Clear_AHS_Data.xml will not execute successfully when AHS is disabled through the iLO web interface.

The iLO Event Log now logs the name of the user that ran Clear_AHS_Data.XML.

Fixed the Clear_AHS_Data.xml informational message.

Removed unrelated VSP messages when running Mod_VSP_Flow_Control.

Fixed the Set_Server_Name.xml log entry in the iLO Event Log.

Fixed synchronization issues with the Power Regulator Values in iLO web interface and XML scripts.

Fixed Get_Network.XML to display correct network information when the iLO 4 configured link is set to Auto.

Fixed invalid XML response for Get_All_Languages.xml and Get_Language.xml.

Fixed the Get_EmHealth.xml Storage Controller label.

Fixed the IRC playback video when the server is powered off.

Fixed IRC intermittent hang when un-mounting virtual media during a server reboot.

Fixed the issue that caused an SSH session to disconnect when the IRC Trust Setting is changed.

Fixed an issue that caused the .NET IRC to prompt for user credentials when started from the iLO web interface.

Fixed an issue that caused the numeric keypad  to work incorrectly in some situations.

Fixed intermittent Unknown status for System Health, Server Power and UID in the iLO web interface Overview page.

Fixed an issue that caused a DHCP supplied time zone not to be applied to the time iLO obtained from an SNTP server.

Fixed a temporary loss of communication with Smart Array firmware which could lead to iLO noting a critical storage condition.
For more information, see the CA: http://h20000.www2.hp.com/bizsupport/TechSupport/Document.jsp?locale=en_US&objectID=c03384383.

Fixed an issue in which the server remains to be powered off when issuing a shutdown command (f12 > F2) using ESXi 5.0 U1.

Fixed intermittent communication issues between iLO and a Smart Array Controller.

Fixed the iLO web interface System Information page to display correct fan speed and temperatures.

Various SNMP performance enhancements.

Reworded the event log message to better identify when non-iLO firmware is flashed.

Added controlled stepping of fan speed to avoid large fan speed changes that could cause fan failures.

Enhancements
Support for HP Insight Remote Support 7.0 and later.

Support for Location Discovery Services (ML and DL servers only).

Support for configurable Remote Console hot keys.

Integrated Management Log enhancements (iLO web interface): Added the ability to change the status of Critical or Caution events to Repaired. Added the ability to add a Maintenance Note to the IML log.
Added logging for some Smart Array storage events.
Added a customizable login security banner.
Added more defined SNMP traps related to the server power state.
Changed the handling of cache modules in order to not report an error for normal conditions such as cache recharging or logical drive expansion.

Improved iLO Event Log message when non-iLO firmware is flashed.

Added CLI performance improvements.

Added CLI support for adding and removing SSH keys.

Added manual_ilo_reset to the CLI, which allows network changes without an immediate reset.

Version:1.05 (4 Jun 2012)
Fixes
Upgrade Requirement:
Optional - Users should update to this version if their system is affected by one of the documented fixes or if there is a desire to utilize any of the enhanced functionality provided by this version.

- Feature not supported message was not displayed for all tags for some xml scripts
- User could not set MIN_PASSWORD to zero (0) using a RIBCL script
- Could not import SSH key via RIBCL if the key is for the Administrator account
- Unable to restore the captured file from HPONCFG on Blade Servers
- Incorrect error message when SSH Port was left blank in HPONCFG or XML scripts
- IRC session gets disconnected after a minute after booting into the server OS
- Possible mismatch representation between ILO CLI and GUI network gateway setting
- Physical DVD on HP BladeSystem c3000 Enclosure might fail to mount correctly via Scriptable VM
- No event was logged when SSH Key was deleted

Enhancements
- The iLO SNMP interface will react to excessive activity to SNMP Network port 161 to prevent “Denial of Service” type attacks
- When the Agentless Management Service (AMS) is installed on the host operating system, the iLO “Server Name” will be updated. This overwrites the information entered in the iLO GUI (same behavior in iLO 3 under Windows)
- The HP SmartMemory Technology is better displayed on the System Information Memory page
- There is support for iLO 4 monitoring larger, internally attached storage enclosures
- When the Agentless Management Service (AMS) is installed on the host operating system, the host Network Link status will be displayed, even if “SNMP Pass-thru” is enabled
- NIC Link Status:  The host OS “network LINK” status will be better reflected in the iLO GUI. If no cable is connected to the port AND the NIC is disabled by the HOST, the GUI will show “Informational” rather than “Link Down”
- When the Agentless Management Service (AMS) is installed on the host Linux operating system, events logged to the Integrated Management Log (IML) are also logged to the Linux “messages” file

Version:1.01 (27 Mar 2012)
Enhancements
Upgrade Requirement:
Optional - Users should update to this version if their system is affected by one of the documented fixes or if there is a desire to utilize any of the enhanced functionality provided by this version.

Initial Release with the following features:

 iLO 4 supports HP Active Health System, HP's always-on diagnostic capability that is new for Gen8 HP ProLiant servers
 iLO 4 supports HP Agentless Management for out-of-the box SNMP-based server management that does not require OS-based Agents
 iLO 4 supports the new, built-in Intelligent Provisioning capability for easy server setup which is new for Gen8 HP ProLiant servers
 iLO 4 supports up to 1Gbit dedicated LAN access on Gen8 HP ProLiant ML/DL/SL servers

Legal Disclaimer: Products sold prior to the November 1, 2015 separation of Hewlett-Packard Company into Hewlett Packard Enterprise Company and HP Inc. may have older product names and model numbers that differ from current models.
