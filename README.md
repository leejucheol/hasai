# 프로젝트 이름
설명 한 줄 (무엇을 해결하는 앱/웹/도구인지)

## 사용 기술
- Front: React, TypeScript
- Back: Node.js, Nest.js
- DB: MongoDB

## 주요 기능
- 사용자 로그인 및 인증 (JWT)
- 일정 자동 추천 알고리즘
- 마이페이지에서 CRUD 가능

## 화면 예시
(스크린샷 이미지 첨부)

## 실행 방법 (bash는 터미널에서 명령어를 입력하고 실행하는 환경을 말함.)
```bash
npm install -g @nestjs/cli # 컴퓨터 전체 다른 프로젝트에서도 사용가능
npm install --save-dev @nestjs/testing jest @types/jest ts-jest 
# 위 명령어는 NestJS 환경에서 TypeScript와 Jest 기반의 테스트 환경을 구축할 때 표준적으로 사용하는 패키지
nest new 프로젝트 명 # 이미 프로젝트 명이 있으면 하지말기
npm 선택 
cd 프로젝트명
npm run start:dev
nest g co users # user에 대한 controller
nest g s users # user에 대한 service
nest g mo users # user에 대한 module

```
## Project setup

```bash
$ npm install # 로컬 즉 지금 현재 프로젝트 위치에만 설치 -> 로컬 설치 (다른 프로젝트에서는 사용불가)
```

## Compile and run the project

```bash
# development
$ npm run start

# watch mode
$ npm run start:dev

# production mode
$ npm run start:prod
```

## Run tests

```bash
# unit tests
$ npm run test

# e2e tests
$ npm run test:e2e

# test coverage
$ npm run test:cov
```

## Deployment

When you're ready to deploy your NestJS application to production, there are some key steps you can take to ensure it runs as efficiently as possible. Check out the [deployment documentation](https://docs.nestjs.com/deployment) for more information.

If you are looking for a cloud-based platform to deploy your NestJS application, check out [Mau](https://mau.nestjs.com), our official platform for deploying NestJS applications on AWS. Mau makes deployment straightforward and fast, requiring just a few simple steps:

```bash
$ npm install -g @nestjs/mau
$ mau deploy
```

With Mau, you can deploy your application in just a few clicks, allowing you to focus on building features rather than managing infrastructure.

## Resources

Check out a few resources that may come in handy when working with NestJS:

- Visit the [NestJS Documentation](https://docs.nestjs.com) to learn more about the framework.
- For questions and support, please visit our [Discord channel](https://discord.gg/G7Qnnhy).
- To dive deeper and get more hands-on experience, check out our official video [courses](https://courses.nestjs.com/).
- Deploy your application to AWS with the help of [NestJS Mau](https://mau.nestjs.com) in just a few clicks.
- Visualize your application graph and interact with the NestJS application in real-time using [NestJS Devtools](https://devtools.nestjs.com).
- Need help with your project (part-time to full-time)? Check out our official [enterprise support](https://enterprise.nestjs.com).
- To stay in the loop and get updates, follow us on [X](https://x.com/nestframework) and [LinkedIn](https://linkedin.com/company/nestjs).
- Looking for a job, or have a job to offer? Check out our official [Jobs board](https://jobs.nestjs.com).

## Support

Nest is an MIT-licensed open source project. It can grow thanks to the sponsors and support by the amazing backers. If you'd like to join them, please [read more here](https://docs.nestjs.com/support).

## Stay in touch

- Author - [Kamil Myśliwiec](https://twitter.com/kammysliwiec)
- Website - [https://nestjs.com](https://nestjs.com/)
- Twitter - [@nestframework](https://twitter.com/nestframework)

## License

Nest is [MIT licensed](https://github.com/nestjs/nest/blob/master/LICENSE).
