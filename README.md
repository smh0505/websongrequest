# websongrequest
(대충 김편집 트위치에 상주하는 트수들을 위한 웹에스알 클래식 버전)

## 사용방법
1. [여기](https://smh0505.github.io/websongrequest/)로 들어가기.
(편리한 사용을 위해 즐겨찾기 추가 및 바로가기 생성을 권장합니다.)
2. 유튜브 URL 칸에 자신이 SR로 넣고 싶은 유튜브 동영상의 URL를 입력.
![image](https://user-images.githubusercontent.com/42821865/120219098-b0670300-c208-11eb-8fd4-24661d60b60e.png)

여기서 영상을 우클릭 하거나 공유 버튼을 클릭하면 URL을 복사할 수 있습니다. (예시: [자비란](https://www.youtube.com/channel/UCM5TAPH7AD7F2iSr-iXIgtQ)님 영상)

3. 시작 시간과 종료 시간을 초단위로 설정.
4. 아래에 뜨는 커맨드를 복사하여 채팅창에 붙여넣고 엔터키를 눌러주시면 됩니다.

단, 시작 시간과 종료 시간 사이의 간격이 150초 (= 2분 30초)를 넘기면 길이 제한에 걸려서 복사가 불가능합니다.

## 유의 사항
이 프로그램은 [YouTube Data API v3](https://developers.google.com/youtube/v3/getting-started?hl=ko)를 사용합니다. 유튜브 URL이 아닌 다른 주소를 입력하면 제대로 작동이 되지 않습니다.

## 예시
![image](https://user-images.githubusercontent.com/42821865/120577311-24183400-c3f2-11eb-99aa-e27963ce9344.png)

결과: `!sr https://youtu.be/mpCMdq2fv0k&end=150`

![image](https://user-images.githubusercontent.com/42821865/120577344-31352300-c3f2-11eb-8b73-c97be516673a.png)

결과: `!sr https://youtu.be/mpCMdq2fv0k&start=60&end=150`

## Special Thanks
[김편집](https://www.twitch.tv/arpa__)

[레밀레기](https://www.twitch.tv/remilegi)

[Google Developers](https://developers.google.com/?hl=ko)

그리고 여러분
