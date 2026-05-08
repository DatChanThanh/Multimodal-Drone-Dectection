# Multispectral-Object-Detection

[![PWC](https://img.shields.io/endpoint.svg?url=https://paperswithcode.com/badge/cross-modality-fusion-transformer-for/multispectral-object-detection-on-flir)](https://paperswithcode.com/sota/multispectral-object-detection-on-flir?p=cross-modality-fusion-transformer-for)

[![PWC](https://img.shields.io/endpoint.svg?url=https://paperswithcode.com/badge/cross-modality-fusion-transformer-for/pedestrian-detection-on-llvip)](https://paperswithcode.com/sota/pedestrian-detection-on-llvip?p=cross-modality-fusion-transformer-for)

[![New](https://img.shields.io/badge/2021-NEW-brightgreen.svg)](https://github.com/DocF/multispectral-object-detection/)
![Visitors](https://visitor-badge.glitch.me/badge?page_id=DocF.multispectral-object-detection)
[![GitHub stars](https://img.shields.io/github/stars/DocF/multispectral-object-detection.svg?style=social&label=Stars)](https://github.com/DocF/multispectral-object-detection)




## Abstract
The rapid proliferation of unmanned aerial vehicles (UAVs) has intensified the need for robust surveillance systems capable of distinguishing drones from biological entities like birds in unpredictable environments. While multispectral vision provides a resilient alternative to uni-modal sensors under adverse weather and lighting, existing architectures often struggle with cross-modal feature alignment and noise-induced spatial distortions. This paper proposes Multispectral Attention Context and Receptive-field Network (MACR-Net), an ultra-lightweight multimodal framework designed for high-precision drone detection. MACR-Net introduces a Global-Local Cross-Scale Interaction (GLCI) module to capture multi-scale semantic context and a Multimodal Spatial Cross-Perception (MSCP) mechanism to adaptively fuse RGB-IR streams while preserving target-specific thermal and structural signatures. Furthermore, we design an improved hybrid neck integrating Coordinate-Aware Attention (CAA) and Receptive Field Deformable (RFD) modules to anchor precise spatial coordinates and mitigate geometric distortions. Experimental results on the benchmark Multimodal Drone Detection Dataset demonstrate that MACR-Net outperforms state-of-the-art models, achieving a peak $\mathrm{mAP_{50}}$ of $91.13\%$ and a significant $\mathrm{mAP_{50-95}}$ of $65.77\%$. Remarkably, the architecture maintains an extremely compact footprint with only 2.77M parameters and $0.77$ GFLOPs, establishing an optimal balance between superior detection robustness and real-time feasibility for resource-constrained edge deployment.



## Installation 
Python>=3.6.0 is required with all requirements.txt installed including PyTorch>=1.7

#### Clone the repo
    git clone https://github.com/DatChanThanh/Multimodal-Drone-Dectection
#### Install requirements
 ```bash
$ pip install -r requirements.txt
```

## Dataset


  
