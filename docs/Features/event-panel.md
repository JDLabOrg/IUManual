# 이벤트 패널
이벤트 패널은 아이유에디터 메뉴 View > Event 항목을 활성화 시키면 등장합니다. 스크롤 애니메이터, 베리에이블 트리거 같은 이벤트를 추가할 수 있습니다.<br /><br />

*****
![Alt text](/../img/event-panel-scr.png)<br /><br />
## 스크롤 애니메이터 Scroll Animator
가로로 긴 웹페이지를 스크롤 하게 될 경우, 선택한 요소들에 대한 애니메이션 이벤트를 추가합니다.

### X-Position
X 위치 값에 대한 애니메이션을 추가합니다.

### Y-Position
Y 위치 값에 대한 애니메이션을 추가합니다.

### Opacity
Opacity 투명도 값에 대한 애니메이션을 추가합니다.

<br />

*****
![Alt text](/../img/event-panel-var.png)<br /><br />
## 베리에이블 트리거 Variable Trigger

### 트리거 Trigger
선택된 위젯에 특정액션이 발생될 경우 (롤오버 or 클릭) 정의해 두었던 변수 variable 값을 1씩 더하게 됩니다. 최초값과 최대값을 설정합니다.

### 리시버 Receiver
트리거메뉴에서 정의한 변수값과 일치하게 될 경우, 리시버 메뉴에서 보여주고 싶은 위젯을 연결합니다. 예를들어, 위젯을 선택하여 equation 필드에 test==1 을 입력할 경우, test 변수가 1이 되었을 때 해당 위젯을 보여주게 됩니다.