# Thermal2RGB 
- PyTorch implementation
- Borrows heavily from TIC-CGAN
- Dataset Used : KAIST MultiSpectral Dataset

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

### Testing
- Please download the pre-trained model from [here](https://drive.google.com/open?id=1N_vjU2db2HWWsKiQXqWTujR5_XtOEUjQ) (google drive link), and put it under `./checkpoints/IC_gll_v36/`
- Test the model :
```bash
python test.py --dataroot datasets/ --name IC_gll_v36 --phase test
```
The test results will be saved to here: `./results/`.

## Acknowledgments
This code borrows heavily from https://github.com/Kuangxd/TICCGAN and [pytorch-CycleGAN-and-pix2pix](https://github.com/junyanz/pytorch-CycleGAN-and-pix2pix)

## Contact me
If you have any questions, please write an issue or contact me at shivom9713@gmail.com

## Google Colab Script
This is the link for my google colab Script if you want to check that out
https://colab.research.google.com/drive/1LE4HlIKfHRA9c8DriD2M9JOuTlGq6UgF?usp=sharing

## Results of TIC-GAN (day-time infrared to day-time RGB translation)
![gitff](https://user-images.githubusercontent.com/56249279/108856964-9bc70d80-7610-11eb-9339-6e21ad66eb0f.PNG)

## (Night-time infrared to day-RGB translation results)
# Extreme Low light Night-time Performance Results using our proposed approaches 
![Night time performance](https://user-images.githubusercontent.com/56249279/151710411-b114eae3-725e-4064-8473-b6194029c77d.PNG)

# Good light Night-time performance Results using our proposed approaches
![Model Performance](https://user-images.githubusercontent.com/56249279/151710333-58385456-3d02-48ee-838b-06ecbb8f27b8.PNG)



