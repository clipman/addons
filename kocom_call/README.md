# Hass.io Add-on: Kocom Call with RS485 

![Supports aarch64 Architecture][aarch64-shield] ![Supports amd64 Architecture][amd64-shield] ![Supports armhf Architecture][armhf-shield] ![Supports armv7 Architecture][armv7-shield] ![Supports i386 Architecture][i386-shield]

## About
Kocom Call with RS485
코콤 주방 모니터와 연결된 rs485통신을 통하여 공동현관문과 현관문의 호출을 제어합니다.

## Installation

1. 홈어시스턴트의 Hass.io > ADD-ON STORE에서 Add new repository by URL에 https://github.com/clipman/addons 를 입력한 다음 ADD 버튼을 누릅니다.
2. ADD-ON STORE 페이지 하단에서 "Kocom Call with RS485" 클릭합니다.
3. "INSTALL" 버튼을 누르면 애드온이 설치됩니다. 최대 약 10분 정도 소요. 
4. INSTALL 버튼위에 설치 애니메이션이 동작하는데 이것이 멈추더라도 REBUILD, START 버튼이 나타나지 않는 경우가 있습니다.
5. 이 애드온은 이미지를 내려받는 것이 아니라 직접 여러분의 Hassio에서 이미지를 만듭니다. 따라서 컴퓨터성능과 인터넷 속도에 따라서 시간이 좀 걸립니다. 
6. INSTALL 버튼을 누른다음 설치 애니메이션이 실행되면 제대로 설치중인 것입니다. INSTALL을 여러번 누르지 마시고 기다리다 지치면 브라우저 페이지를 리프리시 하세요. 
7. share/kocom/ 폴더에 있는 kocom_call.conf 파일을 본인의 환경에 맞게 수정합니다.
8. "START" 버튼으로 애드온을 실행합니다.

만일 kocom_call.py 파일을 수정하시려면 한번 실행한 후 애드온을 Stop 하시고 share/kocom/ 폴더에 있는 파일을 알맞게 수정하신 다음 애드온을 Start 하시면 이후부터는 수정된 파일을 적용합니다.

## Configuration

configuration.yaml
이 파일들을 참고하여 설정합니다.


[forum]: https://cafe.naver.com/koreassistant
[github]: https://github.com/clipman/addons
[aarch64-shield]: https://img.shields.io/badge/aarch64-yes-green.svg
[amd64-shield]: https://img.shields.io/badge/amd64-yes-green.svg
[armhf-shield]: https://img.shields.io/badge/armhf-yes-green.svg
[armv7-shield]: https://img.shields.io/badge/armv7-yes-green.svg
[i386-shield]: https://img.shields.io/badge/i386-yes-green.svg
