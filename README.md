## Enhanced CNN for image denoising by Chunwei Tian, Yong Xu, Lunke Fei, Junqian Wang, Jie Wen and Nan Luo is published in CAAI Transactions on Intelligence Technology (SCI-IF:7.985), 2019. It is implemented by Pytorch. Besides, it is the best paper for CAAI Transactions on Intelligence Technology in 2018 and 2019. 

## The code of ECNDNet is collected by Profillic (The largest collection of ML models and code to power your projects) at https://www.catalyzex.com/paper/arxiv:1810.11834.

### This code written with Pytorch>=0.4. 
#### 1. Dependences
####   pyTorch(>=0.4)
####   torchvision 
####   openCv for Python
####   HDF5 for Python
####   Python 2.73

#### 2. Test ECNDNet 
####  If the noise level is 15, we will run the following commod:
####         python test.py  --num_of_layers 17 --logdir sigma15/ --test_data Set68 --test_noiseL 15
####    or python test.py  --num_of_layers 17 --logdir sigma15/ --test_data Set12 --test_noiseL 15

####  If the noise level is 25, we will run the following commod:
####        python test.py  --num_of_layers 17 --logdir sigma25/ --test_data Set68 --test_noiseL 25
####    or python test.py  --num_of_layers 17 --logdir sigma25/ --test_data Set12 --test_noiseL 25

####  If the noise level is 25, we will run the following commod:
####    python test.py  --num_of_layers 17 --logdir sigma50/ --test_data Set68 --test_noiseL 50
####   or python test.py  --num_of_layers 17 --logdir sigma50/ --test_data Set12 --test_noiseL 50
#### 3. Network architecture 
#### ![RUNOOB 图标](./result//1.png)

#### 4. Experiment results
#### ECNDNet for BSD68
#### ![RUNOOB 图标](./result/2.png)

#### ECNDNet for Set12
#### ![RUNOOB 图标](./result/3.png)

#### Running time of ECNDNet for a noisy image of different sizes
#### ![RUNOOB 图标](./result/6.png)

#### Visual results of ECNDNet for BSD68
#### ![RUNOOB 图标](./result/4.png)

#### Visual results of ECNDNet for Set12
#### ![RUNOOB 图标](./result/5.png)

### If you cite this paper, please refer to the following format:
#### 1. Tian C, Xu Y, Fei L, et al. Enhanced CNN for image denoising[J]. CAAI Transactions on Intelligence Technology, 2019, 4(1): 17-23.
#### 2. @article{tian2019enhanced,
####  title={Enhanced CNN for image denoising},
####  author={Tian, Chunwei and Xu, Yong and Fei, Lunke and Wang, Junqian and Wen, Jie and Luo, Nan},
####  journal={CAAI Transactions on Intelligence Technology},
####  volume={4},
####  number={1},
####  pages={17--23},
####  year={2019},
####  publisher={IET}
#### }
