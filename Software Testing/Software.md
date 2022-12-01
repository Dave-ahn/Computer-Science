# Software (경래님 수업)

## Software Testing

확장성

애자일 방식으로 TDD 테스트 주도 개발

api 를 짜기 전에 test 코드 부터 짠다

결과물을 고정하고 결과물을 향해서 간다

허들이 낮은 테스트 코드를 작성하면 다같이 완성시킨다

automation testing

안정성 o
인력소모 x
비용 절약
테스트 속도 up
확장성 up

시스템 테스트 전략 3가지

---

### end to end test

-> 전체적인 flow test
ex. 브라우저상 클릭 후 생기는 변화에 대한 검증

이상 행동에 대한 테스트

---

### integration tests

통합 테스트
가상의 클라이언트를 만들어서

모듈 간의 호환성 검증
웹페이지 postman을 통한 api호출시 올바르게 동작하는지 확인

---

### unit tests (초기 진행 비용)

기능 단위 테스트
독립적으로 진행되는 가장작은 다위의 테스트

하나의 기능 또는 메소드를 테스트

코드 커버리지 : 테스트가 코드를 얼마나 커버하는지 정도를 나타내는 지표

cypress 자동으로 테스트 할 수 있다.
기능적인 부분

end-to-end test 사이트 찾아보기