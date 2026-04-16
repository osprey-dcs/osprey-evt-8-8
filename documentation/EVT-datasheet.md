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
| Depth | <span style="color:red">445 mm |
| Communication | 1Gbps Ethernet, RJ45 |
| Power Input Voltage | 12 VDC into 2 contact |
| Number of Digital Channels | 8 Inputs, 8 Outputs per chassis |
| Digital Inputs | 8x SMA connecters; 50k ohm input impedance; TTL capable |
| Digital Outputs | 8x SMA connecters; 50ohm drive capable; LVTTL; short circuit safe |
| Channel to Channel Jitter | < 20pSec RMS |

## Absolute Maximums

| Specification | Minimum | Maximum |
| ---- | ---- | ---- |
| Ambient Temperature | 0 C | 40 C |
| Ambient Humidity | | 90% non-condensing |
| Power Current | | 4A |
| Digital Input abs. voltage | | 6.5V max |
| Digital Output drive current | | 90mA max |
| Event Clock Rate | 50MHz |  250Mhz |
| Event Bitrate | 1Gbps |  5Gbps |
| Number of user configurable events | | 255 |

## Connectors

- 2 contact barrel jack, positive inside.  Cliff Electronics [SCD-026](http://www.farnell.com/datasheets/1859067.pdf)

- Grounding stud

- Ethernet RJ45 UTP

- Timing, 8x LC duplex, multi-mode

- 16x SMA-F

- Micro USB diagnostic serial interface
