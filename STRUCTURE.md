# STRUCTURE — 214 Donuts (214도넛)

/ (배포 루트, CF [assets] directory="./")
├─ index.html            단일 파일 (인라인 CSS/JS, 영어 위주)
├─ dn-hero.webp          [도구생성] 빨강 214 도넛 박스 (히어로)
├─ dn-craft.webp         컷 도넛 + 빈티지 광고 (크래프트/갤러리)
├─ dn-biscoff.webp       비스코프 크림 도넛 (갤러리 feat2)
├─ dn-box.webp           초록 박스 모둠 (갤러리)
├─ dn-sign.webp          214 DONUT OPEN 입간판 (갤러리)
├─ dn-interior.webp      DESSERT 사인 인테리어 (갤러리)
├─ dn-window.webp        노을 창가 데칼 (오시는길)
├─ wrangler.toml         name=214donuts, [assets] ./
├─ .assetsignore         .git·문서·img·_* 제외
├─ CHANGELOG.md / STRUCTURE.md
├─ _convert_tool.html    [도구] 큐레이션 이미지 webp 변환 (배포제외, 파일명 매칭)
└─ img/                  원본 178장 (배포 제외)

## 섹션 앵커
#top 히어로(+상단 이전안내 티커) · #craft 제조 스토리 · #donuts 도넛 갤러리 · #visit 오시는길 · #contact 채널
(로고=CSS 워드마크 "214"+Donuts, 이미지 로고 없음)

## 디자인
- 팔레트: 크래프트 베이지 #EFE4CE · 잉크 #22190F · 브랜드 레드 #C5372C(텍스트용 --red-d #A5271E) · 그린 #2E5A3B · 주황 액센트 #E08A2B. (실제 브랜드 컬러 = 초록 214 DONUT + 빨강 OPEN + 크래프트, 요청과 일치)
- 폰트: **Fraunces(디스플레이, 우아한 세리프 이탤릭 — 다올 "고급지다=첨부 사진 라벨 느낌"=세리프 이탤릭)** + Archivo(본문·"214"숫자박스) + Space Mono(라벨) + Pretendard(한글). 각진 에디토리얼(border-radius 0, 2px 검정 테두리, 그림자 오프셋 버튼) + 흐르는 세리프 이탤릭 제목의 대비. ⚠️마퀴 제거(v0.2). GHEA Aram/Narek는 무료 CDN 없음(파일 주면 교체 가능하나 다올 취향=세리프 이탤릭).
- 강제 리빌 + noscript 폴백 + 1.5s 타임아웃, rAF 강제 스무스 스크롤.

## ⚠️ 교체 대상 / 확인 필요 (납품 전)
- **주소·영업시간**: 가게 이전준비중(2026-09 중순 재오픈 예정). 서부대성로 196은 기존 주소일 수 있음 → 새 주소 확정 후 교체(본문·JSON-LD·푸터·네이버링크). 현재는 "이전/재오픈" 정직 고지 + 네이버 place 링크(자동 최신)로 처리.
- **가격/메뉴명**: 실가격 미제공 → 사진led 갤러리, 가격 무표기. 실메뉴 확보 시 카드에 반영.
- **도메인**: og·canonical·JSON-LD = 214donuts.pages.dev(임시 placeholder). 실배포 도메인 확정 시 치환.
- **폰트 self-host**: 납품 시 Archivo·Space Mono·Pretendard self-host(셸 복구 후). GHEA 파일 제공 시 GHEA로 교체 가능.

## 배포
GitHub Daorl8/214donuts(예정) 또는 사장님 CF → 214donuts.pages.dev(placeholder).
