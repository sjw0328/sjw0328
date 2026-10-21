# 서주원 / NTLGS Dev

지도, 토론, 커뮤니티, 오픈소스. 필요하다고 생각한 것을 직접 만들고 운영하는 학생 개발자입니다.
기획부터 배포, 장애 대응까지 혼자 합니다.

---

## 오픈소스

### matchum (맞춤)
로컬에서 동작하는 규칙 기반 한국어 맞춤법 검사 파이썬 라이브러리. 외부 서비스에 접속하지 않고 표준 라이브러리만 사용합니다.

[![PyPI](https://img.shields.io/pypi/v/matchum)](https://pypi.org/project/matchum/) [![OpenSSF Baseline](https://www.bestpractices.dev/projects/15483/baseline)](https://www.bestpractices.dev/en/projects/15483/baseline-1) [![DOI](https://zenodo.org/badge/DOI/10.5281/zenodo.23531936.svg)](https://doi.org/10.5281/zenodo.23531936)

- 저장소: https://github.com/sjw0328/matchum
- 설치: `pip install matchum`
- 특징: 오류(ERROR)·문맥 의존(WARNING) 2단계 판정 / `py-hanspell` 호환 계층 / 명령줄 도구 / GitHub Release 발행 시 테스트 후 PyPI 자동 배포(Trusted Publishing)
- 규칙 한 줄과 예문 두 개로 기여할 수 있습니다. 오탐·누락 신고와 규칙 제안은 이슈로 받습니다.

### OMEGA X
Windows PC 최적화 도구. 성능 카운터로 상태를 측정하고, 실제 효과를 추정해 액션을 고릅니다.

[![OpenSSF Baseline](https://www.bestpractices.dev/projects/15412/baseline)](https://www.bestpractices.dev/en/projects/15412/baseline-1)

- 소스: https://github.com/sjw0328/source (GPL-3.0)
- 스택: Python, CustomTkinter, PyInstaller, Inno Setup
- 특징: 안전 부스트 / 최대 부스트 2단계 모드 / CPU 온도 감시와 자체 스로틀링 / 파괴적 작업은 확인 창과 백업을 먼저 거침

---

## 운영 중인 서비스

### NTLGS GLOBAL
세계 지도를 목차로 쓰는 지역 정보 플랫폼. 국가를 고르면 뉴스, 환율, 지진, 재난, 선박 위치가 한 화면에 모입니다.

- 사이트: https://ntlgs.kro.kr
- 스택: Cloudflare Workers, D1, Cron Triggers, D3.js, TopoJSON
- 특징: 크론이 USGS·GDACS·World Bank·GDELT를 주기 수집해 매시간 JSON 스냅샷 생성 / 번역은 브라우저 내 wasm(bergamot)으로 실행 / UI 4개 국어 지원

### 토론하자
한국어 익명 토론 플랫폼. 찬성·반대로 붙으면 실시간 찬반 비율이 바로 보입니다.

- 사이트: https://토론하자.kro.kr
- 스택: Supabase, Tailwind CSS, GitHub Pages
- 특징: 1차 MVP를 React + Vite + Supabase로 이틀 만에 배포 후 재구현 / 한국어 도메인 punycode 처리로 Search Console 사이트맵 제출

### 게임하자
게임 커뮤니티 플랫폼. 클럽을 만들고 전략을 공유하고 다른 클럽과 겨룹니다.

- 사이트: https://게임하자.kro.kr
- 스택: PWA, Service Worker, Supabase, GitHub Pages
- 특징: 설치형 PWA, 오프라인 지원

---

## 그 외 작업

- **OMEGA 15** — 올인원 PC 유틸리티
- **NTLGS GLOBAL 유튜브** — 정치·경제 이슈 쇼츠, 양쪽 진영을 같은 기준으로 다룸
- **세상의 모든 IT** — IT·보안 상식 쇼츠 채널

---

## 기술

`Python` `JavaScript` `Cloudflare Workers` `D1` `Supabase` `React` `Vite` `Tailwind CSS` `PWA` `D3.js` `CustomTkinter` `GitHub Actions` `PyPI`

---

## 링크

- 프로필: https://pinnn.me/@seodes105
- 유튜브: https://youtube.com/channel/UCIWA6hxQVdkCYqvHzinczzg
- 문의: 프로필 페이지의 문의 폼 / 라이선스 문의 seodes105@gmail.com
