## 오버로딩, 오버라이딩 차이점?
### 오버로딩
- 컴파일 시점에 결정
- 메서드 이름은 같지만 파라미터 개수나 타입이 다른 것   
### 오버라이딩 
- 런타임 시점에 결정
- 부모 클래스에 정의된 메소드를 자식이 상속받아 자식 클래스에서 새롭게 정의하는 것

## 제네릭이란?
- 클래스 내부에서 사용할 데이터 타입을 외부에서 지정하는 기법
- 외부 인스턴스 생성시에 클래스타입을 결정하는 것.
### 제네릭 사용 이유와 이점
1. 컴파일 타임에 타입 검사를 통해 예외 방지
2. 클래스 외부에서 타입을 정해주기 때문에 따로 타입을 체크하고 변환해줄 필요가 없다.