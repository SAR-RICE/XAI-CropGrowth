<div align="center">
<h1>XAI-SAR-CropGrowth</h1>
<h4>The official repository of full cycle rice growth monitoring with dual-pol SAR data and interpretable deep learning. </h4>
<h4>We will update this repository with the publication details and release the code as soon as the related paper is published.</h4>

</div>

## 🔥🔥Highlights🔥🔥
### *1.A full-cycle crop growth monitoring model based on multi-temporal SAR images.*</br>
### *2.Combining crop geometry and physiological activity to characterize crop growth.*</br>
### *3.Interpretable architectures utilize reinforcement learning ideas to select input features and provide feature importance.*</br>
### *4.Scalable support for multi-band images composed of heterogeneous features.*</br>

**0. Main Environments.** </br>
The environment installation procedure can be followed by the steps below (python=3.8):</br>
```
pip install torch==1.13.0 torchvision==0.14.0 torchaudio==0.13.0 --extra-index-url https://download.pytorch.org/whl/cu117
pip install packaging
pip install timm==0.4.12
pip install pytest chardet yacs termcolor
pip install submitit tensorboardX
pip install triton==2.0.0
pip install causal_conv1d==1.0.0  # causal_conv1d-1.0.0+cu118torch1.13cxx11abiFALSE-cp38-cp38-linux_x86_64.whl
pip install scikit-learn matplotlib thop h5py SimpleITK scikit-image medpy yacs
pip install gdal
```
