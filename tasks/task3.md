# 과제 3 (난이도 상)

https://github.com/udacity/asteroids에 들어가 해당 리포지토리를 로컬 머신에 클론 받고 다음 과제를 수행해주세요.

## 버그를 유발한 커밋 찾기

asteroids를 실행하면 우주선과 소행성이 나타납니다. 키보드에서 ←와 →를 누르면 우주선이 가리키는 방향이 바뀌고, ↑를 누르면 우주선이 전진합니다. 스페이스 바를 누르면 로켓이 발사되죠. 

index.html 파일을 열고 게임을 직접 실행해 봅시다.

![asteroids-intro](../resources/asteroids-intro.png)

엇! 그런데 에러가 있네요. 스페이스 바에서 손을 떼지 않고 계속 눌러봅시다. 쉼 없이 총알이 발사됩니다. 

![asteroids-bug](../resources/asteroids-bug.png)

이렇게 끊임없이 총알이 발사되면 게임을 금방 깰 수 있어서 안 됩니다. 처음엔 총알이 끊임없이 발사되지 않도록 구현했었는데, 어디선가 총알이 끊임없이 발사되도록 하는 코드가 들어간 것 같네요.

어떤 커밋때문에 버그가 생겼는지 찾아봅시다. 그리고 버그를 수정하려면 어떻게 해야 하는지 적어봅시다.

### 정답

(여기에 버그를 유발한 커밋의 id와 어떻게 하면 버그를 수정할 수 있는지 적어주세요.)
(git shortlog로 확인후git checkout daebb7 하면 과거로 돌아가있음. git commit --amend 로 접속하여 added를 fixed로 수정.)
(git shortlog로 확인후git rebase -i daebb756018ed433d7d5986efaef2bc56cc13188에서 edit로 변경후 닫기. git commit --amend로 커밋 내용 고치고 닫기. git rebase --continue하기)

### 힌트

과제 2를 통해 커밋도 체크아웃 할 수 있다는 것을 배웠습니다. 이전 커밋을 체크하웃하면 타임머신을 타고 과거로 돌아갈 수 있습니다!
