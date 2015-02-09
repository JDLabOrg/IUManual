# 정적인 웹사이트 제작 (새로 만들기)
데이터베이스와 연동되지 않는 정적인 웹페이지를 제작해보겠습니다.<br />(워드프레스 프로젝트는 준비중입니다.)

*****
![Alt text](/img/steps-new-project.png)<br />
## 프로젝트 생성
1. 아이유에디터의 메뉴 중, __File > New Project__를 선택합니다.
2. 팝업 윈도우에서 __Default Project > Empty Page__ 를 선택합니다.


*****
![Alt text](/img/steps-add-widget.png)<br />
## 위젯 추가하기
1. 중앙 툴바의 위젯 항목내의 __위젯__을 클릭하여 __활성화__ 시킵니다.
2. 활성화 상태에서 스테이지에 __클릭+드래그__를 하여 원하는 크기로 추가하거나, __클릭__하여 원하는 크기를 입력합니다.

*****
![Alt text](/img/steps-edit-style.png)<br />
## 스타일 변경하기
1. 추가된 위젯을 선택한 후, 상단 툴바에서 __프라퍼티__ 탭을 선택합니다.
2. 원하는 스타일을 변경합니다.

*****
## 프로젝트 저장 & 빌드하기
1. 아이유에디터의 메뉴 중, __File > Save__ 를 선택하여 원하는 위치에 저장합니다.
2. 아이유에디터의 상단 툴바내 제일 좌측에 있는 __빌드버튼__![Alt text](/img/steps-build-btn.png)을 클릭합니다.
3. 스테이지에 추가된 위젯이 웹페이지로 만들어진 것을 확인할 수 있습니다.
![Alt text](/img/steps-after-build.png)

*****

## 서버에 업로드하기 (Heroku)
* 헤로쿠에 업로드하기 위해서는 사용가능한 계정이 있어야 합니다. 
* 가입을 했다면, 헤로쿠 툴벨트를 설치하도록 합니다.
<br /><br />

![Alt text](/img/steps-upload-to-heroku.png)<br />
1. 상단 툴바에 있는 __업로드__ 버튼을 클릭하여, __Synd with Heroku__ 메뉴를 선택합니다.
![Alt text](/img/steps-heroku-setup.png)<br />
2. 헤로쿠 셋업 팝업에서 로그인을 합니다.<br />
3. __Initialize__ 버튼을 클릭하여 Git 을 준비합니다.<br />
4. __Sync with New App__ 필드에 원하는 __프로젝트 이름__을 입력합니다.(대소문자구분불가, 공백불가)<br />
5. 4번까지 완료되었다면, __Create__ 버튼을 클릭합니다.<br />
6. __Git State__ 윈도우에 진행로그가 표시됩니다. 2~5분의 시간이 소요됩니다.<br />
![Alt text](/img/steps-heroku-success.png)<br />
7. 업로드가 완료되면, 위처럼 로그가 뜨는 것을 확인할 수 있습니다.
![Alt text](/img/steps-after-heroku-upload.png)<br />
8. __visit__ 버튼을 클릭하면, 업로드된 사이트주소로 이동합니다.