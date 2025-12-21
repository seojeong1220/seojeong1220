#  안녕하세요! 박서정입니다.



## Education
- **가천대학교 전자공학과** 졸업
- **[Intel] Edge AI SW Academy** (8기) (2025.07 ~ 2026.01) [수강중]



## Projects
### 1. RFID 기반 보안 모터 제어 시스템 
[<img src="https://img.shields.io/badge/GitHub-Repository-181717?style=flat&logo=github&logoColor=white">](https://github.com/seojeong1220/Project-RFIDSecurityMotorSystem)


- **프로젝트 설명**  
  RFID 인증과 IR 리모컨 입력을 FreeRTOS 기반 멀티태스킹 구조로 통합하여,  
  **인증된 사용자만 모터를 제어할 수 있는 안전한 임베디드 보안 시스템**을 구축했습니다.  
  UID는 Flash에 저장되어 재부팅 후에도 인증 상태가 유지됩니다.

- **사용 기술**  
  `C` · `STM32F411` · `FreeRTOS` · `SPI(MFRC522)` · `ULN2003 Stepper Motor` · `UART`


### 2. OpenVINO 기반 공장 컨베이어 자동화 시스템 🏅 Intel Edge AI Academy 프로젝트 경진대회 – 우수상 수상작
[<img src="https://img.shields.io/badge/GitHub-Repository-181717?style=flat&logo=github&logoColor=white">](https://github.com/seojeong1220/Project-SmartFactory)


- **프로젝트 설명**  
공장 생산라인에서 이동하는 제품의 **불량 여부(QC 스티커 유무, 오염도 비율)**를 자동으로 분류하는  
AI 기반 스마트 팩토리 모형 시스템을 구현했습니다.
OpenVINO로 최적화된 모델을 사용하여  정상 / 부분 불량 / 완전 불량을 실시간으로 판단하며, 결과는 Arduino + 포토센서 + 액추에이터와 연동되어 자동 분류됩니다.  
버튼 하나로 여러 모델을 한 레일에서 구별할 수 있는 **멀티 모델 팩토리 시스템**으로 구현되었습니다.

- **사용 기술**  
  `Python` · `OpenVINO` · `YOLOX` · `SegNext` · `EfficientNet` · `Arduino` · `MySQL` · `PySerial` · `ONNX`

### 3. 출입 감지 기반 실시간 보안 모니터링 시스템 
[<img src="https://img.shields.io/badge/GitHub-Repository-181717?style=flat&logo=github&logoColor=white">](https://github.com/seojeong1220/Project-InstructionDetectionsystem)


- **프로젝트 설명**  
Button Sensor + Wi-Fi + Bluetooth 기반으로  
**침입을 감지해 관리실에서 실시간으로 상태를 확인할 수 있는 보안 모니터링 시스템**을 구현했습니다.  
STM32·ESP-01·HC-06·Arduino·Raspberry Pi를 연동하여 로그 저장 및 실시간 경보 알림이 가능한 구조로 설계했습니다. 

**사용 기술**  
`C` · `STM32` · `ESP-01(AT Command)` · `HC-06 Bluetooth` · `Arduino` · `LCD/Buzzer/LED` · `Raspberry Pi` · `MariaDB` · `PHP`

### 4. 지하식 소화전 불법주차 방지 음성 안내 시스템
[<img src="https://img.shields.io/badge/GitHub-Repository-181717?style=flat&logo=github&logoColor=white">](https://github.com/seojeong1220/Project-FireParkingAlertSystem)


- **프로젝트 설명**  
실제 지하식 소화전의 구조적 취약점을 기반으로,
**불법 주정차를 자동으로 감지하고 경고하는 IoT 안전 시스템**을 구현했습니다.
차량이 소화전 위에 주차하거나 사람이 밟고 지나갈 경우 음성 안내 + LED 점등이 자동으로 동작하여 소방차의 소화전 접근성을 높입니다.
 
**사용 기술**  
`Arduino` · `Solar Panel`

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

