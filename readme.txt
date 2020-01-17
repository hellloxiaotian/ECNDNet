Enhanced CNN for image denoising by Chunwei Tian, Yong Xu, Lunke Fei, Junqian Wang, Jie Wen and Nan Luo is published in CAAI Transactions on Intelligence Technology, 2019. It is implemented by Pytorch


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

3. Network architecture 
![RUNOOB 图标](./result/1.png)

4. Experiment results
ECNDNet for BSD68
![RUNOOB 图标](./result/2.png)

ECNDNet for Set12
![RUNOOB 图标](./result/3.png)

Running time of ECNDNet for a noisy image of different sizes
![RUNOOB 图标](./result/6.png)

Visual results of ECNDNet for BSD68
![RUNOOB 图标](./result/4.png)

Visual results of ECNDNet for Set12
![RUNOOB 图标](./result/5.png)
