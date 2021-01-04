# PremECPE
Emotion Cause Pair Extraction

This repository contains the code and dataset of the following paper:

##Model
An overview of our model is given below:

## Dataset
* The [Dataset](/datasets/sina) we are using is a publicly available dataset released by [(Xia and Ding 2019)](https://www.aclweb.org/anthology/P19-1096.pdf) [[dataset link](https://github.com/NUSTM/ECPE/tree/master/data_combine)]
* The pre-trained word vectors can be found [here](https://github.com/NUSTM/ECPE/blob/master/data_combine/w2v_200.txt).
## Requirements

* Python 3.6
* PyTorch 1.2.0

## Usage
#### 1.Clone or download this repository
```bash

```
#### 2.Download pre-trained word vectors [w2v_200.txt](https://github.com/NUSTM/ECPE/blob/master/data_combine/w2v_200.txt) and place it in the root path. I placed it in root path, so no need to do it!

#### 3.Run our model
```bash
python train.py
```
