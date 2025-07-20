# Design and Simulation of Sub-THz PBG-Based Circular Slot Antenna  
### For Satellite Communication and Biomedical Applications

---

## **Project Overview**

This repository presents the **design, simulation, and analysis** of a **Sub-Terahertz (THz) Circular-Slot Microstrip Antenna integrated with a Photonic Band Gap (PBG) substrate**.  
The antenna serves a **dual-purpose application**:

- **Satellite Communication** (High-data-rate, sub-THz links)  
- **Biomedical Diagnostics** (Breast Cancer Detection using THz Sensing)

The design targets efficient operation in the **140–150 GHz band**, ensuring high gain, minimal reflection, and surface wave suppression via the PBG structure.

---

## **Key Specifications**

| **Parameter**               | **Value**             |
|----------------------------|-----------------------|
| Operational Frequency       | ~147 GHz (Sub-THz)    |
| Reflection Coefficient (S11)| -51.041 dB            |
| VSWR                        | 1.0007                |
| Peak Gain                   | 8.68 dBi              |
| Substrate                   | Polyimide (εr = 3.5)  |
| PBG Structure               | Cuboidal air holes, 0.613 mm lattice |

---

## **Features**

- **Compact Circular-Slot Patch Design**  
- **Photonic Band Gap (PBG) Substrate** for surface wave suppression  
- **MATLAB-based Bandgap Optimization**  
- **CST Microwave Studio Simulations** for S11, gain, and field analysis  
- **Biomedical Testing**: Breast tissue model for cancer detection  
- **Satellite Application**: Suitable for nanosatellite payloads  

---

### **1. Analytical Modeling**

- Calculated patch dimensions using standard microstrip formulas  
- Designed cuboidal air holes for PBG implementation

### **2. Bandgap Analysis (MATLAB)**

- Optimized **lattice constant (a = 0.613 mm)**  
- Ensured photonic bandgap covers **140–150 GHz**

### **3. CST Simulation Iterations**

- **Rectangular patch → Circular patch → Circular slot loading**  
- Added **dual circular slots** for dual-mode resonance  
- **PBG integration** around patch for wave suppression  
- Final design achieved optimal gain and impedance matching

### **4. Biomedical Validation**

- Simulated antenna interaction with **3D breast tissue model**  
- Monitored S11 and gain variations to detect cancerous tissues  

---

## **Applications**

### **1. Satellite Communication**

- High data-rate, short-range THz communication  
- Integration in **nanosatellites** and **CubeSats**

### **2. Biomedical Diagnostics**

- **Non-invasive breast cancer detection**  
- Sensitive to dielectric changes in biological tissues

---

## **Future Scope**

- **Fabrication & Experimental Validation**  
- **Phased Array Design** for beam steering  
- **Reconfigurable Antennas** with tunable materials (Graphene, MEMS)  
- **Wearable Medical Devices** using flexible substrates  
- **Integration in LEO Satellites** for sub-THz payload systems  

---


## **References**

1. C. A. Balanis, *Antenna Theory: Analysis and Design*, Wiley, 2005.  
2. S. Thakur and N. Singh, "Circular-slot THz antenna on PBG substrate for satellite communication," *Optik*, vol. 242, pp. 167–176, 2021.  
3. H. F. Zhang, "2D-fractal plasma photonic crystals with Fibonacci sequence," *AIP Advances*, 2017.  
4. Y. D. Sirmaci et al., "Fishnet based metamaterial THz patch antenna," *Optical and Quantum Electronics*, 2016.  
5. Custom MATLAB scripts developed in this project, IIIT Nagpur, 2025.

---



