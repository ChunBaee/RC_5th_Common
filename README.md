# RC_5th_Common
(주) 소프트스퀘어드 의 부트캠프인 '라이징캠프' 5주차 미션 과제입니다.

멜론 홈화면, 재생목록 및 재생화면 클론입니다.

## 핵심개념

📕 외부 라이브러리나 구글링을 해서 적용하기 전에 꼭 구글 공식 문서를 확인하자

📕 외부 라이브러리는 해당 깃허브에 가면 정확한 정보를 얻을 수 있다. (~~쉬운 사용법이라고는 하지 않았다..~~)

## 진행상황

🚂 화면들 간에 실시간으로 주고받아야 하는 정보들이 꽤 많아서 하나의 Activity만을 두고, 모두 Fragment로 처리하면서, 하나의 ViewModel로 데이터를 관리하기로 했다.

🚂 내부 정보들은 Firebase에 직접 입력 후 다운받는 형식으로 사용했다. 이왕이면 멜론 공식 API 를 사용하고 싶었지만, 지원하지 않는다 카더라..

## 에러사항

💢 너무 버벅거림이 심하다.. 초기화면의 RecyclerView 조차도..

![Screenshot_20220211-181753_RC_Mission_5](https://user-images.githubusercontent.com/80454599/163403401-6054d304-4422-4731-a79f-de2f40d70db3.jpg)
![Screenshot_20220211-181801_RC_Mission_5](https://user-images.githubusercontent.com/80454599/163403414-4e8909d6-49f5-445f-bd52-1be30f713f47.jpg)
![Screenshot_20220211-181812_RC_Mission_5](https://user-images.githubusercontent.com/80454599/163403419-a66132ce-1827-4911-bba7-2236e90a5e44.jpg)
