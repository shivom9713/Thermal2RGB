# Thermal2RGB (Borrows heavily from TIC-CGAN)
- PyTorch implementation

## Prerequisites
- Linux or macOS
- Python 2 or 3
- NVIDIA GPU + CUDA cuDNN

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
This code borrows heavily from [pytorch-CycleGAN-and-pix2pix](https://github.com/junyanz/pytorch-CycleGAN-and-pix2pix).

## Contact with me
If you have any questions, please contact 
with me. (shivom9713@gmail.com)

## Google Colab Script
This is the link for my google colab Script if you want to check that out
https://colab.research.google.com/drive/1LE4HlIKfHRA9c8DriD2M9JOuTlGq6UgF?usp=sharing

Thanks
