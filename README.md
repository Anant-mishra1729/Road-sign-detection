# Road-sign-detection using YOLO-v5

## Description

### [Yolov5](https://github.com/ultralytics/yolov5)
YOLOv5 is a family of **object detection architectures** and models pretrained on the COCO dataset.

### <a href="https://github.com/Anant-mishra1729/Road-sign-detection/blob/main/Updated_YOLOv5_Road_sign_detection.ipynb">Jupyter notebook</a>
### Fails to load try using <a href="https://nbviewer.org/github/Anant-mishra1729/Road-sign-detection/blob/main/Updated_YOLOv5_Road_sign_detection.ipynb">Jupyter notebook</a>
## Getting Started

### Dependencies

* YOLOv5
* Pytorch

### Creating Dataset

* Import dataset in Roboflow 
* Do data preprocessing (Splitting data, Data Augementation) using Roboflow API
* Export generated dataset in YOLOv5 format using API key or download it.

### Model creation and testing

#### Quick testing
* Download pretrained weights Pretrained_weights/best.pt
* Clone YOLOv5 repository
```
git clone https://github.com/ultralytics/yolov5
cd yolov5
pip install -r requirements.txt
python detect.py --weights best.pt --source image.png
``` 

#### Training

* Clone this repository
```
git clone https://github.com/Anant-mishra1729/Road-sign-detection.git
cd Road-sign-detection
python detect.py --weights best.pt --source image.png
```

* Clone YOLOv5 repository
```
git clone https://github.com/ultralytics/yolov5
cd yolov5
``` 

* Use Updated_YOLOv5_Road_sign_detection.ipynb for creating model.
* Store best.pt for future inference.
</details>

> In case of any issue or error go through [Yolov5](https://github.com/ultralytics/yolov5) documentation. 

### Result
<img src = "output.jpeg"/>

## Authors

* [Anant Mishra]("https://github.com/Anant-mishra1729")

## License

This project is licensed under the MIT License - see the LICENSE.md file for details

## Acknowledgments

* [Dataset](https://www.kaggle.com/datasets/andrewmvd/road-sign-detection)
* [Roboflow](https://roboflow.com/)
