# ROOF THERMAL ANALYSIS WITH & WITHOUT INSULATION USING ANSYS

### Comparative Study of Heat Transfer through Roof with and without Insulation

## 📌 Project Overview

This project investigates heat transfer through a residential building roof using thermal analysis in ANSYS. The objective was to compare the heat loss rate of an uninsulated roof with an insulated roof and evaluate the effectiveness of thermal insulation in reducing energy loss.

The study demonstrates how insulation affects thermal resistance and decreases heat transfer from the indoor environment to the surrounding atmosphere.

---

## 🎯 Objectives

- Analyze heat transfer through a roof structure without insulation.
- Analyze heat transfer through the same roof after applying insulation.
- Compare heat loss rates for both cases.
- Determine the percentage reduction in heat transfer.
- Study temperature and heat flux distributions.

---

## 🛠 Software and Tools Used

- ANSYS Mechanical
- ANSYS Steady State Thermal Analysis
- CAD Geometry Modeling
- Heat Transfer Theory
- Microsoft Excel

---

## 📖 Problem Statement

The roof of an electrically heated house has the following dimensions:

| Parameter | Value |
|------------|--------|
| Roof Length | 6 m |
| Roof Width | 8 m |
| Roof Thickness | 0.25 m |
| Insulation Thickness | 0.20 m|
| Thermal Conductivity | 0.8 W/m·K |
| Indoor Temperature | 15 °C |
| Outdoor Temperature | 4 °C |
|Isulation Material | Fiber Glass |

Heat transfer through the roof was evaluated using Fourier's Law:

\[
Q={kA(T_1-T_2)} / L
\]

Where:

- Q = Heat transfer rate (W)
- k = Thermal conductivity (W/m·K)
- A = Surface area (m²)
- L = Thickness (m)
- T₁ − T₂ = Temperature difference (°C)

---

## 🔬 Methodology

### Step 1: Geometry Creation

- Created roof geometry in ANSYS.
- Dimensions used:
  - Length = 6 m
  - Width = 8 m
  - Thickness = 0.25 m
  - Area = 48 m^2

### Step 2: Material Assignment

Assigned material properties:

- Thermal conductivity = 0.8 W/m·K
- Thermal conductivity of Fiber Glass (Insulation Material) = 1.27 W/m·K

### Step 3: Boundary Conditions

Applied:

**Case 1: Without Insulation**

- Indoor surface temperature = 15°C
- Outdoor surface temperature = 4°C

**Case 2: With Insulation**

Added insulation layer and repeated the thermal analysis.

### Step 4: Solve and Post Processing

Generated:

- Temperature contours
- Heat flux contours
- Total heat transfer results

---

## 📊 Results

### Without Insulation

| Parameter | Result |
|------------|---------|
| Heat Transfer Rate | 1689.6 W |
| Maximum Temperature | 15 °C |
| Minimum Temperature | 4 °C |

### With Insulation

| Parameter | Result |
|------------|---------|
| Heat Transfer Rate | 1121.6 W |
| Maximum Temperature | 15 °C |
| Minimum Temperature | 4 °C |

---
## 📊 Thermal Resistance Improvement

###Thermal Resistance Comparison

| Parameter | Case 1 (Without Insulation) | Case 2 (With Insulation) | Improvement |
|-----------|-----------------------------|---------------------------|-------------|
| Heat Flux, q" (W/mm²) | 3.520 × 10⁻⁵ | 2.3366 × 10⁻⁵ | ↓ Reduced |
| Thermal Resistance, R | 1.00 | 1.507 | +50.7% increase |

### Key Observation

- Heat flux decreases significantly after adding insulation.
- Thermal resistance increases from **1.00 to 1.507**.
- This corresponds to a **50.7% improvement in thermal resistance**.
- Lower heat flux confirms better insulation performance and reduced energy loss.

---

## 📈 Comparison

| Parameter | Case 1 (Without Insulation) | Case 2 (With Insulation) | Reduction |
|-----------|-----------------------------|---------------------------|-----------|
| Average Heat Flux, q" (W/mm²) | 3.520 × 10⁻⁵ | 2.3366 × 10⁻⁵ | — |
| Area, A (m²) | 48 | 48 | — |
| Heat Transfer, Q (W) | 1689.6 | 1121.6 | ↓ 33.6% |

