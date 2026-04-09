# Junction Field-Effect Transistor (JFET)

## What is a JFET?
A JFET (Junction Field-Effect Transistor) is a three-terminal semiconductor device used for amplification and switching. It controls current flow using an electric field (voltage) rather than base current, making it a **voltage-controlled device** with extremely high input impedance.

---

## Terminals

- **Gate (G)** — The control terminal. Applies voltage to regulate current flow through the channel.  
- **Drain (D)** — The terminal where current exits the channel.  
- **Source (S)** — The terminal where current enters the channel.  

---

## How It Works

Current flows from the **Drain to the Source** through a semiconductor channel. The voltage applied at the Gate creates an electric field that narrows or "pinches off" this channel, thereby controlling the amount of current flowing through it.

Since the Gate-channel junction is **reverse-biased**, virtually no gate current flows. This gives the JFET an extremely **high input impedance** (megaohms to gigaohms).

---

## Types

| Type              | Channel Material       | To Reduce Current                  |
|------------------|----------------------|-----------------------------------|
| N-channel JFET   | N-type semiconductor | Make Gate voltage more negative   |
| P-channel JFET   | P-type semiconductor | Make Gate voltage more positive   |

**Note:** N-channel JFETs are more commonly used due to higher electron mobility and better performance.

---

## Operating Regions

### 1. Ohmic (Linear) Region
- JFET behaves like a variable resistor  
- VDS is small; channel is open  
- Used in switching applications  

---

### 2. Saturation (Active) Region
- Drain current becomes nearly constant  
- Channel is partially pinched off  
- Used for amplification  

**Formula:** ID = IDSS * (1 - VGS / VP)^2

---

### 3. Cutoff Region
- Gate voltage fully pinches off the channel  
- No current flows from Drain to Source  
- Device is **OFF**  

---

## Applications

- High-impedance amplifiers (audio, instrumentation)  
- RF amplifiers and oscillators  
- Analog switches  
- Buffer amplifiers (impedance matching)  
- Voltage-controlled resistors (AGC circuits)  

---
