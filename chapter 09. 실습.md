## 1. 커밋과 로그이력
### 🟢 3번의 커밋 후 다시 현재로의 과거 여행
| 이전 이전 버전 | 이전 버전 | 최신 버전 |
|:---:|:---:|:---:|
|$ git checkout HEAD~2|$ git checkout HEAD~|$ git checkout main|
|X|X|$ git checkout-|
## 2. 과거 이전 버전으로 이동
```
🟢 $ git checkcout[이전 커밋]
- 상태가 clean 해야 함
  - 3영역이 동일한 상태
🟢 현재 상태를 clean한 상태로 하는 방법
- 임시 저장인 git stash
  - 작업 디렉토리와 스테이징 영역의 저장하고 3영역이 동일한 상태가 되도록
  (동일한 상태가 아닐 경우, $ git checkout HEAD~ => ⚠️error)
  ($ git stash = $ git restore --staged hello.txt
                 $ git restore hello.txt
  위는 다음 2개의 명령으로도 같은 기능을 수행)
🟢 과거 버전 이동 준비
- 작업 영역은 깨끗 clean 하게
- 스테이징 영역은 커밋과 같게
🟢 다시 최신 버전으로 돌아오기 $ git checkout main
🟢 다시 checkout 이전으로 돌아오기 $ git checkout-
```
