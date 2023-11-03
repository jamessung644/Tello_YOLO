# Tello_YOLO

## Download model, and file 모델 및 파일 설치 

[YOLOv3 Download Link](https://pjreddie.com/darknet/yolo/)

- YOLOv3-tiny


<img width="733" alt="스크린샷 2023-11-03 오전 9 40 23" src="https://github.com/jamessung644/Tello_YOLO/assets/39661528/0adb9657-a00f-49bf-a05e-d7064caf9942">

- YOLOv3-tiny Download .cfg, .weight file




### 설치 방법

-git clone the repository

-깃 클론을 하십시요

```bash
git clone https://github.com/jamessung644/Tello_YOLO
```
## 사용방법

This code is written on Python ver. -3.9.6-. Put downloaded model on Cloned fie, and install following Libraries
이 코드는 파이썬 버전 **3.9.6**에서 작성되었습니다. 설치한 모델을 clone한 파일에 넣은 후, 아래의 라이브러리들을 설치해주세요:
```
!pip install opencv-python
```
```
!pip install djitellopy
```
```
!pip3 install keras
```
```
!pip3 install tensorflow
```
link modle on .ipynb Code. Connect TELLO on wifi and run the code. Make sure it detect objects

모델을 코드에 연결하여 실행한 뒤 텔로의 전원을 켜고 텔로의 와이파이에 연결하여 객체가 제대로 탐지되는지 확인하십시오.
