# 메모 통합 발전 (Memo Synthesis)

Obsidian 볼트의 메모들을 AI로 통합하고 발전시키는 플러그인입니다.  
Gemini, Claude, Perplexity 세 가지 AI API를 지원하며 모델도 자유롭게 선택할 수 있습니다.

## 설치 방법 (BRAT)

1. Obsidian에서 **BRAT** 플러그인을 먼저 설치합니다.
2. BRAT 설정 → **Add Beta plugin** 클릭
3. 아래 GitHub 주소 입력:
   ```
   {YOUR_GITHUB_USERNAME}/obsidian-memo-synthesis
   ```
4. **Add Plugin** 클릭 → Obsidian 재시작
5. 설정 → 커뮤니티 플러그인에서 **메모 통합 발전** 활성화

## 설정

플러그인 설정(⚙️)에서 아래 항목을 입력합니다:

| 항목 | 설명 |
|------|------|
| **기본 AI 제공자** | Gemini / Claude / Perplexity 중 선택 |
| **Gemini API 키** | [Google AI Studio](https://aistudio.google.com/) |
| **Claude API 키** | [Anthropic Console](https://console.anthropic.com/) |
| **Perplexity API 키** | [Perplexity API](https://www.perplexity.ai/settings/api) |

## 사용법

### 커맨드 팔레트 (Ctrl+P)
- **메모 통합 발전 실행** — 설정된 AI로 바로 실행
- **메모 통합 발전 (API 선택 후 실행)** — 실행 시 API와 모델을 선택

### 리본 아이콘
왼쪽 사이드바의 🧠 아이콘 클릭

## 기능

### 4가지 트리거 모드
| 모드 | 설명 |
|------|------|
| ✏️ 주제 직접 입력 | 키워드로 볼트 검색 후 메모 선택 |
| 📰 뉴스/텍스트 붙여넣기 | 외부 텍스트 붙여넣기 → 주제 자동 추출 |
| 📄 메모 하나 선택 | 단일 메모를 기반으로 발전 |
| 🗂️ 메모 여러 개 | 여러 메모 선택 → 공통 주제 추출 |

### 5가지 출력 형식
- 📄 LEET 언어이해 지문
- 📋 수사기획 보고서
- ✍️ 기고문/에세이
- 🔗 심화 통합 메모
- 💡 개념 정리 노트

### 자동 연관 메모 탐지
AI 결과물에 등장하는 키워드를 분석해 볼트 내 관련 메모를 자동으로 찾아 링크합니다.

## 지원 모델

### Google Gemini
- Gemini 2.5 Pro
- Gemini 2.5 Flash *(기본값)*
- Gemini 1.5 Pro / Flash

### Anthropic Claude
- Claude Opus 4.7
- Claude Sonnet 4.6 *(기본값)*
- Claude Haiku 4.5
- Claude 3.5 Sonnet

### Perplexity AI
- Sonar Pro
- Sonar *(기본값)*
- Sonar Reasoning Pro / Reasoning

## 라이선스

MIT
