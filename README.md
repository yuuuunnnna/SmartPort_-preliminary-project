# SmartPort_preliminary-project

스마트선박항만_예비프로젝트

항만 내 주요 시설 7개 클래스 정의
---------------------------------------------
- Container 이미지 : 1,107   객체 수 : 48,957
- Crane  이미지 : 872 객체 수 : 7,716
- Forklift 이미지 : 1,359 객체 수 : 3,057
- Person 이미지 : 2,409 객체 수 : 2,362
- Ship 이미지 : 1,918 객체 수 : 1,889
- Stacker 이미지 : 1,570 객체 수 : 1,589
- Truck 이미지 : 1,592 객체 수 : 1,492

합계  9,851 객체 수 67,062 구축

image Auamentation 활용하여 총 약 23,000 장 구축

Yolo5s, Yolo5m, Yolov5L, Yolov7, Faster-RCNN 학습 후 모델 비교 하여 성능 좋은 모델 선택

-- Yolov7 모델 선택하여 서비스 구축함

-- Gradio 라이브러리 사용하여 웹 서비스 구축

