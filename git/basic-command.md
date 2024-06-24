# Git command

> git 기본 명령어를 정리해봅시다.

## init
- 현재 위치에 `.git` 폴더를 생성

``` bash
git init
```

## add
- working directory => staging area 로 !
![](https://velog.velcdn.com/images%2Fjaneljs%2Fpost%2F2654de26-d74b-4618-9a3c-96668a4e2a53%2Fimage.png)

``` bash
git add .
```
'.' 은 내 위치 !

## status
- 현재 git 상태 확인

```bash
git status
```

## commit
- staging area에 올라간 내용을 스냅샷 찍기'
    - `-m` 옵션을 통해 커밋메시지를 바로 입력가능

``` bash
git commit -m "first commit"
```