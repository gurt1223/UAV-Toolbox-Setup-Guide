# UAV-Toolbox-Setup-Guide

The UAV Toolbox Setup Guide repository is a comprehensive resource for researchers, students, and engineers working to test custom algorithms built in MATLAB/Simulink (i.e., model identification, path planning, control, etc.) using PX4-based UAVs in MATLAB. It provides both _written_ and _video_ tutorials to help set up the R2025a release of the UAV Toolbox and the UAV Toolbox Support Package for PX4 Autopilots. Additionally, it highlights both the Baseline Robust Aircraft Testing (BRAT) Framework tutorial video and the BRAT Framework repository as complementary resources for getting started with building a custom algorithm and integrating it with PX4 Inputs/Outputs. 

---

## Table of Contents
- **[File Guide](https://github.com/gurt1223/UAV-Toolbox-Setup-Guide/edit/main/README.md#file-guide)**
- [How to Use](#how-to-use)
- [Required Software](#required-software)
- [Optional PX4 Base Code Modifications](#optional-px4-base-code-modifications)
- [Related Publications](#related-publications)
- [Acknowledgments](#acknowledgments)
- [Citing This Resource](#citing-this-resource)

---

## File Guide
- **[Appendices_Prerelease.pdf](https://github.com/gurt1223/UAV-Toolbox-Setup-Guide/blob/main/Appendices_Prerelease.pdf)**<br>
  Pre-release edition of Garrett Asper's Master's Thesis Appendix. Step-by-step instructions for setting up the UAV Toolbox.

- **[UAV Toolbox Support Package for PX4 Setup and Configuration Tutorial Video](https://youtu.be/UafbBIGAWPQ)**<br>
  A tutorial video detailing the steps to set up the UAV Toolbox Support Package for PX4 Autopilots that complements the written steps found in the appendix.

- **[Baseline Robust Aircraft Testing (BRAT) Framework Tutorial Video](https://youtu.be/mS8hB7pjNKs)**<br>
  A tutorial video that walks through the baseline robust aircraft testing (BRAT) framework in Simulink and demonstrates the Connected IO (bench test) and Build, Deploy, & Start (flight test) functionality.

- **[Baseline Robust Aircraft Testing (BRAT) Framework Repository](https://github.com/gurt1223/brat/)**<br>
  A GitHub repository with the latest release of BRAT, a framework to get started with the PX4 Input/Output blocks available in Simulink.

---

## How to Use
1. Start with the `Appendix_PreRelease.pdf`.  
2. Watch the [video tutorial](https://youtu.be/UafbBIGAWPQ).  
3. Refer to the related publications for applications of this setup.

---

## Required Software
- QGroundControl (v4.4.2)
- MATLAB - R2025a
- Simulink
- MATLAB/Simulink Add-Ons
  - UAV Toolbox
  - UAV Toolbox Support Package for PX4 Autopilots
  - MATLAB Coder
  - Simulink Coder
  - Embedded Coder 

---

## Optional PX4 Base Code Modifications
Optional modifications can be made to the PX4 firmware code to enable features, including custom logging (uORB topic), custom parameters, custom telemetry stream, and flash memory reduction.
These modification instructions are given in the `Appendix_PreRelease.pdf`, which references example files available in the [PX4-Modification-Example-Files](https://github.com/gurt1223/PX4-Modification-Example-Files) GitHub repository.

---

## Related Publications
<details>
<summary>Click to expand</summary>

[1]	Asper, G. D. and Simmons, B. M., “Rapid Flight Control Law Deployment and Testing Framework for Subscale VTOL Aircraft,” NASA/TM−20220011570, Sept. 2022. 

[2]	Asper, G. D., Simmons, B. M., Ackerman, K. A., Axten, R. M., and Corrigan, P. E., “Inexpensive Multirotor Platform for Advanced Controls Testing (IMPACT): Development, Integration, and Experimentation,” NASA/TM-20240000223, March 2024. 

[3]	Simmons, B.M., Ackerman, K.A., and Asper, G.D. “Aero-Propulsive Damping Characterization for eVTOL Aircraft Using Free Motion Wind-Tunnel Testing,” AIAA SciTech 2025 Forum, AIAA Paper 2025-0006, Jan. 2025.

[4]	Corrigan, P.E., Matt, J.J., and Asper, G.D. “Design and Testing of an Octocopter for Aerodynamic and Power Consumption Modeling,” NASA/TM-20240013453, March 2025. 

[5]	Asper, G.D. and Woolsey, C.A., “Toward a Fault-Tolerant Control Allocation Evaluation Framework for eVTOL Aircraft,” VSGC Student Research Conference, Virginia Space Grant Consortium, April 2025.

[6]	Simmons, B.M., Ackerman, K.A., Asper, G.D., Gray, M.N., Snyder, S.M., Axten, R.M., Geuther, S.C., and Chan, R. “Subscale Tiltrotor eVTOL Aircraft Dynamic Modeling and Flight Control Software Development,” Vertical Flight Society Annual Forum & Technology Display, May 2025. 
Awarded Best Paper Submitted to the Modeling & Simulation Technical Committee.

[7]	Comer, A.M., Simmons, B.M., and Asper, G.D. “Design, Simulation, and Flight Testing of a Multi-Purpose VTOL Flight Control System,” NASA/TM—20250000954, September 2025. 

[8]	Simmons, B.M., Ackerman, K.A., and Asper, G.D. “Aero-Propulsive Damping Characterization for eVTOL Aircraft Using Free Motion Wind-Tunnel Testing,” Journal of Aircraft, In review.

[9]	Corrigan, P.E., Asper, G.D., Simmons, B.M., and Woolsey, C.A., “Aircraft System Identification Approach for Control Surface Fault Diagnosis,” AIAA SciTech 2026 Forum, Submitted for consideration, 2026. 

[10]	Asper, G.D., Corrigan, P.E., Simmons, B.M., and Woolsey, C.A., “An Evaluation of Fault-Tolerant Control Allocation Strategies for eVTOL Aircraft,” AIAA SciTech 2026 Forum, Submitted for consideration, 2026.

</details>

---

## Acknowledgments
Thank you to Patrick Corrigan, Benjamin Simmons, and Anthony Comer for your support in learning the ins and outs of this toolchain.<br>
Thank you to the developers at MathWorks, particularly Arun Mathamkode and Ankur Bose, for your insight and openness to feedback on problems and improvements.

---

## Citing This Resource
If you use the steps available in **Appendix_PreRelease.pdf** to set up the UAV Toolbox for your research, please cite Garrett Asper's Master's Thesis:<br>  
Asper, G. D., “An Evaluation of Fault-Tolerant Control Allocation Strategies for eVTOL Aircraft,” M.S. Thesis, Virginia Tech, Blacksburg, VA, To be published Jan. 2026.<br>
_Please check back in January to ensure there are no updates to the citation. The repository contains a prerelease of the appendices, but citing the above thesis is the most effective way to acknowledge these resources._

