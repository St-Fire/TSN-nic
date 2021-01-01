# TSN NIC

+ ### PCIE-0400-TSN
	+ **kontron**
		+ https://www.kontron.com/products/systems/ethernet-solutions/network-interfaces-tsn/pcie-0400-tsn-network-interface-card.html
	+ ## hardware
	+ **INTERFACES**
		+ 4 port 10/100/1000 Ethernet, RJ45
Host Interface PCIe Gen 1 x4
LEDs for Link, Speed, activity
	+ **EMC**
		+ EN55022 class B
	+ **SHOCK**
	+ **BOARD SIZE**
	+ **BRACKET OPTIONS**
		+ Standard and low profi le, 2 and 4 ports
	+ **MOUNTING**
		+ PCIe Interface card
	+ **ALTITUDE**
	+ **VIBRATION,CCORDING TO EN 60068-2-6**
		+ 10-500 Hz: 1G/3 axis (tbc)
	+ **OPERATING TEMPERATURE**
	+ **HUMIDITY**
	+ **MTBF**
		+  50.000 h (tbc)
	+ ## software
	+ **PROCESSOR** 
		+ Intel® Cyclone V, fi eld upgradeable
	+ SWITCH OPERATION 
		+ Cut through, StoreAndForward
	+ **SOFTWARE SUPPORT**
		+ Linux Kernel device drivers, TSN Software stacks
	+ **VERIFIED OS**
		+ Linux
	+ **SUPPORTED TSN STANDARDS IEEE-802.1 TSN**
		+ 802.1 as(rev): timing and synchronization
   		+ 802.1 Qbv: traffic scheduling
  		+ 802.1 Qbu: frame preemption
   		+ 802.1 Qcc: Stream Reservation Protocol enhancements
   		+ 802.1 CB, Qci, …: N/A – will be provided per update
---

+ ### AXM57104
	+ **Asix** 
		+ https://www.asix.com.tw/en/product/IndustrialEthernet/TSN/AXM57104
	+ ## hardware
	+ **Compliant to PCI Express base spec. v2.1 Gen1**
	+ **PCIe Network Interface Controller (NIC)**
		+ Gigabit Ethernet Network Interface Controller
          Ethernet packet through Bus-Master DMA
          Unicast/multicast/broadcast filters
          Support Legacy and MSI interrupt
	+ **32 Synchronous I/O pins and one I2C master**
	+ **One Pulse Per Second (PPS) output**
	+ **Support PCI Express x1 slot, Standard profile bracket**
	+ **Operating Temperature Range: -40 to +85°C**
	+ ##software
	+ **TSN Gigabit Ethernet Switch**
		+ Support TSN Timing and Synchronization for Time-Sensitive
Applications compliant to IEEE 802.1AS-Rev/AS, and IEEE
1588V2
		+ Support TSN Forwarding and Queuing of Time Sensitive
Streams (FQTSS) : Specifies Credit-Based Shaper (CBS)
compliant to IEEE 802.1Qav
		+ Support TSN Time-Aware Shaper (TAS) compliant to IEEE
802.1Qbv
		+ Support TSN Per-Stream Filtering and Policing (PSFP)
compliant to IEEE 802.1Qci
		+ 4 Gigabit Ethernet SGMII interfaces
		+ Port-based and 802.1Q tag-based VLANs
		+ Support 8 priority queues
		+ QoS according to the PCP bits (802.1p), or Ethertype
		+ Support Independent VLAN Learning (IVL)
		+ DSA (Distributed Switch Architecture) for frame tagging
		+ Shared Dynamic and Static MAC Table (4096 entries),Automatic MAC addresses learning and ageing
		+ Broadcast storm protection and multicast frames filtering
		+ Per-port Frame rate limiting and Frame/Error counters
		+ 16 Kbytes packet buffer per port
	+ **FPGA hard-core field upgradable via In Application Programming (IAP) for TSN standards evolution**
	+ **Support Board Support Package (BSP)**
	+ **Target Applications**
		+ Enable TSN on Industrial Automation Platforms
          Fieldbus over TSN Gateway
          Converge IT & OT Networks
---
+ ### RELY-TSN-PCIe
	+ **Relyum**
		+ https://www.hkaco.com/embeded/relyum/products/RELY-PCIe-NIC-Family/rely-tsn-lp-pcie.html
	+ ## hardware
	+ **Communication**
		+  2x Ethernet port 
		+ Media options (SFP cages):
			+ 10/100/1000Base-T
			+ 1000Base-X
			+ 100Base-FX • RSTP IEEE802.1w
	+ **Processing performance**
		+ On-board UltraScale™ FPGA for high-speed network switching
	+ ## software
	+ **Communication**
		+ LLDP support 
		+ VLAN support 
		+ Ethernet type based or IEEE 802.1P Traffic
prioritization 
		+ 1 PPS output  
		+ PCIex1. Seamless integration on old Legacy PCI
Systems through optional adapter
	+ **TSN features**
		+ IEEE 802.1AS - Timing and Synchronization 
		+ IEEE 802.1Qbv - Enhancements for Scheduled Traffic 
		+ IEEE 802.1Qav - Forwarding and Queuing
Enhancements for Time-Sensitive Streams 
		+ IEEE 802.1Qcc – Enhancements for Stream Reservation Protocol 
		+ IEEE 802.1Qci* – Per-Stream Filtering and Policing 
		+ IEEE 802.1CB* – Frame Replication and Elimination for Reliability 
		+ IEEE 802.1Qbu* & IEEE 802.3br* – Frame Replication and Elimination for Reliability
	+ **Software features**
		+  Ethernet network drivers available for most OS:
			+ Linux, Windows, VxWorks, etc.
	+ **Processing performance**
		+ PTP timestamping 
		+ Multi-core CPU unit to support autonomous software
applications
	+ **Configuration and Management**
		+  SNMPv3, SSH, Netconf support
		+ Accessible through HTTP(S)
		+ Configuration profiles and Firmware updates
		+ Real-time network monitoring
