# Agriculture-Application-Robot
Some of the algorithms used in developing the robot are available here.

## Quick Guide
The four required files for running in your enivroment are 
* frozen_inference_graph.pb 
* labelmap.pbtxt
* utils folder
* python program 

## Plant-weed detection


### Installation
```shell
git clone https://github.com/ummadiviany/Agriculture-Application-Robot

cd Agriculture-Application-Robot/plant-weed

```


### Testing in your computer

``` shell
python Plant-weed-detection.py
```

### Results
A Image with single ground plant is taken as a example to test the model.The model is working perfect with 100 accuracy.

![GroundNut detected Image](/plant-weed/output.png)



## Aerial Plant detection


### Installation
```shell
git clone https://github.com/ummadiviany/Agriculture-Application-Robot

cd Agriculture-Application-Robot/aerial-plant-detection

```


### Testing in your computer
``` shell
python aerial-plant-detection.py
```


### Results
An image from the given test data is taken as example to test our trained model. 

![Input aerial image](/aerial-plant-detection/input.JPG)

The output image show us the accuracy of model. It detected almost all plant correctly .

![Output aerial image with plants detected and given bounding boxex](/aerial-plant-detection/output.jpg)



