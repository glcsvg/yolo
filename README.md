# yolo
# CDCL

This is the code repository for the paper:  
**Cross-Domain Complementary Learning with Synthetic Data for Multi-Person Part Segmentation**  
Kevin Lin, Lijuan Wang, Kun Luo, Yinpeng Chen, Zicheng Liu, Ming-Ting Sun
[[Paper](https://arxiv.org/abs/1907.05193)] [[Demo Video](https://youtu.be/8QaGfdHwH48)]


## Install Deps

```
pip install -r requiremet.txt
```
is developed Python 3 CUDA 10.0, CUDNN 7.4.1.5, Tensorflow 1.10.0, Keras 2.2.4
 
 
# Weights
## Download the pre-trained model

Please download the pre-trained model using the following command:

 ```
 cd CDCL_human-part
 fetch_data.sh
```

### xxx

We suggest creating a new conda environment for setting up the relevant dependencies. After installing [Anaconda](https://docs.anaconda.com/anaconda/install/linux/) on your machine, please run the following command:

    $ conda env create -f cdcl_environment.yaml

After creating the environment, you just need to activate the environment and continue running the demo code.  

    $ conda activate cdcl

## Possible options

```
python train.py --help
```

<b>[Usage]</b><p>
```Bash
python cdlc_cam.py --gpus [N] --model [mmodel name] --output_folder[output file] --scale [SCALE]

```
