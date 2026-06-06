# Universal 1S-4S Battery Capacity Indicator 🔋

A highly compact, hardware-selectable Lithium-Polymer battery indicator designed for custom FPV drones and edge-computing robotics. 

This project aims to completely eliminate the parasitic battery drain common in off-the-shelf modules while maintaining an ultra-small physical footprint.

### 📐 Engineering Constraints
* **Physical Footprint:** 20mm x 15mm.
* **Power Budget:** Quiescent current strictly under 5mA.
* **Logic Threshold:** Exact hardware crossover at 3.70V per cell (20% capacity "cliff").

### ⚡ System Architecture
The system operates entirely in the analog domain, ensuring zero software latency.
* **Logic Engine:** Utilizes the TLV7031 nanopower push-pull comparator (drawing 300nA).
* **Power Regulation:** HT7533-1 LDO (SOT-89 package for thermal efficiency up to 16.8V).
* **Routing:** 22 surface-mount components routed on a single top layer (F.Cu) utilizing a bottom-layer (B.Cu) ground pour and stitched vias.


**Plasmon Dhal**
EEE
ABV-IIITM
