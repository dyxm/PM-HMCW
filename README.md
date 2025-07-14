# Monocular 3D Object Detection for Proximity Monitoring in Human-Machine Collision Warning Systems on Construction Sites
[Paper](https://arxiv.org/abs/2305.17931) | [Results](#results) | [Dataset & Models](#dataset-and-models) | [Citation](#citation)

## Introduction
<div align="center"><img src="https://github.com/user-attachments/assets/43938578-cb29-4340-ab38-620fcb53d372" alt="Demo 1" /></div>

<p align="justify">
Monitoring workers’ proximities to avoid struck-by hazards has aroused great concern in construction safety management. Existing methods are either too laborious and costly to apply extensively or lack spatial perception for accurate monitoring. This study proposes a novel framework for proximity monitoring using only an ordinary two-dimensional (2D) camera to realize human-machine collision warning, which integrates a monocular three-dimensional (3D) object detection model and a post-processing classification module to identify four proximity categories: <b>Dangerous</b>, <b>Potentially Dangerous</b>, <b>Concerned</b>, and <b>Safe</b>. A new dataset containing 22,500 virtual and real-world construction images with 3D bounding box annotations has been created and publicly released to facilitate system development and evaluation. Experiments show that the implemented system is rapid-response and camera carrier-independent, achieving promising proximity detection performance on both virtual and real-world data, with mean precision, recall, and F1 scores of approximately 0.8, 0.7, and 0.8, respectively, within a range of 50 meters. This study preliminarily reveals the potential and feasibility of proximity monitoring using only a 2D surveillance camera, providing a new, promising, and affordable way for early warning of human-machine collisions.
</p>

**Keywords:** Construction safety, Proximity monitoring, Human-machine collision, Struck-by hazards, Monocular three-dimensional object detection, Computer vision


## Method

- **Research framework**
<div align="center"><img src="https://github.com/user-attachments/assets/96c83d14-6476-4b0c-a849-ef36b5adf7f4" alt="Research framework" /></div>
<br>


- **Proximity definitions**
<div align="center">
      <img src="https://github.com/user-attachments/assets/e38b5a43-a0fa-4721-b5ed-f1ee56ef848d" width=300 alt="Proximity definitions" />
      <img src="https://github.com/user-attachments/assets/e4f00887-9428-4379-a56f-0003b10ec27a" width=500 alt="Proximity definitions" />
</div>
</br>

## Results

<div align="center"><img src="https://github.com/user-attachments/assets/43938578-cb29-4340-ab38-620fcb53d372" alt="Demo 1" /></div>
<div align="center">Demo 1. On virtual data. R_exclusion=7, R_warning=14</div>
<br>

<div align="center"><img src="https://github.com/user-attachments/assets/1003de4c-acae-411c-89e7-13bac0b01ac0" alt="Demo 2" /></div>
<div align="center">Demo 2. On real-world data. R_exclusion=4, R_warning=8</div>
<br>

<div align="center"><img src="https://github.com/user-attachments/assets/86c69376-b88d-4420-9e88-7da85180fcda" alt="Demo 3" /></div>
<div align="center">Demo 3. On real-world data. R_exclusion=4, R_warning=8</div>
<br>

<div align="center"><img src="https://github.com/user-attachments/assets/c8e03760-e59e-4283-b53c-ed4c094d1d0f" alt="Demo 4" /></div>
<div align="center">Demo 4. On real-world data. R_exclusion=4, R_warning=8</div>
<be>


## Dataset and Models

The dataset and trained models can be accessed at:
- the [TeraBox](https://1024terabox.com/s/18QLXYfaaMEVhrU7JOLVkyQ)
- and, the [Baidu Netdisk](https://pan.baidu.com/s/19T5X1D9QTbmSgLClUz4YsA) using the code **wnp5**


## Citation
Please cite our work if you find the dataset useful.
```
@article{DING2025111722,
      title = {Monocular three-dimensional object detection for proximity monitoring in human-machine collision warning systems on construction sites},
      journal = {Engineering Applications of Artificial Intelligence},
      volume = {159},
      pages = {111722},
      year = {2025},
      issn = {0952-1976},
      doi = {https://doi.org/10.1016/j.engappai.2025.111722},
      url = {https://www.sciencedirect.com/science/article/pii/S0952197625017245},
      author = {Yuexiong Ding and Qiong Liu and Ankang Ji and Heng Li and Xiaowei Luo},
}

@misc{ding2023monocular2dcamerabasedproximity,
      title={Monocular 2D Camera-based Proximity Monitoring for Human-Machine Collision Warning on Construction Sites}, 
      author={Yuexiong Ding and Xiaowei Luo},
      year={2023},
      eprint={2305.17931},
      archivePrefix={arXiv},
      primaryClass={cs.CV},
      url={https://arxiv.org/abs/2305.17931}, 
}
```
