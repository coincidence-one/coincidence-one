# 원우연

프론트엔드 개발자 원우연입니다.  
무엇을 어떤 구조로 만들지는 제가 주도해서 정하고, AI의 도움을 받아 함께 다듬습니다. 구현도 AI와 나눠 하지만, 결과를 리뷰하고 책임지는 건 제 몫입니다.  
지금은 미국 조지아 한인 중고거래 앱 피치마켓을 혼자 만들고 운영하고 있습니다.

- 포트폴리오: https://coincidence-one.github.io/wooyeon-portfolio/
- 블로그: https://coincidence-one.tistory.com
- LinkedIn: https://www.linkedin.com/in/wooyeon-won
- 메일: dndus567@gmail.com

## 프로젝트

| 프로젝트 | 설명 | 링크 |
| --- | --- | --- |
| 피치마켓 | 미국 조지아 한인 중고거래 서비스. 웹(Next.js 16), 서버(NestJS 11 · Prisma), 모바일(Expo 54)을 풀스택으로 설계하고 지금은 혼자 운영합니다. | [peachmarket.app](https://peachmarket.app) |
| 별마실 (Tiny Orbits) | 행성 7개를 돌아다니는 브라우저 멀티플레이 게임. Canvas, Web Audio, Supabase Realtime. | [tinoy-orbits.vercel.app](https://tinoy-orbits.vercel.app) |
| 하고-만달 | 오타니의 만다라트를 스크롤로 읽고 내 81칸을 채우는 웹앱. Next.js, Canvas 2D. | [hago-mandal.vercel.app](https://hago-mandal.vercel.app) · [저장소](https://github.com/coincidence-one/hago-mandal) |

## 경력

**애드크림 (TVCF) · 프론트엔드 개발자 · 2026.05 ~ 현재**

- TVCF 메인 서비스(Next.js) 응답 지연·502 대응: 프리페치 차단, 홈 ISR 적용, PM2 클러스터링. 목록 페이지 JS 1.03MB → 590kB
- 배포 파이프라인(GitHub Actions · Docker): 배포 중 서비스 제외 시간 약 5분 → 30초 이내
- 마이페이지 이관: CRA → Vite, React 17 → 19, React Router 5 → 7
- DNS를 Cloudflare로 이전하고 캐시 적용: 웹서버 송신 트래픽 약 60% 감소(전후 4주 평균 비교)

**도슨티 · 프론트엔드 개발자 · 2023.11 ~ 2026.04**

- AI 챗봇 SaaS docenty.ai: 임베드 챗봇 위젯 SDK(Vite), SaaS 대시보드(Next.js)
- 이커머스 플랫폼 6곳 이상 OAuth 연동, TossPayments 구독 결제, 한국어·영어·일본어 지원
- SEO 리뉴얼 4회: Google 검색 노출 분기 1,880회 → 3,300회
- GEO 마케팅 SaaS(Dct-Geo): 토픽·질문 발굴 엔진, 결제 MVP

## 기술

- Frontend: React, TypeScript, Next.js(App Router), Vite, TanStack Query, Zustand, Tailwind CSS
- Backend · Mobile: NestJS, Prisma, PostgreSQL, Socket.io, Supabase, React Native(Expo)
- Infra · Ops: GitHub Actions, Docker, PM2, nginx, Cloudflare, Sentry
