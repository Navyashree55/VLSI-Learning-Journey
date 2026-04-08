##  Channel Length Modulation

When  V_DS  exceeds  V_GS - V_th  (pinch-off condition), a depletion region forms at the drain end of the channel.

As  V_DS  increases further:
- The depletion region widens toward the source
- This effectively **reduces the channel length**
- A shorter channel → lower resistance  
- Hence, **drain current increases slightly** even in saturation region  
- Instead of being constant (ideal case)

---

##  CMOS (Complementary Metal Oxide Semiconductor)

CMOS is the dominant technology used for fabricating:
- Integrated Circuits (ICs)
- Microprocessors
- Microcontrollers
- Memory devices  

It uses a **combination of:**
- P-type MOSFET (PMOS)
- N-type MOSFET (NMOS)

---

##  CMOS Characteristics

- High speed  
- High noise margin  
- Very low power consumption  

This makes CMOS ideal for:
- Battery-powered devices  
- High-density electronic systems  

---

##  Working Principle of CMOS

A CMOS circuit uses:
- **Pull-up network** → PMOS transistors  
- **Pull-down network** → NMOS transistors  

### Operation:
- Only **one network is ON at a time**
- This prevents direct current flow from VDD to GND  
- Power is mainly consumed **during switching**

---

## CMOS Inverter

### Structure:
- PMOS connected to **VDD**
- NMOS connected to **GND**
- Output taken between them

### Working:
- Input = 0 → PMOS ON, NMOS OFF → Output = 1  
- Input = 1 → NMOS ON, PMOS OFF → Output = 0  

---

## Applications of CMOS

- ICs (RAM, ROM, CPU)
- ASIC Design
- CMOS Sensors

---
