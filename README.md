# Leather-Anomaly-Detection-CV

가죽 이미지 데이터들을 Custom Dataset으로 만들고, 폴더명을 기반으로 라벨링을 진행 (normal, anomaly)

Autoencoder 모델을 구축하여 정상 데이터만으로 학습을 진행

test dataset에 대한 MSE값을 통해 비정상에 대한 threshold를 선정한 후 confusion matrix로 성능 파악
