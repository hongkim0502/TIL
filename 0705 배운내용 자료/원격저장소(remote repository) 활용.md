# 원격저장소(remote repository) 활용

> 원격저장소를 제공해주는 서비스 중에 GitHub를 활용

## 원격저장소를 등록

```bash
$ git remote add origin <주소>
```

- git 원격저장소에 origin이라는 이름으로 <주소>에 추가

### 원격저장소 조회

```bash
$ git remote -v
origin  https://github.com/hongkim0502/project1.git (fetch)
origin  https://github.com/hongkim0502/project1.git (push)

```

### 원격저장소 삭제

```bash
$ git remote rm origin
```

- git에 원격저장소 origin을 삭제

### push

```bash
$ git push origin master
```

- git에 origin을 master로 push
- 커밋 내역을 push함 현재 폴더의 파일들을 업로드하는 개념이 아님

# Clone

> 원격 저장소를 복제

```bash
$ git clone <url>
```

- 예시 화면

![image-20210705161128355](C:/Users/hongk/AppData/Roaming/Typora/typora-user-images/image-20210705161128355.png)

주소복사



# 간단 명령어

```bash
# git 저장소 만들기
git init

#버전 기록
git add . #.은 전부다 
git commit -m '메세지'

#상태 알아보기
git status
git log

#원격 저장소 등록 및 push
git remote add origin <url>
git push origin master

#원격저장소 관리
git remote -v
git remote rm origin

#원격저장소 복제
git clone <url>
```

