# bread-game
한예준이 만든 [선생님을 피해 매점가기] 게임

캔버스 기반 2D 액션 게임 시리즈. 외부 리소스 없이 HTML 한 장으로 동작하며,
PC(방향키 + 스페이스바)와 모바일(터치 버튼) 모두 지원합니다.

| 파일 | 편 | 설명 |
|---|---|---|
| `index.html` | 1편 · 매점 빵 사오기 | 교실 → 복도 → 계단 → 매점 → 교실. 난이도 보통(65초) / 불가능(35초) |
| `mario.html` | 2편 · 슈퍼 빵 어드벤처 | 점프 액션 중심 |
| `sonic.html` | 3편 · 풀스피드 빵 대시 | 스핀대시 · 스프링 · 체크포인트. ACT 1~2 |

## 배포

빌드 단계가 없는 정적 사이트입니다.

- **GitHub Pages** — https://hansuksoo.github.io/bread-game/ (2·3편은 `/mario.html`, `/sonic.html`)
- **Vercel** — `vercel.json`의 `cleanUrls` 덕분에 `/mario`, `/sonic` 으로 접속됩니다 (Framework Preset: Other)

## 로컬 실행

파일을 브라우저로 바로 열면 됩니다. 서버가 필요 없습니다.
