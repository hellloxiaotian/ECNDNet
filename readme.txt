ECNDNet-Pytorch
This a PyTorch implementation of the CAAI 2019 paper Enhanced CNN for image denoising. It can be downloaded at  https://digital-library.theiet.org/content/journals/10.1049/trit.2018.1054

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