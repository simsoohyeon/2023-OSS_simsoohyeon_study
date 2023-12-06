## 1. 깃 개요
- 2005년, 리누스 토발즈 개발
- 대표적인 오픈소스 소프트웨어 프로젝트
- 모든 개발자는 지역 시스템에 코드의 전체 사본 소유
```
깃: 컴퓨터 파일의 변경을 추적하는데 사용되는 버전 관리 시스템
- 여러 개발자가 함께 작업
- 소스 코드의 변경 사항을 추적
- 소스 코드 관리에 분산 버전 제어 도구가 사용
- 여러 개의 평행 분기를 통해 비선형 개발 지원

깃허브: 버전 관리를 위한 서버 저장소 및 개발을 위한 협업 관리 시스템

깃 설치: 두 개의 SW 제공 Git Bash, Git GUI
Git Bash: CLI 명령어줄 인터페이스
CLI를 알면 GUI 사용 가능 -> 반대는 성립 X
```
## 2. 깃 내부 주요 영역 구조
```
- 작업 디렉토르(working directory, working folder)
- 작업 공간(work space), 작업 트리(woking tree)
  modified, untracked
- 스테이징 영역(staging area, stage area, index)
  staged, indexed
- 깃 저장소(git repository, repository, .git directory)
  committed
- 임시 저장소(stash)
```
```
Add 명령: Working directory -> Staging Area 이동
Commit 명령: Staging Area -> Git repository 이동
```
## 3. 브랜치
- 나무 가지, 지점, 분기
```
- 분기 가지의 개념
  : 새로운 수정을 할 수 있는 또 다른 버전의 작업 흐름 ex) 병합 merge
```
