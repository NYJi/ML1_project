# Korean Melon Disease Detection
#### - Korean melon disease diagonosis using CycleGAN, Compare between CNN and SVM

## 📌BACKGROUND
- Plant disease is one of the causes of reducing crop yields. Korean melon also is decreasing because of plant disease.
  Thus, for solving this problems, we suggest the plant disease diagnosis model using machine learning.

<br>

## 📌DATASET
- 시설 작물 질병 진단 이미지 By AIHUB
- 참외 노균병 및 참외 흰가루병 이미지 사용 

<br>

## 📌DATA AUGMENTATION
Healthy leaf images are more than milions, but two types of disease image were offered images about 400 (Downy mildew, White powdery mildew).
![image](https://github.com/zangyook/korean_melon_disease_detection/assets/100524867/438c9474-51e9-433d-8a39-890a56f96a72)
Each class used 450 images in order to prevent imbalance data problem. For data augmentation we designed CycleGAN model and generated the fake plant disease. 
![image](https://github.com/zangyook/korean_melon_disease_detection/assets/100524867/f9856ef6-3036-4749-aff9-59a610d0b6c6)

## 📌MODEL
- Classification model : 1) SVM 2) CNN

  <br> 
## 📌RESULT
![image](https://github.com/zangyook/korean_melon_disease_detection/assets/100524867/8877cd2b-d8e1-431b-989a-a62eaf5ca113)
- In the augmented cases, The accuracy was greatly improved.
![image](https://github.com/zangyook/korean_melon_disease_detection/assets/100524867/daa3ab5a-9e17-4b34-bd2a-57db893b53e3)


