# Charybdis

통합 트랙볼이 있는 인체공학적 키보드.

고품질의 맞춤형 부품으로 제작된 완전한 마우스 대체 솔루션.

4x6, 3x6 "미니", 3x5 "나노" 버전이 있습니다.

다른 반쪽에는 [Scylla](https://github.com/Bastardkb/Scylla), [TKB Mini](https://github.com/Bastardkb/TBK-Mini) 또는 [Skeletyl](https://github.com/Bastardkb/Skeletyl)과 함께 사용하도록 제작되었습니다.

![](pics/1ae.jpg)

![](pics/1af.jpg)

# 필요한 부품

## 3D 프린트 - 케이스

STL 파일은 이 Github 리포지토리의 `files` 폴더에 포함되어 있습니다.

온라인 설명서에 링크된 자세한 케이스 프린팅 방법을 참조하세요.

구축하는 키보드에 따라 다른 프린트가 필요합니다. 버전에 따라 이름이 약간 다를 수 있습니다.

이 리포지토리는 항상 최신 3D 모델 버전으로 업데이트되며 이전 버전과 호환됩니다. 예를 들어, `charybdis.stl`은 `charybdis3_v131.stl`을 참조할 수 있습니다.

**3D 프린트 - 4x6**

| 설명            | 파일                     | 참고 사항                                                                                           |
| --------------- | ------------------------ | ---------------------------------------------------------------------------------------------------- |
| 오른쪽 케이스   | `4x6/charybdis.stl`      |                                                                                                      |
| 왼쪽 케이스     |                          | [Scylla 리포지토리](https://github.com/Bastardkb/Scylla)에서 다운로드                                |
| 오른쪽 플레이트 | `4x6/plate_shield2.stl`  |                                                                                                      |
| 왼쪽 플레이트   |                          | [Scylla 리포지토리](https://github.com/Bastardkb/Scylla)에서 다운로드                                |
| 어댑터 - 상단   | `4x6/adapter_top.stl`    | 4x6과 3x5용 어댑터가 다르니 4x6 폴더에서 적합한 것을 선택하세요!                                    |
| 어댑터 - 하단   | `adapter_bottom.stl`     |                                                                                                      |
| 텐트 - 오른쪽   | `4x6/tent_alien.stl`     | 선택 사항: 30도 텐트                                                                                |
| 텐트 - 왼쪽     | `4x6/tent_alien.stl`     | 선택 사항: 30도 텐트, 왼쪽은 파일을 미러링하세요                                                    |

**3D 프린트 - 3x6**

| 설명            | 파일                       | 참고 사항                                                                                                      |
| --------------- | -------------------------- | ------------------------------------------------------------------------------------------------------------- |
| 오른쪽 케이스   | `3x6 mini/Cmini.stl`       |                                                                                                               |
| 왼쪽 케이스     |                            | [TBK Mini 리포지토리](https://github.com/bastardkb/tbk-Mini)에서 다운로드, 왼쪽은 파일을 미러링하세요           |
| 오른쪽 플레이트 | `3x6 mini/plate.stl`       |                                                                                                               |
| 왼쪽 플레이트   |                            | [TBK Mini 리포지토리](https://github.com/bastardkb/tbk-Mini)에서 다운로드, 왼쪽은 파일을 미러링하세요           |
| 어댑터 - 상단   | `3x5 nano/adapter_top.stl` | 3x6 미니는 3x5 나노와 동일한 상단 어댑터를 사용합니다                                                           |
| 어댑터 - 하단   | `adapter_bottom.stl`       |                                                                                                               |
| 텐트 - 오른쪽   | `3x6 mini/tent.stl`        | 선택 사항: 30도 텐트                                                                                         |
| 텐트 - 왼쪽     | `3x6 mini/tent.stl`        | 선택 사항: 30도 텐트, 왼쪽은 파일을 미러링하세요                                                             |

**3D 프린트 - 3x5**

| 설명            | 파일                           | 참고 사항                                                                                                      |
| --------------- | ------------------------------ | ------------------------------------------------------------------------------------------------------------- |
| 오른쪽 케이스   | `3x5 nano/charybdisnano.stl`   |                                                                                                               |
| 왼쪽 케이스     |                                | [Skeletyl 리포지토리](https://github.com/bastardkb/skeletyl)에서 다운로드, 왼쪽은 파일을 미러링하세요           |
| 오른쪽 플레이트 | `3x5 nano/plate.stl`           |                                                                                                               |
| 왼쪽 플레이트   |                                | [Skeletyl 리포지토리](https://github.com/bastardkb/skeletyl)에서 다운로드, 왼쪽은 파일을 미러링하세요           |
| 어댑터 - 상단   | `3x5 nano/adapter_top.stl`     | 4x6과 3x5용 어댑터가 다르니 3x5 폴더에서 적합한 것을 선택하세요!                                                |
| 어댑터 - 하단   | `adapter_bottom.stl`           |                                                                                                               |
| 텐트 - 오른쪽   | `3x5 nano/tent/alien/tent.stl` | 선택 사항: 텐트*                                                                                               |
| 텐트 - 왼쪽     | `3x5 nano/tent/alien/tent.stl` | 선택 사항: 텐트, 왼쪽은 파일을 미러링하세요*                                                                  |

*텐트를 프린트하는 경우, Charybdis Nano에는 여러 가지가 있습니다. 가장 강하고 프린트하기 쉬운 최신 디자인인 에일리언 버전을 사용하는 것이 좋습니다. 30도와 15도 버전이 모두 제공됩니다.

## BastardKB에서 키트 구입

케이스와 모든 PCB 및 전자 부품을 포함한 전체 키트를 상점에서 구입할 수 있습니다:
https://bastardkb.com/

케이스를 직접 프린트하려는 경우 전자 부품 키트만 구입할 수도 있습니다.

## 전자 부품

전자 부품을 직접 조달하려면 [BOM](electronics_bom.md) 파일에서 BOM을 참조하십시오.

## 모드

BTU 또는 볼 베어링을 추가하는 몇 가지 모드가 있으니 *mods* 폴더를 확인하세요.

![](pics/1ac.png)

# 제작 가이드

자세한 설명은 아래 링크된 온라인 설명서에서 확인할 수 있습니다.

# 링크

- 디스코드: https://bastardkb.com/discord
- 웹사이트: https://bastardkb.com/
- 설명서: https://docs.bastardkb.com

# Patreon에서 후원

키보드가 마음에 드셨다면, Patreon을 통해 저를 도와주세요: https://www.patreon.com/bastardkb

정기적으로 업데이트와 작업의 통찰을 게시하고 있습니다. 키보드 혁신에 전념하고 있으며, 많은 도움이 됩니다!

# 라이선스

이 작업물은 Creative Commons Attribution-NonCommercial-ShareAlike 4.0 International License에 따라 라이선스가 부여됩니다.
