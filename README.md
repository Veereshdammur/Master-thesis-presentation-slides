# Master-thesis-presentation-slides

This repository contains the final master thesis presentation. The topic of my master thesis is "A deep learning based compensation of motion and multipath interfernce in Time-of-flight cameras"

## Thesis Abstract 
Range-imaging is the vital technique to obtain the 3D information of the scene in vision systems. Time-of-flight is the range-imaging technology that has gained more scientific attention in recent years. The PMD (photonic mixer device) cameras reconstruct the depth of the observed scene based on the time-of-flight principle.

In this thesis, we attempt to compensate for the motion and multipath interference artifacts on the PMD camera pipeline using deep learning networks. We employ existing synthetic measurements to generate PMD camera’s measurements by modeling the sensor behavior. Conventionally four phases are used to determine the depth of the pixel on a PMD camera pipeline, whereas in this work, we employed two phases (measurements) per frequency. We also developed a parametric noise model to add noise to the PMD raw measurements.

We conducted two experiments (multi reflection and motion experiments) to compensate for the multipath interference and motion artifacts on the PMD camera pipeline. The evaluation of the multi reflection experiment described in the thesis shows that multipath interference can be adequately compensated on the PMD camera pipeline whereas, in the motion experiment, the model did not generalize on the test set. One possible reason for this behavior is due to the presence of occlusion pixels in the images. From these experiments, we can conclude that, with more real-world scenes for model training, we could improve the depth accuracy of the PMD camera using supervised learning approaches.


