# baemin-6
우아한테크캠프 4기 [1주차] 2조 6팀 : 김채은, 권기석

# [권기석](https://github.com/Kwongiseok)
많이 부족할 수도 있으나, 캠프 안에서 최선을 다하겠습니다!
함께 쭉쭉 성장해봐요!
- 서울 구로구 거주
- 프론트엔드 개발을 좋아합니다!
- 배드민턴 치는 걸 좋아합니다!


---
# 나만의 Tip
## 내가 자주 사용하는 Git 명령어
origin -> remote 원격으로 저장한 변수

- 새로운 Git branch를 만들 때 : `git checkout -b [branch name] [parent branch]` <br>
- 원격 branch에서 로컬로 가져 올 때 : `git checkout -t remotes/origin/[branch 명]`
- git remote 브랜치 최신 정보로 업데이트 하기 : `git remote prune origin`
- git remote 정보를 로컬에 동기화 하기 : `git fetch --prune`

## Vscode에서 자주 사용하는 기능
- snippet (나만의 단축어) : [vscode snippet 공식 문서](https://code.visualstudio.com/docs/editor/userdefinedsnippets)

- react-snippet-plugin (리액트 개발시 편함!): [vscode plugin react-snippet 공식 문서](https://marketplace.visualstudio.com/items?itemName=burkeholland.simple-react-snippets)
  =======

  

---



# [김채은](https://github.com/chaeeun037)

> 안녕하세요, 웹 개발을 하는 김채은입니다!
> 주로 프론트엔드 개발을 해왔고, 서버도 얕게 다루어봤습니다.
> 실제 개발 시간을 단축하기 위해 설계를 꼼꼼하게 하고, 프로젝트 전체를 보기 위해 노력하고 있습니다. :)




### ❤️ like

- 30분 산책
- 아이스 아메리카노
- 시원한 맥주, 하이볼


### 👨‍💻 Career

- 삼성 청년 SW 아카데미 SSAFY 3기 ( 2020.01 ~ 2020.12)
- 컴퓨터과학과 학부 ( 2015.03 ~ 2020.02 )
- 스타트업 인턴 ( 2018.06 ~ 2019. 01 )
- 평창 동계 올림픽, 패럴림픽 조직위원회 정보통신부 매니저 ( 2018.01 ~ 2018.03 )



# 나만의 Tip
### 알아두면 편리한 git 명령어



* Repository 별 로그인 정보 설정

```
git config --global credential.github.com.useHttpPath true
```



* stage에 올릴 때 예외처리할 파일 설정

[예시]

```
git reset -- 01_java/.metadata/

find . -name .settings -exec git reset {} \;
find . -name .classpath -exec git reset {} \;
```



* git commit timestamp 수정

[예시]

```
GIT_COMMITER_DATE="Sun 10 Nov 2019 23:00:00 GMT+0900" git commit --amend --no-edit --date "Sun 10 Nov 2019 23:00:00 GMT+0900"
```



* git commit 내용 수정하기 - rebase

[예시]

```
git rebase -i HEAD~10
git rebase --continue
```

