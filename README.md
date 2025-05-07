
# ML & DL by Dataset

다양한 데이터셋을 활용한 머신러닝 및 딥러닝 실험을 정리한 저장소입니다.
이 저장소는 구조화 및 비구조화된 데이터를 대상으로 탐색, 프로토타이핑, 모델 벤치마킹을 목적으로 설계되었습니다.

---

## Goals

- 실제 데이터셋에 ML/DL 기법을 적용
- 각 데이터셋별로 베이스라인 모델과 고급 모델 비교
- 전처리, 특성 엔지니어링, 시각화 기법 탐색
- 재사용 가능한 구성 요소 및 주피터 노트북 공유

---

## Project Structure

```
ml-dl-by-dataset/
├── datasets/          # Downloaded or linked datasets
├── notebooks/         # Experiment notebooks per dataset
│   ├── power_usage/   # e.g. FFT + GRU anomaly detection
└── README.md
```

---

## Currently Included Experiments

| Dataset / Domain      | Task                        | Method(s)                        |
|------------------------|-----------------------------|----------------------------------|
| Power Usage (TimeSeries) | Anomaly Detection            | FFT + GRU, Transformer           |
| CIFAR-10 (Image) (예정)  | Classification                | CNN, Data Augmentation           |
| Titanic (Tabular) (예정) | Binary Classification         | Logistic Regression, XGBoost     |
<!--| UCI HAR (Sensor)        | Multiclass Classification     | GRU, LSTM, 1D-CNN                |
| Custom CSVs             | Exploratory + Regression      | Linear, Tree, Ensemble           |
!-->
---

## 🧑‍💻 Author

**Your Name**  
📎 GitHub: [@beomdo-park](https://github.com/beomdo-park)  
📧 Contact: pbeomdo@gmail.com
