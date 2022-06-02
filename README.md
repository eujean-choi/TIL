# TIL Day 01

>  2022년 06월 02일 목요일



## Why Git & Github?

![Git로고](https://git-scm.com/images/logos/2color-lightbg@2x.png)

### Git

- 분산 버전 관리 프로그램
- 백업, 복구, 협업을 위해 사용
- [Git 공식문서](https://git-scm.com/book/ko/v2)

### Github

- Git을 사용하는 프로젝트의 협업을 위한 웹호스팅 서비스
- 포트폴리오를 자랑할 수 있는 공간



## CLI

> CLI (Command Line Interface): 터미널을 통해 사용자와 컴퓨터가 상호 작용하는 방식

### 터미널 명령어 정리

| 명령어 |              설명              |
| :----: | :----------------------------: |
| mkdir  |      폴더 (디렉토리) 생성      |
| touch  |           파일 생성            |
|   ls   |   현재 폴더의 파일 목록 출력   |
|   cd   |   다른 폴더(디렉토리)로 이동   |
|   rm   | 파일 삭제 / 폴더 삭제(-r 옵션) |

### 예시

```bash
$ mkdir test

$ touch a.txt

$ ls
$ ls -a

$ cd ..
$ cd test

$ rm a.txt
$ rm -r test
```



## Visual Studio Code

> Visual Studio Code (VS code): 마이크로소프트에서 개발한 텍스트 에디터의 한 종류

### 장점

- Windows, Mac, Linux 운영체제를 모두 지원
- 기존 개발 도구보다 빠르고 가벼움
- Extension을 통해 다양한 기능을 설치 가능 -  무한한 확장성
- 무료로 사용 가능

### Git Bash 연동하기

1. 터미널 창 열기 (Ctrl + `)
2. 화살표를 누르고 Select Default Profile을 클릭
3. Git Bash 선택
4. 휴지통 버튼으로 터미널을 종료/재시작
   - 휴지통(Kill Terminal): 터미널 자체를 종료
   - 닫기(Close Terminal): 종료가 아니라 창만 보이지 않도록
5. 기본 터미널이 Git Bash로 열리는지 확인



## Markdown(마크다운)

> Markdown: 일반 텍스트 기반의 경량 Markup 언어

### Markup(마크업)이란?

- 마크(Mark)로 둘러싸인 언어
  - 마크: 글의 역할을 지정하는 표시
- HTML도 마크업 언어의 일종
  - \<h1>제목1\</h1> 과 같이 작성


### 마크다운의 장점과 단점

1. 장점
   - 직관적이고 쉬운 문법
   - 지원 가능한 플랫폼과 프로그램이 다양
2. 단점
   - 표준이 없어서 사용자마다 문법이 상이함
   - 모든 HTML의 기능을 대신할 수 없음

### 주의 사항

- 마크다운의 본질은 글에 역할을 부여하는 것
- 반드시 역할에 맞게 마크다운 문법 작성
  - 글씨를 키우고 싶다고 해서 본문에 제목의 역할을 부여하면 안 됨

### 참고 자료

- [Markdown Guide](https://www.markdownguide.org/basic-syntax/)
- [마크다운 문법 정리](https://gist.github.com/ihoneymon/652be052a0727ad59601)
