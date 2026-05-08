# ZdeHav Magnetic Toolchanger

> **Magnetic tool-changing system for 3D printers**

This repository contains the 3D models and assembly files for the ZdeHav Toolchanger system, including the carriage (X-axis mount) and the toolhead assembly. The system is designed for high repeatability, ease of use, and compatibility with high-performance components.

---

## ⚙️ Working Principle

The ZdeHav Toolchanger utilizes a magnetic coupling system combined with a three-point kinematic mount.

### Kinematic Coupling & Repeatability
Reliable alignment is ensured by a **three-point contact system**:
- **Hardware**: Three acorn (cap) nuts and three standard hex nuts.
- **Mechanism**: The rounded tops of the acorn nuts seat into the centers of the hex nuts, providing a self-centering effect that ensures the toolhead always returns to the exact same position (high repeatability).

### Magnetic Retention
The system uses powerful neodymium magnets to hold the toolhead securely during printing and in the dock.
- **Carriage-to-Head**:
    - **Head**: 3× 6mm neodymium cubes + 25×6×2mm rectangular blocks.
    - **Carriage**: 3× 6mm neodymium cubes + 25×6×2mm rectangular blocks.
- **Dock Retention**:
    - 3× Cylindrical magnets (Ø8mm, 8mm length) for secure docking.

---

## 🛠️ Toolhead Specifications

The toolhead is designed for high-performance extrusion and compact size.

| Component | Specification |
|---|---|
| **Hotend** | Bambu Lab X1C Hotend |
| **Extruder Gears** | Bondtech-style dual drive gears |
| **Motor** | NEMA 14 stepper motor |
| **Cooling** | 3010 fan (dedicated for Bambu hotend) |

---

## ⚡ Electronics & Wiring

The assembly is designed with flexibility in mind regarding electronics:

1. **Custom Toolhead PCB**: Optimized for the [ZdeHav Changer PCB](https://github.com/iZboxo/ZdeHav-Changer-PCB) (CAN bus). This allows for a single-cable setup (Power + CAN) directly on the toolhead.
2. **Direct Wiring**: Alternatively, the design supports routing individual cables ("dumb cables") to an external controller board elsewhere on the printer.

---

## 🖼️ Gallery

<table>
  <tr>
    <td><img width="703" height="581" alt="image" src="https://github.com/user-attachments/assets/0559a89e-299c-4b03-8386-a36000f05c88" /></td>
    <td><img width="4032" height="3024" alt="IMG_1924" src="https://github.com/user-attachments/assets/022945bf-33a9-4082-921d-a26490765179" /></td>
    <td><img width="4032" height="3024" alt="IMG_1923" src="https://github.com/user-attachments/assets/e6538175-cb58-4dc3-91a8-1b49269e168d" /></td>
  </tr>
</table>

---

## 📜 License

This design is released under the **MIT License**.

---

*Design: Zdeněk Havlát — [zdehav.cz](https://zdehav.cz)*
