# SmartPort_preliminary-project

스마트선박항만_예비프로젝트

- 항만 내 주요 시설 7개 클래스 정의
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


- Yolo5s, Yolo5m, Yolov5L, Yolov7, Yolov7 tiny, Faster-RCNN 학습 후 모델 비교 하여 성능 좋은 모델 선택

 - Yolov5
 <img width="770" alt="image" src="https://user-images.githubusercontent.com/73158757/203328820-c35d81b0-6ef3-441f-8af9-20f13fb0762e.png">

 - Yolov7
 <img width="474" alt="image" src="https://user-images.githubusercontent.com/73158757/203328884-56cd2e24-3054-403c-b4a9-e8622bb6637c.png">

- Yolov7_tiny
<img width="485" alt="image" src="https://user-images.githubusercontent.com/73158757/203328972-c6c8e854-855b-4088-9a3b-94ed28490c28.png">

- Faster RCNN
<img width="500" alt="image" src="https://user-images.githubusercontent.com/73158757/203329075-cd681a9c-c216-473b-9ce1-74c37f2488a0.png">


 <img width="480" alt="image" src="https://user-images.githubusercontent.com/73158757/203328568-8beaee05-c1ac-4e98-a4a4-eb10ef7ccbd1.png">


- 기능 1 실시간 카메라 침입탐지 -> 화면 내 사람 탐지 시 사람 수 카운트 및 smtp 사용하여 메일 발송
<img width="515" alt="image" src="https://user-images.githubusercontent.com/73158757/203329479-7f5ab0eb-b580-422d-a574-eb49d9916fae.png">


- 기능 2 Yolov7 모델 선택하여 서비스 구축함 ->  Gradio 라이브러리 사용하여 웹 서비스 구축
<img width="471" alt="image" src="https://user-images.githubusercontent.com/73158757/203328183-fcac31a6-b968-40d4-adb6-ba2f8859642b.png">



