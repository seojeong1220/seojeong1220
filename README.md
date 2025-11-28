#  안녕하세요! 박서정입니다.

## Tech Stack

![C](https://img.shields.io/badge/C-00599C?logo=c&logoColor=white)
![C++](https://img.shields.io/badge/C++-00599C?logo=cplusplus&logoColor=white)
![Python](https://img.shields.io/badge/Python-3776AB?logo=python&logoColor=white)
![Arduino](https://img.shields.io/badge/Arduino-00979D?logo=arduino&logoColor=white)
![STM32](https://img.shields.io/badge/STM32-03234B?logo=STMicroelectronics&logoColor=white)
![ESP32](https://img.shields.io/badge/ESP32-20232A?logo=espressif&logoColor=white)
<br>

![MySQL](https://img.shields.io/badge/MySQL-005C84?logo=mysql&logoColor=white)
![OpenCV](https://img.shields.io/badge/OpenCV-5C3EE8?logo=opencv&logoColor=white)
![PyTorch](https://img.shields.io/badge/PyTorch-EE4C2C?logo=pytorch&logoColor=white)
![OpenVINO](https://img.shields.io/badge/OpenVINO-0029FF?logo=openvino&logoColor=white)
![Hailo](https://img.shields.io/badge/Hailo--8-000000?logo=ai&logoColor=white)
<br>

![GStreamer](https://img.shields.io/badge/GStreamer-2D8CFF?logo=gstreamer&logoColor=white)
![Git](https://img.shields.io/badge/Git-F05032?logo=git&logoColor=white)
![GitHub](https://img.shields.io/badge/GitHub-181717?logo=github&logoColor=white)
![Qt](https://img.shields.io/badge/Qt-41CD52?logo=qt&logoColor=white)


## Projects
### 1. RFID 기반 보안 모터 제어 시스템 
[<img src="https://img.shields.io/badge/GitHub-Repository-181717?style=flat&logo=github&logoColor=white">](https://github.com/seojeong1220/Project-RFIDSecurityMotorSystem)


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


### 2. OpenVINO 기반 공장 컨베이어 자동화 시스템 
[<img src="https://img.shields.io/badge/GitHub-Repository-181717?style=flat&logo=github&logoColor=white">](https://github.com/seojeong1220/Project-SmartFactory)


- **프로젝트 설명**  
공장 생산라인에서 이동하는 제품의 **불량 여부(QC 스티커 유무, 오염도 비율)**를 자동으로 분류하는  
AI 기반 스마트 팩토리 모형 시스템을 구현했습니다.
OpenVINO로 최적화된 모델을 사용하여  정상 / 부분 불량 / 완전 불량을 실시간으로 판단하며, 결과는 Arduino + 포토센서 + 액추에이터와 연동되어 자동 분류됩니다.  
버튼 하나로 여러 모델을 한 레일에서 구별할 수 있는 **멀티 모델 팩토리 시스템**으로 구현되었습니다.

- **주요 역할**
  - YOLOX / SegNext / EfficientNet 기반 모델 학습 및 OpenVINO 최적화
  - Segmentation 기반 Stain Ratio(오염 비율) 계산 알고리즘 구현
  - Python–Arduino 간 PySerial 통신으로 포토센서·액추에이터 제어
  - 생산 이력 자동 저장을 위한 MySQL 연동
  - 카메라 환경 세팅(화이트밸런스·노출 등) 및 데이터셋 트러블슈팅

- **사용 기술**  
  `Python` · `OpenVINO` · `YOLOX` · `SegNext` · `EfficientNet` · `Arduino` · `MySQL` · `PySerial` · `ONNX`

### 3. 출입 감지 기반 실시간 보안 모니터링 시스템 
[<img src="https://img.shields.io/badge/GitHub-Repository-181717?style=flat&logo=github&logoColor=white">](https://github.com/seojeong1220/Project-InstructionDetectionsystem)


**프로젝트 설명**  
Button Sensor + Wi-Fi + Bluetooth 기반으로  
**침입을 감지해 관리실에서 실시간으로 상태를 확인할 수 있는 보안 모니터링 시스템**을 구현했습니다.  
STM32·ESP-01·HC-06·Arduino·Raspberry Pi를 연동하여  
로그 저장 및 실시간 경보 알림이 가능한 구조로 설계했습니다.

- **주요 역할**
- 버튼 센서 이벤트 기반 침입 감지 로직 구현  
- ESP-01(AT Command)을 활용한 Wi-Fi 데이터 전송 처리  
- Raspberry Pi 웹 서버 + MariaDB 기반 출입 로그 저장 기능 구축  
- Bluetooth(HC-06) → Arduino 연동을 통한 LCD·Buzzer·LED 상태 알림 표시  

**사용 기술**  
`C` · `STM32` · `ESP-01(AT Command)` · `HC-06 Bluetooth` · `Arduino` · `LCD/Buzzer/LED` · `Raspberry Pi` · `MariaDB` · `PHP`

## Education
- **가천대학교** 전자공학과 졸업
- [Intel] Edge AI SW Academy (8기) (2025.07 ~ 2026.01) [수강중]
