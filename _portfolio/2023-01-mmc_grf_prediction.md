---
title: "Prediciting ground reaction forces from markerless 3D motion tracking"
excerpt: "Can a physics-based approach accurately predict ground reaction forces from markerless 3D motion tracking during diverse activities? <br/><img src='/images/mmc_grf_prediction_cover.png'>"
collection: portfolio
---
*This research is ongoing.*  
The accuracy of a physics-based approach to predicting ground reaction forces (GRF) and centre of pressure (COP) during a diverse range of activities using only markerless 3D motion tracking is being investigated.  
` `  
![Custom markerless motion capture pose estimation](/images/mmc_grf_prediction_mocap.png){: .align-center}  
A diverse range of activities, including walking, running, jumping and change of direction, is examined. The body segment positions throughout these movements are captured with a commercial markerless 3D motion tracking system and force plates. The resulting centre of mass trajectories from the motion capture are used to derive the theoretically required GRFs. These predicted GRFs are then compared against those measured with the force plates.  
` `  
![Predicted vs measured GRFs](/images/mmc_grf_prediction_results.png){: .align-center}
Preliminary results show that 93-99% of variance in GRFs can be predicted with the current physics-based approach.

<!--COP trajectories are predicted using the assumption of zero net moment about the body's centre of mass, proposed by [Herr and Popovic (2008)](https://doi.org/10.1242/jeb.008573) and likewise compared against the measured ground truth.-->
