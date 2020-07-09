### git 설정하기
```
git config --global user.name sherazzang
git config --global user.email "shera31@naver.com"
```

설정한 내용확인
gif config --list


### 로컬 저장소 생성하기]
git init - 로컬저장소를 시작으로 새로운 프로젝트를 시작하는 경우에 사용하면 비어있는 git 저장소가 생성]

git close - 원격저장소에 있는 프로젝트를 받아와서 로컬저장소에 만드는법. 

```
git init
```


### 로컬 저장소에 저장하기
git status - 파일을 생성후 커맨드를 실행해서 확인

On branch master
Initia
l commit

Untracked files : // git에 등록되지 않은 파일 목록을 보여준다.
(use "git add<file>..." to include in what will be commintted)

Readme.md

nothing added to commit but untracked files present (use "git add" to track)



### git으로 관리할 파일을 등록

```
git add readme.md
```

git status

On branch master
Initial commit

Changes to be committe4d:
(use "git rm --cached<file>..." to unstage)
new file : Readme.md
//로컬저장소에 저장한다
git commit - m "initial commit"


### 로컬저장소와 원격저장소 연결

```
git remote add origin https:github.com/username/myproject.git

git remote -v
```

### 원격저장소에 저장하기
```
git push origin master

git push -u origin master]
```

pull - 원격저장소의 내용을 가져와 로컬저장소의 내용과 자동으로병행박업을 수행

fetch - 원격저장소의 내용을 확인만 하고 로컬저장소의 내용과 병행작업을 수행하지 않는다.


### 요약
```
mkdir ~/Myproject //작업디렉토리 생성
cd ~/Myproject // 작업디렉토리 이동
git init //로컬저장소로 적용
git status //로컬저장소 상태 확인
git add 파일 //git 목록에 파일 추가
git add . //git 목록에 모든 파일 추가
git commit -m "커밋코멘트" //  로컬저장소에 커밋
git remote add origin https://github.com/sherazzang/myproject.gif //로컬과 원격 저장소 연결
remote -v //연결된 원격 저장소 확인
push orgin master // 원격저장소에 push

```


### git  emote: Permission to~~~~~ 403 가 날경우


```
A 라는 github 아이디로 '최초' 글로벌 유저 등록을 했고,
나중에 B 라는 아이디로 다시 글로벌 유저등록해서 B 아이디로 push를 진행하려 할 때,
그 push의 시점은 여전히 A 라는 github 아이디를 찾고 있습니다.

※ 여기서 원하는건 B 라는 github 아이디로 push를 진행하고 싶을 때 

```

> 제어판 --> 사용자 계정 --> 자격증명 관리자의 window 자격증명 관리 --> github 편집 -->사용자 이름, 암호 변경
> 그리고 push 하면 OK