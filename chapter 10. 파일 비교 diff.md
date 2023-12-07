# 1. 3영역의 파일 비교 diff
## 🟢 파일 비교
```
- 깃 3영역의 파일비교
- 커밋 간의 파일 비교
  - HEAD~ HEAD^
    - 하나 전 커밋
    - ~ => tilde, 틸드, 물결
    - ^ => caret, 커렛, 모자, 삿갓
- HEAD~~ HEAD~2 HEAD^^ HEAD^~
  - 두개 이전 커밋 ( HEAD^2 ⚠️error)
- 브랜치 간의 파일 비교
```
## 🟢 깃 3영역
```
- PC 탐색기 저장소 폴더에서 보이는 파일: 작업 디렉토리 파일
- 저장소 하부의 .git 폴더에 정보로 숨겨진 파일: 스테이징 영역, 깃(지역) 저장소
- 리눅스 명령어 ls로 보이는 파일: 작업 디렉토리의 파일
- 깃 명령 git ls-files로 보이는 파일: 스테이징 영역의 파일
```
# 2. 두 버전과의 파일 비교 diff
```
🟢 $ git diff clD1 clD3 -> git diff HEAD~2 HEAD~
🟢 $ git diff clD1 clD2 -> $ git diff HEAD~ HEAD
⚠️ $ git diff HEAD HEAD~ => 인자의 순서에 따라 결과 표시가 다름
```

