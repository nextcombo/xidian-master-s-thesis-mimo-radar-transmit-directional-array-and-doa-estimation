# [Xidian Master's Thesis] MIMO Radar Transmit Directional Array and DOA Estimation [Attached MATLAB Code]

This paper applies the Nonlinear Least Squares Direction of Arrival (DOA) synthesis method to MIMO radar directional synthesis. It first decomposes the covariance matrix of the transmitted waveform, then constructs a nonlinear least squares cost function to optimize the decomposed components, thereby maximally approaching the desired directional synthesis pattern. Compared with existing MIMO radar directional synthesis methods, this paper's method can flexibly adjust the transition band width and main lobe amplitude of the synthesised pattern through a penalty function, and has smaller mean square error. Additionally, a subspace DOA estimation method for MIMO radar models is studied, which directly transforms the data covariance matrix based on over-estimation theory to construct projection matrices for the signal subspace and noise subspace. This method does not require feature decomposition of the data covariance matrix or knowledge of the source number, and is applicable to coherent source problems, maintaining good estimation performance in low SNR and multi-target scenarios. Simulation experiments verify the effectiveness of this method.

Table of Contents:

I. Introduction
Traditional phased array radars only utilize the receiving aperture, and research on this aspect has been relatively mature, making it difficult to achieve significant breakthroughs. MIMO radar can achieve breakthroughs in the field of radar by utilizing multiple transmit and receive antenna configurations, parallel transmission in space, and simultaneous use of both transmit and receive apertures, aiming to solve a series of challenges currently faced by radar. Compared to traditional radar, MIMO radar has several advantages [2^]:
1. RCS average approximates constant. Since targets are composed of many small scattering bodies, slight changes in the distance and azimuth of the target will cause changes in its scattering cross section (RCS), i.e., changes in the energy of the reflected waves. MIMO radar utilizes the statistical characteristics of the target's RCS, allowing the target's scattering cross section to be approximately constant with MIMO radar, improving detection performance.
2. Due to increased spatiotemporal and waveform resources, strong electromagnetic interference can be suppressed through signal processing in the spatial, time, and waveform domains.
③ The multiple transmit antennas of MIMO radar illuminate different sides of the target, detecting more target feature information and enhancing target recognition capability.
④ In theory, MIMO radar does not need scanning and can accumulate coherently over a long period, improving signal-to-noise ratio.
⑤ It has good anti-stealth performance. MIMO radar utilizes the scattering characteristics from different angles, while stealthy aircraft cannot achieve stealth at any angle, so there is always a large radar cross section (RCS) detected.
⑥ It has strong anti-destroy capabilities. The spacing between the transmit antennas of MIMO radar is large, making it difficult to be destroyed simultaneously, even if several transmit antennas are lost, the impact on system performance is minimal.
MIMO radar, as a new radar system, has attracted widespread attention both domestically and internationally since its proposal. However, most research on MIMO radar is still in the theoretical stage, with many theoretical issues waiting to be resolved. Finding the optimal orthogonal phase coding and developing more robust high-resolution algorithms are directions that require further research in the field of MIMO radar. Therefore, as a promising new radar system, MIMO radar is very worth our attention and research.
This article studies the problem of direction estimation in MIMO radar and some practical problems encountered in the formation of transmit beams. The main contents are summarized as follows:
Chapter 2 mainly introduces the basic principles of MIMO radar and the two array structures of MIMO radar's signal model. Starting from the traditional array signal model, it deduces the generalized MIMO radar model; then, based on this general model, it derives the signal model of dual-base station MIMO radar that meets the requirements of transmit spatial diversity and the single-base station MIMO radar with the advantage of virtual aperture extension.
Chapter 3 deduces the transmit directional pattern of MIMO radar and studies a method for forming the transmit directional pattern of MIMO radar.
The comprehensive method is based on the correlation matrix R of the transmitted waveform. By decomposing R, a nonlinear least squares optimization algorithm is employed to optimize the factors of R, maximizing the match between the transmitted directional pattern and the target directional pattern. This method has been compared with other literature-based methods for integrated approaches, validating its effectiveness and superiority in controlling main lobe ripple and transition band width.
Chapter 4 mainly studies the DOA estimation algorithm for MIMO radar. It introduces the basic methods of current DOA estimation and then researches a subspace algorithm based on this. This algorithm does not require feature decomposition of the data covariance matrix or known source number, completely avoiding the troubles that MUSIC method must face when dealing with small and large eigenvalues in general non-ideal situations. Moreover, this method is applicable to both coherent sources and non-coherent sources, and can still accurately estimate the DOA of targets under low signal-to-noise ratio conditions.
Chapter 5 summarizes the work of the entire paper and provides some perspective analysis on related research topics.
Principle of MIMO radar DOA estimation
MATLAB simulation results

## Images

![[Master's thesis from Xi'an University of Technology] Total Sum of MIMO Radar Transmitted Directional Pattern and DOA Estimation [Attached MATLAB Code]](01.jpg)
![[Master's thesis from Xi'an University of Technology] Total Sum of MIMO Radar Transmitted Directional Pattern and DOA Estimation [Attached MATLAB Code]](02.jpg)
![[Master's thesis from Xi'an University of Technology] Total Sum of MIMO Radar Transmitted Directional Pattern and DOA Estimation [Attached MATLAB Code]](03.jpg)
![[Master's thesis from Xi'an University of Technology] Total Sum of MIMO Radar Transmitted Directional Pattern and DOA Estimation [Attached MATLAB Code]](04.jpg)
![[Master's thesis from Xi'an University of Technology] Total Sum of MIMO Radar Transmitted Directional Pattern and DOA Estimation [Attached MATLAB Code]](05.jpg)
![[Master's thesis from Xi'an University of Technology] Total Sum of MIMO Radar Transmitted Directional Pattern and DOA Estimation [Attached MATLAB Code]](06.jpg)
![[Master's thesis from Xi'an University of Technology] Total Sum of MIMO Radar Transmitted Directional Pattern and DOA Estimation [Attached MATLAB Code]](07.jpg)
![[Master's thesis from Xi'an University of Technology] Total Sum of MIMO Radar Transmitted Directional Pattern and DOA Estimation [Attached MATLAB Code]](08.jpg)
![[Master's thesis from Xi'an University of Technology] Total Sum of MIMO Radar Transmitted Directional Pattern and DOA Estimation [Attached MATLAB Code]](09.jpg)
![[Master's thesis from Xi'an University of Technology] Total Sum of MIMO Radar Transmitted Directional Pattern and DOA Estimation [Attached MATLAB Code]](10.jpg)
![[Master's thesis from Xi'an University of Technology] Total Sum of MIMO Radar Transmitted Directional Pattern and DOA Estimation [Attached MATLAB Code]](11.jpg)

<!-- PAYMENT_BLOCK -->

## Get this dataset

- Payment link (Stripe): [Buy now](https://buy.stripe.com/3cs8yP7sY87d0vu9AB)
- Payment QR code: ![Payment QR code](pay.png)

<!-- /PAYMENT_BLOCK -->
