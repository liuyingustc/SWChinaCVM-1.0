SWChinaCVM-1.0

This is a reference 3-D P- and S-wave community velocity model of the crust and uppermost mantle in southwest China (SWChinaCVM-1.0, DOI:10.12093/02md.02.2019.01.v1), obtained by joint body and surface wave traveltime tomography. This work is supported by the China Seismic Experimental Site（CSES）. 

* Model Data Format: Lon Lat Dep(km) Vp(km/s) Vs(km/s)

* Method: Joint inversion of body wave (P and S-wave) travel time and Rayleigh wave traveltime data (Fang et al., (2016), JGR).

* Grid space: Horizontally 0.5 degree interval, vetically at depth 0, 5, 10, 15, 20, 25, 30, 35, 40, 50, 60, 70 km.

* We provide models with different relative depths: 1) SWChinaCVMv1.0.txt: Depth is relative to the surface (0 km), 2) SWChinaCVMv1.0.txt.wrst.sea_level: Depth is relative to the mean sea level (0 km). Please choose appropriate one according to your situation. For example, if you are dealing with surface wave problems, model with depth relative to the surface (SWChinaCVMv1.0.txt) is recommended. If you are doing body wave tomography or earthquake relocations, model with depth relative to the mean sea level (SWChinaCVMv1.0.txt.wrst.sea_level) is recommended.

The resolutions of Vp and Vs model are calculated according to the checkerboard resolution test. Grid Nodes with resolution higher than 0.7 are considered as well resolved.
* Format: Lon Lat Dep(km) resolution_of_Vp resolution_of_Vs

If you have any questions, please feel free to contact Huajian Yao (hjyao@ustc.edu.cn) or Ying Liu (liuying7@ustc.edu.cn).

References:

Liu, Y., Yao, H., Zhang, H., and Fang, H. (2021). The Community Velocity Model V.1.0 of Southwest China, Constructed from Joint Body‐ and Surface‐Wave Travel‐Time Tomography. Seismological Research Letters 2021; doi: https://doi.org/10.1785/0220200318.

Yao H., 2020. Building the multi-scale community velocity model in the Sichuan-Yunnan area, China: Strategies and progresses, Science China Earth Sciences (invited), 63(9): 1425-1428, https://doi.org/10.1007/s11430-020-9645-3.

