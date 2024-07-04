# 🎓 데이터 분석가 포트폴리오

제 데이터 분석가 포트폴리오에 오신 것을 환영합니다! 이곳에서는 저의 프로젝트, 기술 및 데이터 분석 분야에 대한 기여를 확인하실 수 있습니다.

---

## 📊 Project

### Project 1: 신용카드 사기 검출
**Objective**: 어떤 모델이 데이터를 축소하거나 증강하였을때 가장 뛰어난 검출능력을 보이는지 확인하였습니다.

**Technologies Used**:
- 차원축소: PCA, tSNE, UMAP
- 차원증강: SMOTE, BorderLineSMOTE, ADASYN
- 머신러닝모델: RandomForest, XGBoost, CatBoost, LightGBM
- 딥러닝모델: TensorFlow, Pytorch 

**Key Results**:
Dimesionality Reduction과 Augmentation 중에 뭐가 더 모델의 성능에 좋을까 비교해보기 위해서 
다양한 머신러닝 모델과 딥러닝 모델을 활용하였다. 
그 결과 어떤 방식으로 어떤 모델을 사용했을때 가장 성능이 좋은지 순위표를 만들 수 있었다.

url: https://github.com/Minyst/ML_DL_Portfolio/tree/main/Credit%20Card%20Fraud%20Detection



---

### Project 2: YOLOv10 Pretrained model vs Custom model

**Objective**: Pretrained YOLOv10 model과 Custom YOLOv10 model 중 어떤 것이 더 성능이 좋은지 비교합니다.

**Technologies Used**:

- 모델: YOLOv10
- 패키지: ultralytics, supervision, cv2

**Key Results**:
비디오를 캡처한 후 여러 프레임을 생성하였습니다. <br/>
각 프레임을 모델로 학습시킨 후, 이러한 프레임들을 다시 하나의 비디오로 만들었습니다. <br/>
Pretrained model의 경우, 모델을 그대로 사용하여 예측을 수행했습니다. <br/>
Custom model의 경우, 기존의 YOLOv10 가중치를 사용하여 준비된 데이터를 학습시키고, <br/>
그 결과 나온 최고의 가중치를 최종 모델의 가중치로 선택한 후 이를 예측에 사용했습니다. <br/>
이 과정은 릴레이 레이스와 비슷합니다.

Pretrained model과 Custom model을 비교했을 때, 상당한 차이가 있었습니다. <br/>
다양한 클래스의 이미지로 지속적으로 학습된 Custom model은 자동으로 인식하는 Pretrained model보다 <br/>
클래스 예측 범위가 더 넓었지만, 정확도는 Pretrained model에 비해 훨씬 낮았습니다.

URL: https://github.com/Minyst/ML_DL_Portfolio/tree/main/YOLOv10%20Pretrained%20vs%20Custom

---

## 📈 기술

- **프로그래밍 언어**: Python, SQL
- **데이터 시각화**: Matplotlib, Seaborn, Tableau
- **머신 러닝 & 딥러닝**: Scikit-Learn, TensorFlow, Pytorch
- **데이터 조작**: Pandas, NumPy
- **데이터베이스**: MySQL
- **도구**: Jupyter Notebook

---

## 🛠️ 도구 및 기술

![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)
![SQL](https://img.shields.io/badge/SQL-4479A1?style=for-the-badge&logo=postgresql&logoColor=white)
![Tableau](https://img.shields.io/badge/Tableau-E97627?style=for-the-badge&logo=tableau&logoColor=white)

---



---

## 📫 연락처

문의 사항이나 협업 기회가 있으시면 언제든지 연락해 주세요:

- **이메일**: [username@example.com](mailto:username@example.com)
- **LinkedIn**: [linkedin.com/in/username](https://www.linkedin.com/in/username)
- **GitHub**: [github.com/username](https://github.com/username)

---


