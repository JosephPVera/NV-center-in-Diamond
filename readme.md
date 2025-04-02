---
# NV center diamond
---

## 1. Bulk properties
| Method        | Band gap (eV) | Lattice constants (Å) |
| :-------------: |:-------------:|:---------------------:|
| PBE           | 4.16          |     3.57              |
| HSE06         | 5.37          |     3.55              | 
| Experimental  | 5.47          |                   |

## 2. Dielectric tensor
### 2.1. Ionic contribution
$$
A =
\begin{bmatrix}
a_{11} & a_{12} & a_{13} \\
a_{21} & a_{22} & a_{23} \\
a_{31} & a_{32} & a_{33}
\end{bmatrix}
$$

## 3. Point defects
Using a supercell $3x3x3$.
### 3.1. PBE functional
#### 3.1.1. Formation energy diagram
![Alt text](https://github.com/JosephPVera/NV-center-Diamond/blob/main/Point-defects/PBE/formation-energy/energy_A-1.png)
#### 3.1.2. $NV^{-1}$ defect: Kohn-Sham states
![Alt text](https://github.com/JosephPVera/NV-center-Diamond/blob/main/Point-defects/PBE/N_C-V_C_-1/band_index/kohn-sham-states.png)
#### 3.1.3. $NV^{-1}$ defect: Localized Kohn-Sham states
![Alt text](https://github.com/JosephPVera/NV-center-Diamond/blob/main/Point-defects/PBE/N_C-V_C_-1/band_index/Spin_down-kpoint_1.png)

### 3.2. HSE06 functional
| Defect     | Charge | Magnetization ($\mu_{B}$) | Spin state |
| :--------: |:------:|:-------------------------:| :---------:|
| $N_C-V_C$  | -1     |        2                  |     1      |
#### 3.2.1. Formation energy diagram
![Alt text](https://github.com/JosephPVera/NV-center-Diamond/blob/main/Point-defects/HSE06/formation-energy/energy_A-1.png)
#### 3.2.2. $NV^{-1}$ defect: Kohn-Sham states
![Alt text](https://github.com/JosephPVera/NV-center-Diamond/blob/main/Point-defects/HSE06/N_C-V_C_-1/band_index/kohn-sham-states.png)
#### 3.2.3. $NV^{-1}$ defect: Localized Kohn-Sham states
![Alt text](https://github.com/JosephPVera/NV-center-in-Diamond/blob/main/Point-defects/HSE06/N_C-V_C_-1/band_index/Spin_up-kpoint_1.png)
![Alt text](https://github.com/JosephPVera/NV-center-Diamond/blob/main/Point-defects/HSE06/N_C-V_C_-1/band_index/Spin_down-kpoint_1.png)

## 4. Representation
Only well-localized states in gap.
![Alt text](https://github.com/JosephPVera/NV-center-in-Diamond/blob/main/Point-defects/HSE06/N_C-V_C_-1/kohn-sham-states-deg.png)

Spin density
![Alt text](https://github.com/JosephPVera/NV-center-in-Diamond/blob/main/Point-defects/HSE06/N_C-V_C_-1/diamond.png)
