# 2주차 논의 주제
>필수 : Spring 과 SpringBoot 의 차이점.

Spring Boot makes it easy to create stand-alone, production-grade Spring based Applications that you can "just run".
스프링 부트는 단독적이고 상용화 수준의 스프링 기반 어플을 단지 실행할 수 있을 정도로 쉽게 만들 수 있다.  
[출처]:https://spring.io/projects/spring-boot  
1. 의존성 설정이 매우 간단하다  
Spring의 경우 의존성을 설정해 줄때 과정이 매우 길지만, SpringBoot 는 웹에 대한 의존성을 추가하는 과정이 매우 간단하다.
2. SpringBoot의 강력한 자동환경 설정
복잡한 환경설정이 없이도 웹 어플리케이션을 만들고 실행시켜주는 어노테이션을 의미한다.
3. 편리한 배포
Spring과는 다르게 내장 WAS를 가지고 있기 때문에 쉽게 배포할 수 있다.  
![WAS](https://gmlwjd9405.github.io/images/web/webserver-vs-was1.png)  
Springboot는 Tomcat이나 Jetty같은 내장형 WAS를 가지고 있다.
>필수 아니지만 알아보면 좋은것 : Unit Test 란?  

먼저 Spring에서는 개발과 테스트가 분리되어 있다. src과 test의 영역이 분리되어 있다.  
컴퓨터 프로그래밍에서 소스 코드의 특정 모듈이 의도된 대로 정확히 작동하는지 검증하는 절차다.  
>단위 테스트를 사용하는 목적은 내가 작성한 코드가 내가 의도한 대로 동작하는가? 에 대한 답변을 확인하기 위해서이다.  

## Point Concept
> Unit Test 를 왜 하는지, 하면 어떤 이점이 있는지.


