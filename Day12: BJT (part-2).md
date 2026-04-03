## Current Relationships

 Emitter current | I_E = I_C + I_B |

 Collector current (in terms of alpha) | I_C = alpha * I_E 

 Base current (in terms of alpha) | I_B = (1 - alpha) * I_E 

 Collector current (in terms of beta) | I_C = beta * I_B 

 Relationship between alpha and beta | beta = alpha / (1 - alpha), alpha = beta / (1 + beta) 

---

## Early Effect — Detailed Explanation

1. The increase in reverse bias at the collector-base junction causes the depletion region at that junction to widen.  
2. This eats into the base from the collector side, so the effective base width becomes thinner.  
3. Because the base is thinner, carriers injected from the emitter have less distance to diffuse, which increases the collector current slightly.

---

## Operating Modes of BJT

### 1. Forward Active Mode
- **Junction Bias:**  
  - E-B Junction: Forward  
  - B-C Junction: Reverse  
- **Behavior:** Collector current (I_C) is controlled by base current (I_B)  
- **Application:** Amplification

### 2. Reverse Active Mode
- **Junction Bias:**  
  - E-B Junction: Reverse  
  - B-C Junction: Forward  
- **Application:** Rare; used in specific circuits

### 3. Cut-Off Mode
- **Junction Bias:**  
  - E-B Junction: Reverse  
  - B-C Junction: Reverse  
- **Behavior:** No current flows → Transistor is OFF

### 4. Saturation Mode
- **Junction Bias:**  
  - E-B Junction: Forward  
  - B-C Junction: Forward  
  - V_CB = 0 (shorted condition)  
- **Application:** Used in switching operations

---
