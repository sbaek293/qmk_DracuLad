# qmk_DracuLad

DracuLad 기반이며 `vial-qmk` 루트에서 `5h100ky/dracula` 타겟으로 빌드되는 QMK 키보드 설정입니다.
This repository contains a DracuLad-based QMK setup built as the `5h100ky/dracula` target from the `vial-qmk` root.

- MCU: ProMicro RP2040 (`development_board: promicro_rp2040`)
- 엔코더: 좌/우 모두 활성화
- 우측: Pimoroni Trackball 활성화
- Vial 포팅: `vial` 키맵 제공

빌드 예시 (`vial-qmk` 루트에서):

```bash
make 5h100ky/dracula:vial
```
