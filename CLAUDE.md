# CLAUDE.md

## 프로젝트 개요

aSSIST 서울과학종합대학원대학교 바이브코딩 실습 과정 학습 자료 사이트.
Jekyll + GitHub Pages(Cayman 테마)로 배포되며, 콘텐츠는 Markdown으로 작성한다.

## 사이트 URL

https://sung-ho-oh.github.io/assist-vibe-coding/

## 파일 구조

- `_config.yml` — Jekyll 설정 (테마: cayman, 플러그인: jekyll-remote-theme)
- `index.md` — 메인 페이지 (과정 소개, 학습 목표, 과제 평가 안내)
- `day1.md` — 1일차 (개발 기초, LLM 대시보드, Cloudflare, Opal)
- `day2.md` — 2일차 (Apps Script, AppSheet, n8n, GitHub, Claude Code)

## 작업 규칙

- 모든 .md 파일 상단에 Jekyll front matter(`layout: default`, `title:`)를 유지할 것
- 내부 링크는 확장자 없이 상대 경로 사용 (예: `[1일차](day1)`)
- 메인으로 돌아가는 링크: `[← 메인으로 돌아가기](./)`
- 한국어로 작성

## 빌드 및 배포

- GitHub Pages가 main 브랜치 push 시 자동 빌드/배포
- 로컬 테스트: `bundle exec jekyll serve`
