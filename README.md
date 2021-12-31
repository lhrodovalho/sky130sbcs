A <b>resistorless self-biased current source</b> intended to be integrated in the efabless MPW4. </br>


Table of contents
==============================
<!--ts-->
  * [Summary](#Summary)
  * [Description](#Description)
    * [Schematics and Layouts](#Schematics-and-Layouts)
    * [Simulation Results](#Simulation-Results)
  * [Team Members](#Team-Members)  
  * [References](#References)
<!--te-->

---
Summary
=======

A resistorless self-biased current source based on [1] using series-parallel current mirrors [2]

### Target Performance Summary

| Specifications        | -                            |
| :---                  | :---                         |
| VDD                   | 1.0-1.8 V                    |
| Total current         | 3.50 &mu;A                   |
| Output current        | 0.27 &mu;A                   |
| Temperature stability | 0.5 %/V                      |
| Supply stability      | 1160 ppm/°C                  |
| Area                  | 100 x 60 &mu;m²              |

---
Description
===========

### Schematics and Layouts
---
![image](./docs/circuits/sbcs.png)
![image](./docs/layouts/sbcs.png)

Self-biased current source circuit diagram

### Simulation Results

#### TT corner
![image](./docs/plots/tt_dc_vdd_io.png)
![image](./docs/plots/tt_dc_vdd_psrr.png)
![image](./docs/plots/tt_dc_temp_io.png)
![image](./docs/plots/tt_tran_io.png)

Status and Issues
============

* Documentation is extremely incomplete.

Team members
============

**Ph.D. Luís Henrique Rodovalho (Rodovalho)**
| [luishenriquerodovalho@gmail.com](mailto:luishenriquerodovalho@gmail.com?subject=Hi% "Hi!") <img width="15" src="https://cdn-icons-png.flaticon.com/128/2089/2089181.png" alt="email"> | 

References
==========

[1] Serra-Graells, Francisco, and Jose Luis Huertas. "Sub-1-V CMOS proportional-to-absolute temperature references." IEEE Journal of Solid-State Circuits 38.1 (2003): 84-88.

[2] Arnaud, Alfredo, Rafaella Fiorelli, and Carlos Galup-Montoro. "Nanowatt, sub-nS OTAs, with sub-10-mV input offset, using series-parallel current mirrors." IEEE Journal of Solid-State Circuits 41.9 (2006): 2009-2018.


