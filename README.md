# Multispectral-Object-Detection




## Abstract
The rapid proliferation of unmanned aerial vehicles (UAVs) has intensified the need for robust surveillance systems capable of distinguishing drones from biological entities like birds in unpredictable environments. While multispectral vision provides a resilient alternative to uni-modal sensors under adverse weather and lighting, existing architectures often struggle with cross-modal feature alignment and noise-induced spatial distortions. This paper proposes Multispectral Attention Context and Receptive-field Network (MACR-Net), an ultra-lightweight multimodal framework designed for high-precision drone detection. MACR-Net introduces a Global-Local Cross-Scale Interaction (GLCI) module to capture multi-scale semantic context and a Multimodal Spatial Cross-Perception (MSCP) mechanism to adaptively fuse RGB-IR streams while preserving target-specific thermal and structural signatures. Furthermore, we design an improved hybrid neck integrating Coordinate-Aware Attention (CAA) and Receptive Field Deformable (RFD) modules to anchor precise spatial coordinates and mitigate geometric distortions. Experimental results on the benchmark Multimodal Drone Detection Dataset demonstrate that MACR-Net outperforms state-of-the-art models, achieving a peak $\mathrm{mAP_{50}}$ of $91.13\%$ and a significant $\mathrm{mAP_{50-95}}$ of $65.77\%$. Remarkably, the architecture maintains an extremely compact footprint with only 2.77M parameters and $0.77$ GFLOPs, establishing an optimal balance between superior detection robustness and real-time feasibility for resource-constrained edge deployment.

## Architecture
![Architecture](https://github.com/DatChanThanh/Multimodal-Drone-Dectection/blob/69eb7b5493d77884281eb463889eaeabf71677c1/architecture(1).png)

Fig. Architecture of the proposed MACR-Net, including (a) detailed stream-wise backbone, (b) GLCI module, (c) MSCP module, and an improved neck with the CAA (d) and RFD (e) modules.

## Installation 
Python>=3.6.0 is required with all requirements.txt installed including PyTorch>=1.7

#### Clone the repo
    git clone https://github.com/DatChanThanh/Multimodal-Drone-Dectection
#### Install requirements
 ```bash
$ pip install -r requirements.txt
```

## Dataset
The dataset can be download on [Google Drive](https://drive.google.com/drive/u/1/folders/15TJjTUcQEKmzlx7vJDgb7TK7XPZJZ5hF) (please report if not available).

If there is any error or need to be discussed, please email to [Thanh-Dat Tran](https://github.com/DatChanThanh) via [trandatt21@gmail.com](mailto:trandatt21@gmail.com).


  
