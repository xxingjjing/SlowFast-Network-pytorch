## Run the demo on your own data
1.Clone the repository
```bash
git clone https://github.com/xxingjjing/SlowFast-Network-pytorch.git
```
2.Download Yolo v3 model: 
https://pan.baidu.com/s/1tT2uzI44KD3zzAgMskU1Aw

3.Download DeepSort re-id model: 
https://pan.baidu.com/s/1D1_Lw_lq-O75xFX-zFEEbg

4.Download Pre-trained SlowFast Network model: 
https://pan.baidu.com/s/17GLB2k3VhPgRsVCadVmjaA

5.Modify the model path and your video path in video_demo.py.

6.Run cam_demo.py.


## Requirements
python 3  
PyTorch >= 1.0  
tensorboardX 
OpenCV

## Install


### 先到support目录安装一个扩展
cd support && python setup.py install

### 以下包提示缺什么就装什么
conda install pytorch==1.2.0 torchvision==0.4.0 cudatoolkit=10.0 -c pytorch
conda install -c menpo opencv
conda install matplotlib
conda install -c anaconda pandas
conda install -c anaconda scipy
conda install -c anaconda scikit-learn
## Code Reference:
[1] https://github.com/Guocode/SlowFast-Networks/  
[2] https://github.com/potterhsu/easy-faster-rcnn.pytorch 

