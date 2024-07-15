## @ControllerAdvice 란?
여러 컨트롤러에 대해 전역적으로 @ExceptionHandler를 적용해준다.
@ControllerAdvice 어노테이션에는 @Component 어노테이션이 있어서
@ControllerAdvice가 선언된 클래스는 스프링 빈으로 등록된다.

여러 ControllerAdvice가 있을때 @Order 어노테이션으로 순서를 지정하지 않는다면 Spring은 ControllerAdvice를 를 임의의 순서로 처리할 수 있으므로 일관된 예외 응답을 위해서는 주의해야한다.

## @ExceptionHandler
매우 유연하게 에러를 처리할 수 있는 방법을 제공하는 기능   
컨트롤러의 메소드나 @ControllerAdvice, @RestControllerAdvice가 있는 클래스의 메소드에 어노테이션을 추가하여서 에러를 손쉽게 처리할 수 있다.

@ExceptionHandler에 의해 발생한 예외는 ExceptionHandlerExceptionResolver에 의해 처리가 된다

Spring은 예외가 발생하면 가장 구체적인 예외 핸들러를 먼저 찾고, 없으면 부모 예외의 핸들러를 찾는다.