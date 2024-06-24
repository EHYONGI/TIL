# Git command

## init
- `.git` 폴더 생성 (위치 확인이 중요함 !! - 상하위 겹치는 것 있으면 오류)

``` bash
git init
```

## status
- 현재 git 상태 확인

```bash
git status
```

## add
- working directory => staging area 로 !
![](https://velog.velcdn.com/images%2Fjaneljs%2Fpost%2F2654de26-d74b-4618-9a3c-96668a4e2a53%2Fimage.png)

``` bash
git add .
```
'.' 은 내 위치 !

## commit
- staging area에 올라간 내용을 스냅샷 찍기'
    - `-m` 옵션을 통해 커밋메시지를 바로 입력가능

``` bash
git commit -m "first commit"
```

## push
- 원격저장소로 브랜치를 업로드 하는 명령어 -> 올라가는 것 !

```bash
git push origin master
git push {remote_name}{remote_url}
```

+
## remote add
- 원격저장소의 주소를 저장하는 명령어

```bash
git remote add {remote_name} {remote_url}
```