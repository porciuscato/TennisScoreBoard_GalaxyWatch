# Tennis Score Board

갤러시 워치를 위한 테니스 스코어 보드 어플이다.

## 어플 만든 계기

아버지께서 테니스를 좋아하시는데, 경기 중 스코어를 암기하면 종종 잊는 경우가 발생해 우기는 사람들이 생긴다고 하신다.

그래서 스마트폰에 테니스 스코어 어플을 설치하긴 했지만, 경기 중 점수가 날 때마다 핸드폰을 꺼내서 점수를 체크하는 건 너무나 번거로운 일이다. 게다가 핸드폰을 주머니에 넣고 게임을 했다가 한 경기도 안 되서 폰이 박살날 것이다.

이전에 아버지께 갤럭시 워치를 사드린 적이 있는데, 이 워치에 핸드폰과 같은 스코어 어플이 있으면 좋겠다고 말씀하셨다. 그래서 하나 만들었다.

## 어플 개발 환경

[Tizen Studio](https://developer.tizen.org/development/tizen-studio/download)의 최신 버전(2021년 2월 27일에 4.1 버전)을 다운받아 Wearable 4 버전에 맞춰 개발했다. 아버지의 워치 타이젠 버전과 동일하다.

## 개발 참조

타이젠 스튜디오에서 제공하는 샘플 코드 중 계산기 코드를 기반으로 개발했다.

타이젠 개발은 처음이라 이 [글](https://cyberx.tistory.com/158)의 도움을 받아 시작했다.

어플 개발 이후 워치에 어플을 전송할 때 [개발 레퍼런스](https://developer.tizen.org/sites/default/files/documentation/1_tizen_studio_windows.pdf)를 참조했다.

하지만 워치와 PC의 연결이 계속 실패하여 이 [글](https://forum.developer.samsung.com/t/cant-connect-samsung-galaxy-watch-to-tizen-device-manager/7189/3)을 보고 해결했다.

즉, 핸드폰의 핫스팟을 켜 노트북과 워치를 연결했다. 이래도 되지 않자, 세 기기를 모두 재부팅하고 다시 연결했더니 성공했다.