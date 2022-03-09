## Env  Install
1. Build Docker ```gltorch`` likee ```https://github.com/NVlabs/nvdiffrast/blob/main/run_sample.sh```
2. Install dependences of [Deep3DFaceRecon_pytorch](https://github.com/sicxu/Deep3DFaceRecon_pytorch) in docker env ```gltorch```

## Face Recon
### BFM Preprocess
1. Transfer original BFM model (```01_MorphableModel.mat```) to face recon model using ```https://github.com/microsoft/Deep3DFaceReconstruction/blob/master/utils.py``` and save its result as ```BFM_model_front.mat```