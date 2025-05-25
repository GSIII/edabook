---
title: europython 키워드 트렌드 분석 (2020–2024)
author: 이진
date: 2025-05-25
category: PyCon
layout: post
---

유럽 PyCon(EuroPython)의 2020년부터 2024년까지 발표자료 기반 TF-IDF 키워드를 분석하여, 기술 트렌드와 키워드 흐름을 정리했습니다. 본 보고서는 PyCon Korea의 프로그램 구성 및 글로벌 트렌드 반영에 참고가 될 수 있습니다.

> ##### 참고
>
> 본 분석은 유럽 PyCon 데이터를 기반으로 하며, 한국 개발자 커뮤니티의 특수성을 모두 반영하지는 않습니다. 그러나 글로벌 파이썬 커뮤니티의 흐름을 파악하는 데 유익한 자료가 될 것입니다.
{: .block-tip }

---

## 1. 분석 개요

- **기간:** 2020년 ~ 2024년
- **데이터:** 연도별 발표자료에서 추출된 상위 100개 및 (2024년 기준) 하위 100개 TF-IDF 키워드
- **목적:** 주요 기술 주제 파악 및 파이콘 한국의 프로그램 구성에 인사이트 제공

---

## 2. 꾸준히 등장하는 핵심 키워드

### 공통 키워드
- `python`, `europython`, `talk`, `speaker`, `code`, `https`, `org`, `license`, `video`, `community`, `project`, `development`

### 기술 분야별 키워드
- **데이터/AI:** `machine`, `learning`, `science`, `model`
- **웹 개발:** `django`, `api`, `web`, `flask`
- **소프트웨어 공학:** `testing`, `performance`, `memory`

---

## 3. 연도별 주요 변화

### 🦠 2020
- 키워드: `covid`, `online`, `ep2020`, `docker`, `pandas`
- 팬데믹으로 인해 **온라인 컨퍼런스**가 핵심
- 데이터 배포 및 자동화에 집중

### 💻 2021
- 키워드: `fastapi`, `type`, `functional`, `causal`
- `FastAPI` 등장, **함수형 프로그래밍 및 타입 힌트** 논의 증가
- **인과 추론** 등 고급 데이터 분석 주제 등장

### 🎤 2022
- 키워드: `liffey`, `wicklow`, `cpython`, `jupyter`, `security`
- 오프라인 복귀 및 **CPython 내부 최적화** 논의 활성화

### 🤖 2023
- 키워드: `ai`, `rust`, `graphql`, `vector`, `polars`
- **AI, 고성능 데이터 처리**(Polars, Vector DB) 대두
- `Rust`와의 연계도 눈에 띄는 변화

### 🧠 2024
- 키워드: `llms`, `rag`, `observability`, `opentelemetry`, `generation`
- **LLM (대형언어모델)** 과 **RAG**, 시스템 모니터링에 대한 관심 급증

---

## 4. 2024년 Bottom 키워드 분석

- 주로 **틈새 기술**, **고유명사**, **희귀 주제** 포함
- 예: `hiroshima`, `helmholtz`, `hiding`, `historically`
- 이는 다양한 관심사를 포용하는 컨퍼런스의 특성을 보여줌

---

## 5. PyCon Korea를 위한 제언

1. **AI/LLM 및 RAG 관련 세션 강화**
2. `FastAPI`, `GraphQL` 등 최신 웹 트렌드 반영
3. `Rust`, `CPython`, `typing` 관련 성능 최적화 세션 기획
4. `Polars`, `Apache Spark` 등 데이터 엔지니어링 트렌드 반영
5. 테스트, 문서화 등 기본기 세션 유지
6. 영상 공개 및 온라인 병행 운영 지속 고려
7. 초급~고급까지 다양한 수준 포용 트랙 구성

---

## 6. 결론

지난 5년간의 유럽 PyCon 키워드 트렌드는 AI/ML의 부상과 더불어 웹, 데이터, 시스템 기술이 빠르게 진화하고 있음을 보여줍니다. 파이콘 한국도 이러한 흐름을 반영하면서, 한국 커뮤니티의 특수성과 필요에 맞는 프로그램을 구성한다면 더 풍성하고 의미 있는 컨퍼런스가 될 것입니다.

> ##### TIP
>
> 컨퍼런스 기획 시, 글로벌 흐름과 국내 개발자의 관심사를 균형 있게 반영하세요.
{: .block-tip }
