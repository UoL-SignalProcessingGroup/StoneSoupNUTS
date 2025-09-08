# Stone Soup Goes NUTS: Adding Proposals and the No-U-Turn Sampler to Stone Soup
Tutorial repository for the paper submitted  and presented at [FUSION 2025](https://fusion2025.org/) with title: "Stone Soup goes NUTS: adding proposals and The 
No-U-Turn Sampler to Stone Soup"
You can read the paper on [IEEE Xplore](https://ieeexplore.ieee.org/document/11124070)

## Abstract
Particle filters are essential for state estimation in non-linear and non-Gaussian systems, with performance hinging
on effective proposal distributions. This paper presents the implementation of Kalman Filter and No-U-Turn Sampler (NUTS)
proposals within the Stone Soup Python framework. The Kalman Filter proposal offers computational efficiency for structured
systems, while NUTS enables robust exploration of complex, high-dimensional distributions. Benchmark evaluations demonstrate
the complementary strengths of these methods, enhancing Stone Soup’s capabilities for diverse state estimation challenges

## Authors 
[Alberto Acuto](https://github.com/A-acuto)<sup>1</sup>, [Lyudmil Vladimirov](https://github.com/sglvladi)<sup>1</sup>, 
[Alessandro Varsi](https://github.com/AVarsi88)<sup>1</sup>, [Paul Horridge](https://github.com/paulhorridge)<sup>1</sup> 
 and [Simon Maskell](http://www.simonmaskell.com/)<sup>1</sup>
 
<sup>1</sup> University of Liverpool, Department of Electrical Engineering and Electronics 

## Community engagement
The code shared can be run and modifief for various uses. We refer to the [Stone Soup](https://github.com/dstl/Stone-Soup)
community for further examples on how to use the framework, raise issues on the implementation and proposing and 
implementing improvements. 


### Installation

To install and test the code provided you can use a virtual environment.
How to set up a virtual environemnt:

```unix
python3 -m venv <name_of_venv>
```

#### Activate the venv

##### Unix
```bash
source <name_of_venv>/bin/activate
```

##### Windows
```powershell
.\<name_of_venv>\Scripts\activate
```

Then you can install all the dependencies by doing:
```bash
python -m pip install -e .[dev]
```

#### Please note:
This code is built on top of [Stone Soup](https://github.com/dstl/Stone-Soup) and when the code will be reviewed and included
in the main branch we will update the installation guide for easier running of the tutorial.

## Cite this work
```bibtex
@INPROCEEDINGS{11124070,
  author={Acuto, Alberto and Vladimirov, Lyudmil and Varsi, Alessandro and Horridge, Paul and Maskell, Simon},
  booktitle={2025 28th International Conference on Information Fusion (FUSION)}, 
  title={Stone Soup Goes NUTS: Adding Proposals and the No-U-Turn Sampler to Stone Soup}, 
  year={2025},
  volume={},
  number={},
  pages={1-8},
  keywords={Accuracy;Particle filters;Mathematical models;Time measurement;Robustness;Trajectory;State-space methods;Proposals;Kalman filters;State estimation;Particle Filter;proposal distributions;importance sampling;no-u-turn-sampler},
  doi={10.23919/FUSION65864.2025.11124070}
}
```



