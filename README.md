# Bayesian Framework for Quantum Algorithms in Qiskit

## _Team: Baye's Baes_

**Team members:** _Conrad Haupt, Annie Ho, Shawal Kassim, Eric-Muthemba Kiarie, Roman Peters_

**Coach:** _Ismail Akhalwaya_


This project was developed for the Qiskit Camp Africa in 2019. It shows that Bayesian Inference can be integrated into Qiskit using the QInfer toolkit. This notebook showcases a proof-of-concept for the Iterative Quantum Phase Estimation circuit where the phase of the unitary is determined through a Sequential Monte-Carlo sampling scheme over an arbitrary prior distribution. The experimental results used for updating the posterior come from a QASM simulation of the IQPE circuit at iteration 1. The presentation is given in the PDF while the proof of concept is shown in the notebook.

[1] N. Wiebe and C. E. Granade, “Efficient Bayesian Phase Estimation,” Phys. Rev. Lett., vol. 117, no. 1, p. 010503, Jun. 2016.

[2] C. Granade et al., “QInfer: Statistical inference software for quantum applications,” Quantum, vol. 1, p. 5, Apr. 2017.

[3] H. Abraham et al., Qiskit: An Open-source Framework for Quantum Computing. 2019.