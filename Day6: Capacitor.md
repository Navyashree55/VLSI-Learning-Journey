# Capacitor

## Definition
- A capacitor is a passive electrical component that stores energy in an electric field.

## Unit
- SI Unit: Farad (F)

---

## Basic Formula
Q = C × V

Where:
- Q = Charge (Coulombs)
- C = Capacitance (Farads)
- V = Voltage (Volts)

---

## Energy Stored
E = 1/2 × C × V²

---

## Construction & Working
- A capacitor consists of two conductive plates separated by an insulating material (dielectric).
- When voltage is applied:
  - One plate stores positive charge
  - The other plate stores negative charge
- Energy is stored in the electric field between the plates.

---

## Types of Capacitors

### 1. Non-Polarized Capacitor
- No positive or negative terminal
- Can be connected in any direction

#### Ceramic Capacitor
- A type of non-polarized capacitor that uses ceramic as dielectric
- Small, disc-shaped (through-hole) or rectangular (SMD)
- Common colors: orange, brown, yellow, blue
- No polarity marking

---

### 2. Polarized Capacitor
- Has positive (+) and negative (−) terminals
- Must be connected correctly

#### Types:
- Electrolytic capacitor
- Tantalum capacitor

---

## Polarity Identification

### Electrolytic Capacitor:
- Stripe on body → Negative (−) terminal
- Long lead → Positive (+)
- Short lead → Negative (−)

### Tantalum Capacitor:
- Mark (+) on body → Positive terminal

### Ceramic Capacitor:
- Non-polarized (no polarity)

---

## Capacitor Value Identification

### Direct Marking:
Example:
10µF 25V

- 10µF → Capacitance  
- 25V → Voltage rating  

---

### Code Method (3-Digit Code)

Example:
104

- First two digits → 10  
- Third digit → number of zeros (4)

Value:
10 × 10⁴ = 100000 pF = 100 nF

---

### Common Codes

| Code | Value |
|------|-------|
| 101  | 100 pF |
| 102  | 1 nF |
| 103  | 10 nF |
| 104  | 100 nF |
| 105  | 1 µF |

---

## Important Behavior

- Capacitor opposes change in voltage

### DC Behavior:
- Initially allows current
- After charging → blocks DC

### AC Behavior:
- Allows AC to pass because it continuously charges and discharges

---

## Lag and Lead Concept (AC Only)

- Current leads voltage by 90°
- Voltage lags current by 90°

---

## Capacitive Reactance

Xc = 1 / (2πfC)

Where:
- Xc → Capacitive reactance (Ω)
- f → Frequency (Hz)
- C → Capacitance (F)

Key Points:
- Higher frequency → lower reactance
- Higher capacitance → lower reactance

---

## Applications

- Energy storage
- Filtering (noise removal)
- Coupling and decoupling
- Timing circuits (RC circuits)

---

## Passive Nature

- Capacitor is a passive component
- It does not generate or amplify energy
- It only stores and releases energy

---

## Key Insight

- Capacitor stores energy in an electric field
- It opposes change in voltage
- It blocks DC and allows AC
- Polarized capacitors must be connected correctly
- In AC circuits, current leads voltage by 90°
