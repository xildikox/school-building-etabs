# 🏫 School Building Structural Analysis – CE 482 Final Project

This repository contains the ETABS-based structural analysis of a reinforced concrete school building completed as part of the **CE 482 – Computational Structural Analysis and Design** course at Abdullah Gül University.

## 📌 Project Scope

- 3D finite element modeling of a school building using **ETABS**
- Seismic data input based on **AFAD Earthquake Hazard Map** for Elazığ, Turkey
- Modal analysis and response spectrum analysis
- Parametric studies on structural section sizes and their impact on dynamic response

## 🛠️ Tools Used

- **ETABS v22.5.1** for modeling and analysis  
- **AFAD TDTH** for seismic parameters  
- **MS Word** for report preparation  

## 📐 Key Modeling Details

- Concrete: **C30** (E = 32,500 MPa)  
- Steel: **B420S** (fy = 420 MPa)  
- Beams: 30x60 cm, Columns: 40x40 / 50x40 cm  
- Slab thickness: 15 cm  
- Soil Class: **ZD**, SDS = 1.000, SD1 = 0.517  
- Story height adjusted to: **Z - 0.4 m** (as per assignment instructions)  

## 📊 Analysis Summary

- **Modal analysis**: 1st mode period ≈ 0.253 s  
- **Response spectrum**: Based on AFAD coefficients with 5% damping  
- **Parametric impact**: Increasing column sizes → decreased period (higher stiffness)  
- Slab and beam changes had minor effect on modal behavior  

## 📁 Files

- `CE482_Elif_Arslan_Final`: ETABS model file  
- `School Building Report.docx`: Final report with figures and analysis  

## 📚 References

- Turkish Earthquake Code (2018)  
- TS500, TS498  
- [AFAD Seismic Map](https://tdth.afad.gov.tr)  
- ETABS v22.5.1 User Manual  
