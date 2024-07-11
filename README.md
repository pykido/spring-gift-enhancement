# [구현할 기능 목록] 2단계 - 연관 관계 매핑 
- 실제 도메인 모델을 어떻게 구성하고 객체와 테이블을 어떻게 매핑해야 하는지 알아보자!
- 객체의 참조와 테이블의 외래 키를 매핑해서 객체에서는 참조를 사용하고 테이블에서는 외래 키 사용하기
### 1. 테이블 고려하여 엔티티 설계 
- Member 
  - [x] 필드값 수정   
  - [x] Member와 Wish : 일대다(1:N) 연관관계 (Member는 List<Wish> 안에 여러 Wish를 추가할 수 있다)

- Wish 
  - [x] Wish와 Member : 다대일(N:1) 연관관계
  - [x] Wish와 Product : 다대일(N:1) 연관관계 (Product는 여러 Wish 안에 포함될 수 있다)

- Product
  - [x] Product와 Wish : 일대다(1:N) 연관관계 (Product는 여러 Wish 안에 포함될 수 있다)


### 2. 테스트해보기 

