# Team AEQIS
**AEQIS**[*aikɪs*] stands for "**A**uto**e**ncoder-based **Q**EC Scheme **I**deally Suited for a **S**pecific error model."  
It named after 'aegis', the shield of Athena.

## [2022 양자정보경진대회(Quantum Hackathon Korea 2022)](https://github.com/qiskit-community/quantum-hackathon-korea-22)
🎉2022 양자정보경진대회 참가🎉  
🎉Quantum Hackathon Korea 2022 Participant🎉

## TL;DR
- Qauntum Error correction using QCNN 
- Implemnt it by qiskit
- Compare with shor-code

## Introduction
In the current noisy intermediate-scale quantum (NISQ) era, quantum processors are not advanced enough to be fault-tolerant. Quantum Processors are highly sensitive to the environment and may face quantum decoherence, losing their quantumness. Ultimate solution is to achieve the sufficient number and coherence time of qubits through material studies. However, this seems unlikely to happen in the near future. Therefore, as an alternative, it is necessary to devise and utilize error correction techniques.

Meanwhile, motivated by the success of classical convolutional neural networks (CNN) on pattern recognition and the potential of quantum machine learning (QML), several algorithms to implement quantum convolutional neural network (QCNN) have been proposed recently. QCNN based on parameterized quantum circuits (PQC) are, in itself, relatively robust to gate errors; this characteristic makes it possible to obtain meaningful results even with NISQ devices.

In this project, we construct quantum convolutional autoencoders, and then utilize these QCNNs to implement a quantum error correction scheme optimized for a given error model.

## Problem statement
1. **Construct QCNN encoder & decoder**
2. **Optimize the constructed autoencoder for a given error model**
3. **Implement a quantum error correction scheme using the optimized autoencoder**
4. **Demonstrate that the resultant scheme can actually perform error correction**
5. **Compare the performance of the resultant scheme with known quantum codes of
comparable complexity**

## References
- Iris Cong, Soonwon Choi, and Mikhail D. Lukin. Quantum convolutional neural networks. Nature Physics, 15(12):1273–1278, December 2019.

## Members 
- Yunseo Kim [@yunseo-qleap]
- Inhyuk Oh [@OHINHYUK55]

## Mentors
- Dr.HwangYongsoo 

