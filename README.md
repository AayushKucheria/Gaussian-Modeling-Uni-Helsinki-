## Investigating and Enhancing Gaussian Process-based Fouling Detection Systems

## Abstract 

This report presents an investigation into enhancing the computational efficiency of a Gaussian Process (GP)-based fouling detection system for industrial pipes. The original system, implemented in Stan, successfully combined ultrasonic guided waves (UGWs) with GP modeling to detect and reconstruct fouling distributions. Our work explored the feasibility of porting this implementation to GPyTorch, a modern probabilistic programming framework, with the aim of improving computational performance. However, detailed architectural analysis revealed incompatibilities between the system's specialized requirements and standardized framework constraints. This discovery led to a strategic pivot, focusing instead on enhancing the original Stan implementation through neural network approaches. The project's key contributions include a system architecture analysis, development of monitoring systems, and insights into implementing complex probabilistic models.

## Acknowledgements

This work was conducted by Aayush Kucheria in a summer internship in the Multi-source probabilistic inference (MUPI) research group at the University of Helsinki. It was done under the project “AI for Ultrasonics”, with the supervision of Arto Klami and Denys Iablonskyi. 

Full report [here](https://github.com/AayushKucheria/Gaussian-Modeling-Uni-Helsinki-/blob/main/Investigating%20and%20Enhancing%20Gaussian%20Process-based%20Fouling%20Detection%20Systems.pdf).
