# Symbol Detection on landmark
Symbol detection is done using state-of-art model of yoloV5. The model successfully achieved good precision and recall. 

## Dataset
-Small real world dataset is used for this problem and object labeling is done using online tool available called LabelImg. [download](https://tzutalin.github.io/labelImg/)
-with Yolo txt labels 

## Pre-processing of Dataset
- resize images into 1280x1280 (multiple of 32)
-we kept the size of training images large because the targetted symbols are already very small but it increases the training time

## Results 
![image](results.jpg)


