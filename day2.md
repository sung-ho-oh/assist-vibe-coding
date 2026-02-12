---
layout: default
title: 2일차 학습 자료
---

[← 메인으로 돌아가기](./)

# 바이브코딩 강의 2일차 학습 자료

_aSSIST 서울과학종합대학원대학교 · AI공학·경영학 박사과정 · 노코드 기반 업무자동화 실습_

---

## Google 생태계를 활용: Apps Script로 AI 이메일 자동화

하기 파일을 1. 구글 드라이브에 저장 2. 더블 클릭하여 파일 오픈 3. 메뉴 중 파일에서 Google Sheets로 저장한다.

  * 실습 데이터: Inventory.xlsx
  * AppSheet 강의 자료: <https://gamma.app/docs/4-3-AppSheets-5fune3b3ors3iay>

### 실습 과제3: 데이터 흐름 기반 업무 자동화 설계 (Form–Sheet–Apps Script–AI)

가상의 Data가 필요 시 LLM에게 요청함:

> "앱시트 자동화 실습을 할 겁니다. 구글 스프레드 시트에 넣을 가상의 품목별 품질관리 통계 데이터 30개를 만들어 주세요."

#### 과제 기술서

  * **자동화 과제 정의:** 이 자동화는 어떤 반복 업무를 줄여주는가?
  * **입력–처리–출력 구조 설명**
    * 입력: 사용자는 어떤 데이터를 입력하는가?
    * 처리:
      * 데이터는 어디에 저장되는가? (Sheet)
      * AppSheet, 구글 스프레드 시트, 구글 앱 스크립트는 각각 어떤 역할을 하는가?
      * AI는 어떤 시점에, 어떤 기준으로 판단 또는 해석하는가?
    * 출력: 사용자는 어떤 결과를 보게 되며, 결과를 보고 난 뒤에 어떤 판단이나 행동을 할 수 있는가
  * **사용한 핵심 프롬프트:** GAS 개발을 위한 최초 프롬프트, 수정 프롬프트, 판단 기준을 수정하거나 보완한 프롬프트
  * **한계 인식:** 이 자동화가 못하는 것, 확장하려면 어떤 도구가 필요한가

#### 과제 제출: 과제 기술서와 실습 결과물 링크

---

## n8n 워크플로우 개발하기

  * n8n 강의 자료: <https://gamma.app/docs/n8n--vawbr6x1zwu3z41>
  * AI Chatting json 파일: AI_Chatting.json (다운로드하여 n8n에서 import)
  * 기업마당: 기업마당_url.json (다운로드 받아서 n8n에서 import file)

---

## GitHub 계정 & 저장소 만들기

참고 자료: <https://gamma.app/docs/Git-GitHub--6z0amqsrvp8zstx>

### 1단계. GitHub 계정 만들기

  1. <https://github.com> 접속
  2. 우측 상단 **Sign up**
  3. 이메일 / 비밀번호 / 사용자명 입력
  4. 인증 메일 확인 → 계정 활성화

> 사용자명은 향후 포트폴리오 URL이 됩니다. 예: `github.com/osung-ho`

### 2단계. 새 저장소(Repository) 만들기

  1. 로그인 후 우측 상단 **\+ → New repository**
  2. 아래처럼 입력

항목 | 입력
---|---
Repository name | `my-html-site`
Description | (선택)
Public | ✅
Initialize README | ❌ (체크 해제)

  3. **Create repository**

### 3단계. HTML 업로드

  1. 방금 만든 저장소 화면에서 **Add file → Upload files**
  2. `index.html` 파일 끌어다 놓기
  3. 아래 **Commit changes**

### 4단계. 구조 확인

저장소가 이렇게 보이면 성공:


    my-html-site
     └ index.html


---

## GitHub 파일 업로드 방법

Claude 무료 계정일 경우 수동으로 GitHub에 파일을 업로드(Commit)함, 유료 계정은 Claude Code에서 자동으로 업로드(Commit)됨.

---

## Claude에서 PRD 개발 결과 예시

pdf 파일 등 활용한 상세 PRD 개발은 LLM에서 진행 후 GitHub에 업로드함.

Terminal에서 명령어(Claude Local 설치 시 자연어 가능) 또는 웹에서 직접 GitHub 업로드함.

### 예시 프로젝트

  * **당직시스템 개발 PRD:** pdf 파일로 만들어진 화면 설계 + 작동 이미지 (DAS_PRD_Architecture_v2.0.docx, das-project.zip)
  * **디자인씽킹 시스템 개발 PRD** (mini-design-thinking-lab.zip)

---

## Claude Code (유료버전 사용자 only) 시연

  1. GitHub의 저장소를 연결한 후 Vibe Coding함.
  2. 가볍게 즐길 수 있는 게임을 만들고 싶어요. 어떤 게 좋을까요?
  3. (추천한 게임 중에서 선택) 타이핑 게임
  4. 게임 기록이 남을 수 있도록 supabase와 연동시켜 주세요.
  5. supabase 가입 후 설정값 확보
  6. supabase는 무료로 2개까지 운영할 수 있도록 허용하고 있음.

---

## 개인별 종합과제 (40%): 수업 중 제출 원칙, 최종 납기는 2월 14일

### 실습과제 안내

수업 중 학습한 도구 한 개 이상 활용하여 자동화 도구 설계 및 구현하기

  * 자동화 과제의 문제 정의 명확성
  * 자동화 구조의 논리성
  * 실제 구현 결과 또는 설계의 완결성
  * 본인의 언어로 설명 가능 여부

### 과제 평가 안내

본 과제는 **결과물의 완성도나 기술 수준을 평가하지 않습니다.**

다음 세 가지가 평가의 핵심입니다.

  1. 본인의 업무를 자동화 과제로 **어떻게 정의했는가**
  2. 입력–처리–출력 구조가 **논리적으로 설명 가능한가**
  3. **'도구'가 아닌 설계 파트너로 활용했는가**

**부분 구현 + 설계 설명만으로도 충분히 통과 가능** 합니다.

---

## 바이브 코딩 심화학습 자료

심화학습을 원하시는 분을 위한 자료: <https://goobong.gitbook.io/fastcampus>

  * Part 1. AI 에이전트와 Claude Code 기초
  * Part 2. Agent 개념과 아키텍처
  * Part 3. 바이브코딩으로 Hybrid Search RAG 구현하기
  * Part 4. 바이브코딩으로 MCP server 구현하기
  * Part 5. AI Agent 프로젝트 3개
  * Part 6. 바이브코딩과 AI agent best practice
