# 🎓 Data Scientist Portfolio

---

## 📊 Project

### Project 1: Credit Card Fraud Detection

**Objective** <br/>
어떤 모델이 데이터를 축소하거나 증강하였을때 가장 뛰어난 검출능력을 보이는지 확인하였습니다.

**Technologies Used** <br/>
- Dimensionality Reduction: PCA, tSNE, UMAP
- Dimensionality Augmentation: SMOTE, BorderLineSMOTE, ADASYN
- Machine Learning Models: RandomForest, XGBoost, CatBoost, LightGBM
- Deep Learning Models: TensorFlow, Pytorch 

**Key Results** <br/>
Dimesionality Reduction과 Augmentation 중에 뭐가 더 모델의 성능에 좋을까 비교해보기 위해서 
다양한 머신러닝 모델과 딥러닝 모델을 활용하였습니다. 
그 결과 어떤 방식으로 어떤 모델을 사용했을때 가장 성능이 좋은지 순위표를 만들 수 있었습니다.

**URL** <br/>
https://github.com/Minyst/ML_DL_Portfolio_KR/tree/main/Credit%20Card%20Fraud%20Detection

---

### Project 2: YOLOv10 Pretrained model vs Custom model

**Objective** <br/>
Pretrained YOLOv10과 Custom YOLOv10중 어떤 것이 더 성능이 좋은지 비교합니다.

**Technologies Used** <br/>

- Model: YOLOv10
- Package: ultralytics, supervision, cv2

**Key Results** <br/>
비디오를 캡처한 후 여러 프레임을 생성하였고 <br/>
각 프레임을 모델로 학습시킨 후, 이러한 프레임들을 다시 하나의 비디오로 만들었습니다. <br/>
Pretrained model의 경우, 모델을 그대로 사용하여 예측을 수행했지만 <br/>
Custom model의 경우, 기존의 YOLOv10 가중치를 사용하여 준비된 데이터를 학습시키고, <br/>
그 결과 나온 최고의 가중치를 최종 모델의 가중치로 선택한 후 이를 예측에 사용했습니다. <br/>
이 과정은 릴레이 레이스와 비슷합니다.

Pretrained model과 Custom model을 비교했을 때, 상당한 차이가 있었습니다. <br/>
다양한 클래스의 이미지로 지속적으로 학습된 Custom model은 자동으로 인식하는 Pretrained model보다 <br/>
클래스 예측 범위가 더 넓었지만, 정확도는 Pretrained model에 비해 훨씬 낮았습니다.

**URL** <br/>
https://github.com/Minyst/ML_DL_Portfolio_KR/tree/main/YOLO

---

### Project 3: Detectron2 Pretrained model vs Custom model

**Objective** <br/>
Pretrained detectron2와 Custom detectron2중 어떤 것이 더 성능이 좋은지 비교합니다.

**Technologies Used** <br/>
- Model: Detectron2
- Package: detectron2, cv2

**Key Results** <br/>
detectron2는 yolov10이랑 거의 똑같지만 차이점이 두가지 있습니다.
첫번째, detectron2는 yolov10과 달리 faster_rcnn weights를 사용합니다.
두번째, yolov10에서는 pretrained와 custom이 결과가 조금 다르게 나왔지만 
detectron은 차이가 느껴지지 않았습니다.

**URL** <br/>
https://github.com/Minyst/ML_DL_Portfolio_KR/tree/main/Detectron

---

### Project 4: AI Cover - RVC

**Objective** <br/>
RVC 모델을 활용해 한 가수의 목소리로 다른 가수의 노래를 부르게 하는 것 

**Technologies Used** <br/>
- Model: RVC

**Key Results** <br/>
이 프로젝트는 5가지 과정으로 나누어서 설명할 수 있습니다.
첫번째, 다운받아온 youtube music을 음성과 배경음악으로 split합니다.
두번째, 모델이 더 잘 학습할 수 있도록 음성을 여러개로 slice합니다.
세번째, RVC_pretrained를  download하고.
네번째, train합니다.
다섯번째, 가수가 다른 노래를 부르는 음악파일을 생성합니다.

생각보다 자연스러운 음악이 생성되어서 놀라웠습니다.
디테일한 설정도 할 수 있는데 전문가가 있다면 더욱 더 싱크로율과 완성도가 높아질 것으로 기대됩니다.

**URL** <br/>
https://github.com/Minyst/ML_DL_Portfolio_KR/tree/main/AI%20Cover

---

### Project 5: CNN - CIFAR-10

**Objective** <br/>
CIFAR-10 데이터를 활용해서 
Tensorflow와 Pytorch로 복잡한 CNN 구성해보기

**Technologies Used** <br/>
- Models : TensorFlow, Pytorch
- CNN Process : Data Augmentation, Conv2d, Padding, Batch Normalization, Pooling, Dropout, Flatten 

**Key Results** <br/>
Tensorflow와 Pytorch로 할 수 있는 CNN의 모든 과정을 담았습니다.

**URL** <br/>
https://github.com/Minyst/ML_DL_Portfolio_KR/tree/main/CNN

---

## 📈 Skills

- **프로그래밍 언어**: Python, SQL
- **데이터 시각화**: Matplotlib, Seaborn, Tableau
- **머신 러닝 & 딥러닝**: Scikit-Learn, TensorFlow, Pytorch
- **데이터 전처**: Pandas, NumPy
- **데이터베이스**: MySQL
- **도구**: Jupyter Notebook

---

## 🛠️ Tools & Technologies


---



---

## 📫 Contact

문의 사항이나 협업 기회가 있으시면 언제든지 연락해 주세요:

- **Email**: [username@example.com](mailto:username@example.com)
- **LinkedIn**: [linkedin.com/in/username](https://www.linkedin.com/in/username)
- **GitHub**: [github.com/username](https://github.com/username)

---


