# Fillip's mini project for use git


# Git 기초


## 목차


- <a href="https://velog.io/@euisuk-chung/1.-%EA%B9%83Git%EC%9D%B4%EB%9E%80">Git이란?</a>
- <a href="https://velog.io/@yeonjoo7/GIT%EA%B8%B0%EB%B3%B8-%EB%AA%85%EB%A0%B9%EC%96%B4%EB%93%A4">Git 기본 명령어</a>
- <a href="https://git-scm.com/book/ko/v2/Git-%EB%B8%8C%EB%9E%9C%EC%B9%98-%EB%B8%8C%EB%9E%9C%EC%B9%98%EC%99%80-Merge-%EC%9D%98-%EA%B8%B0%EC%B4%88">브랜치와 병합</a>
- <a href="https://devyihyun.tistory.com/30">GitHub 사용</a>
- <a href="https://velog.io/@jinuku/Git-%ED%98%91%EC%97%85-%EA%B0%80%EC%9D%B4%EB%93%9C">협업 가이드</a>

## Git이란?

**Git**은 분산형 버전 관리 시스템입니다. 여러 명이 동시에 작업할 수 있도록 코드를 관리하고, 작업 내역을 기록하는 데 사용됩니다.

*예를 들어*, 다음과 같은 상황에서 유용합니다:

- 여러 개발자가 동시에 코드를 수정할 때
- 프로젝트의 특정 시점으로 되돌리고 싶을 때
- 실수로 파일을 지웠을 때 복구하고 싶을 때

>"분산형 버전 관리 시스템 Git은 모든 파일의 변경 이력을 기록하여 협업을 쉽게 해줍니다." - Git 사용자

## Git 기본 명령어

### . Git 저장소 초기화

```bash
 git init
```

- 새로운 Git 저장소를 초기화합니다.

### 2. 파일 추가 및 커밋

```bash
git add <파일명>
git commit -m "첫 번째 커밋"
```
스테이징 영역에 파일을 추가하고, 커밋을 생성합니다.

## GitHub 사용


GitHub는 Git을 기반으로 한 협업 플랫폼입니다. 다음 단계를 통해 원격 저장소를 사용할 수 있습니다:

1. GitHub 계정 생성
2. 새로운 리포지토리 생성
3. 원격 저장소 연결:

```bash
git remote add origin <GitHub 저장소 URL>
git push origin main
```
<img src="https://git-scm.com/images/logos/downloads/Git-Logo-2Color.png"/>

추가 리소스

Git에 대해 더 알고 싶다면, Git 공식 문서(https://git-scm.com/doc)를 확인하세요.
GitHub 사용법에 대한 자세한 정보는 GitHub Docs(https://docs.github.com/en)에서 찾아볼 수 있습니다.

<a href="https://www.tablesgenerator.com/markdown_tables">table</a>