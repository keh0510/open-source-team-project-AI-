# open-source-team-project-AI-
# Generative AI Hub — Team Project

GPT, Gemini, Grok 등 **주요 생성형 AI 모델을 한 페이지에서 비교**할 수 있는 정적 웹 프로젝트입니다.  
3인 팀 프로젝트로 진행되었으며, **각 팀원이 하나의 AI 모델 섹션을 전담**하여 설계·구현하였습니다.

---

## 프로젝트 개요
- 목적: 생성형 AI 모델의 **특징·성능·활용 분야를 직관적으로 비교**
- 방식: 단일 페이지(SPA 형태) + 탭 전환 UI
- 특징:
  - 역할 분담 기반 협업
  - 반응형 UI
  - 애니메이션 전환
  - 비교 표 및 멀티미디어(영상) 포함

---

## 팀 구성 및 역할 분담

| 팀원 | 담당 파트 | 주요 작업 |
|---|---|---|
| **주소민** | GPT | GPT 개요, 성능, 작동 원리, 버전별 특징, 활용 분야 정리 |
| **김은호** | Gemini | Gemini 멀티모달 개념, 역사, 성능, 버전 비교, 영상·이미지 자료 구성 |
| **이규찬** | Grok | Grok 개념, 탄생 배경, MoE 구조, 실시간 데이터 특성, 모델·가격 비교 표 |

> 각 팀원은 **자신이 맡은 섹션(`#gpt-section`, `#gemini-section`, `#grok-section`)만 단독으로 수정**하여  
> 협업 중 코드 충돌을 최소화했습니다.

---

## 주요 기능
- **GPT**
  - 개요, 성능, 작동 원리
  - 버전별 특징(무료 / Plus / Pro)
  - 학습·창작·프로그래밍 등 활용 분야 정리
- **Gemini**
  - 멀티모달 AI 개념 및 탄생 배경
  - Ultra / Pro / Nano 버전 비교
  - 영상·이미지 기반 활용 사례 제시
- **Grok**
  - 실시간 데이터 기반 AI 특징
  - MoE 아키텍처 설명
  - 모델 기능 및 가격/플랜 비교

### 2. 사용자 인터페이스 기능
- 상단 탭 네비게이션(홈 / GPT / Gemini / Grok)
- 탭 클릭 시 콘텐츠 전환 애니메이션
- 모바일·데스크톱 반응형 레이아웃

### 3. 비교 및 시각화 요소
- 모델 간 기능 비교 테이블
- 가격/플랜 비교 표 제공
- 이미지 및 YouTube 영상 임베드

---

## 기술 스택
- **HTML5** — 시맨틱 구조
- **CSS3**
  - CSS 변수(`:root`)를 활용한 테마 관리
  - 반응형(Media Query)
  - 유리효과(Glassmorphism) 및 애니메이션
- **JavaScript (Vanilla)**
  - `showContent()` 함수로 섹션 토글
  - 네비게이션 active 상태 제어

---



### 커밋 메시지 규칙
- `feat:` 기능 추가
- `style:` 디자인 및 레이아웃 수정
- `fix:` 오류 수정
- `docs:` 문서 수정

예시:
- `feat: add gpt version comparison`
- `style: improve gemini mobile layout`
- `fix: nav active state bug`

---

## 실행 방법
### 로컬 실행
- `index.html` 파일을 브라우저로 열기

### Live Server (권장)
1. VS Code에서 프로젝트 열기
2. Live Server 실행
3. 실시간 변경 사항 확인

---

## 배포
- GitHub Pages 사용
- `Settings → Pages → main / root` 설정

---

## 프로젝트 의의
- 생성형 AI 모델을 **기술적·활용적 관점에서 비교**
- 역할 분담을 통한 **협업 개발 경험**
- UI/UX, 정보 구조화, 기술 이해를 동시에 강화한 프로젝트

---

## 제작자
- Team Generative AI Hub
  - 주소민 (GPT)
  - 김은호 (Gemini)
  - 이규찬 (Grok)
