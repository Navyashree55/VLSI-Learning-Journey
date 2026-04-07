## MOSFET Characteristics

- V_TN is positive  
- V_TP is negative  

### NMOS:
- V_GSn = V_G - V_S = Vin - 0 = Vin  
- V_DSn = V_D - V_S = Vout - 0 = Vout  

### PMOS:
- V_GSp = V_G - V_S = Vin - VDD  
- V_DSp = V_D - V_S = Vout - VDD  

---

##  NMOS Regions

- If V_GSn < V_Tn → Cut-off region  
- If V_GSn > V_Tn → device turns ON  

Conditions:
- If (V_GSn - V_Tn) > V_DSn → Linear region  
- If (V_GSn - V_Tn) < V_DSn → Saturation region  

---

##  PMOS Regions

- If V_GSp > V_TP → Cut-off region  
- If V_GSp < V_TP → device turns ON  

Conditions:
- If (V_GSp - V_TP) > V_DSp → Saturation region  
- If (V_GSp - V_TP) < V_DSp → Linear region  

---

##  Enhancement MOSFET

- Requires positive gate voltage to conduct  
- Positive threshold voltage required  
- Normally OFF (non-conductive in natural state)  
- Widely used in digital circuits and CMOS technology  
- Majority carriers are electrons  

---

##  Depletion MOSFET

- Conducts in natural state (no gate voltage required)  
- Requires negative gate voltage  
- Normally ON (conductive in natural state)  
- Less used in digital, more used in analog circuits  
- Majority carriers are holes  

---
