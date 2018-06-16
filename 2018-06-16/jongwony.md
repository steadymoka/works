---
name: 최종원
---

## DODO 영수증 프린터로 폴라로이드 만들기

- [github](https://github.com/lastone9182/pocket_polar)

아래 명령어로 시작된 프로젝트

```
sudo echo 'dodo!' > /dev/tty.BLUETOOTH_DEVICE
```

## Plan

라즈베리 파이를 카메라와 영수증 프린터와 연결하여 폴라로이드
카메라를 만든 사례가 있어서,

좀 더 나아가 구하게 된 블루투스 기능을 가진 프린터를
사용하여 휴대폰 만으로 다양한 기능(typewriter, qr code, barcode, image
processing 등)을 소화할 수 있는 DIY 프린터로 만들기

사례가 있어 금방 끝날 줄 알았으나,

1. 프린터 공급업체에서 sdk
링크가 사라져 졸지에 리버싱을 하게 되었다...

2. 안드로이드 디바이스를 제어하는 권한을 얻지 못해 루팅해야 한다...

## Done

1. 한글 영문 글자 출력

2. 글씨 크기, 굵기, 정렬 제어
