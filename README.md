### This is the pytorch version repo. for “Towards Invading Deep Crowd-counting Models via Density Variation-based Adversarial Patches”.

### Prerequisites
PyTorch: 1.10.2 + cu113

### Datasets
ShanghaiTech Dataset: https://drive.google.com/file/d/16dhJn7k4FWVwByRsQAEpl9lwjuV03jVI/view

NWPU Dataset: https://mailnwpueducn-my.sharepoint.com/personal/gjy3035_mail_nwpu_edu_cn/_layouts/15/onedrive.aspx?id=%2Fpersonal%2Fgjy3035%5Fmail%5Fnwpu%5Fedu%5Fcn%2FDocuments%2F%E8%AE%BA%E6%96%87%E5%BC%80%E6%BA%90%E6%95%B0%E6%8D%AE%2FNWPU%2DCrowd&ga=1

JHU-Crowd++ Dataset: http://www.crowd-counting.com/

### Models and its checkpoints
MCNN: https://github.com/CommissarMa/MCNN-pytorch

CAN: https://github.com/weizheliu/Context-Aware-Crowd-Counting

BL: https://github.com/ZhihengCV/Bayesian-Crowd-Counting

DM-Count: https://github.com/cvlab-stonybrook/DM-Count

SASNet: https://github.com/TencentYoutuResearch/CrowdCounting-SASNet

DGCC: https://github.com/ZPDu/Domain-general-Crowd-Counting-in-Unseen-Scenarios

MP-Count: https://github.com/Shimmer93/MPCount

### Adversarial patch generation methods in crowd counting

APAM: https://github.com/harrywuhust2022/Adv-Crowd-analysis

PAP: https://github.com/shunchang-liu/PAP-Pytorch

### Transferable adversarial attacks

MIM: https://github.com/dongyp13/Non-Targeted-Adversarial-Attacks

DIM: https://github.com/cihangxie/DI-2-FGSM

TIM: https://github.com/dongyp13/Translation-Invariant-Attacks

SI-NIM: https://githuba.com/JHL-HUST/SI-NI-FGSM

We recommend using the repo. at https://github.com/Harry24k/adversarial-attacks-pytorch

### Training Process

1: put data into 'data_path',

2: generate density maps refering to (https://github.com/CommissarMa/MCNN-pytorch),

3: download the pre-trained models' checkpoints to 'model_path',

4: run dicm_attack.py to generate adversaial patches

5: evaluate the generated samples in the 'save_path' folder
