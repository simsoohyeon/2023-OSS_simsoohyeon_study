# 1. 여러 커밋과 로그 이력
## 🟢 로그의 옵션
```
- 명령 git log: 기본적으로 가장 최근의 커밋부터 표시
$ git log --graph 문자 그림으로 로그 이력 그리기
$ git log --reverse 오래된 커밋부터 표시 --graph와 함께 사용 X
S git log -n 최근 n개의 로그 이력 표시

초록색 M: 스테이징 영역에서 파일이 수정됨
빨간색 M: 작업 디렉토리 영역에서 파일이 수정됨
```
# 2. 과거로의 시간 여행
## 🟢 명령 checkout
```
- 현재 브랜치에서 과거 커밋 HEAD~로 이동
  - 그 상태에서 당시의 파일의 내용을 확인 가능
$ git checkout HEAD~ HEAD 이전 커밋으로 이동
(현재 상태가 깨끗해야 checkout 가능)
$ git checkout - 이전 checkout으로 이동
```
|:---:||:---:||:---:|
```

