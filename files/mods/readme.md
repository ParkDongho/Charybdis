# 목차

- [목차](#목차)
- [카립디스 - 일반](#카립디스---일반)
  - [BTU 모드](#btu-모드)
  - [Veichu 베어링 모드](#veichu-베어링-모드)
  - [정적 베어링 모드](#정적-베어링-모드)
  - [나사 사용 정적 베어링 모드](#나사-사용-정적-베어링-모드)
    - [업그레이드된 정적 베어링 모드 인서트](#업그레이드된-정적-베어링-모드-인서트)
  - [카립디스를 위한 트랙패드 모드](#카립디스를-위한-트랙패드-모드)
  - [대체 센서](#대체-센서)
- [카립디스](#카립디스)
  - [손목 받침대](#손목-받침대)
    - [스트레이트 모드](#스트레이트-모드)
    - [슬로프 모드](#슬로프-모드)
  - [카립디스/스킬라를 위한 모듈형 조절 텐팅 스탠드](#카립디스스킬라를-위한-모듈형-조절-텐팅-스탠드)
    - [베이스](#베이스)
    - [손목 받침대가 있는 변형](#손목-받침대가-있는-변형)
- [카립디스 나노](#카립디스-나노)
  - [카립디스 나노 텐트를 위한 Midglow PCB](#카립디스-나노-텐트를-위한-midglow-pcb)
  - [카립디스 나노 유기 텐트를 위한 트랙패드 모드](#카립디스-나노-유기-텐트를-위한-트랙패드-모드)
  - [의자 장착 플레이트](#의자-장착-플레이트)
  - [모듈형 엄지 클러스터](#모듈형-엄지-클러스터)
  - [트랙볼 커버 - Sensor_cover](#트랙볼-커버---sensor_cover)
  - [트랙볼 커버 - Ball_cover](#트랙볼-커버---ball_cover)

# 카립디스 - 일반

## BTU 모드

매우 부드럽고, *매우 비쌉니다*.

![](../../pics/1ac.png)

베어링 대신 BTU를 사용하려면 바닥 어댑터 btu 모델을 인쇄하고 4.8mm BTU를 구해야 합니다.

어댑터 모델은 다음을 기준으로 설계되었습니다: https://nl.rs-online.com/web/p/ball-transfer-units/7431408/.

`btu` 폴더에서 파일을 인쇄하세요.

## Veichu 베어링 모드

Veichu 베어링은 BTU보다 저렴한 대안입니다. 

이들은 나사가 없기 때문에 3D 프린트에 눌러서 끼워야 합니다.

`veichu` 폴더에서 파일을 인쇄하세요.

## 정적 베어링 모드

꽤 부드럽고, *덜 비쌉니다*.

![](../../pics/1ad.jpeg)

베어링을 사용하지 않거나 비싼 BTU 부품을 구매하지 않으려면 이 옵션을 사용할 수 있습니다. 
3.175mm (1/8") 및 2.5mm 볼에 대한 파일이 있으며, 각각 3개와 바닥 btu 모델을 인쇄해야 합니다.

볼을 모델에 눌러 끼운 후 수정된 [바닥 btu 모델](btu/adapter_btu_bottom_v32.stl)에 삽입하세요.

링크:
- [바닥 BTU 모델](btu/adapter_btu_bottom_v32.stl)
- [인서트](static-bearing) (3.175mm 또는 2.5mm 중 선택)

## 나사 사용 정적 베어링 모드

모델에 볼 인서트를 고정하기 위해 나사를 사용합니다. M3 4mm 나사가 필요합니다.

두 가지 버전이 있습니다: 3.175mm 볼과 4mm 볼.

인쇄:
- [바닥 BTU 모델](static-bearing-screws/bottom.stl)
- [3.175mm 인서트](static-bearing-screws/balls-3.1mm/inserts.stl)
- [4mm 인서트](static-bearing-screws/balls-4mm/inserts.stl)

### 업그레이드된 정적 베어링 모드 인서트

인서트가 약간 더 높아 5mm 높이이며, 베어링 볼을 위한 오목함이 더 두드러집니다.

결과적으로 베어링 볼의 스냅이 약간 덜 강렬하고, 볼이 쉴 수 있는 더 많은 표면 각도를 제공하여 볼을 더 안전하게 고정합니다.

인쇄:
- [바닥 BTU 모델](static-bearing-screws/bottom.stl)
- [tall-inserts.stl](static-bearing-screws/balls-3.1mm/tall-inserts.stl)

지지대를 인쇄하고 잘라냅니다. 필요하면 버를 샌딩합니다.

## 카립디스를 위한 트랙패드 모드

`mods/trackpad/trackball-holder` 폴더의 2개 파일을 인쇄하세요. 트랙볼 홀더 대신 설치합니다.
트랙패드를 sda, scl, vcc, gnd에 연결합니다.

필요한 하드웨어:

| 부품 이름                        | 수량 | 링크                                                                                     |
| --------------------------------- | ---- | ---------------------------------------------------------------------------------------- |
| M4 8mm Torx 나사                 | 1    | Conrad                                                                                   |
| M4 나사 인서트, M4 X D6.0 X L5.0 | 1    | https://fr.aliexpress.com/item/4000232925592.html?spm=a2g0s.12269583.0.0.6aef4f282LZO4v |

![](../../pics/1ai.png)

## 대체 센서

PMW3389 및 ADNS9800 센서 PCB를 수용하기 위해 [`bottom_adapter_alternative_sensors`](./bottom_adapter_alternative_sensors/README.md) 디렉터리에 파일이 있습니다.

# 카립디스

## 손목 받침대

이 손목 받침대는 키보드 하단에 배치되어 손목을 지지합니다. 경사진 버전과 직선 버전이 있습니다.

각 버전에는 3개의 파일이 있습니다:

- `STL`: 3D 프린팅용
- `DWG`: 레이저 절단용
- `SLDPRT`: Solidworks 소스 파일

카립디스와 스킬라의 파일은 다릅니다:
- 카립디스의 경우 [4x6-palm-rest](4x6-palm-rest)의 파일을 사용합니다.
- 스킬라의 경우 [손목 받침대 폴더](https://github.com/Bastardkb/Scylla/tree/main/files/palm-rest)에서 파일을 사용합니다.

### 스트레이트 모드
![](../../pics/1aq.JPEG)

### 슬로프 모드
![](../../pics/1ar.JPEG)

## 카립디스/스킬라를 위한 모듈형 조절 텐팅 스탠드

자세한 내용: [tenting-stand-with-wrist-pads/readme.md](tenting-stand-with-wrist-pads/readme.md)

### 베이스

![텐팅 스탠드](tenting-stand-with-wrist-pads/assets/stand.jpg)

### 손목 받침대가 있는 변형

![손목 받침대가 있는 텐딩 스탠드](tenting-stand-with-wrist-pads/assets/home-with-pads.jpg)

# 카립디스 나노

## 카립디스 나노 텐트를 위한 Midglow PCB

레포 확인: https://github.com/Bastardkb/Charybdis-nano-tent-glow

![](../../pics/1ag.jpg)

**유기 텐트만 midglow rgb와 호환됩니다!**

## 카립디스 나노 유기 텐트를 위한 트랙패드 모드

`mods/trackpad/3x5-tent` 폴더의 2개 파일을 인쇄하세요. 유기 텐트에 설치하고 sda, scl, vcc, gnd에 연결합니다.

필요한 하드웨어:

| 부품 이름                        | 수량 | 링크                                                                                     |
| --------------------------------- | ---- | ---------------------------------------------------------------------------------------- |
| M4 8mm Torx 나사                 | 5    | Conrad                                                                                   |
| M4 나사 인서트, M4 X D6.0 X L5.0 | 5    | https://fr.aliexpress.com/item/4000232925592.html?spm=a2g0s.

12269583.0.0.6aef4f282LZO4v |

![](../../pics/1ah.png)

## 의자 장착 플레이트

표준 카메라 장착 장비를 사용하여 의자 또는 책상에 장착하기 위한 대체 바닥 플레이트입니다. 1/4 인치 장착 볼트(1/4-20 UNC)와 호환됩니다.
`3x5 nano/chairMountPlate` 폴더에 있습니다.  

![](../../pics/1aj.png)

## 모듈형 엄지 클러스터

3x5 Skeletyl/카립디스 나노를 기반으로 합니다. 약간 수정된 플레이트, 3 스위치 엄지 클러스터(Skeletyl 스타일), 트랙볼/트랙패드 장착을 위한 2 스위치 엄지 클러스터(카립디스 나노 스타일) 및 수정된 메인 바디가 포함됩니다.

참고: 아래 사진은 모듈형 엄지 클러스터를 위한 공간을 만들기 위해 잘라낸 표준 Skeletyl 메인 바디를 사용했지만, 목적에 맞게 인쇄된 메인 바디가 더 나은 결과를 제공할 것입니다!

| 부품 이름                        | 수량 | 링크                                                                                     |
| --------------------------------- | ---- | ---------------------------------------------------------------------------------------- |
| M4 8mm Torx 나사                 | 2    | Conrad                                                                                   |
| M4 나사 인서트, M4 X D6.0 X L5.0 | 2    | https://fr.aliexpress.com/item/4000232925592.html?spm=a2g0s.12269583.0.0.6aef4f282LZO4v |

![](../../pics/MTC.png)

## 트랙볼 커버 - Sensor_cover

원래의 바닥 커버와 결합하여 사용되는 트랙볼 센서 커버입니다. 센서를 외부 요소로부터 보호합니다.

![](./trackball-cover/pics/full-sensor-cover.png)

파일은 [트랙볼 커버](trackball-cover)에 있습니다.

## 트랙볼 커버 - Ball_cover

공이 떨어지지 않도록 adapter_v2_top_v75.stl 대신 사용합니다.
[정적 베어링 나사](static-bearing-screws)를 위한 높이를 조정합니다.
처음에는 공을 회전시키기 어려울 수 있지만 몇 번 끼우고 빼면서 회전시키면 익숙해질 것입니다.
이 부분의 나사 구멍은 M3 (x5x5) 나사 인서트를 접착할 수 있는 내부 직경(5mm)을 가지고 있습니다.

![](./trackball-cover/pics/ball-cover.jpg)
