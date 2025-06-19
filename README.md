# Helmets and Vests Object Detection

### Project Summary:
This project creates a machine learning model to operate an object detection task on vehicle registration plates, using PyTorch.

---

### Dataset Description:

This dataset consists of `5308` training and `386` validation dataset. Each dataset has images in `.jpg` format and labels in `.txt` format with the `xmin, ymin, xmax, ymax` format. Below are sample images from some of the classes present in the dataset:

TODO: UPDATE - ![](./visuals/sports_classification_image.jpg?raw=true)

---

### Machine Learning Model Architecture:

I used `yolo_v8_m_backbone_coco` as backbone through keras cv and trained it to be able to detect the helmets and vests. 

---

### Training Hyperparameters:

* Epochs: `200`
  
* Initial Learning Rate: `0.002`

* Final Learning Rate: `0.0001`

---

### COCO Detection Evaluation:

```
Class        person AP: 75.95679473876953
Class          vest AP: 65.84795379638672
Class   helmet_blue AP: 72.79402160644531
Class    helmet_red AP: 64.81745147705078
Class  helmet_white AP: 72.9461441040039
Class helmet_yellow AP: 73.53299713134766

Mean Average Precision: 70.98255920410156
```

---

### Inference on Images:

TODO: UPDATE -
TODO: UPDATE -
TODO: UPDATE -

---

### Loss and mAP:

TODO: UPDATE -
TODO: UPDATE -
TODO: UPDATE -

---

### Inference on Video:

https://www.youtube.com/watch?v=Dip1sJsIk5s
