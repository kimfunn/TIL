# Git 초기 설정

##### 커밋 작성자(autor) 설정

```bash
$ git config --glbal user.email "메일주소"

$git config --global user.name "유저네임"
```

커밋을 작성하는 사람이 누군지 알아야함



```bash
$ git config --global -l
# $ git confil --global --listt
```

<br>

커밋 편집기 변경

```bash
$git config --global core.editor "code --wait"
```

* 해당 명령어는 반드시 vscode가 설치되어 있어야함

기본 텍스트 편집기 vim을 Vscodefh 대체하는 것

# Git Basic

## 로컬 저장소 설정

```bash
$git init 
```
* 폴더에 git 저장소를 초기화하면,

  * .git 숨김 폴더가 생기고
  * bash 에는 (master) 라고 표기 된다.

  / 주의사항

  * git 저장소 내에 또다른 git 저장소를 만들면 안됨!!
  * git init 명령어를 입력할때, (master) 가 있으면 절대! 입력하지 말것

## add

//staging area / INDEX

```bash
$ git add 파일명
$ git add. #현재 디렉토리(하위 디렉토리)
$ git add a.txt # 특정 팔일
$ git add my_folder/ #특정 폴더
```

* working directory 상태의 파일을 `staging area` 상태로 변경
* 커밋을 위한 파일 및 폴더들을 추가하는 명령

> 
