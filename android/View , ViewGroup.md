- 안드로이드 프로그래밍을 할 때면 View,ViewGroup을 많이 다루기때문에 이질감 없이 자연스럽게 쓴다. 하지만 정확한 의미를 잘 모르고 대강 알고만 있어서 이 기회에 정리를 해보았다.

#### View : View는 위젯과 뷰그룹으로 나누어진다.
- 1. 위젯(Widget) : 버튼,텍스트뷰,에디트등이 버튼, 텍스트 뷰, 에디트 등이 위젯이며 흔히 컨트롤(Control)이라고도 한다.
- 2. 뷰그룹(ViewGroup) : 직접적으로 보이지 않으며 뷰(View)를 담는 컨테이너 역할을 한다.
뷰그룹을 좀 더 자세하게 보면 View로 부터 파생된 ViewGroup의 서브클래스들을 애기하며, 뷰그룹을 이용해서 안에 존재할 수 있는 뷰들의  위치를 지정할 수 있다.
뷰그룹도 뷰를 상속하기 때문에 하나의 뷰로 볼 수 있다. 이 말은 하나의 뷰그룹이 다른 뷰그룹에 뷰로써 포함될 수 있다는 말과 같다.

꺠달은 점: 뷰그룹을 하나의 뷰로 볼 수 있다는 깨달음을 얻었다.





















