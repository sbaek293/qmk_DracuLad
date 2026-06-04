# qmk_DracuLad

DracuLad 기반으로 구성한 QMK 키보드 설정입니다.
This repository contains a DracuLad-based QMK setup.

- MCU: ProMicro RP2040 (`development_board: promicro_rp2040`)
- 엔코더: 좌/우 모두 활성화
- 우측: Pimoroni Trackball 활성화
- Vial 포팅: `pimoroni_vial` 키맵 제공

빌드 예시 (QMK Firmware 트리 내부에서):

```bash
qmk compile -kb draculad -km pimoroni_vial
```
