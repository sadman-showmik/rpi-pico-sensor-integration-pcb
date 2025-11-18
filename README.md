# Raspberry Pi Pico Sensor Integration PCB

This repository contains the KiCAD schematic and PCB layout files for a custom PCB designed for the **Raspberry Pi Pico** to interface multiple sensors and support modules.  
All footprints, 3D models, and component references follow the verified Bill of Materials (BOM) shared earlier.

---

## 📌 Features

- Raspberry Pi Pico socket interface  
- INA180A1 current-sense amplifier  
- MCP9701T temperature sensor  
- Protection diode (PMEG3050EP)  
- Multiple connectors (Harting & Amphenol)  
- Status LEDs  
- Precision resistors & trimmer potentiometer  
- Test points for measurement and debugging  

---

## 📁 Repository Contents

- KiCAD schematic (`.sch`) + PCB layout (`.kicad_pcb`)  
- Gerber manufacturing files  
- Datasheet links (`.md`)  
- Complete component list (BOM)  
- Optional firmware/examples for sensor testing  

---

## 🧱 Component List (BOM Overview)

A full CSV is included in `/docs/component_list.csv`. Components include (all verified):

- **Capacitors**: C1206C104K5RAC7210  
- **Diode**: PMEG3050EP,115  
- **Amplifier**: INA180A1IDBVR  
- **Temperature sensor**: MCP9701T-E_TT  
- **Raspberry Pi Pico socket**  
- **LEDs**: 156120VS75000  
- **Resistors**: RMCF1206, RMC1_8331JT, CRM1206AFX series  
- **Trimmer potentiometer**: 3314J-2-103E  
- **Switch**: JS102011SCQN  
- **Connectors**: Harting & Amphenol  

---

## 📄 Datasheets

All datasheet links are available in `/docs/datasheet_links.md`.

---

## 🚀 Getting Started

1. Open the `.sch` and `.kicad_pcb` files in KiCAD.  
2. Review PCB layers, footprints, and component placement.  
3. Export Gerber and drill files using KiCAD’s Plot tool.  
4. Manufacture and assemble the PCB.  
5. Use `/test_code` examples for basic sensor testing and verification.

---

## 📦 Recommended Files to Include

To complete the repository, include:

1. **KiCAD project files**:  
   - `.sch`  
   - `.kicad_pcb`  
   - `.kicad_pro`  
   - `.kicad_sch` (if using KiCAD v7+)  
   - Custom symbol/footprint libraries (if any)

2. **PDF exports**:  
   - Schematic PDF  
   - PCB top & bottom layer images

3. **BOM CSV**  
   - `/docs/component_list.csv` (already prepared from your table)

4. **Datasheet links file**  
   - `/docs/datasheet_links.md` (ready-to-upload)

---

## 👤 Author

**B M Sadman Showmik**  
Email: sadman.showmik@metropolia.fi
