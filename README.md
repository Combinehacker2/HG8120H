# HG8120H
<5>Linux version 2.6.34.10_sd5115v100_wr4.3 (root@wuhci2lslx00064) (gcc version 4.4.6 (GCC) ) #1 SMP Mon Apr 18 21:20:00 CST 2016
<3>PHYS_OFFSET = 80900000.
<4>CPU: ARMv7 Processor [414fc091] revision 1 (ARMv7), cr=10c53c7f
<4>CPU: VIPT nonaliasing data cache, VIPT nonaliasing instruction cache
<4>Machine: sd511x
<4>Memory policy: ECC disabled, Data cache writealloc
<7>On node 0 totalpages: 30464
<7>free_area_init_node: node 0, pgdat c03e5700, node_mem_map c040a000
<7>  Normal zone: 238 pages used for memmap
<7>  Normal zone: 0 pages reserved
<7>  Normal zone: 30226 pages, LIFO batch:7
<4>SD511x chip id:0x51160100
<4>apb bus clk is 100000000
<6>PERCPU: Embedded 7 pages/cpu @c0500000 s4448 r8192 d16032 u65536
<6>pcpu-alloc: s4448 r8192 d16032 u65536 alloc=16*4096
<6>pcpu-alloc: [0] 0 
<4>Built 1 zonelists in Zone order, mobility grouping on.  Total pages: 30226
<5>Kernel command line: noalign mem=119M console=ttyAMA1,115200 ubi.mtd=1 root=/dev/mtdblock11 rootfstype=squashfs mtdparts=hinand:0x100000(startcode),0x7f00000(ubifs),-(reserved) pcie0_sel=x1 maxcpus=0 user_debug=0x1f panic=1 skb_priv=128
<6>PID hash table entries: 512 (order: -1, 2048 bytes)
<6>Dentry cache hash table entries: 16384 (order: 4, 65536 bytes)
<6>Inode-cache hash table entries: 8192 (order: 3, 32768 bytes)
<6>Memory: 119MB = 119MB total
<5>Memory: 116628k/116628k available, 5228k reserved, 0K highmem
<5>Virtual kernel memory layout:
<5>    vector  : 0xffff0000 - 0xffff1000   (   4 kB)
<5>    fixmap  : 0xfff00000 - 0xfffe0000   ( 896 kB)
<5>    DMA     : 0xffc00000 - 0xffe00000   (   2 MB)
<5>    vmalloc : 0xc7800000 - 0xf8000000   ( 776 MB)
<5>    lowmem  : 0xc0000000 - 0xc7700000   ( 119 MB)
<5>    modules : 0xbf000000 - 0xc0000000   (  16 MB)
<5>      .init : 0xc0008000 - 0xc002c000   ( 144 kB)
<5>      .text : 0xc002c000 - 0xc03b6000   (3624 kB)
<5>      .data : 0xc03ca000 - 0xc03e5d80   ( 112 kB)
<6>SLUB: Genslabs=11, HWalign=32, Order=0-3, MinObjects=0, CPUs=1, Nodes=1
<6>Hierarchical RCU implementation.
<6>RCU-based detection of stalled CPUs is enabled.
<6>NR_IRQS:160
<6>Calibrating delay loop... 1327.10 BogoMIPS (lpj=6635520)
<6>Security Framework initialized
<4>Mount-cache hash table entries: 512
<6>CPU: Testing write buffer coherency: ok
<7>Synthetic TSC timer will fire each 131104 jiffies.
<6>Init trace_clock_cyc2ns: precalc_mult = 312500, precalc_shift = 8
<6>Brought up 1 CPUs
<6>SMP: Total of 1 processors activated (1327.10 BogoMIPS).
<4>hi_wdt: User-Mode!
<4>hi_wdt: Init sucessfull!
<6>NET: Registered protocol family 16
<6>L310 cache controller enabled
<6>l2x0: 16 ways, CACHE_ID 0x410000c9, AUX_CTRL 0x02030000
<6>check_res_of_trace_clock: sched_clock() high resolution
<6>Serial: dw  uart driver
<6>uart:0: ttyAMA0 at MMIO 0x1010e000 (irq = 77) is a AMBA/DW
<6>uart:1: ttyAMA1 at MMIO 0x1010f000 (irq = 78) is a AMBA/DW
<6>console [ttyAMA1] enabled
<4>pcie0 sel: 0x1, pcie1 sel:0x0,pcie0 memsize:0xa00000, pcie1 memsize:0xa00000.
<4>PCIE0 1.1 Device Link Down val = 0x00000008.
<3>pcie_init_5116->1222None of the two pcie controllers is enabled!
<4>bio: create slab <bio-0> at 0
<6>vgaarb: loaded
<6>usbcore: registered new interface driver usbfs
<6>usbcore: registered new interface driver hub
<6>usbcore: registered new device driver usb
<6>cfg80211: Calling CRDA to update world regulatory domain
<6>Switching to clocksource timer1
<6>usbcore: registered new interface driver huawei_ether
<6>NET: Registered protocol family 2
<6>IP route cache hash table entries: 128 (order: -3, 512 bytes)
<6>TCP established hash table entries: 4096 (order: 3, 32768 bytes)
<6>TCP bind hash table entries: 4096 (order: 3, 32768 bytes)
<6>TCP: Hash tables configured (established 4096 bind 4096)
<6>TCP reno registered
<6>UDP hash table entries: 128 (order: 0, 4096 bytes)
<6>UDP-Lite hash table entries: 128 (order: 0, 4096 bytes)
<6>NET: Registered protocol family 1
<6>RPC: Registered udp transport module.
<6>RPC: Registered tcp transport module.
<6>RPC: Registered tcp NFSv4.1 backchannel transport module.
<7>PCI: CLS 0 bytes, default 32
<6>squashfs: version 4.0 (2009/01/31) Phillip Lougher
<6>JFFS2 version 2.2. © 2001-2006 Red Hat, Inc.
<6>msgmni has been set to 227
<6>io scheduler noop registered
<6>io scheduler deadline registered
<6>io scheduler cfq registered (default)
<6>brd: module loaded
<3>mtdoops: mtd device (mtddev=name/number) must be supplied
<4>Spi id table Version 1.22
<4>Special nand id table Version 1.33
<4>Hisilicon Nand Flash Controller V301 Device Driver, Version 1.10
<4>Nand ID: 0x2C 0xF1 0x80 0x95 0x04 0x00 0x00 0x00
<4>Nand(Hardware): Block:128KB Page:2KB Chip:128MB OOB:64B ECC:4Bytes 
<6>NAND device: Manufacturer ID: 0x2c, Chip ID: 0xf1 (Micron MT29F1G08ABAEAWP:E)
<4>NAND_ECC_NONE selected by board driver. This is not recommended !!
<5>3 cmdlinepart partitions found on MTD device hinand
<5>Creating 3 MTD partitions on "hinand":
<5>0x000000000000-0x000000100000 : "startcode"
<5>0x000000100000-0x000008000000 : "ubifs"
<5>0x000008000000-0x000008000000 : "reserved"
<3>mtd: partition "reserved" is out of reach -- disabled
<5>UBI: attaching mtd1 to ubi0
<5>UBI: physical eraseblock size:   131072 bytes (128 KiB)
<5>UBI: logical eraseblock size:    126976 bytes
<5>UBI: smallest flash I/O unit:    2048
<5>UBI: VID header offset:          2048 (aligned 2048)
<5>UBI: data offset:                4096
<5>UBI: attached mtd1 to ubi0
<5>UBI: MTD device name:            "ubifs"
<5>UBI: MTD device size:            127 MiB
<5>UBI: number of good PEBs:        1016
<5>UBI: number of bad PEBs:         0
<5>UBI: max. allowed volumes:       128
<5>UBI: wear-leveling threshold:    512
<5>UBI: number of internal volumes: 1
<5>UBI: number of user volumes:     14
<5>UBI: available PEBs:             288
<5>UBI: total number of reserved PEBs: 728
<5>UBI: number of PEBs reserved for bad PEB handling: 20
<5>UBI: max/mean erase counter: 957/813
<5>UBI: image sequence number: 1252790737
<5>UBI: background thread "ubi_bgt0d" started, PID 35
<6>PPP generic driver version 2.4.2
<6>PPP Deflate Compression module registered
<6>PPP BSD Compression module registered
<6>PPP MPPE Compression module registered
<6>NET: Registered protocol family 24
<6>SLIP: version 0.8.4-NET3.019-NEWTTY (dynamic channels, max=256) (6 bit encapsulation enabled).
<6>CSLIP: code copyright 1989 Regents of the University of California.
<6>SLIP linefill/keepalive option.
<6>usbcore: registered new interface driver asix
<6>usbcore: registered new interface driver cdc_ether
<6>usbcore: registered new interface driver net1080
<6>usbcore: registered new interface driver cdc_subset
<6>usbcore: registered new interface driver zaurus
<6>cdc_ncm: 23-Apr-2011
<6>usbcore: registered new interface driver cdc_ncm
<6>ehci_hcd: USB 2.0 'Enhanced' Host Controller (EHCI) Driver
<4>hiusb_start_hcd sucessful(5116)!
<6>hiusb-ehci hiusb-ehci.0: HIUSB EHCI
<6>hiusb-ehci hiusb-ehci.0: new USB bus registered, assigned bus number 1
<6>hiusb-ehci hiusb-ehci.0: irq 71, io mem 0x10a40000
<6>hiusb-ehci hiusb-ehci.0: USB 0.0 started, EHCI 1.00
<6>hub 1-0:1.0: USB hub found
<6>hub 1-0:1.0: 1 port detected
<6>ohci_hcd: USB 1.1 'Open' Host Controller (OHCI) Driver
<6>hiusb-ohci hiusb-ohci.0: HIUSB OHCI
<6>hiusb-ohci hiusb-ohci.0: new USB bus registered, assigned bus number 2
<6>hiusb-ohci hiusb-ohci.0: irq 70, io mem 0x10a50000
<6>hub 2-0:1.0: USB hub found
<6>hub 2-0:1.0: 1 port detected
<6>usbcore: registered new interface driver usbserial
<6>usbserial: USB Serial Driver core
<6>USB Serial support registered for GSM modem (1-port)
<6>usbcore: registered new interface driver option
<6>option: v0.7.2:USB Driver for GSM modems
<4>Netfilter messages via NETLINK v0.30.
<6>ip_tables: (C) 2000-2006 Netfilter Core Team
<6>arp_tables: (C) 2002 David S. Miller
<6>TCP cubic registered
<6>NET: Registered protocol family 17
<4>VFS: Mounted root (squashfs filesystem) readonly on device 31:11.
<6>Freeing init memory: 144K
<4>nf_conntrack version 0.5.0 (4000 buckets, 16000 max)
<4>CONFIG_NF_CT_ACCT is deprecated and will be removed soon. Please use
<4>nf_conntrack.acct=1 kernel parameter, acct=1 nf_conntrack module option or
<4>sysctl net.netfilter.nf_conntrack_acct=1 to enable it.
<4>hw_ssp_basic: module license 'Huawei Tech. Co., Ltd.' taints kernel.
<4>Disabling lock debugging due to kernel taint
<4>set log file to:/var/init_debug.txt
<4>hw_dm_init successfully...
<4>Soc himem config loaded[51160] /etc/wap/wap_ssp_basic.5116h.cfg
<4>Lastword meminfo:0x80802000;0x000fe000;1;
<3>current lastword info:Add=0xc7b01000;max_num=300;Add1=0xc7b01000;Add2=0xc7b06000;Add3=0xc7b0b000;
<4>proc_dbg_log_get_last_logbuffer:reset buffer.
<1>Set kmsgread process pid to:111;
<5>UBIFS: recovery needed
<3>UBIFS error (pid 116): mount_ubifs: fenghe.linux4.3 : space_fixup = 0
<5>UBIFS: recovery completed
<5>UBIFS: mounted UBI device 0, volume 13, name "file_system"
<5>UBIFS: file system size:   19681280 bytes (19220 KiB, 18 MiB, 155 LEBs)
<5>UBIFS: journal size:       9023488 bytes (8812 KiB, 8 MiB, 72 LEBs)
<5>UBIFS: media format:       w4/r0 (latest is w4/r0)
<5>UBIFS: default compressor: lzo
<5>UBIFS: reserved for root:  0 bytes (0 KiB)
<4>reload log OK!
<4>inet6_init********************************************
<6>NET: Registered protocol family 10
<6>lo: Disabled Privacy Extensions
<6>IPv6 over IPv4 tunneling driver
<6>sit0: Disabled Privacy Extensions
<4>
<4> SYSCTL module is installed
<4>
<4> PIE module is installed
<4>
  FUNC = hi_kernel_gpio_init:1370 
 5116 (0x5) can't insmod 5115 mod
