## 1. 파일 비교 diff 
### 🟢 파일 커밋 후 비교
- 3영역이 모두 동일? => $ git status nothing to commit, working
## 2. 파일 삭제 rm과 복구 restore
### 🟢 명령 별칭 git alias 생성
```
: 계속 사용하는 깃 명령을 짧게 다른 이름으로 만드는 방법
- $ git config --global alias.별칭이름'원명령어--긴 옵션-짧은 옵션'
  - 설정 이후에는 다음 명령으로 가능 => $ git 별칭이름
- $ git config --global alias.ss 'status -s'
=> --global은 모든 프로젝트에서 공통적으로 사용하고자 하는 설정,
사용자의 홈디렉토리의 .gitconfig 파일에 아래와 같이 추가
[alias] ss=status-s / s=status / co=checkout / br=branch / c=commit
- 다음은 동일한 명령어
  - $ git status -s, $ git ss
- $ git config --global alias.s 'status'
  - $ git s
- $ git config --global alias.co checkout
  - $ git co
- $ git config --global alias.br branch
  - $ git br
- $ git config --global alias.c commit
  - $ git c
```
  
