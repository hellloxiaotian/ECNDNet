ECNDNet-Pytorch
This a PyTorch implementation of the CAAI 2019 paper Enhanced CNN for image denoising. 

This code written with Pytorch>=0.4. 
1. Dependences
  pyTorch(>=0.4)
  torchvision 
  openCv for Python
  HDF5 for Python
  Python 2.73


2. Test ECNDNet 
  If the noise level is 15, we will run the following commod:
         python test.py  --num_of_layers 17 --logdir sigma15/ --test_data Set68 --test_noiseL 15
    or python test.py  --num_of_layers 17 --logdir sigma15/ --test_data Set12 --test_noiseL 15

  If the noise level is 25, we will run the following commod:
        python test.py  --num_of_layers 17 --logdir sigma25/ --test_data Set68 --test_noiseL 25
    or python test.py  --num_of_layers 17 --logdir sigma25/ --test_data Set12 --test_noiseL 25

  If the noise level is 25, we will run the following commod:
    python test.py  --num_of_layers 17 --logdir sigma50/ --test_data Set68 --test_noiseL 50
   or python test.py  --num_of_layers 17 --logdir sigma50/ --test_data Set12 --test_noiseL 50

![RUNOOB 图标](./result/1.png)

### Resluts
### Gaussian gray noisy image denoising
#### Average PSNR (dB) results of different methods on BSD68 dataset with noise levels of 15, 25 and 50.
![RUNOOB 图标](./result/2.png)
#### PSNR (dB) results for different methods on 12 widely used images with noise levels of 15, 25 and 50.
![RUNOOB 图标](./result/3.png)

### Visual results for gray noisy images
#### Denoising results of one image from the BSD68 dataset with noise level 25 using for different methods: (a) original image, (b) noisy image /20.30 dB, (c) WNNM/29.75 dB, (d) E-PLL/29.59 dB, (e) TNRD/29.76 dB, (f) DnCNN/30.16 dB, (g) BM3D/29.53 dB, (h) IRCNN/30.07 dB, and(i) BRDNet/30.27 dB.
![RUNOOB 图标](./result/4.png)
#### Denoising results of image “monar” from Set12 with noise level 50 using different methods: (a) original image, (b) noisy image/14.71 dB, (c) WNNM/26.32 dB, (d) EPLL/25.94dB, (e) TNRD/26.31 dB, (f) DnCNN/26.78 dB, (g) BM3D/25.82 dB, (h) IRCNN/26.61 dB, and(i) BRDNet/26.97 dB.
![RUNOOB 图标](./result/5.png)

### Gaussian color noisy image Denoising
#### Average PSNR (dB) results of different methods on the CBSD68, Kodak24, and McMaster datasets with noise levels of 15, 25, 35, 50, and 75.
![RUNOOB 图标](./result/6.png)

### Visual results for color noisy images
#### Denoising results for one color image from the McMaster dataset with noise level 35: (a) original image/ σ = 35, (b) noisy image/18.62 dB, (c) CBM3D/31.04 dB, (d) FFDNet/31.94dB, and (e) BRDNet/32.25 dB.
![RUNOOB 图标](./result/7.png)