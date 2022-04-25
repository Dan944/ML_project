# ML_project
Based on 853 pictures and three classes (wear mask, no mask, wear mask incorrectly). We get 80.9 mAP in the validation dataset with more than 100FPS.

## Prepare
### Download data
* Down load data from [my drive](https://drive.google.com/drive/folders/1Npgkvz3keXpVjxguD8YYr_BYqyyvaVBW?usp=sharing) 
* Unzip the file in `root`, replace `datasets` directory via unzip file
* Format like this 
<p align="center">
  <img src="show/file.png" />
</p>

### Environment
* We strongly recommend you to run in `Google Colab` or other Linux system.
* Install necessary part
```
pip install -r requirements.txt
```

## Run!
### Inference
* Open `demo.ipynb`
* Set path
* Run the cells
### Validation
* Just continue running the cells
### Train
* Please use GPU and run the cell
* If you want to freeze, please train with freeze firstly, then train without freeze based on former weights.

## Effect show
<p align="center">
  <img src="show/demo1.jpg" width="480"/>
</p>
<p align="center">
  <img src="show/demo5.jpg" width="480"/>
</p>
<p align="center">
  <img src="show/demo2.jpg" width="280"/>
</p>


## Reference
https://github.com/ultralytics/yolov5  
https://github.com/spacewalk01/yolov5-face-mask-detection
