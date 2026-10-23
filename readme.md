# Channel Estimation in Near-Field XL-MIMO Systems with Enhanced Perception: An Appendix with MATLAB Code

Introduction: The development of large-scale multi-input multi-output (MIMO) systems has sparked the vision of reshaping and controlling the transmission environment for propagation electromagnetic (EM) waves. This vision has led to advanced technologies, such as uncorrelated large-scale MIMO and reconfigurable intelligent surfaces (RIS), which enhance service coverage and eliminate dead zones in wireless networks [2] [3]. Particularly, for centralized large-scale antenna array deployment strategies like RIS and ultra-large MIMO (XL-MIMO) [4], their large aperture significantly expands the boundary of the near-field region [5]. While this transformation in XL-MIMO systems can achieve effective beam focusing to achieve higher transmission rates [6], it introduces new challenges in wireless system design.
In the actual near-field region, the spherical wavefront of the electromagnetic wave deviates from the plane wavefront typically assumed in the far-field counterpart. This introduces two degrees of freedom (DoF), namely, angle and distance, to accurately describe spatial characteristics, thereby complicating the task of channel estimation (CE) [7]. Moreover, the surge in antenna elements in an XL-MIMO array not only greatly increases the dimensionality of the channel matrix to be estimated but also makes it impractical to deploy dedicated RF chains for each antenna element [8]. Therefore, hybrid analog-digital antenna array architectures with limited number of RF chains have been widely adopted [9]. However, this solution only allows low-dimensional baseband samples per time slot, posing additional challenges in precisely reconstructing high-dimensional channels in an XL-MIMO system.
In this paper, we propose a perception-enhanced CE scheme for near-field XL-MIMO systems operating in Time Division Duplex (TDD) mode, and our contributions are summarized as follows:
·We introduce a cost-effective XL-MIMO transceiver architecture that uses off-the-shelf power sensors to measure the received power of the electromagnetic wave. This architecture not only enhances the perception capability of the near-field propagation environment but also ensures practical and efficient implementation in real-world scenarios.
· We propose a time-reversal algorithm to estimate the positions of UEs and scattering bodies. Unlike traditional positioning methods [12], [23], [25], our proposed algorithm does not require any baseband samples and can be implemented through efficient fast Fourier transform (FFT) computations.
· We utilize the estimated position coordinates from the CE process to derive a new dictionary by exploring the eigenvalue decomposition (EVD) of the near-field channel matrix. Notably, the column-wise orthogonality inherent in the feature vectors naturally reduces the size of the dictionary to its minimum. We also found that the codewords in the suggested dictionary admit the form of Discrete Longitudinal Evolution (DPLE).
· Numerical results show that this time-reversal algorithm achieves precise positioning without baseband sampling. Moreover, the proposed dictionary based on DPLE, combined with the estimated positions of UEs and scattering bodies, achieves satisfactory accuracy while requiring only a small amount of baseband samples, reducing it by up to 77% compared to traditional DFT and spherical wave dictionaries, resulting in significantly less stringent storage requirements.
The article includes illustrations.
This paper introduces a cost-effective XL-MIMO transceiver structure and proposes a time-reversal-based near-field positioning algorithm based on DPLE. Compared to widely adopted algorithms, the proposed positioning scheme achieves precise performance without high-power ADC for baseband sampling and is computationally efficient due to FFT implementation. To fully leverage the estimated positions, we further propose a new near-field XL-MIMO CE based on DPLE. By leveraging the EVD associated with the near-field channel, the proposed DPLE-based dictionary outperforms traditional DFT and spherical wave dictionaries in terms of channel sparsity, CE NMSE, storage requirements, and more importantly, the required baseband samples. The proposed sensing-enhanced CE method provides an ideal solution for the following aspects: a low-complexity but efficient CE scheme with minimal hardware requirements and training overhead.
MATLAB simulation results

## Images

![(Channel Estimation)Enhanced Channel Estimation in Near-Field XL-MIMO Systems [with MATLAB Code]](01.jpg)
![(Channel Estimation)Enhanced Channel Estimation in Near-Field XL-MIMO Systems [with MATLAB Code]](02.jpg)
![(Channel Estimation)Enhanced Channel Estimation in Near-Field XL-MIMO Systems [with MATLAB Code]](03.jpg)
![(Channel Estimation)Enhanced Channel Estimation in Near-Field XL-MIMO Systems [with MATLAB Code]](04.jpg)
![(Channel Estimation)Enhanced Channel Estimation in Near-Field XL-MIMO Systems [with MATLAB Code]](05.jpg)
![(Channel Estimation)Enhanced Channel Estimation in Near-Field XL-MIMO Systems [with MATLAB Code]](06.jpg)
![(Channel Estimation)Enhanced Channel Estimation in Near-Field XL-MIMO Systems [with MATLAB Code]](07.jpg)
![(Channel Estimation)Enhanced Channel Estimation in Near-Field XL-MIMO Systems [with MATLAB Code]](08.jpg)
![(Channel Estimation)Enhanced Channel Estimation in Near-Field XL-MIMO Systems [with MATLAB Code]](09.jpg)
![(Channel Estimation)Enhanced Channel Estimation in Near-Field XL-MIMO Systems [with MATLAB Code]](10.jpg)
![(Channel Estimation)Enhanced Channel Estimation in Near-Field XL-MIMO Systems [with MATLAB Code]](11.jpg)

<!-- PAYMENT_BLOCK -->

## Get this dataset

- Payment link (Stripe): [Buy now](https://buy.stripe.com/3cs8yP7sY87d0vu9AB)
- Payment QR code: ![Payment QR code](pay.png)

<!-- /PAYMENT_BLOCK -->
