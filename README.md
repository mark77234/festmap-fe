# festmap-fe

Simple static front-end for FestMap.

Vercel 배포

- GitHub에 푸시 후 Vercel에서 리포지토리를 연결하면 자동 배포됩니다.
- 또는 CLI로 배포하려면:
  - `npm install`
  - `npx vercel login`
  - `npx vercel --prod`

로컬에서 확인

- `npm install`
- `npm run start` (http://localhost:3000)

Pretty URL

- `/privacy` 경로는 `vercel.json`에서 `/privacy.html`로 라우트되도록 설정되어 있습니다.
