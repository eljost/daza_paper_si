## Supporting Information - Computational Results

This repository contains the geometries (.xyz files) for all relevant stationary points, discussed in the paper

"On the synthesis of N,1,4-Tri(4-alkoxy-2-hydroxybenzyl)-DAZA: Investigations on a unique reductive amination reaction".

Each of the four directories contains optimized geometries of educt(s), transition state (TS) and product. Additionally, trajectories of the intrinsic reaction coordinate integrated from the TS, as well as, the associated imaginary mode at the TS are provided. Finally, the input files to pysisyphus are given, to reproduce the results.

Two exemplary inputs for the double hybrid density functional theory calculations  (gas phase and solvated)  are found in *double_hybrid_gas.inp* and 
*double_hybrid_solvated.inp*.

All quantum chemical calculations were carried out using ORCA 5.0.4.

&nbsp;

| Directory   |      Description      |
|----------|-------------|
| *00_1step* | One step carbonyl insertion via **TS 1** |
| *01_reductive_amination* |    Reductive amination via **3e**   |
| *02_2steps_step1* | First step of two-step carbonyl insertion via **TS 2.1** |
| *03_2steps_step2* | Second step of two-step carbonyl insertion via **TS 2.2** |¸
