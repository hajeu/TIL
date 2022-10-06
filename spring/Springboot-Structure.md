# 스프링부트 구조

## Controller

웹 브라우저의 요청을 전담하여 처리한다.
Controller가 Service를 호출한다.

## Service

비지니스 로직을 수행한다.
DB에 접근하는 DAO를 이용해서 결과값을 받아 온다.

## DAO

DB에 접속하여 비즈니스 로직 실행에 필요한 쿼리를 호출한다.

## DB

알맞은 쿼리를 실행하고 결과값을 반환한다.

## DTO

Data Transfer Object의 약자
각 계층이 데이터를 주고 받을 때 사용하는 객체이다.
Getter, Setter

## VO

read-Only가 특징
사용하는 도중에 변경 불가능하며 오직 읽기만 가능합니다.
Getter
