# Next.js 대시보드 실습

Vercel의 공식 [Next.js Learn 코스](https://nextjs.org/learn)에서 App Router로 대시보드 앱(Acme)을 만드는 과정을 따라 하며 Next.js를 익히는 실습 저장소입니다. 공식 스타터 템플릿(Next.js App Router Course - Starter)에서 시작했습니다.

## 기술 스택

- Next.js(App Router), React, TypeScript
- Tailwind CSS
- PostgreSQL(`postgres`), NextAuth.js v5(beta), Zod
- 패키지 매니저: pnpm

## 실행 방법

```bash
pnpm install
cp .env.example .env   # Postgres 연결 정보와 AUTH_SECRET 입력
pnpm dev
```

## 참고

- 코스: https://nextjs.org/learn/dashboard-app
