지네릭(Generics)

- 다양한 타입의 객체들을 다루는 메서드나 컬렉션 클래스에 컴파일 시, 타입 체크를 해주는 기능

  - 장점

    - 타입 안정성을 제공

      - 의도하지 않은 타입의 객체가 저장되는 것을 막고 저장된 객체를

        꺼내올 때 원래의 타입과 다른 타입으로 잘못 형변환 되어 발생할 수 있는 오류를 줄여

    - 타입체크와 형변환을 생략할 수 있기 때문에 코드가 간결

    

<T>를 타입변수라고 함

기호의 종류만 다를 뿐 임의의 참조형 타입을 의미한다는 것은 모두 같