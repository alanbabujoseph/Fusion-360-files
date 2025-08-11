# Helical Screw – Fusion 360 Design

## 📄 Overview
This project features a **parametric helical screw (single‑start blade)** modeled in Autodesk Fusion 360.  
It highlights **clean, feature‑driven modeling**, **precise control of pitch/turns**, and **production‑ready exports**.

---

## 🛠 Features
- **Accurate Geometry** – Outer/inner diameters, pitch, turns, and thickness are fully parametric.
- **Realistic Metal Render** – Materials and environment tuned for a polished look.
- **Editable Timeline** – Clearly named sketches and features for quick tweaks.
- **Manufacturing‑Ready** – Exported STEP for CAM; STL optional for printing.

---

## 🧰 Tools Used (Fusion 360)
- **Coil / Helix** – Generates the helical path using diameter, pitch, and turns.
- **Sweep** – Forms the blade by sweeping a profile along the helix.
- **Loft** (optional) – For tapered or blended blade profiles between stations.
- **Thicken** – Converts surface sweeps to solids at a specified thickness.
- **Fillet** – Softens edges to reduce stress risers and improve printability.
- **Combine** – Joins the blade to the shaft or cuts a bore/keyway.
- **Mirror** – Quickly switch handedness or duplicate symmetric features.

---

## 📂 Files in this Repository
- `helical_Blade_v1.stl` – Mesh for 3D printing.
- `Helical Blade v1.png` – Rendered image of the model.

> If you use different filenames or folders, update the links below.

---

## 📸 Preview

<img width="1520" height="834" alt="Helical Blade v1" src="https://github.com/user-attachments/assets/e2a8a1ac-01ea-4ec8-9a45-7a358b8769e3" />


---

## 🔧 Key Parameters (Modify → Change Parameters)
- `outer_diameter` – Blade OD  
- `inner_diameter` – Shaft/bore diameter  
- `pitch` – Axial advance per revolution  
- `turns` – Number of helical revolutions  
- `thickness` – Blade thickness (after **Thicken**)  
- `fillet_radius` – Edge rounding

> Handedness can be flipped by mirroring or reversing helix direction.

---

## 🚀 Manufacturing Notes
- **CNC/CAM:** Use the STEP export. For finishing, apply scallop/parallel passes on the blade surface; verify tool reach and holder clearance.  
- **3D Printing:** Orient the axis vertically to minimize supports under the blade. Use 3–5 perimeters and ≥25% infill; increase `thickness` for FDM durability.

---

## 📜 License
MIT License — free to use and adapt with attribution.

---

## 👤 Author
**Alan Babu Joseph**  
Master’s in Biomechanical Engineering | Mechanical Graduate Intern  
Passionate about CAD, CAM, additive manufacturing, and product design.

# Helical-screw
