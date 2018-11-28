# HPE_Microserver_Gen8
## Firmware
### iLO 4
|Version|Update Date|File|Note|
|----|----|----|----|
2.61|Jul 27 2018|[ilo4_v261.bin](files/ilo4_v261.bin)|BIN file, upgrade via web Admin->Firmware
2.61|Jul 27 2018|[ilo4_v261_lnx_firmware-ilo4-2.61-1.1.i386.rpm](files/ilo4_v261_lnx_firmware-ilo4-2.61-1.1.i386.rpm)|Linux 
2.61|Jul 27 2018|[ilo4_v261_lnx_README.md](ilo4_v261_lnx_README.md)|[Release Note (URL)](https://support.hpe.com/hpsc/swd/public/detail?sp4ts.oid=1009143853&swItemId=MTX_fa40c1bfdb924daf87a10fa810&swEnvOid=4184)
### System BIOS
|Version|Update Date|File|Note|
|----|----|----|----|
J06|05/21/2018|[CPQJ0613.4B5](files/CPQJ0613.4B5)|BIN file, upgrade via web Admin->Firmware 
J06|05/21/2018|[sbios_vj06_lnx_firmware-system-j06-2018.05.21-1.1.i386.rpm](files/sbios_vj06_lnx_firmware-system-j06-2018.05.21-1.1.i386.rpm)|Linux
J06|05/21/2018|[sbios_vj06_lnx_README.md](sbios_vj06_lnx_README.md)|[Linux Release Note (URL)](https://support.hpe.com/hpsc/swd/public/detail?sp4ts.oid=5390291&swItemId=MTX_6d14418a08954e5a8c8cb08bf0&swEnvOid=4184)
J06|05/21/2018|[sbios_vj06_usb_SP99339.exe](files/sbios_vj06_usb_SP99339.exe)|USB Key Media 
J06|05/21/2018|[sbios_vj06_usb_README.md](sbios_vj06_usb_README.md)|[USB Key Media Release Note (URL)](https://support.hpe.com/hpsc/swd/public/detail?sp4ts.oid=5390291&swItemId=MTX_c9a347de9ded465088b735c472&swEnvOid=4184)

### other firmware

### Other repo
* [chiphell - [NAS] HP ProLiant MicroServer Gen8迷你服务器 汇总贴：降噪、升级、改造](https://www.chiphell.com/thread-1196090-1-1.html)
* https://github.com/houselabs/gen8
    * HW/SW/Virtualization Hypervisor knowledge
    * esxi/vmware_remote_console_alfredworkflow
* https://github.com/mhycy/hardware-gen8-pwm-convert
    * MOD for PWM signal
    * offline post [mhycy_hardware-gen8-pwm-convert.md](mhycy_hardware-gen8-pwm-convert.md)
    * https://www.chiphell.com/thread-1087322-1-1.html
    * http://homeservershow.com/forums/index.php?/topic/7294-faking-the-fan-signal/
    * http://bbs.nga.cn/read.php?tid=6929793&rand=805
    * PHD2.0-2*3AW，6P, 脚距2.0mm ，双排卧插 袋装
        ```
        属性    参数值	
        商品目录	PCB连接器 - 针座，公插针	
        脚位数	 2x3	
        连接器类型	PH Connector	
        脚间距（同排单行）	2mm	
        公母头类型	Male	
        安装特性	Right Angle
        ```
* https://github.com/mhycy/hardware-gen8-sas-convert
    * MOD for SATA sockets
    * offline post [mhycy_hardware-gen8-sas-convert.md](mhycy_hardware-gen8-sas-convert.md)
* https://github.com/atyu30/hpgen8
    * obsolete version
    * cp034894.exe* hp-firmware-ilo4-2.55-1.1.i386.rpm
    * hpvsa-1.2.16-114.rhel7u4.x86_64.dd
    * lang_zh_250.lpk
* https://github.com/dschense/Proxmox-HP-Proliant-Microserver-Gen8-PCIE-Passthrough
    * patch for Proxmox kernel to support PCIE passthrough
    * obsolete because latest Proxmox already support (need to verify)
* https://github.com/swaygently/ansible-rose-gen8
    * Initialization HP MicroServer Gen8 server for RHEL/CentOS .
    * 初始化安装CentOS的HP MicroServer Gen8，安装mcp、初始化虚拟机。其中虚拟化了一台OPNsense作为软路由，其他的虚拟机连接到软路由的LAN口。
* https://github.com/GerGitHub/HPMicroserverGen8-ESXI-Windows-DSM
    * looks like NULL content