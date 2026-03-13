# CoralMorphoCT
This repository contains scripts developed to evaluate porosity and other volumetric outcomes in segmented labCT images of coral skeleton samples.
Currently, the code is tailored to samples from the specie *Porites astreoides*. This code could be applied to samples of other species, but adjustments in certain parameters (e.g. structural element sizes for morphological operations) may be needed due to differences in coral skeleton architecture and feature length scales.

This tool was developed as part of a larger study, "Asymmetric Depth Acclimation and Plasticity Limit the Refugial Potential of Mesophotic Porites astreoides", investigating adaptation to depth changes in corals, specifically Porites astreoides. The full project repository — including data, additional scripts, data processing workflows, and supporting material — is available here: XXXXX. 

## Method overview
- Users are prompted to select the input file - a binary mask of the coral skeleton, in 3D tiff format - and pixel size in units of um.
- Through logical and morphological operations, masks of the total volume (volume included within the outer surface of the sample), open pore volume, and closed pore volume are generated and exported as 3D tifs. PNG images of representative slices are also generated. 
- Whole-sample and slicewise measurements of volumes and derived ratios (including porosity = pore volume / total volume) are calculated and exported as CSVs.
*Note: Outputs are exported to the input path.*

## Usage
### Linux
1. Create a conda environment with the environmentl.yml file.
2. Activate the environment, and run the python file.

## Publication
xxx

## Funding
This tool was developed in 2025 by Isabela Vitienes, in the Zaslansky lab of the Department of Operative, Preventive and Pediatric Dentistry at Charité – Universitätsmedizin Berlin, with funding from the DFG (FOR5657).
