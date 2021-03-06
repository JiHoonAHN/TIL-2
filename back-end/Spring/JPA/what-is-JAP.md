# JPA
> JPA는 Java Persistence API의 약자입니다. Persistence라는 단어는 JAVA DTO에게 '없어지지 않고 오랫동안 지속'되는 '영속성(persistence)'을 부여해준다는 의미입니다.  
>**즉, 데이터를 DB상에 영구적으로 저장해주는 API**  

**JPA사용하기 이전의 문제점**  
>- 기존 JDBC만 사용하면 반복적이며 비슷한 SQL문을 많이 만들어야함(ex. CRUD)
>- DB table과 자바 객체간의 매핑하는 소모적인 작업을 지속해야함  

**사용이유**
>- SQL문을 개발자가 만들지 않기 때문에 **객체 중심적인 개발**을 할 수 있다.
>- 특정 **DBMS 문법에 종속적이지 않은 개발**이 가능하다
>- 영속성 컨택스트는 효율적인 SQL처리에 크게 기여하여 성능상의 이점