<4> 
<4>
<4> GPIO module is installed
<4>
<4> I2C module is installed
<4>
<4> TIMER module is installed
<4>
<4> SPI module is installed
<4>
<4> HW module is installed
<4>
<4> UART module is installed
<4>
  FUNC = hi_kernel_dp_init:161 
 5116/5118 (0x6) can't insmod 5115 mod
<4> 
<4>
<4> fail to install BRIDGE module
<4>
<4> BRIDGE module is installed
<4>
<4> GPON module is installed
<4>
<4> EPON module is installed
<4>
  FUNC = hi_kernel_dp_l3_init:1710 
 5116/5118 (0x6) can't insmod 5115 mod
<4> 
<4>
<4> fail to install L3 module
<4>
<4> L3 module is installed
<4>
<4> OAM module is installed
<4>
<4> SCI module is installed
<4>
<4> hi_adp_cnt module is installed
<4>COMMON For LDSP Install Successfully...
<4>I2C For LDSP Install Successfully...
<4>GPIO For LDSP Install Successfully...
<4>HIGHWAY For LDSP Install Successfully...
<4>
<4> ------ SOC is 5116 H PILOT ------ 
<4><ldsp>board version is 7092
<4><ldsp>pcb version is 0
<4><ldsp>orig board version is 9
<4>CHIPADP-SD5115 BASIC For LDSP Install Successfully...
<4>CHIPADP-SD5115 EXT For LDSP Install Successfully...
<4>LSW L2 For LDSP Install Successfully...
<4>LSW L3 For LDSP Install Successfully...
<4>DEV For LDSP Install Successfully...
<4>WIFI For LDSP Install Successfully...
<4>[DM]:board_ver=7092,pcb_ver=0
<4>hw_dm_init_data successfully...
<4>SPI For LDSP Install Successfully...
<4>UART For LDSP Install Successfully...
<4>BATTERY For LDSP Install Successfully...
<4>OPTIC For LDSP Install Successfully...
<4>PLOAM For LDSP Install Successfully...
<4>GMAC For LDSP Install Successfully...
<4>KEY For LDSP Install Successfully...
<4>LED For LDSP Install Successfully...
<4>RF For LDSP Install Successfully...
<4>SIM For LDSP Install Successfully...
<4>CODEC For LDSP Install Successfully...
<4>LE964[1] For LDSP install successfully...
<4> ptp_drv_init() !! chip: 10
<4>PTP For BBSP Install Successfully...
<4>disc rate1
<4>dhcp_module_init load success !
<4>
<4> pppoe_module_init load success !
<4>l2base For BBSP Install Successfully...
<4>
<4>[ker_L2M_CTP] for bbsp Install Successfully...
<4>EMAC For LDSP Install Successfully...
<4>MPCP For LDSP Install Successfully...
<4>linux kernel dopra is installed!
<4>
<4> dsp sdk  insmod success!
<4>DSP For VOICE Install Successfully...
<4>l2ext For BBSP Install Successfully...
<4>
<4> vlanflt_module_init load success !
<4>l3base for bbsp Install Successfully...
<6>GRE over IPv4 tunneling driver
<4>arp_config_bridge_filter: 
<4>
<4> hw_arp_announce_module_init load success !
<4>
<4> arp_module_init load success !
<4>hw_route_ipv4_module_init in 
<4>Route ipv4 for bbsp Install Successfully...
<4>Neighbour discovery for bbsp Install Successfully...
<4>Portal For BBSP Install Successfully...
<4>User device for bbsp Install Successfully...
<4>BBSP_FT_FIREWALL_FLOW_LOG close!!
<4>l3ext for bbsp Install Successfully...
<4>
<4> install success
<6>ip6_tables: (C) 2000-2006 Netfilter Core Team
<6>ip6tnl0: Disabled Privacy Extensions
<4>hw_route_ipv6_module_init in 
<4>Route ipv6 for bbsp Install Successfully
<4>
<4>[ker_ROUTE_ADPT] for bbsp Install Successfully...
<4>
<4>------y1731_ker_hook installed!-----
<4>ker_video_diag For BBSP Install Successfully...
<4><LDSP> system has slave space for bob 
<4>read data is over time
<4> 
SD511X test self OK
<4>Optic test self ERROR
<4>WIFI test self NoCheck
<4>PHY[1] test self OK
<4>PHY[2] test self OK
<4>PHY[3] test self OK
<4>PHY[4] test self OK
<4>
<4><LDSP> 5171 optic 
<4>FILE = /usr1/code/ICP_ONT_V300R015C10_Compile/code/current/ONT_Code/CI/Make/../../Source/ldsp/driver/optic/hw_ker_drv_optic.c 
<4>LINE =  7498, FUNC = hw_drv_optic_cal_sw_ver_set 
<4><LDSP> read cal version file error 
<4>
<4><LDSP> bob optic was calibrated 
<4><LDSP> optic firmware load success! 
<6>GPON init success ! 
<6>
<3>ubi_open_volume error with 2, try UBI_READONLY;
<4>ttyAMA1: 1 input overrun(s)
<6>warning: process `bbsp' used the deprecated sysctl system call with 3.12.16.-2.1.0.
<6>warning: process `bbsp' used the deprecated sysctl system call with 3.12.16.-2.5.0.
<6>warning: process `bbsp' used the deprecated sysctl system call with 3.12.16.-2.6.0.
<4>
<4> Alloc uiSize[1048576] uiLoop1[3]
<4> OS-Functions are registered !CPU-TYPE=6
<4>  HIAPI_ZspBootCompleteWait: Boot Complete!
<4>
<4> le964x init dev success!
<4>
<4> le9641 cal channel dev success!
<4>
<4> le964x hard init success!!!!! 
<4>
<4>======0 0 1 0========================
<4>
<4>======0 0 1 0========================
<4>
<4> ppp_open: br0_ifindex 6
<4>Init Access Mode To GPON .................[PLOAM]ONUID(0): O1 => O1
<4>[PLOAM]ONUID(0): O1 => O2
<4>
<4>The link of ETH3 is up, uni_phy
<4>
<4>eth3,status:f100    
<4>
<4>IP:            40151232                  
<4>devicetype:    MSFT 5.0 
<4>[PLOAM]ONUID(0): O2 => O3
<4>[PLOAM]ONUID(11): O3 => O4
<4>[PLOAM]ONUID(11): O4 => O5
<1>Set kmsgread process pid to:933;
<4>set log file to:/var/console.log
<4>
<4>The link of ETH0 is up, uni_phy
<4>
<4>eth0,status:f100    
<4>
<4>The link of ETH0 is down, uni_phy
<4>
<4>The link of ETH0 is up, uni_phy
<4>
<4>eth0,status:f1000   
<4>
<4>The link of ETH0 is down, uni_phy
<4>
<4>The link of ETH0 is up, uni_phy
<4>
<4>eth0,status:h10     
<4>
<4>The link of ETH0 is down, uni_phy
<4>
<4>The link of ETH0 is up, uni_phy
<4>
<4>eth0,status:f1000   
<4>
<4>The link of ETH0 is down, uni_phy
<4>
<4>The link of ETH0 is up, uni_phy
<4>
<4>eth0,status:h10     
<4>
<4>The link of ETH0 is down, uni_phy
<0>[ker_debug]hw_ssp_log_highmem_to_flash:1550:0x497ce7d5;
<4>
<4>The link of ETH0 is up, uni_phy
<4>
<4>eth0,status:f100    
<4>
<4>The link of ETH0 is down, uni_phy
<4>
<4>The link of ETH0 is up, uni_phy
<4>
<4>eth0,status:f1000   
<4>
<4>The link of ETH0 is down, uni_phy
<4>
<4>The link of ETH0 is up, uni_phy
<4>
<4>eth0,status:h10     
<4>
<4>The link of ETH0 is down, uni_phy
<4>
<4>The link of ETH0 is up, uni_phy
<4>
<4>eth0,status:f1000   
<4>
<4>The link of ETH0 is down, uni_phy
<4>
<4>The link of ETH0 is up, uni_phy
<4>
<4>eth0,status:h10     
<4>
<4>The link of ETH0 is down, uni_phy
<4>
<4>The link of ETH0 is up, uni_phy
<4>
<4>eth0,status:f100    
<4>
<4>The link of ETH0 is down, uni_phy
<4>
<4>The link of ETH0 is up, uni_phy
<4>
<4>eth0,status:f1000   
<4>set log file to:/var/console.log

