# mems-piezoresistive-pressure-sensor
Fabrication and characterization of a MEMS piezoresistive pressure sensor using silicon micromachining, photolithography, ion implantation, metallization, anodic bonding, and device testing.
# Piezoresistive MEMS Pressure Sensor Fabrication and Characterization

## Project Overview

This project documents the fabrication and characterization of a **piezoresistive MEMS pressure sensor** using standard silicon micromachining and cleanroom processing techniques.

The pressure sensor was fabricated on a silicon wafer using oxidation, photolithography, wet etching, boron ion implantation, anodic bonding, aluminum metallization, packaging, and final device testing. The goal was to create a silicon diaphragm-based pressure sensor and verify that the electrical output changes with applied pressure.

This project highlights hands-on experience in MEMS fabrication, semiconductor process flow, wafer-level metrology, device packaging, and electrical characterization.

---

## Objective

The main objectives of this project were to:

- Fabricate a MEMS-based silicon pressure sensor.
- Form a thin silicon diaphragm using anisotropic wet etching.
- Create piezoresistive regions using boron ion implantation.
- Pattern aluminum metal lines for electrical contact.
- Package and test the fabricated pressure sensor.
- Measure the device response under applied pressure.

---

## Starting Material

- 2-inch n-type silicon wafer
- (100) crystal orientation
- <110> flat
- Substrate resistivity: approximately 1–10 Ω·cm

---

## Fabrication Process Flow

### 1. Wafer Cleaning and Field Oxidation

The silicon wafer was cleaned using a Baker cleaning process to remove native oxide, organic contaminants, particles, and metallic contamination.

After cleaning, a silicon dioxide layer was grown using a dry-wet-dry oxidation sequence. This oxide layer served as a masking layer for later etching and patterning steps.

---

### 2. Photolithography for Diaphragm Etch Mask

Photolithography was performed to define the backside diaphragm opening.

Key steps included:

- Wafer cleaning
- HMDS coating for photoresist adhesion
- Positive photoresist coating
- Soft bake
- Mask alignment
- UV exposure
- Development
- Hard bake
- Microscope inspection

This step defined the oxide mask opening for anisotropic silicon etching.

---

### 3. Buffered Oxide Etching

Buffered oxide etch was used to remove the exposed silicon dioxide in the diaphragm region.

This opened the oxide window required for the later TMAH silicon etching process.

---

### 4. TMAH Anisotropic Silicon Etching

TMAH wet etching was used to form the silicon diaphragm structure. The etching process reduced the silicon thickness in the patterned diaphragm region.

The wafer thickness was monitored during the process to track etch progress and diaphragm formation.

---

### 5. Re-Oxidation and Piezoresistor Patterning

After diaphragm etching, the wafer was re-oxidized to grow a new oxide layer.

A second lithography step was used to pattern the piezoresistor regions. Backside alignment was used to align the resistor pattern with the diaphragm region.

---

### 6. Boron Ion Implantation and Annealing

Boron ion implantation was used to form the piezoresistive regions in silicon.

The implanted wafer was then annealed to:

- Activate the implanted boron dopants.
- Repair implantation-induced damage in the silicon crystal.
- Improve electrical behavior of the piezoresistors.

---

### 7. Silicon-Glass Anodic Bonding

The silicon wafer was anodically bonded to a Pyrex glass wafer.

This bonding step supported the diaphragm structure and helped form the final pressure sensor package.

---

### 8. Via Opening

A third lithography step was performed to open vias through the oxide layer. These vias provided access to the piezoresistor regions for metal contact formation.

---

### 9. Aluminum Deposition and Sintering

Aluminum was deposited to form electrical contact pads and metal interconnects.

A sintering step was performed to improve the metal-semiconductor contact quality.

---

### 10. Aluminum Metal Line Patterning

Photolithography and etching were used to define the aluminum metal lines and contact pads.

This step completed the electrical routing required for device testing.

---

### 11. Sheet Resistance Measurement and Packaging

Sheet resistance measurements were performed for both the aluminum layer and piezoresistor regions.

The device was then packaged and prepared for pressure chamber testing.

---

### 12. Device Testing

The fabricated pressure sensor was tested in a pressure chamber. Pressure was applied from 0 psi to 30 psi and then reduced back to 0 psi.

The device output voltage changed with applied pressure, confirming pressure-sensitive behavior.

---

## Key Results

| Parameter | Result |
|---|---|
| Calculated oxide thickness after first oxidation | ~1.152 µm |
| Measured oxide thickness after field oxidation | ~1.096–1.099 µm |
| Average wafer thickness after TMAH etching | ~138 µm |
| Boron implantation energy | 50 keV |
| Boron implantation dose | 8 × 10¹⁴ atoms/cm² |
| Aluminum sheet resistance | ~0.126 Ω/sq |
| Piezoresistor sheet resistance | ~214.947 Ω/sq |
| Pressure test range | 0–30 psi |
| Output at 30 psi | ~145.97 mV |
| Pressure sensitivity | ~4.86 mV/psi |

---

## Skills Demonstrated

- MEMS pressure sensor fabrication
- Silicon wafer cleaning
- Thermal oxidation
- Photolithography
- Mask alignment
- BOE oxide etching
- TMAH anisotropic silicon etching
- Boron ion implantation
- Annealing and dopant activation
- Silicon-glass anodic bonding
- Via opening
- Aluminum deposition
- Metal line patterning
- Sheet resistance measurement
- Device packaging
- Pressure sensor testing
- Cleanroom process documentation
- Process troubleshooting and inspection

---


---

## Project Report

The full project report is available here:

[View Full Report](Reports/Piezoresistive_Pressure_sensor_Project_Report.pdf)

---

## Notes

This repository is intended as a technical portfolio summary of a MEMS microfabrication laboratory project.

All chemical handling and cleanroom processing must follow official cleanroom safety protocols, equipment training, and supervisor instructions.
