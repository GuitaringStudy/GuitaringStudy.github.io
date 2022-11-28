# github page로 블로그 만들기

### 1. 테마 선택

jekyllthemes.org

jamstackthemes.dev

jekyllthemes.io

jekyll-themes.com

### 2. 테마 적용하기


#### 1) 원하는 테마의 git repository로 이동
- repository를 download zip
- clone을 사용하는 방법도 있지만 downlaod가 편한 것 같음.



#### 2) 다운로드한 폴더 열기
- 다운로드한 폴더의 압축을 풀어줌.
- 전체 파일 복사


#### 3) username.github.io에 붙여넣기
- 위에서 복사한 파일 전부를 붙여넣음
- 동일한 이름 파일은 덮어쓰기



#### 4) bundle 명령어 실행
- command나 git bash에서 username.github.io 경로에 이동해서 아래 명령 실행

```
bundle install
bundle exec jekyll serve
```

#### 5) 로컬 서버 접속
- 다시 127.0.0.1:4000에 접속하면 테마가 적용된 페이지가 나옴.
- 이대로 push해도 되고, 변경해서 push해도 됨.


### 3. 블로그 설정
- _conif.yml 파일에서 제목이나 이름 등을 변경함.
- _post에 markdown 파일을 추가해서 글(포스트) 추가.
- 원격에 push

```
git add .
git commit -m "commit message"
git push
```
