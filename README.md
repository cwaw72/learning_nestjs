# learning_nestjs
nestjs 적용기
1. dotenv 사용하다 환경변수 설정 시 mongoose 연결 후 호출이되어 적용이 안되는 현상을 발견함
nestjs에서는 dotenv -> @nest/config를 사용한다고 함 https://darrengwon.tistory.com/965


2. nestjs 테스트 코드 작성
https://velog.io/@1yongs_/NestJS-Testing-Jest


3. useGlobalPipes 이란
In the case of hybrid apps the useGlobalPipes() method doesn't set up pipes for gateways and micro services. For "standard" (non-hybrid) microservice apps, useGlobalPipes() does mount pipes global lck
참고 https://docs.nestjs.com/pipes
