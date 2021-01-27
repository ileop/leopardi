---
layout: post
title:  "Publication: Blind image watermarking in Wavelet-domain robust to printing and smart-phone acquisition"
date:   2018-01-28 12:24:30 +0100
categories: unitn master-school computer-vision watermarking
---
# Blind image watermarking in Wavelet-domain robust to printing and smart-phone acquisition
> **IS&T Electronic Imaging 2018 Symposium**, San Francisco, California

[[DOI: https://doi.org/10.2352/ISSN.2470-1173.2018.13.IPAS-262](https://doi.org/10.2352/ISSN.2470-1173.2018.13.IPAS-262)]

* Jan 28, 2018 
* UniTN
* Authors: 
    * Leopardi, Andrea 
    * Soresina, Davide 
    * Marcantonio, Davide 
    * Malacarne, Alain 
    * Conci, Nicola 
    * Boato, Giulia
* **Source**: Electronic Imaging, Image Processing: Algorithms and Systems XVI, pp. 262-1-262-9(9)
* **Publisher**: Society for Imaging Science and Technology


## Abstract 
In these days and age, printed and digital images are the principal means of communication chosen by companies to convey information about their products, since visual contents produce a direct and effective influence on people. At the same time, imagery can be digitally enriched with additional information, imperceptible to the human eye, yet still retrievable using specific software or hardware: this is the case of digital watermarking. In this work, we propose a digital watermarking pipeline that performs information embedding robust to printing operations and enables blind detection from digital acquisitions. We select a watermark from a set of orthogonal antipodal matrices and adaptively insert repeated copies in the horizontal, vertical and diagonal sub-bands of the Wavelet domain. Blind detection is achieved denoising the digitally acquired marked image, retrieving the watermark information from the Wavelet domain, restoring the original scaling with an optimization algorithm and computing a similarity score with each of the possible orthogonal marks. Our system is able to reconstruct the embedded information both in the cases of acquisition from digital and printed watermarked images. It is able to recognize the correct mark among the set of possible messages, even when considering poor-quality printing systems.

![toy-src](/assets/img/2018-01-28-Publication-BlindWatermarking/toys16.jpg)
![toy-emb](/assets/img/2018-01-28-Publication-BlindWatermarking/embedding.png)
![toy-dst](/assets/img/2018-01-28-Publication-BlindWatermarking/monsters2.jpg)
![toy-det](/assets/img/2018-01-28-Publication-BlindWatermarking/detection.jpg)
![mug-src](/assets/img/2018-01-28-Publication-BlindWatermarking/mug27.jpg)
![mug-dst](/assets/img/2018-01-28-Publication-BlindWatermarking/mug3.jpg)

