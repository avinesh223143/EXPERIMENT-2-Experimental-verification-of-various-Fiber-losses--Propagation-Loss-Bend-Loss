# EX.NO: 2 – Verification of Fiber Losses

## Aim:
To measure propagation and bending losses for two wavelengths in plastic fiber.

## Equipments Required:
- Link-B Kit  
- Patch chords  
- Oscilloscope  
- Function Generator  
- Fiber cables 

## Theory:  
Optical Fibers are available in different variety of materials. These materials are usually selected by taking into account their absorption characteristics for different wavelengths of light. In case of Optical Fiber, since the signal is transmitted in the form of light which is completely different in nature as that of electrons, one has to consider the interaction of matter the radiation to study the losses in fiber.

Losses are introduced in fiber due to various reasons. As light propagates from one end of Fiber to another end, part of it is absorbed in the material exhibiting absorption loss. Also part of the light is reflected back or in some other directions from the impurity particles present in the material contributing to the loss of the signal at the other end of the Fiber. In general terms it is know as propagation loss. Plastic Fibers have higher loss of the order of 180 dB/Km. Whenever the condition for angel of incidence of the incident lights is violated the losses are introduced due to refraction of light. This occurs when fiber is subjected to bending. Lower the radius of curvature more is the loss. Other losses are due to the coupling of Fiber at LED and photo detector ends.

## Procedure:
- Setup for 660nm and 950nm measurements  
- Measure output voltages for 1m and 3m fibers  
- Calculate attenuation \( a \) using:  
V1/V2 = e [ -a (L1+L2 ) ] 
- Bend fiber and record output vs diameter
- 
## Circuit:
<img width="952" height="500" alt="image" src="https://github.com/user-attachments/assets/736d5f4e-0c04-4193-b151-5852158e21a1" />

## Tabulation:

### Propagation Loss:

| Fiber Length | Input Amplitude (V) | Output Amplitude (V) |
|--------------|---------------------|------------------------|
|        1     |       5             |           10           |
|        0.5   |       5             |           14           |

### Bending Loss:

| Bending Diameter | Input Amplitude (V) | Output Amplitude (V) |
|------------------|---------------------|------------------------|
| 1 for 8cm        |        5            |             10.3       |
| 0.5 for 6.4 cm   |        5            |             9.76       |

## Calulation:
![WhatsApp Image 2025-11-16 at 21 38 57_be622e46](https://github.com/user-attachments/assets/bad5298c-054e-40a1-9797-c43340397656)


## Result:
Attenuation and bending loss characteristics verified.

---
