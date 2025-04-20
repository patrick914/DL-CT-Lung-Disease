# 🩺 CT 이미지 기반 폐 질환 분류 딥러닝 프로젝트

이 프로젝트는 흉부 CT 이미지 데이터를 활용해 딥러닝 모델로 **COVID-19**와 **폐암**을 자동으로 분류하는 것을 목표로 합니다.  
Transfer Learning(VGG16)과 커스텀 CNN 모델을 비교하며, 의료 영상 기반 AI 모델의 가능성을 탐구합니다.

---

## 📁 프로젝트 구조

```
DL-CT-Lung-Disease/
├── data/                  # 데이터 설명 및 출처
├── notebooks/             # 분석 코드 (Jupyter Notebooks)
├── results/               # 예측 결과 이미지 (예: Grad-CAM, Confusion Matrix)
├── README.md              # 프로젝트 설명 파일
└── requirements.txt       # 필요한 Python 패키지
```

---

## 🧠 사용 모델

- ✅ 커스텀 CNN 모델
- ✅ 전이학습 기반 VGG16 모델 (Keras 제공)
- ✅ 활성화 함수: ReLU
- ✅ 최적화 알고리즘: Adam
- ✅ 손실 함수: Binary/Categorical Crossentropy

---

## 🗂️ 데이터 출처

- [AI Hub - COVID-19 CT 이미지](https://aihub.or.kr/)
- [Cancer Imaging Archive - 폐암 CT](https://www.cancerimagingarchive.net/)

> ⚠️ **데이터 용량 문제로 GitHub에는 직접 포함하지 않았습니다.**  
> 대신 위 링크를 통해 다운로드 가능합니다.

---

## 📈 결과 예시

- 높은 정확도 및 AUC로 COVID/폐암 예측 가능
- Grad-CAM으로 CT 이미지에서 질병 영역 시각화
- 전이학습(VGG16) 모델이 커스텀 CNN보다 성능 우수

---

## 🧪 실행 방법

```bash
pip install -r requirements.txt
jupyter notebook
# notebooks 폴더의 .ipynb 파일을 열어 실행
```

---

## 📌 시사점 및 다음 과제

- 전이학습 기반 모델은 적은 데이터로도 높은 성능을 낼 수 있음
- 다양한 폐 질환 분류, 더 큰 데이터셋 적용 가능
- 의료 영상에 대한 explainability 기술 적용 중요

---

## 🙋‍♂️ 개발자

- 강종현  
- Contact: (이메일 또는 GitHub 링크 추가 가능)
