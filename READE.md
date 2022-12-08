# 내용 정리

## JPA 3.0

- JPA 3.0부터 javax에서 jakarta로 변경됨에 따라 기존 소스와 다르게 진행
- JpaRepository를 상속 받으면 Bean으로 등록되기 때문에 별도로 어노테이션을 선언하지
  않아도된다. [JpaRepository 참고](https://velog.io/@dltkdgns3435/SpringBoot-spring-data-jpa-%EC%82%AC%EC%9A%A9%EC%8B%9C-Repository-%EC%96%B4%EB%85%B8%ED%85%8C%EC%9D%B4%EC%85%98%EC%9D%80-%EA%BC%AD-%ED%95%84%EC%9A%94%ED%95%9C%EA%B0%80)

## 책 오타 내용

- 105 페이지 PostApiController에서 save 메소드를 PutMapping으로 선언했으나 110 페이지 내용에서 Test시 post로 요청하는 내용으로 보아 PostMapping이 맞다고 생각하여
  수정함
- 