# project_moim
 
 비공개 모임프로젝트 Tople(Together People)입니다.

 
 1인 가구가 늘어가고 좀 더 나은 여가생활을 보내고자 하는 사람들의 수요가 늘어나서 비공개 모임 프로젝트를 만들어 봤습니다.
 카카오 회원가입, 구글 맵을 사용했고, mvc패턴을 적용한 톰켓기반 스프링 서버를 만들어 봤습니다.

- 안드로이드

1. 

사용을 원하실 경우 각각 카카오와 구글에 등록이 필요합니다.

https://re-build.tistory.com/9 -카카오
https://webnautes.tistory.com/647 - 구글맵

그레이들의 설정은 다 되어있으니 Manifest안의 meta 데이터 값만 수정하시면 됩니다.

2. 

그리고 각각의 activity 안에 서버와 통신을 위한 URL 값들을 본인 값으로 수정해 주시면 되는데,

예를들어 Project_4T_ToPle_V_1_0_2/app/src/main/java/com/example/project_4t_tople/activity/AdminActivity.java 해당 경로를 보시면,

![url](https://user-images.githubusercontent.com/53204149/65139182-28969080-da47-11e9-8948-e5871b106e08.png)

위와 같이 url 값이 있는데 해당 정보를 본인의 값으로 수정해 주시면 됩니다.



- 서버 사용하기


1.	workspace 경로 복사하기

![workspace](https://user-images.githubusercontent.com/53204149/65135794-80ca9400-da41-11e9-9dbc-92e1c40583db.png)

2.	Spring 프로젝트 import

![image](https://user-images.githubusercontent.com/53204149/65134423-3a743580-da3f-11e9-9cd7-5657b6647abf.png)


![image](https://user-images.githubusercontent.com/53204149/65134429-3fd18000-da3f-11e9-88de-6d46d0557160.png)


3.	자바 버전 설정

![image](https://user-images.githubusercontent.com/53204149/65134442-43fd9d80-da3f-11e9-9d15-0573c6d1df5a.png)

 
![image](https://user-images.githubusercontent.com/53204149/65134452-46f88e00-da3f-11e9-8554-1532ecaa5919.png)

4.	Controller, Service 클래스파일 베이스 패스 수정


![image](https://user-images.githubusercontent.com/53204149/65134477-51b32300-da3f-11e9-94be-61f5eddd6bf0.png)

![image](https://user-images.githubusercontent.com/53204149/65134479-537ce680-da3f-11e9-900d-227563ee608e.png)

 

5.	DB 확인
 

![image](https://user-images.githubusercontent.com/53204149/65134487-57106d80-da3f-11e9-8a60-9ababb087cb5.png)



7. SqlDeveloper 에서 테이블 생성 및 확인

아래 경로에 sql 코드가 있습니다.

moim.4t.spring/src/main/resources/sql/android_project.sql

8. test.jsp 실행 확인
 

![image](https://user-images.githubusercontent.com/53204149/65134506-5bd52180-da3f-11e9-817f-eb7b4a5fd248.png)

![image](https://user-images.githubusercontent.com/53204149/65134515-5f68a880-da3f-11e9-9f72-a9d423243a82.png)
