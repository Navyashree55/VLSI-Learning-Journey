# Day 19: Op-Amp (Operational Amplifier)

## What is an Op-Amp?
An **Operational Amplifier (Op-Amp)** is a building block of modern electronics.  
It takes a small input signal and amplifies it into a larger output signal.

---

## Basic Op-Amp Structure

- V+ → Non-inverting input  
- V− → Inverting input  
- Vout → Output  
- Vcc / Vee → Power supply  

---

## Amplifier Definition

An Op-Amp is a **high gain differential amplifier**.

- It amplifies the **difference between two input signals**.

---

## Input Terminals Behavior

### Non-Inverting Input (V+)
- If input voltage increases → Output increases

### Inverting Input (V−)
- If input voltage increases → Output decreases

### Output (Vout)
- Amplified signal appears at the output

---

## Characteristics of Ideal Op-Amp

- Infinite input impedance  
- Zero output impedance  
- Infinite bandwidth  
- Infinite open-loop gain  
- Zero common mode gain  

---

## Feedback in Op-Amp

### What is Feedback?
- Taking a part of output and feeding it back to input

### Why Feedback is Needed?
- Controls the system  
- Reduces errors  
- Makes output stable  

---

## Basic Op-Amp Configurations

---

## 1. Inverting Amplifier

### Circuit Description
- Input is applied to inverting terminal (V−)  
- Non-inverting terminal is grounded  
- Feedback resistor connects output to input  

### Gain
Av = - (R2 / R1)

### Key Points
- Output is inverted  
- If input increases → output decreases  

---

## 2. Non-Inverting Amplifier

### Circuit Description
- Input is applied to non-inverting terminal (V+)  
- Feedback network connected to inverting terminal  

### Gain
Av = 1 + (R2 / R1)

### Key Points
- Output is not inverted  
- If input increases → output increases  


## Applications

- Signal processing  
- Filters  
- Amplifiers  
- Analog circuits
