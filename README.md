Raspberry Pi Pico Sensor Integration PCB

This repository contains the KiCAD schematic and layout files for a custom PCB designed for Raspberry Pi Pico to interface multiple sensors and support modules.
All footprints, models, and component references follow the exact Bill of Materials (BOM) shared earlier.

📌 Features

Raspberry Pi Pico socket interface

INA180A1 current-sense amplifier

MCP9701T temperature sensor

Protection diode (PMEG3050EP)

Multiple connectors (Harting & Amphenol)

Status LEDs

Precision resistors & trimmer potentiometer

Test points for debugging

📁 Contents

KiCAD schematic + PCB layout

Gerber manufacturing files

Datasheet links

Complete component list

(Optional) Firmware examples for testing

🧱 Component List (BOM Overview)

A full CSV is included in /docs/component_list.csv.

Components include (all verified from your list):

Capacitors: C1206C104K5RAC7210

Diode: PMEG3050EP,115

Amplifier: INA180A1IDBVR

Temperature sensor: MCP9701T-E_TT

Pico socket

LEDs: 156120VS75000

Resistors (RMCF1206, RMC1_8331JT, CRM1206AFX…)

Trimmer potentiometer: 3314J-2-103E

C&K switch: JS102011SCQN

Connectors (Harting, Amphenol)

📄 Datasheets

All links are available in /docs/datasheet_links.md.

🚀 Getting Started

Open the .sch and .kicad_pcb files in KiCAD.

Review PCB layers and footprints

Export Gerbers using KiCAD's plot tool

Manufacture + assemble

Use examples/test_code for basic sensor testing

📞 Author

B M Sadman Showmik

📦 Files You Should Upload

To complete the repo, include:

1. KiCAD files

.sch

.kicad_pcb

.kicad_pro

.kicad_sch (if v7+)

Symbol/footprint libs if custom

2. PDF exports

Schematic PDF

PCB top/bottom layers as images

3. BOM CSV

Already prepared from your table.

4. Datasheet links file

I can generate a ready-to-upload .md file if you want.
