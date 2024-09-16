# Microstrip Patch Antenna Design

This project focuses on the design of a microstrip patch antenna using coaxial feeding, operating at a frequency of 3 GHz. The project was developed using Ansys HFSS software to simulate and analyze the antenna's performance.

## Project Overview

### Antenna Introduction
A microstrip patch antenna is a compact, low-profile antenna used in modern communication systems such as Wi-Fi, Bluetooth, and satellites. The antenna consists of a radiating patch on one side of a dielectric substrate and a ground plane on the other side.

### Design Parameters
The following parameters were used in the design:

| Parameter        | Value        |
|------------------|--------------|
| Dielectric Constant (εr) | 4.4          |
| Resonant Frequency (f₀) | 3 GHz        |
| Patch Length (L) | 30.42 mm      |
| Patch Width (W)  | 23.42 mm      |
| Substrate Height (h) | 1.6 mm    |
| Substrate Length | 60 mm        |
| Substrate Width  | 60 mm        |
| Feed Location (X, Y) | (0, -1.5) mm |

### Antenna Feeding
Coaxial feeding was used for the antenna, where the inner conductor of the coaxial connector is soldered onto the patch, and the outer conductor is attached to the ground plane.

## Design Procedure
The antenna design process involved the following steps:

1. Ground Plane Setup
2. Substrate Setup
3. Patch Design
4. Feed Line Setup
5. Radiation Boundary Addition
6. Simulation and Analysis

## Results

### Return Loss (S11 Parameter)
The return loss of the designed antenna was found to be *-17.5 dB*, indicating a good match between the antenna and the feed line.

![Return Loss](https://github.com/user-attachments/assets/84757386-d962-484f-b0b7-a78e8d72c26e)

### 2D Radiation Pattern at 3 GHz
The following is the 2D polar plot showing the radiation pattern of the antenna at 3 GHz.

![2D Radiation Pattern](![2D](https://github.com/user-attachments/assets/bdab3a42-c018-43ce-99d4-9d50a868d4e5)
)

### 3D Radiation Pattern at 3 GHz
Here is the 3D radiation pattern showing the antenna's performance at 3 GHz.

![3D Radiation Pattern](https://example.com/3d_radiation_pattern.png)

## Discussion
The microstrip patch antenna resonates at the desired frequency of *3 GHz* with a return loss of *-17.5 dB*. The antenna design achieves efficient performance, making it suitable for applications like weather radar, surface ship radar, and satellite communication.

## Conclusion
The designed antenna is compact and easy to fabricate, making it an excellent choice for modern communication systems. The simple coaxial feeding technique further enhances the antenna's usability in various applications.

## Team Members
- Lavanya (210002082)
- Divya (210002046)
- Rishitha (210002035)
- Vagdevi (210002015)
- Charanya (210002020)
- Indravallika (210002034)

---
