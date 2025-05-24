# satellite-object-localization

### This repo provides supplments for the Localization of Gravity Waves, Bores and Ocean Eddies.
#### Kindly consider citing this work if you have utilized any of its ideas or code, in whole or in part. Your acknowledgment would be greatly appreciated and serve as motivation for us to continue producing high-quality work in the future.

Mostafa, Seraj Al Mahmud, Omar Faruque, Chenxi Wang, Jia Yue, Sanjay Purushotham, and Jianwu Wang. "gWaveNet: Classification of Gravity Waves from Noisy Satellite Data Using Custom Kernel Integrated Deep Learning Method." In International Conference on Pattern Recognition, pp. 164-180. Springer, Cham, 2025. (You can find the Camera Ready version available in [arXiv](https://www.arxiv.org/abs/2505.05599). Bibtex are as follows:

```
@article{mostafa2025enhancing,
  title={Enhancing Satellite Object Localization with Dilated Convolutions and Attention-aided Spatial Pooling},
  author={Mostafa, Seraj Al Mahmud and Wang, Chenxi and Yue, Jia and Hozumi, Yuta and Wang, Jianwu},
  journal={arXiv preprint arXiv:2505.05599},
  year={2025}
}
```

How to use this repository:

Update your class labels and data paths in: ..\source_code\yolov5-master\data\custom.yaml

All the proposed appraocahes including MDRC, AaSP, SSCA and all other modules are implemented as "class" in: ..\source_code\yolov5-master\mdoels\common.py

All the state-of-the-art appraocahes (e.g., CBAM, ViT) are implemented as "class" in: ..\source_code\yolov5-master\mdoels\common.py

All the modules (AaSP, MDRC, SSCA, CBAM, ViT, SPP, Tranformer) are imported and called in: ..\source_code\yolov5-master\mdoels\yolo.py

The configuration file is in: ..\source_code\yolov5-master\mdoels\custom_config.yaml
