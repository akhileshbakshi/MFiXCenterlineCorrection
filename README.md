# MFiXCenterlineCorrection

radial_vel_correction.f implements improved centerline treatment while using 3D cyldrical coordinates in MFiX. The model and implementation are based on the second-order scheme deeveloped by Fukagata and Kasagi [1]. The contribution is acknowledged in the MFiX 2014-1 release announcement [2]. More details regarding the model and its improvement to solid-gas flow simulations can be found in [3]. 

[1] K. Fukagata and N. Kasagi, Highly energy-conservative finite difference method for the cylindrical coordinate system, J. Comput. Phys. 181 (2) (September 2002) 478–498.
[2] https://mfix.netl.doe.gov/mfix2014-1-release-announcement/
[3] A. Bakshi, C. Altantzis and A.F. Ghoniem, Towards accurate three-dimensional simulation of dense multi-phase flows using cylindrical coordinates, Powder Technology 264 (2014) 242–255.
