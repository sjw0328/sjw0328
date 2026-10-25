<div align="center">

# 서주원 · OMEGA SYSTEMS

**필요하다고 생각한 것을 직접 만들고 운영하는 학생 개발자**<br>
기획 · 개발 · 배포 · 운영을 혼자 합니다. 기준은 하나, *simple is best.*

[![Profile](https://img.shields.io/badge/Profile-pinnn.me-111111?style=flat-square)](https://pinnn.me/@seodes105)
[![Email](https://img.shields.io/badge/License%20inquiry-seodes105%40gmail.com-111111?style=flat-square)](mailto:seodes105@gmail.com)

</div>

---

## 오픈소스 라이브러리

<table>
<tr>
<td width="50%" valign="top">

### [matchum (맞춤)](https://github.com/sjw0328/matchum)
로컬에서 동작하는 규칙 기반 한국어 맞춤법 검사 파이썬 라이브러리. 외부 서비스 접속 없이 표준 라이브러리만 사용합니다.

[![PyPI](https://img.shields.io/pypi/v/matchum?style=flat-square)](https://pypi.org/project/matchum/)
[![OpenSSF Baseline](https://www.bestpractices.dev/projects/15483/baseline)](https://www.bestpractices.dev/en/projects/15483/baseline-1)
[![DOI](https://zenodo.org/badge/DOI/10.5281/zenodo.23531936.svg)](https://doi.org/10.5281/zenodo.23531936)

```bash
pip install matchum
```

- 오류(ERROR) · 문맥 의존(WARNING) 2단계 판정
- `py-hanspell` 호환 계층, 명령줄 도구
- Release 발행 시 테스트 후 PyPI 자동 배포 (Trusted Publishing)
- 규칙 한 줄 + 예문 두 개로 기여 가능

</td>
<td width="50%" valign="top">

### [pyi-doctor](https://github.com/sjw0328/pyi-doctor)
PyInstaller 앱을 포터블 exe와 설치 마법사로 한 번에 빌드하고, 배포 후 자주 생기는 문제를 점검하는 파이썬 라이브러리.

[![PyPI](https://img.shields.io/pypi/v/pyi-doctor?style=flat-square)](https://pypi.org/project/pyi-doctor/)
[![License: MIT](https://img.shields.io/badge/license-MIT-111111?style=flat-square)](https://github.com/sjw0328/pyi-doctor/blob/main/LICENSE)
![Python](https://img.shields.io/badge/python-3.9%2B-111111?style=flat-square)

```bash
pip install pyi-doctor
```

```python
from pyi_doctor import Project, build_all
build_all(Project(entry="main.py", name="MyApp"))
```

- onedir/onefile 빌드 + Inno Setup 설치 마법사
- 격리 환경 실행 테스트 ("내 PC에서만 됨" 점검)
- 백신 오탐 위험 요인 진단 (PE 분석)
- 번들 라이선스 목록 · CycloneDX SBOM 생성

[저장소](https://github.com/sjw0328/pyi-doctor) · [PyPI](https://pypi.org/project/pyi-doctor/) · [한국어 문서](https://github.com/sjw0328/pyi-doctor/blob/main/README.ko.md) · [변경 이력](https://github.com/sjw0328/pyi-doctor/blob/main/CHANGELOG.md)

</td>
</tr>
</table>

### [OMEGA X](https://github.com/sjw0328/source)
Windows PC 최적화 도구. 성능 카운터로 상태를 측정하고, 효과를 추정해 액션을 고릅니다.

[![OpenSSF Baseline](https://www.bestpractices.dev/projects/15412/baseline)](https://www.bestpractices.dev/en/projects/15412/baseline-1)
![License: GPL-3.0](https://img.shields.io/badge/license-GPL--3.0-111111?style=flat-square)

`Python` `CustomTkinter` `PyInstaller` `Inno Setup` — 안전 부스트 / 최대 부스트 2단계 모드 · CPU 온도 감시와 자체 스로틀링 · 파괴적 작업은 확인 창과 백업을 먼저 거침

---

## 운영 중인 서비스

| 서비스 | 내용 | 스택 |
|---|---|---|
| **[NTLGS GLOBAL](https://ntlgs.kro.kr)** | 세계 지도를 목차로 쓰는 지역 정보 플랫폼. 국가를 고르면 뉴스·환율·지진·재난·선박 위치가 한 화면에 모입니다. 크론이 USGS·GDACS·World Bank·GDELT를 주기 수집하고, 번역은 브라우저 내 wasm으로 실행합니다. | Cloudflare Workers · D1 · Cron · D3.js |
| **[토론하자](https://토론하자.kro.kr)** | 한국어 익명 토론 플랫폼. 찬성·반대로 붙으면 실시간 찬반 비율이 보입니다. | Supabase · Tailwind CSS · GitHub Pages |
| **[게임하자](https://게임하자.kro.kr)** | 게임 커뮤니티 플랫폼. 클럽을 만들고 전략을 공유하고 다른 클럽과 겨룹니다. 설치형 PWA, 오프라인 지원. | PWA · Service Worker · Supabase |

---

## 그 외

- **OMEGA 15** — 올인원 PC 유틸리티
- **[Good Source](https://www.youtube.com/channel/UCVIIujuomR_Mq7V4daqr3Fg/)** — 오픈소스·AI 개발 유튜브 채널

---

## 기술

![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=flat-square&logo=javascript&logoColor=black)
![Cloudflare Workers](https://img.shields.io/badge/Cloudflare%20Workers-F38020?style=flat-square&logo=cloudflareworkers&logoColor=white)
![Supabase](https://img.shields.io/badge/Supabase-3FCF8E?style=flat-square&logo=supabase&logoColor=white)
![React](https://img.shields.io/badge/React-61DAFB?style=flat-square&logo=react&logoColor=black)
![Vite](https://img.shields.io/badge/Vite-646CFF?style=flat-square&logo=vite&logoColor=white)
![Tailwind CSS](https://img.shields.io/badge/Tailwind%20CSS-06B6D4?style=flat-square&logo=tailwindcss&logoColor=white)
![D3.js](https://img.shields.io/badge/D3.js-F9A03C?style=flat-square&logo=d3dotjs&logoColor=white)
![GitHub Actions](https://img.shields.io/badge/GitHub%20Actions-2088FF?style=flat-square&logo=githubactions&logoColor=white)
![PyPI](https://img.shields.io/badge/PyPI-3775A9?style=flat-square&logo=pypi&logoColor=white)

---

<sub>문의는 [프로필 페이지](https://pinnn.me/@seodes105)의 문의 폼으로, 라이선스 문의는 seodes105@gmail.com 으로 받습니다. 각 프로젝트는 해당 저장소의 라이선스에 따라 있는 그대로(AS IS) 제공됩니다.</sub>
