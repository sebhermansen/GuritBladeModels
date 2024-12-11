# GuritBladeModels

OVERVIEW
-------------------------------------
This repository contains blade models developed and used by Gurit for supporting engineering design of wind turbine blade materials. 
Provided are variations of the models with different internal configurations, which currently are one, two, and three shear webs.

Currently available models

	- [v] 98 m structural analysis offshore blade model w/ varying internal configurations.

Model is available in formats:

	- [v] Abaqus 		.inp
	
	- [x] ANSYS 		.cdb
	
	
ABOUT THE MODELS
-------------------------------------
A thorough description of the overall blade model is given in Hermansen et al. [1], which is open-access and can be downloaded at TODO. The following gives a brief overview:

The blade model has been generated from the Blade3 software (see blade3.io). The blade mesh consists of 4-noded shell elements with full integration and stabilization techniques and 8-noded solid elements in the trailing edge.

Material layout is based on the typical design philosophy used to design typical modern wind turbine blades. 
Hence, the blade can be roughly divided into fiber-dominated regions, which are the spar caps and trailing + leading edge laminates. 
These utilize UD Glass-Fiber Reinforced Polymer (GFRP), UD Carbon-Fiber Reinforced Polymer (CFRP), biax GFRP, and triax GFRP.
The material properties for the fiber materials are compiled from commerical software databases [3,4].
Core regions consist of Gurit Kerdyn PET foam, with properties from certified datasheet [5].
The glue material in the trailing edge is based on an epoxy glue.
Materials are distributed into 563 sections and plies are divided into nominal thicknesses.

The model contains twelve extreme load cases, which it typically used in the detailed structural design phase.

Baseline for ensuring design integrity has been the DNV guidelines [2].

To suggest improvements, other features, or for any other enquiries, please contact dkrin.blademodel@gurit.com.

REFERENCES
-------------------------------------
[1] Hermansen SM, Borstnar G, Buhl T, Lund E (2025) The Gurit98m: A detailed open-source modern offshore wind turbine blade structural model with optimization applications. Structural and Multidisciplinary Optimization. Under Review

[2] DNV-GL (2015) DNVGL-ST-0376. Tech. rep., DNV GL Group AS

[3] ANSYS (2024) ANSYS Workbench, version 2024 R1

[4] ESAComp (2016) ESAComp - software for analysis and design of composites, Release 4.5.2.

[5] Gurit (2024) Gurit Kerdyn™ Structural Foam Core Recycled and Recyclable v14. https://www.gurit.com/wp-content/uploads/bsk-pdf-manager/2024/06/PDS-Kerdyn-14-0524.pdf




