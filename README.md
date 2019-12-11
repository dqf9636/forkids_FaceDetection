# forkids_FaceDetection

2019 2학기 종합설계 [Forkids]

Face Detection & emotion Recognition Module project


## 개발 환경
* Unity 2018.3.7f1
* OpenCV LBP Cascade(C++) - DLL로 변환해서 사용
 * ./lbpcascade_frontalface.xml
 * ./Assets/Plugins/dlllibrary.dll
* Xception (Keras,Python)
  * h5 -> pb -> bytes 파일 변환
  * ML-Agents, Tensorflowsharp
  

## Checkpoint
* 경로 맞추기
 * DLL Library - imread, imwrite
 * Unity ResultSceneScript - File.ReadAllBytes
