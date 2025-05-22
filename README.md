# 🧠 BAF-25-1-finance_2

연예인 스캔들 외에도 다양한 요인들이 주가에 미치는 영향을 분석합니다.  
GPT-4o 기반 LLM을 활용한 라벨링 → 통계적 유의성 검정(T-test) → 머신러닝 모델링 → XAI 해석까지,  
전 과정을 하나의 파이프라인으로 구성했습니다.

---

## 📌 프로젝트 개요

- **목표**: 엔터 산업 내 기업들의 주가 변동을 예측하되, **스캔들 외 변수**의 영향을 규명
- **특징**:
  - GPT-4o 기반 **자동 라벨링**
  - T-test 기반 **변수 유의성 검정**
  - XGBoost, LightGBM 등 **모델 기반 예측**
  - SHAP 기반 **XAI 해석**

---

## 🔁 분석 파이프라인

1. **LLM 기반 라벨링**  
   → GPT-4o API를 통해 스캔들에 대한 영향 라벨링 (상승/하락 등)

2. **T-test 유의성 검정**  
   → 주요 변수의 통계적 유의성 평가 (ex. 인기도, 상승세 여부 등)

3. **모델 학습 및 평가**  
   → XGBoost, RandomForest 등으로 주가 반응 분류/회귀

4. **SHAP 기반 XAI 해석**  
   → 예측 결과에 영향을 미친 주요 요인 시각화 및 해석

---
	
## 🧩 사용 기술

### 🧠 모델링  
![XGBoost](https://img.shields.io/badge/XGBoost-FF6600?style=for-the-badge&logo=python&logoColor=white)
![LightGBM](https://img.shields.io/badge/LightGBM-8BC34A?style=for-the-badge&logo=python&logoColor=white)
![RandomForest](https://img.shields.io/badge/RandomForest-005C5C?style=for-the-badge&logo=scikit-learn&logoColor=white)

---

### 📊 통계 분석  
![pandas](https://img.shields.io/badge/pandas-150458?style=for-the-badge&logo=pandas&logoColor=white)
![scipy](https://img.shields.io/badge/scipy-8CAAE6?style=for-the-badge&logo=scipy&logoColor=white)
![T-test](https://img.shields.io/badge/T--test-003366?style=for-the-badge&logo=python&logoColor=white)
![Yahoo Finance](https://img.shields.io/badge/Yahoo_Finance-6001D2?style=for-the-badge&logo=yahoo&logoColor=white)

---

### 💬 LLM API  
![GPT-4o](https://img.shields.io/badge/OpenAI_GPT--4o-412991?style=for-the-badge&logo=openai&logoColor=white)

---

### 📈 XAI  
![SHAP](https://img.shields.io/badge/SHAP-000000?style=for-the-badge&logo=chartdotjs&logoColor=white)
![PDP](https://img.shields.io/badge/Partial_Dependence_Plot-4CAF50?style=for-the-badge&logo=plotly&logoColor=white)
![Feature Importance](https://img.shields.io/badge/Feature_Importance-F57C00?style=for-the-badge&logo=python&logoColor=white)
