# 서주원 (NTLGS Dev)

지도, 토론, 커뮤니티. 필요하다고 생각한 서비스를 직접 만들고 운영하는 학생 개발자입니다.
기획부터 배포, 장애 대응까지 혼자 합니다.

---

## 운영 중인 서비스

### NTLGS GLOBAL
세계 지도를 목차로 쓰는 지역 정보 플랫폼. 국가를 고르면 뉴스, 환율, 지진, 재난, 선박 위치가 한 화면에 모입니다.

- 사이트: https://ntlgs.kro.kr
- 스택: Cloudflare Workers, D1, Cron Triggers, D3.js, TopoJSON
- 특징: 크론이 USGS·GDACS·World Bank·GDELT를 주기 수집해 매시간 JSON 스냅샷 생성 / 번역은 브라우저 내 wasm(bergamot)으로만 실행, 서버는 번역문을 저장하지 않음 / UI 4개 국어 지원

### 토론하자
한국어 익명 토론 플랫폼. 찬성·반대로 붙으면 실시간 찬반 비율이 바로 보입니다.

- 사이트: https://토론하자.kro.kr
- 스택: Supabase, Tailwind CSS, GitHub Pages
- 특징: 1차 MVP를 React + Vite + Supabase로 이틀 만에 배포 후 재구현 / 한국어 도메인 punycode 처리로 Search Console 사이트맵 정상 제출

### 게임하자
게임 커뮤니티 플랫폼. 클럽을 만들고 전략을 공유하고 다른 클럽과 겨룹니다.

- 사이트: https://게임하자.kro.kr
- 스택: PWA, Service Worker, Supabase, GitHub Pages
- 특징: 설치형 PWA, 오프라인 지원

---

## 그 외 작업

- **OMEGA X** — Windows 최적화 도구 (Python, CustomTkinter, PyInstaller, Inno Setup)
- **OMEGA 15** — 올인원 PC 유틸리티
- **NTLGS GLOBAL 유튜브** — '오늘 한장' 국제 뉴스 쇼츠

---

## 기술

`Python` `JavaScript` `Cloudflare Workers` `D1` `Supabase` `React` `Vite` `Tailwind CSS` `PWA` `D3.js` `CustomTkinter`

---

## 링크

- 프로필: https://pinnn.me/@seodes105
- 유튜브: https://youtube.com/channel/UCIWA6hxQVdkCYqvHzinczzg
- 문의: 프로필 페이지의 문의 폼으로 연락 주세요
