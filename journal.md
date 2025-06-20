
# Journal – Building **Keyverse 60** PCB
**By CodewMilan** | Part of the **Highway Series**

---

## June 17, 2025 — learning( cus i didnt know lol)
- Decided to embark on designing a **custom 60-key ortholinear keyboard PCB**.
- Spent the day **watching YouTube tutorials** on PCB design for mechanical keyboards.
  - Topics covered: matrix wiring, diode placement, microcontroller pin assignments, and designing footprints.
- Installed **KiCad** and explored open-source keyboard projects for reference.
- Sketched the **5×12 ortholinear layout** for the Keyverse 60.

---

## June 18, 2025 — finished schematic
- Created the schematic in KiCad:
  - Added **ATmega32u4 (Pro Micro)** as the controller.
  - Added **60 diodes (1N4148)** for per-key protection.
  - Laid out the **row and column matrix** for the ortholinear configuration.
- Verified connections by cross-checking with reference builds from QMK documentation.
- First draft of the schematic completed.

---

## June 19 did the pcb layout
- Switched to **PCB layout editor** in KiCad.
- Arranged the key switch footprints in the 5×12 ortholinear grid.
- Added **Kailh hot-swap socket** footprints.
- Carefully routed traces for all rows and columns, ensuring no conflicts or overlaps.
- Verified DRC (Design Rule Check) for errors—resolved a few minor net conflicts.
- Finalized USB-C footprint for the Pro Micro.

---

## June 20 finally done !!!!
- Finalized silkscreen with the **Keyverse 60** name and **Highway Series** branding.
- Exported **Gerber files**.
- imported it into easyeda to ease ordering process.
- Uploaded files to **JLCPCB** for manufacturing.
- Submitted the **Keyverse 60** entry to the **Highway Form** for community showcase.
- Feeling proud of completing my **first fully custom keyboard PCB design**.