### Key Observation

- Heat flux reduction directly reduces total heat transfer.
- Case 2 shows **33.6% reduction in heat transfer**, confirming insulation effectiveness.
- Results are consistent between flux and total heat transfer calculations.

---

## 📷 Simulation Results

<h3> 1 Pager Report </h3>
<p align="center">
1 Pager Report <br />
<img src="https://img.sanishtech.com/u/9729c43f871e21060a2c98bce6b0b64b.png" height="80%" width="80%" alt="Geometry Model"/>
<h3>1. Geometry Model</h3>
<p align="center">
1a. 3D Geometry Design in Spaceclaim <br />
<img src="https://img.sanishtech.com/u/d22d3d6837522d44e718751dc5a090d6.png" height="80%" width="80%" alt="Geometry Model"/>
<p align="center">
1b. Roof Geometry without Insulation <br />
<img src="https://img.sanishtech.com/u/5995d5763071e432b98badc327dc97e7.png" height="80%" width="80%" alt="Geometry Model"/>
<p align="center">
1c. Roof Geometry with Insulation <br />
<img src="https://img.sanishtech.com/u/c324ea7376334505f23688c7c5f6d44c.png" height="80%" width="80%" alt="Geometry Model"/>
<br />

<h3>2. Mesh </h3>
<p align="center">
2a. Mesh <br />
<img src="https://img.sanishtech.com/u/4eb87fab113b42a338b0d89f77b83248.png" height="80%" width="80%" alt="Geometry Model"/>
  
<h3>3. Temperature Distribution (Without Insulation)</h3>
<p align="center">
3a. Temperature Distribution (Without Insulation)
<img src="https://img.sanishtech.com/u/23b7b137897cf37e237f910737743f50.png" height="80%" width="80%" alt="Temperature Without Insulation"/>
</p>

<h3>4. Heat Flux Distribution (Without Insulation)</h3>
<p align="center">
4a. Total Heat Flux Distribution (Without Insulation)
<img src="https://img.sanishtech.com/u/4866387ce681f8f4358480ed4e1141a6.png" height="80%" width="80%" alt="Heat Flux Without Insulation"/>
</p>

<h3>5. Temperature Distribution (With Insulation)</h3>
<p align="center">
5a. Temperature Distribution (With Insulation
<img src="https://img.sanishtech.com/u/54b2cc915c262e020f1314a18856436e.png" height="80%" width="80%" alt="Temperature With Insulation"/>
</p>

<h3>6. Heat Flux Distribution (With Insulation)</h3>
<p align="center">
6a. Total Heat Flux Distribution (With Insulation)
<img src="https://img.sanishtech.com/u/afe34937ec31ef579ddb7adf76383fb3.png" height="80%" width="80%" alt="Heat Flux With Insulation"/>
</p>

---

## 💡Summary of Results

- Addition of insulation reduces heat flux on the roof surface from 3.52 x W/mm2 to 2.3366 x W/mm2.
- Total heat transfer through the roof is reduced from 1689.6 W to 1121.6 W, i.e., 33.6% reduction.
- Thermal resistance of the roof system increases by 50.7%.Heat transfer decreased significantly after applying insulation.
- Insulation reduced energy loss and improved thermal efficiency.

---
## Conclusion

The steady-state thermal analysis shows that adding an insulation layer significantly improves roof thermal performance by reducing heat transfer and increasing thermal resistance. A **33.6% reduction in heat loss** was observed, confirming the effectiveness of insulation in minimizing thermal energy losses. This directly contributes to improved indoor thermal stability and reduced heating and cooling demand. Further performance gains can be achieved by increasing insulation thickness or selecting materials with lower thermal conductivity to enhance thermal resistance.

---
## 🚀 Future Improvements

- Perform transient thermal analysis.
- Investigate different insulation materials.
- Study effects of varying insulation thickness.
- Include convection and radiation effects.

---

## 👨‍💻 Author

Muhammad Ubaid Khalid

Mechanical Engineer | CFD & FEA Specialist

📧 engrubaidkhalid321@gmail.com

🔗 LinkedIn: https://www.linkedin.com/in/m-ubaid
