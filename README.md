<div align="center">



<!--
<a align="center" href="https://ultralytics.com/yolov3" target="_blank">
<img width="800" src="https://github.com/ultralytics/yolov5/releases/download/v1.0/banner-api.png"></a>
-->



## <div align="center">HERD-YOLO: an energy-efficient and comprehensive garbage bin overflow detection model based on spiking neural networks</div>
</div>

### Requirements

The code has been validated using pytorch 1.10.1, Python 3.8, CUDA 11.3, and cuDNN 8.2.0_0. You can directly replicate the conda environment using the **environment.yml** file. Additional dependencies are listed in the **environment.txt**.


<details open>
<summary>Install</summary>

```bash
$ git clone https://github.com/Rah-xephon/HERD-Yolo.git
$ pip install -r requirements.txt
```

</details>

### Pretrained Checkpoints

We provide the best and the last trained model based on HERD-YOLO on the GBS dataset.

The relevant parameter files are in the `runs/train`.

### Dataset

You can get our GBS dataset from：[the Garbage Bin Status (GBS) Dataset](https://zenodo.org/records/14711706)


### Training & Spiking Rate
<details open>
<summary>Train</summary>
For training
```python
python train.py
```
</details>


Calculating the spiking rate:

Dependencies can be downloaded from [Visualizer](https://github.com/luo3300612/Visualizer).
```python
python calculate_fr.py
```

### Citation


```shell
@Article{smartcities8020071,
AUTHOR = {Yang, Liwen and Zha, Xionghui and Huang, Jin and Liu, Zhengming and Chen, Jiaqi and Mou, Chaozhou},
TITLE = {Energy-Efficient and Comprehensive Garbage Bin Overflow Detection Model Based on Spiking Neural Networks},
JOURNAL = {Smart Cities},
VOLUME = {8},
YEAR = {2025},
NUMBER = {2},
ARTICLE-NUMBER = {71},
URL = {https://www.mdpi.com/2624-6511/8/2/71},
ISSN = {2624-6511}
}
```

<p>
YOLOv3 is a collection of object detection models pretrained on the COCO dataset, reflecting Ultralytics' open-source exploration into future vision AI techniques. EMS-YOLO is integrated into this framework as well. As an outstanding model in the spiking neural network domain, EMS-YOLO's open-source framework has been utilized in the HERD-YOLO project. We greatly appreciate the research efforts behind EMS-YOLO and kindly ask that you cite their work when applicable.

<b>We greatly appreciate the research efforts behind EMS-YOLO（[BICLab/EMS-YOLO: Offical implementation of "Deep Directly-Trained Spiking Neural Networks for Object Detection" (ICCV2023)](https://github.com/BICLab/EMS-YOLO)） and kindly ask that you cite their work when applicable.</b>
</p>

