# LCSS-control
This repository contains the MATLAB source code used for reproducing the trajectory planning simulations in the LCSS papers titled:

*K. Ren, H. Ahn and M. Kamgarpour, "Chance-Constrained Trajectory Planning With Multimodal Environmental Uncertainty," in IEEE Control Systems Letters, vol. 7, pp. 13-18, 2023.*

<p align="center">
  <img src="https://github.com/renkai99/renkai99.github.io/blob/main/assets/img/publication_preview/nuscenes.gif" width="45%" />
</p>

## Dependencies
The following dependencies need to be installed/configured and must be on the MATLAB path:

[YALMIP](https://yalmip.github.io/) (configured with an optimization solver such as [CPLEX](https://www.ibm.com/analytics/cplex-optimizer))

[MagInset](https://www.mathworks.com/matlabcentral/fileexchange/49055-maginset)

MATLAB Toolbox: [Control System](https://www.mathworks.com/products/control.html), [Statistics](https://www.mathworks.com/products/statistics.html), and [Optimization](https://www.mathworks.com/products/optimization.html)

## Instructions

After installing the dependencies, simply run **main.m**.

## References of the work
Please cite the original paper when using any part of this code. BibTeX citation data:
```
@ARTICLE{Ren_2023_LCSS,
  author={Ren, Kai and Ahn, Heejin and Kamgarpour, Maryam},
  journal={IEEE Control Systems Letters}, 
  title={Chance-Constrained Trajectory Planning With Multimodal Environmental Uncertainty}, 
  year={2023},
  volume={7},
  pages={13-18},
  doi={10.1109/LCSYS.2022.3186269}}
```
