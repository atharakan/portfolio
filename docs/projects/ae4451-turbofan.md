# Afterburning Turbofan Engine Design & Optimization

**Course:** AE 4451 – Jet & Rocket Propulsion  
**Term:** Fall 2025  
**Project Type:** Team-based engine cycle design and optimization  
**Engine Type:** Afterburning turbofan with combined nozzle

---

## Overview
Developed a full thermodynamic cycle model for an air-breathing turbine engine and optimized its performance across two flight regimes: static ground roll and high-altitude subsonic cruise. The final configuration balances thrust capability, fuel efficiency, and operational flexibility using a unified engine architecture.

---

## Engine Configuration
- **Architecture:** Afterburning turbofan, combined exhaust nozzle  
- **Compressor pressure ratio:** ≈ **40**  
- **Fan pressure ratio:** ≈ **1.3**  
- **Bypass ratio:** ≈ **5.0**  
- **Bleed air modeled:** Yes  
- **Afterburner modeled:** Yes  

This single hardware configuration satisfies both takeoff and cruise requirements using only throttle-level adjustments.

---

## My Contributions
- Developed component-level thermodynamic cycle equations  
- Implemented full engine model in MATLAB  
- Modeled diffuser, fan, compressor, combustor, turbines, mixer, and nozzle  
- Validated model against provided test cases (<5% error)  
- Performed genetic-algorithm optimization for efficiency and thrust  

---

## Key Analyses
- Cycle modeling of turbofan, turbojet, and ramjet configurations  
- Combined-nozzle performance modeling and comparison  
- Genetic-algorithm optimization of:
  - Compressor and fan pressure ratios  
  - Bypass ratio  
  - Fuel-to-air and afterburner fuel ratios  
  - Bleed fraction  
- Separate optimization for:
  - **Maximum efficiency**
  - **Maximum thrust**

---

## Optimized Performance (Combined Nozzle)

### Maximum Efficiency Configuration
- **Specific thrust (ground roll):** ~2.77 kN·s/kg  
- **Specific thrust (cruise):** ~2.25 kN·s/kg  
- **TSFC (ground roll):** ~0.009 kg/kN·s  
- **TSFC (cruise):** ~0.020 kg/kN·s  

### Maximum Thrust Configuration
- **Specific thrust (ground roll):** ~6.25 kN·s/kg  
- **Specific thrust (cruise):** ~4.41 kN·s/kg  
- Demonstrates substantial thrust margin beyond mission requirements

---

## Results
- Single engine configuration meets thrust requirements at both flight regimes  
- Optimization favored high compressor ratio and moderate bypass ratio  
- Combined nozzle selected for improved accuracy and compactness  
- Engine demonstrates strong efficiency–thrust trade capability  
- Design reflects realistic characteristics of modern turbofan engines :contentReference[oaicite:1]{index=1}

---

## Tools
- MATLAB (cycle modeling, optimization, genetic algorithms)  
- Thermodynamic property tables  
- Analytical propulsion equations  
- LaTeX (final report)

---

## Links
- **Final Technical Report (PDF):** Available upon request  
- **MATLAB Code:** Available upon request
