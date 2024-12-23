<img src="https://capsule-render.vercel.app/api?type=waving&color=BDBDC8&height=200&section=header&text=My%20Agv%20Line%20Tracing&fontSize=60" />

## :desktop_computer:1차 프로젝트 소개

AI 카이로스 로보틱스에서 주관하는 1차 프로젝트에서 pymycobot사의 My AGV를 활용하여 목적지 주행을 구현합니다.
opencv를 활용하여 color detection을 하고 QR 코드를 사용해서 갈림길을 구분하도록 알고리즘을 설계하였습니다.


## :timer_clock:최종 프로젝트 기간

* 프로젝트 기간: 2024.10.16 ~ 2024.10.24
* AGV Line tracing & QR code detection 알고리즘 구현 
* 아이디어 회의 및 기록
* 최종 발표

## :label:기술 스택

<div align="center">
  
  ![ROS2](https://img.shields.io/badge/ROS2-Fox%20Fuchsia-blue?style=for-the-badge&logo=ros&logoColor=white)
  ![Python](https://img.shields.io/badge/Python-3.8+-blue?style=for-the-badge&logo=python&logoColor=white)
  ![Linux](https://img.shields.io/badge/Linux-Ubuntu-orange?style=for-the-badge&logo=linux&logoColor=white)
  ![OpenCV](https://img.shields.io/badge/OpenCV-Computer%20Vision-critical?style=for-the-badge&logo=opencv&logoColor=white)

</div>


## 최종 결과
1. QR 코드 와 광각카메라를 활용한 Line 인식으로 목적지까지 주행할 수 있다
2. topic, cmd_vel, udp 등을 활용하여 통신을 할 수 있다
