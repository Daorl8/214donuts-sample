# CHANGELOG — 214 Donuts (214도넛)

## v0.1 (2026-09-11) 최초 빌드 — 춘천 필드 도넛 베이커리 (레트로 에디토리얼)
- **업종/컨셉**: 춘천 서부대성로 소규모 필드 도넛(봉볼로니) 베이커리·카페. 인공 도넛믹스 無, 국내 밀가루·무항생제 계란·발효버터·우유, 16시간+ 저온숙성, 당일생산/당일판매, 도넛 오전 11시부터. IG @214_donuts. 브랜드 무드=빈티지 아메리카나 광고 콜라주 + 구글아이 캐릭터.
- **팔레트(다올 브리프: 빨강+초록+옅은갈색)**: 크래프트 베이지 #EFE4CE + 잉크 #22190F + 브랜드 레드 #C5372C(텍스트=--red-d #A5271E) + 그린 #2E5A3B + 주황 액센트. **실제 브랜드 컬러가 초록"214 DONUT"+빨강"OPEN"+크래프트라 브리프와 정확히 일치**.
- **폰트(브리프: GHEA Aram/Narek, 각지게 에디토리얼, 영어 위주)**: ⚠️GHEA Aram/Narek는 무료 CDN/구글폰트에 없어(ober 전례와 동일) **Archivo(각진 그로테스크 에디토리얼)로 대체** + Space Mono(모노 라벨·숫자, 레트로 리시트 느낌) + Pretendard(한글). 폰트 파일 주면 GHEA로 self-host 교체 가능.
- **각진 에디토리얼**: border-radius 0, 2px 검정 테두리 프레임, 대문자 Archivo, 오프셋 그림자 버튼, 상단 이전안내 티커, 스크롤 마퀴(Filled Fresh·16 Hrs·No Instant Mix…), 스펙 숫자(16h/11am/0).
- **구성**: 헤더(214 워드마크+nav)→히어로(이전 티커+"Doughnuts, from scratch."+빨강 박스)→마퀴→크래프트(제조 스토리+컷 도넛+스펙 3)→도넛 갤러리(feat2 비스코프+박스·입간판·인테리어·컷, 가격 무표기·"플레이버 매일 로테이션→IG")→오시는길(주소·재오픈 고지·전화·네이버맵·창가 사진)→채널(IG·전화·네이버맵)→그린 푸터+모바일 퀵바(전화·인스타).
- **정직 처리**: 가게 이전준비중이라 영업시간을 지어내지 않고 "reopening mid-September" + "도넛 11am부터" + 네이버 place 링크(자동 최신)로. 주소는 기존값 표기 + STRUCTURE에 교체대상 명시.
- **이미지**: IG 178장 중 다수가 텍스트/이모지 오버레이("Sold out"·"Lemon yogurt cream"·"Merry Christmas" 등). **텍스트 없는 실사진 7장만 큐레이션**(빨강214박스·컷도넛·비스코프·초록박스·OPEN입간판·DESSERT인테리어·노을창가). _convert_tool.html=파일명 직접 매칭. ⚠️셸 다운(9/8 윈도우 업데이트)→브라우저 도구로 webp 생성.
- **마감/안전**: 강제 리빌+1.5s폴백+noscript, rAF 강제 스무스 스크롤, a11y(aria-expanded·focus-visible·noscript), keep-all·safe-area, JSON-LD Bakery+주소+전화. 폼 없음. 이모지 UI 아이콘 0(SVG·모노만).
- **도메인**: og·canonical·JSON-LD = 214donuts.pages.dev(임시 placeholder).
- ⚠️미결: _convert_tool 실행(이미지 생성), 새 주소·영업시간 확정(이전 후), 실메뉴/가격, 폰트 self-host(납품·셸 복구 후), GitHub/CF 배포, 라이브·실기기 QA.
