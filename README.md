# CSATcraft
[수능 문제 틀리면 디버프](https://youtu.be/VJW6pCGYC88?si=8W-fJHJaq6q1PJAU) 영상에 사용된 스크립트입니다

- 마크 버전 1.21.3입니다
- 업데이트 계획은 없습니다
- [skript-gui](https://github.com/APickledWalrus/skript-gui), [disky](https://github.com/DiSkyOrg/DiSky), [skrayfall](https://github.com/eyesniper2/skRayFall),
  [skream](https://www.spigotmc.org/resources/addon-skream.97081/), [skript particle](https://github.com/sovdeeth/skript-particle) 플러그인이 필요합니다
- 마크 비트맵의 한계가 256x256인지라, 리소스팩으로 무슨 짓을 해도 한 gui 안에 문제가 다 안 들어오더라구요 <br> 그래서 디스코드 봇과 스크립트를 연동시켜, 디스코드 채널에 문제 이미지가 뜨도록 했습니다
  - 그래서 etcs.sk의 2번쨰 줄, PGO_main.sk의 165번째 줄을 님들이 사용할 디스코드 봇의 요소들로 대체해주셔야 제대로된 플레이가 가능해요
  - 또한 PGO_main.sk의 163번째 줄에 적혀있는 서버 폴더 속 경로 그대로 assests 폴더를 넣어주셔야 합니다
- 코드에서 벡터 대신 quaternion을 사용할 일말의 필요도 없었다는 점 저도 뒤늗게 알아차렸으니 그거갖고 태클은 자제좀
