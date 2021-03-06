# Teaching assistant ge-pde-ws2122
<!-- 
![](./eqns/ghw.png#gh-dark-mode-only) 

![](./eqns/ghb.png#gh-light-mode-only) -->

## Class of **Numerical methods for Partial Differential Equations (NumPDE)** - WS 2021-2022
### Global exercises (GEs): GE09![](./eqns/rightarrow_w.svg#gh-dark-mode-only)![](./eqns/rightarrow_b.svg#gh-light-mode-only)GE10![](./eqns/rightarrow_w.svg#gh-dark-mode-only)![](./eqns/rightarrow_b.svg#gh-light-mode-only)GE11![](./eqns/rightarrow_w.svg#gh-dark-mode-only)![](./eqns/rightarrow_b.svg#gh-light-mode-only)GE12![](./eqns/rightarrow_w.svg#gh-dark-mode-only)![](./eqns/rightarrow_b.svg#gh-light-mode-only)GE13![](./eqns/rightarrow_w.svg#gh-dark-mode-only)![](./eqns/rightarrow_b.svg#gh-light-mode-only)GE14![](./eqns/rightarrow_w.svg#gh-dark-mode-only)![](./eqns/rightarrow_b.svg#gh-light-mode-only)GE15![](./eqns/rightarrow_w.svg#gh-dark-mode-only)![](./eqns/rightarrow_b.svg#gh-light-mode-only)GE15e

#TODO

- Linear ![](./eqns/plus_w.svg#gh-dark-mode-only) ![](./eqns/plus_b.svg#gh-light-mode-only)  Nonlinear **Hyperbolic systems** of **conservation laws**
  
    ![](./eqns/CL_w.svg#gh-dark-mode-only) 

    ![](./eqns/CL_b.svg#gh-light-mode-only)

    where unknown conserved quantity ![](./eqns/U_w.svg#gh-dark-mode-only) ![](./eqns/U_b.svg#gh-light-mode-only) is defined as follows
    
    ![](./eqns/Udf_w.svg#gh-dark-mode-only) 

    ![](./eqns/Udf_b.svg#gh-light-mode-only)

- **Cauchy**'s problems
- **Riemann**'s problems
- Linear scalar advection equation
- Nonlinear viscous **Burgers**' ![](./eqns/plus_w.svg#gh-dark-mode-only) ![](./eqns/plus_b.svg#gh-light-mode-only) inviscid **Burgers**' equations
- Hyperbolic systems of first order PDE: 
  - (strictly) hyperbolicity: disctinct eigenvalues
  - diagonalizable matrix ![](./eqns/ARLR_w.svg#gh-dark-mode-only) ![](./eqns/ARLR_b.svg#gh-light-mode-only) 
  - Decomposition of system of first order PDEs into separated first order PDEs
- **Shock** solution vs **Rarefaction** solution
- **Finite Volume Methods**
- Conservation form 
  
    ![](./eqns/conserform_w.svg#gh-dark-mode-only) 

    ![](./eqns/conserform_b.svg#gh-light-mode-only)

- Consistent numerical flux function 
- Upwind-to-the-left (UWL): 
  
    ![](./eqns/UWL_w.svg#gh-dark-mode-only) 

    ![](./eqns/UWL_b.svg#gh-light-mode-only)

- Upwind-to-the-right (UWR): 
    
    ![](./eqns/UWR_w.svg#gh-dark-mode-only) 

    ![](./eqns/UWR_b.svg#gh-light-mode-only)

- **Lax-Friedrichs** (LF): 
  
    ![](./eqns/LF_w.svg#gh-dark-mode-only) 

    ![](./eqns/LF_b.svg#gh-light-mode-only)

- **Lax-Wendroff** (LW):

- **Lax-Friedrichs** (LF) in conservation form: 

    ![](./eqns/LFcon_w.svg#gh-dark-mode-only) 

    ![](./eqns/LFcon_b.svg#gh-light-mode-only)

    where the consistent numerical flux functions are defined as follows

    ![](./eqns/LFflux_left_w.svg#gh-dark-mode-only) 

    ![](./eqns/LFflux_left_b.svg#gh-light-mode-only)

    ![](./eqns/LFflux_right_w.svg#gh-dark-mode-only) 

    ![](./eqns/LFflux_right_b.svg#gh-light-mode-only)

- **Lax-Wendroff** (LW) in conservation form:
  
- **Courant-Friedrichs-Lewy** (CFL) condition
- Numerical Analysis: **Lax** Equivalence Theorem: 
  **Consistency** ![](./eqns/plus_w.svg#gh-dark-mode-only) ![](./eqns/plus_b.svg#gh-light-mode-only) **Stability** ![](./eqns/LRarrow_w.svg#gh-dark-mode-only) ![](./eqns/LRarrow_b.svg#gh-light-mode-only)  **Convergence**
  - Nonlinear numerical methods
  - Non-oscillatory behaviours of higher order numerical methods
- Exact **Riemann** solver: **Godunov**'s scheme
- Approximate **Riemann**'s solvers: 
  - **Roe**'s solver 
  - Local **Lax-Friedrichs** (LLF) solver
  - **Harten-Lax-van Leer** (HLL) solver
- Structure of Finite Volume Method
  - **Monotone** ![](./eqns/rightarrow_w.svg#gh-dark-mode-only) ![](./eqns/rightarrow_b.svg#gh-light-mode-only) ![](./eqns/L1_w.svg#gh-dark-mode-only) ![](./eqns/L1_b.svg#gh-light-mode-only)-**Contraction** ![](./eqns/rightarrow_w.svg#gh-dark-mode-only) ![](./eqns/rightarrow_b.svg#gh-light-mode-only) **Total-Variation-Diminishing** (TVD) ![](./eqns/rightarrow_w.svg#gh-dark-mode-only) ![](./eqns/rightarrow_b.svg#gh-light-mode-only) **Monotonicity-Preserving**
- Nonlinear + higher order numerical scheme: 
  - **Harten** theorem
  - Incremental form
  - TVD scheme
- A bit insight into **Godunov**'s solver with graphical explanations

---

## Teaching assistant's extra materials and supplements

### Unnoted materials

#TODO

- [x] CW49/2021 ![](./eqns/rightarrow_w.svg#gh-dark-mode-only) ![](./eqns/rightarrow_b.svg#gh-light-mode-only) Better open in web ![](./eqns/rightarrow_w.svg#gh-dark-mode-only) ![](./eqns/rightarrow_b.svg#gh-light-mode-only) [GE09](https://github.com/tuanvo-git/ge-pde-ws2122/blob/main/GE09/ge-09.pdf) 
- [x] CW50/2021 ![](./eqns/rightarrow_w.svg#gh-dark-mode-only) ![](./eqns/rightarrow_b.svg#gh-light-mode-only) Better open in web ![](./eqns/rightarrow_w.svg#gh-dark-mode-only) ![](./eqns/rightarrow_b.svg#gh-light-mode-only) [GE10](https://github.com/tuanvo-git/ge-pde-ws2122/blob/main/GE10/ge-10.pdf)
- [x] CW51/2021 ![](./eqns/rightarrow_w.svg#gh-dark-mode-only) ![](./eqns/rightarrow_b.svg#gh-light-mode-only) Better open in web ![](./eqns/rightarrow_w.svg#gh-dark-mode-only) ![](./eqns/rightarrow_b.svg#gh-light-mode-only) [GE11](https://github.com/tuanvo-git/ge-pde-ws2122/blob/main/GE11/ge-11.pdf)
- [x] CW02/2022 ![](./eqns/rightarrow_w.svg#gh-dark-mode-only) ![](./eqns/rightarrow_b.svg#gh-light-mode-only) Better open in web ![](./eqns/rightarrow_w.svg#gh-dark-mode-only) ![](./eqns/rightarrow_b.svg#gh-light-mode-only) [GE12](https://github.com/tuanvo-git/ge-pde-ws2122/blob/main/GE12/ge-12.pdf) 
- [x] CW03/2022 ![](./eqns/rightarrow_w.svg#gh-dark-mode-only) ![](./eqns/rightarrow_b.svg#gh-light-mode-only) Better open in web ![](./eqns/rightarrow_w.svg#gh-dark-mode-only) ![](./eqns/rightarrow_b.svg#gh-light-mode-only) [GE13](https://github.com/tuanvo-git/ge-pde-ws2122/blob/main/GE13/ge-13.pdf) 
- [x] CW03/2022 ![](./eqns/rightarrow_w.svg#gh-dark-mode-only) ![](./eqns/rightarrow_b.svg#gh-light-mode-only) Better open in web ![](./eqns/rightarrow_w.svg#gh-dark-mode-only) ![](./eqns/rightarrow_b.svg#gh-light-mode-only) [GE14](https://github.com/tuanvo-git/ge-pde-ws2122/blob/main/GE14/ge-14.pdf) 
- [x] CW04/2022 ![](./eqns/rightarrow_w.svg#gh-dark-mode-only) ![](./eqns/rightarrow_b.svg#gh-light-mode-only) Better open in web ![](./eqns/rightarrow_w.svg#gh-dark-mode-only) ![](./eqns/rightarrow_b.svg#gh-light-mode-only) [GE15](https://github.com/tuanvo-git/ge-pde-ws2122/blob/main/GE15/ge-15.pdf) 
- [x] CW05/2022 ![](./eqns/rightarrow_w.svg#gh-dark-mode-only) ![](./eqns/rightarrow_b.svg#gh-light-mode-only) Better open in web ![](./eqns/rightarrow_w.svg#gh-dark-mode-only) ![](./eqns/rightarrow_b.svg#gh-light-mode-only) [GE15e](https://github.com/tuanvo-git/ge-pde-ws2122/blob/main/GE15e/ge-15e.pdf) 
---
### Noted materials

#TODO

- [x] CW49/2021 ![](./eqns/rightarrow_w.svg#gh-dark-mode-only) ![](./eqns/rightarrow_b.svg#gh-light-mode-only) Better open in web ![](./eqns/rightarrow_w.svg#gh-dark-mode-only) ![](./eqns/rightarrow_b.svg#gh-light-mode-only) [GE09-offline](https://github.com/tuanvo-git/ge-pde-ws2122/blob/main/GE09/ge-09.pdf)
- [x] CW50/2021 ![](./eqns/rightarrow_w.svg#gh-dark-mode-only) ![](./eqns/rightarrow_b.svg#gh-light-mode-only) Better open in web ![](./eqns/rightarrow_w.svg#gh-dark-mode-only) ![](./eqns/rightarrow_b.svg#gh-light-mode-only) [GE10-offline](https://github.com/tuanvo-git/ge-pde-ws2122/blob/main/GE10/ge-10.pdf)
- [x] CW51/2021 ![](./eqns/rightarrow_w.svg#gh-dark-mode-only) ![](./eqns/rightarrow_b.svg#gh-light-mode-only) Better open in web ![](./eqns/rightarrow_w.svg#gh-dark-mode-only) ![](./eqns/rightarrow_b.svg#gh-light-mode-only) [GE11-offline](https://github.com/tuanvo-git/ge-pde-ws2122/blob/main/GE11/ge-11.pdf)
- [x] CW02/2022 ![](./eqns/rightarrow_w.svg#gh-dark-mode-only) ![](./eqns/rightarrow_b.svg#gh-light-mode-only) Better open in web ![](./eqns/rightarrow_w.svg#gh-dark-mode-only) ![](./eqns/rightarrow_b.svg#gh-light-mode-only) [GE12-noted-online](https://github.com/tuanvo-git/ge-pde-ws2122/blob/main/GE12/ge-12-noted.pdf)
- [x] CW03/2022 ![](./eqns/rightarrow_w.svg#gh-dark-mode-only) ![](./eqns/rightarrow_b.svg#gh-light-mode-only) Better open in web ![](./eqns/rightarrow_w.svg#gh-dark-mode-only) ![](./eqns/rightarrow_b.svg#gh-light-mode-only) [GE13-noted-online](https://github.com/tuanvo-git/ge-pde-ws2122/blob/main/GE13/ge-13-noted.pdf)
- [x] CW04/2022 ![](./eqns/rightarrow_w.svg#gh-dark-mode-only) ![](./eqns/rightarrow_b.svg#gh-light-mode-only) Better open in web ![](./eqns/rightarrow_w.svg#gh-dark-mode-only) ![](./eqns/rightarrow_b.svg#gh-light-mode-only) [GE14-noted-online](https://github.com/tuanvo-git/ge-pde-ws2122/blob/main/GE14/ge-14-noted.pdf)
- [x] CW05/2022 ![](./eqns/rightarrow_w.svg#gh-dark-mode-only) ![](./eqns/rightarrow_b.svg#gh-light-mode-only) Better open in web ![](./eqns/rightarrow_w.svg#gh-dark-mode-only) ![](./eqns/rightarrow_b.svg#gh-light-mode-only) [GE15-noted-online](https://github.com/tuanvo-git/ge-pde-ws2122/blob/main/GE15/ge-15-noted.pdf)

<p align="center">
    <img src="https://raw.githubusercontent.com/tuanvo-git/ge-pde-ws2122/main/eqns/ghw.png#gh-dark-mode-only" height="120" width="120"/>
    <img src="https://raw.githubusercontent.com/tuanvo-git/ge-pde-ws2122/main/eqns/ghb.png#gh-light-mode-only" height="120" width="120"/>
</p>