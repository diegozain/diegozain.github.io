---
layout: default
---

[![](images/diegozain.png)](./)

## active source

Understanding material properties of the subsurface can help us find energy resources (i.e. oil, gas, geothermal), mitigate hazards, monitor CO2 sequestration sites, understand ground-water flow, map magma chambers and budget water availability.

### **[Gerjoii](./gerjoii)**

Forward modeling of ground penetrating **radar** and **electrical resistivity** together with a novel 2.5d joint multi-parameter **inversion algorithm** that recovers electrical **permittivity** and **conductivity** of the subsurface from surface acquired radar and resistivity data. Included is a machine learning routine (PyTorch) for finding the weights needed for the inversion. [Code.](https://github.com/diegozain/gerjoii)

[![](images/gpr-er-line-data.png)](./gerjoii)

### **[Wave utils](./gerjoii)**

Code suite for processing waveforms as recorded by receivers in the field. Features include: frequency domain filtering, beamforming analysis, frequency time analysis, multichannel analysis of surface waves, and virtual source gathers by seismic interferometry. Lives inside [Gerjoii.](https://github.com/diegozain/gerjoii)

### Radar synthetic example

__True model of the subsurface. This model is made up because this is a synthetic example.__

![](images/true-dibujo-sy.png)

__Below is the radar wavefield. In the field we do not "see" this since radar is not visible for humans, and we do not have access in depth. This is a simulation of what the electromagnetic wavefield looks like. The receivers are depicted by cyan dots.__

![](images/wavefield-color.gif)

__Below is the data. The data is acquired by the receivers on the surface.__

![](images/line1_d1_observed-dibujo-sy.png)

__The question now is, given JUST the data, how do we recover the subsurface parameters?__

[![](images/dudes.png)](./)