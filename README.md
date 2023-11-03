# Tello_YOLO

## 모델 및 파일 설치 

[YOLO 공식 페이지](https://pjreddie.com/darknet/yolo/)

- YOLOv3-tiny

### 설치 방법

- **한국어**: 깃 클론을 하십시요
- **English**: git clone the repository

```bash
git clone https://github.com/jamessung644/Tello_YOLO
```
## 사용방법

이 코드는 파이썬 버전 -3.9.6-에서 작성되었습니다. 설치한 모델을 clone한 파일에 넣은 후, 아래의 라이브러리들을 설치해주세요:
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
모델을 코드에 연결하여 실행한 뒤 텔로의 전원을 켜고 텔로의 와이파이에 연결하여 객체가 제대로 탐지되는지 확인하십시오.
