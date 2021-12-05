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
