# 2021-1-Algorithm-Study
2021년 1학기 알고리즘 스터디 **그룹2 repository**입니다.

## Git, Github는 어떻게 쓰나요?
git은 형상관리 시스템으로 개발자라면 누구나 쓰게 됩니다. 이번 기회에 익숙해지면 좋을거에요!
git과 github 사용법에 대해서는 몇 개 레퍼런스를 추천해드릴게요

- 영상
  - [생활코딩 GIT1](https://opentutorials.org/module/3733): Git이 뭔지, concept에 대해 다룹니다.
  - [생활코딩 GIT2](https://opentutorials.org/module/3762): Git을 사용하는 구체적인 방법에 대해 다룹니다.
  - [생활코딩 GIT4 - CLI 협업](https://opentutorials.org/module/3967): Github를 이용해 협업하는 법에 대해 다룹니다. (`pull`, `push`)
- 글
  - [Git과 Github 소개](https://www.zerocho.com/category/Git/post/58045dbc146be6001542a465): 이후에 시리즈로 계속 이어져 있습니다! 실습해보시면서 하면 좋을 것 같아요.
  - [누구나 쉽게 이해할 수 있는 Git 입문](https://backlog.com/git-tutorial/kr/): 명령어 생각 안 날 때 참고하면 좋아요!

Git을 완전히 마스터해야만 하는 건 아닙니다. 당장은 `add`, `commit`, `clone`, `push`, `pull` 정도 개념만 이해해도 됩니다! 그래서 너무 git 자체에 매몰되지 마시고 git 쓰다가 모르는 것에 대해선 그룹장에게 편하게 물어보세요! 처음할 땐 어려운 게 당연하니까 좌절하지 않아도 됩니다.


## 어떻게 제출하나요?
폴더 구조는 다음과 같이 구성해주시면 됩니다.
```text
[all1m-algorithm-study/2021-1-Algorithm-Study 구조]

2021-Algorithm-Study
├── README.md
├── week1
│     ├── GroupA
│     │      ├── {문제 이름}_{그룹원 이름}.cpp
│     │      └── boj1000_iknoom1107.py
│     └── GroupB
│            ├── boj1000_powergee.cpp
│            └── boj13460_mulmuri.py
├── week2
│     ├── GroupA
│     └── GroupB
....
```
- **`draft` 브랜치에 commit 해주세요!**
- github에서 브랜치 전환은 좌측 상단에서 할 수 있습니다.

![image](https://user-images.githubusercontent.com/44166353/113237212-68e3f980-92e1-11eb-82c0-d55940161615.png)

- 로컬에서 커밋하실 때도 `draft` 브랜치에 하시는 걸 권장 드립니다.
  - branch는 `checkout` 명령으로 바꿀 수 있습니다.
  - 원격 저장소의 branch가 오지 않은 경우 [이 링크](https://cjh5414.github.io/get-git-remote-branch/)를 참고해서 해결해보세요!

## 궁금한 사항은
- 문제를 풀다가
- git 사용에 관해서
- 기타 무엇이든지

그룹장에게 갠톡, 단톡으로 편하게 남겨주세요!
