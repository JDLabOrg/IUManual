# 중앙 툴바
![Alt text](/../img/mid-toolbar.png)<br /><br />
중앙 툴바는 스테이지 바로 상단에 위치하며, __1)위젯 2)포지션 3)높이/너비 4)정렬 5)배경컬러__ 영역으로 구분됩니다.<br />

*****
## 위젯 Widget
위젯 영역에는 아이유에디터에서 사용 가능한 모든 위젯들이 보여집니다. 기본적으로 __박스 / 텍스트 / 이미지__ 위젯을 제공하며, 다양한 위젯을 지원합니다.<br />

![Alt text](/../img/widget-box.png)
### 박스 Box
박스 형태의 위젯입니다. &lt;div&gt; 태그로 생성됩니다.

![Alt text](/../img/widget-text.png)
### 텍스트 Text
텍스트 위젯입니다. &lt;p&gt;,&lt;h1&gt;,&lt;h2&gt; 태그로 설정 가능합니다.

![Alt text](/../img/widget-image.png)<br />
### 이미지 Image
이미지 위젯입니다.

![Alt text](/../img/widget-transition.png)<br />
### 트랜지션 Transition
롤오버 또는 클릭 이벤트가 발생했을 때 상태변화를 만들 수 있는 위젯입니다. 2개의 하위요소가 제공됩니다.

![Alt text](/../img/widget-carousel.png)<br />
### 캐러젤 Carousel
캐러젤을 손쉽게 만들 수 있는 위젯입니다. 추가할 하위요소의 갯수를 조정할수있습니다.

![Alt text](/../img/widget-googlemap.png)<br />
### 구글맵 Google map
구글맵 위치정보를 보여주는 위젯입니다. 컬러스타일이나, 줌 설정 등 다양하게 커스터마이징할 수 있습니다.

![Alt text](/../img/widget-webmovie.png)<br />
### 비메오 또는 유튜브 Vimeo or Youtube
비메오나 유튜브, 웹 상의 비디오를 보여주는 위젯입니다. 자동재생/자동반복 등의 설정이 가능합니다.

![Alt text](/../img/widget-videoclip.png)<br />
### 비디오클립 Videoclip
리소스 라이브러리에 추가된 영상을 보여줄 수 있는 위젯입니다. 지원 가능한 동영상 포맷은 .mp4 입니다.

![Alt text](/../img/widget-import.png)<br />
### 임포트 Import
헤더 또는 푸터 그리고 커스텀 컴포지션 요소를 임포트 할 수 있는 위젯입니다.

![Alt text](/../img/widget-tweet.png)<br />
### 트윗 공유 버튼 Tweet Share Button
트위터로 공유하기를 수행하는 위젯입니다.

![Alt text](/../img/widget-facebook.png)<br />
### 페이스북 좋아요 버튼 Facebook Like Button
페이스북 좋아요를 수행하는 위젯입니다.

![Alt text](/../img/widget-centeredbox.png)<br />
### 센터박스 Centered Box
페이지 요소를 가로 중앙으로 자동 정렬시켜주는 박스 위젯입니다. 속성은 Box와 동일하나 위치 & 크기 조절이 불가능합니다.

![Alt text](/../img/widget-form.png)<br />
### 폼 Form
Input 요소를 감싸주는 &lt;form&gt; 태그 위젯입니다.

![Alt text](/../img/widget-textfield.png)<br />
### 인풋 텍스트 Input Text
사용자가 직접 텍스트를 입력할 수 있는 텍스트필드 위젯입니다.

![Alt text](/../img/widget-textarea.png)<br />
### 인풋 패러그래프 텍스트 Input Paragraph Text
사용자가 직접 텍스트를 입력할 수 있는 텍스트영역 위젯입니다.

![Alt text](/../img/widget-submit.png)<br />
### 서브밋 버튼 Submit Button
입력된 데이타를 서버로 전송하는 서브밋 버튼 위젯입니다.

![Alt text](/../img/widget-html.png)<br />

### HTML
사용자가 직접 html 코드를 입력 가능한 위젯입니다. 추가하고싶은 코드를 직접 입력할 수 있습니다.

<br /><br />



*****
## 포지션 Position
선택된 요소의 포지션을 설정합니다.<br />
(단위를 % 로 바꿀 경우, x/y 값은 드래그로 변경되지 않으며 w/h 값 역시 드래그로 변경되지 않습니다.)


### x 좌표 입력필드 & 스텝퍼 X position input field & Stepper
요소의 x 좌표를 직접 입력하거나, 스텝퍼를 이용하여 1px 씩 조절합니다. px 또는 % 로 단위를 변경할 수 있습니다. 
### y 좌표 입력필드 & 스텝퍼 Y position input field & Stepper
요소의 y 좌표를 직접 입력하거나, 스텝퍼를 이용하여 1px 씩 조절합니다. px 또는 % 로 단위를 변경할 수 있습니다.
### 포지션 속성 설정 팝업 Position setting popup
요소의 포지션 Position, 오버플로우 Overflow, z-index 속성을 변경할 수 있습니다. 

<br /><br />

*****
## 높이/너비 Width/Height 
선택된 요소의 높이와 너비값을 설정합니다.<br />


### Width 값 입력필드 & 스텝퍼 Width value input field & Stepper
요소의 width 값을 직접 입력하거나, 스텝퍼를 이용하여 1px 씩 조절합니다. px 또는 % 로 단위를 변경할 수 있습니다.

### Height 값 입력필드 & 스텝퍼 Height value input field & Stepper
요소의 height 값을 직접 입력하거나, 스텝퍼를 이용하여 1px 씩 조절합니다. px 또는 % 로 단위를 변경할 수 있습니다.

### 최소/최대 크기 설정 팝업 Min/Max-width & Min/Max-height setting popup 
요소의 최소/최대 높이 또는 너비를 설정할 수 있습니다.

<br /><br />

*****
## 정렬 Align
선택된 요소를 가운데로 고정 시킬수 있습니다. 포지션 옵션이 Relative인 요소는 가로 정렬만 가능합니다. <br /><br /><br />
*****
## 배경컬러 Background Color
선택된 요소의 배경색을 선택하거나 투명값으로 설정할수 있습니다. <br /><br />
