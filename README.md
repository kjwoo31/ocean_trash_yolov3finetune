# ocean_trash_yolov3finetune  

해양 침적 쓰레기 이미지 데이터 해커톤의 프로토타입 제작.  
코드와 필요한 소스를 정리하였다.  

### 목적  

 선박과 바다생물에 위협이 되는 낚시, 어업 관련 쓰레기를 이미지 인식 기술을 통해 찾는 기술이다. 이 기술은 위험도가 높은 쓰레기가 많은 지역을 파악하고, 먼저 처리할 수 있게 돕는다. 그리고 낚싯줄, 그물 등으로 인한 선박 사고와 유령어업 문제를 예방한다.  

### 내용  

1. data : training data, annotation - 대회 데이터, [JAMSTEC 데이터](http://www.godac.jamstec.go.jp/catalog/dsdebris/metadataList?lang=en)  
2. Detection : Keras implementation of YOLOv3 (Tensorflow backend)  
3. Yolo_Detection_oceantrash.ipynb : 프로토타입 코드 내용  

### 사용 방법  

Yolo_Detection_oceantrash.ipynb를 google drive에 옮겨 colab 실행  

### 참고한 코드 내용  

[DLCV](https://github.com/chulminkw/DLCV)  
[keras-yolo3](https://github.com/qqwweee/keras-yolo3)  
[labelImg](https://github.com/tzutalin/labelImg)  
