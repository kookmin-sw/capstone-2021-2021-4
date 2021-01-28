[![Work in Repl.it](https://classroom.github.com/assets/work-in-replit-14baed9a392b3a25080506f3b7b6d57f295ec2978f6f33ec97e36a161684cbe9.svg)](https://classroom.github.com/online_ide?assignment_repo_id=350588&assignment_repo_type=GroupAssignmentRepo)
# Somecloud Front-end

썸클라우드 프론트엔드 코드-모듈화 뼈대

## Usage
- clone
```
git clone https://github.com/kookmin-sw/capstone-2021-4/ -b frontend
```

- run
```
sh localserver.sh
```

- 안될 시
```
python3 -m pip install http.server 
```

## 디렉터리 구조
```
app
- css
  - views - ./views 에 해당하는(cloud_add, cloud_list ...) 파일 이름과 일치
- img
- js
  - cloud_add.js
  - cloud_list.js
  - dashboard.js - ./views 에 해당하는(cloud_add, cloud_list ...) 파일 이름과 일치
pages 
- 로그인, 인트로 페이지 파일
templates
- _content-area - 콘텐츠 영역 렌더링하는데 필요한 파일
- _left-side - 왼쪽 매뉴 영역
- _menu - 상단 매뉴 영역
- _right-side - 아직 사용 안하지만 냅둔파일
vendor
- Wintermin 내부 라이브러리 파일들
views
- cloud_add - 클라우드 추가 화면
- cloud_list - 클라우드 리스트 화면
- dashboard - 대시보드 화면
index.html - 메인 index.html 파일
localserver.sh - 실행 파일
refer_* - 개발할 때 참고하는 파일 ( 아이콘, 버튼, 영역, 등등)
```

## 커밋 / 푸쉬 요령 - ex) cloud_add.html 완성 후 여기에 커밋 할 때
``` 
❯ git status
On branch frontend
Your branch is up to date with 'origin/frontend'.

nothing to commit, working tree clean
```
- git status 를 치고 현재 브랜치가 `frontend` 브랜치인지 확인한다. 

```
git add views/cloud_add.html
git add app/css/views/cloud_add.css
git commit -m "cloud_add.html 에서 버튼을 추가하고, css디자인을 입힘"
git push origin frontend
```
- 파일마다 꼭 할 필요는 없지만 해주면 좋고, 최소한 커밋할 때 어떤걸 했는지 커밋메세지로 남기는것이 중요함.

## 팀소개 및 페이지를 꾸며주세요.

- 프로젝트 소개
  - 프로젝트 설치방법 및 데모, 사용방법, 프리뷰등을 readme.md에 작성.
  - Api나 사용방법등 내용이 많을경우 wiki에 꾸미고 링크 추가.

- 팀페이지 꾸미기
  - 프로젝트 소개 및 팀원 소개
  - index.md 예시보고 수정.

- GitHub Pages 리파지토리 Settings > Options > GitHub Pages 
  - Source를 marster branch
  - Theme Chooser에서 태마선택
  - 수정후 팀페이지 확인하여 점검.

**팀페이지 주소** -> https://kookmin-sw.github.io/ '{{자신의 리파지토리 아이디}}'

**예시)** 2020년 0조  https://kookmin-sw.github.io/capstone-2020-0/


## 내용에 아래와 같은 내용들을 추가하세요.

### 1. 프로잭트 소개

프로젝트

### 2. 소개 영상

프로젝트 소개하는 영상을 추가하세요

### 3. 팀 소개

팀을 소개하세요.

팀원정보 및 담당이나 사진 및 SNS를 이용하여 소개하세요.

### 4. 사용법

소스코드제출시 설치법이나 사용법을 작성하세요.

### 5. 기타

추가적인 내용은 자유롭게 작성하세요.


## Markdown을 사용하여 내용꾸미기

Markdown은 작문을 스타일링하기위한 가볍고 사용하기 쉬운 구문입니다. 여기에는 다음을위한 규칙이 포함됩니다.

```markdown
Syntax highlighted code block

# Header 1
## Header 2
### Header 3

- Bulleted
- List

1. Numbered
2. List

**Bold** and _Italic_ and `Code` text

[Link](url) and ![Image](src)
```

자세한 내용은 [GitHub Flavored Markdown](https://guides.github.com/features/mastering-markdown/).

### Support or Contact

readme 파일 생성에 추가적인 도움이 필요하면 [도움말](https://help.github.com/articles/about-readmes/) 이나 [contact support](https://github.com/contact) 을 이용하세요.
