# Static-Analysis-with-2fix-point
# Static Structural Analysis of a Long Circular Beam (1D Element) 🌉



## 📌 Project Overview
This project performs a Finite Element Analysis (FEA) on a long structural member (20 meters in length) modeled as a **1D Line Body with a Circular Cross-Section** using **Ansys Mechanical**. The simulation validates the component's structural response—specifically its deflection, bending moment, and shear force—under static loading. This approach efficiently utilizes the **Beam Tool** to apply classical beam theory principles within a powerful FEA framework.

## ⚙️ Simulation Setup and Methodology

### 1. Geometry and Element
* **Element Type:** 1D Line Body (Beam Element).
* **Cross Section:** Circular (`Circular1`). The beam model relies on the sectional properties (Area Moment of Inertia) derived from the circular geometry.
* **Length:** 20.00 meters (indicating a structure typical of long-span beams or columns).

### 2. Material Properties: Structural Steel
The beam is modeled using standard **Structural Steel**.
* **Young's Modulus ($E$):** $2.0 \times 10^{11} \text{ Pa}$
* **Tensile Yield Strength:** 250 MPa

### 3. Boundary Conditions & Loads
* **Constraints:** [Specific constraints (e.g., Simple or Fixed Supports) were applied to define the load-bearing condition.]
* **Loads:** Static forces or distributed loads were applied to induce bending and deflection.

## 📊 Results & Analysis (Beam Tool)

### 🔍 Key Findings
The simulation focuses on the primary results obtained via the **Beam Tool**:

1.  **Total Deformation:** Analysis of the maximum displacement (deflection), which is crucial for meeting serviceability limits in long structures.
2.  **Axial/Bending Stress:** Calculation of the maximum stresses occurring at the cross-section fibers, essential for checking against the material's yield strength (250 MPa).
3.  **Shear Force and Bending Moment:** The Beam Tool provides internal force and moment diagrams, confirming the structural behavior under load.



## 🚀 Repository Contents
* `Project.wbpj`: The Ansys Workbench project file.
* `static 2 FIX.pdf`: The detailed simulation report.

---
## 👨‍💻 Author
**Yazan Alzyuod**
* **Mechanical Engineer**
* 📧 [yqlasem@gmail.com](mailto:yqlasem@gmail.com)
* 🔗 [LinkedIn Profile](https://www.linkedin.com/in/yazan-alzyuod)
* 💻 [GitHub Profile](https://github.com/Yazan-Alzyuod)
* 📞 00962775327776
