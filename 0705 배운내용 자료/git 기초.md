# git 기초

> 분산버전관리시스템(DVCS, Distributed Version Contorl System)  

## git 설치

윈도후 환경에서는 기본적으로 git이 없어 git bash를 설치하여 활용한다.[설치링크]()

## 기본 문법

### git 저장소 초기화(생성)

```bash
$ git init
```

.git 숨김 폴더에 git과 관련된 모든 정포가 담겨있음

### add

```bash
$ git add <디렉토리>
$ git add a.txt # 파일 하나만
$ git add a.txt b.txt # 여러 파일
$ git add my_folder/ # 특정 폴더
$ git add . # 현재 디렉토리 모든 파일/폴더
```

'working directory' 의 변경사항을 'staging area' 상태로 변경

### add 전

```bash
$ agit status
```

### add 이후

```bash
$ git status
```

### commit

```bash
$ git commit -m '커밋메세지'
```

- 커밋메세지는 버전을 나타낼 수 있도록 잘 작성해야함

- 커밋 해시 값은 고유한 커밋을 나타냄

- 커밋 목록을 확인하기 위해서는 git log 명령어를 사용

  ### status

  

  