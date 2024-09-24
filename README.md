**Installation**
Prerequisites:

Make sure you have the following installed:

Python 3.6 or later

PyTorch (version compatible with your CUDA version)

Other requirements

**Cloning the github repository**
!git clone https://github.com/IDEA-Research/DINO.git
%cd DINO

**Other Requirement Installation**
!pip install -r requirements.txt

**Dataset**
This project uses the COCO dataset for evaluation. Ensure that you have the dataset properly downloaded and structured as expected.
COCODIR/
  ├── train2017/
  ├── val2017/
  └── annotations/
  	├── instances_train2017.json
  	└── instances_val2017.json

**Pretrained Model**
    DINO model checkpoint "checkpoint0011_4scale.pth" is used with backbone as ResNet-50
