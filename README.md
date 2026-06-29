# IR Walking Robot Controller
**IR 센서 기반 보행 로봇 제어 보드**

> TCRT5000 IR 센서 입력으로 L293D 모터 드라이버를 구동하는 보행 로봇용 커스텀 PCB.
> Altium으로 스키매틱부터 PCB 레이아웃, 3D 검증까지 전 과정 설계 후 실제 발주했습니다.

<img src="https://github.com/user-attachments/assets/3de65d78-d15e-4007-b9ce-e87b3d9c7d6a" alt="완성 보드 3D 앞면" width="60%">

## 개요
IR 센서로 감지한 신호에 따라 모터를 제어하는 보행 로봇 제어 보드입니다.
브레드보드 프로토타입을 커스텀 PCB로 발전시킨 프로젝트입니다.

## 구성
- **입력**: TCRT5000 IR 센서
- **모터 드라이버**: L293D
- **전원**: 스위치(SW) + 배터리, 로직/모터 전원 분리
- **설계 툴**: Altium Designer

## 완성된 보드

| 앞면 (3D) | 뒷면 (3D) |
|:---:|:---:|
| <img src="https://github.com/user-attachments/assets/3de65d78-d15e-4007-b9ce-e87b3d9c7d6a" alt="3D 앞면" width="100%"> | <img src="https://github.com/user-attachments/assets/1fca7b30-8402-4a0f-b7b2-46a96f7f3967" alt="3D 뒷면" width="100%"> |

## 설계 과정

1. 회로 설계 (스키매틱)
2. 브레드보드 프로토타입 검증
3. PCB 레이아웃 (양면 기판)
4. 3D 뷰로 부품 배치·풋프린트 검증
5. 제조 발주

| 회로 설계 (Schematic) | PCB 레이아웃 |
|:---:|:---:|
| <img src="https://github.com/user-attachments/assets/7c640feb-7df0-462a-ba87-95b0cf137262" alt="스키매틱" width="100%"> | <img src="https://github.com/user-attachments/assets/addc8bd5-7640-4576-b272-991b4e3ec42c" alt="PCB 레이아웃" width="100%"> |

## 프로토타입

브레드보드로 먼저 회로를 검증한 뒤 커스텀 PCB로 발전시켰습니다.

<img src="https://github.com/user-attachments/assets/cedd9e7b-d779-4af0-abb3-345211e9e942" alt="브레드보드 프로토타입" width="60%">

## 회고
- 브레드보드 → 커스텀 PCB 전환 과정을 직접 경험
- Altium으로 스키매틱부터 3D 검증까지 전체 워크플로우 수행
