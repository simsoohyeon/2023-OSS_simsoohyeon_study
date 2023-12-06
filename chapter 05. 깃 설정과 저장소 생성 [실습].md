## 1. 깃 설정 범위와 명령
```
- 설정 범위
  System: 모든 사용자
  Global: 현재 사용자의 모든 저장소
  Local: 현재 사용자의 현재 저장소

사용자 이름: $ git config --global user.name ai7dnn
사용자 전자메일: $ git config --global user.email sshyun0604@gmail.com
줄바꿈 자동 변환: $ git config --global core.autocrlf true
줄바꿈 안전 설정: $ git config --global core.safecrlf false
기본 편집기 설정: $ git config --global core.editor 'code --wait'
기본 브랜치 이름: $ git config --global init.defaultBranch main
```
## 2. 저장소 생성
```
- git init: 디렉토리를 git repository로 만들어야 git으로 버전 관리가 가능
- 2가지 방식 $ git init OR $ git init.
  : 현재 디렉토리를 git repository로 만들기 위해 사용
- git init basic: 현재 폴더 하부에 basic을 생성하고 git repository로 만들기 위해서 사용
  (기준 폴더 하부에 basic 저장소 생성)
- cd basic: change directory (저장소에 들어가면 브랜치가 main으로 자동변경)
- $ ls -al: 모든 접속 기록
```
```
- 깃 저장소 하부 .git 폴더
  : 깃 저장소에는 반드시 .git 폴더가 포함
  : 여러  폴더와 파일이 저장
  : 커밋된 모든 파일의 모든 버전 기록이 저장
- 폴더 .git 삭제 -> 깃 저장소로서의 기능 상실


