# DI(Dependency Injection, 의존성 주입)
## 의존성 주입이란?  
: 어떤 객체가 사용하는 의존객체를 직접 만들어서 사용하는것이 아니라 주입받아 사용하는 방법  
>즉 클래스안에 new 연산자가 들어가 있지 않고 외부에서 객체를 주입해주는것

<img width="90%" src=./img/DIway.jpg>

- **일반적인 의존성**  
    방법1은 A객체가 B와 C객체를 New 생성자를 통해서 직접 생성하는 방법
- **의존성 주입을 이용한 방법**  
 방법2는 **외부에서 생성 된 객체를 setter() 나 생성자를 통해 사용하는 방법**  

### Spring 에서의 DI
<img width=90% src=./img/SpringDI.jpg>

**Bean 컨테이너에서 Di를 자동으로 해준다**
>스프링에서 객체를 ``Bean`` 이라고 부르며, 프로젝트가 실행될때 사용자가 Bean으로 관리하는 객체들의 생성과 소멸에 관련된 작업을 자동적으로 행하는데 객체가 생성되는 곳을 스프링에서 Bean 컨테이너 라고 부른다.