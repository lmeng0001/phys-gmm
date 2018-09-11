# phys-gmm
This package contains the inference implementation for the "Physically Consistent Bayesian Non-Parametric Mixture Model" (PC-GMM) proposed in [1]. This approach is used to fit GMM to trajectory data while ensuring that the points clustered in each Gaussian represent/follow some linear dynamics.; i.e. not only should they be close in "Euclidan"-position space but they should following the same direction. This GMM fitting approach is useful for learning Dynamical Systems (DS) that follow the Linear Parameter Varying (LPV) formulation, as introduced in [1,2]




**References**    
[1] Figueroa, N. and Billard, A. (2018) A Physically-Consistent Bayesian Non-Parametric Mixture Model for Dynamical System Learning. In Proceedings of the 2nd Conference on Robot Learning (CoRL). Accepted.
[2] Mirrazavi Salehian, S. S. (2018) Compliant control of Uni/ Multi- robotic arms with dynamical systems. PhD Thesis.  

**Contact**: [Nadia Figueroa](http://lasa.epfl.ch/people/member.php?SCIPER=238387) (nadia.figueroafernandez AT epfl dot ch)
