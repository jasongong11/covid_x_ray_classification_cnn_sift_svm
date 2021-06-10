# STA 208 covid-19 x-ray classification with CNN and SIFT-SVM
This final project is a classification model for Stat 208, Davis 2021 spring class. Professor: Dr. James Sharpna. 

### Team members: Jiawen Liu, Chenze Li, & Xuanjun Gong

In this project, we're going to use CNN and SIFT + SVM for COVID-19 classification based on medical X-Ray Images.

# Files in the zip

figure: all figures corresponding to the results which includes confusion matrix of CNN and ROC curve of SIFT-SVM.    
code: code of CNN models and SIVT-SVM models.  
- cnn: codes for CNN Model
- sift_svm: codes for SIFT-SVM models and the plots for this model

notebooks: Well-documented Report of STA208 Final Project.    
data: the list of train set and test set

### data dir tree

```
data
│   readme.md
│   test.txt  
│   train.txt  
│
└───test
│   │
│   └───positive
│   │   │   image1.png
│   │   │   image2.png
│   │   │   ...
│   │
│   └───negative
│       │   image1.png
│       │   image2.png
│       │   ...
│
└───train
│   │
│   └───positive
│   │   │   image1.png
│   │   │   image2.png
│   │   │   ...
│   │
│   └───negative
│       │   image1.png
│       │   image2.png
│       │   ...
│
```

# Data source

https://www.kaggle.com/andyczhao/covidx-cxr2?select=test.txt

# Contribution

Jiawen Liu: Data introdution + Image Prepocessing + first 4 models of CNN method  
Chenze Li: Introduction + CNN Overview + last 6 models of CNN method + Conclusion  
Xuanjun Gong: SIFT-SVM Overview + SIFT-SVM Model  
