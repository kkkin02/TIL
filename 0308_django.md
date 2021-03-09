# Django



### 작성규칙

+ 요소들 나열할 때 마지막에도 , 찍어야 함

1. views 함수의 첫 번째 인자는 반드시 request
2. render 함수의 첫 번째 인자도 반드시 request
3. template은 **templates** 폴더에 저장





### 주의

`<a href="/index/">인덱스</a>` : 이렇게 써야해

`<a href="/index">인덱스</a>` : redirect를 한 번 거쳐서 /index/ 페이지로

`<a href="index">인덱스</a>` : 현재 내 위치에서 index로 한 번 더 들어감



### 순서

1. 프로젝트 생성
   - `django-admin startproject 프로젝트이름 . `
2. 앱 생성
   - `python manage.py startapp 앱이름`
3. 앱 등록(settings - installed_apps)
4. 앱 url 생성, 연결 (views 함수 정의, templates 작성)
5. 앱 로직작성 