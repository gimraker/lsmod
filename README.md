# lsmod
aubot hba1000 16i

[20230403_23:21:17.481 ]

SynologyNAS login: root

Synology strongly advises you not to run commands as the root user, who has
the highest privileges on the system. Doing so may cause major damages
to the system. Please note that if you choose to proceed, all consequences are
at your own risk.



BusyBox v1.30.1 () built-in shell (ash)

SynologyNAS> lsmod
Module                  Size  Used by    Tainted: P  
epyc7002_synobios     102400  0 
adt7475                45056  0 
hwmon_vid              16384  1 adt7475
nfsv3                  45056  0 
nfs                   323584  1 nfsv3
nfs_ssc                16384  1 nfs
lockd                 110592  2 nfsv3,nfs
grace                  16384  1 lockd
sunrpc                512000  3 nfsv3,nfs,lockd
atlantic              270336  0 
r8168                 552960  0 
ixgbe                 311296  0 
vxlan                  65536  0 
ip6_udp_tunnel         16384  1 vxlan
udp_tunnel             20480  1 vxlan
vfat                   20480  0 
fat                    81920  1 vfat
crc_itu_t              16384  1 atlantic
sha256_generic         16384  0 
libsha256              20480  1 sha256_generic
synorbd                98304  0 
synofsbd               28672  0 
ast                    53248  0 
i2c_algo_bit           16384  1 ast
drm_vram_helper        16384  1 ast
drm_kms_helper        200704  4 ast,drm_vram_helper
fbcore                106496 67 ast,drm_kms_helper
fbdev                  16384  1 fbcore
drm_ttm_helper         16384  1 drm_vram_helper
ttm                    86016  2 drm_vram_helper,drm_ttm_helper
usbhid                 40960  0 
hid                   118784  1 usbhid
drm                   434176  6 ast,drm_vram_helper,drm_kms_helper,drm_ttm_helper,ttm
usbmouse               16384  0 
usbkbd                 16384  0 
drm_panel_orientation_quirks    24576  1 drm
hdmi                   24576  1 drm
usb_storage            61440  0 
backport_sa6400        69632  3 drm_kms_helper,ttm,drm,[permanent]
i40e                  561152  0 
igb                   188416  0 
backport_sa6400_export    16384  1 backport_sa6400
e1000e                180224  0 
auxiliary              16384  1 i40e
aacraid               126976  0 
video                  53248  0 
thermal                20480  0 
backlight              16384  2 drm,video
acpi_cpufreq           16384  0 
button                 20480  0 
xhci_pci               16384  0 
xhci_hcd              237568  1 xhci_pci
usbcore               249856  6 usbhid,usbmouse,usbkbd,usb_storage,xhci_pci,xhci_hcd
usb_common             16384  2 xhci_hcd,usbcore
redpill               180224  0 
SynologyNAS> SynologyNAS> lsmod
-ash: SynologyNAS: not found
SynologyNAS> Module                  Size  Used by    Tainted: P  
-ash: Module: not found
SynologyNAS> epyc7002_synobios     102400  0 
-ash: epyc7002_synobios: not found
SynologyNAS> adt7475                45056  0 
-ash: adt7475: not found
SynologyNAS> hwmon_vid              16384  1 adt7475
-ash: hwmon_vid: not found
SynologyNAS> nfsv3                  45056  0 
-ash: nfsv3: not found
SynologyNAS> nfs                   323584  1 nfsv3
-ash: nfs: not found
SynologyNAS> nfs_ssc                16384  1 nfs
-ash: nfs_ssc: not found
SynologyNAS> lockd                 110592  2 nfsv3,nfs
-ash: lockd: not found
SynologyNAS> grace                  16384  1 lockd
-ash: grace: not found
SynologyNAS> sunrpc                512000  3 nfsv3,nfs,lockd
-ash: sunrpc: not found
SynologyNAS> atlantic              270336  0 
-ash: atlantic: not found
SynologyNAS> r8168                 552960  0 
-ash: r8168: not found
SynologyNAS> ixgbe                 311296  0 
-ash: ixgbe: not found
SynologyNAS> vxlan                  65536  0 
-ash: vxlan: not found
SynologyNAS> ip6_udp_tunnel         16384  1 vxlan
-ash: ip6_udp_tunnel: not found
SynologyNAS> udp_tunnel             20480  1 vxlan
-ash: udp_tunnel: not found
SynologyNAS> vfat                   20480  0 
-ash: vfat: not found
SynologyNAS> fat                    81920  1 vfat
-ash: fat: not found
SynologyNAS> crc_itu_t              16384  1 atlantic
-ash: crc_itu_t: not found
SynologyNAS> sha256_generic         16384  0 
-ash: sha256_generic: not found
SynologyNAS> libsha256              20480  1 sha256_generic
-ash: libsha256: not found
SynologyNAS> synorbd                98304  0 
-ash: synorbd: not found
SynologyNAS> synofsbd               28672  0 
-ash: synofsbd: not found
SynologyNAS> ast                    53248  0 
-ash: ast: not found
SynologyNAS> i2c_algo_bit           16384  1 ast
-ash: i2c_algo_bit: not found
SynologyNAS> drm_vram_helper        16384  1 ast
-ash: drm_vram_helper: not found
SynologyNAS> drm_kms_helper        200704  4 ast,drm_vram_helper
-ash: drm_kms_helper: not found
SynologyNAS> fbcore                106496 67 ast,drm_kms_helper
-ash: fbcore: not found
SynologyNAS> fbdev                  16384  1 fbcore
-ash: fbdev: not found
SynologyNAS> drm_ttm_helper         16384  1 drm_vram_helper
-ash: drm_ttm_helper: not found
SynologyNAS> ttm                    86016  2 drm_vram_helper,drm_ttm_helper
-ash: ttm: not found
SynologyNAS> usbhid                 40960  0 
-ash: usbhid: not found
SynologyNAS> hid                   118784  1 usbhid
-ash: hid: not found
SynologyNAS> drm                   434176  6 ast,drm_vram_helper,drm_kms_helper,
drm_ttm_helper,ttm
-ash: drm: not found
SynologyNAS> usbmouse               16384  0 
-ash: usbmouse: not found
SynologyNAS> usbkbd                 16384  0 
-ash: usbkbd: not found
SynologyNAS> drm_panel_orientation_quirks    24576  1 drm
-ash: drm_panel_orientation_quirks: not found
SynologyNAS> hdmi                   24576  1 drm
-ash: hdmi: not found
SynologyNAS> usb_storage            61440  0 
-ash: usb_storage: not found
SynologyNAS> backport_sa6400        69632  3 drm_kms_helper,ttm,drm,[permanent]
-ash: backport_sa6400: not found
SynologyNAS> i40e                  561152  0 
-ash: i40e: not found
SynologyNAS> igb                   188416  0 
-ash: igb: not found
SynologyNAS> backport_sa6400_export    16384  1 backport_sa6400
-ash: backport_sa6400_export: not found
SynologyNAS> e1000e                180224  0 
-ash: e1000e: not found
SynologyNAS> auxiliary              16384  1 i40e
-ash: auxiliary: not found
SynologyNAS> aacraid               126976  0 
-ash: aacraid: not found
SynologyNAS> video                  53248  0 
-ash: video: not found
SynologyNAS> thermal                20480  0 
-ash: thermal: not found
SynologyNAS> backlight              16384  2 drm,video
-ash: backlight: not found
SynologyNAS> acpi_cpufreq           16384  0 
-ash: acpi_cpufreq: not found
SynologyNAS> button                 20480  0 
-ash: button: not found
SynologyNAS> xhci_pci               16384  0 
-ash: xhci_pci: not found
SynologyNAS> xhci_hcd              237568  1 xhci_pci
-ash: xhci_hcd: not found
SynologyNAS> usbcore               249856  6 usbhid,usbmouse,usbkbd,usb_storage,
xhci_pci,xhci_hcd
-ash: usbcore: not found
SynologyNAS> usb_common             16384  2 xhci_hcd,usbcore
-ash: usb_common: not found
SynologyNAS> redpill               180224  0 
-ash: redpill: not found
SynologyNAS> clear
-ash: clear: not found
SynologyNAS> SynologyNAS> aacraid               126976  0 
-ash: SynologyNAS: not found
SynologyNAS> ls /sys/block
nvme0n1   ram1      ram11     ram13     ram15     ram3      ram5      ram7      ram9
ram0      ram10     ram12     ram14     ram2      ram4      ram6      ram8      synoboot
SynologyNAS> lsmod | grep aacraid
aacraid               126976  0 
SynologyNAS> lsmod | grep aacraid
aacraid               126976  0 
SynologyNAS> ls /sys/block
nvme0n1   ram1      ram11     ram13     ram15     ram3      ram5      ram7      ram9
ram0      ram10     ram12     ram14     ram2      ram4      ram6      ram8      synoboot
SynologyNAS> lsmod | grep aacraid
aacraid               126976  0 
SynologyNAS> dmsesg
-ash: dmsesg: not found
SynologyNAS> dmesg
[    0.000000] Linux version 5.10.55+ (root@build2) (x86_64-pc-linux-gnu-gcc (GCC) 8.5.0, GNU ld (GNU Binutils) 2.30) #42962 SMP Tue Jan 31 23:54:31 CST 2023
[    0.000000] Command line: BOOT_IMAGE=/zImage-dsm console=ttyS0,115200n8 earlyprintk log_buf_len=32M earlycon=uart8250,io,0x3f8,115200n8 root=/dev/md0 loglevel=15 noefi syno_hw_version=SA6400 i915.enable_guc=2 netif_num=4 synoboot2 pid=0x5583 mac2=7e21363bcd3b mac3=7e21363bcd5b mac1=7e21363bcd1b mac4=7e21363bcd7b sn=0000XXXBN4YEE SMBusHddDynamicPower=1 vid=0x0781 vender_format_version=2 syno_ttyS1=serial,0x2f8 syno_ttyS0=serial,0x3f8
[    0.000000] KERNEL supported cpus:
[    0.000000]   Intel GenuineIntel
[    0.000000]   AMD AuthenticAMD
[    0.000000]   Hygon HygonGenuine
[    0.000000] x86/fpu: Supporting XSAVE feature 0x001: 'x87 floating point registers'
[    0.000000] x86/fpu: Supporting XSAVE feature 0x002: 'SSE registers'
[    0.000000] x86/fpu: Supporting XSAVE feature 0x004: 'AVX registers'
[    0.000000] x86/fpu: Supporting XSAVE feature 0x008: 'MPX bounds registers'
[    0.000000] x86/fpu: Supporting XSAVE feature 0x010: 'MPX CSR'
[    0.000000] x86/fpu: xstate_offset[2]:  576, xstate_sizes[2]:  256
[    0.000000] x86/fpu: xstate_offset[3]:  832, xstate_sizes[3]:   64
[    0.000000] x86/fpu: xstate_offset[4]:  896, xstate_sizes[4]:   64
[    0.000000] x86/fpu: Enabled xstate features 0x1f, context size is 960 bytes, using 'compacted' format.
[    0.000000] BIOS-provided physical RAM map:
[    0.000000] BIOS-e820: [mem 0x0000000000000000-0x000000000009afff] usable
[    0.000000] BIOS-e820: [mem 0x000000000009b000-0x000000000009ffff] reserved
[    0.000000] BIOS-e820: [mem 0x00000000000e0000-0x00000000000fffff] reserved
[    0.000000] BIOS-e820: [mem 0x0000000000100000-0x000000009a2f1fff] usable
[    0.000000] BIOS-e820: [mem 0x000000009a2f2000-0x000000009de5dfff] reserved
[    0.000000] BIOS-e820: [mem 0x000000009de5e000-0x000000009dfe6fff] usable
[    0.000000] BIOS-e820: [mem 0x000000009dfe7000-0x000000009e417fff] ACPI NVS
[    0.000000] BIOS-e820: [mem 0x000000009e418000-0x000000009ec0efff] reserved
[    0.000000] BIOS-e820: [mem 0x000000009ec0f000-0x000000009ec0ffff] usable
[    0.000000] BIOS-e820: [mem 0x000000009ec10000-0x000000009fffffff] reserved
[    0.000000] BIOS-e820: [mem 0x00000000e0000000-0x00000000efffffff] reserved
[    0.000000] BIOS-e820: [mem 0x00000000fe000000-0x00000000fe010fff] reserved
[    0.000000] BIOS-e820: [mem 0x00000000fec00000-0x00000000fec00fff] reserved
[    0.000000] BIOS-e820: [mem 0x00000000fed00000-0x00000000fed03fff] reserved
[    0.000000] BIOS-e820: [mem 0x00000000fee00000-0x00000000fee00fff] reserved
[    0.000000] BIOS-e820: [mem 0x00000000ff000000-0x00000000ffffffff] reserved
[    0.000000] BIOS-e820: [mem 0x0000000100000000-0x000000105bffffff] usable
[    0.000000] earlycon: uart8250 at I/O port 0x3f8 (options '115200n8')
[    0.000000] printk: bootconsole [uart8250] enabled
[    0.000000] NX (Execute Disable) protection: active
[    0.000000] SMBIOS 3.2.0 present.
[    0.000000] DMI: Supermicro Super Server/X11SCA-F, BIOS 1.8 11/04/2022
[    0.000000] tsc: Detected 2100.000 MHz processor
[    0.000000] tsc: Detected 2099.944 MHz TSC
[    0.001063] e820: update [mem 0x00000000-0x00000fff] usable ==> reserved
[    0.013913] e820: remove [mem 0x000a0000-0x000fffff] usable
[    0.020548] last_pfn = 0x105c000 max_arch_pfn = 0x400000000
[    0.027189] MTRR default type: write-back
[    0.031953] MTRR fixed ranges enabled:
[    0.036406]   00000-9FFFF write-back
[    0.040651]   A0000-BFFFF uncachable
[    0.044897]   C0000-FFFFF write-protect
[    0.049457] MTRR variable ranges enabled:
[    0.054221]   0 base 00C0000000 mask 7FC0000000 uncachable
[    0.060746]   1 base 00A0000000 mask 7FE0000000 uncachable
[    0.067268]   2 base 2000000000 mask 6000000000 uncachable
[    0.073793]   3 base 4000000000 mask 4000000000 uncachable
[    0.080319]   4 disabled
[    0.083323]   5 disabled
[    0.086323]   6 disabled
[    0.089327]   7 disabled
[    0.092332]   8 disabled
[    0.095336]   9 disabled
[    0.098792] x86/PAT: PAT support disabled because CONFIG_X86_PAT is disabled in the kernel.
[    0.112161] x86/PAT: Configuration [0-7]: WB  WT  UC- UC  WB  WT  UC- UC  
[    0.120349] last_pfn = 0x9ec10 max_arch_pfn = 0x400000000
[    0.136097] found SMP MP-table at [mem 0x000fcf30-0x000fcf3f]
[    0.142967] Using GB pages for direct mapping
[    0.170193] printk: log_buf_len: 33554432 bytes
[    0.175587] printk: early log buf free: 1044496(99%)
[    0.181493] RAMDISK: [mem 0x2e177000-0x330b2fff]
[    0.187415] ACPI: Early table checksum verification disabled
[    0.194155] ACPI: RSDP 0x00000000000F05B0 000024 (v02 SUPERM)
[    0.201002] ACPI: XSDT 0x000000009E2FA0C0 000104 (v01 SUPERM SUPERM   01072009 AMI  00010013)
[    0.211155] ACPI: FACP 0x000000009E338228 000114 (v06                 01072009 AMI  00010013)
[    0.221324] ACPI: DSDT 0x000000009E2FA260 03DFC6 (v02 SUPERM SMCI--MB 01072009 INTL 20160527)
[    0.231487] ACPI: FACS 0x000000009E417F80 000040
[    0.236978] ACPI: APIC 0x000000009E338340 00012C (v04                 01072009 AMI  00010013)
[    0.247133] ACPI: FPDT 0x000000009E338470 000044 (v01                 01072009 AMI  00010013)
[    0.257284] ACPI: FIDT 0x000000009E3384B8 00009C (v01 SUPERM SMCI--MB 01072009 AMI  00010013)
[    0.267435] ACPI: MCFG 0x000000009E338558 00003C (v01 SUPERM SMCI--MB 01072009 MSFT 00000097)
[    0.277590] ACPI: SPMI 0x000000009E338598 000041 (v05 SUPERM SMCI--MB 00000000 AMI. 00000000)
[    0.287741] ACPI: SSDT 0x000000009E3385E0 001B26 (v02 CpuRef CpuSsdt  00003000 INTL 20160527)
[    0.297887] ACPI: SSDT 0x000000009E33A108 0031E8 (v02 SaSsdt SaSsdt   00003000 INTL 20160527)
[    0.308038] ACPI: SSDT 0x000000009E33D2F0 0026A5 (v02 PegSsd PegSsdt  00001000 INTL 20160527)
[    0.318189] ACPI: HPET 0x000000009E33F998 000038 (v01 SUPERM SMCI--MB 00000002      01000013)
[    0.328344] ACPI: SSDT 0x000000009E33F9D0 001CD5 (v02 SUPERM CflS_Rvp 00001000 INTL 20160527)
[    0.338495] ACPI: SSDT 0x000000009E3416A8 000FAE (v02 SUPERM Ther_Rvp 00001000 INTL 20160527)
[    0.348650] ACPI: SSDT 0x000000009E342658 002FCF (v02 INTEL  xh_cfsd4 00000000 INTL 20160527)
[    0.358801] ACPI: UEFI 0x000000009E345628 000042 (v01 SUPERM SMCI--MB 00000002      01000013)
[    0.368947] ACPI: LPIT 0x000000009E345670 000094 (v01 SUPERM SMCI--MB 00000002      01000013)
[    0.379098] ACPI: SSDT 0x000000009E345708 0027DE (v02 SUPERM PtidDevc 00001000 INTL 20160527)
[    0.389249] ACPI: SSDT 0x000000009E347EE8 0014E2 (v02 SUPERM TbtTypeC 00000000 INTL 20160527)
[    0.399395] ACPI: DBGP 0x000000009E3493D0 000034 (v01 SUPERM SMCI--MB 00000002      01000013)
[    0.409546] ACPI: DBG2 0x000000009E349408 000054 (v00 SUPERM SMCI--MB 00000002      01000013)
[    0.419697] ACPI: SSDT 0x000000009E349460 001B74 (v02 SUPERM UsbCTabl 00001000 INTL 20160527)
[    0.429843] ACPI: SSDT 0x000000009E34AFD8 000144 (v02 Intel  ADebTabl 00001000 INTL 20160527)
[    0.439994] ACPI: TPM2 0x000000009E34B120 000034 (v04 SUPERM SMCI--MB 00000001 AMI  00000000)
[    0.450145] ACPI: DMAR 0x000000009E34B158 000070 (v01 INTEL  EDK2     00000002      01000013)
[    0.460291] ACPI: WSMT 0x000000009E34B1C8 000028 (v01 SUPERM          01072009 AMI  00010013)
[    0.470443] ACPI: EINJ 0x000000009E34B1F0 000130 (v01 AMI    AMI.EINJ 00000000 AMI. 00000000)
[    0.480593] ACPI: ERST 0x000000009E34B320 000230 (v01 AMIER  AMI.ERST 00000000 AMI. 00000000)
[    0.490748] ACPI: BERT 0x000000009E34B550 000030 (v01 AMI    AMI.BERT 00000000 AMI. 00000000)
[    0.500899] ACPI: HEST 0x000000009E34B580 00027C (v01 AMI    AMI.HEST 00000000 AMI. 00000000)
[    0.511050] ACPI: Reserving FACP table memory at [mem 0x9e338228-0x9e33833b]
[    0.519437] ACPI: Reserving DSDT table memory at [mem 0x9e2fa260-0x9e338225]
[    0.527829] ACPI: Reserving FACS table memory at [mem 0x9e417f80-0x9e417fbf]
[    0.536217] ACPI: Reserving APIC table memory at [mem 0x9e338340-0x9e33846b]
[    0.544605] ACPI: Reserving FPDT table memory at [mem 0x9e338470-0x9e3384b3]
[    0.552993] ACPI: Reserving FIDT table memory at [mem 0x9e3384b8-0x9e338553]
[    0.561385] ACPI: Reserving MCFG table memory at [mem 0x9e338558-0x9e338593]
[    0.569773] ACPI: Reserving SPMI table memory at [mem 0x9e338598-0x9e3385d8]
[    0.578161] ACPI: Reserving SSDT table memory at [mem 0x9e3385e0-0x9e33a105]
[    0.586548] ACPI: Reserving SSDT table memory at [mem 0x9e33a108-0x9e33d2ef]
[    0.594936] ACPI: Reserving SSDT table memory at [mem 0x9e33d2f0-0x9e33f994]
[    0.603324] ACPI: Reserving HPET table memory at [mem 0x9e33f998-0x9e33f9cf]
[    0.611712] ACPI: Reserving SSDT table memory at [mem 0x9e33f9d0-0x9e3416a4]
[    0.620100] ACPI: Reserving SSDT table memory at [mem 0x9e3416a8-0x9e342655]
[    0.628488] ACPI: Reserving SSDT table memory at [mem 0x9e342658-0x9e345626]
[    0.636876] ACPI: Reserving UEFI table memory at [mem 0x9e345628-0x9e345669]
[    0.645268] ACPI: Reserving LPIT table memory at [mem 0x9e345670-0x9e345703]
[    0.653656] ACPI: Reserving SSDT table memory at [mem 0x9e345708-0x9e347ee5]
[    0.662044] ACPI: Reserving SSDT table memory at [mem 0x9e347ee8-0x9e3493c9]
[    0.670432] ACPI: Reserving DBGP table memory at [mem 0x9e3493d0-0x9e349403]
[    0.678820] ACPI: Reserving DBG2 table memory at [mem 0x9e349408-0x9e34945b]
[    0.687208] ACPI: Reserving SSDT table memory at [mem 0x9e349460-0x9e34afd3]
[    0.695595] ACPI: Reserving SSDT table memory at [mem 0x9e34afd8-0x9e34b11b]
[    0.703983] ACPI: Reserving TPM2 table memory at [mem 0x9e34b120-0x9e34b153]
[    0.712376] ACPI: Reserving DMAR table memory at [mem 0x9e34b158-0x9e34b1c7]
[    0.720764] ACPI: Reserving WSMT table memory at [mem 0x9e34b1c8-0x9e34b1ef]
[    0.729152] ACPI: Reserving EINJ table memory at [mem 0x9e34b1f0-0x9e34b31f]
[    0.737539] ACPI: Reserving ERST table memory at [mem 0x9e34b320-0x9e34b54f]
[    0.745931] ACPI: Reserving BERT table memory at [mem 0x9e34b550-0x9e34b57f]
[    0.754319] ACPI: Reserving HEST table memory at [mem 0x9e34b580-0x9e34b7fb]
[    0.762718] ACPI: Local APIC address 0xfee00000
[    0.768319] No NUMA configuration found
[    0.772884] Faking a node at [mem 0x0000000000000000-0x000000105bffffff]
[    0.780863] NODE_DATA(0) allocated [mem 0x1052ffa000-0x1052ffdfff]
[    0.788296] Zone ranges:
[    0.791305]   DMA      [mem 0x0000000000001000-0x0000000000ffffff]
[    0.798657]   DMA32    [mem 0x0000000001000000-0x00000000ffffffff]
[    0.806011]   Normal   [mem 0x0000000100000000-0x000000105bffffff]
[    0.813364] Movable zone start for each node
[    0.818438] Early memory node ranges
[    0.822684]   node   0: [mem 0x0000000000001000-0x000000000009afff]
[    0.830140]   node   0: [mem 0x0000000000100000-0x000000009a2f1fff]
[    0.837598]   node   0: [mem 0x000000009de5e000-0x000000009dfe6fff]
[    0.845054]   node   0: [mem 0x000000009ec0f000-0x000000009ec0ffff]
[    0.852511]   node   0: [mem 0x0000000100000000-0x000000105bffffff]
[    0.859973] Initmem setup node 0 [mem 0x0000000000001000-0x000000105bffffff]
[    0.868375] On node 0 totalpages: 16737302
[    0.873245]   DMA zone: 64 pages used for memmap
[    0.878731]   DMA zone: 21 pages reserved
[    0.883499]   DMA zone: 3994 pages, LIFO batch:0
[    0.888986]   DMA32 zone: 9810 pages used for memmap
[    0.894891]   DMA32 zone: 627836 pages, LIFO batch:63
[    0.900895]   Normal zone: 251648 pages used for memmap
[    0.907111]   Normal zone: 16105472 pages, LIFO batch:63
[    0.913431] On node 0, zone DMA: 1 pages in unavailable ranges
[    0.913457] On node 0, zone DMA: 101 pages in unavailable ranges
[    0.924633] On node 0, zone DMA32: 15212 pages in unavailable ranges
[    0.931821] On node 0, zone DMA32: 3112 pages in unavailable ranges
[    1.043389] On node 0, zone Normal: 5104 pages in unavailable ranges
[    1.051046] On node 0, zone Normal: 16384 pages in unavailable ranges
[    1.059619] ACPI: PM-Timer IO Port: 0x1808
[    1.072153] ACPI: Local APIC address 0xfee00000
[    1.077547] ACPI: LAPIC_NMI (acpi_id[0x01] high edge lint[0x1])
[    1.084599] ACPI: LAPIC_NMI (acpi_id[0x02] high edge lint[0x1])
[    1.091642] ACPI: LAPIC_NMI (acpi_id[0x03] high edge lint[0x1])
[    1.098685] ACPI: LAPIC_NMI (acpi_id[0x04] high edge lint[0x1])
[    1.105728] ACPI: LAPIC_NMI (acpi_id[0x05] high edge lint[0x1])
[    1.112771] ACPI: LAPIC_NMI (acpi_id[0x06] high edge lint[0x1])
[    1.119814] ACPI: LAPIC_NMI (acpi_id[0x07] high edge lint[0x1])
[    1.126858] ACPI: LAPIC_NMI (acpi_id[0x08] high edge lint[0x1])
[    1.133900] ACPI: LAPIC_NMI (acpi_id[0x09] high edge lint[0x1])
[    1.140943] ACPI: LAPIC_NMI (acpi_id[0x0a] high edge lint[0x1])
[    1.147983] ACPI: LAPIC_NMI (acpi_id[0x0b] high edge lint[0x1])
[    1.155025] ACPI: LAPIC_NMI (acpi_id[0x0c] high edge lint[0x1])
[    1.162068] ACPI: LAPIC_NMI (acpi_id[0x0d] high edge lint[0x1])
[    1.169111] ACPI: LAPIC_NMI (acpi_id[0x0e] high edge lint[0x1])
[    1.176155] ACPI: LAPIC_NMI (acpi_id[0x0f] high edge lint[0x1])
[    1.183198] ACPI: LAPIC_NMI (acpi_id[0x10] high edge lint[0x1])
[    1.190303] IOAPIC[0]: apic_id 2, version 32, address 0xfec00000, GSI 0-119
[    1.198587] ACPI: INT_SRC_OVR (bus 0 bus_irq 0 global_irq 2 dfl dfl)
[    1.206146] ACPI: INT_SRC_OVR (bus 0 bus_irq 9 global_irq 9 high level)
[    1.214017] ACPI: IRQ0 used by override.
[    1.218677] ACPI: IRQ9 used by override.
[    1.223341] Using ACPI (MADT) for SMP configuration information
[    1.230384] ACPI: HPET id: 0x8086a201 base: 0xfed00000
[    1.236493] TSC deadline timer available
[    1.241151] smpboot: Allowing 16 CPUs, 0 hotplug CPUs
[    1.247181] PM: hibernation: Registered nosave memory: [mem 0x00000000-0x00000fff]
[    1.256196] PM: hibernation: Registered nosave memory: [mem 0x0009b000-0x0009ffff]
[    1.265207] PM: hibernation: Registered nosave memory: [mem 0x000a0000-0x000dffff]
[    1.274216] PM: hibernation: Registered nosave memory: [mem 0x000e0000-0x000fffff]
[    1.283225] PM: hibernation: Registered nosave memory: [mem 0x9a2f2000-0x9de5dfff]
[    1.292238] PM: hibernation: Registered nosave memory: [mem 0x9dfe7000-0x9e417fff]
[    1.301246] PM: hibernation: Registered nosave memory: [mem 0x9e418000-0x9ec0efff]
[    1.310260] PM: hibernation: Registered nosave memory: [mem 0x9ec10000-0x9fffffff]
[    1.319267] PM: hibernation: Registered nosave memory: [mem 0xa0000000-0xdfffffff]
[    1.328276] PM: hibernation: Registered nosave memory: [mem 0xe0000000-0xefffffff]
[    1.337288] PM: hibernation: Registered nosave memory: [mem 0xf0000000-0xfdffffff]
[    1.346297] PM: hibernation: Registered nosave memory: [mem 0xfe000000-0xfe010fff]
[    1.355310] PM: hibernation: Registered nosave memory: [mem 0xfe011000-0xfebfffff]
[    1.364318] PM: hibernation: Registered nosave memory: [mem 0xfec00000-0xfec00fff]
[    1.373331] PM: hibernation: Registered nosave memory: [mem 0xfec01000-0xfecfffff]
[    1.382340] PM: hibernation: Registered nosave memory: [mem 0xfed00000-0xfed03fff]
[    1.391352] PM: hibernation: Registered nosave memory: [mem 0xfed04000-0xfedfffff]
[    1.400361] PM: hibernation: Registered nosave memory: [mem 0xfee00000-0xfee00fff]
[    1.409374] PM: hibernation: Registered nosave memory: [mem 0xfee01000-0xfeffffff]
[    1.418383] PM: hibernation: Registered nosave memory: [mem 0xff000000-0xffffffff]
[    1.427397] [mem 0xa0000000-0xdfffffff] available for PCI devices
[    1.434648] clocksource: refined-jiffies: mask: 0xffffffff max_cycles: 0xffffffff, max_idle_ns: 1910969940391419 ns
[    1.452077] setup_percpu: NR_CPUS:24 nr_cpumask_bits:24 nr_cpu_ids:16 nr_node_ids:1
[    1.461649] percpu: Embedded 53 pages/cpu s176664 r8192 d32232 u262144
[    1.469430] pcpu-alloc: s176664 r8192 d32232 u262144 alloc=1*2097152
[    1.477000] pcpu-alloc: [0] 00 01 02 03 04 05 06 07 [0] 08 09 10 11 12 13 14 15 
[    1.485845] Built 1 zonelists, mobility grouping on.  Total pages: 16475759
[    1.494134] Policy zone: Normal
[    1.497864] Kernel command line: BOOT_IMAGE=/zImage-dsm console=ttyS0,115200n8 earlyprintk log_buf_len=32M earlycon=uart8250,io,0x3f8,115200n8 root=/dev/md0 loglevel=15 noefi syno_hw_version=SA6400 i915.enable_guc=2 netif_num=4 synoboot2 pid=0x5583 mac2=7e21363bcd3b mac3=7e21363bcd5b mac1=7e21363bcd1b mac4=7e21363bcd7b sn=0000XXXBN4YEE SMBusHddDynamicPower=1 vid=0x0781 vender_format_version=2 syno_ttyS1=serial,0x2f8 syno_ttyS0=serial,0x3f8
[    1.544402] Synology Hardware Version: SA6400
[    1.549621] Internal netif num: 4
[    1.553604] Mac2: 7e21363bcd3b
[    1.557243] Mac3: 7e21363bcd5b
[    1.560881] Mac1: 7e21363bcd1b
[    1.564523] Mac4: 7e21363bcd7b
[    1.568165] Serial Number: 0000XXXBN4YEE
[    1.572844] Support SMBus HDD Dynamic Power Control.
[    1.578782] Vender format version: 2
[    1.587707] Dentry cache hash table entries: 8388608 (order: 14, 67108864 bytes, linear)
[    1.696032] Inode-cache hash table entries: 4194304 (order: 13, 33554432 bytes, linear)
[    1.801065] mem auto-init: stack:off, heap alloc:off, heap free:off
[    2.034004] Memory: 65465016K/66949208K available (10248K kernel code, 4829K rwdata, 5624K rodata, 1356K init, 10960K bss, 1483936K reserved, 0K cma-reserved)
[    2.219825] SLUB: HWalign=64, Order=0-3, MinObjects=0, CPUs=16, Nodes=1
[    2.306451] ftrace: allocating 33596 entries in 132 pages
[    2.392117] ftrace: allocated 132 pages with 2 groups
[    2.458286] rcu: Hierarchical RCU implementation.
[    2.519804] rcu:     RCU restricting CPUs from NR_CPUS=24 to nr_cpu_ids=16.
[    2.607527]  Rude variant of Tasks RCU enabled.
[    2.666768]  Tracing variant of Tasks RCU enabled.
[    2.729423] rcu: RCU calculated value of scheduler-enlistment delay is 100 jiffies.
[    2.829677] rcu: Adjusting geometry for rcu_fanout_leaf=16, nr_cpu_ids=16
[    2.923812] NR_IRQS: 4352, nr_irqs: 2184, preallocated irqs: 16
[    3.002072] Console: colour dummy device 80x25
[    3.060239] ACPI: Core revision 20200925
[    3.112091] clocksource: hpet: mask: 0xffffffff max_cycles: 0xffffffff, max_idle_ns: 79635855245 ns
[    3.230724] APIC: Switch to symmetric I/O mode setup
[    3.295777] DMAR: Host address width 39
[    3.346004] DMAR: DRHD base: 0x000000fed91000 flags: 0x1
[    3.415604] DMAR: dmar0: reg_base_addr fed91000 ver 1:0 cap d2008c40660462 ecap f050da
[    3.519379] DMAR: RMRR base: 0x0000009e699000 end: 0x0000009e8e2fff
[    3.601508] DMAR-IR: IOAPIC id 2 under DRHD base  0xfed91000 IOMMU 0
[    3.684771] DMAR-IR: HPET id 0 under DRHD base 0xfed91000
[    3.755507] DMAR-IR: Queued invalidation will be enabled to support x2apic and Intr-remapping.
[    3.871591] DMAR-IR: Enabled IRQ remapping in x2apic mode
[    3.942301] x2apic enabled
[    3.977704] Switched APIC routing to cluster x2apic.
[    4.052138] ..TIMER: vector=0x30 apic1=0 pin1=2 apic2=-1 pin2=-1
[    4.135807] clocksource: tsc-early: mask: 0xffffffffffffffff max_cycles: 0x1e44fb6c2ab, max_idle_ns: 440795206594 ns
[    4.273719] Calibrating delay loop (skipped), value calculated using timer frequency.. 4199.88 BogoMIPS (lpj=2099944)
[    4.274720] pid_max: default: 32768 minimum: 301
[    4.275747] LSM: Security Framework initializing
[    4.276739] AppArmor: AppArmor initialized
[    4.277835] Mount-cache hash table entries: 131072 (order: 8, 1048576 bytes, linear)
[    4.278824] Mountpoint-cache hash table entries: 131072 (order: 8, 1048576 bytes, linear)
[    4.280035] mce: CPU0: Thermal monitoring enabled (TM1)
[    4.280761] process: using mwait in idle threads
[    4.281722] Last level iTLB entries: 4KB 64, 2MB 8, 4MB 8
[    4.282719] Last level dTLB entries: 4KB 64, 2MB 0, 4MB 0, 1GB 4
[    4.283725] Speculative Store Bypass: Vulnerable
[    4.284719] TAA: Mitigation: TSX disabled
[    4.285720] SRBDS: Mitigation: TSX disabled
[    4.286898] Freeing SMP alternatives memory: 32K
[    4.288806] smpboot: CPU0: Intel(R) Core(TM) i9-9900T CPU @ 2.10GHz (family: 0x6, model: 0x9e, stepping: 0xd)
[    4.289826] Performance Events: PEBS fmt3+, Skylake events, 32-deep LBR, full-width counters, Intel PMU driver.
[    4.290721] ... version:                4
[    4.291720] ... bit width:              48
[    4.292719] ... generic registers:      4
[    4.293720] ... value mask:             0000ffffffffffff
[    4.294720] ... max period:             00007fffffffffff
[    4.295719] ... fixed-purpose events:   3
[    4.296719] ... event mask:             000000070000000f
[    4.297833] rcu: Hierarchical SRCU implementation.
[    4.299700] NMI watchdog: Enabled. Permanently consumes one hw-PMU counter.
[    4.299841] smp: Bringing up secondary CPUs ...
[    4.300793] x86: Booting SMP configuration:
[    4.301722] .... node  #0, CPUs:        #1  #2  #3  #4  #5  #6  #7  #8  #9 #10 #11 #12 #13 #14 #15
[    4.315607] smp: Brought up 1 node, 16 CPUs
[    4.316722] smpboot: Max logical packages: 1
[    4.317721] smpboot: Total of 16 processors activated (67198.20 BogoMIPS)
[    4.320622] devtmpfs: initialized
[    4.320925] random: get_random_u32 called from bucket_table_alloc.isra.31+0x66/0x150 with crng_init=0
[    4.320936] PM: Registering ACPI NVS region [mem 0x9dfe7000-0x9e417fff] (4395008 bytes)
[    4.322817] clocksource: jiffies: mask: 0xffffffff max_cycles: 0xffffffff, max_idle_ns: 1911260446275000 ns
[    4.323724] futex hash table entries: 4096 (order: 6, 262144 bytes, linear)
[    4.324789] pinctrl core: initialized pinctrl subsystem
[    4.325892] NET: Registered protocol family 16
[    4.326883] audit: initializing netlink subsys (disabled)
[    4.327729] audit: type=2000 audit(1680534966.074:1): state=initialized audit_enabled=0 res=1
[    4.327840] thermal_sys: Registered thermal governor 'step_wise'
[    4.328740] cpuidle: using governor ladder
[    4.330726] cpuidle: using governor menu
[    4.331804] ACPI FADT declares the system doesn't support PCIe ASPM, so disable it
[    4.332721] ACPI: bus type PCI registered
[    4.333720] acpiphp: ACPI Hot Plug PCI Controller Driver version: 0.5
[    4.334810] PCI: MMCONFIG for domain 0000 [bus 00-ff] at [mem 0xe0000000-0xefffffff] (base 0xe0000000)
[    4.335721] PCI: MMCONFIG at [mem 0xe0000000-0xefffffff] reserved in E820
[    4.336735] PCI: Using configuration type 1 for base access
[    4.338257] ENERGY_PERF_BIAS: Set to 'normal', was 'performance'
[    4.340581] Kprobes globally optimized
[    4.340756] ACPI: Added _OSI(Module Device)
[    4.395723] ACPI: Added _OSI(Processor Device)
[    4.453722] ACPI: Added _OSI(3.0 _SCP Extensions)
[    4.514721] ACPI: Added _OSI(Processor Aggregator Device)
[    4.585722] ACPI: Added _OSI(Linux-Dell-Video)
[    4.643722] ACPI: Added _OSI(Linux-Lenovo-NV-HDMI-Audio)
[    4.712722] ACPI: Added _OSI(Linux-HPI-Hybrid-Graphics)
[    4.859264] ACPI: 11 ACPI AML tables successfully acquired and loaded
[    4.953784] ACPI: Dynamic OEM Table Load:
[    5.005726] ACPI: SSDT 0xFFFF888101C48300 0000F4 (v02 PmRef  Cpu0Psd  00003000 INTL 20160527)
[    5.118097] ACPI: \_SB_.PR00: _OSC native thermal LVT Acked
[    5.193300] ACPI: Dynamic OEM Table Load:
[    5.245726] ACPI: SSDT 0xFFFF888101BC9000 000400 (v02 PmRef  Cpu0Cst  00003001 INTL 20160527)
[    5.358196] ACPI: Dynamic OEM Table Load:
[    5.410725] ACPI: SSDT 0xFFFF888100CAB800 0004BB (v02 PmRef  Cpu0Ist  00003000 INTL 20160527)
[    5.523249] ACPI: Dynamic OEM Table Load:
[    5.575724] ACPI: SSDT 0xFFFF888101417200 000128 (v02 PmRef  Cpu0Hwp  00003000 INTL 20160527)
[    5.689079] ACPI: Dynamic OEM Table Load:
[    5.740727] ACPI: SSDT 0xFFFF888100CAC000 000724 (v02 PmRef  HwpLvt   00003000 INTL 20160527)
[    5.854384] ACPI: Dynamic OEM Table Load:
[    5.906726] ACPI: SSDT 0xFFFF888100CAD800 0005FC (v02 PmRef  ApIst    00003000 INTL 20160527)
[    6.019260] ACPI: Dynamic OEM Table Load:
[    6.071725] ACPI: SSDT 0xFFFF888101BC9400 000317 (v02 PmRef  ApHwp    00003000 INTL 20160527)
[    6.185248] ACPI: Dynamic OEM Table Load:
[    6.236726] ACPI: SSDT 0xFFFF88810019F000 000AB0 (v02 PmRef  ApPsd    00003000 INTL 20160527)
[    6.350724] ACPI: Dynamic OEM Table Load:
[    6.402725] ACPI: SSDT 0xFFFF888101BC9800 00030A (v02 PmRef  ApCst    00003000 INTL 20160527)
[    6.523672] ACPI: Interpreter enabled
[    6.570744] ACPI: (supports S0 S4 S5)
[    6.618723] ACPI: Using IOAPIC for interrupt routing
[    6.683771] PCI: Using host bridge windows from ACPI; if necessary, use "pci=nocrs" and report a bug
[    6.804965] ACPI: Enabled 9 GPEs in block 00 to 7F
[    6.884739] ACPI: Power Resource [USBC] (on)
[    6.940910] ACPI: Power Resource [PAUD] (on)
[    7.000233] ACPI: Power Resource [V0PR] (on)
[    7.056731] ACPI: Power Resource [V1PR] (on)
[    7.112731] ACPI: Power Resource [V2PR] (on)
[    7.171924] ACPI: Power Resource [PXTC] (on)
[    7.231624] ACPI: Power Resource [WRST] (on)
[    7.292831] ACPI: Power Resource [FN00] (off)
[    7.349820] ACPI: Power Resource [FN01] (off)
[    7.406816] ACPI: Power Resource [FN02] (off)
[    7.463816] ACPI: Power Resource [FN03] (off)
[    7.520815] ACPI: Power Resource [FN04] (off)
[    7.578738] ACPI: Power Resource [PIN] (off)
[    7.634904] ACPI: Power Resource [SPR0] (off)
[    7.691788] ACPI: Power Resource [SPR1] (off)
[    7.748787] ACPI: Power Resource [SPR2] (off)
[    7.805787] ACPI: Power Resource [SPR3] (off)
[    7.862787] ACPI: Power Resource [SPR5] (off)
[    7.920061] ACPI: Power Resource [ZPDR] (off)
[    7.977129] ACPI: PCI Root Bridge [PCI0] (domain 0000 [bus 00-fe])
[    8.057730] acpi PNP0A08:00: _OSC: OS supports [ExtendedConfig ASPM ClockPM Segments MSI HPX-Type3]
[    8.178374] acpi PNP0A08:00: _OSC: platform does not support [AER]
[    8.261748] acpi PNP0A08:00: _OSC: OS now controls [PCIeHotplug PME PCIeCapability LTR]
[    8.366723] acpi PNP0A08:00: FADT indicates ASPM is unsupported, using BIOS configuration
[    8.474729] PCI host bridge to bus 0000:00
[    8.527723] pci_bus 0000:00: root bus resource [io  0x0000-0x0cf7 window]
[    8.616723] pci_bus 0000:00: root bus resource [io  0x0d00-0xffff window]
[    8.705722] pci_bus 0000:00: root bus resource [mem 0x000a0000-0x000bffff window]
[    8.802722] pci_bus 0000:00: root bus resource [mem 0xa0000000-0xdfffffff window]
[    8.900722] pci_bus 0000:00: root bus resource [mem 0xfc800000-0xfe7fffff window]
[    8.998723] pci_bus 0000:00: root bus resource [bus 00-fe]
[    9.070749] pci 0000:00:00.0: [8086:3e30] type 00 class 0x060000
[    9.149732] pci 0000:00:01.0: [8086:1901] type 01 class 0x060400
[    9.227774] pci 0000:00:01.0: PME# supported from D0 D3hot D3cold
[    9.307940] pci 0000:00:01.1: [8086:1905] type 01 class 0x060400
[    9.386772] pci 0000:00:01.1: PME# supported from D0 D3hot D3cold
[    9.467059] pci 0000:00:08.0: [8086:1911] type 00 class 0x088000
[    9.544733] pci 0000:00:08.0: reg 0x10: [mem 0xa223c000-0xa223cfff 64bit]
[    9.633994] pci 0000:00:12.0: [8086:a379] type 00 class 0x118000
[    9.712766] pci 0000:00:12.0: reg 0x10: [mem 0xa223b000-0xa223bfff 64bit]
[    9.802120] pci 0000:00:14.0: [8086:a36d] type 00 class 0x0c0330
[    9.880765] pci 0000:00:14.0: reg 0x10: [mem 0xa2220000-0xa222ffff 64bit]
[    9.969897] pci 0000:00:14.0: PME# supported from D3hot D3cold
[   10.046258] pci 0000:00:14.2: [8086:a36f] type 00 class 0x050000
[   10.124774] pci 0000:00:14.2: reg 0x10: [mem 0xa2234000-0xa2235fff 64bit]
[   10.213751] pci 0000:00:14.2: reg 0x18: [mem 0xa223a000-0xa223afff 64bit]
[   10.303430] pci 0000:00:15.0: [8086:a368] type 00 class 0x0c8000
[   10.382299] pci 0000:00:15.0: reg 0x10: [mem 0x00000000-0x00000fff 64bit]
[   10.473744] pci 0000:00:15.1: [8086:a369] type 00 class 0x0c8000
[   10.552312] pci 0000:00:15.1: reg 0x10: [mem 0x00000000-0x00000fff 64bit]
[   10.644374] pci 0000:00:1b.0: [8086:a340] type 01 class 0x060400
[   10.722982] pci 0000:00:1b.0: PME# supported from D0 D3hot D3cold
[   10.803099] pci 0000:00:1b.4: [8086:a32c] type 01 class 0x060400
[   10.881980] pci 0000:00:1b.4: PME# supported from D0 D3hot D3cold
[   10.962092] pci 0000:00:1c.0: [8086:a338] type 01 class 0x060400
[   11.040979] pci 0000:00:1c.0: PME# supported from D0 D3hot D3cold
[   11.120743] pci 0000:00:1c.5: [8086:a33d] type 01 class 0x060400
[   11.198980] pci 0000:00:1c.5: PME# supported from D0 D3hot D3cold
[   11.279743] pci 0000:00:1c.6: [8086:a33e] type 01 class 0x060400
[   11.357981] pci 0000:00:1c.6: PME# supported from D0 D3hot D3cold
[   11.438058] pci 0000:00:1c.7: [8086:a33f] type 01 class 0x060400
[   11.516981] pci 0000:00:1c.7: PME# supported from D0 D3hot D3cold
[   11.597454] pci 0000:00:1e.0: [8086:a328] type 00 class 0x078000
[   11.676311] pci 0000:00:1e.0: reg 0x10: [mem 0x00000000-0x00000fff 64bit]
[   11.767746] pci 0000:00:1f.0: [8086:a309] type 00 class 0x060100
[   11.846744] pci 0000:00:1f.3: [8086:a348] type 00 class 0x040300
[   11.924804] pci 0000:00:1f.3: reg 0x10: [mem 0xa2230000-0xa2233fff 64bit]
[   12.013823] pci 0000:00:1f.3: reg 0x20: [mem 0xa2100000-0xa21fffff 64bit]
[   12.102901] pci 0000:00:1f.3: PME# supported from D3hot D3cold
[   12.179747] pci 0000:00:1f.4: [8086:a323] type 00 class 0x0c0500
[   12.258905] pci 0000:00:1f.4: reg 0x10: [mem 0xa2236000-0xa22360ff 64bit]
[   12.347937] pci 0000:00:1f.4: reg 0x20: [io  0xefa0-0xefbf]
[   12.421169] pci 0000:00:1f.5: [8086:a324] type 00 class 0x0c8000
[   12.499770] pci 0000:00:1f.5: reg 0x10: [mem 0xfe010000-0xfe010fff]
[   12.582016] pci 0000:00:1f.6: [8086:15bb] type 00 class 0x020000
[   12.660772] pci 0000:00:1f.6: reg 0x10: [mem 0xa2200000-0xa221ffff]
[   12.743009] pci 0000:00:1f.6: PME# supported from D0 D3hot D3cold
[   12.822744] pci 0000:01:00.0: [9005:028d] type 00 class 0x010700
[   12.900734] pci 0000:01:00.0: reg 0x10: [mem 0xa3b00000-0xa3bfffff 64bit]
[   12.989729] pci 0000:01:00.0: reg 0x18: [mem 0xa3c80000-0xa3c803ff 64bit]
[   13.078727] pci 0000:01:00.0: reg 0x20: [io  0x5000-0x50ff]
[   13.150731] pci 0000:01:00.0: reg 0x30: [mem 0xa3c00000-0xa3c7ffff pref]
[   13.238763] pci 0000:01:00.0: PME# supported from D0 D1 D3hot
[   13.313794] pci 0000:00:01.0: PCI bridge to [bus 01]
[   13.378724] pci 0000:00:01.0:   bridge window [io  0x5000-0x5fff]
[   13.458723] pci 0000:00:01.0:   bridge window [mem 0xa3b00000-0xa3cfffff]
[   13.547774] pci 0000:02:00.0: [8086:1572] type 00 class 0x020000
[   13.625739] pci 0000:02:00.0: reg 0x10: [mem 0xa3000000-0xa37fffff 64bit pref]
[   13.720739] pci 0000:02:00.0: reg 0x1c: [mem 0xa3908000-0xa390ffff 64bit pref]
[   13.814758] pci 0000:02:00.0: reg 0x30: [mem 0xa3880000-0xa38fffff pref]
[   13.902790] pci 0000:02:00.0: PME# supported from D0 D3hot D3cold
[   13.981745] pci 0000:02:00.0: reg 0x184: [mem 0x00000000-0x0000ffff 64bit pref]
[   14.077723] pci 0000:02:00.0: VF(n) BAR0 space: [mem 0x00000000-0x003fffff 64bit pref] (contains BAR0 for 64 VFs)
[   14.211737] pci 0000:02:00.0: reg 0x190: [mem 0x00000000-0x00003fff 64bit pref]
[   14.307723] pci 0000:02:00.0: VF(n) BAR3 space: [mem 0x00000000-0x000fffff 64bit pref] (contains BAR3 for 64 VFs)
[   14.441924] pci 0000:02:00.1: [8086:1572] type 00 class 0x020000
[   14.520739] pci 0000:02:00.1: reg 0x10: [mem 0xa2800000-0xa2ffffff 64bit pref]
[   14.614739] pci 0000:02:00.1: reg 0x1c: [mem 0xa3900000-0xa3907fff 64bit pref]
[   14.708736] pci 0000:02:00.1: reg 0x30: [mem 0xa3800000-0xa387ffff pref]
[   14.796786] pci 0000:02:00.1: PME# supported from D0 D3hot D3cold
[   14.876744] pci 0000:02:00.1: reg 0x184: [mem 0x00000000-0x0000ffff 64bit pref]
[   14.971723] pci 0000:02:00.1: VF(n) BAR0 space: [mem 0x00000000-0x003fffff 64bit pref] (contains BAR0 for 64 VFs)
[   15.106736] pci 0000:02:00.1: reg 0x190: [mem 0x00000000-0x00003fff 64bit pref]
[   15.201722] pci 0000:02:00.1: VF(n) BAR3 space: [mem 0x00000000-0x000fffff 64bit pref] (contains BAR3 for 64 VFs)
[   15.336732] pci 0000:00:01.1: PCI bridge to [bus 02]
[   15.400725] pci 0000:00:01.1:   bridge window [mem 0xa2800000-0xa39fffff]
[   15.489725] pci 0000:00:01.1: bridge has subordinate 02 but max busn 03
[   15.576865] pci 0000:00:1b.0: PCI bridge to [bus 03]
[   15.641928] pci 0000:04:00.0: [144d:a808] type 00 class 0x010802
[   15.719789] pci 0000:04:00.0: reg 0x10: [mem 0xa3e00000-0xa3e03fff 64bit]
[   15.809747] pci 0000:00:1b.4: PCI bridge to [bus 04]
[   15.874732] pci 0000:00:1b.4:   bridge window [mem 0xa3e00000-0xa3efffff]
[   15.962862] pci 0000:00:1c.0: PCI bridge to [bus 05]
[   16.027934] pci 0000:06:00.0: [8086:1533] type 00 class 0x020000
[   16.106788] pci 0000:06:00.0: reg 0x10: [mem 0xa3d00000-0xa3d7ffff]
[   16.188780] pci 0000:06:00.0: reg 0x18: [io  0x4000-0x401f]
[   16.261756] pci 0000:06:00.0: reg 0x1c: [mem 0xa3d80000-0xa3d83fff]
[   16.344012] pci 0000:06:00.0: PME# supported from D0 D3hot D3cold
[   16.423962] pci 0000:00:1c.5: PCI bridge to [bus 06]
[   16.488729] pci 0000:00:1c.5:   bridge window [io  0x4000-0x4fff]
[   16.568726] pci 0000:00:1c.5:   bridge window [mem 0xa3d00000-0xa3dfffff]
[   16.656893] pci 0000:07:00.0: [1a03:1150] type 01 class 0x060400
[   16.735830] pci 0000:07:00.0: enabling Extended Tags
[   16.800853] pci 0000:07:00.0: supports D1 D2
[   16.856721] pci 0000:07:00.0: PME# supported from D0 D1 D2 D3hot D3cold
[   16.942890] pci 0000:00:1c.6: PCI bridge to [bus 07-08]
[   17.011727] pci 0000:00:1c.6:   bridge window [io  0x3000-0x3fff]
[   17.090729] pci 0000:00:1c.6:   bridge window [mem 0xa1000000-0xa20fffff]
[   17.179802] pci_bus 0000:08: extended config space not accessible
[   17.259773] pci 0000:08:00.0: [1a03:2000] type 00 class 0x030000
[   17.338754] pci 0000:08:00.0: reg 0x10: [mem 0xa1000000-0xa1ffffff]
[   17.420741] pci 0000:08:00.0: reg 0x14: [mem 0xa2000000-0xa201ffff]
[   17.501741] pci 0000:08:00.0: reg 0x18: [io  0x3000-0x307f]
[   17.574876] pci 0000:08:00.0: supports D1 D2
[   17.630723] pci 0000:08:00.0: PME# supported from D0 D1 D2 D3hot D3cold
[   17.717885] pci 0000:07:00.0: PCI bridge to [bus 08]
[   17.782734] pci 0000:07:00.0:   bridge window [io  0x3000-0x3fff]
[   17.861727] pci 0000:07:00.0:   bridge window [mem 0xa1000000-0xa20fffff]
[   17.950929] pci 0000:09:00.0: [10e3:8113] type 01 class 0x060401
[   18.030022] pci 0000:09:00.0: PME# supported from D0 D1 D2 D3hot D3cold
[   18.116738] pci 0000:00:1c.7: PCI bridge to [bus 09-0a]
[   18.184807] pci_bus 0000:0a: extended config space not accessible
[   18.264864] pci 0000:09:00.0: PCI bridge to [bus 0a] (subtractive decode)
[   18.355742] ACPI: PCI Interrupt Link [LNKA] (IRQs 3 4 5 6 10 11 12 14 15) *0
[   18.447819] ACPI: PCI Interrupt Link [LNKB] (IRQs 3 4 5 6 10 11 12 14 15) *1
[   18.539816] ACPI: PCI Interrupt Link [LNKC] (IRQs 3 4 5 6 10 11 12 14 15) *0
[   18.632815] ACPI: PCI Interrupt Link [LNKD] (IRQs 3 4 5 6 10 11 12 14 15) *0
[   18.724815] ACPI: PCI Interrupt Link [LNKE] (IRQs 3 4 5 6 10 11 12 14 15) *0
[   18.816815] ACPI: PCI Interrupt Link [LNKF] (IRQs 3 4 5 6 10 11 12 14 15) *0
[   18.908815] ACPI: PCI Interrupt Link [LNKG] (IRQs 3 4 5 6 10 11 12 14 15) *0
[   19.001815] ACPI: PCI Interrupt Link [LNKH] (IRQs 3 4 5 6 10 11 12 14 15) *0
[   19.095124] iommu: Default domain type: Passthrough (set via kernel command line)
[   19.192747] pci 0000:08:00.0: vgaarb: setting as boot VGA device
[   19.193718] pci 0000:08:00.0: vgaarb: VGA device added: decodes=io+mem,owns=io+mem,locks=none
[   19.382730] pci 0000:08:00.0: vgaarb: bridge control possible
[   19.457722] vgaarb: loaded
[   19.493774] SCSI subsystem initialized
[   19.542743] libata version 3.00 loaded.
[   19.592751] pps_core: LinuxPPS API ver. 1 registered
[   19.657723] pps_core: Software ver. 5.3.6 - Copyright 2005-2007 Rodolfo Giometti <giometti@linux.it>
[   19.776727] PTP clock support registered
[   19.827745] EDAC MC: Ver: 3.0.0
[   19.869897] PCI: Using ACPI for IRQ routing
[   20.008137] PCI: pci_cache_line_size set to 64 bytes
[   20.073161] e820: reserve RAM buffer [mem 0x0009b000-0x0009ffff]
[   20.151723] e820: reserve RAM buffer [mem 0x9a2f2000-0x9bffffff]
[   20.230723] e820: reserve RAM buffer [mem 0x9dfe7000-0x9fffffff]
[   20.308722] e820: reserve RAM buffer [mem 0x9ec10000-0x9fffffff]
[   20.387844] clocksource: Switched to clocksource tsc-early
[   20.471943] VFS: Disk quotas dquot_6.6.0
[   20.523293] VFS: Dquot-cache hash table entries: 512 (order 0, 4096 bytes)
[   20.613354] AppArmor: AppArmor Filesystem Enabled
[   20.674933] pnp: PnP ACPI init
[   20.714984] system 00:00: [mem 0x40000000-0x403fffff] could not be reserved
[   20.806131] system 00:00: Plug and Play ACPI device, IDs PNP0c02 (active)
[   20.895133] system 00:01: Plug and Play ACPI device, IDs PNP0c02 (active)
[   20.984607] pnp 00:02: [dma 0 disabled]
[   21.034859] pnp 00:02: Plug and Play ACPI device, IDs PNP0501 (active)
[   21.120642] system 00:03: [io  0x0a00-0x0a1f] has been reserved
[   21.198139] system 00:03: [io  0x0a20-0x0a2f] has been reserved
[   21.275603] system 00:03: [io  0x0a30-0x0a3f] has been reserved
[   21.353068] system 00:03: [io  0x0a40-0x0a4f] has been reserved
[   21.430543] system 00:03: Plug and Play ACPI device, IDs PNP0c02 (active)
[   21.519947] pnp 00:04: [dma 0 disabled]
[   21.570183] pnp 00:04: Plug and Play ACPI device, IDs PNP0501 (active)
[   21.655877] system 00:05: [io  0x0680-0x069f] has been reserved
[   21.733373] system 00:05: [io  0x164e-0x164f] has been reserved
[   21.810847] system 00:05: Plug and Play ACPI device, IDs PNP0c02 (active)
[   21.899843] system 00:06: [io  0x1854-0x1857] has been reserved
[   21.977387] system 00:06: Plug and Play ACPI device, IDs INT3f0d PNP0c02 (active)
[   22.075599] system 00:07: [mem 0xfed10000-0xfed17fff] has been reserved
[   22.162269] system 00:07: [mem 0xfed18000-0xfed18fff] has been reserved
[   22.248854] system 00:07: [mem 0xfed19000-0xfed19fff] has been reserved
[   22.335466] system 00:07: [mem 0xe0000000-0xefffffff] has been reserved
[   22.422029] system 00:07: [mem 0xfed20000-0xfed3ffff] has been reserved
[   22.508624] system 00:07: [mem 0xfed90000-0xfed93fff] could not be reserved
[   22.599774] system 00:07: [mem 0xfed45000-0xfed8ffff] has been reserved
[   22.686368] system 00:07: [mem 0xfee00000-0xfeefffff] could not be reserved
[   22.777519] system 00:07: Plug and Play ACPI device, IDs PNP0c02 (active)
[   22.866662] system 00:08: [io  0x1800-0x18fe] could not be reserved
[   22.948729] system 00:08: [mem 0xfd000000-0xfd69ffff] has been reserved
[   23.035309] system 00:08: [mem 0xfd6c0000-0xfd6cffff] has been reserved
[   23.121891] system 00:08: [mem 0xfd6f0000-0xfdffffff] has been reserved
[   23.208480] system 00:08: [mem 0xfe000000-0xfe01ffff] could not be reserved
[   23.299631] system 00:08: [mem 0xfe200000-0xfe7fffff] has been reserved
[   23.386217] system 00:08: [mem 0xff000000-0xffffffff] has been reserved
[   23.472812] system 00:08: Plug and Play ACPI device, IDs PNP0c02 (active)
[   23.562043] system 00:09: [io  0x2000-0x20fe] has been reserved
[   23.639566] system 00:09: Plug and Play ACPI device, IDs PNP0c02 (active)
[   23.729803] system 00:0a: [mem 0xfd6e0000-0xfd6effff] has been reserved
[   23.816468] system 00:0a: [mem 0xfd6d0000-0xfd6dffff] has been reserved
[   23.903057] system 00:0a: [mem 0xfd6b0000-0xfd6bffff] has been reserved
[   23.989651] system 00:0a: [mem 0xfd6a0000-0xfd6affff] has been reserved
[   24.076251] system 00:0a: Plug and Play ACPI device, IDs PNP0c02 (active)
[   24.166389] pnp: PnP ACPI: found 11 devices
[   24.227084] clocksource: acpi_pm: mask: 0xffffff max_cycles: 0xffffff, max_idle_ns: 2085701024 ns
[   24.343398] NET: Registered protocol family 2
[   24.400620] IP idents hash table entries: 262144 (order: 9, 2097152 bytes, linear)
[   24.502095] tcp_listen_portaddr_hash hash table entries: 32768 (order: 7, 524288 bytes, linear)
[   24.616161] TCP established hash table entries: 524288 (order: 10, 4194304 bytes, linear)
[   24.723840] TCP bind hash table entries: 65536 (order: 8, 1048576 bytes, linear)
[   24.820851] TCP: Hash tables configured (established 524288 bind 65536)
[   24.907476] UDP hash table entries: 32768 (order: 8, 1048576 bytes, linear)
[   24.998832] UDP-Lite hash table entries: 32768 (order: 8, 1048576 bytes, linear)
[   25.095917] NET: Registered protocol family 1
[   25.152940] pci 0000:00:01.1: bridge window [mem 0x00100000-0x000fffff 64bit pref] to [bus 02] add_size a00000 add_align 100000
[   25.303339] pci 0000:00:01.1: BAR 15: assigned [mem 0xa0000000-0xa09fffff 64bit pref]
[   25.405871] pci 0000:00:15.0: BAR 0: assigned [mem 0xa0a00000-0xa0a00fff 64bit]
[   25.501838] pci 0000:00:15.1: BAR 0: assigned [mem 0xa0a01000-0xa0a01fff 64bit]
[   25.597850] pci 0000:00:1e.0: BAR 0: assigned [mem 0xa0a02000-0xa0a02fff 64bit]
[   25.693866] pci 0000:00:01.0: PCI bridge to [bus 01]
[   25.758849] pci 0000:00:01.0:   bridge window [io  0x5000-0x5fff]
[   25.838604] pci 0000:00:01.0:   bridge window [mem 0xa3b00000-0xa3cfffff]
[   25.927479] pci 0000:02:00.0: BAR 7: assigned [mem 0xa0000000-0xa03fffff 64bit pref]
[   26.028886] pci 0000:02:00.1: BAR 7: assigned [mem 0xa0400000-0xa07fffff 64bit pref]
[   26.130291] pci 0000:02:00.0: BAR 10: assigned [mem 0xa0800000-0xa08fffff 64bit pref]
[   26.232843] pci 0000:02:00.1: BAR 10: assigned [mem 0xa0900000-0xa09fffff 64bit pref]
[   26.335387] pci 0000:00:01.1: PCI bridge to [bus 02]
[   26.400328] pci 0000:00:01.1:   bridge window [mem 0xa2800000-0xa39fffff]
[   26.489198] pci 0000:00:01.1:   bridge window [mem 0xa0000000-0xa09fffff 64bit pref]
[   26.590605] pci 0000:00:1b.0: PCI bridge to [bus 03]
[   26.655574] pci 0000:00:1b.4: PCI bridge to [bus 04]
[   26.720505] pci 0000:00:1b.4:   bridge window [mem 0xa3e00000-0xa3efffff]
[   26.809379] pci 0000:00:1c.0: PCI bridge to [bus 05]
[   26.874335] pci 0000:00:1c.5: PCI bridge to [bus 06]
[   26.939256] pci 0000:00:1c.5:   bridge window [io  0x4000-0x4fff]
[   27.019021] pci 0000:00:1c.5:   bridge window [mem 0xa3d00000-0xa3dfffff]
[   27.107904] pci 0000:07:00.0: PCI bridge to [bus 08]
[   27.172837] pci 0000:07:00.0:   bridge window [io  0x3000-0x3fff]
[   27.252597] pci 0000:07:00.0:   bridge window [mem 0xa1000000-0xa20fffff]
[   27.341471] pci 0000:00:1c.6: PCI bridge to [bus 07-08]
[   27.409825] pci 0000:00:1c.6:   bridge window [io  0x3000-0x3fff]
[   27.489583] pci 0000:00:1c.6:   bridge window [mem 0xa1000000-0xa20fffff]
[   27.578467] pci 0000:09:00.0: PCI bridge to [bus 0a]
[   27.643418] pci 0000:00:1c.7: PCI bridge to [bus 09-0a]
[   27.711782] pci_bus 0000:00: resource 4 [io  0x0000-0x0cf7 window]
[   27.792654] pci_bus 0000:00: resource 5 [io  0x0d00-0xffff window]
[   27.873553] pci_bus 0000:00: resource 6 [mem 0x000a0000-0x000bffff window]
[   27.963562] pci_bus 0000:00: resource 7 [mem 0xa0000000-0xdfffffff window]
[   28.053570] pci_bus 0000:00: resource 8 [mem 0xfc800000-0xfe7fffff window]
[   28.143579] pci_bus 0000:01: resource 0 [io  0x5000-0x5fff]
[   28.216496] pci_bus 0000:01: resource 1 [mem 0xa3b00000-0xa3cfffff]
[   28.298529] pci_bus 0000:02: resource 1 [mem 0xa2800000-0xa39fffff]
[   28.380565] pci_bus 0000:02: resource 2 [mem 0xa0000000-0xa09fffff 64bit pref]
[   28.475129] pci_bus 0000:04: resource 1 [mem 0xa3e00000-0xa3efffff]
[   28.557163] pci_bus 0000:06: resource 0 [io  0x4000-0x4fff]
[   28.630085] pci_bus 0000:06: resource 1 [mem 0xa3d00000-0xa3dfffff]
[   28.712118] pci_bus 0000:07: resource 0 [io  0x3000-0x3fff]
[   28.785036] pci_bus 0000:07: resource 1 [mem 0xa1000000-0xa20fffff]
[   28.867071] pci_bus 0000:08: resource 0 [io  0x3000-0x3fff]
[   28.939988] pci_bus 0000:08: resource 1 [mem 0xa1000000-0xa20fffff]
[   29.022792] pci 0000:08:00.0: Video device with shadowed ROM at [mem 0x000c0000-0x000dffff]
[   29.132232] pci 0000:08:00.0: pci_fixup_video+0x0/0xb0 took 106886 usecs
[   29.219969] PCI: CLS 64 bytes, default 64
[   31.257816] Trying to unpack rootfs image as initramfs...
[   31.367658] Freeing initrd memory: 81136K
[   31.420137] DMAR: No ATSR found
[   31.461299] DMAR: dmar0: Using Queued invalidation
[   31.524046] pci 0000:00:00.0: Adding to iommu group 0
[   31.590196] pci 0000:00:01.0: Adding to iommu group 1
[   31.656364] pci 0000:00:01.1: Adding to iommu group 1
[   31.722446] pci 0000:00:08.0: Adding to iommu group 2
[   31.788528] pci 0000:00:12.0: Adding to iommu group 3
[   31.854616] pci 0000:00:14.0: Adding to iommu group 4
[   31.920689] pci 0000:00:14.2: Adding to iommu group 4
[   31.986777] pci 0000:00:15.0: Adding to iommu group 5
[   32.052850] pci 0000:00:15.1: Adding to iommu group 5
[   32.118951] pci 0000:00:1b.0: Adding to iommu group 6
[   32.185026] pci 0000:00:1b.4: Adding to iommu group 7
[   32.251114] pci 0000:00:1c.0: Adding to iommu group 8
[   32.317295] pci 0000:00:1c.5: Adding to iommu group 9
[   32.383376] pci 0000:00:1c.6: Adding to iommu group 10
[   32.450601] pci 0000:00:1c.7: Adding to iommu group 11
[   32.517924] pci 0000:00:1e.0: Adding to iommu group 12
[   32.585168] pci 0000:00:1f.0: Adding to iommu group 13
[   32.652476] pci 0000:00:1f.3: Adding to iommu group 13
[   32.719701] pci 0000:00:1f.4: Adding to iommu group 13
[   32.786922] pci 0000:00:1f.5: Adding to iommu group 13
[   32.854143] pci 0000:00:1f.6: Adding to iommu group 13
[   32.921357] pci 0000:01:00.0: Adding to iommu group 1
[   32.987438] pci 0000:02:00.0: Adding to iommu group 1
[   33.053521] pci 0000:02:00.1: Adding to iommu group 1
[   33.119630] pci 0000:04:00.0: Adding to iommu group 14
[   33.186951] pci 0000:06:00.0: Adding to iommu group 15
[   33.254180] pci 0000:07:00.0: Adding to iommu group 16
[   33.321393] pci 0000:08:00.0: Adding to iommu group 16
[   33.388640] pci 0000:09:00.0: Adding to iommu group 17
[   33.455987] DMAR: Intel(R) Virtualization Technology for Directed I/O
[   33.540374] PCI-DMA: Using software bounce buffering for IO (SWIOTLB)
[   33.624684] software IO TLB: mapped [mem 0x00000000962f2000-0x000000009a2f2000] (64MB)
[   33.728615] RAPL PMU: API unit is 2^-32 Joules, 3 fixed counters, 655360 ms ovfl timer
[   33.832367] RAPL PMU: hw unit of domain pp0-core 2^-14 Joules
[   33.907564] RAPL PMU: hw unit of domain package 2^-14 Joules
[   33.981625] RAPL PMU: hw unit of domain dram 2^-14 Joules
[   34.052657] platform rtc_cmos: registered platform RTC device (no PNP device found)
[   34.157371] Initialise system trusted keyrings
[   34.215566] workingset: timestamp_bits=40 max_order=24 bucket_order=0
[   34.301781] Key type asymmetric registered
[   34.355356] Asymmetric key parser 'x509' registered
[   34.419177] Block layer SCSI generic (bsg) driver version 0.4 loaded (major 250)
[   34.516016] io scheduler mq-deadline registered
[   34.575259] io scheduler kyber registered
[   34.627701] io scheduler bfq registered
[   34.678362] pcieport 0000:00:01.0: PME: Signaling with IRQ 121
[   34.755011] pcieport 0000:00:01.1: PME: Signaling with IRQ 122
[   34.831719] pcieport 0000:00:1b.0: PME: Signaling with IRQ 123
[   34.908453] pcieport 0000:00:1b.4: PME: Signaling with IRQ 124
[   34.985205] pcieport 0000:00:1c.0: PME: Signaling with IRQ 125
[   35.061962] pcieport 0000:00:1c.5: PME: Signaling with IRQ 126
[   35.138699] pcieport 0000:00:1c.6: PME: Signaling with IRQ 127
[   35.197748] tsc: Refined TSC clocksource calibration: 2112.011 MHz
[   35.215577] pcieport 0000:00:1c.7: PME: Signaling with IRQ 128
[   35.295983] clocksource: tsc: mask: 0xffffffffffffffff max_cycles: 0x1e718300d46, max_idle_ns: 440795287503 ns
[   35.372872] Monitor-Mwait will be used to enter C-1 state
[   35.574006] clocksource: Switched to clocksource tsc
[   35.574012] Monitor-Mwait will be used to enter C-2 state
[   35.708998] Monitor-Mwait will be used to enter C-3 state
[   35.779230] ACPI: \_SB_.PR00: Found 3 idle states
[   35.840628] ACPI: \_SB_.PR01: Found 3 idle states
[   35.901980] ACPI: \_SB_.PR02: Found 3 idle states
[   35.963357] ACPI: \_SB_.PR03: Found 3 idle states
[   36.024729] ACPI: \_SB_.PR04: Found 3 idle states
[   36.086106] ACPI: \_SB_.PR05: Found 3 idle states
[   36.147483] ACPI: \_SB_.PR06: Found 3 idle states
[   36.208878] ACPI: \_SB_.PR07: Found 3 idle states
[   36.270251] ACPI: \_SB_.PR08: Found 3 idle states
[   36.331634] ACPI: \_SB_.PR09: Found 3 idle states
[   36.393002] ACPI: \_SB_.PR10: Found 3 idle states
[   36.454435] ACPI: \_SB_.PR11: Found 3 idle states
[   36.515846] ACPI: \_SB_.PR12: Found 3 idle states
[   36.577280] ACPI: \_SB_.PR13: Found 3 idle states
[   36.638638] ACPI: \_SB_.PR14: Found 3 idle states
[   36.700023] ACPI: \_SB_.PR15: Found 3 idle states
[   36.822964] Serial: 8250/16550 driver, 4 ports, IRQ sharing disabled
[   36.905851] serial8250: ttyS0 at I/O 0x3f8 (irq = 4, base_baud = 115200) is a 16550A
[   37.006788] printk: console [ttyS0] enabled
[   37.016291] printk: bootconsole [uart8250] disabled
[   37.027795] AMD-Vi: AMD IOMMUv2 driver by Joerg Roedel <jroedel@suse.de>
[   37.035103] AMD-Vi: AMD IOMMUv2 functionality not available on this system
[   37.046181] brd: module loaded
[   37.049594] Loading iSCSI transport class v2.0-870.
[   37.055835] rdac: device handler registered
[   37.062643] nvme 0000:04:00.0: platform quirk: setting simple suspend
[   37.069812] nvme nvme0: pci function 0000:04:00.0
[   37.074973] i2c /dev entries driver
[   37.079442] NET: Registered protocol family 17
[   37.081347] nvme nvme0: Shutdown timeout set to 8 seconds
[   37.084313] Key type dns_resolver registered
[   37.096240] IPI shorthand broadcast: enabled
[   37.100943] sched_clock: Marking stable (35848995550, 1251904629)->(41074386684, -3973486505)
[   37.103856] nvme nvme0: 16/0/0 default/read/poll queues
[   37.110313] registered taskstats version 1
[   37.118392]  nvme0n1:
[   37.120417] Loading compiled-in X.509 certificates
[   37.128147] Loaded X.509 cert 'Synology SDG kernel module signing key: 7bd0b0d6bcd31651c22ce3978bdc8c8bdc417329'
[   37.141301] Loaded X.509 cert 'Synology Root Certification Authority: f2c075361f168425f8b5ef31b796406c3aab2089'
[   37.152312] Loaded X.509 cert 'Synology Kernel Module Signing Certification Authority: 600839b5d127e0e11d817a31f0575d323a7c0e28'
[   37.164907] Loaded X.509 cert 'Synology kernel module signing key: 4646ce54489669338118a3b1286da156ac366fa5'
[   37.175613] page_owner is disabled
[   37.179344] AppArmor: AppArmor sha1 policy hashing enabled
[   37.189512] Freeing unused kernel image (initmem) memory: 1356K
[   37.215871] Write protecting the kernel read-only data: 18432k
[   37.223001] Freeing unused kernel image (text/rodata gap) memory: 2036K
[   37.230421] Freeing unused kernel image (rodata/data gap) memory: 520K
[   37.237535] rodata_test: all tests were successful
[   37.242776] Run /init as init process
[   37.246776]   with arguments:
[   37.250001]     /init
[   37.252481]     synoboot2
[   37.255338]   with environment:
[   37.258757]     HOME=/
[   37.261331]     TERM=linux
[   37.264277]     BOOT_IMAGE=/zImage-dsm
[   37.268370]     pid=0x5583
[   37.271329]     vid=0x0781
[   37.711733] random: crng init done
[   37.737885] redpill: loading out-of-tree module taints kernel.
[   37.745219] redpill: module verification failed: signature and/or required key missing - tainting kernel
[   37.758356] <redpill/redpill_main.c:45> ================================================================================================
[   37.771695] <redpill/redpill_main.c:46> RedPill v0.6-at-2023_03_12-19_43_26 loading...
[   37.835544] <redpill/symbol_helper.c:100> kallsyms_lookup_name address = 0xffffffff810fcb90
[   37.835544] 
[   37.848655] <redpill/call_protected.c:83> Got addr ffffffff812cac30 for cmdline_proc_show
[   37.857569] <redpill/cmdline_delegate.c:350> Cmdline count: 411
[   37.864022] <redpill/cmdline_delegate.c:417> Cmdline: BOOT_IMAGE=/zImage-dsm console=ttyS0,115200n8 earlyprintk log_buf_len=32M earlycon=uart8250,io,0x3f8,115200n8 root=/dev/md0 loglevel=15 noefi syno_hw_version=SA6400 i915.enable_guc=2 netif_num=4 synoboot2 pid=0x5583 mac2=7e21363bcd3b mac3=7e21363bcd5b mac1=7e21363bcd1b mac4=7e21363bcd7b sn=0000XXXBN4YEE SMBusHddDynamicPower=1 vid=0x0781 vender_format_version=2 syno_ttyS1=serial,0x2f8 syno_ttyS0=serial,0x3f8
[   37.864022] 
[   37.909887] <redpill/cmdline_delegate.c:429> Param #0: |BOOT_IMAGE=/zImage-dsm|
[   37.917848] <redpill/cmdline_delegate.c:324> Option "BOOT_IMAGE=/zImage-dsm" not recognized - ignoring
[   37.927975] <redpill/cmdline_delegate.c:429> Param #1: |console=ttyS0,115200n8|
[   37.935931] <redpill/cmdline_delegate.c:324> Option "console=ttyS0,115200n8" not recognized - ignoring
[   37.946062] <redpill/cmdline_delegate.c:429> Param #2: |earlyprintk|
[   37.952979] <redpill/cmdline_delegate.c:324> Option "earlyprintk" not recognized - ignoring
[   37.962075] <redpill/cmdline_delegate.c:429> Param #3: |log_buf_len=32M|
[   37.969368] <redpill/cmdline_delegate.c:324> Option "log_buf_len=32M" not recognized - ignoring
[   37.978826] <redpill/cmdline_delegate.c:429> Param #4: |earlycon=uart8250,io,0x3f8,115200n8|
[   37.988011] <redpill/cmdline_delegate.c:324> Option "earlycon=uart8250,io,0x3f8,115200n8" not recognized - ignoring
[   37.999368] <redpill/cmdline_delegate.c:429> Param #5: |root=/dev/md0|
[   38.006480] <redpill/cmdline_delegate.c:324> Option "root=/dev/md0" not recognized - ignoring
[   38.015756] <redpill/cmdline_delegate.c:429> Param #6: |loglevel=15|
[   38.022673] <redpill/cmdline_delegate.c:324> Option "loglevel=15" not recognized - ignoring
[   38.031761] <redpill/cmdline_delegate.c:429> Param #7: |noefi|
[   38.038107] <redpill/cmdline_delegate.c:324> Option "noefi" not recognized - ignoring
[   38.046627] <redpill/cmdline_delegate.c:429> Param #8: |syno_hw_version=SA6400|
[   38.054584] <redpill/cmdline_delegate.c:26> HW version set to: SA6400
[   38.061595] <redpill/cmdline_delegate.c:429> Param #9: |i915.enable_guc=2|
[   38.069080] <redpill/cmdline_delegate.c:324> Option "i915.enable_guc=2" not recognized - ignoring
[   38.078725] <redpill/cmdline_delegate.c:429> Param #10: |netif_num=4|
[   38.085737] <redpill/cmdline_delegate.c:239> Declared network ifaces # as 4
[   38.093313] <redpill/cmdline_delegate.c:429> Param #11: |synoboot2|
[   38.100137] <redpill/cmdline_delegate.c:324> Option "synoboot2" not recognized - ignoring
[   38.109039] <redpill/cmdline_delegate.c:429> Param #12: |pid=0x5583|
[   38.115964] <redpill/cmdline_delegate.c:142> PID override: 0x5583
[   38.122596] <redpill/cmdline_delegate.c:429> Param #13: |mac2=7e21363bcd3b|
[   38.130167] <redpill/cmdline_delegate.c:312> Set MAC #1: 7e21363bcd3b
[   38.137179] <redpill/cmdline_delegate.c:429> Param #14: |mac3=7e21363bcd5b|
[   38.144757] <redpill/cmdline_delegate.c:312> Set MAC #2: 7e21363bcd5b
[   38.151768] <redpill/cmdline_delegate.c:429> Param #15: |mac1=7e21363bcd1b|
[   38.159338] <redpill/cmdline_delegate.c:312> Set MAC #3: 7e21363bcd1b
[   38.166349] <redpill/cmdline_delegate.c:429> Param #16: |mac4=7e21363bcd7b|
[   38.173924] <redpill/cmdline_delegate.c:312> Set MAC #4: 7e21363bcd7b
[   38.180938] <redpill/cmdline_delegate.c:429> Param #17: |sn=0000XXXBN4YEE|
[   38.188421] <redpill/cmdline_delegate.c:45> S/N set to: 0000XXXBN4YEE
[   38.195431] <redpill/cmdline_delegate.c:429> Param #18: |SMBusHddDynamicPower=1|
[   38.203482] <redpill/cmdline_delegate.c:324> Option "SMBusHddDynamicPower=1" not recognized - ignoring
[   38.213606] <redpill/cmdline_delegate.c:429> Param #19: |vid=0x0781|
[   38.220524] <redpill/cmdline_delegate.c:108> VID override: 0x0781
[   38.227159] <redpill/cmdline_delegate.c:429> Param #20: |vender_format_version=2|
[   38.235305] <redpill/cmdline_delegate.c:324> Option "vender_format_version=2" not recognized - ignoring
[   38.245530] <redpill/cmdline_delegate.c:429> Param #21: |syno_ttyS1=serial,0x2f8|
[   38.253675] <redpill/cmdline_delegate.c:324> Option "syno_ttyS1=serial,0x2f8" not recognized - ignoring
[   38.263900] <redpill/cmdline_delegate.c:429> Param #22: |syno_ttyS0=serial,0x3f8|
[   38.272047] <redpill/cmdline_delegate.c:324> Option "syno_ttyS0=serial,0x3f8" not recognized - ignoring
[   38.282281] <redpill/cmdline_delegate.c:388> Add cmdline blacklist "vid=" @ 0
[   38.290051] <redpill/cmdline_delegate.c:389> Add cmdline blacklist "pid=" @ 1
[   38.297802] <redpill/cmdline_delegate.c:390> Add cmdline blacklist "mfg" @ 2
[   38.305476] <redpill/cmdline_delegate.c:391> Add cmdline blacklist "dom_szmax=" @ 3
[   38.313814] <redpill/cmdline_delegate.c:392> Add cmdline blacklist "elevator=" @ 4
[   38.322054] <redpill/cmdline_delegate.c:393> Add cmdline blacklist "loglevel=" @ 5
[   38.330295] <redpill/cmdline_delegate.c:394> Add cmdline blacklist "log_buf_len=" @ 6
[   38.338816] <redpill/cmdline_delegate.c:395> Add cmdline blacklist "earlyprintk" @ 7
[   38.347247] <redpill/cmdline_delegate.c:396> Add cmdline blacklist "syno_port_thaw=" @ 8
[   38.356062] <redpill/cmdline_delegate.c:399> Add cmdline blacklist "synoboot_satadom=" @ 9
[   38.365047] <redpill/cmdline_delegate.c:450> CmdLine processed successfully, tokens=23
[   38.373666] <redpill/runtime_config.c:187> Found platform definition for "SA6400"
[   38.381817] <redpill/runtime_config.c:198> Validating runtime config...
[   38.389015] <redpill/runtime_config.c:48> Configured boot device type to USB
[   38.396678] <redpill/runtime_config.c:206> Config validation resulted in OK
[   38.404252] <redpill/runtime_config.c:224> Runtime config populated
[   38.411079] <redpill/uart_fixer.c:72> Registering UART fixer shim
[   38.417716] <redpill/uart_fixer.c:86> Successfully registered UART fixer shim
[   38.425476] <redpill/scsi_notifier.c:164> Registering SCSI device notifier
[   38.432959] <redpill/scsi_notifier.c:176> The sd driver was already loaded when SCSI device notifier registered - some devices may already be registered
[   38.447806] <redpill/scsi_notifier.c:104> Overriding (%pf?)()<0000000030abf4b5> with (%pf?)()<0000000036f2baca>
[   38.458775] <redpill/scsi_notifier.c:192> Successfully registered SCSI device notifier
[   38.467393] <redpill/sata_port_shim.c:119> Registering SATA port emulator shim
[   38.475251] <redpill/sata_port_shim.c:123> Registering for new devices notifications
[   38.483684] <redpill/scsi_notifier.c:149> 000000006e7fd983 (priority=-2147483648) subscribed to SCSI device events
[   38.494945] <redpill/sata_port_shim.c:130> Iterating over existing devices
[   38.502437] <redpill/sata_port_shim.c:137> Successfully registered SATA port emulator shim
[   38.511422] <redpill/boot_device_shim.c:48> Registering boot device router shim
[   38.519370] <redpill/usb_boot_shim.c:229> Registering USB boot device shim
[   38.526854] <redpill/usb_boot_shim.c:194> Registered usbcore module notifier
[   38.541400] <redpill/usb_boot_shim.c:247> Successfully registered USB boot device shim
[   38.550019] <redpill/boot_device_shim.c:76> Successfully registered boot device router shim
[   38.559108] <redpill/intercept_execve.c:118> Registering execve() interceptor
[   38.583182] <redpill/intercept_execve.c:125> execve() interceptor registered
[   38.590869] <redpill/bios_shim.c:247> Registering mfgBIOS shim
[   38.597223] <redpill/bios_shims_collection.c:237> Shimming disk led control API
[   38.612096] <redpill/override_symbol.c:256> Overriding syno_ahci_disk_led_enable_by_port() with (%pf?)()<00000000ee416859>
[   38.628939] <redpill/override_symbol.c:171> Saved syno_ahci_disk_led_enable_by_port() ptr <00000000cde020d9>
[   38.639640] <redpill/memory_helper.c:17> Disabling memory protection for page(s) at 00000000cde020d9+12/1 (<<00000000168ca6b2)
[   38.652421] <redpill/call_protected.c:84> Got addr ffffffff81053e70 for flush_tlb_all
[   38.661010] <redpill/override_symbol.c:220> Obtaining lock for <00000000cde020d9/00000000cde020d9>
[   38.670741] <redpill/override_symbol.c:181> Generating trampoline
[   38.677374] <redpill/override_symbol.c:186> Generated trampoline to 00000000ee416859<00000000ee416859> for syno_ahci_disk_led_enable_by_port<00000000cde020d9>: 
[   38.692974] <redpill/override_symbol.c:220> Writing trampoline code to <00000000cde020d9>
[   38.701869] <redpill/override_symbol.c:220> Released lock for <00000000cde020d9>
[   38.709925] <redpill/memory_helper.c:33> Enabling memory protection for page(s) at 00000000cde020d9+12/1 (<<00000000168ca6b2)
[   38.722277] <redpill/override_symbol.c:268> Successfully overrode syno_ahci_disk_led_enable_by_port() with trampoline to 00000000ee416859<00000000ee416859>
[   38.737408] <redpill/bios_shims_collection.c:273> Finished shim_disk_leds_ctrl
[   38.745267] <redpill/override_symbol.c:256> Overriding apply_relocate_add() with (%pf?)()<00000000039f394e>
[   38.756206] <redpill/override_symbol.c:171> Saved apply_relocate_add() ptr <000000005fd11e6b>
[   38.765490] <redpill/memory_helper.c:17> Disabling memory protection for page(s) at 000000005fd11e6b+12/1 (<<00000000ebf98114)
[   38.777930] <redpill/override_symbol.c:220> Obtaining lock for <000000005fd11e6b/000000005fd11e6b>
[   38.787692] <redpill/override_symbol.c:181> Generating trampoline
[   38.794326] <redpill/override_symbol.c:186> Generated trampoline to 00000000039f394e<00000000039f394e> for apply_relocate_add<000000005fd11e6b>: 
[   38.808511] <redpill/override_symbol.c:220> Writing trampoline code to <000000005fd11e6b>
[   38.817415] <redpill/override_symbol.c:220> Released lock for <000000005fd11e6b>
[   38.825467] <redpill/memory_helper.c:33> Enabling memory protection for page(s) at 000000005fd11e6b+12/1 (<<00000000ebf98114)
[   38.837811] <redpill/override_symbol.c:268> Successfully overrode apply_relocate_add() with trampoline to 00000000039f394e<00000000039f394e>
[   38.858431] <redpill/bios_shim.c:174> Registered bios module notifier
[   38.865451] <redpill/bios_shim.c:257> Successfully registered mfgBIOS shim
[   38.872922] <redpill/disable_exectutables.c:16> Registering common executables disabler shim
[   38.882094] <redpill/intercept_execve.c:58> Filename uboot_do_upd.sh will be blocked from execution
[   38.891940] <redpill/intercept_execve.c:58> Filename ./uboot_do_upd.sh will be blocked from execution
[   38.901968] <redpill/intercept_execve.c:58> Filename /usr/syno/bin/syno_pstore_collect will be blocked from execution
[   38.913516] <redpill/intercept_execve.c:58> Filename /tmpData/upd@te/sas_fw_upgrade_tool will be blocked from execution
[   38.925258] <redpill/intercept_execve.c:58> Filename /usr/syno/sbin/syno_oob_fw_upgrade will be blocked from execution
[   38.936902] <redpill/disable_exectutables.c:30> Successfully registered common executables disabler shim
[   38.947223] <redpill/block_fw_update_shim.c:71> Registering firmware update blocker shim
[   38.956027] <redpill/intercept_execve.c:58> Filename ./H2OFFT-Lx64 will be blocked from execution
[   38.965683] <redpill/block_fw_update_shim.c:49> Saved backup DMI: Super Server
[   38.973540] <redpill/block_fw_update_shim.c:79> Successfully registered firmware update blocker shim
[   38.983491] <redpill/pci_shim.c:203> Registering PCI devices shim
[   38.990115] <redpill/pci_shim.c:205> Creating vPCI devices for SA6400
[   38.997130] <redpill/pci_shim.c:227> Successfully registered PCI devices shim
[   39.004901] <redpill/smart_shim.c:1032> Registering SMART emulator shim
[   39.012101] <redpill/smart_shim.c:1042> SCSI driver exists - installing canary
[   39.019965] <redpill/override_symbol.c:256> Overriding sd_ioctl() with (%pf?)()<000000009384917b>
[   39.034273] <redpill/override_symbol.c:171> Saved sd_ioctl() ptr <000000006f55880c>
[   39.042612] <redpill/memory_helper.c:17> Disabling memory protection for page(s) at 000000006f55880c+12/1 (<<00000000628f6918)
[   39.055067] <redpill/override_symbol.c:220> Obtaining lock for <000000006f55880c/000000006f55880c>
[   39.064824] <redpill/override_symbol.c:181> Generating trampoline
[   39.071457] <redpill/override_symbol.c:186> Generated trampoline to 000000009384917b<000000009384917b> for sd_ioctl<000000006f55880c>: 
[   39.084683] <redpill/override_symbol.c:220> Writing trampoline code to <000000006f55880c>
[   39.093582] <redpill/override_symbol.c:220> Released lock for <000000006f55880c>
[   39.101630] <redpill/memory_helper.c:33> Enabling memory protection for page(s) at 000000006f55880c+12/1 (<<00000000628f6918)
[   39.113988] <redpill/override_symbol.c:268> Successfully overrode sd_ioctl() with trampoline to 000000009384917b<000000009384917b>
[   39.126753] <redpill/smart_shim.c:1054> Successfully registered SMART emulator shim
[   39.135085] <redpill/pmu_shim.c:344> Registering PMU emulator shim
[   39.141812] <redpill/virtual_uart.c:987> Adding vUART ttyS1
[   39.147873] <redpill/virtual_uart.c:645> Initializing ttyS1 vUART
[   39.154517] <redpill/virtual_uart.c:661> Initialized ttyS1 vUART
[   39.161063] <redpill/virtual_uart.c:799> Registering ttyS1 (io=0x2f8) in the driver
[   39.169578] serial8250: ttyS1 at I/O 0x2f8 (irq = 3, base_baud = 115200) is a 16550A
[   39.178126] <redpill/virtual_uart.c:852> ttyS1 registered with driver (line=1)
[   39.185999] <redpill/vuart_virtual_irq.c:66> Enabling vIRQ for ttyS1
[   39.193050] <redpill/vuart_virtual_irq.c:101> vIRQ fully enabled for for ttyS1
[   39.200923] <redpill/virtual_uart.c:1004> Added vUART at ttyS1
[   39.207285] <redpill/virtual_uart.c:931> Setting TX callback for for ttyS1 (line=1)
[   39.215608] <redpill/virtual_uart.c:945> Added TX callback for ttyS1 (line=1)
[   39.223378] <redpill/pmu_shim.c:361> Successfully registered PMU emulator shim
[   39.231249] <redpill/sanitize_cmdline.c:89> Cmdline param "earlyprintk" blacklisted - skipping
[   39.240636] <redpill/sanitize_cmdline.c:89> Cmdline param "log_buf_len=32M" blacklisted - skipping
[   39.250386] <redpill/sanitize_cmdline.c:89> Cmdline param "loglevel=15" blacklisted - skipping
[   39.259760] <redpill/sanitize_cmdline.c:89> Cmdline param "pid=0x5583" blacklisted - skipping
[   39.269053] <redpill/sanitize_cmdline.c:89> Cmdline param "vid=0x0781" blacklisted - skipping
[   39.278336] <redpill/sanitize_cmdline.c:102> Sanitized cmdline to: BOOT_IMAGE=/zImage-dsm console=ttyS0,115200n8 earlycon=uart8250,io,0x3f8,115200n8 root=/dev/md0 noefi syno_hw_version=SA6400 i915.enable_guc=2 netif_num=4 synoboot2 mac2=7e21363bcd3b mac3=7e21363bcd5b mac1=7e21363bcd1b mac4=7e21363bcd7b sn=0000XXXBN4YEE SMBusHddDynamicPower=1 vender_format_version=2 syno_ttyS1=serial,0x2f8 syno_ttyS0=serial,0x3f8
[   39.318032] <redpill/override_symbol.c:256> Overriding cmdline_proc_show() with (%pf?)()<00000000b016cdbc>
[   39.330962] <redpill/override_symbol.c:171> Saved cmdline_proc_show() ptr <00000000bdc3dabd>
[   39.340155] <redpill/memory_helper.c:17> Disabling memory protection for page(s) at 00000000bdc3dabd+12/1 (<<00000000584e676c)
[   39.352607] <redpill/override_symbol.c:220> Obtaining lock for <00000000bdc3dabd/00000000bdc3dabd>
[   39.362368] <redpill/override_symbol.c:181> Generating trampoline
[   39.369001] <redpill/override_symbol.c:186> Generated trampoline to 00000000b016cdbc<00000000b016cdbc> for cmdline_proc_show<00000000bdc3dabd>: 
[   39.383090] <redpill/override_symbol.c:220> Writing trampoline code to <00000000bdc3dabd>
[   39.391994] <redpill/override_symbol.c:220> Released lock for <00000000bdc3dabd>
[   39.400040] <redpill/memory_helper.c:33> Enabling memory protection for page(s) at 00000000bdc3dabd+12/1 (<<00000000584e676c)
[   39.412393] <redpill/override_symbol.c:268> Successfully overrode cmdline_proc_show() with trampoline to 00000000b016cdbc<00000000b016cdbc>
[   39.426011] <redpill/sanitize_cmdline.c:138> /proc/cmdline sanitized
[   39.432918] <redpill/redpill_main.c:69> RedPill v0.6-at-2023_03_12-19_43_26 loaded successfully (stealth=1)
[   39.482833] ACPI: bus type USB registered
[   39.487802] usbcore: registered new interface driver usbfs
[   39.493786] usbcore: registered new interface driver hub
[   39.499592] usbcore: registered new device driver usb
[   39.505103] <redpill/usb_boot_shim.c:166> usbcore registered, adding device watcher
[   39.513450] <redpill/call_protected.c:116> Got ptr 00000000fcfd05c2 for usb_register_notify
[   39.522556] <redpill/usb_boot_shim.c:127> Registered USB device notifier
[   39.552907] xhci_hcd 0000:00:14.0: xHCI Host Controller
[   39.558962] xhci_hcd 0000:00:14.0: new USB bus registered, assigned bus number 1
[   39.568154] xhci_hcd 0000:00:14.0: hcc params 0x200077c1 hci version 0x110 quirks 0x0000000000009010
[   39.578395] xhci_hcd 0000:00:14.0: cache line size of 64 is not supported
[   39.586198] hub 1-0:1.0: USB hub found
[   39.591327] hub 1-0:1.0: 16 ports detected
[   39.597109] <redpill/usb_boot_shim.c:72> Found new device <vid=1d6b, pid=0002> - didn't match expected <vid=0781, pid=5583> (prev_shimmed=0)
[   39.611104] xhci_hcd 0000:00:14.0: xHCI Host Controller
[   39.618064] xhci_hcd 0000:00:14.0: new USB bus registered, assigned bus number 2
[   39.626123] xhci_hcd 0000:00:14.0: Host supports USB 3.1 Enhanced SuperSpeed
[   39.633979] usb usb2: We don't know the algorithms for LPM for this host, disabling LPM.
[   39.644169] hub 2-0:1.0: USB hub found
[   39.649579] hub 2-0:1.0: 10 ports detected
[   39.654800] usb: port power management may be unreliable
[   39.661438] <redpill/usb_boot_shim.c:72> Found new device <vid=1d6b, pid=0003> - didn't match expected <vid=0781, pid=5583> (prev_shimmed=0)
[   39.685644] udevd[4497]: starting version 3.2.11
[   39.691511] udevd[4497]: specified group 'tty' unknown
[   39.698197] udevd[4497]: specified group 'dialout' unknown
[   39.705572] udevd[4497]: specified group 'kmem' unknown
[   39.711274] udevd[4497]: specified group 'input' unknown
[   39.717078] udevd[4497]: specified group 'video' unknown
[   39.722900] udevd[4497]: specified group 'audio' unknown
[   39.728757] udevd[4497]: specified group 'disk' unknown
[   39.734486] udevd[4497]: specified group 'cdrom' unknown
[   39.740304] udevd[4497]: specified group 'tape' unknown
[   39.747141] udevd[4498]: starting eudev-3.2.11
[   39.761524] input: Sleep Button as /devices/LNXSYSTM:00/LNXSYBUS:00/PNP0C0E:00/input/input0
[   39.771099] ACPI: Sleep Button [SLPB]
[   39.777033] input: Power Button as /devices/LNXSYSTM:00/LNXPWRBN:00/input/input1
[   39.787499] thermal LNXTHERM:00: registered as thermal_zone0
[   39.794826] ACPI: Thermal Zone [TZ00] (28 C)
[   39.794973] ACPI: Power Button [PWRF]
[   39.804886] kvm_intel: Unknown symbol __tracepoint_kvm_ple_window_update (err -2)
[   39.814633] Adaptec aacraid driver 1.2.1[50983]-custom
[   39.821441] aacraid 0000:01:00.0: can't disable ASPM; OS doesn't have ASPM control
[   39.821457] kvm_intel: Unknown symbol vcpu_put (err -2)
[   39.834184] aacraid: Comm Interface type3 enabled
[   39.842054] kvm_intel: Unknown symbol kvm_arch_has_assigned_device (err -2)
[   39.845849] AAC0: kernel 4.90-0[0] Jul 13 2020
[   39.855683] AAC0: monitor 0.0-0[0]
[   39.860761] AAC0: bios 0.13-209[32000]
[   39.864868] AAC0: serial 10F447
[   39.868302] AAC0: Non-DASD support enabled.
[   39.872878] AAC0: 64bit support enabled.
[   39.877172] aacraid 0000:01:00.0: 64 Bit DAC enabled
[   39.879732] usb 1-13: new high-speed USB device number 2 using xhci_hcd
[   39.891268] kvm_intel: Unknown symbol kvm_rdpmc (err -2)
[   39.891318] Intel(R) Gigabit Ethernet Linux Driver - version 5.13.7
[   39.891535] e1000e: Intel(R) PRO/1000 Network Driver
[   39.891536] e1000e: Copyright(c) 1999 - 2015 Intel Corporation.
[   39.891898] e1000e 0000:00:1f.6: Interrupt Throttling Rate (ints/sec) set to dynamic conservative mode
[   39.918476] kvm_intel: Unknown symbol kvm_vcpu_mark_page_dirty (err -2)
[   39.928556] Copyright(c) 2007 - 2022 Intel Corporation.
[   39.941497] kvm_intel: Unknown symbol kvm_vcpu_halt (err -2)
[   39.941727] scsi host0: aacraid
[   39.947668] kvm_intel: Unknown symbol kvm_clear_guest_page (err -2)
[   39.947670] kvm_intel: Unknown symbol kvm_requeue_exception (err -2)
[   39.947676] kvm_intel: Unknown symbol reprogram_counter (err -2)
[   39.947681] kvm_intel: Unknown symbol __SCK__tp_func_kvm_nested_vmenter_failed (err -2)
[   39.947683] kvm_intel: Unknown symbol kvm_exit (err -2)
[   39.947685] kvm_intel: Unknown symbol kvm_init (err -2)
[   39.947689] kvm_intel: Unknown symbol kvm_deliver_exception_payload (err -2)
[   39.947691] kvm_intel: Unknown symbol kvm_set_msr (err -2)
[   39.947694] kvm_intel: Unknown symbol kvm_default_tsc_scaling_ratio (err -2)
[   39.947697] kvm_intel: Unknown symbol __tracepoint_kvm_nested_vmexit (err -2)
[   39.947702] kvm_intel: Unknown symbol enable_vmware_backdoor (err -2)
[   39.978108] igb 0000:06:00.0: added PHC on eth0
[   39.980388] kvm_intel: Unknown symbol kvm_enable_efer_bits (err -2)
[   39.986102] igb 0000:06:00.0: Intel(R) Gigabit Ethernet Linux Driver
[   39.991794] kvm_intel: Unknown symbol __SCT__tp_func_kvm_nested_vmexit (err -2)
[   39.999483] igb 0000:06:00.0: eth0: (PCIe:2.5GT/s:Width x1) 
[   40.005459] kvm_intel: Unknown symbol __kvm_request_immediate_exit (err -2)
[   40.005528] i40e: Intel(R) 40-10 Gigabit Ethernet Connection Network Driver - version 2.20.12
[   40.005529] i40e: Copyright(c) 2013 - 2022 Intel Corporation.
[   40.013127] igb 0000:06:00.0 eth0: MAC: ac:1f:6b:f6:ed:71
[   40.013543] igb 0000:06:00.0: eth0: PBA No: 010B00-000
[   40.021019] kvm_intel: Unknown symbol kvm_lapic_expired_hv_timer (err -2)
[   40.027150] i40e 0000:02:00.0: fw 8.6.68629 api 1.15 nvm 8.60 0x8000bd5d 1.3122.0
[   40.035974] igb 0000:06:00.0: LRO is disabled
[   40.039972] kvm_intel: Unknown symbol kvm_fixup_and_inject_pf_error (err -2)
[   40.041087] Got empty serial number. Generate serial number from product.
[   40.041779] hub 1-13:1.0: USB hub found
[   40.041906] hub 1-13:1.0: 4 ports detected
[   40.042547] <redpill/usb_boot_shim.c:72> Found new device <vid=0557, pid=7000> - didn't match expected <vid=0781, pid=5583> (prev_shimmed=0)
[   40.046937] igb 0000:06:00.0: Using MSI-X interrupts. 1 rx queue(s), 1 tx queue(s)
[   40.055004] kvm_intel: Unknown symbol gfn_to_page (err -2)
[   40.056172] scsi 0:2:0:0: Direct-Access     HGST     HUH721008AL5200          A21D PQ: 0 ANSI: 6
[   40.057039] <redpill/scsi_notifier.c:65> Probing SCSI device using sd_probe_shim
[   40.057041] <redpill/scsi_notifier.c:77> Triggering SCSI_EVT_DEV_PROBING notifications
[   40.057043] <redpill/scsi_notifier.c:87> Calling original sd_probe()
[   40.057054] sd 0:2:0:0: sd_probe: unknown type 0.
[   40.057059] <redpill/scsi_notifier.c:91> Triggering SCSI_EVT_DEV_PROBED notifications - sd_probe() exit=-22
[   40.057062] sd: probe of 0:2:0:0 failed with error -22
[   40.062849] scsi 0:2:1:0: Direct-Access     HGST     HUH721008AL5200          A21D PQ: 0 ANSI: 6
[   40.068986] kvm_intel: Unknown symbol __SCK__tp_func_kvm_cr (err -2)
[   40.071641] get_vm_area_caller: ffffffff811fb1d0
[   40.073500] free_vm_area: ffffffff811fb6e0
[   40.075322] apply_to_page_range: ffffffff811e8450
[   40.075752] copy_init_mm: ffffffff810613a0
[   40.075972] native_write_cr4: ffffffff8102ea60
[   40.076355] flush_tlb_mm_range: ffffffff81053da0
[   40.078268] __mmu_notifier_invalidate_range_start: ffffffff81210860
[   40.079190] <redpill/scsi_notifier.c:65> Probing SCSI device using sd_probe_shim
[   40.080199] __mmu_notifier_invalidate_range_end: ffffffff812109f0
[   40.082049] walk_page_mapping: ffffffff811f4ef0
[   40.082049] init module
[   40.087736] scsi 0:2:2:0: Direct-Access     HGST     HUH721008AL5200          A21D PQ: 0 ANSI: 6
[   40.090580] <redpill/scsi_notifier.c:77> Triggering SCSI_EVT_DEV_PROBING notifications
[   40.090582] <redpill/scsi_notifier.c:87> Calling original sd_probe()
[   40.090588] kvm_intel: Unknown symbol kvm_probe_user_return_msr (err -2)
[   40.090592] kvm_intel: Unknown symbol kvm_vcpu_write_guest_page (err -2)
[   40.090598] kvm_intel: Unknown symbol kvm_no_apic_vcpu (err -2)
[   40.090602] kvm_intel: Unknown symbol handle_ud (err -2)
[   40.090604] kvm_intel: Unknown symbol kvm_mmu_new_pgd (err -2)
[   40.090608] kvm_intel: Unknown symbol reprogram_fixed_counter (err -2)
[   40.090613] kvm_intel: Unknown symbol __tracepoint_kvm_nested_vmenter_failed (err -2)
[   40.090619] kvm_intel: Unknown symbol kvm_get_msr_common (err -2)
[   40.090623] kvm_intel: Unknown symbol kvm_mmu_slot_largepage_remove_write_access (err -2)
[   40.090627] kvm_intel: Unknown symbol __tracepoint_kvm_fast_mmio (err -2)
[   40.090631] kvm_intel: Unknown symbol kvm_arch_has_noncoherent_dma (err -2)
[   40.090633] kvm_intel: Unknown symbol kvm_hv_get_assist_page (err -2)
[   40.090635] kvm_intel: Unknown symbol kvm_emulate_halt (err -2)
[   40.090638] kvm_intel: Unknown symbol kvm_set_apic_base (err -2)
[   40.090643] kvm_intel: Unknown symbol supported_xss (err -2)
[   40.090647] kvm_intel: Unknown symbol kvm_vcpu_map (err -2)
[   40.090649] kvm_intel: Unknown symbol kvm_msr_allowed (err -2)
[   40.090653] kvm_intel: Unknown symbol kvm_lapic_find_highest_irr (err -2)
[   40.090655] kvm_intel: Unknown symbol kvm_set_xcr (err -2)
[   40.090656] kvm_intel: Unknown symbol kvm_wait_lapic_expire (err -2)
[   40.090659] kvm_intel: Unknown symbol reprogram_gp_counter (err -2)
[   40.090664] kvm_intel: Unknown symbol kvm_write_guest_virt_system (err -2)
[   40.090666] kvm_intel: Unknown symbol kvm_find_cpuid_entry (err -2)
[   40.090668] kvm_intel: Unknown symbol kvm_task_switch (err -2)
[   40.090671] kvm_intel: Unknown symbol __SCT__tp_func_kvm_fast_mmio (err -2)
[   40.090673] kvm_intel: Unknown symbol kvm_read_guest_virt (err -2)
[   40.090675] kvm_intel: Unknown symbol kvm_vcpu_gfn_to_page (err -2)
[   40.090677] kvm_intel: Unknown symbol kvm_write_guest (err -2)
[   40.090679] kvm_intel: Unknown symbol __tracepoint_kvm_cr (err -2)
[   40.090681] kvm_intel: Unknown symbol kvm_io_bus_write (err -2)
[   40.090683] kvm_intel: Unknown symbol kvm_mmu_set_mmio_spte_mask (err -2)
[   40.090684] kvm_intel: Unknown symbol kvm_mmu_clear_dirty_pt_masked (err -2)
[   40.090686] kvm_intel: Unknown symbol kvm_set_user_return_msr (err -2)
[   40.090688] kvm_intel: Unknown symbol kvm_require_cpl (err -2)
[   40.090691] kvm_intel: Unknown symbol __SCT__tp_func_kvm_cr (err -2)
[   40.090693] kvm_intel: Unknown symbol kvm_init_shadow_ept_mmu (err -2)
[   40.090695] kvm_intel: Unknown symbol __tracepoint_kvm_pml_full (err -2)
[   40.090697] kvm_intel: Unknown symbol kvm_requeue_exception_e (err -2)
[   40.090698] kvm_intel: Unknown symbol kvm_lmsw (err -2)
[   40.090700] kvm_intel: Unknown symbol kvm_lapic_set_eoi (err -2)
[   40.090702] kvm_intel: Unknown symbol kvm_queue_exception (err -2)
[   40.090704] kvm_intel: Unknown symbol kvm_lapic_switch_to_hv_timer (err -2)
[   40.090706] kvm_intel: Unknown symbol kvm_emulate_rdmsr (err -2)
[   40.090708] kvm_intel: Unknown symbol __tracepoint_kvm_write_tsc_offset (err -2)
[   40.090710] kvm_intel: Unknown symbol kvm_vcpu_is_reset_bsp (err -2)
[   40.090712] kvm_intel: Unknown symbol __tracepoint_kvm_pi_irte_update (err -2)
[   40.090713] kvm_intel: Unknown symbol kvm_apicv_init (err -2)
[   40.090716] kvm_intel: Unknown symbol __SCT__tp_func_kvm_nested_vmexit_inject (err -2)
[   40.090718] kvm_intel: Unknown symbol kvm_vcpu_unmap (err -2)
[   40.090723] kvm_intel: Unknown symbol kvm_write_guest_page (err -2)
[   40.090729] kvm_intel: Unknown symbol kvm_valid_efer (err -2)
[   40.090732] kvm_intel: Unknown symbol supported_xcr0 (err -2)
[   40.090734] kvm_intel: Unknown symbol __SCK__tp_func_kvm_pi_irte_update (err -2)
[   40.090736] kvm_intel: Unknown symbol kvm_set_rflags (err -2)
[   40.090844] kvm_intel: Unknown symbol kvm_mmu_slot_leaf_clear_dirty (err -2)
[   40.090846] kvm_intel: Unknown symbol kvm_tsc_scaling_ratio_frac_bits (err -2)
[   40.090848] kvm_intel: Unknown symbol kvm_mce_cap_supported (err -2)
[   40.090849] kvm_intel: Unknown symbol kvm_handle_invpcid (err -2)
[   40.090852] kvm_intel: Unknown symbol kvm_load_host_xsave_state (err -2)
[   40.090854] kvm_intel: Unknown symbol __tracepoint_kvm_page_fault (err -2)
[   40.090856] kvm_intel: Unknown symbol kvm_mmu_free_roots (err -2)
[   40.090859] kvm_intel: Unknown symbol kvm_mmu_slot_set_dirty (err -2)
[   40.090860] kvm_intel: Unknown symbol kvm_queue_exception_p (err -2)
[   40.090862] kvm_intel: Unknown symbol kvm_read_l1_tsc (err -2)
[   40.090865] kvm_intel: Unknown symbol __tracepoint_kvm_inj_virq (err -2)
[   40.090867] kvm_intel: Unknown symbol kvm_cpu_has_interrupt (err -2)
[   40.090869] kvm_intel: Unknown symbol __kvm_apic_update_irr (err -2)
[   40.090872] kvm_intel: Unknown symbol handle_fastpath_set_msr_irqoff (err -2)
[   40.090874] kvm_intel: Unknown symbol kvm_apic_update_ppr (err -2)
[   40.090876] kvm_intel: Unknown symbol kvm_configure_mmu (err -2)
[   40.090882] kvm_intel: Unknown symbol kvm_apic_update_irr (err -2)
[   40.090884] kvm_intel: Unknown symbol kvm_init_mmu (err -2)
[   40.090886] kvm_intel: Unknown symbol kvm_emulate_wbinvd (err -2)
[   40.090887] kvm_intel: Unknown symbol kvm_set_cr3 (err -2)
[   40.090891] kvm_intel: Unknown symbol kvm_lapic_switch_to_sw_timer (err -2)
[   40.090895] kvm_intel: Unknown symbol __SCK__tp_func_kvm_page_fault (err -2)
[   40.090897] kvm_intel: Unknown symbol kvm_get_cr8 (err -2)
[   40.090898] kvm_intel: Unknown symbol kvm_x86_ops (err -2)
[   40.090902] kvm_intel: Unknown symbol __SCT__tp_func_kvm_pi_irte_update (err -2)
[   40.090904] kvm_intel: Unknown symbol vcpu_load (err -2)
[   40.090906] kvm_intel: Unknown symbol kvm_handle_memory_failure (err -2)
[   40.090907] kvm_intel: Unknown symbol kvm_set_dr (err -2)
[   40.090909] kvm_intel: Unknown symbol kvm_set_msi_irq (err -2)
[   40.090912] kvm_intel: Unknown symbol kvm_emulate_hypercall (err -2)
[   40.090917] kvm_intel: Unknown symbol kvm_spurious_fault (err -2)
[   40.090919] kvm_intel: Unknown symbol kvm_has_tsc_control (err -2)
[   40.090921] kvm_intel: Unknown symbol kvm_get_linear_rip (err -2)
[   40.090925] kvm_intel: Unknown symbol kvm_get_msr (err -2)
[   40.090927] kvm_intel: Unknown symbol load_pdptrs (err -2)
[   40.090930] kvm_intel: Unknown symbol kvm_get_running_vcpu (err -2)
[   40.090933] kvm_intel: Unknown symbol kvm_vcpu_read_guest_page (err -2)
[   40.090935] kvm_intel: Unknown symbol kvm_set_cpu_caps (err -2)
[   40.090936] kvm_intel: Unknown symbol kvm_vcpu_exit_request (err -2)
[   40.090940] kvm_intel: Unknown symbol host_efer (err -2)
[   40.090942] kvm_intel: Unknown symbol kvm_max_tsc_scaling_ratio (err -2)
[   40.090945] kvm_intel: Unknown symbol __SCT__tp_func_kvm_pml_full (err -2)
[   40.090947] kvm_intel: Unknown symbol pdptrs_changed (err -2)
[   40.090949] kvm_intel: Unknown symbol kvm_set_cr4 (err -2)
[   40.090951] kvm_intel: Unknown symbol __SCK__tp_func_kvm_exit (err -2)
[   40.090953] kvm_intel: Unknown symbol kvm_release_page_clean (err -2)
[   40.090955] kvm_intel: Unknown symbol kvm_handle_page_fault (err -2)
[   40.090956] kvm_intel: Unknown symbol kvm_cpu_caps (err -2)
[   40.090958] kvm_intel: Unknown symbol kvm_spec_ctrl_test_value (err -2)
[   40.090960] kvm_intel: Unknown symbol __SCT__tp_func_kvm_exit (err -2)
[   40.090962] kvm_intel: Unknown symbol kvm_apic_clear_irr (err -2)
[   40.090966] kvm_intel: Unknown symbol __x86_set_memory_region (err -2)
[   40.090967] kvm_intel: Unknown symbol kvm_load_guest_xsave_state (err -2)
[   40.090969] kvm_intel: Unknown symbol kvm_set_cr0 (err -2)
[   40.090971] kvm_intel: Unknown symbol kvm_set_cr8 (err -2)
[   40.090973] kvm_intel: Unknown symbol kvm_get_dr (err -2)
[   40.090977] kvm_intel: Unknown symbol kvm_mmu_page_fault (err -2)
[   40.090979] kvm_intel: Unknown symbol __SCK__tp_func_kvm_nested_vmexit (err -2)
[   40.090984] kvm_intel: Unknown symbol kvm_emulate_instruction (err -2)
[   40.090988] kvm_intel: Unknown symbol __SCK__tp_func_kvm_pml_full (err -2)
[   40.090990] kvm_intel: Unknown symbol kvm_mtrr_get_guest_memory_type (err -2)
[   40.090993] kvm_intel: Unknown symbol kvm_mmu_reset_context (err -2)
[   40.090995] kvm_intel: Unknown symbol kvm_get_apic_mode (err -2)
[   40.090999] kvm_intel: Unknown symbol kvm_vcpu_read_guest (err -2)
[   40.091001] kvm_intel: Unknown symbol kvm_vcpu_on_spin (err -2)
[   40.091004] kvm_intel: Unknown symbol __SCK__tp_func_kvm_fast_mmio (err -2)
[   40.091005] kvm_intel: Unknown symbol kvm_read_guest (err -2)
[   40.091008] kvm_intel: Unknown symbol kvm_define_user_return_msr (err -2)
[   40.091011] kvm_intel: Unknown symbol kvm_rebooting (err -2)
[   40.091012] kvm_intel: Unknown symbol kvm_get_rflags (err -2)
[   40.091015] kvm_intel: Unknown symbol kvm_queue_exception_e (err -2)
[   40.091017] kvm_intel: Unknown symbol __SCT__tp_func_kvm_inj_virq (err -2)
[   40.091020] kvm_intel: Unknown symbol current_vcpu (err -2)
[   40.091023] kvm_intel: Unknown symbol __SCT__tp_func_kvm_write_tsc_offset (err -2)
[   40.091026] kvm_intel: Unknown symbol __tracepoint_kvm_exit (err -2)
[   40.091027] kvm_intel: Unknown symbol kvm_emulate_cpuid (err -2)
[   40.091029] kvm_intel: Unknown symbol kvm_emulate_wrmsr (err -2)
[   40.091031] kvm_intel: Unknown symbol __SCK__tp_func_kvm_inj_virq (err -2)
[   40.091033] kvm_intel: Unknown symbol kvm_apic_set_eoi_accelerated (err -2)
[   40.091036] kvm_intel: Unknown symbol kvm_vcpu_kick (err -2)
[   40.091038] kvm_intel: Unknown symbol kvm_inject_realmode_interrupt (err -2)
[   40.091039] kvm_intel: Unknown symbol kvm_mmu_invlpg (err -2)
[   40.091041] kvm_intel: Unknown symbol kvm_fast_pio (err -2)
[   40.091043] kvm_intel: Unknown symbol __SCK__tp_func_kvm_ple_window_update (err -2)
[   40.091045] kvm_intel: Unknown symbol kvm_set_msr_common (err -2)
[   40.091047] kvm_intel: Unknown symbol __SCT__tp_func_kvm_nested_vmenter_failed (err -2)
[   40.091049] kvm_intel: Unknown symbol __SCK__tp_func_kvm_nested_vmexit_inject (err -2)
[   40.091050] kvm_intel: Unknown symbol kvm_intr_is_single_vcpu (err -2)
[   40.091053] kvm_intel: Unknown symbol kvm_apic_has_interrupt (err -2)
[   40.091056] kvm_intel: Unknown symbol __SCT__tp_func_kvm_ple_window_update (err -2)
[   40.091058] kvm_intel: Unknown symbol __SCK__tp_func_kvm_write_tsc_offset (err -2)
[   40.091061] kvm_intel: Unknown symbol __tracepoint_kvm_nested_vmexit_inject (err -2)
[   40.091063] kvm_intel: Unknown symbol __SCT__tp_func_kvm_page_fault (err -2)
[   40.091064] kvm_intel: Unknown symbol kvm_require_dr (err -2)
[   40.091066] kvm_intel: Unknown symbol kvm_skip_emulated_instruction (err -2)
[   40.091068] kvm_intel: Unknown symbol kvm_inject_page_fault (err -2)
[   40.091069] kvm_intel: Unknown symbol kvm_cpu_get_interrupt (err -2)
[   40.091073] kvm_intel: Unknown symbol kvm_vcpu_write_guest (err -2)
[   40.091074] kvm_intel: Unknown symbol kvm_complete_insn_gp (err -2)
[   40.091077] kvm_intel: Unknown symbol kvm_mmu_set_mask_ptes (err -2)
[   40.091078] kvm_intel: Unknown symbol kvm_apic_write_nodecode (err -2)
[   40.091080] kvm_intel: Unknown symbol kvm_lapic_hv_timer_in_use (err -2)
[   40.091084] kvm_intel: Unknown symbol allow_smaller_maxphyaddr (err -2)
[   40.105838] <redpill/scsi_notifier.c:65> Probing SCSI device using sd_probe_shim
[   40.106868] aac_srb_callback: srb failed, status = 5
[   40.113201] sd 0:2:1:0: sd_probe: unknown type 0.
[   40.118019] <redpill/scsi_notifier.c:77> Triggering SCSI_EVT_DEV_PROBING notifications
[   40.118769] aac_srb_callback: srb failed, status = 5
[   40.125752] <redpill/scsi_notifier.c:91> Triggering SCSI_EVT_DEV_PROBED notifications - sd_probe() exit=-22
[   40.126816] aac_srb_callback: srb failed, status = 5
[   40.133458] <redpill/scsi_notifier.c:87> Calling original sd_probe()
[   40.137950] sd: probe of 0:2:1:0 failed with error -22
[   40.138776] aac_srb_callback: srb failed, status = 5
[   40.141352] e1000e 0000:00:1f.6 0000:00:1f.6 (uninitialized): registered PHC clock
[   40.142710] sd 0:2:2:0: sd_probe: unknown type 0.
[   40.156838] aac_srb_callback: srb failed, status = 5
[   40.164920] <redpill/scsi_notifier.c:91> Triggering SCSI_EVT_DEV_PROBED notifications - sd_probe() exit=-22
[   40.177881] usb 2-5: new SuperSpeed Gen 1 USB device number 2 using xhci_hcd
[   40.178831] aac_srb_callback: srb failed, status = 5
[   40.178878] scsi 0:3:123:0: Enclosure         ADAPTEC  Smart Adapter            4.90 PQ: 0 ANSI: 5
[   40.180640] sd: probe of 0:2:2:0 failed with error -22
[   40.181068] <redpill/scsi_notifier.c:65> Probing SCSI device using sd_probe_shim
[   40.203988] e1000e 0000:00:1f.6 eth1: (PCI Express:2.5GT/s:Width x1) ac:1f:6b:f6:ed:70
[   40.204716] <redpill/usb_boot_shim.c:90> Device <vid=0781, pid=5583> shimmed to <vid=f400, pid=f400>
[   40.204901] <redpill/scsi_notifier.c:73> sd_probe_shim: new SCSI device connected - not a disk, ignoring
[   40.338199] i40e 0000:02:00.0: MAC address: 00:11:32:4f:72:1d
[   40.341701] e1000e 0000:00:1f.6 eth1: Intel(R) PRO/1000 Network Connection
[   40.348548] i40e 0000:02:00.0: FW LLDP is enabled
[   40.354079] e1000e 0000:00:1f.6 eth1: MAC: 13, PHY: 12, PBA No: 010BFF-0FF
[   40.360739] usb 1-13.1: new low-speed USB device number 3 using xhci_hcd
[   40.365381] i40e 0000:02:00.0 eth2: NIC Link is Up, 10 Gbps Full Duplex, Flow Control: None
[   40.365905] i40e 0000:02:00.0: PCI-Express: Speed 8.0GT/s Width x8
[   40.366403] i40e 0000:02:00.0: User requested queue count/HW max RSS count:  0/16
[   40.366405] i40e 0000:02:00.0: Features: PF-id[0] VFs: 64 VSIs: 66 QP: 16 RSS FD_ATR FD_SB NTUPLE CloudF DCB VxLAN NVGRE PTP VEPA
[   40.381147] i40e 0000:02:00.1: fw 8.6.68629 api 1.15 nvm 8.60 0x8000bd5d 1.3122.0
[   40.384843] kvm_intel: Unknown symbol __tracepoint_kvm_ple_window_update (err -2)
[   40.493793] Got empty serial number. Generate serial number from product.
[   40.501043] kvm_intel: Unknown symbol vcpu_put (err -2)
[   40.507811] drivers/usb/core/hub.c (2984) Same device found. Change serial to ffffffd1ffffffb2ffffffdbffffffa0 
[   40.507878] usb-storage 2-5:1.0: USB Mass Storage device detected
[   40.508207] scsi host1: usb-storage 2-5:1.0
[   40.508273] usbcore: registered new interface driver usb-storage
[   40.514688] kvm_intel: Unknown symbol kvm_arch_has_assigned_device (err -2)
[   40.526109] <redpill/usb_boot_shim.c:72> Found new device <vid=0557, pid=2419> - didn't match expected <vid=0781, pid=5583> (prev_shimmed=1)
[   40.534263] kvm_intel: Unknown symbol kvm_rdpmc (err -2)
[   40.634561] i40e 0000:02:00.1: MAC address: 00:11:32:4f:72:1e
[   40.641147] kvm_intel: Unknown symbol kvm_vcpu_mark_page_dirty (err -2)
[   40.641216] input: USBDevice as /devices/pci0000:00/0000:00:14.0/usb1/1-13/1-13.1/1-13.1:1.0/input/input2
[   40.641255] usbcore: registered new interface driver usbkbd
[   40.641292] input: USBDevice as /devices/pci0000:00/0000:00:14.0/usb1/1-13/1-13.1/1-13.1:1.1/input/input3
[   40.641314] usbcore: registered new interface driver usbmouse
[   40.649387] i40e 0000:02:00.1: FW LLDP is enabled
[   40.719359] kvm_intel: Unknown symbol kvm_vcpu_halt (err -2)
[   40.730834] i40e 0000:02:00.1: PCI-Express: Speed 8.0GT/s Width x8
[   40.732914] kvm_intel: Unknown symbol kvm_clear_guest_page (err -2)
[   40.740663] i40e 0000:02:00.1: User requested queue count/HW max RSS count:  0/16
[   40.747748] kvm_intel: Unknown symbol kvm_requeue_exception (err -2)
[   40.754352] i40e 0000:02:00.1: Features: PF-id[1] VFs: 64 VSIs: 66 QP: 16 RSS FD_ATR FD_SB NTUPLE CloudF DCB VxLAN NVGRE PTP VEPA
[   40.816833] kvm_intel: Unknown symbol reprogram_counter (err -2)
[   40.816880] usbcore: registered new interface driver usbhid
[   40.816881] usbhid: USB HID core driver
[   41.534632] scsi 1:0:0:0: Direct-Access      USB      SanDisk 3.2Gen1         1.00 PQ: 0 ANSI: 6
[   41.538468] kvm_intel: Unknown symbol __SCK__tp_func_kvm_nested_vmenter_failed (err -2)
[   41.544168] <redpill/scsi_notifier.c:65> Probing SCSI device using sd_probe_shim
[   41.552113] kvm_intel: Unknown symbol kvm_exit (err -2)
[   41.560742] <redpill/scsi_notifier.c:77> Triggering SCSI_EVT_DEV_PROBING notifications
[   41.570679] kvm_intel: Unknown symbol kvm_init (err -2)
[   41.580998] <redpill/scsi_notifier.c:87> Calling original sd_probe()
[   41.581334] sd 1:0:0:0: [synoboot] 120176640 512-byte logical blocks: (61.5 GB/57.3 GiB)
[   41.587265] kvm_intel: Unknown symbol kvm_deliver_exception_payload (err -2)
[   41.595113] sd 1:0:0:0: [synoboot] Write Protect is off
[   41.599872] kvm_intel: Unknown symbol kvm_set_msr (err -2)
[   41.607355] sd 1:0:0:0: [synoboot] Mode Sense: 43 00 00 00
[   41.614647] kvm_intel: Unknown symbol kvm_default_tsc_scaling_ratio (err -2)
[   41.624111] sd 1:0:0:0: [synoboot] Write cache: disabled, read cache: enabled, doesn't support DPO or FUA
[   41.630460] kvm_intel: Unknown symbol __tracepoint_kvm_nested_vmexit (err -2)
[   41.965517] kvm_intel: Unknown symbol enable_vmware_backdoor (err -2)
[   41.965521] kvm_intel: Unknown symbol kvm_enable_efer_bits (err -2)
[   41.965526] kvm_intel: Unknown symbol __SCT__tp_func_kvm_nested_vmexit (err -2)
[   41.965532] kvm_intel: Unknown symbol __kvm_request_immediate_exit (err -2)
[   41.965535] kvm_intel: Unknown symbol kvm_lapic_expired_hv_timer (err -2)
[   41.965537] kvm_intel: Unknown symbol kvm_fixup_and_inject_pf_error (err -2)
[   41.965540] kvm_intel: Unknown symbol gfn_to_page (err -2)
[   41.965545] kvm_intel: Unknown symbol __SCK__tp_func_kvm_cr (err -2)
[   41.965547] kvm_intel: Unknown symbol kvm_probe_user_return_msr (err -2)
[   41.965551] kvm_intel: Unknown symbol kvm_vcpu_write_guest_page (err -2)
[   41.965555] kvm_intel: Unknown symbol kvm_no_apic_vcpu (err -2)
[   41.965559] kvm_intel: Unknown symbol handle_ud (err -2)
[   41.965561] kvm_intel: Unknown symbol kvm_mmu_new_pgd (err -2)
[   41.965565] kvm_intel: Unknown symbol reprogram_fixed_counter (err -2)
[   41.965569] kvm_intel: Unknown symbol __tracepoint_kvm_nested_vmenter_failed (err -2)
[   41.965572] kvm_intel: Unknown symbol kvm_get_msr_common (err -2)
[   41.965574] kvm_intel: Unknown symbol kvm_mmu_slot_largepage_remove_write_access (err -2)
[   41.965578] kvm_intel: Unknown symbol __tracepoint_kvm_fast_mmio (err -2)
[   41.965583] kvm_intel: Unknown symbol kvm_arch_has_noncoherent_dma (err -2)
[   42.103806] kvm_intel: Unknown symbol kvm_hv_get_assist_page (err -2)
[   42.104034] ast 0000:08:00.0: [drm] P2A bridge disabled, using default configuration
[   42.112072] kvm_intel: Unknown symbol kvm_emulate_halt (err -2)
[   42.120504] ast 0000:08:00.0: [drm] AST 2500 detected
[   42.120526] ast 0000:08:00.0: [drm] Analog VGA only
[   42.126966] kvm_intel: Unknown symbol kvm_set_apic_base (err -2)
[   42.132470] ast 0000:08:00.0: [drm] dram MCLK=800 Mhz type=1 bus_width=16
[   42.137786] kvm_intel: Unknown symbol supported_xss (err -2)
[   42.144476] [TTM] Zone  kernel: Available graphics memory: 32775176 KiB
[   42.151727] kvm_intel: Unknown symbol kvm_vcpu_map (err -2)
[   42.157900] [TTM] Zone   dma32: Available graphics memory: 2097152 KiB
[   42.165105] kvm_intel: Unknown symbol kvm_msr_allowed (err -2)
[   42.171159] [TTM] Initializing pool allocator
[   42.171163] [TTM] Initializing DMA pool allocator
[   42.178274] kvm_intel: Unknown symbol kvm_lapic_find_highest_irr (err -2)
[   42.201892] kvm_intel: Unknown symbol kvm_set_xcr (err -2)
[   42.207872] kvm_intel: Unknown symbol kvm_wait_lapic_expire (err -2)
[   42.216154] kvm_intel: Unknown symbol reprogram_gp_counter (err -2)
[   42.222999] kvm_intel: Unknown symbol kvm_write_guest_virt_system (err -2)
[   42.231845] kvm_intel: Unknown symbol kvm_find_cpuid_entry (err -2)
[   42.238690] kvm_intel: Unknown symbol kvm_task_switch (err -2)
[   42.246410] kvm_intel: Unknown symbol __SCT__tp_func_kvm_fast_mmio (err -2)
[   42.254003] kvm_intel: Unknown symbol kvm_read_guest_virt (err -2)
[   42.262083] kvm_intel: Unknown symbol kvm_vcpu_gfn_to_page (err -2)
[   42.268923] kvm_intel: Unknown symbol kvm_write_guest (err -2)
[   42.276646] kvm_intel: Unknown symbol __tracepoint_kvm_cr (err -2)
[   42.283390] kvm_intel: Unknown symbol kvm_io_bus_write (err -2)
[   42.291200] kvm_intel: Unknown symbol kvm_mmu_set_mmio_spte_mask (err -2)
[   42.298600] kvm_intel: Unknown symbol kvm_mmu_clear_dirty_pt_masked (err -2)
[   42.306289] kvm_intel: Unknown symbol kvm_set_user_return_msr (err -2)
[   42.314751] kvm_intel: Unknown symbol kvm_require_cpl (err -2)
[   42.321115] kvm_intel: Unknown symbol __SCT__tp_func_kvm_cr (err -2)
[   42.328056] kvm_intel: Unknown symbol kvm_init_shadow_ept_mmu (err -2)
[   42.336536] kvm_intel: Unknown symbol __tracepoint_kvm_pml_full (err -2)
[   42.343846] kvm_intel: Unknown symbol kvm_requeue_exception_e (err -2)
[   42.352314] kvm_intel: Unknown symbol kvm_lmsw (err -2)
[   42.358017] kvm_intel: Unknown symbol kvm_lapic_set_eoi (err -2)
[   42.364582] kvm_intel: Unknown symbol kvm_queue_exception (err -2)
[   42.372681] kvm_intel: Unknown symbol kvm_lapic_switch_to_hv_timer (err -2)
[   42.380278] kvm_intel: Unknown symbol kvm_emulate_rdmsr (err -2)
[   42.388182] kvm_intel: Unknown symbol __tracepoint_kvm_write_tsc_offset (err -2)
[   42.396238] kvm_intel: Unknown symbol kvm_vcpu_is_reset_bsp (err -2)
[   42.404515] kvm_intel: Unknown symbol __tracepoint_kvm_pi_irte_update (err -2)
[   42.412390] kvm_intel: Unknown symbol kvm_apicv_init (err -2)
[   42.420013] kvm_intel: Unknown symbol __SCT__tp_func_kvm_nested_vmexit_inject (err -2)
[   42.428638] kvm_intel: Unknown symbol kvm_vcpu_unmap (err -2)
[   42.436268] kvm_intel: Unknown symbol kvm_write_guest_page (err -2)
[   42.443112] kvm_intel: Unknown symbol kvm_valid_efer (err -2)
[   42.450740] kvm_intel: Unknown symbol supported_xcr0 (err -2)
[   42.457020] kvm_intel: Unknown symbol __SCK__tp_func_kvm_pi_irte_update (err -2)
[   42.466431] kvm_intel: Unknown symbol kvm_set_rflags (err -2)
[   42.472707] kvm_intel: Unknown symbol kvm_mmu_slot_leaf_clear_dirty (err -2)
[   42.481737] kvm_intel: Unknown symbol kvm_tsc_scaling_ratio_frac_bits (err -2)
[   42.489622] kvm_intel: Unknown symbol kvm_mce_cap_supported (err -2)
[   42.497912] kvm_intel: Unknown symbol kvm_handle_invpcid (err -2)
[   42.504555] kvm_intel: Unknown symbol kvm_load_host_xsave_state (err -2)
[   42.513199] kvm_intel: Unknown symbol __tracepoint_kvm_page_fault (err -2)
[   42.520690] kvm_intel: Unknown symbol kvm_mmu_free_roots (err -2)
[   42.528689] kvm_intel: Unknown symbol kvm_mmu_slot_set_dirty (err -2)
[   42.535708] kvm_intel: Unknown symbol kvm_queue_exception_p (err -2)
[   42.543989] kvm_intel: Unknown symbol kvm_read_l1_tsc (err -2)
[   42.550363] kvm_intel: Unknown symbol __tracepoint_kvm_inj_virq (err -2)
[   42.559019] kvm_intel: Unknown symbol kvm_cpu_has_interrupt (err -2)
[   42.565964] kvm_intel: Unknown symbol __kvm_apic_update_irr (err -2)
[   42.574253] kvm_intel: Unknown symbol handle_fastpath_set_msr_irqoff (err -2)
[   42.582034] kvm_intel: Unknown symbol kvm_apic_update_ppr (err -2)
[   42.590131] kvm_intel: Unknown symbol kvm_configure_mmu (err -2)
[   42.596689] kvm_intel: Unknown symbol kvm_apic_update_irr (err -2)
[   42.604777] kvm_intel: Unknown symbol kvm_init_mmu (err -2)
[   42.610862] kvm_intel: Unknown symbol kvm_emulate_wbinvd (err -2)
[   42.618860] kvm_intel: Unknown symbol kvm_set_cr3 (err -2)
[   42.624845] kvm_intel: Unknown symbol kvm_lapic_switch_to_sw_timer (err -2)
[   42.632440] kvm_intel: Unknown symbol __SCK__tp_func_kvm_page_fault (err -2)
[   42.641478] kvm_intel: Unknown symbol kvm_get_cr8 (err -2)
[   42.647477] kvm_intel: Unknown symbol kvm_x86_ops (err -2)
[   42.654817] kvm_intel: Unknown symbol __SCT__tp_func_kvm_pi_irte_update (err -2)
[   42.662872] kvm_intel: Unknown symbol vcpu_load (err -2)
[   42.670021] kvm_intel: Unknown symbol kvm_handle_memory_failure (err -2)
[   42.677337] kvm_intel: Unknown symbol kvm_set_dr (err -2)
[   42.684589] kvm_intel: Unknown symbol kvm_set_msi_irq (err -2)
[   42.690966] kvm_intel: Unknown symbol kvm_emulate_hypercall (err -2)
[   42.699240] kvm_intel: Unknown symbol kvm_spurious_fault (err -2)
[   42.705891] kvm_intel: Unknown symbol kvm_has_tsc_control (err -2)
[   42.713986] kvm_intel: Unknown symbol kvm_get_linear_rip (err -2)
[   42.720639] kvm_intel: Unknown symbol kvm_get_msr (err -2)
[   42.727983] kvm_intel: Unknown symbol load_pdptrs (err -2)
[   42.733985] kvm_intel: Unknown symbol kvm_get_running_vcpu (err -2)
[   42.742180] kvm_intel: Unknown symbol kvm_vcpu_read_guest_page (err -2)
[   42.749397] kvm_intel: Unknown symbol kvm_set_cpu_caps (err -2)
[   42.757194] kvm_intel: Unknown symbol kvm_vcpu_exit_request (err -2)
[   42.764136] kvm_intel: Unknown symbol host_efer (err -2)
[   42.771289] kvm_intel: Unknown symbol kvm_max_tsc_scaling_ratio (err -2)
[   42.778603] kvm_intel: Unknown symbol __SCT__tp_func_kvm_pml_full (err -2)
[   42.787473] kvm_intel: Unknown symbol pdptrs_changed (err -2)
[   42.795108] kvm_intel: Unknown symbol kvm_set_cr4 (err -2)
[   42.801104] kvm_intel: Unknown symbol __SCK__tp_func_kvm_exit (err -2)
[   42.809566] kvm_intel: Unknown symbol kvm_release_page_clean (err -2)
[   42.816602] kvm_intel: Unknown symbol kvm_handle_page_fault (err -2)
[   42.824875] kvm_intel: Unknown symbol kvm_cpu_caps (err -2)
[   42.830951] kvm_intel: Unknown symbol kvm_spec_ctrl_test_value (err -2)
[   42.838152] kvm_intel: Unknown symbol __SCT__tp_func_kvm_exit (err -2)
[   42.846622] kvm_intel: Unknown symbol kvm_apic_clear_irr (err -2)
[   42.853278] kvm_intel: Unknown symbol __x86_set_memory_region (err -2)
[   42.861755] kvm_intel: Unknown symbol kvm_load_guest_xsave_state (err -2)
[   42.869150] kvm_intel: Unknown symbol kvm_set_cr0 (err -2)
[   42.876491] kvm_intel: Unknown symbol kvm_set_cr8 (err -2)
[   42.882480] kvm_intel: Unknown symbol kvm_get_dr (err -2)
[   42.889727] kvm_intel: Unknown symbol kvm_mmu_page_fault (err -2)
[   42.896377] kvm_intel: Unknown symbol __SCK__tp_func_kvm_nested_vmexit (err -2)
[   42.905702] kvm_intel: Unknown symbol kvm_emulate_instruction (err -2)
[   42.912825] kvm_intel: Unknown symbol __SCK__tp_func_kvm_pml_full (err -2)
[   42.921678] kvm_intel: Unknown symbol kvm_mtrr_get_guest_memory_type (err -2)
[   42.929472] kvm_intel: Unknown symbol kvm_mmu_reset_context (err -2)
[   42.937754] kvm_intel: Unknown symbol kvm_get_apic_mode (err -2)
[   42.944310] kvm_intel: Unknown symbol kvm_vcpu_read_guest (err -2)
[   42.952395] kvm_intel: Unknown symbol kvm_vcpu_on_spin (err -2)
[   42.958865] kvm_intel: Unknown symbol __SCK__tp_func_kvm_fast_mmio (err -2)
[   42.967797] kvm_intel: Unknown symbol kvm_read_guest (err -2)
[   42.974071] kvm_intel: Unknown symbol kvm_define_user_return_msr (err -2)
[   42.982823] kvm_intel: Unknown symbol kvm_rebooting (err -2)
[   42.989002] kvm_intel: Unknown symbol kvm_get_rflags (err -2)
[   42.996624] kvm_intel: Unknown symbol kvm_queue_exception_e (err -2)
[   43.003561] kvm_intel: Unknown symbol __SCT__tp_func_kvm_inj_virq (err -2)
[   43.012391] kvm_intel: Unknown symbol current_vcpu (err -2)
[   43.018481] kvm_intel: Unknown symbol __SCT__tp_func_kvm_write_tsc_offset (err -2)
[   43.028090] kvm_intel: Unknown symbol __tracepoint_kvm_exit (err -2)
[   43.035022] kvm_intel: Unknown symbol kvm_emulate_cpuid (err -2)
[   43.042927] kvm_intel: Unknown symbol kvm_emulate_wrmsr (err -2)
[   43.049485] kvm_intel: Unknown symbol __SCK__tp_func_kvm_inj_virq (err -2)
[   43.058335] kvm_intel: Unknown symbol kvm_apic_set_eoi_accelerated (err -2)
[   43.065932] kvm_intel: Unknown symbol kvm_vcpu_kick (err -2)
[   43.073463] kvm_intel: Unknown symbol kvm_inject_realmode_interrupt (err -2)
[   43.081161] kvm_intel: Unknown symbol kvm_mmu_invlpg (err -2)
[   43.088792] kvm_intel: Unknown symbol kvm_fast_pio (err -2)
[   43.094875] kvm_intel: Unknown symbol __SCK__tp_func_kvm_ple_window_update (err -2)
[   43.104572] kvm_intel: Unknown symbol kvm_set_msr_common (err -2)
[   43.111224] kvm_intel: Unknown symbol __SCT__tp_func_kvm_nested_vmenter_failed (err -2)
[   43.121299] kvm_intel: Unknown symbol __SCK__tp_func_kvm_nested_vmexit_inject (err -2)
[   43.129938] kvm_intel: Unknown symbol kvm_intr_is_single_vcpu (err -2)
[   43.138412] kvm_intel: Unknown symbol kvm_apic_has_interrupt (err -2)
[   43.145436] kvm_intel: Unknown symbol __SCT__tp_func_kvm_ple_window_update (err -2)
[   43.155143] kvm_intel: Unknown symbol __SCK__tp_func_kvm_write_tsc_offset (err -2)
[   43.163405] kvm_intel: Unknown symbol __tracepoint_kvm_nested_vmexit_inject (err -2)
[   43.173197] kvm_intel: Unknown symbol __SCT__tp_func_kvm_page_fault (err -2)
[   43.180896] kvm_intel: Unknown symbol kvm_require_dr (err -2)
[   43.188522] kvm_intel: Unknown symbol kvm_skip_emulated_instruction (err -2)
[   43.196207] kvm_intel: Unknown symbol kvm_inject_page_fault (err -2)
[   43.204486] kvm_intel: Unknown symbol kvm_cpu_get_interrupt (err -2)
[   43.211417] kvm_intel: Unknown symbol kvm_vcpu_write_guest (err -2)
[   43.219611] kvm_intel: Unknown symbol kvm_complete_insn_gp (err -2)
[   43.226442] kvm_intel: Unknown symbol kvm_mmu_set_mask_ptes (err -2)
[   43.233366] kvm_intel: Unknown symbol kvm_apic_write_nodecode (err -2)
[   43.241839] kvm_intel: Unknown symbol kvm_lapic_hv_timer_in_use (err -2)
[   43.249164] kvm_intel: Unknown symbol allow_smaller_maxphyaddr (err -2)
[   43.262431] [drm] Initialized ast 0.1.0 20120228 for 0000:08:00.0 on minor 0
[   43.272780] kvm_intel: Unknown symbol __tracepoint_kvm_ple_window_update (err -2)
[   43.277219]  synoboot: synoboot1 synoboot2 synoboot3
[   43.282010] kvm_intel: Unknown symbol vcpu_put (err -2)
[   43.288727] sd 1:0:0:0: [synoboot] Attached SCSI removable disk
[   43.293137] kvm_intel: Unknown symbol kvm_arch_has_assigned_device (err -2)
[   43.299595] <redpill/scsi_notifier.c:91> Triggering SCSI_EVT_DEV_PROBED notifications - sd_probe() exit=0
[   43.307169] kvm_intel: Unknown symbol kvm_rdpmc (err -2)
[   43.323374] kvm_intel: Unknown symbol kvm_vcpu_mark_page_dirty (err -2)
[   43.323384] kvm_intel: Unknown symbol kvm_vcpu_halt (err -2)
[   43.323389] kvm_intel: Unknown symbol kvm_clear_guest_page (err -2)
[   43.323394] kvm_intel: Unknown symbol kvm_requeue_exception (err -2)
[   43.323402] kvm_intel: Unknown symbol reprogram_counter (err -2)
[   43.323411] kvm_intel: Unknown symbol __SCK__tp_func_kvm_nested_vmenter_failed (err -2)
[   43.323416] kvm_intel: Unknown symbol kvm_exit (err -2)
[   43.323420] kvm_intel: Unknown symbol kvm_init (err -2)
[   43.323427] kvm_intel: Unknown symbol kvm_deliver_exception_payload (err -2)
[   43.323434] kvm_intel: Unknown symbol kvm_set_msr (err -2)
[   43.323439] kvm_intel: Unknown symbol kvm_default_tsc_scaling_ratio (err -2)
[   43.323446] kvm_intel: Unknown symbol __tracepoint_kvm_nested_vmexit (err -2)
[   43.323454] kvm_intel: Unknown symbol enable_vmware_backdoor (err -2)
[   43.323458] kvm_intel: Unknown symbol kvm_enable_efer_bits (err -2)
[   43.323466] kvm_intel: Unknown symbol __SCT__tp_func_kvm_nested_vmexit (err -2)
[   43.323472] kvm_intel: Unknown symbol __kvm_request_immediate_exit (err -2)
[   43.323476] kvm_intel: Unknown symbol kvm_lapic_expired_hv_timer (err -2)
[   43.323480] kvm_intel: Unknown symbol kvm_fixup_and_inject_pf_error (err -2)
[   43.323486] kvm_intel: Unknown symbol gfn_to_page (err -2)
[   43.323493] pmd_set_huge: Cannot satisfy [mem 0xa1000000-0xa1200000] with a huge-page mapping due to MTRR override.
[   43.323494] kvm_intel: Unknown symbol __SCK__tp_func_kvm_cr (err -2)
[   43.323499] kvm_intel: Unknown symbol kvm_probe_user_return_msr (err -2)
[   43.323504] kvm_intel: Unknown symbol kvm_vcpu_write_guest_page (err -2)
[   43.323510] kvm_intel: Unknown symbol kvm_no_apic_vcpu (err -2)
[   43.323515] kvm_intel: Unknown symbol handle_ud (err -2)
[   43.323519] kvm_intel: Unknown symbol kvm_mmu_new_pgd (err -2)
[   43.323526] kvm_intel: Unknown symbol reprogram_fixed_counter (err -2)
[   43.323532] kvm_intel: Unknown symbol __tracepoint_kvm_nested_vmenter_failed (err -2)
[   43.323535] kvm_intel: Unknown symbol kvm_get_msr_common (err -2)
[   43.323539] kvm_intel: Unknown symbol kvm_mmu_slot_largepage_remove_write_access (err -2)
[   43.323544] kvm_intel: Unknown symbol __tracepoint_kvm_fast_mmio (err -2)
[   43.323549] kvm_intel: Unknown symbol kvm_arch_has_noncoherent_dma (err -2)
[   43.323553] kvm_intel: Unknown symbol kvm_hv_get_assist_page (err -2)
[   43.323556] kvm_intel: Unknown symbol kvm_emulate_halt (err -2)
[   43.323562] kvm_intel: Unknown symbol kvm_set_apic_base (err -2)
[   43.323567] kvm_intel: Unknown symbol supported_xss (err -2)
[   43.323572] kvm_intel: Unknown symbol kvm_vcpu_map (err -2)
[   43.323575] kvm_intel: Unknown symbol kvm_msr_allowed (err -2)
[   43.323580] kvm_intel: Unknown symbol kvm_lapic_find_highest_irr (err -2)
[   43.323583] kvm_intel: Unknown symbol kvm_set_xcr (err -2)
[   43.323587] kvm_intel: Unknown symbol kvm_wait_lapic_expire (err -2)
[   43.323591] kvm_intel: Unknown symbol reprogram_gp_counter (err -2)
[   43.323599] kvm_intel: Unknown symbol kvm_write_guest_virt_system (err -2)
[   43.323602] kvm_intel: Unknown symbol kvm_find_cpuid_entry (err -2)
[   43.323606] kvm_intel: Unknown symbol kvm_task_switch (err -2)
[   43.323611] kvm_intel: Unknown symbol __SCT__tp_func_kvm_fast_mmio (err -2)
[   43.323615] kvm_intel: Unknown symbol kvm_read_guest_virt (err -2)
[   43.323620] kvm_intel: Unknown symbol kvm_vcpu_gfn_to_page (err -2)
[   43.323623] kvm_intel: Unknown symbol kvm_write_guest (err -2)
[   43.323628] kvm_intel: Unknown symbol __tracepoint_kvm_cr (err -2)
[   43.323631] kvm_intel: Unknown symbol kvm_io_bus_write (err -2)
[   43.323635] kvm_intel: Unknown symbol kvm_mmu_set_mmio_spte_mask (err -2)
[   43.323639] kvm_intel: Unknown symbol kvm_mmu_clear_dirty_pt_masked (err -2)
[   43.323642] kvm_intel: Unknown symbol kvm_set_user_return_msr (err -2)
[   43.323646] kvm_intel: Unknown symbol kvm_require_cpl (err -2)
[   43.323652] kvm_intel: Unknown symbol __SCT__tp_func_kvm_cr (err -2)
[   43.323656] kvm_intel: Unknown symbol kvm_init_shadow_ept_mmu (err -2)
[   43.323660] kvm_intel: Unknown symbol __tracepoint_kvm_pml_full (err -2)
[   43.323664] kvm_intel: Unknown symbol kvm_requeue_exception_e (err -2)
[   43.323667] kvm_intel: Unknown symbol kvm_lmsw (err -2)
[   43.323671] kvm_intel: Unknown symbol kvm_lapic_set_eoi (err -2)
[   43.323675] kvm_intel: Unknown symbol kvm_queue_exception (err -2)
[   43.323679] kvm_intel: Unknown symbol kvm_lapic_switch_to_hv_timer (err -2)
[   43.323683] kvm_intel: Unknown symbol kvm_emulate_rdmsr (err -2)
[   43.323687] kvm_intel: Unknown symbol __tracepoint_kvm_write_tsc_offset (err -2)
[   43.323691] kvm_intel: Unknown symbol kvm_vcpu_is_reset_bsp (err -2)
[   43.323695] kvm_intel: Unknown symbol __tracepoint_kvm_pi_irte_update (err -2)
[   43.323698] kvm_intel: Unknown symbol kvm_apicv_init (err -2)
[   43.323703] kvm_intel: Unknown symbol __SCT__tp_func_kvm_nested_vmexit_inject (err -2)
[   43.323707] kvm_intel: Unknown symbol kvm_vcpu_unmap (err -2)
[   43.323710] kvm_intel: Unknown symbol kvm_write_guest_page (err -2)
[   43.323717] kvm_intel: Unknown symbol kvm_valid_efer (err -2)
[   43.323728] kvm_intel: Unknown symbol supported_xcr0 (err -2)
[   43.323733] kvm_intel: Unknown symbol __SCK__tp_func_kvm_pi_irte_update (err -2)
[   43.323736] kvm_intel: Unknown symbol kvm_set_rflags (err -2)
[   43.323740] kvm_intel: Unknown symbol kvm_mmu_slot_leaf_clear_dirty (err -2)
[   43.323744] kvm_intel: Unknown symbol kvm_tsc_scaling_ratio_frac_bits (err -2)
[   43.323748] kvm_intel: Unknown symbol kvm_mce_cap_supported (err -2)
[   43.323751] kvm_intel: Unknown symbol kvm_handle_invpcid (err -2)
[   43.323756] kvm_intel: Unknown symbol kvm_load_host_xsave_state (err -2)
[   43.323760] kvm_intel: Unknown symbol __tracepoint_kvm_page_fault (err -2)
[   43.323763] kvm_intel: Unknown symbol kvm_mmu_free_roots (err -2)
[   43.323768] kvm_intel: Unknown symbol kvm_mmu_slot_set_dirty (err -2)
[   43.323772] kvm_intel: Unknown symbol kvm_queue_exception_p (err -2)
[   43.323775] kvm_intel: Unknown symbol kvm_read_l1_tsc (err -2)
[   43.323781] kvm_intel: Unknown symbol __tracepoint_kvm_inj_virq (err -2)
[   43.323784] kvm_intel: Unknown symbol kvm_cpu_has_interrupt (err -2)
[   43.323789] kvm_intel: Unknown symbol __kvm_apic_update_irr (err -2)
[   43.323794] kvm_intel: Unknown symbol handle_fastpath_set_msr_irqoff (err -2)
[   43.323797] kvm_intel: Unknown symbol kvm_apic_update_ppr (err -2)
[   43.323802] kvm_intel: Unknown symbol kvm_configure_mmu (err -2)
[   43.323810] kvm_intel: Unknown symbol kvm_apic_update_irr (err -2)
[   43.323814] kvm_intel: Unknown symbol kvm_init_mmu (err -2)
[   43.323817] kvm_intel: Unknown symbol kvm_emulate_wbinvd (err -2)
[   43.323821] kvm_intel: Unknown symbol kvm_set_cr3 (err -2)
[   43.323827] kvm_intel: Unknown symbol kvm_lapic_switch_to_sw_timer (err -2)
[   43.323833] kvm_intel: Unknown symbol __SCK__tp_func_kvm_page_fault (err -2)
[   43.323836] kvm_intel: Unknown symbol kvm_get_cr8 (err -2)
[   43.323840] kvm_intel: Unknown symbol kvm_x86_ops (err -2)
[   43.323846] kvm_intel: Unknown symbol __SCT__tp_func_kvm_pi_irte_update (err -2)
[   43.323851] kvm_intel: Unknown symbol vcpu_load (err -2)
[   43.323855] kvm_intel: Unknown symbol kvm_handle_memory_failure (err -2)
[   43.323858] kvm_intel: Unknown symbol kvm_set_dr (err -2)
[   43.323862] kvm_intel: Unknown symbol kvm_set_msi_irq (err -2)
[   43.323867] kvm_intel: Unknown symbol kvm_emulate_hypercall (err -2)
[   43.323874] kvm_intel: Unknown symbol kvm_spurious_fault (err -2)
[   43.323878] kvm_intel: Unknown symbol kvm_has_tsc_control (err -2)
[   43.323882] kvm_intel: Unknown symbol kvm_get_linear_rip (err -2)
[   43.323888] kvm_intel: Unknown symbol kvm_get_msr (err -2)
[   43.323892] kvm_intel: Unknown symbol load_pdptrs (err -2)
[   43.323897] kvm_intel: Unknown symbol kvm_get_running_vcpu (err -2)
[   43.323902] kvm_intel: Unknown symbol kvm_vcpu_read_guest_page (err -2)
[   43.323906] kvm_intel: Unknown symbol kvm_set_cpu_caps (err -2)
[   43.323910] kvm_intel: Unknown symbol kvm_vcpu_exit_request (err -2)
[   43.323916] kvm_intel: Unknown symbol host_efer (err -2)
[   43.323919] kvm_intel: Unknown symbol kvm_max_tsc_scaling_ratio (err -2)
[   43.323924] kvm_intel: Unknown symbol __SCT__tp_func_kvm_pml_full (err -2)
[   43.323929] kvm_intel: Unknown symbol pdptrs_changed (err -2)
[   43.323933] kvm_intel: Unknown symbol kvm_set_cr4 (err -2)
[   43.323938] kvm_intel: Unknown symbol __SCK__tp_func_kvm_exit (err -2)
[   43.323941] kvm_intel: Unknown symbol kvm_release_page_clean (err -2)
[   43.323945] kvm_intel: Unknown symbol kvm_handle_page_fault (err -2)
[   43.323948] kvm_intel: Unknown symbol kvm_cpu_caps (err -2)
[   43.323952] kvm_intel: Unknown symbol kvm_spec_ctrl_test_value (err -2)
[   43.323956] kvm_intel: Unknown symbol __SCT__tp_func_kvm_exit (err -2)
[   43.323961] kvm_intel: Unknown symbol kvm_apic_clear_irr (err -2)
[   43.323966] kvm_intel: Unknown symbol __x86_set_memory_region (err -2)
[   43.323970] kvm_intel: Unknown symbol kvm_load_guest_xsave_state (err -2)
[   43.323973] kvm_intel: Unknown symbol kvm_set_cr0 (err -2)
[   43.323978] kvm_intel: Unknown symbol kvm_set_cr8 (err -2)
[   43.323981] kvm_intel: Unknown symbol kvm_get_dr (err -2)
[   43.323987] kvm_intel: Unknown symbol kvm_mmu_page_fault (err -2)
[   43.323992] kvm_intel: Unknown symbol __SCK__tp_func_kvm_nested_vmexit (err -2)
[   43.323999] kvm_intel: Unknown symbol kvm_emulate_instruction (err -2)
[   43.324006] kvm_intel: Unknown symbol __SCK__tp_func_kvm_pml_full (err -2)
[   43.324010] kvm_intel: Unknown symbol kvm_mtrr_get_guest_memory_type (err -2)
[   43.324015] kvm_intel: Unknown symbol kvm_mmu_reset_context (err -2)
[   43.324018] kvm_intel: Unknown symbol kvm_get_apic_mode (err -2)
[   43.324025] kvm_intel: Unknown symbol kvm_vcpu_read_guest (err -2)
[   43.324029] kvm_intel: Unknown symbol kvm_vcpu_on_spin (err -2)
[   43.324034] kvm_intel: Unknown symbol __SCK__tp_func_kvm_fast_mmio (err -2)
[   43.324037] kvm_intel: Unknown symbol kvm_read_guest (err -2)
[   43.324042] kvm_intel: Unknown symbol kvm_define_user_return_msr (err -2)
[   43.324046] kvm_intel: Unknown symbol kvm_rebooting (err -2)
[   43.324050] kvm_intel: Unknown symbol kvm_get_rflags (err -2)
[   43.324055] kvm_intel: Unknown symbol kvm_queue_exception_e (err -2)
[   43.324059] kvm_intel: Unknown symbol __SCT__tp_func_kvm_inj_virq (err -2)
[   43.324064] kvm_intel: Unknown symbol current_vcpu (err -2)
[   43.324070] kvm_intel: Unknown symbol __SCT__tp_func_kvm_write_tsc_offset (err -2)
[   43.324075] kvm_intel: Unknown symbol __tracepoint_kvm_exit (err -2)
[   43.324078] kvm_intel: Unknown symbol kvm_emulate_cpuid (err -2)
[   43.324083] kvm_intel: Unknown symbol kvm_emulate_wrmsr (err -2)
[   43.324087] kvm_intel: Unknown symbol __SCK__tp_func_kvm_inj_virq (err -2)
[   43.324090] kvm_intel: Unknown symbol kvm_apic_set_eoi_accelerated (err -2)
[   43.324095] kvm_intel: Unknown symbol kvm_vcpu_kick (err -2)
[   43.324099] kvm_intel: Unknown symbol kvm_inject_realmode_interrupt (err -2)
[   43.324103] kvm_intel: Unknown symbol kvm_mmu_invlpg (err -2)
[   43.324106] kvm_intel: Unknown symbol kvm_fast_pio (err -2)
[   43.324110] kvm_intel: Unknown symbol __SCK__tp_func_kvm_ple_window_update (err -2)
[   43.324114] kvm_intel: Unknown symbol kvm_set_msr_common (err -2)
[   43.324118] kvm_intel: Unknown symbol __SCT__tp_func_kvm_nested_vmenter_failed (err -2)
[   43.324122] kvm_intel: Unknown symbol __SCK__tp_func_kvm_nested_vmexit_inject (err -2)
[   43.324126] kvm_intel: Unknown symbol kvm_intr_is_single_vcpu (err -2)
[   43.324130] kvm_intel: Unknown symbol kvm_apic_has_interrupt (err -2)
[   43.324136] kvm_intel: Unknown symbol __SCT__tp_func_kvm_ple_window_update (err -2)
[   43.324141] kvm_intel: Unknown symbol __SCK__tp_func_kvm_write_tsc_offset (err -2)
[   43.324145] kvm_intel: Unknown symbol __tracepoint_kvm_nested_vmexit_inject (err -2)
[   43.324149] kvm_intel: Unknown symbol __SCT__tp_func_kvm_page_fault (err -2)
[   43.324153] kvm_intel: Unknown symbol kvm_require_dr (err -2)
[   43.324157] kvm_intel: Unknown symbol kvm_skip_emulated_instruction (err -2)
[   43.324160] kvm_intel: Unknown symbol kvm_inject_page_fault (err -2)
[   43.324164] kvm_intel: Unknown symbol kvm_cpu_get_interrupt (err -2)
[   43.324169] kvm_intel: Unknown symbol kvm_vcpu_write_guest (err -2)
[   43.324173] kvm_intel: Unknown symbol kvm_complete_insn_gp (err -2)
[   43.324177] kvm_intel: Unknown symbol kvm_mmu_set_mask_ptes (err -2)
[   43.324181] kvm_intel: Unknown symbol kvm_apic_write_nodecode (err -2)
[   43.324185] kvm_intel: Unknown symbol kvm_lapic_hv_timer_in_use (err -2)
[   43.324191] kvm_intel: Unknown symbol allow_smaller_maxphyaddr (err -2)
[   43.693815] kvm_intel: Unknown symbol __tracepoint_kvm_ple_window_update (err -2)
[   43.693820] kvm_intel: Unknown symbol vcpu_put (err -2)
[   43.693826] kvm_intel: Unknown symbol kvm_arch_has_assigned_device (err -2)
[   43.693830] kvm_intel: Unknown symbol kvm_rdpmc (err -2)
[   43.693833] kvm_intel: Unknown symbol kvm_vcpu_mark_page_dirty (err -2)
[   43.693842] kvm_intel: Unknown symbol kvm_vcpu_halt (err -2)
[   43.693846] kvm_intel: Unknown symbol kvm_clear_guest_page (err -2)
[   43.693848] kvm_intel: Unknown symbol kvm_requeue_exception (err -2)
[   43.693855] kvm_intel: Unknown symbol reprogram_counter (err -2)
[   43.693861] kvm_intel: Unknown symbol __SCK__tp_func_kvm_nested_vmenter_failed (err -2)
[   43.693865] kvm_intel: Unknown symbol kvm_exit (err -2)
[   43.693868] kvm_intel: Unknown symbol kvm_init (err -2)
[   43.693874] kvm_intel: Unknown symbol kvm_deliver_exception_payload (err -2)
[   43.693878] kvm_intel: Unknown symbol kvm_set_msr (err -2)
[   43.693880] kvm_intel: Unknown symbol kvm_default_tsc_scaling_ratio (err -2)
[   43.693885] kvm_intel: Unknown symbol __tracepoint_kvm_nested_vmexit (err -2)
[   43.693891] kvm_intel: Unknown symbol enable_vmware_backdoor (err -2)
[   43.693894] kvm_intel: Unknown symbol kvm_enable_efer_bits (err -2)
[   43.693900] kvm_intel: Unknown symbol __SCT__tp_func_kvm_nested_vmexit (err -2)
[   43.693907] kvm_intel: Unknown symbol __kvm_request_immediate_exit (err -2)
[   43.693910] kvm_intel: Unknown symbol kvm_lapic_expired_hv_timer (err -2)
[   43.693913] kvm_intel: Unknown symbol kvm_fixup_and_inject_pf_error (err -2)
[   43.693917] kvm_intel: Unknown symbol gfn_to_page (err -2)
[   43.693922] kvm_intel: Unknown symbol __SCK__tp_func_kvm_cr (err -2)
[   43.693925] kvm_intel: Unknown symbol kvm_probe_user_return_msr (err -2)
[   43.693928] kvm_intel: Unknown symbol kvm_vcpu_write_guest_page (err -2)
[   43.693933] kvm_intel: Unknown symbol kvm_no_apic_vcpu (err -2)
[   43.693938] kvm_intel: Unknown symbol handle_ud (err -2)
[   43.693941] kvm_intel: Unknown symbol kvm_mmu_new_pgd (err -2)
[   43.693946] kvm_intel: Unknown symbol reprogram_fixed_counter (err -2)
[   43.693950] kvm_intel: Unknown symbol __tracepoint_kvm_nested_vmenter_failed (err -2)
[   43.693953] kvm_intel: Unknown symbol kvm_get_msr_common (err -2)
[   43.693956] kvm_intel: Unknown symbol kvm_mmu_slot_largepage_remove_write_access (err -2)
[   43.693961] kvm_intel: Unknown symbol __tracepoint_kvm_fast_mmio (err -2)
[   43.693965] kvm_intel: Unknown symbol kvm_arch_has_noncoherent_dma (err -2)
[   43.693968] kvm_intel: Unknown symbol kvm_hv_get_assist_page (err -2)
[   43.693970] kvm_intel: Unknown symbol kvm_emulate_halt (err -2)
[   43.693973] kvm_intel: Unknown symbol kvm_set_apic_base (err -2)
[   43.693977] kvm_intel: Unknown symbol supported_xss (err -2)
[   43.693983] kvm_intel: Unknown symbol kvm_vcpu_map (err -2)
[   43.693986] kvm_intel: Unknown symbol kvm_msr_allowed (err -2)
[   43.693990] kvm_intel: Unknown symbol kvm_lapic_find_highest_irr (err -2)
[   43.693995] kvm_intel: Unknown symbol kvm_set_xcr (err -2)
[   43.693999] kvm_intel: Unknown symbol kvm_wait_lapic_expire (err -2)
[   43.694004] kvm_intel: Unknown symbol reprogram_gp_counter (err -2)
[   43.694016] kvm_intel: Unknown symbol kvm_write_guest_virt_system (err -2)
[   43.694020] kvm_intel: Unknown symbol kvm_find_cpuid_entry (err -2)
[   43.694025] kvm_intel: Unknown symbol kvm_task_switch (err -2)
[   43.694031] kvm_intel: Unknown symbol __SCT__tp_func_kvm_fast_mmio (err -2)
[   43.694037] kvm_intel: Unknown symbol kvm_read_guest_virt (err -2)
[   43.694044] kvm_intel: Unknown symbol kvm_vcpu_gfn_to_page (err -2)
[   43.694049] kvm_intel: Unknown symbol kvm_write_guest (err -2)
[   43.694055] kvm_intel: Unknown symbol __tracepoint_kvm_cr (err -2)
[   43.694060] kvm_intel: Unknown symbol kvm_io_bus_write (err -2)
[   43.694065] kvm_intel: Unknown symbol kvm_mmu_set_mmio_spte_mask (err -2)
[   43.694070] kvm_intel: Unknown symbol kvm_mmu_clear_dirty_pt_masked (err -2)
[   43.694075] kvm_intel: Unknown symbol kvm_set_user_return_msr (err -2)
[   43.694080] kvm_intel: Unknown symbol kvm_require_cpl (err -2)
[   43.694087] kvm_intel: Unknown symbol __SCT__tp_func_kvm_cr (err -2)
[   43.694092] kvm_intel: Unknown symbol kvm_init_shadow_ept_mmu (err -2)
[   43.694098] kvm_intel: Unknown symbol __tracepoint_kvm_pml_full (err -2)
[   43.694103] kvm_intel: Unknown symbol kvm_requeue_exception_e (err -2)
[   43.694107] kvm_intel: Unknown symbol kvm_lmsw (err -2)
[   43.694112] kvm_intel: Unknown symbol kvm_lapic_set_eoi (err -2)
[   43.694117] kvm_intel: Unknown symbol kvm_queue_exception (err -2)
[   43.694122] kvm_intel: Unknown symbol kvm_lapic_switch_to_hv_timer (err -2)
[   43.694127] kvm_intel: Unknown symbol kvm_emulate_rdmsr (err -2)
[   43.694133] kvm_intel: Unknown symbol __tracepoint_kvm_write_tsc_offset (err -2)
[   43.694138] kvm_intel: Unknown symbol kvm_vcpu_is_reset_bsp (err -2)
[   43.694143] kvm_intel: Unknown symbol __tracepoint_kvm_pi_irte_update (err -2)
[   43.694148] kvm_intel: Unknown symbol kvm_apicv_init (err -2)
[   43.694154] kvm_intel: Unknown symbol __SCT__tp_func_kvm_nested_vmexit_inject (err -2)
[   43.694159] kvm_intel: Unknown symbol kvm_vcpu_unmap (err -2)
[   43.694163] kvm_intel: Unknown symbol kvm_write_guest_page (err -2)
[   43.694171] kvm_intel: Unknown symbol kvm_valid_efer (err -2)
[   43.694177] kvm_intel: Unknown symbol supported_xcr0 (err -2)
[   43.694183] kvm_intel: Unknown symbol __SCK__tp_func_kvm_pi_irte_update (err -2)
[   43.694187] kvm_intel: Unknown symbol kvm_set_rflags (err -2)
[   43.694190] kvm_intel: Unknown symbol kvm_mmu_slot_leaf_clear_dirty (err -2)
[   43.694193] kvm_intel: Unknown symbol kvm_tsc_scaling_ratio_frac_bits (err -2)
[   43.694196] kvm_intel: Unknown symbol kvm_mce_cap_supported (err -2)
[   43.694198] kvm_intel: Unknown symbol kvm_handle_invpcid (err -2)
[   43.694202] kvm_intel: Unknown symbol kvm_load_host_xsave_state (err -2)
[   43.694205] kvm_intel: Unknown symbol __tracepoint_kvm_page_fault (err -2)
[   43.694208] kvm_intel: Unknown symbol kvm_mmu_free_roots (err -2)
[   43.694212] kvm_intel: Unknown symbol kvm_mmu_slot_set_dirty (err -2)
[   43.694214] kvm_intel: Unknown symbol kvm_queue_exception_p (err -2)
[   43.694217] kvm_intel: Unknown symbol kvm_read_l1_tsc (err -2)
[   43.694222] kvm_intel: Unknown symbol __tracepoint_kvm_inj_virq (err -2)
[   43.694224] kvm_intel: Unknown symbol kvm_cpu_has_interrupt (err -2)
[   43.694228] kvm_intel: Unknown symbol __kvm_apic_update_irr (err -2)
[   43.694232] kvm_intel: Unknown symbol handle_fastpath_set_msr_irqoff (err -2)
[   43.694235] kvm_intel: Unknown symbol kvm_apic_update_ppr (err -2)
[   43.694238] kvm_intel: Unknown symbol kvm_configure_mmu (err -2)
[   43.694245] kvm_intel: Unknown symbol kvm_apic_update_irr (err -2)
[   43.694247] kvm_intel: Unknown symbol kvm_init_mmu (err -2)
[   43.694250] kvm_intel: Unknown symbol kvm_emulate_wbinvd (err -2)
[   43.694253] kvm_intel: Unknown symbol kvm_set_cr3 (err -2)
[   43.694257] kvm_intel: Unknown symbol kvm_lapic_switch_to_sw_timer (err -2)
[   43.694263] kvm_intel: Unknown symbol __SCK__tp_func_kvm_page_fault (err -2)
[   43.694265] kvm_intel: Unknown symbol kvm_get_cr8 (err -2)
[   43.694268] kvm_intel: Unknown symbol kvm_x86_ops (err -2)
[   43.694272] kvm_intel: Unknown symbol __SCT__tp_func_kvm_pi_irte_update (err -2)
[   43.694277] kvm_intel: Unknown symbol vcpu_load (err -2)
[   43.694279] kvm_intel: Unknown symbol kvm_handle_memory_failure (err -2)
[   43.694282] kvm_intel: Unknown symbol kvm_set_dr (err -2)
[   43.694285] kvm_intel: Unknown symbol kvm_set_msi_irq (err -2)
[   43.694288] kvm_intel: Unknown symbol kvm_emulate_hypercall (err -2)
[   43.694294] kvm_intel: Unknown symbol kvm_spurious_fault (err -2)
[   43.694297] kvm_intel: Unknown symbol kvm_has_tsc_control (err -2)
[   43.694300] kvm_intel: Unknown symbol kvm_get_linear_rip (err -2)
[   43.694305] kvm_intel: Unknown symbol kvm_get_msr (err -2)
[   43.694308] kvm_intel: Unknown symbol load_pdptrs (err -2)
[   43.694312] kvm_intel: Unknown symbol kvm_get_running_vcpu (err -2)
[   43.694316] kvm_intel: Unknown symbol kvm_vcpu_read_guest_page (err -2)
[   43.694318] kvm_intel: Unknown symbol kvm_set_cpu_caps (err -2)
[   43.694321] kvm_intel: Unknown symbol kvm_vcpu_exit_request (err -2)
[   43.694326] kvm_intel: Unknown symbol host_efer (err -2)
[   43.694328] kvm_intel: Unknown symbol kvm_max_tsc_scaling_ratio (err -2)
[   43.694333] kvm_intel: Unknown symbol __SCT__tp_func_kvm_pml_full (err -2)
[   43.694336] kvm_intel: Unknown symbol pdptrs_changed (err -2)
[   43.694339] kvm_intel: Unknown symbol kvm_set_cr4 (err -2)
[   43.694343] kvm_intel: Unknown symbol __SCK__tp_func_kvm_exit (err -2)
[   43.694346] kvm_intel: Unknown symbol kvm_release_page_clean (err -2)
[   43.694348] kvm_intel: Unknown symbol kvm_handle_page_fault (err -2)
[   43.694351] kvm_intel: Unknown symbol kvm_cpu_caps (err -2)
[   43.694353] kvm_intel: Unknown symbol kvm_spec_ctrl_test_value (err -2)
[   43.694357] kvm_intel: Unknown symbol __SCT__tp_func_kvm_exit (err -2)
[   43.694360] kvm_intel: Unknown symbol kvm_apic_clear_irr (err -2)
[   43.694364] kvm_intel: Unknown symbol __x86_set_memory_region (err -2)
[   43.694367] kvm_intel: Unknown symbol kvm_load_guest_xsave_state (err -2)
[   43.694370] kvm_intel: Unknown symbol kvm_set_cr0 (err -2)
[   43.694373] kvm_intel: Unknown symbol kvm_set_cr8 (err -2)
[   43.694375] kvm_intel: Unknown symbol kvm_get_dr (err -2)
[   43.694380] kvm_intel: Unknown symbol kvm_mmu_page_fault (err -2)
[   43.694384] kvm_intel: Unknown symbol __SCK__tp_func_kvm_nested_vmexit (err -2)
[   43.694389] kvm_intel: Unknown symbol kvm_emulate_instruction (err -2)
[   43.694395] kvm_intel: Unknown symbol __SCK__tp_func_kvm_pml_full (err -2)
[   43.694397] kvm_intel: Unknown symbol kvm_mtrr_get_guest_memory_type (err -2)
[   43.694401] kvm_intel: Unknown symbol kvm_mmu_reset_context (err -2)
[   43.694404] kvm_intel: Unknown symbol kvm_get_apic_mode (err -2)
[   43.694409] kvm_intel: Unknown symbol kvm_vcpu_read_guest (err -2)
[   43.694412] kvm_intel: Unknown symbol kvm_vcpu_on_spin (err -2)
[   43.694416] kvm_intel: Unknown symbol __SCK__tp_func_kvm_fast_mmio (err -2)
[   43.694419] kvm_intel: Unknown symbol kvm_read_guest (err -2)
[   43.694422] kvm_intel: Unknown symbol kvm_define_user_return_msr (err -2)
[   43.694425] kvm_intel: Unknown symbol kvm_rebooting (err -2)
[   43.694428] kvm_intel: Unknown symbol kvm_get_rflags (err -2)
[   43.694432] kvm_intel: Unknown symbol kvm_queue_exception_e (err -2)
[   43.694435] kvm_intel: Unknown symbol __SCT__tp_func_kvm_inj_virq (err -2)
[   43.694439] kvm_intel: Unknown symbol current_vcpu (err -2)
[   43.694444] kvm_intel: Unknown symbol __SCT__tp_func_kvm_write_tsc_offset (err -2)
[   43.694448] kvm_intel: Unknown symbol __tracepoint_kvm_exit (err -2)
[   43.694451] kvm_intel: Unknown symbol kvm_emulate_cpuid (err -2)
[   43.694454] kvm_intel: Unknown symbol kvm_emulate_wrmsr (err -2)
[   43.694457] kvm_intel: Unknown symbol __SCK__tp_func_kvm_inj_virq (err -2)
[   43.694460] kvm_intel: Unknown symbol kvm_apic_set_eoi_accelerated (err -2)
[   43.694464] kvm_intel: Unknown symbol kvm_vcpu_kick (err -2)
[   43.694466] kvm_intel: Unknown symbol kvm_inject_realmode_interrupt (err -2)
[   43.694469] kvm_intel: Unknown symbol kvm_mmu_invlpg (err -2)
[   43.694471] kvm_intel: Unknown symbol kvm_fast_pio (err -2)
[   43.694474] kvm_intel: Unknown symbol __SCK__tp_func_kvm_ple_window_update (err -2)
[   43.694477] kvm_intel: Unknown symbol kvm_set_msr_common (err -2)
[   43.694480] kvm_intel: Unknown symbol __SCT__tp_func_kvm_nested_vmenter_failed (err -2)
[   43.694483] kvm_intel: Unknown symbol __SCK__tp_func_kvm_nested_vmexit_inject (err -2)
[   43.694486] kvm_intel: Unknown symbol kvm_intr_is_single_vcpu (err -2)
[   43.694490] kvm_intel: Unknown symbol kvm_apic_has_interrupt (err -2)
[   43.694494] kvm_intel: Unknown symbol __SCT__tp_func_kvm_ple_window_update (err -2)
[   43.694498] kvm_intel: Unknown symbol __SCK__tp_func_kvm_write_tsc_offset (err -2)
[   43.694501] kvm_intel: Unknown symbol __tracepoint_kvm_nested_vmexit_inject (err -2)
[   43.694504] kvm_intel: Unknown symbol __SCT__tp_func_kvm_page_fault (err -2)
[   43.694507] kvm_intel: Unknown symbol kvm_require_dr (err -2)
[   43.694509] kvm_intel: Unknown symbol kvm_skip_emulated_instruction (err -2)
[   43.694512] kvm_intel: Unknown symbol kvm_inject_page_fault (err -2)
[   43.694515] kvm_intel: Unknown symbol kvm_cpu_get_interrupt (err -2)
[   43.694519] kvm_intel: Unknown symbol kvm_vcpu_write_guest (err -2)
[   43.694521] kvm_intel: Unknown symbol kvm_complete_insn_gp (err -2)
[   43.694525] kvm_intel: Unknown symbol kvm_mmu_set_mask_ptes (err -2)
[   43.694527] kvm_intel: Unknown symbol kvm_apic_write_nodecode (err -2)
[   43.694530] kvm_intel: Unknown symbol kvm_lapic_hv_timer_in_use (err -2)
[   43.694535] kvm_intel: Unknown symbol allow_smaller_maxphyaddr (err -2)
[   43.695437] Console: switching to colour frame buffer device 128x48
[   44.075815] kvm_intel: Unknown symbol __tracepoint_kvm_ple_window_update (err -2)
[   44.078271] ast 0000:08:00.0: [drm] fb0: astdrmfb frame buffer device
[   46.244060] kvm_intel: Unknown symbol vcpu_put (err -2)
[   46.249768] kvm_intel: Unknown symbol kvm_arch_has_assigned_device (err -2)
[   46.257360] kvm_intel: Unknown symbol kvm_rdpmc (err -2)
[   46.263156] kvm_intel: Unknown symbol kvm_vcpu_mark_page_dirty (err -2)
[   46.270373] kvm_intel: Unknown symbol kvm_vcpu_halt (err -2)
[   46.276552] kvm_intel: Unknown symbol kvm_clear_guest_page (err -2)
[   46.283392] kvm_intel: Unknown symbol kvm_requeue_exception (err -2)
[   46.290329] kvm_intel: Unknown symbol reprogram_counter (err -2)
[   46.296886] kvm_intel: Unknown symbol __SCK__tp_func_kvm_nested_vmenter_failed (err -2)
[   46.305612] kvm_intel: Unknown symbol kvm_exit (err -2)
[   46.311311] kvm_intel: Unknown symbol kvm_init (err -2)
[   46.317011] kvm_intel: Unknown symbol kvm_deliver_exception_payload (err -2)
[   46.324698] kvm_intel: Unknown symbol kvm_set_msr (err -2)
[   46.330691] kvm_intel: Unknown symbol kvm_default_tsc_scaling_ratio (err -2)
[   46.338382] kvm_intel: Unknown symbol __tracepoint_kvm_nested_vmexit (err -2)
[   46.346165] kvm_intel: Unknown symbol enable_vmware_backdoor (err -2)
[   46.353189] kvm_intel: Unknown symbol kvm_enable_efer_bits (err -2)
[   46.360037] kvm_intel: Unknown symbol __SCT__tp_func_kvm_nested_vmexit (err -2)
[   46.368006] kvm_intel: Unknown symbol __kvm_request_immediate_exit (err -2)
[   46.375599] kvm_intel: Unknown symbol kvm_lapic_expired_hv_timer (err -2)
[   46.382989] kvm_intel: Unknown symbol kvm_fixup_and_inject_pf_error (err -2)
[   46.390682] kvm_intel: Unknown symbol gfn_to_page (err -2)
[   46.396672] kvm_intel: Unknown symbol __SCK__tp_func_kvm_cr (err -2)
[   46.403605] kvm_intel: Unknown symbol kvm_probe_user_return_msr (err -2)
[   46.410917] kvm_intel: Unknown symbol kvm_vcpu_write_guest_page (err -2)
[   46.418228] kvm_intel: Unknown symbol kvm_no_apic_vcpu (err -2)
[   46.424692] kvm_intel: Unknown symbol handle_ud (err -2)
[   46.430492] kvm_intel: Unknown symbol kvm_mmu_new_pgd (err -2)
[   46.436865] kvm_intel: Unknown symbol reprogram_fixed_counter (err -2)
[   46.443979] kvm_intel: Unknown symbol __tracepoint_kvm_nested_vmenter_failed (err -2)
[   46.452515] kvm_intel: Unknown symbol kvm_get_msr_common (err -2)
[   46.459166] kvm_intel: Unknown symbol kvm_mmu_slot_largepage_remove_write_access (err -2)
[   46.468068] kvm_intel: Unknown symbol __tracepoint_kvm_fast_mmio (err -2)
[   46.475476] kvm_intel: Unknown symbol kvm_arch_has_noncoherent_dma (err -2)
[   46.483060] kvm_intel: Unknown symbol kvm_hv_get_assist_page (err -2)
[   46.490088] kvm_intel: Unknown symbol kvm_emulate_halt (err -2)
[   46.496536] kvm_intel: Unknown symbol kvm_set_apic_base (err -2)
[   46.503092] kvm_intel: Unknown symbol supported_xss (err -2)
[   46.509273] kvm_intel: Unknown symbol kvm_vcpu_map (err -2)
[   46.515353] kvm_intel: Unknown symbol kvm_msr_allowed (err -2)
[   46.521704] kvm_intel: Unknown symbol kvm_lapic_find_highest_irr (err -2)
[   46.529113] kvm_intel: Unknown symbol kvm_set_xcr (err -2)
[   46.535094] kvm_intel: Unknown symbol kvm_wait_lapic_expire (err -2)
[   46.542014] kvm_intel: Unknown symbol reprogram_gp_counter (err -2)
[   46.548847] kvm_intel: Unknown symbol kvm_write_guest_virt_system (err -2)
[   46.556344] kvm_intel: Unknown symbol kvm_find_cpuid_entry (err -2)
[   46.563184] kvm_intel: Unknown symbol kvm_task_switch (err -2)
[   46.569539] kvm_intel: Unknown symbol __SCT__tp_func_kvm_fast_mmio (err -2)
[   46.577113] kvm_intel: Unknown symbol kvm_read_guest_virt (err -2)
[   46.583861] kvm_intel: Unknown symbol kvm_vcpu_gfn_to_page (err -2)
[   46.590700] kvm_intel: Unknown symbol kvm_write_guest (err -2)
[   46.597074] kvm_intel: Unknown symbol __tracepoint_kvm_cr (err -2)
[   46.603806] kvm_intel: Unknown symbol kvm_io_bus_write (err -2)
[   46.610269] kvm_intel: Unknown symbol kvm_mmu_set_mmio_spte_mask (err -2)
[   46.617674] kvm_intel: Unknown symbol kvm_mmu_clear_dirty_pt_masked (err -2)
[   46.625364] kvm_intel: Unknown symbol kvm_set_user_return_msr (err -2)
[   46.632491] kvm_intel: Unknown symbol kvm_require_cpl (err -2)
[   46.638859] kvm_intel: Unknown symbol __SCT__tp_func_kvm_cr (err -2)
[   46.645791] kvm_intel: Unknown symbol kvm_init_shadow_ept_mmu (err -2)
[   46.652907] kvm_intel: Unknown symbol __tracepoint_kvm_pml_full (err -2)
[   46.660222] kvm_intel: Unknown symbol kvm_requeue_exception_e (err -2)
[   46.667341] kvm_intel: Unknown symbol kvm_lmsw (err -2)
[   46.673035] kvm_intel: Unknown symbol kvm_lapic_set_eoi (err -2)
[   46.679572] kvm_intel: Unknown symbol kvm_queue_exception (err -2)
[   46.686319] kvm_intel: Unknown symbol kvm_lapic_switch_to_hv_timer (err -2)
[   46.693918] kvm_intel: Unknown symbol kvm_emulate_rdmsr (err -2)
[   46.700466] kvm_intel: Unknown symbol __tracepoint_kvm_write_tsc_offset (err -2)
[   46.708529] kvm_intel: Unknown symbol kvm_vcpu_is_reset_bsp (err -2)
[   46.715448] kvm_intel: Unknown symbol __tracepoint_kvm_pi_irte_update (err -2)
[   46.723327] kvm_intel: Unknown symbol kvm_apicv_init (err -2)
[   46.729596] kvm_intel: Unknown symbol __SCT__tp_func_kvm_nested_vmexit_inject (err -2)
[   46.738227] kvm_intel: Unknown symbol kvm_vcpu_unmap (err -2)
[   46.744485] kvm_intel: Unknown symbol kvm_write_guest_page (err -2)
[   46.751321] kvm_intel: Unknown symbol kvm_valid_efer (err -2)
[   46.757593] kvm_intel: Unknown symbol supported_xcr0 (err -2)
[   46.763847] kvm_intel: Unknown symbol __SCK__tp_func_kvm_pi_irte_update (err -2)
[   46.771911] kvm_intel: Unknown symbol kvm_set_rflags (err -2)
[   46.778188] kvm_intel: Unknown symbol kvm_mmu_slot_leaf_clear_dirty (err -2)
[   46.785881] kvm_intel: Unknown symbol kvm_tsc_scaling_ratio_frac_bits (err -2)
[   46.793754] kvm_intel: Unknown symbol kvm_mce_cap_supported (err -2)
[   46.800679] kvm_intel: Unknown symbol kvm_handle_invpcid (err -2)
[   46.807305] kvm_intel: Unknown symbol kvm_load_host_xsave_state (err -2)
[   46.814618] kvm_intel: Unknown symbol __tracepoint_kvm_page_fault (err -2)
[   46.822121] kvm_intel: Unknown symbol kvm_mmu_free_roots (err -2)
[   46.828772] kvm_intel: Unknown symbol kvm_mmu_slot_set_dirty (err -2)
[   46.835801] kvm_intel: Unknown symbol kvm_queue_exception_p (err -2)
[   46.842735] kvm_intel: Unknown symbol kvm_read_l1_tsc (err -2)
[   46.849103] kvm_intel: Unknown symbol __tracepoint_kvm_inj_virq (err -2)
[   46.856414] kvm_intel: Unknown symbol kvm_cpu_has_interrupt (err -2)
[   46.863349] kvm_intel: Unknown symbol __kvm_apic_update_irr (err -2)
[   46.870279] kvm_intel: Unknown symbol handle_fastpath_set_msr_irqoff (err -2)
[   46.878057] kvm_intel: Unknown symbol kvm_apic_update_ppr (err -2)
[   46.884797] kvm_intel: Unknown symbol kvm_configure_mmu (err -2)
[   46.891356] kvm_intel: Unknown symbol kvm_apic_update_irr (err -2)
[   46.898101] kvm_intel: Unknown symbol kvm_init_mmu (err -2)
[   46.904176] kvm_intel: Unknown symbol kvm_emulate_wbinvd (err -2)
[   46.910826] kvm_intel: Unknown symbol kvm_set_cr3 (err -2)
[   46.916823] kvm_intel: Unknown symbol kvm_lapic_switch_to_sw_timer (err -2)
[   46.924416] kvm_intel: Unknown symbol __SCK__tp_func_kvm_page_fault (err -2)
[   46.932104] kvm_intel: Unknown symbol kvm_get_cr8 (err -2)
[   46.938096] kvm_intel: Unknown symbol kvm_x86_ops (err -2)
[   46.944087] kvm_intel: Unknown symbol __SCT__tp_func_kvm_pi_irte_update (err -2)
[   46.952151] kvm_intel: Unknown symbol vcpu_load (err -2)
[   46.957954] kvm_intel: Unknown symbol kvm_handle_memory_failure (err -2)
[   46.965258] kvm_intel: Unknown symbol kvm_set_dr (err -2)
[   46.971153] kvm_intel: Unknown symbol kvm_set_msi_irq (err -2)
[   46.977516] kvm_intel: Unknown symbol kvm_emulate_hypercall (err -2)
[   46.984440] kvm_intel: Unknown symbol kvm_spurious_fault (err -2)
[   46.991091] kvm_intel: Unknown symbol kvm_has_tsc_control (err -2)
[   46.997827] kvm_intel: Unknown symbol kvm_get_linear_rip (err -2)
[   47.004469] kvm_intel: Unknown symbol kvm_get_msr (err -2)
[   47.010462] kvm_intel: Unknown symbol load_pdptrs (err -2)
[   47.016441] kvm_intel: Unknown symbol kvm_get_running_vcpu (err -2)
[   47.023282] kvm_intel: Unknown symbol kvm_vcpu_read_guest_page (err -2)
[   47.030499] kvm_intel: Unknown symbol kvm_set_cpu_caps (err -2)
[   47.036952] kvm_intel: Unknown symbol kvm_vcpu_exit_request (err -2)
[   47.043872] kvm_intel: Unknown symbol host_efer (err -2)
[   47.049675] kvm_intel: Unknown symbol kvm_max_tsc_scaling_ratio (err -2)
[   47.056976] kvm_intel: Unknown symbol __SCT__tp_func_kvm_pml_full (err -2)
[   47.064463] kvm_intel: Unknown symbol pdptrs_changed (err -2)
[   47.070735] kvm_intel: Unknown symbol kvm_set_cr4 (err -2)
[   47.076719] kvm_intel: Unknown symbol __SCK__tp_func_kvm_exit (err -2)
[   47.083839] kvm_intel: Unknown symbol kvm_release_page_clean (err -2)
[   47.090866] kvm_intel: Unknown symbol kvm_handle_page_fault (err -2)
[   47.097784] kvm_intel: Unknown symbol kvm_cpu_caps (err -2)
[   47.103870] kvm_intel: Unknown symbol kvm_spec_ctrl_test_value (err -2)
[   47.111089] kvm_intel: Unknown symbol __SCT__tp_func_kvm_exit (err -2)
[   47.118204] kvm_intel: Unknown symbol kvm_apic_clear_irr (err -2)
[   47.124850] kvm_intel: Unknown symbol __x86_set_memory_region (err -2)
[   47.131974] kvm_intel: Unknown symbol kvm_load_guest_xsave_state (err -2)
[   47.139380] kvm_intel: Unknown symbol kvm_set_cr0 (err -2)
[   47.145361] kvm_intel: Unknown symbol kvm_set_cr8 (err -2)
[   47.151353] kvm_intel: Unknown symbol kvm_get_dr (err -2)
[   47.157215] kvm_intel: Unknown symbol kvm_mmu_page_fault (err -2)
[   47.163871] kvm_intel: Unknown symbol __SCK__tp_func_kvm_nested_vmexit (err -2)
[   47.171844] kvm_intel: Unknown symbol kvm_emulate_instruction (err -2)
[   47.178968] kvm_intel: Unknown symbol __SCK__tp_func_kvm_pml_full (err -2)
[   47.186464] kvm_intel: Unknown symbol kvm_mtrr_get_guest_memory_type (err -2)
[   47.194253] kvm_intel: Unknown symbol kvm_mmu_reset_context (err -2)
[   47.201175] kvm_intel: Unknown symbol kvm_get_apic_mode (err -2)
[   47.207734] kvm_intel: Unknown symbol kvm_vcpu_read_guest (err -2)
[   47.214476] kvm_intel: Unknown symbol kvm_vcpu_on_spin (err -2)
[   47.220925] kvm_intel: Unknown symbol __SCK__tp_func_kvm_fast_mmio (err -2)
[   47.228518] kvm_intel: Unknown symbol kvm_read_guest (err -2)
[   47.234783] kvm_intel: Unknown symbol kvm_define_user_return_msr (err -2)
[   47.242193] kvm_intel: Unknown symbol kvm_rebooting (err -2)
[   47.248371] kvm_intel: Unknown symbol kvm_get_rflags (err -2)
[   47.254645] kvm_intel: Unknown symbol kvm_queue_exception_e (err -2)
[   47.261581] kvm_intel: Unknown symbol __SCT__tp_func_kvm_inj_virq (err -2)
[   47.269072] kvm_intel: Unknown symbol current_vcpu (err -2)
[   47.275158] kvm_intel: Unknown symbol __SCT__tp_func_kvm_write_tsc_offset (err -2)
[   47.283412] kvm_intel: Unknown symbol __tracepoint_kvm_exit (err -2)
[   47.290349] kvm_intel: Unknown symbol kvm_emulate_cpuid (err -2)
[   47.296907] kvm_intel: Unknown symbol kvm_emulate_wrmsr (err -2)
[   47.303454] kvm_intel: Unknown symbol __SCK__tp_func_kvm_inj_virq (err -2)
[   47.310955] kvm_intel: Unknown symbol kvm_apic_set_eoi_accelerated (err -2)
[   47.318541] kvm_intel: Unknown symbol kvm_vcpu_kick (err -2)
[   47.324722] kvm_intel: Unknown symbol kvm_inject_realmode_interrupt (err -2)
[   47.332408] kvm_intel: Unknown symbol kvm_mmu_invlpg (err -2)
[   47.338665] kvm_intel: Unknown symbol kvm_fast_pio (err -2)
[   47.344737] kvm_intel: Unknown symbol __SCK__tp_func_kvm_ple_window_update (err -2)
[   47.353095] kvm_intel: Unknown symbol kvm_set_msr_common (err -2)
[   47.359744] kvm_intel: Unknown symbol __SCT__tp_func_kvm_nested_vmenter_failed (err -2)
[   47.368462] kvm_intel: Unknown symbol __SCK__tp_func_kvm_nested_vmexit_inject (err -2)
[   47.377100] kvm_intel: Unknown symbol kvm_intr_is_single_vcpu (err -2)
[   47.384221] kvm_intel: Unknown symbol kvm_apic_has_interrupt (err -2)
[   47.391242] kvm_intel: Unknown symbol __SCT__tp_func_kvm_ple_window_update (err -2)
[   47.399587] kvm_intel: Unknown symbol __SCK__tp_func_kvm_write_tsc_offset (err -2)
[   47.407823] kvm_intel: Unknown symbol __tracepoint_kvm_nested_vmexit_inject (err -2)
[   47.416270] kvm_intel: Unknown symbol __SCT__tp_func_kvm_page_fault (err -2)
[   47.423957] kvm_intel: Unknown symbol kvm_require_dr (err -2)
[   47.430233] kvm_intel: Unknown symbol kvm_skip_emulated_instruction (err -2)
[   47.437921] kvm_intel: Unknown symbol kvm_inject_page_fault (err -2)
[   47.444841] kvm_intel: Unknown symbol kvm_cpu_get_interrupt (err -2)
[   47.451772] kvm_intel: Unknown symbol kvm_vcpu_write_guest (err -2)
[   47.458607] kvm_intel: Unknown symbol kvm_complete_insn_gp (err -2)
[   47.465446] kvm_intel: Unknown symbol kvm_mmu_set_mask_ptes (err -2)
[   47.472381] kvm_intel: Unknown symbol kvm_apic_write_nodecode (err -2)
[   47.479490] kvm_intel: Unknown symbol kvm_lapic_hv_timer_in_use (err -2)
[   47.486789] kvm_intel: Unknown symbol allow_smaller_maxphyaddr (err -2)
[   47.499869] kvm_intel: Unknown symbol __tracepoint_kvm_ple_window_update (err -2)
[   47.509490] kvm_intel: Unknown symbol vcpu_put (err -2)
[   47.516402] kvm_intel: Unknown symbol kvm_arch_has_assigned_device (err -2)
[   47.523993] kvm_intel: Unknown symbol kvm_rdpmc (err -2)
[   47.529796] kvm_intel: Unknown symbol kvm_vcpu_mark_page_dirty (err -2)
[   47.537014] kvm_intel: Unknown symbol kvm_vcpu_halt (err -2)
[   47.543191] kvm_intel: Unknown symbol kvm_clear_guest_page (err -2)
[   47.550022] kvm_intel: Unknown symbol kvm_requeue_exception (err -2)
[   47.556962] kvm_intel: Unknown symbol reprogram_counter (err -2)
[   47.563495] kvm_intel: Unknown symbol __SCK__tp_func_kvm_nested_vmenter_failed (err -2)
[   47.572218] kvm_intel: Unknown symbol kvm_exit (err -2)
[   47.577927] kvm_intel: Unknown symbol kvm_init (err -2)
[   47.583639] kvm_intel: Unknown symbol kvm_deliver_exception_payload (err -2)
[   47.591322] kvm_intel: Unknown symbol kvm_set_msr (err -2)
[   47.597314] kvm_intel: Unknown symbol kvm_default_tsc_scaling_ratio (err -2)
[   47.605010] kvm_intel: Unknown symbol __tracepoint_kvm_nested_vmexit (err -2)
[   47.612796] kvm_intel: Unknown symbol enable_vmware_backdoor (err -2)
[   47.619820] kvm_intel: Unknown symbol kvm_enable_efer_bits (err -2)
[   47.626662] kvm_intel: Unknown symbol __SCT__tp_func_kvm_nested_vmexit (err -2)
[   47.634638] kvm_intel: Unknown symbol __kvm_request_immediate_exit (err -2)
[   47.642232] kvm_intel: Unknown symbol kvm_lapic_expired_hv_timer (err -2)
[   47.649634] kvm_intel: Unknown symbol kvm_fixup_and_inject_pf_error (err -2)
[   47.657326] kvm_intel: Unknown symbol gfn_to_page (err -2)
[   47.663319] kvm_intel: Unknown symbol __SCK__tp_func_kvm_cr (err -2)
[   47.670254] kvm_intel: Unknown symbol kvm_probe_user_return_msr (err -2)
[   47.677555] kvm_intel: Unknown symbol kvm_vcpu_write_guest_page (err -2)
[   47.684868] kvm_intel: Unknown symbol kvm_no_apic_vcpu (err -2)
[   47.691332] kvm_intel: Unknown symbol handle_ud (err -2)
[   47.697134] kvm_intel: Unknown symbol kvm_mmu_new_pgd (err -2)
[   47.703501] kvm_intel: Unknown symbol reprogram_fixed_counter (err -2)
[   47.710624] kvm_intel: Unknown symbol __tracepoint_kvm_nested_vmenter_failed (err -2)
[   47.719163] kvm_intel: Unknown symbol kvm_get_msr_common (err -2)
[   47.725813] kvm_intel: Unknown symbol kvm_mmu_slot_largepage_remove_write_access (err -2)
[   47.734730] kvm_intel: Unknown symbol __tracepoint_kvm_fast_mmio (err -2)
[   47.742137] kvm_intel: Unknown symbol kvm_arch_has_noncoherent_dma (err -2)
[   47.749730] kvm_intel: Unknown symbol kvm_hv_get_assist_page (err -2)
[   47.756763] kvm_intel: Unknown symbol kvm_emulate_halt (err -2)
[   47.763226] kvm_intel: Unknown symbol kvm_set_apic_base (err -2)
[   47.769786] kvm_intel: Unknown symbol supported_xss (err -2)
[   47.775961] kvm_intel: Unknown symbol kvm_vcpu_map (err -2)
[   47.782048] kvm_intel: Unknown symbol kvm_msr_allowed (err -2)
[   47.788414] kvm_intel: Unknown symbol kvm_lapic_find_highest_irr (err -2)
[   47.795817] kvm_intel: Unknown symbol kvm_set_xcr (err -2)
[   47.801800] kvm_intel: Unknown symbol kvm_wait_lapic_expire (err -2)
[   47.808740] kvm_intel: Unknown symbol reprogram_gp_counter (err -2)
[   47.815571] kvm_intel: Unknown symbol kvm_write_guest_virt_system (err -2)
[   47.823059] kvm_intel: Unknown symbol kvm_find_cpuid_entry (err -2)
[   47.829890] kvm_intel: Unknown symbol kvm_task_switch (err -2)
[   47.836263] kvm_intel: Unknown symbol __SCT__tp_func_kvm_fast_mmio (err -2)
[   47.843853] kvm_intel: Unknown symbol kvm_read_guest_virt (err -2)
[   47.850601] kvm_intel: Unknown symbol kvm_vcpu_gfn_to_page (err -2)
[   47.857441] kvm_intel: Unknown symbol kvm_write_guest (err -2)
[   47.863800] kvm_intel: Unknown symbol __tracepoint_kvm_cr (err -2)
[   47.870545] kvm_intel: Unknown symbol kvm_io_bus_write (err -2)
[   47.877008] kvm_intel: Unknown symbol kvm_mmu_set_mmio_spte_mask (err -2)
[   47.884415] kvm_intel: Unknown symbol kvm_mmu_clear_dirty_pt_masked (err -2)
[   47.892105] kvm_intel: Unknown symbol kvm_set_user_return_msr (err -2)
[   47.899228] kvm_intel: Unknown symbol kvm_require_cpl (err -2)
[   47.905590] kvm_intel: Unknown symbol __SCT__tp_func_kvm_cr (err -2)
[   47.912524] kvm_intel: Unknown symbol kvm_init_shadow_ept_mmu (err -2)
[   47.919648] kvm_intel: Unknown symbol __tracepoint_kvm_pml_full (err -2)
[   47.926950] kvm_intel: Unknown symbol kvm_requeue_exception_e (err -2)
[   47.934062] kvm_intel: Unknown symbol kvm_lmsw (err -2)
[   47.939763] kvm_intel: Unknown symbol kvm_lapic_set_eoi (err -2)
[   47.946314] kvm_intel: Unknown symbol kvm_queue_exception (err -2)
[   47.953056] kvm_intel: Unknown symbol kvm_lapic_switch_to_hv_timer (err -2)
[   47.960652] kvm_intel: Unknown symbol kvm_emulate_rdmsr (err -2)
[   47.967193] kvm_intel: Unknown symbol __tracepoint_kvm_write_tsc_offset (err -2)
[   47.975253] kvm_intel: Unknown symbol kvm_vcpu_is_reset_bsp (err -2)
[   47.982189] kvm_intel: Unknown symbol __tracepoint_kvm_pi_irte_update (err -2)
[   47.990064] kvm_intel: Unknown symbol kvm_apicv_init (err -2)
[   47.996344] kvm_intel: Unknown symbol __SCT__tp_func_kvm_nested_vmexit_inject (err -2)
[   48.004973] kvm_intel: Unknown symbol kvm_vcpu_unmap (err -2)
[   48.011249] kvm_intel: Unknown symbol kvm_write_guest_page (err -2)
[   48.018082] kvm_intel: Unknown symbol kvm_valid_efer (err -2)
[   48.024355] kvm_intel: Unknown symbol supported_xcr0 (err -2)
[   48.030629] kvm_intel: Unknown symbol __SCK__tp_func_kvm_pi_irte_update (err -2)
[   48.038693] kvm_intel: Unknown symbol kvm_set_rflags (err -2)
[   48.044968] kvm_intel: Unknown symbol kvm_mmu_slot_leaf_clear_dirty (err -2)
[   48.052658] kvm_intel: Unknown symbol kvm_tsc_scaling_ratio_frac_bits (err -2)
[   48.060537] kvm_intel: Unknown symbol kvm_mce_cap_supported (err -2)
[   48.067471] kvm_intel: Unknown symbol kvm_handle_invpcid (err -2)
[   48.074122] kvm_intel: Unknown symbol kvm_load_host_xsave_state (err -2)
[   48.081433] kvm_intel: Unknown symbol __tracepoint_kvm_page_fault (err -2)
[   48.088929] kvm_intel: Unknown symbol kvm_mmu_free_roots (err -2)
[   48.095581] kvm_intel: Unknown symbol kvm_mmu_slot_set_dirty (err -2)
[   48.102607] kvm_intel: Unknown symbol kvm_queue_exception_p (err -2)
[   48.109541] kvm_intel: Unknown symbol kvm_read_l1_tsc (err -2)
[   48.115912] kvm_intel: Unknown symbol __tracepoint_kvm_inj_virq (err -2)
[   48.123221] kvm_intel: Unknown symbol kvm_cpu_has_interrupt (err -2)
[   48.130158] kvm_intel: Unknown symbol __kvm_apic_update_irr (err -2)
[   48.137078] kvm_intel: Unknown symbol handle_fastpath_set_msr_irqoff (err -2)
[   48.144861] kvm_intel: Unknown symbol kvm_apic_update_ppr (err -2)
[   48.151599] kvm_intel: Unknown symbol kvm_configure_mmu (err -2)
[   48.158149] kvm_intel: Unknown symbol kvm_apic_update_irr (err -2)
[   48.164881] kvm_intel: Unknown symbol kvm_init_mmu (err -2)
[   48.170955] kvm_intel: Unknown symbol kvm_emulate_wbinvd (err -2)
[   48.177606] kvm_intel: Unknown symbol kvm_set_cr3 (err -2)
[   48.183602] kvm_intel: Unknown symbol kvm_lapic_switch_to_sw_timer (err -2)
[   48.191199] kvm_intel: Unknown symbol __SCK__tp_func_kvm_page_fault (err -2)
[   48.198877] kvm_intel: Unknown symbol kvm_get_cr8 (err -2)
[   48.204863] kvm_intel: Unknown symbol kvm_x86_ops (err -2)
[   48.210860] kvm_intel: Unknown symbol __SCT__tp_func_kvm_pi_irte_update (err -2)
[   48.218926] kvm_intel: Unknown symbol vcpu_load (err -2)
[   48.224725] kvm_intel: Unknown symbol kvm_handle_memory_failure (err -2)
[   48.232028] kvm_intel: Unknown symbol kvm_set_dr (err -2)
[   48.237915] kvm_intel: Unknown symbol kvm_set_msi_irq (err -2)
[   48.244275] kvm_intel: Unknown symbol kvm_emulate_hypercall (err -2)
[   48.251213] kvm_intel: Unknown symbol kvm_spurious_fault (err -2)
[   48.257863] kvm_intel: Unknown symbol kvm_has_tsc_control (err -2)
[   48.264606] kvm_intel: Unknown symbol kvm_get_linear_rip (err -2)
[   48.271260] kvm_intel: Unknown symbol kvm_get_msr (err -2)
[   48.277234] kvm_intel: Unknown symbol load_pdptrs (err -2)
[   48.283223] kvm_intel: Unknown symbol kvm_get_running_vcpu (err -2)
[   48.290064] kvm_intel: Unknown symbol kvm_vcpu_read_guest_page (err -2)
[   48.297272] kvm_intel: Unknown symbol kvm_set_cpu_caps (err -2)
[   48.303726] kvm_intel: Unknown symbol kvm_vcpu_exit_request (err -2)
[   48.310654] kvm_intel: Unknown symbol host_efer (err -2)
[   48.316440] kvm_intel: Unknown symbol kvm_max_tsc_scaling_ratio (err -2)
[   48.323751] kvm_intel: Unknown symbol __SCT__tp_func_kvm_pml_full (err -2)
[   48.331249] kvm_intel: Unknown symbol pdptrs_changed (err -2)
[   48.337526] kvm_intel: Unknown symbol kvm_set_cr4 (err -2)
[   48.343489] kvm_intel: Unknown symbol __SCK__tp_func_kvm_exit (err -2)
[   48.350612] kvm_intel: Unknown symbol kvm_release_page_clean (err -2)
[   48.357638] kvm_intel: Unknown symbol kvm_handle_page_fault (err -2)
[   48.364575] kvm_intel: Unknown symbol kvm_cpu_caps (err -2)
[   48.370663] kvm_intel: Unknown symbol kvm_spec_ctrl_test_value (err -2)
[   48.377879] kvm_intel: Unknown symbol __SCT__tp_func_kvm_exit (err -2)
[   48.384993] kvm_intel: Unknown symbol kvm_apic_clear_irr (err -2)
[   48.391645] kvm_intel: Unknown symbol __x86_set_memory_region (err -2)
[   48.398769] kvm_intel: Unknown symbol kvm_load_guest_xsave_state (err -2)
[   48.406173] kvm_intel: Unknown symbol kvm_set_cr0 (err -2)
[   48.412151] kvm_intel: Unknown symbol kvm_set_cr8 (err -2)
[   48.418139] kvm_intel: Unknown symbol kvm_get_dr (err -2)
[   48.424031] kvm_intel: Unknown symbol kvm_mmu_page_fault (err -2)
[   48.430682] kvm_intel: Unknown symbol __SCK__tp_func_kvm_nested_vmexit (err -2)
[   48.438637] kvm_intel: Unknown symbol kvm_emulate_instruction (err -2)
[   48.445761] kvm_intel: Unknown symbol __SCK__tp_func_kvm_pml_full (err -2)
[   48.453261] kvm_intel: Unknown symbol kvm_mtrr_get_guest_memory_type (err -2)
[   48.461047] kvm_intel: Unknown symbol kvm_mmu_reset_context (err -2)
[   48.467981] kvm_intel: Unknown symbol kvm_get_apic_mode (err -2)
[   48.474540] kvm_intel: Unknown symbol kvm_vcpu_read_guest (err -2)
[   48.481286] kvm_intel: Unknown symbol kvm_vcpu_on_spin (err -2)
[   48.487750] kvm_intel: Unknown symbol __SCK__tp_func_kvm_fast_mmio (err -2)
[   48.495345] kvm_intel: Unknown symbol kvm_read_guest (err -2)
[   48.501617] kvm_intel: Unknown symbol kvm_define_user_return_msr (err -2)
[   48.509026] kvm_intel: Unknown symbol kvm_rebooting (err -2)
[   48.515206] kvm_intel: Unknown symbol kvm_get_rflags (err -2)
[   48.521481] kvm_intel: Unknown symbol kvm_queue_exception_e (err -2)
[   48.528415] kvm_intel: Unknown symbol __SCT__tp_func_kvm_inj_virq (err -2)
[   48.535891] kvm_intel: Unknown symbol current_vcpu (err -2)
[   48.541970] kvm_intel: Unknown symbol __SCT__tp_func_kvm_write_tsc_offset (err -2)
[   48.550222] kvm_intel: Unknown symbol __tracepoint_kvm_exit (err -2)
[   48.557150] kvm_intel: Unknown symbol kvm_emulate_cpuid (err -2)
[   48.563707] kvm_intel: Unknown symbol kvm_emulate_wrmsr (err -2)
[   48.570266] kvm_intel: Unknown symbol __SCK__tp_func_kvm_inj_virq (err -2)
[   48.577764] kvm_intel: Unknown symbol kvm_apic_set_eoi_accelerated (err -2)
[   48.585353] kvm_intel: Unknown symbol kvm_vcpu_kick (err -2)
[   48.591522] kvm_intel: Unknown symbol kvm_inject_realmode_interrupt (err -2)
[   48.599213] kvm_intel: Unknown symbol kvm_mmu_invlpg (err -2)
[   48.605488] kvm_intel: Unknown symbol kvm_fast_pio (err -2)
[   48.611574] kvm_intel: Unknown symbol __SCK__tp_func_kvm_ple_window_update (err -2)
[   48.619922] kvm_intel: Unknown symbol kvm_set_msr_common (err -2)
[   48.626570] kvm_intel: Unknown symbol __SCT__tp_func_kvm_nested_vmenter_failed (err -2)
[   48.635290] kvm_intel: Unknown symbol __SCK__tp_func_kvm_nested_vmexit_inject (err -2)
[   48.643920] kvm_intel: Unknown symbol kvm_intr_is_single_vcpu (err -2)
[   48.651049] kvm_intel: Unknown symbol kvm_apic_has_interrupt (err -2)
[   48.658079] kvm_intel: Unknown symbol __SCT__tp_func_kvm_ple_window_update (err -2)
[   48.666420] kvm_intel: Unknown symbol __SCK__tp_func_kvm_write_tsc_offset (err -2)
[   48.674675] kvm_intel: Unknown symbol __tracepoint_kvm_nested_vmexit_inject (err -2)
[   48.683119] kvm_intel: Unknown symbol __SCT__tp_func_kvm_page_fault (err -2)
[   48.690807] kvm_intel: Unknown symbol kvm_require_dr (err -2)
[   48.697085] kvm_intel: Unknown symbol kvm_skip_emulated_instruction (err -2)
[   48.704773] kvm_intel: Unknown symbol kvm_inject_page_fault (err -2)
[   48.711700] kvm_intel: Unknown symbol kvm_cpu_get_interrupt (err -2)
[   48.718626] kvm_intel: Unknown symbol kvm_vcpu_write_guest (err -2)
[   48.725466] kvm_intel: Unknown symbol kvm_complete_insn_gp (err -2)
[   48.732306] kvm_intel: Unknown symbol kvm_mmu_set_mask_ptes (err -2)
[   48.739241] kvm_intel: Unknown symbol kvm_apic_write_nodecode (err -2)
[   48.746360] kvm_intel: Unknown symbol kvm_lapic_hv_timer_in_use (err -2)
[   48.753671] kvm_intel: Unknown symbol allow_smaller_maxphyaddr (err -2)
[   48.768929] kvm_intel: Unknown symbol __tracepoint_kvm_ple_window_update (err -2)
[   48.777719] kvm_intel: Unknown symbol vcpu_put (err -2)
[   48.783450] kvm_intel: Unknown symbol kvm_arch_has_assigned_device (err -2)
[   48.791045] kvm_intel: Unknown symbol kvm_rdpmc (err -2)
[   48.798203] kvm_intel: Unknown symbol kvm_vcpu_mark_page_dirty (err -2)
[   48.805428] kvm_intel: Unknown symbol kvm_vcpu_halt (err -2)
[   48.811601] kvm_intel: Unknown symbol kvm_clear_guest_page (err -2)
[   48.818436] kvm_intel: Unknown symbol kvm_requeue_exception (err -2)
[   48.825376] kvm_intel: Unknown symbol reprogram_counter (err -2)
[   48.831934] kvm_intel: Unknown symbol __SCK__tp_func_kvm_nested_vmenter_failed (err -2)
[   48.840650] kvm_intel: Unknown symbol kvm_exit (err -2)
[   48.846356] kvm_intel: Unknown symbol kvm_init (err -2)
[   48.852067] kvm_intel: Unknown symbol kvm_deliver_exception_payload (err -2)
[   48.859756] kvm_intel: Unknown symbol kvm_set_msr (err -2)
[   48.865747] kvm_intel: Unknown symbol kvm_default_tsc_scaling_ratio (err -2)
[   48.873425] kvm_intel: Unknown symbol __tracepoint_kvm_nested_vmexit (err -2)
[   48.881212] kvm_intel: Unknown symbol enable_vmware_backdoor (err -2)
[   48.888237] kvm_intel: Unknown symbol kvm_enable_efer_bits (err -2)
[   48.895065] kvm_intel: Unknown symbol __SCT__tp_func_kvm_nested_vmexit (err -2)
[   48.903037] kvm_intel: Unknown symbol __kvm_request_immediate_exit (err -2)
[   48.910627] kvm_intel: Unknown symbol kvm_lapic_expired_hv_timer (err -2)
[   48.918034] kvm_intel: Unknown symbol kvm_fixup_and_inject_pf_error (err -2)
[   48.925708] kvm_intel: Unknown symbol gfn_to_page (err -2)
[   48.931689] kvm_intel: Unknown symbol __SCK__tp_func_kvm_cr (err -2)
[   48.938623] kvm_intel: Unknown symbol kvm_probe_user_return_msr (err -2)
[   48.945937] kvm_intel: Unknown symbol kvm_vcpu_write_guest_page (err -2)
[   48.953247] kvm_intel: Unknown symbol kvm_no_apic_vcpu (err -2)
[   48.959714] kvm_intel: Unknown symbol handle_ud (err -2)
[   48.965502] kvm_intel: Unknown symbol kvm_mmu_new_pgd (err -2)
[   48.971872] kvm_intel: Unknown symbol reprogram_fixed_counter (err -2)
[   48.978995] kvm_intel: Unknown symbol __tracepoint_kvm_nested_vmenter_failed (err -2)
[   48.987533] kvm_intel: Unknown symbol kvm_get_msr_common (err -2)
[   48.994185] kvm_intel: Unknown symbol kvm_mmu_slot_largepage_remove_write_access (err -2)
[   49.003106] kvm_intel: Unknown symbol __tracepoint_kvm_fast_mmio (err -2)
[   49.010510] kvm_intel: Unknown symbol kvm_arch_has_noncoherent_dma (err -2)
[   49.018104] kvm_intel: Unknown symbol kvm_hv_get_assist_page (err -2)
[   49.025134] kvm_intel: Unknown symbol kvm_emulate_halt (err -2)
[   49.031597] kvm_intel: Unknown symbol kvm_set_apic_base (err -2)
[   49.038143] kvm_intel: Unknown symbol supported_xss (err -2)
[   49.044322] kvm_intel: Unknown symbol kvm_vcpu_map (err -2)
[   49.050408] kvm_intel: Unknown symbol kvm_msr_allowed (err -2)
[   49.056779] kvm_intel: Unknown symbol kvm_lapic_find_highest_irr (err -2)
[   49.064174] kvm_intel: Unknown symbol kvm_set_xcr (err -2)
[   49.070165] kvm_intel: Unknown symbol kvm_wait_lapic_expire (err -2)
[   49.077089] kvm_intel: Unknown symbol reprogram_gp_counter (err -2)
[   49.083935] kvm_intel: Unknown symbol kvm_write_guest_virt_system (err -2)
[   49.091431] kvm_intel: Unknown symbol kvm_find_cpuid_entry (err -2)
[   49.098273] kvm_intel: Unknown symbol kvm_task_switch (err -2)
[   49.104644] kvm_intel: Unknown symbol __SCT__tp_func_kvm_fast_mmio (err -2)
[   49.112238] kvm_intel: Unknown symbol kvm_read_guest_virt (err -2)
[   49.118985] kvm_intel: Unknown symbol kvm_vcpu_gfn_to_page (err -2)
[   49.125805] kvm_intel: Unknown symbol kvm_write_guest (err -2)
[   49.132156] kvm_intel: Unknown symbol __tracepoint_kvm_cr (err -2)
[   49.138896] kvm_intel: Unknown symbol kvm_io_bus_write (err -2)
[   49.145356] kvm_intel: Unknown symbol kvm_mmu_set_mmio_spte_mask (err -2)
[   49.152762] kvm_intel: Unknown symbol kvm_mmu_clear_dirty_pt_masked (err -2)
[   49.160453] kvm_intel: Unknown symbol kvm_set_user_return_msr (err -2)
[   49.167575] kvm_intel: Unknown symbol kvm_require_cpl (err -2)
[   49.173949] kvm_intel: Unknown symbol __SCT__tp_func_kvm_cr (err -2)
[   49.180878] kvm_intel: Unknown symbol kvm_init_shadow_ept_mmu (err -2)
[   49.188001] kvm_intel: Unknown symbol __tracepoint_kvm_pml_full (err -2)
[   49.195315] kvm_intel: Unknown symbol kvm_requeue_exception_e (err -2)
[   49.202426] kvm_intel: Unknown symbol kvm_lmsw (err -2)
[   49.208135] kvm_intel: Unknown symbol kvm_lapic_set_eoi (err -2)
[   49.214689] kvm_intel: Unknown symbol kvm_queue_exception (err -2)
[   49.221438] kvm_intel: Unknown symbol kvm_lapic_switch_to_hv_timer (err -2)
[   49.229035] kvm_intel: Unknown symbol kvm_emulate_rdmsr (err -2)
[   49.235589] kvm_intel: Unknown symbol __tracepoint_kvm_write_tsc_offset (err -2)
[   49.243655] kvm_intel: Unknown symbol kvm_vcpu_is_reset_bsp (err -2)
[   49.250592] kvm_intel: Unknown symbol __tracepoint_kvm_pi_irte_update (err -2)
[   49.258467] kvm_intel: Unknown symbol kvm_apicv_init (err -2)
[   49.264742] kvm_intel: Unknown symbol __SCT__tp_func_kvm_nested_vmexit_inject (err -2)
[   49.273374] kvm_intel: Unknown symbol kvm_vcpu_unmap (err -2)
[   49.279651] kvm_intel: Unknown symbol kvm_write_guest_page (err -2)
[   49.286483] kvm_intel: Unknown symbol kvm_valid_efer (err -2)
[   49.292753] kvm_intel: Unknown symbol supported_xcr0 (err -2)
[   49.299022] kvm_intel: Unknown symbol __SCK__tp_func_kvm_pi_irte_update (err -2)
[   49.307083] kvm_intel: Unknown symbol kvm_set_rflags (err -2)
[   49.313360] kvm_intel: Unknown symbol kvm_mmu_slot_leaf_clear_dirty (err -2)
[   49.321050] kvm_intel: Unknown symbol kvm_tsc_scaling_ratio_frac_bits (err -2)
[   49.328926] kvm_intel: Unknown symbol kvm_mce_cap_supported (err -2)
[   49.335861] kvm_intel: Unknown symbol kvm_handle_invpcid (err -2)
[   49.342515] kvm_intel: Unknown symbol kvm_load_host_xsave_state (err -2)
[   49.349826] kvm_intel: Unknown symbol __tracepoint_kvm_page_fault (err -2)
[   49.357323] kvm_intel: Unknown symbol kvm_mmu_free_roots (err -2)
[   49.363977] kvm_intel: Unknown symbol kvm_mmu_slot_set_dirty (err -2)
[   49.371006] kvm_intel: Unknown symbol kvm_queue_exception_p (err -2)
[   49.377939] kvm_intel: Unknown symbol kvm_read_l1_tsc (err -2)
[   49.384310] kvm_intel: Unknown symbol __tracepoint_kvm_inj_virq (err -2)
[   49.391619] kvm_intel: Unknown symbol kvm_cpu_has_interrupt (err -2)
[   49.398545] kvm_intel: Unknown symbol __kvm_apic_update_irr (err -2)
[   49.405482] kvm_intel: Unknown symbol handle_fastpath_set_msr_irqoff (err -2)
[   49.413261] kvm_intel: Unknown symbol kvm_apic_update_ppr (err -2)
[   49.420012] kvm_intel: Unknown symbol kvm_configure_mmu (err -2)
[   49.426569] kvm_intel: Unknown symbol kvm_apic_update_irr (err -2)
[   49.433312] kvm_intel: Unknown symbol kvm_init_mmu (err -2)
[   49.439394] kvm_intel: Unknown symbol kvm_emulate_wbinvd (err -2)
[   49.446040] kvm_intel: Unknown symbol kvm_set_cr3 (err -2)
[   49.452031] kvm_intel: Unknown symbol kvm_lapic_switch_to_sw_timer (err -2)
[   49.459629] kvm_intel: Unknown symbol __SCK__tp_func_kvm_page_fault (err -2)
[   49.467304] kvm_intel: Unknown symbol kvm_get_cr8 (err -2)
[   49.473295] kvm_intel: Unknown symbol kvm_x86_ops (err -2)
[   49.479288] kvm_intel: Unknown symbol __SCT__tp_func_kvm_pi_irte_update (err -2)
[   49.487346] kvm_intel: Unknown symbol vcpu_load (err -2)
[   49.493136] kvm_intel: Unknown symbol kvm_handle_memory_failure (err -2)
[   49.500448] kvm_intel: Unknown symbol kvm_set_dr (err -2)
[   49.506343] kvm_intel: Unknown symbol kvm_set_msi_irq (err -2)
[   49.512714] kvm_intel: Unknown symbol kvm_emulate_hypercall (err -2)
[   49.519652] kvm_intel: Unknown symbol kvm_spurious_fault (err -2)
[   49.526298] kvm_intel: Unknown symbol kvm_has_tsc_control (err -2)
[   49.533047] kvm_intel: Unknown symbol kvm_get_linear_rip (err -2)
[   49.539688] kvm_intel: Unknown symbol kvm_get_msr (err -2)
[   49.545681] kvm_intel: Unknown symbol load_pdptrs (err -2)
[   49.551674] kvm_intel: Unknown symbol kvm_get_running_vcpu (err -2)
[   49.558503] kvm_intel: Unknown symbol kvm_vcpu_read_guest_page (err -2)
[   49.565719] kvm_intel: Unknown symbol kvm_set_cpu_caps (err -2)
[   49.572180] kvm_intel: Unknown symbol kvm_vcpu_exit_request (err -2)
[   49.579118] kvm_intel: Unknown symbol host_efer (err -2)
[   49.584919] kvm_intel: Unknown symbol kvm_max_tsc_scaling_ratio (err -2)
[   49.592229] kvm_intel: Unknown symbol __SCT__tp_func_kvm_pml_full (err -2)
[   49.599725] kvm_intel: Unknown symbol pdptrs_changed (err -2)
[   49.605979] kvm_intel: Unknown symbol kvm_set_cr4 (err -2)
[   49.611960] kvm_intel: Unknown symbol __SCK__tp_func_kvm_exit (err -2)
[   49.619085] kvm_intel: Unknown symbol kvm_release_page_clean (err -2)
[   49.626108] kvm_intel: Unknown symbol kvm_handle_page_fault (err -2)
[   49.633045] kvm_intel: Unknown symbol kvm_cpu_caps (err -2)
[   49.639120] kvm_intel: Unknown symbol kvm_spec_ctrl_test_value (err -2)
[   49.646341] kvm_intel: Unknown symbol __SCT__tp_func_kvm_exit (err -2)
[   49.653462] kvm_intel: Unknown symbol kvm_apic_clear_irr (err -2)
[   49.660104] kvm_intel: Unknown symbol __x86_set_memory_region (err -2)
[   49.667226] kvm_intel: Unknown symbol kvm_load_guest_xsave_state (err -2)
[   49.674634] kvm_intel: Unknown symbol kvm_set_cr0 (err -2)
[   49.680625] kvm_intel: Unknown symbol kvm_set_cr8 (err -2)
[   49.686604] kvm_intel: Unknown symbol kvm_get_dr (err -2)
[   49.692496] kvm_intel: Unknown symbol kvm_mmu_page_fault (err -2)
[   49.699135] kvm_intel: Unknown symbol __SCK__tp_func_kvm_nested_vmexit (err -2)
[   49.707110] kvm_intel: Unknown symbol kvm_emulate_instruction (err -2)
[   49.714214] kvm_intel: Unknown symbol __SCK__tp_func_kvm_pml_full (err -2)
[   49.721712] kvm_intel: Unknown symbol kvm_mtrr_get_guest_memory_type (err -2)
[   49.729496] kvm_intel: Unknown symbol kvm_mmu_reset_context (err -2)
[   49.736428] kvm_intel: Unknown symbol kvm_get_apic_mode (err -2)
[   49.742987] kvm_intel: Unknown symbol kvm_vcpu_read_guest (err -2)
[   49.749733] kvm_intel: Unknown symbol kvm_vcpu_on_spin (err -2)
[   49.756196] kvm_intel: Unknown symbol __SCK__tp_func_kvm_fast_mmio (err -2)
[   49.763787] kvm_intel: Unknown symbol kvm_read_guest (err -2)
[   49.770063] kvm_intel: Unknown symbol kvm_define_user_return_msr (err -2)
[   49.777473] kvm_intel: Unknown symbol kvm_rebooting (err -2)
[   49.783650] kvm_intel: Unknown symbol kvm_get_rflags (err -2)
[   49.789922] kvm_intel: Unknown symbol kvm_queue_exception_e (err -2)
[   49.796857] kvm_intel: Unknown symbol __SCT__tp_func_kvm_inj_virq (err -2)
[   49.804357] kvm_intel: Unknown symbol current_vcpu (err -2)
[   49.810433] kvm_intel: Unknown symbol __SCT__tp_func_kvm_write_tsc_offset (err -2)
[   49.818688] kvm_intel: Unknown symbol __tracepoint_kvm_exit (err -2)
[   49.825614] kvm_intel: Unknown symbol kvm_emulate_cpuid (err -2)
[   49.832167] kvm_intel: Unknown symbol kvm_emulate_wrmsr (err -2)
[   49.838725] kvm_intel: Unknown symbol __SCK__tp_func_kvm_inj_virq (err -2)
[   49.846226] kvm_intel: Unknown symbol kvm_apic_set_eoi_accelerated (err -2)
[   49.853823] kvm_intel: Unknown symbol kvm_vcpu_kick (err -2)
[   49.860000] kvm_intel: Unknown symbol kvm_inject_realmode_interrupt (err -2)
[   49.867694] kvm_intel: Unknown symbol kvm_mmu_invlpg (err -2)
[   49.873963] kvm_intel: Unknown symbol kvm_fast_pio (err -2)
[   49.880033] kvm_intel: Unknown symbol __SCK__tp_func_kvm_ple_window_update (err -2)
[   49.888362] kvm_intel: Unknown symbol kvm_set_msr_common (err -2)
[   49.895010] kvm_intel: Unknown symbol __SCT__tp_func_kvm_nested_vmenter_failed (err -2)
[   49.903739] kvm_intel: Unknown symbol __SCK__tp_func_kvm_nested_vmexit_inject (err -2)
[   49.912372] kvm_intel: Unknown symbol kvm_intr_is_single_vcpu (err -2)
[   49.919498] kvm_intel: Unknown symbol kvm_apic_has_interrupt (err -2)
[   49.926523] kvm_intel: Unknown symbol __SCT__tp_func_kvm_ple_window_update (err -2)
[   49.934872] kvm_intel: Unknown symbol __SCK__tp_func_kvm_write_tsc_offset (err -2)
[   49.943126] kvm_intel: Unknown symbol __tracepoint_kvm_nested_vmexit_inject (err -2)
[   49.951572] kvm_intel: Unknown symbol __SCT__tp_func_kvm_page_fault (err -2)
[   49.959263] kvm_intel: Unknown symbol kvm_require_dr (err -2)
[   49.965537] kvm_intel: Unknown symbol kvm_skip_emulated_instruction (err -2)
[   49.973225] kvm_intel: Unknown symbol kvm_inject_page_fault (err -2)
[   49.980149] kvm_intel: Unknown symbol kvm_cpu_get_interrupt (err -2)
[   49.987089] kvm_intel: Unknown symbol kvm_vcpu_write_guest (err -2)
[   49.993922] kvm_intel: Unknown symbol kvm_complete_insn_gp (err -2)
[   50.000759] kvm_intel: Unknown symbol kvm_mmu_set_mask_ptes (err -2)
[   50.007695] kvm_intel: Unknown symbol kvm_apic_write_nodecode (err -2)
[   50.014820] kvm_intel: Unknown symbol kvm_lapic_hv_timer_in_use (err -2)
[   50.022123] kvm_intel: Unknown symbol allow_smaller_maxphyaddr (err -2)
[   50.033837] kvm_intel: Unknown symbol __tracepoint_kvm_ple_window_update (err -2)
[   50.043245] kvm_intel: Unknown symbol vcpu_put (err -2)
[   50.048947] kvm_intel: Unknown symbol kvm_arch_has_assigned_device (err -2)
[   50.056540] kvm_intel: Unknown symbol kvm_rdpmc (err -2)
[   50.062341] kvm_intel: Unknown symbol kvm_vcpu_mark_page_dirty (err -2)
[   50.069554] kvm_intel: Unknown symbol kvm_vcpu_halt (err -2)
[   50.075718] kvm_intel: Unknown symbol kvm_clear_guest_page (err -2)
[   50.082559] kvm_intel: Unknown symbol kvm_requeue_exception (err -2)
[   50.089486] kvm_intel: Unknown symbol reprogram_counter (err -2)
[   50.096046] kvm_intel: Unknown symbol __SCK__tp_func_kvm_nested_vmenter_failed (err -2)
[   50.104771] kvm_intel: Unknown symbol kvm_exit (err -2)
[   50.110466] kvm_intel: Unknown symbol kvm_init (err -2)
[   50.116175] kvm_intel: Unknown symbol kvm_deliver_exception_payload (err -2)
[   50.123853] kvm_intel: Unknown symbol kvm_set_msr (err -2)
[   50.129829] kvm_intel: Unknown symbol kvm_default_tsc_scaling_ratio (err -2)
[   50.137506] kvm_intel: Unknown symbol __tracepoint_kvm_nested_vmexit (err -2)
[   50.145287] kvm_intel: Unknown symbol enable_vmware_backdoor (err -2)
[   50.152312] kvm_intel: Unknown symbol kvm_enable_efer_bits (err -2)
[   50.159152] kvm_intel: Unknown symbol __SCT__tp_func_kvm_nested_vmexit (err -2)
[   50.167123] kvm_intel: Unknown symbol __kvm_request_immediate_exit (err -2)
[   50.174711] kvm_intel: Unknown symbol kvm_lapic_expired_hv_timer (err -2)
[   50.182103] kvm_intel: Unknown symbol kvm_fixup_and_inject_pf_error (err -2)
[   50.189792] kvm_intel: Unknown symbol gfn_to_page (err -2)
[   50.195776] kvm_intel: Unknown symbol __SCK__tp_func_kvm_cr (err -2)
[   50.202704] kvm_intel: Unknown symbol kvm_probe_user_return_msr (err -2)
[   50.210000] kvm_intel: Unknown symbol kvm_vcpu_write_guest_page (err -2)
[   50.217312] kvm_intel: Unknown symbol kvm_no_apic_vcpu (err -2)
[   50.223777] kvm_intel: Unknown symbol handle_ud (err -2)
[   50.229574] kvm_intel: Unknown symbol kvm_mmu_new_pgd (err -2)
[   50.235945] kvm_intel: Unknown symbol reprogram_fixed_counter (err -2)
[   50.243071] kvm_intel: Unknown symbol __tracepoint_kvm_nested_vmenter_failed (err -2)
[   50.251604] kvm_intel: Unknown symbol kvm_get_msr_common (err -2)
[   50.258258] kvm_intel: Unknown symbol kvm_mmu_slot_largepage_remove_write_access (err -2)
[   50.267173] kvm_intel: Unknown symbol __tracepoint_kvm_fast_mmio (err -2)
[   50.274570] kvm_intel: Unknown symbol kvm_arch_has_noncoherent_dma (err -2)
[   50.282155] kvm_intel: Unknown symbol kvm_hv_get_assist_page (err -2)
[   50.289186] kvm_intel: Unknown symbol kvm_emulate_halt (err -2)
[   50.295639] kvm_intel: Unknown symbol kvm_set_apic_base (err -2)
[   50.302198] kvm_intel: Unknown symbol supported_xss (err -2)
[   50.308373] kvm_intel: Unknown symbol kvm_vcpu_map (err -2)
[   50.314458] kvm_intel: Unknown symbol kvm_msr_allowed (err -2)
[   50.320829] kvm_intel: Unknown symbol kvm_lapic_find_highest_irr (err -2)
[   50.328223] kvm_intel: Unknown symbol kvm_set_xcr (err -2)
[   50.334214] kvm_intel: Unknown symbol kvm_wait_lapic_expire (err -2)
[   50.341150] kvm_intel: Unknown symbol reprogram_gp_counter (err -2)
[   50.347991] kvm_intel: Unknown symbol kvm_write_guest_virt_system (err -2)
[   50.355491] kvm_intel: Unknown symbol kvm_find_cpuid_entry (err -2)
[   50.362327] kvm_intel: Unknown symbol kvm_task_switch (err -2)
[   50.368699] kvm_intel: Unknown symbol __SCT__tp_func_kvm_fast_mmio (err -2)
[   50.376295] kvm_intel: Unknown symbol kvm_read_guest_virt (err -2)
[   50.383036] kvm_intel: Unknown symbol kvm_vcpu_gfn_to_page (err -2)
[   50.389878] kvm_intel: Unknown symbol kvm_write_guest (err -2)
[   50.396245] kvm_intel: Unknown symbol __tracepoint_kvm_cr (err -2)
[   50.402991] kvm_intel: Unknown symbol kvm_io_bus_write (err -2)
[   50.409454] kvm_intel: Unknown symbol kvm_mmu_set_mmio_spte_mask (err -2)
[   50.416858] kvm_intel: Unknown symbol kvm_mmu_clear_dirty_pt_masked (err -2)
[   50.424543] kvm_intel: Unknown symbol kvm_set_user_return_msr (err -2)
[   50.431665] kvm_intel: Unknown symbol kvm_require_cpl (err -2)
[   50.438036] kvm_intel: Unknown symbol __SCT__tp_func_kvm_cr (err -2)
[   50.444968] kvm_intel: Unknown symbol kvm_init_shadow_ept_mmu (err -2)
[   50.452089] kvm_intel: Unknown symbol __tracepoint_kvm_pml_full (err -2)
[   50.459383] kvm_intel: Unknown symbol kvm_requeue_exception_e (err -2)
[   50.466499] kvm_intel: Unknown symbol kvm_lmsw (err -2)
[   50.472206] kvm_intel: Unknown symbol kvm_lapic_set_eoi (err -2)
[   50.478753] kvm_intel: Unknown symbol kvm_queue_exception (err -2)
[   50.485499] kvm_intel: Unknown symbol kvm_lapic_switch_to_hv_timer (err -2)
[   50.493097] kvm_intel: Unknown symbol kvm_emulate_rdmsr (err -2)
[   50.499653] kvm_intel: Unknown symbol __tracepoint_kvm_write_tsc_offset (err -2)
[   50.507725] kvm_intel: Unknown symbol kvm_vcpu_is_reset_bsp (err -2)
[   50.514654] kvm_intel: Unknown symbol __tracepoint_kvm_pi_irte_update (err -2)
[   50.522528] kvm_intel: Unknown symbol kvm_apicv_init (err -2)
[   50.528794] kvm_intel: Unknown symbol __SCT__tp_func_kvm_nested_vmexit_inject (err -2)
[   50.537425] kvm_intel: Unknown symbol kvm_vcpu_unmap (err -2)
[   50.543702] kvm_intel: Unknown symbol kvm_write_guest_page (err -2)
[   50.550542] kvm_intel: Unknown symbol kvm_valid_efer (err -2)
[   50.556810] kvm_intel: Unknown symbol supported_xcr0 (err -2)
[   50.563073] kvm_intel: Unknown symbol __SCK__tp_func_kvm_pi_irte_update (err -2)
[   50.571139] kvm_intel: Unknown symbol kvm_set_rflags (err -2)
[   50.577397] kvm_intel: Unknown symbol kvm_mmu_slot_leaf_clear_dirty (err -2)
[   50.585088] kvm_intel: Unknown symbol kvm_tsc_scaling_ratio_frac_bits (err -2)
[   50.592965] kvm_intel: Unknown symbol kvm_mce_cap_supported (err -2)
[   50.599898] kvm_intel: Unknown symbol kvm_handle_invpcid (err -2)
[   50.606553] kvm_intel: Unknown symbol kvm_load_host_xsave_state (err -2)
[   50.613866] kvm_intel: Unknown symbol __tracepoint_kvm_page_fault (err -2)
[   50.621367] kvm_intel: Unknown symbol kvm_mmu_free_roots (err -2)
[   50.628021] kvm_intel: Unknown symbol kvm_mmu_slot_set_dirty (err -2)
[   50.635036] kvm_intel: Unknown symbol kvm_queue_exception_p (err -2)
[   50.641967] kvm_intel: Unknown symbol kvm_read_l1_tsc (err -2)
[   50.648328] kvm_intel: Unknown symbol __tracepoint_kvm_inj_virq (err -2)
[   50.655639] kvm_intel: Unknown symbol kvm_cpu_has_interrupt (err -2)
[   50.662559] kvm_intel: Unknown symbol __kvm_apic_update_irr (err -2)
[   50.669493] kvm_intel: Unknown symbol handle_fastpath_set_msr_irqoff (err -2)
[   50.677274] kvm_intel: Unknown symbol kvm_apic_update_ppr (err -2)
[   50.684006] kvm_intel: Unknown symbol kvm_configure_mmu (err -2)
[   50.690556] kvm_intel: Unknown symbol kvm_apic_update_irr (err -2)
[   50.697302] kvm_intel: Unknown symbol kvm_init_mmu (err -2)
[   50.703385] kvm_intel: Unknown symbol kvm_emulate_wbinvd (err -2)
[   50.710020] kvm_intel: Unknown symbol kvm_set_cr3 (err -2)
[   50.716006] kvm_intel: Unknown symbol kvm_lapic_switch_to_sw_timer (err -2)
[   50.723602] kvm_intel: Unknown symbol __SCK__tp_func_kvm_page_fault (err -2)
[   50.731289] kvm_intel: Unknown symbol kvm_get_cr8 (err -2)
[   50.737277] kvm_intel: Unknown symbol kvm_x86_ops (err -2)
[   50.743273] kvm_intel: Unknown symbol __SCT__tp_func_kvm_pi_irte_update (err -2)
[   50.751332] kvm_intel: Unknown symbol vcpu_load (err -2)
[   50.757133] kvm_intel: Unknown symbol kvm_handle_memory_failure (err -2)
[   50.764445] kvm_intel: Unknown symbol kvm_set_dr (err -2)
[   50.770341] kvm_intel: Unknown symbol kvm_set_msi_irq (err -2)
[   50.776714] kvm_intel: Unknown symbol kvm_emulate_hypercall (err -2)
[   50.783649] kvm_intel: Unknown symbol kvm_spurious_fault (err -2)
[   50.790298] kvm_intel: Unknown symbol kvm_has_tsc_control (err -2)
[   50.797045] kvm_intel: Unknown symbol kvm_get_linear_rip (err -2)
[   50.803698] kvm_intel: Unknown symbol kvm_get_msr (err -2)
[   50.809683] kvm_intel: Unknown symbol load_pdptrs (err -2)
[   50.815676] kvm_intel: Unknown symbol kvm_get_running_vcpu (err -2)
[   50.822518] kvm_intel: Unknown symbol kvm_vcpu_read_guest_page (err -2)
[   50.829734] kvm_intel: Unknown symbol kvm_set_cpu_caps (err -2)
[   50.836198] kvm_intel: Unknown symbol kvm_vcpu_exit_request (err -2)
[   50.843129] kvm_intel: Unknown symbol host_efer (err -2)
[   50.848927] kvm_intel: Unknown symbol kvm_max_tsc_scaling_ratio (err -2)
[   50.856239] kvm_intel: Unknown symbol __SCT__tp_func_kvm_pml_full (err -2)
[   50.863742] kvm_intel: Unknown symbol pdptrs_changed (err -2)
[   50.870016] kvm_intel: Unknown symbol kvm_set_cr4 (err -2)
[   50.876008] kvm_intel: Unknown symbol __SCK__tp_func_kvm_exit (err -2)
[   50.883120] kvm_intel: Unknown symbol kvm_release_page_clean (err -2)
[   50.890148] kvm_intel: Unknown symbol kvm_handle_page_fault (err -2)
[   50.897082] kvm_intel: Unknown symbol kvm_cpu_caps (err -2)
[   50.903165] kvm_intel: Unknown symbol kvm_spec_ctrl_test_value (err -2)
[   50.910379] kvm_intel: Unknown symbol __SCT__tp_func_kvm_exit (err -2)
[   50.917491] kvm_intel: Unknown symbol kvm_apic_clear_irr (err -2)
[   50.924133] kvm_intel: Unknown symbol __x86_set_memory_region (err -2)
[   50.931253] kvm_intel: Unknown symbol kvm_load_guest_xsave_state (err -2)
[   50.938651] kvm_intel: Unknown symbol kvm_set_cr0 (err -2)
[   50.944647] kvm_intel: Unknown symbol kvm_set_cr8 (err -2)
[   50.950632] kvm_intel: Unknown symbol kvm_get_dr (err -2)
[   50.956536] kvm_intel: Unknown symbol kvm_mmu_page_fault (err -2)
[   50.963183] kvm_intel: Unknown symbol __SCK__tp_func_kvm_nested_vmexit (err -2)
[   50.971158] kvm_intel: Unknown symbol kvm_emulate_instruction (err -2)
[   50.978285] kvm_intel: Unknown symbol __SCK__tp_func_kvm_pml_full (err -2)
[   50.985780] kvm_intel: Unknown symbol kvm_mtrr_get_guest_memory_type (err -2)
[   50.993551] kvm_intel: Unknown symbol kvm_mmu_reset_context (err -2)
[   51.000474] kvm_intel: Unknown symbol kvm_get_apic_mode (err -2)
[   51.007035] kvm_intel: Unknown symbol kvm_vcpu_read_guest (err -2)
[   51.013759] kvm_intel: Unknown symbol kvm_vcpu_on_spin (err -2)
[   51.020223] kvm_intel: Unknown symbol __SCK__tp_func_kvm_fast_mmio (err -2)
[   51.027817] kvm_intel: Unknown symbol kvm_read_guest (err -2)
[   51.034092] kvm_intel: Unknown symbol kvm_define_user_return_msr (err -2)
[   51.041492] kvm_intel: Unknown symbol kvm_rebooting (err -2)
[   51.047670] kvm_intel: Unknown symbol kvm_get_rflags (err -2)
[   51.053942] kvm_intel: Unknown symbol kvm_queue_exception_e (err -2)
[   51.060876] kvm_intel: Unknown symbol __SCT__tp_func_kvm_inj_virq (err -2)
[   51.068378] kvm_intel: Unknown symbol current_vcpu (err -2)
[   51.074455] kvm_intel: Unknown symbol __SCT__tp_func_kvm_write_tsc_offset (err -2)
[   51.082710] kvm_intel: Unknown symbol __tracepoint_kvm_exit (err -2)
[   51.089643] kvm_intel: Unknown symbol kvm_emulate_cpuid (err -2)
[   51.096198] kvm_intel: Unknown symbol kvm_emulate_wrmsr (err -2)
[   51.102756] kvm_intel: Unknown symbol __SCK__tp_func_kvm_inj_virq (err -2)
[   51.110254] kvm_intel: Unknown symbol kvm_apic_set_eoi_accelerated (err -2)
[   51.117851] kvm_intel: Unknown symbol kvm_vcpu_kick (err -2)
[   51.124030] kvm_intel: Unknown symbol kvm_inject_realmode_interrupt (err -2)
[   51.131717] kvm_intel: Unknown symbol kvm_mmu_invlpg (err -2)
[   51.137991] kvm_intel: Unknown symbol kvm_fast_pio (err -2)
[   51.144078] kvm_intel: Unknown symbol __SCK__tp_func_kvm_ple_window_update (err -2)
[   51.152432] kvm_intel: Unknown symbol kvm_set_msr_common (err -2)
[   51.159081] kvm_intel: Unknown symbol __SCT__tp_func_kvm_nested_vmenter_failed (err -2)
[   51.167810] kvm_intel: Unknown symbol __SCK__tp_func_kvm_nested_vmexit_inject (err -2)
[   51.176448] kvm_intel: Unknown symbol kvm_intr_is_single_vcpu (err -2)
[   51.183572] kvm_intel: Unknown symbol kvm_apic_has_interrupt (err -2)
[   51.190589] kvm_intel: Unknown symbol __SCT__tp_func_kvm_ple_window_update (err -2)
[   51.198935] kvm_intel: Unknown symbol __SCK__tp_func_kvm_write_tsc_offset (err -2)
[   51.207191] kvm_intel: Unknown symbol __tracepoint_kvm_nested_vmexit_inject (err -2)
[   51.215635] kvm_intel: Unknown symbol __SCT__tp_func_kvm_page_fault (err -2)
[   51.223321] kvm_intel: Unknown symbol kvm_require_dr (err -2)
[   51.229594] kvm_intel: Unknown symbol kvm_skip_emulated_instruction (err -2)
[   51.237267] kvm_intel: Unknown symbol kvm_inject_page_fault (err -2)
[   51.244205] kvm_intel: Unknown symbol kvm_cpu_get_interrupt (err -2)
[   51.251131] kvm_intel: Unknown symbol kvm_vcpu_write_guest (err -2)
[   51.257967] kvm_intel: Unknown symbol kvm_complete_insn_gp (err -2)
[   51.264808] kvm_intel: Unknown symbol kvm_mmu_set_mask_ptes (err -2)
[   51.271742] kvm_intel: Unknown symbol kvm_apic_write_nodecode (err -2)
[   51.278866] kvm_intel: Unknown symbol kvm_lapic_hv_timer_in_use (err -2)
[   51.286181] kvm_intel: Unknown symbol allow_smaller_maxphyaddr (err -2)
[   51.298913] kvm_intel: Unknown symbol __tracepoint_kvm_ple_window_update (err -2)
[   51.307251] kvm_intel: Unknown symbol vcpu_put (err -2)
[   51.312953] kvm_intel: Unknown symbol kvm_arch_has_assigned_device (err -2)
[   51.320544] kvm_intel: Unknown symbol kvm_rdpmc (err -2)
[   51.326346] kvm_intel: Unknown symbol kvm_vcpu_mark_page_dirty (err -2)
[   51.333571] kvm_intel: Unknown symbol kvm_vcpu_halt (err -2)
[   51.339747] kvm_intel: Unknown symbol kvm_clear_guest_page (err -2)
[   51.346565] kvm_intel: Unknown symbol kvm_requeue_exception (err -2)
[   51.353497] kvm_intel: Unknown symbol reprogram_counter (err -2)
[   51.360058] kvm_intel: Unknown symbol __SCK__tp_func_kvm_nested_vmenter_failed (err -2)
[   51.368781] kvm_intel: Unknown symbol kvm_exit (err -2)
[   51.374486] kvm_intel: Unknown symbol kvm_init (err -2)
[   51.380199] kvm_intel: Unknown symbol kvm_deliver_exception_payload (err -2)
[   51.387886] kvm_intel: Unknown symbol kvm_set_msr (err -2)
[   51.393868] kvm_intel: Unknown symbol kvm_default_tsc_scaling_ratio (err -2)
[   51.401561] kvm_intel: Unknown symbol __tracepoint_kvm_nested_vmexit (err -2)
[   51.409347] kvm_intel: Unknown symbol enable_vmware_backdoor (err -2)
[   51.416369] kvm_intel: Unknown symbol kvm_enable_efer_bits (err -2)
[   51.423214] kvm_intel: Unknown symbol __SCT__tp_func_kvm_nested_vmexit (err -2)
[   51.431188] kvm_intel: Unknown symbol __kvm_request_immediate_exit (err -2)
[   51.438780] kvm_intel: Unknown symbol kvm_lapic_expired_hv_timer (err -2)
[   51.446182] kvm_intel: Unknown symbol kvm_fixup_and_inject_pf_error (err -2)
[   51.453878] kvm_intel: Unknown symbol gfn_to_page (err -2)
[   51.459869] kvm_intel: Unknown symbol __SCK__tp_func_kvm_cr (err -2)
[   51.466803] kvm_intel: Unknown symbol kvm_probe_user_return_msr (err -2)
[   51.474111] kvm_intel: Unknown symbol kvm_vcpu_write_guest_page (err -2)
[   51.481419] kvm_intel: Unknown symbol kvm_no_apic_vcpu (err -2)
[   51.487882] kvm_intel: Unknown symbol handle_ud (err -2)
[   51.493677] kvm_intel: Unknown symbol kvm_mmu_new_pgd (err -2)
[   51.500049] kvm_intel: Unknown symbol reprogram_fixed_counter (err -2)
[   51.507171] kvm_intel: Unknown symbol __tracepoint_kvm_nested_vmenter_failed (err -2)
[   51.515709] kvm_intel: Unknown symbol kvm_get_msr_common (err -2)
[   51.522349] kvm_intel: Unknown symbol kvm_mmu_slot_largepage_remove_write_access (err -2)
[   51.531263] kvm_intel: Unknown symbol __tracepoint_kvm_fast_mmio (err -2)
[   51.538667] kvm_intel: Unknown symbol kvm_arch_has_noncoherent_dma (err -2)
[   51.546261] kvm_intel: Unknown symbol kvm_hv_get_assist_page (err -2)
[   51.553277] kvm_intel: Unknown symbol kvm_emulate_halt (err -2)
[   51.559741] kvm_intel: Unknown symbol kvm_set_apic_base (err -2)
[   51.566299] kvm_intel: Unknown symbol supported_xss (err -2)
[   51.572475] kvm_intel: Unknown symbol kvm_vcpu_map (err -2)
[   51.578562] kvm_intel: Unknown symbol kvm_msr_allowed (err -2)
[   51.584927] kvm_intel: Unknown symbol kvm_lapic_find_highest_irr (err -2)
[   51.592327] kvm_intel: Unknown symbol kvm_set_xcr (err -2)
[   51.598314] kvm_intel: Unknown symbol kvm_wait_lapic_expire (err -2)
[   51.605251] kvm_intel: Unknown symbol reprogram_gp_counter (err -2)
[   51.612084] kvm_intel: Unknown symbol kvm_write_guest_virt_system (err -2)
[   51.619582] kvm_intel: Unknown symbol kvm_find_cpuid_entry (err -2)
[   51.626409] kvm_intel: Unknown symbol kvm_task_switch (err -2)
[   51.632779] kvm_intel: Unknown symbol __SCT__tp_func_kvm_fast_mmio (err -2)
[   51.640376] kvm_intel: Unknown symbol kvm_read_guest_virt (err -2)
[   51.647118] kvm_intel: Unknown symbol kvm_vcpu_gfn_to_page (err -2)
[   51.653948] kvm_intel: Unknown symbol kvm_write_guest (err -2)
[   51.660321] kvm_intel: Unknown symbol __tracepoint_kvm_cr (err -2)
[   51.667054] kvm_intel: Unknown symbol kvm_io_bus_write (err -2)
[   51.673517] kvm_intel: Unknown symbol kvm_mmu_set_mmio_spte_mask (err -2)
[   51.680925] kvm_intel: Unknown symbol kvm_mmu_clear_dirty_pt_masked (err -2)
[   51.688612] kvm_intel: Unknown symbol kvm_set_user_return_msr (err -2)
[   51.695734] kvm_intel: Unknown symbol kvm_require_cpl (err -2)
[   51.702108] kvm_intel: Unknown symbol __SCT__tp_func_kvm_cr (err -2)
[   51.709040] kvm_intel: Unknown symbol kvm_init_shadow_ept_mmu (err -2)
[   51.716162] kvm_intel: Unknown symbol __tracepoint_kvm_pml_full (err -2)
[   51.723464] kvm_intel: Unknown symbol kvm_requeue_exception_e (err -2)
[   51.730588] kvm_intel: Unknown symbol kvm_lmsw (err -2)
[   51.736293] kvm_intel: Unknown symbol kvm_lapic_set_eoi (err -2)
[   51.742851] kvm_intel: Unknown symbol kvm_queue_exception (err -2)
[   51.749596] kvm_intel: Unknown symbol kvm_lapic_switch_to_hv_timer (err -2)
[   51.757194] kvm_intel: Unknown symbol kvm_emulate_rdmsr (err -2)
[   51.763734] kvm_intel: Unknown symbol __tracepoint_kvm_write_tsc_offset (err -2)
[   51.771799] kvm_intel: Unknown symbol kvm_vcpu_is_reset_bsp (err -2)
[   51.778728] kvm_intel: Unknown symbol __tracepoint_kvm_pi_irte_update (err -2)
[   51.786602] kvm_intel: Unknown symbol kvm_apicv_init (err -2)
[   51.792882] kvm_intel: Unknown symbol __SCT__tp_func_kvm_nested_vmexit_inject (err -2)
[   51.801510] kvm_intel: Unknown symbol kvm_vcpu_unmap (err -2)
[   51.807752] kvm_intel: Unknown symbol kvm_write_guest_page (err -2)
[   51.814595] kvm_intel: Unknown symbol kvm_valid_efer (err -2)
[   51.820868] kvm_intel: Unknown symbol supported_xcr0 (err -2)
[   51.827138] kvm_intel: Unknown symbol __SCK__tp_func_kvm_pi_irte_update (err -2)
[   51.835209] kvm_intel: Unknown symbol kvm_set_rflags (err -2)
[   51.841482] kvm_intel: Unknown symbol kvm_mmu_slot_leaf_clear_dirty (err -2)
[   51.849171] kvm_intel: Unknown symbol kvm_tsc_scaling_ratio_frac_bits (err -2)
[   51.857051] kvm_intel: Unknown symbol kvm_mce_cap_supported (err -2)
[   51.863983] kvm_intel: Unknown symbol kvm_handle_invpcid (err -2)
[   51.870639] kvm_intel: Unknown symbol kvm_load_host_xsave_state (err -2)
[   51.877951] kvm_intel: Unknown symbol __tracepoint_kvm_page_fault (err -2)
[   51.885447] kvm_intel: Unknown symbol kvm_mmu_free_roots (err -2)
[   51.892100] kvm_intel: Unknown symbol kvm_mmu_slot_set_dirty (err -2)
[   51.899131] kvm_intel: Unknown symbol kvm_queue_exception_p (err -2)
[   51.906053] kvm_intel: Unknown symbol kvm_read_l1_tsc (err -2)
[   51.912428] kvm_intel: Unknown symbol __tracepoint_kvm_inj_virq (err -2)
[   51.919740] kvm_intel: Unknown symbol kvm_cpu_has_interrupt (err -2)
[   51.926670] kvm_intel: Unknown symbol __kvm_apic_update_irr (err -2)
[   51.933605] kvm_intel: Unknown symbol handle_fastpath_set_msr_irqoff (err -2)
[   51.941392] kvm_intel: Unknown symbol kvm_apic_update_ppr (err -2)
[   51.948121] kvm_intel: Unknown symbol kvm_configure_mmu (err -2)
[   51.954680] kvm_intel: Unknown symbol kvm_apic_update_irr (err -2)
[   51.961419] kvm_intel: Unknown symbol kvm_init_mmu (err -2)
[   51.967506] kvm_intel: Unknown symbol kvm_emulate_wbinvd (err -2)
[   51.974158] kvm_intel: Unknown symbol kvm_set_cr3 (err -2)
[   51.980141] kvm_intel: Unknown symbol kvm_lapic_switch_to_sw_timer (err -2)
[   51.987742] kvm_intel: Unknown symbol __SCK__tp_func_kvm_page_fault (err -2)
[   51.995427] kvm_intel: Unknown symbol kvm_get_cr8 (err -2)
[   52.001416] kvm_intel: Unknown symbol kvm_x86_ops (err -2)
[   52.007409] kvm_intel: Unknown symbol __SCT__tp_func_kvm_pi_irte_update (err -2)
[   52.015465] kvm_intel: Unknown symbol vcpu_load (err -2)
[   52.021268] kvm_intel: Unknown symbol kvm_handle_memory_failure (err -2)
[   52.028563] kvm_intel: Unknown symbol kvm_set_dr (err -2)
[   52.034458] kvm_intel: Unknown symbol kvm_set_msi_irq (err -2)
[   52.040829] kvm_intel: Unknown symbol kvm_emulate_hypercall (err -2)
[   52.047762] kvm_intel: Unknown symbol kvm_spurious_fault (err -2)
[   52.054415] kvm_intel: Unknown symbol kvm_has_tsc_control (err -2)
[   52.061157] kvm_intel: Unknown symbol kvm_get_linear_rip (err -2)
[   52.067811] kvm_intel: Unknown symbol kvm_get_msr (err -2)
[   52.073800] kvm_intel: Unknown symbol load_pdptrs (err -2)
[   52.079790] kvm_intel: Unknown symbol kvm_get_running_vcpu (err -2)
[   52.086633] kvm_intel: Unknown symbol kvm_vcpu_read_guest_page (err -2)
[   52.093845] kvm_intel: Unknown symbol kvm_set_cpu_caps (err -2)
[   52.100308] kvm_intel: Unknown symbol kvm_vcpu_exit_request (err -2)
[   52.107231] kvm_intel: Unknown symbol host_efer (err -2)
[   52.113027] kvm_intel: Unknown symbol kvm_max_tsc_scaling_ratio (err -2)
[   52.120324] kvm_intel: Unknown symbol __SCT__tp_func_kvm_pml_full (err -2)
[   52.127824] kvm_intel: Unknown symbol pdptrs_changed (err -2)
[   52.134100] kvm_intel: Unknown symbol kvm_set_cr4 (err -2)
[   52.140080] kvm_intel: Unknown symbol __SCK__tp_func_kvm_exit (err -2)
[   52.147185] kvm_intel: Unknown symbol kvm_release_page_clean (err -2)
[   52.154216] kvm_intel: Unknown symbol kvm_handle_page_fault (err -2)
[   52.161150] kvm_intel: Unknown symbol kvm_cpu_caps (err -2)
[   52.167236] kvm_intel: Unknown symbol kvm_spec_ctrl_test_value (err -2)
[   52.174456] kvm_intel: Unknown symbol __SCT__tp_func_kvm_exit (err -2)
[   52.181576] kvm_intel: Unknown symbol kvm_apic_clear_irr (err -2)
[   52.188232] kvm_intel: Unknown symbol __x86_set_memory_region (err -2)
[   52.195343] kvm_intel: Unknown symbol kvm_load_guest_xsave_state (err -2)
[   52.202752] kvm_intel: Unknown symbol kvm_set_cr0 (err -2)
[   52.208740] kvm_intel: Unknown symbol kvm_set_cr8 (err -2)
[   52.214729] kvm_intel: Unknown symbol kvm_get_dr (err -2)
[   52.220628] kvm_intel: Unknown symbol kvm_mmu_page_fault (err -2)
[   52.227284] kvm_intel: Unknown symbol __SCK__tp_func_kvm_nested_vmexit (err -2)
[   52.235255] kvm_intel: Unknown symbol kvm_emulate_instruction (err -2)
[   52.242380] kvm_intel: Unknown symbol __SCK__tp_func_kvm_pml_full (err -2)
[   52.249866] kvm_intel: Unknown symbol kvm_mtrr_get_guest_memory_type (err -2)
[   52.257640] kvm_intel: Unknown symbol kvm_mmu_reset_context (err -2)
[   52.264572] kvm_intel: Unknown symbol kvm_get_apic_mode (err -2)
[   52.271133] kvm_intel: Unknown symbol kvm_vcpu_read_guest (err -2)
[   52.277858] kvm_intel: Unknown symbol kvm_vcpu_on_spin (err -2)
[   52.284323] kvm_intel: Unknown symbol __SCK__tp_func_kvm_fast_mmio (err -2)
[   52.291908] kvm_intel: Unknown symbol kvm_read_guest (err -2)
[   52.298174] kvm_intel: Unknown symbol kvm_define_user_return_msr (err -2)
[   52.305582] kvm_intel: Unknown symbol kvm_rebooting (err -2)
[   52.311761] kvm_intel: Unknown symbol kvm_get_rflags (err -2)
[   52.318042] kvm_intel: Unknown symbol kvm_queue_exception_e (err -2)
[   52.326326] kvm_intel: Unknown symbol __SCT__tp_func_kvm_inj_virq (err -2)
[   52.333825] kvm_intel: Unknown symbol current_vcpu (err -2)
[   52.339914] kvm_intel: Unknown symbol __SCT__tp_func_kvm_write_tsc_offset (err -2)
[   52.348169] kvm_intel: Unknown symbol __tracepoint_kvm_exit (err -2)
[   52.355101] kvm_intel: Unknown symbol kvm_emulate_cpuid (err -2)
[   52.361652] kvm_intel: Unknown symbol kvm_emulate_wrmsr (err -2)
[   52.368209] kvm_intel: Unknown symbol __SCK__tp_func_kvm_inj_virq (err -2)
[   52.375712] kvm_intel: Unknown symbol kvm_apic_set_eoi_accelerated (err -2)
[   52.383297] kvm_intel: Unknown symbol kvm_vcpu_kick (err -2)
[   52.389478] kvm_intel: Unknown symbol kvm_inject_realmode_interrupt (err -2)
[   52.397166] kvm_intel: Unknown symbol kvm_mmu_invlpg (err -2)
[   52.403427] kvm_intel: Unknown symbol kvm_fast_pio (err -2)
[   52.409515] kvm_intel: Unknown symbol __SCK__tp_func_kvm_ple_window_update (err -2)
[   52.417865] kvm_intel: Unknown symbol kvm_set_msr_common (err -2)
[   52.424517] kvm_intel: Unknown symbol __SCT__tp_func_kvm_nested_vmenter_failed (err -2)
[   52.433235] kvm_intel: Unknown symbol __SCK__tp_func_kvm_nested_vmexit_inject (err -2)
[   52.441871] kvm_intel: Unknown symbol kvm_intr_is_single_vcpu (err -2)
[   52.448986] kvm_intel: Unknown symbol kvm_apic_has_interrupt (err -2)
[   52.456018] kvm_intel: Unknown symbol __SCT__tp_func_kvm_ple_window_update (err -2)
[   52.464359] kvm_intel: Unknown symbol __SCK__tp_func_kvm_write_tsc_offset (err -2)
[   52.472612] kvm_intel: Unknown symbol __tracepoint_kvm_nested_vmexit_inject (err -2)
[   52.481048] kvm_intel: Unknown symbol __SCT__tp_func_kvm_page_fault (err -2)
[   52.488736] kvm_intel: Unknown symbol kvm_require_dr (err -2)
[   52.495010] kvm_intel: Unknown symbol kvm_skip_emulated_instruction (err -2)
[   52.502699] kvm_intel: Unknown symbol kvm_inject_page_fault (err -2)
[   52.509627] kvm_intel: Unknown symbol kvm_cpu_get_interrupt (err -2)
[   52.516562] kvm_intel: Unknown symbol kvm_vcpu_write_guest (err -2)
[   52.523401] kvm_intel: Unknown symbol kvm_complete_insn_gp (err -2)
[   52.530241] kvm_intel: Unknown symbol kvm_mmu_set_mask_ptes (err -2)
[   52.537177] kvm_intel: Unknown symbol kvm_apic_write_nodecode (err -2)
[   52.544300] kvm_intel: Unknown symbol kvm_lapic_hv_timer_in_use (err -2)
[   52.551607] kvm_intel: Unknown symbol allow_smaller_maxphyaddr (err -2)
[   52.564835] kvm_intel: Unknown symbol __tracepoint_kvm_ple_window_update (err -2)
[   52.574192] kvm_intel: Unknown symbol vcpu_put (err -2)
[   52.579896] kvm_intel: Unknown symbol kvm_arch_has_assigned_device (err -2)
[   52.587486] kvm_intel: Unknown symbol kvm_rdpmc (err -2)
[   52.593283] kvm_intel: Unknown symbol kvm_vcpu_mark_page_dirty (err -2)
[   52.600507] kvm_intel: Unknown symbol kvm_vcpu_halt (err -2)
[   52.606672] kvm_intel: Unknown symbol kvm_clear_guest_page (err -2)
[   52.613501] kvm_intel: Unknown symbol kvm_requeue_exception (err -2)
[   52.620442] kvm_intel: Unknown symbol reprogram_counter (err -2)
[   52.626998] kvm_intel: Unknown symbol __SCK__tp_func_kvm_nested_vmenter_failed (err -2)
[   52.635727] kvm_intel: Unknown symbol kvm_exit (err -2)
[   52.641423] kvm_intel: Unknown symbol kvm_init (err -2)
[   52.647122] kvm_intel: Unknown symbol kvm_deliver_exception_payload (err -2)
[   52.654812] kvm_intel: Unknown symbol kvm_set_msr (err -2)
[   52.660790] kvm_intel: Unknown symbol kvm_default_tsc_scaling_ratio (err -2)
[   52.668484] kvm_intel: Unknown symbol __tracepoint_kvm_nested_vmexit (err -2)
[   52.676270] kvm_intel: Unknown symbol enable_vmware_backdoor (err -2)
[   52.683292] kvm_intel: Unknown symbol kvm_enable_efer_bits (err -2)
[   52.690127] kvm_intel: Unknown symbol __SCT__tp_func_kvm_nested_vmexit (err -2)
[   52.698089] kvm_intel: Unknown symbol __kvm_request_immediate_exit (err -2)
[   52.705686] kvm_intel: Unknown symbol kvm_lapic_expired_hv_timer (err -2)
[   52.713090] kvm_intel: Unknown symbol kvm_fixup_and_inject_pf_error (err -2)
[   52.720781] kvm_intel: Unknown symbol gfn_to_page (err -2)
[   52.726773] kvm_intel: Unknown symbol __SCK__tp_func_kvm_cr (err -2)
[   52.733704] kvm_intel: Unknown symbol kvm_probe_user_return_msr (err -2)
[   52.741016] kvm_intel: Unknown symbol kvm_vcpu_write_guest_page (err -2)
[   52.748329] kvm_intel: Unknown symbol kvm_no_apic_vcpu (err -2)
[   52.754779] kvm_intel: Unknown symbol handle_ud (err -2)
[   52.760576] kvm_intel: Unknown symbol kvm_mmu_new_pgd (err -2)
[   52.766943] kvm_intel: Unknown symbol reprogram_fixed_counter (err -2)
[   52.774066] kvm_intel: Unknown symbol __tracepoint_kvm_nested_vmenter_failed (err -2)
[   52.782602] kvm_intel: Unknown symbol kvm_get_msr_common (err -2)
[   52.789257] kvm_intel: Unknown symbol kvm_mmu_slot_largepage_remove_write_access (err -2)
[   52.798175] kvm_intel: Unknown symbol __tracepoint_kvm_fast_mmio (err -2)
[   52.805581] kvm_intel: Unknown symbol kvm_arch_has_noncoherent_dma (err -2)
[   52.813173] kvm_intel: Unknown symbol kvm_hv_get_assist_page (err -2)
[   52.820204] kvm_intel: Unknown symbol kvm_emulate_halt (err -2)
[   52.826664] kvm_intel: Unknown symbol kvm_set_apic_base (err -2)
[   52.833226] kvm_intel: Unknown symbol supported_xss (err -2)
[   52.839403] kvm_intel: Unknown symbol kvm_vcpu_map (err -2)
[   52.845479] kvm_intel: Unknown symbol kvm_msr_allowed (err -2)
[   52.851848] kvm_intel: Unknown symbol kvm_lapic_find_highest_irr (err -2)
[   52.859254] kvm_intel: Unknown symbol kvm_set_xcr (err -2)
[   52.865232] kvm_intel: Unknown symbol kvm_wait_lapic_expire (err -2)
[   52.872171] kvm_intel: Unknown symbol reprogram_gp_counter (err -2)
[   52.879013] kvm_intel: Unknown symbol kvm_write_guest_virt_system (err -2)
[   52.886508] kvm_intel: Unknown symbol kvm_find_cpuid_entry (err -2)
[   52.893350] kvm_intel: Unknown symbol kvm_task_switch (err -2)
[   52.899717] kvm_intel: Unknown symbol __SCT__tp_func_kvm_fast_mmio (err -2)
[   52.907312] kvm_intel: Unknown symbol kvm_read_guest_virt (err -2)
[   52.914056] kvm_intel: Unknown symbol kvm_vcpu_gfn_to_page (err -2)
[   52.920898] kvm_intel: Unknown symbol kvm_write_guest (err -2)
[   52.927267] kvm_intel: Unknown symbol __tracepoint_kvm_cr (err -2)
[   52.934009] kvm_intel: Unknown symbol kvm_io_bus_write (err -2)
[   52.940473] kvm_intel: Unknown symbol kvm_mmu_set_mmio_spte_mask (err -2)
[   52.947879] kvm_intel: Unknown symbol kvm_mmu_clear_dirty_pt_masked (err -2)
[   52.955568] kvm_intel: Unknown symbol kvm_set_user_return_msr (err -2)
[   52.962692] kvm_intel: Unknown symbol kvm_require_cpl (err -2)
[   52.969061] kvm_intel: Unknown symbol __SCT__tp_func_kvm_cr (err -2)
[   52.975989] kvm_intel: Unknown symbol kvm_init_shadow_ept_mmu (err -2)
[   52.983117] kvm_intel: Unknown symbol __tracepoint_kvm_pml_full (err -2)
[   52.990428] kvm_intel: Unknown symbol kvm_requeue_exception_e (err -2)
[   52.997551] kvm_intel: Unknown symbol kvm_lmsw (err -2)
[   53.003239] kvm_intel: Unknown symbol kvm_lapic_set_eoi (err -2)
[   53.009794] kvm_intel: Unknown symbol kvm_queue_exception (err -2)
[   53.016539] kvm_intel: Unknown symbol kvm_lapic_switch_to_hv_timer (err -2)
[   53.024122] kvm_intel: Unknown symbol kvm_emulate_rdmsr (err -2)
[   53.030677] kvm_intel: Unknown symbol __tracepoint_kvm_write_tsc_offset (err -2)
[   53.038744] kvm_intel: Unknown symbol kvm_vcpu_is_reset_bsp (err -2)
[   53.045669] kvm_intel: Unknown symbol __tracepoint_kvm_pi_irte_update (err -2)
[   53.053545] kvm_intel: Unknown symbol kvm_apicv_init (err -2)
[   53.059820] kvm_intel: Unknown symbol __SCT__tp_func_kvm_nested_vmexit_inject (err -2)
[   53.068450] kvm_intel: Unknown symbol kvm_vcpu_unmap (err -2)
[   53.074727] kvm_intel: Unknown symbol kvm_write_guest_page (err -2)
[   53.081568] kvm_intel: Unknown symbol kvm_valid_efer (err -2)
[   53.087842] kvm_intel: Unknown symbol supported_xcr0 (err -2)
[   53.094104] kvm_intel: Unknown symbol __SCK__tp_func_kvm_pi_irte_update (err -2)
[   53.102170] kvm_intel: Unknown symbol kvm_set_rflags (err -2)
[   53.108444] kvm_intel: Unknown symbol kvm_mmu_slot_leaf_clear_dirty (err -2)
[   53.116128] kvm_intel: Unknown symbol kvm_tsc_scaling_ratio_frac_bits (err -2)
[   53.124006] kvm_intel: Unknown symbol kvm_mce_cap_supported (err -2)
[   53.130936] kvm_intel: Unknown symbol kvm_handle_invpcid (err -2)
[   53.137590] kvm_intel: Unknown symbol kvm_load_host_xsave_state (err -2)
[   53.144893] kvm_intel: Unknown symbol __tracepoint_kvm_page_fault (err -2)
[   53.152394] kvm_intel: Unknown symbol kvm_mmu_free_roots (err -2)
[   53.159046] kvm_intel: Unknown symbol kvm_mmu_slot_set_dirty (err -2)
[   53.166064] kvm_intel: Unknown symbol kvm_queue_exception_p (err -2)
[   53.172988] kvm_intel: Unknown symbol kvm_read_l1_tsc (err -2)
[   53.179359] kvm_intel: Unknown symbol __tracepoint_kvm_inj_virq (err -2)
[   53.186671] kvm_intel: Unknown symbol kvm_cpu_has_interrupt (err -2)
[   53.193607] kvm_intel: Unknown symbol __kvm_apic_update_irr (err -2)
[   53.200537] kvm_intel: Unknown symbol handle_fastpath_set_msr_irqoff (err -2)
[   53.208320] kvm_intel: Unknown symbol kvm_apic_update_ppr (err -2)
[   53.215061] kvm_intel: Unknown symbol kvm_configure_mmu (err -2)
[   53.221621] kvm_intel: Unknown symbol kvm_apic_update_irr (err -2)
[   53.228362] kvm_intel: Unknown symbol kvm_init_mmu (err -2)
[   53.234445] kvm_intel: Unknown symbol kvm_emulate_wbinvd (err -2)
[   53.241077] kvm_intel: Unknown symbol kvm_set_cr3 (err -2)
[   53.247070] kvm_intel: Unknown symbol kvm_lapic_switch_to_sw_timer (err -2)
[   53.254668] kvm_intel: Unknown symbol __SCK__tp_func_kvm_page_fault (err -2)
[   53.262357] kvm_intel: Unknown symbol kvm_get_cr8 (err -2)
[   53.268344] kvm_intel: Unknown symbol kvm_x86_ops (err -2)
[   53.274337] kvm_intel: Unknown symbol __SCT__tp_func_kvm_pi_irte_update (err -2)
[   53.282398] kvm_intel: Unknown symbol vcpu_load (err -2)
[   53.288191] kvm_intel: Unknown symbol kvm_handle_memory_failure (err -2)
[   53.295503] kvm_intel: Unknown symbol kvm_set_dr (err -2)
[   53.301387] kvm_intel: Unknown symbol kvm_set_msi_irq (err -2)
[   53.307758] kvm_intel: Unknown symbol kvm_emulate_hypercall (err -2)
[   53.314691] kvm_intel: Unknown symbol kvm_spurious_fault (err -2)
[   53.321344] kvm_intel: Unknown symbol kvm_has_tsc_control (err -2)
[   53.328088] kvm_intel: Unknown symbol kvm_get_linear_rip (err -2)
[   53.334742] kvm_intel: Unknown symbol kvm_get_msr (err -2)
[   53.340731] kvm_intel: Unknown symbol load_pdptrs (err -2)
[   53.346728] kvm_intel: Unknown symbol kvm_get_running_vcpu (err -2)
[   53.353561] kvm_intel: Unknown symbol kvm_vcpu_read_guest_page (err -2)
[   53.360778] kvm_intel: Unknown symbol kvm_set_cpu_caps (err -2)
[   53.367238] kvm_intel: Unknown symbol kvm_vcpu_exit_request (err -2)
[   53.374177] kvm_intel: Unknown symbol host_efer (err -2)
[   53.379973] kvm_intel: Unknown symbol kvm_max_tsc_scaling_ratio (err -2)
[   53.387288] kvm_intel: Unknown symbol __SCT__tp_func_kvm_pml_full (err -2)
[   53.394778] kvm_intel: Unknown symbol pdptrs_changed (err -2)
[   53.401049] kvm_intel: Unknown symbol kvm_set_cr4 (err -2)
[   53.407042] kvm_intel: Unknown symbol __SCK__tp_func_kvm_exit (err -2)
[   53.414153] kvm_intel: Unknown symbol kvm_release_page_clean (err -2)
[   53.421182] kvm_intel: Unknown symbol kvm_handle_page_fault (err -2)
[   53.428114] kvm_intel: Unknown symbol kvm_cpu_caps (err -2)
[   53.434185] kvm_intel: Unknown symbol kvm_spec_ctrl_test_value (err -2)
[   53.441391] kvm_intel: Unknown symbol __SCT__tp_func_kvm_exit (err -2)
[   53.448517] kvm_intel: Unknown symbol kvm_apic_clear_irr (err -2)
[   53.455169] kvm_intel: Unknown symbol __x86_set_memory_region (err -2)
[   53.462291] kvm_intel: Unknown symbol kvm_load_guest_xsave_state (err -2)
[   53.469696] kvm_intel: Unknown symbol kvm_set_cr0 (err -2)
[   53.475679] kvm_intel: Unknown symbol kvm_set_cr8 (err -2)
[   53.481667] kvm_intel: Unknown symbol kvm_get_dr (err -2)
[   53.487556] kvm_intel: Unknown symbol kvm_mmu_page_fault (err -2)
[   53.494206] kvm_intel: Unknown symbol __SCK__tp_func_kvm_nested_vmexit (err -2)
[   53.502173] kvm_intel: Unknown symbol kvm_emulate_instruction (err -2)
[   53.509285] kvm_intel: Unknown symbol __SCK__tp_func_kvm_pml_full (err -2)
[   53.516772] kvm_intel: Unknown symbol kvm_mtrr_get_guest_memory_type (err -2)
[   53.524559] kvm_intel: Unknown symbol kvm_mmu_reset_context (err -2)
[   53.531492] kvm_intel: Unknown symbol kvm_get_apic_mode (err -2)
[   53.538051] kvm_intel: Unknown symbol kvm_vcpu_read_guest (err -2)
[   53.544792] kvm_intel: Unknown symbol kvm_vcpu_on_spin (err -2)
[   53.551250] kvm_intel: Unknown symbol __SCK__tp_func_kvm_fast_mmio (err -2)
[   53.558835] kvm_intel: Unknown symbol kvm_read_guest (err -2)
[   53.565110] kvm_intel: Unknown symbol kvm_define_user_return_msr (err -2)
[   53.572516] kvm_intel: Unknown symbol kvm_rebooting (err -2)
[   53.578690] kvm_intel: Unknown symbol kvm_get_rflags (err -2)
[   53.584965] kvm_intel: Unknown symbol kvm_queue_exception_e (err -2)
[   53.591904] kvm_intel: Unknown symbol __SCT__tp_func_kvm_inj_virq (err -2)
[   53.599404] kvm_intel: Unknown symbol current_vcpu (err -2)
[   53.605487] kvm_intel: Unknown symbol __SCT__tp_func_kvm_write_tsc_offset (err -2)
[   53.613742] kvm_intel: Unknown symbol __tracepoint_kvm_exit (err -2)
[   53.620678] kvm_intel: Unknown symbol kvm_emulate_cpuid (err -2)
[   53.627232] kvm_intel: Unknown symbol kvm_emulate_wrmsr (err -2)
[   53.633791] kvm_intel: Unknown symbol __SCK__tp_func_kvm_inj_virq (err -2)
[   53.641289] kvm_intel: Unknown symbol kvm_apic_set_eoi_accelerated (err -2)
[   53.648885] kvm_intel: Unknown symbol kvm_vcpu_kick (err -2)
[   53.655061] kvm_intel: Unknown symbol kvm_inject_realmode_interrupt (err -2)
[   53.662749] kvm_intel: Unknown symbol kvm_mmu_invlpg (err -2)
[   53.669007] kvm_intel: Unknown symbol kvm_fast_pio (err -2)
[   53.675081] kvm_intel: Unknown symbol __SCK__tp_func_kvm_ple_window_update (err -2)
[   53.683430] kvm_intel: Unknown symbol kvm_set_msr_common (err -2)
[   53.690083] kvm_intel: Unknown symbol __SCT__tp_func_kvm_nested_vmenter_failed (err -2)
[   53.698812] kvm_intel: Unknown symbol __SCK__tp_func_kvm_nested_vmexit_inject (err -2)
[   53.707442] kvm_intel: Unknown symbol kvm_intr_is_single_vcpu (err -2)
[   53.714565] kvm_intel: Unknown symbol kvm_apic_has_interrupt (err -2)
[   53.721595] kvm_intel: Unknown symbol __SCT__tp_func_kvm_ple_window_update (err -2)
[   53.729946] kvm_intel: Unknown symbol __SCK__tp_func_kvm_write_tsc_offset (err -2)
[   53.738204] kvm_intel: Unknown symbol __tracepoint_kvm_nested_vmexit_inject (err -2)
[   53.746644] kvm_intel: Unknown symbol __SCT__tp_func_kvm_page_fault (err -2)
[   53.754338] kvm_intel: Unknown symbol kvm_require_dr (err -2)
[   53.760609] kvm_intel: Unknown symbol kvm_skip_emulated_instruction (err -2)
[   53.768298] kvm_intel: Unknown symbol kvm_inject_page_fault (err -2)
[   53.775231] kvm_intel: Unknown symbol kvm_cpu_get_interrupt (err -2)
[   53.782167] kvm_intel: Unknown symbol kvm_vcpu_write_guest (err -2)
[   53.789005] kvm_intel: Unknown symbol kvm_complete_insn_gp (err -2)
[   53.795837] kvm_intel: Unknown symbol kvm_mmu_set_mask_ptes (err -2)
[   53.802772] kvm_intel: Unknown symbol kvm_apic_write_nodecode (err -2)
[   53.809885] kvm_intel: Unknown symbol kvm_lapic_hv_timer_in_use (err -2)
[   53.817200] kvm_intel: Unknown symbol allow_smaller_maxphyaddr (err -2)
[   53.833921] kvm_intel: Unknown symbol __tracepoint_kvm_ple_window_update (err -2)
[   53.842636] kvm_intel: Unknown symbol vcpu_put (err -2)
[   53.848324] kvm_intel: Unknown symbol kvm_arch_has_assigned_device (err -2)
[   53.855917] kvm_intel: Unknown symbol kvm_rdpmc (err -2)
[   53.861710] kvm_intel: Unknown symbol kvm_vcpu_mark_page_dirty (err -2)
[   53.868932] kvm_intel: Unknown symbol kvm_vcpu_halt (err -2)
[   53.875105] kvm_intel: Unknown symbol kvm_clear_guest_page (err -2)
[   53.881945] kvm_intel: Unknown symbol kvm_requeue_exception (err -2)
[   53.888886] kvm_intel: Unknown symbol reprogram_counter (err -2)
[   53.895440] kvm_intel: Unknown symbol __SCK__tp_func_kvm_nested_vmenter_failed (err -2)
[   53.904155] kvm_intel: Unknown symbol kvm_exit (err -2)
[   53.909851] kvm_intel: Unknown symbol kvm_init (err -2)
[   53.915561] kvm_intel: Unknown symbol kvm_deliver_exception_payload (err -2)
[   53.923245] kvm_intel: Unknown symbol kvm_set_msr (err -2)
[   53.929214] kvm_intel: Unknown symbol kvm_default_tsc_scaling_ratio (err -2)
[   53.936893] kvm_intel: Unknown symbol __tracepoint_kvm_nested_vmexit (err -2)
[   53.944677] kvm_intel: Unknown symbol enable_vmware_backdoor (err -2)
[   53.951704] kvm_intel: Unknown symbol kvm_enable_efer_bits (err -2)
[   53.958548] kvm_intel: Unknown symbol __SCT__tp_func_kvm_nested_vmexit (err -2)
[   53.966512] kvm_intel: Unknown symbol __kvm_request_immediate_exit (err -2)
[   53.974102] kvm_intel: Unknown symbol kvm_lapic_expired_hv_timer (err -2)
[   53.981499] kvm_intel: Unknown symbol kvm_fixup_and_inject_pf_error (err -2)
[   53.989188] kvm_intel: Unknown symbol gfn_to_page (err -2)
[   53.995162] kvm_intel: Unknown symbol __SCK__tp_func_kvm_cr (err -2)
[   54.002093] kvm_intel: Unknown symbol kvm_probe_user_return_msr (err -2)
[   54.009398] kvm_intel: Unknown symbol kvm_vcpu_write_guest_page (err -2)
[   54.016713] kvm_intel: Unknown symbol kvm_no_apic_vcpu (err -2)
[   54.023173] kvm_intel: Unknown symbol handle_ud (err -2)
[   54.028973] kvm_intel: Unknown symbol kvm_mmu_new_pgd (err -2)
[   54.035314] kvm_intel: Unknown symbol reprogram_fixed_counter (err -2)
[   54.042440] kvm_intel: Unknown symbol __tracepoint_kvm_nested_vmenter_failed (err -2)
[   54.050975] kvm_intel: Unknown symbol kvm_get_msr_common (err -2)
[   54.057628] kvm_intel: Unknown symbol kvm_mmu_slot_largepage_remove_write_access (err -2)
[   54.066548] kvm_intel: Unknown symbol __tracepoint_kvm_fast_mmio (err -2)
[   54.073941] kvm_intel: Unknown symbol kvm_arch_has_noncoherent_dma (err -2)
[   54.081537] kvm_intel: Unknown symbol kvm_hv_get_assist_page (err -2)
[   54.088548] kvm_intel: Unknown symbol kvm_emulate_halt (err -2)
[   54.095009] kvm_intel: Unknown symbol kvm_set_apic_base (err -2)
[   54.101554] kvm_intel: Unknown symbol supported_xss (err -2)
[   54.107728] kvm_intel: Unknown symbol kvm_vcpu_map (err -2)
[   54.113798] kvm_intel: Unknown symbol kvm_msr_allowed (err -2)
[   54.120159] kvm_intel: Unknown symbol kvm_lapic_find_highest_irr (err -2)
[   54.127565] kvm_intel: Unknown symbol kvm_set_xcr (err -2)
[   54.133555] kvm_intel: Unknown symbol kvm_wait_lapic_expire (err -2)
[   54.140483] kvm_intel: Unknown symbol reprogram_gp_counter (err -2)
[   54.147323] kvm_intel: Unknown symbol kvm_write_guest_virt_system (err -2)
[   54.154813] kvm_intel: Unknown symbol kvm_find_cpuid_entry (err -2)
[   54.161626] kvm_intel: Unknown symbol kvm_task_switch (err -2)
[   54.167970] kvm_intel: Unknown symbol __SCT__tp_func_kvm_fast_mmio (err -2)
[   54.175568] kvm_intel: Unknown symbol kvm_read_guest_virt (err -2)
[   54.182311] kvm_intel: Unknown symbol kvm_vcpu_gfn_to_page (err -2)
[   54.189141] kvm_intel: Unknown symbol kvm_write_guest (err -2)
[   54.195497] kvm_intel: Unknown symbol __tracepoint_kvm_cr (err -2)
[   54.202237] kvm_intel: Unknown symbol kvm_io_bus_write (err -2)
[   54.208694] kvm_intel: Unknown symbol kvm_mmu_set_mmio_spte_mask (err -2)
[   54.216072] kvm_intel: Unknown symbol kvm_mmu_clear_dirty_pt_masked (err -2)
[   54.223729] kvm_intel: Unknown symbol kvm_set_user_return_msr (err -2)
[   54.230851] kvm_intel: Unknown symbol kvm_require_cpl (err -2)
[   54.237208] kvm_intel: Unknown symbol __SCT__tp_func_kvm_cr (err -2)
[   54.244131] kvm_intel: Unknown symbol kvm_init_shadow_ept_mmu (err -2)
[   54.251251] kvm_intel: Unknown symbol __tracepoint_kvm_pml_full (err -2)
[   54.258550] kvm_intel: Unknown symbol kvm_requeue_exception_e (err -2)
[   54.265664] kvm_intel: Unknown symbol kvm_lmsw (err -2)
[   54.271359] kvm_intel: Unknown symbol kvm_lapic_set_eoi (err -2)
[   54.277902] kvm_intel: Unknown symbol kvm_queue_exception (err -2)
[   54.284646] kvm_intel: Unknown symbol kvm_lapic_switch_to_hv_timer (err -2)
[   54.292224] kvm_intel: Unknown symbol kvm_emulate_rdmsr (err -2)
[   54.298784] kvm_intel: Unknown symbol __tracepoint_kvm_write_tsc_offset (err -2)
[   54.306852] kvm_intel: Unknown symbol kvm_vcpu_is_reset_bsp (err -2)
[   54.313783] kvm_intel: Unknown symbol __tracepoint_kvm_pi_irte_update (err -2)
[   54.321662] kvm_intel: Unknown symbol kvm_apicv_init (err -2)
[   54.327922] kvm_intel: Unknown symbol __SCT__tp_func_kvm_nested_vmexit_inject (err -2)
[   54.336554] kvm_intel: Unknown symbol kvm_vcpu_unmap (err -2)
[   54.342827] kvm_intel: Unknown symbol kvm_write_guest_page (err -2)
[   54.349660] kvm_intel: Unknown symbol kvm_valid_efer (err -2)
[   54.355931] kvm_intel: Unknown symbol supported_xcr0 (err -2)
[   54.362204] kvm_intel: Unknown symbol __SCK__tp_func_kvm_pi_irte_update (err -2)
[   54.370275] kvm_intel: Unknown symbol kvm_set_rflags (err -2)
[   54.376547] kvm_intel: Unknown symbol kvm_mmu_slot_leaf_clear_dirty (err -2)
[   54.384227] kvm_intel: Unknown symbol kvm_tsc_scaling_ratio_frac_bits (err -2)
[   54.392098] kvm_intel: Unknown symbol kvm_mce_cap_supported (err -2)
[   54.399020] kvm_intel: Unknown symbol kvm_handle_invpcid (err -2)
[   54.405645] kvm_intel: Unknown symbol kvm_load_host_xsave_state (err -2)
[   54.412960] kvm_intel: Unknown symbol __tracepoint_kvm_page_fault (err -2)
[   54.420457] kvm_intel: Unknown symbol kvm_mmu_free_roots (err -2)
[   54.427093] kvm_intel: Unknown symbol kvm_mmu_slot_set_dirty (err -2)
[   54.434123] kvm_intel: Unknown symbol kvm_queue_exception_p (err -2)
[   54.441056] kvm_intel: Unknown symbol kvm_read_l1_tsc (err -2)
[   54.447409] kvm_intel: Unknown symbol __tracepoint_kvm_inj_virq (err -2)
[   54.454718] kvm_intel: Unknown symbol kvm_cpu_has_interrupt (err -2)
[   54.461637] kvm_intel: Unknown symbol __kvm_apic_update_irr (err -2)
[   54.468570] kvm_intel: Unknown symbol handle_fastpath_set_msr_irqoff (err -2)
[   54.476356] kvm_intel: Unknown symbol kvm_apic_update_ppr (err -2)
[   54.483094] kvm_intel: Unknown symbol kvm_configure_mmu (err -2)
[   54.489629] kvm_intel: Unknown symbol kvm_apic_update_irr (err -2)
[   54.496368] kvm_intel: Unknown symbol kvm_init_mmu (err -2)
[   54.502455] kvm_intel: Unknown symbol kvm_emulate_wbinvd (err -2)
[   54.509106] kvm_intel: Unknown symbol kvm_set_cr3 (err -2)
[   54.515091] kvm_intel: Unknown symbol kvm_lapic_switch_to_sw_timer (err -2)
[   54.522684] kvm_intel: Unknown symbol __SCK__tp_func_kvm_page_fault (err -2)
[   54.530364] kvm_intel: Unknown symbol kvm_get_cr8 (err -2)
[   54.536352] kvm_intel: Unknown symbol kvm_x86_ops (err -2)
[   54.542326] kvm_intel: Unknown symbol __SCT__tp_func_kvm_pi_irte_update (err -2)
[   54.550394] kvm_intel: Unknown symbol vcpu_load (err -2)
[   54.556194] kvm_intel: Unknown symbol kvm_handle_memory_failure (err -2)
[   54.563505] kvm_intel: Unknown symbol kvm_set_dr (err -2)
[   54.569384] kvm_intel: Unknown symbol kvm_set_msi_irq (err -2)
[   54.575750] kvm_intel: Unknown symbol kvm_emulate_hypercall (err -2)
[   54.582677] kvm_intel: Unknown symbol kvm_spurious_fault (err -2)
[   54.589326] kvm_intel: Unknown symbol kvm_has_tsc_control (err -2)
[   54.596071] kvm_intel: Unknown symbol kvm_get_linear_rip (err -2)
[   54.602710] kvm_intel: Unknown symbol kvm_get_msr (err -2)
[   54.608696] kvm_intel: Unknown symbol load_pdptrs (err -2)
[   54.614691] kvm_intel: Unknown symbol kvm_get_running_vcpu (err -2)
[   54.621529] kvm_intel: Unknown symbol kvm_vcpu_read_guest_page (err -2)
[   54.628728] kvm_intel: Unknown symbol kvm_set_cpu_caps (err -2)
[   54.635165] kvm_intel: Unknown symbol kvm_vcpu_exit_request (err -2)
[   54.642086] kvm_intel: Unknown symbol host_efer (err -2)
[   54.647883] kvm_intel: Unknown symbol kvm_max_tsc_scaling_ratio (err -2)
[   54.655180] kvm_intel: Unknown symbol __SCT__tp_func_kvm_pml_full (err -2)
[   54.662681] kvm_intel: Unknown symbol pdptrs_changed (err -2)
[   54.668957] kvm_intel: Unknown symbol kvm_set_cr4 (err -2)
[   54.674947] kvm_intel: Unknown symbol __SCK__tp_func_kvm_exit (err -2)
[   54.682059] kvm_intel: Unknown symbol kvm_release_page_clean (err -2)
[   54.689070] kvm_intel: Unknown symbol kvm_handle_page_fault (err -2)
[   54.695989] kvm_intel: Unknown symbol kvm_cpu_caps (err -2)
[   54.702066] kvm_intel: Unknown symbol kvm_spec_ctrl_test_value (err -2)
[   54.709275] kvm_intel: Unknown symbol __SCT__tp_func_kvm_exit (err -2)
[   54.716393] kvm_intel: Unknown symbol kvm_apic_clear_irr (err -2)
[   54.723048] kvm_intel: Unknown symbol __x86_set_memory_region (err -2)
[   54.730166] kvm_intel: Unknown symbol kvm_load_guest_xsave_state (err -2)
[   54.737566] kvm_intel: Unknown symbol kvm_set_cr0 (err -2)
[   54.743555] kvm_intel: Unknown symbol kvm_set_cr8 (err -2)
[   54.749542] kvm_intel: Unknown symbol kvm_get_dr (err -2)
[   54.755423] kvm_intel: Unknown symbol kvm_mmu_page_fault (err -2)
[   54.762074] kvm_intel: Unknown symbol __SCK__tp_func_kvm_nested_vmexit (err -2)
[   54.770038] kvm_intel: Unknown symbol kvm_emulate_instruction (err -2)
[   54.777160] kvm_intel: Unknown symbol __SCK__tp_func_kvm_pml_full (err -2)
[   54.784658] kvm_intel: Unknown symbol kvm_mtrr_get_guest_memory_type (err -2)
[   54.792445] kvm_intel: Unknown symbol kvm_mmu_reset_context (err -2)
[   54.799374] kvm_intel: Unknown symbol kvm_get_apic_mode (err -2)
[   54.805899] kvm_intel: Unknown symbol kvm_vcpu_read_guest (err -2)
[   54.812643] kvm_intel: Unknown symbol kvm_vcpu_on_spin (err -2)
[   54.819097] kvm_intel: Unknown symbol __SCK__tp_func_kvm_fast_mmio (err -2)
[   54.826692] kvm_intel: Unknown symbol kvm_read_guest (err -2)
[   54.832965] kvm_intel: Unknown symbol kvm_define_user_return_msr (err -2)
[   54.840374] kvm_intel: Unknown symbol kvm_rebooting (err -2)
[   54.846548] kvm_intel: Unknown symbol kvm_get_rflags (err -2)
[   54.852825] kvm_intel: Unknown symbol kvm_queue_exception_e (err -2)
[   54.859758] kvm_intel: Unknown symbol __SCT__tp_func_kvm_inj_virq (err -2)
[   54.867253] kvm_intel: Unknown symbol current_vcpu (err -2)
[   54.873334] kvm_intel: Unknown symbol __SCT__tp_func_kvm_write_tsc_offset (err -2)
[   54.881588] kvm_intel: Unknown symbol __tracepoint_kvm_exit (err -2)
[   54.888505] kvm_intel: Unknown symbol kvm_emulate_cpuid (err -2)
[   54.895065] kvm_intel: Unknown symbol kvm_emulate_wrmsr (err -2)
[   54.901622] kvm_intel: Unknown symbol __SCK__tp_func_kvm_inj_virq (err -2)
[   54.909118] kvm_intel: Unknown symbol kvm_apic_set_eoi_accelerated (err -2)
[   54.916717] kvm_intel: Unknown symbol kvm_vcpu_kick (err -2)
[   54.922883] kvm_intel: Unknown symbol kvm_inject_realmode_interrupt (err -2)
[   54.930556] kvm_intel: Unknown symbol kvm_mmu_invlpg (err -2)
[   54.936812] kvm_intel: Unknown symbol kvm_fast_pio (err -2)
[   54.942875] kvm_intel: Unknown symbol __SCK__tp_func_kvm_ple_window_update (err -2)
[   54.951224] kvm_intel: Unknown symbol kvm_set_msr_common (err -2)
[   54.957868] kvm_intel: Unknown symbol __SCT__tp_func_kvm_nested_vmenter_failed (err -2)
[   54.966595] kvm_intel: Unknown symbol __SCK__tp_func_kvm_nested_vmexit_inject (err -2)
[   54.975217] kvm_intel: Unknown symbol kvm_intr_is_single_vcpu (err -2)
[   54.982327] kvm_intel: Unknown symbol kvm_apic_has_interrupt (err -2)
[   54.989344] kvm_intel: Unknown symbol __SCT__tp_func_kvm_ple_window_update (err -2)
[   54.997695] kvm_intel: Unknown symbol __SCK__tp_func_kvm_write_tsc_offset (err -2)
[   55.005941] kvm_intel: Unknown symbol __tracepoint_kvm_nested_vmexit_inject (err -2)
[   55.014360] kvm_intel: Unknown symbol __SCT__tp_func_kvm_page_fault (err -2)
[   55.022048] kvm_intel: Unknown symbol kvm_require_dr (err -2)
[   55.028303] kvm_intel: Unknown symbol kvm_skip_emulated_instruction (err -2)
[   55.035994] kvm_intel: Unknown symbol kvm_inject_page_fault (err -2)
[   55.042921] kvm_intel: Unknown symbol kvm_cpu_get_interrupt (err -2)
[   55.049846] kvm_intel: Unknown symbol kvm_vcpu_write_guest (err -2)
[   55.056685] kvm_intel: Unknown symbol kvm_complete_insn_gp (err -2)
[   55.063508] kvm_intel: Unknown symbol kvm_mmu_set_mask_ptes (err -2)
[   55.070441] kvm_intel: Unknown symbol kvm_apic_write_nodecode (err -2)
[   55.077551] kvm_intel: Unknown symbol kvm_lapic_hv_timer_in_use (err -2)
[   55.084854] kvm_intel: Unknown symbol allow_smaller_maxphyaddr (err -2)
[   55.097913] kvm_intel: Unknown symbol __tracepoint_kvm_ple_window_update (err -2)
[   55.107375] kvm_intel: Unknown symbol vcpu_put (err -2)
[   55.113072] kvm_intel: Unknown symbol kvm_arch_has_assigned_device (err -2)
[   55.120666] kvm_intel: Unknown symbol kvm_rdpmc (err -2)
[   55.126457] kvm_intel: Unknown symbol kvm_vcpu_mark_page_dirty (err -2)
[   55.133670] kvm_intel: Unknown symbol kvm_vcpu_halt (err -2)
[   55.139844] kvm_intel: Unknown symbol kvm_clear_guest_page (err -2)
[   55.146684] kvm_intel: Unknown symbol kvm_requeue_exception (err -2)
[   55.153612] kvm_intel: Unknown symbol reprogram_counter (err -2)
[   55.160171] kvm_intel: Unknown symbol __SCK__tp_func_kvm_nested_vmenter_failed (err -2)
[   55.168891] kvm_intel: Unknown symbol kvm_exit (err -2)
[   55.174591] kvm_intel: Unknown symbol kvm_init (err -2)
[   55.180303] kvm_intel: Unknown symbol kvm_deliver_exception_payload (err -2)
[   55.187986] kvm_intel: Unknown symbol kvm_set_msr (err -2)
[   55.193978] kvm_intel: Unknown symbol kvm_default_tsc_scaling_ratio (err -2)
[   55.201659] kvm_intel: Unknown symbol __tracepoint_kvm_nested_vmexit (err -2)
[   55.209446] kvm_intel: Unknown symbol enable_vmware_backdoor (err -2)
[   55.216469] kvm_intel: Unknown symbol kvm_enable_efer_bits (err -2)
[   55.223314] kvm_intel: Unknown symbol __SCT__tp_func_kvm_nested_vmexit (err -2)
[   55.231285] kvm_intel: Unknown symbol __kvm_request_immediate_exit (err -2)
[   55.238877] kvm_intel: Unknown symbol kvm_lapic_expired_hv_timer (err -2)
[   55.246282] kvm_intel: Unknown symbol kvm_fixup_and_inject_pf_error (err -2)
[   55.253955] kvm_intel: Unknown symbol gfn_to_page (err -2)
[   55.259927] kvm_intel: Unknown symbol __SCK__tp_func_kvm_cr (err -2)
[   55.266859] kvm_intel: Unknown symbol kvm_probe_user_return_msr (err -2)
[   55.274162] kvm_intel: Unknown symbol kvm_vcpu_write_guest_page (err -2)
[   55.281473] kvm_intel: Unknown symbol kvm_no_apic_vcpu (err -2)
[   55.287927] kvm_intel: Unknown symbol handle_ud (err -2)
[   55.293727] kvm_intel: Unknown symbol kvm_mmu_new_pgd (err -2)
[   55.300093] kvm_intel: Unknown symbol reprogram_fixed_counter (err -2)
[   55.307219] kvm_intel: Unknown symbol __tracepoint_kvm_nested_vmenter_failed (err -2)
[   55.315749] kvm_intel: Unknown symbol kvm_get_msr_common (err -2)
[   55.322388] kvm_intel: Unknown symbol kvm_mmu_slot_largepage_remove_write_access (err -2)
[   55.331291] kvm_intel: Unknown symbol __tracepoint_kvm_fast_mmio (err -2)
[   55.338696] kvm_intel: Unknown symbol kvm_arch_has_noncoherent_dma (err -2)
[   55.346289] kvm_intel: Unknown symbol kvm_hv_get_assist_page (err -2)
[   55.353311] kvm_intel: Unknown symbol kvm_emulate_halt (err -2)
[   55.359765] kvm_intel: Unknown symbol kvm_set_apic_base (err -2)
[   55.366312] kvm_intel: Unknown symbol supported_xss (err -2)
[   55.372481] kvm_intel: Unknown symbol kvm_vcpu_map (err -2)
[   55.378565] kvm_intel: Unknown symbol kvm_msr_allowed (err -2)
[   55.384917] kvm_intel: Unknown symbol kvm_lapic_find_highest_irr (err -2)
[   55.392314] kvm_intel: Unknown symbol kvm_set_xcr (err -2)
[   55.398287] kvm_intel: Unknown symbol kvm_wait_lapic_expire (err -2)
[   55.405210] kvm_intel: Unknown symbol reprogram_gp_counter (err -2)
[   55.412055] kvm_intel: Unknown symbol kvm_write_guest_virt_system (err -2)
[   55.419550] kvm_intel: Unknown symbol kvm_find_cpuid_entry (err -2)
[   55.426376] kvm_intel: Unknown symbol kvm_task_switch (err -2)
[   55.432728] kvm_intel: Unknown symbol __SCT__tp_func_kvm_fast_mmio (err -2)
[   55.440322] kvm_intel: Unknown symbol kvm_read_guest_virt (err -2)
[   55.447055] kvm_intel: Unknown symbol kvm_vcpu_gfn_to_page (err -2)
[   55.453895] kvm_intel: Unknown symbol kvm_write_guest (err -2)
[   55.460250] kvm_intel: Unknown symbol __tracepoint_kvm_cr (err -2)
[   55.466992] kvm_intel: Unknown symbol kvm_io_bus_write (err -2)
[   55.473446] kvm_intel: Unknown symbol kvm_mmu_set_mmio_spte_mask (err -2)
[   55.480845] kvm_intel: Unknown symbol kvm_mmu_clear_dirty_pt_masked (err -2)
[   55.488532] kvm_intel: Unknown symbol kvm_set_user_return_msr (err -2)
[   55.495647] kvm_intel: Unknown symbol kvm_require_cpl (err -2)
[   55.502009] kvm_intel: Unknown symbol __SCT__tp_func_kvm_cr (err -2)
[   55.508930] kvm_intel: Unknown symbol kvm_init_shadow_ept_mmu (err -2)
[   55.516052] kvm_intel: Unknown symbol __tracepoint_kvm_pml_full (err -2)
[   55.523357] kvm_intel: Unknown symbol kvm_requeue_exception_e (err -2)
[   55.530472] kvm_intel: Unknown symbol kvm_lmsw (err -2)
[   55.536167] kvm_intel: Unknown symbol kvm_lapic_set_eoi (err -2)
[   55.542711] kvm_intel: Unknown symbol kvm_queue_exception (err -2)
[   55.549452] kvm_intel: Unknown symbol kvm_lapic_switch_to_hv_timer (err -2)
[   55.557029] kvm_intel: Unknown symbol kvm_emulate_rdmsr (err -2)
[   55.563585] kvm_intel: Unknown symbol __tracepoint_kvm_write_tsc_offset (err -2)
[   55.571655] kvm_intel: Unknown symbol kvm_vcpu_is_reset_bsp (err -2)
[   55.578578] kvm_intel: Unknown symbol __tracepoint_kvm_pi_irte_update (err -2)
[   55.586447] kvm_intel: Unknown symbol kvm_apicv_init (err -2)
[   55.592706] kvm_intel: Unknown symbol __SCT__tp_func_kvm_nested_vmexit_inject (err -2)
[   55.601336] kvm_intel: Unknown symbol kvm_vcpu_unmap (err -2)
[   55.607593] kvm_intel: Unknown symbol kvm_write_guest_page (err -2)
[   55.614426] kvm_intel: Unknown symbol kvm_valid_efer (err -2)
[   55.620694] kvm_intel: Unknown symbol supported_xcr0 (err -2)
[   55.626967] kvm_intel: Unknown symbol __SCK__tp_func_kvm_pi_irte_update (err -2)
[   55.635035] kvm_intel: Unknown symbol kvm_set_rflags (err -2)
[   55.641305] kvm_intel: Unknown symbol kvm_mmu_slot_leaf_clear_dirty (err -2)
[   55.648995] kvm_intel: Unknown symbol kvm_tsc_scaling_ratio_frac_bits (err -2)
[   55.656874] kvm_intel: Unknown symbol kvm_mce_cap_supported (err -2)
[   55.663793] kvm_intel: Unknown symbol kvm_handle_invpcid (err -2)
[   55.670428] kvm_intel: Unknown symbol kvm_load_host_xsave_state (err -2)
[   55.677743] kvm_intel: Unknown symbol __tracepoint_kvm_page_fault (err -2)
[   55.685240] kvm_intel: Unknown symbol kvm_mmu_free_roots (err -2)
[   55.691880] kvm_intel: Unknown symbol kvm_mmu_slot_set_dirty (err -2)
[   55.698899] kvm_intel: Unknown symbol kvm_queue_exception_p (err -2)
[   55.705824] kvm_intel: Unknown symbol kvm_read_l1_tsc (err -2)
[   55.712176] kvm_intel: Unknown symbol __tracepoint_kvm_inj_virq (err -2)
[   55.719486] kvm_intel: Unknown symbol kvm_cpu_has_interrupt (err -2)
[   55.726388] kvm_intel: Unknown symbol __kvm_apic_update_irr (err -2)
[   55.733324] kvm_intel: Unknown symbol handle_fastpath_set_msr_irqoff (err -2)
[   55.741098] kvm_intel: Unknown symbol kvm_apic_update_ppr (err -2)
[   55.747848] kvm_intel: Unknown symbol kvm_configure_mmu (err -2)
[   55.754407] kvm_intel: Unknown symbol kvm_apic_update_irr (err -2)
[   55.761138] kvm_intel: Unknown symbol kvm_init_mmu (err -2)
[   55.767206] kvm_intel: Unknown symbol kvm_emulate_wbinvd (err -2)
[   55.773840] kvm_intel: Unknown symbol kvm_set_cr3 (err -2)
[   55.779815] kvm_intel: Unknown symbol kvm_lapic_switch_to_sw_timer (err -2)
[   55.787416] kvm_intel: Unknown symbol __SCK__tp_func_kvm_page_fault (err -2)
[   55.795102] kvm_intel: Unknown symbol kvm_get_cr8 (err -2)
[   55.801095] kvm_intel: Unknown symbol kvm_x86_ops (err -2)
[   55.807088] kvm_intel: Unknown symbol __SCT__tp_func_kvm_pi_irte_update (err -2)
[   55.815155] kvm_intel: Unknown symbol vcpu_load (err -2)
[   55.820943] kvm_intel: Unknown symbol kvm_handle_memory_failure (err -2)
[   55.828248] kvm_intel: Unknown symbol kvm_set_dr (err -2)
[   55.834143] kvm_intel: Unknown symbol kvm_set_msi_irq (err -2)
[   55.840489] kvm_intel: Unknown symbol kvm_emulate_hypercall (err -2)
[   55.847414] kvm_intel: Unknown symbol kvm_spurious_fault (err -2)
[   55.854053] kvm_intel: Unknown symbol kvm_has_tsc_control (err -2)
[   55.860800] kvm_intel: Unknown symbol kvm_get_linear_rip (err -2)
[   55.867437] kvm_intel: Unknown symbol kvm_get_msr (err -2)
[   55.873426] kvm_intel: Unknown symbol load_pdptrs (err -2)
[   55.879408] kvm_intel: Unknown symbol kvm_get_running_vcpu (err -2)
[   55.886249] kvm_intel: Unknown symbol kvm_vcpu_read_guest_page (err -2)
[   55.893462] kvm_intel: Unknown symbol kvm_set_cpu_caps (err -2)
[   55.899910] kvm_intel: Unknown symbol kvm_vcpu_exit_request (err -2)
[   55.906839] kvm_intel: Unknown symbol host_efer (err -2)
[   55.912631] kvm_intel: Unknown symbol kvm_max_tsc_scaling_ratio (err -2)
[   55.919934] kvm_intel: Unknown symbol __SCT__tp_func_kvm_pml_full (err -2)
[   55.927426] kvm_intel: Unknown symbol pdptrs_changed (err -2)
[   55.933701] kvm_intel: Unknown symbol kvm_set_cr4 (err -2)
[   55.939687] kvm_intel: Unknown symbol __SCK__tp_func_kvm_exit (err -2)
[   55.946812] kvm_intel: Unknown symbol kvm_release_page_clean (err -2)
[   55.953838] kvm_intel: Unknown symbol kvm_handle_page_fault (err -2)
[   55.960746] kvm_intel: Unknown symbol kvm_cpu_caps (err -2)
[   55.966817] kvm_intel: Unknown symbol kvm_spec_ctrl_test_value (err -2)
[   55.974024] kvm_intel: Unknown symbol __SCT__tp_func_kvm_exit (err -2)
[   55.981138] kvm_intel: Unknown symbol kvm_apic_clear_irr (err -2)
[   55.987785] kvm_intel: Unknown symbol __x86_set_memory_region (err -2)
[   55.994888] kvm_intel: Unknown symbol kvm_load_guest_xsave_state (err -2)
[   56.002292] kvm_intel: Unknown symbol kvm_set_cr0 (err -2)
[   56.008285] kvm_intel: Unknown symbol kvm_set_cr8 (err -2)
[   56.014273] kvm_intel: Unknown symbol kvm_get_dr (err -2)
[   56.020155] kvm_intel: Unknown symbol kvm_mmu_page_fault (err -2)
[   56.026793] kvm_intel: Unknown symbol __SCK__tp_func_kvm_nested_vmexit (err -2)
[   56.034774] kvm_intel: Unknown symbol kvm_emulate_instruction (err -2)
[   56.041896] kvm_intel: Unknown symbol __SCK__tp_func_kvm_pml_full (err -2)
[   56.049382] kvm_intel: Unknown symbol kvm_mtrr_get_guest_memory_type (err -2)
[   56.057170] kvm_intel: Unknown symbol kvm_mmu_reset_context (err -2)
[   56.064086] kvm_intel: Unknown symbol kvm_get_apic_mode (err -2)
[   56.070635] kvm_intel: Unknown symbol kvm_vcpu_read_guest (err -2)
[   56.077377] kvm_intel: Unknown symbol kvm_vcpu_on_spin (err -2)
[   56.083843] kvm_intel: Unknown symbol __SCK__tp_func_kvm_fast_mmio (err -2)
[   56.091426] kvm_intel: Unknown symbol kvm_read_guest (err -2)
[   56.097694] kvm_intel: Unknown symbol kvm_define_user_return_msr (err -2)
[   56.105092] kvm_intel: Unknown symbol kvm_rebooting (err -2)
[   56.111265] kvm_intel: Unknown symbol kvm_get_rflags (err -2)
[   56.117523] kvm_intel: Unknown symbol kvm_queue_exception_e (err -2)
[   56.124447] kvm_intel: Unknown symbol __SCT__tp_func_kvm_inj_virq (err -2)
[   56.131942] kvm_intel: Unknown symbol current_vcpu (err -2)
[   56.138029] kvm_intel: Unknown symbol __SCT__tp_func_kvm_write_tsc_offset (err -2)
[   56.146280] kvm_intel: Unknown symbol __tracepoint_kvm_exit (err -2)
[   56.153217] kvm_intel: Unknown symbol kvm_emulate_cpuid (err -2)
[   56.159774] kvm_intel: Unknown symbol kvm_emulate_wrmsr (err -2)
[   56.166324] kvm_intel: Unknown symbol __SCK__tp_func_kvm_inj_virq (err -2)
[   56.173816] kvm_intel: Unknown symbol kvm_apic_set_eoi_accelerated (err -2)
[   56.181403] kvm_intel: Unknown symbol kvm_vcpu_kick (err -2)
[   56.187572] kvm_intel: Unknown symbol kvm_inject_realmode_interrupt (err -2)
[   56.195244] kvm_intel: Unknown symbol kvm_mmu_invlpg (err -2)
[   56.201500] kvm_intel: Unknown symbol kvm_fast_pio (err -2)
[   56.207573] kvm_intel: Unknown symbol __SCK__tp_func_kvm_ple_window_update (err -2)
[   56.215921] kvm_intel: Unknown symbol kvm_set_msr_common (err -2)
[   56.222571] kvm_intel: Unknown symbol __SCT__tp_func_kvm_nested_vmenter_failed (err -2)
[   56.231302] kvm_intel: Unknown symbol __SCK__tp_func_kvm_nested_vmexit_inject (err -2)
[   56.239935] kvm_intel: Unknown symbol kvm_intr_is_single_vcpu (err -2)
[   56.247035] kvm_intel: Unknown symbol kvm_apic_has_interrupt (err -2)
[   56.254053] kvm_intel: Unknown symbol __SCT__tp_func_kvm_ple_window_update (err -2)
[   56.262404] kvm_intel: Unknown symbol __SCK__tp_func_kvm_write_tsc_offset (err -2)
[   56.270661] kvm_intel: Unknown symbol __tracepoint_kvm_nested_vmexit_inject (err -2)
[   56.279099] kvm_intel: Unknown symbol __SCT__tp_func_kvm_page_fault (err -2)
[   56.286785] kvm_intel: Unknown symbol kvm_require_dr (err -2)
[   56.293052] kvm_intel: Unknown symbol kvm_skip_emulated_instruction (err -2)
[   56.300730] kvm_intel: Unknown symbol kvm_inject_page_fault (err -2)
[   56.307667] kvm_intel: Unknown symbol kvm_cpu_get_interrupt (err -2)
[   56.314596] kvm_intel: Unknown symbol kvm_vcpu_write_guest (err -2)
[   56.321436] kvm_intel: Unknown symbol kvm_complete_insn_gp (err -2)
[   56.328276] kvm_intel: Unknown symbol kvm_mmu_set_mask_ptes (err -2)
[   56.335199] kvm_intel: Unknown symbol kvm_apic_write_nodecode (err -2)
[   56.342296] kvm_intel: Unknown symbol kvm_lapic_hv_timer_in_use (err -2)
[   56.349596] kvm_intel: Unknown symbol allow_smaller_maxphyaddr (err -2)
[   56.363894] kvm_intel: Unknown symbol __tracepoint_kvm_ple_window_update (err -2)
[   56.372188] kvm_intel: Unknown symbol vcpu_put (err -2)
[   56.377883] kvm_intel: Unknown symbol kvm_arch_has_assigned_device (err -2)
[   56.385477] kvm_intel: Unknown symbol kvm_rdpmc (err -2)
[   56.391278] kvm_intel: Unknown symbol kvm_vcpu_mark_page_dirty (err -2)
[   56.398502] kvm_intel: Unknown symbol kvm_vcpu_halt (err -2)
[   56.404675] kvm_intel: Unknown symbol kvm_clear_guest_page (err -2)
[   56.411499] kvm_intel: Unknown symbol kvm_requeue_exception (err -2)
[   56.418436] kvm_intel: Unknown symbol reprogram_counter (err -2)
[   56.424996] kvm_intel: Unknown symbol __SCK__tp_func_kvm_nested_vmenter_failed (err -2)
[   56.433726] kvm_intel: Unknown symbol kvm_exit (err -2)
[   56.439431] kvm_intel: Unknown symbol kvm_init (err -2)
[   56.445131] kvm_intel: Unknown symbol kvm_deliver_exception_payload (err -2)
[   56.452818] kvm_intel: Unknown symbol kvm_set_msr (err -2)
[   56.458807] kvm_intel: Unknown symbol kvm_default_tsc_scaling_ratio (err -2)
[   56.466504] kvm_intel: Unknown symbol __tracepoint_kvm_nested_vmexit (err -2)
[   56.474287] kvm_intel: Unknown symbol enable_vmware_backdoor (err -2)
[   56.481314] kvm_intel: Unknown symbol kvm_enable_efer_bits (err -2)
[   56.488157] kvm_intel: Unknown symbol __SCT__tp_func_kvm_nested_vmexit (err -2)
[   56.496133] kvm_intel: Unknown symbol __kvm_request_immediate_exit (err -2)
[   56.503728] kvm_intel: Unknown symbol kvm_lapic_expired_hv_timer (err -2)
[   56.511130] kvm_intel: Unknown symbol kvm_fixup_and_inject_pf_error (err -2)
[   56.518821] kvm_intel: Unknown symbol gfn_to_page (err -2)
[   56.524813] kvm_intel: Unknown symbol __SCK__tp_func_kvm_cr (err -2)
[   56.531744] kvm_intel: Unknown symbol kvm_probe_user_return_msr (err -2)
[   56.539057] kvm_intel: Unknown symbol kvm_vcpu_write_guest_page (err -2)
[   56.546370] kvm_intel: Unknown symbol kvm_no_apic_vcpu (err -2)
[   56.552833] kvm_intel: Unknown symbol handle_ud (err -2)
[   56.558632] kvm_intel: Unknown symbol kvm_mmu_new_pgd (err -2)
[   56.565001] kvm_intel: Unknown symbol reprogram_fixed_counter (err -2)
[   56.572126] kvm_intel: Unknown symbol __tracepoint_kvm_nested_vmenter_failed (err -2)
[   56.580662] kvm_intel: Unknown symbol kvm_get_msr_common (err -2)
[   56.587291] kvm_intel: Unknown symbol kvm_mmu_slot_largepage_remove_write_access (err -2)
[   56.596209] kvm_intel: Unknown symbol __tracepoint_kvm_fast_mmio (err -2)
[   56.603614] kvm_intel: Unknown symbol kvm_arch_has_noncoherent_dma (err -2)
[   56.611208] kvm_intel: Unknown symbol kvm_hv_get_assist_page (err -2)
[   56.618225] kvm_intel: Unknown symbol kvm_emulate_halt (err -2)
[   56.624673] kvm_intel: Unknown symbol kvm_set_apic_base (err -2)
[   56.631230] kvm_intel: Unknown symbol supported_xss (err -2)
[   56.637411] kvm_intel: Unknown symbol kvm_vcpu_map (err -2)
[   56.643492] kvm_intel: Unknown symbol kvm_msr_allowed (err -2)
[   56.649862] kvm_intel: Unknown symbol kvm_lapic_find_highest_irr (err -2)
[   56.657265] kvm_intel: Unknown symbol kvm_set_xcr (err -2)
[   56.663247] kvm_intel: Unknown symbol kvm_wait_lapic_expire (err -2)
[   56.670184] kvm_intel: Unknown symbol reprogram_gp_counter (err -2)
[   56.677017] kvm_intel: Unknown symbol kvm_write_guest_virt_system (err -2)
[   56.684514] kvm_intel: Unknown symbol kvm_find_cpuid_entry (err -2)
[   56.691354] kvm_intel: Unknown symbol kvm_task_switch (err -2)
[   56.697729] kvm_intel: Unknown symbol __SCT__tp_func_kvm_fast_mmio (err -2)
[   56.705320] kvm_intel: Unknown symbol kvm_read_guest_virt (err -2)
[   56.712068] kvm_intel: Unknown symbol kvm_vcpu_gfn_to_page (err -2)
[   56.718903] kvm_intel: Unknown symbol kvm_write_guest (err -2)
[   56.725274] kvm_intel: Unknown symbol __tracepoint_kvm_cr (err -2)
[   56.732017] kvm_intel: Unknown symbol kvm_io_bus_write (err -2)
[   56.738480] kvm_intel: Unknown symbol kvm_mmu_set_mmio_spte_mask (err -2)
[   56.745869] kvm_intel: Unknown symbol kvm_mmu_clear_dirty_pt_masked (err -2)
[   56.753552] kvm_intel: Unknown symbol kvm_set_user_return_msr (err -2)
[   56.760671] kvm_intel: Unknown symbol kvm_require_cpl (err -2)
[   56.767044] kvm_intel: Unknown symbol __SCT__tp_func_kvm_cr (err -2)
[   56.773975] kvm_intel: Unknown symbol kvm_init_shadow_ept_mmu (err -2)
[   56.781100] kvm_intel: Unknown symbol __tracepoint_kvm_pml_full (err -2)
[   56.788411] kvm_intel: Unknown symbol kvm_requeue_exception_e (err -2)
[   56.795532] kvm_intel: Unknown symbol kvm_lmsw (err -2)
[   56.801240] kvm_intel: Unknown symbol kvm_lapic_set_eoi (err -2)
[   56.807790] kvm_intel: Unknown symbol kvm_queue_exception (err -2)
[   56.814537] kvm_intel: Unknown symbol kvm_lapic_switch_to_hv_timer (err -2)
[   56.822131] kvm_intel: Unknown symbol kvm_emulate_rdmsr (err -2)
[   56.828691] kvm_intel: Unknown symbol __tracepoint_kvm_write_tsc_offset (err -2)
[   56.836758] kvm_intel: Unknown symbol kvm_vcpu_is_reset_bsp (err -2)
[   56.843692] kvm_intel: Unknown symbol __tracepoint_kvm_pi_irte_update (err -2)
[   56.851569] kvm_intel: Unknown symbol kvm_apicv_init (err -2)
[   56.857839] kvm_intel: Unknown symbol __SCT__tp_func_kvm_nested_vmexit_inject (err -2)
[   56.866471] kvm_intel: Unknown symbol kvm_vcpu_unmap (err -2)
[   56.872746] kvm_intel: Unknown symbol kvm_write_guest_page (err -2)
[   56.879588] kvm_intel: Unknown symbol kvm_valid_efer (err -2)
[   56.885862] kvm_intel: Unknown symbol supported_xcr0 (err -2)
[   56.892135] kvm_intel: Unknown symbol __SCK__tp_func_kvm_pi_irte_update (err -2)
[   56.900202] kvm_intel: Unknown symbol kvm_set_rflags (err -2)
[   56.906475] kvm_intel: Unknown symbol kvm_mmu_slot_leaf_clear_dirty (err -2)
[   56.914154] kvm_intel: Unknown symbol kvm_tsc_scaling_ratio_frac_bits (err -2)
[   56.922023] kvm_intel: Unknown symbol kvm_mce_cap_supported (err -2)
[   56.928951] kvm_intel: Unknown symbol kvm_handle_invpcid (err -2)
[   56.935602] kvm_intel: Unknown symbol kvm_load_host_xsave_state (err -2)
[   56.942893] kvm_intel: Unknown symbol __tracepoint_kvm_page_fault (err -2)
[   56.950393] kvm_intel: Unknown symbol kvm_mmu_free_roots (err -2)
[   56.957046] kvm_intel: Unknown symbol kvm_mmu_slot_set_dirty (err -2)
[   56.964060] kvm_intel: Unknown symbol kvm_queue_exception_p (err -2)
[   56.970990] kvm_intel: Unknown symbol kvm_read_l1_tsc (err -2)
[   56.977361] kvm_intel: Unknown symbol __tracepoint_kvm_inj_virq (err -2)
[   56.984673] kvm_intel: Unknown symbol kvm_cpu_has_interrupt (err -2)
[   56.991597] kvm_intel: Unknown symbol __kvm_apic_update_irr (err -2)
[   56.998532] kvm_intel: Unknown symbol handle_fastpath_set_msr_irqoff (err -2)
[   57.006316] kvm_intel: Unknown symbol kvm_apic_update_ppr (err -2)
[   57.013060] kvm_intel: Unknown symbol kvm_configure_mmu (err -2)
[   57.019610] kvm_intel: Unknown symbol kvm_apic_update_irr (err -2)
[   57.026351] kvm_intel: Unknown symbol kvm_init_mmu (err -2)
[   57.032439] kvm_intel: Unknown symbol kvm_emulate_wbinvd (err -2)
[   57.039089] kvm_intel: Unknown symbol kvm_set_cr3 (err -2)
[   57.045080] kvm_intel: Unknown symbol kvm_lapic_switch_to_sw_timer (err -2)
[   57.052678] kvm_intel: Unknown symbol __SCK__tp_func_kvm_page_fault (err -2)
[   57.060354] kvm_intel: Unknown symbol kvm_get_cr8 (err -2)
[   57.066345] kvm_intel: Unknown symbol kvm_x86_ops (err -2)
[   57.072337] kvm_intel: Unknown symbol __SCT__tp_func_kvm_pi_irte_update (err -2)
[   57.080404] kvm_intel: Unknown symbol vcpu_load (err -2)
[   57.086186] kvm_intel: Unknown symbol kvm_handle_memory_failure (err -2)
[   57.093491] kvm_intel: Unknown symbol kvm_set_dr (err -2)
[   57.099384] kvm_intel: Unknown symbol kvm_set_msi_irq (err -2)
[   57.105740] kvm_intel: Unknown symbol kvm_emulate_hypercall (err -2)
[   57.112678] kvm_intel: Unknown symbol kvm_spurious_fault (err -2)
[   57.119315] kvm_intel: Unknown symbol kvm_has_tsc_control (err -2)
[   57.126052] kvm_intel: Unknown symbol kvm_get_linear_rip (err -2)
[   57.132695] kvm_intel: Unknown symbol kvm_get_msr (err -2)
[   57.138683] kvm_intel: Unknown symbol load_pdptrs (err -2)
[   57.144677] kvm_intel: Unknown symbol kvm_get_running_vcpu (err -2)
[   57.151517] kvm_intel: Unknown symbol kvm_vcpu_read_guest_page (err -2)
[   57.158715] kvm_intel: Unknown symbol kvm_set_cpu_caps (err -2)
[   57.165179] kvm_intel: Unknown symbol kvm_vcpu_exit_request (err -2)
[   57.172115] kvm_intel: Unknown symbol host_efer (err -2)
[   57.177912] kvm_intel: Unknown symbol kvm_max_tsc_scaling_ratio (err -2)
[   57.185230] kvm_intel: Unknown symbol __SCT__tp_func_kvm_pml_full (err -2)
[   57.192726] kvm_intel: Unknown symbol pdptrs_changed (err -2)
[   57.199001] kvm_intel: Unknown symbol kvm_set_cr4 (err -2)
[   57.204993] kvm_intel: Unknown symbol __SCK__tp_func_kvm_exit (err -2)
[   57.212114] kvm_intel: Unknown symbol kvm_release_page_clean (err -2)
[   57.219141] kvm_intel: Unknown symbol kvm_handle_page_fault (err -2)
[   57.226067] kvm_intel: Unknown symbol kvm_cpu_caps (err -2)
[   57.232154] kvm_intel: Unknown symbol kvm_spec_ctrl_test_value (err -2)
[   57.239370] kvm_intel: Unknown symbol __SCT__tp_func_kvm_exit (err -2)
[   57.246479] kvm_intel: Unknown symbol kvm_apic_clear_irr (err -2)
[   57.253128] kvm_intel: Unknown symbol __x86_set_memory_region (err -2)
[   57.260240] kvm_intel: Unknown symbol kvm_load_guest_xsave_state (err -2)
[   57.267647] kvm_intel: Unknown symbol kvm_set_cr0 (err -2)
[   57.273636] kvm_intel: Unknown symbol kvm_set_cr8 (err -2)
[   57.279635] kvm_intel: Unknown symbol kvm_get_dr (err -2)
[   57.285534] kvm_intel: Unknown symbol kvm_mmu_page_fault (err -2)
[   57.292178] kvm_intel: Unknown symbol __SCK__tp_func_kvm_nested_vmexit (err -2)
[   57.300148] kvm_intel: Unknown symbol kvm_emulate_instruction (err -2)
[   57.307275] kvm_intel: Unknown symbol __SCK__tp_func_kvm_pml_full (err -2)
[   57.314762] kvm_intel: Unknown symbol kvm_mtrr_get_guest_memory_type (err -2)
[   57.322545] kvm_intel: Unknown symbol kvm_mmu_reset_context (err -2)
[   57.329477] kvm_intel: Unknown symbol kvm_get_apic_mode (err -2)
[   57.336037] kvm_intel: Unknown symbol kvm_vcpu_read_guest (err -2)
[   57.342782] kvm_intel: Unknown symbol kvm_vcpu_on_spin (err -2)
[   57.349248] kvm_intel: Unknown symbol __SCK__tp_func_kvm_fast_mmio (err -2)
[   57.356837] kvm_intel: Unknown symbol kvm_read_guest (err -2)
[   57.363115] kvm_intel: Unknown symbol kvm_define_user_return_msr (err -2)
[   57.370519] kvm_intel: Unknown symbol kvm_rebooting (err -2)
[   57.376697] kvm_intel: Unknown symbol kvm_get_rflags (err -2)
[   57.382969] kvm_intel: Unknown symbol kvm_queue_exception_e (err -2)
[   57.389907] kvm_intel: Unknown symbol __SCT__tp_func_kvm_inj_virq (err -2)
[   57.397396] kvm_intel: Unknown symbol current_vcpu (err -2)
[   57.403477] kvm_intel: Unknown symbol __SCT__tp_func_kvm_write_tsc_offset (err -2)
[   57.411731] kvm_intel: Unknown symbol __tracepoint_kvm_exit (err -2)
[   57.418661] kvm_intel: Unknown symbol kvm_emulate_cpuid (err -2)
[   57.425220] kvm_intel: Unknown symbol kvm_emulate_wrmsr (err -2)
[   57.431775] kvm_intel: Unknown symbol __SCK__tp_func_kvm_inj_virq (err -2)
[   57.439276] kvm_intel: Unknown symbol kvm_apic_set_eoi_accelerated (err -2)
[   57.446863] kvm_intel: Unknown symbol kvm_vcpu_kick (err -2)
[   57.453040] kvm_intel: Unknown symbol kvm_inject_realmode_interrupt (err -2)
[   57.460729] kvm_intel: Unknown symbol kvm_mmu_invlpg (err -2)
[   57.467005] kvm_intel: Unknown symbol kvm_fast_pio (err -2)
[   57.473082] kvm_intel: Unknown symbol __SCK__tp_func_kvm_ple_window_update (err -2)
[   57.481421] kvm_intel: Unknown symbol kvm_set_msr_common (err -2)
[   57.488072] kvm_intel: Unknown symbol __SCT__tp_func_kvm_nested_vmenter_failed (err -2)
[   57.496803] kvm_intel: Unknown symbol __SCK__tp_func_kvm_nested_vmexit_inject (err -2)
[   57.505435] kvm_intel: Unknown symbol kvm_intr_is_single_vcpu (err -2)
[   57.512552] kvm_intel: Unknown symbol kvm_apic_has_interrupt (err -2)
[   57.519573] kvm_intel: Unknown symbol __SCT__tp_func_kvm_ple_window_update (err -2)
[   57.527923] kvm_intel: Unknown symbol __SCK__tp_func_kvm_write_tsc_offset (err -2)
[   57.536175] kvm_intel: Unknown symbol __tracepoint_kvm_nested_vmexit_inject (err -2)
[   57.544620] kvm_intel: Unknown symbol __SCT__tp_func_kvm_page_fault (err -2)
[   57.552312] kvm_intel: Unknown symbol kvm_require_dr (err -2)
[   57.558575] kvm_intel: Unknown symbol kvm_skip_emulated_instruction (err -2)
[   57.566264] kvm_intel: Unknown symbol kvm_inject_page_fault (err -2)
[   57.573196] kvm_intel: Unknown symbol kvm_cpu_get_interrupt (err -2)
[   57.580125] kvm_intel: Unknown symbol kvm_vcpu_write_guest (err -2)
[   57.586962] kvm_intel: Unknown symbol kvm_complete_insn_gp (err -2)
[   57.593784] kvm_intel: Unknown symbol kvm_mmu_set_mask_ptes (err -2)
[   57.600718] kvm_intel: Unknown symbol kvm_apic_write_nodecode (err -2)
[   57.607840] kvm_intel: Unknown symbol kvm_lapic_hv_timer_in_use (err -2)
[   57.615160] kvm_intel: Unknown symbol allow_smaller_maxphyaddr (err -2)
[   57.631916] kvm_intel: Unknown symbol __tracepoint_kvm_ple_window_update (err -2)
[   57.640604] kvm_intel: Unknown symbol vcpu_put (err -2)
[   57.646310] kvm_intel: Unknown symbol kvm_arch_has_assigned_device (err -2)
[   57.653902] kvm_intel: Unknown symbol kvm_rdpmc (err -2)
[   57.659702] kvm_intel: Unknown symbol kvm_vcpu_mark_page_dirty (err -2)
[   57.666918] kvm_intel: Unknown symbol kvm_vcpu_halt (err -2)
[   57.673094] kvm_intel: Unknown symbol kvm_clear_guest_page (err -2)
[   57.679933] kvm_intel: Unknown symbol kvm_requeue_exception (err -2)
[   57.686861] kvm_intel: Unknown symbol reprogram_counter (err -2)
[   57.693399] kvm_intel: Unknown symbol __SCK__tp_func_kvm_nested_vmenter_failed (err -2)
[   57.702128] kvm_intel: Unknown symbol kvm_exit (err -2)
[   57.707828] kvm_intel: Unknown symbol kvm_init (err -2)
[   57.713529] kvm_intel: Unknown symbol kvm_deliver_exception_payload (err -2)
[   57.721204] kvm_intel: Unknown symbol kvm_set_msr (err -2)
[   57.727197] kvm_intel: Unknown symbol kvm_default_tsc_scaling_ratio (err -2)
[   57.734870] kvm_intel: Unknown symbol __tracepoint_kvm_nested_vmexit (err -2)
[   57.742650] kvm_intel: Unknown symbol enable_vmware_backdoor (err -2)
[   57.749666] kvm_intel: Unknown symbol kvm_enable_efer_bits (err -2)
[   57.756508] kvm_intel: Unknown symbol __SCT__tp_func_kvm_nested_vmexit (err -2)
[   57.764482] kvm_intel: Unknown symbol __kvm_request_immediate_exit (err -2)
[   57.772073] kvm_intel: Unknown symbol kvm_lapic_expired_hv_timer (err -2)
[   57.779481] kvm_intel: Unknown symbol kvm_fixup_and_inject_pf_error (err -2)
[   57.787156] kvm_intel: Unknown symbol gfn_to_page (err -2)
[   57.793144] kvm_intel: Unknown symbol __SCK__tp_func_kvm_cr (err -2)
[   57.800073] kvm_intel: Unknown symbol kvm_probe_user_return_msr (err -2)
[   57.807384] kvm_intel: Unknown symbol kvm_vcpu_write_guest_page (err -2)
[   57.814691] kvm_intel: Unknown symbol kvm_no_apic_vcpu (err -2)
[   57.821154] kvm_intel: Unknown symbol handle_ud (err -2)
[   57.826950] kvm_intel: Unknown symbol kvm_mmu_new_pgd (err -2)
[   57.833317] kvm_intel: Unknown symbol reprogram_fixed_counter (err -2)
[   57.840442] kvm_intel: Unknown symbol __tracepoint_kvm_nested_vmenter_failed (err -2)
[   57.848983] kvm_intel: Unknown symbol kvm_get_msr_common (err -2)
[   57.855631] kvm_intel: Unknown symbol kvm_mmu_slot_largepage_remove_write_access (err -2)
[   57.864534] kvm_intel: Unknown symbol __tracepoint_kvm_fast_mmio (err -2)
[   57.871930] kvm_intel: Unknown symbol kvm_arch_has_noncoherent_dma (err -2)
[   57.879524] kvm_intel: Unknown symbol kvm_hv_get_assist_page (err -2)
[   57.886555] kvm_intel: Unknown symbol kvm_emulate_halt (err -2)
[   57.893014] kvm_intel: Unknown symbol kvm_set_apic_base (err -2)
[   57.899548] kvm_intel: Unknown symbol supported_xss (err -2)
[   57.905723] kvm_intel: Unknown symbol kvm_vcpu_map (err -2)
[   57.911809] kvm_intel: Unknown symbol kvm_msr_allowed (err -2)
[   57.918170] kvm_intel: Unknown symbol kvm_lapic_find_highest_irr (err -2)
[   57.925573] kvm_intel: Unknown symbol kvm_set_xcr (err -2)
[   57.931545] kvm_intel: Unknown symbol kvm_wait_lapic_expire (err -2)
[   57.938463] kvm_intel: Unknown symbol reprogram_gp_counter (err -2)
[   57.945299] kvm_intel: Unknown symbol kvm_write_guest_virt_system (err -2)
[   57.952794] kvm_intel: Unknown symbol kvm_find_cpuid_entry (err -2)
[   57.959624] kvm_intel: Unknown symbol kvm_task_switch (err -2)
[   57.965976] kvm_intel: Unknown symbol __SCT__tp_func_kvm_fast_mmio (err -2)
[   57.973571] kvm_intel: Unknown symbol kvm_read_guest_virt (err -2)
[   57.980308] kvm_intel: Unknown symbol kvm_vcpu_gfn_to_page (err -2)
[   57.987148] kvm_intel: Unknown symbol kvm_write_guest (err -2)
[   57.993504] kvm_intel: Unknown symbol __tracepoint_kvm_cr (err -2)
[   58.000249] kvm_intel: Unknown symbol kvm_io_bus_write (err -2)
[   58.006703] kvm_intel: Unknown symbol kvm_mmu_set_mmio_spte_mask (err -2)
[   58.014092] kvm_intel: Unknown symbol kvm_mmu_clear_dirty_pt_masked (err -2)
[   58.021780] kvm_intel: Unknown symbol kvm_set_user_return_msr (err -2)
[   58.028885] kvm_intel: Unknown symbol kvm_require_cpl (err -2)
[   58.035240] kvm_intel: Unknown symbol __SCT__tp_func_kvm_cr (err -2)
[   58.042174] kvm_intel: Unknown symbol kvm_init_shadow_ept_mmu (err -2)
[   58.049294] kvm_intel: Unknown symbol __tracepoint_kvm_pml_full (err -2)
[   58.056590] kvm_intel: Unknown symbol kvm_requeue_exception_e (err -2)
[   58.063687] kvm_intel: Unknown symbol kvm_lmsw (err -2)
[   58.069387] kvm_intel: Unknown symbol kvm_lapic_set_eoi (err -2)
[   58.075923] kvm_intel: Unknown symbol kvm_queue_exception (err -2)
[   58.082670] kvm_intel: Unknown symbol kvm_lapic_switch_to_hv_timer (err -2)
[   58.090249] kvm_intel: Unknown symbol kvm_emulate_rdmsr (err -2)
[   58.096808] kvm_intel: Unknown symbol __tracepoint_kvm_write_tsc_offset (err -2)
[   58.104870] kvm_intel: Unknown symbol kvm_vcpu_is_reset_bsp (err -2)
[   58.111807] kvm_intel: Unknown symbol __tracepoint_kvm_pi_irte_update (err -2)
[   58.119686] kvm_intel: Unknown symbol kvm_apicv_init (err -2)
[   58.125954] kvm_intel: Unknown symbol __SCT__tp_func_kvm_nested_vmexit_inject (err -2)
[   58.134575] kvm_intel: Unknown symbol kvm_vcpu_unmap (err -2)
[   58.140848] kvm_intel: Unknown symbol kvm_write_guest_page (err -2)
[   58.147682] kvm_intel: Unknown symbol kvm_valid_efer (err -2)
[   58.153954] kvm_intel: Unknown symbol supported_xcr0 (err -2)
[   58.160227] kvm_intel: Unknown symbol __SCK__tp_func_kvm_pi_irte_update (err -2)
[   58.168291] kvm_intel: Unknown symbol kvm_set_rflags (err -2)
[   58.174564] kvm_intel: Unknown symbol kvm_mmu_slot_leaf_clear_dirty (err -2)
[   58.182230] kvm_intel: Unknown symbol kvm_tsc_scaling_ratio_frac_bits (err -2)
[   58.190100] kvm_intel: Unknown symbol kvm_mce_cap_supported (err -2)
[   58.197022] kvm_intel: Unknown symbol kvm_handle_invpcid (err -2)
[   58.203657] kvm_intel: Unknown symbol kvm_load_host_xsave_state (err -2)
[   58.210954] kvm_intel: Unknown symbol __tracepoint_kvm_page_fault (err -2)
[   58.218450] kvm_intel: Unknown symbol kvm_mmu_free_roots (err -2)
[   58.225088] kvm_intel: Unknown symbol kvm_mmu_slot_set_dirty (err -2)
[   58.232106] kvm_intel: Unknown symbol kvm_queue_exception_p (err -2)
[   58.239023] kvm_intel: Unknown symbol kvm_read_l1_tsc (err -2)
[   58.245374] kvm_intel: Unknown symbol __tracepoint_kvm_inj_virq (err -2)
[   58.252668] kvm_intel: Unknown symbol kvm_cpu_has_interrupt (err -2)
[   58.259591] kvm_intel: Unknown symbol __kvm_apic_update_irr (err -2)
[   58.266501] kvm_intel: Unknown symbol handle_fastpath_set_msr_irqoff (err -2)
[   58.274284] kvm_intel: Unknown symbol kvm_apic_update_ppr (err -2)
[   58.281024] kvm_intel: Unknown symbol kvm_configure_mmu (err -2)
[   58.287579] kvm_intel: Unknown symbol kvm_apic_update_irr (err -2)
[   58.294320] kvm_intel: Unknown symbol kvm_init_mmu (err -2)
[   58.300389] kvm_intel: Unknown symbol kvm_emulate_wbinvd (err -2)
[   58.307023] kvm_intel: Unknown symbol kvm_set_cr3 (err -2)
[   58.312999] kvm_intel: Unknown symbol kvm_lapic_switch_to_sw_timer (err -2)
[   58.320596] kvm_intel: Unknown symbol __SCK__tp_func_kvm_page_fault (err -2)
[   58.328281] kvm_intel: Unknown symbol kvm_get_cr8 (err -2)
[   58.334270] kvm_intel: Unknown symbol kvm_x86_ops (err -2)
[   58.340246] kvm_intel: Unknown symbol __SCT__tp_func_kvm_pi_irte_update (err -2)
[   58.348311] kvm_intel: Unknown symbol vcpu_load (err -2)
[   58.354111] kvm_intel: Unknown symbol kvm_handle_memory_failure (err -2)
[   58.361427] kvm_intel: Unknown symbol kvm_set_dr (err -2)
[   58.367309] kvm_intel: Unknown symbol kvm_set_msi_irq (err -2)
[   58.373665] kvm_intel: Unknown symbol kvm_emulate_hypercall (err -2)
[   58.380601] kvm_intel: Unknown symbol kvm_spurious_fault (err -2)
[   58.387250] kvm_intel: Unknown symbol kvm_has_tsc_control (err -2)
[   58.393990] kvm_intel: Unknown symbol kvm_get_linear_rip (err -2)
[   58.400628] kvm_intel: Unknown symbol kvm_get_msr (err -2)
[   58.406606] kvm_intel: Unknown symbol load_pdptrs (err -2)
[   58.412601] kvm_intel: Unknown symbol kvm_get_running_vcpu (err -2)
[   58.419440] kvm_intel: Unknown symbol kvm_vcpu_read_guest_page (err -2)
[   58.426654] kvm_intel: Unknown symbol kvm_set_cpu_caps (err -2)
[   58.433097] kvm_intel: Unknown symbol kvm_vcpu_exit_request (err -2)
[   58.440018] kvm_intel: Unknown symbol host_efer (err -2)
[   58.445809] kvm_intel: Unknown symbol kvm_max_tsc_scaling_ratio (err -2)
[   58.453107] kvm_intel: Unknown symbol __SCT__tp_func_kvm_pml_full (err -2)
[   58.460606] kvm_intel: Unknown symbol pdptrs_changed (err -2)
[   58.466883] kvm_intel: Unknown symbol kvm_set_cr4 (err -2)
[   58.472871] kvm_intel: Unknown symbol __SCK__tp_func_kvm_exit (err -2)
[   58.479994] kvm_intel: Unknown symbol kvm_release_page_clean (err -2)
[   58.487011] kvm_intel: Unknown symbol kvm_handle_page_fault (err -2)
[   58.493928] kvm_intel: Unknown symbol kvm_cpu_caps (err -2)
[   58.499995] kvm_intel: Unknown symbol kvm_spec_ctrl_test_value (err -2)
[   58.507200] kvm_intel: Unknown symbol __SCT__tp_func_kvm_exit (err -2)
[   58.514319] kvm_intel: Unknown symbol kvm_apic_clear_irr (err -2)
[   58.520957] kvm_intel: Unknown symbol __x86_set_memory_region (err -2)
[   58.528077] kvm_intel: Unknown symbol kvm_load_guest_xsave_state (err -2)
[   58.535475] kvm_intel: Unknown symbol kvm_set_cr0 (err -2)
[   58.541455] kvm_intel: Unknown symbol kvm_set_cr8 (err -2)
[   58.547448] kvm_intel: Unknown symbol kvm_get_dr (err -2)
[   58.553335] kvm_intel: Unknown symbol kvm_mmu_page_fault (err -2)
[   58.559980] kvm_intel: Unknown symbol __SCK__tp_func_kvm_nested_vmexit (err -2)
[   58.567954] kvm_intel: Unknown symbol kvm_emulate_instruction (err -2)
[   58.575066] kvm_intel: Unknown symbol __SCK__tp_func_kvm_pml_full (err -2)
[   58.582562] kvm_intel: Unknown symbol kvm_mtrr_get_guest_memory_type (err -2)
[   58.590322] kvm_intel: Unknown symbol kvm_mmu_reset_context (err -2)
[   58.597256] kvm_intel: Unknown symbol kvm_get_apic_mode (err -2)
[   58.603805] kvm_intel: Unknown symbol kvm_vcpu_read_guest (err -2)
[   58.610552] kvm_intel: Unknown symbol kvm_vcpu_on_spin (err -2)
[   58.617012] kvm_intel: Unknown symbol __SCK__tp_func_kvm_fast_mmio (err -2)
[   58.624608] kvm_intel: Unknown symbol kvm_read_guest (err -2)
[   58.630871] kvm_intel: Unknown symbol kvm_define_user_return_msr (err -2)
[   58.638277] kvm_intel: Unknown symbol kvm_rebooting (err -2)
[   58.644454] kvm_intel: Unknown symbol kvm_get_rflags (err -2)
[   58.650713] kvm_intel: Unknown symbol kvm_queue_exception_e (err -2)
[   58.657636] kvm_intel: Unknown symbol __SCT__tp_func_kvm_inj_virq (err -2)
[   58.665139] kvm_intel: Unknown symbol current_vcpu (err -2)
[   58.671226] kvm_intel: Unknown symbol __SCT__tp_func_kvm_write_tsc_offset (err -2)
[   58.679479] kvm_intel: Unknown symbol __tracepoint_kvm_exit (err -2)
[   58.686412] kvm_intel: Unknown symbol kvm_emulate_cpuid (err -2)
[   58.692970] kvm_intel: Unknown symbol kvm_emulate_wrmsr (err -2)
[   58.699527] kvm_intel: Unknown symbol __SCK__tp_func_kvm_inj_virq (err -2)
[   58.707007] kvm_intel: Unknown symbol kvm_apic_set_eoi_accelerated (err -2)
[   58.714586] kvm_intel: Unknown symbol kvm_vcpu_kick (err -2)
[   58.720755] kvm_intel: Unknown symbol kvm_inject_realmode_interrupt (err -2)
[   58.728418] kvm_intel: Unknown symbol kvm_mmu_invlpg (err -2)
[   58.734673] kvm_intel: Unknown symbol kvm_fast_pio (err -2)
[   58.740742] kvm_intel: Unknown symbol __SCK__tp_func_kvm_ple_window_update (err -2)
[   58.749095] kvm_intel: Unknown symbol kvm_set_msr_common (err -2)
[   58.755728] kvm_intel: Unknown symbol __SCT__tp_func_kvm_nested_vmenter_failed (err -2)
[   58.764456] kvm_intel: Unknown symbol __SCK__tp_func_kvm_nested_vmexit_inject (err -2)
[   58.773080] kvm_intel: Unknown symbol kvm_intr_is_single_vcpu (err -2)
[   58.780183] kvm_intel: Unknown symbol kvm_apic_has_interrupt (err -2)
[   58.787231] kvm_intel: Unknown symbol __SCT__tp_func_kvm_ple_window_update (err -2)
[   58.795582] kvm_intel: Unknown symbol __SCK__tp_func_kvm_write_tsc_offset (err -2)
[   58.803838] kvm_intel: Unknown symbol __tracepoint_kvm_nested_vmexit_inject (err -2)
[   58.812279] kvm_intel: Unknown symbol __SCT__tp_func_kvm_page_fault (err -2)
[   58.819963] kvm_intel: Unknown symbol kvm_require_dr (err -2)
[   58.826233] kvm_intel: Unknown symbol kvm_skip_emulated_instruction (err -2)
[   58.833906] kvm_intel: Unknown symbol kvm_inject_page_fault (err -2)
[   58.840831] kvm_intel: Unknown symbol kvm_cpu_get_interrupt (err -2)
[   58.847743] kvm_intel: Unknown symbol kvm_vcpu_write_guest (err -2)
[   58.854579] kvm_intel: Unknown symbol kvm_complete_insn_gp (err -2)
[   58.861403] kvm_intel: Unknown symbol kvm_mmu_set_mask_ptes (err -2)
[   58.868338] kvm_intel: Unknown symbol kvm_apic_write_nodecode (err -2)
[   58.875443] kvm_intel: Unknown symbol kvm_lapic_hv_timer_in_use (err -2)
[   58.882747] kvm_intel: Unknown symbol allow_smaller_maxphyaddr (err -2)
[   58.896890] kvm_intel: Unknown symbol __tracepoint_kvm_ple_window_update (err -2)
[   58.905267] kvm_intel: Unknown symbol vcpu_put (err -2)
[   58.910956] kvm_intel: Unknown symbol kvm_arch_has_assigned_device (err -2)
[   58.918551] kvm_intel: Unknown symbol kvm_rdpmc (err -2)
[   58.924348] kvm_intel: Unknown symbol kvm_vcpu_mark_page_dirty (err -2)
[   58.931556] kvm_intel: Unknown symbol kvm_vcpu_halt (err -2)
[   58.937729] kvm_intel: Unknown symbol kvm_clear_guest_page (err -2)
[   58.944570] kvm_intel: Unknown symbol kvm_requeue_exception (err -2)
[   58.951509] kvm_intel: Unknown symbol reprogram_counter (err -2)
[   58.958055] kvm_intel: Unknown symbol __SCK__tp_func_kvm_nested_vmenter_failed (err -2)
[   58.966780] kvm_intel: Unknown symbol kvm_exit (err -2)
[   58.972475] kvm_intel: Unknown symbol kvm_init (err -2)
[   58.978186] kvm_intel: Unknown symbol kvm_deliver_exception_payload (err -2)
[   58.985873] kvm_intel: Unknown symbol kvm_set_msr (err -2)
[   58.991862] kvm_intel: Unknown symbol kvm_default_tsc_scaling_ratio (err -2)
[   58.999542] kvm_intel: Unknown symbol __tracepoint_kvm_nested_vmexit (err -2)
[   59.007326] kvm_intel: Unknown symbol enable_vmware_backdoor (err -2)
[   59.014343] kvm_intel: Unknown symbol kvm_enable_efer_bits (err -2)
[   59.021187] kvm_intel: Unknown symbol __SCT__tp_func_kvm_nested_vmexit (err -2)
[   59.029159] kvm_intel: Unknown symbol __kvm_request_immediate_exit (err -2)
[   59.036748] kvm_intel: Unknown symbol kvm_lapic_expired_hv_timer (err -2)
[   59.044146] kvm_intel: Unknown symbol kvm_fixup_and_inject_pf_error (err -2)
[   59.051841] kvm_intel: Unknown symbol gfn_to_page (err -2)
[   59.057830] kvm_intel: Unknown symbol __SCK__tp_func_kvm_cr (err -2)
[   59.064763] kvm_intel: Unknown symbol kvm_probe_user_return_msr (err -2)
[   59.072074] kvm_intel: Unknown symbol kvm_vcpu_write_guest_page (err -2)
[   59.079391] kvm_intel: Unknown symbol kvm_no_apic_vcpu (err -2)
[   59.085850] kvm_intel: Unknown symbol handle_ud (err -2)
[   59.091650] kvm_intel: Unknown symbol kvm_mmu_new_pgd (err -2)
[   59.098019] kvm_intel: Unknown symbol reprogram_fixed_counter (err -2)
[   59.105145] kvm_intel: Unknown symbol __tracepoint_kvm_nested_vmenter_failed (err -2)
[   59.113675] kvm_intel: Unknown symbol kvm_get_msr_common (err -2)
[   59.120323] kvm_intel: Unknown symbol kvm_mmu_slot_largepage_remove_write_access (err -2)
[   59.129233] kvm_intel: Unknown symbol __tracepoint_kvm_fast_mmio (err -2)
[   59.136642] kvm_intel: Unknown symbol kvm_arch_has_noncoherent_dma (err -2)
[   59.144238] kvm_intel: Unknown symbol kvm_hv_get_assist_page (err -2)
[   59.151263] kvm_intel: Unknown symbol kvm_emulate_halt (err -2)
[   59.157729] kvm_intel: Unknown symbol kvm_set_apic_base (err -2)
[   59.164286] kvm_intel: Unknown symbol supported_xss (err -2)
[   59.170455] kvm_intel: Unknown symbol kvm_vcpu_map (err -2)
[   59.176530] kvm_intel: Unknown symbol kvm_msr_allowed (err -2)
[   59.182889] kvm_intel: Unknown symbol kvm_lapic_find_highest_irr (err -2)
[   59.190277] kvm_intel: Unknown symbol kvm_set_xcr (err -2)
[   59.196268] kvm_intel: Unknown symbol kvm_wait_lapic_expire (err -2)
[   59.203189] kvm_intel: Unknown symbol reprogram_gp_counter (err -2)
[   59.210037] kvm_intel: Unknown symbol kvm_write_guest_virt_system (err -2)
[   59.217523] kvm_intel: Unknown symbol kvm_find_cpuid_entry (err -2)
[   59.224362] kvm_intel: Unknown symbol kvm_task_switch (err -2)
[   59.230715] kvm_intel: Unknown symbol __SCT__tp_func_kvm_fast_mmio (err -2)
[   59.238308] kvm_intel: Unknown symbol kvm_read_guest_virt (err -2)
[   59.245041] kvm_intel: Unknown symbol kvm_vcpu_gfn_to_page (err -2)
[   59.251880] kvm_intel: Unknown symbol kvm_write_guest (err -2)
[   59.258252] kvm_intel: Unknown symbol __tracepoint_kvm_cr (err -2)
[   59.264995] kvm_intel: Unknown symbol kvm_io_bus_write (err -2)
[   59.271457] kvm_intel: Unknown symbol kvm_mmu_set_mmio_spte_mask (err -2)
[   59.278867] kvm_intel: Unknown symbol kvm_mmu_clear_dirty_pt_masked (err -2)
[   59.286544] kvm_intel: Unknown symbol kvm_set_user_return_msr (err -2)
[   59.293669] kvm_intel: Unknown symbol kvm_require_cpl (err -2)
[   59.300037] kvm_intel: Unknown symbol __SCT__tp_func_kvm_cr (err -2)
[   59.306972] kvm_intel: Unknown symbol kvm_init_shadow_ept_mmu (err -2)
[   59.314095] kvm_intel: Unknown symbol __tracepoint_kvm_pml_full (err -2)
[   59.321405] kvm_intel: Unknown symbol kvm_requeue_exception_e (err -2)
[   59.328530] kvm_intel: Unknown symbol kvm_lmsw (err -2)
[   59.334225] kvm_intel: Unknown symbol kvm_lapic_set_eoi (err -2)
[   59.340781] kvm_intel: Unknown symbol kvm_queue_exception (err -2)
[   59.347518] kvm_intel: Unknown symbol kvm_lapic_switch_to_hv_timer (err -2)
[   59.355087] kvm_intel: Unknown symbol kvm_emulate_rdmsr (err -2)
[   59.361643] kvm_intel: Unknown symbol __tracepoint_kvm_write_tsc_offset (err -2)
[   59.369714] kvm_intel: Unknown symbol kvm_vcpu_is_reset_bsp (err -2)
[   59.376647] kvm_intel: Unknown symbol __tracepoint_kvm_pi_irte_update (err -2)
[   59.384506] kvm_intel: Unknown symbol kvm_apicv_init (err -2)
[   59.390769] kvm_intel: Unknown symbol __SCT__tp_func_kvm_nested_vmexit_inject (err -2)
[   59.399401] kvm_intel: Unknown symbol kvm_vcpu_unmap (err -2)
[   59.405665] kvm_intel: Unknown symbol kvm_write_guest_page (err -2)
[   59.412501] kvm_intel: Unknown symbol kvm_valid_efer (err -2)
[   59.418770] kvm_intel: Unknown symbol supported_xcr0 (err -2)
[   59.425043] kvm_intel: Unknown symbol __SCK__tp_func_kvm_pi_irte_update (err -2)
[   59.433111] kvm_intel: Unknown symbol kvm_set_rflags (err -2)
[   59.439375] kvm_intel: Unknown symbol kvm_mmu_slot_leaf_clear_dirty (err -2)
[   59.447065] kvm_intel: Unknown symbol kvm_tsc_scaling_ratio_frac_bits (err -2)
[   59.454942] kvm_intel: Unknown symbol kvm_mce_cap_supported (err -2)
[   59.461877] kvm_intel: Unknown symbol kvm_handle_invpcid (err -2)
[   59.468531] kvm_intel: Unknown symbol kvm_load_host_xsave_state (err -2)
[   59.475844] kvm_intel: Unknown symbol __tracepoint_kvm_page_fault (err -2)
[   59.483338] kvm_intel: Unknown symbol kvm_mmu_free_roots (err -2)
[   59.489978] kvm_intel: Unknown symbol kvm_mmu_slot_set_dirty (err -2)
[   59.497010] kvm_intel: Unknown symbol kvm_queue_exception_p (err -2)
[   59.503944] kvm_intel: Unknown symbol kvm_read_l1_tsc (err -2)
[   59.510311] kvm_intel: Unknown symbol __tracepoint_kvm_inj_virq (err -2)
[   59.517624] kvm_intel: Unknown symbol kvm_cpu_has_interrupt (err -2)
[   59.524558] kvm_intel: Unknown symbol __kvm_apic_update_irr (err -2)
[   59.531493] kvm_intel: Unknown symbol handle_fastpath_set_msr_irqoff (err -2)
[   59.539269] kvm_intel: Unknown symbol kvm_apic_update_ppr (err -2)
[   59.546013] kvm_intel: Unknown symbol kvm_configure_mmu (err -2)
[   59.552550] kvm_intel: Unknown symbol kvm_apic_update_irr (err -2)
[   59.559283] kvm_intel: Unknown symbol kvm_init_mmu (err -2)
[   59.565369] kvm_intel: Unknown symbol kvm_emulate_wbinvd (err -2)
[   59.572019] kvm_intel: Unknown symbol kvm_set_cr3 (err -2)
[   59.578013] kvm_intel: Unknown symbol kvm_lapic_switch_to_sw_timer (err -2)
[   59.585609] kvm_intel: Unknown symbol __SCK__tp_func_kvm_page_fault (err -2)
[   59.593293] kvm_intel: Unknown symbol kvm_get_cr8 (err -2)
[   59.599287] kvm_intel: Unknown symbol kvm_x86_ops (err -2)
[   59.605277] kvm_intel: Unknown symbol __SCT__tp_func_kvm_pi_irte_update (err -2)
[   59.613342] kvm_intel: Unknown symbol vcpu_load (err -2)
[   59.619145] kvm_intel: Unknown symbol kvm_handle_memory_failure (err -2)
[   59.626457] kvm_intel: Unknown symbol kvm_set_dr (err -2)
[   59.632341] kvm_intel: Unknown symbol kvm_set_msi_irq (err -2)
[   59.638713] kvm_intel: Unknown symbol kvm_emulate_hypercall (err -2)
[   59.645649] kvm_intel: Unknown symbol kvm_spurious_fault (err -2)
[   59.652298] kvm_intel: Unknown symbol kvm_has_tsc_control (err -2)
[   59.659040] kvm_intel: Unknown symbol kvm_get_linear_rip (err -2)
[   59.665676] kvm_intel: Unknown symbol kvm_get_msr (err -2)
[   59.671664] kvm_intel: Unknown symbol load_pdptrs (err -2)
[   59.677658] kvm_intel: Unknown symbol kvm_get_running_vcpu (err -2)
[   59.684480] kvm_intel: Unknown symbol kvm_vcpu_read_guest_page (err -2)
[   59.691696] kvm_intel: Unknown symbol kvm_set_cpu_caps (err -2)
[   59.698154] kvm_intel: Unknown symbol kvm_vcpu_exit_request (err -2)
[   59.705094] kvm_intel: Unknown symbol host_efer (err -2)
[   59.710885] kvm_intel: Unknown symbol kvm_max_tsc_scaling_ratio (err -2)
[   59.718188] kvm_intel: Unknown symbol __SCT__tp_func_kvm_pml_full (err -2)
[   59.725686] kvm_intel: Unknown symbol pdptrs_changed (err -2)
[   59.731961] kvm_intel: Unknown symbol kvm_set_cr4 (err -2)
[   59.737952] kvm_intel: Unknown symbol __SCK__tp_func_kvm_exit (err -2)
[   59.745071] kvm_intel: Unknown symbol kvm_release_page_clean (err -2)
[   59.752103] kvm_intel: Unknown symbol kvm_handle_page_fault (err -2)
[   59.759036] kvm_intel: Unknown symbol kvm_cpu_caps (err -2)
[   59.765097] kvm_intel: Unknown symbol kvm_spec_ctrl_test_value (err -2)
[   59.772306] kvm_intel: Unknown symbol __SCT__tp_func_kvm_exit (err -2)
[   59.779430] kvm_intel: Unknown symbol kvm_apic_clear_irr (err -2)
[   59.786085] kvm_intel: Unknown symbol __x86_set_memory_region (err -2)
[   59.793206] kvm_intel: Unknown symbol kvm_load_guest_xsave_state (err -2)
[   59.800603] kvm_intel: Unknown symbol kvm_set_cr0 (err -2)
[   59.806594] kvm_intel: Unknown symbol kvm_set_cr8 (err -2)
[   59.812582] kvm_intel: Unknown symbol kvm_get_dr (err -2)
[   59.818484] kvm_intel: Unknown symbol kvm_mmu_page_fault (err -2)
[   59.825133] kvm_intel: Unknown symbol __SCK__tp_func_kvm_nested_vmexit (err -2)
[   59.833104] kvm_intel: Unknown symbol kvm_emulate_instruction (err -2)
[   59.840231] kvm_intel: Unknown symbol __SCK__tp_func_kvm_pml_full (err -2)
[   59.847721] kvm_intel: Unknown symbol kvm_mtrr_get_guest_memory_type (err -2)
[   59.855503] kvm_intel: Unknown symbol kvm_mmu_reset_context (err -2)
[   59.862437] kvm_intel: Unknown symbol kvm_get_apic_mode (err -2)
[   59.868996] kvm_intel: Unknown symbol kvm_vcpu_read_guest (err -2)
[   59.875739] kvm_intel: Unknown symbol kvm_vcpu_on_spin (err -2)
[   59.882196] kvm_intel: Unknown symbol __SCK__tp_func_kvm_fast_mmio (err -2)
[   59.889786] kvm_intel: Unknown symbol kvm_read_guest (err -2)
[   59.896047] kvm_intel: Unknown symbol kvm_define_user_return_msr (err -2)
[   59.903453] kvm_intel: Unknown symbol kvm_rebooting (err -2)
[   59.909631] kvm_intel: Unknown symbol kvm_get_rflags (err -2)
[   59.915896] kvm_intel: Unknown symbol kvm_queue_exception_e (err -2)
[   59.922833] kvm_intel: Unknown symbol __SCT__tp_func_kvm_inj_virq (err -2)
[   59.930333] kvm_intel: Unknown symbol current_vcpu (err -2)
[   59.936417] kvm_intel: Unknown symbol __SCT__tp_func_kvm_write_tsc_offset (err -2)
[   59.944673] kvm_intel: Unknown symbol __tracepoint_kvm_exit (err -2)
[   59.951606] kvm_intel: Unknown symbol kvm_emulate_cpuid (err -2)
[   59.958163] kvm_intel: Unknown symbol kvm_emulate_wrmsr (err -2)
[   59.964700] kvm_intel: Unknown symbol __SCK__tp_func_kvm_inj_virq (err -2)
[   59.972201] kvm_intel: Unknown symbol kvm_apic_set_eoi_accelerated (err -2)
[   59.979798] kvm_intel: Unknown symbol kvm_vcpu_kick (err -2)
[   59.985977] kvm_intel: Unknown symbol kvm_inject_realmode_interrupt (err -2)
[   59.993663] kvm_intel: Unknown symbol kvm_mmu_invlpg (err -2)
[   59.999922] kvm_intel: Unknown symbol kvm_fast_pio (err -2)
[   60.006008] kvm_intel: Unknown symbol __SCK__tp_func_kvm_ple_window_update (err -2)
[   60.014352] kvm_intel: Unknown symbol kvm_set_msr_common (err -2)
[   60.021002] kvm_intel: Unknown symbol __SCT__tp_func_kvm_nested_vmenter_failed (err -2)
[   60.029732] kvm_intel: Unknown symbol __SCK__tp_func_kvm_nested_vmexit_inject (err -2)
[   60.038336] kvm_intel: Unknown symbol kvm_intr_is_single_vcpu (err -2)
[   60.045456] kvm_intel: Unknown symbol kvm_apic_has_interrupt (err -2)
[   60.052484] kvm_intel: Unknown symbol __SCT__tp_func_kvm_ple_window_update (err -2)
[   60.060834] kvm_intel: Unknown symbol __SCK__tp_func_kvm_write_tsc_offset (err -2)
[   60.069092] kvm_intel: Unknown symbol __tracepoint_kvm_nested_vmexit_inject (err -2)
[   60.077538] kvm_intel: Unknown symbol __SCT__tp_func_kvm_page_fault (err -2)
[   60.085225] kvm_intel: Unknown symbol kvm_require_dr (err -2)
[   60.091492] kvm_intel: Unknown symbol kvm_skip_emulated_instruction (err -2)
[   60.099177] kvm_intel: Unknown symbol kvm_inject_page_fault (err -2)
[   60.106094] kvm_intel: Unknown symbol kvm_cpu_get_interrupt (err -2)
[   60.113034] kvm_intel: Unknown symbol kvm_vcpu_write_guest (err -2)
[   60.119870] kvm_intel: Unknown symbol kvm_complete_insn_gp (err -2)
[   60.126696] kvm_intel: Unknown symbol kvm_mmu_set_mask_ptes (err -2)
[   60.133614] kvm_intel: Unknown symbol kvm_apic_write_nodecode (err -2)
[   60.140728] kvm_intel: Unknown symbol kvm_lapic_hv_timer_in_use (err -2)
[   60.148032] kvm_intel: Unknown symbol allow_smaller_maxphyaddr (err -2)
[   60.161901] kvm_intel: Unknown symbol __tracepoint_kvm_ple_window_update (err -2)
[   60.170619] kvm_intel: Unknown symbol vcpu_put (err -2)
[   60.176407] kvm_intel: Unknown symbol kvm_arch_has_assigned_device (err -2)
[   60.185270] kvm_intel: Unknown symbol kvm_rdpmc (err -2)
[   60.191162] kvm_intel: Unknown symbol kvm_vcpu_mark_page_dirty (err -2)
[   60.199646] kvm_intel: Unknown symbol kvm_vcpu_halt (err -2)
[   60.205914] kvm_intel: Unknown symbol kvm_clear_guest_page (err -2)
[   60.214015] kvm_intel: Unknown symbol kvm_requeue_exception (err -2)
[   60.221039] kvm_intel: Unknown symbol reprogram_counter (err -2)
[   60.228861] kvm_intel: Unknown symbol __SCK__tp_func_kvm_nested_vmenter_failed (err -2)
[   60.237676] kvm_intel: Unknown symbol kvm_exit (err -2)
[   60.244642] kvm_intel: Unknown symbol kvm_init (err -2)
[   60.250448] kvm_intel: Unknown symbol kvm_deliver_exception_payload (err -2)
[   60.259395] kvm_intel: Unknown symbol kvm_set_msr (err -2)
[   60.265463] kvm_intel: Unknown symbol kvm_default_tsc_scaling_ratio (err -2)
[   60.274411] kvm_intel: Unknown symbol __tracepoint_kvm_nested_vmexit (err -2)
[   60.282287] kvm_intel: Unknown symbol enable_vmware_backdoor (err -2)
[   60.290573] kvm_intel: Unknown symbol kvm_enable_efer_bits (err -2)
[   60.297512] kvm_intel: Unknown symbol __SCT__tp_func_kvm_nested_vmexit (err -2)
[   60.306752] kvm_intel: Unknown symbol __kvm_request_immediate_exit (err -2)
[   60.314434] kvm_intel: Unknown symbol kvm_lapic_expired_hv_timer (err -2)
[   60.323099] kvm_intel: Unknown symbol kvm_fixup_and_inject_pf_error (err -2)
[   60.330865] kvm_intel: Unknown symbol gfn_to_page (err -2)
[   60.338115] kvm_intel: Unknown symbol __SCK__tp_func_kvm_cr (err -2)
[   60.345137] kvm_intel: Unknown symbol kvm_probe_user_return_msr (err -2)
[   60.353714] kvm_intel: Unknown symbol kvm_vcpu_write_guest_page (err -2)
[   60.361112] kvm_intel: Unknown symbol kvm_no_apic_vcpu (err -2)
[   60.368829] kvm_intel: Unknown symbol handle_ud (err -2)
[   60.374707] kvm_intel: Unknown symbol kvm_mmu_new_pgd (err -2)
[   60.382345] kvm_intel: Unknown symbol reprogram_fixed_counter (err -2)
[   60.389549] kvm_intel: Unknown symbol __tracepoint_kvm_nested_vmenter_failed (err -2)
[   60.399356] kvm_intel: Unknown symbol kvm_get_msr_common (err -2)
[   60.406097] kvm_intel: Unknown symbol kvm_mmu_slot_largepage_remove_write_access (err -2)
[   60.416276] kvm_intel: Unknown symbol __tracepoint_kvm_fast_mmio (err -2)
[   60.423773] kvm_intel: Unknown symbol kvm_arch_has_noncoherent_dma (err -2)
[   60.432622] kvm_intel: Unknown symbol kvm_hv_get_assist_page (err -2)
[   60.439741] kvm_intel: Unknown symbol kvm_emulate_halt (err -2)
[   60.447471] kvm_intel: Unknown symbol kvm_set_apic_base (err -2)
[   60.454118] kvm_intel: Unknown symbol supported_xss (err -2)
[   60.461563] kvm_intel: Unknown symbol kvm_vcpu_map (err -2)
[   60.467737] kvm_intel: Unknown symbol kvm_msr_allowed (err -2)
[   60.475369] kvm_intel: Unknown symbol kvm_lapic_find_highest_irr (err -2)
[   60.482867] kvm_intel: Unknown symbol kvm_set_xcr (err -2)
[   60.490118] kvm_intel: Unknown symbol kvm_wait_lapic_expire (err -2)
[   60.497141] kvm_intel: Unknown symbol reprogram_gp_counter (err -2)
[   60.505244] kvm_intel: Unknown symbol kvm_write_guest_virt_system (err -2)
[   60.512832] kvm_intel: Unknown symbol kvm_find_cpuid_entry (err -2)
[   60.520935] kvm_intel: Unknown symbol kvm_task_switch (err -2)
[   60.527397] kvm_intel: Unknown symbol __SCT__tp_func_kvm_fast_mmio (err -2)
[   60.536238] kvm_intel: Unknown symbol kvm_read_guest_virt (err -2)
[   60.543060] kvm_intel: Unknown symbol kvm_vcpu_gfn_to_page (err -2)
[   60.551165] kvm_intel: Unknown symbol kvm_write_guest (err -2)
[   60.557613] kvm_intel: Unknown symbol __tracepoint_kvm_cr (err -2)
[   60.565627] kvm_intel: Unknown symbol kvm_io_bus_write (err -2)
[   60.572177] kvm_intel: Unknown symbol kvm_mmu_set_mmio_spte_mask (err -2)
[   60.580847] kvm_intel: Unknown symbol kvm_mmu_clear_dirty_pt_masked (err -2)
[   60.580850] kvm_intel: Unknown symbol kvm_set_user_return_msr (err -2)
[   60.580853] kvm_intel: Unknown symbol kvm_require_cpl (err -2)
[   60.603461] kvm_intel: Unknown symbol __SCT__tp_func_kvm_cr (err -2)
[   60.611657] kvm_intel: Unknown symbol kvm_init_shadow_ept_mmu (err -2)
[   60.618877] kvm_intel: Unknown symbol __tracepoint_kvm_pml_full (err -2)
[   60.627447] kvm_intel: Unknown symbol kvm_requeue_exception_e (err -2)
[   60.634667] kvm_intel: Unknown symbol kvm_lmsw (err -2)
[   60.641633] kvm_intel: Unknown symbol kvm_lapic_set_eoi (err -2)
[   60.648275] kvm_intel: Unknown symbol kvm_queue_exception (err -2)
[   60.656282] kvm_intel: Unknown symbol kvm_lapic_switch_to_hv_timer (err -2)
[   60.663970] kvm_intel: Unknown symbol kvm_emulate_rdmsr (err -2)
[   60.671793] kvm_intel: Unknown symbol __tracepoint_kvm_write_tsc_offset (err -2)
[   60.679950] kvm_intel: Unknown symbol kvm_vcpu_is_reset_bsp (err -2)
[   60.688130] kvm_intel: Unknown symbol __tracepoint_kvm_pi_irte_update (err -2)
[   60.696084] kvm_intel: Unknown symbol kvm_apicv_init (err -2)
[   60.703621] kvm_intel: Unknown symbol __SCT__tp_func_kvm_nested_vmexit_inject (err -2)
[   60.712335] kvm_intel: Unknown symbol kvm_vcpu_unmap (err -2)
[   60.719869] kvm_intel: Unknown symbol kvm_write_guest_page (err -2)
[   60.726800] kvm_intel: Unknown symbol kvm_valid_efer (err -2)
[   60.734336] kvm_intel: Unknown symbol supported_xcr0 (err -2)
[   60.740701] kvm_intel: Unknown symbol __SCK__tp_func_kvm_pi_irte_update (err -2)
[   60.750021] kvm_intel: Unknown symbol kvm_set_rflags (err -2)
[   60.756370] kvm_intel: Unknown symbol kvm_mmu_slot_leaf_clear_dirty (err -2)
[   60.765300] kvm_intel: Unknown symbol kvm_tsc_scaling_ratio_frac_bits (err -2)
[   60.773262] kvm_intel: Unknown symbol kvm_mce_cap_supported (err -2)
[   60.781455] kvm_intel: Unknown symbol kvm_handle_invpcid (err -2)
[   60.788199] kvm_intel: Unknown symbol kvm_load_host_xsave_state (err -2)
[   60.796771] kvm_intel: Unknown symbol __tracepoint_kvm_page_fault (err -2)
[   60.796774] kvm_intel: Unknown symbol kvm_mmu_free_roots (err -2)
[   60.812287] kvm_intel: Unknown symbol kvm_mmu_slot_set_dirty (err -2)
[   60.819404] kvm_intel: Unknown symbol kvm_queue_exception_p (err -2)
[   60.827602] kvm_intel: Unknown symbol kvm_read_l1_tsc (err -2)
[   60.834054] kvm_intel: Unknown symbol __tracepoint_kvm_inj_virq (err -2)
[   60.842627] kvm_intel: Unknown symbol kvm_cpu_has_interrupt (err -2)
[   60.849652] kvm_intel: Unknown symbol __kvm_apic_update_irr (err -2)
[   60.857853] kvm_intel: Unknown symbol handle_fastpath_set_msr_irqoff (err -2)
[   60.865727] kvm_intel: Unknown symbol kvm_apic_update_ppr (err -2)
[   60.873735] kvm_intel: Unknown symbol kvm_configure_mmu (err -2)
[   60.880387] kvm_intel: Unknown symbol kvm_apic_update_irr (err -2)
[   60.888393] kvm_intel: Unknown symbol kvm_init_mmu (err -2)
[   60.894563] kvm_intel: Unknown symbol kvm_emulate_wbinvd (err -2)
[   60.902474] kvm_intel: Unknown symbol kvm_set_cr3 (err -2)
[   60.908562] kvm_intel: Unknown symbol kvm_lapic_switch_to_sw_timer (err -2)
[   60.917412] kvm_intel: Unknown symbol __SCK__tp_func_kvm_page_fault (err -2)
[   60.925191] kvm_intel: Unknown symbol kvm_get_cr8 (err -2)
[   60.932449] kvm_intel: Unknown symbol kvm_x86_ops (err -2)
[   60.938533] kvm_intel: Unknown symbol __SCT__tp_func_kvm_pi_irte_update (err -2)
[   60.947863] kvm_intel: Unknown symbol vcpu_load (err -2)
[   60.953739] kvm_intel: Unknown symbol kvm_handle_memory_failure (err -2)
[   60.962313] kvm_intel: Unknown symbol kvm_set_dr (err -2)
[   60.968283] kvm_intel: Unknown symbol kvm_set_msi_irq (err -2)
[   60.975919] kvm_intel: Unknown symbol kvm_emulate_hypercall (err -2)
[   60.982936] kvm_intel: Unknown symbol kvm_spurious_fault (err -2)
[   60.990847] kvm_intel: Unknown symbol kvm_has_tsc_control (err -2)
[   60.997658] kvm_intel: Unknown symbol kvm_get_linear_rip (err -2)
[   61.005579] kvm_intel: Unknown symbol kvm_get_msr (err -2)
[   61.011647] kvm_intel: Unknown symbol load_pdptrs (err -2)
[   61.018903] kvm_intel: Unknown symbol kvm_get_running_vcpu (err -2)
[   61.025834] kvm_intel: Unknown symbol kvm_vcpu_read_guest_page (err -2)
[   61.034314] kvm_intel: Unknown symbol kvm_set_cpu_caps (err -2)
[   61.040853] kvm_intel: Unknown symbol kvm_vcpu_exit_request (err -2)
[   61.049055] kvm_intel: Unknown symbol host_efer (err -2)
[   61.054935] kvm_intel: Unknown symbol kvm_max_tsc_scaling_ratio (err -2)
[   61.063503] kvm_intel: Unknown symbol __SCT__tp_func_kvm_pml_full (err -2)
[   61.071085] kvm_intel: Unknown symbol pdptrs_changed (err -2)
[   61.078621] kvm_intel: Unknown symbol kvm_set_cr4 (err -2)
[   61.084703] kvm_intel: Unknown symbol __SCK__tp_func_kvm_exit (err -2)
[   61.093093] kvm_intel: Unknown symbol kvm_release_page_clean (err -2)
[   61.100200] kvm_intel: Unknown symbol kvm_handle_page_fault (err -2)
[   61.108401] kvm_intel: Unknown symbol kvm_cpu_caps (err -2)
[   61.114558] kvm_intel: Unknown symbol kvm_spec_ctrl_test_value (err -2)
[   61.123045] kvm_intel: Unknown symbol __SCT__tp_func_kvm_exit (err -2)
[   61.130249] kvm_intel: Unknown symbol kvm_apic_clear_irr (err -2)
[   61.138164] kvm_intel: Unknown symbol __x86_set_memory_region (err -2)
[   61.145377] kvm_intel: Unknown symbol kvm_load_guest_xsave_state (err -2)
[   61.154047] kvm_intel: Unknown symbol kvm_set_cr0 (err -2)
[   61.160134] kvm_intel: Unknown symbol kvm_set_cr8 (err -2)
[   61.167384] kvm_intel: Unknown symbol kvm_get_dr (err -2)
[   61.173358] kvm_intel: Unknown symbol kvm_mmu_page_fault (err -2)
[   61.181273] kvm_intel: Unknown symbol __SCK__tp_func_kvm_nested_vmexit (err -2)
[   61.189339] kvm_intel: Unknown symbol kvm_emulate_instruction (err -2)
[   61.197725] kvm_intel: Unknown symbol __SCK__tp_func_kvm_pml_full (err -2)
[   61.205312] kvm_intel: Unknown symbol kvm_mtrr_get_guest_memory_type (err -2)
[   61.214352] kvm_intel: Unknown symbol kvm_mmu_reset_context (err -2)
[   61.221395] kvm_intel: Unknown symbol kvm_get_apic_mode (err -2)
[   61.229215] kvm_intel: Unknown symbol kvm_vcpu_read_guest (err -2)
[   61.236051] kvm_intel: Unknown symbol kvm_vcpu_on_spin (err -2)
[   61.243780] kvm_intel: Unknown symbol __SCK__tp_func_kvm_fast_mmio (err -2)
[   61.251467] kvm_intel: Unknown symbol kvm_read_guest (err -2)
[   61.259003] kvm_intel: Unknown symbol kvm_define_user_return_msr (err -2)
[   61.266491] kvm_intel: Unknown symbol kvm_rebooting (err -2)
[   61.273924] kvm_intel: Unknown symbol kvm_get_rflags (err -2)
[   61.280296] kvm_intel: Unknown symbol kvm_queue_exception_e (err -2)
[   61.288501] kvm_intel: Unknown symbol __SCT__tp_func_kvm_inj_virq (err -2)
[   61.296074] kvm_intel: Unknown symbol current_vcpu (err -2)
[   61.303423] kvm_intel: Unknown symbol __SCT__tp_func_kvm_write_tsc_offset (err -2)
[   61.311774] kvm_intel: Unknown symbol __tracepoint_kvm_exit (err -2)
[   61.319967] kvm_intel: Unknown symbol kvm_emulate_cpuid (err -2)
[   61.326600] kvm_intel: Unknown symbol kvm_emulate_wrmsr (err -2)
[   61.334423] kvm_intel: Unknown symbol __SCK__tp_func_kvm_inj_virq (err -2)
[   61.342016] kvm_intel: Unknown symbol kvm_apic_set_eoi_accelerated (err -2)
[   61.350876] kvm_intel: Unknown symbol kvm_vcpu_kick (err -2)
[   61.357144] kvm_intel: Unknown symbol kvm_inject_realmode_interrupt (err -2)
[   61.366089] kvm_intel: Unknown symbol kvm_mmu_invlpg (err -2)
[   61.372427] kvm_intel: Unknown symbol kvm_fast_pio (err -2)
[   61.379778] kvm_intel: Unknown symbol __SCK__tp_func_kvm_ple_window_update (err -2)
[   61.388217] kvm_intel: Unknown symbol kvm_set_msr_common (err -2)
[   61.396137] kvm_intel: Unknown symbol __SCT__tp_func_kvm_nested_vmenter_failed (err -2)
[   61.404917] kvm_intel: Unknown symbol __SCK__tp_func_kvm_nested_vmexit_inject (err -2)
[   61.414816] kvm_intel: Unknown symbol kvm_intr_is_single_vcpu (err -2)
[   61.422025] kvm_intel: Unknown symbol kvm_apic_has_interrupt (err -2)
[   61.430309] kvm_intel: Unknown symbol __SCT__tp_func_kvm_ple_window_update (err -2)
[   61.438754] kvm_intel: Unknown symbol __SCK__tp_func_kvm_write_tsc_offset (err -2)
[   61.448278] kvm_intel: Unknown symbol __tracepoint_kvm_nested_vmexit_inject (err -2)
[   61.456808] kvm_intel: Unknown symbol __SCT__tp_func_kvm_page_fault (err -2)
[   61.465762] kvm_intel: Unknown symbol kvm_require_dr (err -2)
[   61.472125] kvm_intel: Unknown symbol kvm_skip_emulated_instruction (err -2)
[   61.481079] kvm_intel: Unknown symbol kvm_inject_page_fault (err -2)
[   61.488095] kvm_intel: Unknown symbol kvm_cpu_get_interrupt (err -2)
[   61.496298] kvm_intel: Unknown symbol kvm_vcpu_write_guest (err -2)
[   61.503225] kvm_intel: Unknown symbol kvm_complete_insn_gp (err -2)
[   61.511323] kvm_intel: Unknown symbol kvm_mmu_set_mask_ptes (err -2)
[   61.518352] kvm_intel: Unknown symbol kvm_apic_write_nodecode (err -2)
[   61.526729] kvm_intel: Unknown symbol kvm_lapic_hv_timer_in_use (err -2)
[   61.534125] kvm_intel: Unknown symbol allow_smaller_maxphyaddr (err -2)
[   71.560849] printk: udevd: 11 output lines suppressed due to ratelimiting
[   71.585341] epyc7002_synobios: module license 'Synology Inc.' taints kernel.
[   71.593424] Disabling lock debugging due to kernel taint
[   71.599361] <redpill/bios_shim.c:210> Symbol section <00000000b80f1c03> @ vaddr<18446744072099508224> size[10584]
[   71.611828] <redpill/bios_shim.c:219> Symbol #0 in mfgBIOS "epyc7002_synobios" {}<0000000000000000>
[   71.621689] <redpill/bios_shim.c:219> Symbol #1 in mfgBIOS "epyc7002_synobios" {}<0000000063e45edd>
[   71.631531] <redpill/bios_shim.c:219> Symbol #2 in mfgBIOS "epyc7002_synobios" {}<0000000054f633d4>
[   71.641378] <redpill/bios_shim.c:219> Symbol #3 in mfgBIOS "epyc7002_synobios" {}<000000007566eebf>
[   71.651223] <redpill/bios_shim.c:219> Symbol #4 in mfgBIOS "epyc7002_synobios" {}<00000000e16a385e>
[   71.661079] <redpill/bios_shim.c:219> Symbol #5 in mfgBIOS "epyc7002_synobios" {}<00000000bd9d03f4>
[   71.670906] <redpill/bios_shim.c:219> Symbol #6 in mfgBIOS "epyc7002_synobios" {}<000000007090a4c2>
[   71.680751] <redpill/bios_shim.c:219> Symbol #7 in mfgBIOS "epyc7002_synobios" {}<000000006a709aaa>
[   71.690605] <redpill/bios_shim.c:219> Symbol #8 in mfgBIOS "epyc7002_synobios" {__UNIQUE_ID_depends105}<00000000a74c85a2>
[   71.702532] <redpill/bios_shim.c:219> Symbol #9 in mfgBIOS "epyc7002_synobios" {__UNIQUE_ID_retpoline104}<0000000084f2774f>
[   71.714644] <redpill/bios_shim.c:219> Symbol #10 in mfgBIOS "epyc7002_synobios" {__UNIQUE_ID_name103}<000000001b2713fb>
[   71.726390] <redpill/bios_shim.c:219> Symbol #11 in mfgBIOS "epyc7002_synobios" {__UNIQUE_ID_vermagic102}<00000000663c605a>
[   71.738497] <redpill/bios_shim.c:219> Symbol #12 in mfgBIOS "epyc7002_synobios" {_note_7}<00000000c876667d>
[   71.749097] <redpill/bios_shim.c:219> Symbol #13 in mfgBIOS "epyc7002_synobios" {__FUNCTION__.42208}<000000007566eebf>
[   71.760734] <redpill/bios_shim.c:219> Symbol #14 in mfgBIOS "epyc7002_synobios" {check_gpio_consistency.cold.1}<0000000054f633d4>
[   71.773413] <redpill/bios_shim.c:219> Symbol #15 in mfgBIOS "epyc7002_synobios" {SYNO_CTRL_FAN_RESISTOR.cold.2}<00000000c53e53e5>
[   71.786103] <redpill/bios_shim.c:219> Symbol #16 in mfgBIOS "epyc7002_synobios" {SYNO_CTRL_FAN_STATUS_GET.cold.3}<0000000057897c49>
[   71.798986] <redpill/bios_shim.c:219> Symbol #17 in mfgBIOS "epyc7002_synobios" {SYNO_HDD_LED_SET.cold.4}<00000000d86026a5>
[   71.811093] <redpill/bios_shim.c:219> Symbol #18 in mfgBIOS "epyc7002_synobios" {SYNO_COPY_BUTTON_GPIO_GET.cold.5}<00000000b4b72ee2>
[   71.824046] <redpill/bios_shim.c:219> Symbol #19 in mfgBIOS "epyc7002_synobios" {SYNO_ENABLE_HDD_LED.cold.6}<000000002ac31ea5>
[   71.836445] <redpill/bios_shim.c:219> Symbol #20 in mfgBIOS "epyc7002_synobios" {SYNO_ENABLE_PHY_LED.cold.7}<00000000996d16d2>
[   71.848837] <redpill/bios_shim.c:219> Symbol #21 in mfgBIOS "epyc7002_synobios" {SYNO_BUZZER_BUTTON_GPIO_GET.cold.8}<00000000e136eb38>
[   71.862004] <redpill/bios_shim.c:219> Symbol #22 in mfgBIOS "epyc7002_synobios" {SYNO_CTRL_BUZZER_MUTE_SET.cold.9}<0000000086392877>
[   71.874967] <redpill/bios_shim.c:219> Symbol #23 in mfgBIOS "epyc7002_synobios" {.LC6}<000000002ba6f5c6>
[   71.885285] <redpill/bios_shim.c:219> Symbol #24 in mfgBIOS "epyc7002_synobios" {__kstrtab_save_char_from_uart}<00000000bb5e2955>
[   71.897964] <redpill/bios_shim.c:219> Symbol #25 in mfgBIOS "epyc7002_synobios" {__kstrtabns_save_char_from_uart}<00000000781bf222>
[   71.910828] <redpill/bios_shim.c:219> Symbol #26 in mfgBIOS "epyc7002_synobios" {__ksymtab_save_char_from_uart}<0000000051696743>
[   71.923498] <redpill/bios_shim.c:219> Symbol #27 in mfgBIOS "epyc7002_synobios" {__kstrtab_save_current_data_from_uart}<0000000031b520f7>
[   71.936937] <redpill/bios_shim.c:219> Symbol #28 in mfgBIOS "epyc7002_synobios" {__kstrtabns_save_current_data_from_uart}<00000000107fc723>
[   71.950561] <redpill/bios_shim.c:219> Symbol #29 in mfgBIOS "epyc7002_synobios" {__ksymtab_save_current_data_from_uart}<000000008406813d>
[   71.963985] <redpill/bios_shim.c:219> Symbol #30 in mfgBIOS "epyc7002_synobios" {__kstrtab_synobios_lock_ttyS_protection}<000000000f4ae302>
[   71.977614] <redpill/bios_shim.c:219> Symbol #31 in mfgBIOS "epyc7002_synobios" {__kstrtabns_synobios_lock_ttyS_protection}<0000000019e20817>
[   71.991421] <redpill/bios_shim.c:219> Symbol #32 in mfgBIOS "epyc7002_synobios" {__ksymtab_synobios_lock_ttyS_protection}<00000000bb62f659>
[   72.005059] <redpill/bios_shim.c:219> Symbol #33 in mfgBIOS "epyc7002_synobios" {__kstrtab_synobios_lock_ttyS_current}<00000000a3da5ace>
[   72.018393] <redpill/bios_shim.c:219> Symbol #34 in mfgBIOS "epyc7002_synobios" {__kstrtabns_synobios_lock_ttyS_current}<0000000075ced34d>
[   72.031933] <redpill/bios_shim.c:219> Symbol #35 in mfgBIOS "epyc7002_synobios" {__ksymtab_synobios_lock_ttyS_current}<00000000c48b7d92>
[   72.045269] <redpill/bios_shim.c:219> Symbol #36 in mfgBIOS "epyc7002_synobios" {__kstrtab_try_wakeup_waiting_microp}<000000001f5c7a0e>
[   72.058517] <redpill/bios_shim.c:219> Symbol #37 in mfgBIOS "epyc7002_synobios" {__kstrtabns_try_wakeup_waiting_microp}<000000001cdce5b8>
[   72.071952] <redpill/bios_shim.c:219> Symbol #38 in mfgBIOS "epyc7002_synobios" {__ksymtab_try_wakeup_waiting_microp}<000000004527c079>
[   72.085198] <redpill/bios_shim.c:219> Symbol #39 in mfgBIOS "epyc7002_synobios" {syno_ttyS_read}<000000000a90bf48>
[   72.096470] <redpill/bios_shim.c:219> Symbol #40 in mfgBIOS "epyc7002_synobios" {syno_ttyS_read.cold.8}<0000000091541f6f>
[   72.108382] <redpill/bios_shim.c:219> Symbol #41 in mfgBIOS "epyc7002_synobios" {state.29417}<00000000711264b5>
[   72.119358] <redpill/bios_shim.c:219> Symbol #42 in mfgBIOS "epyc7002_synobios" {save_bytes.29416}<0000000039fa483f>
[   72.130800] <redpill/bios_shim.c:219> Symbol #43 in mfgBIOS "epyc7002_synobios" {state.29435}<00000000fa010d19>
[   72.141791] <redpill/bios_shim.c:219> Symbol #44 in mfgBIOS "epyc7002_synobios" {syno_ttyS_set_termios.cold.9}<00000000e32c010a>
[   72.154372] <redpill/bios_shim.c:219> Symbol #45 in mfgBIOS "epyc7002_synobios" {__key.29453}<00000000fa010d19>
[   72.165339] <redpill/bios_shim.c:219> Symbol #46 in mfgBIOS "epyc7002_synobios" {__key.11921}<00000000fa010d19>
[   72.176309] <redpill/bios_shim.c:219> Symbol #47 in mfgBIOS "epyc7002_synobios" {syno_ttyS_open.cold.10}<000000009943225f>
[   72.188331] <redpill/bios_shim.c:219> Symbol #48 in mfgBIOS "epyc7002_synobios" {syno_ttyS_write_with_length.cold.11}<0000000041e42068>
[   72.201580] <redpill/bios_shim.c:219> Symbol #49 in mfgBIOS "epyc7002_synobios" {synobios_lock_ttyS_write.cold.12}<0000000086a80e91>
[   72.214558] <redpill/bios_shim.c:219> Symbol #50 in mfgBIOS "epyc7002_synobios" {syno_ttyS_close.cold.13}<00000000063973f6>
[   72.226649] <redpill/bios_shim.c:219> Symbol #51 in mfgBIOS "epyc7002_synobios" {__kstrtab_syno_append_shutdown_hook}<00000000de11b711>
[   72.239891] <redpill/bios_shim.c:219> Symbol #52 in mfgBIOS "epyc7002_synobios" {__kstrtabns_syno_append_shutdown_hook}<00000000e5a839fd>
[   72.253324] <redpill/bios_shim.c:219> Symbol #53 in mfgBIOS "epyc7002_synobios" {__ksymtab_syno_append_shutdown_hook}<00000000af9ccc26>
[   72.266575] <redpill/bios_shim.c:219> Symbol #54 in mfgBIOS "epyc7002_synobios" {syno_shutdown_hooks}<00000000ef740db5>
[   72.278330] <redpill/bios_shim.c:219> Symbol #55 in mfgBIOS "epyc7002_synobios" {synobios_read_proc_cpu_arch_open}<00000000cfc18709>
[   72.291281] <redpill/bios_shim.c:219> Symbol #56 in mfgBIOS "epyc7002_synobios" {synobios_read_proc_cpu_arch}<00000000a81b029f>
[   72.303775] <redpill/bios_shim.c:219> Symbol #57 in mfgBIOS "epyc7002_synobios" {synobios_read_proc_crypto_hw_open}<000000003ae09d9a>
[   72.316835] <redpill/bios_shim.c:219> Symbol #58 in mfgBIOS "epyc7002_synobios" {synobios_read_proc_crypto_hw}<0000000091d1fee6>
[   72.329417] <redpill/bios_shim.c:219> Symbol #59 in mfgBIOS "epyc7002_synobios" {synobios_read_proc_platform_open}<00000000171b06b8>
[   72.342376] <redpill/bios_shim.c:219> Symbol #60 in mfgBIOS "epyc7002_synobios" {synobios_read_proc_platform_name}<00000000b8be309a>
[   72.355333] <redpill/bios_shim.c:219> Symbol #61 in mfgBIOS "epyc7002_synobios" {gSynoCPUMapping}<00000000bc39b5b4>
[   72.366688] <redpill/bios_shim.c:219> Symbol #62 in mfgBIOS "epyc7002_synobios" {synobios_read_proc_cpu_arch.cold.17}<0000000009903aa6>
[   72.379930] <redpill/bios_shim.c:219> Symbol #63 in mfgBIOS "epyc7002_synobios" {gSynoCRYPTOMapping}<0000000034168a01>
[   72.391576] <redpill/bios_shim.c:219> Symbol #64 in mfgBIOS "epyc7002_synobios" {synobios_read_proc_crypto_hw.cold.18}<00000000ab266c32>
[   72.404917] <redpill/bios_shim.c:219> Symbol #65 in mfgBIOS "epyc7002_synobios" {synobios_record_event_new.isra.4.part.5}<00000000fc4358e5>
[   72.418536] <redpill/bios_shim.c:219> Symbol #66 in mfgBIOS "epyc7002_synobios" {scSynoBios}<000000006431d261>
[   72.429401] <redpill/bios_shim.c:219> Symbol #67 in mfgBIOS "epyc7002_synobios" {synobios_error_btrfs_meta_corrupted_event}<00000000383df27e>
[   72.443212] <redpill/bios_shim.c:219> Symbol #68 in mfgBIOS "epyc7002_synobios" {synobios_error_fs_btrfs_event}<00000000ebe20633>
[   72.455887] <redpill/bios_shim.c:219> Symbol #69 in mfgBIOS "epyc7002_synobios" {synobios_error_fs_event}<0000000058aba018>
[   72.467996] <redpill/bios_shim.c:219> Symbol #70 in mfgBIOS "epyc7002_synobios" {synobios_autoremap_raid_event}<00000000bea8aec4>
[   72.480664] <redpill/bios_shim.c:219> Symbol #71 in mfgBIOS "epyc7002_synobios" {synobios_record_raid_event}<00000000b53bdc8c>
[   72.493056] <redpill/bios_shim.c:219> Symbol #72 in mfgBIOS "epyc7002_synobios" {synobios_event_ecc_notification}<0000000037adea91>
[   72.505921] <redpill/bios_shim.c:219> Symbol #73 in mfgBIOS "epyc7002_synobios" {synobios_raid_sync_event}<0000000025773cf9>
[   72.518110] <redpill/bios_shim.c:219> Symbol #74 in mfgBIOS "epyc7002_synobios" {synobios_error_oom_event}<00000000079f7cbe>
[   72.530305] <redpill/bios_shim.c:219> Symbol #75 in mfgBIOS "epyc7002_synobios" {synobios_poll}<0000000081d8e030>
[   72.541471] <redpill/bios_shim.c:219> Symbol #76 in mfgBIOS "epyc7002_synobios" {synobios_ops}<00000000fc547b9f>
[   72.552544] <redpill/bios_shim.c:219> Symbol #77 in mfgBIOS "epyc7002_synobios" {last_jiffies.40930}<000000007090a4c2>
[   72.564169] <redpill/bios_shim.c:219> Symbol #78 in mfgBIOS "epyc7002_synobios" {buzzer_press_count.40931}<0000000036a0a8ec>
[   72.576367] <redpill/bios_shim.c:219> Symbol #79 in mfgBIOS "epyc7002_synobios" {micropLogSwitch}<00000000c414c9e2>
[   72.587718] <redpill/bios_shim.c:219> Symbol #80 in mfgBIOS "epyc7002_synobios" {synobios_event_handler.cold.19}<00000000651d3c29>
[   72.600480] <redpill/bios_shim.c:219> Symbol #81 in mfgBIOS "epyc7002_synobios" {synobios_rtc_init.cold.20}<0000000011963d40>
[   72.612773] <redpill/bios_shim.c:219> Symbol #82 in mfgBIOS "epyc7002_synobios" {card_detect_proc_ops}<00000000cfe433a9>
[   72.624607] <redpill/bios_shim.c:219> Symbol #83 in mfgBIOS "epyc7002_synobios" {add_card_detect_proc.cold.21}<00000000bd92b49e>
[   72.637195] <redpill/bios_shim.c:219> Symbol #84 in mfgBIOS "epyc7002_synobios" {synobios_ioctl}<000000007d2238bc>
[   72.648452] <redpill/bios_shim.c:219> Symbol #85 in mfgBIOS "epyc7002_synobios" {check_fan}<00000000e2384ff5>
[   72.659213] <redpill/bios_shim.c:219> Symbol #86 in mfgBIOS "epyc7002_synobios" {sys_status_lock}<0000000089aa425f>
[   72.670571] <redpill/bios_shim.c:219> Symbol #87 in mfgBIOS "epyc7002_synobios" {pgSysStatus}<00000000e79f1c45>
[   72.681554] <redpill/bios_shim.c:219> Symbol #88 in mfgBIOS "epyc7002_synobios" {LedSetLock}<00000000aa6f4d16>
[   72.692437] <redpill/bios_shim.c:219> Symbol #89 in mfgBIOS "epyc7002_synobios" {synobios_ioctl.cold.22}<00000000b6de3829>
[   72.704458] <redpill/bios_shim.c:219> Symbol #90 in mfgBIOS "epyc7002_synobios" {__FUNCTION__.40986}<00000000104ae649>
[   72.716087] <redpill/bios_shim.c:219> Symbol #91 in mfgBIOS "epyc7002_synobios" {__func__.41047}<000000001dd2d3e0>
[   72.727341] <redpill/bios_shim.c:219> Symbol #92 in mfgBIOS "epyc7002_synobios" {__key.41328}<0000000036a0a8ec>
[   72.738326] <redpill/bios_shim.c:219> Symbol #93 in mfgBIOS "epyc7002_synobios" {__key.41311}<0000000036a0a8ec>
[   72.749310] <redpill/bios_shim.c:219> Symbol #94 in mfgBIOS "epyc7002_synobios" {synobios_init.cold.23}<000000008b962459>
[   72.761218] <redpill/bios_shim.c:219> Symbol #95 in mfgBIOS "epyc7002_synobios" {synobios_read_proc_cpu_arch_ops}<00000000549b2b7d>
[   72.774084] <redpill/bios_shim.c:219> Symbol #96 in mfgBIOS "epyc7002_synobios" {synobios_read_proc_crypto_hw_ops}<000000008824997e>
[   72.787063] <redpill/bios_shim.c:219> Symbol #97 in mfgBIOS "epyc7002_synobios" {synobios_read_proc_platform_ops}<00000000108bcbec>
[   72.799914] <redpill/bios_shim.c:219> Symbol #98 in mfgBIOS "epyc7002_synobios" {system_mode}<00000000e9ae1f47>
[   72.810892] <redpill/bios_shim.c:219> Symbol #99 in mfgBIOS "epyc7002_synobios" {gSynoModelMapping}<00000000251c194e>
[   72.822435] <redpill/bios_shim.c:219> Symbol #100 in mfgBIOS "epyc7002_synobios" {synobios_cleanup.cold.24}<000000000218ce02>
[   72.834736] <redpill/bios_shim.c:219> Symbol #101 in mfgBIOS "epyc7002_synobios" {__UNIQUE_ID_license291}<0000000030c0ddb1>
[   72.846834] <redpill/bios_shim.c:219> Symbol #102 in mfgBIOS "epyc7002_synobios" {__UNIQUE_ID_description290}<000000001f901135>
[   72.859322] <redpill/bios_shim.c:219> Symbol #103 in mfgBIOS "epyc7002_synobios" {__UNIQUE_ID_author289}<00000000d623d739>
[   72.871341] <redpill/bios_shim.c:219> Symbol #104 in mfgBIOS "epyc7002_synobios" {__UNIQUE_ID_system_mode282}<000000008df0484f>
[   72.883819] <redpill/bios_shim.c:219> Symbol #105 in mfgBIOS "epyc7002_synobios" {__UNIQUE_ID_system_modetype281}<0000000089088c59>
[   72.896682] <redpill/bios_shim.c:219> Symbol #106 in mfgBIOS "epyc7002_synobios" {__param_system_mode}<00000000b5f71612>
[   72.908508] <redpill/bios_shim.c:219> Symbol #107 in mfgBIOS "epyc7002_synobios" {__param_str_system_mode}<0000000083ad9d44>
[   72.920713] <redpill/bios_shim.c:219> Symbol #108 in mfgBIOS "epyc7002_synobios" {__UNIQUE_ID_check_fan280}<00000000c145330a>
[   72.933014] <redpill/bios_shim.c:219> Symbol #109 in mfgBIOS "epyc7002_synobios" {__UNIQUE_ID_check_fantype279}<00000000a0b16151>
[   72.945687] <redpill/bios_shim.c:219> Symbol #110 in mfgBIOS "epyc7002_synobios" {__param_check_fan}<000000000444f1c0>
[   72.957331] <redpill/bios_shim.c:219> Symbol #111 in mfgBIOS "epyc7002_synobios" {__param_str_check_fan}<00000000bd7c3820>
[   72.969342] <redpill/bios_shim.c:219> Symbol #112 in mfgBIOS "epyc7002_synobios" {.LC37}<0000000017be144f>
[   72.979844] <redpill/bios_shim.c:219> Symbol #113 in mfgBIOS "epyc7002_synobios" {MpId.29958}<00000000cdc1e8d5>
[   72.990823] <redpill/bios_shim.c:219> Symbol #114 in mfgBIOS "epyc7002_synobios" {SetMicropId.cold.0}<000000008fb645b2>
[   73.002556] <redpill/bios_shim.c:219> Symbol #115 in mfgBIOS "epyc7002_synobios" {CheckMicropId.cold.1}<00000000ff5498a8>
[   73.014478] <redpill/bios_shim.c:219> Symbol #116 in mfgBIOS "epyc7002_synobios" {.LC0}<00000000bbcc31a4>
[   73.024889] <redpill/bios_shim.c:219> Symbol #117 in mfgBIOS "epyc7002_synobios" {days_since_epoch}<000000001430ea53>
[   73.036416] <redpill/bios_shim.c:219> Symbol #118 in mfgBIOS "epyc7002_synobios" {days_since_leapyear}<00000000bca8ae72>
[   73.048240] <redpill/bios_shim.c:219> Symbol #119 in mfgBIOS "epyc7002_synobios" {days_since_year}<000000004dcdd3e0>
[   73.059684] <redpill/bios_shim.c:219> Symbol #120 in mfgBIOS "epyc7002_synobios" {rtc_seiko_set_auto_poweron.cold.0}<0000000001e6c947>
[   73.072840] <redpill/bios_shim.c:219> Symbol #121 in mfgBIOS "epyc7002_synobios" {rtc_set_interrupt}<0000000007cf7338>
[   73.084469] <redpill/bios_shim.c:219> Symbol #122 in mfgBIOS "epyc7002_synobios" {i2c_bus_no}<000000001270a3d1>
[   73.095455] <redpill/bios_shim.c:219> Symbol #123 in mfgBIOS "epyc7002_synobios" {linuxI2CCharWrite.cold.1}<000000008950563b>
[   73.107761] <redpill/bios_shim.c:219> Symbol #124 in mfgBIOS "epyc7002_synobios" {linuxI2CCharRead.cold.2}<00000000b1e156a5>
[   73.119965] <redpill/bios_shim.c:219> Symbol #125 in mfgBIOS "epyc7002_synobios" {uLostAddr.31344}<00000000ef245fa4>
[   73.131423] <redpill/bios_shim.c:219> Symbol #126 in mfgBIOS "epyc7002_synobios" {linuxI2CSmbusRegRead.cold.3}<00000000fa169d61>
[   73.144009] <redpill/bios_shim.c:219> Symbol #127 in mfgBIOS "epyc7002_synobios" {__FUNCTION__.31345}<00000000de9fe9e9>
[   73.155745] <redpill/bios_shim.c:219> Symbol #128 in mfgBIOS "epyc7002_synobios" {SetDiskLedStatusByLedTrigger.cold.0}<00000000b6ae3d85>
[   73.169088] <redpill/bios_shim.c:219> Symbol #129 in mfgBIOS "epyc7002_synobios" {SetHddActLedByLedTrigger.cold.1}<0000000027a64598>
[   73.182046] <redpill/bios_shim.c:219> Symbol #130 in mfgBIOS "epyc7002_synobios" {SetupDiskLedMap.cold.2}<00000000e698cb5a>
[   73.194156] <redpill/bios_shim.c:219> Symbol #131 in mfgBIOS "epyc7002_synobios" {uLostAddr.45750}<0000000027f72586>
[   73.205607] <redpill/bios_shim.c:219> Symbol #132 in mfgBIOS "epyc7002_synobios" {HWMONReadPmbusStatusReg.cold.0}<000000003b560dc3>
[   73.218480] <redpill/bios_shim.c:219> Symbol #133 in mfgBIOS "epyc7002_synobios" {uLostAddr.45759}<00000000edb38bd3>
[   73.229930] <redpill/bios_shim.c:219> Symbol #134 in mfgBIOS "epyc7002_synobios" {I2CPmbusReadPowerStatus.cold.1}<00000000d488d602>
[   73.242801] <redpill/bios_shim.c:219> Symbol #135 in mfgBIOS "epyc7002_synobios" {__FUNCTION__.45765}<000000005e04868e>
[   73.254535] <redpill/bios_shim.c:219> Symbol #136 in mfgBIOS "epyc7002_synobios" {HWMONGetPSUStatusByI2C.cold.2}<0000000025c9ac65>
[   73.267306] <redpill/bios_shim.c:219> Symbol #137 in mfgBIOS "epyc7002_synobios" {InitModuleType}<000000002e249ef8>
[   73.278667] <redpill/bios_shim.c:219> Symbol #138 in mfgBIOS "epyc7002_synobios" {model_ops}<000000008e287e85>
[   73.289540] <redpill/bios_shim.c:219> Symbol #139 in mfgBIOS "epyc7002_synobios" {GetBuzzerCleared}<000000001145b8e5>
[   73.301087] <redpill/bios_shim.c:219> Symbol #140 in mfgBIOS "epyc7002_synobios" {GetPowerStatus}<00000000320e9158>
[   73.312438] <redpill/bios_shim.c:219> Symbol #141 in mfgBIOS "epyc7002_synobios" {Uninitialize}<00000000effb23cc>
[   73.323608] <redpill/bios_shim.c:219> Symbol #142 in mfgBIOS "epyc7002_synobios" {synobios_ops}<0000000015ec51ce>
[   73.334773] <redpill/bios_shim.c:223> Found vtable - size 424
[   73.341026] <redpill/bios_shim.c:237> Found "synobios_ops" in "epyc7002_synobios" @ <0000000015ec51ce =424=> 0000000008e5a72f>
[   73.353419] <redpill/override_symbol.c:278> Restoring apply_relocate_add<000000005fd11e6b> to original code
[   73.364028] <redpill/memory_helper.c:17> Disabling memory protection for page(s) at 000000005fd11e6b+12/1 (<<00000000ebf98114)
[   73.376496] <redpill/override_symbol.c:249> Obtaining lock for <000000005fd11e6b/000000005fd11e6b>
[   73.386247] <redpill/override_symbol.c:249> Writing original code to <000000005fd11e6b>
[   73.396322] <redpill/override_symbol.c:249> Released lock for <000000005fd11e6b>
[   73.404372] <redpill/memory_helper.c:33> Enabling memory protection for page(s) at 000000005fd11e6b+12/1 (<<00000000ebf98114)
[   73.416737] <redpill/override_symbol.c:286> Successfully restored original code of apply_relocate_add
[   73.426774] <redpill/override_symbol.c:145> Freeing OVS for apply_relocate_add
[   73.436459] <redpill/bios_shims_collection.c:104> Will print 424 bytes of memory from 0000000015ec51ce
[   73.447557] 40 
[   73.447557] d7 
[   73.449481] 29 
[   73.451397] a0 
[   73.453308] ff 
[   73.455225] ff 
[   73.457137] ff 
[   73.459053] ff 
[   73.460975]  [00] 0x000      00000000c77bae42        __this_module+0x0/0xffffffffffff58c0 [epyc7002_synobios]
[   73.472650] 00 
[   73.472650] b6 
[   73.474571] 28 
[   73.476481] a0 
[   73.478398] ff 
[   73.480310] ff 
[   73.482223] ff 
[   73.484139] ff 
[   73.486062]  [01] 0x008      00000000d26c8397        GetBrand+0x0/0x10 [epyc7002_synobios]
[   73.495939] f0 
[   73.495939] 16 
[   73.497855] 29 
[   73.499766] a0 
[   73.501688] ff 
[   73.503605] ff 
[   73.505516] ff 
[   73.507432] ff 
[   73.509350]  [02] 0x010      0000000050299f21        GetModel+0x0/0xa0 [epyc7002_synobios]
[   73.519233] 00 
[   73.519234] 00 
[   73.521145] 00 
[   73.523058] 00 
[   73.524975] 00 
[   73.526886] 00 
[   73.528804] 00 
[   73.530713] 00 
[   73.532635]  [03] 0x018      0000000000000000        0x0
[   73.539309] 50 
[   73.539310] 01 
[   73.541229] 29 
[   73.543140] a0 
[   73.545057] ff 
[   73.546963] ff 
[   73.548876] ff 
[   73.550788] ff 
[   73.552709]  [04] 0x020      0000000040d0ddd3        rtc_seiko_get_time+0x0/0x1a0 [epyc7002_synobios]
[   73.563623] f0 
[   73.563623] 02 
[   73.565541] 29 
[   73.567455] a0 
[   73.569369] ff 
[   73.571285] ff 
[   73.573198] ff 
[   73.575113] ff 
[   73.577030]  [05] 0x028      00000000d4298d72        rtc_seiko_set_time+0x0/0x1d0 [epyc7002_synobios]
[   73.587928] a0 
[   73.587929] b1 
[   73.589839] 28 
[   73.591745] a0 
[   73.593661] ff 
[   73.595574] ff 
[   73.597486] ff 
[   73.599403] ff 
[   73.601323]  [06] 0x030      0000000090e7955e        GetFanStatusActivePulse+0x0/0xd0 [epyc7002_synobios]
[   73.612619] d0 
[   73.612620] 14 
[   73.614536] 29 
[   73.616447] a0 
[   73.618364] ff 
[   73.620275] ff 
[   73.622187] ff 
[   73.624104] ff 
[   73.626021]  [07] 0x038      00000000cb565628        SetFanStatusMircopWithGPIO+0x0/0xc0 [epyc7002_synobios]
[   73.637596] 00 
[   73.637596] 00 
[   73.639511] 00 
[   73.641433] 00 
[   73.643346] 00 
[   73.645257] 00 
[   73.647175] 00 
[   73.649085] 00 
[   73.651000]  [08] 0x040      0000000000000000        0x0
[   73.657653] d0 
[   73.657653] 16 
[   73.659565] 29 
[   73.661479] a0 
[   73.663392] ff 
[   73.665308] ff 
[   73.667221] ff 
[   73.669133] ff 
[   73.671052]  [09] 0x048      0000000079162bf6        GetCpuTemperature+0x0/0x20 [epyc7002_synobios]
[   73.681765] 00 
[   73.681766] 00 
[   73.683691] 00 
[   73.685605] 00 
[   73.687516] 00 
[   73.689432] 00 
[   73.691344] 00 
[   73.693260] 00 
[   73.695172]  [10] 0x050      0000000000000000        0x0
[   73.701822] 00 
[   73.701823] 00 
[   73.703738] 00 
[   73.705650] 00 
[   73.707567] 00 
[   73.709479] 00 
[   73.711391] 00 
[   73.713308] 00 
[   73.715224]  [11] 0x058      0000000000000000        0x0
[   73.721884] 00 
[   73.721885] 00 
[   73.723806] 00 
[   73.725718] 00 
[   73.727630] 00 
[   73.729547] 00 
[   73.731458] 00 
[   73.733375] 00 
[   73.735287]  [12] 0x060      0000000000000000        0x0
[   73.741947] 00 
[   73.741947] 00 
[   73.743863] 00 
[   73.745777] 00 
[   73.747690] 00 
[   73.749597] 00 
[   73.751519] 00 
[   73.753431] 00 
[   73.755345]  [13] 0x068      0000000000000000        0x0
[   73.762004] 00 
[   73.762004] 00 
[   73.763920] 00 
[   73.765832] 00 
[   73.767747] 00 
[   73.769660] 00 
[   73.771576] 00 
[   73.773487] 00 
[   73.775400]  [14] 0x070      0000000000000000        0x0
[   73.782059] b0 
[   73.782059] b5 
[   73.783977] 28 
[   73.785887] a0 
[   73.787801] ff 
[   73.789715] ff 
[   73.791633] ff 
[   73.793544] ff 
[   73.795462]  [15] 0x078      000000008ea625c3        SetGpioPin+0x0/0x20 [epyc7002_synobios]
[   73.805527] d0 
[   73.805527] b5 
[   73.807437] 28 
[   73.809354] a0 
[   73.811268] ff 
[   73.813180] ff 
[   73.815094] ff 
[   73.817010] ff 
[   73.818926]  [16] 0x080      00000000a7c953c6        GetGpioPin+0x0/0x30 [epyc7002_synobios]
[   73.828999] 00 
[   73.828999] 00 
[   73.830912] 00 
[   73.832828] 00 
[   73.834741] 00 
[   73.836655] 00 
[   73.838557] 00 
[   73.840474] 00 
[   73.842387]  [17] 0x088      0000000000000000        0x0
[   73.849036] e0 
[   73.849037] fd 
[   73.850953] 28 
[   73.852864] a0 
[   73.854781] ff 
[   73.856692] ff 
[   73.858598] ff 
[   73.860511] ff 
[   73.862433]  [18] 0x090      00000000d82a2fdc        rtc_seiko_set_auto_poweron+0x0/0x90 [epyc7002_synobios]
[   73.874002] 30 
[   73.874003] fd 
[   73.875920] 28 
[   73.877835] a0 
[   73.879747] ff 
[   73.881660] ff 
[   73.883573] ff 
[   73.885487] ff 
[   73.887405]  [19] 0x098      00000000718efe17        rtc_get_auto_poweron+0x0/0x50 [epyc7002_synobios]
[   73.898421] 40 
[   73.898422] 05 
[   73.900334] 29 
[   73.902238] a0 
[   73.904154] ff 
[   73.906067] ff 
[   73.907978] ff 
[   73.909895] ff 
[   73.911811]  [20] 0x0a0      00000000e0f59df2        rtc_seiko_auto_poweron_init+0x0/0x20 [epyc7002_synobios]
[   73.923492] 70 
[   73.923492] fe 
[   73.925413] 28 
[   73.927324] a0 
[   73.929241] ff 
[   73.931153] ff 
[   73.933068] ff 
[   73.934981] ff 
[   73.936897]  [21] 0x0a8      00000000b075bf92        rtc_seiko_auto_poweron_uninit+0x0/0x20 [epyc7002_synobios]
[   73.948756] 60 
[   73.948757] 14 
[   73.950668] 29 
[   73.952580] a0 
[   73.954496] ff 
[   73.956408] ff 
[   73.958324] ff 
[   73.960240] ff 
[   73.962155]  [22] 0x0b0      000000007e176522        SetAlarmLed+0x0/0x20 [epyc7002_synobios]
[   73.972316] 10 
[   73.972316] 13 
[   73.974227] 29 
[   73.976140] a0 
[   73.978056] ff 
[   73.979968] ff 
[   73.981886] ff 
[   73.983807] ff 
[   73.985728]  [23] 0x0b8      000000001145b8e5        GetBuzzerCleared+0x0/0x30 [epyc7002_synobios]
[   73.996361] 00 
[   73.996361] 00 
[   73.998278] 00 
[   74.000189] 00 
[   74.002102] 00 
[   74.004019] 00 
[   74.005932] 00 
[   74.007837] 00 
[   74.009752]  [24] 0x0c0      0000000000000000        0x0
[   74.016396] 40 
[   74.016397] 13 
[   74.018309] 29 
[   74.020225] a0 
[   74.022139] ff 
[   74.024061] ff 
[   74.025967] ff 
[   74.027887] ff 
[   74.029804]  [25] 0x0c8      00000000320e9158        GetPowerStatus+0x0/0x30 [epyc7002_synobios]
[   74.040257] 00 
[   74.040258] 00 
[   74.042179] 00 
[   74.044090] 00 
[   74.046004] 00 
[   74.047919] 00 
[   74.049833] 00 
[   74.051744] 00 
[   74.053659]  [26] 0x0d0      0000000000000000        0x0
[   74.060314] e0 
[   74.060314] 12 
[   74.062232] 29 
[   74.064133] a0 
[   74.066045] ff 
[   74.067960] ff 
[   74.069870] ff 
[   74.071785] ff 
[   74.073705]  [27] 0x0d8      000000002e249ef8        InitModuleType+0x0/0x30 [epyc7002_synobios]
[   74.084155] 70 
[   74.084156] 13 
[   74.086076] 29 
[   74.087992] a0 
[   74.089905] ff 
[   74.091817] ff 
[   74.093733] ff 
[   74.095643] ff 
[   74.097563]  [28] 0x0e0      00000000effb23cc        Uninitialize+0x0/0x40 [epyc7002_synobios]
[   74.107817] 00 
[   74.107818] 00 
[   74.109740] 00 
[   74.111660] 00 
[   74.113572] 00 
[   74.115485] 00 
[   74.117402] 00 
[   74.119312] 00 
[   74.121219]  [29] 0x0e8      0000000000000000        0x0
[   74.127880] 00 
[   74.127880] 00 
[   74.129796] 00 
[   74.131706] 00 
[   74.133620] 00 
[   74.135535] 00 
[   74.137448] 00 
[   74.139364] 00 
[   74.141277]  [30] 0x0f0      0000000000000000        0x0
[   74.147937] 00 
[   74.147937] 00 
[   74.149852] 00 
[   74.151766] 00 
[   74.153686] 00 
[   74.155603] 00 
[   74.157514] 00 
[   74.159430] 00 
[   74.161340]  [31] 0x0f8      0000000000000000        0x0
[   74.168002] 00 
[   74.168002] 00 
[   74.169915] 00 
[   74.171831] 00 
[   74.173743] 00 
[   74.175659] 00 
[   74.177571] 00 
[   74.179483] 00 
[   74.181400]  [32] 0x100      0000000000000000        0x0
[   74.188056] 00 
[   74.188056] 00 
[   74.189973] 00 
[   74.191889] 00 
[   74.193799] 00 
[   74.195716] 00 
[   74.197629] 00 
[   74.199541] 00 
[   74.201457]  [33] 0x108      0000000000000000        0x0
[   74.208116] 00 
[   74.208117] 00 
[   74.210028] 00 
[   74.211944] 00 
[   74.213846] 00 
[   74.215765] 00 
[   74.217686] 00 
[   74.219596] 00 
[   74.221514]  [34] 0x110      0000000000000000        0x0
[   74.228173] 00 
[   74.228173] 00 
[   74.230085] 00 
[   74.231998] 00 
[   74.233904] 00 
[   74.235810] 00 
[   74.237727] 00 
[   74.239647] 00 
[   74.241562]  [35] 0x118      0000000000000000        0x0
[   74.248224] 00 
[   74.248225] 00 
[   74.250142] 00 
[   74.252060] 00 
[   74.253970] 00 
[   74.255888] 00 
[   74.257800] 00 
[   74.259716] 00 
[   74.261627]  [36] 0x120      0000000000000000        0x0
[   74.268286] 00 
[   74.268287] 00 
[   74.270200] 00 
[   74.272116] 00 
[   74.274032] 00 
[   74.275951] 00 
[   74.277866] 00 
[   74.279778] 00 
[   74.281694]  [37] 0x128      0000000000000000        0x0
[   74.288355] 00 
[   74.288355] 00 
[   74.290268] 00 
[   74.292183] 00 
[   74.294096] 00 
[   74.296008] 00 
[   74.297922] 00 
[   74.299840] 00 
[   74.301742]  [38] 0x130      0000000000000000        0x0
[   74.308402] 00 
[   74.308403] 00 
[   74.310319] 00 
[   74.312231] 00 
[   74.314136] 00 
[   74.316052] 00 
[   74.317966] 00 
[   74.319877] 00 
[   74.321795]  [39] 0x138      0000000000000000        0x0
[   74.328464] b0 
[   74.328464] 13 
[   74.330385] 29 
[   74.332297] a0 
[   74.334210] ff 
[   74.336125] ff 
[   74.338041] ff 
[   74.339953] ff 
[   74.341874]  [40] 0x140      000000009fad66ab        GetCPUInfo+0x0/0x70 [epyc7002_synobios]
[   74.351941] 00 
[   74.351942] 00 
[   74.353858] 00 
[   74.355770] 00 
[   74.357685] 00 
[   74.359598] 00 
[   74.361513] 00 
[   74.363425] 00 
[   74.365340]  [41] 0x148      0000000000000000        0x0
[   74.371999] 00 
[   74.372000] 00 
[   74.373914] 00 
[   74.375830] 00 
[   74.377741] 00 
[   74.379655] 00 
[   74.381571] 00 
[   74.383482] 00 
[   74.385400]  [42] 0x150      0000000000000000        0x0
[   74.392064] 00 
[   74.392064] 00 
[   74.393977] 00 
[   74.395894] 00 
[   74.397805] 00 
[   74.399723] 00 
[   74.401634] 00 
[   74.403549] 00 
[   74.405463]  [43] 0x158      0000000000000000        0x0
[   74.412120] 00 
[   74.412121] 00 
[   74.414037] 00 
[   74.415951] 00 
[   74.417862] 00 
[   74.419780] 00 
[   74.421691] 00 
[   74.423605] 00 
[   74.425519]  [44] 0x160      0000000000000000        0x0
[   74.432179] 00 
[   74.432179] 00 
[   74.434091] 00 
[   74.436006] 00 
[   74.437922] 00 
[   74.439834] 00 
[   74.441747] 00 
[   74.443665] 00 
[   74.445575]  [45] 0x168      0000000000000000        0x0
[   74.452235] 00 
[   74.452235] 00 
[   74.454151] 00 
[   74.456064] 00 
[   74.457981] 00 
[   74.459893] 00 
[   74.461805] 00 
[   74.463722] 00 
[   74.465642]  [46] 0x170      0000000000000000        0x0
[   74.472302] 00 
[   74.472302] 00 
[   74.474213] 00 
[   74.476131] 00 
[   74.478042] 00 
[   74.479959] 00 
[   74.481872] 00 
[   74.483784] 00 
[   74.485700]  [47] 0x178      0000000000000000        0x0
[   74.492360] 00 
[   74.492360] 00 
[   74.494280] 00 
[   74.496192] 00 
[   74.498105] 00 
[   74.500023] 00 
[   74.501935] 00 
[   74.503850] 00 
[   74.505763]  [48] 0x180      0000000000000000        0x0
[   74.512422] 00 
[   74.512423] 00 
[   74.514333] 00 
[   74.516251] 00 
[   74.518163] 00 
[   74.520079] 00 
[   74.521991] 00 
[   74.523902] 00 
[   74.525820]  [49] 0x188      0000000000000000        0x0
[   74.532484] 00 
[   74.532485] 00 
[   74.534400] 00 
[   74.536313] 00 
[   74.538225] 00 
[   74.540139] 00 
[   74.542057] 00 
[   74.543969] 00 
[   74.545880]  [50] 0x190      0000000000000000        0x0
[   74.552540] 00 
[   74.552541] 00 
[   74.554456] 00 
[   74.556368] 00 
[   74.558282] 00 
[   74.560199] 00 
[   74.562118] 00 
[   74.564035] 00 
[   74.565958]  [51] 0x198      0000000000000000        0x0
[   74.572624] 00 
[   74.572625] 00 
[   74.574540] 00 
[   74.576453] 00 
[   74.578357] 00 
[   74.580270] 00 
[   74.582186] 00 
[   74.584099] 00 
[   74.586011]  [52] 0x1a0      0000000000000000        0x0
[   74.592674] 
[   74.594302] <redpill/bios_shims_collection.c:117> Finished printing memory at 0000000053d08b32
[   74.603679] <redpill/bios_shims_collection.c:86> mfgBIOS vtable [7] originally SetFanStatusMircopWithGPIO [epyc7002_synobios]<00000000cb565628> will now be bios_VTK_SET_FAN_STATE_null_zero_int [redpill]<00000000c07ac642>
[   74.624955] <redpill/bios_shims_collection.c:86> mfgBIOS vtable [10] originally 0x0<0000000000000000> will now be bios_VTK_SET_DISK_LED_null_zero_int [redpill]<0000000017eb00ed>
[   74.642181] <redpill/bios_shims_collection.c:86> mfgBIOS vtable [11] originally 0x0<0000000000000000> will now be bios_VTK_SET_PWR_LED_null_zero_int [redpill]<00000000ef3022d1>
[   74.659313] <redpill/bios_shims_collection.c:86> mfgBIOS vtable [16] originally GetGpioPin [epyc7002_synobios]<00000000a7c953c6> will now be shim_get_gpio_pin_usable [redpill]<0000000081b034fa>
[   74.678041] <redpill/bios_shims_collection.c:86> mfgBIOS vtable [15] originally SetGpioPin [epyc7002_synobios]<000000008ea625c3> will now be shim_set_gpio_pin_usable [redpill]<00000000f952a3a0>
[   74.696765] <redpill/bios_shims_collection.c:86> mfgBIOS vtable [17] originally 0x0<0000000000000000> will now be bios_VTK_SET_GPIO_PIN_BLINK_null_zero_int [redpill]<000000004d032948>
[   74.714548] <redpill/bios_shims_collection.c:86> mfgBIOS vtable [22] originally SetAlarmLed [epyc7002_synobios]<000000007e176522> will now be bios_VTK_SET_ALR_LED_null_zero_int [redpill]<0000000060df12f9>
[   74.734311] <redpill/bios_shims_collection.c:86> mfgBIOS vtable [23] originally GetBuzzerCleared [epyc7002_synobios]<000000001145b8e5> will now be bios_get_buz_clr [redpill]<00000000957312bc>
[   74.752854] <redpill/bios_shims_collection.c:86> mfgBIOS vtable [24] originally 0x0<0000000000000000> will now be bios_VTK_SET_BUZ_CLR_null_zero_int [redpill]<00000000dd850310>
[   74.769987] <redpill/bios_shims_collection.c:86> mfgBIOS vtable [25] originally GetPowerStatus [epyc7002_synobios]<00000000320e9158> will now be bios_get_power_status [redpill]<00000000b16a5213>
[   74.788798] <redpill/bios_shims_collection.c:86> mfgBIOS vtable [29] originally 0x0<0000000000000000> will now be bios_VTK_SET_CPU_FAN_STATUS_null_zero_int [redpill]<000000000e96a5fd>
[   74.806580] <redpill/bios_shims_collection.c:86> mfgBIOS vtable [30] originally 0x0<0000000000000000> will now be bios_VTK_SET_PHY_LED_null_zero_int [redpill]<0000000032d7d8e4>
[   74.823691] <redpill/bios_shims_collection.c:86> mfgBIOS vtable [31] originally 0x0<0000000000000000> will now be bios_VTK_SET_HDD_ACT_LED_null_zero_int [redpill]<000000001b648c9c>
[   74.841201] <redpill/bios_shims_collection.c:86> mfgBIOS vtable [33] originally 0x0<0000000000000000> will now be bios_VTK_GET_MICROP_ID_null_zero_int [redpill]<00000000c5189650>
[   74.858518] <redpill/bios_shims_collection.c:86> mfgBIOS vtable [34] originally 0x0<0000000000000000> will now be bios_VTK_SET_MICROP_ID_null_zero_int [redpill]<0000000019375d9f>
[   74.875824] <redpill/bios_shims_collection.c:155> Platform requires RTC proxy - enabling
[   74.884631] <redpill/rtc_proxy.c:260> Registering RTC proxy shim
[   74.891166] <redpill/rtc_proxy.c:268> Successfully registered RTC proxy shim
[   74.898848] <redpill/bios_shims_collection.c:86> mfgBIOS vtable [4] originally rtc_seiko_get_time [epyc7002_synobios]<0000000040d0ddd3> will now be rtc_proxy_get_time [redpill]<000000004704f422>
[   74.917676] <redpill/bios_shims_collection.c:86> mfgBIOS vtable [5] originally rtc_seiko_set_time [epyc7002_synobios]<00000000d4298d72> will now be rtc_proxy_set_time [redpill]<00000000c5a7599f>
[   74.936499] <redpill/bios_shims_collection.c:86> mfgBIOS vtable [20] originally rtc_seiko_auto_poweron_init [epyc7002_synobios]<00000000e0f59df2> will now be rtc_proxy_init_auto_power_on [redpill]<00000000650350ca>
[   74.957215] <redpill/bios_shims_collection.c:86> mfgBIOS vtable [19] originally rtc_get_auto_poweron [epyc7002_synobios]<00000000718efe17> will now be rtc_proxy_get_auto_power_on [redpill]<000000002e35ba90>
[   74.977168] <redpill/bios_shims_collection.c:86> mfgBIOS vtable [18] originally rtc_seiko_set_auto_poweron [epyc7002_synobios]<00000000d82a2fdc> will now be rtc_proxy_set_auto_power_on [redpill]<000000006c3f2fef>
[   74.997695] <redpill/bios_shims_collection.c:86> mfgBIOS vtable [21] originally rtc_seiko_auto_poweron_uninit [epyc7002_synobios]<00000000b075bf92> will now be rtc_proxy_uinit_auto_power_on [redpill]<00000000103448b2>
[   75.018691] <redpill/bios_hwmon_shim.c:332> Registering mfgBIOS HW Monitor shim
[   75.026653] <redpill/bios_shims_collection.c:86> mfgBIOS vtable [6] originally GetFanStatusActivePulse [epyc7002_synobios]<0000000090e7955e> will now be bios_get_fan_state [redpill]<000000006a8faed4>
[   75.045936] <redpill/bios_shims_collection.c:86> mfgBIOS vtable [9] originally GetCpuTemperature [epyc7002_synobios]<0000000079162bf6> will now be bios_get_cpu_temp [redpill]<00000000ebf6df74>
[   75.064564] <redpill/bios_shims_collection.c:86> mfgBIOS vtable [47] originally 0x0<0000000000000000> will now be bios_hwmon_get_thermal [redpill]<00000000b112f6a9>
[   75.080563] <redpill/bios_shims_collection.c:86> mfgBIOS vtable [45] originally 0x0<0000000000000000> will now be bios_hwmon_get_voltages [redpill]<00000000103e34b5>
[   75.096655] <redpill/bios_shims_collection.c:86> mfgBIOS vtable [43] originally 0x0<0000000000000000> will now be bios_hwmon_get_fans_rpm [redpill]<000000002f3cd437>
[   75.112747] <redpill/bios_shims_collection.c:86> mfgBIOS vtable [46] originally 0x0<0000000000000000> will now be bios_hwmon_get_hdd_backplane [redpill]<00000000bfc9cb4e>
[   75.129309] <redpill/bios_hwmon_shim.c:358> Successfully registered mfgBIOS HW Monitor shim
[   75.138404] <redpill/bios_shims_collection.c:104> Will print 424 bytes of memory from 0000000015ec51ce
[   75.148535] 40 
[   75.148536] d7 
[   75.150447] 29 
[   75.152358] a0 
[   75.154275] ff 
[   75.156186] ff 
[   75.158104] ff 
[   75.160015] ff 
[   75.161938]  [00] 0x000      00000000c77bae42        __this_module+0x0/0xffffffffffff58c0 [epyc7002_synobios]
[   75.173590] 00 
[   75.173591] b6 
[   75.175508] 28 
[   75.177423] a0 
[   75.179346] ff 
[   75.181259] ff 
[   75.183174] ff 
[   75.185092] ff 
[   75.187012]  [01] 0x008      00000000d26c8397        GetBrand+0x0/0x10 [epyc7002_synobios]
[   75.196894] f0 
[   75.196894] 16 
[   75.198801] 29 
[   75.200717] a0 
[   75.202638] ff 
[   75.204549] ff 
[   75.206466] ff 
[   75.208378] ff 
[   75.210295]  [02] 0x010      0000000050299f21        GetModel+0x0/0xa0 [epyc7002_synobios]
[   75.220179] 00 
[   75.220179] 00 
[   75.222093] 00 
[   75.224010] 00 
[   75.225932] 00 
[   75.227843] 00 
[   75.229760] 00 
[   75.231667] 00 
[   75.233578]  [03] 0x018      0000000000000000        0x0
[   75.240238] 6c 
[   75.240238] e7 
[   75.242154] 00 
[   75.244067] a0 
[   75.245978] ff 
[   75.247894] ff 
[   75.249810] ff 
[   75.251724] ff 
[   75.253649]  [04] 0x020      000000004704f422        rtc_proxy_get_time+0x0/0xd0 [redpill]
[   75.263533] 3c 
[   75.263533] e8 
[   75.265439] 00 
[   75.267360] a0 
[   75.269271] ff 
[   75.271187] ff 
[   75.273102] ff 
[   75.275013] ff 
[   75.276932]  [05] 0x028      00000000c5a7599f        rtc_proxy_set_time+0x0/0x215 [redpill]
[   75.286894] 00 
[   75.286894] 48 
[   75.288806] 00 
[   75.290721] a0 
[   75.292636] ff 
[   75.294549] ff 
[   75.296463] ff 
[   75.298378] ff 
[   75.300295]  [06] 0x030      000000006a8faed4        bios_get_fan_state+0x0/0x10 [redpill]
[   75.310175] 0f 
[   75.310176] ed 
[   75.312089] 00 
[   75.314002] a0 
[   75.315921] ff 
[   75.317833] ff 
[   75.319746] ff 
[   75.321660] ff 
[   75.323577]  [07] 0x038      00000000c07ac642        bios_VTK_SET_FAN_STATE_null_zero_int+0x0/0x27 [redpill]
[   75.335159] 00 
[   75.335159] 00 
[   75.337074] 00 
[   75.338988] 00 
[   75.340903] 00 
[   75.342817] 00 
[   75.344731] 00 
[   75.346643] 00 
[   75.348557]  [08] 0x040      0000000000000000        0x0
[   75.355216] f0 
[   75.355216] 48 
[   75.357132] 00 
[   75.359044] a0 
[   75.360951] ff 
[   75.362863] ff 
[   75.364776] ff 
[   75.366691] ff 
[   75.368612]  [09] 0x048      00000000ebf6df74        bios_get_cpu_temp+0x0/0x40 [redpill]
[   75.378400] 36 
[   75.378400] ed 
[   75.380312] 00 
[   75.382223] a0 
[   75.384136] ff 
[   75.386052] ff 
[   75.387964] ff 
[   75.389880] ff 
[   75.391799]  [10] 0x050      0000000017eb00ed        bios_VTK_SET_DISK_LED_null_zero_int+0x0/0x27 [redpill]
[   75.403284] 5d 
[   75.403285] ed 
[   75.405197] 00 
[   75.407109] a0 
[   75.409025] ff 
[   75.410940] ff 
[   75.412848] ff 
[   75.414760] ff 
[   75.416686]  [11] 0x058      00000000ef3022d1        bios_VTK_SET_PWR_LED_null_zero_int+0x0/0x27 [redpill]
[   75.428070] 00 
[   75.428070] 00 
[   75.429984] 00 
[   75.431895] 00 
[   75.433808] 00 
[   75.435722] 00 
[   75.437639] 00 
[   75.439561] 00 
[   75.441484]  [12] 0x060      0000000000000000        0x0
[   75.448143] 00 
[   75.448143] 00 
[   75.450066] 00 
[   75.451987] 00 
[   75.453901] 00 
[   75.455816] 00 
[   75.457734] 00 
[   75.459649] 00 
[   75.461566]  [13] 0x068      0000000000000000        0x0
[   75.468225] 00 
[   75.468226] 00 
[   75.470147] 00 
[   75.472060] 00 
[   75.473972] 00 
[   75.475887] 00 
[   75.477803] 00 
[   75.479715] 00 
[   75.481629]  [14] 0x070      0000000000000000        0x0
[   75.488289] bc 
[   75.488290] ee 
[   75.490204] 00 
[   75.492117] a0 
[   75.494032] ff 
[   75.495945] ff 
[   75.497857] ff 
[   75.499774] ff 
[   75.501689]  [15] 0x078      00000000f952a3a0        shim_set_gpio_pin_usable+0x0/0x98 [redpill]
[   75.512139] a0 
[   75.512139] 4c 
[   75.514056] 00 
[   75.515977] a0 
[   75.517896] ff 
[   75.519811] ff 
[   75.521728] ff 
[   75.523649] ff 
[   75.525567]  [16] 0x080      0000000081b034fa        shim_get_gpio_pin_usable+0x0/0x10 [redpill]
[   75.536006] 84 
[   75.536007] ed 
[   75.537923] 00 
[   75.539835] a0 
[   75.541750] ff 
[   75.543663] ff 
[   75.545575] ff 
[   75.547492] ff 
[   75.549409]  [17] 0x088      000000004d032948        bios_VTK_SET_GPIO_PIN_BLINK_null_zero_int+0x0/0x27 [redpill]
[   75.561465] fa 
[   75.561465] ea 
[   75.563386] 00 
[   75.565297] a0 
[   75.567214] ff 
[   75.569126] ff 
[   75.571042] ff 
[   75.572955] ff 
[   75.574873]  [18] 0x090      000000006c3f2fef        rtc_proxy_set_auto_power_on+0x0/0x74 [redpill]
[   75.585603] 7f 
[   75.585603] ea 
[   75.587510] 00 
[   75.589423] a0 
[   75.591340] ff 
[   75.593258] ff 
[   75.595172] ff 
[   75.597085] ff 
[   75.599007]  [19] 0x098      000000002e35ba90        rtc_proxy_get_auto_power_on+0x0/0x7b [redpill]
[   75.609740] 51 
[   75.609741] ea 
[   75.611661] 00 
[   75.613574] a0 
[   75.615490] ff 
[   75.617412] ff 
[   75.619323] ff 
[   75.621241] ff 
[   75.623158]  [20] 0x0a0      00000000650350ca        rtc_proxy_init_auto_power_on+0x0/0x2e [redpill]
[   75.633984] 6e 
[   75.633985] eb 
[   75.635895] 00 
[   75.637810] a0 
[   75.639723] ff 
[   75.641640] ff 
[   75.643558] ff 
[   75.645475] ff 
[   75.647391]  [21] 0x0a8      00000000103448b2        rtc_proxy_uinit_auto_power_on+0x0/0x2e [redpill]
[   75.658310] ab 
[   75.658311] ed 
[   75.660226] 00 
[   75.662142] a0 
[   75.664054] ff 
[   75.665966] ff 
[   75.667884] ff 
[   75.669805] ff 
[   75.671715]  [22] 0x0b0      0000000060df12f9        bios_VTK_SET_ALR_LED_null_zero_int+0x0/0x27 [redpill]
[   75.683091] b0 
[   75.683092] 4c 
[   75.685006] 00 
[   75.686927] a0 
[   75.688841] ff 
[   75.690752] ff 
[   75.692665] ff 
[   75.694581] ff 
[   75.696502]  [23] 0x0b8      00000000957312bc        bios_get_buz_clr+0x0/0x10 [redpill]
[   75.706191] d2 
[   75.706192] ed 
[   75.708108] 00 
[   75.710021] a0 
[   75.711933] ff 
[   75.713850] ff 
[   75.715762] ff 
[   75.717678] ff 
[   75.719594]  [24] 0x0c0      00000000dd850310        bios_VTK_SET_BUZ_CLR_null_zero_int+0x0/0x27 [redpill]
[   75.730997] c0 
[   75.730998] 4c 
[   75.732910] 00 
[   75.734823] a0 
[   75.736713] ff 
[   75.738629] ff 
[   75.740541] ff 
[   75.742452] ff 
[   75.744375]  [25] 0x0c8      00000000b16a5213        bios_get_power_status+0x0/0x20 [redpill]
[   75.754540] 00 
[   75.754541] 00 
[   75.756451] 00 
[   75.758369] 00 
[   75.760274] 00 
[   75.762187] 00 
[   75.764100] 00 
[   75.766016] 00 
[   75.767929]  [26] 0x0d0      0000000000000000        0x0
[   75.774588] e0 
[   75.774588] 12 
[   75.776500] 29 
[   75.778415] a0 
[   75.780328] ff 
[   75.782243] ff 
[   75.784150] ff 
[   75.786063] ff 
[   75.787978]  [27] 0x0d8      000000002e249ef8        InitModuleType+0x0/0x30 [epyc7002_synobios]
[   75.798421] 70 
[   75.798421] 13 
[   75.800333] 29 
[   75.802251] a0 
[   75.804172] ff 
[   75.806084] ff 
[   75.807996] ff 
[   75.809912] ff 
[   75.811828]  [28] 0x0e0      00000000effb23cc        Uninitialize+0x0/0x40 [epyc7002_synobios]
[   75.822091] f9 
[   75.822091] ed 
[   75.824005] 00 
[   75.825918] a0 
[   75.827831] ff 
[   75.829742] ff 
[   75.831658] ff 
[   75.833575] ff 
[   75.835491]  [29] 0x0e8      000000000e96a5fd        bios_VTK_SET_CPU_FAN_STATUS_null_zero_int+0x0/0x27 [redpill]
[   75.847543] 20 
[   75.847543] ee 
[   75.849456] 00 
[   75.851362] a0 
[   75.853275] ff 
[   75.855190] ff 
[   75.857106] ff 
[   75.859020] ff 
[   75.860937]  [30] 0x0f0      0000000032d7d8e4        bios_VTK_SET_PHY_LED_null_zero_int+0x0/0x27 [redpill]
[   75.872320] 47 
[   75.872320] ee 
[   75.874232] 00 
[   75.876149] a0 
[   75.878061] ff 
[   75.879977] ff 
[   75.881889] ff 
[   75.883804] ff 
[   75.885722]  [31] 0x0f8      000000001b648c9c        bios_VTK_SET_HDD_ACT_LED_null_zero_int+0x0/0x27 [redpill]
[   75.897481] 00 
[   75.897481] 00 
[   75.899393] 00 
[   75.901310] 00 
[   75.903225] 00 
[   75.905147] 00 
[   75.907066] 00 
[   75.908983] 00 
[   75.910899]  [32] 0x100      0000000000000000        0x0
[   75.917564] 6e 
[   75.917565] ee 
[   75.919477] 00 
[   75.921388] a0 
[   75.923304] ff 
[   75.925221] ff 
[   75.927132] ff 
[   75.929048] ff 
[   75.930973]  [33] 0x108      00000000c5189650        bios_VTK_GET_MICROP_ID_null_zero_int+0x0/0x27 [redpill]
[   75.942552] 95 
[   75.942553] ee 
[   75.944468] 00 
[   75.946379] a0 
[   75.948293] ff 
[   75.950209] ff 
[   75.952117] ff 
[   75.954038] ff 
[   75.955954]  [34] 0x110      0000000019375d9f        bios_VTK_SET_MICROP_ID_null_zero_int+0x0/0x27 [redpill]
[   75.967538] 00 
[   75.967539] 00 
[   75.969459] 00 
[   75.971373] 00 
[   75.973284] 00 
[   75.975199] 00 
[   75.977115] 00 
[   75.979025] 00 
[   75.980942]  [35] 0x118      0000000000000000        0x0
[   75.987593] 00 
[   75.987594] 00 
[   75.989513] 00 
[   75.991430] 00 
[   75.993344] 00 
[   75.995263] 00 
[   75.997178] 00 
[   75.999091] 00 
[   76.001004]  [36] 0x120      0000000000000000        0x0
[   76.007655] 00 
[   76.007656] 00 
[   76.009568] 00 
[   76.011481] 00 
[   76.013398] 00 
[   76.015309] 00 
[   76.017226] 00 
[   76.019138] 00 
[   76.021051]  [37] 0x128      0000000000000000        0x0
[   76.027703] 00 
[   76.027703] 00 
[   76.029610] 00 
[   76.031522] 00 
[   76.033439] 00 
[   76.035351] 00 
[   76.037262] 00 
[   76.039169] 00 
[   76.041085]  [38] 0x130      0000000000000000        0x0
[   76.047741] 00 
[   76.047741] 00 
[   76.049657] 00 
[   76.051572] 00 
[   76.053483] 00 
[   76.055397] 00 
[   76.057310] 00 
[   76.059224] 00 
[   76.061142]  [39] 0x138      0000000000000000        0x0
[   76.067797] b0 
[   76.067798] 13 
[   76.069714] 29 
[   76.071626] a0 
[   76.073543] ff 
[   76.075465] ff 
[   76.077376] ff 
[   76.079292] ff 
[   76.081206]  [40] 0x140      000000009fad66ab        GetCPUInfo+0x0/0x70 [epyc7002_synobios]
[   76.091278] 00 
[   76.091279] 00 
[   76.093192] 00 
[   76.095107] 00 
[   76.097019] 00 
[   76.098935] 00 
[   76.100849] 00 
[   76.102760] 00 
[   76.104678]  [41] 0x148      0000000000000000        0x0
[   76.111346] 00 
[   76.111346] 00 
[   76.113264] 00 
[   76.115179] 00 
[   76.117091] 00 
[   76.119010] 00 
[   76.120931] 00 
[   76.122852] 00 
[   76.124768]  [42] 0x150      0000000000000000        0x0
[   76.131435] 90 
[   76.131435] 4b 
[   76.133346] 00 
[   76.135263] a0 
[   76.137173] ff 
[   76.139091] ff 
[   76.141013] ff 
[   76.142923] ff 
[   76.144843]  [43] 0x158      000000002f3cd437        bios_hwmon_get_fans_rpm+0x0/0x110 [redpill]
[   76.155290] 00 
[   76.155290] 00 
[   76.157207] 00 
[   76.159119] 00 
[   76.161030] 00 
[   76.162947] 00 
[   76.164861] 00 
[   76.166777] 00 
[   76.168700]  [44] 0x160      0000000000000000        0x0
[   76.175357] 60 
[   76.175358] 4a 
[   76.177271] 00 
[   76.179184] a0 
[   76.181099] ff 
[   76.183009] ff 
[   76.184916] ff 
[   76.186827] ff 
[   76.188750]  [45] 0x168      00000000103e34b5        bios_hwmon_get_voltages+0x0/0x130 [redpill]
[   76.199197] 10 
[   76.199198] 48 
[   76.201110] 00 
[   76.203022] a0 
[   76.204939] ff 
[   76.206852] ff 
[   76.208765] ff 
[   76.210689] ff 
[   76.212605]  [46] 0x170      00000000bfc9cb4e        bios_hwmon_get_hdd_backplane+0x0/0xe0 [redpill]
[   76.223432] 50 
[   76.223432] 49 
[   76.225344] 00 
[   76.227259] a0 
[   76.229176] ff 
[   76.231095] ff 
[   76.233010] ff 
[   76.234922] ff 
[   76.236844]  [47] 0x178      00000000b112f6a9        bios_hwmon_get_thermal+0x0/0x110 [redpill]
[   76.247205] 00 
[   76.247205] 00 
[   76.249117] 00 
[   76.251023] 00 
[   76.252935] 00 
[   76.254841] 00 
[   76.256754] 00 
[   76.258668] 00 
[   76.260586]  [48] 0x180      0000000000000000        0x0
[   76.267251] 00 
[   76.267252] 00 
[   76.269164] 00 
[   76.271078] 00 
[   76.272991] 00 
[   76.274908] 00 
[   76.276820] 00 
[   76.278727] 00 
[   76.280643]  [49] 0x188      0000000000000000        0x0
[   76.287307] 00 
[   76.287308] 00 
[   76.289224] 00 
[   76.291143] 00 
[   76.293057] 00 
[   76.294971] 00 
[   76.296886] 00 
[   76.298798] 00 
[   76.300716]  [50] 0x190      0000000000000000        0x0
[   76.307380] 00 
[   76.307381] 00 
[   76.309288] 00 
[   76.311198] 00 
[   76.313111] 00 
[   76.315027] 00 
[   76.316944] 00 
[   76.318854] 00 
[   76.320770]  [51] 0x198      0000000000000000        0x0
[   76.327426] 00 
[   76.327427] 00 
[   76.329343] 00 
[   76.331246] 00 
[   76.333163] 00 
[   76.335072] 00 
[   76.336990] 00 
[   76.338902] 00 
[   76.340814]  [52] 0x1a0      0000000000000000        0x0
[   76.347478] 
[   76.349108] <redpill/bios_shims_collection.c:117> Finished printing memory at 0000000053d08b32
[   76.358478] <redpill/bios_hwcap_shim.c:79> Registering mfgBIOS HW Capability shim
[   76.366626] <redpill/override_symbol.c:256> Overriding GetHwCapability() with (%pf?)()<00000000e4220cff>
[   76.383830] <redpill/override_symbol.c:171> Saved GetHwCapability() ptr <00000000fdbb1a9e>
[   76.392865] <redpill/memory_helper.c:17> Disabling memory protection for page(s) at 00000000fdbb1a9e+12/1 (<<00000000b5a5eb24)
[   76.405331] <redpill/override_symbol.c:220> Obtaining lock for <00000000fdbb1a9e/00000000fdbb1a9e>
[   76.415078] <redpill/override_symbol.c:181> Generating trampoline
[   76.423080] <redpill/override_symbol.c:186> Generated trampoline to 00000000e4220cff<00000000e4220cff> for GetHwCapability<00000000fdbb1a9e>: 
[   76.436973] <redpill/override_symbol.c:220> Writing trampoline code to <00000000fdbb1a9e>
[   76.445862] <redpill/override_symbol.c:220> Released lock for <00000000fdbb1a9e>
[   76.453913] <redpill/memory_helper.c:33> Enabling memory protection for page(s) at 00000000fdbb1a9e+12/1 (<<00000000b5a5eb24)
[   76.466279] <redpill/override_symbol.c:268> Successfully overrode GetHwCapability() with trampoline to 00000000e4220cff<00000000e4220cff>
[   76.479721] <redpill/bios_hwcap_shim.c:87> Successfully registered mfgBIOS HW Capability shim
[   76.490363] <redpill/bios_psu_status_shim.c:23> Registering mfgBIOS HWMONGetPSUStatusByI2C shim
[   76.499833] <redpill/override_symbol.c:256> Overriding HWMONGetPSUStatusByI2C() with (%pf?)()<00000000a5a48881>
[   76.517652] <redpill/override_symbol.c:171> Saved HWMONGetPSUStatusByI2C() ptr <0000000090700ebb>
[   76.527374] <redpill/memory_helper.c:17> Disabling memory protection for page(s) at 0000000090700ebb+12/1 (<<000000007466ab3c)
[   76.539797] <redpill/override_symbol.c:220> Obtaining lock for <0000000090700ebb/0000000090700ebb>
[   76.549550] <redpill/override_symbol.c:181> Generating trampoline
[   76.556177] <redpill/override_symbol.c:186> Generated trampoline to 00000000a5a48881<00000000a5a48881> for HWMONGetPSUStatusByI2C<0000000090700ebb>: 
[   76.570741] <redpill/override_symbol.c:220> Writing trampoline code to <0000000090700ebb>
[   76.579644] <redpill/override_symbol.c:220> Released lock for <0000000090700ebb>
[   76.587699] <redpill/memory_helper.c:33> Enabling memory protection for page(s) at 0000000090700ebb+12/1 (<<000000007466ab3c)
[   76.600067] <redpill/override_symbol.c:268> Successfully overrode HWMONGetPSUStatusByI2C() with trampoline to 00000000a5a48881<00000000a5a48881>
[   76.614165] <redpill/bios_psu_status_shim.c:31> Successfully registered mfgBIOS HWMONGetPSUStatusByI2C shim
[   76.626132] <redpill/bios_shim.c:135> epyc7002_synobios BIOS *early* shimmed
[   76.634023] synobios open /dev/ttyS1 success
[   76.639888] Fail to get disk 1 led type
[   76.644075] Fail to get disk 2 led type
[   76.648255] Fail to get disk 3 led type
[   76.652435] Fail to get disk 4 led type
[   76.656610] Fail to get disk 5 led type
[   76.660793] Fail to get disk 6 led type
[   76.664970] Fail to get disk 7 led type
[   76.669144] Fail to get disk 8 led type
[   76.673323] Fail to get disk 9 led type
[   76.677502] Fail to get disk 10 led type
[   76.681776] Fail to get disk 11 led type
[   76.686049] Fail to get disk 12 led type
[   76.690326] <redpill/bios_shims_collection.c:226> Received syno_ahci_disk_led_enable_by_port_shim with port=1 val=1
[   76.701683] <redpill/bios_shims_collection.c:226> Received syno_ahci_disk_led_enable_by_port_shim with port=2 val=1
[   76.713029] <redpill/bios_shims_collection.c:226> Received syno_ahci_disk_led_enable_by_port_shim with port=3 val=1
[   76.724374] <redpill/bios_shims_collection.c:226> Received syno_ahci_disk_led_enable_by_port_shim with port=4 val=1
[   76.735720] <redpill/bios_shims_collection.c:226> Received syno_ahci_disk_led_enable_by_port_shim with port=5 val=1
[   76.747084] <redpill/bios_shims_collection.c:226> Received syno_ahci_disk_led_enable_by_port_shim with port=6 val=1
[   76.758418] <redpill/bios_shims_collection.c:226> Received syno_ahci_disk_led_enable_by_port_shim with port=7 val=1
[   76.769775] <redpill/bios_shims_collection.c:226> Received syno_ahci_disk_led_enable_by_port_shim with port=8 val=1
[   76.781130] <redpill/bios_shims_collection.c:226> Received syno_ahci_disk_led_enable_by_port_shim with port=9 val=1
[   76.792482] <redpill/bios_shims_collection.c:226> Received syno_ahci_disk_led_enable_by_port_shim with port=10 val=1
[   76.803935] <redpill/bios_shims_collection.c:226> Received syno_ahci_disk_led_enable_by_port_shim with port=11 val=1
[   76.815392] <redpill/bios_shims_collection.c:226> Received syno_ahci_disk_led_enable_by_port_shim with port=12 val=1
[   76.826830] <redpill/rtc_proxy.c:204> RTC power-on "enabled" via rtc_proxy_init_auto_power_on
[   76.836112] <redpill/rtc_proxy.c:39> MfgCompatTime raw data: sec=0 min=0 hr=0 wkd=0 day=0 mth=0 yr=0
[   76.846063] <redpill/rtc_proxy.c:60> Reading BCD-based RTC
[   76.852215] <redpill/rtc_proxy.c:145> Time got from RTC is 2023-04-03 15:17:23 (UTC)
[   76.861901] <redpill/rtc_proxy.c:39> MfgCompatTime raw data: sec=23 min=17 hr=15 wkd=1 day=3 mth=3 yr=123
[   76.872382] 2023-4-3 15:17:23 UTC
[   76.876009] synobios: load, major number 201
[   76.882026] Brand: Synology
[   76.885074] Model: SA-6400
[   76.888035] <redpill/bios_shims_collection.c:61> mfgBIOS: nullify zero-int for VTK_SET_MICROP_ID
[   76.897603] synobios cpu_arch proc entry initialized
[   76.903011] synobios crypto_hw proc entry initialized
[   76.908508] synobios syno_platform proc entry initialized
[   76.914391] <redpill/bios_shims_collection.c:104> Will print 424 bytes of memory from 0000000015ec51ce
[   76.924515] 40 
[   76.924516] d7 
[   76.926431] 29 
[   76.928343] a0 
[   76.930260] ff 
[   76.932173] ff 
[   76.934085] ff 
[   76.936002] ff 
[   76.937921]  [00] 0x000      00000000c77bae42        __this_module+0x0/0xffffffffffff58c0 [epyc7002_synobios]
[   76.949593] 00 
[   76.949594] b6 
[   76.951511] 28 
[   76.953430] a0 
[   76.955344] ff 
[   76.957259] ff 
[   76.959171] ff 
[   76.961084] ff 
[   76.963006]  [01] 0x008      00000000d26c8397        GetBrand+0x0/0x10 [epyc7002_synobios]
[   76.972889] f0 
[   76.972890] 16 
[   76.974790] 29 
[   76.976704] a0 
[   76.978619] ff 
[   76.980534] ff 
[   76.982448] ff 
[   76.984354] ff 
[   76.986273]  [02] 0x010      0000000050299f21        GetModel+0x0/0xa0 [epyc7002_synobios]
[   76.996153] 00 
[   76.996154] 00 
[   76.998068] 00 
[   76.999981] 00 
[   77.001893] 00 
[   77.003810] 00 
[   77.005723] 00 
[   77.007639] 00 
[   77.009564]  [03] 0x018      0000000000000000        0x0
[   77.016229] 6c 
[   77.016230] e7 
[   77.018141] 00 
[   77.020054] a0 
[   77.021971] ff 
[   77.023883] ff 
[   77.025798] ff 
[   77.027701] ff 
[   77.029623]  [04] 0x020      000000004704f422        rtc_proxy_get_time+0x0/0xd0 [redpill]
[   77.039492] 3c 
[   77.039493] e8 
[   77.041409] 00 
[   77.043321] a0 
[   77.045238] ff 
[   77.047150] ff 
[   77.049066] ff 
[   77.050980] ff 
[   77.052897]  [05] 0x028      00000000c5a7599f        rtc_proxy_set_time+0x0/0x215 [redpill]
[   77.062871] 00 
[   77.062872] 48 
[   77.064790] 00 
[   77.066693] a0 
[   77.068610] ff 
[   77.070530] ff 
[   77.072443] ff 
[   77.074360] ff 
[   77.076277]  [06] 0x030      000000006a8faed4        bios_get_fan_state+0x0/0x10 [redpill]
[   77.086161] 0f 
[   77.086162] ed 
[   77.088075] 00 
[   77.089987] a0 
[   77.091902] ff 
[   77.093815] ff 
[   77.095728] ff 
[   77.097644] ff 
[   77.099564]  [07] 0x038      00000000c07ac642        bios_VTK_SET_FAN_STATE_null_zero_int+0x0/0x27 [redpill]
[   77.111147] 00 
[   77.111147] 00 
[   77.113067] 00 
[   77.114978] 00 
[   77.116894] 00 
[   77.118808] 00 
[   77.120713] 00 
[   77.122625] 00 
[   77.124543]  [08] 0x040      0000000000000000        0x0
[   77.131191] f0 
[   77.131192] 48 
[   77.133108] 00 
[   77.135021] a0 
[   77.136936] ff 
[   77.138850] ff 
[   77.140760] ff 
[   77.142677] ff 
[   77.144588]  [09] 0x048      00000000ebf6df74        bios_get_cpu_temp+0x0/0x40 [redpill]
[   77.154376] 50 
[   77.154376] 08 
[   77.156288] 29 
[   77.158205] a0 
[   77.160118] ff 
[   77.162032] ff 
[   77.163946] ff 
[   77.165857] ff 
[   77.167771]  [10] 0x050      000000009cc2b957        SetDiskLedStatusByLedTrigger+0x0/0x130 [epyc7002_synobios]
[   77.179623] 80 
[   77.179624] 14 
[   77.181539] 29 
[   77.183451] a0 
[   77.185368] ff 
[   77.187281] ff 
[   77.189192] ff 
[   77.191108] ff 
[   77.193024]  [11] 0x058      000000002792a9c2        SetPowerLedStatus+0x0/0x50 [epyc7002_synobios]
[   77.203740] 00 
[   77.203741] 00 
[   77.205653] 00 
[   77.207569] 00 
[   77.209481] 00 
[   77.211394] 00 
[   77.213309] 00 
[   77.215226] 00 
[   77.217139]  [12] 0x060      0000000000000000        0x0
[   77.223798] 00 
[   77.223799] 00 
[   77.225711] 00 
[   77.227628] 00 
[   77.229539] 00 
[   77.231454] 00 
[   77.233368] 00 
[   77.235283] 00 
[   77.237195]  [13] 0x068      0000000000000000        0x0
[   77.243856] 00 
[   77.243856] 00 
[   77.245768] 00 
[   77.247684] 00 
[   77.249596] 00 
[   77.251512] 00 
[   77.253425] 00 
[   77.255336] 00 
[   77.257252]  [14] 0x070      0000000000000000        0x0
[   77.263900] bc 
[   77.263901] ee 
[   77.265819] 00 
[   77.267729] a0 
[   77.269642] ff 
[   77.271558] ff 
[   77.273471] ff 
[   77.275388] ff 
[   77.277323]  [15] 0x078      00000000f952a3a0        shim_set_gpio_pin_usable+0x0/0x98 [redpill]
[   77.287777] a0 
[   77.287778] 4c 
[   77.289693] 00 
[   77.291604] a0 
[   77.293521] ff 
[   77.295435] ff 
[   77.297346] ff 
[   77.299263] ff 
[   77.301189]  [16] 0x080      0000000081b034fa        shim_get_gpio_pin_usable+0x0/0x10 [redpill]
[   77.311638] 84 
[   77.311639] ed 
[   77.313561] 00 
[   77.315462] a0 
[   77.317378] ff 
[   77.319289] ff 
[   77.321202] ff 
[   77.323120] ff 
[   77.325035]  [17] 0x088      000000004d032948        bios_VTK_SET_GPIO_PIN_BLINK_null_zero_int+0x0/0x27 [redpill]
[   77.337080] fa 
[   77.337080] ea 
[   77.338996] 00 
[   77.340908] a0 
[   77.342821] ff 
[   77.344737] ff 
[   77.346650] ff 
[   77.348562] ff 
[   77.350483]  [18] 0x090      000000006c3f2fef        rtc_proxy_set_auto_power_on+0x0/0x74 [redpill]
[   77.361205] 7f 
[   77.361206] ea 
[   77.363117] 00 
[   77.365034] a0 
[   77.366945] ff 
[   77.368860] ff 
[   77.370773] ff 
[   77.372687] ff 
[   77.374608]  [19] 0x098      000000002e35ba90        rtc_proxy_get_auto_power_on+0x0/0x7b [redpill]
[   77.385337] 51 
[   77.385337] ea 
[   77.387251] 00 
[   77.389164] a0 
[   77.391081] ff 
[   77.392994] ff 
[   77.394909] ff 
[   77.396821] ff 
[   77.398742]  [20] 0x0a0      00000000650350ca        rtc_proxy_init_auto_power_on+0x0/0x2e [redpill]
[   77.409567] 6e 
[   77.409567] eb 
[   77.411479] 00 
[   77.413395] a0 
[   77.415307] ff 
[   77.417223] ff 
[   77.419136] ff 
[   77.421048] ff 
[   77.422967]  [21] 0x0a8      00000000103448b2        rtc_proxy_uinit_auto_power_on+0x0/0x2e [redpill]
[   77.433887] 60 
[   77.433887] 14 
[   77.435805] 29 
[   77.437717] a0 
[   77.439624] ff 
[   77.441534] ff 
[   77.443449] ff 
[   77.445362] ff 
[   77.447282]  [22] 0x0b0      000000007e176522        SetAlarmLed+0x0/0x20 [epyc7002_synobios]
[   77.457437] b0 
[   77.457437] 4c 
[   77.459355] 00 
[   77.461266] a0 
[   77.463182] ff 
[   77.465094] ff 
[   77.467010] ff 
[   77.468923] ff 
[   77.470839]  [23] 0x0b8      00000000957312bc        bios_get_buz_clr+0x0/0x10 [redpill]
[   77.480534] d2 
[   77.480535] ed 
[   77.482450] 00 
[   77.484353] a0 
[   77.486258] ff 
[   77.488174] ff 
[   77.490086] ff 
[   77.491998] ff 
[   77.493919]  [24] 0x0c0      00000000dd850310        bios_VTK_SET_BUZ_CLR_null_zero_int+0x0/0x27 [redpill]
[   77.505293] c0 
[   77.505294] 4c 
[   77.507207] 00 
[   77.509122] a0 
[   77.511035] ff 
[   77.512951] ff 
[   77.514863] ff 
[   77.516778] ff 
[   77.518686]  [25] 0x0c8      00000000b16a5213        bios_get_power_status+0x0/0x20 [redpill]
[   77.528853] 00 
[   77.528853] 00 
[   77.530764] 00 
[   77.532678] 00 
[   77.534592] 00 
[   77.536505] 00 
[   77.538421] 00 
[   77.540334] 00 
[   77.542250]  [26] 0x0d0      0000000000000000        0x0
[   77.548910] e0 
[   77.548910] 12 
[   77.550823] 29 
[   77.552734] a0 
[   77.554651] ff 
[   77.556562] ff 
[   77.558475] ff 
[   77.560391] ff 
[   77.562306]  [27] 0x0d8      000000002e249ef8        InitModuleType+0x0/0x30 [epyc7002_synobios]
[   77.572750] 70 
[   77.572751] 13 
[   77.574672] 29 
[   77.576582] a0 
[   77.578499] ff 
[   77.580401] ff 
[   77.582318] ff 
[   77.584231] ff 
[   77.586149]  [28] 0x0e0      00000000effb23cc        Uninitialize+0x0/0x40 [epyc7002_synobios]
[   77.596407] f9 
[   77.596407] ed 
[   77.598319] 00 
[   77.600237] a0 
[   77.602156] ff 
[   77.604069] ff 
[   77.605987] ff 
[   77.607908] ff 
[   77.609826]  [29] 0x0e8      000000000e96a5fd        bios_VTK_SET_CPU_FAN_STATUS_null_zero_int+0x0/0x27 [redpill]
[   77.621869] 20 
[   77.621869] ee 
[   77.623786] 00 
[   77.625697] a0 
[   77.627610] ff 
[   77.629525] ff 
[   77.631441] ff 
[   77.633354] ff 
[   77.635271]  [30] 0x0f0      0000000032d7d8e4        bios_VTK_SET_PHY_LED_null_zero_int+0x0/0x27 [redpill]
[   77.646666] c0 
[   77.646667] 09 
[   77.648581] 29 
[   77.650492] a0 
[   77.652406] ff 
[   77.654323] ff 
[   77.656233] ff 
[   77.658151] ff 
[   77.660069]  [31] 0x0f8      0000000073a8ebce        SetHddActLedByLedTrigger+0x0/0x190 [epyc7002_synobios]
[   77.671554] 00 
[   77.671554] 00 
[   77.673469] 00 
[   77.675383] 00 
[   77.677297] 00 
[   77.679201] 00 
[   77.681116] 00 
[   77.683029] 00 
[   77.684946]  [32] 0x100      0000000000000000        0x0
[   77.691594] 6e 
[   77.691595] ee 
[   77.693491] 00 
[   77.695407] a0 
[   77.697319] ff 
[   77.699232] ff 
[   77.701148] ff 
[   77.703060] ff 
[   77.704982]  [33] 0x108      00000000c5189650        bios_VTK_GET_MICROP_ID_null_zero_int+0x0/0x27 [redpill]
[   77.716562] 95 
[   77.716562] ee 
[   77.718477] 00 
[   77.720390] a0 
[   77.722302] ff 
[   77.724209] ff 
[   77.726124] ff 
[   77.728036] ff 
[   77.729953]  [34] 0x110      0000000019375d9f        bios_VTK_SET_MICROP_ID_null_zero_int+0x0/0x27 [redpill]
[   77.741538] 00 
[   77.741539] 00 
[   77.743448] 00 
[   77.745365] 00 
[   77.747277] 00 
[   77.749192] 00 
[   77.751107] 00 
[   77.753018] 00 
[   77.754934]  [35] 0x118      0000000000000000        0x0
[   77.761582] 00 
[   77.761583] 00 
[   77.763499] 00 
[   77.765411] 00 
[   77.767322] 00 
[   77.769236] 00 
[   77.771151] 00 
[   77.773065] 00 
[   77.774980]  [36] 0x120      0000000000000000        0x0
[   77.781642] 00 
[   77.781642] 00 
[   77.783561] 00 
[   77.785474] 00 
[   77.787387] 00 
[   77.789303] 00 
[   77.791214] 00 
[   77.793132] 00 
[   77.795044]  [37] 0x128      0000000000000000        0x0
[   77.801704] 00 
[   77.801704] 00 
[   77.803619] 00 
[   77.805530] 00 
[   77.807447] 00 
[   77.809366] 00 
[   77.811283] 00 
[   77.813193] 00 
[   77.815110]  [38] 0x130      0000000000000000        0x0
[   77.821774] 00 
[   77.821775] 00 
[   77.823697] 00 
[   77.825610] 00 
[   77.827525] 00 
[   77.829437] 00 
[   77.831354] 00 
[   77.833269] 00 
[   77.835183]  [39] 0x138      0000000000000000        0x0
[   77.841842] b0 
[   77.841842] 13 
[   77.843755] 29 
[   77.845667] a0 
[   77.847583] ff 
[   77.849493] ff 
[   77.851409] ff 
[   77.853321] ff 
[   77.855238]  [40] 0x140      000000009fad66ab        GetCPUInfo+0x0/0x70 [epyc7002_synobios]
[   77.865303] 00 
[   77.865304] 00 
[   77.867219] 00 
[   77.869132] 00 
[   77.871042] 00 
[   77.872959] 00 
[   77.874873] 00 
[   77.876786] 00 
[   77.878703]  [41] 0x148      0000000000000000        0x0
[   77.885351] 00 
[   77.885351] 00 
[   77.887267] 00 
[   77.889189] 00 
[   77.891102] 00 
[   77.893012] 00 
[   77.894925] 00 
[   77.896839] 00 
[   77.898758]  [42] 0x150      0000000000000000        0x0
[   77.905423] 70 
[   77.905424] 16 
[   77.907328] 29 
[   77.909242] a0 
[   77.911158] ff 
[   77.913070] ff 
[   77.914982] ff 
[   77.916897] ff 
[   77.918816]  [43] 0x158      0000000036138bf2        HWMONGetFanSpeedRPMFromADT+0x0/0x60 [epyc7002_synobios]
[   77.930389] 20 
[   77.930390] 14 
[   77.932308] 29 
[   77.934226] a0 
[   77.936137] ff 
[   77.938049] ff 
[   77.939963] ff 
[   77.941878] ff 
[   77.943792]  [44] 0x160      0000000068cb9e18        EPYC7002GetPSUStatusByI2C+0x0/0x40 [epyc7002_synobios]
[   77.955285] 10 
[   77.955286] 16 
[   77.957204] 29 
[   77.959121] a0 
[   77.961032] ff 
[   77.962947] ff 
[   77.964863] ff 
[   77.966773] ff 
[   77.968691]  [45] 0x168      000000004bffb431        HWMONGetVoltageSensorFromADT+0x0/0x60 [epyc7002_synobios]
[   77.980464] e0 
[   77.980464] 17 
[   77.982375] 29 
[   77.984290] a0 
[   77.986203] ff 
[   77.988119] ff 
[   77.990033] ff 
[   77.991947] ff 
[   77.993864]  [46] 0x170      00000000236403cf        HWMONGetHDDBackPlaneStatusBySMBUS+0x0/0x160 [epyc7002_synobios]
[   78.006204] b0 
[   78.006205] 15 
[   78.008125] 29 
[   78.010037] a0 
[   78.011954] ff 
[   78.013867] ff 
[   78.015779] ff 
[   78.017696] ff 
[   78.019610]  [47] 0x178      00000000f4f9341b        HWMONGetThermalSensorFromADT+0x0/0x60 [epyc7002_synobios]
[   78.031383] 00 
[   78.031383] 00 
[   78.033298] 00 
[   78.035210] 00 
[   78.037126] 00 
[   78.039038] 00 
[   78.040950] 00 
[   78.042866] 00 
[   78.044779]  [48] 0x180      0000000000000000        0x0
[   78.051448] 00 
[   78.051448] 00 
[   78.053362] 00 
[   78.055276] 00 
[   78.057188] 00 
[   78.059094] 00 
[   78.061008] 00 
[   78.062924] 00 
[   78.064837]  [49] 0x188      0000000000000000        0x0
[   78.071500] 00 
[   78.071500] 00 
[   78.073421] 00 
[   78.075335] 00 
[   78.077241] 00 
[   78.079151] 00 
[   78.081069] 00 
[   78.082981] 00 
[   78.084894]  [50] 0x190      0000000000000000        0x0
[   78.091554] 00 
[   78.091554] 00 
[   78.093469] 00 
[   78.095381] 00 
[   78.097298] 00 
[   78.099209] 00 
[   78.101126] 00 
[   78.103043] 00 
[   78.104961]  [51] 0x198      0000000000000000        0x0
[   78.111619] 00 
[   78.111620] 00 
[   78.113531] 00 
[   78.115447] 00 
[   78.117359] 00 
[   78.119273] 00 
[   78.121187] 00 
[   78.123101] 00 
[   78.125018]  [52] 0x1a0      0000000000000000        0x0
[   78.131675] 
[   78.133300] <redpill/bios_shims_collection.c:117> Finished printing memory at 0000000053d08b32
[   78.142679] <redpill/bios_shims_collection.c:86> mfgBIOS vtable [10] originally SetDiskLedStatusByLedTrigger [epyc7002_synobios]<000000009cc2b957> will now be bios_VTK_SET_DISK_LED_null_zero_int [redpill]<0000000017eb00ed>
[   78.164154] <redpill/bios_shims_collection.c:86> mfgBIOS vtable [11] originally SetPowerLedStatus [epyc7002_synobios]<000000002792a9c2> will now be bios_VTK_SET_PWR_LED_null_zero_int [redpill]<00000000ef3022d1>
[   78.184483] <redpill/bios_shims_collection.c:86> mfgBIOS vtable [22] originally SetAlarmLed [epyc7002_synobios]<000000007e176522> will now be bios_VTK_SET_ALR_LED_null_zero_int [redpill]<0000000060df12f9>
[   78.204250] <redpill/bios_shims_collection.c:86> mfgBIOS vtable [31] originally SetHddActLedByLedTrigger [epyc7002_synobios]<0000000073a8ebce> will now be bios_VTK_SET_HDD_ACT_LED_null_zero_int [redpill]<000000001b648c9c>
[   78.225601] <redpill/bios_shims_collection.c:155> Platform requires RTC proxy - enabling
[   78.234411] <redpill/rtc_proxy.c:260> Registering RTC proxy shim
[   78.240947] <redpill/rtc_proxy.c:263> The RTC proxy shim is already registered - unregistering first
[   78.250887] <redpill/rtc_proxy.c:244> Unregistering RTC proxy shim
[   78.257600] <redpill/rtc_proxy.c:254> Successfully unregistered RTC proxy shim
[   78.265453] <redpill/rtc_proxy.c:268> Successfully registered RTC proxy shim
[   78.273123] <redpill/bios_hwmon_shim.c:332> Registering mfgBIOS HW Monitor shim
[   78.281090] <redpill/bios_shims_collection.c:86> mfgBIOS vtable [47] originally HWMONGetThermalSensorFromADT [epyc7002_synobios]<00000000f4f9341b> will now be bios_hwmon_get_thermal [redpill]<00000000b112f6a9>
[   78.301317] <redpill/bios_shims_collection.c:86> mfgBIOS vtable [45] originally HWMONGetVoltageSensorFromADT [epyc7002_synobios]<000000004bffb431> will now be bios_hwmon_get_voltages [redpill]<00000000103e34b5>
[   78.321659] <redpill/bios_shims_collection.c:86> mfgBIOS vtable [43] originally HWMONGetFanSpeedRPMFromADT [epyc7002_synobios]<0000000036138bf2> will now be bios_hwmon_get_fans_rpm [redpill]<000000002f3cd437>
[   78.341813] <redpill/bios_shims_collection.c:86> mfgBIOS vtable [46] originally HWMONGetHDDBackPlaneStatusBySMBUS [epyc7002_synobios]<00000000236403cf> will now be bios_hwmon_get_hdd_backplane [redpill]<00000000bfc9cb4e>
[   78.363094] <redpill/bios_hwmon_shim.c:358> Successfully registered mfgBIOS HW Monitor shim
[   78.372192] <redpill/bios_shims_collection.c:104> Will print 424 bytes of memory from 0000000015ec51ce
[   78.382327] 40 
[   78.382327] d7 
[   78.384239] 29 
[   78.386152] a0 
[   78.388058] ff 
[   78.389974] ff 
[   78.391885] ff 
[   78.393801] ff 
[   78.395720]  [00] 0x000      00000000c77bae42        __this_module+0x0/0xffffffffffff58c0 [epyc7002_synobios]
[   78.407385] 00 
[   78.407386] b6 
[   78.409297] 28 
[   78.411214] a0 
[   78.413125] ff 
[   78.415038] ff 
[   78.416955] ff 
[   78.418866] ff 
[   78.420787]  [01] 0x008      00000000d26c8397        GetBrand+0x0/0x10 [epyc7002_synobios]
[   78.430667] f0 
[   78.430667] 16 
[   78.432579] 29 
[   78.434496] a0 
[   78.436410] ff 
[   78.438321] ff 
[   78.440238] ff 
[   78.442145] ff 
[   78.444053]  [02] 0x010      0000000050299f21        GetModel+0x0/0xa0 [epyc7002_synobios]
[   78.453918] 00 
[   78.453919] 00 
[   78.455831] 00 
[   78.457746] 00 
[   78.459659] 00 
[   78.461571] 00 
[   78.463486] 00 
[   78.465399] 00 
[   78.467315]  [03] 0x018      0000000000000000        0x0
[   78.473976] 6c 
[   78.473977] e7 
[   78.475898] 00 
[   78.477809] a0 
[   78.479726] ff 
[   78.481638] ff 
[   78.483549] ff 
[   78.485464] ff 
[   78.487383]  [04] 0x020      000000004704f422        rtc_proxy_get_time+0x0/0xd0 [redpill]
[   78.497257] 3c 
[   78.497258] e8 
[   78.499171] 00 
[   78.501086] a0 
[   78.502997] ff 
[   78.504914] ff 
[   78.506827] ff 
[   78.508724] ff 
[   78.510641]  [05] 0x028      00000000c5a7599f        rtc_proxy_set_time+0x0/0x215 [redpill]
[   78.520599] 00 
[   78.520600] 48 
[   78.522505] 00 
[   78.524420] a0 
[   78.526332] ff 
[   78.528245] ff 
[   78.530151] ff 
[   78.532068] ff 
[   78.533976]  [06] 0x030      000000006a8faed4        bios_get_fan_state+0x0/0x10 [redpill]
[   78.543860] 0f 
[   78.543860] ed 
[   78.545773] 00 
[   78.547689] a0 
[   78.549601] ff 
[   78.551514] ff 
[   78.553429] ff 
[   78.555342] ff 
[   78.557258]  [07] 0x038      00000000c07ac642        bios_VTK_SET_FAN_STATE_null_zero_int+0x0/0x27 [redpill]
[   78.568834] 00 
[   78.568835] 00 
[   78.570745] 00 
[   78.572657] 00 
[   78.574573] 00 
[   78.576485] 00 
[   78.578402] 00 
[   78.580317] 00 
[   78.582230]  [08] 0x040      0000000000000000        0x0
[   78.588889] f0 
[   78.588890] 48 
[   78.590802] 00 
[   78.592714] a0 
[   78.594629] ff 
[   78.596547] ff 
[   78.598452] ff 
[   78.600365] ff 
[   78.602281]  [09] 0x048      00000000ebf6df74        bios_get_cpu_temp+0x0/0x40 [redpill]
[   78.612068] 36 
[   78.612069] ed 
[   78.613985] 00 
[   78.615895] a0 
[   78.617803] ff 
[   78.619715] ff 
[   78.621630] ff 
[   78.623544] ff 
[   78.625464]  [10] 0x050      0000000017eb00ed        bios_VTK_SET_DISK_LED_null_zero_int+0x0/0x27 [redpill]
[   78.636951] 5d 
[   78.636952] ed 
[   78.638862] 00 
[   78.640779] a0 
[   78.642691] ff 
[   78.644604] ff 
[   78.646519] ff 
[   78.648432] ff 
[   78.650352]  [11] 0x058      00000000ef3022d1        bios_VTK_SET_PWR_LED_null_zero_int+0x0/0x27 [redpill]
[   78.661744] 00 
[   78.661745] 00 
[   78.663655] 00 
[   78.665573] 00 
[   78.667483] 00 
[   78.669398] 00 
[   78.671311] 00 
[   78.673225] 00 
[   78.675142]  [12] 0x060      0000000000000000        0x0
[   78.681809] 00 
[   78.681809] 00 
[   78.683723] 00 
[   78.685637] 00 
[   78.687549] 00 
[   78.689462] 00 
[   78.691378] 00 
[   78.693290] 00 
[   78.695198]  [13] 0x068      0000000000000000        0x0
[   78.701864] 00 
[   78.701864] 00 
[   78.703779] 00 
[   78.705694] 00 
[   78.707606] 00 
[   78.709518] 00 
[   78.711435] 00 
[   78.713347] 00 
[   78.715259]  [14] 0x070      0000000000000000        0x0
[   78.721920] bc 
[   78.721921] ee 
[   78.723836] 00 
[   78.725747] a0 
[   78.727665] ff 
[   78.729575] ff 
[   78.731491] ff 
[   78.733403] ff 
[   78.735322]  [15] 0x078      00000000f952a3a0        shim_set_gpio_pin_usable+0x0/0x98 [redpill]
[   78.745771] a0 
[   78.745771] 4c 
[   78.747693] 00 
[   78.749606] a0 
[   78.751511] ff 
[   78.753428] ff 
[   78.755342] ff 
[   78.757254] ff 
[   78.759172]  [16] 0x080      0000000081b034fa        shim_get_gpio_pin_usable+0x0/0x10 [redpill]
[   78.769621] 84 
[   78.769622] ed 
[   78.771526] 00 
[   78.773439] a0 
[   78.775346] ff 
[   78.777258] ff 
[   78.779172] ff 
[   78.781105] ff 
[   78.783024]  [17] 0x088      000000004d032948        bios_VTK_SET_GPIO_PIN_BLINK_null_zero_int+0x0/0x27 [redpill]
[   78.795078] fa 
[   78.795078] ea 
[   78.796989] 00 
[   78.798908] a0 
[   78.800830] ff 
[   78.802740] ff 
[   78.804657] ff 
[   78.806569] ff 
[   78.808491]  [18] 0x090      000000006c3f2fef        rtc_proxy_set_auto_power_on+0x0/0x74 [redpill]
[   78.819218] 7f 
[   78.819219] ea 
[   78.821134] 00 
[   78.823046] a0 
[   78.824959] ff 
[   78.826876] ff 
[   78.828791] ff 
[   78.830703] ff 
[   78.832621]  [19] 0x098      000000002e35ba90        rtc_proxy_get_auto_power_on+0x0/0x7b [redpill]
[   78.843342] 51 
[   78.843343] ea 
[   78.845260] 00 
[   78.847171] a0 
[   78.849084] ff 
[   78.851001] ff 
[   78.852913] ff 
[   78.854829] ff 
[   78.856745]  [20] 0x0a0      00000000650350ca        rtc_proxy_init_auto_power_on+0x0/0x2e [redpill]
[   78.867570] 6e 
[   78.867570] eb 
[   78.869486] 00 
[   78.871399] a0 
[   78.873314] ff 
[   78.875228] ff 
[   78.877138] ff 
[   78.879056] ff 
[   78.880972]  [21] 0x0a8      00000000103448b2        rtc_proxy_uinit_auto_power_on+0x0/0x2e [redpill]
[   78.891890] ab 
[   78.891890] ed 
[   78.893795] 00 
[   78.895714] a0 
[   78.897631] ff 
[   78.899547] ff 
[   78.901460] ff 
[   78.903376] ff 
[   78.905293]  [22] 0x0b0      0000000060df12f9        bios_VTK_SET_ALR_LED_null_zero_int+0x0/0x27 [redpill]
[   78.916686] b0 
[   78.916687] 4c 
[   78.918597] 00 
[   78.920510] a0 
[   78.922427] ff 
[   78.924339] ff 
[   78.926250] ff 
[   78.928165] ff 
[   78.930083]  [23] 0x0b8      00000000957312bc        bios_get_buz_clr+0x0/0x10 [redpill]
[   78.939779] d2 
[   78.939780] ed 
[   78.941699] 00 
[   78.943615] a0 
[   78.945528] ff 
[   78.947440] ff 
[   78.949352] ff 
[   78.951269] ff 
[   78.953185]  [24] 0x0c0      00000000dd850310        bios_VTK_SET_BUZ_CLR_null_zero_int+0x0/0x27 [redpill]
[   78.964578] c0 
[   78.964579] 4c 
[   78.966492] 00 
[   78.968406] a0 
[   78.970318] ff 
[   78.972235] ff 
[   78.974149] ff 
[   78.976063] ff 
[   78.977983]  [25] 0x0c8      00000000b16a5213        bios_get_power_status+0x0/0x20 [redpill]
[   78.988144] 00 
[   78.988145] 00 
[   78.990058] 00 
[   78.991970] 00 
[   78.993885] 00 
[   78.995797] 00 
[   78.997714] 00 
[   78.999625] 00 
[   79.001542]  [26] 0x0d0      0000000000000000        0x0
[   79.008199] e0 
[   79.008199] 12 
[   79.010114] 29 
[   79.012017] a0 
[   79.013933] ff 
[   79.015844] ff 
[   79.017759] ff 
[   79.019672] ff 
[   79.021592]  [27] 0x0d8      000000002e249ef8        InitModuleType+0x0/0x30 [epyc7002_synobios]
[   79.032039] 70 
[   79.032039] 13 
[   79.033955] 29 
[   79.035864] a0 
[   79.037781] ff 
[   79.039693] ff 
[   79.041609] ff 
[   79.043523] ff 
[   79.045437]  [28] 0x0e0      00000000effb23cc        Uninitialize+0x0/0x40 [epyc7002_synobios]
[   79.055701] f9 
[   79.055702] ed 
[   79.057621] 00 
[   79.059533] a0 
[   79.061450] ff 
[   79.063363] ff 
[   79.065278] ff 
[   79.067191] ff 
[   79.069102]  [29] 0x0e8      000000000e96a5fd        bios_VTK_SET_CPU_FAN_STATUS_null_zero_int+0x0/0x27 [redpill]
[   79.081147] 20 
[   79.081147] ee 
[   79.083058] 00 
[   79.084970] a0 
[   79.086888] ff 
[   79.088798] ff 
[   79.090715] ff 
[   79.092628] ff 
[   79.094545]  [30] 0x0f0      0000000032d7d8e4        bios_VTK_SET_PHY_LED_null_zero_int+0x0/0x27 [redpill]
[   79.105928] 47 
[   79.105929] ee 
[   79.107840] 00 
[   79.109758] a0 
[   79.111668] ff 
[   79.113584] ff 
[   79.115496] ff 
[   79.117408] ff 
[   79.119320]  [31] 0x0f8      000000001b648c9c        bios_VTK_SET_HDD_ACT_LED_null_zero_int+0x0/0x27 [redpill]
[   79.131089] 00 
[   79.131090] 00 
[   79.133004] 00 
[   79.134920] 00 
[   79.136830] 00 
[   79.138743] 00 
[   79.140659] 00 
[   79.142572] 00 
[   79.144489]  [32] 0x100      0000000000000000        0x0
[   79.151144] 6e 
[   79.151144] ee 
[   79.153058] 00 
[   79.154972] a0 
[   79.156887] ff 
[   79.158801] ff 
[   79.160712] ff 
[   79.162627] ff 
[   79.164548]  [33] 0x108      00000000c5189650        bios_VTK_GET_MICROP_ID_null_zero_int+0x0/0x27 [redpill]
[   79.176126] 95 
[   79.176126] ee 
[   79.178041] 00 
[   79.179958] a0 
[   79.181870] ff 
[   79.183783] ff 
[   79.185699] ff 
[   79.187612] ff 
[   79.189531]  [34] 0x110      0000000019375d9f        bios_VTK_SET_MICROP_ID_null_zero_int+0x0/0x27 [redpill]
[   79.201110] 00 
[   79.201110] 00 
[   79.203026] 00 
[   79.204938] 00 
[   79.206855] 00 
[   79.208766] 00 
[   79.210680] 00 
[   79.212595] 00 
[   79.214509]  [35] 0x118      0000000000000000        0x0
[   79.221169] 00 
[   79.221169] 00 
[   79.223084] 00 
[   79.224995] 00 
[   79.226912] 00 
[   79.228824] 00 
[   79.230741] 00 
[   79.232653] 00 
[   79.234565]  [36] 0x120      0000000000000000        0x0
[   79.241228] 00 
[   79.241229] 00 
[   79.243142] 00 
[   79.245053] 00 
[   79.246969] 00 
[   79.248883] 00 
[   79.250797] 00 
[   79.252710] 00 
[   79.254623]  [37] 0x128      0000000000000000        0x0
[   79.261286] 00 
[   79.261286] 00 
[   79.263193] 00 
[   79.265106] 00 
[   79.267020] 00 
[   79.268939] 00 
[   79.270856] 00 
[   79.272767] 00 
[   79.274680]  [38] 0x130      0000000000000000        0x0
[   79.281334] 00 
[   79.281335] 00 
[   79.283249] 00 
[   79.285162] 00 
[   79.287074] 00 
[   79.288990] 00 
[   79.290901] 00 
[   79.292817] 00 
[   79.294721]  [39] 0x138      0000000000000000        0x0
[   79.301384] b0 
[   79.301385] 13 
[   79.303297] 29 
[   79.305207] a0 
[   79.307125] ff 
[   79.309037] ff 
[   79.310953] ff 
[   79.312866] ff 
[   79.314781]  [40] 0x140      000000009fad66ab        GetCPUInfo+0x0/0x70 [epyc7002_synobios]
[   79.324837] 00 
[   79.324838] 00 
[   79.326752] 00 
[   79.328663] 00 
[   79.330576] 00 
[   79.332483] 00 
[   79.334399] 00 
[   79.336310] 00 
[   79.338225]  [41] 0x148      0000000000000000        0x0
[   79.344884] 00 
[   79.344884] 00 
[   79.346799] 00 
[   79.348712] 00 
[   79.350624] 00 
[   79.352540] 00 
[   79.354452] 00 
[   79.356369] 00 
[   79.358279]  [42] 0x150      0000000000000000        0x0
[   79.364938] 90 
[   79.364939] 4b 
[   79.366857] 00 
[   79.368767] a0 
[   79.370690] ff 
[   79.372603] ff 
[   79.374520] ff 
[   79.376435] ff 
[   79.378353]  [43] 0x158      000000002f3cd437        bios_hwmon_get_fans_rpm+0x0/0x110 [redpill]
[   79.388799] 20 
[   79.388799] 14 
[   79.390712] 29 
[   79.392627] a0 
[   79.394544] ff 
[   79.396456] ff 
[   79.398368] ff 
[   79.400286] ff 
[   79.402210]  [44] 0x160      0000000068cb9e18        EPYC7002GetPSUStatusByI2C+0x0/0x40 [epyc7002_synobios]
[   79.413690] 60 
[   79.413690] 4a 
[   79.415600] 00 
[   79.417515] a0 
[   79.419431] ff 
[   79.421346] ff 
[   79.423257] ff 
[   79.425173] ff 
[   79.427088]  [45] 0x168      00000000103e34b5        bios_hwmon_get_voltages+0x0/0x130 [redpill]
[   79.437529] 10 
[   79.437530] 48 
[   79.439440] 00 
[   79.441356] a0 
[   79.443263] ff 
[   79.445174] ff 
[   79.447091] ff 
[   79.449002] ff 
[   79.450923]  [46] 0x170      00000000bfc9cb4e        bios_hwmon_get_hdd_backplane+0x0/0xe0 [redpill]
[   79.461747] 50 
[   79.461747] 49 
[   79.463661] 00 
[   79.465573] a0 
[   79.467489] ff 
[   79.469405] ff 
[   79.471317] ff 
[   79.473230] ff 
[   79.475149]  [47] 0x178      00000000b112f6a9        bios_hwmon_get_thermal+0x0/0x110 [redpill]
[   79.485496] 00 
[   79.485497] 00 
[   79.487418] 00 
[   79.489328] 00 
[   79.491242] 00 
[   79.493152] 00 
[   79.495063] 00 
[   79.496971] 00 
[   79.498882]  [48] 0x180      0000000000000000        0x0
[   79.505541] 00 
[   79.505542] 00 
[   79.507454] 00 
[   79.509370] 00 
[   79.511281] 00 
[   79.513199] 00 
[   79.515109] 00 
[   79.517023] 00 
[   79.518940]  [49] 0x188      0000000000000000        0x0
[   79.525598] 00 
[   79.525598] 00 
[   79.527512] 00 
[   79.529427] 00 
[   79.531338] 00 
[   79.533255] 00 
[   79.535169] 00 
[   79.537084] 00 
[   79.538997]  [50] 0x190      0000000000000000        0x0
[   79.545666] 00 
[   79.545666] 00 
[   79.547578] 00 
[   79.549491] 00 
[   79.551407] 00 
[   79.553317] 00 
[   79.555231] 00 
[   79.557145] 00 
[   79.559059]  [51] 0x198      0000000000000000        0x0
[   79.565722] 00 
[   79.565723] 00 
[   79.567635] 00 
[   79.569547] 00 
[   79.571464] 00 
[   79.573365] 00 
[   79.575283] 00 
[   79.577199] 00 
[   79.579110]  [52] 0x1a0      0000000000000000        0x0
[   79.585768] 
[   79.587403] <redpill/bios_shims_collection.c:117> Finished printing memory at 0000000053d08b32
[   79.596758] <redpill/bios_shim.c:128> epyc7002_synobios BIOS *fully* shimmed
[   79.609175] Module [epyc7002_synobios] is removed. 
[   79.615330] synobios: unload
[   79.618553] <redpill/bios_shim.c:101> epyc7002_synobios BIOS went away - you may get a kernel panic if YOU unloaded it
[   79.631530] <redpill/override_symbol.c:256> Overriding apply_relocate_add() with (%pf?)()<00000000039f394e>
[   79.642469] <redpill/override_symbol.c:171> Saved apply_relocate_add() ptr <000000005fd11e6b>
[   79.652831] <redpill/memory_helper.c:17> Disabling memory protection for page(s) at 000000005fd11e6b+12/1 (<<00000000ebf98114)
[   79.665288] <redpill/override_symbol.c:220> Obtaining lock for <000000005fd11e6b/000000005fd11e6b>
[   79.675054] <redpill/override_symbol.c:181> Generating trampoline
[   79.683047] <redpill/override_symbol.c:186> Generated trampoline to 00000000039f394e<00000000039f394e> for apply_relocate_add<000000005fd11e6b>: 
[   79.697236] <redpill/override_symbol.c:220> Writing trampoline code to <000000005fd11e6b>
[   79.706135] <redpill/override_symbol.c:220> Released lock for <000000005fd11e6b>
[   79.714190] <redpill/memory_helper.c:33> Enabling memory protection for page(s) at 000000005fd11e6b+12/1 (<<00000000ebf98114)
[   79.726551] <redpill/override_symbol.c:268> Successfully overrode apply_relocate_add() with trampoline to 00000000039f394e<00000000039f394e>
[   79.740279] <redpill/rtc_proxy.c:244> Unregistering RTC proxy shim
[   79.748373] <redpill/rtc_proxy.c:254> Successfully unregistered RTC proxy shim
[   79.756225] <redpill/bios_hwmon_shim.c:364> Forcefully resetting mfgBIOS HW Monitor shim
[   79.765031] <redpill/bios_hwmon_shim.c:372> Successfully reset mfgBIOS HW Monitor
[   79.773168] <redpill/bios_hwcap_shim.c:111> Forcefully resetting mfgBIOS HW Capability shim
[   79.782254] <redpill/override_symbol.c:145> Freeing OVS for GetHwCapability
[   79.789834] <redpill/bios_hwcap_shim.c:115> Successfully reset mfgBIOS HW Capability
[   79.798257] <redpill/bios_psu_status_shim.c:55> Forcefully resetting mfgBIOS HWMONGetPSUStatusByI2C shim
[   79.808570] <redpill/override_symbol.c:145> Freeing OVS for HWMONGetPSUStatusByI2C
[   79.816801] <redpill/bios_psu_status_shim.c:59> Successfully reset mfgBIOS HWMONGetPSUStatusByI2C
[   79.996630] Module [rp] is removed. 
[   80.066569] ext3: synoboot1 mounted, process=mount
[   80.076068] ext4: synoboot1 mounted, process=mount
[   80.083151] ext2: synoboot1 mounted, process=mount
[   80.104301] VFS: opened file in mnt_point: (/dev), file: (/null), comm: (inetd), pid:(4912)
[   80.104303] VFS: opened file in mnt_point: (/dev), file: (/null), comm: (inetd), pid:(4867)
[   80.114518] VFS: opened file in mnt_point: (/dev), file: (/urandom), comm: (ttyd), pid:(4295)
[   80.123603] VFS: opened file in mnt_point: (/dev), file: (/null), comm: (ash), pid:(4295)
[   80.132883] VFS: opened file in mnt_point: (/dev), file: (/null), comm: (inetd), pid:(4296)
[   80.141777] VFS: opened file in mnt_point: (/dev), file: (/null), comm: (inetd), pid:(4579)
[   80.156267] VFS: opened file in mnt_point: (/dev), file: (/null), comm: (inetd), pid:(4912)
[   80.165503] VFS: opened file in mnt_point: (/dev), file: (/null), comm: (inetd), pid:(4867)
[   80.174592] VFS: opened file in mnt_point: (/dev), file: (/urandom), comm: (ttyd), pid:(4295)
[   80.183678] VFS: opened file in mnt_point: (/dev), file: (/null), comm: (ash), pid:(4295)
[   80.348136] Intel(R) 10GbE PCI Express Linux Network Driver - version 5.18.6
[   80.364821] Copyright(c) 1999 - 2022 Intel Corporation.
[   80.421410] RPC: Registered named UNIX socket transport module.
[   80.429178] RPC: Registered udp transport module.
[   80.434306] RPC: Registered tcp transport module.
[   80.439428] RPC: Registered tcp NFSv4.1 backchannel transport module.
[   81.519236] Module [adt7475] is removed. 
[   83.552525] Module [adt7475] is removed. 
[   85.587530] Module [adt7475] is removed. 
[   86.653109] <redpill/bios_shim.c:210> Symbol section <0000000078cde760> @ vaddr<18446744072100188160> size[10584]
[   86.664588] <redpill/bios_shim.c:219> Symbol #0 in mfgBIOS "epyc7002_synobios" {}<0000000000000000>
[   86.674444] <redpill/bios_shim.c:219> Symbol #1 in mfgBIOS "epyc7002_synobios" {}<000000006a758c3a>
[   86.684290] <redpill/bios_shim.c:219> Symbol #2 in mfgBIOS "epyc7002_synobios" {}<0000000066307673>
[   86.694132] <redpill/bios_shim.c:219> Symbol #3 in mfgBIOS "epyc7002_synobios" {}<00000000eff2a9c4>
[   86.703980] <redpill/bios_shim.c:219> Symbol #4 in mfgBIOS "epyc7002_synobios" {}<000000006ee5620a>
[   86.713823] <redpill/bios_shim.c:219> Symbol #5 in mfgBIOS "epyc7002_synobios" {}<0000000067f5ccc4>
[   86.723666] <redpill/bios_shim.c:219> Symbol #6 in mfgBIOS "epyc7002_synobios" {}<000000000ff0e3b4>
[   86.733493] <redpill/bios_shim.c:219> Symbol #7 in mfgBIOS "epyc7002_synobios" {}<0000000088b283fa>
[   86.743340] <redpill/bios_shim.c:219> Symbol #8 in mfgBIOS "epyc7002_synobios" {__UNIQUE_ID_depends105}<00000000843c8de2>
[   86.755260] <redpill/bios_shim.c:219> Symbol #9 in mfgBIOS "epyc7002_synobios" {__UNIQUE_ID_retpoline104}<00000000b7500e00>
[   86.767370] <redpill/bios_shim.c:219> Symbol #10 in mfgBIOS "epyc7002_synobios" {__UNIQUE_ID_name103}<00000000142743a5>
[   86.779103] <redpill/bios_shim.c:219> Symbol #11 in mfgBIOS "epyc7002_synobios" {__UNIQUE_ID_vermagic102}<00000000648695db>
[   86.791213] <redpill/bios_shim.c:219> Symbol #12 in mfgBIOS "epyc7002_synobios" {_note_7}<00000000b25b8843>
[   86.801786] <redpill/bios_shim.c:219> Symbol #13 in mfgBIOS "epyc7002_synobios" {__FUNCTION__.42208}<00000000eff2a9c4>
[   86.813424] <redpill/bios_shim.c:219> Symbol #14 in mfgBIOS "epyc7002_synobios" {check_gpio_consistency.cold.1}<0000000066307673>
[   86.826100] <redpill/bios_shim.c:219> Symbol #15 in mfgBIOS "epyc7002_synobios" {SYNO_CTRL_FAN_RESISTOR.cold.2}<00000000a45a84ba>
[   86.838778] <redpill/bios_shim.c:219> Symbol #16 in mfgBIOS "epyc7002_synobios" {SYNO_CTRL_FAN_STATUS_GET.cold.3}<00000000c09a882f>
[   86.851626] <redpill/bios_shim.c:219> Symbol #17 in mfgBIOS "epyc7002_synobios" {SYNO_HDD_LED_SET.cold.4}<00000000cbd8d53d>
[   86.863728] <redpill/bios_shim.c:219> Symbol #18 in mfgBIOS "epyc7002_synobios" {SYNO_COPY_BUTTON_GPIO_GET.cold.5}<000000005244ad0e>
[   86.876692] <redpill/bios_shim.c:219> Symbol #19 in mfgBIOS "epyc7002_synobios" {SYNO_ENABLE_HDD_LED.cold.6}<00000000b47bce47>
[   86.889091] <redpill/bios_shim.c:219> Symbol #20 in mfgBIOS "epyc7002_synobios" {SYNO_ENABLE_PHY_LED.cold.7}<00000000cd1f4024>
[   86.901486] <redpill/bios_shim.c:219> Symbol #21 in mfgBIOS "epyc7002_synobios" {SYNO_BUZZER_BUTTON_GPIO_GET.cold.8}<0000000070bf958b>
[   86.914635] <redpill/bios_shim.c:219> Symbol #22 in mfgBIOS "epyc7002_synobios" {SYNO_CTRL_BUZZER_MUTE_SET.cold.9}<000000000f274026>
[   86.927598] <redpill/bios_shim.c:219> Symbol #23 in mfgBIOS "epyc7002_synobios" {.LC6}<00000000be5fa628>
[   86.937920] <redpill/bios_shim.c:219> Symbol #24 in mfgBIOS "epyc7002_synobios" {__kstrtab_save_char_from_uart}<00000000aa9b1438>
[   86.950590] <redpill/bios_shim.c:219> Symbol #25 in mfgBIOS "epyc7002_synobios" {__kstrtabns_save_char_from_uart}<000000007622b1f0>
[   86.963455] <redpill/bios_shim.c:219> Symbol #26 in mfgBIOS "epyc7002_synobios" {__ksymtab_save_char_from_uart}<000000008714ec5a>
[   86.976132] <redpill/bios_shim.c:219> Symbol #27 in mfgBIOS "epyc7002_synobios" {__kstrtab_save_current_data_from_uart}<0000000052d0d1cb>
[   86.989557] <redpill/bios_shim.c:219> Symbol #28 in mfgBIOS "epyc7002_synobios" {__kstrtabns_save_current_data_from_uart}<000000005cd95cda>
[   87.003177] <redpill/bios_shim.c:219> Symbol #29 in mfgBIOS "epyc7002_synobios" {__ksymtab_save_current_data_from_uart}<00000000db53e31c>
[   87.016608] <redpill/bios_shim.c:219> Symbol #30 in mfgBIOS "epyc7002_synobios" {__kstrtab_synobios_lock_ttyS_protection}<00000000f8e5aa7b>
[   87.030229] <redpill/bios_shim.c:219> Symbol #31 in mfgBIOS "epyc7002_synobios" {__kstrtabns_synobios_lock_ttyS_protection}<00000000370363c5>
[   87.044038] <redpill/bios_shim.c:219> Symbol #32 in mfgBIOS "epyc7002_synobios" {__ksymtab_synobios_lock_ttyS_protection}<00000000042d8e8b>
[   87.057651] <redpill/bios_shim.c:219> Symbol #33 in mfgBIOS "epyc7002_synobios" {__kstrtab_synobios_lock_ttyS_current}<000000004824e24a>
[   87.070988] <redpill/bios_shim.c:219> Symbol #34 in mfgBIOS "epyc7002_synobios" {__kstrtabns_synobios_lock_ttyS_current}<00000000a7bdb60c>
[   87.084515] <redpill/bios_shim.c:219> Symbol #35 in mfgBIOS "epyc7002_synobios" {__ksymtab_synobios_lock_ttyS_current}<0000000067d87d47>
[   87.097845] <redpill/bios_shim.c:219> Symbol #36 in mfgBIOS "epyc7002_synobios" {__kstrtab_try_wakeup_waiting_microp}<000000006dfbf901>
[   87.111084] <redpill/bios_shim.c:219> Symbol #37 in mfgBIOS "epyc7002_synobios" {__kstrtabns_try_wakeup_waiting_microp}<00000000bb20b395>
[   87.124517] <redpill/bios_shim.c:219> Symbol #38 in mfgBIOS "epyc7002_synobios" {__ksymtab_try_wakeup_waiting_microp}<000000000554633a>
[   87.137761] <redpill/bios_shim.c:219> Symbol #39 in mfgBIOS "epyc7002_synobios" {syno_ttyS_read}<000000004dd98027>
[   87.149020] <redpill/bios_shim.c:219> Symbol #40 in mfgBIOS "epyc7002_synobios" {syno_ttyS_read.cold.8}<000000007c8f8ab5>
[   87.160944] <redpill/bios_shim.c:219> Symbol #41 in mfgBIOS "epyc7002_synobios" {state.29417}<0000000045a7db77>
[   87.171922] <redpill/bios_shim.c:219> Symbol #42 in mfgBIOS "epyc7002_synobios" {save_bytes.29416}<00000000e86d00c1>
[   87.183377] <redpill/bios_shim.c:219> Symbol #43 in mfgBIOS "epyc7002_synobios" {state.29435}<00000000548dc4d9>
[   87.194358] <redpill/bios_shim.c:219> Symbol #44 in mfgBIOS "epyc7002_synobios" {syno_ttyS_set_termios.cold.9}<000000004491d175>
[   87.206938] <redpill/bios_shim.c:219> Symbol #45 in mfgBIOS "epyc7002_synobios" {__key.29453}<00000000548dc4d9>
[   87.217905] <redpill/bios_shim.c:219> Symbol #46 in mfgBIOS "epyc7002_synobios" {__key.11921}<00000000548dc4d9>
[   87.228876] <redpill/bios_shim.c:219> Symbol #47 in mfgBIOS "epyc7002_synobios" {syno_ttyS_open.cold.10}<00000000ea881b45>
[   87.240892] <redpill/bios_shim.c:219> Symbol #48 in mfgBIOS "epyc7002_synobios" {syno_ttyS_write_with_length.cold.11}<00000000210b1d72>
[   87.254140] <redpill/bios_shim.c:219> Symbol #49 in mfgBIOS "epyc7002_synobios" {synobios_lock_ttyS_write.cold.12}<00000000ce39bec3>
[   87.267099] <redpill/bios_shim.c:219> Symbol #50 in mfgBIOS "epyc7002_synobios" {syno_ttyS_close.cold.13}<00000000b502e2f8>
[   87.279194] <redpill/bios_shim.c:219> Symbol #51 in mfgBIOS "epyc7002_synobios" {__kstrtab_syno_append_shutdown_hook}<00000000e6df334d>
[   87.292433] <redpill/bios_shim.c:219> Symbol #52 in mfgBIOS "epyc7002_synobios" {__kstrtabns_syno_append_shutdown_hook}<000000002f833dce>
[   87.305869] <redpill/bios_shim.c:219> Symbol #53 in mfgBIOS "epyc7002_synobios" {__ksymtab_syno_append_shutdown_hook}<00000000a2c1901f>
[   87.319100] <redpill/bios_shim.c:219> Symbol #54 in mfgBIOS "epyc7002_synobios" {syno_shutdown_hooks}<000000006d05afb0>
[   87.330835] <redpill/bios_shim.c:219> Symbol #55 in mfgBIOS "epyc7002_synobios" {synobios_read_proc_cpu_arch_open}<000000001128a7dc>
[   87.343800] <redpill/bios_shim.c:219> Symbol #56 in mfgBIOS "epyc7002_synobios" {synobios_read_proc_cpu_arch}<00000000b30d1ed7>
[   87.356290] <redpill/bios_shim.c:219> Symbol #57 in mfgBIOS "epyc7002_synobios" {synobios_read_proc_crypto_hw_open}<000000007c7bc7c9>
[   87.369345] <redpill/bios_shim.c:219> Symbol #58 in mfgBIOS "epyc7002_synobios" {synobios_read_proc_crypto_hw}<0000000068ee7515>
[   87.381911] <redpill/bios_shim.c:219> Symbol #59 in mfgBIOS "epyc7002_synobios" {synobios_read_proc_platform_open}<00000000d3a8e252>
[   87.394864] <redpill/bios_shim.c:219> Symbol #60 in mfgBIOS "epyc7002_synobios" {synobios_read_proc_platform_name}<0000000017c2919f>
[   87.407832] <redpill/bios_shim.c:219> Symbol #61 in mfgBIOS "epyc7002_synobios" {gSynoCPUMapping}<00000000a0ed4224>
[   87.419193] <redpill/bios_shim.c:219> Symbol #62 in mfgBIOS "epyc7002_synobios" {synobios_read_proc_cpu_arch.cold.17}<0000000026137bad>
[   87.432433] <redpill/bios_shim.c:219> Symbol #63 in mfgBIOS "epyc7002_synobios" {gSynoCRYPTOMapping}<00000000c432cdb1>
[   87.444074] <redpill/bios_shim.c:219> Symbol #64 in mfgBIOS "epyc7002_synobios" {synobios_read_proc_crypto_hw.cold.18}<00000000a7dad6ed>
[   87.457411] <redpill/bios_shim.c:219> Symbol #65 in mfgBIOS "epyc7002_synobios" {synobios_record_event_new.isra.4.part.5}<00000000d9dde97e>
[   87.471030] <redpill/bios_shim.c:219> Symbol #66 in mfgBIOS "epyc7002_synobios" {scSynoBios}<00000000f778ee90>
[   87.481911] <redpill/bios_shim.c:219> Symbol #67 in mfgBIOS "epyc7002_synobios" {synobios_error_btrfs_meta_corrupted_event}<0000000093beadfc>
[   87.495712] <redpill/bios_shim.c:219> Symbol #68 in mfgBIOS "epyc7002_synobios" {synobios_error_fs_btrfs_event}<000000004b9ad1de>
[   87.508384] <redpill/bios_shim.c:219> Symbol #69 in mfgBIOS "epyc7002_synobios" {synobios_error_fs_event}<00000000108e9686>
[   87.520490] <redpill/bios_shim.c:219> Symbol #70 in mfgBIOS "epyc7002_synobios" {synobios_autoremap_raid_event}<00000000fae7cae0>
[   87.533170] <redpill/bios_shim.c:219> Symbol #71 in mfgBIOS "epyc7002_synobios" {synobios_record_raid_event}<0000000096df3df4>
[   87.545565] <redpill/bios_shim.c:219> Symbol #72 in mfgBIOS "epyc7002_synobios" {synobios_event_ecc_notification}<00000000cba66f17>
[   87.558440] <redpill/bios_shim.c:219> Symbol #73 in mfgBIOS "epyc7002_synobios" {synobios_raid_sync_event}<00000000d94f68cd>
[   87.570653] <redpill/bios_shim.c:219> Symbol #74 in mfgBIOS "epyc7002_synobios" {synobios_error_oom_event}<00000000a5feab00>
[   87.582852] <redpill/bios_shim.c:219> Symbol #75 in mfgBIOS "epyc7002_synobios" {synobios_poll}<0000000065011eb8>
[   87.594023] <redpill/bios_shim.c:219> Symbol #76 in mfgBIOS "epyc7002_synobios" {synobios_ops}<0000000020864c5f>
[   87.605078] <redpill/bios_shim.c:219> Symbol #77 in mfgBIOS "epyc7002_synobios" {last_jiffies.40930}<000000000ff0e3b4>
[   87.616719] <redpill/bios_shim.c:219> Symbol #78 in mfgBIOS "epyc7002_synobios" {buzzer_press_count.40931}<000000000475dcdb>
[   87.628916] <redpill/bios_shim.c:219> Symbol #79 in mfgBIOS "epyc7002_synobios" {micropLogSwitch}<000000006c243b72>
[   87.640251] <redpill/bios_shim.c:219> Symbol #80 in mfgBIOS "epyc7002_synobios" {synobios_event_handler.cold.19}<000000002e59d142>
[   87.653025] <redpill/bios_shim.c:219> Symbol #81 in mfgBIOS "epyc7002_synobios" {synobios_rtc_init.cold.20}<0000000088d26061>
[   87.665327] <redpill/bios_shim.c:219> Symbol #82 in mfgBIOS "epyc7002_synobios" {card_detect_proc_ops}<00000000015668b8>
[   87.677153] <redpill/bios_shim.c:219> Symbol #83 in mfgBIOS "epyc7002_synobios" {add_card_detect_proc.cold.21}<00000000ba2d3603>
[   87.689739] <redpill/bios_shim.c:219> Symbol #84 in mfgBIOS "epyc7002_synobios" {synobios_ioctl}<0000000021ab7b5b>
[   87.701007] <redpill/bios_shim.c:219> Symbol #85 in mfgBIOS "epyc7002_synobios" {check_fan}<00000000bef6733e>
[   87.711785] <redpill/bios_shim.c:219> Symbol #86 in mfgBIOS "epyc7002_synobios" {sys_status_lock}<000000008d7e17ba>
[   87.723141] <redpill/bios_shim.c:219> Symbol #87 in mfgBIOS "epyc7002_synobios" {pgSysStatus}<0000000081a8d180>
[   87.734105] <redpill/bios_shim.c:219> Symbol #88 in mfgBIOS "epyc7002_synobios" {LedSetLock}<000000009573faaf>
[   87.744985] <redpill/bios_shim.c:219> Symbol #89 in mfgBIOS "epyc7002_synobios" {synobios_ioctl.cold.22}<000000001f8b96d0>
[   87.757002] <redpill/bios_shim.c:219> Symbol #90 in mfgBIOS "epyc7002_synobios" {__FUNCTION__.40986}<00000000e569aec3>
[   87.768633] <redpill/bios_shim.c:219> Symbol #91 in mfgBIOS "epyc7002_synobios" {__func__.41047}<000000009d460101>
[   87.779892] <redpill/bios_shim.c:219> Symbol #92 in mfgBIOS "epyc7002_synobios" {__key.41328}<000000000475dcdb>
[   87.790872] <redpill/bios_shim.c:219> Symbol #93 in mfgBIOS "epyc7002_synobios" {__key.41311}<000000000475dcdb>
[   87.801851] <redpill/bios_shim.c:219> Symbol #94 in mfgBIOS "epyc7002_synobios" {synobios_init.cold.23}<000000002492014b>
[   87.813763] <redpill/bios_shim.c:219> Symbol #95 in mfgBIOS "epyc7002_synobios" {synobios_read_proc_cpu_arch_ops}<000000009a085e7d>
[   87.826624] <redpill/bios_shim.c:219> Symbol #96 in mfgBIOS "epyc7002_synobios" {synobios_read_proc_crypto_hw_ops}<00000000fe46617f>
[   87.839581] <redpill/bios_shim.c:219> Symbol #97 in mfgBIOS "epyc7002_synobios" {synobios_read_proc_platform_ops}<0000000076dfa7b0>
[   87.852447] <redpill/bios_shim.c:219> Symbol #98 in mfgBIOS "epyc7002_synobios" {system_mode}<0000000089fdc0c5>
[   87.863426] <redpill/bios_shim.c:219> Symbol #99 in mfgBIOS "epyc7002_synobios" {gSynoModelMapping}<00000000e4dd1908>
[   87.874969] <redpill/bios_shim.c:219> Symbol #100 in mfgBIOS "epyc7002_synobios" {synobios_cleanup.cold.24}<00000000a974e764>
[   87.887260] <redpill/bios_shim.c:219> Symbol #101 in mfgBIOS "epyc7002_synobios" {__UNIQUE_ID_license291}<00000000baf5a1d0>
[   87.899371] <redpill/bios_shim.c:219> Symbol #102 in mfgBIOS "epyc7002_synobios" {__UNIQUE_ID_description290}<00000000c4e06740>
[   87.911848] <redpill/bios_shim.c:219> Symbol #103 in mfgBIOS "epyc7002_synobios" {__UNIQUE_ID_author289}<0000000086ca9534>
[   87.923866] <redpill/bios_shim.c:219> Symbol #104 in mfgBIOS "epyc7002_synobios" {__UNIQUE_ID_system_mode282}<0000000082af561e>
[   87.936341] <redpill/bios_shim.c:219> Symbol #105 in mfgBIOS "epyc7002_synobios" {__UNIQUE_ID_system_modetype281}<000000005cb103d4>
[   87.949220] <redpill/bios_shim.c:219> Symbol #106 in mfgBIOS "epyc7002_synobios" {__param_system_mode}<0000000076a692a7>
[   87.961030] <redpill/bios_shim.c:219> Symbol #107 in mfgBIOS "epyc7002_synobios" {__param_str_system_mode}<00000000b59b143a>
[   87.973238] <redpill/bios_shim.c:219> Symbol #108 in mfgBIOS "epyc7002_synobios" {__UNIQUE_ID_check_fan280}<00000000c0f8745a>
[   87.985520] <redpill/bios_shim.c:219> Symbol #109 in mfgBIOS "epyc7002_synobios" {__UNIQUE_ID_check_fantype279}<000000005fd235c2>
[   87.998194] <redpill/bios_shim.c:219> Symbol #110 in mfgBIOS "epyc7002_synobios" {__param_check_fan}<000000000f077b72>
[   88.009824] <redpill/bios_shim.c:219> Symbol #111 in mfgBIOS "epyc7002_synobios" {__param_str_check_fan}<00000000a6a54b18>
[   88.021830] <redpill/bios_shim.c:219> Symbol #112 in mfgBIOS "epyc7002_synobios" {.LC37}<0000000059e21005>
[   88.032339] <redpill/bios_shim.c:219> Symbol #113 in mfgBIOS "epyc7002_synobios" {MpId.29958}<00000000da21c4c4>
[   88.043325] <redpill/bios_shim.c:219> Symbol #114 in mfgBIOS "epyc7002_synobios" {SetMicropId.cold.0}<000000009fa094cf>
[   88.055053] <redpill/bios_shim.c:219> Symbol #115 in mfgBIOS "epyc7002_synobios" {CheckMicropId.cold.1}<0000000015975f13>
[   88.066959] <redpill/bios_shim.c:219> Symbol #116 in mfgBIOS "epyc7002_synobios" {.LC0}<00000000f9ca3347>
[   88.077372] <redpill/bios_shim.c:219> Symbol #117 in mfgBIOS "epyc7002_synobios" {days_since_epoch}<00000000f29c1f93>
[   88.088903] <redpill/bios_shim.c:219> Symbol #118 in mfgBIOS "epyc7002_synobios" {days_since_leapyear}<000000000f8844b4>
[   88.100730] <redpill/bios_shim.c:219> Symbol #119 in mfgBIOS "epyc7002_synobios" {days_since_year}<000000009bead0f9>
[   88.112185] <redpill/bios_shim.c:219> Symbol #120 in mfgBIOS "epyc7002_synobios" {rtc_seiko_set_auto_poweron.cold.0}<00000000e389ef70>
[   88.125338] <redpill/bios_shim.c:219> Symbol #121 in mfgBIOS "epyc7002_synobios" {rtc_set_interrupt}<00000000ad030e43>
[   88.136980] <redpill/bios_shim.c:219> Symbol #122 in mfgBIOS "epyc7002_synobios" {i2c_bus_no}<0000000022031bf4>
[   88.147964] <redpill/bios_shim.c:219> Symbol #123 in mfgBIOS "epyc7002_synobios" {linuxI2CCharWrite.cold.1}<00000000b0739438>
[   88.160261] <redpill/bios_shim.c:219> Symbol #124 in mfgBIOS "epyc7002_synobios" {linuxI2CCharRead.cold.2}<00000000221e23fd>
[   88.172469] <redpill/bios_shim.c:219> Symbol #125 in mfgBIOS "epyc7002_synobios" {uLostAddr.31344}<00000000ede58064>
[   88.183924] <redpill/bios_shim.c:219> Symbol #126 in mfgBIOS "epyc7002_synobios" {linuxI2CSmbusRegRead.cold.3}<000000008df8af67>
[   88.196501] <redpill/bios_shim.c:219> Symbol #127 in mfgBIOS "epyc7002_synobios" {__FUNCTION__.31345}<0000000071846cfe>
[   88.208234] <redpill/bios_shim.c:219> Symbol #128 in mfgBIOS "epyc7002_synobios" {SetDiskLedStatusByLedTrigger.cold.0}<000000004fd987f1>
[   88.221557] <redpill/bios_shim.c:219> Symbol #129 in mfgBIOS "epyc7002_synobios" {SetHddActLedByLedTrigger.cold.1}<000000008e6ee217>
[   88.234495] <redpill/bios_shim.c:219> Symbol #130 in mfgBIOS "epyc7002_synobios" {SetupDiskLedMap.cold.2}<00000000d60af776>
[   88.246595] <redpill/bios_shim.c:219> Symbol #131 in mfgBIOS "epyc7002_synobios" {uLostAddr.45750}<00000000c39d4c53>
[   88.258026] <redpill/bios_shim.c:219> Symbol #132 in mfgBIOS "epyc7002_synobios" {HWMONReadPmbusStatusReg.cold.0}<0000000011d74577>
[   88.270910] <redpill/bios_shim.c:219> Symbol #133 in mfgBIOS "epyc7002_synobios" {uLostAddr.45759}<0000000031d259e0>
[   88.282365] <redpill/bios_shim.c:219> Symbol #134 in mfgBIOS "epyc7002_synobios" {I2CPmbusReadPowerStatus.cold.1}<00000000d35c02ab>
[   88.295229] <redpill/bios_shim.c:219> Symbol #135 in mfgBIOS "epyc7002_synobios" {__FUNCTION__.45765}<00000000a05b5bdc>
[   88.306953] <redpill/bios_shim.c:219> Symbol #136 in mfgBIOS "epyc7002_synobios" {HWMONGetPSUStatusByI2C.cold.2}<00000000548c3b7b>
[   88.319729] <redpill/bios_shim.c:219> Symbol #137 in mfgBIOS "epyc7002_synobios" {InitModuleType}<0000000041c427f2>
[   88.331076] <redpill/bios_shim.c:219> Symbol #138 in mfgBIOS "epyc7002_synobios" {model_ops}<00000000d326d57a>
[   88.341956] <redpill/bios_shim.c:219> Symbol #139 in mfgBIOS "epyc7002_synobios" {GetBuzzerCleared}<00000000556a4b9b>
[   88.353498] <redpill/bios_shim.c:219> Symbol #140 in mfgBIOS "epyc7002_synobios" {GetPowerStatus}<00000000c0a248f4>
[   88.364855] <redpill/bios_shim.c:219> Symbol #141 in mfgBIOS "epyc7002_synobios" {Uninitialize}<000000001cd18d2a>
[   88.376020] <redpill/bios_shim.c:219> Symbol #142 in mfgBIOS "epyc7002_synobios" {synobios_ops}<000000003d08a40c>
[   88.387185] <redpill/bios_shim.c:223> Found vtable - size 424
[   88.393442] <redpill/bios_shim.c:237> Found "synobios_ops" in "epyc7002_synobios" @ <000000003d08a40c =424=> 000000009837932d>
[   88.405837] <redpill/override_symbol.c:278> Restoring apply_relocate_add<000000005fd11e6b> to original code
[   88.416445] <redpill/memory_helper.c:17> Disabling memory protection for page(s) at 000000005fd11e6b+12/1 (<<00000000ebf98114)
[   88.428918] <redpill/override_symbol.c:249> Obtaining lock for <000000005fd11e6b/000000005fd11e6b>
[   88.438669] <redpill/override_symbol.c:249> Writing original code to <000000005fd11e6b>
[   88.447380] <redpill/override_symbol.c:249> Released lock for <000000005fd11e6b>
[   88.455435] <redpill/memory_helper.c:33> Enabling memory protection for page(s) at 000000005fd11e6b+12/1 (<<00000000ebf98114)
[   88.467777] <redpill/override_symbol.c:286> Successfully restored original code of apply_relocate_add
[   88.477815] <redpill/override_symbol.c:145> Freeing OVS for apply_relocate_add
[   88.486246] <redpill/bios_shims_collection.c:104> Will print 424 bytes of memory from 000000003d08a40c
[   88.496388] 40 
[   88.496389] 97 
[   88.498308] 4a 
[   88.500225] a0 
[   88.502139] ff 
[   88.504049] ff 
[   88.505966] ff 
[   88.507882] ff 
[   88.509809]  [00] 0x000      00000000f094de10        __this_module+0x0/0xffffffffffff58c0 [epyc7002_synobios]
[   88.521464] 00 
[   88.521465] 76 
[   88.523383] 49 
[   88.525304] a0 
[   88.527217] ff 
[   88.529123] ff 
[   88.531035] ff 
[   88.532951] ff 
[   88.534870]  [01] 0x008      00000000b851adcb        GetBrand+0x0/0x10 [epyc7002_synobios]
[   88.544744] f0 
[   88.544745] d6 
[   88.546662] 49 
[   88.548580] a0 
[   88.550495] ff 
[   88.552407] ff 
[   88.554319] ff 
[   88.556234] ff 
[   88.558153]  [02] 0x010      0000000044981e82        GetModel+0x0/0xa0 [epyc7002_synobios]
[   88.568027] 00 
[   88.568028] 00 
[   88.569941] 00 
[   88.571845] 00 
[   88.573763] 00 
[   88.575674] 00 
[   88.577591] 00 
[   88.579502] 00 
[   88.581422]  [03] 0x018      0000000000000000        0x0
[   88.588093] 50 
[   88.588093] c1 
[   88.590009] 49 
[   88.591921] a0 
[   88.593838] ff 
[   88.595749] ff 
[   88.597663] ff 
[   88.599577] ff 
[   88.601491]  [04] 0x020      00000000a7efa86c        rtc_seiko_get_time+0x0/0x1a0 [epyc7002_synobios]
[   88.612402] f0 
[   88.612402] c2 
[   88.614315] 49 
[   88.616233] a0 
[   88.618145] ff 
[   88.620056] ff 
[   88.621973] ff 
[   88.623886] ff 
[   88.625805]  [05] 0x028      000000001940e761        rtc_seiko_set_time+0x0/0x1d0 [epyc7002_synobios]
[   88.636719] a0 
[   88.636720] 71 
[   88.638641] 49 
[   88.640553] a0 
[   88.642468] ff 
[   88.644380] ff 
[   88.646297] ff 
[   88.648209] ff 
[   88.650130]  [06] 0x030      00000000741ad99c        GetFanStatusActivePulse+0x0/0xd0 [epyc7002_synobios]
[   88.661428] d0 
[   88.661428] d4 
[   88.663339] 49 
[   88.665255] a0 
[   88.667168] ff 
[   88.669083] ff 
[   88.670996] ff 
[   88.672912] ff 
[   88.674829]  [07] 0x038      00000000afffda15        SetFanStatusMircopWithGPIO+0x0/0xc0 [epyc7002_synobios]
[   88.686409] 00 
[   88.686410] 00 
[   88.688326] 00 
[   88.690236] 00 
[   88.692155] 00 
[   88.694077] 00 
[   88.695988] 00 
[   88.697905] 00 
[   88.699817]  [08] 0x040      0000000000000000        0x0
[   88.706477] d0 
[   88.706477] d6 
[   88.708377] 49 
[   88.710298] a0 
[   88.712209] ff 
[   88.714127] ff 
[   88.716040] ff 
[   88.717955] ff 
[   88.719872]  [09] 0x048      00000000f0649a4a        GetCpuTemperature+0x0/0x20 [epyc7002_synobios]
[   88.730590] 00 
[   88.730590] 00 
[   88.732501] 00 
[   88.734416] 00 
[   88.736330] 00 
[   88.738247] 00 
[   88.740157] 00 
[   88.742073] 00 
[   88.743989]  [10] 0x050      0000000000000000        0x0
[   88.750646] 00 
[   88.750647] 00 
[   88.752563] 00 
[   88.754475] 00 
[   88.756387] 00 
[   88.758304] 00 
[   88.760219] 00 
[   88.762131] 00 
[   88.764045]  [11] 0x058      0000000000000000        0x0
[   88.770704] 00 
[   88.770704] 00 
[   88.772619] 00 
[   88.774532] 00 
[   88.776449] 00 
[   88.778361] 00 
[   88.780277] 00 
[   88.782189] 00 
[   88.784106]  [12] 0x060      0000000000000000        0x0
[   88.790766] 00 
[   88.790766] 00 
[   88.792688] 00 
[   88.794599] 00 
[   88.796514] 00 
[   88.798427] 00 
[   88.800342] 00 
[   88.802256] 00 
[   88.804163]  [13] 0x068      0000000000000000        0x0
[   88.810831] 00 
[   88.810831] 00 
[   88.812749] 00 
[   88.814666] 00 
[   88.816569] 00 
[   88.818484] 00 
[   88.820396] 00 
[   88.822311] 00 
[   88.824224]  [14] 0x070      0000000000000000        0x0
[   88.830884] b0 
[   88.830885] 75 
[   88.832801] 49 
[   88.834713] a0 
[   88.836628] ff 
[   88.838541] ff 
[   88.840456] ff 
[   88.842369] ff 
[   88.844286]  [15] 0x078      000000006ff7ffd4        SetGpioPin+0x0/0x20 [epyc7002_synobios]
[   88.854352] d0 
[   88.854352] 75 
[   88.856269] 49 
[   88.858186] a0 
[   88.860101] ff 
[   88.862012] ff 
[   88.863925] ff 
[   88.865842] ff 
[   88.867758]  [16] 0x080      000000007d2226aa        GetGpioPin+0x0/0x30 [epyc7002_synobios]
[   88.877829] 00 
[   88.877830] 00 
[   88.879746] 00 
[   88.881657] 00 
[   88.883575] 00 
[   88.885486] 00 
[   88.887401] 00 
[   88.889315] 00 
[   88.891231]  [17] 0x088      0000000000000000        0x0
[   88.897890] e0 
[   88.897891] bd 
[   88.899803] 49 
[   88.901715] a0 
[   88.903631] ff 
[   88.905542] ff 
[   88.907460] ff 
[   88.909370] ff 
[   88.911292]  [18] 0x090      00000000dff3e2ce        rtc_seiko_set_auto_poweron+0x0/0x90 [epyc7002_synobios]
[   88.922872] 30 
[   88.922872] bd 
[   88.924784] 49 
[   88.926700] a0 
[   88.928613] ff 
[   88.930531] ff 
[   88.932452] ff 
[   88.934363] ff 
[   88.936285]  [19] 0x098      0000000036c12a89        rtc_get_auto_poweron+0x0/0x50 [epyc7002_synobios]
[   88.947282] 40 
[   88.947283] c5 
[   88.949197] 49 
[   88.951119] a0 
[   88.953031] ff 
[   88.954934] ff 
[   88.956855] ff 
[   88.958783] ff 
[   88.960698]  [20] 0x0a0      00000000ad91c22b        rtc_seiko_auto_poweron_init+0x0/0x20 [epyc7002_synobios]
[   88.972369] 70 
[   88.972370] be 
[   88.974288] 49 
[   88.976205] a0 
[   88.978119] ff 
[   88.980032] ff 
[   88.981945] ff 
[   88.983860] ff 
[   88.985776]  [21] 0x0a8      00000000f64cbe08        rtc_seiko_auto_poweron_uninit+0x0/0x20 [epyc7002_synobios]
[   88.997646] 60 
[   88.997647] d4 
[   88.999568] 49 
[   89.001469] a0 
[   89.003386] ff 
[   89.005301] ff 
[   89.007213] ff 
[   89.009119] ff 
[   89.011039]  [22] 0x0b0      000000007b40b78b        SetAlarmLed+0x0/0x20 [epyc7002_synobios]
[   89.021196] 10 
[   89.021196] d3 
[   89.023110] 49 
[   89.025023] a0 
[   89.026935] ff 
[   89.028851] ff 
[   89.030764] ff 
[   89.032681] ff 
[   89.034594]  [23] 0x0b8      00000000556a4b9b        GetBuzzerCleared+0x0/0x30 [epyc7002_synobios]
[   89.045224] 00 
[   89.045225] 00 
[   89.047132] 00 
[   89.049044] 00 
[   89.050950] 00 
[   89.052867] 00 
[   89.054778] 00 
[   89.056694] 00 
[   89.058608]  [24] 0x0c0      0000000000000000        0x0
[   89.065270] 40 
[   89.065270] d3 
[   89.067189] 49 
[   89.069105] a0 
[   89.071017] ff 
[   89.072934] ff 
[   89.074846] ff 
[   89.076762] ff 
[   89.078686]  [25] 0x0c8      00000000c0a248f4        GetPowerStatus+0x0/0x30 [epyc7002_synobios]
[   89.089101] 00 
[   89.089101] 00 
[   89.091018] 00 
[   89.092923] 00 
[   89.094834] 00 
[   89.096740] 00 
[   89.098654] 00 
[   89.100569] 00 
[   89.102482]  [26] 0x0d0      0000000000000000        0x0
[   89.109142] e0 
[   89.109143] d2 
[   89.111057] 49 
[   89.112970] a0 
[   89.114887] ff 
[   89.116799] ff 
[   89.118716] ff 
[   89.120638] ff 
[   89.122547]  [27] 0x0d8      0000000041c427f2        InitModuleType+0x0/0x30 [epyc7002_synobios]
[   89.132989] 70 
[   89.132989] d3 
[   89.134902] 49 
[   89.136809] a0 
[   89.138732] ff 
[   89.140654] ff 
[   89.142564] ff 
[   89.144464] ff 
[   89.146380]  [28] 0x0e0      000000001cd18d2a        Uninitialize+0x0/0x40 [epyc7002_synobios]
[   89.156643] 00 
[   89.156643] 00 
[   89.158555] 00 
[   89.160471] 00 
[   89.162383] 00 
[   89.164294] 00 
[   89.166208] 00 
[   89.168125] 00 
[   89.170036]  [29] 0x0e8      0000000000000000        0x0
[   89.176698] 00 
[   89.176699] 00 
[   89.178612] 00 
[   89.180524] 00 
[   89.182432] 00 
[   89.184343] 00 
[   89.186260] 00 
[   89.188175] 00 
[   89.190097]  [30] 0x0f0      0000000000000000        0x0
[   89.196757] 00 
[   89.196758] 00 
[   89.198679] 00 
[   89.200590] 00 
[   89.202508] 00 
[   89.204428] 00 
[   89.206342] 00 
[   89.208253] 00 
[   89.210171]  [31] 0x0f8      0000000000000000        0x0
[   89.216819] 00 
[   89.216819] 00 
[   89.218736] 00 
[   89.220647] 00 
[   89.222566] 00 
[   89.224487] 00 
[   89.226398] 00 
[   89.228314] 00 
[   89.230227]  [32] 0x100      0000000000000000        0x0
[   89.236888] 00 
[   89.236888] 00 
[   89.238803] 00 
[   89.240716] 00 
[   89.242631] 00 
[   89.244544] 00 
[   89.246459] 00 
[   89.248372] 00 
[   89.250284]  [33] 0x108      0000000000000000        0x0
[   89.256943] 00 
[   89.256944] 00 
[   89.258856] 00 
[   89.260770] 00 
[   89.262687] 00 
[   89.264601] 00 
[   89.266511] 00 
[   89.268430] 00 
[   89.270341]  [34] 0x110      0000000000000000        0x0
[   89.277009] 00 
[   89.277010] 00 
[   89.278922] 00 
[   89.280841] 00 
[   89.282761] 00 
[   89.284673] 00 
[   89.286590] 00 
[   89.288500] 00 
[   89.290414]  [35] 0x118      0000000000000000        0x0
[   89.297077] 00 
[   89.297078] 00 
[   89.298990] 00 
[   89.300905] 00 
[   89.302819] 00 
[   89.304729] 00 
[   89.306646] 00 
[   89.308557] 00 
[   89.310471]  [36] 0x120      0000000000000000        0x0
[   89.317134] 00 
[   89.317134] 00 
[   89.319046] 00 
[   89.320962] 00 
[   89.322875] 00 
[   89.324791] 00 
[   89.326709] 00 
[   89.328625] 00 
[   89.330537]  [37] 0x128      0000000000000000        0x0
[   89.337196] 00 
[   89.337197] 00 
[   89.339114] 00 
[   89.341025] 00 
[   89.342938] 00 
[   89.344854] 00 
[   89.346766] 00 
[   89.348679] 00 
[   89.350596]  [38] 0x130      0000000000000000        0x0
[   89.357244] 00 
[   89.357244] 00 
[   89.359161] 00 
[   89.361073] 00 
[   89.362990] 00 
[   89.364901] 00 
[   89.366816] 00 
[   89.368730] 00 
[   89.370641]  [39] 0x138      0000000000000000        0x0
[   89.377301] b0 
[   89.377302] d3 
[   89.379217] 49 
[   89.381129] a0 
[   89.383041] ff 
[   89.384956] ff 
[   89.386873] ff 
[   89.388787] ff 
[   89.390712]  [40] 0x140      00000000e41893b7        GetCPUInfo+0x0/0x70 [epyc7002_synobios]
[   89.400773] 00 
[   89.400774] 00 
[   89.402679] 00 
[   89.404594] 00 
[   89.406508] 00 
[   89.408420] 00 
[   89.410332] 00 
[   89.412246] 00 
[   89.414165]  [41] 0x148      0000000000000000        0x0
[   89.420831] 00 
[   89.420831] 00 
[   89.422741] 00 
[   89.424659] 00 
[   89.426563] 00 
[   89.428476] 00 
[   89.430392] 00 
[   89.432303] 00 
[   89.434218]  [42] 0x150      0000000000000000        0x0
[   89.440876] 00 
[   89.440877] 00 
[   89.442793] 00 
[   89.444706] 00 
[   89.446621] 00 
[   89.448523] 00 
[   89.450438] 00 
[   89.452352] 00 
[   89.454268]  [43] 0x158      0000000000000000        0x0
[   89.460919] 00 
[   89.460919] 00 
[   89.462830] 00 
[   89.464734] 00 
[   89.466651] 00 
[   89.468565] 00 
[   89.470476] 00 
[   89.472394] 00 
[   89.474306]  [44] 0x160      0000000000000000        0x0
[   89.480965] 00 
[   89.480965] 00 
[   89.482880] 00 
[   89.484794] 00 
[   89.486705] 00 
[   89.488611] 00 
[   89.490527] 00 
[   89.492440] 00 
[   89.494356]  [45] 0x168      0000000000000000        0x0
[   89.500996] 00 
[   89.500996] 00 
[   89.502912] 00 
[   89.504824] 00 
[   89.506730] 00 
[   89.508642] 00 
[   89.510557] 00 
[   89.512471] 00 
[   89.514383]  [46] 0x170      0000000000000000        0x0
[   89.521041] 00 
[   89.521041] 00 
[   89.522959] 00 
[   89.524871] 00 
[   89.526787] 00 
[   89.528699] 00 
[   89.530604] 00 
[   89.532517] 00 
[   89.534433]  [47] 0x178      0000000000000000        0x0
[   89.541100] 00 
[   89.541101] 00 
[   89.543015] 00 
[   89.544917] 00 
[   89.546833] 00 
[   89.548746] 00 
[   89.550662] 00 
[   89.552573] 00 
[   89.554490]  [48] 0x180      0000000000000000        0x0
[   89.561156] 00 
[   89.561156] 00 
[   89.563072] 00 
[   89.564990] 00 
[   89.566904] 00 
[   89.568817] 00 
[   89.570724] 00 
[   89.572641] 00 
[   89.574553]  [49] 0x188      0000000000000000        0x0
[   89.581203] 00 
[   89.581204] 00 
[   89.583120] 00 
[   89.585031] 00 
[   89.586948] 00 
[   89.588870] 00 
[   89.590780] 00 
[   89.592693] 00 
[   89.594610]  [50] 0x190      0000000000000000        0x0
[   89.601270] 00 
[   89.601270] 00 
[   89.603181] 00 
[   89.605096] 00 
[   89.607003] 00 
[   89.608917] 00 
[   89.610828] 00 
[   89.612733] 00 
[   89.614646]  [51] 0x198      0000000000000000        0x0
[   89.621300] 00 
[   89.621300] 00 
[   89.623212] 00 
[   89.625125] 00 
[   89.627030] 00 
[   89.628948] 00 
[   89.630870] 00 
[   89.632782] 00 
[   89.634687]  [52] 0x1a0      0000000000000000        0x0
[   89.641348] 
[   89.642980] <redpill/bios_shims_collection.c:117> Finished printing memory at 0000000077985bb3
[   89.652363] <redpill/bios_shims_collection.c:86> mfgBIOS vtable [7] originally SetFanStatusMircopWithGPIO [epyc7002_synobios]<00000000afffda15> will now be bios_VTK_SET_FAN_STATE_null_zero_int [redpill]<00000000c07ac642>
[   89.673634] <redpill/bios_shims_collection.c:86> mfgBIOS vtable [10] originally 0x0<0000000000000000> will now be bios_VTK_SET_DISK_LED_null_zero_int [redpill]<0000000017eb00ed>
[   89.690851] <redpill/bios_shims_collection.c:86> mfgBIOS vtable [11] originally 0x0<0000000000000000> will now be bios_VTK_SET_PWR_LED_null_zero_int [redpill]<00000000ef3022d1>
[   89.707988] <redpill/bios_shims_collection.c:86> mfgBIOS vtable [16] originally GetGpioPin [epyc7002_synobios]<000000007d2226aa> will now be shim_get_gpio_pin_usable [redpill]<0000000081b034fa>
[   89.726701] <redpill/bios_shims_collection.c:86> mfgBIOS vtable [15] originally SetGpioPin [epyc7002_synobios]<000000006ff7ffd4> will now be shim_set_gpio_pin_usable [redpill]<00000000f952a3a0>
[   89.745422] <redpill/bios_shims_collection.c:86> mfgBIOS vtable [17] originally 0x0<0000000000000000> will now be bios_VTK_SET_GPIO_PIN_BLINK_null_zero_int [redpill]<000000004d032948>
[   89.763216] <redpill/bios_shims_collection.c:86> mfgBIOS vtable [22] originally SetAlarmLed [epyc7002_synobios]<000000007b40b78b> will now be bios_VTK_SET_ALR_LED_null_zero_int [redpill]<0000000060df12f9>
[   89.782998] <redpill/bios_shims_collection.c:86> mfgBIOS vtable [23] originally GetBuzzerCleared [epyc7002_synobios]<00000000556a4b9b> will now be bios_get_buz_clr [redpill]<00000000957312bc>
[   89.801526] <redpill/bios_shims_collection.c:86> mfgBIOS vtable [24] originally 0x0<0000000000000000> will now be bios_VTK_SET_BUZ_CLR_null_zero_int [redpill]<00000000dd850310>
[   89.818656] <redpill/bios_shims_collection.c:86> mfgBIOS vtable [25] originally GetPowerStatus [epyc7002_synobios]<00000000c0a248f4> will now be bios_get_power_status [redpill]<00000000b16a5213>
[   89.837487] <redpill/bios_shims_collection.c:86> mfgBIOS vtable [29] originally 0x0<0000000000000000> will now be bios_VTK_SET_CPU_FAN_STATUS_null_zero_int [redpill]<000000000e96a5fd>
[   89.855281] <redpill/bios_shims_collection.c:86> mfgBIOS vtable [30] originally 0x0<0000000000000000> will now be bios_VTK_SET_PHY_LED_null_zero_int [redpill]<0000000032d7d8e4>
[   89.872382] <redpill/bios_shims_collection.c:86> mfgBIOS vtable [31] originally 0x0<0000000000000000> will now be bios_VTK_SET_HDD_ACT_LED_null_zero_int [redpill]<000000001b648c9c>
[   89.889892] <redpill/bios_shims_collection.c:86> mfgBIOS vtable [33] originally 0x0<0000000000000000> will now be bios_VTK_GET_MICROP_ID_null_zero_int [redpill]<00000000c5189650>
[   89.907210] <redpill/bios_shims_collection.c:86> mfgBIOS vtable [34] originally 0x0<0000000000000000> will now be bios_VTK_SET_MICROP_ID_null_zero_int [redpill]<0000000019375d9f>
[   89.924527] <redpill/bios_shims_collection.c:155> Platform requires RTC proxy - enabling
[   89.933332] <redpill/rtc_proxy.c:260> Registering RTC proxy shim
[   89.939871] <redpill/rtc_proxy.c:268> Successfully registered RTC proxy shim
[   89.947553] <redpill/bios_shims_collection.c:86> mfgBIOS vtable [4] originally rtc_seiko_get_time [epyc7002_synobios]<00000000a7efa86c> will now be rtc_proxy_get_time [redpill]<000000004704f422>
[   89.966376] <redpill/bios_shims_collection.c:86> mfgBIOS vtable [5] originally rtc_seiko_set_time [epyc7002_synobios]<000000001940e761> will now be rtc_proxy_set_time [redpill]<00000000c5a7599f>
[   89.985197] <redpill/bios_shims_collection.c:86> mfgBIOS vtable [20] originally rtc_seiko_auto_poweron_init [epyc7002_synobios]<00000000ad91c22b> will now be rtc_proxy_init_auto_power_on [redpill]<00000000650350ca>
[   90.005907] <redpill/bios_shims_collection.c:86> mfgBIOS vtable [19] originally rtc_get_auto_poweron [epyc7002_synobios]<0000000036c12a89> will now be rtc_proxy_get_auto_power_on [redpill]<000000002e35ba90>
[   90.025871] <redpill/bios_shims_collection.c:86> mfgBIOS vtable [18] originally rtc_seiko_set_auto_poweron [epyc7002_synobios]<00000000dff3e2ce> will now be rtc_proxy_set_auto_power_on [redpill]<000000006c3f2fef>
[   90.046397] <redpill/bios_shims_collection.c:86> mfgBIOS vtable [21] originally rtc_seiko_auto_poweron_uninit [epyc7002_synobios]<00000000f64cbe08> will now be rtc_proxy_uinit_auto_power_on [redpill]<00000000103448b2>
[   90.067360] <redpill/bios_hwmon_shim.c:332> Registering mfgBIOS HW Monitor shim
[   90.075327] <redpill/bios_shims_collection.c:86> mfgBIOS vtable [6] originally GetFanStatusActivePulse [epyc7002_synobios]<00000000741ad99c> will now be bios_get_fan_state [redpill]<000000006a8faed4>
[   90.094626] <redpill/bios_shims_collection.c:86> mfgBIOS vtable [9] originally GetCpuTemperature [epyc7002_synobios]<00000000f0649a4a> will now be bios_get_cpu_temp [redpill]<00000000ebf6df74>
[   90.113256] <redpill/bios_shims_collection.c:86> mfgBIOS vtable [47] originally 0x0<0000000000000000> will now be bios_hwmon_get_thermal [redpill]<00000000b112f6a9>
[   90.129243] <redpill/bios_shims_collection.c:86> mfgBIOS vtable [45] originally 0x0<0000000000000000> will now be bios_hwmon_get_voltages [redpill]<00000000103e34b5>
[   90.145326] <redpill/bios_shims_collection.c:86> mfgBIOS vtable [43] originally 0x0<0000000000000000> will now be bios_hwmon_get_fans_rpm [redpill]<000000002f3cd437>
[   90.161400] <redpill/bios_shims_collection.c:86> mfgBIOS vtable [46] originally 0x0<0000000000000000> will now be bios_hwmon_get_hdd_backplane [redpill]<00000000bfc9cb4e>
[   90.177960] <redpill/bios_hwmon_shim.c:358> Successfully registered mfgBIOS HW Monitor shim
[   90.187052] <redpill/bios_shims_collection.c:104> Will print 424 bytes of memory from 000000003d08a40c
[   90.197175] 40 
[   90.197175] 97 
[   90.199091] 4a 
[   90.201007] a0 
[   90.202917] ff 
[   90.204830] ff 
[   90.206747] ff 
[   90.208659] ff 
[   90.210581]  [00] 0x000      00000000f094de10        __this_module+0x0/0xffffffffffff58c0 [epyc7002_synobios]
[   90.222245] 00 
[   90.222245] 76 
[   90.224161] 49 
[   90.226075] a0 
[   90.227989] ff 
[   90.229892] ff 
[   90.231808] ff 
[   90.233713] ff 
[   90.235631]  [01] 0x008      00000000b851adcb        GetBrand+0x0/0x10 [epyc7002_synobios]
[   90.245517] f0 
[   90.245517] d6 
[   90.247422] 49 
[   90.249335] a0 
[   90.251247] ff 
[   90.253163] ff 
[   90.255074] ff 
[   90.256992] ff 
[   90.258911]  [02] 0x010      0000000044981e82        GetModel+0x0/0xa0 [epyc7002_synobios]
[   90.268772] 00 
[   90.268773] 00 
[   90.270691] 00 
[   90.272612] 00 
[   90.274518] 00 
[   90.276430] 00 
[   90.278347] 00 
[   90.280268] 00 
[   90.282180]  [03] 0x018      0000000000000000        0x0
[   90.288841] 6c 
[   90.288841] e7 
[   90.290757] 00 
[   90.292670] a0 
[   90.294581] ff 
[   90.296497] ff 
[   90.298412] ff 
[   90.300324] ff 
[   90.302247]  [04] 0x020      000000004704f422        rtc_proxy_get_time+0x0/0xd0 [redpill]
[   90.312128] 3c 
[   90.312128] e8 
[   90.314038] 00 
[   90.315951] a0 
[   90.317867] ff 
[   90.319781] ff 
[   90.321697] ff 
[   90.323617] ff 
[   90.325536]  [05] 0x028      00000000c5a7599f        rtc_proxy_set_time+0x0/0x215 [redpill]
[   90.335514] 00 
[   90.335514] 48 
[   90.337424] 00 
[   90.339340] a0 
[   90.341255] ff 
[   90.343165] ff 
[   90.345081] ff 
[   90.346996] ff 
[   90.348915]  [06] 0x030      000000006a8faed4        bios_get_fan_state+0x0/0x10 [redpill]
[   90.358790] 0f 
[   90.358790] ed 
[   90.360701] 00 
[   90.362619] a0 
[   90.364539] ff 
[   90.366452] ff 
[   90.368369] ff 
[   90.370280] ff 
[   90.372202]  [07] 0x038      00000000c07ac642        bios_VTK_SET_FAN_STATE_null_zero_int+0x0/0x27 [redpill]
[   90.383782] 00 
[   90.383782] 00 
[   90.385698] 00 
[   90.387599] 00 
[   90.389513] 00 
[   90.391428] 00 
[   90.393345] 00 
[   90.395258] 00 
[   90.397175]  [08] 0x040      0000000000000000        0x0
[   90.403838] f0 
[   90.403839] 48 
[   90.405752] 00 
[   90.407669] a0 
[   90.409584] ff 
[   90.411495] ff 
[   90.413409] ff 
[   90.415326] ff 
[   90.417245]  [09] 0x048      00000000ebf6df74        bios_get_cpu_temp+0x0/0x40 [redpill]
[   90.427014] 36 
[   90.427014] ed 
[   90.428925] 00 
[   90.430843] a0 
[   90.432754] ff 
[   90.434659] ff 
[   90.436575] ff 
[   90.438489] ff 
[   90.440409]  [10] 0x050      0000000017eb00ed        bios_VTK_SET_DISK_LED_null_zero_int+0x0/0x27 [redpill]
[   90.451893] 5d 
[   90.451893] ed 
[   90.453810] 00 
[   90.455722] a0 
[   90.457639] ff 
[   90.459550] ff 
[   90.461462] ff 
[   90.463380] ff 
[   90.465298]  [11] 0x058      00000000ef3022d1        bios_VTK_SET_PWR_LED_null_zero_int+0x0/0x27 [redpill]
[   90.476673] 00 
[   90.476674] 00 
[   90.478589] 00 
[   90.480502] 00 
[   90.482413] 00 
[   90.484327] 00 
[   90.486242] 00 
[   90.488155] 00 
[   90.490072]  [12] 0x060      0000000000000000        0x0
[   90.496730] 00 
[   90.496731] 00 
[   90.498643] 00 
[   90.500560] 00 
[   90.502455] 00 
[   90.504373] 00 
[   90.506293] 00 
[   90.508199] 00 
[   90.510113]  [13] 0x068      0000000000000000        0x0
[   90.516776] 00 
[   90.516776] 00 
[   90.518695] 00 
[   90.520612] 00 
[   90.522527] 00 
[   90.524445] 00 
[   90.526362] 00 
[   90.528274] 00 
[   90.530180]  [14] 0x070      0000000000000000        0x0
[   90.536839] bc 
[   90.536840] ee 
[   90.538756] 00 
[   90.540666] a0 
[   90.542585] ff 
[   90.544497] ff 
[   90.546412] ff 
[   90.548323] ff 
[   90.550226]  [15] 0x078      00000000f952a3a0        shim_set_gpio_pin_usable+0x0/0x98 [redpill]
[   90.560675] a0 
[   90.560675] 4c 
[   90.562591] 00 
[   90.564504] a0 
[   90.566420] ff 
[   90.568341] ff 
[   90.570255] ff 
[   90.572171] ff 
[   90.574098]  [16] 0x080      0000000081b034fa        shim_get_gpio_pin_usable+0x0/0x10 [redpill]
[   90.584535] 84 
[   90.584535] ed 
[   90.586450] 00 
[   90.588368] a0 
[   90.590288] ff 
[   90.592201] ff 
[   90.594114] ff 
[   90.596030] ff 
[   90.597952]  [17] 0x088      000000004d032948        bios_VTK_SET_GPIO_PIN_BLINK_null_zero_int+0x0/0x27 [redpill]
[   90.610002] fa 
[   90.610003] ea 
[   90.611920] 00 
[   90.613833] a0 
[   90.615745] ff 
[   90.617658] ff 
[   90.619576] ff 
[   90.621487] ff 
[   90.623409]  [18] 0x090      000000006c3f2fef        rtc_proxy_set_auto_power_on+0x0/0x74 [redpill]
[   90.634142] 7f 
[   90.634142] ea 
[   90.636049] 00 
[   90.637969] a0 
[   90.639882] ff 
[   90.641799] ff 
[   90.643710] ff 
[   90.645627] ff 
[   90.647543]  [19] 0x098      000000002e35ba90        rtc_proxy_get_auto_power_on+0x0/0x7b [redpill]
[   90.658276] 51 
[   90.658277] ea 
[   90.660191] 00 
[   90.662108] a0 
[   90.664021] ff 
[   90.665933] ff 
[   90.667848] ff 
[   90.669760] ff 
[   90.671678]  [20] 0x0a0      00000000650350ca        rtc_proxy_init_auto_power_on+0x0/0x2e [redpill]
[   90.682508] 6e 
[   90.682509] eb 
[   90.684421] 00 
[   90.686336] a0 
[   90.688249] ff 
[   90.690166] ff 
[   90.692078] ff 
[   90.693993] ff 
[   90.695900]  [21] 0x0a8      00000000103448b2        rtc_proxy_uinit_auto_power_on+0x0/0x2e [redpill]
[   90.706824] ab 
[   90.706824] ed 
[   90.708737] 00 
[   90.710653] a0 
[   90.712565] ff 
[   90.714472] ff 
[   90.716367] ff 
[   90.718284] ff 
[   90.720204]  [22] 0x0b0      0000000060df12f9        bios_VTK_SET_ALR_LED_null_zero_int+0x0/0x27 [redpill]
[   90.731578] b0 
[   90.731579] 4c 
[   90.733494] 00 
[   90.735405] a0 
[   90.737322] ff 
[   90.739235] ff 
[   90.741146] ff 
[   90.743062] ff 
[   90.744984]  [23] 0x0b8      00000000957312bc        bios_get_buz_clr+0x0/0x10 [redpill]
[   90.754677] d2 
[   90.754678] ed 
[   90.756599] 00 
[   90.758501] a0 
[   90.760418] ff 
[   90.762329] ff 
[   90.764244] ff 
[   90.766158] ff 
[   90.768079]  [24] 0x0c0      00000000dd850310        bios_VTK_SET_BUZ_CLR_null_zero_int+0x0/0x27 [redpill]
[   90.779463] c0 
[   90.779463] 4c 
[   90.781386] 00 
[   90.783303] a0 
[   90.785225] ff 
[   90.787147] ff 
[   90.789062] ff 
[   90.790980] ff 
[   90.792902]  [25] 0x0c8      00000000b16a5213        bios_get_power_status+0x0/0x20 [redpill]
[   90.803057] 00 
[   90.803057] 00 
[   90.804971] 00 
[   90.806888] 00 
[   90.808802] 00 
[   90.810714] 00 
[   90.812630] 00 
[   90.814542] 00 
[   90.816459]  [26] 0x0d0      0000000000000000        0x0
[   90.823119] e0 
[   90.823119] d2 
[   90.825035] 49 
[   90.826956] a0 
[   90.828868] ff 
[   90.830784] ff 
[   90.832695] ff 
[   90.834613] ff 
[   90.836520]  [27] 0x0d8      0000000041c427f2        InitModuleType+0x0/0x30 [epyc7002_synobios]
[   90.846973] 70 
[   90.846974] d3 
[   90.848895] 49 
[   90.850808] a0 
[   90.852719] ff 
[   90.854633] ff 
[   90.856547] ff 
[   90.858462] ff 
[   90.860382]  [28] 0x0e0      000000001cd18d2a        Uninitialize+0x0/0x40 [epyc7002_synobios]
[   90.870636] f9 
[   90.870636] ed 
[   90.872554] 00 
[   90.874471] a0 
[   90.876383] ff 
[   90.878298] ff 
[   90.880205] ff 
[   90.882116] ff 
[   90.884037]  [29] 0x0e8      000000000e96a5fd        bios_VTK_SET_CPU_FAN_STATUS_null_zero_int+0x0/0x27 [redpill]
[   90.896079] 20 
[   90.896079] ee 
[   90.897995] 00 
[   90.899908] a0 
[   90.901825] ff 
[   90.903735] ff 
[   90.905653] ff 
[   90.907559] ff 
[   90.909487]  [30] 0x0f0      0000000032d7d8e4        bios_VTK_SET_PHY_LED_null_zero_int+0x0/0x27 [redpill]
[   90.920876] 47 
[   90.920876] ee 
[   90.922792] 00 
[   90.924704] a0 
[   90.926621] ff 
[   90.928532] ff 
[   90.930449] ff 
[   90.932361] ff 
[   90.934271]  [31] 0x0f8      000000001b648c9c        bios_VTK_SET_HDD_ACT_LED_null_zero_int+0x0/0x27 [redpill]
[   90.946041] 00 
[   90.946042] 00 
[   90.947959] 00 
[   90.949869] 00 
[   90.951785] 00 
[   90.953700] 00 
[   90.955612] 00 
[   90.957527] 00 
[   90.959441]  [32] 0x100      0000000000000000        0x0
[   90.966101] 6e 
[   90.966101] ee 
[   90.968017] 00 
[   90.969939] a0 
[   90.971850] ff 
[   90.973763] ff 
[   90.975679] ff 
[   90.977595] ff 
[   90.979510]  [33] 0x108      00000000c5189650        bios_VTK_GET_MICROP_ID_null_zero_int+0x0/0x27 [redpill]
[   90.991088] 95 
[   90.991089] ee 
[   90.993009] 00 
[   90.994921] a0 
[   90.996827] ff 
[   90.998739] ff 
[   91.000656] ff 
[   91.002566] ff 
[   91.004488]  [34] 0x110      0000000019375d9f        bios_VTK_SET_MICROP_ID_null_zero_int+0x0/0x27 [redpill]
[   91.016070] 00 
[   91.016070] 00 
[   91.017980] 00 
[   91.019898] 00 
[   91.021812] 00 
[   91.023725] 00 
[   91.025631] 00 
[   91.027534] 00 
[   91.029452]  [35] 0x118      0000000000000000        0x0
[   91.036109] 00 
[   91.036110] 00 
[   91.038023] 00 
[   91.039939] 00 
[   91.041850] 00 
[   91.043766] 00 
[   91.045680] 00 
[   91.047591] 00 
[   91.049506]  [36] 0x120      0000000000000000        0x0
[   91.056157] 00 
[   91.056157] 00 
[   91.058074] 00 
[   91.059984] 00 
[   91.061903] 00 
[   91.063814] 00 
[   91.065729] 00 
[   91.067641] 00 
[   91.069560]  [37] 0x128      0000000000000000        0x0
[   91.076224] 00 
[   91.076224] 00 
[   91.078140] 00 
[   91.080053] 00 
[   91.081967] 00 
[   91.083880] 00 
[   91.085793] 00 
[   91.087708] 00 
[   91.089626]  [38] 0x130      0000000000000000        0x0
[   91.096292] 00 
[   91.096292] 00 
[   91.098206] 00 
[   91.100121] 00 
[   91.102035] 00 
[   91.103946] 00 
[   91.105861] 00 
[   91.107776] 00 
[   91.109690]  [39] 0x138      0000000000000000        0x0
[   91.116349] b0 
[   91.116349] d3 
[   91.118265] 49 
[   91.120177] a0 
[   91.122092] ff 
[   91.124006] ff 
[   91.125922] ff 
[   91.127833] ff 
[   91.129753]  [40] 0x140      00000000e41893b7        GetCPUInfo+0x0/0x70 [epyc7002_synobios]
[   91.139826] 00 
[   91.139827] 00 
[   91.141742] 00 
[   91.143653] 00 
[   91.145562] 00 
[   91.147473] 00 
[   91.149388] 00 
[   91.151306] 00 
[   91.153218]  [41] 0x148      0000000000000000        0x0
[   91.159871] 00 
[   91.159871] 00 
[   91.161784] 00 
[   91.163696] 00 
[   91.165613] 00 
[   91.167524] 00 
[   91.169442] 00 
[   91.171353] 00 
[   91.173270]  [42] 0x150      0000000000000000        0x0
[   91.179927] 90 
[   91.179928] 4b 
[   91.181846] 00 
[   91.183766] a0 
[   91.185678] ff 
[   91.187595] ff 
[   91.189508] ff 
[   91.191420] ff 
[   91.193342]  [43] 0x158      000000002f3cd437        bios_hwmon_get_fans_rpm+0x0/0x110 [redpill]
[   91.203781] 00 
[   91.203782] 00 
[   91.205695] 00 
[   91.207598] 00 
[   91.209516] 00 
[   91.211427] 00 
[   91.213343] 00 
[   91.215255] 00 
[   91.217172]  [44] 0x160      0000000000000000        0x0
[   91.223832] 60 
[   91.223833] 4a 
[   91.225743] 00 
[   91.227660] a0 
[   91.229573] ff 
[   91.231478] ff 
[   91.233394] ff 
[   91.235308] ff 
[   91.237223]  [45] 0x168      00000000103e34b5        bios_hwmon_get_voltages+0x0/0x130 [redpill]
[   91.247674] 10 
[   91.247674] 48 
[   91.249588] 00 
[   91.251501] a0 
[   91.253419] ff 
[   91.255341] ff 
[   91.257254] ff 
[   91.259166] ff 
[   91.261087]  [46] 0x170      00000000bfc9cb4e        bios_hwmon_get_hdd_backplane+0x0/0xe0 [redpill]
[   91.271914] 50 
[   91.271915] 49 
[   91.273828] 00 
[   91.275742] a0 
[   91.277664] ff 
[   91.279575] ff 
[   91.281489] ff 
[   91.283404] ff 
[   91.285320]  [47] 0x178      00000000b112f6a9        bios_hwmon_get_thermal+0x0/0x110 [redpill]
[   91.295677] 00 
[   91.295677] 00 
[   91.297590] 00 
[   91.299490] 00 
[   91.301402] 00 
[   91.303314] 00 
[   91.305233] 00 
[   91.307152] 00 
[   91.309070]  [48] 0x180      0000000000000000        0x0
[   91.315738] 00 
[   91.315739] 00 
[   91.317649] 00 
[   91.319566] 00 
[   91.321480] 00 
[   91.323392] 00 
[   91.325303] 00 
[   91.327222] 00 
[   91.329132]  [49] 0x188      0000000000000000        0x0
[   91.335796] 00 
[   91.335797] 00 
[   91.337717] 00 
[   91.339631] 00 
[   91.341547] 00 
[   91.343469] 00 
[   91.345381] 00 
[   91.347285] 00 
[   91.349202]  [50] 0x190      0000000000000000        0x0
[   91.355843] 00 
[   91.355843] 00 
[   91.357760] 00 
[   91.359682] 00 
[   91.361592] 00 
[   91.363509] 00 
[   91.365414] 00 
[   91.367328] 00 
[   91.369240]  [51] 0x198      0000000000000000        0x0
[   91.375896] 00 
[   91.375896] 00 
[   91.377815] 00 
[   91.379731] 00 
[   91.381645] 00 
[   91.383556] 00 
[   91.385471] 00 
[   91.387385] 00 
[   91.389303]  [52] 0x1a0      0000000000000000        0x0
[   91.395967] 
[   91.397600] <redpill/bios_shims_collection.c:117> Finished printing memory at 0000000077985bb3
[   91.406973] <redpill/bios_hwcap_shim.c:79> Registering mfgBIOS HW Capability shim
[   91.415119] <redpill/override_symbol.c:256> Overriding GetHwCapability() with (%pf?)()<00000000e4220cff>
[   91.432281] <redpill/override_symbol.c:171> Saved GetHwCapability() ptr <00000000dea5f9f8>
[   91.441284] <redpill/memory_helper.c:17> Disabling memory protection for page(s) at 00000000dea5f9f8+12/1 (<<0000000027e85f0a)
[   91.453757] <redpill/override_symbol.c:220> Obtaining lock for <00000000dea5f9f8/00000000dea5f9f8>
[   91.463516] <redpill/override_symbol.c:181> Generating trampoline
[   91.470150] <redpill/override_symbol.c:186> Generated trampoline to 00000000e4220cff<00000000e4220cff> for GetHwCapability<00000000dea5f9f8>: 
[   91.484056] <redpill/override_symbol.c:220> Writing trampoline code to <00000000dea5f9f8>
[   91.492955] <redpill/override_symbol.c:220> Released lock for <00000000dea5f9f8>
[   91.501005] <redpill/memory_helper.c:33> Enabling memory protection for page(s) at 00000000dea5f9f8+12/1 (<<0000000027e85f0a)
[   91.513375] <redpill/override_symbol.c:268> Successfully overrode GetHwCapability() with trampoline to 00000000e4220cff<00000000e4220cff>
[   91.526816] <redpill/bios_hwcap_shim.c:87> Successfully registered mfgBIOS HW Capability shim
[   91.536085] <redpill/bios_psu_status_shim.c:23> Registering mfgBIOS HWMONGetPSUStatusByI2C shim
[   91.545535] <redpill/override_symbol.c:256> Overriding HWMONGetPSUStatusByI2C() with (%pf?)()<00000000a5a48881>
[   91.563383] <redpill/override_symbol.c:171> Saved HWMONGetPSUStatusByI2C() ptr <00000000345531e1>
[   91.573036] <redpill/memory_helper.c:17> Disabling memory protection for page(s) at 00000000345531e1+12/1 (<<00000000e1cddb66)
[   91.585491] <redpill/override_symbol.c:220> Obtaining lock for <00000000345531e1/00000000345531e1>
[   91.595249] <redpill/override_symbol.c:181> Generating trampoline
[   91.601882] <redpill/override_symbol.c:186> Generated trampoline to 00000000a5a48881<00000000a5a48881> for HWMONGetPSUStatusByI2C<00000000345531e1>: 
[   91.616449] <redpill/override_symbol.c:220> Writing trampoline code to <00000000345531e1>
[   91.625350] <redpill/override_symbol.c:220> Released lock for <00000000345531e1>
[   91.633399] <redpill/memory_helper.c:33> Enabling memory protection for page(s) at 00000000345531e1+12/1 (<<00000000e1cddb66)
[   91.645765] <redpill/override_symbol.c:268> Successfully overrode HWMONGetPSUStatusByI2C() with trampoline to 00000000a5a48881<00000000a5a48881>
[   91.659862] <redpill/bios_psu_status_shim.c:31> Successfully registered mfgBIOS HWMONGetPSUStatusByI2C shim
[   91.670455] <redpill/bios_shim.c:135> epyc7002_synobios BIOS *early* shimmed
[   91.678352] synobios open /dev/ttyS1 success
[   91.683016] Fail to get disk 1 led type
[   91.687208] Fail to get disk 2 led type
[   91.691388] Fail to get disk 3 led type
[   91.695564] Fail to get disk 4 led type
[   91.699739] Fail to get disk 5 led type
[   91.703924] Fail to get disk 6 led type
[   91.708103] Fail to get disk 7 led type
[   91.712287] Fail to get disk 8 led type
[   91.716472] Fail to get disk 9 led type
[   91.720653] Fail to get disk 10 led type
[   91.724930] Fail to get disk 11 led type
[   91.729203] Fail to get disk 12 led type
[   91.733476] <redpill/bios_shims_collection.c:226> Received syno_ahci_disk_led_enable_by_port_shim with port=1 val=1
[   91.744832] <redpill/bios_shims_collection.c:226> Received syno_ahci_disk_led_enable_by_port_shim with port=2 val=1
[   91.756191] <redpill/bios_shims_collection.c:226> Received syno_ahci_disk_led_enable_by_port_shim with port=3 val=1
[   91.767536] <redpill/bios_shims_collection.c:226> Received syno_ahci_disk_led_enable_by_port_shim with port=4 val=1
[   91.778879] <redpill/bios_shims_collection.c:226> Received syno_ahci_disk_led_enable_by_port_shim with port=5 val=1
[   91.790237] <redpill/bios_shims_collection.c:226> Received syno_ahci_disk_led_enable_by_port_shim with port=6 val=1
[   91.801574] <redpill/bios_shims_collection.c:226> Received syno_ahci_disk_led_enable_by_port_shim with port=7 val=1
[   91.812931] <redpill/bios_shims_collection.c:226> Received syno_ahci_disk_led_enable_by_port_shim with port=8 val=1
[   91.824292] <redpill/bios_shims_collection.c:226> Received syno_ahci_disk_led_enable_by_port_shim with port=9 val=1
[   91.835648] <redpill/bios_shims_collection.c:226> Received syno_ahci_disk_led_enable_by_port_shim with port=10 val=1
[   91.847096] <redpill/bios_shims_collection.c:226> Received syno_ahci_disk_led_enable_by_port_shim with port=11 val=1
[   91.858544] <redpill/bios_shims_collection.c:226> Received syno_ahci_disk_led_enable_by_port_shim with port=12 val=1
[   91.869994] <redpill/rtc_proxy.c:204> RTC power-on "enabled" via rtc_proxy_init_auto_power_on
[   91.879275] <redpill/rtc_proxy.c:39> MfgCompatTime raw data: sec=0 min=0 hr=0 wkd=0 day=0 mth=0 yr=0
[   91.889244] <redpill/rtc_proxy.c:60> Reading BCD-based RTC
[   91.895390] <redpill/rtc_proxy.c:145> Time got from RTC is 2023-04-03 15:17:38 (UTC)
[   91.903822] <redpill/rtc_proxy.c:39> MfgCompatTime raw data: sec=38 min=17 hr=15 wkd=1 day=3 mth=3 yr=123
[   91.914303] 2023-4-3 15:17:38 UTC
[   91.917922] synobios: load, major number 201
[   91.922577] Brand: Synology
[   91.925630] Model: SA-6400
[   91.928581] <redpill/bios_shims_collection.c:61> mfgBIOS: nullify zero-int for VTK_SET_MICROP_ID
[   91.938135] synobios cpu_arch proc entry initialized
[   91.943541] synobios crypto_hw proc entry initialized
[   91.949044] synobios syno_platform proc entry initialized
[   91.954927] <redpill/bios_shims_collection.c:104> Will print 424 bytes of memory from 000000003d08a40c
[   91.965074] 40 
[   91.965075] 97 
[   91.967008] 4a 
[   91.968923] a0 
[   91.970838] ff 
[   91.972752] ff 
[   91.974664] ff 
[   91.976581] ff 
[   91.978511]  [00] 0x000      00000000f094de10        __this_module+0x0/0xffffffffffff58c0 [epyc7002_synobios]
[   91.990184] 00 
[   91.990185] 76 
[   91.992096] 49 
[   91.994013] a0 
[   91.995934] ff 
[   91.997846] ff 
[   91.999763] ff 
[   92.001674] ff 
[   92.003596]  [01] 0x008      00000000b851adcb        GetBrand+0x0/0x10 [epyc7002_synobios]
[   92.013477] f0 
[   92.013478] d6 
[   92.015391] 49 
[   92.017305] a0 
[   92.019220] ff 
[   92.021134] ff 
[   92.023048] ff 
[   92.024959] ff 
[   92.026882]  [02] 0x010      0000000044981e82        GetModel+0x0/0xa0 [epyc7002_synobios]
[   92.036763] 00 
[   92.036764] 00 
[   92.038680] 00 
[   92.040602] 00 
[   92.042513] 00 
[   92.044429] 00 
[   92.046342] 00 
[   92.048254] 00 
[   92.050175]  [03] 0x018      0000000000000000        0x0
[   92.056840] 6c 
[   92.056841] e7 
[   92.058747] 00 
[   92.060670] a0 
[   92.062590] ff 
[   92.064503] ff 
[   92.066419] ff 
[   92.068332] ff 
[   92.070255]  [04] 0x020      000000004704f422        rtc_proxy_get_time+0x0/0xd0 [redpill]
[   92.080125] 3c 
[   92.080126] e8 
[   92.082043] 00 
[   92.083964] a0 
[   92.085875] ff 
[   92.087792] ff 
[   92.089702] ff 
[   92.091609] ff 
[   92.093528]  [05] 0x028      00000000c5a7599f        rtc_proxy_set_time+0x0/0x215 [redpill]
[   92.103496] 00 
[   92.103497] 48 
[   92.105412] 00 
[   92.107324] a0 
[   92.109239] ff 
[   92.111156] ff 
[   92.113070] ff 
[   92.114982] ff 
[   92.116902]  [06] 0x030      000000006a8faed4        bios_get_fan_state+0x0/0x10 [redpill]
[   92.126781] 0f 
[   92.126782] ed 
[   92.128697] 00 
[   92.130611] a0 
[   92.132525] ff 
[   92.134440] ff 
[   92.136351] ff 
[   92.138265] ff 
[   92.140188]  [07] 0x038      00000000c07ac642        bios_VTK_SET_FAN_STATE_null_zero_int+0x0/0x27 [redpill]
[   92.151771] 00 
[   92.151771] 00 
[   92.153693] 00 
[   92.155605] 00 
[   92.157521] 00 
[   92.159432] 00 
[   92.161348] 00 
[   92.163264] 00 
[   92.165184]  [08] 0x040      0000000000000000        0x0
[   92.171847] f0 
[   92.171848] 48 
[   92.173770] 00 
[   92.175690] a0 
[   92.177602] ff 
[   92.179515] ff 
[   92.181430] ff 
[   92.183348] ff 
[   92.185265]  [09] 0x048      00000000ebf6df74        bios_get_cpu_temp+0x0/0x40 [redpill]
[   92.195054] 50 
[   92.195054] c8 
[   92.196969] 49 
[   92.198881] a0 
[   92.200794] ff 
[   92.202710] ff 
[   92.204626] ff 
[   92.206539] ff 
[   92.208460]  [10] 0x050      000000007a38cb5c        SetDiskLedStatusByLedTrigger+0x0/0x130 [epyc7002_synobios]
[   92.220305] 80 
[   92.220306] d4 
[   92.222221] 49 
[   92.224133] a0 
[   92.226051] ff 
[   92.227972] ff 
[   92.229884] ff 
[   92.231802] ff 
[   92.233718]  [11] 0x058      000000002c18a2bd        SetPowerLedStatus+0x0/0x50 [epyc7002_synobios]
[   92.244444] 00 
[   92.244445] 00 
[   92.246367] 00 
[   92.248285] 00 
[   92.250202] 00 
[   92.252118] 00 
[   92.254036] 00 
[   92.255953] 00 
[   92.257870]  [12] 0x060      0000000000000000        0x0
[   92.264534] 00 
[   92.264534] 00 
[   92.266446] 00 
[   92.268362] 00 
[   92.270279] 00 
[   92.272191] 00 
[   92.274104] 00 
[   92.276018] 00 
[   92.277933]  [13] 0x068      0000000000000000        0x0
[   92.284596] 00 
[   92.284597] 00 
[   92.286517] 00 
[   92.288430] 00 
[   92.290345] 00 
[   92.292259] 00 
[   92.294160] 00 
[   92.296077] 00 
[   92.297990]  [14] 0x070      0000000000000000        0x0
[   92.304652] bc 
[   92.304653] ee 
[   92.306574] 00 
[   92.308487] a0 
[   92.310401] ff 
[   92.312316] ff 
[   92.314230] ff 
[   92.316142] ff 
[   92.318065]  [15] 0x078      00000000f952a3a0        shim_set_gpio_pin_usable+0x0/0x98 [redpill]
[   92.328512] a0 
[   92.328513] 4c 
[   92.330434] 00 
[   92.332347] a0 
[   92.334263] ff 
[   92.336185] ff 
[   92.338096] ff 
[   92.340009] ff 
[   92.341929]  [16] 0x080      0000000081b034fa        shim_get_gpio_pin_usable+0x0/0x10 [redpill]
[   92.352381] 84 
[   92.352382] ed 
[   92.354302] 00 
[   92.356217] a0 
[   92.358128] ff 
[   92.360041] ff 
[   92.361957] ff 
[   92.363871] ff 
[   92.365793]  [17] 0x088      000000004d032948        bios_VTK_SET_GPIO_PIN_BLINK_null_zero_int+0x0/0x27 [redpill]
[   92.377834] fa 
[   92.377834] ea 
[   92.379750] 00 
[   92.381673] a0 
[   92.383583] ff 
[   92.385496] ff 
[   92.387411] ff 
[   92.389324] ff 
[   92.391245]  [18] 0x090      000000006c3f2fef        rtc_proxy_set_auto_power_on+0x0/0x74 [redpill]
[   92.401979] 7f 
[   92.401980] ea 
[   92.403901] 00 
[   92.405812] a0 
[   92.407719] ff 
[   92.409630] ff 
[   92.411546] ff 
[   92.413458] ff 
[   92.415365]  [19] 0x098      000000002e35ba90        rtc_proxy_get_auto_power_on+0x0/0x7b [redpill]
[   92.426096] 51 
[   92.426096] ea 
[   92.428008] 00 
[   92.429925] a0 
[   92.431843] ff 
[   92.433759] ff 
[   92.435672] ff 
[   92.437587] ff 
[   92.439508]  [20] 0x0a0      00000000650350ca        rtc_proxy_init_auto_power_on+0x0/0x2e [redpill]
[   92.450324] 6e 
[   92.450325] eb 
[   92.452238] 00 
[   92.454149] a0 
[   92.456067] ff 
[   92.457977] ff 
[   92.459894] ff 
[   92.461807] ff 
[   92.463717]  [21] 0x0a8      00000000103448b2        rtc_proxy_uinit_auto_power_on+0x0/0x2e [redpill]
[   92.474636] 60 
[   92.474636] d4 
[   92.476551] 49 
[   92.478466] a0 
[   92.480382] ff 
[   92.482302] ff 
[   92.484214] ff 
[   92.486131] ff 
[   92.488047]  [22] 0x0b0      000000007b40b78b        SetAlarmLed+0x0/0x20 [epyc7002_synobios]
[   92.498212] b0 
[   92.498213] 4c 
[   92.500130] 00 
[   92.502042] a0 
[   92.503958] ff 
[   92.505859] ff 
[   92.507776] ff 
[   92.509692] ff 
[   92.511609]  [23] 0x0b8      00000000957312bc        bios_get_buz_clr+0x0/0x10 [redpill]
[   92.521303] d2 
[   92.521303] ed 
[   92.523220] 00 
[   92.525142] a0 
[   92.527062] ff 
[   92.528975] ff 
[   92.530890] ff 
[   92.532804] ff 
[   92.534727]  [24] 0x0c0      00000000dd850310        bios_VTK_SET_BUZ_CLR_null_zero_int+0x0/0x27 [redpill]
[   92.546118] c0 
[   92.546119] 4c 
[   92.548029] 00 
[   92.549947] a0 
[   92.551868] ff 
[   92.553780] ff 
[   92.555696] ff 
[   92.557609] ff 
[   92.559530]  [25] 0x0c8      00000000b16a5213        bios_get_power_status+0x0/0x20 [redpill]
[   92.569695] 00 
[   92.569696] 00 
[   92.571607] 00 
[   92.573522] 00 
[   92.575435] 00 
[   92.577352] 00 
[   92.579262] 00 
[   92.581177] 00 
[   92.583093]  [26] 0x0d0      0000000000000000        0x0
[   92.589746] e0 
[   92.589747] d2 
[   92.591658] 49 
[   92.593574] a0 
[   92.595487] ff 
[   92.597402] ff 
[   92.599315] ff 
[   92.601228] ff 
[   92.603147]  [27] 0x0d8      0000000041c427f2        InitModuleType+0x0/0x30 [epyc7002_synobios]
[   92.613598] 70 
[   92.613598] d3 
[   92.615513] 49 
[   92.617431] a0 
[   92.619348] ff 
[   92.621260] ff 
[   92.623177] ff 
[   92.625087] ff 
[   92.627008]  [28] 0x0e0      000000001cd18d2a        Uninitialize+0x0/0x40 [epyc7002_synobios]
[   92.637271] f9 
[   92.637272] ed 
[   92.639192] 00 
[   92.641098] a0 
[   92.643010] ff 
[   92.644927] ff 
[   92.646839] ff 
[   92.648751] ff 
[   92.650673]  [29] 0x0e8      000000000e96a5fd        bios_VTK_SET_CPU_FAN_STATUS_null_zero_int+0x0/0x27 [redpill]
[   92.662724] 20 
[   92.662725] ee 
[   92.664640] 00 
[   92.666554] a0 
[   92.668469] ff 
[   92.670381] ff 
[   92.672297] ff 
[   92.674210] ff 
[   92.676128]  [30] 0x0f0      0000000032d7d8e4        bios_VTK_SET_PHY_LED_null_zero_int+0x0/0x27 [redpill]
[   92.687522] c0 
[   92.687523] c9 
[   92.689437] 49 
[   92.691351] a0 
[   92.693266] ff 
[   92.695179] ff 
[   92.697092] ff 
[   92.699007] ff 
[   92.700924]  [31] 0x0f8      00000000b43530e0        SetHddActLedByLedTrigger+0x0/0x190 [epyc7002_synobios]
[   92.712403] 00 
[   92.712404] 00 
[   92.714319] 00 
[   92.716232] 00 
[   92.718148] 00 
[   92.720060] 00 
[   92.721976] 00 
[   92.723890] 00 
[   92.725803]  [32] 0x100      0000000000000000        0x0
[   92.732462] 6e 
[   92.732463] ee 
[   92.734379] 00 
[   92.736300] a0 
[   92.738212] ff 
[   92.740129] ff 
[   92.742051] ff 
[   92.743962] ff 
[   92.745884]  [33] 0x108      00000000c5189650        bios_VTK_GET_MICROP_ID_null_zero_int+0x0/0x27 [redpill]
[   92.757455] 95 
[   92.757455] ee 
[   92.759371] 00 
[   92.761282] a0 
[   92.763199] ff 
[   92.765111] ff 
[   92.767028] ff 
[   92.768950] ff 
[   92.770866]  [34] 0x110      0000000019375d9f        bios_VTK_SET_MICROP_ID_null_zero_int+0x0/0x27 [redpill]
[   92.782479] 00 
[   92.782480] 00 
[   92.784399] 00 
[   92.786302] 00 
[   92.788217] 00 
[   92.790134] 00 
[   92.792056] 00 
[   92.793974] 00 
[   92.795891]  [35] 0x118      0000000000000000        0x0
[   92.802541] 00 
[   92.802541] 00 
[   92.804458] 00 
[   92.806370] 00 
[   92.808285] 00 
[   92.810197] 00 
[   92.812113] 00 
[   92.814026] 00 
[   92.815943]  [36] 0x120      0000000000000000        0x0
[   92.822609] 00 
[   92.822609] 00 
[   92.824524] 00 
[   92.826436] 00 
[   92.828353] 00 
[   92.830273] 00 
[   92.832186] 00 
[   92.834104] 00 
[   92.836015]  [37] 0x128      0000000000000000        0x0
[   92.842675] 00 
[   92.842676] 00 
[   92.844591] 00 
[   92.846506] 00 
[   92.848419] 00 
[   92.850336] 00 
[   92.852258] 00 
[   92.854170] 00 
[   92.856083]  [38] 0x130      0000000000000000        0x0
[   92.862747] 00 
[   92.862747] 00 
[   92.864669] 00 
[   92.866580] 00 
[   92.868487] 00 
[   92.870402] 00 
[   92.872316] 00 
[   92.874231] 00 
[   92.876151]  [39] 0x138      0000000000000000        0x0
[   92.882810] b0 
[   92.882810] d3 
[   92.884726] 49 
[   92.886638] a0 
[   92.888554] ff 
[   92.890466] ff 
[   92.892384] ff 
[   92.894298] ff 
[   92.896215]  [40] 0x140      00000000e41893b7        GetCPUInfo+0x0/0x70 [epyc7002_synobios]
[   92.906287] 00 
[   92.906287] 00 
[   92.908199] 00 
[   92.910114] 00 
[   92.912027] 00 
[   92.913944] 00 
[   92.915850] 00 
[   92.917762] 00 
[   92.919680]  [41] 0x148      0000000000000000        0x0
[   92.926347] 00 
[   92.926348] 00 
[   92.928260] 00 
[   92.930173] 00 
[   92.932090] 00 
[   92.934006] 00 
[   92.935927] 00 
[   92.937838] 00 
[   92.939754]  [42] 0x150      0000000000000000        0x0
[   92.946417] 70 
[   92.946417] d6 
[   92.948327] 49 
[   92.950245] a0 
[   92.952156] ff 
[   92.954074] ff 
[   92.955994] ff 
[   92.957906] ff 
[   92.959823]  [43] 0x158      000000003a13e5e1        HWMONGetFanSpeedRPMFromADT+0x0/0x60 [epyc7002_synobios]
[   92.971402] 20 
[   92.971402] d4 
[   92.973314] 49 
[   92.975230] a0 
[   92.977136] ff 
[   92.979049] ff 
[   92.980964] ff 
[   92.982878] ff 
[   92.984793]  [44] 0x160      0000000036abfc94        EPYC7002GetPSUStatusByI2C+0x0/0x40 [epyc7002_synobios]
[   92.996285] 10 
[   92.996286] d6 
[   92.998207] 49 
[   93.000119] a0 
[   93.002036] ff 
[   93.003958] ff 
[   93.005869] ff 
[   93.007786] ff 
[   93.009705]  [45] 0x168      00000000d997ab30        HWMONGetVoltageSensorFromADT+0x0/0x60 [epyc7002_synobios]
[   93.021473] e0 
[   93.021474] d7 
[   93.023387] 49 
[   93.025302] a0 
[   93.027218] ff 
[   93.029129] ff 
[   93.031046] ff 
[   93.032957] ff 
[   93.034878]  [46] 0x170      00000000cf4041b1        HWMONGetHDDBackPlaneStatusBySMBUS+0x0/0x160 [epyc7002_synobios]
[   93.047212] b0 
[   93.047213] d5 
[   93.049127] 49 
[   93.051045] a0 
[   93.052967] ff 
[   93.054880] ff 
[   93.056792] ff 
[   93.058704] ff 
[   93.060622]  [47] 0x178      000000009e3458d4        HWMONGetThermalSensorFromADT+0x0/0x60 [epyc7002_synobios]
[   93.072389] 00 
[   93.072390] 00 
[   93.074301] 00 
[   93.076217] 00 
[   93.078128] 00 
[   93.080042] 00 
[   93.081957] 00 
[   93.083871] 00 
[   93.085789]  [48] 0x180      0000000000000000        0x0
[   93.092457] 00 
[   93.092457] 00 
[   93.094371] 00 
[   93.096282] 00 
[   93.098197] 00 
[   93.100113] 00 
[   93.102026] 00 
[   93.103943] 00 
[   93.105866]  [49] 0x188      0000000000000000        0x0
[   93.112530] 00 
[   93.112530] 00 
[   93.114448] 00 
[   93.116368] 00 
[   93.118280] 00 
[   93.120196] 00 
[   93.122109] 00 
[   93.124027] 00 
[   93.125939]  [50] 0x190      0000000000000000        0x0
[   93.132597] 00 
[   93.132597] 00 
[   93.134514] 00 
[   93.136434] 00 
[   93.138347] 00 
[   93.140260] 00 
[   93.142177] 00 
[   93.144082] 00 
[   93.145996]  [51] 0x198      0000000000000000        0x0
[   93.152654] 00 
[   93.152654] 00 
[   93.154570] 00 
[   93.156483] 00 
[   93.158394] 00 
[   93.160310] 00 
[   93.162222] 00 
[   93.164137] 00 
[   93.166053]  [52] 0x1a0      0000000000000000        0x0
[   93.172704] 
[   93.174335] <redpill/bios_shims_collection.c:117> Finished printing memory at 0000000077985bb3
[   93.183716] <redpill/bios_shims_collection.c:86> mfgBIOS vtable [10] originally SetDiskLedStatusByLedTrigger [epyc7002_synobios]<000000007a38cb5c> will now be bios_VTK_SET_DISK_LED_null_zero_int [redpill]<0000000017eb00ed>
[   93.205189] <redpill/bios_shims_collection.c:86> mfgBIOS vtable [11] originally SetPowerLedStatus [epyc7002_synobios]<000000002c18a2bd> will now be bios_VTK_SET_PWR_LED_null_zero_int [redpill]<00000000ef3022d1>
[   93.225512] <redpill/bios_shims_collection.c:86> mfgBIOS vtable [22] originally SetAlarmLed [epyc7002_synobios]<000000007b40b78b> will now be bios_VTK_SET_ALR_LED_null_zero_int [redpill]<0000000060df12f9>
[   93.245285] <redpill/bios_shims_collection.c:86> mfgBIOS vtable [31] originally SetHddActLedByLedTrigger [epyc7002_synobios]<00000000b43530e0> will now be bios_VTK_SET_HDD_ACT_LED_null_zero_int [redpill]<000000001b648c9c>
[   93.266657] <redpill/bios_shims_collection.c:155> Platform requires RTC proxy - enabling
[   93.275462] <redpill/rtc_proxy.c:260> Registering RTC proxy shim
[   93.282011] <redpill/rtc_proxy.c:263> The RTC proxy shim is already registered - unregistering first
[   93.291945] <redpill/rtc_proxy.c:244> Unregistering RTC proxy shim
[   93.298670] <redpill/rtc_proxy.c:254> Successfully unregistered RTC proxy shim
[   93.306533] <redpill/rtc_proxy.c:268> Successfully registered RTC proxy shim
[   93.314205] <redpill/bios_hwmon_shim.c:332> Registering mfgBIOS HW Monitor shim
[   93.322170] <redpill/bios_shims_collection.c:86> mfgBIOS vtable [47] originally HWMONGetThermalSensorFromADT [epyc7002_synobios]<000000009e3458d4> will now be bios_hwmon_get_thermal [redpill]<00000000b112f6a9>
[   93.342410] <redpill/bios_shims_collection.c:86> mfgBIOS vtable [45] originally HWMONGetVoltageSensorFromADT [epyc7002_synobios]<00000000d997ab30> will now be bios_hwmon_get_voltages [redpill]<00000000103e34b5>
[   93.362748] <redpill/bios_shims_collection.c:86> mfgBIOS vtable [43] originally HWMONGetFanSpeedRPMFromADT [epyc7002_synobios]<000000003a13e5e1> will now be bios_hwmon_get_fans_rpm [redpill]<000000002f3cd437>
[   93.382901] <redpill/bios_shims_collection.c:86> mfgBIOS vtable [46] originally HWMONGetHDDBackPlaneStatusBySMBUS [epyc7002_synobios]<00000000cf4041b1> will now be bios_hwmon_get_hdd_backplane [redpill]<00000000bfc9cb4e>
[   93.404178] <redpill/bios_hwmon_shim.c:358> Successfully registered mfgBIOS HW Monitor shim
[   93.413262] <redpill/bios_shims_collection.c:104> Will print 424 bytes of memory from 000000003d08a40c
[   93.423397] 40 
[   93.423397] 97 
[   93.425307] 4a 
[   93.427221] a0 
[   93.429137] ff 
[   93.431054] ff 
[   93.432972] ff 
[   93.434887] ff 
[   93.436810]  [00] 0x000      00000000f094de10        __this_module+0x0/0xffffffffffff58c0 [epyc7002_synobios]
[   93.448474] 00 
[   93.448474] 76 
[   93.450390] 49 
[   93.452303] a0 
[   93.454219] ff 
[   93.456130] ff 
[   93.458042] ff 
[   93.459959] ff 
[   93.461875]  [01] 0x008      00000000b851adcb        GetBrand+0x0/0x10 [epyc7002_synobios]
[   93.471761] f0 
[   93.471762] d6 
[   93.473672] 49 
[   93.475586] a0 
[   93.477503] ff 
[   93.479418] ff 
[   93.481330] ff 
[   93.483246] ff 
[   93.485161]  [02] 0x010      0000000044981e82        GetModel+0x0/0xa0 [epyc7002_synobios]
[   93.495045] 00 
[   93.495045] 00 
[   93.496951] 00 
[   93.498865] 00 
[   93.500776] 00 
[   93.502691] 00 
[   93.504597] 00 
[   93.506510] 00 
[   93.508428]  [03] 0x018      0000000000000000        0x0
[   93.515093] 6c 
[   93.515093] e7 
[   93.517007] 00 
[   93.518921] a0 
[   93.520837] ff 
[   93.522753] ff 
[   93.524665] ff 
[   93.526581] ff 
[   93.528499]  [04] 0x020      000000004704f422        rtc_proxy_get_time+0x0/0xd0 [redpill]
[   93.538373] 3c 
[   93.538374] e8 
[   93.540296] 00 
[   93.542219] a0 
[   93.544140] ff 
[   93.546053] ff 
[   93.547969] ff 
[   93.549881] ff 
[   93.551798]  [05] 0x028      00000000c5a7599f        rtc_proxy_set_time+0x0/0x215 [redpill]
[   93.561777] 00 
[   93.561778] 48 
[   93.563692] 00 
[   93.565604] a0 
[   93.567521] ff 
[   93.569433] ff 
[   93.571350] ff 
[   93.573268] ff 
[   93.575190]  [06] 0x030      000000006a8faed4        bios_get_fan_state+0x0/0x10 [redpill]
[   93.585073] 0f 
[   93.585074] ed 
[   93.586990] 00 
[   93.588900] a0 
[   93.590814] ff 
[   93.592731] ff 
[   93.594642] ff 
[   93.596557] ff 
[   93.598479]  [07] 0x038      00000000c07ac642        bios_VTK_SET_FAN_STATE_null_zero_int+0x0/0x27 [redpill]
[   93.610063] 00 
[   93.610063] 00 
[   93.611983] 00 
[   93.613895] 00 
[   93.615808] 00 
[   93.617722] 00 
[   93.619640] 00 
[   93.621552] 00 
[   93.623469]  [08] 0x040      0000000000000000        0x0
[   93.630127] f0 
[   93.630127] 48 
[   93.632041] 00 
[   93.633957] a0 
[   93.635868] ff 
[   93.637785] ff 
[   93.639696] ff 
[   93.641605] ff 
[   93.643524]  [09] 0x048      00000000ebf6df74        bios_get_cpu_temp+0x0/0x40 [redpill]
[   93.653313] 36 
[   93.653313] ed 
[   93.655235] 00 
[   93.657147] a0 
[   93.659060] ff 
[   93.660974] ff 
[   93.662887] ff 
[   93.664804] ff 
[   93.666726]  [10] 0x050      0000000017eb00ed        bios_VTK_SET_DISK_LED_null_zero_int+0x0/0x27 [redpill]
[   93.678212] 5d 
[   93.678213] ed 
[   93.680132] 00 
[   93.682044] a0 
[   93.683962] ff 
[   93.685884] ff 
[   93.687798] ff 
[   93.689712] ff 
[   93.691630]  [11] 0x058      00000000ef3022d1        bios_VTK_SET_PWR_LED_null_zero_int+0x0/0x27 [redpill]
[   93.703023] 00 
[   93.703024] 00 
[   93.704936] 00 
[   93.706848] 00 
[   93.708763] 00 
[   93.710680] 00 
[   93.712593] 00 
[   93.714504] 00 
[   93.716421]  [12] 0x060      0000000000000000        0x0
[   93.723080] 00 
[   93.723080] 00 
[   93.724993] 00 
[   93.726909] 00 
[   93.728824] 00 
[   93.730747] 00 
[   93.732669] 00 
[   93.734592] 00 
[   93.736514]  [13] 0x068      0000000000000000        0x0
[   93.743179] 00 
[   93.743179] 00 
[   93.745096] 00 
[   93.747006] 00 
[   93.748922] 00 
[   93.750835] 00 
[   93.752752] 00 
[   93.754663] 00 
[   93.756580]  [14] 0x070      0000000000000000        0x0
[   93.763246] bc 
[   93.763246] ee 
[   93.765158] 00 
[   93.767075] a0 
[   93.768987] ff 
[   93.770904] ff 
[   93.772815] ff 
[   93.774731] ff 
[   93.776647]  [15] 0x078      00000000f952a3a0        shim_set_gpio_pin_usable+0x0/0x98 [redpill]
[   93.787100] a0 
[   93.787100] 4c 
[   93.789021] 00 
[   93.790933] a0 
[   93.792849] ff 
[   93.794763] ff 
[   93.796673] ff 
[   93.798590] ff 
[   93.800509]  [16] 0x080      0000000081b034fa        shim_get_gpio_pin_usable+0x0/0x10 [redpill]
[   93.810955] 84 
[   93.810956] ed 
[   93.812869] 00 
[   93.814786] a0 
[   93.816697] ff 
[   93.818613] ff 
[   93.820526] ff 
[   93.822437] ff 
[   93.824358]  [17] 0x088      000000004d032948        bios_VTK_SET_GPIO_PIN_BLINK_null_zero_int+0x0/0x27 [redpill]
[   93.836411] fa 
[   93.836411] ea 
[   93.838328] 00 
[   93.840239] a0 
[   93.842155] ff 
[   93.844068] ff 
[   93.845985] ff 
[   93.847906] ff 
[   93.849823]  [18] 0x090      000000006c3f2fef        rtc_proxy_set_auto_power_on+0x0/0x74 [redpill]
[   93.860553] 7f 
[   93.860554] ea 
[   93.862462] 00 
[   93.864373] a0 
[   93.866289] ff 
[   93.868201] ff 
[   93.870116] ff 
[   93.872030] ff 
[   93.873947]  [19] 0x098      000000002e35ba90        rtc_proxy_get_auto_power_on+0x0/0x7b [redpill]
[   93.884678] 51 
[   93.884679] ea 
[   93.886595] 00 
[   93.888509] a0 
[   93.890424] ff 
[   93.892337] ff 
[   93.894247] ff 
[   93.896154] ff 
[   93.898072]  [20] 0x0a0      00000000650350ca        rtc_proxy_init_auto_power_on+0x0/0x2e [redpill]
[   93.908900] 6e 
[   93.908900] eb 
[   93.910816] 00 
[   93.912737] a0 
[   93.914647] ff 
[   93.916563] ff 
[   93.918477] ff 
[   93.920393] ff 
[   93.922316]  [21] 0x0a8      00000000103448b2        rtc_proxy_uinit_auto_power_on+0x0/0x2e [redpill]
[   93.933238] ab 
[   93.933239] ed 
[   93.935149] 00 
[   93.937068] a0 
[   93.938970] ff 
[   93.940885] ff 
[   93.942798] ff 
[   93.944715] ff 
[   93.946631]  [22] 0x0b0      0000000060df12f9        bios_VTK_SET_ALR_LED_null_zero_int+0x0/0x27 [redpill]
[   93.958026] b0 
[   93.958027] 4c 
[   93.959948] 00 
[   93.961859] a0 
[   93.963776] ff 
[   93.965686] ff 
[   93.967604] ff 
[   93.969515] ff 
[   93.971433]  [23] 0x0b8      00000000957312bc        bios_get_buz_clr+0x0/0x10 [redpill]
[   93.981126] d2 
[   93.981127] ed 
[   93.983043] 00 
[   93.984962] a0 
[   93.986878] ff 
[   93.988785] ff 
[   93.990705] ff 
[   93.992617] ff 
[   93.994530]  [24] 0x0c0      00000000dd850310        bios_VTK_SET_BUZ_CLR_null_zero_int+0x0/0x27 [redpill]
[   94.005906] c0 
[   94.005906] 4c 
[   94.007821] 00 
[   94.009742] a0 
[   94.011654] ff 
[   94.013569] ff 
[   94.015484] ff 
[   94.017390] ff 
[   94.019306]  [25] 0x0c8      00000000b16a5213        bios_get_power_status+0x0/0x20 [redpill]
[   94.029472] 00 
[   94.029472] 00 
[   94.031385] 00 
[   94.033302] 00 
[   94.035213] 00 
[   94.037130] 00 
[   94.039041] 00 
[   94.040959] 00 
[   94.042883]  [26] 0x0d0      0000000000000000        0x0
[   94.049550] e0 
[   94.049550] d2 
[   94.051462] 49 
[   94.053369] a0 
[   94.055280] ff 
[   94.057198] ff 
[   94.059119] ff 
[   94.061032] ff 
[   94.062952]  [27] 0x0d8      0000000041c427f2        InitModuleType+0x0/0x30 [epyc7002_synobios]
[   94.073402] 70 
[   94.073402] d3 
[   94.075324] 49 
[   94.077235] a0 
[   94.079150] ff 
[   94.081065] ff 
[   94.082980] ff 
[   94.084890] ff 
[   94.086810]  [28] 0x0e0      000000001cd18d2a        Uninitialize+0x0/0x40 [epyc7002_synobios]
[   94.097068] f9 
[   94.097069] ed 
[   94.098983] 00 
[   94.100899] a0 
[   94.102815] ff 
[   94.104734] ff 
[   94.106650] ff 
[   94.108561] ff 
[   94.110484]  [29] 0x0e8      000000000e96a5fd        bios_VTK_SET_CPU_FAN_STATUS_null_zero_int+0x0/0x27 [redpill]
[   94.122528] 20 
[   94.122529] ee 
[   94.124441] 00 
[   94.126356] a0 
[   94.128271] ff 
[   94.130190] ff 
[   94.132103] ff 
[   94.134020] ff 
[   94.135937]  [30] 0x0f0      0000000032d7d8e4        bios_VTK_SET_PHY_LED_null_zero_int+0x0/0x27 [redpill]
[   94.147330] 47 
[   94.147330] ee 
[   94.149244] 00 
[   94.151160] a0 
[   94.153070] ff 
[   94.154987] ff 
[   94.156898] ff 
[   94.158812] ff 
[   94.160732]  [31] 0x0f8      000000001b648c9c        bios_VTK_SET_HDD_ACT_LED_null_zero_int+0x0/0x27 [redpill]
[   94.172502] 00 
[   94.172502] 00 
[   94.174420] 00 
[   94.176342] 00 
[   94.178254] 00 
[   94.180169] 00 
[   94.182079] 00 
[   94.183998] 00 
[   94.185921]  [32] 0x100      0000000000000000        0x0
[   94.192589] 6e 
[   94.192590] ee 
[   94.194508] 00 
[   94.196425] a0 
[   94.198345] ff 
[   94.200259] ff 
[   94.202175] ff 
[   94.204076] ff 
[   94.205997]  [33] 0x108      00000000c5189650        bios_VTK_GET_MICROP_ID_null_zero_int+0x0/0x27 [redpill]
[   94.217577] 95 
[   94.217578] ee 
[   94.219494] 00 
[   94.221406] a0 
[   94.223322] ff 
[   94.225234] ff 
[   94.227151] ff 
[   94.229065] ff 
[   94.230983]  [34] 0x110      0000000019375d9f        bios_VTK_SET_MICROP_ID_null_zero_int+0x0/0x27 [redpill]
[   94.242565] 00 
[   94.242566] 00 
[   94.244486] 00 
[   94.246399] 00 
[   94.248315] 00 
[   94.250227] 00 
[   94.252143] 00 
[   94.254056] 00 
[   94.255965]  [35] 0x118      0000000000000000        0x0
[   94.262627] 00 
[   94.262628] 00 
[   94.264545] 00 
[   94.266456] 00 
[   94.268373] 00 
[   94.270284] 00 
[   94.272200] 00 
[   94.274113] 00 
[   94.276030]  [36] 0x120      0000000000000000        0x0
[   94.282685] 00 
[   94.282685] 00 
[   94.284603] 00 
[   94.286509] 00 
[   94.288428] 00 
[   94.290341] 00 
[   94.292257] 00 
[   94.294168] 00 
[   94.296088]  [37] 0x128      0000000000000000        0x0
[   94.302752] 00 
[   94.302753] 00 
[   94.304667] 00 
[   94.306580] 00 
[   94.308495] 00 
[   94.310409] 00 
[   94.312326] 00 
[   94.314244] 00 
[   94.316162]  [38] 0x130      0000000000000000        0x0
[   94.322823] 00 
[   94.322823] 00 
[   94.324741] 00 
[   94.326656] 00 
[   94.328570] 00 
[   94.330485] 00 
[   94.332398] 00 
[   94.334314] 00 
[   94.336226]  [39] 0x138      0000000000000000        0x0
[   94.342885] b0 
[   94.342886] d3 
[   94.344799] 49 
[   94.346714] a0 
[   94.348627] ff 
[   94.350543] ff 
[   94.352459] ff 
[   94.354372] ff 
[   94.356297]  [40] 0x140      00000000e41893b7        GetCPUInfo+0x0/0x70 [epyc7002_synobios]
[   94.366359] 00 
[   94.366359] 00 
[   94.368266] 00 
[   94.370176] 00 
[   94.372094] 00 
[   94.374005] 00 
[   94.375918] 00 
[   94.377823] 00 
[   94.379741]  [41] 0x148      0000000000000000        0x0
[   94.386400] 00 
[   94.386401] 00 
[   94.388312] 00 
[   94.390228] 00 
[   94.392141] 00 
[   94.394057] 00 
[   94.395975] 00 
[   94.397891] 00 
[   94.399808]  [42] 0x150      0000000000000000        0x0
[   94.406462] 90 
[   94.406462] 4b 
[   94.408378] 00 
[   94.410291] a0 
[   94.412207] ff 
[   94.414118] ff 
[   94.416035] ff 
[   94.417953] ff 
[   94.419874]  [43] 0x158      000000002f3cd437        bios_hwmon_get_fans_rpm+0x0/0x110 [redpill]
[   94.430323] 20 
[   94.430324] d4 
[   94.432236] 49 
[   94.434153] a0 
[   94.436075] ff 
[   94.437987] ff 
[   94.439901] ff 
[   94.441814] ff 
[   94.443734]  [44] 0x160      0000000036abfc94        EPYC7002GetPSUStatusByI2C+0x0/0x40 [epyc7002_synobios]
[   94.455220] 60 
[   94.455220] 4a 
[   94.457133] 00 
[   94.459050] a0 
[   94.460963] ff 
[   94.462876] ff 
[   94.464789] ff 
[   94.466702] ff 
[   94.468625]  [45] 0x168      00000000103e34b5        bios_hwmon_get_voltages+0x0/0x130 [redpill]
[   94.479074] 10 
[   94.479075] 48 
[   94.480995] 00 
[   94.482906] a0 
[   94.484820] ff 
[   94.486736] ff 
[   94.488648] ff 
[   94.490566] ff 
[   94.492482]  [46] 0x170      00000000bfc9cb4e        bios_hwmon_get_hdd_backplane+0x0/0xe0 [redpill]
[   94.503310] 50 
[   94.503310] 49 
[   94.505221] 00 
[   94.507135] a0 
[   94.509051] ff 
[   94.510962] ff 
[   94.512881] ff 
[   94.514802] ff 
[   94.516717]  [47] 0x178      00000000b112f6a9        bios_hwmon_get_thermal+0x0/0x110 [redpill]
[   94.527073] 00 
[   94.527074] 00 
[   94.528991] 00 
[   94.530912] 00 
[   94.532823] 00 
[   94.534740] 00 
[   94.536653] 00 
[   94.538564] 00 
[   94.540483]  [48] 0x180      0000000000000000        0x0
[   94.547139] 00 
[   94.547140] 00 
[   94.549056] 00 
[   94.550969] 00 
[   94.552885] 00 
[   94.554796] 00 
[   94.556714] 00 
[   94.558627] 00 
[   94.560539]  [49] 0x188      0000000000000000        0x0
[   94.567203] 00 
[   94.567203] 00 
[   94.569113] 00 
[   94.571030] 00 
[   94.572943] 00 
[   94.574859] 00 
[   94.576782] 00 
[   94.578704] 00 
[   94.580616]  [50] 0x190      0000000000000000        0x0
[   94.587284] 00 
[   94.587284] 00 
[   94.589198] 00 
[   94.591113] 00 
[   94.593025] 00 
[   94.594943] 00 
[   94.596864] 00 
[   94.598777] 00 
[   94.600693]  [51] 0x198      0000000000000000        0x0
[   94.607357] 00 
[   94.607358] 00 
[   94.609274] 00 
[   94.611185] 00 
[   94.613103] 00 
[   94.615016] 00 
[   94.616932] 00 
[   94.618854] 00 
[   94.620776]  [52] 0x1a0      0000000000000000        0x0
[   94.627435] 
[   94.629058] <redpill/bios_shims_collection.c:117> Finished printing memory at 0000000077985bb3
[   94.638429] <redpill/bios_shim.c:128> epyc7002_synobios BIOS *fully* shimmed
[   94.818497] i40e 0000:02:00.0 eth2: set new mac address 7e:21:36:3b:cd:5b
[   94.833656] i40e 0000:02:00.1 eth3: set new mac address 7e:21:36:3b:cd:7b
[   97.927085] igb 0000:06:00.0 eth0: igb: eth0 NIC Link is Up 1000 Mbps Full Duplex, Flow Control: None
[   99.578556] <redpill/intercept_execve.c:96> Blocked /usr/syno/bin/syno_pstore_collect from running
[  105.945146] <redpill/pmu_shim.c:310> Got 1 bytes from PMU: reason=1 hex={2d} ascii="-"
[  106.094308] <redpill/pmu_shim.c:310> Got 1 bytes from PMU: reason=1 hex={33} ascii="3"
[  106.102933] <redpill/pmu_shim.c:239> Executing cmd OUT_BUZ_LONG handler 000000008efc5c5d
[  106.111736] <redpill/pmu_shim.c:45> vPMU received OUT_BUZ_LONG using 1 bytes - NOOP
[  106.243528] <redpill/pmu_shim.c:310> Got 1 bytes from PMU: reason=1 hex={2d} ascii="-"
[  106.392687] <redpill/pmu_shim.c:310> Got 1 bytes from PMU: reason=1 hex={34} ascii="4"
[  106.401313] <redpill/pmu_shim.c:239> Executing cmd OUT_PWR_LED_ON handler 000000008efc5c5d
[  106.410309] <redpill/pmu_shim.c:45> vPMU received OUT_PWR_LED_ON using 1 bytes - NOOP
[  106.542424] <redpill/pmu_shim.c:310> Got 1 bytes from PMU: reason=1 hex={2d} ascii="-"
[  106.691582] <redpill/pmu_shim.c:310> Got 1 bytes from PMU: reason=1 hex={6b} ascii="k"
[  106.700303] <redpill/pmu_shim.c:234> Unknown 1 byte PMU command with signature hex="6b" ascii="k"
[  106.894629] <redpill/pmu_shim.c:310> Got 1 bytes from PMU: reason=1 hex={2d} ascii="-"
[  107.043795] <redpill/pmu_shim.c:310> Got 1 bytes from PMU: reason=1 hex={6b} ascii="k"
[  107.052423] <redpill/pmu_shim.c:234> Unknown 1 byte PMU command with signature hex="6b" ascii="k"
[  107.193520] <redpill/pmu_shim.c:310> Got 1 bytes from PMU: reason=1 hex={2d} ascii="-"
[  107.342681] <redpill/pmu_shim.c:310> Got 1 bytes from PMU: reason=1 hex={6b} ascii="k"
[  107.351303] <redpill/pmu_shim.c:234> Unknown 1 byte PMU command with signature hex="6b" ascii="k"
[  107.492525] <redpill/pmu_shim.c:310> Got 1 bytes from PMU: reason=1 hex={2d} ascii="-"
[  107.641683] <redpill/pmu_shim.c:310> Got 1 bytes from PMU: reason=1 hex={6b} ascii="k"
[  107.641947] <redpill/bios_shims_collection.c:58> mfgBIOS: nullify zero-int for VTK_SET_PHY_LED
[  107.650306] <redpill/pmu_shim.c:234> Unknown 1 byte PMU command with signature hex="6b" ascii="k"
[  107.669355] <redpill/bios_shims_collection.c:59> mfgBIOS: nullify zero-int for VTK_SET_HDD_ACT_LED
[  107.828399] <redpill/pmu_shim.c:310> Got 1 bytes from PMU: reason=1 hex={2d} ascii="-"
[  107.977564] <redpill/pmu_shim.c:310> Got 1 bytes from PMU: reason=1 hex={3b} ascii=";"
[  107.977697] <redpill/memory_helper.c:17> Disabling memory protection for page(s) at 00000000dea5f9f8+12/1 (<<0000000027e85f0a)
[  107.986189] <redpill/pmu_shim.c:239> Executing cmd OUT_STATUS_LED_PULSE_ORANGE handler 000000008efc5c5d
[  107.986190] <redpill/pmu_shim.c:45> vPMU received OUT_STATUS_LED_PULSE_ORANGE using 1 bytes - NOOP
[  108.018637] <redpill/override_symbol.c:249> Obtaining lock for <00000000dea5f9f8/00000000dea5f9f8>
[  108.028406] <redpill/override_symbol.c:249> Writing original code to <00000000dea5f9f8>
[  108.038490] <redpill/override_symbol.c:249> Released lock for <00000000dea5f9f8>
[  108.046554] <redpill/override_symbol.c:220> Obtaining lock for <00000000dea5f9f8/00000000dea5f9f8>
[  108.056308] <redpill/override_symbol.c:220> Writing trampoline code to <00000000dea5f9f8>
[  108.065216] <redpill/override_symbol.c:220> Released lock for <00000000dea5f9f8>
[  108.073270] <redpill/bios_hwcap_shim.c:65> proxying GetHwCapability(id=2)->support => real=1 [org_fout=0, ovs_fout=0]
[  108.249556] ext3: synoboot1 mounted, process=mount
[  108.256605] ext4: synoboot1 mounted, process=mount
[  108.262845] ext2: synoboot1 mounted, process=mount
[  108.271660] vfat: synoboot1 mounted, process=mount
[  108.411475] synoboot1 unmounted, process=umount
[  217.299910] ext2: synoboot2 mounted, process=mantool
[  217.310556] ext2 filesystem being mounted at /tmp/bootmnt supports timestamps until 2038 (0x7fffffff)
[  217.323506] synoboot2 unmounted, process=mantool
[  673.995625] scsi 0:2:3:0: Direct-Access     HGST     HUH721008AL5200          A21D PQ: 0 ANSI: 6
[  674.006755] <redpill/scsi_notifier.c:65> Probing SCSI device using sd_probe_shim
[  674.014820] <redpill/scsi_notifier.c:77> Triggering SCSI_EVT_DEV_PROBING notifications
[  674.023456] <redpill/scsi_notifier.c:87> Calling original sd_probe()
[  674.030394] sd 0:2:3:0: sd_probe: unknown type 0.
[  674.035538] <redpill/scsi_notifier.c:91> Triggering SCSI_EVT_DEV_PROBED notifications - sd_probe() exit=-22
[  674.046150] sd: probe of 0:2:3:0 failed with error -22
[  676.414800] scsi 0:2:4:0: Direct-Access     HGST     HUH721008AL5200          A21D PQ: 0 ANSI: 6
[  676.425991] <redpill/scsi_notifier.c:65> Probing SCSI device using sd_probe_shim
[  676.434065] <redpill/scsi_notifier.c:77> Triggering SCSI_EVT_DEV_PROBING notifications
[  676.442692] <redpill/scsi_notifier.c:87> Calling original sd_probe()
[  676.449616] sd 0:2:4:0: sd_probe: unknown type 0.
[  676.454762] <redpill/scsi_notifier.c:91> Triggering SCSI_EVT_DEV_PROBED notifications - sd_probe() exit=-22
[  676.465348] sd: probe of 0:2:4:0 failed with error -22
[  679.988891] scsi 0:2:5:0: Direct-Access     HGST     HUH721008AL5200          A21D PQ: 0 ANSI: 6
[  680.000423] <redpill/scsi_notifier.c:65> Probing SCSI device using sd_probe_shim
[  680.008486] <redpill/scsi_notifier.c:77> Triggering SCSI_EVT_DEV_PROBING notifications
[  680.017118] <redpill/scsi_notifier.c:87> Calling original sd_probe()
[  680.024064] sd 0:2:5:0: sd_probe: unknown type 0.
[  680.029204] <redpill/scsi_notifier.c:91> Triggering SCSI_EVT_DEV_PROBED notifications - sd_probe() exit=-22
[  680.039822] sd: probe of 0:2:5:0 failed with error -22
[  682.176083] scsi 0:2:6:0: Direct-Access     HGST     HUH721008AL5200          A21D PQ: 0 ANSI: 6
[  682.187308] <redpill/scsi_notifier.c:65> Probing SCSI device using sd_probe_shim
[  682.195364] <redpill/scsi_notifier.c:77> Triggering SCSI_EVT_DEV_PROBING notifications
[  682.203980] <redpill/scsi_notifier.c:87> Calling original sd_probe()
[  682.210928] sd 0:2:6:0: sd_probe: unknown type 0.
[  682.216066] <redpill/scsi_notifier.c:91> Triggering SCSI_EVT_DEV_PROBED notifications - sd_probe() exit=-22
[  682.226685] sd: probe of 0:2:6:0 failed with error -22
[  686.102011] scsi 0:2:7:0: Direct-Access     HGST     HUH721008AL5200          A21D PQ: 0 ANSI: 6
[  686.113194] <redpill/scsi_notifier.c:65> Probing SCSI device using sd_probe_shim
[  686.121265] <redpill/scsi_notifier.c:77> Triggering SCSI_EVT_DEV_PROBING notifications
[  686.129887] <redpill/scsi_notifier.c:87> Calling original sd_probe()
[  686.136822] sd 0:2:7:0: sd_probe: unknown type 0.
[  686.141959] <redpill/scsi_notifier.c:91> Triggering SCSI_EVT_DEV_PROBED notifications - sd_probe() exit=-22
[  686.152573] sd: probe of 0:2:7:0 failed with error -22
SynologyNAS> 


