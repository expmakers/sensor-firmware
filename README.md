# sensor-firmware

과학 실험실 앱의 무선 센서 펌웨어 업데이트 파일입니다. 앱의 "센서 업데이트" 화면이 이 저장소의 최신 Release를 받아 씁니다.

- 파일은 [Releases](../../releases)에 있습니다. 태그 = 펌웨어 버전 (`v2.0.0`).
- 파일 이름은 센서 종류: `temperature.bin` 온도, `pressure.bin` 기온·기압, `co2.bin` 이산화탄소, `magnetic.bin` 자기장, `distance.bin` 거리.
- 형식: MCUboot 서명 이미지 (CC2340R5 on-chip OAD).

센서는 점검 모드(전원이 켜진 상태에서 버튼을 빠르게 3번)일 때만 업데이트를 받습니다.
