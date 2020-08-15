### package to install left

```bash
conda create --name opn python=3.6
source activate opn

pip install opencv-contrib-python pillow

conda install pytorch=0.4.0 cuda90 -c pytorch
conda install torchvision

#### after that

conda install -c anaconda cudatoolkit=9.0
conda install -c anaconda cudnn
pip install matplotlib
pip install tqdm
pip install scipy
```