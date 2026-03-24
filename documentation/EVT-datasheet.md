# EVT-8-8 Datasheet

Osprey EVT-8-8 Chassis is a highly scalable EPICS native event & timing system
consisting of one or more 2U 19-inch rack mounted chassis.
Each chassis has 16 timed Digital I/O accessible through SMA connectors.

Multiple chassis may be [connected together](system-setup.md#Topologies) sharing event and timing data.

## Parameters

| Parameter | Value |
| ---- | ---- |
| Height | 2U |
| Width | 19 Inch |
| Depth | <span style="color:red">400 mm?</span> |
| Communication | 1Gbps Ethernet, RJ45 |
| Power Input Voltage | 12 VDC into 2 contact [DC barrel Jack](#PowerInput)[^acdc] |
| Number of Digital Channels | 8 Inputs, 8 Outputs per chassis |
| Digital Inputs | 8x SMA connecters; 50k ohm input impedance |
| Digital Outputs | 8x SMA connecters; 50ohm drive capable; 3.3V Output |
| Channel to Channel Jitter | < 20pSec |

## Absolute Maximums

| Specification | Minimum | Maximum |
| ---- | ---- | ---- |
| Ambient Temperature | 0 C | 40 C |
| Ambient Humidity | | 90% non-condensing |
| Power Input Voltage[^acdc] | 0V DC | 13 VDC |
| Power Current | | 4A |
| Digital Input abs. voltage | | +6.5 V |
| Digital Output Load| 36ohm| |

[^acdc]: 120V AC/DC converter included.


## Connectors

<a name="PowerInput"></a>

- Power Input.

2 contact barrel jack, positive inside.  Cliff Electronics [SCD-026](http://www.farnell.com/datasheets/1859067.pdf)

- Grounding stud

- Ethernet RJ45 UTP

- Timing, 8x LC duplex, multi-mode

- 16x SMA-F

- Pulse Per Second, BNC-F
