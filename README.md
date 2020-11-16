# FUS 14기 Git 수업
## 성수캠퍼스
11월 16일부터 20일까지 패스트캠퍼스 성수교육장에서 Git 관련 수업 내용을 정리해 봤습니다.
CLI 명령어 환경에서 Git을 학습합니다.

## Command Line Interface (CLI)
- pwd: Print Working Directory
- whoami
- clar
- mkdir
- cd: Change Directory
- ls: List Segments
- cat 파일명: 파일 내용 화면에 출력 (파일명은 확장자가 있어야함)
- rmdir
- rm (rm -r 폴더명: 폴더 하위 디렉토리까지 모두 제거)
- mv: 파일 이동 및 이름 변경

## Git
- 초기환경 설정
  - git config --global user.name
  - git config --global user.email 
- git init
- git status
- git add
- git commit -m (커밋 메시지 작성) 

## Local에서 Remote저장소로 보내기
- git push -u origin main
- git reset --hard 태그명 (그 태그로 커밋 바꾸기..?)