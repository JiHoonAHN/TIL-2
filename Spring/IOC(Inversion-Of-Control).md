# IOC(Inversion Of Control)
: IoC란 프로그램의 제어 흐름 구조가 바뀌는것
> IoC 는 제어 흐름의 개념을 거꾸로 뒤집는 개념, 오브젝트는 자신이 사용할 오브젝트를 스스로 생성하거나 선택하지 않음
- 작업을 수행하는 쪽에서 Object를 생성하는 제어 흐름의 개념을 거꾸로 뒤집는것
- IoC에서는 Object가 자신이 사용할 Object를 생성하거나 선택하지 않는다.
- Object는 자신이 어떻게 생성되고 어떻게 사용되는지 알 수 없다.  
  컨테이너가 제어 권한을 가지고 있으므로
- 모든 Object는 제어권한을 위임받은 특별한 Object에 의해서 만들어지고 사용됨