FILE NAME:    iLO4_273.bin
TITLE:        iLO 4 firmware v2.73

LANGUAGE:  English

DIVISIONS:  Systems

PRODUCTS AFFECTED:

  HPE ProLiant BL660c Gen9 Server Blade   
  HPE ProLiant BL460c Gen9 Server Blade 
  HPE ProLiant DL580 Gen9 Server   
  HPE ProLiant DL560 Gen9 Server
  HPE ProLiant DL380 Gen9 Server  
  HPE ProLiant DL360 Gen9 Server
  HPE ProLiant DL180 Gen9 Server 
  HPE ProLiant DL160 Gen9 Server 
  HPE ProLiant DL120 Gen9 Server
  HPE ProLiant DL80 Gen9 Server
  HPE ProLiant DL60 Gen9 Server
  HPE ProLiant DL20 Gen9 Server
  HPE ProLiant ML350 Gen9 Server 
  HPE ProLiant ML150 Gen9 Server
  HPE ProLiant ML110 Gen9 Server
  HPE ProLiant ML30 Gen9 Server
  HPE ProLiant XL450 Gen9 Server
  HPE ProLiant XL750f Gen9 Server
  HPE ProLiant XL740f Gen9 Server
  HPE ProLiant XL730f Gen9 Server
  HPE ProLiant XL250a Gen9 Server 
  HPE ProLiant XL230a Gen9 Server  
  HPE ProLiant XL230b Gen9 Server
  HPE ProLiant XL190r Gen9 Server    
  HPE ProLiant XL170r Gen9 Server    
  HPE ProLiant WS460c Gen9 Graphics Server Blade    
  HPE ProLiant EC200a Server
  HPE Synergy 480 Gen9 Compute Module
  HPE Synergy 620 Gen9 Compute Module
  HPE Synergy 660 Gen9 Compute Module	
  HPE Synergy 680 Gen9 Compute Module 
  HPE ProLiant BL660c Gen8 Server Blade   
  HPE ProLiant BL465c Gen8 Server Blade   
  HPE ProLiant BL460c Gen8 Server Blade   
  HPE ProLiant BL420c Gen8 Server Blade
  HPE ProLiant DL580 Gen8 Server   
  HPE ProLiant DL560 Gen8 Server
  HPE ProLiant DL385p Gen8 Server   
  HPE ProLiant DL380p Gen8 Server   
  HPE ProLiant DL380e Gen8 Server   
  HPE ProLiant DL360p Gen8 Server   
  HPE ProLiant DL360e Gen8 Server   
  HPE ProLiant DL320e Gen8 v2 Server   
  HPE ProLiant DL320e Gen8 Server   
  HPE ProLiant DL160 Gen8 Server
  HPE ProLiant ML350e Gen8 Server   
  HPE ProLiant ML350p Gen8 Server   
  HPE ProLiant ML310e Gen8 v2 Server
  HPE ProLiant ML310e Gen8 Server
  HPE ProLiant SL4540 Gen8 Server   
  HPE ProLiant SL210t Gen8 Server   
  HPE ProLiant SL270s Gen8 Server   
  HPE ProLiant SL270s Gen8 SE Server   
  HPE ProLiant SL250s Gen8 Server   
  HPE ProLiant SL230s Gen8 Server 
  HPE ProLiant XL220a Gen8 Server
  HPE ProLiant MicroServer Gen8   
  HPE ProLiant WS460c Gen8 Graphics Server Blade   

OPERATING SYSTEM:

  Microsoft Windows Server 2008 *
  Microsoft Windows Server 2012
  Microsoft Windows Server 2012 Essentials
  Microsoft Windows Server 2012 R2
  Microsoft Windows Storage Server 2008
  Microsoft Windows Server 2016
  Microsoft Windows Server 2019
  Red Hat Enterprise Linux 6 (x86, AMD64/EM64T) 
  Red Hat Enterprise Linux 7
  SUSE Linux Enterprise Server 15
  SUSE Linux Enterprise Server 11 SP4 (x86, AMD64/EM64T)
  SUSE Linux Enterprise Server 12 SP3, 12 SP2
  VMware vSphere 6.7, 6.5 U1, 6.5 U2, 6.0 U3

  *Not supported on all platforms, see the OS support list for your platform. http://www.hpe.com/info/OSsupport 

SYSTEM CONFIGURATION:  N/A

PREREQUISITE:  N/A

BUILD DATE:      February 10, 2020    	
EFFECTIVE DATE:  February 13, 2020		


DESCRIPTION:   Firmware for the Hewlett Packard Enterprise
               iLO 4 Management Controller
               
LAST RECOMMENDED OR CRITICAL VERSION: 2.70


PREVIOUS VERSION: 2.72


UPGRADE REQUIREMENTS: OPTIONAL

  ***ATTENTION***
  Note for ESXi users: If you are booted from the Embedded SD Card, it is strongly 
  recommended that you reboot the server immediately after updating the iLO firmware.

