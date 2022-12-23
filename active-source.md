---
layout: default
---

# ⚡ active source

Understanding material properties of the subsurface can help us find energy resources (i.e. oil, gas, geothermal), mitigate hazards, monitor CO₂ sequestration sites, understand ground-water flow, map magma chambers and budget water availability.

## 🔰 [Gerjoii](https://github.com/diegozain/gerjoii)

Gerjoii is: forward modeling of ground penetrating **radar** and **electrical resistivity** together with a novel 2.5d joint multi-parameter **inversion algorithm** that recovers electrical **permittivity** and **conductivity** of the subsurface from surface acquired radar and resistivity data. Included is a machine learning routine (PyTorch) for finding the weights needed for the inversion.

For a digested code-tour go [here](https://github.com/diegozain/gerjoii/blob/master/docs/manuals/about/gerjoii-show.pdf), for the code [here](https://github.com/diegozain/gerjoii).

### 🌊 [Wave utils](./gerjoii)

Code suite for processing waveforms as recorded by receivers in the field. Features include: frequency domain filtering, beamforming analysis, frequency time analysis, multichannel analysis of surface waves, and virtual source gathers by seismic interferometry. Lives inside [Gerjoii.](https://github.com/diegozain/gerjoii)

## 🔌⛽ remediation monitoring

Can we find the **3D** spread of the remediation agent in the subsurface using DC data? Yes, it is the blue stuff.

![](images/adapt-dcip.png)

On the left is the DCIP instrument used in this survey. On the right is the 3D time-lapse result before and after the injection of the remediation agent. The colored dots denote the location of the injections.

![](images/quots.gif)

## 📡🔌 2d multiphysics: GPR full-waveform inversion & DC data

Visit the peer-reviewed [paper](https://doi.org/10.1190/geo2021-0161.1) for details!

![](images/condus.png)

## 📡 GPR 2d full-waveform inversion

This is a synthetic example of what GPR full-waveform inversion can do. For a field study visit the peer-reviewed [paper](https://doi.org/10.1190/geo2021-0161.1).

![](images/tinyradar.png)

## 🔌 ER 2.5d inversion

Visit the peer-reviewed [paper](https://library.seg.org/doi/10.1190/geo2020-0373.1)

[Gerjoii](https://github.com/diegozain/gerjoii) supports 2.5d inversion of ER data. Below is an example of an imaged alluvial aquifer.

![](images/bhrs-er.jpg)
![](images/bhrs-dc.png)

Red is where the ground-water is. Yellow is where dry sand lies. Dashed line is a 1m depth marker. Solid lines are borehole locations.

😉 This method is way better than Res2dInv.

![](images/gerjoii-vs-res2dinv.png)

## 🌳 radar on trees

Forward modeling of radar on trees. _Left_ is the wavefield in the tree and _right_ is the observed data.

![](images/wavefield.gif)![](images/line1-tree.png)

## 👻 finding graves

Every black dot represents a known grave marker from the image on the left.

[![](images/idaho-energy.jpg)](./)
