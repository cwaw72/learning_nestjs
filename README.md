# learning_nestjs
nestjs 적용기
1. dotenv 사용하다 환경변수 설정 시 mongoose 연결 후 호출이되어 적용이 안되는 현상을 발견함
nestjs에서는 dotenv -> @nest/config를 사용한다고 함 https://darrengwon.tistory.com/965


2. nestjs 테스트 코드 작성
https://velog.io/@1yongs_/NestJS-Testing-Jest


3. useGlobalPipes 이란
In the case of hybrid apps the useGlobalPipes() method doesn't set up pipes for gateways and micro services. For "standard" (non-hybrid) microservice apps, useGlobalPipes() does mount pipes globally
참고 https://docs.nestjs.com/pipes

4. mongoose 연결
https://docs.nestjs.com/techniques/mongodb


5. testing
https://docs.nestjs.com/fundamentals/testing

6. validation이 내장된 CRUD 컨트롤러를 빠르게 생성하려면 CLI의 CRUD 생성기

nest g resource [name]

7. CLI를 사용하여 컨트롤러를 만들려면 $ nest g controller cats 명령을 실행하면 됩니다.

8. Nest를 사용하면 보다 객체지향적인 방식(OO-way)으로 종속성을 설계하고 구성할 수 있으므로 SOLID 원칙을 따르는 것이 좋습니다.

---

종속성은 클래스가 기능을 수행하는 데 필요한 서비스 또는 개체입니다. 종속성 주입(DI)은 클래스가 종속성을 생성하지 않고 외부 소스로부터 종속성을 요청하는 디자인 패턴입니다.