FIRMWARE DEPENDENCY:

  Hewlett Packard Enterprise recommends the following or greater versions of iLO utilities
  for best performance:  
  
  - RESTful Interface Tool (iLOREST) 2.3
  - HPQLOCFG v5.2 
  - Lights-Out XML Scripting Sample bundle 5.10.0
  - HPONCFG Windows 5.3.0
  - HPONCFG Linux 5.4.0
  - LOCFG v5.10.0
  - HPLOMIG 5.2.0

KNOWN ISSUES: 
  - Fibre Channel Ports are displayed with degraded status if they are configured but not attached.

FIXES:
The following issues are resolved in this version:
  - Added fix for Embedded Remote Support in an IPv6-only environment.
  - Added fix for Embedded Remote Support data collection for systems with multiple Smart Array Controllers.


Enhancements:
  - Suppress SNMP traps for NIC link up/link down events that occur during POST.


SECURITY: 

  For the latest security bulletins and vulnerabilities, please visit: 
  https://support.hpe.com/hpesc/public/home
  
Security best practices:

  Please refer to the HPE Integrated Lights-Out Security Technology Brief for the latest on security best practices at:
  http://www.hpe.com/support/iLO4_security_en



  

Feature previews:
  - Shared Network Port, port selection: Allows you to choose between port 1 and 
    port 2 for Shared Network Port functionality. You can configure this setting
    on the Network > Shared Network Port > General page in the iLO web interface. 
    
    NOTE: Not all sideband NICs are supported. In some cases, port 2 might not 
    be fully functional.

         NICs that work with port #2 for sideband:
         HPE FlexFabric 10Gb 2-port 556FLR-T Adapter
         HPE FlexFabric 10Gb 2-port 533FLR-T Adapter
         HPE Ethernet 10G 2-port 562FLR-SFP+ ALOM
         HPE Ethernet  10/25G 2-port 640FLR-SFP28 ALOM
         HPE FlexFabric 10Gb 4-port 536FLR-T Adapter
         361i-2port-1GB NIC
         331FLR-4P-1G NIC
         366FLR-4P- 1G NIC
         561FLR-T-2P-10GB NIC
         526FLR-SFP+2P-10GB NIC
         InfiniBand QDR/Ethernet 10Gb 2-port 544+FLR-QSFP Adapter **Port #2 Only
         534FLR-SFP+2P-10GB NIC
         Ethernet 1GB 2-port 330i Adapter
         BCM57810 NetXtreme II 10 GigE (NDIS VBD)
         FlexFabric 10Gb 2-port 554FLR-SFP+ Adapter
         Ethernet 10Gb 2P 560FLR-SFP+ Adapter
  

SUPPORT -

1.  iLO 4 firmware updates and utilities can be found here:

      http://www.hpe.com/support/iLO4 

2. IPv6 network communications - Dedicated network connection only
     Supported Networking Features
                IPv6 Static Address Assignment
                IPv6 SLAAC Address Assignment
                IPv6 Static Route Assignment
                IPv6 Static Default Gateway Entry
                DHCPv6 Stateful Address Assignment
                DHCPv6 Stateless DNS, Domain Name, and NTP Configuration
                Integrated Remote Console
                OA Single Sign-On
                SIM Single Sign-On
                Web Server
                SSH Server
                SNTP Client
                DDNS Client
                RIBCL over IPv6
                SNMP
                AlertMail
                Remote Syslog
                WinDBG Support
                HPQLOCFG/HPLOMIG over an IPv6 connection
                Scriptable Virtual Media
                CLI/RIBCL Key Import over IPv6
                Authentication using LDAP and Kerberos over IPv6
                iLO Federation
                IPMI
     Networking Features not supported by IPv6 in this release 
 		IPv6 Over Shared Network Port Connections
                NETBIOS-WINS
                Enterprise Secure Key Manager (ESKM) Support
                Embedded Remote Support (ERS)

3. You might encounter a "data inconsistency error" when you use iLO Federation
   Management. This error occurs when an iLO on your network is not 
   responding correctly. Use the data on the Multi-System map page to 
   troubleshoot data inconsistency errors.

DOCUMENTATION -

1.  iLO 4 documentation is available at http://www.hpe.com/info/iLO/docs.

2.  Check the online help for information about how to use iLO. To access the 
    online help, Click the question mark icon in the upper right corner of 
    any iLO web interface page.

HOW TO USE -

1.  Download the iLO 4 Online Firmware Update Component for your
    operating system.

2.  Install the firmware using one of these options:

    a) Run the component on the host to be updated.
       The component will update the iLO 4 firmware and reset the iLO processor.

    b) Extract the firmware from the component. This will place the firmware
       image file, iLo4_yyy.bin (where yyy represents the firmware version), in
       the target directory.  You now have these options:

       i) Login to iLO, navigate to the Update Firmware page, and update the
          firmware from there.

       ii) Use the Lights-Out Configuration Utility (HPQLOCFG) and RIBCL/XML
           scripts to update iLO 4 across the network.

       iii) Use the Online Lights-Out Configuration utility (HPONCFG) and
            RIBCL/XML scripts to update iLO 4 from the supported host OS.

3.  iLO automatically resets after a successful update.
    There is no need to manually reset iLO.

Copyright 2002,2020 Hewlett Packard Enterprise Development, LP