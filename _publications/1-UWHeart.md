---
title: "UWHeart: Periodicity-Driven Contact-free Heartbeat Rate Estimation Based on IR-UWB Technology"
collection: publications
category: conferences
permalink: /publication/1-UWHeart
venue: 'BIBM'
paperurl: 'https://cyjuejuezi.github.io/yangcao.github.io/files/paper1.pdf'
citation: 'Cao, Yang, et al. "UWHeart: Periodicity-Driven Contact-free Heartbeat Rate Estimation Based on IR-UWB Technology." 2024 IEEE International Conference on Bioinformatics and Biomedicine (BIBM). IEEE, 2024.'
---
Current RF-based solutions have demonstrated that human heartbeat activity induces millimeter-scale chest displacements, changing RF reflection paths and making contact-free heartbeat monitoring possible. However, human heartbeat activity is very weak and can be hidden by out by the body movements or breathing, which poses significant challenges in accurately extracting heartbeat information. To solve this, in this paper we propose a contact-free heartbeat rate estimation system based on the periodic variation feature, namely UWHeart. UWHeart utilizes Impulse Radio-Ultra Wideband (IR-UWB) to capture reflection signals from the monitoring target and outputs the heartbeat rate. This system first filters out the noise unrelated to heartbeat through band-pass filtering. Then, we leverage the periodicity of heartbeat activity to construct autocorrelation matrix features of the denoised signal. Finally, we develop a one-dimensional Temporal Convolutional Network (TCN) model to realize the mapping between the heartbeat autocorrelation features and actual heartbeats, and accurately estimate the heartbeat rate of the monitoring target. We also implement the UWHeart system on commercial IR-UWB equipment to verify our method through a series of experiments, and the experimental results prove the effectiveness of our method.
