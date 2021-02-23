# Thermal2RGB 
- PyTorch implementation
- (Borrows heavily from TIC-CGAN)

## Prerequisites
- Linux or macOS
- Python 2 or 3
- NVIDIA GPU + CUDA cuDNN
## Requirements
- torch>=0.4.0
- torchvision>=0.2.1
- dominate>=2.3.1
- visdom>=0.1.8.3
- scipy==1.1.0

## Getting Started
### Installation
- Install PyTorch and dependencies from http://pytorch.org
- Install python libraries [dominate](https://github.com/Knio/dominate).
```bash
pip install dominate
```

### Testing
- Please download the pre-trained model from [here](https://drive.google.com/open?id=1N_vjU2db2HWWsKiQXqWTujR5_XtOEUjQ) (google drive link), and put it under `./checkpoints/IC_gll_v36/`
- Test the model :
```bash
python test.py --dataroot datasets/ --name IC_gll_v36 --phase test
```
The test results will be saved to here: `./results/`.

## Acknowledgments
This code borrows heavily from https://github.com/Kuangxd/TICCGAN and [pytorch-CycleGAN-and-pix2pix](https://github.com/junyanz/pytorch-CycleGAN-and-pix2pix)

## Contact with me
If you have any questions, please contact 
with me. (shivom9713@gmail.com)

## Google Colab Script
This is the link for my google colab Script if you want to check that out
https://colab.research.google.com/drive/1LE4HlIKfHRA9c8DriD2M9JOuTlGq6UgF?usp=sharing

## Results
![set02_03_I00042_fake_B](https://user-images.githubusercontent.com/56249279/108854293-b64bb780-760d-11eb-9864-7d7195b8a652.png)
![set02_03_I00042_real_A](https://user-images.githubusercontent.com/56249279/108854303-b8ae1180-760d-11eb-9f67-ca0c1b6ae7e4.png)
![set02_03_I00042_real_B](https://user-images.githubusercontent.com/56249279/108854307-b946a800-760d-11eb-9dc1-3ddce6ff7e23.png)
![set02_04_I00768_fake_B](https://user-images.githubusercontent.com/56249279/108854310-b9df3e80-760d-11eb-9dd5-a9bea140a60b.png)
![set02_04_I00768_real_A](https://user-images.githubusercontent.com/56249279/108854316-bb106b80-760d-11eb-8bae-41e114b5fa59.png)
![set02_04_I00768_real_B](https://user-images.githubusercontent.com/56249279/108854321-bba90200-760d-11eb-8570-57f5612e0d7b.png))
Thanks
