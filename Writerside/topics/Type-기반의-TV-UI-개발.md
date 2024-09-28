# Type 기반의 TV UI 개발


화면은 SceneType - ContentList
컨텐츠 상세화면은 SceneType - ContentDetail
재생화면은 SceneType - Play
로 구분할 수 있고 각각의 SceneType은 Component를 상속받아 등록하여 화면을 구성했습니다.
SceneType 갯수만큼 Component가 만들었습니다.

![스크린샷_2024-09-28_오후_9.51.46.png](스크린샷_2024-09-28_오후_9.51.46.png)
위의 넷플릭스 화면이라고 하면 SceneType으로 구분했었던 카테고리 , 컨텐츠 리스트 , 상세화면 이라는 기본적인 VOD 서비스 구조를 사용 할 수 없고
1개의 SceneType으로 구성된 화면이 됩니다.





TV 개발에서 개장 중요한 부분은 포커스 관리입니다.
최종 사용자가 리모컨을 이용해서 카테고리를 선택하고 컨텐츠 리스트에서 컨텐츠를 선택하여 재생까지 이어지는 과정.
