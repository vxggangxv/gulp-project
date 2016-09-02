## 모던 웹 디자인 워크프로세스 - Gulp 활용 편
CSS/Javascript 파일의 문법 검사, 병합, 압축을 수행하는 Gulp 프로젝트 책 예제입니다.<br>
책을 읽고 내려 받아 사용해보세요.

=

### Book 예제 다운로드
<p>아래 링크를 클릭해 예제 파일을 내려 받습니다.</p>
[Gulp 프로젝트](https://github.com/yamoo9/Making-Modern-Web-Design-Work-Process/archive/Gulp.zip)

=
### Node.js & NPM에 의존하는 프로젝트
<p>프로젝트는 Node.js 환경에서 작동합니다. Node.js가 설치되어 있지 않다면<br>
아래 링크로 이동하여 설치 파일을 내려 받습니다.</p>
[Node.js 다운로드](http://nodejs.org/download/)

=
### NPM 모듈 설치
<p>내려 받은 ZIP 파일 압축을 푼 후, Git Bash에서 압축을 푼 디렉토리로 <code>cd</code> 명령으로 이동합니다.<br>
그리고 NPM 설치 명령을 실행하여 <strong>프로젝트의 의존 개발모듈(devDependencies)</strong>을 내려 받습니다.</p>
```
$ npm install
```

=
#### Gulp 프로젝트 명령어
다운로드 받은 Gulp 프로젝트는 아래 명령어를 지원합니다.

* `gulp` 또는 `gulp default` - 기본 업무로 clean > styles > scripts > watch 순으로 실행됩니다.
* `gulp watch` - 파일의 변경 내용을 지속적으로 관찰하여 관련 업무를 수행합니다.
* `gulp clean` - 생성된 파일을 제거합니다.
* `gulp styles` - CSS 문법 검사, 병합, 압축 과정을 수행하는 업무입니다.
* `gulp scripts` - Javascript 문법 검사, 병합, 압축 과정을 수행하는 업무입니다.



=
#### 프로젝트 의존 개발 모듈 목록
<p>책에서 다룬 실습 예제는 아래 NPM 모듈에 의존합니다. 버전 앞에 붙는 기호(^)는<br>
"해당 버전에 호환"되는 집합을 의미합니다. 예를 들어 "^1.1.1"은 1.1.0-0 버전보다 크고<br>
2.0.0-0 버전 보다 작다는 의미로 해석됩니다.</p>
[참고 URL: 시멘틱 버전 관리(Semantic Versioning)](http://semver.org/lang/ko/)

* __del__             - 버전 ^1.1.0
* __gulp__            - 버전 ^3.8.10
* __gulp-concat__     - 버전 ^2.4.2
* __gulp-concat-css__ - 버전 ^1.1.1
* __gulp-csslint__    - 버전 ^0.1.5
* __gulp-if__         - 버전 ^1.2.5
* __gulp-jshint__     - 버전 ^1.9.0
* __gulp-rename__     - 버전 ^1.2.0
* __gulp-uglify__     - 버전 ^1.0.2
* __gulp-uglifycss__  - 버전 ^1.0.4
* __jshint-stylish__  - 버전 ^1.0.0
