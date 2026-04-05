# AIE Silafluorene Calculations

<img align="right" src='https://github.com/LinusP217/AIE_Silafluorene/blob/main/LockedSF_HOMO.png' width = "300" height = "284">

Computational Supporting Information for the publication 'Uncovering Structural Dynamics of Silicon-based Aggregation Induced Emission Molecules with Ultrafast Spectroscopy.' Geometry optimizations were carried out in the Gaussian 16 Rev A.03<sup>1</sup> software package with the CAM-B3LYP functional and 6-311+G(d,p) basis set. Solvation effects were included through the Polarizable Continuum Model (PCM). See below file tree for metadata.

## Contents 📁
```
.
├── data/
│   ├── input_files/
│   │   ├── LockSF_gs_opt.com      # S0 geometry optimization
│   │   ├── LockSF_gs_vertical.com # S0 -> Sn vertical exication
│   │   ├── UnlockSF_gs_opt.com
│   │   └── UnlockSF_gs_vertical.com
│   │
│   ├── optimized_structures/
│   │   ├── LockSF_gs.xyz         # optimzied gs structure
│   │   └── UnlockSF_gs.xyz
│   │
│   └── simulated_abs/
│       ├── LockSF_Abs_Spectrum.csv    # Convoluted absorption from vert excitations ^^
│       └── UnlockSF_Abs_Spectrum.csv
│

3 directories, 8 files
```

### Usage 💻
Make a copy of the entire repo with the following command in a terminal:
```bash
git clone https://github.com/tjz21/AIE_Silafluorene.git
```

or if you would just like a specific file, use `wget` and the raw url for that file:

<img align="center" src='https://github.com/tjz21/AIE_Silafluorene/blob/main/raw_link_image.png' width = "600" height = "63.4">

```bash
wget [raw URL of specific file]
```

### Contact 📫
GitHub repository maintained by Tim J. Zuehlsdorff, tim.zuehlsdorff@oregonstate.edu

[cc-zero-png]: https://licensebuttons.net/l/zero/1.0/88x31.png "CC0 1.0 Universal (CC0 1.0) Public Domain Dedication button"
[cc-zero]: https://creativecommons.org/publicdomain/zero/1.0/

[![CC0 1.0 Universal (CC0 1.0) Public Domain Dedication
button][cc-zero-png]][cc-zero]
