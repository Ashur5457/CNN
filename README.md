# semiconductor detection CNN
This notebook utilizes the WM-811K wafer map dataset, originally available from the Multimedia Information Research Laboratory at National Taiwan University (http://mirlab.org/dataSet/public/) and sourced from a Kaggle notebook (https://www.kaggle.com/code/ashishpatel26/wm-811k-wafermap/notebook).

In this experiment, we focus on semiconductor defect detection using die size = 533 with data augmentation. We use five different architectures to compare performance:

CNN,
CNN + Random Forest (RF),
CNN + AdaBoost,
CNN + SVM,
ResNet50,
The objective is to evaluate and compare the effectiveness of these models in improving defect detection in semiconductor wafer maps using enhanced image data.
