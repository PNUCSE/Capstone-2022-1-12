### 1. 프로젝트 소개

본 졸업 과제는 웹과 앱을 통해 경상도 사투리 번역 서비스를 이용할 수 있게 하고, 보다 쉽게 사투리를 접할 수 있게 함으로써 지역 간의 소통을 원활하게 하는 것을 목표로 한다.

### 2. 팀소개

김도영, coby5502@gmail.com, 웹/앱 개발

김윤종, , 

황승찬, , 

### 3. 시스템 구성도

<img width="415" alt="image" src="https://user-images.githubusercontent.com/57849386/195581140-e749c701-672e-4e0e-82f4-f2aeb56f8adb.png">

<img width="1332" alt="스크린샷 2022-10-13 오후 8 10 07" src="https://user-images.githubusercontent.com/57849386/195581455-0e8a2d4f-a022-463c-af43-facaaebd72a6.png">

### 4. 소개 및 시연 영상


### 5. 설치 및 사용법

사투리 번역 웹 서비스의 경우, Docker를 사용하여 배포를 용이하게 만들었습니다.
프로젝트 터미널에서 다음과 같은 명령어를 입력하면, 도커 배포가 시작됩니다.

``` javascript
$ docker build -f Dockerfile-prod -t saturi-app-prod .
$ docker run -it -p 80:80 saturi-app-prod
```

