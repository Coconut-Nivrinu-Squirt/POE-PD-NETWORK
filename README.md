# Power Over Ethernet network adapter with type C power Delivery Ciurcit
[![Firmware License](https://img.shields.io/badge/Firmware%20License-EUPL%201.2-blue)](https://interoperable-europe.ec.europa.eu/node/143855)
[![Hardware License](https://img.shields.io/badge/Hardware%20License-CERN--OHL--S%20v2-orange)](https://cern-ohl.web.cern.ch/)
[![OSHWA Certification](https://img.shields.io/badge/OSHWA%20Certification-PENDING-red)](https://certification.oshwa.org/)

## Legal and Licensing Architecture

This is a hardware-primary open-source project utilizing a strict dual-license architecture to protect both the physical board design and the firmware blobs.

*   **Hardware Design:** All physical design files, CAD models, schematics, and PCB layouts are licensed under the **CERN Open Hardware Licence Version 2 - Strongly Reciprocal (CERN-OHL-S v2)**.
*   **Firmware & Software:** All source code, firmware, and software required to operate this hardware (located in the `/firmware` directory) are licensed under the **European Union Public License v1.2 (EUPL-1.2)**.
*   **Provenance:** The Open Source Hardware (OSHW) gear logo and pending OSHWA UID (`OSHWA UID: [PENDING]`) act as physical marks of original provenance. **Use of theese marks in your product constitutes a commitment to open sourcing your derivative work!!!** 

See the root `LICENSE` file and the `LICENSES/` directory for full unmodified legal texts.

# Project Source credits
Some footprints and symbols in this project are sourced under fair use terms from [Ultra Librarian](https://www.ultralibrarian.com/)

*this project is a work in progress. Things may update randomly!*
### This is an Open source project intended to let you build your own combination Power delivery Source With a network adapter.
|Supported power source type | Voltages supplied | Source |
| ------------ | -------------- | -------------- |
| External Power Supply | 5VDC, 3.3VDC, 25VDC | 5 pin Screw lock plug of choice |
| Internal Power Supply | 5VDC, 3.3VDC, 25VDC | POE power source curcitry |
| USB OTG Power Supply | 5VDC, 3.3VDC | Vbus - Sourced from attached device |

