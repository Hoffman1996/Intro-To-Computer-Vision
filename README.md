# Final Project – Introduction to Computer Vision

This project represents the culmination of the knowledge and practical skills gained throughout the **Introduction to Computer Vision** course. It challenged me to implement a full end-to-end object detection pipeline under real-world constraints, with an emphasis on dataset creation, model training, and performance evaluation.

### Project Summary

The core objective was to **train an object detection model without relying on human-labeled data**. To achieve this, the project utilized the **Florence-2** model, a large vision-language transformer, to automatically generate annotations for the **Flickr image dataset**. The task focused on detecting two specific classes:  
- `person`  
- `pet` (defined as the union of `dog`, `cat`, and `horse`)

A smaller model — chosen from architectures such as YOLO, Faster R-CNN, RetinaNet, or EfficientDet — was then trained using this synthetic dataset, with additional augmentations applied to improve generalization. The project also discussed how **Test-Time Augmentations (TTA)** and **ensemble methods** could be used to validate the generated dataset, though their implementation was not required.

### Key Learning Outcomes
- Gained hands-on experience with **self-supervised dataset creation**
- Understood trade-offs in object detection architecture and framework selection
- Learned to use modern tools like **Detectron2**, **MMDetection**, and **YOLO (Ultralytics)**
- Practiced model evaluation using metrics such as **mAP@50 and mAP@50-95**
- Reflected on dataset quality, model robustness, and areas for future improvement
