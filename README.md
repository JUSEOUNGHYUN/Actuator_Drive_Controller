# 📛 Actuator_Drive_Controller

📍 프로젝트 기간 : 2022.11.18 ~ 2023.03.02 (4개월)

# 📌 개요
- VR Finger Motion인 ultraleap과 unity와 연동하여 ultraleap finger와 unity 3d obejct와 닿을때마다 펌웨어 server COM에게 Finger Frequency, pulse width의 데이터를 보내는 프로그램을 구현했습니다.
- 성균관대학교 과제
- Touch, Throw, Bounce 총 3개의 모드가 있습니다.

# 🛠️ 기술
<img src="https://img.shields.io/badge/C Sharp-239120?style=flat-square&logo=C Sharp&logoColor=white"/> <img src="https://img.shields.io/badge/Unity-000000?style=flat-square&logo=Unity&logoColor=white"/> <img src="https://img.shields.io/badge/Ultraleap-40AEF0?style=flat-square&logo=Ultraleap&logoColor=white"/>

# 📺 기본 화면
- IP,Port Canvas, Touch, Throw, Bounce, Init_Object, UI Activate

https://github.com/JUSEOUNGHYUN/FIMWOMANAGER/assets/80812790/fc8bfcac-b9d2-441b-8fe9-a56235c1c4ea

# 🎏 기능 구현
- Unity와 Ultraleap과 연동 후 데이터 송수신
- Unity와 펌웨어 COM과 NetworkSocket으로 Server-Client 통신
- COM = Server , Unity(PC) = Client
- COM과 송수신할때 보내는 데이터 수치를 쉽게 볼수 있게 Unity에서 Canvas(UI) 개발
- 3D Object인 농구공을 Ultraleap을 (Touch, Throw, Bounce) 3개의 모드 구현
- DataLog 파일 생성 및 Write

## 1. Unity Ultraleap 연동
https://github.com/JUSEOUNGHYUN/FIMWOMANAGER/assets/80812790/a454dc05-50c7-4671-9609-0c6c25dcb7c6

## 2. Throw Mode
https://github.com/JUSEOUNGHYUN/FIMWOMANAGER/assets/80812790/f76d7e20-6b06-4e55-88e5-a583da834d16


# 🎥 시연 동영상
https://github.com/JUSEOUNGHYUN/FIMWOMANAGER/assets/80812790/bf44583b-846a-4c2e-83ec-198a0f790967


