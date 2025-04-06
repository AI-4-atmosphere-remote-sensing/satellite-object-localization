# satellite-object-localization
Localization of Gravity Waves, Bores and Ocean Eddies

How to use this repository:

Update your class labels and data paths in: ..\source_code\yolov5-master\data\custom.yaml

All the proposed appraocahes including MDRC, AaSP, SSCA and all other modules are implemented as "class" in: ..\source_code\yolov5-master\mdoels\common.py

All the state-of-the-art appraocahes (e.g., CBAM, ViT) are implemented as "class" in: ..\source_code\yolov5-master\mdoels\common.py

All the modules (AaSP, MDRC, SSCA, CBAM, ViT, SPP, Tranformer) are imported and called in: ..\source_code\yolov5-master\mdoels\yolo.py

The configuration file is in: ..\source_code\yolov5-master\mdoels\custom_config.yaml
