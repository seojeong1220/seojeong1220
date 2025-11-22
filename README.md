#  안녕하세요! 박서정입니다.

📧 Email: seojeong3854@gmail.com

##  Tech Stack
![C](https://img.shields.io/badge/C-00599C?logo=c&logoColor=white)
![C++](https://img.shields.io/badge/C++-00599C?logo=cplusplus&logoColor=white)
![Python](https://img.shields.io/badge/Python-3776AB?logo=python&logoColor=white)
![Arduino](https://img.shields.io/badge/Arduino-00979D?logo=arduino&logoColor=white)
![STM32](https://img.shields.io/badge/STM32-03234B?logo=STMicroelectronics&logoColor=white)
![ESP32](https://img.shields.io/badge/ESP32-20232A?logo=espressif&logoColor=white)
![MySQL](https://img.shields.io/badge/MySQL-005C84?logo=mysql&logoColor=white)
<br>
![OpenCV](https://img.shields.io/badge/OpenCV-5C3EE8?logo=opencv&logoColor=white)
![PyTorch](https://img.shields.io/badge/PyTorch-EE4C2C?logo=pytorch&logoColor=white)
![OpenVINO](https://img.shields.io/badge/OpenVINO-0029FF?logo=openvino&logoColor=white)
![Hailo](https://img.shields.io/badge/Hailo--8-000000?logo=ai&logoColor=white)
![GStreamer](https://img.shields.io/badge/GStreamer-2D8CFF?logo=gstreamer&logoColor=white)
![Git](https://img.shields.io/badge/Git-F05032?logo=git&logoColor=white)
![GitHub](https://img.shields.io/badge/GitHub-181717?logo=github&logoColor=white)
![Qt](https://img.shields.io/badge/Qt-41CD52?logo=qt&logoColor=white)


## Projects
### RFID 기반 보안 모터 제어 시스템

- **프로젝트 설명**  
  RFID 인증과 IR 리모컨 입력을 FreeRTOS 기반 멀티태스킹 구조로 통합하여,  
  **인증된 사용자만 모터를 제어할 수 있는 안전한 임베디드 보안 시스템**을 구축했습니다.  
  UID는 Flash에 저장되어 재부팅 후에도 인증 상태가 유지됩니다.

- **주요 역할**
  - RFID 기반 사용자 인증 처리 및 Flash 저장 기능 구현
  - IR Remote NEC 프로토콜 디코딩 (Interrupt + Timer 기반)
  - 인증 상태 기반 모터 제어 FSM 설계
  - FreeRTOS Task 구조 설계 및 디버깅

- **사용 기술**  
  `C` · `STM32F411` · `FreeRTOS` · `SPI(MFRC522)` · `ULN2003 Stepper Motor` · `UART`

- **관련 링크**  
  - GitHub Repository: *(추가 예정)*  
  - Demo Video: *(선택)*


###  OpenVINO 기반 공장 컨베이어 자동화 시스템

- **프로젝트 설명**  
  OpenVINO로 최적화된 AI 모델을 활용하여 컨베이어 위 제품을  
  **정상 / 부분 불량 / 완전 불량**으로 실시간 분류하는 자동화 시스템을 개발했습니다.  
  Python + PySerial로 AI 연산 결과를 하드웨어 제어와 연동했습니다.

- **주요 역할**
  - 모델 추론 모듈 개발 및 OpenVINO 최적화
  - Tkinter 기반 실시간 시각화 UI 개발
  - PySerial을 이용한 Arduino 기반 컨베이어 동작 연동
  - 검사 결과 자동 저장을 위한 MySQL 연동

- **사용 기술**  
  `Python` · `OpenVINO` · `Tkinter` · `Arduino` · `MySQL` · `PySerial`

- **관련 링크**  
  - GitHub Repository: *(추가 예정)*  

---


